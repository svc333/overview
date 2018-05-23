---

copyright:

  years: 2017, 2018

lastupdated: "2018-04-02"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:tip: .tip}

# Cloudressourcennamen
{: #crn}

Mit Cloudressourcennamen (CRNs) können {{site.data.keyword.Bluemix_notm}}-Ressourcen eindeutig identifiziert werden. Ein CRN wird verwendet, um eine Ressource in einer Weise anzugeben, die garantiert global eindeutig ist, z. B. in  {{site.data.keyword.Bluemix_notm}} IAM-Richtlinien und -Services, die im Cloud-Katalog aufgelistet sind (IAM = Identity and Access Management).

Ein CRN wird aus einer Kette von "Segmenten" gebildet, die die Ressource, ihre Position und den Service, zu dem sie gehört, hierarchisch angeben. Der Segmentbegrenzer wird auf ':' (d. h. den Doppelpunkt) gesetzt. Alle CRNs beginnen mit der Segmentkennung 'crn'.


## CRN-Format
{: #format}

Das kanonische Basisformat einer CRN lautet wie folgt:

**crn:[version](#version):[cname](#cname):[ctyp](#ctype):[servicename](#service-name):[position](#location):[umfang](#scope):[serviceinstanz](#service-instance):[ressourcentyp:ressource](#resource-type)**


## version
{: #version}

Das Segment `version` gibt die Version des CRN-Formats an. Derzeit ist **v1** der einzige gültige Wert für das Versionssegment.


## cname
{: #cname}

Das Segment `cname` gibt die Cloudinstanz an und ist eine alphanumerische Kennung, die die Cloudinstanz, die die Ressource enthält, eindeutig identifiziert. Ein Segment `cname` identifiziert eine unabhängige Steuerebene (Control Plane), die Eigner der identifizierten Ressource ist. Das Segment `cname` muss für {{site.data.keyword.Bluemix_notm}}-Benutzer `bluemix` lauten.


## ctyp
{: #ctype}

Das Segment `ctyp` gibt den Typ der Cloudinstanz an, die durch den angegebenen `cname` dargestellt wird.

>Gültige Werte:
  - public - Alle Services, die über den öffentlichen Katalog verfügbar sind.
  - dedicated - Nur für aktuelle dedizierte {{site.data.keyword.Bluemix_notm}}-Umgebungen.
  - local - Alle Services, die lokal in Ihrer eigenen Umgebung bereitgestellt sind.


## servicename
{: #service-name}

Das Segment `servicename` gibt eindeutig eine Funktion (Service, Komponente, Produkt) an, die von der Cloud angeboten wird. Bei der Funktion kann es sich um einen vom Benutzer bereitgestellten Service handeln (z. B. die Services, die im {{site.data.keyword.Bluemix_notm}}-Katalog aufgelistet sind) oder um eine interne Architekturkomponente, die für die {{site.data.keyword.Bluemix_notm}}-Funktionalität von entscheidender Bedeutung ist.

Das Segment `servicename` gibt den Service an, zu dem die Ressource gehört, und {{site.data.keyword.Bluemix_notm}} erzwingt die globale Eindeutigkeit von Servicenamen. Das Segment `servicename` muss alphanumerisch und kleingeschrieben sein, es darf keine Leerzeichen oder Sonderzeichen (mit Ausnahme von '-') enthalten.

Bei Services, die im {{site.data.keyword.Bluemix_notm}}-Katalog registriert sind, muss das Segment `servicename` einem der Services entsprechen, die für den {{site.data.keyword.Bluemix_notm}} Global Catalog-Service registriert sind. Es handelt sich um die Eigenschaft `name`, die von der {{site.data.keyword.Bluemix_notm}} Global Catalog-Service-API `GET https://resource-catalog.bluemix.net/api/v1/{` für die entsprechende Ressourceninstanz oder das Segment `servicename` zurückgegeben wurde, das von der Befehlszeilenschnittstelle angezeigt wird: `bx service offerings` in der Spalte `service`.


## position
{: #location}

Die Angabe zur Cloudposition (Ländergruppe/Region/Zone/Rechenzentrum), an der sich die Ressource befindet.

Das Segment `position` muss einer der folgenden Werte sein:

### Global

 * `global`

### Ländergruppen

 * `us`
 * `eu`
 * `cn`
 * `ap`

### Regionen

 * `us-south`
 * `us-east`
 * `au-syd`
 * `eu-gb`
 * `eu-de`

### Rechenzentren


| | | | | |
|---|---|---|---|---|
| AMS01  | AMS03  | CHE01  | DAL01  |  DAL05  |
| DAL06  | DAL07  | DAL09  | DAL10  |  DAL12  |
| DAL13  | FRA02  | HKG02  | HOU02  |  LON02  |
| MEL01  | MEX01  | MIL01  | MON01  |  OSL01  |
| PAR01  | SJC01  | SJC03  | SAO01  |  SEA01  |
| SEO01  | SNG01  | SYD01  | TOK02  |  TOR01  |
| WDC01  | WDC04  | WDC06  | WDC07  |
{: caption="Tabelle 1. Gültige Werte für Rechenzentren" caption-side="top"}

Für einige Ressourcen ist keine Region erforderlich (sie können als `global` betrachtet werden). In diesem Fall wird das Segment `region` auf `global` gesetzt.
{: tip}


## umfang
{: #scope}

Das Segment `umfang` gibt die Abgrenzung oder den Eigner der Ressource an. Für einige Ressourcen ist kein Eigner erforderlich (sie können als `global` betrachtet werden). In diesem Fall ist das Segment `umfang` leer (eine leere Zeichenfolge).

Der Wert des Segments `umfang` muss als `{scopePrefix}`/`{id}` formatiert werden. `scopePrefix` stellt das Format dar, das zur Angabe des Eigners oder der Abgrenzung verwendet wird. `id` stellt die Identität des Eigners oder der Abgrenzung in einem Format dar, das für `scopePrefix` spezifisch ist.

| Umfangstyp | Umfangspräfix | Verwendung | Beispiel |
| --- | --- | --- | --- |
| Konto | a/`{account id}` | Das Konto, in dem die Ressource erstellt wurde. | a/292558 |
| Organisation | o/`{org guid}` | Die {{site.data.keyword.Bluemix_notm}}-Organisation, der die Ressource zugeordnet wurde. | o/4716e2d1-35b7-431f-891a-b552bf0b3c66 |
| Bereich | s/`{space guid}` | Der {{site.data.keyword.Bluemix_notm}}-Bereich, dem die Ressource zugeordnet wurde. | s/48b3cdcd-e804-4398-9032-73065863ad7c |
{: caption="Tabelle 2. Verwendung von 'umfang'" caption-side="top"}

`account id` muss die ID des IBM Kontos sein (verknüpfte {{site.data.keyword.Bluemix_notm}}- und Softlayer-Konten)


## serviceinstanz
{: #service-instance}

Das Segment `serviceinstanz` gibt die Serviceinstanz eindeutig an. Das Format des Segments `serviceinstanz` ist vom Service abhängig. Jeder Service muss das Format seines Segments `serviceinstanz` als Teil der Servicemetadaten dokumentieren. Manche Services haben keine Instanzen, weil die Instanz global ist. In diesem Fall ist das Feld `serviceinstanz` leer.

Das Segment `serviceinstanz` muss alphanumerisch und kleingeschrieben sein, es darf keine Leerzeichen oder Sonderzeichen (mit Ausnahme von '-' und '/') enthalten.

Beispiel: Ein Tool 'devops' könnte zum Verfolgen und Planen von Arbeitselementen eine einfache `GUID`-Instanz-ID ("1234-5678-9012-3456") haben, in der die Richtlinienkomponente eines Service für die automatische Gruppenskalierung eine hierarchische Namenskonvention verwenden kann und folgendes Segment `service-id` hat:

>`c7a27f55-d35e-4153-b044-8ca9155fc467/my-test-asg1/my-scaleout-policy`

Sie können CRNs auch mit dem folgenden CLI-Befehl von einer {{site.data.keyword.Bluemix_notm}}-Ressource abrufen:
```
bluemix resource service-instance
```
{: codeblock}


## ressourcentyp, ressource
{: #resource-type}

Der Wert der Segmente `ressourcentyp` und `ressource` hängt vom Service ab. Es ist ein Service erforderlich, um die unterstützten Segmente `ressourcentyp` und das Format des Segments `ressource` als Teil der Servicemetadaten zu dokumentieren.

Beispiel: Ein Image im Container für Kundenbelege in einem Objektspeicherservice kann über einen `ressourcentyp` von `object` und einen `ressourcenwert` von `CustomerReceipts/clientdinner.png` verfügen.

Das Segment `ressourcentyp` muss alphanumerisch und kleingeschrieben sein, es darf keine Leerzeichen oder Sonderzeichen (mit Ausnahme von '-') enthalten. Ein Service kann entscheiden, dass `ressourcentyp` optional ist. In diesem Fall wird der Wert leer gelassen.


## CRN-Beispiele
{: #crn_examples}

Im Folgenden finden Sie eine Liste mit CRN-Beispielen.

| Beispiel | Wert |
| --- | --- |
| Container | `crn:v1:bluemix:public:containers-kubernetes:us-south:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:8042b2a8af6a4a5cbf6dbe09e07311d2:worker:kube-hou02-pa8042b2a8af6a4a5cbf6dbe09e07311d2-w1:`|
| Ressourcengruppe | `crn:v1:bluemix:public:resource-controller: global:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:resource-group:59bcbfa6ea2f006b4ed7094c1a08dcdd` |
| Serviceinstanz | `crn:v1:bluemix:public:cloud-object-storage:global:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:1a0ec336-f391-4091-a6fb-5e084a4c56f4::` |
| Bucket | `crn:v1:bluemix:public:cloud-object-storage:global:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:1a0ec336-f391-4091-a6fb-5e084a4c56f4:bucket:mybucket` |
{: caption="Tabelle 3. CRN-Beispiele" caption-side="top"}

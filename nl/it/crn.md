---

copyright:

  years: 2017, 2019

lastupdated: "2019-05-06"

keywords: crn, cloud resource name

subcollection: overview

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:tip: .tip}

# Nomi delle risorse cloud
{: #crn}

I nomi delle risorse cloud (o CRN, Cloud Resource Name) identificano in modo univoco le risorse {{site.data.keyword.Bluemix_notm}}. Un CRN viene utilizzato per specificare una risorsa in un modo che sia inequivocabile e globalmente univoco, come nelle politiche e nei servizi {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) elencati nel catalogo cloud.

Un CRN è formato da una concatenazione di "segmenti" che identificano gerarchicamente la risorsa, la sua posizione e il servizio a cui appartiene. Il delimitatore di segmento è impostato su ':' (il carattere dei due punti). Tutti i CRN iniziano con l'identificativo di segmento `crn`.


## Formato del CRN
{: #format-crn}

Il formato tradizionale di base di un CRN è:

`crn:version:cname:ctype:service-name:location:scope:service-instance:resource-type:resource`


## version
{: #version-crn}

Il segmento `version` identifica la versione del formato CRN. Attualmente, l'unico valore valido per il segmento della versione è `v1`.


## cname
{: #cname-crn}

Il segmento `cname` identifica l'istanza cloud ed è un identificativo alfanumerico che identifica in modo univoco l'istanza cloud che contiene la risorsa. Un `cname` identifica efficacemente un piano di controllo indipendente che possiede la risorsa identificata. Il valore per il segmento `cname` deve essere `bluemix` per gli utenti {{site.data.keyword.Bluemix_notm}}.


## ctype
{: #ctype-crn}

Il segmento `ctype` identifica il tipo di istanza cloud rappresentato dal segmento `cname` specificato.

 Valori validi:
  - `public`: tutti i servizi disponibili dal catalogo pubblico
  - `dedicated`: solo per gli ambienti dedicati {{site.data.keyword.Bluemix_notm}} correnti
  - `local`: tutti i servizi distribuiti localmente nel tuo ambiente


## service-name
{: #service-name-crn}

Il segmento `service-name` identifica in modo univoco una capacità (servizio, componente, prodotto) offerta dal cloud. La capacità può essere un servizio fornito dall'utente, come i servizi elencati nel catalogo {{site.data.keyword.Bluemix_notm}}, o un componente dell'architettura interna fondamentale per la funzionalità di {{site.data.keyword.Bluemix_notm}}.

Il segmento `service-name` indica il servizio a cui appartiene la risorsa e {{site.data.keyword.Bluemix_notm}} applica l'unicità globale dei nomi dei servizi. Il segmento `service-name` deve essere alfanumerico, in minuscolo e senza spazi o caratteri speciali diversi da '-'.

Per i servizi registrati nel catalogo {{site.data.keyword.Bluemix_notm}}, il segmento `service-name` deve corrispondere a uno dei servizi registrati nel servizio del Catalogo globale di {{site.data.keyword.Bluemix_notm}}. È la proprietà `name` restituita dall'API del servizio Catalogo globale di {{site.data.keyword.Bluemix_notm}} `GET https://globalcatalog.cloud.ibm.com/api/v1/{id}` per l'istanza della risorsa corrispondente o il valore `service-name` visualizzato dall'interfaccia della riga di comando: `ibmcloud service offerings` nella colonna `service`.


## location
{: #location-crn}

Area geografica/regione/zona/data center cloud in cui risiede la risorsa.

Il segmento `location` deve essere uno dei seguenti valori:

### Globale
{: #global-crn}

 * `global`

### Aree geografiche
{: #geos-crn}

 * `us`
 * `eu`
 * `cn`
 * `ap`

### Regioni
{: #regions-crn}

 * `us-south`
 * `us-east`
 * `au-syd`
 * `eu-gb`
 * `eu-de`
 * ` jp-tok `

### Data center
{: #dc-crn}

 * ` AMS01  `
 * `AMS03`
 * ` CHE01  `
 * ` DAL01  `
 * `  DAL05  `
 * ` DAL06  `
 * `DAL07`
 * `DAL09`
 * `DAL10`
 * `DAL12`
 * `DAL13`
 * ` FRA02  `
 * ` HKG02  `
 * `HOU02`
 * `LON02`
 * ` MEL01  `
 * ` MEX01  `
 * ` MIL01  `
 * `MON01`
 * `  OSL01  `
 * ` PAR01  `
 * `SJC01`
 * `SJC03`
 * ` SAO01  `
 * `SEA01`
 * ` SEO01  `
 * `SNG01`
 * `SYD01`
 * `TOK02`
 * `TOR01`
 * `WDC01`
 * `WDC04`
 * `WDC06`
 * `WDC07`

Alcune risorse non richiedono una regione poiché possono essere considerate globali. In questo caso, il segmento `region` è impostato su `global`.
{: tip}


## ambito
{: #scope-crn}

Il segmento `scope` identifica il contenimento o il proprietario della risorsa. Alcune risorse non richiedono un proprietario (possono essere considerate `global`). In questo caso, il segmento `scope` è vuoto (una stringa vuota).

Il valore del segmento `scope` deve essere formattato come `{scopePrefix}`/`{id}`. `scopePrefix` rappresenta il formato utilizzato per identificare il proprietario o il contenimento. `id` rappresenta l'identità del proprietario o del contenimento in un formato specifico per `scopePrefix`.

| Tipo di ambito | Prefisso ambito | Utilizzo | Esempio |
| --- | --- | --- | --- |
| Account | a/`{account id}` | L'account in cui è stata creata la risorsa. | `a/292558` |
| Organizzazione | o/`{org guid}` | L'organizzazione {{site.data.keyword.Bluemix_notm}} a cui è stata assegnata la risorsa. | `o/4716e2d1-35b7-431f-891a-b552bf0b3c66` |
| Spazio | s/`{space guid}` | Lo spazio {{site.data.keyword.Bluemix_notm}} a cui è stata assegnata la risorsa. | `s/48b3cdcd-e804-4398-9032-73065863ad7c` |
{: caption="Tabella 1. Utilizzo di `scope`" caption-side="top"}



## service-instance
{: #service-instance-crn}

Il segmento `service-instance` identifica l'istanza del servizio in modo univoco. Il formato del segmento `service-instance` varia in base al servizio. Ogni servizio deve documentare il formato del proprio segmento `service_instance` come parte dei relativi metadati di servizio. Alcuni servizi non hanno istanze perché l'istanza è globale e, in questo caso, il campo `service-instance` è vuoto.

Il valore `service-instance` deve essere alfanumerico, in minuscolo, senza spazi o caratteri speciali diversi da '-' e '/'.

Ad esempio, uno strumento DevOps per tracciare e pianificare gli elementi di lavoro può avere un semplice ID istanza `GUID` ("1234-5678-9012-3456") dove il componente della politica di un servizio del gruppo di ridimensionamento automatico può utilizzare una convenzione di denominazione gerarchica e avere un segmento `service-id` come:

>`c7a27f55-d35e-4153-b044-8ca9155fc467/my-test-asg1/my-scaleout-policy`

Puoi anche ottenere un CRN da una risorsa {{site.data.keyword.Bluemix_notm}} utilizzando il seguente comando CLI:
```
ibmcloud resource service-instance
```
{: codeblock}

## resource-type, resource
{: #resource-type-crn}

Il valore dei segmenti `resource-type` e `resource` varia in base al servizio. È richiesto un servizio per documentare il segmento `resource types` supportato e il formato del segmento `resource` come parte dei relativi metadati di servizio.

Ad esempio, un'immagine nel contenitore delle ricevute dei clienti in un servizio Object Storage può avere un segmento `resource-type` di `object` e un valore `resource` di `CustomerReceipts/clientdinner.png`.

Il segmento `resource-type` deve essere alfanumerico, in minuscolo e senza spazi o caratteri speciali diversi da '-'. Un servizio può decidere che il segmento `resource-type` sia facoltativo, nel qual caso viene lasciato vuoto.


## Esempi di CRN
{: #crn_examples}

La seguente tabella fornisce un elenco di esempi di CRN.

| Esempio | Valore |
| --- | --- |
| Nodo di lavoro Kubernetes | `crn:v1:bluemix:public:containers-kubernetes:us-south:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:8042b2a8af6a4a5cbf6dbe09e07311d2:worker:kube-hou02-pa8042b2a8af6a4a5cbf6dbe09e07311d2-w1` |
| Gruppo di risorse | `crn:v1:bluemix:public:resource-controller: global:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:resource-group:59bcbfa6ea2f006b4ed7094c1a08dcdd` |
| Istanza del servizio | `crn:v1:bluemix:public:cloud-object-storage:global:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:1a0ec336-f391-4091-a6fb-5e084a4c56f4::` |
| Bucket | `crn:v1:bluemix:public:cloud-object-storage:global:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:1a0ec336-f391-4091-a6fb-5e084a4c56f4:bucket:mybucket` |
{: caption="Tabella 2. Esempi di CRN" caption-side="top"}

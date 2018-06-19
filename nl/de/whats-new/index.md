---

copyright:

  years: 2015, 2018

lastupdated: "2018-06-01"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# Neuerungen in {{site.data.keyword.Bluemix_notm}}
{: #whatsnew}

Wenn Sie stets auf dem aktuellen Stand über die neuen Features und Services bleiben, die in {{site.data.keyword.Bluemix}} verfügbar sind, können Sie am meisten von {{site.data.keyword.Bluemix_notm}} profitieren. Die Aktualisierungen sind in die folgenden Kategorien unterteilt: [{{site.data.keyword.Bluemix_notm}}-Plattform](index.html#platform_category), [{{site.data.keyword.Bluemix_local_notm}} und {{site.data.keyword.Bluemix_dedicated_notm}}](index.html#dedicatedandlocal), [Infrastruktur und Ressourcen](index.html#compute_category) sowie [Services](index.html#services_category).
{:shortdesc}

## {{site.data.keyword.Bluemix_notm}}-Plattform
{: #platform_category}

### Service-IDs und API-Schlüssel schützen
Datum der Neuerung: 01 Juni 2018

Damit eine Situation vermieden werden kann, in der die Service-ID oder der API-Schlüssel gelöscht und so ein Ausfall oder eine Unterbrechung verursacht wird, können Sie Service-IDs und API-Schlüssel über die Benutzerschnittstelle oder die Befehlszeilenschnittstelle sperren. Das Sperren einer Service-ID verhindert darüber hinaus, dass Zugriffsrichtlinien geändert, gelöscht oder zugewiesen werden und dass API-Schlüssel, die der Service-ID zugewiesen sind, erstellt oder gelöscht werden. Weitere Informationen finden Sie in [Service-ID sperren](/docs/iam/serviceid.html#locking-a-service-id) und [API-Schlüssel sperren](/docs/iam/userid_keys.html#locking-an-api-key).

### Upgrade für das Lite-Konto auf ein Abonnementkonto durchführen
Datum der Neuerung: 31. Mai 2018

Sie können nun direkt über die {{site.data.keyword.Bluemix_notm}}-Konsole ein Upgrade für Ihr Lite-Konto auf ein Abonnementkonto durchführen. Mit einem Abonnementkonto können Sie sowohl Plattform- als auch Infrastrukturangebote verwenden und Preisnachlässe nutzen, indem Sie eine monatliche Ausgabe- und Laufzeitverpflichtung vereinbaren. Darüber hinaus lassen sich durch festgelegte Abrechnungen im Rahmen eines monatlichen Zahlungsplans Überraschungen vermeiden, während Ihnen gleichzeitig die Flexibilität zur Verfügung steht, das Bestellvolumen nach Bedarf zu erhöhen oder zu reduzieren. Weitere Informationen finden Sie in [Häufig gestellte Fragen zu Abonnementkonten](/docs/billing-usage/billing-faq.html#subscription-faqs). 

### Neuer Markenname in der {{site.data.keyword.Bluemix_notm}}-Befehlszeilenschnittstelle
Datum der Neuerung: 15. Mai 2018

Die Befehle der {{site.data.keyword.Bluemix_notm}}-Befehlszeilenschnittstelle (CLI) wurden von `bluemix` und `bx` in **ibmcloud** geändert. Sie können die CLI-Befehle `bluemix` und `bx` jedoch weiterhin verwenden, bis sie zu einem späteren Zeitpunkt entfernt werden. Eine Abkürzung des neuen Befehls ist nicht verfügbar, der vollständige Name **ibmcloud** muss verwendet werden. 

### Mehrfaktorauthentifizierung für Ihr {{site.data.keyword.Bluemix_notm}}-Konto
Datum der Neuerung: 02. Mai 2018

Die Mehrfaktorauthentifizierung (MFA) fügt eine zusätzliche Sicherheitsebene zu Ihrem Konto hinzu, indem alle Benutzer neben ihrer Standard-IBMid und Ihrem Kennwort während der Anmeldung einen zeitbasierten einmaligen Kenncode eingeben müssen. Dies wird gängigerweise auch als Zwei-Faktor-Authentifizierung (2FA) bezeichnet. Mehrfaktorauthentifizierung wird pro Konto aktiviert und alle Benutzer in dem Konto müssen sich unter Verwendung einer zusätzlichen Sicherheitsmaßnahme anmelden.

Weitere Informationen finden Sie im Blog-Artikel [IBM Cloud Platform nun mit Unterstützung für die Mehrfaktorauthentifizierung](https://www.ibm.com/blogs/bluemix/2018/05/ibm-cloud-platform-now-adds-support-multi-factor-authentication/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link").

### Mit Zugriffsgruppen schnellen Zugriff zuweisen
Datum der Neuerung: 03. April 2018

Wollen Sie in der Lage sein, schnell den Zugriff zuzuweisen, indem Sie die kleinstmögliche Anzahl an Richtlinien verwenden? Das können Sie nun mithilfe von Zugriffsgruppen. Mit Zugriffsgruppen können Sie eine Gruppe von Benutzern und Service-IDs gruppieren und eine einzige Richtlinie zuweisen, die für alle Mitglieder der Gruppe gilt. Durch die Verwendung von Zugriffsgruppen können Sie die Zeit begrenzen, die Sie für die Verwaltung des Zugriffs auf die Benutzer und Service-IDs in Ihrem Konto verwenden. Weitere Details finden Sie im Blog [Neue Funktion: Zugriffsgruppen](https://www.ibm.com/blogs/bluemix/2018/04/access-groups/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link").

### SoftLayer- und {{site.data.keyword.Bluemix_notm}}-Konto verknüpfen
Datum der Neuerung: 1. März 2018

Sie können Ihr SoftLayer-Konto mit Ihrem {{site.data.keyword.Bluemix_notm}}-Konto verknüpfen, um sich zentral anzumelden, bei der {{site.data.keyword.Bluemix_notm}}-Konsole, und sowohl auf die Infrastructure as a Service- (IaaS) als auch auf die Platform as a Service-Ressourcen (PaaS) zuzugreifen. Wenn Sie neu bei {{site.data.keyword.Bluemix_notm}} sind, erstellen und verknüpfen Sie ein Konto, um ein kostenfreies {{site.data.keyword.Bluemix_notm}}-Lite-Konto zu erhalten. Oder, wenn Sie bereits über ein {{site.data.keyword.Bluemix_notm}}-Konto mit PaaS-Ressourcen verfügen, verknüpfen Sie Ihre Konten, um eine gemeinsame Rechnung für Ihre IaaS- und PaaS-Ressourcen zu erhalten. Weitere Informationen zum schnellen Verknüpfen Ihrer Konten finden Sie in den [Schritten zum Verknüpfen Ihrer IaaS- und PaaS-Konten](https://www.ibm.com/blogs/bluemix/2018/03/follow-steps-link-iaas-paas-accounts/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link").


### {{site.data.keyword.Bluemix_notm}} Foundry-Service jetzt für Region 'Vereinigte Staaten (Osten)' verfügbar
Datum der Neuerung: 15. Dezember 2017

In Washington, DCm ist jetzt ein neues Rechenzentrum für die Region 'Vereinigte Staaten (Osten)' verfügbar. Diese neue Region ist über den Endpunkt `us-east.bluemix.net` erreichbar. Details über die gebührenpflichtigen Services, die in dieser neuen Region angeboten werden, finden Sie unter [Services nach Region](/docs/services/services_region.html#services_region).

### Unterstützung für Ressourcen in der Europäischen Union
Datum der Neuerung: 14. Dezember 2017

Falls sich Ihre Services und Rechenzentren in Europa befinden, bietet {{site.data.keyword.Bluemix_notm}} jetzt ein zusätzliches Leistungsspektrum für den Schutz Ihrer Daten in der Europäischen Union. Sie können anfordern, dass der Support für Sie von Kundenunterstützungsteams bereitgestellt wird, die in Europa ansässig sind. Dieser Support ist täglich rund um die Uhr verfügbar. Weitere Informationen finden Sie in den Abschnitten [Option 'Unterstützung in der EU' aktivieren](/docs/billing-usage/eusupported.html#bill_eusupported) und [Unterstützung für Ressourcen in der EU anfordern](/docs/get-support/howtogetsupport.html#eusupported).

### Unterstützung für TLS 1.0 und 1.1 wird eingestellt
Datum der Neuerung: 28. Dezember 2017

{{site.data.keyword.Bluemix_notm}} stellt die Unterstützung für TLS 1.0 und TLS 1.1 bei vielen Cloud-Produkten und -Services am 1. März 2018 ein. Weitere Informationen zu den Auswirkungen dieser Änderung und zu den Maßnahmen, die Sie möglicherweise ergreifen müssen, finden Sie unter [Unterstützung für TLS 1.0 und 1.1 wird eingestellt](/docs/troubleshoot/appsectls.html).

### Neue Organisationsmöglichkeit für Ressourcen in Ihrem Konto
Datum der Neuerung: 16. November 2017

Ressourcengruppen sind eine neue Möglichkeit für Sie, anpassbare Gruppierungen von Kontoressourcen zu erstellen; der Zugriff auf die Gruppe und die darin enthaltenen Ressourcen wird mithilfe von Identity and Access Management (IAM) verwaltet. Für jeden Benutzer ist anfangs eine Standardressourcengruppe vorhanden. Diese Ressourcengruppe können Sie umbenennen und neue Serviceinstanzen zu ihr hinzufügen, wenn Sie diese aus dem Katalog erstellen.

Benutzer mit einem nutzungsabhängigen Konto oder einem Abonnementkonto können weitere Ressourcengruppen erstellen, um die Verwaltung von Kontingenten und die Anzeige von Abrechnung und Nutzung für ein Ressourcenset zu vereinfachen. Durch die Gruppierung von Ressourcen wird außerdem die gleichzeitige Zuweisung von Zugriffsberechtigungen für mehrere Services an die Benutzer erleichtert. Weitere Informationen zum Arbeiten mit Ressourcengruppen für Ihr Konto finden Sie unter [Ressourcengruppen verwalten](/docs/account/resourcegroups.html#rgs).

### Aktualisierungen für {{site.data.keyword.Bluemix_notm}} IAM
Datum der Neuerung: 16. November 2017

Die Einführung von [Ressourcengruppen](/docs/overview/resource-groups.html#whatis) in Ihrem {{site.data.keyword.Bluemix_notm}}-Konto bietet Ihnen ein neues Verfahren für die Zuordnung von Zugriffsberechtigungen. Benutzern und Service-IDs kann der Zugriff auf alle Services innerhalb einer Ressourcengruppe erteilt werden, wodurch Sie gleichzeitig schnell auf mehrere Ressourcen zugreifen können. Außerdem können Sie den Zugriff für jeden Benutzer oder jede Service-ID anpassen, indem Sie den Zugriff nur für einige Services in einer Ressourcengruppe ermöglichen oder indem Sie den Zugriff auf einzelne Ressourcen bis auf die Ebene der Serviceinstanz hinab festlegen.

Weitere Informationen zu den Features, die Sie bei IAM nutzen können, enthält der Abschnitt [Welche Funktionen bietet IAM?](/docs/iam/index.html#features)

### Dashboardansicht anpassen
Datum der Neuerung: 16. November 2017

Sie können alle Ressourcen in Ihrem Konto im Dashboard der {{site.data.keyword.Bluemix_notm}}-Konsole anzeigen und verwalten. Außerdem können Sie künftig Filter festlegen, um die Ansicht anzupassen. Beispielsweise können Sie eine Filterung nach Ressourcengruppe vornehmen, um die speziellen Ressourcen in einer Ressourcengruppe anzuzeigen. Auch eine Filterung nach Region oder Cloud Foundry-Bereich ist möglich. Weitere Details finden Sie unter [Ressourcen im Dashboard verwalten](/docs/overview/ui.html#dashboardview).


### Support Center
Datum der Neuerung: 2. November 2017

Im neuen Support Center können Sie nach Informationen suchen, Fragen an die Entwickler-Community stellen und Tickets verwalten. Navigieren Sie in der Menüleiste der {{site.data.keyword.Bluemix_notm}}-Konsole zu **Support > Support Center**.

### Einführung von IBM Cloud
Datum der Neuerung: 31. Oktober 2017

Bluemix heißt jetzt IBM Cloud. Außer dem Namen ändert sich nichts. Sie können Ihre Apps und Services weiterhin wie gewohnt ohne großen Aufwand erstellen und ausführen. Weitere Details finden Sie im [IBM Cloud-Blog](https://www.ibm.com/blogs/bluemix/2017/10/bluemix-is-now-ibm-cloud/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link").

### Lite-Konto
Datum der Neuerung: 31. Oktober 2017

Mit dem neuen Typ des Lite-Kontos können Sie ausgewählte Services kostenlos und ohne Zeitbegrenzung ausprobieren. Dieses neue Konto umfasst darüber hinaus Nutzungsüberwachungs- und Effizienzfunktionen, die eine bessere Verwaltung Ihrer Ressourcen fördern. Mehr über die verfügbaren Funktionen finden Sie unter [Kontotypen](/docs/account/index.html#liteaccount).

### Funktion 'Identity and Access Management' für Anwendungsauthentifizierung
Datum der Neuerung: 6. Oktober 2017

Identity and Access Management (IAM) bietet jetzt die Möglichkeit der Erstellung einer Service-ID, die eine Art Identität darstellt, mit der sich Apps bei Ihren {{site.data.keyword.Bluemix_notm}}-Services authentifizieren können. Anstelle der Verwendung von einzelnen Benutzerberechtigungsnachweisen kann eine Service-ID mit einem zugeordneten API-Schlüssel und Zugriffsberechtigungen in Form einer Servicerichtlinie erstellt werden, die der Service-ID zugeordnet wird, damit Sie die Zugriffsebene für jede Anwendung steuern können, die sich mit dieser ID authentifiziert.

Weitere Informationen zu den Vorzügen dieser Funktion und zu ihrer Verwendung enthält der Blogbeitrag [Introducing IBM Cloud IAM Service IDs and API Keys](https://www.ibm.com/blogs/bluemix/2017/10/introducing-ibm-cloud-iam-service-ids-api-keys/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link").

### Globaler {{site.data.keyword.Bluemix_notm}}-Katalog
Datum der Neuerung: 27. Juli 2017

Als Erweiterung der letzten Konsolenaktualisierung für die Verwaltung Ihrer öffentlichen Regionen an einer zentralen Stelle in der Konsole gibt es in {{site.data.keyword.Bluemix_notm}} jetzt einen globalen Katalog, der die Auswahl und Bereitstellung von Elementen im Katalog optimiert. Ungeachtet der Region, die Sie in der Konsole ausgewählt haben, werden jetzt alle Services angezeigt, die in allen öffentlichen Regionen aus Ihrem Katalog verfügbar sind. Sobald Sie eine Kachel im Katalog auswählen, können Sie feststellen, in welchen Regionen der Service verfügbar ist, und auswählen, wo Sie den Service bereitstellen wollen.

Weitere Informationen zu den neuesten Aktualisierungen des Katalogs enthält der Blogbeitrag [A global {{site.data.keyword.Bluemix_notm}} catalog makes building things easier](https://www.ibm.com/blogs/bluemix/2017/07/global-bluemix-catalog-makes-building-things-easier/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link").

### Aktualisierungen der {{site.data.keyword.Bluemix_notm}}-Konsole
Datum der Neuerung: 23. Mai 2017

Sie können Ihre öffentlichen Regionen ab sofort an einer zentralen Stelle in der aktualisierten {{site.data.keyword.Bluemix_notm}}-Konsole verwalten. Der Regionsselektor ermöglicht Ihnen einen optimierten Zugriff auf Ihre Ressourcen; zu den weiteren Verbesserungen gehören eine höhere Verfügbarkeit und eine gesteigerte Leistung.

Weitere Informationen zu dieser Aktualisierung enthält der Blogbeitrag [New Global Bluemix UI for Higher Availability and More](https://www.ibm.com/blogs/bluemix/2017/05/new-global-bluemix-ui-higher-availability/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link").

### Identity and Access Management
Datum der Neuerung: 1. Mai 2017

Durch die neuesten Aktualisierungen und Verbesserungen können Eigner oder Administratoren von {{site.data.keyword.Bluemix_notm}}-Konten jetzt eine einheitliche Benutzerschnittstelle für die Zugriffssteuerung verwenden und hierdurch die folgende Funktionalität nutzen:
 * Differenzierten Benutzerzugriff auf Kubernetes-Services und andere Services verwalten, sobald diese die neuen Zugriffssteuerungsfunktionen annehmen
 * Servicerichtlinien und Cloud Foundry-Rollen zu Benutzern in ihren Organisationen zuordnen

Des Weiteren können Benutzer der {{site.data.keyword.Bluemix_notm}}-Plattform API-Schlüssel, die ihren Benutzer-IDs zugeordnet sind, erstellen, löschen und auflisten, sowie diese API-Schlüssel bei Verwendung von APIs oder CLIs zur Authentifizierung verwenden.

Zu guter Letzt wurde die einheitliche Benutzermanagementfunktion erweitert, damit bei einem verknüpften IaaS-PaaS-Konto die einheitliche Verwaltung von Benutzern möglich ist, ohne dass Benutzer separat im SoftLayer-Kundenportal oder der {{site.data.keyword.Bluemix_notm}}-Konsole hinzugefügt werden müssen.

Zusätzliche Angaben über die neueste Aktualisierung können Sie dem Blogbeitrag [Introducing Identity & Access Management](https://www.ibm.com/blogs/bluemix/2017/05/introducing-identity-access-management/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link") entnehmen.

### Geändertes Navigationsdesign für {{site.data.keyword.Bluemix_notm}}-Dokumente
Datum der Neuerung: 13. April 2017

Diese aktualisierte Navigation verfolgt den Zweck, die Organisation des Inhalts in den Dokumenten besser verständlich zu machen und eine effizientere Suche nach relevantem Inhalt zu ermöglichen. Dank einer geringeren Verschachtelung der Inhaltsebenen müssen Sie nicht so tief nach den Informationen graben, die Sie für die erfolgreiche Nutzung von {{site.data.keyword.Bluemix_notm}} benötigen.


## {{site.data.keyword.Bluemix_local_notm}} und {{site.data.keyword.Bluemix_dedicated_notm}}
{: #dedicatedandlocal}

### Aktualisierungen für die Administrationskonsole im Februar
{: #febadminconsole}
Datum der Neuerung: 28. Februar 2018

Durch die neueste Aktualisierung im Februar können Sie das folgende neue Feature nutzen:

#### Neue Berechtigung für das Verwalten von Wartungsaktualisierungen

Es wurde eine neue Benutzerberechtigung eingeführt, um Benutzern spezifisch zu ermöglichen, Wartungsaktualisierungen zu genehmigen und neu zu planen sowie Fenster für Wartungsaktualisierung einzurichten. die festlegen, wann Wartungsaktualisierungen in einer dedizierten Umgebung bereitgestellt werden können.
Weitere Informationen können Sie dem [Video](https://youtu.be/7c7jyp_JJWU){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link") entnehmen.

### Aktualisierungen für die Administrationskonsole im Dezember
{: #decemberadminconsole}
Datum der Neuerung: 14. Dezember 2017

Durch die neuesten Aktualisierungen und Verbesserungen im Dezember können Sie die folgenden neuen Features nutzen:

#### Benachrichtigungen über Schwellenwert für durchschnittliche CPU-Auslastung abonnieren

Der CPU-Durchschnitt wurde als Schwellenwerttyp bei den Benachrichtigungsabonnements hinzugefügt. Sie können nun Benachrichtigungen empfangen, wenn die CPU-Auslastung (und zwar der Durchschnittswert für insgesamt alle DEA und Diego-Zellen) einen bestimmten Schwellenwert über- oder unterschreitet.

#### Steuerungszugriff für Cloudsysteme in der Europäischen Union

Kombiniert mit der neuen Funktion, die in der Europäischen Union für die Unterstützung von Cloudressourcen verfügbar ist (beginnend in Frankfurt), bietet die Administrationskonsole jetzt die Möglichkeit, Richtlinien zu definieren, die den Zugriff durch IBM Mitarbeiter steuern. Sie können Zugriffssteuerungsrichtlinien verwalten, Zugriffsanforderungen anzeigen, Aktionen für die Anforderungen ausführen und den Verlauf überwachen.

#### Erweiterte Informationen in Sicherheitsberichten

Sicherheitsberichte enthalten neben den eindeutigen IDs für Benutzer und Organisationen jetzt benutzerfreundliche Namen.

### Aktualisierungen für die Administrationskonsole im August
{: #augustadminconsole}
Datum der Neuerung: 31. August 2017

Durch die neuesten Aktualisierungen und Verbesserungen im August können Sie die folgenden neuen Features nutzen:

#### Aktualisierung der Nutzungsmetriken für {{site.data.keyword.cloudant_short_notm}}-Services

  * Die Berechnung der Nutzungsmetriken für {{site.data.keyword.cloudant_short_notm}} wurde aktualisiert, damit die Gesamtsumme der in allen Knoten in einem {{site.data.keyword.cloudant_short_notm}}-Cluster genutzten und verfügbaren GB wiedergegeben wird. Ein {{site.data.keyword.cloudant_short_notm}}-Cluster enthält normalerweise 3 Knoten und ein Dokument in der Datenbank wird zur Hochverfügbarkeit und Notfallwiederherstellung auf allen Knoten im Cluster repliziert. Durch die im August vorgenommenen Aktualisierungen gibt die Kapazitätsmetrik in der {{site.data.keyword.cloudant_short_notm}}-Skala (verfügbar in der Ansicht _Ressourcennutzung > Services_) den Speicherplatz für alle Knoten im Cluster an. Falls ein einzelner {{site.data.keyword.cloudant_short_notm}}-Cluster beispielsweise 3 Knoten mit einer Kapazität von jeweils 1000 GB enthält, beträgt das Kapazitätslimit 3000 GB. Wurden 1500 GB dieser Kapazität benutzt, hat die {{site.data.keyword.cloudant_short_notm}}-Nutzungsmetrik den Wert 50%.

#### Aktualisierungen bei der Planung von Wartungsaktualisierungen

  * In {{site.data.keyword.Bluemix_dedicated_notm}} können Kunden das Datum und die Uhrzeit der Zeiträume verwalten, in denen ihre dedizierten Umgebungen für die Bereitstellung von Systemaktualisierungen zur Verfügung stehen. Kunden können mit Datumsangaben und Uhrzeiten Verfügbarkeitsfenster definieren, in denen Wartungsaktualisierungen in ihrer dedizierten Umgebung bereitgestellt bzw. nicht bereitgestellt werden können. Bei der Aktualisierung im August wurde die Option _Verfügbare Aktualisierungsfenster_ in _Aktualisierungsfenster_ und _Nicht verfügbare Aktualisierungsfenster_ in _Ausfallfenster_ umbenannt. Neben der Terminologieänderung bietet sich für die Kunden jetzt eine größere Flexibilität und Spanne beim Definieren von Ausfallzeiten, also nicht verfügbaren Zeitpunkten. Nach der Anforderung müssen die Ausfallzeiten durch IBM genehmigt werden; die Dauer bis zur Genehmigung kann hierbei variieren. Wenn die angeforderten Ausfallzeiten genehmigt sind, storniert IBM vorhandene Aktualisierungen, die momentan über das Nichtverfügbarkeitsfenster geplant sind. Darüber hinaus erstellt IBM neue Datensätze für diese Aktualisierungen und plant sie außerhalb der genehmigten Ausfallzeiten ein.

Weitere Informationen können Sie dem [Video](https://bit.ly/2eCQNvu){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link") entnehmen.

### Aktualisierungen für die Administrationskonsole im Juli
{: #julyadminconsole}
Datum der Neuerung: 31. Juli 2017

Durch die neuesten Aktualisierungen und Verbesserungen im Juli können Sie die folgenden neuen Features nutzen:

#### Aktualisierungen der Funktionen für den Verlauf der Ressourcennutzung

  * Bei der letzten Aktualisierung im Juni wurde in der Ansicht 'Protokoll' für die Hauptspeicher- und Plattenspeichernutzung die Anzeige der Nutzungsdaten für die letzten 48 Stunden, 30 Tage und 5 Monate eingeführt. Bei der neuesten Aktualisierung im Juli wurde die Funktionalität für den Verlauf der Ressourcennutzung erweitert und ermöglicht jetzt eine Anpassung des Zeitraums, für den Ressourcennutzungsdaten angezeigt werden sollen. Die Ansichten für die stündliche, tägliche und monatliche Nutzung sind weiterhin verfügbar, aber Benutzer können nun auch einen Anfangszeitpunkt mit Datum und Uhrzeit sowie eine Dauer angeben, für die Hauptspeicher- und Plattenspeichernutzungsmetriken angezeigt werden sollen (z. B. Hauptspeichernutzung für 15 Tage ab dem 1. Juli 2017).
  * Es wurde ein neuer CLI-Befehl eingeführt, mit dem der Verlauf der Ressourcenmetriken in der CLI angezeigt werden kann. Die Parameter des Befehls sowie Verwendungsbeispiele können Sie durch Eingabe von `_cf ba resource-metrics-history -help_` aufrufen.

Weitere Informationen können Sie dem [Video](https://youtu.be/QBij0jB5qAk){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link") entnehmen.

### Aktualisierungen für die Administrationskonsole im Juni
{: #juneadminconsole}
Datum der Neuerung: 26. Juni 2017

Durch die neuesten Aktualisierungen und Verbesserungen im Juni können Sie die folgenden neuen Features nutzen:

#### Aktualisierungen der Seite 'Ressourcennutzung'

  * Systemressourcen
    * Die Ansicht 'Protokoll' für Haupt- und Plattenspeicher wurde aktualisiert und zeigt nun Daten für die letzten 48 Stunden, 30 Tage und 5 Monate an.
    * Durch einen bereitgestellten Link 'Weitere Informationen' kann angezeigt werden, wie die Metrik-API der Administrationskonsole zur Generierung der Verlaufsansichten verwendet wird.
  * Anwendungen
    * Es werden Nutzungsinformationen für alle Anwendungen in der Umgebung bereitgestellt.
    * Die Daten sind nach Anwendungsname, physischem Hauptspeicher, reserviertem Speicher, physischer Platte, physischer CPU oder Organisationsname sortiert.
    * Durch einen Suchvorgang können Ergebnisse nach Anwendungsname und Organisation gefiltert werden.
    * Durch einen bereitgestellten Link 'Weitere Informationen' kann angezeigt werden, wie die Metrik-API der Administrationskonsole zur Generierung der Ansicht 'Anwendungen' verwendet wird.

Weitere Informationen finden Sie unter [Ressourcennutzung](/docs/hybrid/index.html#resourceusage).

#### Aktualisierungen der API für Metriken

  * Es wurde eine Umgebungsstatistik hinzugefügt, die tägliche oder monatliche Durchschnittswerte für die Hauptspeicher- und Plattenspeichernutzung bereitstellt.

Weitere Informationen finden Sie unter [API für Metriken](/docs/hybrid/index.html#envappmetricsapi).


### Aktualisierungen für die Administrationskonsole im Mai
{: #mayadminconsole}
Datum der Neuerung: 30. Mai 2017

Durch die neuesten Aktualisierungen und Verbesserungen im Mai können Sie die folgenden neuen Features nutzen:

 * Die Seite 'Status' wurde unter anderem durch eine differenziertere Diagnose für Vorfälle verbessert, die sich auf die {{site.data.keyword.Bluemix_notm}}-Plattform und -Laufzeiten auswirken.
 * Die Seite 'Berichte und Protokolle' für die Sicherheit wurde folgendermaßen verbessert:
   * Berichte werden nun im Tabellenformat angezeigt, was das Anzeigen und Durchsuchen von Berichten vereinfacht und darüber hinaus die Möglichkeit zum Sortieren nach Berichtskategorie, Dateiname oder Erstellungsdatum bietet.
   * Die Filterung wurde unter anderem durch die gleichzeitige Filterung von mehreren Kategorien erweitert.
   * Der Inhalt eines Berichts kann nun im Gesamtanzeigemodus erfolgen.
   * Benutzer mit Administratorberechtigung und der Berechtigung zum Schreiben von Berichten können jetzt Berichte löschen.
   * Berichtslisten werden schneller angezeigt, indem durch kontinuierliches Blättern nach und nach bedarfsgerechte Ladevorgänge erfolgen, was zu einer besseren Gesamtleistung führt.
 * Sicherheitsberichte können bedarfsgerecht innerhalb eines Zeitraums angefordert werden, der sich maximal über eine Woche erstrecken kann und höchstens 3 Monate vor dem Zeitpunkt der Anforderung beginnen kann. Es ist zu beachten, dass eine gewisse umgebungsspezifische Konfiguration erforderlich ist, damit diese Funktionalität für Benutzer mit Administratorberechtigung verfügbar ist. Außerdem benötigen Benutzer mit Administratorberechtigung für diese Funktion die Berechtigung zum Schreiben von Berichten.

### Aktualisierungen für die Administrationskonsole im April
{: #apriladminconsole}
Datum der Neuerung: 2. Mai 2017

Durch die neuesten Aktualisierungen und Verbesserungen im April können Sie die folgenden neuen Features nutzen:

 * Die Statusapp für Umgebungen von {{site.data.keyword.Bluemix_notm}} Dedicated und Local wurde neu gestaltet. Sie können jetzt schnelle Suchvorgänge nach Komponentenname oder Datumsdatum durchführen. Außerdem können Sie zwischen der Ansicht für Komponentenstatusbeiträge und den speziellen Benachrichtigungen für Ihre Umgebung umschalten. Weitere Informationen enthält der Blogbeitrag [New {{site.data.keyword.Bluemix_notm}} Status Page](https://www.ibm.com/blogs/bluemix/2017/05/new-bluemix-status-page/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link").
 * Ausgehend von der Kachel 'Ressourcennutzung' können jetzt Servicenutzungsdaten für ausgewählte Services angezeigt werden. Weitere Informationen finden Sie unter [Details zur Verwendung des Service](/docs/hybrid/index.html#servicesresourceusage).

## Infrastruktur und Ressourcen
{: #compute_category}

### Kubernetes-Dashboard-Zugriff für {{site.data.keyword.containerlong_notm}}

{{site.data.keyword.containerlong_notm}} unterstützt jetzt direkten Zugriff auf das Kubernetes-Dashboard über die {{site.data.keyword.Bluemix_notm}}-Konsole. Dieser vereinfachte Pfad zum Dashboard bietet eine verbesserte Benutzererfahrung für das Cluster-Management und die Darstellung von Ressourcen. Weitere Details finden Sie im [{{site.data.keyword.Bluemix_notm}}-Blog](https://www.ibm.com/blogs/bluemix/2018/04/kubernetes-dashboard-access/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link").

### Neueste Aktualisierungen für Buildpacks

Auf den folgenden Seiten finden Sie eine kumulative Liste der neuesten Aktualisierungen:

* [Neueste Aktualisierungen für das Buildpack für SDK for Nodejs](/docs/runtimes/nodejs/updates.html#latest_updates)
* [Neueste Aktualisierungen für das Liberty Buildpack](/docs/runtimes/liberty/updates.html#latest_updates)
* [Neueste Aktualisierungen für das Buildpack für ASP.NET Core](/docs/runtimes/dotnet/updates.html#latest_updates)
* [Neueste Aktualisierungen für das Buildpack für IBM XPages for {{site.data.keyword.Bluemix_notm}}](/docs/starters/xpages/index.html#updates)

### Neueste Aktualisierungen für {{site.data.keyword.containerlong_notm}}

{{site.data.keyword.containerlong_notm}} verwendet ab Mai 2017 die Kubernetes-Architektur. Die vorherige Architektur für einzelne und skalierbare Containergruppen wird [ab dem 5. Dezember 2017 nicht mehr unterstützt](https://www.ibm.com/blogs/bluemix/2017/07/deprecation-single-scalable-group-container-service-bluemix-public/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link").  

[Informationen zum Einstieg in die native Kubernetes-Umgebung bei {{site.data.keyword.Bluemix_notm}}](/docs/containers/container_index.html) finden Sie in der Dokumentation. Etwaige Fragen können Sie in Slack unter der Adresse 'https://ibm-container-service.slack.com/' posten.

### Neues Liberty Buildpack für Java v3.11
Datum der Neuerung: 17. Juli 2017

Das Liberty Buildpack v3.11 bietet eine neue monatliche Liberty-Laufzeitversion und weitere Verbesserungen. Die monatliche Liberty-Laufzeitversion wurde auf das Release [2017.7.0.0](https://developer.ibm.com/wasdev/blog/2017/07/07/beta-websphere-liberty-tools-july-2017/) aktualisiert. Die IBM JDK wurde auf die Versionen 8.0.4.7 und 7.1.4.5 aktualisiert. Das Buildpack stellt außerdem aktualisierte Versionen des Dienstprogramms 'App-Management' und des Agenten für die automatische Skalierung bereit. Die Cloudant-Standardbibliothek ist nun offiziell [java-cloudant](https://github.com/cloudant/java-cloudant); die [Ektorp-Bibliothek](https://github.com/helun/Ektorp) ist als Option weiterhin verfügbar (Details über diese Änderung enthält ein [Blogbeitrag](https://www.ibm.com/blogs/bluemix/2017/05/default-library-change-cloudant-auto-wiring-liberty-buildpack/)). Das Verhältnis für die Standard-Heapspeichergröße beträgt nun 50%, wenn Ihre Anwendung weniger als 512 MB Hauptspeicher hatte; lag der Wert über 512 MB, beträgt das Verhältnis weiterhin 75%. Ein neues Staging-Taskprotokoll wird jetzt generiert, das ein Debug von Staging-Fehlern vereinfacht. Zusätzliche Informationen enthält die Dokumentation über die [neuesten Aktualisierungen](https://console.ng.bluemix.net/docs/runtimes/liberty/updates.html).

### Neues Liberty Buildpack für Java v3.10
Datum der Neuerung: 12. Juni 2017

Das Liberty Buildpack v3.10 bietet neue vierteljährliche und monatliche Liberty-Laufzeitversionen und weitere Verbesserungen. Die Version der Liberty-Standardlaufzeit wurde auf 17.0.0.2 aktualisiert. Die monatliche Liberty-Laufzeitversion wurde auf das Release [2017.5.0.0](https://developer.ibm.com/wasdev/blog/2017/05/12/beta-websphere-liberty-tools-may-2017/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link") aktualisiert. Das Buildpack stellt außerdem aktualisierte Versionen des Dienstprogramms 'App-Management' und des eXtreme Scale-Clients bereit. Zusätzliche Informationen finden Sie in der Dokumentation über die [neuesten Aktualisierungen](/docs/runtimes/liberty/updates.html).

### Neues Buildpack für SDK for Node.js v3.12
Datum der Neuerung: 16. Mai 2017

Das Buildpack für SDK for Node.js v3.12 stellt für IBM SDK for Node.js die Versionen 0.12.17, 0.12.18, 4.8.0, 4.8.2, 6.10.0 und 6.10.2 bereit. Der Standardwert wurde vom letzten 4.x-Release auf das neueste 6.x-Release geändert und lautet somit derzeit 6.10.2. Da es sich um eine Änderung der Hauptversion handelt, könnten Auswirkungen auf Apps bestehen, die den Standardwert verwenden. Weitere Informationen zur Vermeidung von Problemen enthält der Blogbeitrag [Node.js version long-term support and the SDK for Node.js buildpack](https://www.ibm.com/blogs/bluemix/2016/11/node-version-support-and-sdk-buildpack/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link").

Neben den neuen Laufzeiten enthält dieses Release eine Buildpack-Fehlerkorrektur für ein Problem beim Handler für das Health Center 'App-Management' und den Node.js-Versionen 6.9.5 und 6.10.0.

### Neues Liberty Buildpack für Java v3.9
Datum der Neuerung: 27. April 2017

Das Liberty Buildpack v3.9 bietet eine neue monatliche Liberty-Laufzeitversion und weitere Verbesserungen. Die Version der Liberty-Standardlaufzeit wurde zur Berücksichtigung der iFixes PI77770, PI77605, IFPI77438 und IFPI79275 aktualisiert. Die monatliche Liberty-Laufzeitversion wurde auf das Release [2017.3.0.0](https://developer.ibm.com/wasdev/blog/2017/03/14/beta-websphere-liberty-tools-march-2017/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link") aktualisiert. Die Hauptspeicherberechnung wurde vom Staging in den Startprozess verschoben, was Heapspeicheränderungen beim Neustart einer Anwendung vereinfacht. Das Buildpack stellt außerdem aktualisierte Versionen des Service-Agenten für die automatische Skalierung und des eXtreme Scale-Clients bereit. Zusätzliche Informationen finden Sie in der Dokumentation über die [neuesten Aktualisierungen](/docs/runtimes/liberty/updates.html).

## Services
{: #services_category}

### {{site.data.keyword.streaminganalyticsshort}} führt neue Servicepläne mit einer containerbasierten Infrastruktur ein
Datum der Neuerung: 20. April 2018

{{site.data.keyword.streaminganalyticsshort}} wird jetzt in einer containerbasierten Kubernetes-Infrastruktur ausgeführt, die den Serivce mit Sicherheits- und Verfügbarkeitsvorteilen ausstattet.
 
Sie können auf diese neue containerbasierte Infrastruktur mithilfe von [Serviceplänen der Version 2](/docs/services/StreamingAnalytics/service_plans.html#service_plans) zugreifen. Sie können den {{site.data.keyword.streaminganalyticsshort}}-Plan wählen, der sich am besten für Ihre Arbeit eignet. Die Servicepläne der Version 2 umfassen die folgenden Verbesserungen:
 
* [IBM Streams-QSE mit Docker](https://www-01.ibm.com/marketing/iwm/iwm/web/preLogin.do?source=swg-ibmistvi)![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link"): Im [ Development Guide](https://developer.ibm.com/streamsdev/docs/cloud-beta-devguide/)![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link") erfahren Sie, wie Sie die neue Streams-QSE mit RHEL 7 in einer Docker-Umgebung verwenden können, um Ihre Anwendungen mit den neuen {{site.data.keyword.streaminganalyticsshort}}-Plänen der Version 2 zu kompilieren und bereitzustellen. 
* [{{site.data.keyword.streaminganalyticsshort}} v2-REST-API](https://console.bluemix.net/apidocs/1939-streaming-analytics-v2#introduction)![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link")
* [Neue Starter- und Beispielanwendungen ](https://developer.ibm.com/streamsdev/docs/cloud-beta-samples/) ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link")
* [Erweiterungen für hohe Verfügbarkeit im {{site.data.keyword.streaminganalyticsshort}}-Service](/docs/services/StreamingAnalytics/c_ha.html#consistent-regions)
* [Problembestimmungsfeatures im {{site.data.keyword.streaminganalyticsshort}}-Service ](https://developer.ibm.com/streamsdev/2018/02/15/streaming-analytics-console-gives-ways-find-fix-errors-beta-plans/)![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link")
* [Überwachung des Verhaltens von Operatoren und garantierte Tupelverarbeitung in der Cloud](https://developer.ibm.com/streamsdev/2018/02/15/monitor-operators-behave-ensure-resource-optimization/)![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link")

### {{site.data.keyword.iva_full_notm}} gibt es jetzt in einer Betaversion!
Datum der Neuerung: 16. März 2018

Mit [{{site.data.keyword.iva_full}}](https://console.bluemix.net/catalog/services/voice-agent-with-watson)![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link") können Sie auf der Basis von Watson-Services einen kognitiven Sprachunterstützungsagenten erstellen, mit dem Kunden telefonieren und sprechen können. Da sich der Sprachunterstützungsagent auf die künstliche Intelligenz von Watson stützt, kann er dialogorientiert kommunizieren, komplexe Interaktionen abwickeln und Kundenanrufe innerhalb des Sprachunterstützungsagenten lösen.

Diese Betaversion führt die folgenden zentralen Features ein:

* Finden Sie einfacher als je zuvor den Einstieg, indem Sie einen Sprachunterstützungsagenten und alle erforderlichen Watson-Services in einem einzigen Schritt erstellen.
* Übertragen Sie Anrufe aus Ihrem Sprachunterstützungsagenten beispielsweise an einen Contact-Center-Mitarbeiter oder an andere Ziele.
* Sammeln und analysieren Sie Anrufdaten, indem Sie Ihren Sprachunterstützungsagenten für das Weiterleiten von detaillierten Anrufdatensätzen, Transkriptionen und {{site.data.keyword.conversationshort}}-Ereignissen an eine {{site.data.keyword.cloudant_short_notm}}-Datenbank konfigurieren.
* Überwachen Sie die Servicenutzung und zeigen Sie Anrufprotokolle auf der neuen Seite _Nutzung_ an. Sie können schnell Statistiken für den aktuellen Monat anzeigen, Anrufprotokolle suchen und filtern und Systemnachrichten für jeden einzelnen Anruf anzeigen.
* Richten Sie sichere Anrufe mit Medienverschlüsselung mit SIP TLS (sips-URIs) über Port 5061 und Secure Real-time Transport Protocol (SRTP) ein.
* Stellen Sie eine Verbindung mit {{site.data.keyword.speechtotextfull}}- und {{site.data.keyword.texttospeechfull}}-Serviceinstanzen in anderen {{site.data.keyword.cloud_notm}}-Bereichen für eine höhere Flexibilität her.

Lesen Sie zum Einstieg die [{{site.data.keyword.iva_short}}](/docs/services/voice-agent/getting-started.html)-Dokumentation.

### Aktualisierungen für {{site.data.keyword.visualrecognitionshort}}
Datum der Neuerung: 14. März 2018

Der {{site.data.keyword.visualrecognitionfull}}-Service wurde aktualisiert, sodass nun Modellschulungen mit angepassten Klassifikationsmerkmalen in Form von Klassifikationsmerkmalen für tiefes Lernen generiert werden, die auf dem neuronalen Netz basieren. Möglicherweise erfordert die zum Generieren dieser Modelle für tiefes Lernen erforderliche Rechenleistung mehr Schulungszeit für die neuen Modelle.

Derzeit können vorhandene angepasste Klassifikationsmerkmale weiterhin aktualisiert und erneut geschult werden. Sie werden nicht auf dieses neue Maschinenmodellformat für tiefes Lernen aktualisiert.

### {{site.data.keyword.streaminganalyticsshort}}-Aktualisierungen
Datum der Neuerung: 14. Februar 2018

Die ['Beta - Entry'- und 'Beta - Enhanced'-Pläne](/docs/services/StreamingAnalytics/beta_plans.html#beta_plans) für die Konsole im [{{site.data.keyword.streaminganalyticsshort}}-Service](https://console.bluemix.net/catalog/services/streaming-analytics){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link") enthalten diverse Erweiterungen:

* [Neue IBM Streams-QSE für Docker](https://www-01.ibm.com/marketing/iwm/iwm/web/preLogin.do?source=swg-ibmistvi){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link"): Im [Streaming Analytics Beta Development Guide](https://developer.ibm.com/streamsdev/docs/cloud-beta-devguide/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link") erfahren Sie, wie Sie die neue Streams-QSE mit RHEL 7 in einer Docker-Umgebung verwenden können, um Ihre Anwendungen mit den neuen {{site.data.keyword.streaminganalyticsshort}}-Beta-Plänen zu kompilieren und bereitzustellen.
* [{{site.data.keyword.streaminganalyticsshort}} v2-REST-API](https://console.bluemix.net/apidocs/1939-streaming-analytics-v2#introduction){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link")
* [Neue Starter- und Beispielanwendungen](https://developer.ibm.com/streamsdev/docs/cloud-beta-samples/)
* [Erweiterungen für hohe Verfügbarkeit im {{site.data.keyword.streaminganalyticsshort}}-Service](/docs/services/StreamingAnalytics/consistentregions.html#consistentregions)
* [Neue Problembestimmungsfeatures in der Betaversion des {{site.data.keyword.streaminganalyticsshort}}-Service](https://developer.ibm.com/streamsdev/2018/02/15/streaming-analytics-console-gives-ways-find-fix-errors-beta-plans/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link")
* [Überwachung des Verhaltens von Operatoren und garantierte Tupelverarbeitung in der Cloud](https://developer.ibm.com/streamsdev/2018/02/15/monitor-operators-behave-ensure-resource-optimization/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link")

### {{site.data.keyword.keymanagementservicelong_notm}} wird um die Region 'Sydney' erweitert
Datum der Neuerung: 31. Januar 2018

Der {{site.data.keyword.keymanagementserviceshort}}-Verschlüsselungsschlüsselmanagementservice ist ab sofort in der Region 'Sydney' verfügbar. 'Sydney' ist die dritte Region nach 'Vereinigte Staaten (Süden) (Dallas)' und 'London', in der der GA-Status für {{site.data.keyword.keymanagementserviceshort}}-Benutzer bereitgestellt wird.

{{site.data.keyword.keymanagementserviceshort}} ist ein Verschlüsselungsschlüsselmanagementservice, der eine einfache und wirtschaftliche Schlüsselmanagementlösung für das Verwalten von Schlüsseln anbietet, die zum Verschlüsseln von in {{site.data.keyword.Bluemix_notm}} gespeicherten Daten verwendet werden. {{site.data.keyword.keymanagementserviceshort}} verwaltet den kompletten Lebenszyklus von Schlüsseln - von der Schlüsselerstellung über die Anwendungsnutzung bis hin zur Schlüsselarchivierung und -vernichtung - und setzt gleichzeitig das Vier-Augen-Prinzip für die Datenverwaltung und Schlüsselverwaltung durch.

{{site.data.keyword.keymanagementserviceshort}} unterstützt BYOK (Bring-Your-Own-Key – benutzerverwaltete Verschlüsselung) in anwendbaren IBM Datenservices. BYOK ermöglicht Benutzern, Root-of-Trust-Masterverschlüsselungsschlüssel zu importieren, die intern erstellt wurden, um die Sicherheit ihrer in {{site.data.keyword.Bluemix_notm}} gespeicherten ruhenden Daten besser verwalten zu können.


### {{site.data.keyword.containershort_notm}}: Unterstützung von Kubernetes 1.8.x
Datum der Neuerung: 19. Januar 2018

Seit November 2017 unterstützte {{site.data.keyword.containershort_notm}} Kubernetes `1.8.x`. Wir freuen uns, bekanntgeben zu können, dass die Standardversion von Kubernetes jetzt `1.8.6` lautet.  In naher Zukunft wird die Unterstützung für `1.9.x` bereitgestellt.

### Watson Discovery Visual Insights
Datum der Neuerung: 30. November 2017

Dank des Verständnisses von {{site.data.keyword.discoveryshort}} für semantische Elemente, die im Text erkannt wurden (z. B. Entitäten, Beziehung, Konzepte u. a.) können Sie Verbindungen grafisch orientiert untersuchen.

Zum Einstieg können Sie die weltweiten Nachrichten in der sofort einsatzfähigen Datensammlung '{{site.data.keyword.discoveryshort}} News' durchsuchen. Sie können aber auch Ihre eigenen Dokumentsammlungen in {{site.data.keyword.discoveryshort}} durchsuchen. Melden Sie sich einfach mit Ihren {{site.data.keyword.Bluemix_notm}}-Berechtigungsnachweisen an. Weitere Informationen finden Sie unter [Visual Insights (experimentell)](https://visual-insights.bluemix.net){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link").

### Neuer IBM Cloud-Betaservice 'Managed Database Server'
Datum der Neuerung: 30. November 2017

Mit dem neuen IBM Cloud-Betaservice 'Managed Database Server' können Sie eine Instanz von Microsoft SQL Server bei {{site.data.keyword.Bluemix_notm}} erstellen. Diese SQL Server-Instanz können Sie wie jedes beliebige Datenbankmanagementsystem verwenden, jedoch ohne den Aufwand und die Kosten, die mit einer Hardwareinstallation oder einer Softwareinstallation und -wartung einhergehen.

Dieser Service bietet die folgenden Features:
* Auswahl unter den Microsoft SQL Server Versionen 2012, 2014 und 2016 (Enterprise und Standard Edition)
* Verschiedene vordefinierte Konfigurationen oder Größen zur Ausrichtung an Ihren Anwendungsworkloadanforderungen
* Vollständige Verwaltung durch IBM, inklusive Überwachung, Programmkorrektur, Sicherung und Berichterstellung

Informationen zum Einstieg finden Sie unter [Einführung in IBM Cloud Managed Database Server](/docs/services/managed-sql-server/getting-started.html).

### Neuerungen in {{site.data.keyword.mobilepushshort}}
Datum der Neuerung: 26. Oktober 2017

In den letzten Monaten wurden einige Erweiterungen am {{site.data.keyword.mobilepushshort}}-Service vorgenommen. Der Service ist nun in den Regionen 'Frankfurt' sowie 'Dallas', 'London' und 'Sydney' verfügbar. Die Details der Erweiterungen sind nachfolgend aufgeführt:

#### Überwachung
Sie können jetzt die Leistung von Push-Benachrichtigungen für bestimmte Zeiträume, die Anzahl der gesendeten Benachrichtigungen sowie die Gesamtzahl der registrierten Geräte überwachen. Außerdem können Sie Web-Hooks registrieren, um über alle Ereignisse im Lebenszyklus einer Benachrichtigung informiert zu werden. Weitere Details enthalten die folgenden Dokumentationslinks und Blogbeiträge:
* [Benachrichtigungen überwachen](/docs/services/mobilepush/push_monitoring.html#push_monitoring)
* [Alerts über Web-Hook-Ereignisse empfangen](/docs/services/mobilepush/push_webhook.html#webhook_event_based_notifications)
* [Monitoring in IBM Push Notifications](https://www.ibm.com/blogs/bluemix/2017/03/monitoring-ibm-push-notifications/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link")

#### Webbenachrichtigungen
Für Webbenachrichtigungen wird jetzt neben Firefox, Chrome, Chrome App and Extensions auch der Safari-Web-Browser unterstützt. Web-SDKs und zugehörige Informationen sind unter [IBM Bluemix Push Notifications Web SDK](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-javascript-webpush/blob/Doc/README.md){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link") zu finden.

#### Neueste Benachrichtigungen für Android und iOS
Für iOS 11-Benachrichtigungen gibt es jetzt eine Währungsunterstützung. Außerdem wurden mehrere neue benachrichtigungsbezogene Erweiterungen aus iOS10 und Android N integriert.

* iOS10: Rich Media-Benachrichtigungen, Images, Schaltflächen und Karten in interaktiven Benachrichtigungen, Unterstützung von lokalisierten Zeichenfolgen
* Android N: Erweiterbare Benachrichtigungen, interaktive Benachrichtigungen und Benachrichtigungen im Hintergrund, Einstellungen für LED-Licht

Zusätzliche Details finden Sie in der Dokumentation unter [Rich-Media-Benachrichtigungen](/docs/services/mobilepush/push_step_4_nf_rich.html#interactive-notifications), [Interaktive Benachrichtigungen und Benachrichtigungen im Hintergrund](/docs/services/mobilepush/push_step_4_nf_interactive.html#interactive-notifications) sowie [Erweiterte Push-Benachrichtigungen aktivieren](/docs/services/mobilepush/push_step_4_nf_adv.html#enabling-advanced-push-notifications).

#### Unterstützung von APNS HTTP/2
Apple hat eine Unterstützung des HTTP-Protokolls für Apple Notifications eingeführt. Der {{site.data.keyword.mobilepushshort}}-Service unterstützt jetzt das HTTP/2-Protokoll. Durch diese Unterstützung können Benachrichtigungen Nutzdaten in einer Größe von 4 KB enthalten; gleichzeitig wird der Durchsatz gesteigert und es gibt eine Funktion für ein Sofortfeedback. Die Unterstützung von Universal Certificate ermöglicht der App Verbindungen sowohl zur Sandbox- als auch zur Produktionsumgebung.

#### Neuer Lite-Plan
Der Lite-Plan für den {{site.data.keyword.mobilepushshort}}-Service ermöglicht das kostenlose Senden von Benachrichtigungen mit einer Größe von 100 K monatlich. Weitere Informationen enthält der Blogbeitrag [Lite Plan For Push Notifications Service on Bluemix](https://www.ibm.com/blogs/bluemix/2017/06/lite-plan-push-notifications-service-bluemix/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link").



### Neuerungen in Mobile Analytics
Datum der Neuerung: 26. Oktober 2017

In den letzten Monaten wurden Erweiterungen am {{site.data.keyword.mobileanalytics_short}}-Service vorgenommen. Der Service ist nun in den Regionen 'Frankfurt' und 'Sydney' sowie 'Dallas' und 'London' verfügbar. Die Details der Erweiterungen sind nachfolgend aufgeführt:

#### Web-SDK-Unterstützung
{{site.data.keyword.mobileanalytics_short}} ist jetzt ein Omni-Channel-Service und bietet zusätzlich Unterstützung für Web-App-Analysen. Weitere Details finden Sie unter der Adresse [https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-web-analytics/](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-web-analytics/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link").

#### Integration mit {{site.data.keyword.mobilefoundation_short}}-Service
Der {{site.data.keyword.mobilefoundation_short}}-Service nutzt jetzt den {{site.data.keyword.mobileanalytics_short}}-Service zur App-, Benutzer- und Leistungsanalyse. Benutzer können die Option 'In DB2-Data-Warehouse exportieren' nutzen, um eine Adapteranalyse und benutzerdefinierte Diagramme zu erstellen. Zusätzliche Details enthalten die folgenden Blogbeiträge:

* [Mobile Foundation Service integration with Mobile Analytics Service](https://www.ibm.com/blogs/bluemix/2017/08/mobile-foundation-service-integration-mobile-analytics-service-2/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link")
* [Building custom charts using IBM Bluemix Mobile Analytics service and IBM Mobile Foundation Service](https://mobilefirstplatform.ibmcloud.com/blog/2017/04/26/custom-charts-using-analytics-and-dashdb-analytics-service/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link")
* [Building charts for Adapter analytics using IBM Bluemix Mobile Analytics service and IBM Mobile Foundation Service](https://mobilefirstplatform.ibmcloud.com/blog/2017/04/26/adapter-analytics-using-analytics-and-dashdb-analytics-service/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link")

#### {{site.data.keyword.mobilefirst_notm}}-Boilerplate enthält jetzt {{site.data.keyword.mobileanalytics_short}}
Die Mobile Services-Boilerplate ist eine Vorlage, die eine Reihe von mobilen Services bereitstellt und Benutzern so einen schnellen Einstieg ermöglicht. Der {{site.data.keyword.mobileanalytics_short}}-Service ist jetzt Bestandteil der Boilerplate, die im [Katalog](https://console.bluemix.net/catalog/starters/mobilefirst-services-starter){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link") verfügbar ist.


### Aktualisierungen für {{site.data.keyword.streaminganalyticsshort}}
Datum der Neuerung: 20. Oktober 2017

* IBM Streams Runner for Apache Beam: Sie können jetzt Beam-Anwendungen lokal in Ihrer Streams-Entwicklungsumgebung entwickeln und anschließend diese Apps an den {{site.data.keyword.streaminganalyticsshort}}-Service in {{site.data.keyword.Bluemix_notm}} übergeben. IBM Streams Runner for Apache Beam führt Beam-Pipelines in einer Streams-Umgebung aus. Eine Beam-Anwendung, die mit Streams Runner gestartet wird, wird in eine Datei des Typs 'Streams Application Bundle' (SAB) umgesetzt, die Sie anschließend in {{site.data.keyword.streaminganalyticsshort}} bereitstellen können. Weitere Details finden Sie unter [IBM Streams Runner for Apache Beam bei der Streaming-Analyse](/docs/services/StreamingAnalytics/gs_beamrunner.html).
* Informationen aus Protokolldateien können Sie jetzt noch schneller abrufen. Die Konsole wurde mit einer verbesserten Anzeige von Anwendungsdiagrammen für Python- oder Java-Topologien aktualisiert. Weitere Informationen finden Sie unter [Erweiterungen der Konsole](https://developer.ibm.com/streamsdev/2017/10/13/enhancements-to-the-console/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link").

### IBM App Launch for {{site.data.keyword.Bluemix_notm}} Services
Datum der Neuerung: 12. Oktober 2017

IBM App Launch for {{site.data.keyword.Bluemix_notm}} Services ist ein experimentelles Angebot, mit dem Sie Kundenerlebnisse messen können. Hierzu wird eine Plattform bereitgestellt, mit der Sie zielgruppenspezifische Projekte für unterschiedliche Schnittmengen Ihrer Benutzergruppen erstellen können. Der App Launch-Service vermittelt Ihnen Einblicke in die Kundenpräferenzen und Problemstellungen, die sich bei Projekten ergeben, und hilft Ihnen dabei, die App für bessere Kundenerlebnisse zu personalisieren.

App-Eigner können nun die Bereitstellung von Innovationen für mobile Apps beschleunigen, da komplexe Releasezyklen vermieden werden. Der App Launch-Service versetzt App-Eigner in die Lage, Features für mobile Apps kurzfristig zur Verfügung zu stellen und die Wirkung durch eine Kontrolle der Zielgruppe zu messen. Der App-Eigner kann zusammen mit dem App-Entwickler die KPIs (Key Performance Indicator, wesentliche Leistungsindikatoren) für die Features definieren, die Wirkung messen und anhand des Echtzeitfeedbacks Entscheidungen über ihr Rollout oder Rollback treffen. Außerdem ermöglicht der Service das Testen verschiedener Varianten von Anwendungsfeatures, Benutzerschnittstellenkomponenten sowie Nachrichten und anschließend Entscheidungen, die auf dem Feedback basieren.

Weitere Informationen enthält das [Lernprogramm - Einführung](/docs/services/app-launch/index.html#gettingstartedtemplate).

### Aktualisierungen für {{site.data.keyword.ibmwatson_notm}} {{site.data.keyword.relationshipextractionshort}}
Datum der Neuerung: 4. Oktober 2017

Durch {{site.data.keyword.relationshipextractionshort}} sind für Benutzer eine neue Anpassungsfunktion und neue Sprachmodelle verfügbar. Die neuen Sprachen sind Niederländisch, Koreanisch und vereinfachtes Chinesisch (Unterstützung für WKS).

### Aktualisierung für {{site.data.keyword.containerlong_notm}}-Cluster
Datum der Neuerung: 20. September 2017

Sie können Ihre Cluster jetzt auf die neueste verfügbare Version von Kubernetes in {{site.data.keyword.Bluemix_notm}} aktualisieren. Aktualisieren Sie Ihre Kubernetes-Masterknoten und Ihre Workerknoten entweder über die grafische Benutzerschnittstelle oder über die CLI auf Kubernetes 1.7, damit Sie die neuen Features und Patches nutzen können.

Weitere Informationen enthält der Blogbeitrag [Kubernetes 1.7 available in {{site.data.keyword.containerlong_notm}}](https://www.ibm.com/blogs/bluemix/2017/09/kubernetes-1-7-available-ibm-bluemix-container-service/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link").

### Neuer experimenteller Service 'IBM Voice Agent with Watson'
Datum der Neuerung: 15. September 2017

Mit dem neuen experimentellen Service {{site.data.keyword.iva_full}} können Sie auf der Basis von Watson-Services einen kognitiven Sprachunterstützungsagenten erstellen, mit dem Kunden telefonieren und sprechen können. Da sich der Sprachunterstützungsagent auf die künstliche Intelligenz von Watson stützt, kann er dialogorientiert kommunizieren, komplexe Interaktionen abwickeln und Kundenanrufe innerhalb des Sprachunterstützungsagenten lösen.

{{site.data.keyword.iva_short}} wird nahtlos verbunden und koordiniert die Watson-Services '{{site.data.keyword.speechtotextshort}}', '{{site.data.keyword.conversationshort}}' und '{{site.data.keyword.texttospeechshort}}', um einen Dialog in natürliche Sprache zu simulieren. Jeder Sprachunterstützungsagent wird automatisch skaliert, um mehrere Anrufe gleichzeitig abzuwickeln. Bei diesem experimentellen Release können Sie Ihren Sprachunterstützungsagenten mithilfe der folgenden Schlüsselfunktionen anpassen:

* Zum Einstieg können Sie das {{site.data.keyword.conversationshort}}-Beispieldialogmodul importieren und dann ein eigenes Dialogmodul erstellen, das zu den Anforderungen Ihres Unternehmens passt.
* Sie können das Verhalten des Sprachunterstützungsagenten innerhalb des {{site.data.keyword.conversationshort}}-Service mithilfe der APIs programmieren. Ihre Steuerungsmöglichkeiten erstrecken sich auf alle Bereiche, vom Einsprechen in eine laufende Bandansage bis hin zur Beendigung des Anrufs bei einem beliebigen Knoten in Ihrem Dialogmodul.
* Sie können ohne großen Aufwand mehrere Sprachunterstützungsagenten erstellen und verwalten, wenn Sie unterschiedliche Telefonnummern mit kognitiven Agenten verbinden möchten, die auf verschiedene Themen spezialisiert sind.
* Sie können das Funktionsspektrum des Service durch die Verbindung mit einer Serviceorchestrierungsengine (SOE) erweitern, damit Sie APIs anderer Anbieter einsetzen können. Beispielsweise kann die SOE Auslöser aus dem {{site.data.keyword.conversationshort}}-Service überwachen und dann mit den von Ihnen bereitgestellten APIs nach Informationen in vorhandenen Systemen suchen oder andere Analysefunktionen ausführen.

Lesen Sie zum Einstieg die Dokumentation unter [Einführung in {{site.data.keyword.iva_short}}](/docs/services/voice-agent/getting-started.html).


### Aktualisierung für {{site.data.keyword.streaminganalyticsshort}}-Service: Konsole bietet neue Verfahren für die Problemermittlung in Anwendungen
Datum der Neuerung: 14. August 2017

Für Python- und Java-Anwendungen wird die Position der Quellendatei basierend auf Ihren @spl_note-Annotationen angezeigt.

Details finden Sie im Artikel [Latest improvements to the {{site.data.keyword.streaminganalyticsshort}}](https://developer.ibm.com/streamsdev/2017/08/14/latest-improvements-streaming-analytics-console/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link").

### IBM Cloud Monitoring nun auch in der Region 'Vereintes Königreich' verfügbar
Datum der Neuerung: 1. August 2017

Mit dem {{site.data.keyword.monitoringlong}}-Service können Sie Ihre Datensammlungs-, Aufbewahrungs- und Analysekapazitäten in {{site.data.keyword.Bluemix_notm}} erweitern, wenn Sie mit Metriken arbeiten.

* Aktionen durch Alerts auslösen. {{site.data.keyword.monitoringlong}} stellt eine API bereit, die Sie verwenden können, um Leistungsschwellenwerte festzulegen und sich benachrichtigen zu lassen, wenn diese Schwellenwerte überschritten werden. Definieren Sie Alertregeln für eine einzelne Serviceinstanz oder App-Instanz sowie Alertregeln für eine Gruppe von Instanzen. Wenn ein Alert ausgelöst wird, erhalten Sie eine Benachrichtigung über E-Mail, PagerDuty-Ereignis, Webhook-Nachricht oder eine beliebige Kombination davon.

* Angepasste Metriken hinzufügen. Im Rahmen des Premium-Plans für {{site.data.keyword.monitoringlong}} stehen APIs zur Verfügung, mit denen Sie relevante Anwendungs- und Geschäftsmetriken zu Ihren Cloud Monitoring-Daten hinzufügen können. Darüber hinaus können Sie diese verwenden, um Metrikdaten von außerhalb der {{site.data.keyword.IBM_notm}} Cloud an den {{site.data.keyword.monitoringlong}}-Service zu senden.

* Wiederverwendbare Dashboards erstellen und Funktionalität für die Interaktive Verwendung hinzufügen. Das mit {{site.data.keyword.monitoringlong}} bereitgestellte Grafana bietet Unterstützung für die Erstellung angepasster Dashboards mit einer breiten Palette an Visualisierungsoptionen.  Machen Sie Dashboards durch den Einsatz von Vorlagen dynamisch, indem Sie Metrikabfragen mit Variablen verwenden.

* Über den {{site.data.keyword.Bluemix_notm}}-Katalog auf den Service zugreifen. {{site.data.keyword.monitoringlong}} ist als Servicekachel im DevOps-Abschnitt des {{site.data.keyword.Bluemix_notm}}-Katalogs verfügbar.  Für den {{site.data.keyword.containershort}}-Service mit Einzel- und Gruppencontainern ist der Zugriff über die {{site.data.keyword.Bluemix_notm}}-Benutzerschnittstelle möglich.

* Den Serviceplan auswählen, der den jeweiligen Bedürfnissen am besten entspricht. Abhängig von den jeweiligen Nutzungsanforderungen können Sie den Lite-Serviceplan oder den Premium-Serviceplan auswählen. Der Lite-Plan bietet eine Erfassung von Metriken in Intervallen von einer Minute, Aufbewahrung für 15 Tage und ergänzende Alertfunktionalität.  Alternativ dazu können Sie den Premium-Plan auswählen, der die Verarbeitung größerer Volumen, längere Speicherzeiträume für Metriken und Zugriff auf die Service-APIs umfasst. Mit diesen APIs können Sie beispielsweise Metriken an den {{site.data.keyword.monitoringlong}}-Service senden oder von diesem abrufen. {{site.data.keyword.monitoringlong}} bietet die Erfassung von Metriken in Intervallen von einer Minute.  Im Rahmen des Lite-Plans werden die Metriken bei vollständiger Auflösung für 15 Tage gespeichert. Im Rahmen des Premium-Plans werden die Metriken bei vollständiger Auflösung für 45 Tage gespeichert.

Vom traditionellen {{site.data.keyword.monitoringshort}}-Service wurden Metriken in der vom Service definierten Häufigkeit (ab 30 Sekunden) erfasst und mit der Zeit für 1 Stunde zusammengefasst. {{site.data.keyword.monitoringlong}} bietet nun eine vollständige Auflösungserfassung mit 1 Minute.  Beim Lite-Plan werden Metriken 15 Tage lang aufbewahrt.  Beim Premium-Plan beträgt die Aufbewahrungsdauer 45 Tage.

Weitere Informationen zum {{site.data.keyword.monitoringlong}}-Service finden Sie in der Dokumentation unter [Einführung in Monitoring-Service](/docs/services/cloud-monitoring/index.html#getting-started-with-ibm-cloud-monitoring) oder im Blogbeitrag [IBM Cloud Monitoring – Service Refresh with New Features![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link")](https://www.ibm.com/blogs/bluemix/2017/07/ibm-cloud-monitoring-service-refresh-new-features/).


### IBM Cloud Log Analysis jetzt in Region 'Vereinigte Staaten (Süden)' verfügbar
Datum der Neuerung: 31. Juli 2017

Der {{site.data.keyword.loganalysisfull}}-Service umfasst Protokollerfassungs- und Protokollsuchservices für die {{site.data.keyword.Bluemix_notm}}-Plattform zur automatischen Erfassung von Anwendungs- und {{site.data.keyword.Bluemix_notm}}-Servicedaten von ausgewählten {{site.data.keyword.Bluemix_notm}}-Services. Mit dem {{site.data.keyword.loganalysisshort}}-Service können Sie Folgendes ausführen:

* Sie können Protokolle so lang wie benötigt aufbewahren.  

    Protokolle werden im IBM Cloud-Speicher gespeichert.  Sie können die Protokolle herunterladen, wenn Sie sie benötigen.

* Sie können Ihre aufbewahrten Protokolle verwalten und Protokolldaten mithilfe der neuen API aus externen Positionen an {{site.data.keyword.IBM_notm}} Cloud senden.

* Sie können das Volumen der Protokolle auswählen, die pro Tag durchsucht werden sollen.  

    Im Rahmen verschiedener verfügbarer Pläne können bis zu 500 MB, 2 GB, 5 GB und 10 GB an Protokollen pro Tag durchsucht werden.

* Wiederverwendbare Dashboards erstellen und Funktionalität für die Interaktive Verwendung hinzufügen.

    Das von {{site.data.keyword.loganalysisshort}} gehostete Kibana unterstützt die Erstellung von angepassten Dashboards.

* Über den {{site.data.keyword.Bluemix_notm}}-Katalog auf den Service zugreifen.  

    Für den {{site.data.keyword.loganalysisshort}}-Service mit Einzel- und Gruppencontainern und für {{site.data.keyword.IBM_notm}} Cloud Foundry-Services ist der Zugriff über die {{site.data.keyword.Bluemix_notm}}-Benutzerschnittstelle möglich.

Weitere Informationen zum {{site.data.keyword.loganalysisshort}}-Service enthalten die Abschnitte [Einführung in {{site.data.keyword.loganalysisfull}}](/docs/services/CloudLogAnalysis/index.html#getting-started-with-ibm-cloud-log-analysis) und [Übersicht über {{site.data.keyword.loganalysisshort}}](/docs/services/CloudLogAnalysis/log_analysis_ov.html#log_analysis_ov).

### Umbenennung von IBM dashDB for Analytics
Datum der Neuerung: 18. Juli 2017

Die folgende Tabelle gibt Aufschluss über den neuen Namen:

| Vorheriger Name               | Neuer Name                   | Stichtag |
|-----------------------------|----------------------------|----------------|
| IBM dashDB for Analytics    | IBM Db2 Warehouse on Cloud | 18. Juli 2017  |
{: caption="Tabelle 1. Änderung des Servicenamens" caption-side="top"}

Eine kumulative Liste der Aktualisierungen für Db2 Warehouse on Cloud und Db2 on Cloud finden Sie unter [What's New in Db2 Warehouse on Cloud and Db2 on Cloud](http://www.ibm.com/support/docview.wss?uid=swg21961758){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link").

### IBM Cloud Monitoring jetzt in Region 'Vereinigte Staaten (Süden)' verfügbar
Datum der Neuerung: 17. Juli 2017

Mit dem {{site.data.keyword.monitoringlong}}-Service können Sie Ihre Datensammlungs-, Aufbewahrungs- und Analysekapazitäten in {{site.data.keyword.Bluemix_notm}} erweitern, wenn Sie mit Metriken arbeiten.

* Aktionen durch Alerts auslösen. {{site.data.keyword.monitoringlong}} stellt eine API bereit, die Sie verwenden können, um Leistungsschwellenwerte festzulegen und sich benachrichtigen zu lassen, wenn diese Schwellenwerte überschritten werden. Definieren Sie Alertregeln für eine einzelne Serviceinstanz oder App-Instanz sowie Alertregeln für eine Gruppe von Instanzen. Wenn ein Alert ausgelöst wird, erhalten Sie eine Benachrichtigung über E-Mail, PagerDuty-Ereignis, Webhook-Nachricht oder eine beliebige Kombination davon.

* Angepasste Metriken hinzufügen. Im Rahmen des Premium-Plans für {{site.data.keyword.monitoringlong}} stehen APIs zur Verfügung, mit denen Sie relevante Anwendungs- und Geschäftsmetriken zu Ihren Cloud Monitoring-Daten hinzufügen können. Darüber hinaus können Sie diese verwenden, um Metrikdaten von außerhalb der {{site.data.keyword.IBM_notm}} Cloud an den {{site.data.keyword.monitoringlong}}-Service zu senden.

* Wiederverwendbare Dashboards erstellen und Funktionalität für die Interaktive Verwendung hinzufügen. Das mit {{site.data.keyword.monitoringlong}} bereitgestellte Grafana bietet Unterstützung für die Erstellung angepasster Dashboards mit einer breiten Palette an Visualisierungsoptionen.  Machen Sie Dashboards durch den Einsatz von Vorlagen dynamisch, indem Sie Metrikabfragen mit Variablen verwenden.

* Über den {{site.data.keyword.Bluemix_notm}}-Katalog auf den Service zugreifen. {{site.data.keyword.monitoringlong}} ist als Servicekachel im DevOps-Abschnitt des {{site.data.keyword.Bluemix_notm}}-Katalogs verfügbar.  Für den {{site.data.keyword.containershort}}-Service mit Einzel- und Gruppencontainern ist der Zugriff über die {{site.data.keyword.Bluemix_notm}}-Benutzerschnittstelle möglich.

* Den Serviceplan auswählen, der den jeweiligen Bedürfnissen am besten entspricht. Abhängig von den jeweiligen Nutzungsanforderungen können Sie den Lite-Serviceplan oder den Premium-Serviceplan auswählen. Der Lite-Plan bietet eine Erfassung von Metriken in Intervallen von einer Minute, Aufbewahrung für 15 Tage und ergänzende Alertfunktionalität.  Alternativ dazu können Sie den Premium-Plan auswählen, der die Verarbeitung größerer Volumen, längere Speicherzeiträume für Metriken und Zugriff auf die Service-APIs umfasst. Mit diesen APIs können Sie beispielsweise Metriken an den {{site.data.keyword.monitoringlong}}-Service senden oder von diesem abrufen. {{site.data.keyword.monitoringlong}} bietet die Erfassung von Metriken in Intervallen von einer Minute.  Im Rahmen des Lite-Plans werden die Metriken bei vollständiger Auflösung für 15 Tage gespeichert. Im Rahmen des Premium-Plans werden die Metriken bei vollständiger Auflösung für 45 Tage gespeichert.

Vom traditionellen {{site.data.keyword.monitoringshort}}-Service wurden Metriken in der vom Service definierten Häufigkeit (ab 30 Sekunden) erfasst und mit der Zeit für 1 Stunde zusammengefasst. {{site.data.keyword.monitoringlong}} bietet nun eine vollständige Auflösungserfassung mit 1 Minute.  Beim Lite-Plan werden Metriken 15 Tage lang aufbewahrt.  Beim Premium-Plan beträgt die Aufbewahrungsdauer 45 Tage.

Weitere Informationen zum {{site.data.keyword.monitoringlong}}-Service finden Sie in der Dokumentation unter [Einführung in Monitoring-Service](/docs/services/cloud-monitoring/index.html#getting-started-with-ibm-cloud-monitoring) oder im Blogbeitrag [IBM Cloud Monitoring – Service Refresh with New Features![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link")](https://www.ibm.com/blogs/bluemix/2017/07/ibm-cloud-monitoring-service-refresh-new-features/).

### Upgrade von {{site.data.keyword.contdelivery_short}}
Datum der Neuerung: 11. Juli 2017

Zu den Vorteilen dieses Upgrades gehören Fehlerkorrekturen, Leistungsverbesserungen und Optimierungen der Funktionalität für den Benutzer. Zu den nennenswerten Erweiterungen gehören Folgende (sofern noch nicht in Ihrer Umgebung vorhanden):
<ul>
<li>Programmkorrekturen und Verbesserungen für Internationalisierung und barrierefreie Bedienung</li>
<li>Zugriffssteuerung für Toolchains (verfügbar auf der Registerkarte 'Verwalten' für eine Toolchain)</li>
<li>Neue Toolintegrationen in den Continuous Delivery-Toolkatalog</li>
<li>Verbesserte Gruppierung von mehreren Arbeitsbereichen in der Orion-Web-IDE</li>
<li>Unterstützung für mehrere Editorregisterkarten in der Orion-Web-IDE</li>
<li>Unterstützung für Benutzerschnittstellenthemen in der Orion-Web-IDE</li>
</ul>

### Betaversion von {{site.data.keyword.uccr_short}}
Datum der Neuerung: 23. Juni 2017

{{site.data.keyword.uccr_short}} ist eine auf Unternehmen abgestimmte Release-Management-Lösung, die sowohl cloudbasierte als auch lokale Bereitstellungstools unterstützt.

Die Betaversion von {{site.data.keyword.uccr_short}} bietet die folgenden Schlüsselfunktionen:
* Durch die Verwendung von Releases können Sie mehrere Bereitstellungspläne und -ereignisse verwalten sowie an Releaseentwicklungen durch mehrere Teams mitarbeiten.
* Sie können für jede releasebezogene Aktivität Ereignisse erstellen und diese mithilfe des Kalenders verwalten.
* Sie können eigene Ereignisse und Releases importieren.
* Sie können Kalenderereignisse für Ihre Organisation anpassen.
* Sie können E-Mail- und Slack-Tasks für Releasebenachrichtigungen verwenden.

### dashDB for Transactions in {{site.data.keyword.DB2_on_Cloud_short}} umbenannt
Datum der Neuerung: 14. Juni 2017

IBM {{site.data.keyword.DB2OnCloud_short}} ist der neue Name für dashDB for Transactions. Im Rahmen dieser Umbenennung wird auch der vormalige selbstverwaltete Service '{{site.data.keyword.DB2OnCloud_short}}' in 'IBM Db2 Hosted' umbenannt. Derzeit werden lediglich die Anzeigenamen aktualisiert; APIs oder Befehlszeilenschnittstellen bleiben somit unverändert.

### Aktualisierungen für {{site.data.keyword.sparks}}: Connector für Stocator-S3 enthält Unterstützung für Service 'IBM Cloud Object Storage Cross Region' (Betaversion)
Datum der Neuerung: 5. Juni 2017

{{site.data.keyword.sparks}}-Benutzer können jetzt auf Daten zugreifen, die im Service 'IBM Cloud Object Storage Cross Region' gespeichert sind, und diese Daten analysieren. Diese Funktionalität wird als Betaversion angeboten. IBM Cloud Object Storage bietet einen kosteneffizienten Speicher mit großer Kapazität für Analysen und andere Anwendungen, der skalierbar, flexibel und einfach zu verwenden ist.

Apache Spark greift auf Daten in IBM Cloud Object Storage über einen Speicherconnector zu, der auf der Stocator-Technologie basiert, implizit für Objektspeicher konzipiert ist und daher schneller als herkömmliche Objektspeicherconnectors arbeitet. Als Benutzer müssen Sie den Apache Spark-Code weder ändern noch erneut kompilieren.

Im Blogbeitrag [Access and Analyze data in IBM Cross Region Cloud Object Storage](https://www.ibm.com/blogs/bluemix/2017/06/access-analyze-data-ibm-cross-region-cloud-object-storage/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link") ist die Verwendung von Daten in IBM Cloud Object Storage mit {{site.data.keyword.sparks}} unter {{site.data.keyword.Bluemix_notm}} und IBM Data Science Experience (DSx) beschrieben.

Bei Fragen und Kommentaren können Sie sich unter der Adresse [sparksrv@us.ibm.com](sparksrv@us.ibm.com) mit uns in Verbindung setzen. Ihre Meinung interessiert uns sehr!

### Neuer skalierbarer Plan für {{site.data.keyword.dashdbshort_notm}} for Transactions verfügbar
Datum der Neuerung: 31. Mai 2017

Für {{site.data.keyword.dashdbshort}} for Transactions ist ein neuer Plan verfügbar, der gemeinsam mit Ihrem Datenbankbedarf vergrößert werden kann. Der neue Flex-Plan ermöglicht Ihnen den Einstieg mit einem kompakten System, dessen Leistung und Speicherkapazität Sie später zügig und ohne großen Aufwand erhöhen können. {{site.data.keyword.dashdbshort}} for Transactions ist zu 100% mit Db2 kompatibel und bietet ein Service-Level-Agreement von 99,95% für Pläne mit hoher Verfügbarkeit.

### Neue Aktualisierungen des {{site.data.keyword.mobilepush}}-Service bei {{site.data.keyword.Bluemix_notm}}
Datum der Neuerung: 24. Mai 2017

Die folgenden neuen Aktualisierungen sind für den {{site.data.keyword.mobilepush}}-Service bei {{site.data.keyword.Bluemix_notm}} verfügbar:

**Lite-Plan**: Neben dem bestehenden Basic-Plan für den {{site.data.keyword.mobilepush}}-Service wird ein Lite-Plan eingeführt. Mit dem neuen Plan können Benutzer bis zu einhunderttausend digitale Nachrichten pro Monat kostenlos senden. Bei einem Upgrade vom Lite-Plan auf den Basic-Plan werden für den Benutzer nach einer Million digitalen Nachrichten Gebühren fällig. Die Zählung beginnt zu dem Zeitpunkt, an dem das Upgrade des Lite-Plans auf den Basic-Plan erfolgt.

**Überwachung**: Sie können jetzt Informationen zu gesendeten Nachrichten und registrierten Geräten in der Konsole des {{site.data.keyword.mobilepush}}-Service einsehen. Außerdem können Sie REST-APIs für die Überwachung auf Nachrichtenebene einsetzen. Von der Nachrichtenübermittlung über die Nachrichtenzuteilung bis zum Nachrichtenempfang können Details durch die Konfiguration von Web-Hooks abgerufen werden.  Weitere Informationen finden Sie unter [Überwachung für {{site.data.keyword.mobilepush}}](/docs/services/mobilepush/t_push_monitoring.html#monitor-notifications).

**Web-Benachrichtigungen**: Sie können jetzt Benachrichtigungen an Safari-Web-Browser senden.

### Aktualisierungen für Secure Gateway
Datum der Neuerung: 24. Mai 2017

Die neueste Wartungsaktualisierung für Secure Gateway beinhaltet untergeordnete Fehlerkorrekturen in der Benutzerschnittstelle und im API-Manager, eine aktualisierte Dokumentation und die Aktualisierung des Clients auf Version 1.7.1. Der Secure Gateway-Client ist nun bei AIX 7.1+ verfügbar und unterstützt abgehende Verbindungen über einen squid-Proxy.

### Aktualisierungen für den {{site.data.keyword.streaminganalyticsshort}}-Service: Entwicklung von Streams-Anwendungen in der Python-Entwicklungsumgebung
Datum der Neuerung: 13. April 2017

Früher mussten Sie eine lokale Version von IBM Streams installieren, um Python-Anwendungen entwickeln zu können. Dies ist nun nicht mehr erforderlich. Jetzt können Sie Anwendungen mit Python in Ihrer bevorzugten Entwicklungsumgebung oder in einem interaktiven Jupyter-Notizbuch entwickeln.

Mit dem Kontext STREAMING_ANALYTICS_SERVICE können Sie eine Python-Anwendung an den {{site.data.keyword.streaminganalyticsshort}}-Service übergeben. Der {{site.data.keyword.streaminganalyticsshort}}-Service erfordert Python 3.5.

Sie können mithilfe von Jupyter-Notizbüchern Python-Beispielanwendungen in IBM Data Science Experience (DSX) erstellen und diese Anwendungen direkt aus DSX an die {{site.data.keyword.streaminganalyticsshort}}-Instanz übergeben. Probieren Sie die Python-Beispielanwendungen für die Streamverarbeitung in Notizbüchern auf der [Seite der DSX-Community](https://datascience.ibm.com/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link") aus.

Weitere Informationen zu den Aktualisierungen für den {{site.data.keyword.streaminganalyticsshort}}-Service enthält der Blogbeitrag [{{site.data.keyword.streaminganalyticsshort}} updates: DSX integration and easier Python development](https://www.ibm.com/blogs/bluemix/2017/05/streaming-analytics-updates-dsx-integration-easier-python-development/){: new_window} ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link").

### Aktualisierungen für {{site.data.keyword.sparks}}: Apache Spark 2.1 wird jetzt unterstützt
Datum der Neuerung: 21. April 2017

Für {{site.data.keyword.sparkl}} wird die Unterstützung von Apache Spark 2.1 zur Erstellung von Algorithmen eingeführt, die Einblicke in komplexe Daten ermöglichen. Apache Spark 2.1 hilft erheblich beim strukturierten Streaming durch die hinzugefügte Unterstützung von Ereigniszeitwasserzeichen und von Kafka 10. Schwerpunkt von Apache Spark 2.1 ist auch eine zunehmende Stabilität und Nutzbarkeit in Spark SQL, SparkR und den MLlib-Modulen. Weitere Details über Spark 2.1 finden Sie auf der Seite [Spark Release 2.1.0](http://spark.apache.org/releases/spark-release-2-1-0.html).

Ihre Fragen zu {{site.data.keyword.sparkl}} oder zur neueren Version Apache Spark 2.1 sind uns unter der Adresse  'sparksrv@us.ibm.com' jederzeit willkommen.

### {{site.data.keyword.macm_short}} wird nicht weiterentwickelt
Datum der Neuerung: 18. April 2017

Mit Wirkung zum 30. März 2017 wird die Kachel für den {{site.data.keyword.macm_long}}-Service aus dem {{site.data.keyword.Bluemix_notm}}-Katalog entfernt; Sie können dann keine neuen MACM-Instanzen mehr bereitstellen. Vorhandene Instanzen werden jedoch weiterhin unterstützt. Die Unterstützung endet am 30. März 2018. Bitte löschen Sie Ihre Serviceinstanzen für {{site.data.keyword.macm_short}} (MACM) vor dem Ende der Unterstützung. Benutzern wird die Migration auf IBM Watson Content Hub empfohlen. Watson Content Hub ist bei IBM Marketplace verfügbar und wird Benutzern im Rahmen eines 30-tägigen kostenlosen Tests zur Verfügung gestellt. IBM Watson Content Hub bietet eine ähnliche Funktionalität wie MACM, die durch neue Funktionen wie das Asset-Management, das kognitive Tagging mithilfe von IBM Watson-Services und einem integrierten Netz zur Bereitstellung von Inhalten (Content Delivery Network, CDN) ergänzt wird, um eine optimale Funktionalität für Ihre Kunden zu gewährleisten. IBM bietet Services, die zur Migration von Inhalt aus MACM auf Watson Content Hub eingesetzt werden können.


### Aktualisierungen für {{site.data.keyword.sparks}}: Unterstützung von Notizbüchern in Data Science Experience jetzt verfügbar
Datum der Neuerung: 11. April 2017

Ihre neue Plattform arbeitet mit Notizbüchern; Spark verwendet Data Science Experience. Wenn Sie sich für [Data Science Experience](http://datascience.ibm.com/) registrieren, können Sie eigene Notizbücher erstellen und Ihre Erfahrungen mit anderen Data-Scientists austauschen.

Falls Sie in {{site.data.keyword.sparks}} bereits mit Notizbüchern gearbeitet haben, können Sie Ihre Notizbücher auf Data Science Experience migrieren. Weitere Informationen finden Sie unter [Dokumentation in Notizbüchern migrieren](/docs/services/AnalyticsforApacheSpark/index-gentopic2.html#migration_to_dsx).


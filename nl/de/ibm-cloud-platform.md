---


copyright:
  years: 2016, 2018
lastupdated: "2018-11-30"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# Was ist die {{site.data.keyword.Bluemix_notm}}-Plattform?
{: #whatis}

Die Cloud-Plattform von IBM stellt durch die Kombination von 'Platform as a Service' (PaaS) mit 'Infrastructure as a Service' (IaaS) eine integrierte Erfahrung bereit. Die Plattform passt sich an die Dimensionierung an und unterstützt sowohl kleine Entwicklungsteams und Organisationen als auch große Unternehmen. Mit der globalen Bereitstellung in Rechenzentren auf der ganzen Wert gewinnt die von Ihnen auf {{site.data.keyword.cloud}} aufgebaute Lösung rasch an Dynamik und funktioniert zuverlässig in einer getesteten und unterstützten Umgebung, der Sie vertrauen können.
{: .shortdesc}

Die {{site.data.keyword.Bluemix_notm}}-Plattform setzt sich aus mehreren Komponenten zusammen, die durch ihre Zusammenarbeit ein konsistentes und zuverlässiges Cloud-Erlebnis bieten. 

  * Ein Katalog, der Hunderte von {{site.data.keyword.Bluemix_notm}}-Angeboten umfasst
  * Eine robuste Konsole, die als Front-End für das Erstellen, Anzeigen und Verwalten Ihrer Cloud-Ressourcen dient
  * Eine Komponente für Identitäts- und Zugriffsmanagement, die Benutzer für beide Plattformservices sicher authentifiziert und den Zugriff auf Ressourcen in der Gesamtheit von {{site.data.keyword.Bluemix_notm}} einheitlich steuert
  * Ein Such- und Taggingmechanismus zum Filtern und Identifizieren Ihrer Ressourcen
  * Ein Konto- und Abrechnungsverwaltungssystem, das die genaue Verwendung von Preisstrukturplänen (Preistarifen) zur Verfügung stellt und Schutz vor Kreditkartenbetrug bietet

## Hosting-Umgebung auswählen
{: #choose-compute}

Mit {{site.data.keyword.Bluemix_notm}} müssen Sie keine hohen Investitionen mehr in Hardware tätigen, um eine neue App zu testen oder zu betreiben. Stattdessen übernehmen wir die gesamte Verwaltung für Sie und berechnen nur das, wovon Sie tatsächlich Gebrauch machen. Ihre Cloud-Server-Umgebung ist die Basis Ihrer Infrastrukturebene. Sie können eine einzelne Option oder aber eine Kombination für komplexere Umgebungen auswählen. 

Für das Hosting Ihrer Apps stehen Ihnen diverse Möglichkeiten offen, wodurch Sie genau so viel Kontrolle über die Infrastruktur erhalten, wie Sie wünschen oder wie erforderlich ist. Sie können Ihre App auf eine der folgenden Arten ausführen: 

  * Als serverlose Funktion
  * Als Cloud Foundry-App
  * Als Docker-Container in einem Kubernetes-Cluster
  * Als VMware
  * Als virtuelle Maschine (VM)
  * Auf leistungsfähigen {{site.data.keyword.baremetal_short}}-Instanzen 

Bei {{site.data.keyword.baremetal_short}} handelt es sich um physische Server mit einem Tenant, die für einen einzelnen Kunden bestimmt sind. Sie steuern fast alles, angefangen beim Server-Host bis zum Arbeitsspeicher und den Speichergeräten. Diese Server werden mit Workloads verwendet, die Rechenleistungen über einen längeren Zeitraum von beispielsweise mehreren Monaten erfordern. 

{{site.data.keyword.BluVirtServers_short}}-Instanzen können als öffentliche oder als dedizierte Instanzen bereitgestellt werden. Bei öffentlichen Instanzen werden die Ressourcen des Servers gemeinsam mit mit anderen Kunden geteilt. Daher spricht man in diesem Kontext von einer Multi-Tenant-Umgebung. Bei privaten Instanzen werden die Ressourcen des physischen Servers einem Kunden zugewiesen, der eine oder mehrere virtuelle Maschinen auf demselben Server haben kann. Diese Server sind ideal für Workloads, die für eine begrenzte Zeit, beispielsweise einige Wochen, ausgeführt werden. Einige Beispiele für Workloads sind Entwicklung und Test, Sicherung und Wiederherstellung sowie Notfallwiederherstellung (Disaster Recovery). Weitere Informationen zu den Serveroptionen finden Sie in [Bare-Metal-Server vs. virtuelle Server: Auswahl der besten Option für Sie](https://www.ibm.com/blogs/bluemix/2018/06/bare-metal-virtual-servers-works/){: new_window} ![Symbol für externen Link](../icons/launch-glyph.svg "Symbol für externen Link").

Die folgende Tabelle enthält eine Zusammenfassung Ihrer Berechnungsoptionen.

| Option | Beschreibung | 
|--------|---------------|
| [{{site.data.keyword.baremetal_short}}](/docs/bare-metal/about.html)  | Stündliche oder monatliche Berechnung von Servern mit einem einzigen Tenant, die Ihnen zugeordnet sind und in keiner Hinsicht (einschließlich Serverressourcen) gemeinsam mit anderen Kunden genutzt werden. |
| [{{site.data.keyword.BluVirtServers_short}}](/docs/vsi/vsi_about.html) | Skalierbare virtuelle Server, die mit dedizierten Cores und Hauptspeicherzuordnungen gekauft werden. |
| [{{site.data.keyword.vmwaresolutions_short}}](/docs/services/vmwaresolutions/vmonic/prod_overview.html) | Ermöglicht die rasche und nahtlose Integration oder Migration von lokalen VMware-Workloads mithilfe einer skalierbaren, sicheren und leistungsstarken Infrastruktur und der branchenweit führenden Technologie für Hybridvirtualisierung von VMware. |
| [{{site.data.keyword.containerlong_notm}}](/docs/containers/cs_why.html) | Kombiniert Docker-Container, die Kubernetes-Technologie, ein intuitives Benutzererlebnis sowie integrierte Sicherheit und Isolation, um die Bereitstellung, den Betrieb, die Skalierung und die Überwachung containerisierter Apps in einem Cluster von Rechenhosts zu automatisieren. |
| [{{site.data.keyword.cfee_full_notm}}](/docs/cloud-foundry/index.html) | Ermöglicht die bedarfsgesteuerte Instanziierung mehrerer isolierter, auf Unternehmen abgestimmter Cloud Foundry-Plattformen. |
| [{{site.data.keyword.openwhisk_short}}](/docs/openwhisk/index.html) | Eine 'Functions-as-a-Service'-Programmierungsplattform (FaaS), die auf Apache OpenWhisk basiert. |
{: caption="Tabelle 1. Berechnungsoptionen" caption-side="top"}

## Anwendungen erstellen
{: #build-apps}

Unabhängig davon, ob Sie über [vorhandenen Code](/docs/apps/tutorials/tutorial_byoc.html) verfügen, den Sie modernisieren und in die Cloud integrieren möchten, oder ob Sie eine [völlig neue Anwendung](/docs/apps/tutorials/tutorial_starter-kit.html) entwickeln, können sich Ihre Entwickler können das rasch wachsende Ökosystem verfügbarer Services und Laufzeitframeworks in {{site.data.keyword.Bluemix_notm}} zunutze machen.

Für jede Sprache stehen [Programmierungsanleitungen](https://cloud.ibm.com/docs/home/build){: new_window} ![Symbol für externen Link](../icons/launch-glyph.svg "Symbol für externen Link") zur Verfügung, die Ihnen dabei helfen, Ihr Ziel möglichst rasch umzusetzen. Ihnen stehen zahlreiche Optionen vom Hosting Ihrer Apps mit {{site.data.keyword.Bluemix_notm}}-Infrastruktur von {{site.data.keyword.baremetal_short}} bis zu ihrer Ausführung als serverlose Funktion zur Verfügung.

## Services verbinden
{: #connect-services}

Mit einem Angebot von über 190 Services, die im Katalog zur Auswahl stehen, können Sie eine individuell angepasste Lösung für Ihre speziellen Anforderungen erstellen. Sie können Services auch problemlos mit Apps außerhalb von {{site.data.keyword.Bluemix_notm}} verbinden, wenn dies zu Ihrem Anwendungsfall passt. Sie können eine neue Gruppe von Berechtigungsnachweisen für die Fälle generieren, in denen Sie einen externen Konsumenten manuell mit einem {{site.data.keyword.Bluemix_notm}}-Service verbinden möchten. Wenn Sie beispielsweise versuchen, eine App außerhalb von {{site.data.keyword.Bluemix_notm}} mit einem Watson-Service zu verbinden, müssen Sie einen neuen Berechtigungsnachweis generieren, mit dem App und Service miteinander verbunden werden. So einfach ist das. Weitere Informationen enthält [Berechtigungsnachweis hinzufügen](/docs/resources/service_credentials.html#service_credentials).

## Konto einrichten

Wenn Sie {{site.data.keyword.Bluemix_notm}} einfach nur ausprobieren, können Sie direkt den Katalog aufsuchen und sich mit denjenigen Services näher befassen, die Sie erkunden und zu Ihrem Test- oder Lite-Konto hinzufügen wollen. Wenn Sie jedoch bereit sind, mit einer Umgebung für eine Gruppe von Entwicklern oder für eine ganze Organisation loszulegen und Apps bis zur Reife für ihre Ausführung im Produktionsbetrieb zu bringen, sollten Sie in Ihrem Konto die wichtigsten Basisdaten einrichten:

* Benutzerzugriffsgruppen zum Organisieren von Benutzern und Service-IDs in einer einzigen Entität, damit die Zuweisung des Zugriffs in einem optimierten Prozess erfolgen kann.
* Ressourcengruppen zum Organisieren Ihrer Ressourcen, um die Zuweisung von Zugriff auf eine Gruppe von Ressourcen möglichst schnell und einfach zu gestalten.
* Zugriffsrichtlinien für Ihre Zugriffsgruppen oder für einzelne Entwickler, die IAM-Zugriffsrichtlinien oder die Cloud Foundry-Rollen 'org' und 'space' benötigen.

Weitere Informationen können Sie unter [Bewährte Verfahren für das Einrichten Ihres Kontos](/docs/account/bp_account.html#account_setup) und [Bewährte Verfahren für die Zuweisung von Zugriff](/docs/iam/bp_access.html) nachlesen. Wenn Sie bereit sind, den Sprung zu wagen, prüfen Sie die einzelnen Teile und Komponenten der [Kontohierarchie](/docs/account/account_overview.html#overview).

## Preisstruktur und Abrechnung

Unabhängig von Ihrem Kontotyp können Sie {{site.data.keyword.Bluemix_notm}} unter Verwendung von Lite-Plänen für diejenigen Services erkunden, die kostenfreie Kontingente bereitstellen. Wenn Sie sich für einen Service aus dem Katalog entscheiden und eine Kachel auswählen, werden Details der Preisinformationen angezeigt, sofern verschiedene Typen von Plänen angeboten werden. Wenn Sie über einen gebührenpflichtigen Plan verfügen und einen Serviceplan auswählen, können Sie die voraussichtlich anfallenden Kosten mit der Kostenschätzungsfunktion schätzen lassen. Weitere Informationen enthält [Kosten schätzen](/docs/billing-usage/estimating_costs.html#cost).


Die Abrechnung mit {{site.data.keyword.Bluemix_notm}} stellt mehrere Services bereit, mit denen sichergestellt wird, dass die {{site.data.keyword.Bluemix_notm}}-Plattform Preisstrukturen, Konten, Nutzung und vieles mehr sicher verwalten kann.

### {{site.data.keyword.Bluemix_notm}}-Kontoverwaltung
{: #account}

Die Kontoverwaltung sorgt für die Pflege der Rechnungsbeziehung mit dem Kunden. Jedes Konto ist eine Abrechnungseinheit, die einen Kunden darstellt. Dieser Service steuert den Lebenszyklus des Kontos, das Kontoabonnement, die Kontobenutzerbeziehung und die Kontoorganisation.

### {{site.data.keyword.Bluemix_notm}}-Preisstruktur
{: #pricing}

Der Plattformservice für die {{site.data.keyword.Bluemix_notm}}-Preisstruktur hilft Benutzern, Preisinformationen für Ressourcen im {{site.data.keyword.Bluemix_notm}}-Katalog zu definieren, zu verwalten und abzurufen.

### Collector für {{site.data.keyword.Bluemix_notm}}-Messung
{: #metering}

Die {{site.data.keyword.Bluemix_notm}}-Nutzungsüberwachung ist ein Plattformservice, mit dem Service-Provider Metriken übermitteln können, die für von {{site.data.keyword.Bluemix_notm}}-Benutzern bereitgestellte Ressourceninstanzen erfasst werden. Drittanbieter, die einen integrierten Abrechnungsservice in {{site.data.keyword.Bluemix_notm}} bereitstellen, sind dazu verpflichtet, die Nutzung für alle aktiven Serviceinstanzen stündlich einzureichen. Die Übermittlung ist wichtig, denn wenn es nicht möglich ist, die Nutzung zu melden, kann dies zu Umsatzeinbußen bei IBM führen, was wiederum zu einem Verlust des Umsatzanteils für den Drittanbieter führt.

## {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM)
{: #iam}

{{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) ermöglicht Ihnen die sichere Authentifizierung von Benutzern für Plattformservices und die einheitliche Steuerung des Zugriffs auf Ressourcen innerhalb der {{site.data.keyword.Bluemix_notm}}-Plattform. Weitere Informationen enthält [Was ist IAM?](/docs/iam/index.html) IAM stellt CLI-Befehle und APIs bereit, die Sie bei der Verwaltung von Token, Zugriffsgruppen und Richtlinien unterstützen.


## Ressourcen erstellen
{: #provisioning-layer}

Der Ressourcencontroller ist die {{site.data.keyword.Bluemix_notm}}-Plattformbereitstellungsebene der nächsten Generation, die den Lebenszyklus von {{site.data.keyword.Bluemix_notm}}-Ressourcen in einem Kundenkonto verwaltet. Ressourcen werden global im Gültigkeitsbereich eines Kontos bereitgestellt. Der Ressourcencontroller unterstützt sowohl die synchrone als auch die asynchrone Bereitstellung von Ressourcen. Die Bereitstellungsebene ist für die Steuerung und Überwachung des Lebenszyklus von Ressourcen in einem Kundenkonto verantwortlich. Bei Ressourcen handelt es sich um physische und logische Komponenten, die für eine Anwendung oder eine Serviceinstanz bereitgestellt oder reserviert werden können. Beispiele für Ressourcen sind unter anderem Datenbanken und Konten, Prozessoren, Speicher und Speichergrenzwerte. Im Allgemeinen dienen Ressourcen, die in der Bereitstellungsebene überwacht werden, der Zuordnung von Nutzungsmetriken und Abrechnungen, dies ist jedoch nicht zwingend erforderlich. In bestimmten Fällen kann die Ressource der Bereitstellungsebene zugeordnet werden, um sicherzustellen, dass der Lebenszyklus der Ressource zusammen mit dem Lebenszyklus des Kontos verwaltet werden kann. Der Ressourcencontroller verwendet IAM für die Authentifizierung und und Autorisierung von Aktionen, die für die Bereitstellungsebene ausgeführt werden.

### Verwaltung des Lebenszyklus von Ressourcen
{: #lifecycle}

Der Ressourcencontroller stellt allgemeine APIs zur Verfügung, mit denen der Lebenszyklus von Ressourcen von der Bereitstellung (Instanzerstellung) über die Bindung (Erstellung der Zugriffsberechtigungsnachweise) und die Aufhebung der Bindung (Entfernung des Zugriffs) bis hin zur Aufhebung der Bereitstellung (Instanzlöschung) gesteuert werden kann.

Der Ressourcencontroller stellt APIs zur Verfügung, die Ihnen bei der Verwaltung der folgenden Elemente im Lebenszyklus von Ressourcen unterstützen:
* Bereitstellung
* Aktualisierung einer Ressourceninstanz
* Bindung
* Ressourcenschlüssel
* Aufhebung der Bindung
* Aufhebung der Bereitstellung


## Ressourcen verwalten
{: #resource-manager}


Der Ressourcenmanager von {{site.data.keyword.Bluemix_notm}} verwaltet die Gruppe der Ressourcen anhand von [Ressourcengruppen](/docs/overview/resource-groups.html#whatis). Eine Ressourcengruppe gehört zu einenm Konto. Alle {{site.data.keyword.Bluemix_notm}}-Ressourcen müssen innerhalb einer Ressourcengruppe bereitgestellt werden. Wenn ein Account ausgesetzt wird, so wird die entsprechende Ressourcengruppe ebenfalls ausgesetzt und alle Ressourcen in dieser Ressourcengruppe werden auch ausgesetzt. Wenn ein Benutzer ein Konto erstellt, wird in dem Konto eine Standardressourcengruppe erstellt. Alle Ressourcen, die für {{site.data.keyword.Bluemix_notm}} IAM aktiviert sind, müssen innerhalb einer Ressourcengruppe bereitgestellt werden. Wenn ein Account ausgesetzt wird, so wird die entsprechende Ressourcengruppe ebenfalls ausgesetzt und alle Ressourcen in dieser Ressourcengruppe werden auch ausgesetzt. Bei einem Standardkonto kann der Benutzer nur über eine Ressourcengruppe verfügen. Bei einem nutzungsabhängigen Konto oder einem Abonnementkonto kann Benutzer mehrere Ressourcengruppen erstellen. 


## {{site.data.keyword.Bluemix_notm}}-Katalog
{: #catalog}

Der {{site.data.keyword.Bluemix_notm}}-Katalog dient zur Speicherung der Angebotsdefinitionen (Beschreibung, Funktionen, Bilder, URLs usw.) der Ressourcen, die an der {{site.data.keyword.Bluemix_notm}}-Konsole angezeigt werden. Der Katalogservice verwaltet Angebote länderübergreifend als System of Record (SOR, Kerndatensystem). Der Katalog unterstützt Befehlszeilenschnittstellen (CLIs) und eine RESTful-API, in der Sie Informationen zu vorhandenen Angeboten abrufen und Angebote erstellen, verwalten und löschen können. Starten Sie mit der Basis-URL und verwenden Sie die Endpunkte, um Metadaten zu Services im Katalog abzurufen und die Sichtbarkeit von Services zu verwalten. Abhängig von der Art des jeweiligen Objekts können die Metadaten Informationen zur Preisstruktur, zur Bereitstellung, zu Regionen usw. enthalten. Weitere Informationen enthält die Dokumentation zur [Verwaltung des Katalogs](/docs/overview/catalog.html#global-catalog-overview).

## Ressourcen durchsuchen und mit Tags versehen
{: #search-and-tag}

Der Suchservice ist ein globales und gemeinsam genutztes Repository von Ressourceneigenschaften, das in die {{site.data.keyword.Bluemix_notm}}-Plattform integriert ist. Er wird zum Speichern und Durchsuchen der Attribute von Cloudressourcen verwendet. Der Suchservice kategorisiert und klassifiziert Ressourcen. Eine Ressource wird von Ressourcenprovidern innerhalb der {{site.data.keyword.Bluemix_notm}}-Plattform gesteuert, wie Cloud Foundry, IBM Containers oder Resource Controller, die ihr Eigner sind. Ressourcen werden durch eine ID zur [Cloudressourcenbenennung](/docs/overview/crn.html#crn) (Cloud Resource Name, CRN) eindeutig angegeben. Zu den Eigenschaften einer Ressource gehören Tags und Systemeigenschaften. Beide Eigenschaften werden in einem {{site.data.keyword.Bluemix_notm}}-Abrechnungskonto definiert und erstrecken sich über zahlreiche Regionen.

Dieser Service verwaltet auch Tags, die einer Ressource zugeordnet sind. Tags können mit der Anwendungsprogrammierschnittstelle (API) für Tagging erstellt, gelöscht, gesucht, angehängt und abgehängt werden. Tags werden durch eine ID zur Cloudressourcenbenennung (Cloud Resource Naming, CRN) eindeutig angegeben. Tags besitzen einen Namen, der innerhalb eines Abrechnungskontos eindeutig sein muss. Sie können Tags im Format `schlüssel:wert` oder als Bezeichnung erstellen.


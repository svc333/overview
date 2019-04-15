---

copyright:
  years: 2018, 2019
lastupdated: "2019-03-14"

keywords: cloud environment, virtual server, virtual machine, vm, understanding infrastructure, IaaS model

subcollection: overview


---
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}
{:tip: .tip}
{:note: .note}

# Informationen für Administratoren (Ops) in {{site.data.keyword.cloud_notm}} erkunden
{: #it-ops}

Da viele Organisationen zu einer Cloudumgebung wechseln, die entweder lokal oder in Rechenzentren gehostet wird, ergibt sich eine Neudefinition der Rolle des Administrators für den IT-Betrieb. Der Umfang und die Komplexität dieses Wandels nimmt je nach der Art von Umgebung, die Ihre Organisation bereitstellen möchte, erheblich zu. 
{: .shortdesc}

Vor dem Wechsel zur Cloud haben Sie in einer inhärent sicheren Umgebung mit Systemen gearbeitet, die mit Ihrem privaten LAN oder Intranet verbunden sind. In einer Cloud-Umgebung wird von Ihnen nun die Ausführung der folgenden Tasks erwartet:
 
  * Beschaffen Ihrer Systemkomponenten von 'irgendwoher' 
  * Verstehen der Auswirkungen auf das Netz und der Sicherheitsrisiken
  * Arbeiten mit unterschiedlichen Technologien  
  * Integrieren der neuen Umgebung mit Tools, die nicht nativer Bestandteil des Cloud-Stacks sind 
  * Fortsetzen der Unterstützung Ihrer internen Kunden, als würden Sie noch über ein lokale Rechenzentrum verfügen

{{site.data.keyword.cloud}} unterstützt Sie zu 100% auf Ihrer Reise. Zu den Ressourcen, die Ihnen zur Verfügung stehen, gehören unter anderem umfassende Dokumentation, Planungstools, qualifizierte Systemberater und eine aktive Benutzercommunity. Lassen Sie uns hier mit Ihrer Reise beginnen. 

## Grundlagen verstehen
{: #basics}

### Cloud-Service-Modelle
{: #cloud-svc-models}

Es gibt drei Arten von Cloud-Service-Modellen: 'Infrastructure as a Service' (IaaS), 'Platform as a Service' (PaaS) und 'Software as a Service' (SaaS). Abbildung 1 erläutert, wer in den einzelnen Servicemodellen für was zuständig ist. Weitere Informationen enthält der Abschnitt [IaaS, PaaS und SaaS - Modelle des IBM Cloud-Service](https://www.ibm.com/cloud/learn/iaas-paas-saas){: new_window} ![Symbol für externen Link](../icons/launch-glyph.svg "Symbol für externen Link").

![Abbildung 1. Cloud-Service-Modelle](images/cloud-svc-models.png "Cloud-Service-Modelle")

Beim IaaS-Modell ist Ihr Provider lediglich für die Wartung der zugrunde liegenden Infrastruktur und die optionale Installation von Software wie Betriebssystemen, Anwendungen und Datenbanken verantwortlich. Sie selbst haben eingeschränkt Zugriff auf die zugrunde liegende Infrastruktur und Sie sind für die Installation Ihrer Software oder für ihre Installation durch Ihren Service-Provider zuständig. Außerdem sind Sie für alle anderen Wartungsarbeiten verantwortlich, was Service-Packs, Virensoftware und Patches einschließt.

Beim PaaS-Modell ist Ihr Provider über das Betriebssystem für die Systeme und für das gesamte Infrastrukturmanagement verantwortlich, was Betriebssystempatches, Reparaturen der Hardware und Netzeinstellungen einschließt. Sie selbst erstellen und warten die Anwendung und Sie oder Ihr Provider können Middleware (einschließlich Datenbanken oder anderer Typen) installieren. Dieses Modell wird zum Entwickeln und Testen von Software verwendet. Weitere Informationen enthält die [praktische Anleitung zu Platform as a Service: Was ist PaaS? ![Symbol für externen Link](../icons/launch-glyph.svg "Symbol für externen Link")](https://www.ibm.com/blogs/cloud-computing/2016/08/10/practical-guide-paas/){: new_window}

Beim SaaS-Modell verwaltet Ihr Anbieter die Systeme über die eigentliche Anwendung. Die Anwendung erkennt die Cloud und Benutzer können je nach Softwareanbieter unterschiedliche Endpunkte zur Verwendung der Software verwenden. Der Cloud-Provider ist für das gesamte Infrastruktur- und Anwendungsmanagement verantwortlich, was Software-Updates, Reparaturen der Hardware und Netzeinstellungen einschließt. Dieses Modell wird häufig bei nutzungsabhängigen Modellen für die Softwarelizenzierung verwendet. Weitere Informationen enthält [SaaS-Anwendungen für Unternehmen und IT](https://www.ibm.com/cloud/saas){: new_window} ![Symbol für externen Link](../icons/launch-glyph.svg "Symbol für externen Link").

### Cloudtypen
{: #cloud-types}

Es gibt drei verschiedene Typen von Clouds: öffentliche Clouds, private Clouds und Hybridclouds. Eine öffentliche Cloud umfasst eine gemeinsam genutzte Gruppe von Ressourcen, die bereitgestellt werden, um den Zugriff auf die Ressourcen eines Unternehmens zu ermöglichen. Eine solche Cloud wird in einer Multi-Tenant-Umgebung per Hosting auf einem virtuellen Server bereitgestellt und der Zugriff auf sie ist standortunabhängig möglich. 

Eine private Cloud umfasst Ressourcen, die bereitgestellt werden, um den Zugriff auf die Ressourcen eines Unternehmens zu ermöglichen. Sie wird auf dedizierter Hardware, beispielsweise einem Bare-Metal-Server, per Hosting bereitgestellt, und zwar entweder lokal in der Geschäftsstelle des Unternehmens (oder geschäftsstellenübergreifend) oder von einem Cloud-Anbieter. Der Zugriff auf eine private Cloud ist standortunabhängig möglich.

Eine Hybridcloud umfasst Ressourcen, die die Aspekte von öffentlichen und privaten Clouds miteinander kombinieren. Sie wird sowohl lokal in der Geschäftsstelle eines Unternehmens (oder geschäftsstellenübergreifend) als auch von einem Cloud-Anbieter per Hosting bereitgestellt. Der Zugriff auf eine Hybridcloud ist standortunabhängig möglich. 

## Infrastruktur planen
{: #planning}

Vor der Bereitstellung sollten Sie Ihre Infrastruktur planen, um sicherzustellen, dass Sie sie für Ihre Workload angemessen dimensionieren. {{site.data.keyword.cloud_notm}} verfügt über mehrere Tools und Sites, die Sie bei der Gestaltung und Dimensionierung Ihrer Infrastruktur unterstützen. 

### Architektur der Infrastruktur

Starten Sie mit der [Architektur der Infrastruktur ![Symbol für externen Link](../icons/launch-glyph.svg "Symbol für externen Link")](https://www.ibm.com/cloud/garage/architectures/infrastructure){: new_window}, um sich einen ausführlicheren Überblick über die drei Typen von Cloudumgebung zu verschaffen. 

### {{site.data.keyword.cloud_notm}} Design Decision Tool

Das [{{site.data.keyword.cloud_notm}} Design Decision Tool ![Symbol für externen Link](../icons/launch-glyph.svg "Symbol für externen Link")](https://github.com/ibm-cloud-architecture/infrastructure-design-decision-tool/){: new_window} hilft Ihnen beim Vergleichen von Alternativen, wenn Sie Ihre angepasste Lösung entwerfen und erstellen. Für jede Infrastrukturkomponente werden eine Beschreibung, Hinweise und Vorbehalte sowie direkte Vergleiche aufgeführt. Außerdem wird anhand eines Beispiels veranschaulicht, wie die Verwendung des Tools erfolgt.

### {{site.data.keyword.cloud_notm}} Stencils

[{{site.data.keyword.cloud_notm}} Stencils ![Symbol für externen Link](../icons/launch-glyph.svg "Symbol für externen Link")](https://github.com/ibm-cloud-architecture/ibm-cloud-stencils){: new_window} hilft Ihnen beim Erstellen eines Diagramms Ihrer {{site.data.keyword.cloud_notm}}-Architektur anhand von gängigen Diagrammtools. 

### Bare-Metal-Server-Optionen

Verwenden Sie das [{{site.data.keyword.cloud_notm}} {{site.data.keyword.baremetal_short}}-Suchtool ![Symbol für externen Link](../icons/launch-glyph.svg "Symbol für externen Link")](https://www.ibm.com/cloud-computing/bluemix/bare-metal-search){: new_window}, um Ihre Bare-Metal-Server-Optionen einschließlich Servern, die für die Unterstützung von SAP HANA- und SAP NetWeaver-Workloads zertifiziert sind, zu dimensionieren und zu schätzen.

### {{site.data.keyword.cloud_notm}}-Services und Compliance

Wie bei jeder Architektur sollten Sie die {{site.data.keyword.cloud_notm}}-Ressourcen berücksichtigen, die Sie möglicherweise zu Ihrer Lösung hinzufügen, wenn Sie Ihre Infrastruktur dimensionieren. Weitere Informationen erhalten Sie, wenn Sie [SaaS-Anwendungen für Unternehmen und IT ![Symbol für externen Link](../icons/launch-glyph.svg "Symbol für externen Link")](https://www.ibm.com/cloud/saas){: new_window} nach einem bestimmten Service durchsuchen. Außerdem müssen Sie an alle Verordnungen denken, die Sie beim Erstellen Ihrer Architektur beachten müssen. Dazu gehört zum Beispiel die Frage, ob Ihre Workload als vertraulich gilt oder besonderen Bestimmungen unterliegt. Weitere Informationen finden Sie in [Compliance ![Symbol für externen Link](../icons/launch-glyph.svg "Symbol für externen Link")](https://www.ibm.com/cloud/compliance){: new_window}.

## Infrastruktur erstellen
{: #build}

Nachdem Sie Ihre Infrastruktur geplant und entworfen haben, können Sie sie nun erstellen. 

### Berechnung
{: #compute}

Ihr Server ist die Basis Ihrer Infrastruktur. Je nach Ihren Anforderungen stehen Ihnen unterschiedliche Optionen offen. Diese können Sie miteinander kombinieren, falls dies Ihre Umgebung erfordert. Die folgende Tabelle enthält eine Zusammenfassung Ihrer Berechnungsoptionen.

| Option | Beschreibung | 
|--------|---------------|
| [{{site.data.keyword.baremetal_short}}](/docs/bare-metal?topic=bare-metal-getting-started)  | Stündliche oder monatliche Berechnung von Servern mit einem einzigen Tenant, die Ihnen zugeordnet sind und in keiner Hinsicht (einschließlich Serverressourcen) gemeinsam mit anderen Kunden genutzt werden. |
| [{{site.data.keyword.BluVirtServers_short}}](/docs/vsi?topic=virtual-servers-about-public-virtual-servers#public-virtual-servers) | Skalierbare virtuelle Server, die mit dedizierten Cores und Hauptspeicherzuordnungen gekauft werden. |
| [{{site.data.keyword.vmwaresolutions_short}}](/docs/services/vmwaresolutions?topic=vmware-solutions-getting-started#getting-started) | Ermöglicht die rasche und nahtlose Integration oder Migration von lokalen VMware-Workloads mithilfe einer skalierbaren, sicheren und leistungsstarken Infrastruktur und der branchenweit führenden Technologie für Hybridvirtualisierung von VMware. |
| [{{site.data.keyword.containerlong_notm}}](/docs/containers?topic=containers-container_index) | Kombiniert Docker-Container, die Kubernetes-Technologie, ein intuitives Benutzererlebnis sowie integrierte Sicherheit und Isolation, um die Bereitstellung, den Betrieb, die Skalierung und die Überwachung containerisierter Apps in einem Cluster von Rechenhosts zu automatisieren. |
| [{{site.data.keyword.cfee_full_notm}}](/docs/cloud-foundry?topic=cloud-foundry-about) | Ermöglicht die bedarfsgesteuerte Instanziierung mehrerer isolierter, auf Unternehmen abgestimmter Cloud Foundry-Plattformen. |
| [{{site.data.keyword.openwhisk_short}}](/docs/openwhisk?topic=cloud-functions-index) | Eine 'Functions-as-a-Service'-Programmierungsplattform (FaaS), die auf Apache OpenWhisk basiert. |
{: caption="Tabelle 1. Berechnungsoptionen" caption-side="top"}
   
### Speicher
{: #storage}

{{site.data.keyword.baremetal_short}} und {{site.data.keyword.BluVirtServers_short}} werden mit Standardspeicher bereitgestellt. {{site.data.keyword.baremetal_short}} verfügen über mindestens 1 TB SATA-Speicher und {{site.data.keyword.BluVirtServers_short}} über mindestens 25 GB SAN-Speicher. Eine Ausnahme hiervon bilden die von SAP zertifizierten {{site.data.keyword.baremetal_short}} für {{site.data.keyword.cloud_notm}}. Weitere Informationen zu dem mit diesen Servern verfügbaren Standardspeicher enthält [Von SAP zertifizierte {{site.data.keyword.cloud_notm}}-Infrastruktur](/docs/bare-metal?topic=bare-metal-ibm-cloud-sap-certified-infrastructure).

Je nach Ihren Bedürfnissen können Sie zusätzlichen Speicher erwerben. Die folgende Tabelle enthält eine Zusammenfassung Ihrer Berechnungsoptionen.

| Option | Beschreibung |
|--------|---------------|
| [{{site.data.keyword.blockstorageshort}}](/docs/infrastructure/BlockStorage/index.html) | Persistenter iSCSI-Speicher mit hoher Leistung, der unabhängig von Recheninstanzen bereitgestellt und verwaltet wird. iSCSI-basierte LUNs sind über redundante MPIO-Verbindungen (MPIO - Multipath I/O) mit autorisierten Geräten verbunden. |
| [{{site.data.keyword.filestorage_short}}](/docs/infrastructure/FileStorage/index.html) | Persistenter, schneller und flexibler NFS-basierter NAS-Dateispeicher. In dieser NAS-Umgebung (NAS - Network-Attached Storage) verfügen Sie über die vollständige Kontrolle über die Dateifreigabefunktion und die Leistung. Dateispeicherfreigaben können über TCP/IP-Routingverbindungen für bis zu 64 berechtigte Geräte verfügbar gemacht werden, um die Ausfallsicherheit sicherzustellen. |
| [{{site.data.keyword.cos_full_notm}}](/docs/services/cloud-object-storage?topic=cloud-object-storage-getting-started-console-) | Mit IBM Cloud Object Storage gespeicherte Informationen werden verschlüsselt und über mehrere geografische Standorte verteilt. Der Zugriff erfolgt mithilfe einer REST-API über HTTP. Dieser Service verwendet die verteilten Speichertechnologien, die von IBM Cloud Object Storage System (ehemals Cleversafe) bereitgestellt werden. |
| Massendatenmigration mit [{{site.data.keyword.cloud_notm}}](/docs/infrastructure/mass-data-migration/index.html) | Lagern Sie große Datenmengen vom Ihrem lokalen Rechenzentrum in den Cloud Object Storage-Bucket aus. |
| [{{site.data.keyword.backup_full}}](/docs/infrastructure/Backup/index.html) | Ein automatisiertes agentenbasiertes Sicherungssystem, das über ein browserbasierte Verwaltungsdienstprogramm verwaltet wird. Sie können Daten auf Servern in einem oder mehreren Rechenzentren im IBM Cloud-Netz sichern. |
{: caption="Tabelle 2. Speicheroptionen" caption-side="top"}

### Vernetzung
{: #network}

Wenn Ihr {{site.data.keyword.cloud_notm}}-Konto eingerichtet ist, erhalten Sie automatisch Anbindung an {{site.data.keyword.vpn_full}}. Standardmäßig verfügt Ihr Server über eine öffentliche IP-Adresse und über eine private IP-Adresse. Wenn Sie wünschen, dass Ihr Server privat ist, können Sie nach der Bereitstellung und Einrichtung Ihres Servers die öffentliche Schnittstelle inaktivieren oder aber den Server als privat bestellen. Weitere Informationen enthält [Einführung in die Arbeit mit VPN (Virtual Private Networking)](/docs/infrastructure/iaas-vpn?topic=VPN-getting-started-with-virtual-private-networking-vpn-).

<!-- begin staging only -->
Innerhalb der Infrastrukturebene können Sie eine virtuelle private Cloud erstellen, d. h. ein virtuelles Netz, das an Ihr {{site.data.keyword.cloud_notm}}-Konto gebunden ist. Eine virtuelle private Cloud bietet Ihnen einen Eingangspunkt, der Cloud-Sicherheit und die Möglichkeit der dynamischen Skalierung Ihrer Virtual Server-Instanzen (VSIs) bietet. Weitere Informationen finden Sie in [Einführung in IBM Cloud Virtual Private Cloud (VPC) Infrastructure](/docs/vpc/vpc-getting-started-with-ibm-cloud-virtual-private-cloud-infrastructure). 
<!-- end staging only -->

Die folgende Tabelle enthält eine Zusammenfassung Ihrer Vernetzungsoptionen.

| Option | Beschreibung | 
|--------|---------------|
| [Content Delivery Network (CDN)](/docs/infrastructure/CDN?topic=CDN-getting-started) | Wird für unterschiedliche Branchenlösungen einschließlich Medien, Unterhaltung, Software, Gaming, Bankwesen und E-Commerce verwendet, um den Anforderungen Ihres Unternehmens gerecht zu werden. |
| [Domain Name Service (DNS)](/docs/cli/reference/ibmcloud?topic=cloud-cli-ibm-dev-tools-for-jetbrains) | Bietet einen zentralen Ausgangspunkt zur Anzeige und Verwaltung Ihrer Domänen über die DNS-Basismanagementschnittstelle sowie die Option, Reverse DNS und Secondary DNS über denselben Ausgangspunkt kostenfrei zu verwalten. |
| [Globale IP-Adressen](/docs/infrastructure/subnets?topic=subnets-getting-started-with-subnets-and-ips) | Bieten Flexibilität und ermöglichen Ihnen die Verlagerung von Workloads zwischen Servern, auch in geografisch getrennten Rechenzentren. |
| [Lastausgleich](/docs/infrastructure/loadbalancer-service?topic=loadbalancer-service-getting-started-with-ibm-cloud-load-balancer) | Verteilt die Verarbeitung und Kommunikation gleichmäßig auf mehrere Server innerhalb eines Rechenzentrums, sodass nicht die gesamte Arbeitslast auf einem einzelnen Gerät ruht. |
| [Virtual Router Appliance](/docs/infrastructure/virtual-router-appliance/getting-started.html) | Leitet den privaten und öffentlichen Netzwerkverkehr über einen voll ausgestatteten Unternehmensrouter mit Firewall, Regulierung des Datenverkehrs (Traffic-Shaping), richtlinienbasiertem Routing, VPN und zahlreichen anderen Funktionen selektiv weiter. |
| [IPSec-VPN](/docs/infrastructure/iaas-vpn?topic=VPN-set-up-ipsec-vpn) | Eine Suite von Protokollen zur Authentifizierung und Verschlüsselung des gesamten IP-Datenverkehrs zwischen zwei Standorten. Dabei wird ein Tunnelmodus verwendet, der ein verschlüsseltes Site-to-Site-Netz bereitstellt. |
| {{site.data.keyword.cloud_notm}} Direct Link | Nutzt einen Cloud Exchange-Anbieter, um Konnektivität an Standorten der {{site.data.keyword.cloud_notm}}-Infrastruktur bereitzustellen. |
{: caption="Tabelle 3. Vernetzungsoptionen" caption-side="top"}


## Infrastruktur verwalten
{: #managing}

Nachdem Sie Ihre Infrastruktur und Umgebung erstellt haben, können Sie mit ihrer Verwaltung beginnen.

| Task | Beschreibung |
|--------|---------------|
| [Systemereignisse überwachen](/docs/account?topic=account-audit-log) | Zeigen Sie die Aktionen an, die für Ihre Infrastrukturressourcen ausgeführt worden sind. |
| [E-Mail-Vorgaben festlegen](/docs/account?topic=account-email-prefs) | Konfigurieren Sie E-Mail-Benachrichtigungen über ungeplante Ereignisse, Wartungen und Ankündigungen für die {{site.data.keyword.cloud_notm}}-Infrastruktur.  |
| [Die Sicherheit Ihrer Daten verstehen](/docs/overview?topic=overview-security) | Die {{site.data.keyword.cloud_notm}}-Plattform besitzt geschichtete netz- und infrastrukturweite Sicherheitsmaßnahmen. |
| [Verstehen, wie Sie null Ausfallzeit sicherstellen können](/docs/overview?topic=overview-zero-downtime) | Alle {{site.data.keyword.cloud_notm}}-Ressourcen werden per Hosting in Rechenzentren auf der ganzen Welt bereitgestellt. |
{: caption="Tabelle 4. Management-Tasks" caption-side="top"}

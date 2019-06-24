---

copyright:
  years: 2018, 2019
lastupdated: "2019-06-06"

keywords: HA, failover, DR, high availability, disaster recovery, locations, data centers

subcollection: overview

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:pre: .pre}
{:table: .aria-labeledby="caption"}
{:note: .deprecated}


# Wie kann sichergestellt werden, dass keine Ausfallzeiten auftreten?
{: #zero-downtime}

Ihre globale Strategie ist wichtig. Sie können ein bestimmtes Rechenzentrum oder einen bestimmten Standort auswählen, um Ihren Kunden Ihre Daten im richtigen Teil der Welt bereitzustellen. 
{:shortdesc}

{{site.data.keyword.Bluemix}}-Plattformservices werden selbst verwaltet. Das bedeutet, dass die Standorte, an denen Sie Ihre App implementieren, Workloads über Rechenzentren verteilen können. Sie können außerdem sicherstellen, dass ein Failover-Design vorhanden ist, was bedeutet, dass Ihre App für Ihre Kunden immer betriebsbereit ist. Für Ihre Infrastrukturressourcen können Sie einzelne Rechenzentren auswählen, in denen die Ressourcen bereitgestellt werden. 

Alle {{site.data.keyword.Bluemix_notm}}-Ressourcen werden per Hosting in Rechenzentren auf der ganzen Welt bereitgestellt. Da Hochverfügbarkeit und Disaster-Recovery nicht für alle Services universell sind, hängt es von dem von Ihnen verwendeten Service ab, welche Art von Hochverfügbarkeit und Disaster-Recovery tatsächlich verfügbar ist.  

## Disaster-Recovery
{: #disaster-recovery}

Bei Disaster-Recovery geht es darum, einen katastrophalen Ausfall oder einen Verfügbarkeitsverlust an einem einzelnen Standort zu überstehen. Um sicherzustellen, dass Disaster-Recovery vorhanden ist, ist es notwendig, dass Sie mehrere {{site.data.keyword.Bluemix_notm}}-Umgebungen fan mehreren Standorten bereitstellen, um einzelne Fehlerquellen (Single Points of Failure) zu vermeiden. Bei diesen Umgebungen kann es sich um eine Kombination aus öffentlichen, dedizierten oder lokalen Plattformen handeln.  

### Erstellen eines Disaster-Recovery-Plans 
{: #dr-plan}

{{site.data.keyword.Bluemix_notm}} entspricht den Anforderungen für die Planung eines Notfalls und bei jeder Anwendung ist ein Plan für Sie zum Wiederherstellen oder zum erneuten Starten vorhanden. Die Wiederherstellung erfolgt durch elektronische Sicherungen in einem Wiederherstellungscenter oder in alternativen Räumlichkeiten für die Datenverarbeitung, die die Datenverarbeitung wiederherstellen. Angesichts eines potenziellen Notfalls enthält der Disaster-Recovery-Plan die System- und Hostinganforderungen für Hardware, Software, Netzwerkkonnektivität sowie externe Sicherungsfunktionen.

Die folgende Liste enthält die Anforderungen des Notfallwiederherstellungsplans:

- Für den Lastausgleich ist ein Dokument vorhanden, in dem erläutert wird, wie der Datenverarbeitungsservice verfügbar bleibt. 
- Für den Fall, dass an mehreren Standorten ein Ausweichbetrieb stattfindet, muss der Disaster-Recovery-Plan erläutern, wer das Failover wodurch verursacht hat, und den Neustart sicherstellen. 
- Der Disaster-Recovery-Plan muss definieren, wie die Lösung funktioniert und welcher Datenverlust aufgetreten ist. 
- Er muss darlegen, wie die maximal tolerierbare Ausfallzeit eingehalten und in der Datenbank des Disaster-Recovery-Plans gespeichert wird.  
- Der Notfallwiederherstellungsplan gibt die Sicherheitsmaßnahmen für die Ausführung im Notfallmodus an, sofern diese sich jeweils von denen in der Produktion unterscheiden. 

### Management des Disaster-Recovery-Plans 
{: #dr-plan-mgmt}

{{site.data.keyword.Bluemix}} berücksichtigt die folgenden Anforderungen: 

- Der Disaster-Recovery-Plan muss nach einer größeren Infrastrukturänderung, nach einem wichtigen Anwendungsrelease und nach jedem Test aktualisiert werden. 
- Er muss jährlich genehmigt werden. 

## Standorte für die Ressourcenbereitstellung 
{: #ov_intro_reg}

Sie können Apps und Serviceinstanzen an unterschiedlichen Standorten mit derselben {{site.data.keyword.cloud_notm}}-Infrastruktur für das Anwendungsmanagement und derselben Ansicht mit Nutzungsdetails zur Gebührenabrechnung erstellen. Sie können Ihre Apps an dem Standort bereitstellen, der Ihren Kunden am nächsten ist, um eine möglichst geringe Latenzzeit zu erzielen. 

Zum Beheben von Sicherheitsproblemen können Sie auch den Standort auswählen, an dem die Anwendungsdaten aufbewahrt werden sollen. Wenn Sie Apps an mehreren Standorten erstellen, werden die Apps an den anderen Standorten weiter ausgeführt, falls ein Standort nicht mehr verfügbar ist. Die verfügbaren Ressourcen sind für jeden verwendeten Standort gleich. Weitere Informationen zu den Plattformressourcen und den Standorten, an denen sie verfügbar sind, finden Sie unter [Serviceverfügbarkeit](/docs/resources?topic=resources-services_region).

Der globale Lastausgleich für die {{site.data.keyword.cloud_notm}}-Konsole stellt sicher, dass bei einer Inaktivität Ihres nächsten geografischen Standorts die Konsole die Informationen für den nächstgelegenen Standort anzeigt. Auf diese Weise verfügen Sie stets über Zugriff auf die Konsole, ohne dass Aktionen erforderlich sind, um auf die benötigten Ressourcen zuzugreifen.

Über die Ansicht 'Ressourcenliste' können Sie standardmäßig alle Ressourcen an allen Standorten anzeigen. Wenn Sie Ressourcen an einem bestimmten Standort anzeigen und mit diesen arbeiten möchten, erweitern Sie das Menü **Standort** und wählen Sie einen Standort aus der Liste aus. Wenn Sie eine bestimmten geografischen Standort erweitern, haben Sie die Möglichkeit, nach einzelnen Rechenzentren, Regionen oder Zonen zu filtern.

Beispiel: Wenn Sie über Ressourcen verfügen, die in der Zone 'London 2' (eu-gb-2) bereitgestellt werden, können Sie die Ressourcenliste so filtern, dass nur diese Ressourcen angezeigt werden. Eine Zone befindet sich innerhalb einer Region und eine Region ist anhand des zugehörigen Metrostandorts organisiert. Zum Filtern der Liste anhand der Zone 'London 2' (eu-gb-2) erweitern Sie die Metro-Option **London** und anschließend die Regionsoption **London (eu-gb)**. Innerhalb dieser Region können Sie eine Zone in der Liste der verfügbaren Zonen auswählen. Wenn Sie über eine Ressource verfügen, die in einem bestimmten Rechenzentrum bereitgestellt wird, können Sie das Rechenzentrum anhand des spezifischen Metrostandorts und des alphanumerischen Codes identifizieren, z. B. London 02 (lon02).

Sie können auch über Ressourcen verfügen, die global bereitgestellt werden. Die Option **Global** bedeutet, dass nur eine einzelne, logische, global zugängliche Instanz des Service - unabhängig von einer Region oder Zone - für Kundenanwendungen veröffentlicht wird. Zugriff auf diese Ressourcentypen besteht über einen globalen Endpunkt.

## Rechenzentren
{: #data_center}

Wenn Sie Infrastrukturressourcen bereitstellen, stehen Ihnen mehr Optionen zur Verfügung, an denen sich Ihre Daten befinden können. Sie können einen Standort auswählen oder eines der aufgelisteten {{site.data.keyword.Bluemix_notm}}-Rechenzentren. Ein *Rechenzentrum* ist der physische Standort, an dem die für Services und Apps verwendeten Ressourcen für Strom, Kühlung, Datenverarbeitung, Vernetzung und Speicher gehostet werden. Rechenzentren bieten keine Isolierung von lokalen Ausfällen, ähnlich wie bei mehreren Zonen an einem Standort. Weitere Informationen finden Sie in [Globale Standorte für Ihr globales Unternehmen ![Symbol für externen Link](../icons/launch-glyph.svg "Symbol für externen Link")](https://www.ibm.com/cloud/data-centers/){: new_window}.

{{site.data.keyword.Bluemix_notm}} bietet Rechenzentren an vielen Standorten in der ganzen Welt. 


![Karte der Rechenzentren, die in den folgenden Tabellen beschrieben werden](images/Global-View.svg)


Die folgende Tabelle enthält den spezifischen Code für die einzelnen Rechenzentren. 

| Rechenzentrum | Code  |
|------------------|-------|
| Dallas 01        | dal01 |
| Dallas 05        | dal05 |
| Dallas 06        | dal06 |
| Dallas 07        | dal07 |
| Dallas 09        | dal09 |
| Dallas 10        | dal10 |
| Dallas 12        | dal12 |
| Dallas 13        | dal13 |
| Houston 01       | hou01 |
| Mexiko 01        | mex01 |
| Montreal 01      | mon01 |
| San Jose 01      | sjc01 |
| San Jose 03      | sjc03 |
| San Jose 04      | sjc04 |
| Sao Paulo 01     | sao01 |
| Seattle 01       | sea01 |
| Toronto 01       | tor01 |
| Washington DC 01 | wdc01 |
| Washington DC 04 | wdc04 |
| Washington DC 06 | wdc06 |
| Washington DC 07 | wdc07 |
{: caption="Tabelle 1. Rechenzentren in Nord- und Südamerika" caption-side="top"}
{: #americas}
{: tab-title="Americas"}
{: tab-group="dcs"}
{: class="simple-tab-table"}
{: summary="Use the buttons before the table to change the context of the table. The column headers identify the data centers located in the specific greographical area."}

| Rechenzentrum | Code  |
|------------------|-------|
| Amsterdam 01     | ams01 |
| Amsterdam 03     | ams03 |
| Frankfurt 02     | fra02 |
| Frankfurt 04     | fra04 |
| Frankfurt 05     | fra05 |
| London 02        | lon02 |
| London 04        | lon04 |
| London 05        | lon05 |
| London 06        | lon06 |
| Mailand 01         | mil01 |
| Oslo 01          | osl01 |
| Paris 01         | par01 |
{: caption="Tabelle 1. Rechenzentren in Europa" caption-side="top"}
{: #europe}
{: tab-title="Europe"}
{: tab-group="dcs"}
{: class="simple-tab-table"}
{: summary="Use the buttons before the table to change the context of the table. The column headers identify the data centers located in the specific greographical area."}

| Rechenzentrum | Code  |
|------------------|-------|
| Hongkong 02     | hkg02 |
| Melbourne 01     | mel01 |
| Seoul 01         | seo01 |
| Singapur 01     | sng01 |
| Sydney 01        | syd01 |
| Sydney 04        | syd04 |
| Sydney 05        | syd05 |
| Tokio 01         | tok02 | 
| Tokio 04         | tok04 |
| Tokio 05         | tok05 |
{: caption="Tabelle 1. Rechenzentren in Asien/Pazifik" caption-side="top"}
{: #asiapacific}
{: tab-title="Asia Pacific"}
{: tab-group="dcs"}
{: class="simple-tab-table"}
{: summary="Use the buttons before the table to change the context of the table. The column headers identify the data centers located in the specific greographical area."}


## Service-Level-Agreements (SLAs)
{: #SLAs} 

{{site.data.keyword.Bluemix_notm}} stellt ein Service-Level mit einer Verfügbarkeit von 99,5 % für mehrere Instanzen eines Plattformservice in einer einzelnen dedizierten oder lokalen Umgebung bereit.

Wenn Sie eine Reklamation wegen Ausfallzeit einreichen wollen, wenden Sie sich an [{{site.data.keyword.Bluemix_notm}} Support](https://cloud.ibm.com/unifiedsupport/supportcenter){: new_window} ![Symbol für externen Link](../icons/launch-glyph.svg "Symbol für externen Link").

{{site.data.keyword.Bluemix_notm}} stellt SLAs für {{site.data.keyword.Bluemix_notm}}-Services zur Verfügung, durch die Sie gegebenenfalls zu Gutschriften auf Ihr Konto berechtigt sind. SLAs stellen die einzige Möglichkeit dar, die Nichteinhaltung eines angegebenen Service-Levels durch {{site.data.keyword.Bluemix_notm}} beizulegen. {{site.data.keyword.Bluemix_notm}} stellt ein Service-Level mit einer Verfügbarkeit von 99,5 % für mehrere Instanzen eines Plattformservice in einer einzelnen dedizierten oder lokalen Umgebung bereit.

Weitere Informationen zu dedizierten Umgebungen finden Sie in [IBM Cloud Dedicated](/docs/hybrid?topic=dedicated-dedicated). In [Bluemix Local](/docs/hybrid?topic=local-local) finden Sie weitere Informationen zu lokalen Umgebungen. 

Die vollständige Servicebeschreibung für {{site.data.keyword.Bluemix_notm}} steht unter [Cloud Services-Bedingungen](http://www-03.ibm.com/software/sla/sladb.nsf/sla/bm){: new_window} ![Symbol für externen Link](../icons/launch-glyph.svg "Symbol für externen Link") zur Verfügung.

### SLA für Verfügbarkeitsausfallzeit 
{: #avail-downtime}

Sie haben Anspruch auf eine Gutschrift auf Ihr Konto, wenn Ausfallzeiten auftreten, bei denen die Verfügbarkeit von 99,5 % unterschritten wird. Die Ausfallzeit der Verfügbarkeit ergibt sich aus der Gesamtzeit in Minuten, in der Sie zu keiner Ihrer Service-Instanzen eine Verbindung herstellen konnten. Die Berechnung der Gesamtausfallzeit beginnt mit der Einreichung eines Berichts zur Meldung des Betriebsunterbrechungsereignisses und endet, wenn mindestens eine der betroffenen Instanzen für die Nutzung verfügbar ist.

{{site.data.keyword.Bluemix_notm}} stellt ein SLA mit 99,95 % Verfügbarkeit für folgende Services bereit: 
- Cloud-Services in der öffentlichen Umgebung, die für hohe Verfügbarkeit konfiguriert sind, wie in den Katalogdetails für jeden Service beschrieben. 
- Cloud-Services in mehreren dedizierten oder lokalen Umgebungen in räumlich getrennten Rechenzentren. 

| Typ	 | Beschreibung	 | Details der Unterstützung|
|-------------------------------------------------------------------------------|--------------------|----------------|
| Öffentliche HA-Umgebung oder mehrere dedizierte/lokale Umgebungen | Andere Umgebungen | Gutschrift         |
| <99,95 %                                                                       |<99,5 %              |10 %             |
| <99,90 %                                                                       |<99,0 %              |25 %             |
{: caption="Tabelle 5. Service-Level der monatlichen Verfügbarkeit" caption-side="top"}

Der Prozentsatz der Verfügbarkeit wird berechnet als Gesamtzahl von Minuten in einem Vertragsmonat minus der Gesamtanzahl von Ausfallzeitminuten in diesem Monat, dividiert durch die Gesamtzahl der Minuten in diesem Monat. 

Ein Monat mit 31 Tagen umfasst beispielsweise insgesamt 44.640 Minuten. Wenn sechs Stunden Verfügbarkeitsausfallzeit auftreten, ergeben sich daraus 360 Minuten Ausfallzeit. Mit einer Ausfallzeit von nur sechs Stunden beträgt die Verfügbarkeit 99,19 %. Da 99,19 % jedoch geringer ist als 99,90 %, haben Sie bei einer öffentlichen oder lokalen Umgebung Anspruch auf eine Gutschrift von 25 %.   

```
= (44.640 Gesamtminuten im Monat - 360 Minuten Ausfallzeit) / 44,640 Gesamtminuten im Monat
= (44.280 Minuten tatsächlicher Verfügbarkeit) / 44,640 Gesamtminuten im Monat
= 99,19 % Verfügbarkeit
```

SLAs schließen keine Ausfallzeiten oder Störungen ein, die mit den angegebenen Ausschlüssen, der Nichtverfügbarkeit der {{site.data.keyword.Bluemix_notm}}-Benutzerschnittstelle oder der Zeit zum erneuten Laden, Konfigurieren, Aktivieren oder Zugreifen auf Inhalte zusammenhängt.

Die SLA für Verfügbarkeitsausfallzeit schließt keine {{site.data.keyword.Bluemix_notm}}-Infrastrukturservices ein. 
{: note}

### SLAs für Infrastrukturservices
{: #iaas-slas}

Infrastrukturdienste sind Bare-Metal-Server und virtuelle Server, Vernetzungs-, Speicher- und Sicherheitsservices. Um eine vollständige Liste der Infrastrukturservices zu finden, durchsuchen Sie den {{site.data.keyword.Bluemix_notm}}-Katalog unter Verwendung des Tags `iaas`. 

Als Ausfallzeit wird die Gesamtzeit von Minuten bezeichnet, in der ein vom Kunden identifizierter Infrastrukturservice nicht zur Verfügung steht, da der Service wegen einer Serviceunterbrechung aufgrund eines Ausfalls des öffentlichen Netzes, des privaten Netzes, einem Stromausfall bei redundanten Infrastrukturen und HVAC-Betriebsunterbrechungen unterbrochen worden ist. Die Berechnung der Gesamtausfallzeit in Minuten beginnt, wenn der bestätigte Ausfall, der den Service betrifft, identifiziert wird, und endet mit Zeitpunkt, an dem der Service wieder verfügbar ist. 

Ausfallzeiten umfassen keine Zeit für geplante oder angekündigte Wartungsarbeiten. Für jeweils 30 Minuten ununterbrochener Ausfallzeit erhalten Sie eine Gutschrift in Höhe von 5 % der monatlichen Gebühren für die identifizierten Services, die direkt von dem Ausfall betroffen sind. Sie haben keinen Anspruch auf eine Gutschrift, wenn die Ausfallzeit weniger als 30 zusammenhängende Minuten beträgt. Ausfallzeiten für unterschiedliche Ausfalltypen können nicht miteinander kombiniert werden, damit diese Berechnung erfüllt wird. 

### SLA für Ersatz von Hardware der Infrastruktur und für Aktualisierungen
{: #hw-replaceupgrade-sla}

{{site.data.keyword.Bluemix_notm}} versucht, beim Austausch fehlerhafter Hardware oder bei der Durchführung eines terminierten Hardware-Upgrades die Ausfallzeit zu minimieren. 

{{site.data.keyword.Bluemix_notm}} stellt Gutschriften für die folgenden Fälle bereit:  
- Ersetzen von Hardware, basierend auf der Zeit des Austauschs ab dem Zeitpunkt, zu dem {{site.data.keyword.Bluemix_notm}} bestätigt, dass ein Kunde einen Hardwarefehler gemeldet hat.
- Geplante Hardware-Upgrades, basierend auf der Gesamtausfallzeit des Service, für den das Upgrade durchgeführt wird. 

Service-Level-Zeiträume schließen jede Zeit aus, die zum erneuten Laden des Betriebssystems oder von Anwendungen erforderlich ist, oder die Zeitleistung verschlechtert ist. Sie haben Anspruch auf eine Gutschrift auf der Grundlage der monatlichen Gebühr für den Service, die von dem Hardwareaustausch oder -upgrade betroffen ist, wenn {{site.data.keyword.Bluemix_notm}} einen bestimmten Service-Level-Zeitraum nicht erfüllt.

| Service-Level-Zeitraum | Prozentsatz der Gutschrift |
|---------------------------|----------------|
| ≤ 2 Stunden                 | Keine           |
| > 2 Stunden                 | 20 %            |
| > 6 Stunden                 | 40 %            |
| > 10 Stunden                | 60 %            |
| > 14 Stunden                | 80 %            |
| > 18 Stunden                | 80 %            |
{: caption="Tabelle 6. Gutschrift basierend auf der monatlichen Gebühr für den Service, der von dem Hardwareaustausch oder -upgrade betroffen ist" caption-side="top"}

### Reklamationen
{: #claims}

Reichen Sie Ihren Antrag innerhalb von 60 Tagen nach Ablauf des vertraglich vereinbarten Monats ein, in dem das Serviceziel (Service-Level) nicht erreicht wurde. Stellen Sie ausreichend Informationen zur Verfügung, damit der betroffene Service ermittelt werden kann, und geben Sie Fehlermeldungen und andere Informationen an, die notwendig sind, um den Reklamationsanspruch zu überprüfen. 

Die Gutschrift ist die höchste anwendbare Vergütung und basiert auf der kumulativen Verfügbarkeit des betroffenen Service während eines Vertragsmonats. Ihre Berechnung erfolgt anhand der monatlichen Gebühren für den betroffenen Service. Gutschriften dürfen 25 % der monatlichen Gebühren nicht überschreiten.

Wenn Sie eine Reklamation wegen Ausfallzeit einreichen wollen, wenden Sie sich an [{{site.data.keyword.Bluemix_notm}} Support](https://cloud.ibm.com/unifiedsupport/supportcenter){: new_window} ![Symbol für externen Link](../icons/launch-glyph.svg "Symbol für externen Link").

### Ausschlüsse
{: #exclusions}

Es werden keine Gutschriften für die Nichteinhaltung einer SLA aus den folgenden Gründen ausgestellt:
- Probleme mit Inhalten, Technologie, Designs oder Anweisungen, die von Kunden oder von der Community bereitgestellt wurden
- Cloud-Services in der Beta-Phase, experimentelle Cloud-Services oder gebührenfreie Cloud-Services
- Build-Packs, die nicht von IBM stammen
- Nicht unterstützte Systemkonfigurationen und -plattformen
- Ausfälle der kundenseitigen Infrastruktur, einschließlich Netzwerk, Hardware, Ausrüstung oder Stromversorgung
- Aktionen, Befehle oder Dateiübertragungen der Systemadministration des Kunden
- Kundenseitige Fehler oder Versäumnisse bei der Bereitstellung von Informationen zu Zugriff, die bzw. der für die Behebung einer Betriebsunterbrechung benötigt wird
- Vom Kunden verursachte Sicherheitsvorfälle oder Sicherheitstests
- Andere Ursachen, auf die IBM keinen Einfluss hat

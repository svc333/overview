---
copyright:
  years: 2019
lastupdated: "2019-06-04"

keywords: understanding infrastructure, vpc, classic infrastructure, cloud environment

subcollection: overview

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}
{:tip: .tip}
{:note: .note}

# {{site.data.keyword.cloud_notm}}-Infrastrukturumgebungen vergleichen
{: #compare-infrastructure}

Sie können die Hauptunterschiede zwischen den {{site.data.keyword.cloud}}-Infrastrukturumgebungen vergleichen, um zu entscheiden, welche für Ihre Workloads und Anwendungen am besten geeignet ist.
{: shortdesc}

Wenn Sie mit den Umgebungstypen nicht vertraut sind, lesen Sie die folgenden Beschreibungen. 

* Die klassische Infrastruktur ist die bestehende IaaS-Plattform. Diese Umgebung ist am besten für Lift-and-shift-Workloads geeignet, da sie es ermöglicht, Anwendungen schnell zu verschieben und dieselbe Architektur beizubehalten. 
* Die VPC-Infrastruktur ist die neue IaaS-Plattform, die auf Software-Defined Networking basiert und am besten für cloudnative Anwendungen geeignet ist. 

Die klassische Infrastruktur und die VPC-Infrastruktur sind kostenneutral, d. h., Sie können sich darauf konzentrieren, welche Umgebung die jeweiligen Anforderungen am besten erfüllt.
{: note}

## Unterscheidungsmerkmale bei der Datenverarbeitung
{: #compare-compute}

In der folgenden Tabelle sind die Unterschiede zwischen der klassischen Infrastruktur und der VPC-Infrastruktur hinsichtlich der Datenverarbeitung aufgeführt. Die verschiedenen Unterscheidungsmerkmale sind in der Kategoriespalte aufgeführt, die Beschreibungen in den Spalten der klassischen Infrastruktur und der VPC-Infrastruktur.  

| Kategorie  |  Klassische Infrastruktur | VPC-Infrastruktur  |
| ---------- | ------------------------- | ------------------ |
| Services   |Umfassender Katalog mit Services, wie z. B. {{site.data.keyword.baremetal_short}}, {{site.data.keyword.BluVirtServers_short}}-Instanzen, VMware, SAP | Nur {{site.data.keyword.BluVirtServers_short}}-Instanzen |
| Leistung und Verfügbarkeit | |Bessere Verfügbarkeit durch Zonenarchitektur erreichbar |
| Preisstruktur | Abrechnung auf stündlicher und monatlicher Basis sowie Features zum Aussetzen der Abrechnung | Abrechnung auf stündlicher Basis, Aussetzen der Abrechnung und Dauernutzungsrabatte |
| Produktfamilie virtueller Server | Öffentlich, dediziert, transient, reserviert | Nur öffentlich |
| Profile | Alle Profile, einschließlich GPU-Profile | Ausgewogene, datenverarbeitungsinentsive und speicherintensive Profile mit Optionen für größere RAM- und vCPU-Nutzung |
| Unterstützte Images | Umfassende Gruppe vorbereiteter Images sowie angepasste Images | Begrenzte Gruppe vorbereiteter Images|
| Plattformintegration | | Integration von IAM und Ressourcengruppe für eine einheitliche Schnittstelle |
{: caption="Tabelle 1. Vergleich bei der Datenverarbeitung" caption-side="top"}

## Unterscheidungsmerkmale beim Netz
{: #compare-network}

In der folgenden Tabelle sind die Unterschiede zwischen der klassischen Infrastruktur und der VPC-Infrastruktur hinsichtlich des Netzbetriebs aufgeführt. Die verschiedenen Unterscheidungsmerkmale sind in der Kategoriespalte aufgeführt, die Beschreibungen in den Spalten der klassischen Infrastruktur und der VPC-Infrastruktur.  

| Kategorie  |  Klassische Infrastruktur | VPC-Infrastruktur  |
| ---------- | ------------------------- | ------------------ |
| Standortkonstrukt | Rechenzentren und PODs <br>(VLAN-Spanning ist möglicherweise erforderlich, um unterschiedliche Pods bzw. Rechenzentren zu verbinden, und der Erwerb von Gateways ist möglicherweise erforderlich, um den Datenverkehr zu steuern und weiterzuleiten)| Regionsmodell mit einer Abstraktion der Infrastruktur, sodass Podstandorte kein Problem darstellen. |
| Netzfunktionen und -services |Physische und virtuelle Appliances verschiedener Anbieter | Cloudnative Netzfunktionen (VPNs, LBaaS)<br>(VPC-Isolation; dedizierte, aus der öffentlichen Cloud ausgegliederte Ressourcen; weitere Optionen für VPNs, LBaaS, mehrere vNIC-Instanzen und größere Teilnetze) |
| IP-Adressen | Unterstützung für IPv6-Adressen | Nur IPv4-Adressen |
| Gateway-Routing | Verwendung einer virtuellen oder physischen Netzappliance (Virtual Router Appliance, Vyatta, Juniper vSRX, Fortinet FSA) | Routing des Datenverkehrs wird durch Services für öffentliche Gateways und variable IP-Adressen verarbeitet. |
| Netzadressumsetzung (NAT) | Verwendung einer virtuellen oder physischen Netzappliance (Virtual Router Appliance, Vyatta, Juniper vSRX, Fortinet FSA) | Unterstützung durch die BYOP-Funktionalität (Bring-your-own-IP, eigene IP-Adresse verwenden) |
| IPsec-VPN | Verwendung einer virtuellen oder physischen Netzappliance (Virtual Router Appliance, Vyatta, Juniper vSRX, Fortinet FSA) | Unterstützung durch das VPN-aaS-Angebot |
| Elastischer Lastausgleich | Cloud Load Balancer  | Load Balancer for VPC |
| Globaler Lastausgleich | Cloud Internet Services, Citrix Netscaler MPX | Cloud Internet Services |
| Hybridkonnektivität | NAT-Lösung zur Überbrückung zwischen IBM Cloud und der jeweiligen IT-Umgebung | Eigene private IP-Adresse ohne NAT- oder IPSec-Tunnel verwenden <br>Hinweis: Sie können Ihre VPC aktivieren, um auf Ressourcen der klassischen Infrastruktur zuzugreifen. |
{: caption="Tabelle 2. Vergleich beim Netzbetrieb" caption-side="top"}

## Unterscheidungsmerkmale beim Speicher
{: #compare-storage}

|  Klassische Infrastruktur | VPC-Infrastruktur  |
| ------------------------- | ------------------ |
|Leistungsfähige Speicherservices, Blockspeicherangebote (iSCSI) und Dateispeicherangebote (NFS-basiert)| Blockspeicher als primärer Bootdatenträger (mit grundlegender Lebenszyklusverwaltung) und Sekundärdatenträger <br> Hinweis: Bei der Bereitstellung ist eine Datenträgerverschlüsselung verfügbar. |
{: caption="Tabelle 3. Vergleich beim Speicher" caption-side="top"}

## Unterscheidungsmerkmale bei der Sicherheit
{: #compare-security}

|  Klassische Infrastruktur | VPC-Infrastruktur  |
| ---------- | ------------------------- |
|Vyatta, Fortigate, Juniper vSRX, Sicherheitsgruppen für VSIs| Sicherheitsgruppen, Netzzugriffssteuerungslisten (ACLs)|
{: caption="Tabelle 4. Vergleich bei der Sicherheit" caption-side="top"}

## Unterscheidungsmerkmale bei der API
{: #compare-apis}

|  Klassische Infrastruktur | VPC-Infrastruktur  |
| ------------------------- | ------------------ |
|Vorhandene {{site.data.keyword.slapi_short}} (SLAPI)| Neue entwicklerfreundliche REST-basierte API |
{: caption="Tabelle 5. Vergleich der API" caption-side="top"}

## Nächste Schritte
{: #compare-nextsteps}

Informationen zur gesamten VPC-Infrastrukturfunktionalität finden Sie in [Informationen zur virtuellen privaten Cloud](/docs/vpc-on-classic?topic=vpc-on-classic-about). Allgemeine Informationen zum Einstieg in die Infrastruktur finden Sie in [Infrastruktur erstellen](/docs/overview?topic=overview-first-steps-it-ops). 

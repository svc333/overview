---
copyright:
  years: 2019
lastupdated: "2019-06-05"

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

# Confronto tra gli ambienti dell'infrastruttura {{site.data.keyword.cloud_notm}}
{: #compare-infrastructure}

Confronta le differenze chiave tra gli ambienti dell'infrastruttura {{site.data.keyword.cloud}} per decidere qual è il migliore per i tuoi carichi di lavoro e applicazioni.
{: shortdesc}

Se non hai familiarità con i tipi di ambiente, controlla le seguenti descrizioni.

* L'infrastruttura classica è la nostra piattaforma IaaS esistente. Questo ambiente è il migliore per la migrazione dei carichi di lavoro, che ti consente di spostare le applicazioni velocemente e di mantenere la stessa architettura.
* L'infrastruttura VPC è la nostra nuova piattaforma IaaS, basata sulla rete definita dal software e ideale per le applicazioni native cloud.

Le infrastrutture classica e VPC non incidono al livello di costi, per cui puoi concentrarti su quale ambiente meglio si adatta ai tuoi bisogni.
{: note}

## Differenziatori di calcolo
{: #compare-compute}

Vedi la seguente tabella per le differenze di calcolo tra l'infrastruttura classica e VPC. 

| Categoria   |  Infrastruttura classica   | Infrastruttura VPC |
| ---------- | ------------------------- | ------------------ |
|  Servizi  |Catalogo completo di servizi, ad esempio {{site.data.keyword.baremetal_short}}, le istanze {{site.data.keyword.BluVirtServers_short}}, VMware, SAP | solo le istanze {{site.data.keyword.BluVirtServers_short}} |
| Prestazioni e disponibilità | | Migliore disponibilità di archiviazione tramite l'architettura della zona |
| Prezzi | Fatturazione oraria e mensile, con in più delle funzioni di sospensione della fatturazione | Fatturazione oraria, sospensione della fatturazione e sconto sull'utilizzo prolungato |
| Famiglie del server virtuali | Pubblico, dedicato, temporaneo, riservato | Solo pubblico |
| Profili | Tutti i profili inclusi i profili GPU | Profili bilanciato, calcolo, memoria con opzioni di RAM e vCPU più elevate |
| Immagini supportate | Serie completa di immagini predefinite, con in più delle immagini personalizzate | Serie limitata di immagini predefinite|
| Integrazione piattaforma | | Integrazione IAM e gruppo di risorse per un'esperienza unificata |
{: row-headers}
{: class="comparison-table"}
{: caption="Tabella 1. Confronto del calcolo" caption-side="top"}
{: summary="This table has row and column headers. The row headers identify possible features. The column headers indentify the differentiators between classic infrastructure and VPC infrastructure. To understand the differences between environments, navigate to the row and find the details for the feature that you're interested in."}

## Differenziatori di rete
{: #compare-network}

Vedi la seguente tabella per le differenze di rete tra l'infrastruttura classica e VPC.  

| Categoria   |  Infrastruttura classica   | Infrastruttura VPC |
| ---------- | ------------------------- | ------------------ |
| Costrutto ubicazione    | Data center e POD <br>(Potrebbe essere necessario lo spanning della VLAN per la connessione a due diversi pod/data center e l'acquisto di gateway per controllare e instradare il traffico)| Modello regionale che astrae l'infrastruttura in modo da non doverti preoccupare delle ubicazioni del pod.|
| Servizi e funzioni di rete |Dispositivi fisici e virtuali da più fornitori | Funzioni di rete native cloud (VPN, LBaaS)<br>(Isolamento VPC, risorse dedicate ricavate dal cloud pubblico, con più opzioni per VPN, LBaaS, più istanze vNIC e dimensioni di sottoreti più grandi) |
| Indirizzi IP | Gli indirizzi IPv6 sono supportati | Solo indirizzi IPv4 |
| Instradamento gateway | Utilizza un dispositivo di rete fisico o virtuale (Virtual Router Appliance, Vyatta, Juniper vSRX, Fortinet FSA) | L'instradamento del traffico è gestito dal gateway pubblico e dai servizi di IP mobili |
| NAT (Network Address Translation) | Utilizza un dispositivo di rete fisico o virtuale (Virtual Router Appliance, Vyatta, Juniper vSRX, Fortinet FSA) | Supportato dalla funzionalità BYOIP (Bring-your-own-IP)  |
| VPN (Virtual private network) IPsec | Utilizza un dispositivo di rete fisico o virtuale (Virtual Router Appliance, Vyatta, Juniper vSRX, Fortinet FSA) | Supportato con l'offerta VPN-as-a-service |
|  Bilanciamento carico elastico | Programma di bilanciamento del carico cloud  | Programma di bilanciamento del carico per VPC |
| Bilanciamento del carico globale| Servizi internet cloud, Citrix Netscaler MPX | Servizi internet cloud |
|Connettività ibrida | Soluzione NAT per collegare IBM Cloud e il tuo ambiente IT | Utilizza il tuo indirizzo IP privato senza NAT o i tunnel IPSec <br>Nota: puoi abilitare il tuo VPC in modo che acceda alle risorse dell'infrastruttura classica.|
{: row-headers}
{: class="comparison-table"}
{: caption="Tabella 2. Confronto della rete" caption-side="top"}
{: summary="This table has row and column headers. The row headers identify possible features. The column headers indentify the differentiators between classic infrastructure and VPC infrastructure. To understand the differences between environments, navigate to the row and find the details for the feature that you're interested in."}

## Differenziatori dell'archiviazione
{: #compare-storage}

Vedi la seguente tabella per le differenze di archiviazione tra l'infrastruttura classica e VPC.

|  Infrastruttura classica   | Infrastruttura VPC |
| ------------------------- | ------------------ |
|Una serie solida di servizi di archiviazione e offerte block storage (iSCSI) e file storage (basata su NFS)| Block storage come disco di avvio primario (con la gestione del ciclo di vita di base) e i volumi di dati secondari  <br> Nota: la crittografia del volume è disponibile durante il provisioning.|
{: caption="Tabella 3. Confronto dell'archiviazione" caption-side="top"}

## Differenziatori della sicurezza
{: #compare-security}

Vedi la seguente tabella per le differenze di sicurezza tra l'infrastruttura classica e VPC.

|  Infrastruttura classica   | Infrastruttura VPC |
| ---------- | ------------------------- |
|Vyatta, Fortigate, Juniper vSRX, gruppi di sicurezza per VSI| Gruppi di sicurezza, ACL (access control list) di rete|
{: caption="Tabella 4. Confronto della sicurezza" caption-side="top"}

## Differenziatori API
{: #compare-apis}

Vedi la seguente tabella per le differenze API tra l'infrastruttura classica e VPC.

|  Infrastruttura classica   | Infrastruttura VPC |
| ------------------------- | ------------------ |
|{{site.data.keyword.slapi_short}} (SLAPI) esistente| Nuova API basata su REST per gli sviluppatori|
{: caption="Tabella 5. Confronto API" caption-side="top"}

## Passi successivi
{: #compare-nextsteps}

Per controllare tutte le funzionalità dell'infrastruttura VPC, vedi [Informazioni sul cloud privato virtuale](/docs/vpc-on-classic?topic=vpc-on-classic-about). Per iniziare ad esplorare l'intera infrastruttura, vedi [Creazione della tua infrastruttura](/docs/overview?topic=overview-first-steps-it-ops).

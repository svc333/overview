---

copyright:
  years: 2018, 2019
lastupdated: "2019-06-04"

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

# Esplora il percorso dell'amministratore delle operazioni IT in {{site.data.keyword.cloud_notm}}
{: #it-ops}

Poiché molte organizzazioni passano a un ambiente cloud, in locale o ospitato nei data center, il ruolo dell'amministratore delle operazioni IT (IT ops admin) sta venendo ridefinito. L'ambito e la complessità di questa modifica aumentano in modo significativo in base al tipo di ambiente che la tua organizzazione vuole distribuire. 
{: .shortdesc}

Prima del passaggio al cloud, hai lavorato con un ambiente intrinsecamente sicuro con sistemi collegati alla tua intranet o LAN privata. In un ambiente cloud, ti aspetti ora di eseguire le seguenti attività:
 
  * Disporre dei tuoi componenti del servizio "da qualche parte." 
  * Comprendere le implicazioni di rete e le richieste di sicurezza.
  * Lavorare con tecnologie diverse.  
  * Integrare il nuovo ambiente con degli strumenti che non fanno parte in modo nativo dello stack cloud. 
  * Continuare a supportare i tuoi clienti interni come se avessi ancora un data center in loco.

{{site.data.keyword.cloud}} è qui per supportarti al 100% durante il tuo percorso. Le risorse disponibili per te includono la documentazione completa, gli strumenti di pianificazione, gli specialisti di supporto qualificati e una community di utenti attiva. Iniziamo il tuo percorso. 

## Introduzione alle nozioni fondamentali
{: #basics}

### Modelli del servizio cloud
{: #cloud-svc-models}

Esistono tre tipi di modelli di servizio cloud: IaaS (Infrastructure as a Service), PaaS (Platform as a Service) e SaaS (Software as a Service). La figura 1 illustra chi fa cosa all'interno di ogni modello del servizio. Per ulteriori informazioni, vedi [IaaS, PaaS, and SaaS - IBM Cloud service models](https://www.ibm.com/cloud/learn/iaas-paas-saas){: new_window} ![Icona link esterno](../icons/launch-glyph.svg "Icona link esterno").

![Figura 1. Modelli del servizio cloud](images/cloud-svc-models.png "Modelli del servizio cloud")

Con il modello IaaS, il tuo provider è responsabile solo della gestione dell'infrastruttura sottostante e facoltativamente dell'installazione del software, come ad esempio i sistemi operativi, le applicazioni e i database. Hai accesso limitato all'infrastruttura sottostante e sei responsabile dell'installazione del tuo software o chiedi al tuo provider di servizi di farlo. Sei responsabile di tutta la rimanente manutenzione, che include i service pack, il software antivirus e le patch.

Con il modello PaaS, il tuo provider è responsabile per i sistemi tramite il sistema operativo e per tutta la gestione dell'infrastruttura, che include le patch del sistema operativo, i ripristini dell'hardware e le impostazioni di rete. Tu crei e gestisci l'applicazione e tu o il tuo provider potete installare il middleware, inclusi i database e altri tipi. Questo modello viene utilizzato per sviluppare e verificare il software. Per ulteriori informazioni, consulta [A practical guide to platform as a service: What is PaaS ![Icona link esterno](../icons/launch-glyph.svg "Icona link esterno")](https://www.ibm.com/blogs/cloud-computing/2016/08/10/practical-guide-paas/){: new_window}.

Con il modello SaaS, il tuo provider gestisce i sistemi tramite l'applicazione attuale. L'applicazione è compatibile con il cloud e gli utenti possono utilizzare diversi endpoint per utilizzare il software, a seconda del provider. Il provider cloud è responsabile di tutta la gestione dell'infrastruttura e dell'applicazione, che include gli aggiornamenti del software i ripristini dell'hardware e le impostazioni di rete. Questo modello è spesso utilizzato nei modelli di licenza software a pagamento. Per ulteriori informazioni, vedi [SaaS applications for business and IT](https://www.ibm.com/cloud/saas){: new_window} ![Icona link esterno](../icons/launch-glyph.svg "Icona link esterno").

### Tipi di cloud
{: #cloud-types}

Esistono tre tipi diversi di cloud disponibili: pubblico, privato e ibrido. Un cloud pubblico include una serie di risorse condivisa di cui è stato eseguito il provisioning per consentire l'accesso alle risorse di un'azienda. È ospitato in un ambiente a più tenant su un server virtuale ed è possibile accedervi da qualsiasi luogo. 

Un cloud privato include le risorse di cui è stato eseguito il provisioning per consentire l'accesso alle risorse di un'azienda. È ospitato su un hardware dedicato, come ad esempio un server bere metal, ed è in loco nell'ufficio dell'azienda (o in più uffici) o in un provider cloud. È possibile accedere a un cloud privato da qualsiasi luogo.

Un cloud ibrido include le risorse che combinano gli aspetti dei cloud privato e pubblico. È ospitato in loco nell'ufficio dell'azienda (o in più uffici) e in un provider cloud. È possibile accedere a un cloud ibrido da qualsiasi luogo. 

## Pianificazione della tua infrastruttura
{: #planning}

Vuoi pianificare la tua infrastruttura prima di eseguirne il provisioning per assicurarti di ridimensionarla correttamente per il tuo carico di lavoro. {{site.data.keyword.cloud_notm}} ha diversi strumenti e siti per aiutarti nella progettazione e nello stabilire le dimensioni della tua infrastruttura. 

### Architettura dell'infrastruttura

Inizia con l'[architettura dell'infrastruttura ![Icona link esterno](../icons/launch-glyph.svg "Icona link esterno")](https://www.ibm.com/cloud/garage/architectures/infrastructure){: new_window} per avere una panoramica più approfondita dei tre tipi di ambienti cloud. 

### {{site.data.keyword.cloud_notm}} Design Decision Tool

Lo strumento [{{site.data.keyword.cloud_notm}} Design Decision Tool ![Icona link esterno](../icons/launch-glyph.svg "Icona link esterno")](https://github.com/ibm-cloud-architecture/infrastructure-design-decision-tool/){: new_window} ti aiuta a confrontare le alternative quando progetti e crei la tua soluzione personalizzata. Ogni componente dell'infrastruttura presenta descrizioni, considerazioni e avvertimenti e dei confronti affiancati. Puoi inoltre trovare un esempio su come utilizzare lo strumento.

### {{site.data.keyword.cloud_notm}} Stencils

[{{site.data.keyword.cloud_notm}} Stencils ![Icona link esterno](../icons/launch-glyph.svg "Icona link esterno")](https://github.com/ibm-cloud-architecture/ibm-cloud-stencils){: new_window} ti aiuta a creare un diagramma della tua architettura {{site.data.keyword.cloud_notm}} utilizzando degli strumenti popolari per la creazione di diagrammi. 

### Opzioni server bare metal

Utilizza [{{site.data.keyword.cloud_notm}} {{site.data.keyword.baremetal_short}} Search Tool ![Icona link esterno](../icons/launch-glyph.svg "Icona link esterno")](https://www.ibm.com/cloud-computing/bluemix/bare-metal-search){: new_window} per dimensionare e stimare le tue opzioni di server bare metal, inclusi i server che sono certificati per supportare i carichi di lavoro SAP HANA e SAP NetWeaver.

### Conformità e servizi {{site.data.keyword.cloud_notm}}

Come con qualsiasi architettura, dovresti considerare le risorse {{site.data.keyword.cloud_notm}} che potresti aggiungere alla tua soluzione quando stabilisci le dimensioni della tua infrastruttura. Per ulteriori informazioni, vedi [SaaS applications for business and IT ![Icona link esterno](../icons/launch-glyph.svg "Icona link esterno")](https://www.ibm.com/cloud/saas){: new_window} e cerca uno specifico servizio. Devi anche pensare a tutte le normative che devi considerare quando crei la tua architettura. Ad esempio, il tuo carico di lavoro è considerato sensibile o è regolamentato? Per ulteriori informazioni, vedi [Compliance ![Icona link esterno](../icons/launch-glyph.svg "Icona link esterno")](https://www.ibm.com/cloud/compliance){: new_window}.

## Creazione della tua infrastruttura
{: #build}

Dopo aver pianificato e progettato la tua infrastruttura, sei pronto per crearla. 

### Calcola
{: #compute}

Il tuo server è la base della tua infrastruttura. Hai diverse opzioni a seconda dei tuoi bisogni o puoi combinarle se è ciò che è richiesto dal tuo ambiente. Consulta la seguente tabella per un riepilogo delle tue opzioni di calcolo.

| Opzione | Descrizione | 
|--------|---------------|
| [{{site.data.keyword.baremetal_short}}](/docs/bare-metal?topic=bare-metal-about-bm#about-bm)  | Server a singolo tenant orari o mensili, a te dedicati e di cui nessuna loro parte, comprese le risorse server, è condivisa con altri clienti. |
| [{{site.data.keyword.BluVirtServers_short}}](/docs/vsi?topic=virtual-servers-getting-started-tutorial) | Server virtuali scalabili acquistati con allocazioni di memoria e core. |
| [{{site.data.keyword.vmwaresolutions_short}}](/docs/services/vmwaresolutions?topic=vmware-solutions-getting-started#getting-started) | Integra o migra velocemente e facilmente i carichi di lavoro VMware in loco utilizzando l'infrastruttura ad elevate prestazioni, sicura e scalabile e la tecnologia di virtualizzazione ibrida VMware leader nel settore. |
| [{{site.data.keyword.containerlong_notm}}](/docs/containers?topic=containers-container_index) | Combina i contenitori Docker e la tecnologia Kubernetes, un'esperienza utente intuitiva e la sicurezza e l'isolamento integrati per automatizzare la distribuzione, il funzionamento, il ridimensionamento e il monitoraggio di applicazioni caricate nei contenitori in un cluster di host di calcolo. |
| [{{site.data.keyword.cfee_full_notm}}](/docs/cloud-foundry?topic=cloud-foundry-about) | Istanzia più piattaforme Cloud Foundry isolate e di livello aziendale su richiesta. |
| [{{site.data.keyword.openwhisk_short}}](/docs/openwhisk?topic=cloud-functions-getting_started#getting_started) | Una piattaforma di programmazione FaaS (Functions-as-a-Service) basata su Apache OpenWhisk. |
{: caption="Tabella 1. Opzioni di calcolo" caption-side="top"}
   
### Archiviazione
{: #storage}

{{site.data.keyword.baremetal_short}} e {{site.data.keyword.BluVirtServers_short}} vengono forniti con l'archiviazione predefinita. I {{site.data.keyword.baremetal_short}} hanno un minimo di 1 TB di spazio su disco SATA e i {{site.data.keyword.BluVirtServers_short}} hanno un minimo di 25 GB di archiviazione SAN. L'eccezione è rappresentata dai {{site.data.keyword.baremetal_short}} con certificazione SAP {{site.data.keyword.cloud_notm}}. Per ulteriori informazioni sull'archiviazione predefinita disponibile con questi server, vedi [{{site.data.keyword.cloud_notm}} SAP-Certified Infrastructure](/docs/bare-metal?topic=bare-metal-sap-cert-infrastructure#sap-cert-infrastructure).

Puoi acquistare ulteriore archiviazione in base alle tue esigenze. Consulta la seguente tabella per un riepilogo delle tue opzioni di archiviazione.

| Opzione | Descrizione |
|--------|---------------|
| [{{site.data.keyword.blockstorageshort}}](/docs/infrastructure/BlockStorage?topic=BlockStorage-getting-started) | Archiviazione iSCSI persistente e a elevate prestazioni di cui viene eseguito il provisioning ed è gestita indipendentemente dalle istanze di calcolo. Le LUN Block Storage basate su iSCSI sono connesse ai dispositivi autorizzati tramite connessioni MPIO (multi-path I/O) ridondanti. |
| [{{site.data.keyword.filestorage_short}}](/docs/infrastructure/FileStorage?topic=FileStorage-getting-started) | File Storage persistente, veloce, collegato alla rete flessibile e basato su NFS. In questo ambiente NAS (network-attached storage), hai un controllo totale sulla funzione e le prestazioni delle tue condivisioni di file. Le condivisioni File Storage possono essere collegate fino a 64 dispositivi autorizzati su connessioni TCP/IP instradate per la resilienza. |
| [{{site.data.keyword.cos_full_notm}}](/docs/services/cloud-object-storage?topic=cloud-object-storage-getting-started) | Le informazioni memorizzate con IBM Cloud Object Storage vengono crittografate e diffuse in più ubicazioni geografiche e sono accessibili tramite HTTP utilizzando un'API REST. Questo servizio utilizza le tecnologie di archiviazione distribuita fornite da IBM Cloud Object Storage System (in precedenza Cleversafe). |
| [{{site.data.keyword.cloud_notm}} Master Data Management](/docs/services/MDMOnCloud?topic=MDMOnCloud-mdmoc_getting_started#mdmoc_getting_started) | Offload di grandi quantità di dati dal tuo data center in loco al tuo bucket Cloud Object Storage. |
| [{{site.data.keyword.backup_full}}](/docs/infrastructure/Backup?topic=Backup-getting-started) | Un sistema di backup basato sull'agent automatizzato che viene gestito tramite un programma di utilità di gestione basato sul browser. Puoi eseguire il backup dei dati tra i server in uno o più data center nella rete IBM Cloud. |
{: caption="Tabella 2. Opzioni di archiviazione" caption-side="top"}

### Rete
{: #network}

Ottieni automaticamente la connettività a {{site.data.keyword.vpn_full}} quando viene configurato il tuo account {{site.data.keyword.cloud_notm}}. Per impostazione predefinita, il tuo server ha un indirizzo IP pubblico e uno privato. Se vuoi che il tuo server sia privato, puoi disattivare l'interfaccia pubblica dopo che è stato eseguito provisioning del tuo server oppure ordinare il tuo server come privato. Per ulteriori informazioni, vedi [Introduzione alla VPN (Virtual Private Networking)](/docs/infrastructure/iaas-vpn?topic=VPN-gettingstarted-with-virtual-private-networking).

In un livello dell'infrastruttura, puoi creare un cloud privato virtuale, che è una rete virtuale collegata al tuo account {{site.data.keyword.cloud_notm}}. Un cloud privato virtuale ti offre un punto di ingresso che fornisce la sicurezza cloud e la capacità di ridimensionare dinamicamente le tue VSI (virtual server instance). Per ulteriori informazioni, vedi [Getting started with IBM Cloud Virtual Private Cloud (VPC) Infrastructure](/docs/vpc-on-classic?topic=vpc-on-classic-getting-started). 

Consulta la seguente tabella per un riepilogo delle tue opzioni di rete.

| Opzione | Descrizione | 
|--------|---------------|
| [Content Delivery Network](/docs/infrastructure/CDN?topic=CDN-getting-started) | Utilizzato per varie soluzioni di settore, tra cui media, intrattenimento, software, giochi, servizi bancari ed e-commerce, per soddisfare le esigenze delle tue attività commerciali. |
| [DNS (Domain Name Service)](/docs/cli/reference/ibmcloud?topic=cloud-cli-ibm-dev-tools-for-jetbrains) | Fornisce un'ubicazione centrale per visualizzare e gestire i tuoi domini tramite l'interfaccia di gestione DNS di base e ti fornisce anche l'opzione di gestire DNS inversi e secondari nella stessa ubicazione gratuitamente. |
| [Indirizzi IP globali](/docs/infrastructure/subnets?topic=subnets-about-global-ip-address#about-global-ip-address) | Forniscono la flessibilità e ti consentono di spostare i carichi di lavoro tra i server, anche tra data center geograficamente eterogenei. |
| [Bilanciamento del carico](/docs/infrastructure/loadbalancer-service?topic=loadbalancer-service-getting-started) | Distribuisce l'elaborazione e le comunicazioni su più server in un data center per evitare che un singolo dispositivo debba sopportare tutto il carico. |
| [VRA (Virtual Router Appliance)](/docs/infrastructure/virtual-router-appliance?topic=virtual-router-appliance-getting-started) | Instrada in modo selettivo il traffico di rete pubblico e privato tramite un router aziendale completo con firewall, modellamento del traffico, instradamento basato su politiche, VPN e un host di altre funzioni. |
| [VPN IPSec](/docs/infrastructure/iaas-vpn?topic=VPN-setup-ipsec-vpn#setup-ipsec-vpn) | Una suite di protocolli progettata per autenticare e crittografare tutto il traffico IP tra due ubicazioni utilizzando una modalità tunnel che fornisce una rete da sito a sito crittografata. |
| [{{site.data.keyword.cloud_notm}} Direct Link](/docs/infrastructure/direct-link?topic=direct-link-get-started-with-ibm-cloud-direct-link#get-started-with-ibm-cloud-direct-link) | Utilizza un provider Cloud Exchange per fornire la connettività alle ubicazioni dell'infrastruttura {{site.data.keyword.cloud_notm}}. |
{: caption="Tabella 3. Opzioni di rete" caption-side="top"}


## Gestione dell'infrastruttura
{: #managing}

Dopo aver creato la tua infrastruttura e il tuo ambiente, sei pronto per iniziare a gestirli.

| Attività | Descrizione |
|--------|---------------|
| [Monitora gli eventi di sistema](/docs/account?topic=account-audit-log) | Visualizza le azioni che sono state eseguite sulle tue risorse dell'infrastruttura. |
| [Configura le preferenze email](/docs/account?topic=account-email-prefs) | Configura le notifiche email dell'infrastruttura {{site.data.keyword.cloud_notm}} sugli eventi non pianificati, la manutenzione e gli annunci.  |
| [Comprendi come proteggere i tuoi dati](/docs/overview?topic=overview-security) | La piattaforma {{site.data.keyword.cloud_notm}} offre diversi livelli di controlli di sicurezza tra la rete e l'infrastruttura. |
| [Comprendi come puoi garantire nessun tempo di inattività](/docs/overview?topic=overview-zero-downtime) | Tutte le risorse {{site.data.keyword.cloud_notm}} sono ospitate in ubicazioni data center in tutto il mondo. |
{: caption="Tabella 4. Attività di gestione" caption-side="top"}

---


copyright:
  years: 2016, 2018
lastupdated: "2018-11-30"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# Cos'è la piattaforma {{site.data.keyword.Bluemix_notm}}?
{: #whatis}

La piattaforma cloud di IBM combina la soluzione PaaS (platform as a service) con la soluzione IaaS (infrastructure as a service) per fornire un'esperienza integrata. La piattaforma esegue il ridimensionamento e supporta sia le organizzazioni e i piccoli team di sviluppo che i grandi business aziendali. Distribuito globalmente tra i data center di tutto il mondo, la soluzione che crei su {{site.data.keyword.cloud}} si avvia velocemente e viene eseguita in modo affidabile in un ambiente supportato e verificato di cui ti puoi fidare.
{: .shortdesc}

La piattaforma {{site.data.keyword.Bluemix_notm}} è composta da più componenti che lavorano insieme per fornire un'esperienza cloud coerente e affidabile. 

  * Un catalogo composto da centinaia di offerte {{site.data.keyword.Bluemix_notm}} 
  * Una console solida che funge da frontend per la creazione, la visualizzazione e la gestione delle tue risorse cloud
  * Un componente di gestione dell'identità e dell'accesso che autentica in modo sicuro gli utenti per i servizi di piattaforma e controlla l'accesso alle risorse in modo coerente tramite {{site.data.keyword.Bluemix_notm}}
  * Un meccanismo di ricerca e contrassegno con tag per filtrare e identificare le tue risorse
  * Un sistema di gestione dell'account e della fatturazione che fornisce l'utilizzo esatto per i piani dei prezzi e la protezione antifrode della carta di credito

## Scelta del tuo ambiente host
{: #choose-compute}

Con {{site.data.keyword.Bluemix_notm}}, non devi più affrontare grandi investimenti in hardware per testare o eseguire una nuova applicazione. Saremo invece noi a gestire il tutto e pagherai solo per ciò che usi. Il tuo ambiente server cloud è la base del tuo livello dell'infrastruttura. Puoi scegliere una sola opzione o una combinazione per ambienti più complessi. 

Hai diverse opzioni per ospitare le tue applicazioni, fornendoti maggiore controllo sull'infrastruttura quando vuoi o ne hai bisogno. Puoi eseguire la tua applicazione in uno dei seguenti modi:

  * Come una funzione senza server
  * Come un'applicazione Cloud Foundry
  * Come un contenitore Docker su un cluster Kubernetes
  * Come VMware
  * Come una macchina virtuale
  * Su {{site.data.keyword.baremetal_short}} ad elevate prestazioni 

{{site.data.keyword.baremetal_short}} sono server fisici a singolo tenant dedicati a un solo cliente. Controlli quasi tutto dall'host del server alla RAM e ai dispositivi di archiviazione. Questi server sono utilizzati con dei carichi di lavoro che richiedono potenza di calcolo per un lungo periodo, ad esempio, diversi mesi. 

{{site.data.keyword.BluVirtServers_short}} possono essere distribuiti come istanze pubbliche o dedicate. Con le istanze pubbliche, le risorse del server vengono condivise con altri clienti, noti anche come un ambiente a più tenant. Le istanze private dedicano le risorse del server fisico a un cliente che può avere più di una macchina virtuale sullo stesso server. Questi server sono ideali per i carichi di lavoro che sono in esecuzione per un periodo di tempo limitato, ad esempio, un paio di settimane. Alcuni esempi di carico di lavoro sono sviluppo e test, backup e ripristino e ripristino di emergenza. Per ulteriori informazioni sulle opzioni server, consulta [Bare metal servers vs. virtual servers: Choosing the best option for you](https://www.ibm.com/blogs/bluemix/2018/06/bare-metal-virtual-servers-works/){: new_window} ![Icona link esterno](../icons/launch-glyph.svg "Icona link esterno").

Consulta la seguente tabella per un riepilogo delle tue opzioni di calcolo.

| Opzione | Descrizione | 
|--------|---------------|
| [{{site.data.keyword.baremetal_short}}](/docs/bare-metal/about.html)  | Server a singolo tenant orari o mensili, a te dedicati e di cui nessuna loro parte, comprese le risorse server, è condivisa con altri clienti. |
| [{{site.data.keyword.BluVirtServers_short}}](/docs/vsi/vsi_about.html) | Server virtuali scalabili acquistati con allocazioni di memoria e core dedicati. |
| [{{site.data.keyword.vmwaresolutions_short}}](/docs/services/vmwaresolutions/vmonic/prod_overview.html) | Integra o migra velocemente e facilmente i carichi di lavoro VMware in loco utilizzando l'infrastruttura ad elevate prestazioni, sicura e scalabile e la tecnologia di virtualizzazione ibrida VMware leader nel settore. |
| [{{site.data.keyword.containerlong_notm}}](/docs/containers/cs_why.html) | Combina i contenitori Docker e la tecnologia Kubernetes, un'esperienza utente intuitiva e la sicurezza e l'isolamento integrati per automatizzare la distribuzione, il funzionamento, il ridimensionamento e il monitoraggio di applicazioni caricate nei contenitori in un cluster di host di calcolo. |
| [{{site.data.keyword.cfee_full_notm}}](/docs/cloud-foundry/index.html) | Istanzia più piattaforme Cloud Foundry isolate e di livello aziendale su richiesta. |
| [{{site.data.keyword.openwhisk_short}}](/docs/openwhisk/index.html) | Una piattaforma di programmazione FaaS (Functions-as-a-Service) basata su Apache OpenWhisk. |
{: caption="Tabella 1. Opzioni di calcolo" caption-side="top"}

## Creazione di applicazioni
{: #build-apps}

Se hai del [codice esistente](/docs/apps/tutorials/tutorial_byoc.html) che vuoi modernizzare e portare nel cloud o stai sviluppando una [nuova applicazione](/docs/apps/tutorials/tutorial_starter-kit.html), i tuoi sviluppatori possono attingere all'ecosistema in continua espansione di framework di runtime e servizi disponibili in {{site.data.keyword.Bluemix_notm}}.

Le [Guide alla programmazione](https://cloud.ibm.com/docs/home/build){: new_window} ![Icona link esterno](../icons/launch-glyph.svg "Icona link esterno") sono disponibili per linguaggio per aiutarti ad essere operativo. Hai molte opzioni per ospitare le tue applicazioni con l'infrastruttura {{site.data.keyword.Bluemix_notm}} dai {{site.data.keyword.baremetal_short}} da eseguire come una funzione senza server.

## Connessione dei servizi 
{: #connect-services}

Con più di 190 servizi tra cui scegliere nel catalogo, puoi creare una soluzione personalizzata che soddisfi i tuoi bisogni. Puoi connettere facilmente i servizi alle applicazioni all'esterno di {{site.data.keyword.Bluemix_notm}} se si adatta al tuo caso di utilizzo. Puoi generare una nuova serie di credenziali per i casi in cui vuoi collegare manualmente un consumatore esterno a un servizio {{site.data.keyword.Bluemix_notm}}. Ad esempio, se stai tentando di collegare un'applicazione all'esterno di {{site.data.keyword.Bluemix_notm}} a un servizio Watson, genera una nuova credenziale che li collega tra loro. È così facile! Per ulteriori informazioni, vedi [Aggiunta di una credenziale](/docs/resources/service_credentials.html#service_credentials).

## Configurazione del tuo account

Se stai soltanto provando {{site.data.keyword.Bluemix_notm}}, puoi andare direttamente al catalogo e iniziare a consultare i servizi che vuoi esplorare e aggiungerli al tuo account Lite o di prova. Tuttavia, se sei pronto per iniziare ad utilizzare un ambiente per un gruppo di sviluppatori o per un'intera organizzazione e hai delle applicazioni in esecuzione nella produzione, prendi in considerazione di configurare le informazioni di base nel tuo account:

* Gruppi di accesso utenti per l'organizzazione degli utenti e degli ID del servizio in una sola entità per rendere l'assegnazione dell'accesso un processo semplice.
* Gruppi di risorse per l'organizzazione delle tue risorse per eseguire l'assegnazione dell'accesso a una serie di risorse in modo veloce e semplice.
* Politiche di accesso per i tuoi gruppi di accesso o sviluppatori individuali che necessitano delle politiche di accesso IAM o dei ruoli dell'organizzazione e dello spazio Cloud Foundry.

Per ulteriori informazioni, consulta le [procedure consigliate per la configurazione del tuo account](/docs/account/bp_account.html#account_setup) e le [procedure consigliate per l'assegnazione dell'accesso](/docs/iam/bp_access.html). Inoltre, se sei pronto ad approfondire, consulta le parti della [gerarchia dell'account](/docs/account/account_overview.html#overview).

## Prezzi e fatturazione 

Indipendentemente dal tuo tipo di account, puoi esplorare {{site.data.keyword.Bluemix_notm}} utilizzando i piani Lite per i servizi che forniscono una quota gratuita. Quando stai scegliendo un servizio dal catalogo e selezioni un tile, se esistono diversi tipi di piani disponibili, puoi visualizzare i dettagli sulle informazioni sui prezzi. Se scegli un piano del servizio con un piano a pagamento, puoi stimare i tuoi costi utilizzando lo strumento di stima dei costi. Per ulteriori informazioni, vedi [Stima dei costi](/docs/billing-usage/estimating_costs.html#cost). 

La fatturazione {{site.data.keyword.Bluemix_notm}} fornisce più servizi che garantiscono che la piattaforma {{site.data.keyword.Bluemix_notm}} possa gestire in modo sicuro i prezzi, gli account, l'utilizzo e altro.

### Gestione dell'account {{site.data.keyword.Bluemix_notm}} 
{: #account}

La gestione dell'account mantiene la relazione di fatturazione con il cliente. Ogni account è un'entità di fatturazione che rappresenta un cliente. Questo servizio controlla il ciclo di vita, la sottoscrizione, la relazione utente e l'organizzazione dell'account.

### Prezzi di {{site.data.keyword.Bluemix_notm}} 
{: #pricing}

Il servizio della piattaforma dei prezzi {{site.data.keyword.Bluemix_notm}} aiuta gli utenti a definire, gestire e richiamare le informazioni sui prezzi per le risorse nel catalogo {{site.data.keyword.Bluemix_notm}}.

### Raccoglitore della misurazione {{site.data.keyword.Bluemix_notm}} 
{: #metering}

La misurazione dell'utilizzo di {{site.data.keyword.Bluemix_notm}} è un servizio della piattaforma che abilita i provider di servizi ad inviare le metriche raccolte per le istanze della risorsa di cui è stato eseguito il provisioning dagli utenti {{site.data.keyword.Bluemix_notm}}. I provider di servizi di terze parti che forniscono un servizio di fatturazione integrato in {{site.data.keyword.Bluemix_notm}} devono inoltrare l'utilizzo per tutte le istanze del servizio attivo ogni ora. L'invio è importante perché la mancata notifica dell'utilizzo può portare alla perdita della raccolta di ricavi per IBM, causando di conseguenza una perdita della quota di ricavi per il provider di servizi di terze parti.


## {{site.data.keyword.Bluemix_notm}} IAM (Identity and Access Management)
{: #iam}

{{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) ti consente di autenticare in modo sicuro gli utenti per i servizi di piattaforma e controllare l'accesso alle risorse in modo coerente attraverso la piattaforma {{site.data.keyword.Bluemix_notm}}. Per ulteriori dettagli, consulta [Cos'è IAM?](/docs/iam/index.html) IAM fornisce i comandi CLI e le API che ti aiutano a gestire i token, i gruppi di accesso e le politiche.


## Creazione delle risorse
{: #provisioning-layer}

Il controller delle risorse è il livello di provisioning della piattaforma {{site.data.keyword.Bluemix_notm}} di nuova generazione che gestisce il ciclo di vita delle risorse {{site.data.keyword.Bluemix_notm}} in un account del cliente. Viene eseguito il provisioning delle risorse globalmente in un ambito dell'account. Il controller delle risorse supporta il provisioning sincrono e asincrono delle risorse. Il livello di provisioning è responsabile del controllo e della traccia del ciclo di vita delle risorse in un account del cliente. Le risorse sono componenti fisici o logici di cui è possibile eseguire il provisioning, o che possono essere riservati, per un'istanza dell'applicazione o del servizio. Esempi di risorse includono database, account, processori, memoria e limiti di archiviazione. In generale, è previsto che alle risorse tracciate dal livello di provisioning siano associate delle metriche di utilizzo e una fatturazione ma non è sempre così. In alcuni casi, la risorsa può essere associata al livello di provisioning per garantire che il ciclo di vita della risorsa possa essere gestito insieme al ciclo di vita dell'account. Il controller delle risorse utilizza IAM per l'autenticazione e l'autorizzazione delle azioni eseguite sul livello di provisioning. 

### Gestione del ciclo di vita della risorsa
{: #lifecycle}

Il controller delle risorse fornisce delle API comuni per controllare il ciclo di vita delle risorse che va dal provisioning (creazione di un'istanza) all'esecuzione del bind (creazione delle credenziali di accesso), all'annullamento del bind (rimozione dell'accesso) e all'annullamento del provisioning (eliminazione di un'istanza). 

Il controller delle risorse fornisce le API che ti aiutano a gestire i seguenti elementi del tuo ciclo di vita delle risorse:
* Provisioning
* Aggiornamento di un'istanza della risorsa
* Esecuzione del bind
* Chiavi di risorsa
* Annullamento del bind
* Annullamento del provisioning


## Gestione delle tue risorse 
{: #resource-manager}


Il gestore delle risorse {{site.data.keyword.Bluemix_notm}} gestisce la raccolta di risorse dai [gruppi di risorse](/docs/overview/resource-groups.html#whatis). Un gruppo di risorse appartiene a un account. Deve essere eseguito il provisioning di tutte le risorse {{site.data.keyword.Bluemix_notm}} all'interno di un gruppo di risorse. Se un account viene sospeso, viene sospeso anche il gruppo di risorse corrispondente e lo sono anche tutte le risorse al suo interno. Quando un utente crea un account, viene creato un gruppo di risorse predefinito nell'account. Deve essere eseguito il provisioning di tutte le risorse abilitate IAM {{site.data.keyword.Bluemix_notm}} all'interno di un gruppo di risorse. Se un account viene sospeso, viene sospeso anche il gruppo di risorse corrispondente e lo sono anche tutte le risorse al suo interno. Per l'account standard, un utente può avere un solo gruppo di risorse. Per un account Pagamento a consumo o Sottoscrizione, a un utente è consentito creare più di un gruppo di risorse. 


## Catalogo {{site.data.keyword.Bluemix_notm}}
{: #catalog}

Il catalogo {{site.data.keyword.Bluemix_notm}} archivia le definizioni di offerte (descrizione, funzioni, immagini, URL e così via) delle risorse visualizzate nella console{{site.data.keyword.Bluemix_notm}}. Il servizio del catalogo gestisce le offerte attraverso più regioni geografiche come il system of record. Il catalogo supporta le CLI e un'API RESTful in cui puoi richiamare le informazioni sulle offerte esistenti e creare, gestire ed eliminare le loro offerte. Inizia con l'URL di base e utilizza gli endpoint per richiamare i metadati sui servizi nel catalogo e gestire la visibilità del servizio. A seconda del tipo di oggetto, i metadati possono includere le informazioni sui prezzi, sul provisioning, sulle regioni e altro. Per ulteriori informazioni, vedi la [documentazione sulla Gestione del catalogo](/docs/overview/catalog.html#global-catalog-overview).

## Ricercare e contrassegnare con tag le risorse 
{: #search-and-tag}

Il servizio di ricerca è un repository di proprietà della risorsa condiviso e globale integrato nella piattaforma {{site.data.keyword.Bluemix_notm}}. Viene utilizzato per archiviare e ricercare gli attributi della risorsa cloud. Categorizza e classifica le risorse. Una risorsa è controllata e gestita dai provider della risorsa all'interno della piattaforma {{site.data.keyword.Bluemix_notm}}, come ad esempio Cloud Foundry, IBM Containers o Resource Controller. Le risorse vengono identificate in modo univoco da un identificativo [CRN (Cloud Resource Name)](/docs/overview/crn.html#crn). Le proprietà di una risorsa includono delle proprietà di sistema e delle tag. Entrambe le proprietà sono definite all'interno di un account di fatturazione {{site.data.keyword.Bluemix_notm}} e si estendono su molte regioni.

Questo servizio gestisce anche le tag che vengono associate a una risorsa. Puoi creare, eliminare, ricercare, collegare o annullare il collegamento delle tag con l'API Tagging. Le tag vengono identificate in modo univoco da un identificativo CRN (Cloud Resource Name). Le tag hanno un nome, che deve essere univoco all'interno di un account di fatturazione. Puoi creare le tag nel formato etichetta o `key:value`.


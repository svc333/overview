---

copyright:
  years: 2016, 2017, 2018
lastupdated: "2018-03-16"

---
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}
{:tip: .tip}

# Esplora l'esperienza di sviluppo in {{site.data.keyword.cloud_notm}}
{: #dev-journey}

Come sviluppatore, {{site.data.keyword.cloud}} hai una serie di funzionalità per iniziare a creare le applicazioni in pochi minuti. Nei nostri dashboard di sviluppo puoi:

* Selezionare i kit starter che sono specifici per il caso di utilizzo e creare le applicazioni starter pronte per la produzione in diversi linguaggi di programmazione e modelli architetturali
* Eseguire il provisioning dei servizi automaticamente come parte della creazione del progetto del tuo kit starter
* Utilizzare una struttura del progetto dell'applicazione portatile che ti consente di gestire i componenti della tua applicazione
* Creazione con un solo clic di una [toolchain DevOps](../services/ContinuousDelivery/index.html#cd_getting_started).
* Utilizzare un'[interfaccia riga di comando](/docs/cli/idt/index.html) per lo sviluppo locale

Per comprendere come l'esperienza di sviluppo {{site.data.keyword.cloud_notm}} può aiutarti a creare rapidamente applicazioni di alta qualità pronte per la produzione, diamo un'occhiata a questi elementi in modo più dettagliato.

## Dashboard di sviluppo
{: #dev-dashboards}

{{site.data.keyword.cloud_notm}} ha dashboard di sviluppo in diverse aree di interesse (come Watson, Security o Finance) o un canale digitale (come Mobile o Applicazioni Web). Puoi accedere a questi dashboard dall'**icona Menu**  ![icona Menu](../icons/icon_hamburger.svg).

Ogni dashboard di sviluppo fornisce kit starter rilevanti per l'area specifica del dashboard e offre un flusso di lavoro coerente e intuitivo che ti consente di creare un'applicazione pronta per la produzione da utilizzare in pochi minuti.

## Progetti applicazione
{: #app-projects}

Un progetto è l'associazione di codice, dati, servizi e toolchain che compongono la tua applicazione. Ad esempio, il progetto mobile {{site.data.keyword.cloud_notm}} contiene il codice per l'applicazione e la logica di backend, l'archiviazione dei dati, i servizi di analisi e di sicurezza ed è configurato per la fornitura continua.

![Riutilizzo](images/garage_reuse2.png "L'esperienza di sviluppo ti consente il riutilizzo e di evitare di reinventare")

Puoi creare e gestire un progetto utilizzando qualsiasi dashboard di sviluppo {{site.data.keyword.cloud_notm}} o {{site.data.keyword.dev_cli_notm}}.

## Kit starter
{: #starter-kits}

Con i kit starter, {{site.data.keyword.cloud_notm}} genera un'applicazione di produzione di base, nel linguaggio desiderato, pronta per la distribuzione cloud. Ogni kit starter include un linguaggio, un framework e un modello per un caso di utilizzo specifico e ti consente di riutilizzare il codice.

### Come i kit starter si differenziano dagli esempi?
I kit starter sono pronti per la produzione e si focalizzano sulla dimostrazione di un'implementazione del modello chiave utilizzando un runtime (ad esempio Node.js e Express). In alcuni casi, i kit starter offrono un'esperienza utente semplice per sottolineare l'integrazione del servizio. In altri casi i kit starter rappresentano un'implementazione personalizzabile di un caso di utilizzo sofisticato.

* Un **frammento** è un paio di righe di codice che viene spesso presentato in una IDE. I frammenti aiutano uno sviluppatore ad integrare una sintassi del linguaggio di programmazione o del supporto con una API definita.
* Una **demo** è solitamente di elevata qualità e accuratezza e utilizza una gamma di servizi e punti di integrazione. Spesso richiede del tempo di configurazione e viene utilizzata per dimostrare un problema di business o una funzione della piattaforma. Viene utilizzata per valutare le fasi di adozione cloud. Alcune volte il suo codice viene incluso nel codice di produzione.
* Un **esempio** è un piccolo esempio di una funzionalità, funzione, servizio o esperienza dell'utente specifici. Un esempio può essere riutilizzato o incluso in un'applicazione di produzione. Viene generalmente utilizzato per mostrare le funzionalità tecniche e un approccio possibile per risolvere un problema tecnico.
* **kit starter** è un modello pronto per la produzione che può essere integrato con una serie di servizi per generare un asset pronto per la produzione che può essere distribuito direttamente in una pipeline DevOps e un cluster Kubernetes. Un kit starter contiene i metadati descrittivi fornendo all'utente informazioni sufficienti per sapere cosa fa. Contiene inoltre le istruzioni che indicano a {{site.data.keyword.cloud_notm}} cosa produrre. L'output è subito pronto per la produzione e può essere ripetuto per ulteriori miglioramenti in base alle pratiche consigliate da IBM. Il contenuto del kit starter non è così complesso come una dimostrazione e non è banale come un frammento o un esempio. Sono creati dinamicamente in base ai requisiti dello sviluppatore.

## Risorse di provisioning automatico
{: #auto-provision}

Se un kit starter specifica le risorse necessarie, {{site.data.keyword.cloud_notm}} crea automaticamente le istanze per quelle risorse quando crei il tuo progetto. Tieni presente che puoi anche eseguire il provisioning manualmente delle risorse o selezionare le istanze della risorsa esistente da aggiungere al tuo progetto dopo averlo creato. Puoi vedere un elenco di istanze del servizio associate al tuo progetto nella vista dei dettagli del progetto insieme alle credenziali nel caso ne avessi bisogno.

## Codice portatile
{: #portable-code}

La creazione di un'applicazione da un kit starter crea automaticamente il codice al tuo posto che ha un formato coerente ed è indipendente dal runtime. Puoi distribuire il codice nel tuo ambiente di scelta, ad esempio Kubernetes o Cloud Foundry, senza fare modifiche.

### Quale codice viene creato?
Il codice creato da un kit starter {{site.data.keyword.cloud_notm}} ha quattro componenti fondamentali: la logica del caso di utilizzo, i componenti del linguaggio, l'abilitazione del servizio e l'abilitazione cloud. La generazione di questi componenti ti consente di risparmiare del tempo prezioso e ti assicura di stare utilizzando un'architettura all'avanguardia.

* **Logica del caso di utilizzo** fornisce funzioni per la funzione principale di un caso di utilizzo particolare. Gli esempi potrebbero essere il codice per un servizio chat di Watson Conversation o il codice per un'applicazione Visual recognition mobile.
* **Componenti del linguaggio** sono file e componenti del codice specifici per il linguaggio di programmazione che selezioni per il tuo kit starter. Ad esempio, i programmatori node.js avranno bisogno di un file package.json per la gestione della dipendenza e questo file viene automaticamente creato per te.
* **Abilitazione del servizio** è il codice che consente alla tua applicazione di collegarsi e utilizzare i servizi che aggiungi al tuo progetto. Gestione delle credenziali, codice di inizializzazione e SDK specifici del servizio sono esempi di elementi di abilitazione del servizio.
* **Abilitazione cloud** è il codice che consente alla tua applicazione l'esecuzione su {{site.data.keyword.cloud_notm}}. Ad esempio, i grafici Helm che consentono alla tua applicazione l'esecuzione su un cluster Kubernetes {{site.data.keyword.cloud_notm}}.

L'applicazione prodotta da {{site.data.keyword.cloud_notm}} non dispone solo dell'architettura, ma riflette anche le pratiche migliori per il linguaggio che hai scelto per il tuo progetto.  

Il progetto include un file readme che contiene i dettagli tecnici del progetto e spiega cosa è necessario per avere la tua applicazione in esecuzione se non lo è immediatamente.
{: tip}

## Toolchain DevOps
{: #devops}

DevOps comprende le procedure e gli strumenti per l'accesso, lo sviluppo, la distribuzione e l'utilizzo della tua applicazione. Una toolchain DevOps è una serie di servizi collegati che automatizzano le attività DevOps. È possibile eseguire DevOps manualmente con applicazioni molto semplici, ma il bisogno di automazione aumenta rapidamente con la complessità dell'applicazione e l'automazione toolchain è indispensabile per la fornitura continua.

Il componente principale di una toolchain DevOps è un repository di controllo della versione del codice come GitHub. Strumenti aggiuntivi possono includere la traccia di backlog, la pipeline di fornitura, l'IDE e il servizio di monitoraggio come [{{site.data.keyword.cloud_notm}}DevOps Insights](../services/DevOpsInsights/index.html#gettingstarted).

Se hai creato un progetto utilizzando un kit starter, puoi creare una nuova toolchain e distribuire la tua applicazione semplicemente facendo clic su **Distribuisci al cloud** nella vista dei dettagli del progetto. È stata creata una toolchain che dispone di un repository del codice, un repository dei problemi, la pipeline di fornitura e l'IDE web.

Puoi quindi utilizzare questa toolchain per ospitare più team e distribuire ad ambienti separati per lo sviluppo, il test e la produzione e stabilire un modello di fornitura continua collaborativo a livello aziendale per la tua applicazione.  

![Fornitura continua](images/garage_continuous_delivery2.png "L'esperienza di sviluppo configura la fornitura continua nel tuo ramo di sviluppo")

Puoi anche dare una rapida occhiata al tuo codice del progetto facendo clic sul pulsante **Download** nella pagina della panoramica progetto del dashboard di sviluppo. Il tuo codice viene scaricato come un file `.zip` contenente la struttura del progetto completa. Puoi facilmente estrarre il file ed eseguire il codice localmente utilizzando la {{site.data.keyword.dev_cli_notm}} o aggiungerlo al tuo repository di gestione del codice.

## Interfaccia riga di comando
{{site.data.keyword.dev_cli_notm}} ti abilita a codificare, creare ed eseguire il tuo progetto localmente.  Un modello comune è di creare il tuo progetto tramite un dashboard di sviluppo, utilizza {{site.data.keyword.dev_cli_notm}} per sviluppare localmente e poi trasmetti gli aggiornamenti al tuo repository e uniscili per avviare la tua toolchain di distribuzione.

## Sviluppo del metodo Garage
{: #developer_concepts}

Controlla il [metodo Garage](https://www.ibm.com/cloud/garage/) per informazioni su come IBM può aiutarti a sviluppare le applicazioni nella tua organizzazione.  

![Panoramica fasi metodo Garage](images/garage_phases_overview2.png "Panoramica fasi metodo Garage")*Panoramica fasi metodo Garage*

{{site.data.keyword.cloud_notm}} ti aiuta a produrre correttamente le applicazioni di produzione al livello aziendale utilizzando il metodo Garage o qualsiasi metodo preferisci. Per capire meglio cosa {{site.data.keyword.cloud_notm}} ha da offrire agli sviluppatori, diamo un'occhiata veloce alle competenze necessarie per creare un'applicazione moderna.

## Competenze dello sviluppatore
{: #skills}

Al giorno d'oggi gli utenti si aspettano molto di più dalle loro applicazioni rispetto a prima. Vogliono applicazioni per fornire informazioni approfondite da dati in tempo reale e archiviati, che sono sempre disponibili e che soddisfano i loro bisogni individuali più accuratamente. Per soddisfare queste aspettative, i creatori dell'applicazione devono riunire tra loro diverse serie di competenze. Ad esempio, un'applicazione cognitiva sofisticata, può richiedere contributi di sviluppatori digitali, di sviluppatori nativi cloud, di sviluppatori di flussi, di data scientist e di specialisti DevOps.

 ![Tipi di sviluppatore](images/developer_skills.png "Relazioni tra sviluppatori")

* **Sviluppatori digitali** autore in un canale digitale particolare come web mobile, voce e chat. Gli sviluppatori digitali sono generalmente concentrati sui casi di utilizzo e soddisfano direttamente i bisogni degli utenti come un'esperienza completa.
* **Sviluppatori nativi cloud** specializzati in costruzione e interconnessione dei componenti cloud. Gli autori di microservizi e back-end-for-frontend rientrano in questa categoria.
* **Sviluppatori flussi** si concentrano sull'elaborazione e l'ottenimento delle informazioni dai flussi di dati. Ad esempio, uno sviluppatore dei flussi può analizzare e avviare un'azione sul testo in entrata, sull'audio o sui flussi video.
* **Data scientist** utilizzano le analisi e il machine learning per produrre modelli predittivi. Questi modelli sono utilizzati nelle metriche di business e forniscono informazioni approfondite agli utenti dell'applicazione.
* **Specialisti DevOps** sono esperti nella risoluzione dei problemi di distribuzione e della toolchain. Per le applicazioni semplici, gli specialisti dedicati non sono generalmente necessari poiché i membri del team di sviluppo gestiscono DevOps con la squadra. Ma per le applicazioni aziendali complesse, con molte dipendenze, gli specialisti DevOps sono essenziali per mantenere la tua applicazione correttamente in produzione.

Le funzionalità degli sviluppatori integrate in {{site.data.keyword.cloud_notm}} si allineano su queste serie di competenze e consentono al tuo team di utilizzare una piattaforma per produrre, distribuire, eseguire e gestire la tua applicazione. Ad esempio, uno sviluppatore digitale che crea un'applicazione mobile potrebbe utilizzare il {{site.data.keyword.cloud_notm}} [Dashboard di sviluppo mobile](https://console.bluemix.net/developer/mobile/dashboard), un creatore dell'applicazione cognitiva potrebbe utilizzare il [Dashboard di sviluppo Watson](https://console.bluemix.net/developer/watson/dashboard) insieme a [Watson Studio](https://console.bluemix.net/catalog/services/watson-studio), uno sviluppatore dei flussi può utilizzare le [Analisi in tempo reale di IBM](../services/StreamingAnalytics/index.html#gettingstarted) e il [Servizio di fornitura continua di {{site.data.keyword.cloud_notm}}](../services/ContinuousDelivery/index.html#cd_getting_started) semplificando il lavoro di uno specialista DevOps.

Pronto per iniziare? [Fai clic qui](../apps/index.html) per creare un'applicazione su {{site.data.keyword.cloud_notm}} adesso!

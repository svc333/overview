---

copyright:

  years: 2018

lastupdated: "2018-11-28"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:pre: .pre}
{:table: .aria-labeledby="caption"}
{:note: .deprecated}


# Come garantisco nessun tempo di inattività?
{: #zero-downtime}

La tua strategia globale è importante. Puoi specificare un data center o un'ubicazione specifici per distribuire i tuoi dati nella parte corretta del mondo per i tuoi clienti.
{:shortdesc}

I servizi della piattaforma {{site.data.keyword.Bluemix}} sono autogestiti. Questo significa che le ubicazioni in cui puoi distribuire la tua applicazione possono diffondere i carichi di lavoro nei data center. Puoi anche garantire che sia implementato un design di failover, il che significa che la tua applicazione è sempre attiva e in esecuzione per i tuoi clienti. Per le tue risorse dell'infrastruttura, puoi selezionare i singoli data center in cui vengono distribuite le risorse. 

Tutte le risorse {{site.data.keyword.Bluemix_notm}} sono ospitate in ubicazioni data center in tutto il mondo. L'alta disponibilità e il ripristino di emergenza non sono universali in tutti i servizi e, pertanto, il tipo di alta disponibilità e ripristino di emergenza disponibile dipende dal servizio che stai utilizzando.  

## Ripristino di emergenza
{: #disaster-recovery}

Con un ripristino di emergenza, puoi superare una perdita di disponibilità o un malfunzionamento di grave entità in una singola ubicazione. Per garantire che il ripristino di emergenza sia implementato, è necessario distribuire diversi ambienti {{site.data.keyword.Bluemix_notm}} in più ubicazioni per evitare dei singoli punti di errore. Questi ambienti possono essere una combinazione di piattaforme pubbliche, dedicate o locali.  

### Piano di ripristino di emergenza 

{{site.data.keyword.Bluemix_notm}} rispetta i requisiti per la pianificazione per un'emergenza e ogni applicazione ha un piano per consentirti il ripristino o il riavvio dopo un evento di emergenza. Il ripristino è da backup elettronici presso un centro di ripristino o strutture di calcolo alternative che ripristinano il calcolo. Prima di qualsiasi potenziale emergenza, il piano di ripristino di emergenza include i requisiti di sistemi e host per le funzionalità di backup offsite, connettività di rete, software e hardware.

Il seguente elenco include i requisiti del piano di ripristino di emergenza:

- Per il bilanciamento del carico, esiste un documento per spiegare in che modo il servizio di calcolo resta disponibile. 
- Laddove si verifica un failover che interessa più siti, il piano di ripristino di emergenza deve spiegare chi fa cosa per causare il failover e garantire il riavvio. 
- Il piano di ripristino di emergenza deve definire come funziona la soluzione e qual è la perdita di dati. 
- Deve confermare in che modo viene soddisfatto il tempo di inattività tollerabile massimo e deve essere archiviato nel database dei piani di ripristino di emergenza.  
- Il piano di ripristino di emergenza specifica i controlli di sicurezza per l'esecuzione in modalità di emergenza, se sono diversi da quanto è in esecuzione in produzione. 

### Gestione del piano di ripristino di emergenza 

I requisiti rispettati da {{site.data.keyword.Bluemix}} sono: 

- Il piano di ripristino di emergenza deve essere aggiornato dopo qualsiasi modifica dell'infrastruttura di notevole entità e qualsiasi release principale dell'applicazione e dopo qualsiasi test. 
- Deve essere approvato annualmente. 

## Ubicazioni per la distribuzione della risorsa 
{: #ov_intro_reg}

Puoi creare applicazioni e istanze del servizio in ubicazioni differenti con la stessa infrastruttura {{site.data.keyword.cloud_notm}} per la gestione di applicazioni e la stessa vista dei dettagli di utilizzo per la fatturazione. Puoi distribuire le tue applicazioni all'ubicazione più vicina ai tuoi clienti per raggiungere una bassa latenza dell'applicazione. 

Per far fronte ai problemi di sicurezza, puoi anche selezionare l'ubicazione in cui desideri conservare i dati delle applicazioni. Quando crei applicazioni in più di un'ubicazione, se un'ubicazione non è più disponibile, le applicazioni che si trovano nelle altre ubicazioni continuano a essere eseguite. La disponibilità di risorse è la stessa per ogni ubicazione che usi. Per ulteriori informazioni sulle risorse della piattaforma e sulle ubicazioni in cui sono disponibili, consulta [Disponibilità dei servizi](/docs/resources/services_region.html#services_region).

Il bilanciamento del carico globale per la console {{site.data.keyword.cloud_notm}} garantisce che, se l'ubicazione geografica a te più prossima non è disponibile, la console visualizza le informazioni per la successiva ubicazione più prossima. In questo modo, puoi sempre accedere alla console senza eseguire alcuna azione per accedere alle risorse di cui hai bisogno.

Puoi visualizzare tutte le risorse in tutte le ubicazioni per impostazione predefinita dalla vista di elenco risorse nella console. Se vuoi visualizzare e gestire le risorse in una specifica ubicazione, espandi il menu **UBICAZIONE** e seleziona un'ubicazione dall'elenco. 

Puoi inoltre utilizzare l'interfaccia riga di comando (CLI, command-line interface) per connetterti all'ubicazione {{site.data.keyword.cloud_notm}} con cui vuoi lavorare utilizzando il comando `ibmcloud api` e specificando l'endpoint API dell'ubicazione. Ad esempio, immetti il seguente comando per stabilire una connessione all'ubicazione {{site.data.keyword.cloud_notm}} Londra:

```
ibmcloud api https://api.eu-gb.bluemix.net
```

A ciascuna ubicazione viene assegnato un prefisso univoco. {{site.data.keyword.cloud_notm}} fornisce le seguenti ubicazioni e i seguenti prefissi di ubicazione.

| **Ubicazione**  | **Endpoint API**        |
|---------------|-------------------------|
| Dallas        | api.ng.bluemix.net      |
| Sydney        | api.au-syd.bluemix.net  |
| Francoforte     | api.eu-de.bluemix.net   |
| Londra        | api.eu-gb.bluemix.net   |
| Washington DC | api.us-east.bluemix.net |
{: caption="Tabella 1. Elenco di ubicazioni {{site.data.keyword.cloud_notm}}" caption-side="top"}

Quando distribuisci le risorse dell'infrastruttura, hai più opzioni relative a dove si trovano i tuoi dati. Puoi effettuare la selezione in un elenco di data center in {{site.data.keyword.Bluemix_notm}}. 

## Data center
{: #data_center}

Un data center è un'ubicazione fisica che ospita le risorse di alimentazione, raffreddamento, calcolo, rete e archiviazione utilizzate per i servizi e le applicazioni. I data center non forniscono un isolamento da malfunzionamenti locali simile alle zone multiple in un'ubicazione. Per ulteriori informazioni, vedi [Global locations for your global business ![Icona link esterno](../icons/launch-glyph.svg "Icona link esterno")](https://www.ibm.com/cloud/data-centers/){: new_window}.

{{site.data.keyword.Bluemix_notm}} offre dei data center in molte ubicazioni in tutto il mondo. Quando distribuisci le risorse dell'infrastruttura, puoi effettuare una selezione da un elenco di data center in {{site.data.keyword.Bluemix_notm}}. 


![Mappa dei data center descritti nelle seguenti tabelle](images/Global-View.svg)

### Nord America
{: #na}

| Nome del data center | Codice  |
|------------------|-------|
| Dallas 01        | dal01 |
| Dallas 05        | dal05 |
| Dallas 06        | dal06 |
| Dallas 07        | dal07 |
| Dallas 09        | dal09 |
| Dallas 10        | dal10 |
| Dallas 12        | dal12 |
| Dallas 13        | dal13 |
| Washington DC 01 | wdc01 |
| Washington DC 04 | wdc04 |
| Washington DC 06 | wdc06 |
| Washington DC 07 | wdc07 |
| San Jose 01      | sjc01 |
| San Jose 03      | sjc03 |
| San Jose 04      | sjc04 |
| Seattle 01       | sea01 |
| Houston 01       | hou01 |
| Montreal 01      | mon01 |
| Toronto 01       | tor01 |
| Mexico 01        | mex01 |
{: caption="Tabella 2. Data center in Nord America" caption-side="top"}

### Sud America
{: #sa}

| Nome del data center | Codice    |
|------------------|---------|
| San Paolo 01 | sao01   |
{: caption="Tabella 3. Data center in Sud America" caption-side="top"}

### Europa
{: #eu}

| Nome del data center | Codice  |
|------------------|-------|
| Londra 02        | lon02 |
| Londra 04        | lon04 |
| Londra 05        | lon05 |
| Londra 06        | lon06 |
| Francoforte 02   | fra02 |
| Francoforte 04   | fra04 |
| Francoforte 05   | fra05 |
| Milano 01        | mil01 |
| Amsterdam 01     | ams01 |
| Amsterdam 03     | ams03 |
| Parigi 01        | par01 |
| Oslo 01          | osl01 |
{: caption="Tabella 4. Data center in Europa" caption-side="top"}

### Asia Pacifico
{: #ap}

| Nome del data center | Codice  |
|------------------|-------|
| Tokyo 01         | tok02 | 
| Tokyo 04         | tok04 |
| Tokyo 05         | tok05 |
| Seoul 01         | seo01 |
| Hong Kong 02     | hkg02 |
| Singapore 01     | sng01 |
| Sydney 01        | syd01 |
| Sydney 04        | syd04 |
| Sydney 05        | syd05 |
| Melbourne 01     | mel01 |
{: caption="Tabella 5. Data center in Asia Pacifico" caption-side="top"}


## SLA (Service Level Agreement)
{: #SLAs} 

{{site.data.keyword.Bluemix_notm}} fornisce un livello di servizio di disponibilità del 99,5% per più istanze di un servizio della piattaforma in un singolo ambiente dedicato o locale.

Per inoltrare un reclamo per il tempo di inattività, contatta il [supporto {{site.data.keyword.Bluemix_notm}}](https://console.cloud.ibm.com/unifiedsupport/supportcenter){: new_window} ![Icona link esterno](../icons/launch-glyph.svg "Icona link esterno").

{{site.data.keyword.Bluemix_notm}} fornisce gli SLA per i servizi {{site.data.keyword.Bluemix_notm}} che potrebbero renderti idoneo per dei crediti verso il tuo account. Gli SLA solo il solo modo che hai per risolvere il mancato rispetto di uno specifico livello di servizio da parte di {{site.data.keyword.Bluemix_notm}}. {{site.data.keyword.Bluemix_notm}} fornisce un livello di servizio di disponibilità del 99,5% per più istanze di un servizio della piattaforma in un singolo ambiente dedicato o locale.

Per ulteriori informazioni sugli ambienti dedicati, vedi [IBM Cloud dedicato](/docs/dedicated/index.html#dedicated) e, per gli ambienti locali, fai clic su [Bluemix locale](/docs/local/index.html#local). 

La descrizione del servizio completa per {{site.data.keyword.Bluemix_notm}} è disponibile in [Cloud Services terms](http://www-03.ibm.com/software/sla/sladb.nsf/sla/bm){: new_window} ![Icona link esterno](../icons/launch-glyph.svg "Icona link esterno").

### SLA di tempo di inattività della disponibilità

Sei idoneo per un credito verso il tuo account se riscontri un tempo di inattività che è inferiore alla disponibilità del 99,5% .Il tempo di inattività della disponibilità è il numero totale di minuti per cui non sei in grado di connetterti ad alcuna tua istanza del servizio. Il numero totale di minuti di tempo di inattività inizia quando inoltri un report per l'evento di interruzione e termina quando almeno una delle istanze interessate è disponibile per l'utilizzo.

{{site.data.keyword.Bluemix_notm}} fornisce uno SLA di disponibilità del 99,95% per: 
- Servizi cloud nell'ambiente pubblico configurati per l'elevata disponibilità come descritto nei dettagli del catalogo per ciascun servizio. 
- Servizi cloud in diversi ambienti dedicati o locali in data center geograficamente separati 

| Tipo	                                                                        | Descrizione	       |Dettagli supporto |
|-------------------------------------------------------------------------------|--------------------|----------------|
| Ambienti dedicati/locali multipli o ambiente pubblico ad alta disponibilità | Altri ambienti | Credito         |
| <99,95%                                                                       |<99,5%              |10%             |
| <99,90%                                                                       |<99,0%              |25%             |
{: caption="Tabella 6. Livello di servizio di disponibilità mensile" caption-side="top"}

La percentuale di disponibilità viene calcolata come il numero totale di minuti in un mese come da contratto meno il numero totale di minuti di tempo di inattività in tale mese diviso per il numero totale di minuti in tale mese. 

Ad esempio, in un mese di 31 giorni, hai un numero totale di 44.640 minuti. Se riscontri sei ore di tempo di inattività della disponibilità, stiamo parlando di 360 minuti di tempo di inattività. Con sole sei ore di tempo di inattività, hai una disponibilità del 99,19% . Poiché 99.19% è meno del 99.90%, sei idoneo per un credito del 25% con un ambiente pubblico o locale.   

```
= (44.640 minuti in totale nel mese - 360 minuti di tempo di inattività) / 44.640 minuti in totale nel mese
= (44.280 minuti effettivi disponibili) / 44.640 minuti in totale nel mese
= 99,19% di disponibilità
```

Gli SLA non includono il tempo di inattività o i malfunzionamenti correlati a specifiche esclusioni, non disponibilità dell'IU {{site.data.keyword.Bluemix_notm}}, tempo di ricaricamento, configurazione, abilitazione o accesso a contenuto.

Lo SLA di tempo di inattività della disponibilità non include i servizi dell'infrastruttura {{site.data.keyword.Bluemix_notm}}.
{: note}

### SLA dei servizi dell'infrastruttura

I servizi dell'infrastruttura sono servizi di server bare metal e virtuali, rete, archiviazione e sicurezza. Per trovare un elenco completo dei servizi dell'infrastruttura, cerca nel catalogo {{site.data.keyword.Bluemix_notm}} con la tag `iaas`. 

Il tempo di inattività è il numero totale di minuti per cui un servizio dell'infrastruttura identificato dal cliente non è disponibile a causa di un'interruzione del servizio basata su interruzioni di HVAC, alimentazione dell'infrastruttura ridondante, rete privata e rete pubblica. Il calcolo del totale di minuti di tempo di inattività va da quando viene identificata l'interruzione convalidata che interessa il servizio a quando il servizio è disponibile. 

Il tempo di inattività non include il tempo per la manutenzione pianificata o annunciata. Per ogni periodo di 30 minuti continui di inattività, ricevi un credito pari al 5% degli addebiti mensili per i servizi identificati che sono direttamente interessati dall'interruzione. Non sei idoneo per un credito se il tempo di inattività è inferiore a 30 minuti continui. Il tempo di inattività per i diversi tipi di interruzione non può essere combinato per soddisfare questo calcolo.

### SLA di sostituzione e upgrade dell'hardware dell'infrastruttura
{{site.data.keyword.Bluemix_notm}} prova a ridurre al minimo il tempo di inattività quando sostituisce hardware malfunzionante o quando esegue un upgrade dell'hardware pianificato. 

{{site.data.keyword.Bluemix_notm}} fornisce il credito per: 
- La sostituzione dell'hardware basata sul tempo per eseguire la sostituzione da quando {{site.data.keyword.Bluemix_notm}} verifica che un cliente ha segnalato un malfunzionamento hardware.
- Upgrade dell'hardware pianificati sulla base del tempo di inattività totale del servizio che riceve l'upgrade. 

I periodi di tempo del livello di servizio escludono il tempo necessario per ricaricare il sistema operativo o le applicazioni oppure il tempo durante il quale le prestazioni potrebbero essere degradate. Sei idoneo per un credito basato sull'addebito mensile per il servizio interessato dalla sostituzione o dall'upgrade dell'hardware se {{site.data.keyword.Bluemix_notm}} non riesce a soddisfare il periodo di tempo del livello di servizio specificato.

| Tipo	                    | Descrizione	   |
|---------------------------|----------------|
| Periodo di tempo del livello di servizio | Percentuale di credito |
| ≤ 2 ore                 | Nessuno        |
| > 2 ore                 | 20%            |
| > 6 ore                 | 40%            |
| > 10 ore                | 60%            |
| > 14 ore                | 80%            |
| > 18 ore                | 80%            |
{: caption="Tabella 7. Credito basato sull'addebito mensile per il servizio interessato dalla sostituzione o dall'upgrade dell'hardware" caption-side="top"}

### Reclami
Inoltra il tuo reclamo entro 60 giorni dalla fine del mese previsto dal contratto per cui non è stato soddisfatto il livello di servizio. Fornisci informazioni sufficienti per identificare il servizio interessato, i messaggi di errore e le altre informazioni necessarie per convalidare il reclamo. 

Il credito sarà la compensazione più alta applicabile sulla base della disponibilità cumulativa del servizio interessato durante un mese previsto da contratto e calcolato utilizzando gli addebiti mensili per tale servizio interessato. I crediti non possono superare il 25% dell'addebito mensile.

Per inoltrare un reclamo per il tempo di inattività, contatta il [supporto {{site.data.keyword.Bluemix_notm}}](https://console.cloud.ibm.com/unifiedsupport/supportcenter){: new_window} ![Icona link esterno](../icons/launch-glyph.svg "Icona link esterno").

### Esclusioni
Non viene dato alcun credito per il mancato rispetto di uno SLA a causa di:
- Problemi con il contenuto, la tecnologia, i progetti o le istruzioni forniti dalla community o dal cliente
- Servizi cloud beta, sperimentali o gratuiti
- Pacchetti di build non IBM
- Piattaforme e configurazioni di sistema non supportate
- Malfunzionamenti dell'infrastruttura del cliente, compresi rete, hardware, struttura o alimentazione
- Trasferimenti file, comandi o azioni di amministrazione del sistema del cliente
- Errori o carenze del cliente nel fornire le informazioni necessarie o l'accesso per risolvere un'interruzione
- Esecuzione di test di sicurezza o incidenti di sicurezza causati dal cliente
- Altre cause oltre il ragionevole controllo di IBM

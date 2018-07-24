---


copyright:
  years: 2015, 2018
lastupdated: "2018-07-17"

---

{:shortdesc: .shortdesc}
{:tip: .tip}
{:new_window: target="_blank"}

# Come funziona la console {{site.data.keyword.cloud_notm}}
{: #ui}

La console {{site.data.keyword.cloud}} è un'interfaccia utente che ti aiuta a gestire tutte le tue risorse {{site.data.keyword.cloud_notm}}. Quando accedi alla [console](https://console.bluemix.net){: new_window} ![Icona link esterno](../icons/launch-glyph.svg "Icona link esterno"), puoi creare un account gratuito, effettuare l'accesso, accedere alla documentazione, accedere al catalogo, consultare le informazioni sui prezzi, ottenere supporto o controllare lo stato dei componenti {{site.data.keyword.cloud_notm}}. Dopo aver eseguito l'accesso, la barra dei menu contiene un'icona Menu ![icona Menu](../icons/icon_hamburger.svg) e ulteriori link, a seconda del tuo tipo di account.
{: shortdesc}

## Utilizzo della console
{: #consoleoptions}

Se sei un utente esistente con un account {{site.data.keyword.cloud_notm}}, puoi utilizzare l'icona Menu ![Icona Menu](../icons/icon_hamburger.svg) per accedere a tutte le risorse esistenti dal tuo dashboard.
  * Utilizza il link **Catalogo** per creare nuove risorse.
  * Utilizza il link **Documenti** per accedere alle informazioni utili su {{site.data.keyword.cloud_notm}}.
  * Dal menu **Supporto**, puoi accedere alle informazioni sulle novità per {{site.data.keyword.cloud_notm}}, al centro di supporto, alle opzioni per aggiungere e visualizzare i ticket e alla pagina Stato.
  * Dal menu **Gestisci**, puoi accedere alle opzioni per il tuo account, per la fatturazione e l'utilizzo e per la sicurezza.

Se hai collegato i tuoi account {{site.data.keyword.cloud_notm}} e SoftLayer, hai le stesse opzioni di un proprietario di account non collegato e inoltre puoi accedere al portale clienti selezionando l'opzione dell'**icona Menu  ![Icona Menu](../icons/icon_hamburger.svg)  > Infrastruttura**. Da qui, puoi visualizzare il riepilogo del tuo account, ordinare archiviazione e dispositivi e gestire l'accesso per utenti e dispositivi solo VPN.

## Ricerca delle risorse
{: #search}

Puoi cercare le risorse da qualsiasi punto nella console {{site.data.keyword.cloud_notm}}. Immetti il nome di una risorsa nel campo di ricerca nella barra dei menu della console.

Digita il tasto `/` sulla tua tastiera per portare il tuo cursore al campo di ricerca.
{: tip}

## Gestione delle risorse sul dashboard
{: #dashboardview}

Puoi utilizzare il dashboard per visualizzare e gestire le risorse {{site.data.keyword.cloud_notm}} e le istanze del servizio Cloud Foundry. Vedi [Che cos'è una risorsa? ](/docs/resources/acct_resources.html#resource) per ulteriori informazioni,

### Visualizzazione delle risorse

Puoi visualizzare tutte le risorse presenti nel tuo account nell'ambito di tutte le regioni dal dashboard. Per personalizzare la tua vista, utilizza le seguenti opzioni:

  * Per visualizzare le risorse in uno specifico gruppo, seleziona un gruppo di risorse dall'elenco **Gruppo di risorse**.
  * Per visualizzare le risorse in una specifica organizzazione Cloud Foundry, seleziona un'organizzazione dall'elenco **Organizzazione Cloud Foundry**.

Quindi, in base agli elementi selezionati, puoi filtrare in base alle seguenti opzioni:

  * Ubicazione
  * Spazio Cloud Foundry
  
Se vuoi visualizzare e gestire le risorse in una specifica regione, espandi il menu **UBICAZIONE** e seleziona una regione dall'elenco.

### Gestione delle risorse

Puoi gestire le tue risorse in vari modi utilizzando il dashboard:

  * Ogni risorsa viene visualizzata nella relativa riga e un'icona Altre azioni  ![Icona Altre azioni](../icons/overflow-menu.svg) è inclusa alla fine della riga. Fai clic sull'icona **Ulteriori azioni** per avviare, arrestare, ridenominare o eliminare una risorsa.
  * Per impostare credenziali o connessioni per una risorsa, fai clic sul nome della risorsa per accedere alla sua pagina dei dettagli. Per ulteriori informazioni, vedi [Aggiunta di una nuova credenziale](/docs/resources/service_credentials.html) e [Gestione delle connessioni](/docs/resources/connecting_apps.html#connect_app).

## Lavorare nel catalogo
{: #catalogcreate}

Per creare una nuova risorsa, fai clic su **Crea risorsa** dal tuo dashboard. Verrai reindirizzato al catalogo. Quando selezioni un tile dal catalogo, puoi visualizzare dove la risorsa è disponibile. Non tutte le risorse elencate nel catalogo sono disponibili in ogni regione.

Dopo aver fatto clic sul tile per la risorsa che vuoi creare, puoi selezionare la posizione in cui eseguire la distribuzione.

  * Per le risorse Cloud Foundry, puoi selezionare una regione specifica e quindi selezionare l'organizzazione e lo spazio a cui assegnare l'istanza di servizio.
  * Per le risorse gestite da {{site.data.keyword.cloud_notm}} Identity and Access Management (IAM), seleziona la posizione in cui eseguire la distribuzione. Quindi, seleziona un gruppo di risorse a cui assegnare l'istanza del servizio.

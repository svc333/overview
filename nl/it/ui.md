---


copyright:
  years: 2015, 2019
lastupdated: "2019-06-25"

keywords: ui, components, using the console, SoftLayer, classic infrastructure

subcollection: overview

---

{:shortdesc: .shortdesc}
{:tip: .tip}
{:note: .note}
{:new_window: target="_blank"}

# Navigazione nella console {{site.data.keyword.cloud_notm}} 
{: #ui}

La console {{site.data.keyword.cloud}} è un'interfaccia utente che ti aiuta a gestire tutte le tue risorse {{site.data.keyword.cloud_notm}}. Quando accedi alla [console](https://cloud.ibm.com){: new_window} ![Icona link esterno](../icons/launch-glyph.svg "Icona link esterno"), puoi creare un account gratuito, effettuare l'accesso, accedere alla documentazione, accedere al catalogo, consultare le informazioni sui prezzi, ottenere supporto o controllare lo stato dei componenti {{site.data.keyword.cloud_notm}}. Dopo aver eseguito l'accesso, la barra dei menu contiene un'icona Menu ![icona Menu](../icons/icon_hamburger.svg) e ulteriori link.
{: shortdesc}


## Utilizzo della console
{: #consoleoptions}

Quando accedi a {{site.data.keyword.cloud_notm}}, viene visualizzato il tuo dashboard, che mostra i widget che riassumono lo stato del tuo account. Se sei interessato nell'aggiunta o rimozione dei widget, vedi [Personalizzazione del tuo dashboard](/docs/overview?topic=overview-custom-dashboard).

  * Utilizza il link **Catalogo** per creare nuove risorse.
  * Utilizza il link **Documenti** per accedere alla documentazione del prodotto. 
  * Utilizza il link **Supporto** per accedere al centro di supporto.  
  * Dal menu **Gestisci**, puoi accedere alle opzioni per il tuo account, per la fatturazione e l'utilizzo e per IAM (Identity and Access Management).
  * Fai clic sull'icona dello stimatore costi ![icona stimatore costi](../icons/Estimator.svg) per aprire lo stimatore costi.
  * Fai clic sull'icona delle notifiche ![icona notifiche](../icons/Notification.svg) per accedere agli annunci e agli eventi pianificati e non pianificati.

## Ricerca delle risorse
{: #search}

Puoi eseguire le ricerca delle risorse per nome o per tag da qualsiasi parte nella console {{site.data.keyword.cloud_notm}} per le risorse che prevedi di trovare nell'elenco risorse. Immetti il nome di una risorsa o la tag nel campo di ricerca nella barra dei menu della console.

Per ulteriori informazioni, vedi [Ricerca delle risorse](/docs/resources?topic=resources-searching-for-resources). 

## Gestione delle risorse nell'elenco risorse
{: #dashboardview}

Vai all'icona Menu ![icona Menu](../icons/icon_hamburger.svg) &gt; **Elenco risorse** per accedere al tuo elenco di risorse dell'account. Puoi utilizzare l'elenco di risorse per visualizzare e gestire le risorse {{site.data.keyword.cloud_notm}} e le istanze del servizio Cloud Foundry. Vedi [Che cos'è una risorsa? ](/docs/resources?topic=resources-resource) per ulteriori informazioni sui diversi tipi di risorse.

### Visualizzazione delle risorse
Puoi visualizzare tutte le risorse presenti nel tuo account nell'ambito di tutte le regioni dall'elenco risorse. Per visualizzare gli elementi importanti per te, filtra il tuo elenco con i filtri per ogni intestazione di colonna. Ad esempio, se vuoi visualizzare e gestire le risorse in una specifica ubicazione, espandi il filtro **Ubicazione** e seleziona un'ubicazione dall'elenco.

### Gestione delle risorse
Puoi gestire le tue risorse in vari modi utilizzando l'elenco risorse:

  * Ogni risorsa viene visualizzata nella relativa riga e un'icona Azioni ![Icona Altre azioni](../icons/action-menu-icon.svg) è inclusa alla fine della riga. Fai clic sull'icona Azioni ![Icona Altre azioni](../icons/action-menu-icon.svg) per avviare, arrestare, ridenominare o eliminare una risorsa.
  * Per impostare credenziali o connessioni per una risorsa, fai clic sul nome della risorsa per accedere alla sua pagina dei dettagli. Seleziona quindi **Credenziali del servizio** o **Connessioni**. Per ulteriori informazioni, vedi [Aggiunta di una credenziale](/docs/resources?topic=resources-service_credentials) e [Gestione delle connessioni](/docs/resources?topic=resources-connect_app).

## Lavorare nel catalogo
{: #catalogcreate}

Per creare una risorsa, fai clic su **Crea** dal tuo elenco risorse. Verrai reindirizzato al catalogo. Quando selezioni un tile dal catalogo, puoi visualizzare dove la risorsa è disponibile. Non tutte le risorse elencate nel catalogo sono disponibili in ogni regione.

Dopo aver fatto clic sul tile per la risorsa che vuoi creare, puoi selezionare la posizione in cui eseguire la distribuzione.

  * Per le risorse Cloud Foundry, puoi selezionare una regione specifica e quindi selezionare l'organizzazione e lo spazio a cui assegnare l'istanza di servizio.
  * Per le risorse gestite da {{site.data.keyword.cloud_notm}} Identity and Access Management (IAM), seleziona la posizione in cui eseguire la distribuzione. Quindi, seleziona un gruppo di risorse a cui assegnare l'istanza del servizio.

## Transizione all'esperienza {{site.data.keyword.cloud_notm}}
{: #redirect-cloud}

Come parte della migrazione da SoftLayer a {{site.data.keyword.cloud_notm}}, acquisisci familiarità con la console {{site.data.keyword.cloud_notm}}, che utilizzi per gestire sia le risorse della piattaforma che dell'infrastruttura. Attualmente siamo in fase di collegamento di tutti gli account SoftLayer e {{site.data.keyword.cloud_notm}}. Pertanto, il tuo account potrebbe non avere ancora accesso. Non appena questo avviene, puoi consultare la nuova esperienza. 

Ciò che prima era noto come SoftLayer è ora denominato infrastruttura classica {{site.data.keyword.cloud_notm}}.
{: note}

### Localizzazione delle tue voci dell'infrastruttura
{: #sl-links}

Fai clic sull'**icona Menu** ![icona Menu](../icons/icon_hamburger.svg) > **Infrastruttura classica** per individuare velocemente dispositivi, archiviazione, rete, sicurezza e servizi. 

![Localizzazione delle tue voci dell'infrastruttura classica.](images/iaas-items.png "Localizzazione delle tue voci dell'infrastruttura")

Puoi anche visualizzare i tuoi dispositivi ed elementi di archiviazione nell'elenco di risorse facendo clic sull'**icona Menu** ![icona Menu](../icons/icon_hamburger.svg) > **Elenco risorse**.
{: tip}

### Gestione di utenti, accesso e chiavi API.
{: #billing-items}

Puoi gestire gli utenti nel tuo account, l'accesso all'infrastruttura classica per i tuoi utenti e le tue chiavi API dalla sezione Accesso (IAM) della console.  

* Per invitare nuovi utenti, rimuovere gli utenti o gestire le impostazioni di accesso, le limitazioni di IP, la password VPN ed altro di un utente specifico, vai a **Gestisci** > **Accesso (IAM)** e seleziona **Utenti**.
* Per iniziare a gestire l'accesso all'infrastruttura classica di un utente, vai a **Gestisci** > **Accesso (IAM)** e seleziona **Utenti**. Per ulteriori dettagli, vedi [Gestione dell'accesso all'infrastruttura classica](/docs/iam?topic=iam-mngclassicinfra).
* Per creare e gestire le chiavi API {{site.data.keyword.cloud_notm}} o una chiave API dell'infrastruttura classica, vai a **Gestisci** > **Accesso (IAM)** e seleziona **Chiavi API**. Per ulteriori informazioni, vedi [Descrizione delle chiavi API](/docs/iam?topic=iam-manapikey).

![Ubicazione per gestire le voci IAM.](images/users-access.png "Gestione di utenti, accesso e chiavi API")

### Inserimento di un ordine
{: #place-order}

Utilizza il catalogo per inserire un ordine. Puoi passare al catalogo in uno dei seguenti modi:

  * Fai clic su **Catalogo** dalla barra dei menu.
  * Fai clic sull'**icona Menu** ![icona Menu](../icons/icon_hamburger.svg) > **Elenco risorse**. Quindi fai clic su **Crea risorsa**.

![Ubicazione per inserire un ordine.](images/orders.png "Inserimento di un ordine")

### Effettuazione di un pagamento
{: #payments}

Puoi effettuare un pagamento dalla sezione Fatturazione e utilizzo della console. Vai a **Gestisci ** > **Fatturazione e utilizzo** e seleziona **Pagamenti**. 

![Ubicazione per effettuare un pagamento.](images/payments.png "Effettuazione di un pagamento")

### Accesso alle tue fatture
{: #invoices}

Puoi accedere alle tue fatture dalla sezione Fatturazione e utilizzo della console. Vai a **Gestisci ** > **Fatturazione e utilizzo** e seleziona **Fatture**.

![Ubicazione per accedere alle tue fatture.](images/invoices.png "Accesso alle tue fatture")

### Accesso alle tue voci di vendita
{: #sales}

Le quote, gli upgrade, gli ordini, gli annullamenti e le spedizioni del tuo dispositivo si trovano nella sezione Fatturazione e utilizzo della console. Vai a **Gestisci ** > **Fatturazione e utilizzo** e seleziona **Vendite**. 

![Ubicazione per accedere alle voci di vendita.](images/sales-items.png "Accesso alle tue voci di vendita")

### Accesso ai tuoi casi di supporto
{: #support-mng}

Per accedere ai tuoi casi di supporto correnti, fai clic su **Supporto** > **Gestisci casi**. Puoi anche accedere ai tuoi casi archiviati facendo clic su **Visualizza casi archiviati**.

![Ubicazione per accedere ai casi di supporto.](images/support-cases.png "Accesso ai tuoi casi di supporto")

### Invio del feedback
{: #feedback-profile}

Puoi inviare una recensione entusiastica, un suggerimento o un qualsiasi altro feedback. Per contattarci, scegli tra i seguenti metodi:

  * Fai clic sul pulsante **Feedback** ubicato sul margine della pagina della console. 
  * Fai clic sull'**icona Avatar** ![icona Avatar](../icons/i-avatar-icon.svg) > **Feedback**. 

![Ubicazione per inviare il feedback.](images/feedback.png "Invio del feedback")

### Impostazione delle preferenze email
{: #email-prefsl}

Puoi configurare le tue preferenze in modo da ricevere delle email sulle notifiche della piattaforma e dell'infrastruttura. Fai clic sull'**Icona Avatar** ![Icona Avatar](../icons/i-avatar-icon.svg) > **Profilo e impostazioni** e seleziona **Notifiche**.

![Ubicazione per configurare le preferenze email.](images/email-prefs.png "Configurazione delle preferenze email")

### Selezione del tuo punto di accesso VPN
{: #vpn-access}

Puoi accedere alla console {{site.data.keyword.cloud_notm}} utilizzando un punto di accesso VPN. Vai a [Accesso VPN](https://www.ibm.com/cloud-computing/bluemix/vpn-access) e seleziona un punto di accesso dagli elenchi.


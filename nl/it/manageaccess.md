---

copyright:

  years: 2017, 2018

lastupdated: "2017-11-10"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}

# Gestione dell'accesso in {{site.data.keyword.Bluemix_notm}}
{: #cloudaccess}

## Cos'è la gestione dell'accesso?

La gestione dell'accesso ti consente di controllare quali utenti vedono, creano, utilizzano e gestiscono le risorse nel tuo account. Per concedere l'accesso, puoi assegnare ruoli che offrano agli utenti dei livelli di accesso per completare le attività di gestione della piattaforma e accedere alle risorse dell'account.

Il modo in cui gestisci l'accesso in {{site.data.keyword.Bluemix_notm}} dipende dal tipo di risorsa a cui vuoi assegnare l'accesso. {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) è il sistema di gestione degli accessi per gestire in modo coerente le risorse attraverso la piattaforma {{site.data.keyword.Bluemix_notm}}. L'infrastruttura {{site.data.keyword.Bluemix_notm}} e le risorse Cloud Foundry non vengono gestite mediante Cloud IAM. Questi tipi di risorse hanno i loro propri sistemi di gestione degli accessi. Se hai una combinazione di tipi di risorse, gestisci ciascun tipo separatamente. Per assegnare l'accesso alle tue risorse dell'infrastruttura, imposta le autorizzazioni all'interno del tuo account SoftLayer. Per assegnare l'accesso alle risorse Cloud Foundry, utilizza l'opzione Assegna utilizzando Cloud Foundry nella sezione Identità e eccesso della console.

## Chi ha l'autorizzazione per gestire l'accesso?

In qualità di proprietario dell'account, puoi gestire l'accesso a tutte le risorse nel tuo account. Puoi anche delegare il compito di gestire l'accesso alle risorse della piattaforma assegnando a un utente nel tuo account il ruolo di amministratore per tutti i servizi.

Se hai dei servizi Cloud Foundry nel tuo account, puoi assegnare a un altro utente il ruolo di gestore organizzazioni o spazio in modo che possa aggiungere utenti e assegnare ruoli utente di Cloud Foundry per accedere alle istanze nell'organizzazione o nello spazio che gestisce.


## Come inizio a gestire l'accesso?

Vai a **Gestisci** &gt; **Sicurezza** &gt; **Identità e accesso** e seleziona quindi **Utenti** per iniziare a gestire l'accesso per gli utenti nel tuo account. Seleziona un utente dall'elenco per iniziare. Vedi solo le opzioni di gestione dell'accesso che sei autorizzato a gestire. Ad esempio, se non sei il proprietario dell'account né un gestore dell'organizzazione o dello spazio, non visualizzerai l'opzione per gestire l'accesso a Cloud Foundry.

I ruoli di accesso possono anche essere assegnati ad applicazioni e servizi utilizzando gli ID di servizio. Per iniziare, vai alla pagina **ID servizio**. Per ulteriori informazioni su come iniziare subito a lavorare con Cloud IAM, segui la procedura nell'[Esercitazione introduttiva](/docs/iam/quickstart.html#getstarted).

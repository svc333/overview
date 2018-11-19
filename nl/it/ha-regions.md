---

copyright:

  years: 2018

lastupdated: "2018-11-01"

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:pre: .pre}
{:tip: .tip}

# Ubicazioni per la distribuzione della risorsa 
{: #ov_intro_reg}

Puoi creare applicazioni e istanze del servizio in ubicazioni differenti con la stessa infrastruttura {{site.data.keyword.cloud_notm}} per la gestione di applicazioni e la stessa vista dei dettagli di utilizzo per la fatturazione. Puoi distribuire le tue applicazioni all'ubicazione più vicina ai tuoi clienti per ottenere una bassa latenza dell'applicazione. 

Per far fronte ai problemi di sicurezza puoi anche selezionare l'ubicazione dove desideri conservare i dati delle applicazioni. Quando crei applicazioni in più di un'ubicazione, se un'ubicazione non è più disponibile, le applicazioni che si trovano nelle altre ubicazioni continuano a essere eseguite. La disponibilità di risorse è la stessa per ogni ubicazione che usi. Per ulteriori informazioni sulle risorse della piattaforma e sulle ubicazioni in cui sono disponibili, consulta [Disponibilità dei servizi](/docs/resources/service_region.html).

Il bilanciamento del carico globale per la console garantisce che, se l'ubicazione geografica a te più prossima è inattiva, la console visualizzerà le informazioni per la successiva ubicazione più prossima. In questo modo, avrai sempre accesso alla console senza dover eseguire alcuna azione per accedere alle informazioni di cui hai bisogno.

Dal dashboard, puoi visualizzare tutte le risorse in tutte le ubicazioni per impostazione predefinita. Se vuoi visualizzare e gestire le risorse in una specifica ubicazione, espandi il menu **UBICAZIONE** e seleziona un'ubicazione dall'elenco. 

Puoi inoltre utilizzare l'interfaccia riga di comando per connetterti all'ubicazione {{site.data.keyword.cloud_notm}} con cui vuoi lavorare utilizzando il comando `ibmcloud api` e specificando l'endpoint API dell'ubicazione. Ad esempio, immetti il seguente comando per stabilire una connessione all'ubicazione {{site.data.keyword.cloud_notm}} Londra:

```
ibmcloud api https://api.eu-gb.bluemix.net
```

A ciascuna ubicazione viene assegnato un prefisso univoco. {{site.data.keyword.cloud_notm}} fornisce le seguenti ubicazioni e i seguenti prefissi di ubicazione.

| **Ubicazione** | **Endpoint API** |
|-----------------|-------------------|
| Dallas | api.us-south.bluemix.net |
| Sydney | api.au-syd.bluemix.net |
| Frankfurt | api.eu-de.bluemix.net |
| London | api.eu-gb.bluemix.net |
| Washington DC | api.us-east.bluemix.net |
| Tokyo | api.jp-tok.bluemix.net |
{: caption="Tabella 1. Elenco di ubicazioni {{site.data.keyword.cloud_notm}}" caption-side="top"}

Quando distribuisci le risorse dell'infrastruttura, hai maggiore scelta su dove si trova il tuo contenuto. Puoi effettuare la selezione in un elenco di data center in {{site.data.keyword.Bluemix_notm}}. Per ulteriori informazioni, consulta [Data center {{site.data.keyword.cloud_notm}}](data-centers.html).

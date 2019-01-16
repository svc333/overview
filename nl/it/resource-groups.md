---

copyright:
  years: 2017, 2018
lastupdated: "2018-10-11"

---

{:shortdesc: .shortdesc}

# Organizzazione delle risorse nei gruppi di risorse
{: #whatis}

Un gruppo di risorse è un modo per organizzare le [risorse](/docs/resources/acct_resources.html#resource) dell'account in raggruppamenti personalizzabili, in modo da poter assegnare rapidamente agli utenti l'accesso a più di una risorsa alla volta. Qualsiasi risorsa dell'account gestita attraverso il controllo dell'accesso {{site.data.keyword.Bluemix}} Identity and Access Management (IAM) appartiene a un gruppo di risorse all'interno del tuo account. Quando aggiungi una nuova risorsa al tuo account dal catalogo, puoi assegnarla a un gruppo di risorse. L'unica eccezione è Kubernetes, che non ti richiede un'assegnazione di un gruppo di risorse, ma l'accesso al servizio viene controllato utilizzando i ruoli IAM.

I servizi che sono gestiti mediante {{site.data.keyword.Bluemix}} IAM e che appartengono a un gruppo di risorse dispongono di numerosi vantaggi, tra cui la possibilità di connettersi ad applicazioni e servizi in qualsiasi spazio Cloud Foundry, che ti consente di connettere applicazioni e servizi da ubicazioni diverse. Poiché i gruppi di risorse non sono definiti dall'ubicazione, puoi eseguire il provisioning di applicazioni e servizi da diverse ubicazioni nello stesso gruppo di risorse. Hai anche la possibilità di utilizzare il controllo dell'accesso dettagliato fino a una singola istanza all'interno di un gruppo di risorse.

Per ulteriori informazioni sull'utilizzo dei gruppi di risorse, vedi [Gestione dei gruppi di risorse](/docs/resources/resourcegroups.html). Se poi non hai dimestichezza con l'utilizzo di gruppi di risorse, consulta le [prassi ottimali per organizzare le risorse in gruppi di risorse](/docs/resources/bestpractice_rgs.html#bp_resourcegroups).

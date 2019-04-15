---

copyright:
  years: 2017, 2019
lastupdated: "2019-03-14"

keywords: access control, resource groups, resource group

subcollection: overview

---

{:shortdesc: .shortdesc}

# Organizzazione delle risorse nei gruppi di risorse
{: #whatis-rgs}

Un gruppo di risorse è un modo per organizzare le risorse dell'account in raggruppamenti personalizzabili, in modo da poter assegnare rapidamente agli utenti l'accesso a più di una risorsa alla volta. Qualsiasi risorsa dell'account gestita attraverso il controllo dell'accesso {{site.data.keyword.Bluemix}} Identity and Access Management (IAM) appartiene a un gruppo di risorse all'interno del tuo account. Quando aggiungi una risorsa al tuo account dal catalogo, puoi assegnarla a un gruppo di risorse. L'unica eccezione è Kubernetes, che non ti richiede un'assegnazione di un gruppo di risorse, ma l'accesso al servizio viene controllato utilizzando i ruoli IAM.

I servizi gestiti tramite {{site.data.keyword.Bluemix_notm}} IAM e appartenenti a un gruppo di risorse presentano numerosi vantaggi. Alcuni dei vantaggi includono la possibilità di connetterti ad applicazioni e servizi in qualsiasi spazio Cloud Foundry, il che significa che puoi connettere applicazioni e servizi da ubicazioni diverse. Poiché i gruppi di risorse non sono definiti dall'ubicazione, puoi eseguire il provisioning di applicazioni e servizi da diverse ubicazioni nello stesso gruppo di risorse. Puoi anche utilizzare il controllo dell'accesso dettagliato fino a una singola istanza all'interno di un gruppo di risorse.

Per ulteriori informazioni sull'utilizzo dei gruppi di risorse, vedi [Gestione dei gruppi di risorse](/docs/resources?topic=resources-rgs). 

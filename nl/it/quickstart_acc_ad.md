---

copyright:

  years: 2018

lastupdated: "2018-11-14"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:tip: .tip}

# Configurazione del tuo account
{: #quickstart_acc_ad}

Questa guida introduttiva è concepita per aiutare gli amministratori dell'account a configurare i propri ambienti {{site.data.keyword.Bluemix}}.
{:shortdesc}

1. Crea i gruppi di risorse da utilizzare per organizzare le risorse create dal catalogo {{site.data.keyword.Bluemix_notm}}. Per ulteriori informazioni, consulta [Prassi ottimali per organizzare le risorse nei gruppi di risorse](/docs/resources/bestpractice_rgs.html#bp_resourcegroups).

  Far ciò in anticipo è importante perché dopo che hai assegnato una risorsa a un gruppo di risorse, non la puoi spostare.
  {:tip}
  
2. Poiché non tutti i servizi sono gestiti da {{site.data.keyword.Bluemix_notm}} IAM (Identity and Access Management), crea la tua organizzazione Cloud Foundry per organizzare e concedere l'accesso a tali servizi. Con un account Lite, ottieni un'organizzazione Cloud Foundry in un'ubicazione {{site.data.keyword.Bluemix_notm}}. Per ulteriori informazioni, vedi [Aggiunta di organizzazioni e spazi](/docs/account/orgs_spaces.html#orgsspacesusers). 
3. Crea i gruppi di accesso utenti per l'organizzazione degli utenti e degli ID del servizio in gruppi che richiedono lo stesso livello di accesso assegnato. Per ulteriori informazioni, vedi [Configurazione dei gruppi di accesso](/docs/iam/groups.html#groups).
4. Invita degli utenti nell'account e aggiungili ai gruppi di accesso per assegnare l'accesso necessario per consentire ai tuoi utenti dell'account di iniziare la creazione. Per ulteriori informazioni, vedi l'[Esercitazione introduttiva per IAM](/docs/iam/quickstart.html#getstarted).
5. Configura le notifiche per gli eventi e i limiti di spesa dell'account. Per ulteriori informazioni, vedi [Impostazione delle preferenze email](/docs/account/email.html) e [Configurazione delle notifiche di spesa](/docs/billing-usage/notifications.html). 
6. Utilizza lo stimatore dei costi per farti un'idea di quanto potrebbe costare il tuo ambiente. Fai clic sull'icona dello stimatore costi ![icona stimatore costi](../icons/Estimator.svg) nella barra dei menu della console. 
7. Utilizza lo stimatore dei costi per farti un'idea di quanto potrebbe costare la tua infrastruttura.  
  
  a. Inizia selezionando un'offerta dal [catalogo](https://console.cloud.ibm.com/catalog){: new_window} ![Icona link esterno](../icons/launch-glyph.svg). 
  
  b. Immetti i dettagli di configurazione, seleziona il tuo piano dei prezzi e fai clic su **Aggiungi alla stima**.

## Passi successivi
{: #next-steps}

* Inizia creando i servizi all'interno dell'account per consentire alla tua organizzazione e ai tuoi sviluppatori di creare le soluzioni di cui hanno bisogno.  
* Crea delle tag e contrassegna le tue risorse per aiutarti ad organizzare come visualizzi la fatturazione e l'utilizzo. Questo rende più facile identificare i riaddebiti a organizzazioni differenti. Per ulteriori informazioni, consulta [Procedure ottimali per contrassegnare con tag le risorse](/docs/account/bp_account.html#tags). 

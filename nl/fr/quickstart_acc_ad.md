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

# Configuration de votre compte
{: #quickstart_acc_ad}

Ce guide de démarrage rapide est conçu pour aider les administrateurs de compte à configurer leur environnement {{site.data.keyword.Bluemix}}.
{:shortdesc}

1. Créez des groupes de ressources à utiliser pour organiser les ressources créées à partir du catalogue {{site.data.keyword.Bluemix_notm}}. Pour plus d'informations, voir [Meilleures pratiques pour l'organisation des ressources dans un groupe de ressources](/docs/resources/bestpractice_rgs.html#bp_resourcegroups).

  Il est important d'effectuer cette action au préalable car une fois que vous affectez une ressource à un groupe de ressources, elle ne peut pas être déplacée.
  {:tip}
  
2. Etant donné que tous les services ne sont pas gérés par {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM), créez votre organisation Cloud Foundry afin d'organiser et d'octroyer l'accès à ces services. Avec un compte Lite, vous obtenez une organisation Cloud Foundry à un emplacement {{site.data.keyword.Bluemix_notm}}. Pour plus d'informations, voir [Ajout d'organisations et d'espaces](/docs/account/orgs_spaces.html#orgsspacesusers). 
3. Créez des groupes d'accès pour l'organisation des utilisateurs et des ID de service dans des groupes exigeant le même niveau d'accès affecté. Pour plus d'informations, voir [Configuration de groupes d'accès](/docs/iam/groups.html#groups).
4. Invitez des utilisateurs à rejoindre le compte et ajoutez-les à des groupes d'accès afin d'affecter l'accès nécessaire pour permettre la génération de vos utilisateurs de compte. Pour plus d'informations, voir le [tutoriel d'initiation pour IAM](/docs/iam/quickstart.html#getstarted).
5. Configurez les notifications pour les événements et les limites des dépenses liées aux comptes. Pour plus d'informations, voir [Définition des préférences de courrier](/docs/account/email.html) et [Définition des notifications relatives aux dépenses](/docs/billing-usage/notifications.html). 
6. Utilisez l'estimateur de coût pour évaluer les coûts de votre environnement. Cliquez sur l'icône Estimateur de coût ![Icône Estimateur](../icons/Estimator.svg) dans la barre de menus de la console. 
7. Utilisez l'estimateur de coût pour évaluer les coûts de votre infrastructure. 
  
  a. Commencez par sélectionner une offre dans le [catalogue](https://console.cloud.ibm.com/catalog){: new_window} ![Icône de lien externe](../icons/launch-glyph.svg). 
  
  b. Entrez les informations de configuration, sélectionnez votre plan de tarification puis cliquez sur **Ajouter à l'estimation**.

## Etapes suivantes
{: #next-steps}

* Commencez par créer des services dans le compte afin de permettre à votre organisation et aux développeurs de générer l'application dont ils ont besoin.  
* Créez des étiquettes et étiquetez vos ressources afin d'organiser l'affichage de la facturation et de l'utilisation. Ainsi, il est plus facile d'identifier les remboursements à différentes organisations. Pour plus d'informations, consultez les [meilleures pratiques pour l'étiquetage des ressources](/docs/account/bp_account.html#tags). 

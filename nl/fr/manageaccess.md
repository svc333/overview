---

copyright:

  years: 2017, 2018

lastupdated: "2017-11-10"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}

# Gestion des accès dans {{site.data.keyword.Bluemix_notm}}
{: #cloudaccess}

## Qu'est-ce que la gestion des accès ?

La gestion des accès vous permet de contrôler quels utilisateurs affichent, créent, utilisent et gèrent les ressources de votre compte. Pour accorder l'accès, vous pouvez affecter des rôles qui donnent à des niveaux utilisateur l'autorisation d'exécuter des tâches de gestion de plateforme et d'accéder à des ressources du compte.

La manière dont vous traitez les accès dans {{site.data.keyword.Bluemix_notm}} dépend du type de ressource auxquelles vous voulez accorder l'accès. {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) est le système de gestion des accès permettant de gérer les ressources de façon cohérente sur la plateforme {{site.data.keyword.Bluemix_notm}}. L'infrastructure {{site.data.keyword.Bluemix_notm}} et les ressources Cloud Foundry ne sont pas gérées à l'aide de Cloud IAM. Ces types de ressource disposent de leur propre système de gestion des accès. Si vous avez une combinaison de types de ressource, vous gérez chaque type séparément. Pour affecter des accès à vos ressources d'infrastructure, vous définissez des droits au sein de votre compte SoftLayer. Pour affecter des accès à des ressources Cloud Foundry, vous utilisez l'option Assign by using Cloud Foundry de la section Identity and Access de la console.

## Qui est autorisé à gérer les accès ?

En tant que propriétaire de compte, vous pouvez gérer les accès à toutes les ressources e votre compte. Vous pouvez également déléguer la tâche de gestion des accès à des ressources de la plateforme en affectant à un utilisateur de votre compte le rôle d'administrateur de tous les services.

Si votre compte détient des services Cloud Foundry, vous pouvez affecter à un autre utilisateur le rôle de responsable de l'organisation ou de l'espace de sorte qu'il puisse ajouter des utilisateurs et affecter des rôlesCloud Foundry pour l'accès à des instances de l'organisation ou de l'espace qu'il gère.


## Comment démarrer la gestion des accès ?

Accédez à **Gérer** &gt; **Sécurité** &gt; **Identity and Access**, puis sélectionnez **Utilisateurs** pour démarrer la gestion des accès pour les utilisateurs de votre compte. Sélectionnez un utilisateur dans la liste. Seules les options de gestion des accès que vous êtes autorisé à gérer s'affichent. Par exemple, si vous n'êtes pas propriétaire de compte ni un responsable d'organisation ou d'espace, l'option de gestion des accès Cloud Foundry ne s'affiche pas.

Vous pouvez également affecter des rôles d'accès à des applications et des services en utilisant les ID de service. Pour ce faire, accédez à la page **ID de service**. Pour plus d'informations sur la manière de démarrer et de travailler rapidement avec Cloud IAM, voir le [tutoriel d'initiation](/docs/iam/quickstart.html#getstarted).

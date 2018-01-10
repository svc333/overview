---


copyright:
  years: 2016, 2017
lastupdated: "2017-11-30"

---

{:shortdesc: .shortdesc}
{:tip: .tip}
{:new_window: target="_blank"}

# Fonctionnement de la console {{site.data.keyword.cloud_notm}}
{: #ui}

La console {{site.data.keyword.cloud}} est une interface utilisateur qui vous aide à gérer l'intégralité de vos ressources {{site.data.keyword.cloud_notm}}. En accédant à la [console](https://console.bluemix.net){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon"), vous pouvez créer un compte gratuit, vous connecter, accéder à la documentation, accéder au catalogue, afficher les informations de tarification, obtenir de l'aide ou vérifier le statut de tous les composants {{site.data.keyword.cloud_notm}}. Une fois que vous êtes connecté, la barre de menus contient une icône de menu ![Icône de menu](../icons/icon_hamburger.svg) et des liens supplémentaires, selon votre type de compte.
{: shortdesc}

## Utilisation de la console
{: #consoleoptions}

Si vous êtes un utilisateur existant qui dispose d'un compte {{site.data.keyword.cloud_notm}}, vous pouvez utiliser l'icône de menu ![Icône de menu](../icons/icon_hamburger.svg) pour accéder à toute les ressources existantes sur votre tableau de bord. 
  * Utilisez le lien **Catalogue** pour créer de nouvelles ressources.
  * Utilisez le lien **Documentation** pour accéder à des informations utiles concernant {{site.data.keyword.cloud_notm}}.
  * A partir du menu **Support**, vous pouvez accéder à des informations concernant les nouveautés de {{site.data.keyword.cloud_notm}}, le centre de support, les options d'ajout et d'affichage des tickets et la page Statut.
  * A partir du menu **Gérer**, vous pouvez accéder à votre compte, à la facturation et l'utilisation et aux options de sécurité.

Si vous avez lié vos comptes {{site.data.keyword.cloud_notm}} et SoftLayer,  vous disposez des mêmes options qu'un propriétaire de compte non lié et vous pouvez de plus accéder au portail client en sélectionnant l'**icône Menu  ![Icône Menu](../icons/icon_hamburger.svg)  > option Infrastructure**. A partir de là, vous pouvez afficher le récapitulatif de votre compte, commander de l'espace de stockage et des périphériques, et gérer les accès des utilisateurs et périphériques du réseau privé virtuel uniquement. 

## Gestion des ressources sur le tableau de bord
{: #dashboardview}

Vous pouvez utiliser le tableau de bord pour afficher et utiliser des ressources {{site.data.keyword.cloud_notm}}. Le terme *ressource* désigne un large éventail d'éléments qui va d'un service à un compte. Pour une définition plus succincte, voir le [{{site.data.keyword.cloud_notm}} glossaire](/docs/overview/glossary/index.html#glossr).

### Affichage des ressources

Vous pouvez afficher toutes les ressources de votre compte à partir du tableau de bord. Pour personnaliser l'affichage, vous disposez des options suivantes :

  * Pour afficher les ressources d'un groupe de ressources spécifique, sélectionnez un groupe de ressources dans la liste **Groupe de ressources**. 
  * Pour afficher les ressources d'une organisation Cloud Foundry spécifique, sélectionnez une organisation dans la liste **Organisation Cloud Foundry**. 

Ensuite, sur la base des éléments sélectionnés, vous pouvez filtrer à l'aide des options suivantes :

  * Région
  * Espace Cloud Foundry
  
### Utilisation des ressources

Vous pouvez utiliser vos ressources de différentes manières à partir du tableau de bord :

  * Chaque ressource est affichée sur sa propre ligne avec une icône Plus d'actions ![Icône Plus d'actions](../icons/overflow-menu.svg) en fin de ligne. Cliquez sur l'icône Plus d'actions pour démarrer, arrêter, renommer ou supprimer une ressource. 
  * Pour définir des données d'identification ou des connexions pour une ressource, cliquez sur le nom de la ressource afin d'accéder à la page des détails de la ressource. Pour plus d'informations, voir [Ajout de nouvelles données d'identification](/docs/services/service_credentials.html) et [Gestion des connexions](/docs/manageapps/connecting_apps.html). 

## Utilisation du catalogue
{: #catalogcreate}

Pour créer une nouvelle ressource, cliquez sur **Create resource** dans le tableau de bord. Vous êtes alors dirigé vers le catalogue. Lorsque vous sélectionnez une vignette dans le catalogue, vous pouvez déterminer où la ressource est disponible. Les ressources du catalogue ne sont pas nécessairement disponibles dans toutes les régions. 

Après avoir cliqué sur la vignette de la ressource que vous voulez créer, vous pouvez sélectionner l'emplacement où vous voulez la déployer. 

  * Pour les ressources Cloud Foundry, vous pouvez sélectionner une région spécifique, puis sélectionner l'organisation et l'espace auxquels l'instance de service doit être affectée.
  * Pour les ressources gérées par {{site.data.keyword.cloud_notm}} Identity and Access Management (IAM), vous sélectionnez un emplacement pour le déploiement. Ensuite, vous sélectionnez un groupe de ressources auquel affecter l'instance de service.

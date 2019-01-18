---


copyright:
  years: 2015, 2018
lastupdated: "2018-11-28"

---

{:shortdesc: .shortdesc}
{:tip: .tip}
{:new_window: target="_blank"}

# Navigation dans la console {{site.data.keyword.cloud_notm}} 
{: #ui}

La console {{site.data.keyword.cloud}} est une interface utilisateur qui vous aide à gérer l'intégralité de vos ressources {{site.data.keyword.cloud_notm}}. En accédant à la [console](https://cloud.ibm.com){: new_window} ![Icône de lien externe](../icons/launch-glyph.svg "Icône de lien externe"), vous pouvez créer un compte gratuit, vous connecter, accéder à la documentation, accéder au catalogue, afficher les informations de tarification, obtenir de l'aide ou vérifier le statut des composants {{site.data.keyword.cloud_notm}}. Une fois que vous êtes connecté, la barre de menus contient une icône de menu ![Icône Menu](../icons/icon_hamburger.svg) ainsi que des liens supplémentaires.
{: shortdesc}


## Utilisation de la console
{: #consoleoptions}

Lorsque vous vous connectez à {{site.data.keyword.cloud_notm}}, la première page qui s'affiche est le tableau de bord. Ce dernier inclut des widgets qui présentent le statut de votre compte. Vous pouvez ensuite gérer vos ressources. Accédez à l'icône Menu ![Icône Menu](../icons/icon_hamburger.svg) &gt; **Liste de ressources** pour afficher toutes les ressources existantes de votre compte.

  * Utilisez le lien **Catalogue** pour créer de nouvelles ressources.
  * Utilisez le lien **Documentation** pour accéder à des informations utiles concernant {{site.data.keyword.cloud_notm}}.
  * Utilisez le lien **Support** pour accéder au centre de support.  
  * Dans le menu **Gérer**, vous pouvez accéder à vos options de compte, de facturation ainsi qu'à celles concernant Identity and Access Management.
  * Cliquez sur l'icône Estimateur de coût ![Icône Estimateur de coût](../icons/Estimator.svg) pour ouvrir cet estimateur.
  * Cliquez sur l'icône Notifications ![Icône Notifications](../icons/Notification.svg) pour accéder aux annonces et aux événements planifiés et à ceux non planifiés.

## Recherche de ressources
{: #search}

Vous pouvez rechercher des ressources par nom ou par étiquette à partir de tout emplacement de la console {{site.data.keyword.cloud_notm}} pour les ressources devant se trouver dans la liste de ressources. Entrez le nom d'une ressource ou une étiquette dans la zone de recherche de la barre de menu de la console.

Pour plus d'informations, voir [Recherche de ressources](/docs/resources/searching.html#searching-for-resources). 

## Gestion des ressources de la liste de ressources
{: #dashboardview}

Accédez à l'icône Menu ![Icône Menu](../icons/icon_hamburger.svg) &gt; **Liste de ressources** pour accéder à la liste de vos ressources de compte. Vous pouvez utiliser la liste des ressources pour afficher et utiliser des ressources {{site.data.keyword.cloud_notm}} et des instances de service Cloud Foundry. Pour plus d'informations sur les différents types de ressources, voir [Qu'est-ce qu'une ressource ?](/docs/resources/acct_resources.html#resource).

### Affichage des ressources
Dans le tableau de bord, vous pouvez afficher toutes les ressources des régions liées à la liste de ressources. Pour afficher les éléments les plus importants pour vous, triez votre liste avec les filtres pour chaque en-tête de colonne. Par exemple, si vous souhaitez afficher et utiliser les ressources d'un emplacement spécifique, développez le menu **Emplacement** puis sélectionnez-en un dans la liste.

### Utilisation des ressources
Vous pouvez utiliser vos ressources de différentes manières à partir de la liste de ressources :

  * Chaque ressource est affichée sur sa propre ligne avec une icône Actions ![Icône Plus d'actions](../icons/action-menu-icon.svg) en fin de ligne. Cliquez sur l'icône Actions ![Icône Plus d'actions](../icons/action-menu-icon.svg) pour démarrer, arrêter, renommer ou supprimer une ressource.
  * Pour définir des données d'identification ou des connexions pour une ressource, cliquez sur le nom de la ressource afin d'accéder à la page des détails de la ressource. Sélectionnez ensuite **Données d'identification pour le service** ou **Connexions**. Pour plus d'informations, voir [Ajout de données d'identification](/docs/resources/service_credentials.html) et [Gestion des connexions](/docs/resources/connecting_apps.html#connect_app).


## Utilisation du catalogue
{: #catalogcreate}

Pour créer une ressource, cliquez sur **Créer** dans votre liste de ressources. Vous êtes alors dirigé vers le catalogue. Lorsque vous sélectionnez une vignette dans le catalogue, vous pouvez déterminer où la ressource est disponible. Les ressources du catalogue ne sont pas nécessairement disponibles dans toutes les régions.

Après avoir cliqué sur la vignette de la ressource que vous voulez créer, vous pouvez sélectionner l'emplacement où vous voulez la déployer.

  * Pour les ressources Cloud Foundry, vous pouvez sélectionner une région spécifique, puis sélectionner l'organisation et l'espace auxquels l'instance de service doit être affectée.
  * Pour les ressources gérées par {{site.data.keyword.cloud_notm}} Identity and Access Management (IAM), vous sélectionnez un emplacement pour le déploiement. Ensuite, vous sélectionnez un groupe de ressources auquel affecter l'instance de service.

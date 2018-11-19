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

# Emplacements pour déploiement de ressources 
{: #ov_intro_reg}

Vous pouvez créer des instances d'application et de service dans différents emplacements avec la même infrastructure {{site.data.keyword.cloud_notm}} pour la gestion des applications et la même vue détaillée de l'utilisation pour la facturation. Vous pouvez déployer vos applications sur l'emplacement le plus proche de vos clients pour réduire les temps d'attente de votre application. 

Pour répondre aux considérations de sécurité, vous pouvez également sélectionner l'emplacement où conserver vos données d'application. Lorsque vous construisez des applications sous un ou plusieurs emplacements et que l'un d'eux devient indisponible, les applications situées aux autres emplacements continuent de fonctionner. Votre franchise de ressources est la même dans tous les emplacements que vous utilisez. Pour plus d'informations sur les ressources de plateforme et les emplacements où elles sont disponibles, voir [Disponibilité des services](/docs/resources/service_region.html).

L'équilibrage de charge global pour la console garantit que si l'emplacement géographique le plus proche tombe en panne, la console affiche les informations de l'emplacement le plus proche suivant. De la sorte, vous pouvez toujours accéder à la console sans avoir à effectuer d'action pour obtenir les informations dont vous avez besoin.

Dans le tableau de bord, vous pouvez afficher par défaut toutes les ressources à travers tous les emplacements. Si vous souhaitez afficher et utiliser les ressources d'un emplacement spécifique, développez le menu **EMPLACEMENT** puis sélectionnez-en un dans la liste. 

Vous pouvez également utiliser l'interface de ligne de commande pour vous connecter à l'emplacement {{site.data.keyword.cloud_notm}} souhaité en utilisant la commande `ibmcloud api` et en spécifiant le noeud final d'API de l'emplacement. Entrez, par exemple, la commande suivante, pour vous connecter à {{site.data.keyword.cloud_notm}}, Londres :

```
ibmcloud api https://api.eu-gb.bluemix.net
```

Un préfixe unique est affecté à chaque emplacement. {{site.data.keyword.cloud_notm}} fournit les emplacements et les préfixes d'emplacement suivants :

| **Emplacement** | **Noeud final d'API** |
|-----------------|-------------------|
| Dallas | api.us-south.bluemix.net |
| Sydney | api.au-syd.bluemix.net |
| Frankfort | api.eu-de.bluemix.net |
| Londres | api.eu-gb.bluemix.net |
| Washington DC | api.us-east.bluemix.net |
| Tokyo | api.jp-tok.bluemix.net |
{: caption="Tableau 1. Liste des emplacements {{site.data.keyword.cloud_notm}}" caption-side="top"}

Lorsque vous déployez des ressources d'infrastructure, vous disposez de plus d'options quant à l'emplacement de vos contenus. Vous pouvez sélectionner un emplacement ou effectuer une sélection dans une liste de centres de données dans {{site.data.keyword.Bluemix_notm}}. Pour plus d'informations, voir [Centres de données {{site.data.keyword.cloud_notm}}](data-centers.html).

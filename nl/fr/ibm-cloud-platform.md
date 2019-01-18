---


copyright:
  years: 2016, 2018
lastupdated: "2018-11-30"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# De quoi est composée la plateforme {{site.data.keyword.Bluemix_notm}} ?
{: #whatis}

La plateforme de cloud d'IBM associe la plateforme sous forme de service (PaaS) à l'infrastructure sous forme de service (IaaS) afin d'offrir une expérience intégrée. La plateforme s'adapte à la fois à de petites organisations et équipes de développement et à de grandes entreprises et les prend en charge. Globalement déployée dans des centres de données dans le monde entier, la solution générée sur {{site.data.keyword.cloud}} est rapide et s'exécute en toute fiabilité dans un environnement testé et pris en charge digne de confiance.
{: .shortdesc}

La plateforme {{site.data.keyword.Bluemix_notm}} inclut plusieurs composants qui offrent une expérience cohérente et fiable. 

  * Un catalogue qui inclut des centaines d'offres {{site.data.keyword.Bluemix_notm}}
  * Une console robuste utilisée comme serveur frontal pour la création, l'affichage et la gestion de vos ressources de cloud
  * Un composant Identity and Access Management (IAM) qui authentifie de manière sécurisée les utilisateurs pour les services de plateforme et contrôle l'accès aux ressources de manière cohérente dans {{site.data.keyword.Bluemix_notm}}
  * Un mécanisme de recherche et d'étiquetage pour le filtrage et l'identification de vos ressources
  * Un système de gestion de compte et de facturation présentant une utilisation exacte des plans de facturation et une protection contre la fraude aux cartes de crédit

## Choix de votre environnement d'hébergement
{: #choose-compute}

Avec {{site.data.keyword.Bluemix_notm}}, il n'est plus nécessaire d'effectuer d'investissements importants en termes de matériel pour tester ou exécuter une nouvelle application. A la place, nous gérons tout pour vous et ne vous facturons que ce que vous utilisez. Votre environnement de serveur Cloud constitue la base de votre couche d'infrastructure. Vous pouvez choisir une seule option ou un ensemble d'options pour plusieurs environnements complexes. 

Vous disposez de plusieurs options pour l'hébergement de vos applications, ce qui vous permet d'avoir le niveau de contrôle souhaité ou requis sur l'infrastructure. Vous pouvez exécuter votre application de l'une des façons suivantes :

  * En tant que fonction sans serveur
  * En tant qu'application Cloud Foundry
  * En tant que conteneur Docker sur un cluster Kubernetes
  * En tant que VMware
  * En tant que machine virtuelle
  * Sur {{site.data.keyword.baremetal_short}} à hautes performances 

Les serveurs {{site.data.keyword.baremetal_short}} sont des serveurs physiques à service unique dédiés à un seul client. Vous pouvez pratiquement tout contrôler, de l'hôte de serveur à la mémoire RAM et aux périphériques de stockage. Ces serveurs sont utilisés avec des charges de travail demandant une puissance de calcule pendant une longue période (par exemple, plusieurs mois). 

Les serveurs {{site.data.keyword.BluVirtServers_short}} peuvent être déployés comme instances publiques ou dédiées. Avec des instances publiques, les ressources du serveur sont partagées avec d'autres clients (il s'agit alors d'un environnement à service partagé). Les instances privées dédient les ressources du serveur physique à un client qui peut avoir une ou plusieurs machines virtuelles sur le même serveur. Ces serveurs constituent la solution idéale pour les charges de travail s'exécutant pendant une période limitée (plusieurs semaines, par exemple). Le développement et le test, la sauvegarde et la reprise ainsi que la reprise après incident constituent des exemples de charge de travail. Pour plus d'informations sur les options de serveur, voir [Bare metal servers vs. virtual servers: Choosing the best option for you](https://www.ibm.com/blogs/bluemix/2018/06/bare-metal-virtual-servers-works/){: new_window} ![Icône de lien externe](../icons/launch-glyph.svg "Icône de lien externe").

Consultez le tableau suivant pour obtenir un récapitulatif de vos options de calcul.

| Option | Description | 
|--------|---------------|
| [{{site.data.keyword.baremetal_short}}](/docs/bare-metal/about.html)  | Serveurs à service exclusif horaires ou mensuels qui vous sont dédiés et qui ne sont pas partagés (notamment les ressources de serveur) avec d'autres clients. |
| [{{site.data.keyword.BluVirtServers_short}}](/docs/vsi/vsi_about.html) | Serveurs virtuels évolutifs achetés avec des coeurs dédiés et des allocations de mémoire. |
| [{{site.data.keyword.vmwaresolutions_short}}](/docs/services/vmwaresolutions/vmonic/prod_overview.html) | Intègre ou migre rapidement et en toute transparence des charges de travail VMware locales en utilisant une infrastructure évolutive, sécurisée et à hautes performances ainsi que la technologie de virtualisation hybride VMware de pointe. |
| [{{site.data.keyword.containerlong_notm}}](/docs/containers/cs_why.html) | Associe les conteneurs Docker, la technologie Kubernetes, une expérience utilisateur intuitive ainsi que l'isolement et la sécurité intégrés permettant d'automatiser le déploiement, le fonctionnement, la mise à l'échelle et la surveillance des applications conteneurisées dans un cluster d'hôtes de calcul. |
| [{{site.data.keyword.cfee_full_notm}}](/docs/cloud-foundry/index.html) | Instancie à la demande plusieurs plateformes Cloud Foundry d'entreprise isolées. |
| [{{site.data.keyword.openwhisk_short}}](/docs/openwhisk/index.html) | Plateforme de programmation FaaS (Functions-as-a-Service) basée sur Apache OpenWhisk. |
{: caption="Tableau 1. Options de calcul" caption-side="top"}

## Génération d'applications
{: #build-apps}

Que vous disposiez d'un [code existant](/docs/apps/tutorials/tutorial_byoc.html) que vous souhaitez moderniser et placer sur le cloud ou que vous développiez une [toute nouvelle application](/docs/apps/tutorials/tutorial_starter-kit.html), vos développeurs peuvent bénéficier de l'écosystème à croissance rapide des services disponibles et des infrastructures d'exécution d'{{site.data.keyword.Bluemix_notm}}.

Des [guides de programmation](https://cloud.ibm.com/docs/home/build){: new_window} ![Icône de lien externe](../icons/launch-glyph.svg "Icône de lien externe") sont disponibles pour chaque langage. Grâce à eux, vous pouvez commencer à effectuer les tâches souhaitées. Avec l'infrastructure {{site.data.keyword.Bluemix_notm}}, vous disposez de plusieurs options pour l'hébergement de vos applications, qu'il s'agisse de serveurs de type {{site.data.keyword.baremetal_short}} ou d'exécution en tant que fonction sans serveur.

## Connexion de services
{: #connect-services}

Avec plus de 190 services disponibles dans le catalogue, vous pouvez choisir une solution adaptée à vos besoins. Par ailleurs, vous pouvez facilement connecter des services à des applications en dehors d'{{site.data.keyword.Bluemix_notm}} si cela est adapté à votre situation. Vous pouvez générer un nouveau jeu de données d'identification pour le cas où vous voudriez connecter manuellement un consommateur extérieur à un service {{site.data.keyword.Bluemix_notm}}. Par exemple, si vous tentez de connecter une application se trouvant hors d'{{site.data.keyword.Bluemix_notm}} à un service Watson, vous générez de nouvelles données d'identification qui connectent entre eux ces deux éléments. C'est aussi simple que ça ! Pour plus d'informations, voir [Ajout de données d'identification](/docs/resources/service_credentials.html#service_credentials).

## Configuration de votre compte

Si vous testez {{site.data.keyword.Bluemix_notm}}, vous pouvez accéder directement au catalogue et commencer à évaluer les services que vous souhaitez explorer et ajouter à votre compte d'essai ou Lite. Toutefois, si vous êtes prêt à utiliser un environnement pour un groupe de développeurs ou l'ensemble d'une organisation et placer vos applications en production, pensez à configurer les éléments fondamentaux de votre compte :

* Groupes d'accès pour l'organisation des utilisateurs et ID de service dans une entité afin de faire de l'affectation d'accès un processus rationalisé.
* Groupes de ressources pour l'organisation de vos ressources pour l'affectation rapide et simple de l'accès à un ensemble de ressources.
* Règles d'accès pour vos groupes d'accès ou des développeurs individuels qui ont besoin de règles d'accès IAM ou de rôles d'espace et d'organisation Cloud Foundry.

Pour plus d'informations, voir les [meilleures pratiques pour la configuration de votre compte](/docs/account/bp_account.html#account_setup) et les [meilleures pratiques pour l'affectation d'accès](/docs/iam/bp_access.html). De plus, si vous êtes prêt à commencer, consultez les différents éléments de la [hiérarchie des comptes](/docs/account/account_overview.html#overview).

## Tarification et facturation

Quel que soit votre type de compte, vous pouvez explorer {{site.data.keyword.Bluemix_notm}} en utilisant des plants Lite offrant un quota gratuit. Lorsque vous choisissez un service dans le catalogue et sélectionnez une vignette s'il existe différents types de plans disponibles, vous pouvez voir des informations détaillées sur la tarification. Si vous choisissez un plan de service avec un plan payant, vous pouvez estimer vos coûts en utilisant l'outil d'estimation de coûts. Pour plus d'informations, voir [Estimation des coûts](/docs/billing-usage/estimating_costs.html#cost).

La facturation {{site.data.keyword.Bluemix_notm}} offre plusieurs services qui garantissent le fait que la plateforme {{site.data.keyword.Bluemix_notm}} peut gérer en toute sécurité la tarification, les comptes, l'utilisation, etc.

### Gestion des comptes {{site.data.keyword.Bluemix_notm}}
{: #account}

La gestion des comptes gère les échanges liés à la facturation avec le client. Chaque compte est une entité de facturation qui représente un client. Ce service contrôle le cycle de vie, l'abonnement, la relation utilisateur et l'organisation du compte.

### Tarification {{site.data.keyword.Bluemix_notm}}
{: #pricing}

Le service de la plateforme de tarification {{site.data.keyword.Bluemix_notm}} permet aux utilisateurs de définir, gérer et extraire des informations de tarification pour les ressources du catalogue {{site.data.keyword.Bluemix_notm}}.

### Collecteur de relevés {{site.data.keyword.Bluemix_notm}}
{: #metering}

{{site.data.keyword.Bluemix_notm}} Usage Metering est un service de plateforme qui permet aux fournisseurs de services de soumettre des mesures collectées pour les instances de ressource mises à disposition par les utilisateurs {{site.data.keyword.Bluemix_notm}}. Les fournisseurs de services tiers qui offrent un service de facturation intégrée dans {{site.data.keyword.Bluemix_notm}} doivent soumettre toutes les heures l'utilisation pour toutes les instances de service actives. Cette étape est importante car l'impossibilité de transmettre les informations d'utilisation peut générer une perte de collecte des recettes pour IBM, pouvant ensuite provoquer une perte de recettes pour le fournisseur de services tiers.

## {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM)
{: #iam}

{{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) vous permet d'authentifier de manière sécurisée les utilisateurs des services de plateforme et de contrôler de façon cohérente l'accès aux ressources dans la plateforme {{site.data.keyword.Bluemix_notm}}. Pour plus de détails, voir [Qu'est-ce qu'IAM ?](/docs/iam/index.html) IAM fournit des API et des commandes d'interface CLI vous permettant de gérer vos jetons, vos groupes d'accès et vos règles.


## Création de ressources
{: #provisioning-layer}

Le contrôleur de ressources constitue la couche de mise à disposition de plateforme {{site.data.keyword.Bluemix_notm}} de nouvelle génération qui gère le cycle de vie des ressources {{site.data.keyword.Bluemix_notm}} dans un compte client. Les ressources sont mises à disposition dans une portée de compte. Le contrôleur de ressources prend en charge la mise à disposition synchrone et asynchrone de ressources. La couche de mise à disposition a la charge du contrôle et du suivi du cycle de vie des ressources dans un compte client. Les ressources sont des composants physiques et logiques pouvant être mis à disposition ou réservés pour une application ou une instance de service. Exemples de ressources : bases de données, comptes, processeurs, limites de mémoire et de stockage. En général, les ressources suivies par la couche de mise à disposition sont conçues de telle sorte que la facturation et les mesures d'utilisation soient associées mais ce n'est pas toujours le cas. Dans la plupart des cas, les ressources peuvent être associées à la couche de mise à disposition afin de garantir que le cycle de vie des ressources peut être géré en même temps que le cycle de vie des comptes. Le contrôleur de ressources utilise IAM pour l'authentification et l'autorisation des actions effectuées dans la couche de mise à disposition.

### Gestion du cycle de vie des ressources
{: #lifecycle}

Le contrôleur de ressources fournit des API communes afin de contrôler le cycle de vie des ressources composé des étapes suivantes : mise à disposition (création d'une instance), liaison (création de données d'identification d'accès), annulation de la liaison (retrait d'accès), annulation de la mise à disposition (suppression d'une instance).

Le contrôleur de ressources fournit des API vous permettant de gérer les éléments suivants de votre cycle de vie de ressources :
* Mise à disposition
* Mise à jour d'une instance de ressource
* Liaison
* Clés de ressource
* Annulation de la liaison
* Annulation de la mise à disposition


## Gestion de vos ressources
{: #resource-manager}


Le gestionnaire de ressources {{site.data.keyword.Bluemix_notm}} gère la collection de ressources par [groupes de ressources](/docs/overview/resource-groups.html#whatis). Un groupe de ressources appartient à un compte. Toutes les ressources {{site.data.keyword.Bluemix_notm}} doivent être mises à disposition dans un groupe de ressources. Si un compte est suspendu, le groupe de ressources correspondant est également suspendu ainsi que toutes les ressources du groupe. Lorsqu'un utilisateur crée un compte, un groupe de ressources par défaut est créé dans le compte. Toutes les ressources activées par IAM {{site.data.keyword.Bluemix_notm}} doivent être mises à disposition dans un groupe de ressources. Si un compte est suspendu, le groupe de ressources correspondant est également suspendu ainsi que toutes les ressources du groupe. Pour un compte standard, un utilisateur ne peut avoir qu'un seul groupe de ressources. Pour un compte Paiement à la carte ou Abonnement, un utilisateur est autorisé à créer plusieurs groupes de ressources. 


## Catalogue {{site.data.keyword.Bluemix_notm}}
{: #catalog}

Le catalogue {{site.data.keyword.Bluemix_notm}} stocke les définitions d'offre (description, fonctions, images, URL, etc.) des ressources affichées dans la console {{site.data.keyword.Bluemix_notm}}. Le service de catalogue gère les offres dans différentes zones géographiques de la même façon que le système d'enregistrement. Le catalogue prend en charge des interfaces CLI et une API RESTful où vous pouvez extraire des informations sur les offres existantes et créer, gérer et supprimer leurs offres. A partir de l'URL de base, utilisez les noeuds finaux pour extraire des métadonnées sur les services du catalogue et pour gérer la visibilité des services. En fonction du type d'objet, les métadonnées peuvent inclure des informations sur la tarification, la mise à disposition, les régions, etc. Pour plus d'informations, voir [Gestion du catalogue](/docs/overview/catalog.html#global-catalog-overview).

## Recherche et étiquetage de ressources
{: #search-and-tag}

Le service de recherche est un référentiel de propriétés de ressources global et partagé intégré à la plateforme {{site.data.keyword.Bluemix_notm}}. Il est utilisé pour le stockage et la recherche des attributs des ressources de cloud. Il catégorise et classe les ressources. Une ressource est contrôlée par des fournisseurs de ressources de la plateforme {{site.data.keyword.Bluemix_notm}}, comme Cloud Foundry, les conteneurs IBM ou le contrôleur de ressources et appartient à ces fournisseurs. Les ressources sont identifiées de manière unique par un identificateur CRN ([Cloud Resource Name](/docs/overview/crn.html#crn)). Les propriétés d'une ressource incluent des étiquettes et des propriétés système. Les deux propriétés sont définies dans un compte de facturation {{site.data.keyword.Bluemix_notm}} et s'appliquent à plusieurs régions.

Ce service gère également les étiquettes associées à une ressource. Vous pouvez créer, supprimer, rechercher, associer ou dissocier des étiquettes à l'aide de l'API d'étiquetage. Les étiquettes sont identifiées de manière unique par un identificateur CRN (Cloud Resource Naming). Les étiquettes ont un nom, qui doit être unique dans un compte de facturation. Elles peuvent avoir le format `clé:valeur` ou un format de libellé.


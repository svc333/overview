---

copyright:
  years: 2016, 2019
lastupdated: "2019-02-19"

keywords: developer tools, building apps, developer entry point, understanding dev journey, get started coding

subcollection: overview

---
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}
{:tip: .tip}

# Exploration de la démarche d'un développeur dans {{site.data.keyword.cloud_notm}}
{: #dev-journey}

En tant que développeur, vous décidez du meilleur point d'entrée pour votre code. Vous pouvez choisir de générer votre code en utilisant nos outils fournis ou utiliser votre propre code et le déployer dans {{site.data.keyword.cloud}}.
{: shortdesc}

{{site.data.keyword.cloud_notm}} comprend un ensemble de fonctions qui vous permet de commencer à générer des applications en quelques minutes. {{site.data.keyword.cloud_notm}} Developer Tools crée une base à hautes performances dont vous avez besoin pour être opérationnel. Les deux outils principaux suivants sont disponibles pour le développement :
 * Console Web {{site.data.keyword.cloud_notm}} (portails de développeur)
 * {{site.data.keyword.cloud_notm}}interface de ligne de commande

Avec {{site.data.keyword.cloud_notm}}, vous pouvez :

* Sélectionner des kits de démarrage qui sont propres aux cas d'utilisation et générer des applications prêtes pour la production dans différents langages de programmation et modèles d'architecture.
* Utiliser un [modèle de code IBM Developer ![Icône de lien externe](../icons/launch-glyph.svg "Icône de lien externe")](https://developer.ibm.com/patterns/){:new_window} pour créer rapidement votre application et la déployer dans {{site.data.keyword.cloud_notm}}.
* Afficher et gérer les ressources automatiquement mises à disposition à partir de votre kit de démarrage ou ajoutées manuellement à votre application.
* Si vous avez une application dans un référentiel existant, vous pouvez utiliser un kit de démarrage vide pour créer un enregistrement d'application et le connecter à votre référentiel de ressources et à une chaîne d'outils DevOps.
* Avec un code d'application portable, vous pouvez effectuer le déploiement dans plusieurs environnements de cloud.
* Créer une [chaîne d'outils DevOps](/docs/services/ContinuousDelivery?topic=ContinuousDelivery-cd_getting_started) en quelques clics.
* Utiliser l'[interface de ligne de commande (CLI)](/docs/cli/reference/ibmcloud?topic=cloud-cli-ibmcloud-cli#ibmcloud-cli) pour le développement local.
* Parcourir le catalogue [{{site.data.keyword.cloud_notm}}![Icône de lien externe](../icons/launch-glyph.svg "Icône de lien externe")](https://{DomainName}/catalog){: new_window} ou rechercher dans ce dernier des applications et des services que vous pouvez créer et commencer à utiliser dès aujourd'hui.

![Présentation de Developer Experience](images/dev-journey.png "Présentation de Developer Experience")

Pour comprendre comment notre expérience peut vous aider à générer rapidement des applications prêtes pour la production de grande qualité, examinons ces éléments de façon plus détaillée.

## Portails de développeur
{: #dev-portals}

{{site.data.keyword.cloud_notm}} propose des portails de développeur s'appliquant à différents domaines d'intérêt (par exemple, Watson, la sécurité ou la finance) ou un canal de vente numérique (par exemple, les applications mobiles ou Web). Vous pouvez accéder à ces portails à partir de l'icône **Menu** ![Icône Menu](../icons/icon_hamburger.svg).

Chaque portail de développeur fournit des kits de démarrage adaptés au domaine d'intérêt du portail. Les portails incluent un flux de travaux cohérent et intuitif pour la création d'une application fonctionnelle prête pour la production en quelques minutes.

## Applications
{: #app-projects}

Une application est composée de code, de données, de services et de chaînes d'outils. Par exemple, l'application mobile {{site.data.keyword.cloud_notm}} contient le code de l'appareil ainsi qu'une logique de back end, le stockage de données, les services d'analyse et de sécurité, et est configurée pour la distribution continue.

![Réutiliser](images/garage_reuse2.png "Avec Developer Experience, vous pouvez réutiliser l'existant")

Vous pouvez créer et gérer une application à l'aide de n'importe quel portail de développeur {{site.data.keyword.cloud_notm}} ou du plug-in {{site.data.keyword.dev_cli_notm}}.

Vous pouvez créer des applications simples et vides directement ou créer des applications plus complexes en utilisant nos kits de démarrage. Si vous choisissez de créer des applications vides sans avoir recours à un kit de démarrage, vous pouvez utiliser le tableau de bord [{{site.data.keyword.cloud_notm}} ![Icône de lien externe](../icons/launch-glyph.svg "Icône de lien externe")](https://{DomainName}){: new_window} sans accéder à un portail.

Vous pouvez utiliser un modèle de code pour créer rapidement votre application et la déployer dans {{site.data.keyword.cloud_notm}}. Sur le site Web [IBM Developer![Icône de lien externe](../icons/launch-glyph.svg "Icône de lien externe")](https://developer.ibm.com/patterns/){:new_window}, choisissez un modèle de code. Vous pouvez afficher le code dans GitHub ou créer et générer une application sur {{site.data.keyword.cloud_notm}}, où vous pouvez utiliser une chaîne d'outils DevOps pour déployer automatiquement votre application.


## Kits de démarrage
{: #starter-kits}

Grâce aux kits de démarrage, tout devient facile et personnalisable. Les kits de démarrage assemblent dans le langage de votre choix une application de production squelette prête pour le déploiement en cloud. Chaque kit de démarrage inclut un langage, une infrastructure et un modèle pour un cas d'utilisation spécifique et pour la réutilisation du code.

Si un kit de démarrage requiert des ressources spécifiques, cela ne constitue nullement un problème. Avec des ressources mises à disposition automatiquement, {{site.data.keyword.cloud_notm}} crée des instances de ces ressources lorsque vous créez votre application. Vous pouvez accéder à des kits de démarrage à partir du portail de développeur ou d'une interface de ligne de commande pour obtenir des instructions concernant votre domaine d'intérêt et votre flux de travaux.

### Qu'est-ce qui distingue les kits de démarrage des exemples ?
Les kits de démarrage sont prêts pour la production et ont pour principal objectif de présenter une implémentation de modèle de clé à l'aide d'un environnement d'exécution (par exemple, Node.js et Express). Dans certains cas, les kits de démarrage offrent une expérience utilisateur simple ayant pour but de mettre en évidence l'intégration du service. Dans d'autres cas, les kits de démarrage représentent une implémentation personnalisable d'un cas d'utilisation sophistiqué.

* Un fragment correspond à quelques lignes de code, souvent présentées dans une interface IDE. Les fragments aident un développeur à intégrer une syntaxe de langage de programmation ou une intégration de support à une API définie.
* Une démonstration est généralement de très bonne qualité et d'une grande fidélité et utilise une gamme de services et de points d'intégration. Elle requiert souvent un certain temps de réglage et est utilisée pour démontrer un problème ou illustrer un dispositif de plateforme. Vous pouvez l'utiliser pour évaluer les phases d'adoption du cloud. Parfois, il s'agit de code inclus dans le code de production.
* Un exemple est un petit exemple d'un dispositif, d'une fonction, d'un service ou d'une démarche utilisateur spécifique. Vous pouvez réutiliser un exemple ou l'inclure dans une application de production. Il est généralement utilisé pour montrer des capacités techniques et une approche possible de résolution d'un problème technique.
* Un kit de démarrage est un modèle prêt pour la production qui peut être intégré à un ensemble de services afin de générer un élément prêt pour la production pouvant être déployé directement dans un pipeline DevOps et un cluster Kubernetes. Un kit de démarrage contient des métadonnées descriptives qui fournissent à l'utilisateur suffisamment d'informations pour lui permettre de déterminer ce qu'il est et ce qu'il fait. Il contient également des instructions indiquant à {{site.data.keyword.cloud_notm}} ce qu'il doit produire. Le résultat est prêt pour la production et peut être itéré pour des améliorations futures à l'aide des meilleures pratiques d'IBM. Le contenu du kit de démarrage n'est pas aussi complexe qu'une démonstration et pas aussi simple qu'un fragment ou un exemple. Il est créé dynamiquement selon les exigences du développeur.

## Ressources mises à disposition automatiquement
{: #auto-provision}

Si un kit de démarrage spécifie les ressources requises, {{site.data.keyword.cloud_notm}} crée automatiquement les instances de ces ressources lorsque vous créez votre application. Vous pouvez également manuellement mettre à disposition des ressources ou sélectionner des instances de ressource existantes afin de les ajouter à votre application une fois cette dernière créée. Une liste des instances de service associées à votre application est visible dans la vue Détails d'application, ainsi que les données d'identification correspondantes dont vous pouvez avoir besoin.

## Code portable
{: #portable-code}

Lorsque vous créez une application à partir d'un kit de démarrage, un code est automatiquement créé pour vous à un format cohérent et ne dépendant pas de l'environnement d'exécution. Vous pouvez déployer le code dans l'environnement de votre choix, par exemple, Kubernetes ou Cloud Foundry, sans apporter de modifications.

Vous pouvez également obtenir une vue rapide de votre code d'application en cliquant sur **Télécharger le code** sur la page Détails de l'application de votre application. Votre code est téléchargé en tant que fichier `.zip` contenant l'ensemble de la structure du code d'application. Vous pouvez facilement extraire le fichier et exécuter le code localement à l'aide du plug-in {{site.data.keyword.dev_cli_notm}} ou l'ajouter à votre référentiel de gestion de code.

### Que est le code créé ?
{: #what-code}

Lorsque vous créez une applications directement ou à l'aide d'un kit de démarrage, l'application contient du code portable. Ce dernier contient du code d'activation de cloud pour plusieurs environnements de cloud. Vous pouvez ensuite générer le code dans quatre zones fondamentales :
* Code qui suit les meilleures pratiques pour un langage spécifique
* Code qui permet à l'application de s'exécuter sur le cloud
* Code initialisé pour la connexion à des services cloud
* Code spécifique à un cas d'utilisation

La génération de ces composants vous fait économiser un temps précieux et garantit l'utilisation d'une architecture hors pair.

* Une logique de cas d'utilisation fournit des fonctions pour la fonction principale d'un cas d'utilisation donné. Par exemple, du code pour un agent conversationnel Watson Conversation ou du code pour une application de reconnaissance vocale mobile.
* Les composants de langage sont des composants de code et des fichiers propres au langage de programmation que vous sélectionnez pour votre kit de démarrage Par exemple, les programmeurs node.js ont besoin d'un fichier package.json pour la gestion des dépendances, et il se trouve que ce fichier est automatiquement créé pour vous.
* L'activation de service est un code qui permet à votre application de se connecter aux services que vous ajoutez et de les utiliser. La gestion des données d'identification, le code d'initialisation et les SDK propres aux services sont des exemples d'éléments d'activation de service.
* L'activation du cloud est un code qui permet à votre application de s'exécuter sur {{site.data.keyword.cloud_notm}}. Par exemple, les graphiques Helm qui permettent à votre application de s'exécuter sur un cluster Kubernetes {{site.data.keyword.cloud_notm}}.

Lorsque vous créez une application à partir d'un kit de démarrage {{site.data.keyword.cloud_notm}}, votre application démarre avec une architecture qui a fait ses preuves et reflète également les meilleures pratiques pour le langage sélectionné.

Chaque application inclut un fichier Readme contenant les détails techniques de l'application et expliquant ce qui est nécessaire pour que votre application soit active si elle n'est pas prête à l'emploi.
{: tip}

## Utilisation de votre propre code et déploiement de ce dernier dans {{site.data.keyword.cloud_notm}}
{: byoc}

Si vous avez une application dans un référentiel existant, vous pouvez utiliser un kit de démarrage vide pour créer un enregistrement d'application dans {{site.data.keyword.cloud_notm}} et connecter l'application à votre référentiel source et à votre chaîne d'outils DevOps.

Vous pouvez commencer à partir du tableau de bord {{site.data.keyword.cloud_notm}} ou d'un kit de démarrage vide. Une fois que vous avez nommé votre application et que vous avez sélectionné un groupe de ressources, sélectionnez le point de démarrage [**Utilisation de votre propre code**](/docs/apps/tutorials?topic=creating-apps-tutorial-byoc#tutorial-byoc), indiquez l'URL du référentiel Git qui contient votre code puis cliquez sur **Créer**.

Vous pouvez connecter votre chaîne d'outils DevOps existante ou en créer une et fournir en continu votre application à l'environnement de votre choix (Kubernetes ou Cloud Foundry, par exemple).


## Chaîne d'outils DevOps
{: #devops}

La chaîne d'outils DevOps comprend des procédures et des outils permettant d'accéder à votre application, de la développer, de la déployer et de l'utiliser. Une chaîne d'outils DevOps est un ensemble de services liés qui automatisent vos tâches DevOps. Il est possible d'exécuter manuellement DevOps avec des applications simples, mais les besoins en automatisation augmentant rapidement à mesure que la complexité s'accroît, l'automatisation de chaîne d'outils devient indispensable pour la distribution continue.

Le composant de base d'une chaîne d'outils DevOps est un référentiel de contrôle de version de code, tel que GitHub. D'autres outils peuvent inclure le suivi des éléments en attente, un pipeline de distribution, un environnement IDE et un service de surveillance ([{{site.data.keyword.cloud_notm}} {{site.data.keyword.DRA_short}}](/docs/services/DevOpsInsights?topic=DevOpsInsights-getting-started#getting-started), par exemple).

Si vous créez une application en utilisant un kit de démarrage, vous pouvez créer une chaîne d'outils et déployer votre application simplement en cliquant sur **Déployer dans le cloud** sur la page **Détails de l'application**. Une chaîne d'outils avec un référentiel de code, un référentiel d'anomalies, un pipeline de distribution et une interface IDE Web est créée.

Vous pouvez ensuite effectuer l'opération de génération sur cette chaîne d'outils afin de satisfaire plusieurs équipes et effectuer le déploiement sur des environnements distincts à des fins de développement, de test et de production. Vous établissez un modèle de distribution continue collaboratif pour votre application.

![Distribution continue](images/garage_continuous_delivery2.png "L'aide au développement configure la distribution continue dans votre branche de développement")


## CLI
{: cli}

Utilisez l'interface de ligne de commande (CLI) pour coder, générer et exécuter votre application localement. La pratique courante consiste à créer votre application à partir d'un portail de développeur dans la console {{site.data.keyword.cloud_notm}}, utiliser les outils de développeur pour effectuer un développement localement puis envoyer les mises à jour au référentiel et fusionner afin de démarrer votre chaîne d'outils de déploiement.

## Développement à l'aide de la méthode Garage
{: #developer_concepts}

Si vous recherchez où mettre en pratique de nouvelles idées et des technologies émergentes, pensez aux déploiements de la [méthode Garage](https://www.ibm.com/cloud/garage/){: new_window} ![Icône de lien externe](../icons/launch-glyph.svg "Icône de lien externe"). Consultez ce site pour comprendre de quelle façon IBM peut vous aider à développer des applications dans votre organisation. 

![Présentation des phases de la méthode Garage](images/garage_phases_overview2.png "Présentation des phases de la méthode Garage") 

{{site.data.keyword.cloud_notm}} vous aide à produire des applications de production de classe d'entreprise performantes en utilisant la méthode Garage ou n'importe quelle méthode de votre choix. Pour mieux comprendre ce qu'{{site.data.keyword.cloud_notm}} offre aux développeurs, examinons rapidement les compétences requises pour générer une application moderne.

## Compétences de développeur
{: #skills}

Les utilisateurs attendent beaucoup plus de leurs applications qu'auparavant. Ils attendent des applications qu'elles leur fournissent des connaissances profondes à partir de données stockées et de données en temps réel, qu'elles soient toujours disponibles et qu'elles répondent plus précisément à leurs besoins. Pour répondre à ces attentes, les fonctions de développeur disponibles dans IBM Cloud s'alignent sur des ensembles de compétences spécifiques et permettent à votre équipe d'utiliser une plateforme pour générer, fournir, exécuter et gérer des applications. Par exemple, une application cognitive sophistiquée peut nécessiter des contributions de la part de développeurs numériques, de développeurs natifs de cloud, de développeurs de flux, de spécialistes des données et de spécialistes DevOps.

 ![Types de développeur](images/developer_skills.png "Relations de développeur")

* Les développeurs numériques créent un canal de vente numérique spécifique, par exemple, des applications Web mobiles, vocales et de discussion en ligne. Les développeurs numériques se concentrent généralement sur des cas d'utilisation et ont pour principal objectif de répondre aux besoins des utilisateurs sous la forme d'une expérience exhaustive.
* Les développeurs natifs de cloud sont spécialisés dans la construction et l'interconnexion de composants de cloud. Les créateurs de microservice et d'architecture BFF (Backend for Frontend) font partie de cette catégorie.
* Les développeurs de flux ont la charge du traitement et de la captation de connaissances à partir de flux de données. Par exemple, un développeur de flux peut analyser et initier une action sur un texte entrant, une parole ou des flux vidéo.
* Les spécialistes des données utilisent des analyses et l'apprentissage automatique pour produire des modèles prédictifs. Ces modèles sont utilisés dans des métriques métier et fournissent des connaissances profondes aux utilisateurs d'application.
* Les spécialistes DevOps sont des experts en résolution de problèmes de déploiement et de chaîne d'outils. Pour les applications simples, il n'est généralement pas nécessaire de faire appel à des spécialistes dédiés car les membres de l'équipe de développement gèrent DevOps avec l'équipe. En revanche, pour les applications d'entreprise complexes, dotées de nombreuses dépendances, des spécialistes DevOps sont essentiels pour garantir le bon fonctionnement de vos applications de production.

Les fonctions de développeur intégrées dans {{site.data.keyword.cloud_notm}} s'alignent sur ces ensembles de compétences et permettent à votre équipe d'utiliser une plateforme pour générer, fournir, exécuter et gérer votre application. Par exemple, un développeur numérique qui crée une application mobile peut utiliser le portail de développeur {{site.data.keyword.cloud_notm}} [Mobile](https://{DomainName}/developer/mobile/dashboard){: new_window} ![Icône de lien externe](../icons/launch-glyph.svg "Icône de lien externe"). Un générateur d'application cognitive peut utiliser le portail de développeur [Watson](https://{DomainName}/developer/watson/dashboard){: new_window} ![Icône de lien externe](../icons/launch-glyph.svg "Icône de lien externe") avec [Watson Studio](https://{DomainName}/catalog/services/watson-studio){: new_window} ![Icône de lien externe](../icons/launch-glyph.svg "Icône de lien externe"). Un développeur de flux peut utiliser [IBM Real-Time Analytics](/docs/services/StreamingAnalytics/index.html). Le service [{{site.data.keyword.cloud_notm}} Continuous Delivery](/docs/services/ContinuousDelivery?topic=ContinuousDelivery-cd_getting_started) simplifie le travail d'un spécialiste DevOps.

[Etes-vous prêt à commencer à générer des applications de qualité prêtes pour la production ? ](/docs/apps/tutorials?topic=creating-apps-tutorial-getting-started#tutorial-getting-started)

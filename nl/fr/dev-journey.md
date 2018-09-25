---

copyright:
  years: 2016, 2017, 2018
lastupdated: "2018-09-12"

---
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}
{:tip: .tip}

# Exploration de la démarche d'un développeur dans {{site.data.keyword.cloud_notm}}
{: #dev-journey}

En tant que développeur, {{site.data.keyword.cloud}} comprend un ensemble de fonctions qui vous permet de commencer à générer des applications en quelques minutes. A partir de nos tableaux de bord de développeur, vous pouvez :

* Sélectionner des kits de démarrage qui sont propres aux cas d'utilisation et produisent des applications de démarrage prêtes pour la production dans une grande variété de langages de programmation et de modèles d'architecture.
* Afficher et gérer les ressources qui ont été automatiquement mises à disposition à partir de votre kit de démarrage ou que vous avez ajoutées manuellement à votre application.
* Obtenir un code d'application portable vous permettant d'effectuer un déploiement vers différents environnements de cloud.
* Créer une [chaîne d'outils DevOps](../services/ContinuousDelivery/index.html#cd_getting_started) en quelques clics.
* Utiliser une [interface de ligne de commande](/docs/cli/idt/index.html) à des fins de développement local.

Pour comprendre comment l'aide au développement {{site.data.keyword.cloud_notm}} peut vous permettre de générer rapidement des applications prêtes pour la production de grande qualité, examinons ces éléments de façon plus détaillée.

## Tableaux de bord de développeur
{: #dev-dashboards}

{{site.data.keyword.cloud_notm}} propose des tableaux de bord de développeur dans différents domaines d'intérêt (par exemple, Watson, la sécurité ou la finance) ou un canal de vente numérique (par exemple, les applications mobiles ou Web). Vous pouvez accéder à ces tableaux de bord à partir de l'**icône Menu** ![icône Menu](../icons/icon_hamburger.svg).

Chaque tableau de bord de développeur fournit des kits de démarrage appropriés pour le domaine thématique qui le concerne et offre un flux de travail cohérent et intuitif qui vous permet de créer en quelques minutes une application prête pour la production.

## Applications
{: #app-projects}

Une application est composée de code, de données, de services et de chaînes d'outils. Par exemple, l'application mobile {{site.data.keyword.cloud_notm}} contient du code d'unité ainsi qu'une logique de back end, le stockage de données, les services d'analyse et de sécurité, et est configuré pour la distribution continue.

![Réutiliser](images/garage_reuse2.png "L'aide au développement vous permet de réutiliser et d'éviter d'avoir à réinventer")

Vous pouvez créer et gérer une application à l'aide de n'importe quel tableau de bord de développeur {{site.data.keyword.cloud_notm}} ou du plug-in {{site.data.keyword.dev_cli_notm}}.

## Kits de démarrage
{: #starter-kits}

A l'aide des kits de démarrage, {{site.data.keyword.cloud_notm}} assemble dans le langage de votre choix une application de production de squelette prête pour le déploiement en cloud. Chaque kit de démarrage comprend un langage, une infrastructure et un modèle pour un scénario d'utilisation spécifique et vous permet de réutiliser le code.

### Qu'est-ce qui distingue les kits de démarrage des exemples ?
Les kits de démarrage sont prêts pour la production et ont pour principal objectif de présenter une implémentation de modèle de clé à l'aide d'un environnement d'exécution (par exemple, Node.js et Express). Dans certains cas, les kits de démarrage offrent une expérience utilisateur simple ayant pour but de mettre en évidence l'intégration du service. Dans d'autres cas, les kits de démarrage représentent une implémentation personnalisable d'un cas d'utilisation sophistiqué.

* Un **fragment** correspond à quelques lignes de code, souvent présentées dans une interface IDE. Les fragments aident un développeur à intégrer une syntaxe de langage de programmation ou une intégration de support à une API définie.
* Une **démonstration** est généralement de très bonne qualité et d'une grande fidélité et utilise une gamme de services et de points d'intégration. Elle requiert souvent un certain temps de réglage et est utilisée pour démontrer un problème ou illustrer un dispositif de plateforme. Elle est utilisée pour évaluer des phases d'adoption du cloud. Parfois, son code est inclus dans le code de production.
* Un **exemple** est un petit exemple d'un dispositif, d'une fonction, d'un service ou d'une démarche utilisateur spécifique. Un exemple peut être réutilisé ou inclus dans une application en production. Il est généralement utilisé pour montrer des capacités techniques et une approche possible de résolution d'un problème technique.
* Un **kit de démarrage** est un modèle prêt pour la production qui peut être intégré à un ensemble de services afin de générer un actif prêt pour la production pouvant être déployé directement dans un pipeline DevOps et un cluster Kubernetes. Un kit de démarrage contient des métadonnées descriptives qui fournissent à l'utilisateur suffisamment d'informations pour lui permettre de déterminer ce qu'il est et ce qu'il fait. Il contient également des instructions indiquant à {{site.data.keyword.cloud_notm}} ce qu'il doit produire. Le résultat est prêt pour la production et peut être itéré pour des améliorations futures à l'aide des meilleures pratiques d'IBM. Le contenu du kit de démarrage n'est pas aussi complexe qu'une démonstration et pas aussi simple qu'un fragment ou un exemple. Il est créé dynamiquement selon les exigences du développeur.

## Ressources mises à disposition automatiquement
{: #auto-provision}

Si un kit de démarrage spécifie les ressources requises, {{site.data.keyword.cloud_notm}} crée automatiquement les instances de ces ressources lorsque vous créez votre application. Notez que vous pouvez également manuellement mettre à disposition des ressources ou sélectionner des instances de ressource existantes afin de les ajouter à votre application une fois celle-ci créée. Une liste des instances de service associées à votre application est visible dans la vue Détails d'application, ainsi que les données d'identification correspondantes dont vous pouvez avoir besoin.

## Code portable
{: #portable-code}

Lorsque vous créez une application à partir d'un kit de démarrage, un code est automatiquement créé pour vous dans un format cohérent et indépendamment de l'environnement d'exécution. Vous pouvez déployer le code dans l'environnement de votre choix, par exemple, Kubernetes ou Cloud Foundry, sans apporter de modifications.

### Que est le code créé ?
Le code créé à partir d'un kit de démarrage {{site.data.keyword.cloud_notm}} comprend quatre composants fondamentaux : la logique de cas d'utilisation, les composants de langage, l'activation de service et l'activation du cloud. La génération de ces composants vous fait économiser un temps précieux et garantit l'utilisation d'une architecture hors pair.

* Une **logique de cas d'utilisation** fournit des fonctions pour la fonction principale d'un cas d'utilisation donné. Par exemple, du code pour un agent conversationnel Watson Conversation ou du code pour une application de reconnaissance vocale mobile.
* Les **composants de langage** sont des composants de code et des fichiers propres au langage de programmation que vous sélectionnez pour votre kit de démarrage Par exemple, les programmeurs node.js auront besoin d'un fichier package.json pour la gestion des dépendances, et il se trouve que ce fichier est automatiquement créé pour vous.
* L'**activation de service** est un code qui permet à votre application de se connecter aux services que vous ajoutez et de les utiliser. La gestion des données d'identification, le code d'initialisation et les SDK propres aux services sont des exemples d'éléments d'activation de service.
* L'**activation du cloud** est un code qui permet à votre application de s'exécuter sur {{site.data.keyword.cloud_notm}}. Par exemple, les graphiques Helm qui permettent à votre application de s'exécuter sur un cluster Kubernetes {{site.data.keyword.cloud_notm}}.

Lorsque vous créez une application à partir d'un kit de démarrage {{site.data.keyword.cloud_notm}}, votre application démarre avec une architecture qui a fait ses preuves et reflète également les meilleures pratiques pour le langage sélectionné.

Chaque application inclut un fichier Readme contenant les détails techniques de l'application et expliquant ce qui est nécessaire pour que votre application soit active si elle n'est pas prête à l'emploi.
{: tip}

## Chaîne d'outils DevOps
{: #devops}

DevOps comprend des procédures et des outils permettant d'accéder à, de développer, de déployer et de faire fonctionner votre application. Une chaîne d'outils DevOps est un ensemble de services liés qui automatisent vos tâches DevOps. Il est possible d'exécuter manuellement DevOps avec des applications très simples, mais les besoins en automatisation augmentent rapidement à mesure que la complexité s'accroît, et l'automatisation de chaîne d'outils est indispensable pour la distribution continue.

Le composant de base d'une chaîne d'outils DevOps est un référentiel de contrôle de version de code, tel que GitHub. D'autres outils peuvent inclure le suivi des éléments en attente, un pipeline de distribution, IDE et un service de surveillance tel que [{{site.data.keyword.cloud_notm}}DevOps Insights](../services/DevOpsInsights/index.html#gettingstarted).

Si vous avez créé une application en utilisant un kit de démarrage, vous pouvez créer une nouvelle chaîne d'outils et déployer votre application simplement en cliquant sur**Déployer dans le cloud** dans la vue Détails d'application. Une chaîne d'outils avec un référentiel de code, un référentiel d'anomalies, un pipeline de distribution et une interface IDE Web est créée.

Vous pouvez ensuite générer sur cette chaîne d'outils afin de satisfaire plusieurs équipes et déployer sur des environnements distincts à des fins de développement, de test et de production, et établir un modèle de distribution continue collaboratif pour votre application.  

![Distribution continue](images/garage_continuous_delivery2.png "L'aide au développement configure la distribution continue dans votre branche de développement")

Vous pouvez également jeter un coup d'oeil rapide à votre code d'application en cliquant sur le bouton **Télécharger** sur la page de présentation de l'application du tableau de bord de développeur. Votre code est téléchargé en tant que fichier `.zip` contenant l'ensemble de la structure du code d'application. Vous pouvez facilement extraire le fichier et exécuter le code localement à l'aide du plug-in {{site.data.keyword.dev_cli_notm}} ou l'ajouter à votre référentiel de gestion de code.

## Interface de ligne de commande
Le plug-in {{site.data.keyword.dev_cli_notm}} vous permet de coder, de générer et d'exécuter votre application localement.  La pratique courante consiste à créer une application via un tableau de bord de développeur, utiliser le plug-in {{site.data.keyword.dev_cli_notm}} pour développer localement, puis envoyer les mises à jour au référentiel et fusionner afin de démarrer votre chaîne d'outils de déploiement.

## Développement à l'aide de la méthode Garage
{: #developer_concepts}

Consultez le site sur la [méthode Garage](https://www.ibm.com/cloud/garage/) pour comprendre de quelle façon IBM peut vous aider à développer des applications dans votre organisation.  

![Présentation des phrases de la méthode Garage](images/garage_phases_overview2.png "Présentation des phrases de la méthode Garage")*Présentation des phases de la méthode Garage*

{{site.data.keyword.cloud_notm}} vous aide à produire des applications de production de classe d'entreprise performantes en utilisant la méthode Garage ou n'importe quelle méthode de votre choix. Pour mieux comprendre ce que {{site.data.keyword.cloud_notm}} offre aux développeurs, examinons rapidement les compétences requises pour générer une application moderne.

## Compétences de développeur
{: #skills}

Aujourd'hui, les utilisateurs attendent beaucoup plus de leurs applications qu'auparavant. Ils attendent des applications qu'elles leur fournissent des connaissances profondes à partir de données stockées et de données en temps réel, qu'elles soient toujours disponibles et qu'elles répondent plus précisément à leurs besoins. Pour répondre à ces attentes, les créateurs d'application doivent réunir de nombreux ensembles de compétences variés. Par exemple, une application cognitive sophistiquée peut nécessiter des contributions de la part de développeurs numériques, de développeurs natifs de cloud, de développeurs de flux, de spécialistes des données et de spécialistes DevOps.

 ![Types de développeur](images/developer_skills.png "Relations de développeur")

* Les **développeurs numériques** créent un canal de vente numérique spécifique, par exemple, des applications Web mobiles, vocales et de dialogue en ligne. Les développeurs numériques se concentrent généralement sur des cas d'utilisation et ont pour principal objectif de répondre aux besoins des utilisateurs sous la forme d'une expérience exhaustive.
* Les **développeurs natifs de cloud** sont spécialisés dans la construction et l'interconnexion de composants de cloud. Les créateurs de microservice et d'architecture BFF (Backend for Frontend) font partie de cette catégorie.
* Les **développeurs de flux** se concentrent sur le traitement et la captation de connaissances à partir de flux de données. Par exemple, un développeur de flux peut analyser et initier une action sur un texte entrant, une parole ou des flux vidéo.
* Les **spécialistes des données** utilisent des analyses et l'apprentissage automatique pour produire des modèles prédictifs. Ces modèles sont utilisés dans des métriques métier et fournissent des connaissances profondes aux utilisateurs d'application.
* Les **spécialistes DevOps** sont des experts en résolution de problèmes de déploiement et de chaîne d'outils. Pour les applications simples, il n'est généralement pas nécessaire de faire appel à des spécialistes dédiés car les membres de l'équipe de développement gèrent DevOps avec l'équipe. En revanche, pour les applications d'entreprise complexes, dotées de nombreuses dépendances, des spécialistes DevOps sont essentiels pour garantir le bon fonctionnement de vos applications de production.

Les capacités de développeur intégrées à {{site.data.keyword.cloud_notm}} s'alignent sur ces ensembles de compétences et permettent à votre équipe d'utiliser une plateforme pour produire, fournir, exécuter et gérer votre application. Par exemple, un développeur numérique qui créer une application mobile peut utiliser le [tableau de bord de développeur mobile](https://console.bluemix.net/developer/mobile/dashboard) {{site.data.keyword.cloud_notm}}, un générateur d'application cognitif peut utiliser le [tableau de bord de développeur Watson](https://console.bluemix.net/developer/watson/dashboard) en même temps que [Watson Studio](https://console.bluemix.net/catalog/services/watson-studio), un développeur de flux peut utiliser [IBM Real-Time Analytics](../services/StreamingAnalytics/index.html#gettingstarted), et le [Service de distribution continues de {{site.data.keyword.cloud_notm}}](../services/ContinuousDelivery/index.html#cd_getting_started) simplifie le travail d'un spécialiste DevOps.

Prêt à commencer ? [Cliquez ici](../apps/index.html) pour générer une application sur {{site.data.keyword.cloud_notm}} dès maintenant !

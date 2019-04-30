---

copyright:
  years: 2018, 2019
lastupdated: "2019-04-18"

keywords: cloud environment, virtual server, virtual machine, vm, understanding infrastructure, IaaS model

subcollection: overview


---
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}
{:tip: .tip}
{:note: .note}

# Exploration du parcours d'administration des opérations informatiques dans {{site.data.keyword.cloud_notm}}
{: #it-ops}

Lorsqu'un grand nombre d'organisations commencent à utiliser un environnement de cloud, soit sur site, soit hébergé dans des centres de données, le rôle de l'administrateur informatique est redéfini. La portée et la complexité de ce changement augmentent de manière significative en fonction du type d'environnement que votre organisation souhaite déployer. 
{: .shortdesc}

Avant de passer au cloud, vous utilisiez un environnement intrinsèquement sécurisé avec des systèmes connectés à votre réseau local privé ou votre réseau intranet. Dans un environnement de cloud, vous devez effectuer les tâches suivantes :
 
  * Vous procurer les composants système 
  * Comprendre les implications réseau et les enjeux de sécurité
  * Utiliser les différentes technologies  
  * Intégrer au nouvel environnement des outils qui ne font pas nativement partie de la pile de cloud. 
  * Continuer à prendre en charge vos clients internes comme si vous aviez toujours un centre de données local.

{{site.data.keyword.cloud}} est là pour vous venir en aide tout au long de votre parcours. Les ressources disponibles incluent une documentation complète, des outils de planification, des experts en matière de support et une communauté d'utilisateurs active. Commençons votre parcours ! 

## Principes de base
{: #basics}

### Modèles du service de cloud
{: #cloud-svc-models}

Il existe trois types de modèles de service de cloud : infrastructure sous forme de services (Infrastructure as a Service), plateforme sous forme de services (PaaS) et logiciel sous forme de services (SaaS). La figure 1 décrit les actions effectuées dans chaque modèle de service. Pour plus d'informations, voir [IaaS, PaaS, and SaaS - IBM Cloud service models](https://www.ibm.com/cloud/learn/iaas-paas-saas){: new_window} ![Icône de lien externe](../icons/launch-glyph.svg "Icône de lien externe").

![Figure 1. Modèles de service de cloud](images/cloud-svc-models.png "Modèles de service de cloud")

Avec le modèle IaaS, votre fournisseur est chargé de gérer l'infrastructure sous-jacente uniquement et éventuellement d'installer des logiciels, tels que les systèmes d'exploitation, les applications et les bases de données. Vous avez un accès limité à l'infrastructure sous-jacente et vous êtes chargé d'installer vos logiciels. Vous pouvez également demander à votre fournisseur de services de les installer. Vous devez également effectuer toutes les autres tâches de maintenance, qui incluent l'installation des modules de mise à jour, des logiciels anti-virus et des correctifs.

Avec le modèle PaaS, votre fournisseur a la charge des systèmes dans le système d'exploitation ainsi que de la gestion de l'infrastructure, qui inclut les correctifs de système d'exploitation, les réparations matérielles et les paramètres réseau. Vous générez et gérez l'application. Vous ou votre fournisseur pouvez installer des logiciels intermédiaires, y compris des bases de données ou d'autres éléments. Ce modèle permet de développer et de tester des logiciels. Pour plus d'informations, voir [A practical guide to platform as a service: What is PaaS ![Icône de lien externe](../icons/launch-glyph.svg "Icône de lien externe")](https://www.ibm.com/blogs/cloud-computing/2016/08/10/practical-guide-paas/){: new_window}.

Avec le modèle SaaS, votre fournisseur gère les systèmes via l'application. L'application est compatible avec le cloud et les utilisateurs peuvent employer différents noeuds finaux, en fonction du fournisseur de logiciel, pour utiliser le logiciel. Le fournisseur de cloud est chargé de gérer l'infrastructure et les applications, ce qui inclut les mises à jour logicielles, les réparations matérielles et les paramètres réseau. Ce modèle est souvent utilisé dans des modèles de licence logicielle dont le paiement s'effectue à la carte. Pour plus d'informations, voir [Applications SaaS pour les entreprises et l'informatique](https://www.ibm.com/cloud/saas){: new_window} ![Icône de lien externe](../icons/launch-glyph.svg "Icône de lien externe").

### Types de cloud
{: #cloud-types}

Trois différents types de cloud sont disponibles : public, privé et hybride. Un cloud public inclut un ensemble partagé de ressources mises à disposition afin d'autoriser l'accès aux ressources d'une entreprise. Il est hébergé dans un environnement à service partagé sur un serveur virtuel et est accessible à partir de n'importe quel emplacement. 

Un cloud privé inclut des ressources mises à disposition pour autoriser l'accès aux ressources d'une entreprise. Il est hébergé sur un matériel dédié (un serveur Bare Metal, par exemple) soit localement dans une entreprise (ou sur les différents sites de l'entreprise), soit par un fournisseur de cloud. Un cloud privé est accessible à partir de n'importe quel emplacement.

Un cloud hybride inclut des ressources associant les aspects des clouds publics et privés. Il est hébergé à la fois dans une entreprise (ou sur les différents sites de l'entreprise) et par un fournisseur de cloud. Un cloud hybride est accessible à partir de n'importe quel emplacement. 

## Planification de votre infrastructure
{: #planning}

Planifiez votre infrastructure avant de la mettre à disposition afin de vérifier que vous l'évaluez correctement pour votre charge de travail. {{site.data.keyword.cloud_notm}} inclut plusieurs outils et sites vous guidant dans le processus de conception et d'évaluation de votre infrastructure. 

### Architecture de l'infrastructure

Tout d'abord, accédez à la page présentant l'[architecture d'infrastructure![Icône de lien externe](../icons/launch-glyph.svg "Icône de lien externe")](https://www.ibm.com/cloud/garage/architectures/infrastructure){: new_window} pour obtenir une présentation plus détaillé des trois types d'environnements de cloud. 

### {{site.data.keyword.cloud_notm}} Design Decision Tool

L'outil [{{site.data.keyword.cloud_notm}} Design Decision Tool ![Icône de lien externe](../icons/launch-glyph.svg "Icône de lien externe")](https://github.com/ibm-cloud-architecture/infrastructure-design-decision-tool/){: new_window} vous permet de comparer les différentes alternatives lors de la conception et de la génération de votre solution personnalisée. Chaque composant d'infrastructure inclut des descriptions, des remarques, des avertissements et des comparaisons. Vous trouverez également un exemple présentant comment utiliser l'outil.

### {{site.data.keyword.cloud_notm}} Stencils

[{{site.data.keyword.cloud_notm}} Stencils ![Icône de lien externe](../icons/launch-glyph.svg "Icône de lien externe")](https://github.com/ibm-cloud-architecture/ibm-cloud-stencils){: new_window} vous permet de créer un diagramme de votre architecture {{site.data.keyword.cloud_notm}} en utilisant des outils de création de diagramme populaires. 

### Options de serveur Bare Metal

Utilisez l'outil [{{site.data.keyword.cloud_notm}} {{site.data.keyword.baremetal_short}} Search Tool ![Icône de lien externe](../icons/launch-glyph.svg "Icône de lien externe")](https://www.ibm.com/cloud-computing/bluemix/bare-metal-search){: new_window} pour évaluer vos options de serveur Bare Metal, incluant les serveurs certifiés pour la prise en charge des charges de travail SAP HANA et SAP NetWeaver.

### Services {{site.data.keyword.cloud_notm}} et conformité

Comme avec toute architecture, vous devez prendre en compte les ressources {{site.data.keyword.cloud_notm}} pouvant être ajoutées à votre solution lorsque vous évaluez votre infrastructure. Pour plus d'informations, voir [Application SaaS pour les entreprises et l'informatique ![Icône de lien externe](../icons/launch-glyph.svg "Icône de lien externe")](https://www.ibm.com/cloud/saas){: new_window} et recherchez un service spécifique. Vous devez également penser à toute réglementation à prendre en compte lors de la génération de votre architecture. Par exemple, votre charge de travail est-elle considérée comme sensible ou est-elle régulée ? Pour plus d'informations, voir [Compliance ![Icône de lien externe](../icons/launch-glyph.svg "Icône de lien externe")](https://www.ibm.com/cloud/compliance){: new_window}.

## Génération de votre infrastructure
{: #build}

Une fois que vous avez planifié et conçu votre infrastructure, vous êtes prêt à la générer. 

### Calcul
{: #compute}

Votre serveur constitue la base de votre infrastructure. Vous disposez de différentes options en fonction de vos besoins. Vous pouvez en associer plusieurs pour répondre aux exigences de votre environnement. Consultez le tableau suivant pour obtenir un récapitulatif de vos options de calcul.

| Option | Description | 
|--------|---------------|
| [{{site.data.keyword.baremetal_short}}](/docs/bare-metal?topic=bare-metal-about-bm#about-bm)  | Serveurs à service exclusif horaires ou mensuels qui vous sont dédiés et qui ne sont pas partagés (notamment les ressources de serveur) avec d'autres clients. |
| [{{site.data.keyword.BluVirtServers_short}}](/docs/vsi?topic=virtual-servers-about-public-virtual-servers#public-virtual-servers) | Serveurs virtuels évolutifs achetés avec des coeurs dédiés et des allocations de mémoire. |
| [{{site.data.keyword.vmwaresolutions_short}}](/docs/services/vmwaresolutions?topic=vmware-solutions-getting-started#getting-started) | Intègre ou migre rapidement et en toute transparence des charges de travail VMware locales en utilisant une infrastructure évolutive, sécurisée et à hautes performances ainsi que la technologie de virtualisation hybride VMware de pointe. |
| [{{site.data.keyword.containerlong_notm}}](/docs/containers?topic=containers-container_index) | Associe les conteneurs Docker, la technologie Kubernetes, une expérience utilisateur intuitive ainsi que l'isolement et la sécurité intégrés permettant d'automatiser le déploiement, le fonctionnement, la mise à l'échelle et la surveillance des applications conteneurisées dans un cluster d'hôtes de calcul. |
| [{{site.data.keyword.cfee_full_notm}}](/docs/cloud-foundry?topic=cloud-foundry-about) | Instancie à la demande plusieurs plateformes Cloud Foundry d'entreprise isolées. |
| [{{site.data.keyword.openwhisk_short}}](/docs/openwhisk?topic=cloud-functions-getting_started#getting_started) | Plateforme de programmation FaaS (Functions-as-a-Service) basée sur Apache OpenWhisk. |
{: caption="Tableau 1. Options de calcul" caption-side="top"}
   
### Stockage
{: #storage}

Les serveurs {{site.data.keyword.baremetal_short}} ainsi que les serveurs {{site.data.keyword.BluVirtServers_short}} sont mis à disposition avec le stockage par défaut. Les serveurs {{site.data.keyword.baremetal_short}} disposent d'au minimum 1 To d'espace disque SATA et les serveurs {{site.data.keyword.BluVirtServers_short}} disposent d'au minimum 25 Go de stockage SAN. Les serveurs {{site.data.keyword.baremetal_short}} {{site.data.keyword.cloud_notm}} certifiés SAP constituent une exception. Pour plus d'informations sur le stockage par défaut disponible avec ces serveurs, voir [{{site.data.keyword.cloud_notm}} SAP-Certified Infrastructure](/docs/bare-metal?topic=bare-metal-sap-cert-infrastructure#sap-cert-infrastructure).

Vous pouvez acheter du stockage supplémentaire en fonction de vos besoins. Consultez le tableau suivant pour obtenir un récapitulatif de vos options de calcul.

| Option | Description |
|--------|---------------|
| [{{site.data.keyword.blockstorageshort}}](/docs/infrastructure/BlockStorage/index.html) | Stockage iSCSI hautes performances persistant mis à disposition et géré indépendamment des instances de calcul. Les numéros d'unité logique Block Storage basés sur iSCSI sont connectés à des périphériques autorisés via des connexions en E-S multi-accès (MPIO) redondantes. |
| [{{site.data.keyword.filestorage_short}}](/docs/infrastructure/FileStorage/index.html) | File Storage basé sur NFS, persistant, rapide et connecté au réseau de façon flexible. Cet environnement NAS vous permet d'avoir un contrôle total des fonctions et des performances de vos partages de fichiers. Les partages File Storage peuvent être connectés à 64 périphériques autorisés via des connexions TCP/IP acheminées pour la résilience. |
| [{{site.data.keyword.cos_full_notm}}](/docs/services/cloud-object-storage?topic=cloud-object-storage-about#about) | Les informations stockées avec IBM Cloud Object Storage sont chiffrées et réparties à plusieurs emplacements géographiques. Elles sont accessibles via HTTP en utilisant une API REST. Ce service utilise les technologies de stockage distribué fournies par IBM Cloud Object Storage System (auparavant Cleversafe). |
| [{{site.data.keyword.cloud_notm}} Master Data Management](/docs/services/MDMOnCloud?topic=MDMOnCloud-mdmoc_getting_started#mdmoc_getting_started) | Décharge de grandes quantités de données de votre centre de données sur site dans votre compartiment Cloud Object Storage. |
| [{{site.data.keyword.backup_full}}](/docs/infrastructure/Backup/index.html) | Système de sauvegarde basé sur un agent automatisé géré via un utilitaire de gestion par navigateur. Vous pouvez sauvegarder les données sur les différents serveurs d'un ou de plusieurs centres de données sur le réseau IBM Cloud. |
{: caption="Tableau 2. Options de stockage" caption-side="top"}

### Réseau
{: #network}

Vous obtenez automatiquement la connectivité à {{site.data.keyword.vpn_full}} lorsque votre compte {{site.data.keyword.cloud_notm}} est configuré. Par défaut, votre serveur a une adresse IP publique et une adresse IP privée. Si vous voulez que votre serveur soit privé, vous pouvez désactiver l'interface publique une fois votre serveur mis à disposition ou commander votre serveur en tant que serveur privé. Pour plus d'informations, voir la rubrique présentant l'[initiation au réseau privé virtuel (VPN)](/docs/infrastructure/iaas-vpn?topic=VPN-gettingstarted-with-virtual-private-networking).

Consultez le tableau suivant pour obtenir un récapitulatif de vos options de réseau.

| Option | Description | 
|--------|---------------|
| [Réseau de distribution de contenu](/docs/infrastructure/CDN?topic=CDN-getting-started) | Elément utilisé pour plusieurs solutions métier (incluant les média, le divertissement, les logiciels, les jeux, la banque et le commerce électronique) afin de répondre aux besoins de vos entreprises. |
| [Service de nom de domaine](/docs/cli/reference/ibmcloud?topic=cloud-cli-ibm-dev-tools-for-jetbrains) | Fournit un emplacement central permettant d'afficher et de gérer vos domaines via l'interface de gestion DNS de base et vous offre la possibilité de gérer gratuitement un serveur de noms de domaine inversé et secondaire au même emplacement. |
| [Adresses IP globales](/docs/infrastructure/subnets?topic=subnets-about-global-ip-address#about-global-ip-address) | Offre flexibilité et vous permet de transférer les charges de travail à des serveurs même dans des centres de données se trouvant à différents emplacements géographiques. |
| [Equilibrage de charge](/docs/infrastructure/loadbalancer-service?topic=loadbalancer-service-getting-started-with-ibm-cloud-load-balancer) | Distribue le traitement et les communications de manière équitable dans plusieurs serveurs d'un centre de données de telle sorte qu'un seul périphérique ne supporte l'intégralité d'une charge. |
| [Virtual Router Appliance](/docs/infrastructure/virtual-router-appliance/getting-started.html) | Achemine de manière sélective le trafic réseau privé et public via un routeur d'entreprise complet équipé d'un pare-feu, d'une fonction de report de l'envoi de paquets, d'un routage basé sur des règles, d'un réseau VPN et d'un hôte disposant d'autres fonctions. |
| [VPN IPSec](/docs/infrastructure/iaas-vpn?topic=VPN-setup-ipsec-vpn#setup-ipsec-vpn) | Suite de protocoles conçus pour l'authentification et le chiffrement de tout le trafic IP entre deux emplacements, en utilisant un mode de tunnel qui fournit un réseau entre sites chiffrés. |
| [{{site.data.keyword.cloud_notm}} Direct Link](/docs/infrastructure/direct-link?topic=direct-link-get-started-with-ibm-cloud-direct-link#get-started-with-ibm-cloud-direct-link) | Optimise un fournisseur Cloud Exchange pour permettre la connectivité aux emplacements de l'infrastructure {{site.data.keyword.cloud_notm}}. |
{: caption="Tableau 3. Options de réseau" caption-side="top"}


## Gestion de votre infrastructure
{: #managing}

Une fois que vous avez généré votre infrastructure et votre environnement, vous êtes prêt à commencer à la gérer.

| Tâche | Description |
|--------|---------------|
| [Surveillance des événements système](/docs/account?topic=account-audit-log) | Affichage des actions effectuées sur les ressources de votre infrastructure. |
| [Définition des préférences de courrier électronique](/docs/account?topic=account-email-prefs) | Configuration des notifications par courrier électronique de l'infrastructure {{site.data.keyword.cloud_notm}} concernant les annonces, la maintenance et les événements non planifiés.  |
| [Sécurisation de vos données](/docs/overview?topic=overview-security) | La plateforme {{site.data.keyword.cloud_notm}} inclut des contrôles de sécurité répartis dans des couches sur le réseau et dans l'infrastructure. |
| [Comment garantir une disponibilité permanente](/docs/overview?topic=overview-zero-downtime) | Toutes les ressources {{site.data.keyword.cloud_notm}} sont hébergées dans différents centres de données dans le monde entier. |
{: caption="Tableau 4. Tâches de gestion" caption-side="top"}

---

copyright:

  years: 2015, 2018

lastupdated: "2018-09-28"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# Nouveautés d'{{site.data.keyword.Bluemix_notm}}
{: #whatsnew}

Restez à jour avec les nouvelles fonctions et les nouveaux services disponibles dans {{site.data.keyword.Bluemix}}, afin d'optimiser l'utilisation de votre expérience {{site.data.keyword.Bluemix_notm}}. Les mises à jour sont classées en fonction des catégories suivantes : [Plateforme {{site.data.keyword.Bluemix_notm}}](index.html#platform_category), [{{site.data.keyword.Bluemix_local_notm}} et {{site.data.keyword.Bluemix_dedicated_notm}}](index.html#dedicatedandlocal), [Calcul](index.html#compute_category), et [Services](index.html#services_category).
{:shortdesc}

## Plateforme {{site.data.keyword.Bluemix_notm}}
{: #platform_category}

### Recherche de ressources
Nouveau à compter du : 17 juillet 2018

Vous pouvez rechercher des ressources à tout emplacement de la console {{site.data.keyword.cloud_notm}}. Entrez le nom d'une ressource dans la zone de recherche de la barre de menu de la console. Appuyez sur la touche Barre oblique (/) pour activer la recherche.

### Ajout de manière dynamique d'utilisateurs fédérés à des groupes d'accès
Nouveau à compter du : 12 juillet 2018

Vous pouvez créer des règles dynamiques pour ajouter dynamiquement des utilisateurs fédérés à des groupes d'accès en fonction d'attributs d'identité spécifiques. Lorsque vos utilisateurs se connectent avec un ID fédéré, les données du fournisseur d'identité mappent dynamiquement vos utilisateurs à un groupe d'accès en fonction des règles définies. Pour plus d'informations, voir [Création de règles dynamiques pour les groupes d’accès](/docs/iam/accessgroup_rules.html#creating-dynamic-rules-for-access-groups).

### Protection des ID de service et des clés d'API
Nouveau à compter du : 1 juin 2018

Pour éviter que la suppression de votre ID de service ou de votre clé d'API ne provoque une indisponibilité ou une interruption, vous pouvez verrouiller les ID de service et les clés d'API en utilisant l'interface utilisateur ou l'interface CLI. Le verrouillage d'un ID de service empêche que les règles d'accès soient changées, modifiées ou affectées et que les clés d'API associées à l'ID de service soient créées ou supprimées. Pour plus d'informations, voir [Verrouillage d'un ID de service](/docs/iam/serviceid.html#locking-a-service-id) et [Verrouillage d'une clé d'API](/docs/iam/userid_keys.html#locking-an-api-key).

### Mise à jour de votre compte Lite vers un compte Abonnement
Nouveau à compter du : 31 mai 2018

Vous pouvez désormais mettre à niveau votre compte Lite vers un compte Abonnement directement à partir de la console {{site.data.keyword.Bluemix_notm}}. Avec un compte Abonnement, vous pouvez utiliser les offres de plateforme et d'infrastructure et tirer le meilleur parti de la remise tarifaire en optant pour un engagement mensuel. Vous pouvez éviter les surprises en choisissant une facturation fixe basée sur un calendrier de paiements mensuels, mais avec la flexibilité de commander plus ou moins selon vos besoins. Pour plus d'informations, voir [FAQ sur les comptes Abonnement](/docs/billing-usage/billing-faq.html#subscription-faqs). 

### {{site.data.keyword.Bluemix_notm}} Modification de l'interface CLI
Nouveau à compter du : 15 mai 2018

Les commandes de l'interface CLI d'{{site.data.keyword.Bluemix_notm}} `bluemix` et `bx` ont été modifiées en **ibmcloud**. Vous pouvez toutefois continuer à utiliser les commandes de l'interface CLI `bluemix` et `bx` jusqu'à ce qu'elles soient retirées. Il n'existe actuellement aucun nom abrégé, uniquement le nom complet **ibmcloud**. 

### Authentification multi-facteur pour votre compte {{site.data.keyword.Bluemix_notm}}
Nouveau à compter du : 2 mai 2018

L'authentification multi-facteur ajoute une couche supplémentaire de sécurité à votre compte en demandant à tous les utilisateurs de fournir un code d'accès à usage unique et durée définie en plus de leur IBMid et mot de passe associé standard lors de la connexion. Ce type d'authentification est également communément appelé authentification à deux facteurs (2FA). L'authentification multi-facteur est activée par compte, et une fois activée, tous les utilisateurs du compte doivent se connecter à l'aide de la mesure de sécurité supplémentaire.

Pour plus d'informations, voir l'article de blogue [IBM Cloud Platform now adds support for Multi-Factor Authentication](https://www.ibm.com/blogs/bluemix/2018/05/ibm-cloud-platform-now-adds-support-multi-factor-authentication/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

### Affectation rapide d'un accès à l'aide de groupes d'accès
Nouveau à compter du : 3 avril 2018

Vous souhaitez pouvoir affecter rapidement un accès en utilisant le moins de règles possible ? Désormais, vous pouvez. Les groupes d'accès vous permettent de regrouper un ensemble d'utilisateurs et d'ID de service et d'affecter une seule règle qui s'applique à tous les membres de ce groupe. L'utilisation de groupes d'accès vous permet de limiter le temps nécessaire à la gestion des accès aux utilisateurs et aux ID de service de votre compte. Pour plus d'informations, consultez l'article de blogue [New feature: Access groups](https://www.ibm.com/blogs/bluemix/2018/04/access-groups/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

### Liaison des comptes SoftLayer et {{site.data.keyword.Bluemix_notm}}
Nouveau à compter du : 01 mars 2018

Vous pouvez lier votre compte SoftLayer à votre compte {{site.data.keyword.Bluemix_notm}} pour vous connecter à un seul emplacement, la console {{site.data.keyword.Bluemix_notm}}, et accéder aux ressources IaaS (infrastructure sous forme de services) et PaaS (plateforme sous forme de services). Si vous ne connaissez pas l'environnement {{site.data.keyword.Bluemix_notm}}, créez et liez un compte afin d'obtenir gratuitement un compte Lite {{site.data.keyword.Bluemix_notm}}. Ou, si vous avez déjà un compte {{site.data.keyword.Bluemix_notm}} avec des ressources PaaS, liez vos comptes afin de recevoir une seule facture pour vos ressources IaaS et PaaS. Consultez le site [Steps to Link your IaaS and PaaS Accounts](https://www.ibm.com/blogs/bluemix/2018/03/follow-steps-link-iaas-paas-accounts/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe") pour savoir comment lier rapidement vos comptes.


### {{site.data.keyword.Bluemix_notm}} Foundry Service région Est des Etats-Unis désormais disponible
Nouveau à compter du :  15 décembre 2017

Un nouveau centre de données pour la région Est des Etats-Unis est désormais disponible à Washington, DC. Cette nouvelle région est accessible via le noeud final `us-east.bluemix.net`. Pour plus de détails sur les services disponibles à l'achat dans cette nouvelle région, voir [Services par région](/docs/resources/services_region.html#services_region).

### Support pour des ressources dans l'Union européenne
Nouveau à compter du :  14 décembre 2017

Si vos services et centres de données se trouvent en Europe, {{site.data.keyword.Bluemix_notm}} propose désormais des fonctions supplémentaires destinées à protéger vos données dans l'Union européenne. vous pouvez demander que le support soit fourni par des équipes de cas client situées en Europe. Ce support est disponible 24 heures sur 24, 7 jours sur 7. Voir [Activation de l'option Support dans l'Union européenne](/docs/billing-usage/eusupported.html#bill_eusupported) et [Demande de support pour des ressources dans l'Union européenne](/docs/get-support/howtogetsupport.html#eusupported) pour plus d'informations.

### Retrait de la prise en charge de TLS 1.0 et 1.1
Nouveau à compter du : 28 novembre 2017

Au 1er mars 2018 {{site.data.keyword.Bluemix_notm}} retire la prise en charge de TLS 1.0 et TLS 1.1 sur un grand nombre de nos produits et services cloud dans le cadre de notre engagement à offrir un cloud totalement sécurisé et conforme aux dernières recommandations de sécurité et de confidentialité. Pour en savoir plus sur la façon dont ce changement vous affecte et les actions qu'il peut être nécessaire de prendre, voir [Retrait de la prise en charge de TLS 1.0 et 1.1](/docs/troubleshoot/appsectls.html).

### Une nouvelle façon d'organiser les ressources au sein de votre compte
Nouveau à compter du : 16 novembre 2017

Les groupes de ressources constituent une nouvelle façon de créer des regroupements personnalisables de ressources de compte, et l'accès au groupe et aux ressources qu'il contient est géré via Identity and Access Management (IAM). Chacun débute par un groupe de ressources par défaut. Vous pouvez renommer ce groupe de ressources et y ajouter de nouvelles instances de service lorsque les créez depuis le catalogue.

Pour les utilisateurs disposant d'un compte Paiement à la carte ou Abonnement, vous pouvez créer des groupes de ressources supplémentaires de manière à faciliter la gestion de quota et l'affichage de la facturation pour un ensemble de ressources. Vous pouvez également regrouper des ressources afin de faciliter l'affectation d'accès utilisateur à plusieurs services à la fois. Pour plus d'informations sur l'utilisation des groupes de ressources pour votre compte, voir [Gestion des groupes de ressources](/docs/account/resourcegroups.html#rgs).

### Mises à jour pour {{site.data.keyword.Bluemix_notm}} IAM
Nouveau à compter du : 16 novembre 2017

L'introduction de [groupes de ressources](/docs/overview/resource-groups.html#whatis) dans votre compte {{site.data.keyword.Bluemix_notm}} a ouvert la voie à une nouvelle façon d'affecter des accès. Des ID utilisateur et de service peuvent être affectés pour un accès à l'ensemble des services d'un groupe de ressources, permettant ainsi de donner rapidement accès à plusieurs ressource à la fois. Vous pouvez également personnaliser l'accès pour chaque ID utilisateur ou service en affectant l'accès uniquement à certains services d'un groupe de ressources, ou simplement en choisissant d'affecter l'accès à des ressources individuelles au niveau de l'instance de service.

Pour plus d'informations sur les fonctions dont vous pouvez bénéficier en utilisant IAM, voir [Quelles fonctions sont fournies par IAM ?](/docs/iam/index.html#features)

### Personnalisez votre vue du tableau de bord
Nouveau à compter du : 16 novembre 2017

Vous pouvez afficher et gérer toutes les ressources de votre compte depuis votre tableau de bord sur la console {{site.data.keyword.Bluemix_notm}}. Et désormais, vous pouvez définir des filtres afin de personnaliser votre vue. Vous pouvez, par exemple, filtrer par groupe de ressources pour afficher les ressources spécifiques d'un groupe. Vous pouvez également filtrer par région ou par espace Cloud Foundry. Pour plus de détails, voir [Gestion des ressources sur le tableau de bord](/docs/overview/ui.html#dashboardview).


### Centre de support
Nouveau à compter du : 2 novembre 2017

Le nouveau centre de support permet désormais de rechercher des informations, poster des questions à notre communauté de développeurs et gérer les tickets. Accédez à **Support > Centre de support** depuis la barre de menus de la console {{site.data.keyword.Bluemix_notm}}.

### Présentation d'IBM Cloud
Nouveau à compter du : 31 octobre 2017

Bluemix devient IBM Cloud. En dehors du lancement du nouveau nom, votre application reste la même. Vous pouvez toujours facilement générer et exécuter vos applications et services comme auparavant. Consultez le [IBM Cloud Blog](https://www.ibm.com/blogs/bluemix/2017/10/bluemix-is-now-ibm-cloud/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe") pour plus de détails.

### Compte Lite
Nouveau à compter du : 31 octobre 2017

Le compte Lite est notre nouveau type de compte, qui offre un accès à une sélection de services en essai gratuit sans limite de temps. Ce nouveau compte inclut également l'utilisation de fonctions de suivi et d'efficience pour vous aider à mieux gérer vos ressources. Pour connaître les disponibilités, voir [Types de compte](/docs/account/index.html#liteaccount).

### Fonctions d'authentification de l'application Identity and Access Management
Nouveau à compter du : 6 octobre 2017

Identity and Access Management (IAM) permet désormais de créer un ID service, que vous pouvez considérer comme une identité utilisable pour des applications à authentifier avec vos services {{site.data.keyword.Bluemix_notm}}. Plutôt que d'utiliser des données d'identification d'un utilisateur individuel, vous pouvez créer un ID service avec une clé d'API associée et des droits d'accès sous la forme d'une règle de service affectée à l'ID service pour vous permettre de contrôler le niveau d'accès d'une application s'authentifiant avec cet ID.

Pour plus d'informations sur les avantages que présente cette fonction et sur sa mise en route, voir [Présentation des ID service IBM Cloud IAM et des clés d'API](https://www.ibm.com/blogs/bluemix/2017/10/introducing-ibm-cloud-iam-service-ids-api-keys/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

### Catalogue global {{site.data.keyword.Bluemix_notm}}
Nouveau à compter du : 27 juillet 2017

S'étendant sur la dernière mise à jour de la console pour gérer vos régions publiques depuis un emplacement unique de la console, {{site.data.keyword.Bluemix_notm}} possède désormais un catalogue global qui permet de rationaliser davantage le processus de sélection et de déploiement d'éléments sélectionnés depuis le catalogue. Quelle que soit la région sélectionnée sur la console, vous pouvez désormais voir depuis votre catalogue tous les services disponibles pour l'ensemble des régions publiques. Lorsque vous sélectionnez une vignette dans le catalogue, vous pouvez voir dans quelles régions le service est disponible et sélectionner l'emplacement où vous souhaitez le déployer.

Pour plus d'informations sur les dernières mises à jour du catalogue, voir [Un catalogue {{site.data.keyword.Bluemix_notm}} global pour simplifier les choses](https://www.ibm.com/blogs/bluemix/2017/07/global-bluemix-catalog-makes-building-things-easier/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

### Mises à jour de la console {{site.data.keyword.Bluemix_notm}}
Nouveau à compter du : 23 mai 2017

Vous pouvez désormais gérer vos régions publiques depuis un emplacement unique via la console {{site.data.keyword.Bluemix_notm}} mise à jour. Le sélecteur de région offre un accès rationalisé aux ressources, et parmi les autres améliorations figurent une disponibilité plus grande et des performances améliorées.

Pour plus d'informations sur cette mise à jour, consultez [New Global Bluemix UI for Higher Availability and More](https://www.ibm.com/blogs/bluemix/2017/05/new-global-bluemix-ui-higher-availability/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

### Identity and Access Management
Nouveau à compter du : 01 mai 2017

Avec les toutes dernières mises à jour et améliorations, les propriétaires de compte ou les administrateurs {{site.data.keyword.Bluemix_notm}} peuvent désormais utiliser une nouvelle interface utilisateur de compte unifié pour tirer partie des fonctions suivantes :
 * Gérer l'accès à granularité fine aux services Kubernetes et autres des utilisateurs lorsqu'ils adoptent les nouvelles fonctions de contrôle d'accès
 * Affecter des règles de service et des rôles Cloud Foundry aux utilisateurs au sein de leurs organisations

En outre, les utilisateurs de la plateforme {{site.data.keyword.Bluemix_notm}} peuvent créer, supprimer et répertorier les clés d'API associées à leurs ID utilisateur. Ils peuvent également utiliser ces clés pour s'authentifier lorsqu'ils utilisent des API ou des interfaces de ligne de commande.

Enfin, nous avons amélioré notre fonction de gestion unifiée des utilisateurs afin de garantir que, pour un compte IaaS-PaaS lié, les utilisateurs sont gérés de façon unifiée sans devoir les ajouter séparément sur le portail client SoftLayer ou la console {{site.data.keyword.Bluemix_notm}}.

Pour plus d'informations cette récente mise à jour, consultez l'article de blogue [Introducing Identity & Access Management](https://www.ibm.com/blogs/bluemix/2017/05/introducing-identity-access-management/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

### Modifications de conception de la navigation pour les documents {{site.data.keyword.Bluemix_notm}}
Nouveau à compter du : 13 avril 2017

Cette mise à jour de la navigation vous permettra de mieux appréhender la façon dont le contenu est organisé dans l'ensemble des documents, vous permettant de trouver plus efficacement le contenu pertinent. Avec un moindre nombre de couches de contenu imbriquées, il n'est plus nécessaire de creuser pour trouver la documentation dont vous avez besoin pour un usage optimal de {{site.data.keyword.Bluemix_notm}}.


## {{site.data.keyword.Bluemix_local_notm}} et {{site.data.keyword.Bluemix_dedicated_notm}}
{: #dedicatedandlocal}

### Mises à jour de février pour la console d'administration
{: #febadminconsole}
Nouveau à compter du : 28 février 2018

Avec la dernière mise à jour de février 2018, vous pouvez utiliser les nouvelles fonctions suivantes :

#### Nouveau droit relatif à la gestion des mises à jour de maintenance

Un nouveau droit utilisateur a été ajouté afin d'autoriser certains utilisateurs à approuver et replanifier des mises à jour de maintenance et à définir des fenêtres de mise à jour de maintenance spécifiant à quel moment des mises à jour de maintenance peuvent être déployées dans un environnement dédié.
Pour plus d'informations, voir la [vidéo de démonstration](https://youtu.be/7c7jyp_JJWU){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

### Mises à jour de décembre pour la console d'administration
{: #decemberadminconsole}
Nouveau à compter du :  14 décembre 2017

Avec les toutes dernières mises à jour et améliorations de décembre, vous pourrez utiliser les nouvelles fonctions suivantes :

#### Abonnement aux notifications de seuil d'utilisation d'UC moyenne

L'UC moyenne a été ajoutée en tant que type de seuil aux abonnements aux notifications. Vous pouvez désormais recevoir des notifications lorsque l'utilisation d'UC (moyennée sur l'ensemble des cellules Diego et de DEA) se situe au-delà ou sous un seuil donné.

#### Contrôle d'accès aux systèmes cloud de l'Union européenne

Combinée à la nouvelle fonction de prise en charge de ressources cloud dans l'Union européenne (en commençant par Francfort), la console d'administration permet désormais de définir des règles de contrôle d'accès par le personnel IBM. Vous pouvez gérer les règles de contrôle d'accès, afficher les demandes d'accès,  effectuer des actions sur les demandes et procéder au suivi de l'historique.

#### Informations améliorées dans les rapports de sécurité

Désormais, les rapports de sécurité incluent des noms conviviaux en plus des ID uniques pour les utilisateurs et les organisations.

### Mises à jour d'août pour la console d'administration
{: #augustadminconsole}
Nouveau à compter du : 31 août 2017

Avec les toutes dernières mises à jour et améliorations d'août, vous pourrez utiliser les nouvelles fonctions suivantes :

#### Mises à jour des statistiques d'utilisation de service {{site.data.keyword.cloudant_short_notm}}

  * Le calcul des statistiques d'utilisation pour {{site.data.keyword.cloudant_short_notm}} a été mis à jour afin de refléter la quantité totale des Go utilisés et disponibles sur l'ensemble des noeuds d'un cluster {{site.data.keyword.cloudant_short_notm}}. En règle générale, un cluster {{site.data.keyword.cloudant_short_notm}} comporte 3 noeuds, et un document de la base de données est répliqué sur l'ensemble des noeuds du cluster à des fins de haute disponibilité et de reprise après incident. Avec les mises à jour d'août, les statistiques de capacité de l'appel {{site.data.keyword.cloudant_short_notm}} (disponible dans la vue _Utilisation des ressources > Services_) indique l'espace sur tous les noeuds du cluster. Si, par exemple, un cluster {{site.data.keyword.cloudant_short_notm}} unique comporte 3 noeuds, chacun d'une capacité de 1 000 Go, la limite de capacité sera de 3 000 Go. Si 1 500 Go de cette capacité sont déjà utilisés, les statistiques d'utilisation de {{site.data.keyword.cloudant_short_notm}} seront de 50 %.

#### Mises à jour apportées à la planification des mises à jour de maintenance

  * Dans {{site.data.keyword.Bluemix_dedicated_notm}}, les clients peuvent gérer les dates et heures de disponibilité de leurs environnements dédiés pour le déploiement des mises à jour système. Ils peuvent définir des fenêtres de disponibilité représentant les dates et heures où les mises à jour de maintenance peuvent ou non être déployées sur leur environnement dédié. Avec la mise à jour d'août, les _fenêtres de disponibilité pour les mises à jour_ ont été renommées en _Fenêtres de mise à jour_, et les _fenêtres d'indisponibilité pour les mises à jour_ en _Fenêtres d'indisponibilité_. Au-delà de ces changements de terminologique, les clients disposent désormais de davantage de flexibilité et de marge pour définir des dates d'interruption totale (indisponibilité). Une fois qu'elles sont demandées, les dates d'indisponibilité doivent être approuvées par IBM et le délai d'approbation est variable. Une fois les dates acceptées, IBM annule toutes les mises à jour actuellement prévues dans le cadre de la fenêtre d'indisponibilité. IBM crée également de nouveaux enregistrements pour ces mises à jour et planifie ces dernières en dehors des dates d'indisponibilité approuvées.

Pour plus d'informations, voir la [vidéo de démonstration](https://bit.ly/2eCQNvu){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

### Mises à jour de juillet pour la console d'administration
{: #julyadminconsole}
Nouveau à compter du : 31 juillet 2017

Avec les toutes dernières mises à jour et améliorations de juillet, vous pourrez utiliser les nouvelles fonctions suivantes :

#### Mises à jour des fonctions de l'historique d'utilisation des ressources

  * Dans la précédente mise à jour (juin), la vue Historique pour l'utilisation de la mémoire et du disque avait introduit l'affichage des données d'utilisation sur les 48 dernières heures, 30 derniers jours et 5 derniers mois. Dans la mise à jour de juillet, la fonctionnalité d'historique d'utilisation des ressources a été étendue afin de permettre la personnalisation de l'intervalle de temps pour lequel afficher les données d'utilisation des ressources. Les vues horaire, quotidienne et mensuelle sont conservées, mais les utilisateurs peuvent désormais spécifier une date/heure de début et une durée pour laquelle afficher les statistiques d'utilisation de la mémoire et du disque (par exemple, afficher l'utilisation de la mémoire pour les 15 jours à compter du 1er juillet 2017).
  * Une nouvelle commande CLI a été introduite pour l'affichage de l'historique des statistiques de ressource dans l'interface de ligne de commande. Les paramètres de la commande, ainsi que des exemples de syntaxe, sont accessibles en tapant la commande suivante : `_cf ba resource-metrics-history -help_`

Pour plus d'informations, voir la [vidéo de démonstration](https://youtu.be/QBij0jB5qAk){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

### Mises à jour de juin pour la console d'administration
{: #juneadminconsole}
Nouveau à compter du : 26 juin 2017

Avec les toutes dernières mises à jour et améliorations de juin, vous pourrez utiliser les nouvelles fonctions suivantes :

#### Mises à jour apportées à la page Utilisation des ressources

  * Ressources système
    * La vue Historique de la mémoire et du disque a été mise à jour afin d'afficher les données sur 48 heures, 30 jours et 5 mois.
    * Un lien En savoir plus est fourni, montrant comment l'API Metrics de la console d'administration est utilisée pour gérer les vues d'historique.
  * Applications
    * Fournit les informations sur l'utilisation de toutes les applications dans l'environnement.
    * Tri par nom d'application, mémoire physique, mémoire réservée, disque physique, disque réservé, UC physique ou nom d'organisation.
    * La recherche est fourni pour filtrer les résultats par nom d'application et nom d'organisation.
    * Un lien En savoir plus est fourni, montrant comment l'API Metrics de la console d'administration est utilisée pour gérer la vue Applications.

Voir [Utilisation des ressources](/docs/hybrid/index.html#resourceusage) pour plus d'informations.

#### Mises à jour de l'API Metrics

  * Des statistiques d'environnement ont été ajoutées, fournissant des moyennes par jour ou par mois pour la consommation de mémoire et de disque.

Voir [API Metrics](/docs/hybrid/index.html#envappmetricsapi) pour plus d'informations.


### Mises à jour de mai pour la console d'administration
{: #mayadminconsole}
Nouveau à compter du : 30 mai 2017

Avec les toutes dernières mises à jour et améliorations de mai, vous pourrez utiliser les nouvelles fonctions suivantes :

 * Améliorations sur la page Statut incluant un niveau de granularité supérieur pour les diagnostics sur les incidents qui affectent la plateforme et les contextes d'exécution {{site.data.keyword.Bluemix_notm}}.
 * Amélioration apportées à la page Rapports et journaux pour la sécurité :
   * Les rapports s'affichent désormais dans un format de tableau, ce qui simplifie la navigation et la recherche de rapports, avec notamment la possibilité de trier par catégorie de rapport, nom de fichier ou date de création.
   * Filtrage amélioré incluant le filtrage simultané de plusieurs catégories.
   * Mode plein écran pour afficher le contenu d'un rapport.
   * Possibilité de supprimer des rapports pour les administrateur dotés du droit "écriture de rapport".
   * Affichage plus rapide des listes de rapports, chargement progressif à la demande via le défilement en continu, ce qui offre une meilleure performance globale.
 * Des rapports de sécurité peuvent être fournis à la demande pour une plage de temps s'étendant à une semaine et commençant au maximum 3 mois avant le moment de la demande. Notez qu'une certaine configuration spécifique à l'environnement est demandée pour que cette fonction soit disponibles pour les administrateurs. Ces derniers doivent également posséder le droits "écriture de rapport".

### Mises à jour d'avril pour la console d'administration
{: #apriladminconsole}
Nouveau à compter du : 2 mai 2017

Avec les toutes dernières mises à jour et améliorations d'avril, vous pourrez utiliser les nouvelles fonctions suivantes :

 * Nouvelle conception de l'application de statut pour les environnements {{site.data.keyword.Bluemix_notm}} dédié et local. Vous pouvez rapidement rechercher par nom de composant ou date d'envoi. Vous pouvez également basculer entre les envois de statut de composant et les notifications spécifiques à votre environnement. Pour plus d'informations, voir l'article de blogue sur la [nouvelle page de statut {{site.data.keyword.Bluemix_notm}}](https://www.ibm.com/blogs/bluemix/2017/05/new-bluemix-status-page/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").
 * Données d'utilisation de service pour les services sélectionnés depuis la vignette Utilisation des ressources. Voir [Détails sur l'utilisation du service](/docs/hybrid/index.html#servicesresourceusage) pour plus d'informations sur les services pris en charge et ce que vous offre la nouvelle vue.

## Calcul
{: #compute_category}

### Création de clusters comportant plusieurs zones dans {{site.data.keyword.containerlong_notm}}
Nouveau à compter du : 10 juillet 2018

Vous souhaitez améliorer la disponibilité des clusters et des applications ? Vous pouvez désormais étendre votre cluster dans plusieurs zones de certaines régions métropolitaines. Pour plus d'informations, voir [Création de clusters à zones multiples dans {{site.data.keyword.containershort_notm}}](cs_clusters.html#multizone).

### L'accès au tableau de bord Kubernetes est désormais disponible dans {{site.data.keyword.containerlong_notm}}

{{site.data.keyword.containerlong_notm}} prend désormais en charge l'accès direct au tableau de bord Kubernetes via la console {{site.data.keyword.Bluemix_notm}}. Ce chemin d'accès simplifié au tableau de bord améliore l'expérience utilisateur pour la gestion de cluster et la visualisation des ressources. Pour plus d'informations, voir le [blogue {{site.data.keyword.Bluemix_notm}} ](https://www.ibm.com/blogs/bluemix/2018/04/kubernetes-dashboard-access/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

### Dernières mises à jour pour les packs de construction

Visitez les pages suivantes pour avoir la liste cumulée des mises à jour les plus récentes :

* [Dernières mises à jour apportées au pack de construction sdk-for-nodejs](/docs/runtimes/nodejs/updates.html#latest_updates)
* [Dernières mises à jour apportées au pack de construction Liberty](/docs/runtimes/liberty/updates.html#latest_updates)
* [Dernières mises à jour apportées au pack de construction ASP.NET Core](/docs/runtimes/dotnet/updates.html#latest_updates)
* [Dernières mises à jour apportées au pack de construction IBM XPages for {{site.data.keyword.Bluemix_notm}}](/docs/starters/xpages/index.html#updates)

### Dernières mises à jour pour {{site.data.keyword.containerlong_notm}}

{{site.data.keyword.containerlong_notm}} a lancé son architecture Kubernetes en mai 2017. L'architecture précédente pour les groupes de conteneurs uniques et évolutifs est désormais [obsolète à compter du 5 décembre 2017](https://www.ibm.com/blogs/bluemix/2017/07/deprecation-single-scalable-group-container-service-bluemix-public/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").  

[Pour obtenir des informations sur l'initiation à l'environnement Kubernetes natif sur {{site.data.keyword.Bluemix_notm}}](/docs/containers/container_index.html), voir la documentation. Si vous avez des questions, vous pouvez les poster sur le site Slack à l'adresse https://ibm-container-service.slack.com/.

### Nouveau pack de construction Liberty for Java version 3.11
Nouveau à compter du : 17 juillet 2017

Le pack de construction Liberty version 3.11 fournit chaque mois une nouvelle version du contexte d'exécution Liberty et comporte d'autres améliorations. La version mensuelle du contexte d'exécution Liberty a été mise à jour vers l'édition [2017.7.0.0](https://developer.ibm.com/wasdev/blog/2017/07/07/beta-websphere-liberty-tools-july-2017/). Le kit Java Development Kit IBM a été mis à jour vers les versions 8.0.4.7 et 7.1.4.5. Le pack de construction fournit également des versions mises à jour de l'utilitaire App Management et de l'agent Auto-Scaling. La bibliothèque Cloudant par défaut est désormais la bibliothèque officielle [java-cloudant](https://github.com/cloudant/java-cloudant), la [bibliothèque Ektorp](https://github.com/helun/Ektorp) est toujours disponible en option. Pour obtenir des détails sur cette modification, voir l'[article du blogue](https://www.ibm.com/blogs/bluemix/2017/05/default-library-change-cloudant-auto-wiring-liberty-buildpack/). Le rapport de taille de segment de mémoire par défaut est désormais de 50 % lorsque votre application comporte moins de 512 Mo de mémoire, mais reste de 75 % si elle comporte plus de 512 Mo. Un nouveau journal des tâches de préproduction est à présent généré, qui permet un débogage simplifié des erreurs de préproduction. Pour plus d'informations, voir la documentation concernant les [dernières mises à jour](https://console.ng.bluemix.net/docs/runtimes/liberty/updates.html).

### Nouveau pack de construction Liberty for Java version 3.10
Nouveau à compter du : 12 juin 2017

Le pack de construction Liberty versions 3.10 fournit chaque mois et chaque trimestre de nouvelles versions du contexte d'exécution Liberty et comporte d'autres améliorations. La version par défaut du contexte d'exécution Liberty a été mise à jour vers la version 17.0.0.2. La version mensuelle du contexte d'exécution Liberty a été mise à jour vers l'édition [2017.5.0.0](https://developer.ibm.com/wasdev/blog/2017/05/12/beta-websphere-liberty-tools-may-2017/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe"). Le pack de construction fournit également des versions mises à jour de l'utilitaire App Management et du client Extreme Scale. Pour plus d'informations, voir la documentation relative aux [dernières mises à jour](/docs/runtimes/liberty/updates.html).

### Nouveau kit de développement de logiciels pour le pack de construction Node.js version 3.12
Nouveau à compter du : 16 mai 2017

Le pack de construction SDK for Node.js v3.12 fournit les versions 0.12.17, 0.12.18, 4.8.0, 4.8.2, 6.10.0 et 6.10.2 d'IBM SDK Node.js. La valeur par défaut est passée de la dernière version 4.x à la dernière version 6.x, et est actuellement la version 6.10.2. S'agissant d'un changement de version principale, cela peut affecter les applications qui dépendent de la valeur par défaut. Voir [Node.js version long-term support and the SDK for Node.js buildpack](https://www.ibm.com/blogs/bluemix/2016/11/node-version-support-and-sdk-buildpack/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe") pour plus d'informations sur les moyens d'éviter les problèmes.

En plus de nouveaux environnements d'exécution, cette édition contient une correction d'erreur concernant l'utilitaire App Management Health Center et les versions  6.9.5 et 6.10.0 de Node.js.

### Nouveau pack de construction Liberty for Java version 3.9
Nouveau à compter du : 27 avril 2017

Le pack de construction Liberty version 3.9 fournit chaque mois une nouvelle version du contexte d'exécution Liberty et comporte d'autres améliorations. La version par défaut du contexte d'exécution Liberty a été mise à jour afin d'inclure les iFixes PI77770, PI77605, IFPI77438 et IFPI79275. La version mensuelle du contexte d'exécution Liberty a été mise à jour vers l'édition [2017.3.0.0](https://developer.ibm.com/wasdev/blog/2017/03/14/beta-websphere-liberty-tools-march-2017/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe"). Le calcul de la mémoire est passé de la préproduction au processus de démarrage, facilitant ainsi les changements de segment de mémoire avec le redémarrage d'une application. Le pack de construction fournit également des versions mises à jour de l'agent de service Auto-Scaling et du client Extreme Scale. Pour plus d'informations, voir la documentation relative aux [dernières mises à jour](/docs/runtimes/liberty/updates.html).

## Services
{: #services_category}

### Dernières mises à jour pour {{site.data.keyword.cloudant_short_notm}}
Nouveau à compter du : 28 septembre 2018

Visitez la page suivante pour afficher la liste complète des [dernières mises à jour ](/docs/services/Cloudant/release_info/release_notes.html#release-notes){:new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe") sur {{site.data.keyword.cloudant_short_notm}}.

### Présentation d'{{site.data.keyword.IBM_notm}} {{site.data.keyword.DRA_short}} (disponibilité générale)
Nouveau à compter du : 20 septembre 2018

Le service {{site.data.keyword.DRA_short}} est désormais disponible dans les régions Sud des Etats-Unis, Allemagne et Royaume-Uni.

{{site.data.keyword.DRA_short}} permet aux différentes équipes d'améliorer leur productivité, leur efficacité et d'accélérer la commercialisation. De plus, elles peuvent utiliser les données des outils DevOps pour évaluer facilement la réussite ou améliorer la qualité du code. Ce service constitue l'outil idéal permettant aux entreprises de comprendre leurs activités DevOpsdans dans leurs bases de code et leurs équipes.

* **Vitesse** : {{site.data.keyword.DRA_short}} affiche toutes les données d'analyse de vos applications dans un seul tableau de bord.
* **Qualité** : réduisez le nombre de versions à risque en implémentant des règles de déploiement de blocage. Par exemple, si vous avez une règle pour la couverture du code impliquant une tolérance sélectionnée, {{site.data.keyword.DRA_short}} bloque toujours les versions de code ne respectant pas les tolérances définies. Ces règles vous permettent d'améliorer la qualité du processus de déploiement. 
* **Contrôle** : mesurez les résultats au fur et à mesure que les équipes réagissent aux différentes tendances dans leurs pratiques DevOps en utilisant la couverture du code, des tests d'unité et d'autres outils. Ces tendances permettent aux équipes de mieux réglementer leurs pratiques DevOps.

### {{site.data.keyword.security-advisor_long_notm}} est à présent disponible en version bêta !
Nouveau à compter du : 5 septembre 2018

De nouvelles fonctions ont été ajoutées à {{site.data.keyword.security-advisor_short}} qui est désormais disponible en tant que service bêta.  {{site.data.keyword.security-advisor_short}} centralise votre sécurité dans un tableau de bord {{site.data.keyword.Bluemix_notm}}. Outre la centralisation des informations, le service rassemble les informations de sécurité essentielles réparties sur des vignettes simples d'utilisation afin de signaler aisément les problèmes de sécurité. Le fait de cliquer sur une vignette active l'exploration en aval afin d'examiner les problèmes classés par priorité, l'historique et les détails liés à l'alerte. Pour résoudre le problème, effectuez une nouvelle exploration en aval pour obtenir tous les détails ainsi que des correctifs suggérés pour supprimer la menace et garantir la sécurité de votre environnement.

{{site.data.keyword.security-advisor_short}} devient rapidement votre console de référence vous permettant de centraliser, consulter et gérer les informations de sécurité dans votre environnement {{site.data.keyword.Bluemix_notm}}.

Dans cette version, nous implémentons les éléments suivants :
* Une API Findings
* La possibilité d'utiliser votre propre fournisseur
* Des mises à jour pour l'utilisation du tableau de bord

Et bien plus encore !

Pour commencer, consultez la documentation [{{site.data.keyword.security-advisor_short}}](/docs/services/security-advisor/index.html).

### Présentation d'{{site.data.keyword.iva_full_notm}} (disponibilité générale)
Nouveau à compter du : 26 juin 2018

[{{site.data.keyword.iva_full}}](https://console.bluemix.net/catalog/services/voice-agent-with-watson)![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe") est désormais disponible. Vous pouvez
créer un agent vocal cognitif construit sur les services Watson que les clients peuvent appeler par téléphone. Avec l'intelligence artificielle Watson au niveau du réseau principal, votre agent vocal est capable de communiquer sur un mode conversationnel, gérant des interactions complexes et résolvant les appels client au sein de l'agent.

Cette version offre les nouvelles fonctions suivantes :

* Ajout d'emplacements de service Watson redondants pour la reprise après incident. 
* Modification des options de configuration avancées afin de personnaliser la façon dont vos agents vocaux transfèrent les appels, lisent les messages préenregistrés lors des appels et interagissent avec les services Watson.
* Configuration du nombre maximal de connexions simultanées dans votre plan de service standard.
* Connexion de vos agents vocaux aux fournisseurs de commutation automatique de canaux SIP, tels NetFoundry, Twilio, AT&T et d'autres fournisseurs de services ou homologues de {{site.data.keyword.iva_short}}.

Pour commencer, consultez la documentation [{{site.data.keyword.iva_short}}](/docs/services/voice-agent/getting-started.html).

### {{site.data.keyword.streaminganalyticsshort}} offre de nouveaux plans de service avec une infrastructure reposant sur un conteneur
Nouveau à compter du : 20 avril 2018

{{site.data.keyword.streaminganalyticsshort}} s'exécute désormais sur une infrastructure Kubernetes reposant sur un conteneur qui fournit des bénéfices en termes de sécurité et de disponibilité au service.
 
Vous pouvez accéder à cette nouvelle infrastructure reposant sur un conteneur à l'aide des [plans de service v2](/docs/services/StreamingAnalytics/service_plans.html#service_plans). Vous pouvez choisir le plan {{site.data.keyword.streaminganalyticsshort}} qui correspond le mieux à vos activités. Les plans de service v2 offrent les améliorations suivantes :
 
* [IBM Streams QSE with Docker](https://www-01.ibm.com/marketing/iwm/iwm/web/preLogin.do?source=swg-ibmistvi)![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe") : consultez le document [ Development Guide](https://developer.ibm.com/streamsdev/docs/cloud-beta-devguide/)![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe") pour apprendre à utiliser la nouvelle fonction Streams QSE avec RHEL 7 qui s'exécute dans un environnement Docker afin de compiler et déployer vos applications avec les nouveaux plans {{site.data.keyword.streaminganalyticsshort}} v2. 
* [API REST {{site.data.keyword.streaminganalyticsshort}} v2](https://console.bluemix.net/apidocs/1939-streaming-analytics-v2#introduction)![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")
* [Nouvelles applications de démarrage et nouveaux exemples d'application](https://developer.ibm.com/streamsdev/docs/cloud-beta-samples/) ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")
* [Améliorations relatives à la haute disponibilité dans le service {{site.data.keyword.streaminganalyticsshort}}](/docs/services/StreamingAnalytics/c_ha.html#consistent-regions)
* [Fonctions d'identification de problème dans le service {{site.data.keyword.streaminganalyticsshort}} ](https://developer.ibm.com/streamsdev/2018/02/15/streaming-analytics-console-gives-ways-find-fix-errors-beta-plans/)![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")
* [Surveillance du comportement des opérateurs et traitement de n-uplet garanti dans le cloud](https://developer.ibm.com/streamsdev/2018/02/15/monitor-operators-behave-ensure-resource-optimization/)![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")

### {{site.data.keyword.iva_full_notm}} est à présent disponible en version bêta !
Nouveau à compter du : 16 mars 2018

Avec [{{site.data.keyword.iva_full}}](https://console.bluemix.net/catalog/services/voice-agent-with-watson)![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe"), vous pouvez créer un agent vocal cognitif basé sur des services Watson que les clients peuvent appeler par téléphone. Avec l'intelligence artificielle Watson au niveau du réseau principal, votre agent vocal est capable de communiquer sur un mode conversationnel, gérant des interactions complexes et résolvant les appels client au sein de l'agent.

Cette version bêta offre les fonctions principales suivantes :

* Commencer plus facilement que jamais en créant un agent vocal et tous les services Watson requis en une seule étape.
* Transférer des appels à partir de votre agent vocal vers, par exemple, un agent du centre d'appel ou une toute autre destination.
* Collecter et analyser des données d'appel en configurant votre agent vocal pour qu'il transfère des événements d'enregistrement de détail d'appel, de transcription, ainsi que des événements de transformation {{site.data.keyword.conversationshort}} vers une base de données {{site.data.keyword.cloudant_short_notm}}.
* Surveiller l'utilisation du service et visualiser les journaux d'appels sur la nouvelle page _Utilisation_. Vous pouvez visualiser des statistiques rapides pour le mois en cours, rechercher et filtrer des journaux d'appels et afficher des messages système pour chaque appel individuel.
* Etablir des appels sécurisés avec chiffrement de support en utilisant SIP TLS (URI SIPS) sur le port 5061 et le protocole SRTP (Secure Real-time Transport Protocol).
* Se connecter aux instances de service {{site.data.keyword.speechtotextfull}} et {{site.data.keyword.texttospeechfull}} dans d'autres espaces {{site.data.keyword.cloud_notm}} pour plus de flexibilité.

Pour commencer, consultez la documentation [{{site.data.keyword.iva_short}}](/docs/services/voice-agent/getting-started.html).

### Mises à jour apportées à {{site.data.keyword.visualrecognitionshort}}
Nouveau à compter du : 14 mars 2018

Le service {{site.data.keyword.visualrecognitionfull}} a été mis à jour et de nouveaux entraînements de modèle de classifieur personnalisé sont à présent générés sous forme de discriminants basés sur un réseau de neurones d'apprentissage en profondeur. En raison du calcul supplémentaire requis pour générer ces modèles d'apprentissage en profondeur, les nouveaux modèles auront peut-être besoin de plus de temps pour s'entraîner.

Actuellement, les discriminants personnalisés existants peuvent continuer à être mis à jour et entraînés à nouveau et ils ne seront pas mis à jour vers ce nouveau format de modèle de machine d'apprentissage en profondeur.

### Mises à jour de {{site.data.keyword.streaminganalyticsshort}}
Nouveau à compter du : 14 février 2018

Les améliorations suivantes ont été apportées aux [plans bêta - entrée et bêta - améliorés](/docs/services/StreamingAnalytics/beta_plans.html#beta_plans) pour la console dans le [service {{site.data.keyword.streaminganalyticsshort}} ](https://console.bluemix.net/catalog/services/streaming-analytics){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe") :

* [Nouvelle fonction IBM Streams QSE pour Docker](https://www-01.ibm.com/marketing/iwm/iwm/web/preLogin.do?source=swg-ibmistvi){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe") : consultez le document [Beta Development Guide](https://developer.ibm.com/streamsdev/docs/cloud-beta-devguide/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe") pour apprendre à utiliser la nouvelle fonction Streams QSE avec RHEL 7 en cours d'exécution dans un environnement Docker afin de compiler et déployer vos applications avec les nouveaux plans bêta {{site.data.keyword.streaminganalyticsshort}}.
* [API REST {{site.data.keyword.streaminganalyticsshort}} v2](https://console.bluemix.net/apidocs/1939-streaming-analytics-v2#introduction){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")
* [Nouvelles applications de démarrage et nouveaux exemples d'application](https://developer.ibm.com/streamsdev/docs/cloud-beta-samples/)
* [Améliorations relatives à la haute disponibilité dans le service {{site.data.keyword.streaminganalyticsshort}}](/docs/services/StreamingAnalytics/consistentregions.html#consistentregions)
* [Nouvelles fonctions d'identification de problème dans la version bêta du service {{site.data.keyword.streaminganalyticsshort}} ](https://developer.ibm.com/streamsdev/2018/02/15/streaming-analytics-console-gives-ways-find-fix-errors-beta-plans/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")
* [Surveillance du comportement des opérateurs et traitement de n-uplet garanti dans le cloud](https://developer.ibm.com/streamsdev/2018/02/15/monitor-operators-behave-ensure-resource-optimization/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")

### Extension d'{{site.data.keyword.keymanagementservicelong_notm}} à la région Sydney
Nouveau à compter du : 31 janvier 2018

A compter d'aujourd'hui, le service de gestion de clés de chiffrement {{site.data.keyword.keymanagementserviceshort}} est disponible dans la région Sydney. Sydney est la troisième région après la région Sud des Etats-Unis (Dallas) et la région Londres à offrir un statut de disponibilité générale pour les utilisateurs {{site.data.keyword.keymanagementserviceshort}}.

{{site.data.keyword.keymanagementserviceshort}} est un service de gestion de clés de chiffrement offrant une solution de gestion simple et économique pour les clés utilisées dans le but de chiffrer les données stockées dans {{site.data.keyword.Bluemix_notm}}. {{site.data.keyword.keymanagementserviceshort}} gère l'ensemble du cycle de vie des clés, de leur création à leur utilisation par une application, leur archivage et leur destruction, tout en imposant la répartition des tâches entre la gestion de données et la gestion de clés.

{{site.data.keyword.keymanagementserviceshort}} prend en charge BYOK (Bring-Your-Own-Key – chiffrement géré par les clients) avec des services de données IBM applicables. BYOK permet aux utilisateurs d'importer des clés de chiffrement de type chaîne de confiance principales créées en interne pour améliorer la gestion de la sécurité de leurs données au repos sauvegardées dans {{site.data.keyword.Bluemix_notm}}.


### {{site.data.keyword.containershort_notm}} : Support Kubernetes 1.8.x
Nouveau à compter du : 19 janvier 2018

Depuis novembre 2017, {{site.data.keyword.containershort_notm}} prenait en charge Kubernetes `1.8.x`. Nous sommes fiers d'annoncer que notre version par défaut de Kubernetes est désormais la version `1.8.6`.  Dans un futur proche, nous fournirons le support pour la version `1.9.x`.

### Watson Discovery Visual Insights
Nouveau à compter du : 30 novembre 2017

Explorez visuellement les connexions optimisées par la maîtrise des éléments sémantiques de {{site.data.keyword.discoveryshort}} dans le texte, comme les entités, les relations, les concepts, etc.

Commencez à explorer les nouvelles du monde grâce à la collection prête à l'emploi {{site.data.keyword.discoveryshort}} News. Ou bien, explorez vos propres collections de documents dans {{site.data.keyword.discoveryshort}}. Il vous suffit de vous connecter avec vos données d'identification {{site.data.keyword.Bluemix_notm}}. Voir [Visual insights experimental](https://visual-insights.bluemix.net){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe") pour plus d'informations.

### Nouveau service IBM Cloud Managed Database Server Beta
Nouveau à compter du : 30 novembre 2017

Avec le nouveau service IBM Cloud Managed Database Server Beta, vous pouvez créer une instance de Microsoft SQL Server sur {{site.data.keyword.Bluemix_notm}}. Vous pouvez utiliser cette instance SQL Server comme tout autre système de gestion de base de données mais sans l'effort et les dépenses de configuration de matériel ou d'installation et de maintenance de logiciel.

Ce service offre les fonctions suivantes :
* Choix entre les versions de Microsoft SQL Server 2012, 2014, et 2016, Enterprise et Standard Editions
* Différentes configurations ou tailles prédéfinies afin de répondre à vos exigences de charge de travail applicative
* Gestion complète par IBM, y compris la surveillance, l'application de correctifs, la sauvegarde et la génération de rapports

Pour commencer, voir [Initiation à IBM Cloud Managed Database Server](/docs/services/managed-sql-server/getting-started.html).

### Nouveautés dans {{site.data.keyword.mobilepushshort}}
Nouveau à compter du : 26 octobre 2017

Nous avons apporté plusieurs améliorations au service {{site.data.keyword.mobilepushshort}} au cours des derniers mois. Le service est désormais disponible dans la région de Francfort en plus de Dallas, Londres et Sydney. Détail des améliorations :

#### Surveillance
Vous pouvez désormais suivre les performances des notifications push pour des périodes spécifiques, suivre le nombre de notifications envoyées et le nombre total de périphériques enregistrés. Vous pouvez également enregistrer des points d'ancrage Web afin d'être informé de tous les événements du cycle de vie d'une notification. Pour plus de détails, consultez les liens de documentation et articles de blogue :
* [Surveillance des notifications](/docs/services/mobilepush/push_monitoring.html#push_monitoring)
* [Réception d'alertes sur événements webhook](/docs/services/mobilepush/push_webhook.html#webhook_event_based_notifications)
* [Surveillance dans IBM Push Notifications](https://www.ibm.com/blogs/bluemix/2017/03/monitoring-ibm-push-notifications/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")

#### Notifications Web
Le navigateur Web Safari est désormais pris en charge pour les notifications Web, ainsi que Firefox, Chrome, Chrome App et Extensions. Les logiciels SDK Web et informations associées sont accessibles sur [IBM Bluemix Push Notifications Web SDK](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-javascript-webpush/blob/Doc/README.md){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

#### Dernières notifications Android et iOS
Prise en charge des devises pour les notifications iOS 11. Nous avons également intégré plusieurs nouvelles améliorations liées aux notification depuis iOS10 et Android N.

* iOS10 – Prise en charge de Rich Media Notifications, des images, des boutons et des cartes dans les notifications interactives, ainsi que des chaînes localisées
* Android N – Notifications extensibles, notifications interactives et en mode silencieux, paramètres de voyant LED

Des détails supplémentaires sont accessibles dans la documentation sur les [notifications de média riche](/docs/services/mobilepush/push_step_4_nf_rich.html#interactive-notifications), sur les [notifications interactives et en mode silencieux](/docs/services/mobilepush/push_step_4_nf_interactive.html#interactive-notifications) et sur l'[l'activation des notifications push avancées](/docs/services/mobilepush/push_step_4_nf_adv.html#enabling-advanced-push-notifications).

#### Prise en charge APNs HTTP/2
Apple a introduit la prise en charge du protocole HTTP pour les notifications Apple. Le service {{site.data.keyword.mobilepushshort}} prend désormais en charge le protocole HTTP/2. Avec cette prise en charge, le contenu des notifications peut être de 4 ko avec un débit accru et fournit une fonction de commentaire instantané. La prise en charge du certificat universel permet à l'application de se connecter aux environnements de bac à sable et de production.

#### Nouveau plan Lite
Le service Lite Plan for {{site.data.keyword.mobilepushshort}} permet d'envoyer chaque mois gratuitement des notifications de 100 ko. Pour plus d'informations, voir l'article de blogue [Lite Plan For Push Notifications Service on Bluemix](https://www.ibm.com/blogs/bluemix/2017/06/lite-plan-push-notifications-service-bluemix/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")f.



### Nouveautés de Mobile Analytics
Nouveau à compter du : 26 octobre 2017

Nous avons apporté des améliorations au service {{site.data.keyword.mobileanalytics_short}} au cours des derniers mois. Le service est désormais disponible dans les régions de Francfort et Sydney en plus de Dallas et Londres. Détail des améliorations :

#### Prise en charge du logiciel SDK Web
{{site.data.keyword.mobileanalytics_short}} est désormais un service Omni canal avec l'ajout de la prise en charge des analyses d'application Web. Pour plus de détails, accédez à [https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-web-analytics/](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-web-analytics/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

#### Intégration au service {{site.data.keyword.mobilefoundation_short}}
Le service {{site.data.keyword.mobilefoundation_short}} optimise désormais le service {{site.data.keyword.mobileanalytics_short}} pour l'analyse des applications, des utilisateurs et des performances. Les utilisateurs peuvent optimiser l'option d'exportation vers l'entrepôt DB2 pour générer des analyses d'adaptateur et des graphiques personnalisés. Vous trouverez des détails supplémentaires dans les articles de blog suivants :

* [Mobile Foundation Service integration with Mobile Analytics Service](https://www.ibm.com/blogs/bluemix/2017/08/mobile-foundation-service-integration-mobile-analytics-service-2/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")
* [Building custom charts using IBM Bluemix Mobile Analytics service and IBM Mobile Foundation Service](https://mobilefirstplatform.ibmcloud.com/blog/2017/04/26/custom-charts-using-analytics-and-dashdb-analytics-service/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")
* [Building charts for Adapter analytics using IBM Bluemix Mobile Analytics service and IBM Mobile Foundation Service](https://mobilefirstplatform.ibmcloud.com/blog/2017/04/26/adapter-analytics-using-analytics-and-dashdb-analytics-service/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")

#### Le conteneur boilerplate {{site.data.keyword.mobilefirst_notm}} inclut désormais {{site.data.keyword.mobileanalytics_short}}
Mobile Services Boilerplate est un modèle qui fournit un ensemble de services mobiles pour une mise en route rapide des utilisateurs. Le service {{site.data.keyword.mobileanalytics_short}} fait désormais partie du conteneur boilerplate disponible dans le [catalogue](https://console.bluemix.net/catalog/starters/mobilefirst-services-starter){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").


### Mises à jour de {{site.data.keyword.streaminganalyticsshort}}
Nouveau à compter du : 20 octobre 2017

* IBM Streams Runner for Apache Beam : Vous pouvez désormais développer des applications Beam en local dans votre environnement de développement Streams puis les envoyer au service {{site.data.keyword.streaminganalyticsshort}} dans {{site.data.keyword.Bluemix_notm}}. IBM Streams Runner for Apache Beam exécute des pipelines Beam dans un environnement Streams. Une application Beam lancée avec Streams Runner est convertie en un fichier SAB (Streams Application Bundle) que vous pouvez déployer dans {{site.data.keyword.streaminganalyticsshort}}. Consultez [IBM Streams Runner for Apache Beam dans Streaming Analytics](/docs/services/StreamingAnalytics/gs_beamrunner.html) pour plus de détails.
* Vous pouvez trouver des informations dans les fichiers journaux encore plus rapidement. La console a été mise à jour pour améliorer l'affichage des graphiques d'application pour des topologies Python ou Java. Voir les [améliorations apportées à la console](https://developer.ibm.com/streamsdev/2017/10/13/enhancements-to-the-console/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

### IBM App Launch for {{site.data.keyword.Bluemix_notm}} Services
Nouveau à compter du : 12 octobre 2017

L'IBM App Launch for {{site.data.keyword.Bluemix_notm}} Services est une offre expérimentale qui vous permet de mesurer les expériences client en fournissant une plateforme pour créer des engagements ciblés sur différents échantillons représentatifs de votre audience. Le service App Launch fournit des analyses des préférences et points noirs des clients en tant que résultat de ces engagements, et vous aide à personnaliser l'application pour une meilleure expérience client.

Les propriétaires d'application peuvent désormais accélérer la distribution des innovations vers les applications mobiles en évitant les complexités du cycle de mise en production. Les service App Launch permet aux propriétaires d'application de lancer rapidement des fonctions dans des applications mobiles et d'en mesure l'impact en contrôlant l'audience ciblée. Le propriétaire d'application peut travailler avec le développeur d'applications afin de définir des indicateurs clé de performance pour les fonctions, mesurer l'impact et prendre des décisions de transfert ou d'annulation de fonction selon les commentaires en temps réel. Le service offre également la possibilité de tester plusieurs variantes des fonctions d'application, des composants de l'interface utilisateur,et des messages, et de prendre des décisions en fonction des commentaires.

Pour plus d'informations, voir le [Tutoriel d'initiation](/docs/services/app-launch/index.html#gettingstartedtemplate).

### Mises à jour apportées à {{site.data.keyword.ibmwatson_notm}} {{site.data.keyword.relationshipextractionshort}}
Nouveau à compter du : 4 octobre 2017

Une nouvelle fonction de personnalisation et de nouveaux modèles de langue sont disponibles pour utilisation avec {{site.data.keyword.relationshipextractionshort}}. Nouvelles langues : néerlandais, coréen et chinois simplifié, prise en charge pour WKS.

### Mise à jour du cluster {{site.data.keyword.containerlong_notm}}
Nouveau à compter du : 20 septembre 2017

Vous pouvez désormais mettre à jour vos clusters vers la version la plus récente disponible de Kubernetes dans {{site.data.keyword.Bluemix_notm}}. A l'aide de l'interface graphique ou de l'interface CLI, mettez à jour votre document maître Kubernetes et vos noeuds worker vers Kubernetes 1.7 et bénéficiez des nouvelles fonctions et correctifs.

Pour plus d'informations, voir [Kubernetes 1.7 available in {{site.data.keyword.containerlong_notm}}](https://www.ibm.com/blogs/bluemix/2017/09/kubernetes-1-7-available-ibm-bluemix-container-service/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

### Nouveau service expérimental IBM Voice Agent with Watson
Nouveau à compter du : 15 septembre 2017

Avec le nouveau service expérimental {{site.data.keyword.iva_full}}, vous pouvez créer un agent vocal cognitif basé sur des services Watson que les clients peuvent appeler par téléphone. Avec l'intelligence artificielle Watson au niveau du réseau principal, votre agent vocal est capable de communiquer sur un mode conversationnel, gérant des interactions complexes et résolvant les appels client au sein de l'agent.

{{site.data.keyword.iva_short}} se connecte de façon transparente et orchestre les services Watson {{site.data.keyword.speechtotextshort}}, {{site.data.keyword.conversationshort}} et {{site.data.keyword.texttospeechshort}} afin de simuler une conversation en langage naturel. Chaque agent vocal se met automatiquement à l'échelle afin de gérer plusieurs appels simultanés. Dans cette édition expérimentale, vous pouvez personnaliser votre agent vocal en utilisant les fonctions clé suivantes :

* Importez l'exemple de boîte de dialogue {{site.data.keyword.conversationshort}} pour commencer, puis créez votre propre boîte de dialogue pour répondre aux besoins de votre société.
* Programmez le comportement de l'agent vocal depuis le service {{site.data.keyword.conversationshort}} en utilisant nos API. Vous contrôlez tous les éléments depuis le comportement d'interruption jusqu'à la fin de l'appel pour tout noeud de votre boîte de dialogue.
* Créez et gérez facilement plusieurs agents vocaux si vous souhaitez connecter différents numéros de téléphone aux agents cognitifs spécialisés pour différents sujets.
* Etendez les fonctions du service en connectant un moteur d'orchestration de services (SOE) afin de pouvoir utiliser des API tierces. Par exemple, le moteur SOE peut écouter les déclencheurs provenant du service {{site.data.keyword.conversationshort}} puis utiliser les API fournies afin de consulter les informations des systèmes existants ou fournir d'autres analyses.

Pour débuter, voir la documentation [Initiation à {{site.data.keyword.iva_short}}](/docs/services/voice-agent/getting-started.html).


### Mise à jour du service {{site.data.keyword.streaminganalyticsshort}} : La console inclut de nouvelles fonctions pour cerner les problèmes dans vos applications
Nouveau à compter du : 14 août 2017

Pour les applications Python et Java, l'emplacement des fichiers source est affiché en fonction de vos annotations @spl_note.

Pour des détails, voir [Latest improvements to the {{site.data.keyword.streaminganalyticsshort}}](https://developer.ibm.com/streamsdev/2017/08/14/latest-improvements-streaming-analytics-console/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

### IBM Cloud Monitoring est désormais disponible dans la région du Royaume-Uni
Nouveau à compter du : 01 août 2017

Utilisez le service {{site.data.keyword.monitoringlong}} pour étendre vos fonctions de collecte, conservation et analyse dans {{site.data.keyword.Bluemix_notm}} lors de l'utilisation de mesures.

* Alerte pour engager une action {{site.data.keyword.monitoringlong}} offre une API que vous pouvez utiliser pour définir des seuils de performance et être avisé lorsque ces seuils sont enfreints. Vous pouvez définir des règles d'alerte pour une instance de service ou d'application spécifique, ainsi que et des règles d'alerte concernant un ensemble d'instances. Lorsqu'une alerte est déclenchée, une notification peut vous être envoyée via un courriel, un événement PagerDuty, une notification Webhook, ou une combinaison des trois.

* Ajout de métriques personnalisées. Le plan de service {{site.data.keyword.monitoringlong}} Premium propose des API que vous pouvez utiliser pour ajouter des métriques d'application et métier pertinentes à vos données Cloud Monitoring. Vous pouvez également les utiliser pour envoyer des données de métriques hors de {{site.data.keyword.IBM_notm}} Cloud vers le service {{site.data.keyword.monitoringlong}}.

* Construction de tableaux de bord réutilisables et interactifs. Grafana hébergé sur {{site.data.keyword.monitoringlong}} prend en charge l'élaboration de tableaux de bord personnalisés offrant un large éventail d'options de visualisation.  Vous pouvez rendre vos modèles de tableaux de bord dynamiques en utilisant des requêtes de métriques faisant appel à des variables.

* Accès à votre service via le catalogue {{site.data.keyword.Bluemix_notm}}. {{site.data.keyword.monitoringlong}} est disponible par le biais d'une vignette de service dans la section DevOps du catalogue {{site.data.keyword.Bluemix_notm}}.  Dans le cas de service {{site.data.keyword.containershort}} avec conteneur unique ou groupes de conteneurs, vous pouvez y accéder depuis l'interface utilisateur de {{site.data.keyword.Bluemix_notm}}.

* Sélection d'un plan de service adapté à vos besoins. Selon vos besoins, vous avez le choix entre le plan de service Lite et le plan de service Premium. Le plan de service Lite permet la collecte de métriques une fois par minute, leur conservation pendant 15 jours, et une alerte complémentaire.  Sinon, vous pouvez opter pour le plan Premium qui autorise une consommation plus élevée, une conservation plus longue des métriques, et l'accès aux API du service (par exemple, pour envoyer ou extraire des métriques du service {{site.data.keyword.monitoringlong}}). {{site.data.keyword.monitoringlong}} permet la collecte de métriques une fois par minute.  Le plan Lite conserve les métriques complètes pendant 15 jours. Le plan Premium les conserve pendant 45 jours.

Le service {{site.data.keyword.monitoringshort}} existant collectait les mesures à des fréquences définies par le service commençant à 30 secondes, et produisait un récapitulatif sur des fréquences de 1 heure au fil du temps. {{site.data.keyword.monitoringlong}} offre désormais une collecte pleine résolution à 1 minute.  Le plan Lite conserve les mesures pendant 15 jours.  Le plan Premium conserve les mesures pendant 45 jours.

Pour plus d'informations sur le service {{site.data.keyword.monitoringlong}}, voir [la documentation d'initiation à la surveillance](/docs/services/cloud-monitoring/index.html#getting-started-with-ibm-cloud-monitoring) ou [the IBM Cloud Monitoring – Service Refresh with New Features![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")](https://www.ibm.com/blogs/bluemix/2017/07/ibm-cloud-monitoring-service-refresh-new-features/).


### IBM Cloud Log Analysis est désormais disponible dans la région du Sud des Etats-Unis
Nouveau à compter du : 31 juillet 2017

{{site.data.keyword.loganalysisfull}} fournit des services de collecte de journaux et de recherche dans ceux-ci pour la plateforme {{site.data.keyword.Bluemix_notm}}, en collectant automatiquement des données d'application et de services {{site.data.keyword.Bluemix_notm}} depuis divers services {{site.data.keyword.Bluemix_notm}}. Utilisez le service {{site.data.keyword.loganalysisshort}} pour :

* Conserver les journaux aussi longtemps que nécessaire.  

    Les journaux sont stockés dans le stockage IBM Cloud.  Vous pouvez les téléchargez quand vous en avez besoin.

* Gérer la conservation de vos journaux et envoyez des données de journal en étant hors {{site.data.keyword.IBM_notm}} Cloud via la nouvelle API.

* Sélectionner le volume de journaux sur lequel vous pourrez effectuer des recherches chaque jour.  

    Différents plans sont disponibles et peuvent vous permettre d'effectuer des recherches sur 500 Mo, 2 Go, 5 Go, et 10 Go de journaux par jour.

* Construire des tableaux de bord réutilisables et interactifs.

    Le plug-in Kibana hébergé de {{site.data.keyword.loganalysisshort}} fournit une prise en charge pour la génération de tableaux de bord personnalisés.

* Accédez à votre service via le catalogue {{site.data.keyword.Bluemix_notm}}.  

    Pour le service {{site.data.keyword.loganalysisshort}} avec des conteneurs uniques et de groupe, ainsi que les services {{site.data.keyword.IBM_notm}} Cloud Foundry, vous pouvez accéder au service depuis l'interface utilisateur de {{site.data.keyword.Bluemix_notm}}.

Pour plus d'informations sur le service {{site.data.keyword.loganalysisshort}}, reportez-vous à l'[initiation à {{site.data.keyword.loganalysisfull}}](/docs/services/CloudLogAnalysis/index.html#getting-started-with-ibm-cloud-log-analysis) et la [présentation de {{site.data.keyword.loganalysisshort}}](/docs/services/CloudLogAnalysis/log_analysis_ov.html#log_analysis_ov).

### IBM dashDB for Analytics a été renommé
Nouveau à compter du : 18 juillet 2017

Le tableau suivant indique le nouveau nom :

| Nom précédent               | Nouveau nom                   | Date d'effet |
|-----------------------------|----------------------------|----------------|
| IBM dashDB for Analytics    | IBM Db2 Warehouse on Cloud | 18 juil. 2017  |
{: caption="Tableau 1. Changement de nom de service" caption-side="top"}

Pour obtenir la liste cumulative des mises à jour pour Db2 Warehouse on Cloud et Db2 on Cloud, voir : [What's New in Db2 Warehouse on Cloud and Db2 on Cloud](http://www.ibm.com/support/docview.wss?uid=swg21961758){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

### IBM Cloud Monitoring est désormais disponible dans la région du Sud des Etats-Unis
Nouveau à compter du : 17 juillet 2017

Utilisez le service {{site.data.keyword.monitoringlong}} pour étendre vos fonctions de collecte, conservation et analyse dans {{site.data.keyword.Bluemix_notm}} lors de l'utilisation de mesures.

* Alerte pour engager une action {{site.data.keyword.monitoringlong}} offre une API que vous pouvez utiliser pour définir des seuils de performance et être avisé lorsque ces seuils sont enfreints. Vous pouvez définir des règles d'alerte pour une instance de service ou d'application spécifique, ainsi que et des règles d'alerte concernant un ensemble d'instances. Lorsqu'une alerte est déclenchée, une notification peut vous être envoyée via un courriel, un événement PagerDuty, une notification Webhook, ou une combinaison des trois.

* Ajout de métriques personnalisées. Le plan de service {{site.data.keyword.monitoringlong}} Premium propose des API que vous pouvez utiliser pour ajouter des métriques d'application et métier pertinentes à vos données Cloud Monitoring. Vous pouvez également les utiliser pour envoyer des données de métriques hors de {{site.data.keyword.IBM_notm}} Cloud vers le service {{site.data.keyword.monitoringlong}}.

* Construction de tableaux de bord réutilisables et interactifs. Grafana hébergé sur {{site.data.keyword.monitoringlong}} prend en charge l'élaboration de tableaux de bord personnalisés offrant un large éventail d'options de visualisation.  Vous pouvez rendre vos modèles de tableaux de bord dynamiques en utilisant des requêtes de métriques faisant appel à des variables.

* Accès à votre service via le catalogue {{site.data.keyword.Bluemix_notm}}. {{site.data.keyword.monitoringlong}} est disponible par le biais d'une vignette de service dans la section DevOps du catalogue {{site.data.keyword.Bluemix_notm}}.  Dans le cas de service {{site.data.keyword.containershort}} avec conteneur unique ou groupes de conteneurs, vous pouvez y accéder depuis l'interface utilisateur de {{site.data.keyword.Bluemix_notm}}.

* Sélection d'un plan de service adapté à vos besoins. Selon vos besoins, vous avez le choix entre le plan de service Lite et le plan de service Premium. Le plan de service Lite permet la collecte de métriques une fois par minute, leur conservation pendant 15 jours, et une alerte complémentaire.  Sinon, vous pouvez opter pour le plan Premium qui autorise une consommation plus élevée, une conservation plus longue des métriques, et l'accès aux API du service (par exemple, pour envoyer ou extraire des métriques du service {{site.data.keyword.monitoringlong}}). {{site.data.keyword.monitoringlong}} permet la collecte de métriques une fois par minute.  Le plan Lite conserve les métriques complètes pendant 15 jours. Le plan Premium les conserve pendant 45 jours.

Le service {{site.data.keyword.monitoringshort}} existant collectait les mesures à des fréquences définies par le service commençant à 30 secondes, et produisait un récapitulatif sur des fréquences de 1 heure au fil du temps. {{site.data.keyword.monitoringlong}} offre désormais une collecte pleine résolution à 1 minute.  Le plan Lite conserve les mesures pendant 15 jours.  Le plan Premium conserve les mesures pendant 45 jours.

Pour plus d'informations sur le service {{site.data.keyword.monitoringlong}}, voir [la documentation d'initiation à la surveillance](/docs/services/cloud-monitoring/index.html#getting-started-with-ibm-cloud-monitoring) ou [the IBM Cloud Monitoring – Service Refresh with New Features![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")](https://www.ibm.com/blogs/bluemix/2017/07/ibm-cloud-monitoring-service-refresh-new-features/).

### Mise à niveau de {{site.data.keyword.contdelivery_short}}
Nouveau à compter du : 11 juillet 2017

Les avantages de la mise à niveau incluent des correctifs de bogue, des améliorations des performances et des améliorations de l'acquis utilisateur. Les améliorations notables, si elles ne sont pas déjà présentes dans votre environnement, incluent :
<ul>
<li>Correctifs et améliorations apportées à l'internationalisation et à l'accessibilité.</li>
<li>Contrôle d'accès des chaînes d'outils, disponible depuis l'onglet Gérer d'une chaîne d'outils.</li>
<li>Nouvelles intégrations d'outils dans le catalogue d'outils de distribution continue.</li>
<li>Regroupement amélioré des espaces de travail multiples dans l'environnement de développement intégré (IDE) Web Orion.</li>
<li>Prise en charge des onglets d'éditeur multiples dans l'environnement de développement intégré (IDE) Web Orion.</li>
<li>Prise en charge des thèmes d'interface utilisateur dans l'environnement de développement intégré (IDE) Web Orion.</li>
</ul>

### {{site.data.keyword.uccr_short}} bêta
Nouveau à compter du : 23 juin 2017

{{site.data.keyword.uccr_short}} est une solution de gestion des mises en production à l'échelle de l'entreprise qui prend en charge les outils de déploiement natifs cloud et sur site.

La version bêta de {{site.data.keyword.uccr_short}} fournit les fonctions clé suivantes :
* Utilisation des éditions pour gérer plusieurs plans et événements de déploiement, ainsi que pour collaborer sur les efforts de mise en production multi-équipes.
* Création d'événements pour toute activité liée à la mise en production et gestion de ces activités avec le calendrier.
* Importation de vos propres événements et mises en production.
* Personnalisation des événements de calendrier en fonction de votre organisation.
* Utilisation des tâches de type e-mail et Slack pour les notifications de mise en production.

### dashDB for Transactions a été renommé en {{site.data.keyword.DB2_on_Cloud_short}}
Nouveau à compter du : 14 juin 2017

IBM {{site.data.keyword.DB2OnCloud_short}} est le nouveau nom de dashDB for Transactions. Dans le cadre de ce renommage l'ancien service auto-géré IBM {{site.data.keyword.DB2OnCloud_short}} sera également renommé, en IBM Db2 Hosted. Pour le moment, seuls les noms d'affichage sont mis à jour, les API et interfaces de ligne de commande restent inchangées.

### Mises à jour de {{site.data.keyword.sparks}} : le connecteur Stocator-S3 inclut la prise en charge du service IBM Cloud Object Storage Cross Region (bêta)
Nouveau à compter du : 05 juin 2017

Les utilisateurs {{site.data.keyword.sparks}} disposent désormais d'un accès pour effectuer des analyses sur les données stockées dans le service IBM Cloud Object Storage Cross Region. Cette fonction est proposée en version bêta. IBM Cloud Object Storage offre du stockage haute capacité et économique pour Analytics et autres applications ; ce stockage est évolutif, flexible et simple à utiliser.

Apache Spark accède aux données IBM Cloud Object Storage via un connecteur de stockage basé sur la technologie Stocator, qui est implicitement conçu pour le stockage d'objets et, de ce fait, plus rapide que les connecteurs de stockage d'objets existants. En tant qu'utilisateur, vous n'avez pas besoin de modifier ou de recompiler du code Apache Spark.

L'article de blogue [Access and Analyze data in IBM Cross Region Cloud Object Storage](https://www.ibm.com/blogs/bluemix/2017/06/access-analyze-data-ibm-cross-region-cloud-object-storage/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe") décrit l'utilisation des données IBM Cloud Object Storage avec {{site.data.keyword.sparks}} sur {{site.data.keyword.Bluemix_notm}} et IBM Data Science Experience (DSx).

Si vous avez des questions ou des commentaires, contactez-nous à l'adresse [sparksrv@us.ibm.com](sparksrv@us.ibm.com). Nous apprécions vraiment tout retour.

### Nouveau plan évolutif disponible pour {{site.data.keyword.dashdbshort_notm}} for Transactions
Nouveau à compter du : 31 mai 2017

Un nouveau plan est disponible pour {{site.data.keyword.dashdbshort}} for Transactions, capable de croître avec vos besoins de base de données. Le nouveau plan Flex permet de commencer avec un système de petite taille et d'augmenter la puissance et la capacité de stockage de ce système simplement et rapidement. {{site.data.keyword.dashdbshort}} for Transactions est 100 % compatible DB2 et fournit un accord sur les niveaux de licence de 99,95 % sur les plans de haute disponibilité.

### Nouvelles mises à jour du service {{site.data.keyword.mobilepush}} sur {{site.data.keyword.Bluemix_notm}}
Nouveau à compter du : 24 mai 2017

Ci-après les nouvelles mises à jour disponibles pour le service {{site.data.keyword.mobilepush}} sur {{site.data.keyword.Bluemix_notm}}

**Plan Lite** : Nous présentons un nouveau plan Lite en plus du plan de base pour le service {{site.data.keyword.mobilepush}}. Conformément au nouveau plan, les utilisateurs peuvent envoyer gratuitement chaque mois jusqu'à plusieurs centaines de milliers de messages numériques. Dans le cas d'une mise à niveau du plan Lite vers le plan de base, l'utilisateur est facturé au-delà du million de messages numériques. Le comptage commence à partir du moment où le plan Lite est mis à niveau vers le plan de base.

**Surveillance** : Vous pouvez désormais obtenir des informations sur les notifications envoyées et les appareils enregistrés dans la console du service {{site.data.keyword.mobilepush}}. Vous pouvez également utiliser l'API REST pour le suivi des niveaux de message. Depuis la distribution des messages à la répartition des messages puis la réception des messages, les détails peuvent être obtenus via la configuration de webhooks.  Voir [Surveillance pour {{site.data.keyword.mobilepush}}](/docs/services/mobilepush/t_push_monitoring.html#monitor-notifications).

**Notifications Web** : Vous pouvez désormais envoyer des notifications à des navigateurs Web Safari.

### Mises à jour de Secure Gateway
Nouveau à compter du : 24 mai 2017

La dernière mises à jour de maintenance de Secure Gateway inclut des correctifs de bogues mineurs dans l'interface utilisateur et le gestionnaire d'API, la mise à jour de la documentation ; le client a été mis à jour vers la version 1.7.1. Le client Secure Gateway est désormais disponible sous AIX 7.1+ et prend en charge la connexion sortante via un proxy Squid.

### Mises à jour du service {{site.data.keyword.streaminganalyticsshort}} : Développez des applications Streams dans votre environnement de développement Python
Nouveau à compter du : 13 avril 2017

Auparavant, vous deviez installer une version locale d'IBM Streams pour développer des applications Python. Ce n'est plus le cas. Désormais, vous pouvez développer des applications avec Python dans votre environnement de développement préféré ou dans un bloc-notes interactif Jupyter.

Vous pouvez utiliser le contexte STREAMING_ANALYTICS_SERVICE pour soumettre une application Python au service {{site.data.keyword.streaminganalyticsshort}}. Le service {{site.data.keyword.streaminganalyticsshort}} requiert Python 3.5.

Vous pouvez créer des applications Python exemple à l'aide de blocs-notes Jupyter dans IBM Data Science Experience (DSX), et soumettre ces applications à l'instance {{site.data.keyword.streaminganalyticsshort}} directement depuis DSX. Consultez les exemples d'applications Python de traitement de flux dans des blocs-notes sur la page de la [communauté DSX](https://datascience.ibm.com/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

Pour plus d'informations sur les mises à jour du service {{site.data.keyword.streaminganalyticsshort}}, voir [{{site.data.keyword.streaminganalyticsshort}} updates: DSX integration and easier Python development](https://www.ibm.com/blogs/bluemix/2017/05/streaming-analytics-updates-dsx-integration-easier-python-development/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

### Mises à jour de {{site.data.keyword.sparks}} : Apache Spark 2.1 désormais pris en charge
Nouveau à compter du : 21 avril 2017

{{site.data.keyword.sparkl}} introduit la prise en charge d'Apache Spark 2.1 pour la création d'algorithmes permettant d'exploiter les connaissances provenant de données complexes. Apache Spark 2.1 sera une aide précieuse pour la diffusion en flux structuré avec l'ajout d'une prise en charge des cotes d'alerte des événements et Kafka 0.10. Apache Spark 2.1 s'est également concentré sur l'augmentation de la stabilité et de la facilité d'emploi dans les modules Spark SQL, SparkR et MLlib. Pour plus de détails sur Spark 2.1, voir [Spark Release 2.1.0](http://spark.apache.org/releases/spark-release-2-1-0.html).

Nous serons heureux de répondre aux questions concernant {{site.data.keyword.sparkl}} ou la version plus récente d'Apache Spark 2.1. Pour nous joindre : sparksrv@us.ibm.com.

### {{site.data.keyword.macm_short}} sera bientôt obsolète
Nouveau à compter du : 18 avril 2017

A compter du 30 mars 2017, le service {{site.data.keyword.macm_long}} sera retiré du catalogue {{site.data.keyword.Bluemix_notm}} et vous ne pourrez plus mettre à disposition de nouvelles instances MACM. Cependant, les instances existantes continueront à être prises en charge. Date de fin de support : 30 mars 2018. Supprimez vos instances de service {{site.data.keyword.macm_short}} (MACM) avant cette date. Nous encourageons les utilisateurs à migrer vers le concentrateur de contenu IBM Watson Content Hub. Watson Content Hub est disponible sur IBM Marketplace et offre aux utilisateurs une période d'essai gratuit de 30 jours. IBM Watson Content Hub fournit une fonctionnalité similaire à MACM avec de nouvelles fonctions supplémentaires telles que la gestion d'actifs, le balisage cognitif à l'aide des services IBM Watson, ainsi que le réseau de diffusion de contenu (CDN) afin de garantir une expérience optimale pour vos clients. IBM propose des engagements de service pour migrer du contenu depuis MACM vers Watson Content Hub.


### Mises à jour {{site.data.keyword.sparks}} : Bloc-notes désormais pris en charge dans Data Science Experience
Nouveau à compter du : 11 avril 2017

Votre nouvelle plateforme pour utiliser des blocs-notes et Spark : Data Science Experience. Connectez-vous à [Data Science Experience](http://datascience.ibm.com/) et commencez à créer des blocs-notes et à partager votre expertise avec d'autres spécialistes des données.

Si vous utilisiez des blocs-notes dans {{site.data.keyword.sparks}}, vous pouvez les migrer vers Data Science Experience. Pour plus d'informations, voir la [documentation sur la migration des blocs-notes](/docs/services/AnalyticsforApacheSpark/index-gentopic2.html#migration_to_dsx).


---

copyright:

  years: 2015, 2019

lastupdated: "2019-02-19"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# Nouveautés d'{{site.data.keyword.Bluemix_notm}}?
{: #whatsnew}

Restez à jour en utilisant les nouvelles fonctions et les nouveaux services disponibles dans {{site.data.keyword.Bluemix}}, afin d'optimiser votre expérience {{site.data.keyword.Bluemix_notm}}. Les mises à jour sont classées en fonction des catégories suivantes : plateforme {{site.data.keyword.Bluemix_notm}}, {{site.data.keyword.Bluemix_local_notm}} et {{site.data.keyword.Bluemix_dedicated_notm}}, Calcul et Services.
{:shortdesc}

## Plateforme {{site.data.keyword.Bluemix_notm}}
{: #platform_category}


### Nouvelle expérience de support pour {{site.data.keyword.Bluemix_notm}}
Nouveau à compter du : 30 novembre 2018 
{: #support}

En collaboration avec le centre de support, vous pouvez essayer de résoudre les problèmes liés à {{site.data.keyword.Bluemix_notm}}. La page d'arrivée inclut des FAQ. Vous pouvez donc trouver les réponses à vos questions sans même contacter {{site.data.keyword.Bluemix_notm}}. Vous avez également la possibilité de discuter en direct avec un représentant de l'équipe de support. Vos cas peuvent désormais être gérés à partir d'un seul emplacement. Accédez à **Support** &gt; **Gérer les cas** pour créer, afficher ou éditer les cas.

Le centre de support inclut également la [page Statut](https://cloud.ibm.com/status){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe"). De plus, il a été amélioré afin d'inclure les incidents imprévus, la maintenance planifiée, les annonces et les notifications de bulletin de sécurité relatives aux événements clés affectant la plateforme, l'infrastructure et les principaux services {{site.data.keyword.Bluemix_notm}}. Cliquez sur **Afficher le statut du cloud** dans le centre de support. Pour découvrir cette nouvelle expérience, connectez-vous et accédez au [centre de support](https://cloud.ibm.com/unifiedsupport/supportcenter){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe"). 

### Connexion unifiée, clés d'API et gestion de l'accès et des utilisateurs dans {{site.data.keyword.Bluemix_notm}}
Nouveau à compter du : 30 novembre 2018
{: #useraccess}

Avec nos dernières mises à jour, vous pouvez bénéficier d'une connexion sécurisée simplifiée disponible pour tous les utilisateurs, quel que soit le type d'ID. Que vous ayez un IBMid ou un ID SoftLayer, vous pouvez rapidement vous connecter à la console {{site.data.keyword.Bluemix_notm}} à partir de notre page de connexion améliorée. Vous pouvez également effectuer des appels d'API sécurisés dans {{site.data.keyword.Bluemix_notm}} et automatiser votre connexion à l'interface CLI en utilisant une clé d'API IAM ou un jeton d'accès IAM. 

Une fois que vous êtes connecté, vous pouvez voir tous les utilisateurs, notamment ceux de l'infrastructure classique et de la plateforme, sur votre page Utilisateurs dans l'interface utilisateur Accès (IAM). En fonction de l'accès dont vous disposez pour voir les autres utilisateurs du compte, vous pouvez filtrer votre vue rapidement par utilisateurs de compte, utilisateurs d'infrastructure classique ou par organisation Cloud Foundry. Vous pouvez également utiliser les filtres pour trouver rapidement des utilisateurs par nom, adresse électronique ou statut.

Maintenant que tous vos utilisateurs se trouvent dans une seule console, vous pouvez gérer leur accès à tous les types de ressources à partir du même emplacement. L'accès commence par l'utilisateur, commencez donc pas sélectionner un utilisateur dans votre liste. Puis, en fonction du type de ressource auquel vous souhaitez affecter l'accès, vous pouvez effectuer une sélection parmi les règles d'accès IAM, l'accès Cloud Foundry ou les droits de l'infrastructure classique. Si vous souhaitez affecter des règles d'accès IAM, essayez de créer un groupe d'accès pour rationaliser votre processus de gestion d'accès en ajoutant tous les utilisateurs au même groupe d'accès ayant besoin des mêmes règles affectées.

Pour plus de détails, consultez la page [Outstanding User Access Improvements Help Deliver a Unified {{site.data.keyword.Bluemix_notm}} Platform](https://www.ibm.com/blogs/bluemix/2018/11/ibm-cloud-access-management){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe"). 

### Recherche de toute la documentation du plug-in {{site.data.keyword.Bluemix_notm}} CLI à un seul emplacement
Nouveau à compter du : 30 novembre 2018
{: #cli}

Vous pouvez désormais accéder à l'ensemble de la documentation du plug-in {{site.data.keyword.Bluemix_notm}} CLI à un seul emplacement. Ainsi, il est plus facile pour vous de trouver la commande de l'interface CLI que vous recherchez sur la plateforme {{site.data.keyword.Bluemix_notm}}. Consultez la section des références dans la [documentation de l'interface CLI](/docs/cli?topic=cloud-cli-ibmcloud-cli).

### Nouveau tableau de bord et nouvelle liste de ressources
Nouveau à compter du : 30 novembre 2018
{: #dash}

Avec notre dernière mise à jour, vous pouvez désormais voir tous vos services d'infrastructure et de plateforme au même emplacement. Lorsque vous vous connectez, vous pouvez désormais accéder immédiatement au nouveau tableau de bord. Une fois que des ressources sont ajoutées à votre compte à partir du catalogue, vous pouvez utiliser la liste de ressources pour avoir une vue complète de vos ressources de compte. :

* Le tableau de bord a été reconçu afin que vous puissiez voir un récapitulatif de vos ressources, de la maintenance, du statut, des applications, du support, de l'utilisation et des utilisateurs.
* Des informations supplémentaires sur vos ressources sont disponibles dans la liste de ressources. Vous pouvez étiqueter vos ressources pour les organiser ou les sélectionner pour effectuer des modifications sur la page des détails.
* Maintenant que vous pouvez voir toutes vos ressources à un seul emplacement, nous avons ajouté une recherche globale afin que vous puissiez rapidement trouver les ressources que vous avez créées et devant apparaître sur la page Liste de ressources. 
* Vous pouvez également rechercher des résultats de catalogue afin que vous puissiez rapidement trouver les ressources à ajouter à votre compte.  

Pour plus de détails, voir [Manage All Your Cloud Resources on the Enhanced {{site.data.keyword.Bluemix_notm}} Platform](https://www.ibm.com/blogs/bluemix/2018/11/manage-all-your-cloud-resources-on-the-enhanced-ibm-cloud-platform/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

### Informations de profil utilisateur, de facturation et de compte unifié pour les services d'infrastructure et de plateforme
Nouveau à compter du : 30 novembre 2018
{: #profile}

Vos informations de compte, de facturation et de profil ont été simplifiées. Vous pouvez désormais voir vos informations de compte pour toutes vos ressources de plateforme et d'infrastructure dans une console unifiée. 

* La zone de profil et de paramètres contient des informations vous concernant ainsi que les préférences de notification par courrier électronique pour tous les types de ressource. 
* La zone d'informations de compte contient des informations sur votre entreprise, des paramètres de compte et un accès rapide pour l'utilisation de groupes de ressources et d'organisations Cloud Foundry. Elle inclut également les meilleures pratiques vous permettant d'être rapidement opérationnel.
* La zone de facturation et d'utilisation de votre compte vous permet de comprendre votre facture, d'effectuer des paiements, de surveiller les abonnements, d'obtenir des devis, d'effectuer le suivi des commandes et de définir des notifications de dépense.

Pour plus d'informations, consultez la page [Bringing It All Together: A Single Account and Billing Management Experience](https://www.ibm.com/blogs/bluemix/2018/11/ibm-cloud-account-management/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

### Organisation de vos ressources à l'aide d'étiquettes
Nouveau à compter du : 30 novembre 2018
{: #tag}

Vous disposez désormais d'étiquettes que vous pouvez ajouter à vos ressources, comme Cloud Object Storage. Elles vous permettent de gérer les ressources et de trouver celles qui vous intéressent. Par exemple, si vous avez des centaines de ressources et que vous souhaitez différencier deux ressources payées le même jour, vous pouvez les étiqueter en indiquant `costcenter:location01`. Ou, si une équipe utilise à plusieurs reprises deux ressources, vous pouvez utiliser une étiquette du type "team-blue". Vous pouvez également filtrer votre liste de ressources par étiquettes pour les organiser rapidement et trouver les ressources dont vous avez besoin. Pour plus d'informations, voir [Utilisation d'étiquettes](/docs/resources?topic=resources-tag) et [Platform Tagging on the Enhanced {{site.data.keyword.Bluemix_notm}} Platform](https://www.ibm.com/blogs/bluemix/2018/11/platform-tagging-on-the-enhanced-ibm-cloud-platform/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe"). 

### Recherche des coûts mensuels précis avec l'estimateur de coût
Nouveau à compter du : 30 novembre 2018
{: #cost-estimator}

Pour vous aider à choisir les services à acheter, vous pouvez utiliser l'estimateur de coût. Vous pouvez désormais parcourir la console et sélectionner chaque service dont vous souhaitez disposer et ajouter l'ensemble des coûts dans un outil facile à utiliser. Vous pouvez même entrer les utilisations de données projetées, les recherches par seconde, les écritures par seconde ainsi que les requêtes par seconde pour obtenir une estimation plus précise de vos dépenses mensuelles. Vous pouvez utiliser l'estimateur de coût avec chaque service de catalogue sélectionné ou vous pouvez cliquer sur l'icône d'estimateur de coût ![Icône Estimateur](../../icons/Estimator.svg) dans le menu de la console pour obtenir un récapitulatif de vos coûts estimés. Pour plus d'informations, voir [Estimation de vos coûts](/docs/billing-usage?topic=billing-usage-cost).

### Mise à jour des noms d'emplacement globaux pour {{site.data.keyword.cloud_notm}}
Nouveau à compter du : 1er novembre 2018
{: #location-name-updates}

Au fur et à mesure qu'{{site.data.keyword.cloud_notm}} continue à développer son empreinte de disponibilité globale, nous mettons à jour la structure de dénomination de nos emplacements pour proposer une hiérarchie plus compréhensible et cohérente des géographies, régions et centres de données à travers le monde. Si vous êtes familiers avec les régions globales actuelles, vous reconnaîtrez des noms tels que Sud des Etats-Unis et Sydney. Nous alignons ces noms d'emplacement avec le nom de la ville où résident physiquement les centres de données.

Pour l'instant, les ID de programmation sont sans changement, de sorte qu'aucun impact n'est prévisible depuis une perspective d'API. Le tableau suivant présente les anciens et les nouveaux noms des emplacements. Pour plus d'informations et une liste exhaustive des centres de données et des régions, voir [Disponibilité des services](/docs/resources?topic=resources-services_region).

| Nom d'affichage de l'emplacement précédent | Nom d'affichage du nouvel emplacement | Code |
|----------|---------|---------|
| Sud des Etats-Unis | Dallas | us-south | 
| Est des Etats-Unis | Washington DC | us-east |
| Royaume-Uni | Londres | eu-gb |
| Allemagne | Francfort | eu-de |
| Sydney | Sydney | au-syd |
| Asie-Pacifique nord | Tokyo | jp-tok |
{: caption="Tableau 1. Nouveaux noms d'emplacement" caption-side="top"}

### Affectation à d'autres d'un accès pour gestion de compte
Nouveau à compter du : 30 octobre 2018
{: #acct-mgmt-services}

Avec {{site.data.keyword.cloud_notm}} IAM (Identity and Access Management), vous pouvez déléguer des tâches courantes que vous effectuez en tant qu'administrateur de compte à un autre utilisateur de votre compte. En créant une règle d'accès sur l'un ou tous les services de gestion de compte disponibles; vous pouvez sans difficulté déléguer des responsabilités comme l'invitation ou la suppression d'utilisateurs, la gestion de groupes d'accès, d'ID de service, la maintenance de services de catalogue privé et même le suivi de la facturation et de l'utilisation. Vous pouvez utiliser quatre services individuels de gestion de compte ainsi qu'une option tous services pour configurer les règles d'accès :

* Gestion d'utilisateur pour inviter et supprimer des utilisateurs
* Groupes d'accès IAM pour créer, éditer, supprimer, mettre à jour et affecter des accès 
* Service d'identité IAM pour afficher, créer, supprimer et affecter des accès aux ID de service et aux clés d'API associées à travers le compte
* Catalogue de ressources globales pour affichage d'offres de catalogue privé et mise à jour des métadonnées et de la visibilité pour les offres
* Tous les services de gestion des comptes pour accès à chacune des options individuelles de gestion de compte en fonction du rôle affecté, ainsi qu'accès à la facturation et au suivi de l'utilisation .

Pour plus d'informations sur les tâches que peut effectuer un utilisateur en fonction du service de gestion de compte auquel il est rattaché et du rôle qui lui est affecté, voir [Exemple d'actions et de rôles de gestion de plateforme pour les services de gestion de compte](/docs/iam?topic=iam-userroles#platformrolestable2). Pour plus d'informations sur cette nouvelle fonction, voir l'article de blogue [Introducing More Flexibility and Control for IBM Cloud Account Management Services Access](https://www.ibm.com/blogs/bluemix/2018/11/introducing-more-flexibility-and-control-for-ibm-cloud-account-management-services-access/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe"). 

### Recherche de ressources
Nouveau à compter du : 17 juillet 2018
{: #forward-slash-key}

Vous pouvez rechercher des ressources à tout emplacement de la console {{site.data.keyword.cloud_notm}}. Entrez le nom d'une ressource dans la zone de recherche de la barre de menu de la console. Appuyez sur la touche Barre oblique (/) pour activer la recherche.

### Ajout de manière dynamique d'utilisateurs fédérés à des groupes d'accès
Nouveau à compter du : 12 juillet 2018
{: #add-fed-users}

Vous pouvez créer des règles dynamiques pour ajouter dynamiquement des utilisateurs fédérés à des groupes d'accès en fonction d'attributs d'identité spécifiques. Lorsque vos utilisateurs se connectent avec un ID fédéré, les données du fournisseur d'identité mappent dynamiquement vos utilisateurs à un groupe d'accès en fonction des règles définies. Pour plus d'informations, voir [Création de règles dynamiques pour les groupes d’accès](/docs/iam?topic=iam-rules).

### Protection des ID de service et des clés d'API
Nouveau à compter du : 1 juin 2018
{: #protect-svcid-apikey}

Pour éviter que la suppression de votre ID de service ou de votre clé d'API ne provoque une indisponibilité ou une interruption, vous pouvez verrouiller les ID de service et les clés d'API en utilisant l'interface utilisateur ou l'interface CLI. Le verrouillage d'un ID de service empêche que les règles d'accès soient changées, modifiées ou affectées et que les clés d'API associées à l'ID de service soient créées ou supprimées. Pour plus d'informations, voir [Verrouillage d'un ID de service](/docs/iam?topic=iam-serviceidapikeys#lockkey) et [Verrouillage d'une clé d'API](/docs/iam?topic=iam-userapikey).

### Mise à jour de votre compte Lite vers un compte Abonnement
Nouveau à compter du : 31 mai 2018
{: #upgrade-lite}

Vous pouvez désormais mettre à niveau votre compte Lite vers un compte Abonnement directement à partir de la console {{site.data.keyword.Bluemix_notm}}. Avec un compte Abonnement, vous pouvez utiliser les offres de plateforme et d'infrastructure et tirer le meilleur parti de la remise tarifaire en optant pour un engagement mensuel. Vous pouvez éviter les surprises en choisissant une facturation fixe basée sur un calendrier de paiements mensuels, mais avec la flexibilité de commander plus ou moins selon vos besoins. Pour plus d'informations, voir [FAQ sur les comptes Abonnement](/docs/billing-usage?topic=billing-usage-billusagefaqs#subs-order). 

### {{site.data.keyword.Bluemix_notm}} Modification de l'interface CLI
Nouveau à compter du : 15 mai 2018
{: #cli-rebrand}

Les commandes de l'interface CLI d'{{site.data.keyword.Bluemix_notm}}, de **`bluemix`** et de **`bx`** ont été modifiées en **`ibmcloud`**. Vous pouvez toutefois continuer à utiliser les commandes de l'interface CLI **`bluemix`** et **`bx`** jusqu'à ce qu'elles soient retirées. Il n'existe actuellement aucun nom abrégé, uniquement le nom complet **`ibmcloud`**. 

### Authentification multi-facteur pour votre compte {{site.data.keyword.Bluemix_notm}}
Nouveau à compter du : 2 mai 2018
{: #account-mfa}

L'authentification multi-facteur ajoute une couche supplémentaire de sécurité à votre compte en demandant à tous les utilisateurs lors de la connexion de fournir un code d'accès à usage unique et à durée définie en plus de leur IBMid et mot de passe standard. Ce type d'authentification est également communément appelé authentification à deux facteurs (2FA). L'authentification multi-facteur est activée par compte, et une fois activée, tous les utilisateurs du compte doivent se connecter en utilisant la mesure de sécurité supplémentaire. Pour plus d'informations, voir l'article de blogue [IBM Cloud Platform now adds support for Multi-Factor Authentication](https://www.ibm.com/blogs/bluemix/2018/05/ibm-cloud-platform-now-adds-support-multi-factor-authentication/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

### Affectation rapide d'un accès à l'aide de groupes d'accès
Nouveau à compter du : 3 avril 2018
{: #access-groups}

Vous souhaitez pouvoir affecter rapidement un accès en utilisant le moins de règles possible ? Désormais, vous pouvez. Les groupes d'accès vous permettent de regrouper un ensemble d'utilisateurs et d'ID de service et d'affecter une seule règle qui s'applique à tous les membres de ce groupe. L'utilisation de groupes d'accès vous permet de limiter le temps nécessaire à la gestion de l'accès aux utilisateurs et aux ID de service de votre compte. Pour plus d'informations, consultez l'article de blogue [New feature: Access groups](https://www.ibm.com/blogs/bluemix/2018/04/access-groups/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

### Liaison des comptes SoftLayer et {{site.data.keyword.Bluemix_notm}}
Nouveau à compter du : 01 mars 2018
{: #account-completion}

Vous pouvez lier votre compte SoftLayer à votre compte {{site.data.keyword.Bluemix_notm}} pour vous connecter à un seul emplacement, la console {{site.data.keyword.Bluemix_notm}}, et accéder aux ressources IaaS (infrastructure sous forme de services) et PaaS (plateforme sous forme de services). Si vous ne connaissez pas l'environnement {{site.data.keyword.Bluemix_notm}}, créez et liez un compte afin d'obtenir gratuitement un compte Lite {{site.data.keyword.Bluemix_notm}}. Ou, si vous avez déjà un compte {{site.data.keyword.Bluemix_notm}} avec des ressources PaaS, liez vos comptes afin de recevoir une seule facture pour vos ressources IaaS et PaaS. Consultez le site [Steps to Link your IaaS and PaaS Accounts](https://www.ibm.com/blogs/bluemix/2018/03/follow-steps-link-iaas-paas-accounts/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe") pour savoir comment lier rapidement vos comptes.


### {{site.data.keyword.Bluemix_notm}} Foundry Service région Est des Etats-Unis désormais disponible
Nouveau à compter du : 15 décembre 2017
{: #cf-useast}

Un nouveau centre de données pour la région Est des Etats-Unis est désormais disponible à Washington, DC. Cette nouvelle région est accessible via le noeud final `us-east.cloud.ibm.com`. Pour plus de détails sur les services disponibles à l'achat dans cette nouvelle région, voir [Services par région](/docs/resources?topic=resources-services_region).

### Support pour des ressources dans l'Union européenne
Nouveau à compter du : 14 décembre 2017
{: #eu-resources}

Si vos services et centres de données se trouvent en Europe, {{site.data.keyword.Bluemix_notm}} propose désormais des fonctions supplémentaires destinées à protéger vos données dans l'Union européenne. Vous pouvez demander que le support soit assuré par des équipes de cas client situées en Europe. Ce support est disponible 24 heures sur 24, 7 jours sur 7. Voir [Activation de l'option Support dans l'Union européenne](/docs/account?topic=account-eu-hipaa-supported#bill_eusupported) et [Demande de support pour des ressources dans l'Union européenne](/docs/get-support?topic=get-support-getting-customer-support#eusupported) pour plus d'informations.

### Retrait de la prise en charge de TLS 1.0 et 1.1
Nouveau à compter du : 28 novembre 2017
{: #nosupport-tls}

Au 1er mars 2018 {{site.data.keyword.Bluemix_notm}} retire la prise en charge de TLS 1.0 et TLS 1.1 sur un grand nombre de nos produits et services cloud dans le cadre de notre engagement à offrir un cloud totalement sécurisé et conforme aux dernières recommandations de sécurité et de confidentialité. Pour en savoir plus sur la façon dont ce changement vous affecte et les actions qu'il peut être nécessaire de prendre, voir [Retrait de la prise en charge de TLS 1.0 et 1.1](/docs/get-support?topic=get-support-tlssupportwithdraw).

### Une nouvelle façon d'organiser les ressources au sein de votre compte
Nouveau à compter du : 16 novembre 2017
{: #usergs}

Les groupes de ressources constituent une nouvelle façon de créer des regroupements personnalisables de ressources de compte, et l'accès au groupe et aux ressources qu'il contient est géré via Identity and Access Management (IAM). Chacun débute par un groupe de ressources par défaut. Vous pouvez renommer ce groupe de ressources et y ajouter de nouvelles instances de service lorsque les créez depuis le catalogue.

Pour les utilisateurs disposant d'un compte Paiement à la carte ou Abonnement, vous pouvez créer des groupes de ressources supplémentaires de manière à faciliter la gestion de quota et l'affichage de la facturation pour un ensemble de ressources. Vous pouvez également regrouper des ressources afin de faciliter l'affectation d'accès utilisateur à plusieurs services à la fois. Pour plus d'informations sur l'utilisation des groupes de ressources pour votre compte, voir [Gestion des groupes de ressources](/docs/resources?topic=resources-rgs).

### Mises à jour pour {{site.data.keyword.Bluemix_notm}} IAM
Nouveau à compter du : 16 novembre 2017
{: #iam-nov17}

L'introduction de groupes de ressources dans votre compte {{site.data.keyword.Bluemix_notm}} a ouvert la voie à une nouvelle façon d'affecter des accès. Des ID utilisateur et de service peuvent être affectés pour un accès à l'ensemble des services d'un groupe de ressources, permettant ainsi de donner rapidement accès à plusieurs ressource à la fois. Vous pouvez également personnaliser l'accès pour chaque ID utilisateur ou service en affectant l'accès uniquement à certains services d'un groupe de ressources, ou simplement en choisissant d'affecter l'accès à des ressources individuelles au niveau de l'instance de service. Pour plus d'informations sur les fonctions dont vous pouvez bénéficier en utilisant IAM, voir [Quelles fonctions sont fournies par IAM ?](/docs/iam?topic=iam-iamoverview#features)

### Personnalisez votre vue du tableau de bord
Nouveau à compter du : 16 novembre 2017
{: #custom-dash}

Vous pouvez afficher et gérer toutes les ressources de votre compte depuis votre tableau de bord sur la console {{site.data.keyword.Bluemix_notm}}. Et désormais, vous pouvez définir des filtres afin de personnaliser votre vue. Vous pouvez, par exemple, filtrer par groupe de ressources pour afficher les ressources spécifiques d'un groupe. Vous pouvez également filtrer par région ou par espace Cloud Foundry. Pour plus de détails, voir [Gestion des ressources sur le tableau de bord](/docs/overview?topic=overview-ui#dashboardview).

### Centre de support
Nouveau à compter du : 2 novembre 2017
{: #support-nov17}

Le nouveau centre de support permet désormais de rechercher des informations, poster des questions à notre communauté de développeurs et gérer les tickets. Accédez à **Support > Centre de support** depuis la barre de menus de la console {{site.data.keyword.Bluemix_notm}}.

### Présentation d'IBM Cloud
Nouveau à compter du : 31 octobre 2017
{: #meet-ibmcloud}

Bluemix devient IBM Cloud. En dehors du lancement du nouveau nom, votre application reste la même. Vous pouvez toujours facilement générer et exécuter vos applications et services comme auparavant. Consultez le [IBM Cloud Blog](https://www.ibm.com/blogs/bluemix/2017/10/bluemix-is-now-ibm-cloud/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe") pour plus de détails.

### Compte Lite
Nouveau à compter du : 31 octobre 2017
{: #new-liteacct}

Le compte Lite est notre nouveau type de compte, qui offre un accès à une sélection de services en essai gratuit sans limite de temps. Ce nouveau compte inclut également l'utilisation de fonctions de suivi et d'efficience pour vous aider à mieux gérer vos ressources. Pour connaître les disponibilités, voir [Types de compte](/docs/account?topic=account-accounts#liteaccount).

### Fonctions d'authentification de l'application Identity and Access Management
Nouveau à compter du : 6 octobre 2017
{: #app-authfeature}

Identity and Access Management (IAM) permet désormais de créer un ID service, que vous pouvez considérer comme une identité utilisable pour des applications à authentifier avec vos services {{site.data.keyword.Bluemix_notm}}. Plutôt que d'utiliser des données d'identification d'un utilisateur individuel, vous pouvez créer un ID service avec une clé d'API associée et des droits d'accès sous la forme d'une règle de service affectée à l'ID service pour vous permettre de contrôler le niveau d'accès d'une application s'authentifiant avec cet ID.

Pour plus d'informations sur les avantages que présente cette fonction et sur sa mise en route, voir [Présentation des ID service IBM Cloud IAM et des clés d'API](https://www.ibm.com/blogs/bluemix/2017/10/introducing-ibm-cloud-iam-service-ids-api-keys/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

### Catalogue global {{site.data.keyword.Bluemix_notm}}
Nouveau à compter du : 27 juillet 2017
{: #gc}

La dernière mise à jour de la console permet de gérer vos régions publiques depuis un emplacement unique de la console. De plus, {{site.data.keyword.Bluemix_notm}} inclut désormais un catalogue global qui permet de rationaliser davantage le processus de sélection et de déploiement d'éléments sélectionnés depuis le catalogue. Quelle que soit la région sélectionnée sur la console, vous pouvez désormais voir depuis votre catalogue tous les services disponibles pour l'ensemble des régions publiques. Lorsque vous sélectionnez une vignette dans le catalogue, vous pouvez voir dans quelles régions le service est disponible et sélectionner l'emplacement où vous souhaitez le déployer. Pour plus d'informations sur les dernières mises à jour du catalogue, voir [Un catalogue {{site.data.keyword.Bluemix_notm}} global pour simplifier les choses](https://www.ibm.com/blogs/bluemix/2017/07/global-bluemix-catalog-makes-building-things-easier/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

### Mises à jour de la console {{site.data.keyword.Bluemix_notm}}
Nouveau à compter du : 23 mai 2017
{: #console-may17}

Vous pouvez désormais gérer vos régions publiques depuis un emplacement unique via la console {{site.data.keyword.Bluemix_notm}} mise à jour. Le sélecteur de région offre un accès rationalisé aux ressources, et parmi les autres améliorations figurent une disponibilité plus grande et des performances améliorées. Pour plus d'informations, consultez la page [New Global Bluemix UI for Higher Availability and More](https://www.ibm.com/blogs/bluemix/2017/05/new-global-bluemix-ui-higher-availability/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

### Identity and Access Management
Nouveau à compter du : 01 mai 2017
{: #iam-may17}

Avec les toutes dernières mises à jour et améliorations, les propriétaires de compte ou les administrateurs {{site.data.keyword.Bluemix_notm}} peuvent désormais utiliser une nouvelle interface utilisateur de compte unifié pour tirer partie des fonctions suivantes :
 * Gérer l'accès à granularité fine aux services Kubernetes et autres des utilisateurs lorsqu'ils adoptent les nouvelles fonctions de contrôle d'accès
 * Affecter des règles de service et des rôles Cloud Foundry aux utilisateurs au sein de leurs organisations

En outre, les utilisateurs de la plateforme {{site.data.keyword.Bluemix_notm}} peuvent créer, supprimer et répertorier les clés d'API associées à leurs ID utilisateur. Ils peuvent également utiliser ces clés pour s'authentifier lorsqu'ils utilisent des API ou des interfaces de ligne de commande.

Enfin, nous avons amélioré notre fonction de gestion unifiée des utilisateurs afin de garantir que, pour un compte IaaS-PaaS lié, les utilisateurs sont gérés de façon unifiée sans devoir les ajouter séparément sur le portail client SoftLayer ou la console {{site.data.keyword.Bluemix_notm}}.

Pour plus d'informations, consultez l'article de blogue [Introducing Identity & Access Management](https://www.ibm.com/blogs/bluemix/2017/05/introducing-identity-access-management/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

### Modifications de conception de la navigation pour les documents {{site.data.keyword.Bluemix_notm}}
Nouveau à compter du : 13 avril 2017
{: #docnavupdates}

Cette mise à jour de la navigation vous permettra de mieux appréhender la façon dont le contenu est organisé dans l'ensemble des documents, vous permettant de trouver plus efficacement le contenu pertinent. Avec un moindre nombre de couches de contenu imbriquées, il n'est plus nécessaire de creuser pour trouver la documentation dont vous avez besoin pour un usage optimal de {{site.data.keyword.Bluemix_notm}}.


## {{site.data.keyword.Bluemix_local_notm}} et {{site.data.keyword.Bluemix_dedicated_notm}}
{: #dedicatedandlocal}

### Mises à jour de février pour la console d'administration
Nouveau à compter du : 28 février 2018
{: #feb18adminconsole}

Avec la dernière mise à jour de février 2018, vous pouvez utiliser les nouvelles fonctions suivantes :

#### Nouveau droit relatif à la gestion des mises à jour de maintenance
{: #newmngmaintpermission}

Un nouveau droit utilisateur a été ajouté afin d'autoriser certains utilisateurs à approuver et replanifier des mises à jour de maintenance et à définir des fenêtres de mise à jour de maintenance spécifiant à quel moment des mises à jour de maintenance peuvent être déployées dans un environnement dédié.
Pour plus d'informations, voir la [vidéo de démonstration](https://youtu.be/7c7jyp_JJWU){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

### Mises à jour de décembre pour la console d'administration
Nouveau à compter du : 14 décembre 2017
{: #december17adminconsole}

Avec les toutes dernières mises à jour et améliorations de décembre, vous pourrez utiliser les nouvelles fonctions suivantes :

#### Abonnement aux notifications de seuil d'utilisation d'UC moyenne
{: #avgcputhresholdnotifications}

L'UC moyenne a été ajoutée en tant que type de seuil aux abonnements aux notifications. Vous pouvez désormais recevoir des notifications lorsque l'utilisation d'UC (moyennée sur l'ensemble des cellules Diego et de DEA) se situe au-delà ou sous un seuil donné.

#### Contrôle d'accès aux systèmes cloud de l'Union européenne
{: #euaccesscontrol}

Combinée à la nouvelle fonction de prise en charge de ressources cloud dans l'Union européenne (en commençant par Francfort), la console d'administration permet désormais de définir des règles de contrôle d'accès par le personnel IBM. Vous pouvez gérer les règles de contrôle d'accès, afficher les demandes d'accès, effectuer des actions sur les demandes et procéder au suivi de l'historique.

#### Informations améliorées dans les rapports de sécurité
{: #enhancedsecreportinfo}

Désormais, les rapports de sécurité incluent des noms conviviaux en plus des ID uniques pour les utilisateurs et les organisations.

### Mises à jour d'août pour la console d'administration
Nouveau à compter du : 31 août 2017
{: #august17adminconsole}

Avec les toutes dernières mises à jour et améliorations d'août, vous pourrez utiliser les nouvelles fonctions suivantes :

#### Mises à jour des statistiques d'utilisation de service {{site.data.keyword.cloudant_short_notm}}
{: #svcusagemetricsupdates}

  * Le calcul des statistiques d'utilisation pour {{site.data.keyword.cloudant_short_notm}} a été mis à jour afin de refléter la quantité totale de Go utilisés et disponibles sur l'ensemble des noeuds d'un cluster {{site.data.keyword.cloudant_short_notm}}. En règle générale, un cluster {{site.data.keyword.cloudant_short_notm}} comporte trois noeuds, et un document de la base de données est répliqué sur l'ensemble des noeuds du cluster à des fins de haute disponibilité et de reprise après incident. Avec les mises à jour d'août, les statistiques de capacité de l'appel {{site.data.keyword.cloudant_short_notm}} (disponible dans la vue _Utilisation des ressources > Services_) indique l'espace sur tous les noeuds du cluster. Si, par exemple, un cluster {{site.data.keyword.cloudant_short_notm}} unique comporte trois noeuds, chacun d'une capacité de 1 000 Go, la limite de capacité sera de 3 000 Go. Si 1 500 Go de cette capacité sont déjà utilisés, les statistiques d'utilisation de {{site.data.keyword.cloudant_short_notm}} seront de 50 %.

#### Mises à jour apportées à la planification des mises à jour de maintenance
{: #maintscheduleupdates}

  * Dans {{site.data.keyword.Bluemix_dedicated_notm}}, les clients peuvent gérer les dates et heures de disponibilité de leurs environnements dédiés pour le déploiement des mises à jour système. Ils peuvent définir des fenêtres de disponibilité représentant les dates et heures où les mises à jour de maintenance peuvent ou non être déployées sur leur environnement dédié. Avec la mise à jour d'août, les _fenêtres de disponibilité pour les mises à jour_ ont été renommées en _Fenêtres de mise à jour_, et les _fenêtres d'indisponibilité pour les mises à jour_ en _Fenêtres d'indisponibilité_. Au-delà de ces changements de terminologique, les clients disposent désormais de davantage de flexibilité et de marge pour définir des dates d'interruption totale (indisponibilité). Une fois qu'elles sont demandées, les dates d'indisponibilité doivent être approuvées par IBM et le délai d'approbation est variable. Une fois les dates acceptées, IBM annule toutes les mises à jour actuellement prévues dans le cadre de la fenêtre d'indisponibilité. IBM crée également de nouveaux enregistrements pour ces mises à jour et planifie ces dernières en dehors des dates d'indisponibilité approuvées.

Pour plus d'informations, voir la [vidéo de démonstration](https://bit.ly/2eCQNvu){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

### Mises à jour de juillet pour la console d'administration
Nouveau à compter du : 31 juillet 2017
{: #july17adminconsole}

Avec les toutes dernières mises à jour et améliorations de juillet, vous pourrez utiliser les nouvelles fonctions suivantes :

#### Mises à jour des fonctions de l'historique d'utilisation des ressources
{: #resourceusagehistoryupdates}

  * Dans la précédente mise à jour (juin), la vue Historique pour l'utilisation de la mémoire et du disque avait introduit l'affichage des données d'utilisation sur les 48 dernières heures, 30 derniers jours et 5 derniers mois. Dans la mise à jour de juillet, la fonctionnalité d'historique d'utilisation des ressources a été étendue afin de permettre la personnalisation de l'intervalle de temps pour lequel afficher les données d'utilisation des ressources. Les vues horaire, quotidienne et mensuelle sont conservées, mais les utilisateurs peuvent désormais spécifier une date/heure de début et une durée pour laquelle afficher les statistiques d'utilisation de la mémoire et du disque (par exemple, afficher l'utilisation de la mémoire pour les 15 jours à compter du 1er juillet 2017).
  * Une nouvelle commande CLI a été introduite pour l'affichage de l'historique des statistiques de ressource dans l'interface de ligne de commande. Les paramètres de la commande, ainsi que des exemples de syntaxe, sont accessibles en tapant la commande suivante : `_cf ba resource-metrics-history -help_`

Pour plus d'informations, voir la [vidéo de démonstration](https://youtu.be/QBij0jB5qAk){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

### Mises à jour de juin pour la console d'administration
Nouveau à compter du : 26 juin 2017
{: #june17adminconsole}

Avec les toutes dernières mises à jour et améliorations de juin, vous pourrez utiliser les nouvelles fonctions suivantes :

#### Mises à jour apportées à la page Utilisation des ressources
{: #resourceusagepageupdates}

  * Ressources système
    * La vue Historique de la mémoire et du disque a été mise à jour afin d'afficher les données sur 48 heures, 30 jours et 5 mois.
    * Un lien En savoir plus est fourni, montrant comment l'API Metrics de la console d'administration est utilisée pour gérer les vues d'historique.
  * Applications
    * Fournit les informations sur l'utilisation de toutes les applications dans l'environnement.
    * Tri par nom d'application, mémoire physique, mémoire réservée, disque physique, disque réservé, UC physique ou nom d'organisation.
    * La recherche est fourni pour filtrer les résultats par nom d'application et nom d'organisation.
    * Un lien En savoir plus est fourni, montrant comment l'API Metrics de la console d'administration est utilisée pour gérer la vue Applications.

Voir [Utilisation des ressources](/docs/hybrid?topic=hybrid-mng#resourceusage) pour plus d'informations.

#### Mises à jour de l'API Metrics
{: #apiformetricsupdates}

  * Des statistiques d'environnement ont été ajoutées, fournissant des moyennes par jour ou par mois pour la consommation de mémoire et de disque.

Voir [API Metrics](/docs/hybrid?topic=hybrid-mng#envappmetricsapi) pour plus d'informations.

### Mises à jour de mai pour la console d'administration
Nouveau à compter du : 30 mai 2017
{: #may17adminconsole}

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
Nouveau à compter du : 2 mai 2017
{: #april17adminconsole}

Avec les toutes dernières mises à jour et améliorations d'avril, vous pourrez utiliser les nouvelles fonctions suivantes :

 * Nouvelle conception de l'application de statut pour les environnements {{site.data.keyword.Bluemix_notm}} dédié et local. Vous pouvez rapidement rechercher par nom de composant ou date d'envoi. Vous pouvez également basculer entre les envois de statut de composant et les notifications spécifiques à votre environnement. Pour plus d'informations, voir l'article de blogue sur la [nouvelle page de statut {{site.data.keyword.Bluemix_notm}}](https://www.ibm.com/blogs/bluemix/2017/05/new-bluemix-status-page/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").
 * Données d'utilisation de service pour les services sélectionnés depuis la vignette Utilisation des ressources. Voir [Détails sur l'utilisation du service](/docs/hybrid?topic=hybrid-servicesresourceusage#servicesresourceusage) pour plus d'informations sur les services pris en charge et ce que vous offre la nouvelle vue.

## Calcul
{: #compute_category}

### Fonctions de l'infrastructure certifiée SAP d'IBM Cloud
Nouveau à compter du : 22 janvier 2019
{: #sapcertinfrafeatures}

Des nouvelles fonctions sont désormais disponibles avec l'offre de l'infrastructure certifiée SAP d'{{site.data.keyword.cloud_notm}} à la fois pour SAP HANA et SAP NetWeaver.

#### Stockage sur plusieurs noeuds
{: #sapcertmultinodestorage}

Stockage sur plusieurs noeuds SAP HANA pour les charges de travail OLAP (Online Analytical Processing), comme SAP Business Warehouse (SAP BW) et SAP BW/4HANA. La solution {{site.data.keyword.cloud_notm}} pour système à plusieurs noeuds SAP HANA peut comprendre jusqu'à 15+1 noeuds (15 noeuds worker, plus un de secours) pour jusqu'à 30 To de mémoire utilisés pour un système. Pour commencer, consultez la section [Configuration de votre infrastructure {{site.data.keyword.cloud_notm}} pour la prise en charge d'un système SAP HANA à plusieurs noeuds](/docs/infrastructure/sap-hana?topic=sap-hana-multi-node-storage).


#### Haute disponibilité
{: #sapcertha}

Les solutions HA (haute disponibilité) sont prises en charge à la fois pour SAP HANA et pour SAP NetWeaver. La solution utilise la version de système d'exploitation prise en charge et est retreinte aux licences de système d'exploitation fournies avec votre déploiement ou à des licences de tiers. Pour commencer, cliquez [ici](/docs/infrastructure/sap-hana?topic=sap-hana-ha) pour SAP HANA et [ici](/docs/infrastructure/sap-netweaver?topic=sap-netweaver-ha) pour SAP NetWeaver.
  
#### Serveur de contenu SAP
{: #sapcontentserver}

Le serveur de contenu SAP est un composant autonome pour le stockage de grande quantités de documents électroniques, quels que soient le format et le contenu. Pour utiliser le serveur de contenu SAP, vos applications SAP doivent prendre en charge son utilisation. Pour commencer, voir [Serveur de contenu SAP](/docs/infrastructure/sap-netweaver?topic=sap-netweaver-content-server).

#### SAP MaxDB
{: #sapmaxdb}

SAP MaxDB est disponible pour SAP NetWeaver. Pour commencer, voir [A propos de l'infrastructure certifiée SAP d'{{site.data.keyword.cloud_notm}}](/docs/infrastructure/sap-netweaver?topic=sap-netweaver-about_ibmcloud_for_sap).

#### SAP Business One
{: #sapbusinessone}

SAP Business One est un logiciel ERP (planification des ressources de l'entreprise) spécialement conçu pour les PME. Il regroupe dans une seule application vos principales fonctions métier (comptabilité et finances, achats et inventaire, ventes et relations client, gestion de projets). Pour plus d'informations, voir [Initiation](/docs/infrastructure/sap-b1?topic=sap-b1-getting-started).

### Fonctions du serveur virtuel
Nouveau à compter du : 16 novembre 2018
{: #vsinov18}

Les fonctions suivantes sont actuellement disponibles pour l'offre {{site.data.keyword.BluVirtServers_full}}.

#### Interruption de la facturation en cas de non-utilisation des instances
{: #vsinov18suspendbilling}

Vous voulez payer en fonction de ce que vous utilisez ? Vous pouvez désormais interrompre la facturation sur les instances de serveur virtuel. La fonction d'interruption de la facturation est disponible sur les instances de serveur virtuel qui ont des volumes horaires publics avec un stockage SAN. Lorsque vous mettez hors tension un serveur virtuel prenant en charge la fonction d'interruption de la facturation, vous ne payez pas les coûts relatifs à certaines ressources de calcul. La facturation s'arrête automatiquement lorsque le serveur est mis hors tension. La fonction d'interruption de la facturation vous permet de réduire les coûts et vous évite d'avoir à remettre à disposition un serveur virtuel quand vous avez à nouveau besoin de ses ressources. Pour plus d'informations, voir [A propos de l'interruption de facturation](/docs/vsi?topic=virtual-servers-about-suspend-billing) ou l'article de blogue {{site.data.keyword.cloud_notm}} [![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")](https://www.ibm.com/blogs/bluemix/2018/10/suspend-billing-1-minute-granularity-virtual-servers/){: new_window}.

#### Réservation de ressources pour les futures instances de serveur virtuel
{: #vsinov18rsvresource}

L'offre d'instances réservées {{site.data.keyword.BluVirtServers_full}} est maintenant disponible. Il s'agit d'une option idéale si vous souhaitez des ressources garanties pour des développements futurs et pour réaliser des économies. Vous avez le choix entre un contrat d'une durée d'un ou de trois ans pour votre capacité réservée. Dans le cadre de cette capacité réservée, vous pouvez réserver un maximum de 20 instances de serveur virtuel d'une taille spécifique et mettre ces instances à disposition lorsque vous en avez besoin. Cette capacité vous est garantie au sein du POD et du centre de données de votre choix pendant toute la durée du contrat. Pour plus d'informations, voir [Reserved virtual servers](/docs/vsi?topic=virtual-servers-about-reserved-virtual-servers).

#### Importation d'images à partir de l'instance de service {{site.data.keyword.cos_full_notm}} dans l'infrastructure {{site.data.keyword.cloud_notm}}
{: #vsinov18importimages}

L'infrastructure {{site.data.keyword.cloud_notm}} interagit désormais avec le service {{site.data.keyword.cos_full_notm}} mis à disposition sur la console {{site.data.keyword.cloud_notm}}. {{site.data.keyword.cos_full_notm}} offre le plug-in de transfert à haut débit Aspera qui réduit considérablement la durée nécessaire pour télécharger une image volumineuse. Une fois que les images ont été téléchargées dans {{site.data.keyword.cos_full_notm}}, vous pouvez [importer les images](/docs/infrastructure/image-templates?topic=image-templates-creating-an-image-template) dans l'infrastructure {{site.data.keyword.cloud_notm}} depuis {{site.data.keyword.cos_full_notm}}. Vous pouvez également [exporter les images](/docs/infrastructure/image-templates?topic=image-templates-exporting-to-ibm-cos) de l'infrastructure {{site.data.keyword.cloud_notm}} vers {{site.data.keyword.cos_full_notm}}.

#### Groupes de placement pour instances de serveur virtuel
{: #vsinov18placement}

Des groupes de placement sont maintenant disponibles pour {{site.data.keyword.BluVirtServers_full}}. Grâce aux groupes de placement, vous pouvez utiliser des instances publiques pour créer une haute disponibilité au sein d'un centre de données ou fournir un niveau de tolérance aux pannes additionnel dans un déploiement plus large. Pour plus d'informations, voir [Groupes de placement](/docs/vsi?topic=virtual-servers-placement-groups). 

### Dernières mises à jour pour les packs de construction
{: #whatsnewbuildpacks}

Visitez les pages suivantes pour avoir la liste cumulée des mises à jour les plus récentes :

* [Dernières mises à jour apportées au pack de construction sdk-for-nodejs](/docs/runtimes/nodejs?topic=Nodejs-latest_updates)
* [Dernières mises à jour apportées au pack de construction Liberty](/docs/runtimes/liberty?topic=liberty-latest_updates)
* [Dernières mises à jour apportées au pack de construction ASP.NET Core](/docs/runtimes/dotnet?topic=Dotnet-latest_updates)
* [Dernières mises à jour apportées au pack de construction IBM XPages for {{site.data.keyword.Bluemix_notm}}](/docs/starters/xpages/index.html#updates)

### Dernières mises à jour pour {{site.data.keyword.containerlong_notm}}
{: #whatsnewkube}

{{site.data.keyword.containerlong_notm}} a lancé son architecture Kubernetes en mai 2017. L'architecture précédente pour les groupes de conteneurs uniques et évolutifs est désormais [obsolète à compter du 5 décembre 2017](https://www.ibm.com/blogs/bluemix/2017/07/deprecation-single-scalable-group-container-service-bluemix-public/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").  

[Pour obtenir des informations sur l'initiation à l'environnement Kubernetes natif sur {{site.data.keyword.Bluemix_notm}}](/docs/containers?topic=containers-container_index), voir la documentation. Si vous avez des questions, vous pouvez les poster sur le canal Slack à l'adresse [https://ibm-container-service.slack.com/](https://ibm-container-service.slack.com/){: new_window} ![Icône de lien externe](../icons/launch-glyph.svg "Icône de lien externe").


### {{site.data.keyword.containerlong_notm}} est maintenant livré avec des maîtres Kubernetes hautement disponibles
Nouveau à compter du : 7 novembre 2018
{: #kubenov18}

Obtenez une disponibilité supérieure pour votre cluster grâce à la fonction de maître Kubernetes à haute disponibilité. Les maîtres Kubernetes à haute disponibilité sont configurés avec plusieurs répliques de votre serveur d'API Kubernetes, etcd, planificateur Kubernetes et contrôleur qui sont distribuées sur divers hôtes physiques. Lorsque vous créez un cluster qui exécute la version 1.12, 1.11 ou 1.10 de Kubernetes, votre maître Kubernetes est défini par défaut pour la haute disponibilité. Pour activer cette fonction dans des clusters existants utilisant l'une de ces versions Kubernetes, vous devez suivre la [procédure de préparation](/docs/containers?topic=containers-110_ha-masters).

### Création de clusters comportant plusieurs zones dans {{site.data.keyword.containerlong_notm}}
Nouveau à compter du : 10 juillet 2018
{: #kubejuly18}

Vous souhaitez améliorer la disponibilité des clusters et des applications ? Vous pouvez désormais étendre votre cluster dans plusieurs zones de certaines régions métropolitaines. Pour plus d'informations, voir [Création de clusters à zones multiples dans {{site.data.keyword.containershort_notm}}](/docs/containers?topic=containers-ha_clusters). 

### L'accès au tableau de bord Kubernetes est désormais disponible dans {{site.data.keyword.containerlong_notm}}
Nouveau à compter du : 18 avril 2018
{: #kubeapril18}

{{site.data.keyword.containerlong_notm}} prend désormais en charge l'accès direct au tableau de bord Kubernetes via la console {{site.data.keyword.Bluemix_notm}}. Ce chemin d'accès simplifié au tableau de bord améliore l'expérience utilisateur pour la gestion de cluster et la visualisation des ressources. Pour plus d'informations, voir le [blogue {{site.data.keyword.Bluemix_notm}} ](https://www.ibm.com/blogs/bluemix/2018/04/kubernetes-dashboard-access/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").


### Nouveau pack de construction Liberty for Java version 3.11
Nouveau à compter du : 17 juillet 2017
{: #libertyjuly17}

Le pack de construction Liberty version 3.11 fournit chaque mois une nouvelle version du contexte d'exécution Liberty et comporte d'autres améliorations. La version mensuelle du contexte d'exécution Liberty a été mise à jour vers l'édition [2017.7.0.0](https://developer.ibm.com/wasdev/blog/2017/07/07/beta-websphere-liberty-tools-july-2017/). Le kit Java Development Kit IBM a été mis à jour vers les versions 8.0.4.7 et 7.1.4.5. Le pack de construction fournit également des versions mises à jour de l'utilitaire App Management et de l'agent Auto-Scaling. La bibliothèque Cloudant par défaut est désormais la bibliothèque officielle [java-cloudant](https://github.com/cloudant/java-cloudant), la [bibliothèque Ektorp](https://github.com/helun/Ektorp) est toujours disponible en option. Pour obtenir des détails sur cette modification, voir l'[article du blogue](https://www.ibm.com/blogs/bluemix/2017/05/default-library-change-cloudant-auto-wiring-liberty-buildpack/). Le rapport de taille de segment de mémoire par défaut est désormais de 50 % lorsque votre application comporte moins de 512 Mo de mémoire, mais reste de 75 % si elle comporte plus de 512 Mo. Un nouveau journal des tâches de préproduction est à présent généré, qui permet un débogage simplifié des erreurs de préproduction. Pour plus d'informations, voir les [dernières mises à jour](/docs/runtimes/liberty?topic=liberty-latest_updates).

### Nouveau pack de construction Liberty for Java version 3.10
Nouveau à compter du : 12 juin 2017
{: #libertyjune17}

Le pack de construction Liberty versions 3.10 fournit chaque mois et chaque trimestre de nouvelles versions du contexte d'exécution Liberty et comporte d'autres améliorations. La version par défaut du contexte d'exécution Liberty a été mise à jour vers la version 17.0.0.2. La version mensuelle du contexte d'exécution Liberty a été mise à jour vers l'édition [2017.5.0.0](https://developer.ibm.com/wasdev/blog/2017/05/12/beta-websphere-liberty-tools-may-2017/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe"). Le pack de construction fournit également des versions mises à jour de l'utilitaire App Management et du client Extreme Scale. Pour plus d'informations, voir les [dernières mises à jour](/docs/runtimes/liberty?topic=liberty-latest_updates).

### Nouveau kit de développement de logiciels pour le pack de construction Node.js version 3.12
Nouveau à compter du : 16 mai 2017
{: #libertymay17}

Le pack de construction SDK for Node.js v3.12 fournit les versions 0.12.17, 0.12.18, 4.8.0, 4.8.2, 6.10.0 et 6.10.2 d'IBM SDK Node.js. La valeur par défaut est passée de la dernière version 4.x à la dernière version 6.x, et est actuellement la version 6.10.2. S'agissant d'un changement de version principale, cela peut affecter les applications qui dépendent de la valeur par défaut. Voir [Node.js version long-term support and the SDK for Node.js buildpack](https://www.ibm.com/blogs/bluemix/2016/11/node-version-support-and-sdk-buildpack/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe") pour plus d'informations sur les moyens d'éviter les problèmes.

En plus de nouveaux environnements d'exécution, cette édition contient une correction d'erreur concernant l'utilitaire App Management Health Center et les versions 6.9.5 et 6.10.0 de Node.js.

### Nouveau pack de construction Liberty for Java version 3.9
Nouveau à compter du : 27 avril 2017
{: #libertyapril17}

Le pack de construction Liberty version 3.9 fournit chaque mois une nouvelle version du contexte d'exécution Liberty et comporte d'autres améliorations. La version par défaut du contexte d'exécution Liberty a été mise à jour afin d'inclure les iFixes PI77770, PI77605, IFPI77438 et IFPI79275. La version mensuelle du contexte d'exécution Liberty a été mise à jour vers l'édition [2017.3.0.0](https://developer.ibm.com/wasdev/blog/2017/03/14/beta-websphere-liberty-tools-march-2017/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe"). Le calcul de la mémoire est passé de la préproduction au processus de démarrage, facilitant ainsi les changements de segment de mémoire avec le redémarrage d'une application. Le pack de construction fournit également des versions mises à jour de l'agent de service Auto-Scaling et du client Extreme Scale. Pour plus d'informations, voir les [dernières mises à jour](/docs/runtimes/liberty?topic=liberty-latest_updates).

## Services
{: #services_category}

### Nouvelles fonctions disponibles dans {{site.data.keyword.appid_short_notm}}
Nouveau à compter du : 22 décembre 2018
{: #appiddec18}

Le service {{site.data.keyword.appid_short_notm}} inclut désormais de nouvelles fonctions avancées qui renforcent la sécurité de vos authentifications et de vos applications.

{{site.data.keyword.appid_short_notm}} vous permet d'ajouter différents types d'authentification aux applications Web et mobiles. Vous pouvez ajouter l'authentification à l'aide de quelques lignes de code et ne plus vous préoccuper de la gestion de l'infrastructure afin qu'elle soit adaptée à votre base utilisateur. Consultez les améliorations énumérées ci-dessous puis lancez-vous !

Authentification multi-facteur - Vous pouvez désormais utiliser l'authentification multi-facteur par courrier électronique pour Cloud Directory. Lorsque l'authentification multi-facteur est activée, il est demandé aux utilisateurs d'indiquer un code unique reçu par courrier électronique en plus de leur nom d'utilisateur. Si vous utilisez la connexion d'entreprise avec SAML 2.0 ou la connexion sociale, vous pouvez activer l'authentification multi-facteur via ce fournisseur d'identité.
Règles de mot de passe avancées - Avec la fonction de règle de mot de passe avancée, vous pouvez appliquer des mots de passe plus sécurisés pour Cloud Directory. Vous pouvez configurer un ensemble de règles pour les mots de passe. Vous pouvez par exemple définir le nombre de fois qu'un utilisateur peut tenter de se connecter avant qu'il ne soit verrouillé ou le nombre maximal d'utilisations d'un même mot de passe.

Les fonctions de sécurité avancées incluent un composant de tarification supplémentaire. Pour plus d'informations sur le mode de calcul de la tarification, voir la section correspondante dans [le catalogue](https://cloud.ibm.com/catalog/services/app-id){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

Consultez la [documentation {{site.data.keyword.appid_short_notm}}](/docs/services/appid?topic=appid-gettingstarted) et commencez dès maintenant !

### Introduction à {{site.data.keyword.backup_notm}}
Nouveau à compter du : 20 décembre 2018
{: #backupdec18}

L'équipe de l'infrastructure de stockage {{site.data.keyword.BluSoftlayer_full}} est fière de présenter la nouvelle version du produit {{site.data.keyword.backup_full}}, qui inclut un niveau de 10 Go gratuit à vie. De plus, tous les plug-in sont désormais gratuits. Par conséquent, l'implémentation de cas d'utilisation d'application spécifiques, comme MSSQL, Oracle DB, Exchange ou même Bare Metal Restore ne génère aucun frais supplémentaire. La nouvelle version du produit {{site.data.keyword.backup_notm}} constitue la meilleure solution pour vos besoins en matière de sauvegarde. Pour plus d'informations, voir le blog [IBM Cloud Blog ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")](https://www.ibm.com/blogs/bluemix/2018/12/introducing-a-new-cloud-backup-service-ibm-cloud-backup/){: new_window}.

### Citrix NetScaler VPX Version 12.1
Nouveau à compter du : 21 novembre 2018
{: #vpx121}

#### Serveurs virtuels avec plusieurs adresses IP
{: #vpxips}
Vous pouvez désormais créer un serveur virtuel d'équilibrage de charge avec plusieurs adresses IPv4 et IPv6 VIP consécutives et non consécutives. Chaque adresse VIP liée à un serveur virtuel est considérée comme un serveur virtuel individuel.

Pour plus d'informations sur cette fonction, voir l'article Citrix [Multiple IP virtual servers ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")](https://docs.citrix.com/en-us/netscaler/12-1/load-balancing/load-balancing-customizing/multi-ip-virtual-servers.html){: new_window}.

#### SSL
{: #vpxssl}

Les mises à jour suivantes ont été appliquées pour les connexions SSL :
 
* Suppression des chiffrements faibles du groupe de chiffrements DEFAULT_BACKEND 
* Prise en charge des chiffrements ECDHE sur le serveur frontal du module de sécurité matérielle externe Thales nShield®
* Prise en charge des chiffrements ECDHE sur le serveur frontal du module de sécurité matérielle du réseau SafeNet
* Suppression de SSLv2 : Le périphérique NetScaler VPX ne prend plus en charge SSLv2 depuis la version 12.1.

Pour plus de détails sur les mises à jour de SSL 12.1, voir [Citrix 12.1 Release Notes ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")](https://docs.citrix.com/en-us/netscaler/12-1/downloads/release-notes-12-1-48-13.html){: new_window}.

#### Prise en charge des groupes de services pour GSLB
{: #vpxgslb}

Vous pouvez désormais configurer des groupes de services basés sur des adresses IP, des groupes de services basés sur des noms de domaine ou des groupes de services de mise à l'échelle automatique basés sur des noms de domaine pour GSLB. Vous pouvez également gérer un groupe de services aussi facilement qu'un seul service, et lier un groupe de services à un serveur virtuel ainsi qu'ajouter des services au groupe.

Pour plus d'informations sur les groupes de services GSLB, voir l'article Citrix [Configuring a GSLB service group ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")](https://docs.citrix.com/en-us/netscaler/12/global-server-load-balancing/configure/configuring-a-gslb-service-group.html){: new_window}.


### Mise à jour majeure de {{site.data.keyword.conversationshort}}
Nouveau à compter du : 9 novembre 2018
{: #whatsnewasstnov18}

{{site.data.keyword.conversationshort}} a une nouvelle apparence et des fonctionnalités supplémentaires. L'artefact connu comme *espace de travail*, qui est un conteneur pour les données de formation du modèle d'apprentissage automatique qui alimente votre agent conversationnel, a été remplacé par une *compétence de dialogue*. Vos déploiements seront désormais plus simples grâce à la possibilité d'ajouter votre compétence de dialogue à un assistant. Le nouveau niveau d'assistant gère l'orchestration des messages entre l'utilisateur et votre compétence. Vous pouvez ajouter des intégrations incorporées à l'assistant pour publier votre compétence de dialogue dans des canaux de transmission de messages populaires avec un minimum d'effort. La documentation de {{site.data.keyword.conversationshort}} a été déplacée. Voir la [documentation du produit](/docs/services/conversation?topic=watson-assistant-about) pour plus d'informations.


### Automatisation de déploiements d'infrastructure et d'application à l'aide de Terraform et d'Ansible
Nouveau à compter du : 2 novembre 2018
{: #autodeploynov18}

Terraform et Ansible sont des logiciels open source que vous pouvez utiliser pour automatiser de bout en bout le déploiement de votre solution de cloud. Terraform vous permet de spécifier vos composants d'infrastructure {{site.data.keyword.Bluemix_notm}} et de générer rapidement des environnements de cloud multiniveau complexes pour activer les plateformes IaC (Infrastructure as Code). Utilisez ensuite Ansible pour vous connecter à vos hôtes de calcul sur le réseau privé afin de déployer vos applications, générer des services, exécuter des scripts ou définir des configurations. 

Pour commencer et découvrir les principes fondamentaux de chaque produit open source, consultez nos tutoriels : 
* [Deploying RedHat OpenShift Container Platform on {{site.data.keyword.Bluemix_notm}} with Terraform](/docs/terraform/tutorials?topic=terraform-redhat)
* [Deploying WordPress on IBM Cloud infrastructure with Terraform and Ansible](/docs/terraform/tutorials?topic=terraform-deploy_wordpress). 

### Dernières mises à jour pour {{site.data.keyword.cloudant_short_notm}}
Nouveau à compter du : 28 septembre 2018
{: #whatsnewcloudantsept18}

Visitez la page suivante pour accéder à la liste complète des [dernières mises à jour](/docs/services/Cloudant/release_info?topic=cloudant-release-notes) {{site.data.keyword.cloudant_short_notm}}.

### Présentation d'{{site.data.keyword.IBM_notm}} {{site.data.keyword.DRA_short}} (disponibilité générale)
Nouveau à compter du : 20 septembre 2018
{: #whatsnewdraept18}

Le service {{site.data.keyword.DRA_short}} est désormais disponible dans les régions Sud des Etats-Unis, Allemagne et Royaume-Uni.

{{site.data.keyword.DRA_short}} permet aux différentes équipes d'améliorer leur productivité, leur efficacité et d'accélérer la commercialisation. De plus, elles peuvent utiliser les données des outils DevOps pour évaluer facilement la réussite ou améliorer la qualité du code. Ce service constitue l'outil idéal permettant aux entreprises de comprendre leurs activités DevOpsdans dans leurs bases de code et leurs équipes.

* **Vitesse** : {{site.data.keyword.DRA_short}} affiche toutes les données d'analyse de vos applications dans un seul tableau de bord.
* **Qualité** : réduisez le nombre de versions à risque en implémentant des règles de déploiement de blocage. Par exemple, si vous avez une règle pour la couverture du code impliquant une tolérance sélectionnée, {{site.data.keyword.DRA_short}} bloque toujours les versions de code ne respectant pas les tolérances définies. Ces règles vous permettent d'améliorer la qualité du processus de déploiement. 
* **Contrôle** : mesurez les résultats au fur et à mesure que les équipes réagissent aux différentes tendances dans leurs pratiques DevOps en utilisant la couverture du code, des tests d'unité et d'autres outils. Ces tendances permettent aux équipes de mieux réglementer leurs pratiques DevOps.

### {{site.data.keyword.security-advisor_long_notm}} est à présent disponible en version bêta !
Nouveau à compter du : 5 septembre 2018
{: #whatsnewsecadvsept18}

De nouvelles fonctions ont été ajoutées à {{site.data.keyword.security-advisor_short}} qui est désormais disponible en tant que service bêta.  {{site.data.keyword.security-advisor_short}} centralise votre sécurité dans un tableau de bord {{site.data.keyword.Bluemix_notm}}. Outre la centralisation des informations, le service rassemble les informations de sécurité essentielles réparties sur des vignettes simples d'utilisation afin de signaler aisément les problèmes de sécurité. Le fait de cliquer sur une vignette active l'exploration en aval afin d'examiner les problèmes classés par priorité, l'historique et les détails liés à l'alerte. Pour résoudre le problème, effectuez une nouvelle exploration en aval pour obtenir tous les détails ainsi que des correctifs suggérés pour supprimer la menace et garantir la sécurité de votre environnement.

{{site.data.keyword.security-advisor_short}} devient rapidement votre console de référence vous permettant de centraliser, consulter et gérer les informations de sécurité dans votre environnement {{site.data.keyword.Bluemix_notm}}.

Dans cette version, nous implémentons les éléments suivants :
* Une API Findings
* La possibilité d'utiliser votre propre fournisseur
* Des mises à jour pour l'utilisation du tableau de bord

Et bien plus encore !

Pour commencer, consultez la documentation [{{site.data.keyword.security-advisor_short}}](/docs/services/security-advisor?topic=security-advisor-index).

### Présentation d'{{site.data.keyword.iva_full_notm}} (disponibilité générale)
Nouveau à compter du : 26 juin 2018
{: #whatsnewvoiceajune18}

[{{site.data.keyword.iva_full}}](https://cloud.ibm.com/catalog/services/voice-agent-with-watson)![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe") est désormais disponible. Vous pouvez
créer un agent vocal cognitif construit sur les services Watson que les clients peuvent appeler par téléphone. Avec l'intelligence artificielle Watson au niveau du réseau principal, votre agent vocal est capable de communiquer sur un mode conversationnel, gérant des interactions complexes et résolvant les appels client au sein de l'agent.

Cette version offre les nouvelles fonctions suivantes :

* Ajout d'emplacements de service Watson redondants pour la reprise après incident. 
* Modification des options de configuration avancées afin de personnaliser la façon dont vos agents vocaux transfèrent les appels, lisent les messages préenregistrés lors des appels et interagissent avec les services Watson.
* Configuration du nombre maximal de connexions simultanées dans votre plan de service standard.
* Connexion de vos agents vocaux aux fournisseurs de commutation automatique de canaux SIP, tels NetFoundry, Twilio, AT&T et d'autres fournisseurs de services ou homologues de {{site.data.keyword.iva_short}}.

Pour commencer, consultez la documentation [{{site.data.keyword.iva_short}}](/docs/services/voice-agent?topic=voice-agent-getting-started-tutorial).

### {{site.data.keyword.streaminganalyticsshort}} offre de nouveaux plans de service avec une infrastructure reposant sur un conteneur
Nouveau à compter du : 20 avril 2018
{: #whatsnewstreamanaapril18}

{{site.data.keyword.streaminganalyticsshort}} s'exécute désormais sur une infrastructure Kubernetes reposant sur un conteneur qui fournit des bénéfices en termes de sécurité et de disponibilité au service.
 
Vous pouvez accéder à cette nouvelle infrastructure reposant sur un conteneur à l'aide des [plans de service v2](/docs/services/StreamingAnalytics?topic=StreamingAnalytics-service_plans). Vous pouvez choisir le plan {{site.data.keyword.streaminganalyticsshort}} qui correspond le mieux à vos activités. Les plans de service v2 offrent les améliorations suivantes :
 
* [IBM Streams QSE with Docker](https://www-01.ibm.com/marketing/iwm/iwm/web/preLogin.do?source=swg-ibmistvi)![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe") : consultez le document [ Development Guide](https://developer.ibm.com/streamsdev/docs/cloud-beta-devguide/)![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe") pour apprendre à utiliser la nouvelle fonction Streams QSE avec RHEL 7 qui s'exécute dans un environnement Docker afin de compiler et déployer vos applications avec les nouveaux plans {{site.data.keyword.streaminganalyticsshort}} v2. 
* [{{site.data.keyword.streaminganalyticsshort}}API REST v2](https://cloud.ibm.com/apidocs/1939-streaming-analytics-v2#introduction)![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")
* [Nouvelles applications de démarrage et nouveaux exemples d'application](https://developer.ibm.com/streamsdev/docs/cloud-beta-samples/) ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")
* [Améliorations relatives à la haute disponibilité dans le service {{site.data.keyword.streaminganalyticsshort}}](/docs/services/StreamingAnalytics?topic=StreamingAnalytics-consistent-regions)
* [Fonctions d'identification de problème dans le service {{site.data.keyword.streaminganalyticsshort}} ](https://developer.ibm.com/streamsdev/2018/02/15/streaming-analytics-console-gives-ways-find-fix-errors-beta-plans/)![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")
* [Surveillance du comportement des opérateurs et traitement de n-uplet garanti dans le cloud](https://developer.ibm.com/streamsdev/2018/02/15/monitor-operators-behave-ensure-resource-optimization/)![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")

### {{site.data.keyword.iva_full_notm}} est à présent disponible en version bêta !
Nouveau à compter du : 16 mars 2018
{: #whatsnewvoiceamarch18}

Avec [{{site.data.keyword.iva_full}}](https://cloud.ibm.com/catalog/services/voice-agent-with-watson)![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe"), vous pouvez créer un agent vocal cognitif basé sur des services Watson que les clients peuvent appeler par téléphone. Avec l'intelligence artificielle Watson au niveau du réseau principal, votre agent vocal est capable de communiquer sur un mode conversationnel, gérant des interactions complexes et résolvant les appels client au sein de l'agent.

Cette version bêta offre les fonctions principales suivantes :

* Commencer plus facilement que jamais en créant un agent vocal et tous les services Watson requis en une seule étape.
* Transférer des appels à partir de votre agent vocal vers, par exemple, un agent du centre d'appel ou une toute autre destination.
* Collecter et analyser des données d'appel en configurant votre agent vocal pour qu'il transfère des événements d'enregistrement de détail d'appel, de transcription, ainsi que des événements de transformation {{site.data.keyword.conversationshort}} vers une base de données {{site.data.keyword.cloudant_short_notm}}.
* Surveiller l'utilisation du service et consulter les journaux d'appels sur la nouvelle page Utilisation. Vous pouvez visualiser des statistiques rapides pour le mois en cours, rechercher et filtrer des journaux d'appels et afficher des messages système pour chaque appel individuel.
* Etablir des appels sécurisés avec chiffrement de support en utilisant SIP TLS (URI SIPS) sur le port 5061 et le protocole SRTP (Secure Real-time Transport Protocol).
* Se connecter aux instances de service {{site.data.keyword.speechtotextfull}} et {{site.data.keyword.texttospeechfull}} dans d'autres espaces {{site.data.keyword.cloud_notm}} pour plus de flexibilité.

Pour commencer, consultez la documentation [{{site.data.keyword.iva_short}}](/docs/services/voice-agent?topic=voice-agent-getting-started-tutorial).

### Mises à jour apportées à {{site.data.keyword.visualrecognitionshort}}
Nouveau à compter du : 14 mars 2018
{: #whatsnewvisregmarch18}

Le service {{site.data.keyword.visualrecognitionfull}} a été mis à jour et de nouveaux entraînements de modèle de classifieur personnalisé sont à présent générés sous forme de discriminants basés sur un réseau de neurones d'apprentissage en profondeur. En raison du calcul supplémentaire requis pour générer ces modèles d'apprentissage en profondeur, les nouveaux modèles auront peut-être besoin de plus de temps pour s'entraîner.

Actuellement, les discriminants personnalisés existants peuvent continuer à être mis à jour et entraînés à nouveau et ils ne seront pas mis à jour vers ce nouveau format de modèle de machine d'apprentissage en profondeur.

### Mises à jour de {{site.data.keyword.streaminganalyticsshort}}
Nouveau à compter du : 14 février 2018
{: #whatsnewstreamanafeb18}

Les améliorations suivantes ont été apportées aux [plans bêta (entrée et bêta) améliorés](/docs/services/StreamingAnalytics/beta_plans.html#beta_plans) pour la console dans le service [{{site.data.keyword.streaminganalyticsshort}}](https://cloud.ibm.com/catalog/services/streaming-analytics){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe") :

* [Nouvelle fonction IBM Streams QSE pour Docker](https://www-01.ibm.com/marketing/iwm/iwm/web/preLogin.do?source=swg-ibmistvi){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe") : consultez le document [Beta Development Guide](https://developer.ibm.com/streamsdev/docs/cloud-beta-devguide/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe") pour apprendre à utiliser la nouvelle fonction Streams QSE avec RHEL 7 en cours d'exécution dans un environnement Docker afin de compiler et déployer vos applications avec les nouveaux plans bêta {{site.data.keyword.streaminganalyticsshort}}.
* [{{site.data.keyword.streaminganalyticsshort}}API REST v2](https://cloud.ibm.com/apidocs/1939-streaming-analytics-v2#introduction){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")
* [Nouvelles applications de démarrage et nouveaux exemples d'application](https://developer.ibm.com/streamsdev/docs/cloud-beta-samples/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")
* [Améliorations relatives à la haute disponibilité dans le service {{site.data.keyword.streaminganalyticsshort}}](/docs/services/StreamingAnalytics?topic=StreamingAnalytics-c_ha)
* [Nouvelles fonctions d'identification de problème dans la version bêta du service {{site.data.keyword.streaminganalyticsshort}} ](https://developer.ibm.com/streamsdev/2018/02/15/streaming-analytics-console-gives-ways-find-fix-errors-beta-plans/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")
* [Surveillance du comportement des opérateurs et traitement de n-uplet garanti dans le cloud](https://developer.ibm.com/streamsdev/2018/02/15/monitor-operators-behave-ensure-resource-optimization/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")

### Extension d'{{site.data.keyword.keymanagementservicelong_notm}} à la région Sydney
Nouveau à compter du : 31 janvier 2018
{: #whatsnewkeyprotectjan18}

A compter d'aujourd'hui, le service de gestion de clés de chiffrement {{site.data.keyword.keymanagementserviceshort}} est disponible dans la région Sydney. Sydney est la troisième région après la région Sud des Etats-Unis (Dallas) et la région Londres à offrir un statut de disponibilité générale pour les utilisateurs {{site.data.keyword.keymanagementserviceshort}}.

{{site.data.keyword.keymanagementserviceshort}} est un service de gestion de clés de chiffrement offrant une solution de gestion simple et économique pour les clés utilisées dans le but de chiffrer les données stockées dans {{site.data.keyword.Bluemix_notm}}. {{site.data.keyword.keymanagementserviceshort}} gère l'ensemble du cycle de vie des clés, de leur création à leur utilisation par une application, leur archivage et leur destruction, tout en imposant la répartition des tâches entre la gestion de données et la gestion de clés.

{{site.data.keyword.keymanagementserviceshort}} prend en charge BYOK (Bring-Your-Own-Key – chiffrement géré par les clients) avec des services de données {{site.data.keyword.IBM_notm}} applicables. BYOK permet aux utilisateurs d'importer des clés de chiffrement de type chaîne de confiance principales créées en interne pour améliorer la gestion de la sécurité de leurs données au repos sauvegardées dans {{site.data.keyword.Bluemix_notm}}.


### {{site.data.keyword.containershort_notm}} : Support Kubernetes 1.8.x
Nouveau à compter du : 19 janvier 2018
{: #whatsnewkubejan18}

Depuis novembre 2017, {{site.data.keyword.containershort_notm}} prenait en charge Kubernetes `1.8.x`. Nous sommes fiers d'annoncer que notre version par défaut de Kubernetes est désormais la version `1.8.6`.  Dans un futur proche, nous fournirons le support pour la version `1.9.x`.


### Nouveau service IBM Cloud Managed Database Server Beta
Nouveau à compter du : 30 novembre 2017
{: #whatsnewmngdbnov17}

Avec le nouveau service IBM Cloud Managed Database Server Beta, vous pouvez créer une instance de Microsoft SQL Server sur {{site.data.keyword.Bluemix_notm}}. Vous pouvez utiliser cette instance SQL Server comme tout autre système de gestion de base de données mais sans l'effort et les dépenses de configuration de matériel ou d'installation et de maintenance de logiciel.

Ce service offre les fonctions suivantes :
* Choix entre les versions de Microsoft SQL Server 2012, 2014, et 2016, Enterprise et Standard Editions
* Différentes configurations ou tailles prédéfinies afin de répondre à vos exigences de charge de travail applicative
* Gestion complète par IBM, y compris la surveillance, l'application de correctifs, la sauvegarde et la génération de rapports

### Nouveautés dans {{site.data.keyword.mobilepushshort}}
Nouveau à compter du : 26 octobre 2017
{: #whatsnewpushoct17}

Nous avons apporté plusieurs améliorations au service {{site.data.keyword.mobilepushshort}} au cours des derniers mois. Le service est désormais disponible dans la région de Francfort en plus de Dallas, Londres et Sydney. Détail des améliorations :

#### Surveillance
{: #monitoring-push}

Vous pouvez désormais suivre les performances des notifications push pour des périodes spécifiques, suivre le nombre de notifications envoyées et le nombre total de périphériques enregistrés. Vous pouvez également enregistrer des points d'ancrage Web afin d'être informé de tous les événements du cycle de vie d'une notification. Pour plus de détails, consultez les liens de documentation et articles de blogue :
* [Surveillance des notifications](/docs/services/mobilepush?topic=mobile-pushnotification-push_monitoring)
* [Réception d'alertes sur événements webhook](/docs/services/mobilepush?topic=mobile-pushnotification-webhook_event_based_notifications)
* [Surveillance dans IBM Push Notifications](https://www.ibm.com/blogs/bluemix/2017/03/monitoring-ibm-push-notifications/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")

#### Notifications Web
{: #webnotifications-push}

Le navigateur Web Safari est désormais pris en charge pour les notifications Web, ainsi que Firefox, Chrome, Chrome App et Extensions. Les logiciels SDK Web et des informations associées sont accessibles sur la page [{{site.data.keyword.Bluemix_notm}} Push Notifications Web SDK](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-javascript-webpush/blob/Doc/README.md){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

#### Dernières notifications Android et iOS
{: #mobilenotifications-push}

Prise en charge des devises pour les notifications iOS 11. Nous avons également intégré plusieurs améliorations concernant les notifications pour iOS10 et Android N.

* iOS10 – Prise en charge de Rich Media Notifications, des images, des boutons et des cartes dans les notifications interactives, ainsi que des chaînes localisées
* Android N – Notifications extensibles, notifications interactives et en mode silencieux, paramètres de voyant LED

Des détails supplémentaires sont accessibles dans la documentation sur les [notifications de média riche](/docs/services/mobilepush?topic=mobile-pushnotification-interactive-notifications), sur les [notifications interactives et en mode silencieux](/docs/services/mobilepush?topic=mobile-pushnotification-interactive-notifications) et sur l'[l'activation des notifications push avancées](/docs/services/mobilepush?topic=mobile-pushnotification-enabling-advanced-push-notifications).

#### Prise en charge APNs HTTP/2
{: #apnshttp2-push}

Apple a introduit la prise en charge du protocole HTTP pour les notifications Apple. Le service {{site.data.keyword.mobilepushshort}} prend désormais en charge le protocole HTTP/2. Avec cette prise en charge, le contenu des notifications peut être de 4 ko avec un débit accru. De plus, vous disposez d'une fonction de commentaire instantané. La prise en charge du certificat universel permet à l'application de se connecter aux environnements de bac à sable et de production.

#### Nouveau plan Lite
{: #liteplan-push}

Le service Lite Plan for {{site.data.keyword.mobilepushshort}} permet d'envoyer chaque mois gratuitement des notifications de 100 ko. Pour plus d'informations, voir l'article de blogue [Lite Plan For Push Notifications Service on {{site.data.keyword.Bluemix_notm}}](https://www.ibm.com/blogs/bluemix/2017/06/lite-plan-push-notifications-service-bluemix/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").



### Nouveautés de Mobile Analytics
Nouveau à compter du : 26 octobre 2017
{: #whatsnewmobileanaoct17}

Nous avons apporté des améliorations au service {{site.data.keyword.mobileanalytics_short}} au cours des derniers mois. Le service est désormais disponible dans les régions de Francfort et Sydney en plus de Dallas et Londres. Détail des améliorations :

#### Prise en charge du logiciel SDK Web
{: #mobileanawebsdk}

{{site.data.keyword.mobileanalytics_short}} est désormais un service Omni canal avec l'ajout de la prise en charge des analyses d'application Web. Pour plus de détails, accédez à [https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-web-analytics/](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-web-analytics/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

#### Intégration au service {{site.data.keyword.mobilefoundation_short}}
{: #mobileanamobilefoundation}

Le service {{site.data.keyword.mobilefoundation_short}} optimise désormais le service {{site.data.keyword.mobileanalytics_short}} pour l'analyse des applications, des utilisateurs et des performances. Les utilisateurs peuvent optimiser l'option d'exportation vers l'entrepôt Db2 pour générer des analyses d'adaptateur et des graphiques personnalisés. Vous trouverez des détails supplémentaires dans les articles de blog suivants :

* [Mobile Foundation Service integration with Mobile Analytics Service](https://www.ibm.com/blogs/bluemix/2017/08/mobile-foundation-service-integration-mobile-analytics-service-2/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")
* [Building custom charts by using IBM Bluemix Mobile Analytics service and IBM Mobile Foundation Service](https://mobilefirstplatform.ibmcloud.com/blog/2017/04/26/custom-charts-using-analytics-and-dashdb-analytics-service/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")
* [Building charts for Adapter analytics by using IBM Bluemix Mobile Analytics service and IBM Mobile Foundation Service](https://mobilefirstplatform.ibmcloud.com/blog/2017/04/26/adapter-analytics-using-analytics-and-dashdb-analytics-service/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")

#### Le conteneur boilerplate {{site.data.keyword.mobilefirst_notm}} inclut désormais {{site.data.keyword.mobileanalytics_short}}
{: #mobileanamobilefirst}

Mobile Services Boilerplate est un modèle qui fournit un ensemble de services mobiles pour une mise en route rapide des utilisateurs. Le service {{site.data.keyword.mobileanalytics_short}} fait désormais partie du conteneur boilerplate disponible dans le [catalogue](https://cloud.ibm.com/catalog/starters/mobilefirst-services-starter){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").


### Mises à jour de {{site.data.keyword.streaminganalyticsshort}}
Nouveau à compter du : 20 octobre 2017
{: #whatsnewstreamanaoct17}

* IBM Streams Runner for Apache Beam : Vous pouvez désormais développer des applications Beam en local dans votre environnement de développement Streams puis les envoyer au service {{site.data.keyword.streaminganalyticsshort}} dans {{site.data.keyword.Bluemix_notm}}. IBM Streams Runner for Apache Beam exécute des pipelines Beam dans un environnement Streams. Une application Beam lancée avec Streams Runner est convertie en un fichier SAB (Streams Application Bundle) que vous pouvez déployer dans {{site.data.keyword.streaminganalyticsshort}}. Consultez [IBM Streams Runner for Apache Beam dans Streaming Analytics](/docs/services/StreamingAnalytics?topic=StreamingAnalytics-gs_beamrunner) pour plus de détails.
* Vous pouvez trouver des informations dans les fichiers journaux encore plus rapidement. La console a été mise à jour pour améliorer l'affichage des graphiques d'application pour des topologies Python ou Java. Voir les [améliorations apportées à la console](https://developer.ibm.com/streamsdev/2017/10/13/enhancements-to-the-console/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

### IBM App Launch for {{site.data.keyword.Bluemix_notm}} Services
Nouveau à compter du : 12 octobre 2017
{: #whatsnewapplaunchoct17}

L'IBM App Launch for {{site.data.keyword.Bluemix_notm}} Services est une offre expérimentale qui vous permet de mesurer les expériences client en fournissant une plateforme pour créer des engagements ciblés sur différents échantillons représentatifs de votre audience. Le service App Launch fournit des analyses des préférences et points noirs des clients en tant que résultat de ces engagements, et vous aide à personnaliser l'application pour une meilleure expérience client.

Les propriétaires d'application peuvent désormais accélérer la distribution des innovations vers les applications mobiles en évitant les complexités du cycle de mise en production. Les service App Launch permet aux propriétaires d'application de lancer rapidement des fonctions dans des applications mobiles et d'en mesure l'impact en contrôlant l'audience ciblée. Le propriétaire d'application peut travailler avec le développeur d'applications afin de définir des indicateurs clé de performance pour les fonctions, mesurer l'impact et prendre des décisions de transfert ou d'annulation de fonction selon les commentaires en temps réel. Le service offre également la possibilité de tester plusieurs variantes des fonctions d'application, des composants de l'interface utilisateur,et des messages, et de prendre des décisions en fonction des commentaires.

Pour plus d'informations, voir le [Tutoriel d'initiation](/docs/services/app-launch?topic=services/app-launch-gettingstartedtemplate).

### Mises à jour apportées à {{site.data.keyword.ibmwatson_notm}} {{site.data.keyword.relationshipextractionshort}}
Nouveau à compter du : 4 octobre 2017
{: #whatsnewrelextoct17}

Une nouvelle fonction de personnalisation et de nouveaux modèles de langue sont disponibles pour utilisation avec {{site.data.keyword.relationshipextractionshort}}. Nouvelles langues : néerlandais, coréen et chinois simplifié, prise en charge pour WKS.

### Mise à jour du cluster {{site.data.keyword.containerlong_notm}}
Nouveau à compter du : 20 septembre 2017
{: #whatsnewkubesept17}

Vous pouvez désormais mettre à jour vos clusters vers la version la plus récente disponible de Kubernetes dans {{site.data.keyword.Bluemix_notm}}. A l'aide de l'interface graphique ou de l'interface CLI, mettez à jour votre document maître Kubernetes et vos noeuds worker vers Kubernetes 1.7 et bénéficiez des nouvelles fonctions et correctifs.

Pour plus d'informations, voir [Kubernetes 1.7 available in {{site.data.keyword.containerlong_notm}}](https://www.ibm.com/blogs/bluemix/2017/09/kubernetes-1-7-available-ibm-bluemix-container-service/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

### Nouveau service expérimental IBM Voice Agent with Watson
Nouveau à compter du : 15 septembre 2017
{: #whatsnewvasept17}

Avec le nouveau service expérimental {{site.data.keyword.iva_full}}, vous pouvez créer un agent vocal cognitif basé sur des services Watson que les clients peuvent appeler par téléphone. Avec l'intelligence artificielle Watson au niveau du réseau principal, votre agent vocal est capable de communiquer sur un mode conversationnel, gérant des interactions complexes et résolvant les appels client au sein de l'agent.

{{site.data.keyword.iva_short}} se connecte de façon transparente et orchestre les services Watson {{site.data.keyword.speechtotextshort}}, {{site.data.keyword.conversationshort}} et {{site.data.keyword.texttospeechshort}} afin de simuler une conversation en langage naturel. Chaque agent vocal se met automatiquement à l'échelle afin de gérer plusieurs appels simultanés. Dans cette édition expérimentale, vous pouvez personnaliser votre agent vocal en utilisant les fonctions clé suivantes :

* Importez l'exemple de boîte de dialogue {{site.data.keyword.conversationshort}} pour commencer, puis créez votre propre boîte de dialogue pour répondre aux besoins de votre société.
* Programmez le comportement de l'agent vocal depuis le service {{site.data.keyword.conversationshort}} en utilisant nos API. Vous contrôlez tous les éléments depuis le comportement d'interruption jusqu'à la fin de l'appel pour tout noeud de votre boîte de dialogue.
* Créez et gérez facilement plusieurs agents vocaux si vous souhaitez connecter différents numéros de téléphone aux agents cognitifs spécialisés pour différents sujets.
* Etendez les fonctions du service en connectant un moteur d'orchestration de services (SOE) afin de pouvoir utiliser des API tierces. Par exemple, le moteur SOE peut écouter les déclencheurs provenant du service {{site.data.keyword.conversationshort}} puis utiliser les API fournies afin de consulter les informations des systèmes existants ou fournir d'autres analyses.

Pour débuter, voir la documentation [Initiation à {{site.data.keyword.iva_short}}](/docs/services/voice-agent?topic=voice-agent-getting-started-tutorial).


### Mise à jour du service {{site.data.keyword.streaminganalyticsshort}} : La console inclut de nouvelles fonctions pour cerner les problèmes dans vos applications
Nouveau à compter du : 14 août 2017
{: #whatsnewstreamanaaug17}

Pour les applications Python et Java, l'emplacement des fichiers source est affiché en fonction de vos annotations @spl_note.

Pour des détails, voir [Latest improvements to the {{site.data.keyword.streaminganalyticsshort}}](https://developer.ibm.com/streamsdev/2017/08/14/latest-improvements-streaming-analytics-console/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

### IBM Cloud Monitoring est désormais disponible dans la région du Royaume-Uni
Nouveau à compter du : 01 août 2017
{: #whatsnewcloudmonitoraug17}

Utilisez le service {{site.data.keyword.monitoringlong}} pour étendre vos fonctions de collecte, conservation et analyse dans {{site.data.keyword.Bluemix_notm}} lors de l'utilisation de mesures.

* Alerte pour engager une action {{site.data.keyword.monitoringlong}} offre une API que vous pouvez utiliser pour définir des seuils de performance et être avisé lorsque ces seuils sont enfreints. Vous pouvez définir des règles d'alerte pour une instance de service ou d'application spécifique, ainsi que et des règles d'alerte concernant un ensemble d'instances. Lorsqu'une alerte est déclenchée, une notification peut vous être envoyée via un courrier électronique, un événement PagerDuty, une notification Webhook, ou une combinaison des trois.

* Ajout de métriques personnalisées. Le plan de service {{site.data.keyword.monitoringlong}} Premium propose des API que vous pouvez utiliser pour ajouter des métriques d'application et métier pertinentes à vos données Cloud Monitoring. Vous pouvez également les utiliser pour envoyer des données de métriques hors de {{site.data.keyword.IBM_notm}} Cloud vers le service {{site.data.keyword.monitoringlong}}.

* Construction de tableaux de bord réutilisables et interactifs. Grafana hébergé sur {{site.data.keyword.monitoringlong}} prend en charge l'élaboration de tableaux de bord personnalisés offrant un large éventail d'options de visualisation.  Vous pouvez rendre vos modèles de tableaux de bord dynamiques en utilisant des requêtes de métriques faisant appel à des variables.

* Accès à votre service via le catalogue {{site.data.keyword.Bluemix_notm}}. {{site.data.keyword.monitoringlong}} est disponible par le biais d'une vignette de service dans la section DevOps du catalogue {{site.data.keyword.Bluemix_notm}}.  Dans le cas de service {{site.data.keyword.containershort}} avec conteneur unique ou groupes de conteneurs, vous pouvez y accéder depuis l'interface utilisateur de {{site.data.keyword.Bluemix_notm}}.

* Sélection d'un plan de service adapté à vos besoins. Selon vos besoins, vous avez le choix entre le plan de service Lite et le plan de service Premium. Le plan de service Lite permet la collecte de métriques une fois par minute, leur conservation pendant 15 jours, et une alerte complémentaire.  Sinon, vous pouvez opter pour le plan Premium qui autorise une consommation plus élevée, une conservation plus longue des métriques, et l'accès aux API du service (par exemple, pour envoyer ou extraire des métriques du service {{site.data.keyword.monitoringlong}}). {{site.data.keyword.monitoringlong}} permet la collecte de métriques une fois par minute.  Le plan Lite conserve les métriques complètes pendant 15 jours. Le plan Premium les conserve pendant 45 jours.

Le service {{site.data.keyword.monitoringshort}} existant collectait les mesures à des fréquences définies par le service commençant à 30 secondes, et produisait un récapitulatif sur des fréquences de 1 heure au fil du temps. {{site.data.keyword.monitoringlong}} offre désormais une collecte pleine résolution à 1 minute.  Le plan Lite conserve les mesures pendant 15 jours.  Le plan Premium conserve les mesures pendant 45 jours.

Pour plus d'informations sur le service {{site.data.keyword.monitoringlong}}, voir la [documentation Initiation à la surveillance](/docs/services/cloud-monitoring?topic=cloud-monitoring-getting-started-with-ibm-cloud-monitoring) ou consultez la page [IBM Cloud Monitoring – Service Refresh with New Features![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")](https://www.ibm.com/blogs/bluemix/2017/07/ibm-cloud-monitoring-service-refresh-new-features/).


### IBM Cloud Log Analysis est désormais disponible dans la région du Sud des Etats-Unis
Nouveau à compter du : 31 juillet 2017
{: #whatsnewcloudlogjuly17}

{{site.data.keyword.loganalysisfull}} fournit des services de collecte de journaux et de recherche dans ceux-ci pour la plateforme {{site.data.keyword.Bluemix_notm}}, en collectant automatiquement des données d'application et de services {{site.data.keyword.Bluemix_notm}} depuis divers services {{site.data.keyword.Bluemix_notm}}. Utilisez le service {{site.data.keyword.loganalysisshort}} pour :

* Conserver les journaux aussi longtemps que nécessaire.  

    Les journaux sont stockés dans le stockage IBM Cloud.  Vous pouvez les téléchargez quand vous en avez besoin.

* Gérer la conservation de vos journaux et envoyez des données de journal en étant hors {{site.data.keyword.IBM_notm}} Cloud via la nouvelle API.

* Sélectionner le nombre de journaux sur lequel vous pourrez effectuer des recherches chaque jour.  

    Différents plans sont disponibles et peuvent vous permettre d'effectuer des recherches sur 500 Mo, 2 Go, 5 Go, et 10 Go de journaux par jour.

* Construire des tableaux de bord réutilisables et interactifs.

    Le plug-in Kibana hébergé de {{site.data.keyword.loganalysisshort}} fournit une prise en charge pour la génération de tableaux de bord personnalisés.

* Accédez à votre service via le catalogue {{site.data.keyword.Bluemix_notm}}.  

    Pour le service {{site.data.keyword.loganalysisshort}} avec des conteneurs uniques et de groupe, ainsi que les services {{site.data.keyword.IBM_notm}} Cloud Foundry, vous pouvez accéder au service depuis l'interface utilisateur de {{site.data.keyword.Bluemix_notm}}.

Pour plus d'informations sur le service {{site.data.keyword.loganalysisshort}}, voir [Initiation à {{site.data.keyword.loganalysisfull}}](/docs/services/CloudLogAnalysis?topic=cloudloganalysis-getting-started-with-cla).

### Système d'exploitation Brocade version 18.x pour le dispositif de routeur virtuel
Nouveau à compter du : 25 juillet 2017
{: #whatsnewvrajuly17}

La version 18.x du système d'exploitation Brocade est maintenant disponible pour le dispositif de routeur virtuel. Parmi les nouvelles fonctions, cette version apporte des correctifs à la brèche de sécurité de Spectre. 

Les nouvelles fonctions du dispositif de routeur virtuel de version 18.x sont exposées dans les rubriques suivantes :

* [Configuration d'un tunnel IPsec qui fonctionne avec des pare-feux de zone](/docs/infrastructure/virtual-router-appliance?topic=virtual-router-appliance-setting-up-an-ipsec-tunnel-that-works-with-zone-firewalls)
* [Configuration d'une interface VFP avec IPsec et des pare-feux de zone](/docs/infrastructure/virtual-router-appliance?topic=virtual-router-appliance-configuring-a-vfp-interface-with-ipsec-and-zone-firewalls)
* [Utilisation de NAT avec IPsec basé sur le préfixe](/docs/infrastructure/virtual-router-appliance/vra-nat.html)
* [Traitement des incidents liés à votre interface VFP](/docs/infrastructure/virtual-router-appliance/vra-vfp-troubleshooting.html)

Si vous réalisez une migration depuis Vyatta 5400, la meilleure façon d'effectuer une mise à niveau vers la version 18.x est de le faire à travers la [procédure normale](/docs/infrastructure/virtual-router-appliance?topic=virtual-router-appliance--upgrading-the-os) du rechargement complet du système d'exploitation.

Dans la mesure où il n'y a pas de mappage simple et individuel des fonctionnalités entre Vyatta 5400 et le dispositif de routeur virtuel, il est utile de créer une configuration de base pour le dispositif de routeur virtuel. WanClouds, un partenaire IBM, peut vous aider dans ce processus et vous guider lors de la création d'une fonctionnalité similaire à celle de Vyatta 5400 sur votre dispositif de routeur virtuel.

Pour en savoir plus sur les problèmes communs rencontrés lors de ce processus de mise à niveau, veuillez vous reporter à votre [documentation additionnelle](/docs/infrastructure/virtual-router-appliance/migration-issues.html#vyatta-5400-common-migration-issues).

### IBM dashDB for Analytics a été renommé
Nouveau à compter du : 18 juillet 2017
{: #whatsnewdb2wjuly17}

Le tableau suivant indique le nouveau nom :

| Nom précédent               | Nouveau nom                   | Date d'effet |
|-----------------------------|----------------------------|----------------|
| IBM dashDB for Analytics    | IBM Db2 Warehouse on Cloud | 18 juil. 2017  |
{: caption="Tableau 1. Changement de nom de service" caption-side="top"}

Pour obtenir la liste cumulative des mises à jour pour IBM Db2 Warehouse on Cloud and Db2 on Cloud, voir [What's New in Db2 Warehouse on Cloud and Db2 on Cloud](http://www.ibm.com/support/docview.wss?uid=swg21961758){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

### IBM Cloud Monitoring est désormais disponible dans la région du Sud des Etats-Unis
Nouveau à compter du : 17 juillet 2017
{: #whatsnewcloudmonitorjuly17}

Utilisez le service {{site.data.keyword.monitoringlong}} pour étendre vos fonctions de collecte, conservation et analyse dans {{site.data.keyword.Bluemix_notm}} lors de l'utilisation de mesures.

* Alerte pour engager une action {{site.data.keyword.monitoringlong}} offre une API que vous pouvez utiliser pour définir des seuils de performance et être avisé lorsque ces seuils sont enfreints. Vous pouvez définir des règles d'alerte pour une instance de service ou d'application spécifique, ainsi que et des règles d'alerte concernant un ensemble d'instances. Lorsqu'une alerte est déclenchée, une notification peut vous être envoyée via un courrier électronique, un événement PagerDuty, une notification Webhook, ou une combinaison des trois.

* Ajout de métriques personnalisées. Le plan de service {{site.data.keyword.monitoringlong}} Premium propose des API que vous pouvez utiliser pour ajouter des métriques d'application et métier pertinentes à vos données Cloud Monitoring. Vous pouvez également les utiliser pour envoyer des données de métriques hors de {{site.data.keyword.IBM_notm}} Cloud vers le service {{site.data.keyword.monitoringlong}}.

* Construction de tableaux de bord réutilisables et interactifs. Grafana hébergé sur {{site.data.keyword.monitoringlong}} prend en charge l'élaboration de tableaux de bord personnalisés offrant un large éventail d'options de visualisation.  Vous pouvez rendre vos modèles de tableaux de bord dynamiques en utilisant des requêtes de métriques faisant appel à des variables.

* Accès à votre service via le catalogue {{site.data.keyword.Bluemix_notm}}. {{site.data.keyword.monitoringlong}} est disponible par le biais d'une vignette de service dans la section DevOps du catalogue {{site.data.keyword.Bluemix_notm}}.  Dans le cas de service {{site.data.keyword.containershort}} avec conteneur unique ou groupes de conteneurs, vous pouvez y accéder depuis l'interface utilisateur de {{site.data.keyword.Bluemix_notm}}.

* Sélection d'un plan de service adapté à vos besoins. Selon vos besoins, vous avez le choix entre le plan de service Lite et le plan de service Premium. Le plan de service Lite permet la collecte de métriques une fois par minute, leur conservation pendant 15 jours, et une alerte complémentaire.  Sinon, vous pouvez opter pour le plan Premium qui autorise une consommation plus élevée, une conservation plus longue des métriques, et l'accès aux API du service (par exemple, pour envoyer ou extraire des métriques du service {{site.data.keyword.monitoringlong}}). {{site.data.keyword.monitoringlong}} permet la collecte de métriques une fois par minute.  Le plan Lite conserve les métriques complètes pendant 15 jours. Le plan Premium les conserve pendant 45 jours.

Le service {{site.data.keyword.monitoringshort}} existant collectait les mesures à des fréquences définies par le service commençant à 30 secondes, et produisait un récapitulatif sur des fréquences d'une heure au fil du temps. {{site.data.keyword.monitoringlong}} offre désormais une collecte pleine résolution à 1 minute.  Le plan Lite conserve les mesures pendant 15 jours.  Le plan Premium conserve les mesures pendant 45 jours.

Pour plus d'informations sur le service {{site.data.keyword.monitoringlong}}, voir [Initiation à la surveillance](/docs/services/cloud-monitoring?topic=cloud-monitoring-getting-started-with-ibm-cloud-monitoring) ou consultez la page [IBM Cloud Monitoring – Service Refresh with New Features![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")](https://www.ibm.com/blogs/bluemix/2017/07/ibm-cloud-monitoring-service-refresh-new-features/).

### Mise à niveau de {{site.data.keyword.contdelivery_short}}
Nouveau à compter du : 11 juillet 2017
{: #whatsnewcdjuly17}

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
{: #whatsnewcrjune17}

{{site.data.keyword.uccr_short}} est une solution de gestion des mises en production à l'échelle de l'entreprise qui prend en charge les outils de déploiement natifs cloud et sur site.

La version bêta de {{site.data.keyword.uccr_short}} fournit les fonctions clé suivantes :
* Utilisation des éditions pour gérer plusieurs plans et événements de déploiement, ainsi que pour collaborer sur les efforts de mise en production multi-équipes.
* Création d'événements pour toute activité liée à la mise en production et gestion de ces activités avec le calendrier.
* Importation de vos propres événements et mises en production.
* Personnalisation des événements de calendrier en fonction de votre organisation.
* Utilisation des tâches de type e-mail et Slack pour les notifications de mise en production.

### dashDB for Transactions a été renommé en {{site.data.keyword.Db2Hosted_notm}}
Nouveau à compter du : 14 juin 2017
{: #whatsnewdb2hjune17}

IBM {{site.data.keyword.DB2OnCloud_short}} est le nouveau nom de dashDB for Transactions. Dans le cadre de ce renommage l'ancien service auto-géré IBM {{site.data.keyword.DB2OnCloud_short}} sera également renommé, en IBM Db2 Hosted. Pour le moment, seuls les noms d'affichage sont mis à jour, les API et interfaces de ligne de commande restent inchangées.

### Mises à jour de {{site.data.keyword.sparks}} : le connecteur Stocator-S3 inclut la prise en charge du service {{site.data.keyword.cos_full_notm}} Cross Region (bêta)
Nouveau à compter du : 05 juin 2017
{: #whatsnewaasjune17}

Les utilisateurs {{site.data.keyword.sparks}} disposent désormais d'un accès pour effectuer des analyses sur les données stockées dans le service {{site.data.keyword.cos_full_notm}} Cross Region. Cette fonction est proposée en version bêta. {{site.data.keyword.cos_full_notm}} offre du stockage haute capacité et économique pour Analytics et autres applications ; ce stockage est évolutif, flexible et simple à utiliser.

Apache Spark accède aux données {{site.data.keyword.cos_full_notm}} via un connecteur de stockage basé sur la technologie Stocator, qui est implicitement conçu pour {{site.data.keyword.objectstorageshort}} et, de ce fait, plus rapidement que les connecteurs {{site.data.keyword.objectstorageshort}} existants. En tant qu'utilisateur, vous n'avez pas besoin de modifier ou de recompiler du code Apache Spark.

L'article de blogue [Access and Analyze data in IBM Cross Region Cloud Object Storage](https://www.ibm.com/blogs/bluemix/2017/06/access-analyze-data-ibm-cross-region-cloud-object-storage/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe") décrit l'utilisation des données {{site.data.keyword.cos_full_notm}} avec {{site.data.keyword.sparks}} sur {{site.data.keyword.Bluemix_notm}} et IBM Data Science Experience (DSx).

Si vous avez des questions ou des commentaires, contactez-nous à l'adresse [sparksrv@us.ibm.com](sparksrv@us.ibm.com). Nous apprécions vraiment tout retour.

### Nouveau plan évolutif disponible pour {{site.data.keyword.dashdbshort_notm}} for Transactions
Nouveau à compter du : 31 mai 2017
{: #whatsnewdb2wmay17}

Un nouveau plan est disponible pour {{site.data.keyword.dashdbshort}} for Transactions, capable de croître avec vos besoins de base de données. Le nouveau plan Flex permet de commencer avec un système de petite taille et d'augmenter la puissance et la capacité de stockage de ce système simplement et rapidement. {{site.data.keyword.dashdbshort}} for Transactions est 100 % compatible DB2 et fournit un accord sur les niveaux de licence de 99,95 % sur les plans de haute disponibilité.

### Nouvelles mises à jour du service {{site.data.keyword.mobilepush}} sur {{site.data.keyword.Bluemix_notm}}
Nouveau à compter du : 24 mai 2017
{: #whatsnewpushmay17}

Ci-après les nouvelles mises à jour disponibles pour le service {{site.data.keyword.mobilepush}} sur {{site.data.keyword.Bluemix_notm}}

**Plan Lite** : Nous présentons un nouveau plan Lite en plus du plan de base pour le service {{site.data.keyword.mobilepush}}. Conformément au nouveau plan, les utilisateurs peuvent envoyer gratuitement chaque mois jusqu'à plusieurs centaines de milliers de messages numériques. Dans le cas d'une mise à niveau du plan Lite vers le plan de base, l'utilisateur est facturé au-delà du million de messages numériques. Le comptage commence à partir du moment où le plan Lite est mis à niveau vers le plan de base.

**Surveillance** : Vous pouvez désormais obtenir des informations sur les notifications envoyées et les appareils enregistrés dans la console du service {{site.data.keyword.mobilepush}}. Vous pouvez également utiliser l'API REST pour le suivi des niveaux de message. Depuis la distribution des messages à la répartition des messages puis la réception des messages, les détails peuvent être obtenus via la configuration de webhooks.  Voir [Surveillance pour {{site.data.keyword.mobilepush}}](/docs/services/mobilepush?topic=mobile-pushnotification-push_monitoring).

**Notifications Web** : Vous pouvez désormais envoyer des notifications à des navigateurs Web Safari.

### Mises à jour de Secure Gateway
Nouveau à compter du : 24 mai 2017
{: #whatsnewsgmay17}

La dernière mises à jour de maintenance de Secure Gateway inclut des correctifs de bogues mineurs dans l'interface utilisateur et le gestionnaire d'API, la mise à jour de la documentation ; le client a été mis à jour vers la version 1.7.1. Le client Secure Gateway est désormais disponible sous AIX 7.1+ et prend en charge la connexion sortante via un proxy Squid.

### Mises à jour du service {{site.data.keyword.streaminganalyticsshort}} : Développez des applications Streams dans votre environnement de développement Python
Nouveau à compter du : 13 avril 2017
{: #whatsnewstreamanaapril17}

Auparavant, vous deviez installer une version locale d'IBM Streams pour développer des applications Python. Ce n'est plus le cas. Désormais, vous pouvez développer des applications avec Python dans votre environnement de développement préféré ou dans un bloc-notes interactif Jupyter.

Vous pouvez utiliser le contexte STREAMING_ANALYTICS_SERVICE pour soumettre une application Python au service {{site.data.keyword.streaminganalyticsshort}}. Le service {{site.data.keyword.streaminganalyticsshort}} requiert Python 3.5.

Vous pouvez créer des applications Python exemple à l'aide de blocs-notes Jupyter dans IBM Data Science Experience (DSX), et soumettre ces applications à l'instance {{site.data.keyword.streaminganalyticsshort}} directement depuis DSX. Consultez les exemples d'applications Python de traitement de flux dans des blocs-notes sur la page de la [communauté DSX](https://datascience.ibm.com/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

Pour plus d'informations sur les mises à jour du service {{site.data.keyword.streaminganalyticsshort}}, voir [{{site.data.keyword.streaminganalyticsshort}} updates: DSX integration and easier Python development](https://www.ibm.com/blogs/bluemix/2017/05/streaming-analytics-updates-dsx-integration-easier-python-development/){: new_window} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe").

### Mises à jour de {{site.data.keyword.sparks}} : Apache Spark 2.1 désormais pris en charge
Nouveau à compter du : 21 avril 2017
{: #whatsnewaasapril17}

{{site.data.keyword.sparkl}} introduit la prise en charge d'Apache Spark 2.1 pour la création d'algorithmes permettant d'exploiter les connaissances provenant de données complexes. Apache Spark 2.1 sera une aide précieuse pour la diffusion en flux structuré avec l'ajout d'une prise en charge des cotes d'alerte des événements et Kafka 0.10. Apache Spark 2.1 s'est également concentré sur l'augmentation de la stabilité et de la facilité d'utilisation dans les modules Spark SQL, SparkR et MLlib. Pour plus de détails sur Spark 2.1, voir [Spark Release 2.1.0](http://spark.apache.org/releases/spark-release-2-1-0.html).

Nous serons heureux de répondre aux questions concernant {{site.data.keyword.sparkl}} ou la version plus récente d'Apache Spark 2.1. Pour nous joindre : sparksrv@us.ibm.com.

### {{site.data.keyword.macm_short}} sera bientôt obsolète
Nouveau à compter du : 18 avril 2017
{: #whatsnewmacmapril17}

Depuis le 30 mars 2017, le service {{site.data.keyword.macm_long}} n'est plus disponible dans le catalogue {{site.data.keyword.Bluemix_notm}} et vous ne pouvez plus mettre à disposition de nouvelles instances MACM. Cependant, les instances existantes continueront à être prises en charge. Date de fin de support : 30 mars 2018. Supprimez vos instances de service {{site.data.keyword.macm_short}} (MACM) avant cette date. Nous encourageons les utilisateurs à migrer vers le concentrateur de contenu IBM Watson Content Hub. Watson Content Hub est disponible sur IBM Marketplace et offre aux utilisateurs une période d'essai gratuit de 30 jours. IBM Watson Content Hub fournit une fonctionnalité similaire à MACM avec de nouvelles fonctions supplémentaires telles que la gestion d'actifs, le balisage cognitif à l'aide des services IBM Watson, ainsi que le réseau de diffusion de contenu (CDN) afin de garantir une expérience optimale pour vos clients. IBM propose des engagements de service pour migrer du contenu depuis MACM vers Watson Content Hub.


### Mises à jour {{site.data.keyword.sparks}} : Bloc-notes désormais pris en charge dans Data Science Experience
Nouveau à compter du : 11 avril 2017
{: #whatsnewasadsxapril17}

Votre nouvelle plateforme pour utiliser des blocs-notes et Spark : Data Science Experience. Connectez-vous à [Data Science Experience](http://datascience.ibm.com/) et commencez à créer des blocs-notes et à partager votre expertise avec d'autres spécialistes des données.

Si vous utilisiez des blocs-notes dans {{site.data.keyword.sparks}}, vous pouvez les migrer vers Data Science Experience. Pour plus d'informations, voir la [documentation sur la migration des blocs-notes](/docs/services/AnalyticsforApacheSpark?topic=AnalyticsforApacheSpark-migrating-to-spark-212).



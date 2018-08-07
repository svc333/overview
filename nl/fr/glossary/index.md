---


copyright:
  years: 2016, 2018
lastupdated: "2018-07-31"


---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# Termes du glossaire de {{site.data.keyword.cloud_notm}} 
{: #glossary}

Ce glossaire comporte des termes et des définitions pour {{site.data.keyword.cloud}}.
{:shortdesc}

Les références croisées suivantes sont employées dans ce glossaire :

- *Voir* renvoie d'un terme non préféré vers le terme préféré ou d'une abréviation vers sa forme non abrégée.
- *Voir aussi* renvoie à un terme connexe ou opposé.

<!--If you do not want letter links at the top of your 
glossary, delete the text between these comment tags.
[A](#glossa)
[C](#glossc)
[D](#glossd)
[E](#glosse)
[F](#glossf)
[G](#glossg)
[H](#glossh)
[I](#glossi)
[J](#glossj)
[L](#glossl)
[M](#glossm)
[N](#glossn)
[O](#glosso)
[P](#glossp)
[R](#glossr)
[S](#glosss)
[T](#glosst)
[U](#glossu)
[V](#glossv)
[W](#glossw)
[Z](#glossz)

-->

## A
{: #glossa}

### accélération BLU
{: #x7470463}

Collection de technologies IBM Db2 conçue pour fonctionner en priorité avec un traitement de requête intelligence métier en lecture majoritaire. BLU Acceleration propose quatre avancées majeures dans la conception de bases de données : le traitement dynamique en mémoire et en colonnes, la compression interactive, le traitement vectoriel parallèle et la non prise en compte de données.

### action
{: #x2012974}

Un fragment de code peut être appelé explicitement ou exécuté en réponse à un événement. Voir aussi [flux](#x3129185), [appeler](#x2057232).

### adresse URL (Uniform Resource Locator)
{: #x2042491}

Adresse unique d'une ressource accessible dans un réseau, tel Internet. L'URL inclut le nom abrégé du protocole utilisé pour accéder à la ressource et les données utilisées par le protocole pour localiser la ressource. Voir aussi [domaine personnalisé](#x5728384), [domaine](#x2021210), [hôte](#x2002243), [route](#x2037338), [sous-domaine](#x2040080).

### affinité
{: #x2149238}

Deux instances de groupe de conteneurs ou plus s'exécutant sur un même noeud réseau. Voir aussi [anti-affinité](#x8888040).

### anti-affinité
{: #x8888040}

Deux instances de groupe de conteneurs ou plus s'exécutant sur différents noeuds réseau afin d'assurer une meilleure disponibilité pour une application. Voir aussi [affinité](#x2149238).

### API
{: #x2008805}

Voir [Interface de programme d'application](#x2000186).

### appel API léger
{: #x7690463}

Opération client qui lit des données. Les appels API légers utilisent moins de ressources que les appels API lourds, car ils exécutent une seule fonction. Voir aussi [appel API lourd](#x7690468).

### appel API lourd
{: #x7690468}

Opération client qui écrit, supprime ou insère des données. Les appels API lourds consomment davantage de ressources que les appels API légers, car ils affectent les données. Voir aussi [appel API léger](#x7690463).

### appeler
{: #x2057232}

Activer une action. Voir aussi [action](#x2012974).

### appli
{: #x4281528}

Application Web ou pour périphérique mobile. Voir aussi [application mobile](#x4258535), [application Web](#x2116500).

### application mobile
{: #x7636517}

Voir [application mobile](#x4258535).

### application mobile
{: #x4258535}

Application conçue pour une plateforme mobile. Tout comme les applications Web, les applis mobiles fournissent une fonctionnalité qui va au-delà de l'affichage statique d'informations, par exemple, en autorisant l'utilisateur à filtrer des nouvelles pratiquement en temps réel. Voir aussi [appli](#x4281528).

### application Web
{: #x7636628}

Voir [application Web](#x2116500).

### application Web
{: #x2116500}

Application à laquelle un navigateur Web peut accéder et qui fournit une fonctionnalité qui va au-delà de l'affichage statique d'informations, par exemple en autorisant l'utilisateur à interroger une base de données. Les composants les plus courants d'une application Web sont les pages HTML, les pages JSP et les servlets. Voir aussi [appli](#x4281528).

### artefact
{: #x2262995}

Entité utilisée ou générée par un processus de développement de logiciel ou de système. Exemples d'artefact : conceptions, exigences, fichiers source, plans, scripts, simulations, modèles, plans de test et fichiers exécutables binaires. Dans un contexte HTTP, les artefacts possèdent un URI et sont appelés ressources.

### authentification (AuthN)
{: #x2014567}

Processus de validation de l’identité d'un utilisateur ou d'un serveur.

### AuthN
{: #x7470446}

Voir [authentification](#x2014567).

### AuthZ
{: #x7470448}

Voir [autorisation](#x2014653).

### autorisation (AuthZ)
{: #x2014653}

En sécurité informatique, droit accordé à un utilisateur de communiquer avec ou d'utiliser un système informatique.

### autorité de certification (CA)
{: #x2016383}

Entreprise ou organisation tierce reconnue qui émet des certificats numériques. L'autorité de certification vérifie généralement l'identité des individus qui reçoivent un certificat unique. Voir aussi [certificat intermédiaire](#x3753781), [couche Secure Sockets Layer](#x2038004), [certificat racine digne de confiance](#x2042234).


## C
{: #glossc}

### CA
{: #x2015942}

Voir [autorité de certification](#x2016383).

### certificat intermédiaire
{: #x3753781}

Certificat subordonné émis par l'autorité de certification racine accréditée spécifiquement pour émettre des certificats serveur d'entité de fin. Le résultat est une chaîne de certificats qui débute à l'autorité de certification racine accréditée, continue avec le certificat intermédiaire et se finit par le certificat SSL émis pour l'organisation. Voir aussi [autorité de certification](#x2016383), [certificat racine digne de confiance](#x2042234).

### certificat racine digne de confiance
{: #x2042234}

Certificat signé par une autorité de certification de confiance. Voir aussi [autorité de certification](#x2016383), [certificat intermédiaire](#x3753781).


### clé privée
{: #x2034701}

Canevas algorithmique servant à chiffrer des messages que seule la clé publique correspondante pourra déchiffrer. La clé privée sert également à déchiffrer les messages encodés par la clé publique correspondante. Elle est conservée sur le système de l'utilisateur et protégée par un mot de passe.

### CLI
{: #x2008863}

Voir [interface de ligne de commande](#x2051424).

### client
{: #x2000644}

Programme logiciel ou ordinateur qui demande des services à un serveur. Voir aussi [hôte](#x2002243).

### cloud computing
{: #x3877850}

Plateforme informatique où les utilisateurs peuvent accéder à des ressources applicatives ou informatiques, tels que les services, n'importe où via leurs périphériques connectés. Une interface utilisateur simplifiée et/ou une interface de programme d'application (API) rendent l'infrastructure prenant en charge ces services transparente pour les utilisateurs.

### cloud dédié
{: #x8439199}

Environnement de Cloud Computing privé qui fournit l'infrastructure avec un matériel à service exclusif. Voir aussi [sans frontières](#x8439189).

### cloud hybride
{: #x4585327}

Environnement de Cloud Computing composé de plusieurs ressources publiques et privées.

### cloud local
{: #x8439194}

Environnement de Cloud Computing dans le centre de données du client. Le cloud local se trouve sur site et fournit une sécurité et un temps d'attente améliorés. Voir aussi [sans frontières](#x8439189).

### cloud mobile
{: #x4585344}

Infrastructure dans laquelle le stockage et le traitement des données des applications est déchargé depuis un périphérique mobile dans le cloud. Avec le Cloud Computing mobile, les applications ne sont pas limitées à un transporteur spécifiques mais sont accessibles via le Web.

### cloud privé
{: #x4585362}

Environnement de Cloud Computing dont l'accès est limité aux membres des réseaux d'une entreprise et de ses partenaires. Voir aussi [cloud public](#x4585370).

### cloud public
{: #x4585370}

Environnement de Cloud Computing dans lequel l'accès aux ressources normalisées, telles que l'infrastructure, le matériel à service partagé et les services, est disponible pour les abonnés, avec une facturation à la carte. Voir aussi [sans frontières](#x8439189), [cloud privé](#x4585362).

### composant
{: #x2017871}

Dans le contexte de la gestion de contrôle de source, regroupement d'artefacts associés dans un flux ou un espace de travail de référentiel. Un composant peut contenir un certain nombre de dossiers et de fichiers.

### compute
{: #x3723424}

Infrastructure ou ressources servant de base à la construction d'applications dans le cloud.

### connexion unique (SSO)
{: #x2213318}

Processus d'authentification par lequel un utilisateur peut accéder à plusieurs systèmes ou applications en saisissant un seul ID utilisateur et mot de passe.

### constituer
{: #x2067189}

Action de déployer une application, un service ou une instance à un emplacement prédéfini en vue de l'exécution ou du test avant le déploiement dans un environnement de production. Voir aussi [déploiement](#x2104544).

### conteneur
{: #x2010901}

Construction système qui permet aux utilisateurs d'exécuter simultanément des instances de système d'exploitation logiques distinctes. Les conteneurs utilisent des couches de systèmes de fichier pour réduire la taille des images et promouvoir la réutilisation. Voir aussi [image](#x2024928), [couche](#x2028320), [registre](#x2064940).

### conteneur boilerplate
{: #x7233930}

Modèle qui inclut une application, son environnement d'exécution et ses services prédéfinis associés, pour un domaine particulier.

### couche
{: #x2028320}

Version modifiée d'une image parent. Les images sont composées de couches, où la version modifiée est placée sur l'image parent, afin de créer la nouvelle image. Voir aussi [conteneur](#x2010901), [image](#x2024928).

### CSR
{: #x2140147}

Voir [demande de signature de certificat](#x3530521).

## D
{: #glossd}

### DEA
{: #x2019805}

Voir [agent DEA (Droplet Execution Agent)](#x7470348).

### déclencher
{: #x2239904}

Activer un déclencheur.

### déclencheur
{: #x2005384}

Mécanisme qui initie des actions. Les déclencheurs peuvent être exécutés explicitement par un utilisateur ou pour le compte d'un utilisateur par une source d'événements d'externe.

### demande de signature de certificat (CSR)
{: #x3530521}

Message électronique qu'une organisation envoie à une autorité de certification pour obtenir un certificat. La demande comprend une clé publique et est signée à l'aide d'une clé privée. L'autorité de certification retourne le certificat après l'avoir signé avec sa propre clé privée.

### démon
{: #x2019215}

Programme qui s'exécute sans surveillance et qui assure des fonctions continues ou périodiques (par exemple, le contrôle du réseau).

### déploiement
{: #x2104544}

Processus qui extrait la sortie d'une génération, prépare la sortie avec des propriétés de configuration, et installe le package à un emplacement prédéfini pour qu'il puisse être testé ou exécuté. Voir aussi [constituer](#x2067189).

### déploiement Blue-Green
{: #x7807335}

Technique de déploiement qui permet la distribution continue et réduit le temps d'indisponibilité en exécutant deux environnements de production identiques appelés Blue et Green. Alors que l'un des environnements (par exemple Blue) est l'environnement de production actif, l'autre (par exemple Green) peut être utilisé pour le test final et le déploiement. Une fois l'application déployée dans Green, Green devient l'environnement de production et Blue devient inactif. Voir aussi [déploiement red-black](#x8439181).

### déploiement red-black
{: #x8439181}

Technique de déploiement qui permet une distribution continue en activant le test, le développement et le déploiement synchronisés. Au départ, le développement est effectué dans un environnement inactif (black) alors que l'environnement actif continue d'accepter le trafic (red). Lorsque le déploiement commence, les deux environnements sont actifs (red-red) jusqu'à ce que le routage soit désactivé dans l'environnement de version précédent, auparavant actif, puis retiré (black) alors que le nouvel environnement est le seul environnement actif. Voir aussi [déploiement Blue-Green](#x7807335).

### DevOps
{: #x5784896}

Méthodologie logicielle qui intègre le développement d'une application et les opérations informatiques de sorte que les équipes puissent fournir du code plus rapidement au service de production et itérer en continu en fonction des réactions du marché.

### dimensionnement
{: #x2004442}

Augmentation de la capacité de la plateforme ou du système via l'ajout d'instances d'application ou de service.

### domaine
{: #x2021210}

Partie d'une hiérarchie de dénomination qui spécifie la route. Par exemple, exemple.com. Dans {{site.data.keyword.cloud_notm}}, les domaines sont associés à des organisations. Les objets de domaine ne sont pas directement liés aux applis. Voir aussi [domaine personnalisé](#x5728384), [hôte](#x2002243), [organisation](#x2032585), [route](#x2037338), [sous-domaine](#x2040080), [adresse URL](#x2042491).

### domaine personnalisé
{: #x5728384}

Partie personnalisée de l'adresse URL sélectionnée par l'utilisateur pour diriger les demandes vers l'application. Un domaine personnalisé constitue une partie de la route. Il peut s'agir d'un domaine partagé, d'un sous-domaine partagé ou d'un domaine et d'un hôte partagés. Voir aussi [domaine](#x2021210), [hôte](#x2002243), [route](#x2037338), [sous-domaine](#x2040080), [adresse URL (Uniform Resource Locator)](#x2042491).

### données d'identification
{: #x2018813}

Informations acquises pendant l'authentification et qui décrivent un utilisateur, des associations de groupe ou d'autres attributs d'identité en rapport avec la sécurité. Elles permettent d'exécuter des services tels que l'autorisation, l'audit ou la délégation. Par exemple, un ID utilisateur et un mot de passe sont des données d'identification qui permettent l'accès aux ressources réseau et système.

### Droplet Execution Agent (DEA)
{: #x7470348}

Composant Cloud Foundry permettant le déploiement d'applications.


## E
{: #glosse}

### environnement d'exécution
{: #x2391929}

Ensemble des ressources utilisées pour exécuter l'application. Voir aussi [module de démarrage](#x7470511).

### espace
{: #x2039442}

Sous-groupe dans une organisation {{site.data.keyword.cloud_notm}}. Les membres d'une organisation ont accès à un ou plusieurs de ses espaces, avec les droits associés à un rôle particulier (par exemple, développeur, responsable ou auditeur). Tout membre d'un espace peut voir les applis, mais seuls les membres disposant des droits de développeur peuvent créer des applis et ajouter des instances de service à l'espace. Les applis et les instances de service sont associées aux espaces. Voir aussi [organisation](#x2032585).

### espace de nom
{: #x2031005}

Nom unique qui identifie le référentiel d'images de votre organisation dans le registre {{site.data.keyword.cloud_notm}}. Voir aussi [image](#x2024928), [référentiel d'images privé](#x8439215).

### espace de travail
{: #x2096037}

Contexte contenant une collection d'artefacts qu'un utilisateur disposant des droits appropriés peut modifier.


## F
{: #glossf}

### fédérer
{: #x2763229}

Fusionner deux entités ou plus. Par exemple, le domaine enregistré d'une société peut être fédéré avec un IBMid.

### fichier d'archive Web (WAR)
{: #x2116506}

Format de fichier comprimé, défini par la norme Java EE, servant au stockage, dans un même fichier de toutes les ressources nécessaires à l'installation et à l'exécution d'une application Web.

### Fichier JAR
{: #x2406009}

Fichier d'archive Java.

### Fichier WAR
{: #x2406005}

Voir [fichier d'archive Web](#x2116506).


### flux
{: #x3129185}

Elément de code qui configure une source d'événements externe en vue de l'exécution d'événements déclencheurs. Voir aussi [action](#x2012974).

## G
{: #glossg}

### Go-heure
{: #x7470477}

Quantité de mémoire cumulée, en gigaoctets, utilisée par l'exécution de toutes les instances d'une application pour un pack de construction donné (par heure).

### gouttelette
{: #x7470343}

Dans Cloud Foundry, archive contenant une application, avec ses dépendances d'exécution et d'infrastructure, antérieure au déploiement sur le cloud.

### groupe de ressources
{: #x2161955}

Environnement, et contraintes, auxquels les instances de ressource contenues adhèrent. Un utilisateur peut être associé à un groupe de ressources pour activer la collaboration.

### GUID
{: #x2390457}

Voir [identificateur global unique](#x2390455).


## H
{: #glossh}

### hôte
{: #x2002243}

Ordinateur connecté à un réseau et qui fournit un point d'accès à celui-ci. L'hôte peut être un client, un serveur ou les deux à la fois. Voir aussi [client](#x2000644), [domaine personnalisé](#x5728384), [domaine](#x2021210), [route](#x2037338), [sous-domaine](#x2040080), [adresse URL](#x2042491).

### HTTPS
{: #x2193603}

Voir [protocole HTTPS (Hypertext Transfer Protocol Secure)](#x2237225).

### Hypertext Transfer Protocol Secure (HTTPS)
{: #x2237225}

Protocole Internet utilisé par les serveurs Web et les navigateurs Web pour transférer et afficher des documents hypermédia sur Internet de façon sécurisée.


## I
{: #glossi}

### IaaS
{: #x4585337}

Voir [infrastructure sous forme de services (IaaS)](#x4585332).

### IAM
{: #x2193801}

Voir [Identity and Access Management](#x7547040).

### identificateur global unique (GUID)
{: #x2390455}

Nombre déterminé de manière algorithmique identifiant de façon unique une entité dans un système.

### identificateur URI (URI)
{: #x2116436}

Adresse unique permettant d'identifier du contenu sur le Web. Le type d'URI le plus courant est l'adresse de page Web, qui correspond à une forme ou un sous-ensemble particulier d'URI appelé URL (Uniform Resource Locator). Un URI décrit généralement la manière d'accéder à la ressource, l'ordinateur contenant la ressource et l'emplacement de la ressource sur cet ordinateur.

### Identity and Access Management (IAM)
{: #x7547040}

Processus permettant de contrôler l'accès des utilisateurs autorisés aux données et aux applications et permettant également aux entreprises de se conformer aux différentes exigences réglementaires.

### image
{: #x2024928}

Système de fichiers et ses paramètres d'exécution utilisés dans l'environnement d'exécution de conteneur afin de créer un conteneur. Le système de fichiers est composé de plusieurs couches, associées lors de l'exécution, qui sont créées lorsque l'image est générée par des mises à jour successives. L'image ne conserve pas son état lors de l'exécution du conteneur. Voir aussi [image de base](#x5366487), [conteneur](#x2010901), [couche](#x2028320), [espace de nom](#x2031005), [image parent](#x8439210), [référentiel d'images privé](#x8439215), [registre](#x2064940).

### image de base
{: #x5366487}

Image qui ne possède pas d'image parent. Voir aussi [image](#x2024928), [image parent](#x8439210).

### image parent
{: #x8439210}

Image qui sert de base à une autre image. Par exemple, Ubuntu Linux est l'image parent de l'image IBM Liberty. Voir aussi [image de base](#x5366487), [image](#x2024928).

### infrastructure
{: #x2023472}

Architecture qui fournit une structure standard pour une application et, en général, des fonctionnalités extensibles.  L'infrastructure active et simplifie une implémentation cohérente de technologies complexes destinées au développement d'applications.

### infrastructure sous forme de services (IaaS)
{: #x4585332}

Distribution d'une infrastructure d'ordinateur, incluant les fonctionnalités de serveur, de réseau, de centre de données et de stockage sous forme de service externe.

### instance
{: #x2002531}

Entité composée de ressources réservées à une application ou à un service en particulier.

### interface de ligne de commande (CLI)
{: #x2051424}

Interface informatique dans laquelle les données d'entrée et de sortie sont de type texte.

### interface de programme d'application (API)
{: #x2000186}

Interface qui permet à un programme d'application écrit dans un langage de haut niveau d'utiliser des données ou des fonctions spécifiques du système d'exploitation ou d'un autre programme.

### Internet of Things (IoT)
{: #x6714341}

Réseau global de noeuds finals qui peuvent capturer ou générer des données. Par exemple, un smartphone, une montre connectée et un serveur back end peuvent communiquer ensemble, en s'envoyant des données, ou même avec d'autres appareils présents au sein du réseau.

### IoT
{: #x6714346}

Voir [Internet of Things](#x6714341).


## J
{: #glossj}

### JavaScript Object Notation (JSON)
{: #x3292165}

Format léger d'échange de données reposant sur la notation littérale des objets JavaScript. JSON est un format indépendant de tout langage de programmation, mais utilise les conventions de divers langages.

### jeton d'accès
{: #x2113001}

Valeur utilisée par le consommateur pour obtenir l'accès aux ressources protégées pour le compte de l'utilisateur, au lieu d'utiliser les données d'identification du fournisseur de services de l'utilisateur.

### JSON
{: #x4267096}

Voir [JavaScript Object Notation (JSON)](#x3292165).


## L
{: #glossl}

### LDAP
{: #x2481619}

Voir [Lightweight Directory Access Protocol (LDAP)](#x2028538).

### lecture majoritaire
{: #x7470468}

S'applique aux données modifiées de manière dynamique.

### lier
{: #x2000361}

Etablir une connexion entre des composants logiciels à travers un réseau au moyen d'un protocole déterminé. Dans des services Web, l'opération de liaison se produit lorsque le demandeur de service appelle ou lance une interaction avec le service au moment de l'exécution, grâce aux détails de liaison dans la description du service pour localiser, contacter et appeler ce dernier.

### Lightweight Directory Access Protocol (LDAP)
{: #x2028538}

Protocole ouvert utilisant TCP/IP pour fournir l'accès aux annuaires qui prennent en charge un modèle X.500 et pour lequel les ressources exigées par le protocole X.500 DAP (Directory Access Protocol) plus complexe ne sont pas requises. Par exemple, le protocole LDAP peut être utilisé pour localiser des personnes, des organisations et d'autres ressources dans un annuaire Internet ou Intranet.

### local
{: #x4561212}

S'applique à un logiciel installé et exécuté sur les ordinateurs d'un utilisateur ou d'une organisation.

### logiciel sous forme de services (SaaS)
{: #x4585386}

Modèle de déploiement selon lequel un logiciel incluant des processus métier, des applications d'entreprise et des outils collaboratifs est fourni aux clients en tant que service via le cloud.


## M
{: #glossm}

### Machine virtuelle
{: #x2043253}

Voir [machine virtuelle](#x2043165).

### machine virtuelle (VM)
{: #x2043165}

Implémentation logicielle d'une machine qui exécute des programmes comme une machine réelle. Voir aussi [serveur virtuel](#x2455638).

### magasin de données
{: #x2052849}

Emplacement, par exemple, système de base de données, fichier ou répertoire, où des données sont stockées.

### MBaaS
{: #x7044865}

Voir [système de back end mobile sous forme de services (MBaaS)](#x7044858).

### méthode HTTP
{: #x2024674}

Action utilisée par le protocole HTTP. Les méthodes HTTP comprennent les méthodes GET, POST et PUT.

### modèle
{: #x2041200}

Structure prédéfinie associée à un artefact.

### module de démarrage
{: #x7470511}

Modèle incluant des services prédéfinis et du code d'application configuré avec un pack de construction particulier. Un module de démarrage peut se composer d'un code d'application écrit dans un langage de programmation spécifique, ou d'une combinaison de code d'application et d'un ensemble de services. Voir aussi [exécution](#x2391929).


## N
{: #glossn}

### noeud final
{: #x2026820}

Adresse d'une interface de programme d'application ou d'un service dans un environnement. Une interface de programme d'application expose un noeud final et appelle en même temps les noeuds finaux pour d'autres services. Voir aussi [route](#x2037338).

### notification push
{: #x5599582}

Alerte signalant une modification ou une mise à jour au niveau d'une icône d'application mobile.


## O
{: #glosso}

### organisation
{: #x2032585}

Méthodologie de regroupement pour les utilisateurs dans {{site.data.keyword.cloud_notm}}. Les organisations permettent de gérer les quotas. Les utilisateurs d'une organisation partagent les quotas d'instances de service et de mémoire. Voir aussi [domaine](#x2021210), [espace](#x2039442).


## P
{: #glossp}

### PaaS
{: #x2029790}

Voir [plateforme sous forme de services](#x2029786).

### pack de construction
{: #x7233925}

Collection de scripts permettant de préparer le code à une exécution sur {{site.data.keyword.cloud_notm}}. Les packs de construction examinent les applications déployées, puis téléchargent et configurent les applications dépendantes.


### partage de fichiers
{: #x2022902}

Dans l'environnement {{site.data.keyword.cloud_notm}}, système de stockage de persistance où les utilisateurs stockent et partagent des fichiers. Dans IBM Containers, les utilisateurs peuvent monter des volumes Docker sur des partages de fichiers.

### plateforme sous forme de services (PaaS)
{: #x2029786}

Distribution d'une plateforme informatique comprenant des applications, des logiciels intermédiaires optimisés, des outils de développement, ainsi que les environnements d'exécution Java et Web 2.0, dans un environnement basé sur le cloud.

### portabilité du cloud
{: #x4585297}

Possibilité de déplacer des applications et des services entre des environnements de Cloud Computing publics ou privés ou depuis des fournisseurs de cloud différents.

### portée
{: #x2037763}

Dans le contexte de la gestion des identités, ensemble d'entités pouvant être affectées par une règle ou un ICA (informations sur le contrôle d'accès).

### protocole d'autorisation OAuth
{: #x6013335}

Protocole d'autorisation basé sur HTTP qui permet à des applications d'accéder à une ressource protégée pour le compte du propriétaire de la ressource, en créant une interaction d'approbation entre le propriétaire de la ressource, le client et le serveur de la ressource.

### push
{: #x2035465}

Envoyer des informations d'un serveur vers un client. Lorsqu'un serveur envoie du contenu, c'est lui qui lance la transaction, et non le client qui la demande.


## R
{: #glossr}

### référentiel d'images privé
{: #x8439215}

Combinaison du registre {{site.data.keyword.cloud_notm}} d'une organisation et de son espace de nom. Le référentiel d'images privé est utilisé lors du référencement d'une image dans une commande. Voir aussi [image](#x2024928), [espace de nom](#x2031005).

### région
{: #x2091391}

Territoire géographique défini. Une région peut être une zone avec un code postal spécifique, une petite ville, une grande ville, un état, un groupe d'états ou même un groupe de pays. Chaque région peut elle-même être un ensemble d'autres régions ou un ensemble de codes postaux formant la région.

### registre
{: #x2064940}

Référentiel public ou privé contenant des images utilisées pour créer des conteneurs. Voir aussi [conteneur](#x2010901),
[image](#x2024928).

### règle
{: #x2037526}

- Critère associant un déclencheur à une action, chaque exécution du déclencheur entraînant l'appel de l'action correspondante avec l'événement
déclencheur en entrée.
- Ensemble d'instructions conditionnelles permettant à des systèmes informatiques d'identifier des relations et d'exécuter les réponses automatisées correspondantes.

### Representational State Transfer (REST)
{: #x3220976}

Style architectural de logiciel pour les systèmes hypermédia répartis, comme le World Wide Web. Ce terme fait également référence à une interface simple qui utilise XML (ou YAML, JSON, texte en clair) sur HTTP sans couche de messagerie supplémentaire, telle que SOAP.

### réseau privé virtuel
{: #x2484351}

Voir [VPN](#x2043188).

### ressource
{: #x2004267}

Composant physique ou logique pouvant être mis à disposition ou réservé pour une application ou une instance de service.  Exemples de ressources : base de données,  comptes, limites de processeur, de mémoire ou de stockage.

### ressource privée
{: #x9439035}

Entrée visible seulement des propriétaires de compte et des comptes qui leur sont associés. Lorsque des ressources sont créées, elles sont privés par défaut. Voir aussi [ressource publique](#x9439040).

### ressource publique
{: #x9439040}

Entrée visible de tout le monde dans le catalogue {{site.data.keyword.cloud_notm}}. Des ressources publiques peuvent être créées par n'importe quel fournisseur (IBM ou fournisseurs tiers). Voir aussi  [ressource privée](#x9439035).

### REST
{: #x3220987}

Voir [Representational State Transfer (REST)](#x3220976).

### route
{: #x2037338}

Adresse URL utilisée pour diriger les demandes vers une application. Une route est composée d'un hôte facultatif (ou sous-domaine) et d'un domaine, spécifiés lorsqu'une application est déployée. Par exemple, dans la route monapp.exemple.com, monapp est l'hôte et exemple.com est le domaine. Une route peut être associée à une ou plusieurs applications. A moins qu'un domaine personnalisé ne soit spécifié, {{site.data.keyword.cloud_notm}} utilise un domaine partagé par défaut dans la route vers votre application. Voir aussi [domaine personnalisé](#x5728384), [domaine](#x2021210), [noeud final](#x2026820), [hôte](#x2002243), [sous-domaine](#x2040080), [adresse URL](#x2042491).


## S
{: #glosss}

### SaaS
{: #x4585391}

Voir [logiciel sous forme de services (SaaS)](#x4585386).

### sans frontières
{: #x8439189}

Qui appartient à une plateforme de développement ouverte, non propriétaire, incluant des modèles de déploiement de cloud public, de cloud dédié et de cloud local. Voir aussi [cloud dédié](#x8439199), [cloud local](#x8439194), [cloud public](#x4585370).

### section
{: #x2094743}

Section d'un progiciel qui définit une action spécifique à entreprendre sur le progiciel ou un ensemble de conditions dans lesquelles des actions doivent être entreprises sur le progiciel. Le progiciel complet est lui-même une section qui contient une hiérarchie composée de multiples sections différentes.

### Secure Sockets Layer (SSL)
{: #x2038004}

Protocole de sécurité garantissant la confidentialité de la communication. SSL permet aux application client/serveur de communiquer de manière à éviter l'écoute électronique, la contrefaçon et la falsification de messages. Voir aussi [autorité de certification](#x2016383).

### serveur virtuel
{: #x2455638}

Serveur partageant ses ressources avec d'autres serveurs pour épauler des applications. Voir aussi [machine virtuelle](#x2043165).

### service
{: #x2038343}

Extension de cloud qui fournit une fonctionnalité prête à l'emploi, telle qu'une base de données, une messagerie ou un logiciel Web pour exécuter du code ou des fonctionnalités de gestion ou de surveillance. Généralement, les services ne requièrent ni installation ni maintenance et peuvent être combinés pour créer des applications.

### service bêta
{: #x7470455}

Service qui n'est pas prêt pour la phase de production et qui se trouve au stade d'essai de développement. Voir aussi [service expérimental](#x7470450).

### service expérimental
{: #x7470450}

Service qui n'est pas prêt pour la production et qui peut être retiré à tout moment. Voir aussi [service bêta](#x7470455).


### service privé
{: #x7690456}

Service que seuls les membres d'une organisation {{site.data.keyword.cloud_notm}} spécifiée peuvent voir.

### session
{: #x2004539}

Temps entre le démarrage d'une appli sur un périphérique mobile et le moment où le produit d'assurance qualité est notifié pour commencer à collectionner le comportement de l'appli, les incidents et les problèmes.

### {{site.data.keyword.cloud_notm}}
{: #x7301758}

Plateforme à norme ouverte reposant sur le cloud qui permet de construire, de gérer et d'exécuter des applications de tout type, comme des périphériques Web, mobiles, de mégadonnées et intelligents. Ses capacités incluent Java, développement de back-end mobile, surveillance d'applications, ainsi que des fonctions de partenaires écosystème et open source &mdash; tous fournis en tant que service dans le cloud.

### SOR
{: #x2214822}

Voir [système d'enregistrement](#x6735061).

### sous-domaine
{: #x2040080}

Domaine intégré à un domaine de dimension supérieure. Voir aussi [domaine personnalisé](#x5728384), [domaine](#x2021210), [hôte](#x2002243), [route](#x2037338), [adresse URL](#x2042491).

### SSL
{: #x2483907}

Voir [couche Secure Sockets Layer (SSL)](#x2038004).

### SSO
{: #x3456450}

Voir [connexion unique (SSO)](#x2213318).

### sur site
{: #x6969434}

Voir [local](#x4561212).

### système de back end mobile sous forme de services (MBaaS)
{: #x7044858}

Modèle informatique qui permet de connecter des applications mobiles à des services Cloud Computing et de fournir des fonctionnalités telles que la gestion des utilisateurs, les notifications push et l'intégration à des réseaux sociaux via une interface de programme d'application et un kit de développement de logiciels unifiés.

### système d'engagement
{: #x6528306}

Système informatique intégrant les technologies qui encouragent l'interaction utilisateur via le courrier électronique, les systèmes de collaboration et la mise en réseau.  Un système d'engagement fait souvent appel aux technologies de cloud pour étendre l'utilité des systèmes d'enregistrement. Voir aussi [système d'enregistrement](#x6735061).

### système d'enregistrement (SOR)
{: #x6735061}

Système de stockage d'informations (tel qu'une base de données ou une application) qui stocke des enregistrements métier et automatise des processus standard. Voir aussi [système d'engagement](#x6528306).


## T
{: #glosst}

### tableau de bord
{: #x2363941}

Composant d'interface utilisateur qui fournit à l'utilisateur un récapitulatif détaillé des informations pertinentes provenant de diverses sources.

### tiers
{: #x2877945}

Qualifie un produit ou un service fourni par une société autre qu'IBM.


## U
{: #glossu}

### URI
{: #x2116461}

Voir [identificateur URI](#x2116436).

### URL
{: #x2042718}

Voir [adresse URL](#x2042491).


## V
{: #glossv}

### vignette
{: #x2092493}

Représentation visuelle d'une application en cours d'exécution qui présente un tableau de bord de statut.

### virtuel
{: #x2043123}

S'applique à un élément qui n'existe pas physiquement mais qui est simulé par l'intermédiaire d'un logiciel.

### VPN (réseau privé virtuel)
{: #x2043188}

Extension de l'intranet d'une entreprise sur l'infrastructure existante d'un réseau public ou privé. Un réseau privé virtuel assure la sécurisation des données qui sont envoyées entre deux noeuds finaux de sa connexion.


## W
{: #glossw}

### WAR
{: #x2844389}

Voir [fichier d'archive Web](#x2116506).


## Z
{: #glossz}

### zone de disponibilité
{: #x7018171}

Emplacement dans une région, où IBM Containers s'exécute.



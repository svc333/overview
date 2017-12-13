---

copyright:

  years: 2017

lastupdated: "2017-11-17"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:tip: .tip}

# Noms de ressource de cloud
{: #crn}

Les noms de ressource de cloud identifient de manière unique des ressources {{site.data.keyword.Bluemix_notm}}. Un nom de ressource de cloud est utilisé pour indiquer une ressource de manière à éviter toute ambiguïté et à garantir qu'elle est globalement unique, par exemple, dans des règles {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) et des services répertoriés dans le catalogue du cloud.

Un nom de ressource de cloud est constitué d'une concaténation de "segments" qui identifient hiérarchiquement la ressource, son emplacement et le service auquel elle appartient. Le délimiteur de segment ':' (c'est-à-dire le caractère deux-points). Tous les noms de ressource de cloud commencent par l'identificateur de segment 'crn'.


## Format d'un nom de ressource de cloud
{: #format}

Le format canonique de base d'un nom de ressource de cloud est le suivant :

**crn:[version](#version):[cname](#cname):[ctype](#ctype):[service-name](#service-name):[location](#location):[scope](#scope):[service-instance](#service-instance):[resource-type:resource](#resource-type)**


## version
{: #version}

Le segment `version` identifie la version du format de nom de ressource de cloud. Actuellement, la seule valeur de version de segment valide est **v1**.


## cname
{: #cname}

Le segment `cname` identifie l'instance cloud et est un identificateur alphanumérique identifiant de manière unique l'instance cloud qui contient la ressource. Un segment `cname` identifie véritablement un plan de contrôle indépendant auquel appartient la ressource identifiée. `cname` doit être `bluemix` pour les utilisateurs {{site.data.keyword.Bluemix_notm}}.


## ctype
{: #ctype}

Le segment `ctype` identifie le type d'instance cloud représentée par le segment `cname` spécifié.

>Les valeurs valides sont les suivantes :
  - public - Tous les services disponibles du catalogue public.
  - dedicated - Uniquement pour les environnements dédiés {{site.data.keyword.Bluemix_notm}}.
  - local - Tous les services déployés en local dans votre propre environnement.


## service-name
{: #service-name}

Le segment `service-name` identifie de manière unique une capacité (service, composant, produit) offerte par le cloud. Cette capacité peut être un service fourni par un utilisateur, tels lesservices répertoriés dans le catalogue {{site.data.keyword.Bluemix_notm}}, ou un composant d'architecture interne critique pour la fonctionnalité {{site.data.keyword.Bluemix_notm}}.

`service-name` indique le service auquel appartient la ressource et {{site.data.keyword.Bluemix_notm}} applique l'unicité globale des noms de service. `service-name` doit être composé de caractères alphanumériques, sans espaces ou caractères spéciaux autres que '-'.

Pour les services enregistrés dans le catalogue {{site.data.keyword.Bluemix_notm}}, `service-name` doit correspondre à l'un des services enregistrés dans le service de catalogue global{{site.data.keyword.Bluemix_notm}}. Il s'agit de la propriété `name` renvoyée par l'API du service de catalogue global {{site.data.keyword.Bluemix_notm}} `GET https://resource-catalog.bluemix.net/api/v1/{id}` pour l'instance de ressource correspondante ou le `service-name` affiché par l'interface de ligne de commande : `bx service offerings` dans la colonne `service`.


## location
{: #location}

La géographie/région/zone/la centre de données de cloud où réside la ressource.

`location` doit avoir l'une des valeurs suivantes :

### Global

 * `global`

### Géographies

 * `us`
 * `eu`
 * `cn`
 * `ap`

### Régions

 * `us-south`
 * `au-syd`
 * `eu-gb`
 * `eu-de`

### Centres de données


| | | | | |
|---|---|---|---|---|
| AMS01  | AMS03  | CHE01  | DAL01  |  DAL05  |
| DAL06  | DAL07  | DAL09  | DAL10  |  DAL12  |
| DAL13  | FRA02  | HKG02  | HOU02  |  LON02  |
| MEL01  | MEX01  | MIL01  | MON01  |  OSL01  |
| PAR01  | SJC01  | SJC03  | SAO01  |  SEA01  |
| SEO01  | SNG01  | SYD01  | TOK02  |  TOR01  |
| WDC01  | WDC04  | WDC06  | WDC07  |
{: caption="Tableau 1. Valeurs de centre de données valides" caption-side="top"}

Certaines ressources ne nécessitent pas de région (elles peuvent être considérées comme étant `globales`). Dans ce cas, le segment `region` est défini sur `global`.
{: tip}


## scope
{: #scope}

Le segment `scope` identifies la restriction ou le propriétaire de la ressource. Certaines ressources ne nécessitent pas de propriétaire (elles peuvent être considérées comme étant `globales`). Dans ce cas, le segment `scope` est vide (chaîne vide).

La valeur du segment `scope` doit être au format `{préfixePortée}`/`{id}`. `préfixePortée` correspond au format utilisé pour identifier le propriétaire ou la restriction. `id` correspond à l'identité du propriétaire ou de la restriction dans un format propre à `scopePrefix`.

| Type de portée | Préfixe de portée | Syntaxe | Exemple |
| --- | --- | --- | --- |
| Compte | a/`{account id}` | Compte dans lequel la ressource a été créée. | a/292558 |
| Organisation | o/`{org guid}` | L'organisation {{site.data.keyword.Bluemix_notm}} à laquelle la ressource a été affectée. | o/4716e2d1-35b7-431f-891a-b552bf0b3c66 |
| Espace | s/`{space guid}` | Espace {{site.data.keyword.Bluemix_notm}} auquel la ressource a été affectée. | s/48b3cdcd-e804-4398-9032-73065863ad7c |
{: caption="Tableau 2. `scope` usage" caption-side="top"}

`account id` doit être l'ID de compte IBM ({{site.data.keyword.Bluemix_notm}} et comptes Softlayer liés).


## service-instance
{: #service-instance}

Le segment `service-instance` identifie l'instance de service de manière unique. Le format du segment `service-instance` varie en fonction du service. Chaque service doit documente le format de son segment `service_instance` dans le cadre de ses métadonnées de service. Certains services n'ont pas d'instances car l'instance est globale et, dans ce cas, `service-instance` sera vide.

`service-instance` doit être composé de caractères alphanumériques minuscules, sans espaces ou caractères spéciaux autres que '-' et '/'.

Par exemple, un outil DevOps de suivi et de planification d'éléments de travail peut avoir un simple ID d'instance `GUID` ("1234-5678-9012-3456") tandis que le composant de règle d'un service de groupe de mise à l'échelle automatique peut utiliser une convention de dénomination hiérarchique et avoir un segment `service-id` comme suit :

>`c7a27f55-d35e-4153-b044-8ca9155fc467/my-test-asg1/my-scaleout-policy`


## resource-type, resource
{: #resource-type}

La valeur des segments `resource-type` et `resource` varie en fonction du service. Un service doit documenter les `types de ressource` pris en charge et le format de `resource` dans le cadre de ses métadonnées de service.

Par exemple, une image dans le conteneur de réception client d'un service Object Storage peut avoir un segment `resource-type` avec la valeur `object` et un segment `resource_ value` avec la valeur `CustomerReceipts/clientdinner.png`. 

`resource-type` doit être composé de caractères alphanumériques minuscules, sans espaces ou caractères spéciaux autres que '-'. Un service peut décider que le segment `resource-type` est facultatif et, auquel cas, le segment sera vide.


## Exemples de nom de ressource de cloud
{: #crn_examples}

Voici une liste d'exemple de nom de ressource de cloud.

| Exemple | Valeur |
| --- | --- |
| Conteneur | `crn:v1:bluemix:public:containers-kubernetes:us-south:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:8042b2a8af6a4a5cbf6dbe09e07311d2:worker:kube-hou02-pa8042b2a8af6a4a5cbf6dbe09e07311d2-w1:`|
| Groupe de ressources | `crn:v1:bluemix:public:resource-controller: global:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:resource-group:59bcbfa6ea2f006b4ed7094c1a08dcdd` |
| Instance de service | `crn:v1:bluemix:public:cloud-object-storage:global:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:1a0ec336-f391-4091-a6fb-5e084a4c56f4::` |
| Compartiment | `crn:v1:bluemix:public:cloud-object-storage:global:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:1a0ec336-f391-4091-a6fb-5e084a4c56f4:bucket:mybucket` |
{: caption="Tableau 3. Exemples de nom de ressource de cloud" caption-side="top"}



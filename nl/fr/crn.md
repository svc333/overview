---

copyright:

  years: 2017, 2019

lastupdated: "2019-05-06"

keywords: crn, cloud resource name

subcollection: overview

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:tip: .tip}

# Noms de ressource de cloud
{: #crn}

Les noms de ressource de cloud identifient de manière unique des ressources {{site.data.keyword.Bluemix_notm}}. Un nom de ressource de cloud est utilisé pour indiquer une ressource de manière à éviter toute ambiguïté et à garantir qu'elle est globalement unique, par exemple, dans des règles {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) et des services répertoriés dans le catalogue du cloud.

Un nom de ressource de cloud est constitué d'une concaténation de "segments" qui identifient hiérarchiquement la ressource, son emplacement et le service auquel elle appartient. Le caractère deux-points (':') est défini comme délimiteur de segment. Tous les noms de ressource de cloud commencent par l'identificateur de segment `crn`.


## Format CRN (nom de ressource de cloud)
{: #format-crn}

Le format canonique de base d'un nom de ressource de cloud est le suivant :

`crn:version:cname:ctype:service-name:location:scope:service-instance:resource-type:resource`


## version
{: #version-crn}

Le segment `version` identifie la version du format de nom de ressource de cloud. Actuellement, la seule valeur de segment de version valide est `v1`.


## cname
{: #cname-crn}

Le segment `cname` identifie l'instance cloud et est un identificateur alphanumérique identifiant de manière unique l'instance cloud qui contient la ressource. Un segment `cname` identifie véritablement un plan de contrôle indépendant auquel appartient la ressource identifiée. La valeur du segment `cname` doit être `bluemix` pour les utilisateurs {{site.data.keyword.Bluemix_notm}}.


## ctype
{: #ctype-crn}

Le segment `ctype` identifie le type d'instance de cloud représentée par le segment `cname` spécifié.

 Les valeurs valides sont les suivantes :
  - `public` - Tous les services disponibles du catalogue public
  - `dedicated` - Uniquement pour les environnements dédiés {{site.data.keyword.Bluemix_notm}}
  - `local` - Tous les services déployés en local dans votre propre environnement


## service-name
{: #service-name-crn}

Le segment `service-name` identifie de manière unique une capacité (service, composant, produit) offerte par le cloud. Cette capacité peut être un service fourni par un utilisateur, tels les services répertoriés dans le catalogue {{site.data.keyword.Bluemix_notm}}, ou un composant d'architecture interne critique pour la fonctionnalité {{site.data.keyword.Bluemix_notm}}.

Le segment `service-name` indique le service auquel appartient la ressource et {{site.data.keyword.Bluemix_notm}} applique l'unicité globale des noms de service. Le segment `service-name` doit être composé de caractères alphanumériques, sans espaces ou caractères spéciaux autres que '-'.

Pour les services enregistrés dans le catalogue {{site.data.keyword.Bluemix_notm}}, le segment `service-name` doit correspondre à un des services enregistrés dans le service {{site.data.keyword.Bluemix_notm}} Global Catalog. Il s'agit de la propriété `name` renvoyée par l'API du service {{site.data.keyword.Bluemix_notm}} Global Catalog `GET https://globalcatalog.cloud.ibm.com/api/v1/{id}` pour l'instance de ressource correspondante ou de la valeur `service-name` affichée par l'interface de ligne de commande `ibmcloud service offerings` dans la colonne `service`.


## location
{: #location-crn}

Secteur géographique/région/zone/centre de données de cloud où réside la ressource.

Le segment `location` doit avoir l'une des valeurs suivantes :

### Global
{: #global-crn}

 * `global`

### Géographies
{: #geos-crn}

 * `us`
 * `eu`
 * `cn`
 * `ap`

### Régions
{: #regions-crn}

 * `us-south`
 * `us-east`
 * `au-syd`
 * `eu-gb`
 * `eu-de`
 * ` jp-tok `

### Centres de données
{: #dc-crn}

 * ` AMS01  `
 * ` AMS03  `
 * ` CHE01  `
 * ` DAL01  `
 * `  DAL05  `
 * ` DAL06  `
 * ` DAL07  `
 * ` DAL09  `
 * ` DAL10  `
 * `  DAL12  `
 * ` DAL13  `
 * ` FRA02  `
 * ` HKG02  `
 * ` HOU02  `
 * `  LON02  `
 * ` MEL01  `
 * ` MEX01  `
 * ` MIL01  `
 * ` MON01  `
 * `  OSL01  `
 * ` PAR01  `
 * ` SJC01  `
 * ` SJC03  `
 * ` SAO01  `
 * `  SEA01  `
 * ` SEO01  `
 * ` SNG01  `
 * ` SYD01  `
 * ` TOK02  `
 * `  TOR01  `
 * ` WDC01  `
 * ` WDC04  `
 * ` WDC06  `
 * ` WDC07  `

Pour certaines ressources, aucune région n'est requise car elles peuvent être considérées comme étant globales. Dans ce cas, le segment `region` a la valeur `global`.
{: tip}


## scope
{: #scope-crn}

Le segment `scope` identifies la restriction ou le propriétaire de la ressource. Certaines ressources ne nécessitent pas de propriétaire (elles peuvent être considérées comme étant `globales`). Dans ce cas, le segment `scope` est vide (chaîne vide).

La valeur du segment `scope` doit être au format `{scopePrefix}`/`{id}`. `scopePrefix` correspond au format utilisé pour identifier le propriétaire ou la restriction. `id` correspond à l'identité du propriétaire ou de la restriction dans un format propre à `scopePrefix`.

| Type de portée | Préfixe de portée | Syntaxe | Exemple |
| --- | --- | --- | --- |
| Compte | a/`{account id}` | Compte dans lequel la ressource a été créée. | `a/292558` |
| Organisation | o/`{org guid}` | Organisation {{site.data.keyword.Bluemix_notm}} à laquelle la ressource a été affectée. | `o/4716e2d1-35b7-431f-891a-b552bf0b3c66` |
| Espace | s/`{space guid}` | Espace {{site.data.keyword.Bluemix_notm}} auquel la ressource a été affectée. | `s/48b3cdcd-e804-4398-9032-73065863ad7c` |
{: caption="Tableau 1. Utilisation de `scope`" caption-side="top"}



## service-instance
{: #service-instance-crn}

Le segment `service-instance` identifie l'instance de service de manière unique. Le format du segment `service-instance` varie en fonction du service. Chaque service doit documenter le format de son segment `service_instance` dans le cadre de ses métadonnées de service. Certains services n'ont pas d'instance car l'instance est globale et, dans ce cas, la zone `service-instance` est vide.

L'élément `service-instance` doit être composé de caractères alphanumériques minuscules. Il ne doit pas inclure d'espace ou de caractères spécial à l'exception des caractères '-' et '/'.

Par exemple, un outil DevOps de suivi et de planification d'éléments de travail peut avoir un simple ID d'instance `GUID` ("1234-5678-9012-3456") tandis que le composant de règle d'un service de groupe de mise à l'échelle automatique peut utiliser une convention de dénomination hiérarchique et avoir un segment `service-id` comme suit :

>`c7a27f55-d35e-4153-b044-8ca9155fc467/my-test-asg1/my-scaleout-policy`

Vous pouvez également vous procurer un nom de ressource de cloud à partir d'une ressource {{site.data.keyword.Bluemix_notm}} à l'aide de la commande d'interface de ligne de commande suivante :
```
ibmcloud resource service-instance
```
{: codeblock}

## resource-type, resource
{: #resource-type-crn}

La valeur des segments `resource-type` et `resource` varie en fonction du service. Un service doit documenter les segments `resource types` pris en charge et le format du segment `resource` dans le cadre de ses métadonnées de service.

Par exemple, une image dans le conteneur de réception client d'un service Object Storage peut avoir un segment `resource-type` de valeur `object` et un élément `resource` de valeur `CustomerReceipts/clientdinner.png`.

Le segment `resource-type` doit être composé de caractères alphanumériques, sans espaces ou caractères spéciaux autres que '-'. Un service peut décider que le segment `resource-type` est facultatif et auquel cas, le segment est laissé vide.


## Exemples de nom de ressource de cloud
{: #crn_examples}

Le tableau suivant fournit une liste d'exemples CRN :

| Exemple | Valeur |
| --- | --- |
| Agent Kubernetes | `crn:v1:bluemix:public:containers-kubernetes:us-south:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:8042b2a8af6a4a5cbf6dbe09e07311d2:worker:kube-hou02-pa8042b2a8af6a4a5cbf6dbe09e07311d2-w1` |
| Groupe de ressources | `crn:v1:bluemix:public:resource-controller: global:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:resource-group:59bcbfa6ea2f006b4ed7094c1a08dcdd` |
| Instance de service | `crn:v1:bluemix:public:cloud-object-storage:global:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:1a0ec336-f391-4091-a6fb-5e084a4c56f4::` |
| Compartiment | `crn:v1:bluemix:public:cloud-object-storage:global:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:1a0ec336-f391-4091-a6fb-5e084a4c56f4:bucket:mybucket` |
{: caption="Tableau 2. Exemples CRN" caption-side="top"}

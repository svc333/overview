---

copyright:
  years: 2018, 2019
lastupdated: "2019-05-13"

keywords: HA, failover, DR

subcollection: overview

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:pre: .pre}
{:table: .aria-labeledby="caption"}
{:note: .deprecated}


# Comment garantir une disponibilité permanente ?
{: #zero-downtime}

Votre stratégie globale est importante. Vous pouvez sélectionner un emplacement ou un centre de données spécifique pour le déploiement de vos données dans la zone géographique appropriée à vos clients. 
{:shortdesc}

Les services de plateforme {{site.data.keyword.Bluemix}} sont auto-gérés. Autrement dit, les emplacements dans lesquels vous déployez votre application peuvent répartir les charges de travail dans plusieurs centres de données. Vous pouvez également mettre en place un système de basculement. Ainsi, votre application est toujours opérationnelle pour vos clients. Pour vos ressources d'infrastructure, vous pouvez sélectionner des centres de données individuels dans lesquels les ressources sont déployées. 

Toutes les ressources {{site.data.keyword.Bluemix_notm}} sont hébergées dans des centres de données répartis dans le monde entier. La haute disponibilité et la reprise après incident ne sont pas identiques dans tous les services. Ainsi, les type de haute disponibilité et de reprise après incident disponibles dépendent du service que vous utilisez.  

## Reprise après incident
{: #disaster-recovery}

Le processus de reprise après incident est utilisé suite à une grave défaillance ou suite à une perte de disponibilité à un emplacement unique. Pour s'assurer que ce processus est en place, il est nécessaire de déployer plusieurs environnements {{site.data.keyword.Bluemix_notm}} à plusieurs emplacements afin d'éviter des points de défaillance uniques. Ces environnements peuvent être une combinaison de plateformes publiques, dédiées ou locales.  

### Plan de reprise après incident 
{: #dr-plan}

{{site.data.keyword.Bluemix_notm}} respecte les exigences de planification en cas de sinistre. Chaque application dispose d'un plan vous permettant d'effectuer la reprise ou le redémarrage après un sinistre. Cette opération s'effectue à partir des sauvegardes électroniques d'un centre de récupération ou d'autres sites permettant la restauration de données informatiques. Avant tout sinistre potentiel, le plan de reprise après incident permet de répondre aux exigences d'hébergement et des systèmes pour les fonctions de sauvegarde hors site, de connectivité réseau, de logiciel et de matériel.

La liste suivante présente les exigences du plan de reprise après incident :

- Pour l'équilibrage de charge, vous disposez d'un document décrivant comment le service de calcul reste disponible. 
- Lorsqu'un basculement survient sur plusieurs sites, le plan de reprise après incident doit décrire les actions à l'origine du basculement et garantir le redémarrage. 
- Il doit définir le mode de fonctionnement de la solution et indiquer la perte de données. 
- Il doit garantir que le temps d'indisponibilité tolérable maximal est respecté. De plus, il doit être stocké dans la base de données de plan de reprise après incident.  
- Il définit les contrôles de sécurité pour l'exécution en mode Sinistre s'ils sont différents de ceux utilisés lors de l'exécution en mode Production. 

### Gestion du plan de reprise après incident 
{: #dr-plan-mgmt}

{{site.data.keyword.Bluemix}} respecte les exigences suivantes : 

- Le plan de reprise après incident doit être mis à jour après toute modification d'infrastructure importante, édition d'application importante et après tout test. 
- Il doit être approuvé manuellement. 

## Emplacements pour déploiement de ressources 
{: #ov_intro_reg}

Vous pouvez créer des instances d'application et de service dans différents emplacements avec la même infrastructure {{site.data.keyword.cloud_notm}} pour la gestion des applications et la même vue détaillée de l'utilisation pour la facturation. Vous pouvez déployer vos applications à l'emplacement le plus proche de vos clients pour réduire les temps d'attente pour vos applications. 

Pour des raisons de sécurité, vous pouvez également sélectionner l'emplacement de conservation des données d'application. Lorsque vous construisez des applications sous un ou plusieurs emplacements et que l'un d'eux devient indisponible, les applications situées aux autres emplacements continuent de fonctionner. Votre franchise de ressources est la même dans tous les emplacements que vous utilisez. Pour plus d'informations sur les ressources de plateforme et les emplacements où elles sont disponibles, voir [Disponibilité des services](/docs/resources?topic=resources-services_region).

L'équilibrage de charge global pour la console {{site.data.keyword.cloud_notm}} garantit que si l'emplacement géographique le plus proche n'est pas disponible, la console affiche les informations de l'emplacement le plus proche suivant. De la sorte, vous pouvez toujours accéder à la console sans avoir à effectuer d'action pour obtenir les ressources dont vous avez besoin.

Par défaut, vous pouvez afficher dans la console toutes les ressources de tous les emplacements de la liste de ressources. Si vous souhaitez afficher et utiliser les ressources d'un emplacement spécifique, développez le menu **Emplacement** puis sélectionnez un emplacement dans la liste. En développant un emplacement géographique spécifique, vous pouvez choisir d'effectuer le filtrage par centre de données ou région individuel ou par zone : 

Une *géographie* est une zone géographique ou un corps politique plus grand qui contient une ou plusieurs régions. Certains services sont pris en charge au niveau géographie entre les régions et gèrent de manière transparente la réplication et les flux des données entre les régions. Par exemple, les données de la géographie UE pour {{site.data.keyword.cos_full_notm}} peut répliquer des données dans plusieurs centres de données au sein des pays de l'Union européenne.  
   * Une *métropole* est un nom de ville spécifique au sein de la zone géographique donnée. Par exemple, Dallas est une métropole dans la géographie d'Amérique du Nord. 
      * Un *centre de données* est l'emplacement physique des serveurs qui fournissent des services de cloud. Vous pouvez identifier des centres de données dans une géographie étendue comme des options qui utilisent le nom de géographie plus un nombre. 
      * Une *région* est un territoire géographique défini. Une région peut être une zone avec un code postal spécifique, une petite ville, une grande ville, un état, un groupe d'états ou même un groupe de pays. Vous pouvez différencier les centres de données des régions dans la liste grâce aux numéros qui sont utilisés pour identifier les centres de données. 
         * Une *zone* est un domaine avec des points de défaillance indépendant conçu pour fournir de l'assistance grâce à une tolérance aux pannes améliorée et des temps d'attente réduits. Vous pouvez identifier des zones car elles utilisent le nom de région plus un nombre et sont intégrées dans la région. 

## Centres de données
{: #data_center}

Lorsque vous déployez des ressources d'infrastructure, vous disposez de plus de choix quant à l'emplacement de vos données. Vous pouvez sélectionner un emplacement ou effectuer une sélection dans la liste des centres de données {{site.data.keyword.Bluemix_notm}}. Un *centre de données* est l'emplacement physique qui héberge les ressources d'alimentation, de refroidissement, de calcul, de réseau et de stockage utilisées pour les services et les applications. Les centres de données n'offrent aucune protection contre les pannes locales comme les emplacements multi-zone. Pour plus d'informations, voir [Global locations for your global business ![Icône de lien externe](../icons/launch-glyph.svg "Icône de lien externe")](https://www.ibm.com/cloud/data-centers/){: new_window}.

{{site.data.keyword.Bluemix_notm}} dispose de centres de données dans de nombreux emplacements dans le monde. Lorsque vous déployez des ressources d'infrastructure, vous pouvez effectuer une sélection dans la liste des centres de données dans {{site.data.keyword.Bluemix_notm}}. 


![Carte des centres de données décrits dans les tableaux suivants](images/Global-View.svg)

### Amérique du Nord
{: #na}

| Centre de données | Code  |
|------------------|-------|
| Dallas 01        | dal01 |
| Dallas 05        | dal05 |
| Dallas 06        | dal06 |
| Dallas 07        | dal07 |
| Dallas 09        | dal09 |
| Dallas 10        | dal10 |
| Dallas 12        | dal12 |
| Dallas 13        | dal13 |
| Washington DC 01 | wdc01 |
| Washington DC 04 | wdc04 |
| Washington DC 06 | wdc06 |
| Washington DC 07 | wdc07 |
| San José 01      | sjc01 |
| San José 03      | sjc03 |
| San José 04      | sjc04 |
| Seattle 01       | sea01 |
| Houston 01       | hou01 |
| Montréal 01      | mon01 |
| Toronto 01       | tor01 |
| Mexico 01        | mex01 |
{: caption="Tableau 1. Centres de données en Amérique du Nord" caption-side="top"}

### Amérique du Sud
{: #sa}

| Centre de données | Code    |
|------------------|---------|
| Sao Paulo 01     | sao01   |
{: caption="Tableau 2. Centre de données en Amérique du Sud" caption-side="top"}

### Europe
{: #eu}

| Centre de données | Code  |
|------------------|-------|
| Londres 02        | lon02 |
| Londres 04        | lon04 |
| Londres 05        | lon05 |
| Londres 06        | lon06 |
| Francfort 02     | fra02 |
| Francfort 04     | fra04 |
| Francfort 05     | fra05 |
| Milan 01         | mil01 |
| Amsterdam 01     | ams01 |
| Amsterdam 03     | ams03 |
| Paris 01         | par01 |
| Oslo 01          | osl01 |
{: caption="Tableau 3. Centres de données en Europe" caption-side="top"}

### Asie-Pacifique
{: #ap}

| Centre de données | Code  |
|------------------|-------|
| Tokyo 01         | tok02 | 
| Tokyo 04         | tok04 |
| Tokyo 05         | tok05 |
| Séoul 01         | seo01 |
| Hong Kong 02     | hkg02 |
| Singapour 01     | sng01 |
| Sydney 01        | syd01 |
| Sydney 04        | syd04 |
| Sydney 05        | syd05 |
| Melbourne 01     | mel01 |
{: caption="Tableau 4. Centre de données dans la zone Asie-Pacifique" caption-side="top"}


## Accords sur les niveaux de service (SLA)
{: #SLAs} 

{{site.data.keyword.Bluemix_notm}} fournit un niveau de service de disponibilité de 99,5 % pour plusieurs instances d'un service de plateforme dans un environnement dédié ou local.

Pour soumettre une réclamation de temps d'indisponibilité, contactez le [support {{site.data.keyword.Bluemix_notm}}](https://console.cloud.ibm.com/unifiedsupport/supportcenter){: new_window} ![Icône de lien externe](../icons/launch-glyph.svg "Icône de lien externe").

{{site.data.keyword.Bluemix_notm}} inclut des accords sur les niveaux de service pour les services {{site.data.keyword.Bluemix_notm}} pouvant vous donner droit à des crédits pour votre compte. Les accords sur les niveaux de service constituent la seule méthode permettant de résoudre l'impossibilité d'{{site.data.keyword.Bluemix_notm}} d'atteindre un niveau de service défini. {{site.data.keyword.Bluemix_notm}} fournit un niveau de service de disponibilité de 99,5 % pour plusieurs instances d'un service de plateforme dans un environnement dédié ou local.

Pour plus d'informations sur les environnements dédiés, voir [IBM Cloud Dedicated](/docs/hybrid?topic=dedicated-dedicated) et pour plus d'informations sur les environnements locaux, voir [Bluemix Local](/docs/hybrid?topic=local-local). 

La description de service complète d'{{site.data.keyword.Bluemix_notm}} est disponible sur la page [Cloud Services terms](http://www-03.ibm.com/software/sla/sladb.nsf/sla/bm){: new_window} ![Icône de lien externe](../icons/launch-glyph.svg "Icône de lien externe").

### Temps d'indisponibilité - Accord sur les niveaux de service
{: #avail-downtime}

Vous pouvez bénéficier d'un crédit pour votre compte si le temps d'indisponibilité est inférieur à 99,5 % de disponibilité. Le temps d'indisponibilité correspond au nombre total de minutes durant lesquelles vous ne pouvez vous connecter à aucune instance de service. Cette période commence lorsque vous soumettez un rapport d'événement d'indisponibilité et se termine lorsque au moins une des instances affectées est à nouveau disponible pour être utilisée.

{{site.data.keyword.Bluemix_notm}} inclut un accord sur les niveaux de service de disponibilité de 99,95 % pour : 
- Les services cloud dans l'environnement public configurés pour la haute disponibilité tels qu'ils sont décrits dans les détails de catalogue pour chaque service. 
- Les services cloud dans plusieurs environnements locaux ou dédiés se trouvant dans des centres de données à différents emplacements géographiques. 

| Type	 | Description	 | Informations relatives au support|
|-------------------------------------------------------------------------------|--------------------|----------------|
| Environnement public à haute disponibilité ou plusieurs environnements locaux/dédiés | Autres environnements | Crédit         |
| <99,9 5%                                                                       |<99,5 %              |10 %             |
| <99,9 0%                                                                       |<99,0 %              |25 %             |
{: caption="Tableau 5. Niveau de service de disponibilité mensuel" caption-side="top"}

Le pourcentage de disponibilité est calculé de la façon suivante : nombre total de minutes d'un mois contractuel moins le nombre total de minutes d'indisponibilité dans ce mois, divisé par le nombre total de minutes dans ce mois. 

Par exemple, dans un mois de 31 jours, le nombre total de minutes est égal à 44 640. Si vous subissez six heures d'indisponibilité, cela correspond à 360 minutes. Avec six heures d'indisponibilité uniquement, la disponibilité est de 99,19 %. Etant donné que 99,19 % est inférieur à 99,90 %, vous pouvez bénéficier d'un crédit de 25 % avec un environnement public ou local.   

```
= (44 640 minutes totales du mois - 360 minutes d'indisponibilité) / 44 640 minutes totales du mois
= (44 280 minutes réellement disponibles) / 44 640 minutes totales du mois
= 99,19 % de disponibilité
```

Les accords sur les niveaux de service ne mentionnent pas les périodes d'indisponibilité ou les défaillances liées aux exclusions spécifiées, à l'indisponibilité de l'interface graphique {{site.data.keyword.Bluemix_notm}}, ainsi qu'à la durée de rechargement, de configuration, d'activation ou d'accès au contenu.

Les accords sur les niveaux de service concernant le temps d'indisponibilité n'incluent pas les services d'infrastructure {{site.data.keyword.Bluemix_notm}}. 
{: note}

### Services d'infrastructure - Accord sur les niveaux de service
{: #iaas-slas}

Les serveurs Bare Metal, les serveurs virtuels, les réseaux, le stockage et les services de sécurité constituent des services d'infrastructure. Pour trouver la liste complète des services d'infrastructure, recherchez l'étiquette `iaas` dans le catalogue {{site.data.keyword.Bluemix_notm}}. 

Le temps d'indisponibilité correspond au nombre total de minutes durant lesquelles un service d'infrastructure identifié par un client est indisponible suite à une interruption de service liée à une panne d'équipements CVC (chauffage, ventilation et climatisation), d'alimentation d'infrastructure redondante, de réseau public et de réseau privé. Le calcul de la durée totale du temps d'indisponibilité commence lorsque l'indisponibilité validée affectant le service est identifiée jusqu'à ce que le service soit disponible. 

Le temps d'indisponibilité n'inclut pas la période de maintenance annoncée ou planifiée. Pour chaque période continue d'indisponibilité de 30 minutes, vous recevez un crédit de 5 % des frais mensuels pour les services identifiés directement affectés par l'indisponibilité. Vous n'êtes pas éligible à un crédit si le temps d'indisponibilité est inférieur à une période continue de 30 minutes. Ce calcul peut ne pas associer les durées d'indisponibilité liées à différents types de panne. 

### Mise à niveau et remplacement matériel de l'infrastructure - Accords sur les niveaux de service
{: #hw-replaceupgrade-sla}

{{site.data.keyword.Bluemix_notm}} tente de réduire le temps d'indisponibilité lors du remplacement du matériel défectueux ou lors d'une mise à niveau matérielle planifiée. 

{{site.data.keyword.Bluemix_notm}} fournit un crédit pour : 
- Le remplacement de matériel. Ce crédit est défini en fonction de la durée écoulée entre le moment où {{site.data.keyword.Bluemix_notm}} a enregistré la panne matérielle signalée par le client et celui où le remplacement est effectué.
- Les mises à niveau de matériel planifiées. Ce crédit dépend de la durée d'indisponibilité totale du service bénéficiant de la mise à niveau. 

Les périodes de niveau de service excluent la durée de rechargement du système d'exploitation ou des applications, ainsi que toute période pendant laquelle les performances sont dégradées. Si {{site.data.keyword.Bluemix_notm}} ne parvient pas à garantir une période de niveau de service définie, vous pouvez bénéficier d'un crédit calculé d'après les frais mensuels du service affecté par la mise à niveau ou le remplacement matériel.

| Période de niveau de service  | Pourcentage de crédit |
|---------------------------|----------------|
| ≤ 2 heures                 | Aucun           |
| > 2 heures                 | 20 %            |
| > 6 heures                 | 40 %            |
| > 10 heures                | 60 %            |
| > 14 heures                | 80 %            |
| > 18 heures                | 80 %            |
{: caption="Tableau 6. Crédit en fonction des frais mensuels pour le service affecté par la mise à niveau ou le remplacement matériel" caption-side="top"}

### Réclamations
{: #claims}

Soumettez votre réclamation dans une période de 60 jours suivant la fin du mois contractuel au cours duquel le niveau de service n'a pas été atteint. Pour valider la réclamation, indiquez les messages d'erreurs, suffisamment d'informations pour identifier le service concerné ainsi que d'autres détails. 

Le crédit correspondra à la compensation applicable la plus élevée d'après la disponibilité totale du service affecté lors d'un mois contractuel et sera calculé en utilisant les frais mensuels de ce service. Les crédits ne peuvent pas excéder 25 % des frais mensuels.

Pour soumettre une réclamation de temps d'indisponibilité, contactez le [support {{site.data.keyword.Bluemix_notm}}](https://console.cloud.ibm.com/unifiedsupport/supportcenter){: new_window} ![Icône de lien externe](../icons/launch-glyph.svg "Icône de lien externe").

### Exclusions
{: #exclusions}

Aucun crédit n'est accordé lorsque l'accord sur les niveaux de service n'est pas respecté pour les raisons suivantes :
- Problèmes liés à des instructions, des conceptions, des technologies ou du contenu fourni par la communauté ou le client
- Services Cloud bêta, expérimental ou gratuit
- Packs de construction non IBM
- Plateformes et configurations système non pris en charge
- Défaillances de l'infrastructure du client, y compris le réseau, le matériel, l'installation ou l'alimentation
- Transferts de fichier, commandes ou actions d'administration système
- Erreurs client ou impossibilité de fournir les informations ou l'accès nécessaires pour la résolution d'une indisponibilité
- Incidents de sécurité provoqués par le client ou test de sécurité
- Autres causes ne dépendant pas d'IBM

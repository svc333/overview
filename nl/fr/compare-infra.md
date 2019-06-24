---
copyright:
  years: 2019
lastupdated: "2019-06-05"

keywords: understanding infrastructure, vpc, classic infrastructure, cloud environment

subcollection: overview

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}
{:tip: .tip}
{:note: .note}

# Comparaison des environnements d'infrastructure {{site.data.keyword.cloud_notm}}
{: #compare-infrastructure}

Comparez les principales différences entre les environnements d'infrastructure {{site.data.keyword.cloud}} afin de déterminer l'environnement le plus approprié pour vos charges de travail et applications.
{: shortdesc}

Si vous n'êtes pas familier avec les types d'environnement, passez en revue les descriptions suivantes :

* L'infrastructure classique est notre plateforme IaaS existante. Cet environnement convient parfaitement aux charges de travail "lift-and-shift", ce qui vous permet de déplacer des applications rapidement et de conserver la même architecture.
* L'infrastructure VPC est notre nouvelle plateforme IaaS, basée sur la mise en réseau définie par logiciel et idéale pour les applications natives en cloud.

L'infrastructure classique et l'infrastructure VPC n'entraînent pas de coût supplémentaire, par conséquent, vous pouvez vous concentrer sur l'identification de l'environnement le mieux adapté à vos besoins.
{: note}

## Facteurs clés de différenciation en matière de calcul
{: #compare-compute}

Pour connaître les différences de calcul entre infrastructure classique et infrastructure VPC, reportez-vous au tableau ci-après.  

| Catégorie   |  Infrastructure classique   | Infrastructure VPC |
| ---------- | ------------------------- | ------------------ |
|  Services  |Catalogue complet de services, par exemple, instances {{site.data.keyword.baremetal_short}}, {{site.data.keyword.BluVirtServers_short}}, VMware, SAP | Instances {{site.data.keyword.BluVirtServers_short}} uniquement |
| Performances et disponibilité | | Meilleure disponibilité pouvant être atteinte via une architecture par zone |
| Tarification | Facturation horaire et mensuelle, plus facturation suspendue | Facturation horaire, suspendue et remise en cas d'utilisation prolongée |
| Familles de serveurs virtuels | Public, dédié, transitoire, réservé | Public uniquement |
| Profils | Tous les profils, y compris les profils GPU | Profils de calcul, de mémoire, équilibrés avec des options RAM et vCPU supérieures |
| Images prises en charge | Jeu complet d'images stockées, plus images personnalisées | Jeu limité d'images stockées|
| Intégration de plateforme | | Intégration IAM et de groupe de ressources pour une expérience unifiée |
{: row-headers}
{: class="comparison-table"}
{: caption="Tableau 1. Comparaison des calcules" caption-side="top"}
{: summary="This table has row and column headers. The row headers identify possible features. The column headers indentify the differentiators between classic infrastructure and VPC infrastructure. To understand the differences between environments, navigate to the row and find the details for the feature that you're interested in."}

## Facteurs clés de différenciation en matière de réseau
{: #compare-network}

Pour connaître les différences de mise en réseau entre infrastructure classique et infrastructure VPC, reportez-vous au tableau ci-après.   

| Catégorie   |  Infrastructure classique   | Infrastructure VPC |
| ---------- | ------------------------- | ------------------ |
| Construction d'emplacement    | Centres de données et POD <br>(Peut nécessiter le spanning VLAN pour connecter deux pods/centres de données différents, et l'achat de passerelles pour contrôler et router le trafic)| Modèle régional qui extrait l'infrastructure, par conséquent, vous n'avez pas à vous préoccuper des emplacements de pod.|
| Fonctions et services de réseau |Dispositifs physiques et virtuels provenant de plusieurs fournisseurs | Fonctions de réseau natives en cloud (VPN, LBaaS)<br>(Isolement VPC, ressources dédiées taillées dans le cloud public avec d'autres options pour les VPN, les services LBaaS, plusieurs instances vNIC et des tailles de sous-réseau plus importantes) |
| Adresses IP | Adresses IPv6 prises en charge | Adresses IPv4 uniquement |
| Routage de passerelle | Utilisez un dispositif réseau virtuel ou physique (dispositif de routeur virtuel, Vyatta, Juniper vSRX, Fortinet FSA) | Le routage de trafic est géré par la passerelle publique et des services d'adresse IP flottante |
| Conversion d'adresses réseau (NAT) | Utilisez un dispositif réseau virtuel ou physique (dispositif de routeur virtuel, Vyatta, Juniper vSRX, Fortinet FSA) | Prise en charge par la fonctionnalité BYOIP (Bring-your-own-IP)  |
| Réseau privé virtuel IPsec (VPN) | Utilisez un dispositif réseau virtuel ou physique (dispositif de routeur virtuel, Vyatta, Juniper vSRX, Fortinet FSA) | Pris en charge avec l'offre VPN-as-a-service. |
|  Equilibrage de charge élastique | Equilibreur de charge cloud  | Equilibreur de charge pour VPC |
| Equilibrage de charge global| Cloud Internet Services, Citrix Netscaler MPX | Cloud Internet Services |
|Connectivité hybride | Solution NAT pour établir un point avec IBM Cloud et votre environnement informatique | Utilisez votre propre adresse IP sans les tunnels NAT ou IPSec <br>Remarque : vous pouvez activer votre VPC pour l'accès aux ressources d'infrastructure classique.|
{: row-headers}
{: class="comparison-table"}
{: caption="Tableau 2. Comparaison des réseaux" caption-side="top"}
{: summary="This table has row and column headers. The row headers identify possible features. The column headers indentify the differentiators between classic infrastructure and VPC infrastructure. To understand the differences between environments, navigate to the row and find the details for the feature that you're interested in."}

## Facteurs clés de différenciation en matière de stockage
{: #compare-storage}

Pour connaître les différences de stockage entre infrastructure classique et infrastructure VPC, reportez-vous au tableau ci-après. 

|  Infrastructure classique   | Infrastructure VPC |
| ------------------------- | ------------------ |
|Jeu robuste de services de stockage, d'offres de stockage par blocs (iSCSI) et de stockage de fichiers (basé sur NFS)| Stockage par blocs en comme disque d'amorçage principal (avec gestion du cycle de vie), et volumes de données secondaires  <br> Remarque : le chiffrement de volume est disponible durant la mise à disposition.|
{: caption="Tableau 3. Comparaison des stockages" caption-side="top"}

## Facteurs clés de différenciation en matière de sécurité
{: #compare-security}

Pour connaître les différences de sécurité entre infrastructure classique et infrastructure VPC, reportez-vous au tableau ci-après. 

|  Infrastructure classique   | Infrastructure VPC |
| ---------- | ------------------------- |
|Vyatta, Fortigate, Juniper vSRX, groupes de sécurité pour instances de serveur virtuel| Groupes de sécurité, listes de contrôle d'accès réseau|
{: caption="Tableau 4. Comparaison des offres de sécurité" caption-side="top"}

## Facteurs clés de différenciation en matière d'API
{: #compare-apis}

Pour connaître les différences d'API entre infrastructure classique et infrastructure VPC, reportez-vous au tableau ci-après. 

|  Infrastructure classique   | Infrastructure VPC |
| ------------------------- | ------------------ |
|Interface {{site.data.keyword.slapi_short}} (SLAPI) existante| Nouvelle API REST conviviale pour les développeurs|
{: caption="Tableau 5. Comparaison des API" caption-side="top"}

## Etapes suivantes
{: #compare-nextsteps}

Pour passer en revue toutes nos fonctionnalités d'infrastructure VPC, voir [A propos du cloud privé virtuel](/docs/vpc-on-classic?topic=vpc-on-classic-about). Pour commencer à explorer l'ensemble de l'infrastructure, voir [Construction de votre infrastructure](/docs/overview?topic=overview-first-steps-it-ops).

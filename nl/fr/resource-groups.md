---

copyright:
  years: 2017, 2019
lastupdated: "2019-03-14"

keywords: access control, resource groups, resource group

subcollection: overview

---

{:shortdesc: .shortdesc}

# Organisation des ressources dans des groupes de ressources
{: #whatis-rgs}

Un groupe de ressources permet d'organiser vos ressources de compte en regroupements personnalisables de manière à pouvoir affecter rapidement des accès utilisateur à plusieurs ressources à la fois. Chaque ressource de compte gérée à l'aide du contrôle d'accès {{site.data.keyword.Bluemix}} Identity and Access Management (IAM) appartient à un groupe de ressources au sein de votre compte. Lorsque vous ajoutez une ressource à votre compte à partir du catalogue, vous pouvez l'affecter à un groupe de ressources. Seul Kubernetes ne vous invite pas à définir une affectation de groupe de ressources. Cependant, l'accès au service est contrôlé en utilisant des rôles IAM.

Les services qui sont gérés en utilisant {{site.data.keyword.Bluemix_notm}} IAM et qui appartiennent à un groupe de ressources offrent plusieurs avantages. Parmi ces avantages, citons notamment la possibilité de se connecter à des applications et des services dans n'importe quel espace Cloud Foundry, ce qui vous permet de vous connecter à des applications et des services à partir de différents emplacements. Etant donné que la portée des groupes de ressources n'est pas établie par emplacement, vous pouvez mettre à disposition des applications et des services issus de différents emplacements dans un même groupe de ressources. Vous pouvez également utiliser le contrôle d'accès à granularité fine jusqu'au niveau d'une instance individuelle dans un groupe de ressources.

Pour plus d'informations sur l'utilisation des groupes de ressources, voir [Gestion des groupes de ressources](/docs/resources?topic=resources-rgs). 

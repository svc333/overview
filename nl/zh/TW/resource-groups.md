---

copyright:
  years: 2017, 2019
lastupdated: "2019-03-14"

keywords: access control, resource groups, resource group

subcollection: overview

---

{:shortdesc: .shortdesc}

# 用資源群組組織資源
{: #whatis-rgs}

資源群組可讓您用可自訂的分組來組織帳戶資源，以便您可以一次將對多個資源的存取權快速指派給使用者。使用 {{site.data.keyword.Bluemix}} Identity and Access Management (IAM) 存取控制來管理的任何帳戶資源，都屬於您帳戶內的資源群組。當您從型錄中將資源新增至帳戶時，可以將資源指派給資源群組。唯一例外是 Kubernetes，它不會提示您進行資源群組指派，而是使用 IAM 角色來控制服務的存取權。

使用 {{site.data.keyword.Bluemix_notm}} IAM 管理並且屬於資源群組的服務，有數項好處。其中一些好處包括能夠連接至任何 Cloud Foundry 空間中的應用程式和服務，這表示您可以從不同位置連接應用程式及服務。因為資源群組的範圍不是根據位置，所以您可以將不同位置的應用程式及服務佈建至相同的資源群組。您也可以使用直到資源群組內個別實例的精細存取控制。

如需使用資源群組的相關資訊，請參閱[管理資源群組](/docs/resources?topic=resources-rgs)。 

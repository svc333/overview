---

copyright:
  years: 2017, 2018
lastupdated: "2018-10-11"

---

{:shortdesc: .shortdesc}

# 用資源群組組織資源
{: #whatis}

資源群組可讓您在可自訂的分組中組織帳戶[資源](/docs/resources/acct_resources.html#resource)，以同時快速地將對多個資源的存取權指派給使用者。任何使用 {{site.data.keyword.Bluemix}} Identity and Access Management (IAM) 存取控制所管理的帳戶資源，都屬於您帳戶內的資源群組。當您從型錄中將新的資源新增至帳戶時，可以將資源指派給資源群組。唯一例外是 Kubernetes，它不會提示您進行資源群組指派，而是使用 IAM 角色來控制服務的存取權。

使用 {{site.data.keyword.Bluemix}} IAM 所管理並屬於資源群組的服務有幾個優點，包括能夠連接至任何 Cloud Foundry 空間中的應用程式及服務，這容許您從不同的位置連接應用程式及服務。因為資源群組的範圍不是根據位置，所以您可以將不同位置的應用程式及服務佈建至相同的資源群組。您也可以使用直到資源群組內個別實例的精細存取控制。

如需使用資源群組的相關資訊，請參閱[管理資源群組](/docs/resources/resourcegroups.html)。此外，如果您是初次使用資源群組，請參閱[用資源群組組織資源的最佳作法](/docs/resources/bestpractice_rgs.html#bp_resourcegroups)。

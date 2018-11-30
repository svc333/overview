---

copyright:

  years: 2018

lastupdated: "2018-11-15"

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:pre: .pre}
{:tip: .tip}

# 资源部署的位置 
{: #ov_intro_reg}

您可以在不同的位置中创建应用程序和服务实例，但前提是这些区域使用相同的 {{site.data.keyword.cloud_notm}} 基础架构来进行应用程序管理，并使用相同的使用情况详细信息视图来进行计费。您可以将应用程序部署至离客户最近的位置，以缩短应用程序等待时间。 

要解决安全问题，还可选择希望在其中保留应用程序数据的位置。在多个位置中构建应用程序后，如果一个位置变为不可用，其他位置中的应用程序会继续运行。您的资源限额对于您使用的每个位置都是相同的。有关平台资源及其可用位置的更多信息，请参阅[服务可用性](/docs/resources/service_region.html)。

控制台的全局负载均衡可确保如果您最接近的地理位置关闭，那么控制台将显示下一个最接近位置的信息。这样一来，您无需执行任何操作来访问所需信息，始终可以访问控制台。

在仪表板中，缺省情况下可以查看所有位置的所有资源。如果要查看和使用特定位置中的资源，请展开**位置**菜单，然后从列表中选择一个位置。 

您还可以使用命令行界面，通过 `ibmcloud api` 命令并指定要使用的 {{site.data.keyword.cloud_notm}} 位置的 API 端点来连接到该位置。例如，输入以下命令来连接到 {{site.data.keyword.cloud_notm}} 伦敦：

```
ibmcloud api https://api.eu-gb.bluemix.net
```

每个位置都分配有唯一前缀。{{site.data.keyword.cloud_notm}} 提供了以下位置和位置前缀。

| **位置** | **API 端点** |
|-----------------|-------------------|
|达拉斯|api.ng.bluemix.net|
|悉尼|api.au-syd.bluemix.net|
| 法兰克福|api.eu-de.bluemix.net|
|伦敦|api.eu-gb.bluemix.net|
|华盛顿特区|api.us-east.bluemix.net|
|东京| api.jp-tok.bluemix.net |
{: caption="表 1. {{site.data.keyword.cloud_notm}} 位置列表" caption-side="top"}

部署基础架构资源时，您对内容的存储位置拥有更多选择。您可以选择一个位置，也可以从 {{site.data.keyword.Bluemix_notm}} 中数据中心列表中进行选择。有关更多信息，请参阅 [{{site.data.keyword.cloud_notm}} 数据中心](data-centers.html)。


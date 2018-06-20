---


copyright:
  years: 2016, 2018
lastupdated: "2018-05-23"

---

{:shortdesc: .shortdesc}
{:tip: .tip}
{:new_window: target="_blank"}

# {{site.data.keyword.cloud_notm}} 控制台的运作方式
{: #ui}

{{site.data.keyword.cloud}} 控制台是帮助您管理所有 {{site.data.keyword.cloud_notm}} 资源的用户界面。访问[控制台](https://console.bluemix.net){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标") 时，可以创建免费帐户、登录、访问文档、访问目录、查看定价信息、获取支持或检查所有 {{site.data.keyword.cloud_notm}} 组件的状态。登录后，根据您的帐户类型，菜单栏会包含“菜单”图标 ![“菜单”图标](../icons/icon_hamburger.svg) 和其他链接。
{: shortdesc}

## 使用控制台
{: #consoleoptions}

如果您是具有 {{site.data.keyword.cloud_notm}} 帐户的现有用户，那么可以使用“菜单”图标 ![“菜单”图标](../icons/icon_hamburger.svg) 在仪表板上访问所有现有资源。
  * 使用**目录**链接可创建新资源。
  * 使用**文档**链接可访问有关 {{site.data.keyword.cloud_notm}} 的有用信息。
  * 在**支持**菜单中，可以访问有关 {{site.data.keyword.cloud_notm}} 新增功能、支持中心、用于添加和查看凭单的选项以及“状态”页面的信息。
  * 在**管理**菜单中，可以访问帐户、计费和使用情况以及安全性选项。

如果链接了 {{site.data.keyword.cloud_notm}} 和 SoftLayer 帐户，那么您除了具有与非链接帐户所有者相同的选项外，还可以通过选择**“菜单”图标 ![“菜单”图标](../icons/icon_hamburger.svg) > 基础架构**选项来导航至客户门户网站。在其中，可以查看帐户汇总，订购存储器和设备，以及管理针对仅使用 VPN 的用户和设备的访问权。

## 在仪表板上管理资源
{: #dashboardview}

可以使用仪表板来查看和使用 {{site.data.keyword.cloud_notm}} 资源和 Cloud Foundry 服务实例。有关资源的更多信息，请参阅[什么是资源？](/docs/resources/acct_resources.html#resource)。

### 查看资源

可以在仪表板中查看帐户中的所有资源。要定制视图，请使用以下选项：

  * 要查看特定资源组中的资源，请从**资源组**列表中选择资源组。
  * 要查看特定 Cloud Foundry 组织中的资源，请从 **Cloud Foundry 组织**列表中选择组织。

然后，根据您选择的项，可以按以下选项进行过滤：

  * 区域
  * Cloud Foundry 空间

### 使用资源

可以在仪表板中以多种方式使用资源：

  * 每个资源都会单独显示一行，并且在行末包含“更多操作”图标 ![“更多操作”图标](../icons/overflow-menu.svg)。单击“更多操作”图标可启动、停止、重命名或删除资源。
  * 要为资源设置凭证或连接，请单击资源的名称以导航至资源详细信息页面。有关更多信息，请参阅[添加新凭证](/docs/resources/service_credentials.html)和[管理连接](/docs/resources/connecting_apps.html#connect_app)。

## 在目录中工作
{: #catalogcreate}

要创建新资源，请在仪表板中单击**创建资源**。然后，系统会将您定向到目录。从目录选择磁贴时，您可以查看资源在哪个区域是可用的。并非目录中列出的每个资源在每个区域中都可用。

单击要创建的资源的磁贴后，可以选择要部署的位置。

  * 对于 Cloud Foundry 资源，可以选择特定区域，然后选择要将服务实例分配到的组织和空间。
  * 对于 {{site.data.keyword.cloud_notm}} Identity and Access Management (IAM) 管理的资源，请选择要部署的位置。然后，选择要将服务实例分配到的资源组。

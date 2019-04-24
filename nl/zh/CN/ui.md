---


copyright:
  years: 2015, 2019
lastupdated: "2019-01-29"

keywords: ui, components, using the console

subcollection: overview

---

{:shortdesc: .shortdesc}
{:tip: .tip}
{:new_window: target="_blank"}

# 浏览 {{site.data.keyword.cloud_notm}} 控制台 
{: #ui}

{{site.data.keyword.cloud}} 控制台是一个可帮助您管理所有 {{site.data.keyword.cloud_notm}} 资源的用户界面。访问[控制台](https://cloud.ibm.com){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标") 时，可以创建免费帐户、登录、访问文档、访问目录、查看定价信息、获取支持或检查 {{site.data.keyword.cloud_notm}} 组件的状态。登录后，菜单栏会包含“菜单”图标 ![“菜单”图标](../icons/icon_hamburger.svg) 和更多链接。
{: shortdesc}


## 使用控制台
{: #consoleoptions}

登录到 {{site.data.keyword.cloud_notm}} 后，可以查看的第一个页面是仪表板，其中显示了概述帐户状态的窗口小部件。接下来，您可以管理资源。转至“菜单”图标 ![“菜单”图标](../icons/icon_hamburger.svg) &gt; **资源列表**以查看帐户中的所有现有资源。

  * 使用**目录**链接可创建新资源。
  * 使用**文档**链接可访问有关 {{site.data.keyword.cloud_notm}} 的有用信息。
  * 使用**支持**链接可访问支持中心。  
  * 在**管理**菜单中，可以访问帐户、计费和使用情况以及 Identity and Access Management 选项。
  * 单击“成本估算工具”图标 ![“成本估算工具”图标](../icons/Estimator.svg) 可打开成本估算工具。
  * 单击“通知”图标 ![“通知”图标](../icons/Notification.svg) 可访问声明以及计划内和计划外事件。

## 搜索资源
{: #search}

您可以在 {{site.data.keyword.cloud_notm}} 控制台中的任意位置通过名称或标记搜索资源，以查找期望在资源列表中找到的资源。在控制台菜单栏的搜索字段中输入资源或标记的名称。

有关更多信息，请参阅[搜索资源](/docs/resources?topic=resources-searching-for-resources)。 

## 管理资源列表中的资源
{: #dashboardview}

转至“菜单”图标 ![“菜单”图标](../icons/icon_hamburger.svg) &gt; **资源列表**以访问帐户资源的列表。可以使用资源列表来查看和使用 {{site.data.keyword.cloud_notm}} 资源和 Cloud Foundry 服务实例。请参阅[什么是资源？](/docs/resources?topic=resources-resource)以获取有关不同类型资源的更多信息。

### 查看资源
可以在资源列表中查看您帐户中所有区域中的所有资源。要查看对您很重要的项，请使用每个列标题的过滤器来过滤列表。例如，如果要查看和使用特定位置中的资源，请展开**位置**过滤器，然后从列表中选择一个位置。

### 处理资源
可以在资源列表中以多种方式处理资源：

  * 每个资源都会单独显示一行，并且在行末包含“操作”图标 ![“更多操作”图标](../icons/action-menu-icon.svg)。单击“操作”图标 ![“更多操作”图标](../icons/action-menu-icon.svg) 可启动、停止、重命名或删除资源。
  * 要为资源设置凭证或连接，请单击资源的名称以导航至资源详细信息页面。然后，选择**服务凭证**或**连接**。有关更多信息，请参阅[添加凭证](/docs/resources?topic=resources-service_credentials)和[管理连接](/docs/resources?topic=resources-connect_app)。


## 在目录中执行操作
{: #catalogcreate}

要创建资源，请在资源列表中单击**创建**。然后，系统会将您定向到目录。从目录中选择某个磁贴后，即可查看资源的可用区域。并不是目录中列出的每个资源在每个区域中都可用。

单击要创建的资源的磁贴后，可以选择要部署的位置。

  * 对于 Cloud Foundry 资源，可以选择特定区域，然后选择要将服务实例分配到哪个组织和空间。
  * 对于 {{site.data.keyword.cloud_notm}} Identity and Access Management (IAM) 管理的资源，可以选择要部署的位置。然后，选择要将服务实例分配到哪个资源组。

---


copyright:
  years: 2016, 2019
lastupdated: "2019-01-31"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# 什么是 {{site.data.keyword.Bluemix_notm}} 平台？
{: #whatis-platform}

IBM 的云平台集平台即服务 (PaaS) 与基础架构即服务 (IaaS) 于一体，以提供集成体验。平台不仅可扩展并支持小型开发团队和组织，也能扩展并支持大型企业业务。在 {{site.data.keyword.cloud}} 上构建的解决方案会以全局方式部署在全球范围的数据中心，并能够在您可信任的经过测试并受支持的环境中，快速启动和可靠地执行。
{: .shortdesc}

{{site.data.keyword.Bluemix_notm}} 平台由多个部分组成，各组成部分之间协同工作，以提供一致、可靠的云体验。 

  * 目录，包含数百个 {{site.data.keyword.Bluemix_notm}} 产品
  * 稳健的控制台，充当创建、查看和管理云资源的前端
  * 身份和访问权管理组件，用于对这两个平台服务的用户进行安全认证，并在整个 {{site.data.keyword.Bluemix_notm}} 上以一致的方式来控制对资源的访问权
  * 搜索和标记机制，用于过滤和标识资源
  * 帐户和计费管理系统，用于提供价格套餐的准确使用情况，并确保信用卡安全，防止信用卡欺诈

## 选择托管环境
{: #choose-compute}

借助 {{site.data.keyword.Bluemix_notm}}，您无需再对硬件进行大笔投资来测试或运行新应用程序。我们会为您管理一切，并且只对您使用的内容收取费用。云服务器环境是基础架构层的基础。您可以为更复杂的环境选择单个选项或选项组合。 

您有多种选项可用于托管应用程序，这使您可以拥有所需的基础架构掌控力。可以使用以下任何一种方法来运行应用程序：

  * 作为无服务器功能
  * 作为 Cloud Foundry 应用程序
  * 作为 Kubernetes 集群上的 Docker 容器
  * 作为 VMware
  * 作为虚拟机
  * 在高性能 {{site.data.keyword.baremetal_short}} 上运行 

{{site.data.keyword.baremetal_short}} 是专用于单个客户的单租户物理服务器。您可以控制从服务器主机一直到 RAM 和存储设备等几乎所有内容。这些服务器用于需要计算能力可持续一定时间（例如，几个月）的工作负载。 

{{site.data.keyword.BluVirtServers_short}} 可以部署为公共实例或专用实例。通过公共实例，服务器的资源可与其他客户共享，这也称为多租户环境。专用实例使物理服务器的资源专用于一个客户，该客户可以在同一服务器上有一个或多个虚拟机。这些服务器最适合用于在有限时间（例如，几周）内运行的工作负载。一些工作负载示例为开发和测试、备份和恢复以及灾难恢复等。有关服务器选项的更多信息，请参阅 [Bare metal servers vs. virtual servers: Choosing the best option for you](https://www.ibm.com/blogs/bluemix/2018/06/bare-metal-virtual-servers-works/){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")。

请查看下表以获取计算选项的摘要。

|选项|描述
| 
|--------|---------------|
| [{{site.data.keyword.baremetal_short}}](/docs/bare-metal?topic=bare-metal-getting-started)  |专供您使用的按小时或按月计费的单租户服务器，任何部分（包括服务器资源）都不会与其他客户共享。|
| [{{site.data.keyword.BluVirtServers_short}}](/docs/vsi?topic=virtual-servers-about-public-virtual-servers#public-virtual-servers) |可扩展的虚拟服务器，随专用核心和内存分配一起购买。|
| [{{site.data.keyword.vmwaresolutions_short}}](/docs/services/vmwaresolutions?topic=vmware-solutions-getting-started#getting-started) |使用安全、可扩展的高性能基础架构和行业领先的 VMware 混合虚拟化技术，快速无缝地集成或迁移内部部署 VMware 工作负载。|
| [{{site.data.keyword.containerlong_notm}}](/docs/containers?topic=containers-container_index) |将 Docker 容器、Kubernetes 技术、直观的用户体验和内置安全性与隔离功能组合在一起，自动对计算主机集群中的容器化应用程序进行部署、操作、扩展和监视。|
| [{{site.data.keyword.cfee_full_notm}}](/docs/cloud-foundry?topic=cloud-foundry-about) |按需实例化多个隔离的企业级 Cloud Foundry 平台。|
| [{{site.data.keyword.openwhisk_short}}](/docs/openwhisk?topic=cloud-functions-index) |基于 Apache OpenWhisk 的函数即服务 (FaaaS) 编程平台。|
{: caption="表 1. 计算选项" caption-side="top"}

## 构建应用程序
{: #build-apps}

无论您是有要进行现代化并移至云的[现有代码](/docs/apps/tutorials?topic=creating-apps-tutorial-byoc#tutorial-byoc)，还是要开发[全新应用程序](/docs/apps/tutorials?topic=creating-apps-tutorial-starterkit)，开发者都可以利用 {{site.data.keyword.Bluemix_notm}} 中快速发展的可用服务和运行时框架生态系统。

按语言提供的[编程指南](https://cloud.ibm.com/docs/home/build){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标") 可帮助您快速入门并熟练运用。通过 {{site.data.keyword.baremetal_short}}，您有多种选项用于通过 {{site.data.keyword.Bluemix_notm}} 基础架构来托管应用程序，以作为无服务器功能运行。

## 连接服务
{: #connect-services}

目录中有 190 多个服务，您可从中选择相应服务来构建定制解决方案，以满足自己的需求。您还可以轻松地将服务连接到 {{site.data.keyword.Bluemix_notm}} 外部的应用程序（如果这适合您的用例）。如果您希望手动将外部使用者连接到 {{site.data.keyword.Bluemix_notm}} 服务，那么可以生成一组新凭证。例如，如果要尝试将 {{site.data.keyword.Bluemix_notm}} 外部的应用程序连接到 Watson 服务，那么可以生成用于将这两者连接在一起的新凭证。就是这么简单！有关更多信息，请参阅[添加凭证](/docs/resources?topic=resources-service_credentials)。

## 设置帐户
{: #set-up-account}

如果只是要试用 {{site.data.keyword.Bluemix_notm}}，您可以直接转至目录并开始查看要探索的产品，然后将其添加到轻量帐户。但是，如果您已准备好供一组开发者或整个组织开始使用的环境，并且应用程序已在生产环境中运行，请考虑在帐户中设置以下基本项：

* 用户访问组，用于将用户和服务标识组织为一个实体，以简化分配访问权的过程。
* 资源组，用于组织资源，以快速、轻松地分配对资源集的访问权。
* 访问策略，用于需要 IAM 访问策略或 Cloud Foundry 组织和空间角色的访问组或单个开发者。

有关更多信息，请参阅[设置帐户的最佳实践](/docs/account?topic=account-account_setup)和[分配访问权的最佳实践](/docs/iam?topic=iam-account_setup)。 

## 定价和计费
{: #pricing-billing}

不管您的帐户是哪种类型，都可以将提供免费配额的轻量套餐用于服务，以探索 {{site.data.keyword.Bluemix_notm}}。从目录中选择服务并选择一个磁贴时，如果有不同类型的可用套餐，那么可以查看有关定价信息的详细情况。如果选择具有付费套餐的服务套餐，那么可以使用成本估算工具来估算成本。有关更多信息，请参阅[估算成本](/docs/billing-usage?topic=billing-usage-cost)。

{{site.data.keyword.Bluemix_notm}} 计费提供了多个服务，用于确保 {{site.data.keyword.Bluemix_notm}} 平台能够安全地管理定价、帐户、使用情况等。

### 帐户管理
{: #account-mgmt}

通过帐户管理，可维护与客户的计费关系。每个帐户都是代表客户的一个计费实体。此服务用于控制帐户生命周期、预订、用户关系和组织。

### 定价
{: #pricing}

定价平台服务可帮助您定义、管理和检索 {{site.data.keyword.Bluemix_notm}}“目录”中资源的定价信息。

### 使用情况测量
{: #metering}

通过使用量计量，服务提供者可以提交针对 {{site.data.keyword.Bluemix_notm}} 用户供应的资源实例而收集的度量值。交付综合计费服务的第三方服务提供者需要每小时提交一次所有活动服务实例的使用量。 

### 使用情况报告
{: #usage}

使用情况报告会返回帐户在指定月份的摘要。帐户记帐管理者有权访问这些报告。

## {{site.data.keyword.Bluemix_notm}} 目录
{: #catalog}

{{site.data.keyword.Bluemix_notm}}“目录”会存储 {{site.data.keyword.Bluemix_notm}} 控制台中提供的资源的产品定义（描述、功能、图像和 URL 等）。可将各个地理位置中的产品作为记录系统进行管理。目录支持命令行界面 (CLI) 和 RESTful API，在其中用户可以检索有关现有产品的信息，还可以创建、管理和删除其资源。有关更多信息，请参阅[管理目录](/docs/overview?topic=overview-manage-catalog)。

## 创建资源
{: #provisioning-layer}

资源控制器是下一代 {{site.data.keyword.Bluemix_notm}} 平台供应层，用于管理帐户中 {{site.data.keyword.Bluemix_notm}} 资源的生命周期。资源在帐户作用域中以全局方式供应。资源控制器支持同步和异步供应资源。例如，资源包括数据库、帐户、处理器、内存以及存储限制。 

通常，由供应层跟踪的资源都会与使用量度量值和帐单相关联，但也并不总是如此。在某些情况下，资源可能会与供应层相关联，以确保资源生命周期可与帐户生命周期一起进行管理。资源控制器使用 {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) 来对针对供应层执行的操作进行认证和授权。

### 资源生命周期管理
{: #lifecycle}

资源控制器提供了公共 API，用于控制资源从创建实例、创建访问凭证、除去访问权一直到删除实例的整个生命周期。

## 管理资源
{: #resource-manager}

资源集合通过[资源组](/docs/overview?topic=overview-whatis-rgs)进行管理。资源组与帐户相关联。所有 {{site.data.keyword.Bluemix_notm}} 资源都必须分配给资源组。创建帐户时，系统会创建缺省资源组。所有支持 IAM 的 {{site.data.keyword.Bluemix_notm}} 资源都必须在资源组中进行供应。如果您有轻量帐户，那么只能有一个资源组。如果您有现收现付或预订帐户，那么可以创建多个资源组。如果帐户暂挂，那么相应的资源组也将暂挂，并且该资源组中的所有资源都将暂挂。 

## 搜索和标记资源
{: #search-and-tag}

搜索服务是集成在 {{site.data.keyword.Bluemix_notm}} 平台中的一个全局共享资源属性存储库，用于存储和搜索云资源的属性，以及对资源进行分类。资源通过[云资源名称 (CRN)](/docs/overview?topic=overview-crn) 标识进行唯一标识。资源的属性包括标记和系统属性。这两个属性都是在 {{site.data.keyword.Bluemix_notm}} 缴费帐户中定义的，并且可跨多个区域。

此服务还可管理与资源相关联的标记。您可以使用标记 API 来创建、删除、搜索、附加或拆离标记。标记通过 CRN 标识进行唯一标识。标记具有名称，此名称在缴费帐户中必须唯一。可以创建 key:value 对或标签格式的标记。

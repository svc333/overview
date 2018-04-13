---

copyright:
  years: 2016, 2017, 2018
lastupdated: "2018-03-16"

---
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}
{:tip: .tip}

# {{site.data.keyword.cloud_notm}} 中的开发者探索之旅
{: #dev-journey}

{{site.data.keyword.cloud}} 有一组功能，可供开发者在几分钟内开始构建应用程序。在开发者仪表板中，可以实现：

* 选择特定于用例的初学者工具包，并使用各种编程语言和体系结构模式生成生产就绪型入门模板应用程序
* 在初学者工具包的项目创建过程中自动供应服务
* 使用支持管理应用程序组件的可移植应用程序项目结构
* 通过一次单击，创建 [DevOps 工具链](../services/ContinuousDelivery/index.html#cd_getting_started)
* 使用[命令行界面](/docs/cli/idt/index.html)进行本地开发

要了解 {{site.data.keyword.cloud_notm}} 开发者体验可以如何帮助您快速构建高质量的生产就绪型应用程序，下面我们来更详细地了解一下这些元素。

## 开发者仪表板
{: #dev-dashboards}

{{site.data.keyword.cloud_notm}} 有适用于不同关注领域（如 Watson、安全性或财务）或数字渠道（如移动或 Web 应用程序）的开发者仪表板。可以通过**菜单**图标 ![“菜单”图标](../icons/icon_hamburger.svg) 来访问这些仪表板。

每个开发者仪表板都提供与仪表板的焦点区域相关的初学者工具包，并提供一致的直观工作流程，支持您在几分钟内创建有效的生产就绪型应用程序。

## 应用程序项目
{: #app-projects}

项目是构成应用程序的代码、数据、服务和工具链的关联。例如，{{site.data.keyword.cloud_notm}} 移动项目包含应用程序和后端逻辑、数据存储、分析和安全服务的代码，并设置用于持续交付。

![复用](images/garage_reuse2.png "通过“开发者体验”，可以复用而避免重新创作")

您可以使用任何 {{site.data.keyword.cloud_notm}} 开发者仪表板或 {{site.data.keyword.dev_cli_notm}} 来创建和管理项目。

## 初学者工具包
{: #starter-kits}

通过初学者工具包，{{site.data.keyword.cloud_notm}} 可按您选择的语言来组合框架生产应用程序，以准备好进行云部署。每个初学者工具包中都包含针对特定用例的语言、框架和模式，并支持复用代码。

### 初学者工具包与样本有何不同？
初学者工具包是生产就绪型的，专注于使用运行时（例如，Node.js 和 Express）来演示关键模式实现。在某些情况下，初学者工具包会提供简单的用户体验来着重强调服务的集成。在另一些情况下，初学者工具包表示对复杂用例的可定制实现。

* **片段**是通常在 IDE 中显示的一些代码行。片段可帮助开发者与编程语言语法集成，或支持与定义的 API 集成。
* 通常，**演示**的质量和精确度较高，并且会使用一系列服务和集成点。演示通常需要设置时间，并用于证明业务问题或演示平台功能。演示还用于评估采用云的阶段。有时，演示代码会包含在生产代码中。
* **样本**是特定特征、功能、服务或用户旅程组成的一个小示例。样本可以复用于或包含在生产应用程序中。样本通常用于显示技术功能以及用于解决技术问题的可行方法。
* **初学者工具包**是一种生产就绪型模式，可与一组服务集成，用于生成可直接部署到 DevOps 管道和 Kubernetes 集群的生产就绪型资产。初学者工具包中包含描述性元数据，为用户提供了足够的信息来了解该工具包的功能和用途。另外还包含指示 {{site.data.keyword.cloud_notm}} 生成哪些内容的指示信息。输出是现成的生产就绪型内容，并可根据 IBM 最佳实践对其进行迭代以获得进一步的增强功能。初学者工具包的内容不像演示那么复杂，也不像片段或样本那么简单。这些内容是根据开发者的需求动态创建的。

## 自动供应的资源
{: #auto-provision}

如果初学者工具包指定了所需资源，那么在创建项目时，{{site.data.keyword.cloud_notm}} 会自动创建这些资源的实例。请注意，在创建项目后，还可以向项目手动供应资源或选择现有资源实例以添加到项目。您可以在“项目详细信息”视图中查看与项目关联的服务实例列表，还可在需要时在其中查看凭证。

## 可移植代码
{: #portable-code}

从初学者工具包创建应用程序会自动创建与运行时无关的统一格式代码。您可以将代码原封不动地部署到所选环境中，例如 Kubernetes 或 Cloud Foundry。

### 创建的是什么代码？
通过 {{site.data.keyword.cloud_notm}} 初学者工具包创建的代码具有四个基本组成部分：用例逻辑、语言组件、服务支持和云支持。生成这些组成部分可节省您宝贵的时间，并确保使用的是同类中最佳的体系结构。

* **用例逻辑**提供了特定用例核心功能的代码。例如，Watson Conversation 聊天机器人的代码或移动可视识别应用程序的代码。
* **语言组件**是特定于为初学者工具包选择的编程语言的代码组件和文件。例如，node.js 程序员需要 package.json 文件进行依赖关系管理，并且会自动创建此文件。
* **服务支持**是支持应用程序连接到并使用向项目添加的服务的代码。服务支持项的示例包括凭证管理、初始化代码和特定于服务的 SDK。
* **云支持**是支持应用程序在 {{site.data.keyword.cloud_notm}} 上运行的代码。例如，用于支持应用程序在 {{site.data.keyword.cloud_notm}} Kubernetes 集群上运行的 Helm 图表。

{{site.data.keyword.cloud_notm}} 生成的应用程序不仅在体系结构上成熟可靠，还反映了为项目所选语言的最佳实践。  

项目包含一个自述文件，其中包含项目的技术详细信息，并说明了应用程序未自动运行时，需要做什么来使应用程序运行。
{: tip}

## DevOps 工具链
{: #devops}

DevOps 包含用于访问、开发、部署和操作应用程序的过程和工具。DevOps 工具链是一组自动执行 DevOps 任务的链接服务。可以使用非常简单的应用程序来手动执行 DevOps，但是随着应用程序越来越复杂，自动化的需求会迅速增加，因此工具链自动化是持续交付的必备功能。

DevOps 工具链的核心组件是代码版本控制存储库，例如 GitHub。其他工具可能包括待办事项跟踪、Delivery Pipeline、IDE 和监视服务，例如 [{{site.data.keyword.cloud_notm}}DevOps Insights](../services/DevOpsInsights/index.html#gettingstarted)。

如果已使用初学者工具包创建了项目，那么只需通过单击“项目详细信息”视图中的**部署到云**，就可创建新工具链并部署应用程序。这将创建一个包含代码存储库、问题存储库、Delivery Pipeline 和 Web IDE 的工具链。

然后，可以在此工具链上进行构建，以容纳多个团队，部署到单独的环境进行开发、测试和生产，以及为应用程序建立企业级协作式持续交付模型。  

![持续交付](images/garage_continuous_delivery2.png "开发者体验用于将持续交付设置到开发分支中")

您还可以通过单击开发者仪表板的“项目概述”页面上的**下载**按钮来快速查看项目代码。代码会下载为包含完整项目结构的 `.zip` 文件。您可以使用 {{site.data.keyword.dev_cli_notm}} 轻松解压缩该文件并在本地运行代码，或者将其添加到代码管理存储库。

## 命令行界面
通过 {{site.data.keyword.dev_cli_notm}}，可以在本地编码、构建和运行项目。常用的模式是通过开发者仪表板创建项目，使用 {{site.data.keyword.dev_cli_notm}} 在本地进行开发，然后将更新推送到存储库并合并以启动部署工具链。

## Garage Method 开发
{: #developer_concepts}

查看 [Garage Method](https://www.ibm.com/cloud/garage/)，以了解 IBM 可以如何帮助您在组织中开发应用程序。  

![Garage Method 各阶段概览图](images/garage_phases_overview2.png "Garage Method 各阶段概览图")*Garage Method 各阶段概览图*

{{site.data.keyword.cloud_notm}} 使用 Garage Method 或您偏爱的任何方法，帮助您生成成功的企业级生产应用程序。为了更好地了解 {{site.data.keyword.cloud_notm}} 能为开发者提供哪些功能，下面我们来快速了解一下构建现代应用程序所需的技能。

## 开发者技能
{: #skills}

如今，用户希望应用程序具备比以往任何时候都要多的功能。他们希望应用程序能根据存储的数据和实时数据提供深入的洞察力，始终可用，以及更贴合自己的个人需求。为了满足这些期望，应用程序创建者需要将许多不同的技能集整合在一起。例如，复杂的认知应用程序可能需要数字开发者、云本机开发者、流开发者、数据研究员和 DevOps 专家等多方的贡献。

 ![开发者类型](images/developer_skills.png "开发者关系")

* **数字开发者**针对特定数字渠道（例如，移动 Web、语音和交谈）编写内容。数字开发者通常专注于用例和直接满足用户需求，以此作为综合体验。
* **云本机开发者**专门构造云组件并将其相互连接起来。微服务和服务于前端的后端创建者属于此类别。
* **流开发者**专注于处理数据流，并从数据流中获得洞察力。例如，流开发者可以对传入文本、语音或视频流执行分析并启动操作。
* **数据研究员**使用分析和机器学习来生成预测模型。这些模型用于业务度量值，并为应用程序用户提供深入的洞察力。
* **DevOps 专家**是解决部署和工具链问题的专家。对于简单应用程序，通常并不需要专门的专家，因为开发团队成员会组成队伍来管理 DevOps。但是对于复杂的企业应用程序，存在大量依赖关系，DevOps 专家对于保持生产应用程序平稳运行就至关重要。

{{site.data.keyword.cloud_notm}} 中内置的开发者功能与这些技能集相对应，并支持团队使用一个平台来生成、交付、运行和管理应用程序。例如，创建移动应用程序的数字开发者可以使用 {{site.data.keyword.cloud_notm}} [Mobile 开发者仪表板](https://console.bluemix.net/developer/mobile/dashboard)，认知应用程序构建者可以将 [Watson 开发者仪表板](https://console.bluemix.net/developer/watson/dashboard)与 [Watson Studio](https://console.bluemix.net/catalog/services/watson-studio) 一起使用，流开发者可以使用 [IBM Real-Time Analytics](../services/StreamingAnalytics/index.html#gettingstarted)，[{{site.data.keyword.cloud_notm}} Continuous Delivery 服务](../services/ContinuousDelivery/index.html#cd_getting_started)则简化了 DevOps 专家的工作。

准备好开始了吗？[单击此处](../apps/index.html)立即在 {{site.data.keyword.cloud_notm}} 上构建应用程序！

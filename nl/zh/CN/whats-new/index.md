---

copyright:

  years: 2015, 2018

lastupdated: "2018-11-16"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# {{site.data.keyword.Bluemix_notm}} 中的新增功能
{: #whatsnew}

及时获取 {{site.data.keyword.Bluemix}} 中提供的新功能和服务，以便最充分地利用 {{site.data.keyword.Bluemix_notm}} 体验。我们将更新组织为以下类别：[{{site.data.keyword.Bluemix_notm}} 平台](index.html#platform_category)、[{{site.data.keyword.Bluemix_local_notm}} 和 {{site.data.keyword.Bluemix_dedicated_notm}}](index.html#dedicatedandlocal)、[计算](index.html#compute_category)和[服务](index.html#services_category)。
{:shortdesc}

## {{site.data.keyword.Bluemix_notm}} 平台
{: #platform_category}

### 已更新 {{site.data.keyword.cloud_notm}} 的全球位置名
最新更新日期：2018 年 11 月 1 日

{{site.data.keyword.cloud_notm}} 继续扩展我们的全球可用性占用量，我们将更新位置命名结构，以便更好地支持全球各地地理区域、区域和数据中心的可理解、一致的层次结构。如果您熟悉我们当前的全球区域，那么将会识别像美国南部和悉尼这样的名称。我们正在将这些位置名称与数据中心实际存在的城市的名称对应。

现在，程序化标识未更改，所以从 API 的角度来看没有影响。下表显示新旧位置名称。有关更多信息以及数据中心与区域的完整列表，请参阅[服务可用性](docs/resources/services_region.html)。

|原位置显示名称| 新位置显示名称| 代码|
|----------|---------|---------|
|美国南部|达拉斯| us-south | 
|美国东部|华盛顿特区| us-east |
|英国|伦敦| eu-gb |
|德国| 法兰克福| eu-de |
|悉尼|悉尼| au-syd |
|亚太地区北部|东京| jp-tok |
{: caption="表 1. 新位置名称" caption-side="top"}

### 将帐户管理访问权分配给其他人
最新更新日期：2018 年 10 月 30 日

使用 {{site.data.keyword.cloud_notm}} Identity and Access Management (IAM)，您可以将作为帐户管理员完成的常见任务委派给帐户中的其他用户。通过在一个或所有可用帐户管理服务上创建访问策略，您可以轻松委派责任，如邀请和除去用户，管理访问组，管理服务标识，维护私有目录服务，甚至监视计费和跟踪使用情况。有四个单独的帐户管理服务和一个可用于设置访问策略的“所有服务”选项：

* 用于邀请和除去用户的用户管理
* 用于创建、编辑、删除、更新和分配访问权的 IAM 访问组 
* IAM 身份服务，用于查看、创建、删除和分配对整个帐户中的服务标识和关联的 API 密钥的访问权
* 用于查看私有目录产品并更新这些产品的元数据和可视性的全球资源目录
* 所有帐户管理服务，用于根据分配的角色访问每个帐户管理服务选项，以及访问计费和使用情况跟踪。


有关用户基于对其拥有策略的帐户管理服务和为其分配的角色而可以执行的任务的更多信息，请参阅[帐户管理服务的平台管理角色和操作示例](/docs/iam/users_roles.html#platformrolestable2)。有关这个新功能的更多信息，请参阅 [Introducing More Flexibility and Control for IBM Cloud Account Management Services Access](https://www.ibm.com/blogs/bluemix/2018/11/introducing-more-flexibility-and-control-for-ibm-cloud-account-management-services-access/){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标") 博客帖子。 


### 搜索资源
最新更新日期：2018 年 7 月 17 日

您可以在 {{site.data.keyword.cloud_notm}} 控制台中的任何位置搜索资源。在控制台菜单栏的搜索字段中输入资源的名称。请按正斜杠键 (/) 以激活搜索。

### 将联合用户动态添加到访问组
最新更新日期：2018 年 7 月 12 日

您可以创建动态规则，以根据特定身份属性自动将联合用户添加到访问组。当用户使用联合标识登录时，身份提供者中的数据会根据设置的规则，将用户动态映射到访问组。有关更多信息，请参阅[为访问组创建动态规则](/docs/iam/accessgroup_rules.html#creating-dynamic-rules-for-access-groups)。

### 保护服务标识和 API 密钥
最新更新日期：2018 年 6 月 1 日

为了避免因删除服务标识或 API 密钥而导致停机或中断的情况，您可以选择使用 UI 或 CLI 锁定服务标识和 API 密钥。锁定服务标识还可以防止变更、删除或分配任何访问策略，以及创建或删除与服务标识相关联的任何 API 密钥。有关更多信息，请参阅[锁定服务标识](/docs/iam/serviceid.html#locking-a-service-id)和[锁定 API 密钥](/docs/iam/userid_keys.html#locking-an-api-key)。

### 将轻量帐户升级为预订帐户
最新更新日期：2018 年 5 月 31 日

您现在可以直接从 {{site.data.keyword.Bluemix_notm}} 控制台将轻量帐户升级到预订帐户。有了预订帐户，您可以同时使用平台和基础架构产品，并通过做出每月开支和期限承诺来享受折扣定价。通过每月付款安排支付固定结算费用，还可避免意外，同时又可以根据需求灵活地选择多订购或少订购。有关更多信息，请参阅[预订帐户常见问题解答](/docs/billing-usage/billing-faq.html#subscription-faqs)。 

### {{site.data.keyword.Bluemix_notm}} CLI 更名
最新更新日期：2018 年 5 月 15 日

{{site.data.keyword.Bluemix_notm}} CLI 命令已从 `bluemix` 和 `bx` 更改为 **ibmcloud**。但是，您仍然可以使用 `bluemix` 和 `bx` CLI 命令，直到未来某个日期这些命令被除去为止。
此时没有短名称，只有全名 **ibmcloud**。 

### {{site.data.keyword.Bluemix_notm}} 帐户的多因子认证
最新更新日期：2018 年 5 月 2 日

多因子认证 (MFA) 可为帐户提供额外一层的安全保护，因为它会要求所有用户在登录期间除了提供标准 IBM 标识和密码外，还要提供基于时间的一次性密码。通常，这也称为双因子认证 (2FA)。MFA 是按帐户启用的，一旦启用后，帐户中的所有用户都必须采用这个额外的安全措施进行登录。

有关更多信息，请参阅 [IBM Cloud Platform now adds support for Multi-Factor Authentication ](https://www.ibm.com/blogs/bluemix/2018/05/ibm-cloud-platform-now-adds-support-multi-factor-authentication/){: new_window}![外部链接图标](../../icons/launch-glyph.svg "外部链接图标") 博客帖子。

### 使用访问组快速分配访问权
最新更新日期：2018 年 4 月 3 日

您是否希望能够尽可能使用最少量的策略来快速分配访问权？现在，您可以使用访问组。访问组支持将一组用户和服务标识分组到一起，然后分配应用于该组中所有成员的单个策略。通过使用访问组，可以限制管理帐户中用户和服务标识访问权所花费的时间。有关更多详细信息，请查看博客帖子[新功能：访问组](https://www.ibm.com/blogs/bluemix/2018/04/access-groups/){: new_window}
![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")。

### SoftLayer 与 {{site.data.keyword.Bluemix_notm}} 帐户链接
最新更新日期：2018 年 3 月 1 日

您可以将 SoftLayer 帐户链接到 {{site.data.keyword.Bluemix_notm}} 帐户，以登录到单个位置（即 {{site.data.keyword.Bluemix_notm}} 控制台），然后可同时访问基础架构即服务 (IaaS) 和平台即服务 (PaaS) 资源。如果您还不熟悉 {{site.data.keyword.Bluemix_notm}}，请创建并链接帐户以获取免费 {{site.data.keyword.Bluemix_notm}} 轻量帐户。或者，如果您已经有可访问 PaaS 资源的 {{site.data.keyword.Bluemix_notm}} 帐户，请链接您的帐户以接收含有 IaaS 和 PaaS 资源的单个帐单。请查看[链接 IaaS 和 PaaS 帐户的步骤](https://www.ibm.com/blogs/bluemix/2018/03/follow-steps-link-iaas-paas-accounts/){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标") 以快速链接帐户。


### 现在，{{site.data.keyword.Bluemix_notm}} Foundry 服务在美国东部区域可用
最新更新日期：2017 年 12 月 15 日

现在，新的美国东部数据中心在华盛顿可用。此新区域可以使用 `us-east.bluemix.net` 端点进行访问。有关在此新区域中可购买的服务的详细信息，请参阅[按区域列出的服务](/docs/resources/services_region.html#services_region)。

### 支持欧盟中的资源
最新更新日期：2017 年 12 月 14 日

如果您的服务和数据中心位于欧洲，现在 {{site.data.keyword.Bluemix_notm}} 提供了额外的功能来保护您在欧盟的数据。您可以请求位于欧洲的客户成功团队提供支持。此支持全天候可用。有关更多信息，请参阅[启用“欧盟支持”选项](/docs/billing-usage/eusupported.html#bill_eusupported)和[请求对欧盟中资源的支持](/docs/get-support/howtogetsupport.html#eusupported)。

### 撤销对 TLS 1.0 和 1.1 的支持
最新更新日期：2017 年 11 月 28 日

2018 年 3 月 1 日，{{site.data.keyword.Bluemix_notm}} 将撤销对许多云产品和服务上 TLS 1.0 和 TLS 1.1 的支持；我们致力于提供高度安全且符合安全和数据隐私业界最佳实践的云，此更改正是这一工作的一部分。要了解有关此更改如何影响您以及您可能需要采取的措施的更多信息，请参阅[撤销对 TLS 1.0 和 1.1 的支持](/docs/troubleshoot/appsectls.html)。

### 新增组织帐户中资源的方法
最新更新日期：2017 年 11 月 16 日

资源组是供您创建可定制帐户资源分组的新方法，并且对组的访问权以及组内的资源均使用 Identity and Access Management (IAM) 进行管理。所有人一开始只有缺省资源组。您可以重命名此资源组，并且可以在目录中创建新服务实例时，向此资源组添加这些服务实例。

如果您是使用现买现付或预订帐户的用户，那么可以创建其他资源组，以便更轻松地管理配额以及查看一组资源的计费使用情况。您还可以对资源进行分组，从而更轻松地为用户一次性分配对多个服务的访问权。要了解有关使用帐户的资源组的更多信息，请参阅[管理资源组](/docs/account/resourcegroups.html#rgs)。

### {{site.data.keyword.Bluemix_notm}} IAM 更新
最新更新日期：2017 年 11 月 16 日

在 {{site.data.keyword.Bluemix_notm}} 帐户内引入的[资源组](/docs/overview/resource-groups.html#whatis)为您分配访问权开辟了一条新的道路。可以为用户和服务标识分配对资源组内所有服务的访问权，从而使您可以一次性快速分配对多个资源的访问权。您还可以通过为每个用户或服务标识只分配对资源组内某些服务的访问权来定制访问权，或者仅选择分配对向下一直到服务实例级别的单个资源的访问权。

有关可以通过 IAM 来利用的功能的更多信息，请参阅 [IAM 提供了哪些功能？](/docs/iam/index.html#features)

### 定制仪表板视图
最新更新日期：2017 年 11 月 16 日

可以在 {{site.data.keyword.Bluemix_notm}} 控制台的仪表板中，查看和管理帐户中的所有资源。现在，可以设置过滤器来定制视图。例如，可以按资源组进行过滤，以查看资源组中的特定资源。还可以按区域或按 Cloud Foundry 空间进行过滤。有关更多详细信息，请参阅[在仪表板上管理资源](/docs/overview/ui.html#dashboardview)。


### 支持中心
最新更新日期：2017 年 11 月 2 日

现在，我们有了新的支持中心，在其中可以搜索信息，向开发者社区发布问题以及管理凭单。在 {{site.data.keyword.Bluemix_notm}} 控制台菜单栏中，转至**支持 > 支持中心**。

### 推出 IBM Cloud
最新更新日期：2017 年 10 月 31 日

Bluemix 现已更名为 IBM Cloud。除了推出新名称外，没有更改其他任何内容。您仍可以像平时一样，轻松地构建和运行应用程序和服务。有关更多详细信息，请参阅 [IBM Cloud 博客](https://www.ibm.com/blogs/bluemix/2017/10/bluemix-is-now-ibm-cloud/){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")。

### 轻量帐户
最新更新日期：2017 年 10 月 31 日

轻量帐户是我们的新帐户类型，让您有权免费试用精选服务，而没有时间限制。这个新帐户还包含使用情况跟踪和效率功能，可帮助您更好地管理资源。要了解可用功能的更多信息，请参阅[帐户类型](/docs/account/index.html#liteaccount)。

### Identity and Access Management 应用程序认证功能
最新更新日期：2017 年 10 月 6 日

现在，Identity and Access Management (IAM) 提供了创建服务标识的功能，您可以将其视为可供应用程序用于向 {{site.data.keyword.Bluemix_notm}} 服务进行认证的身份。服务标识可以使用以服务策略形式分配给服务标识的关联 API 密钥和访问许可权（而不使用个人用户凭证）进行创建，以便您可控制使用该标识进行认证的任何应用程序的访问级别。

有关此功能的优点以及如何开始使用的更多信息，请参阅 [Introducing IBM Cloud IAM Service IDs and API Keys](https://www.ibm.com/blogs/bluemix/2017/10/introducing-ibm-cloud-iam-service-ids-api-keys/){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")。

### {{site.data.keyword.Bluemix_notm}} 全局目录
最新更新日期：2017 年 7 月 27 日

上一次控制台更新后可在控制台中从单个位置管理公共区域，基于此更新进行扩展，{{site.data.keyword.Bluemix_notm}} 现在拥有全局目录，进一步简化了从目录中选择和部署项的过程。不管您在控制台中选择了哪个区域，现在都可以在目录中查看所有公共区域中可用的所有服务。在目录中选择一个磁贴后，即可以看到在其中该服务可用的区域，然后选择要在其中部署该服务的区域。

有关目录最新更新的更多信息，请参阅 [A global {{site.data.keyword.Bluemix_notm}} catalog makes building things easier](https://www.ibm.com/blogs/bluemix/2017/07/global-bluemix-catalog-makes-building-things-easier/){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")。

### {{site.data.keyword.Bluemix_notm}} 控制台更新
最新更新日期：2017 年 5 月 23 日

现在，您可以通过更新的 {{site.data.keyword.Bluemix_notm}} 控制台在单个位置管理各公共区域。区域选择器简化了访问资源的过程；其他增强功能包括可用性更高、性能更佳。

有关此更新的更多信息，请查看 [New Global Bluemix UI for Higher Availability and More](https://www.ibm.com/blogs/bluemix/2017/05/new-global-bluemix-ui-higher-availability/){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")。

### Identity and Access Management
最新更新日期：2017 年 5 月 1 日

通过最新的更新和改进，现在 {{site.data.keyword.Bluemix_notm}} 帐户所有者或管理员可以使用新的统一访问控制 UI 来利用以下功能：
 * 采用新的访问控制功能后，可管理用户对 Kubernetes 服务和其他服务的细颗粒度访问权
 * 为其组织内的用户分配服务策略和 Cloud Foundry 角色

此外，{{site.data.keyword.Bluemix_notm}} 平台用户还可以创建、删除和列出与其用户标识关联的 API 密钥。平台用户在使用 API 或 CLI 时，可以使用这些 API 密钥进行认证。

最后，我们增强了统一用户管理能力，确保在链接的 IaaS-PaaS 帐户中统一管理用户，而无需在 SoftLayer 客户门户网站或 {{site.data.keyword.Bluemix_notm}} 控制台中单独添加用户。

有关最近更新的更多信息，请查看 [Introducing Identity & Access Management](https://www.ibm.com/blogs/bluemix/2017/05/introducing-identity-access-management/){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标") 博客帖子。

### 更改了 {{site.data.keyword.Bluemix_notm}} 文档的导航设计
最新更新日期：2017 年 4 月 13 日

借助这次导航更新，我们相信您可以更好地了解整个文档中的内容组织方式，并且能够更高效地查找相关内容。由于内容的嵌套层更少，您不必再四处搜寻来查找成功使用 {{site.data.keyword.Bluemix_notm}} 所需的文档。


## {{site.data.keyword.Bluemix_local_notm}} 和 {{site.data.keyword.Bluemix_dedicated_notm}}
{: #dedicatedandlocal}

### 管理控制台 2 月更新
{: #febadminconsole}
最新更新日期：2018 年 2 月 28 日

通过 2018 年 2 月的最新更新，您可以使用以下新功能：

#### 用于管理维护更新的新许可权

引入了新的用户许可权，专门允许用户批准和重新安排维护更新，还允许用户设置维护更新时段，以规定何时可将维护更新部署到专用环境中。有关更多信息，请参阅[视频演示](https://youtu.be/7c7jyp_JJWU){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")。

### 管理控制台 12 月更新
{: #decemberadminconsole}
最新更新日期：2017 年 12 月 14 日

通过 12 月的最新更新和改进，您可以使用以下新功能：

#### 预订平均 CPU 使用率阈值的通知

平均 CPU 已添加为通知预订中的阈值类型。现在，您可以在 CPU 使用率（在所有 DEA 和 Diego 单元上的平均值）高于或低于特定阈值时收到通知。

#### 控制对欧盟云系统的访问

现在，管理控制台合并了在欧盟地区（首先是法兰克福）支持云资源的新功能，能够定义用于控制 IBM 人员访问权的策略。您可以管理访问控制策略，查看访问请求，对请求执行操作以及跟踪历史记录。

#### 增强了安全报告中的信息

现在，安全报告中除了用户和组织的唯一标识外，还包含用户友好的名称。

### 管理控制台 8 月更新
{: #augustadminconsole}
最新更新日期：2017 年 8 月 31 日

通过 8 月的最新更新和改进，您可以使用以下新功能：

#### {{site.data.keyword.cloudant_short_notm}} 服务使用情况度量值更新

  * 更新了对 {{site.data.keyword.cloudant_short_notm}} 使用情况度量值的计算，以反映出 {{site.data.keyword.cloudant_short_notm}} 集群中所有节点上的已用 GB 和可用 GB 总量。通常，{{site.data.keyword.cloudant_short_notm}} 集群包含 3 个节点，并且数据库中的文档将在集群中的所有节点上进行复制，以实现高可用性和灾难恢复。通过 8 月更新，{{site.data.keyword.cloudant_short_notm}} 对话框（在_资源使用情况 > 服务_视图中提供）中的容量度量值指示集群中所有节点上的空间。例如，如果单个 {{site.data.keyword.cloudant_short_notm}} 集群中包含 3 个节点，每个节点的容量是 1000 GB，那么容量限制将为 3000 GB。如果已使用该容量中的 1500 GB，那么 {{site.data.keyword.cloudant_short_notm}} 使用情况度量值将为 50%。

#### 维护安排更新

  * 在 {{site.data.keyword.Bluemix_dedicated_notm}} 中，客户可以管理其专用环境可用于部署系统更新的日期和时间。客户可以定义可用时段，这表示维护更新可以和不可以部署到其专用环境的日期和时间。在 8 月更新中，_可用更新时段_已重命名为_更新时段_，_不可用更新时段_已重命名为_中断时段_。除了术语变化外，现在客户在定义中断（不可用）日期时有更大的灵活性和余地。中断日期在请求后需要 IBM 批准，多长时间能获得批准不一定。IBM 在批准了请求的中断日期之后，会取消当前安排在不可用时段中的所有现有更新。IBM 还会为这些更新创建新记录，并将其安排在批准的中断日期以外的时间。

有关更多信息，请参阅[视频演示](https://bit.ly/2eCQNvu){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")。

### 管理控制台 7 月更新
{: #julyadminconsole}
最新更新日期：2017 年 7 月 31 日

通过 7 月的最新更新和改进，您可以使用以下新功能：

#### 资源使用情况历史记录功能更新

  * 在之前的更新（6 月）中，内存和磁盘使用情况的“历史记录”视图引入了显示过去 48 小时、30 天和 5 个月使用情况数据的功能。在这次最新的 7 月更新中，资源使用情况历史记录功能经过扩展，允许定制显示其资源使用数据的时间范围。每小时、每天和每月视图仍然保留，但现在用户可以指定显示其内存和磁盘使用情况度量值的开始日期/时间和持续时间（例如，显示自 2017 年 7 月 1 日起 15 天的内存使用情况）。
  * 引入了新的 CLI 命令，用于在 CLI 中显示资源度量值历史记录。该命令的参数以及用法示例可以通过输入以下命令找到：`_cf ba resource-metrics-history -help_`

有关更多信息，请参阅[视频演示](https://youtu.be/QBij0jB5qAk){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")。

### 管理控制台 6 月更新
{: #juneadminconsole}
最新更新日期：2017 年 6 月 26 日

通过 6 月的最新更新和改进，您可以使用以下新功能：

#### 资源使用情况页面更新

  * 系统资源
    * 内存和磁盘的“历史记录”视图已更新为显示 48 小时、30 天和 5 个月的数据
    * 提供了“了解更多”链接，用于显示管理控制台度量值 API 如何用于生成“历史记录”视图
  * 应用程序
    * 提供环境中所有应用程序的使用情况信息
    * 按应用程序名称、物理内存、保留内存、物理磁盘、保留磁盘、物理 CPU 或组织名称排序
    * 提供了搜索功能，用于按应用程序名称和组织名称过滤结果
    * 提供了“了解更多”链接，用于显示管理控制台度量值 API 如何用于生成“应用程序”视图

有关更多信息，请参阅[资源使用情况](/docs/hybrid/index.html#resourceusage)。

#### 用于度量值的 API 更新

  * 添加了环境统计信息，可按天或按月提供内存和磁盘消耗量的平均值

有关更多信息，请参阅[用于度量值的 API](/docs/hybrid/index.html#envappmetricsapi)。


### 管理控制台 5 月更新
{: #mayadminconsole}
最新更新日期：2017 年 5 月 30 日

通过 5 月的最新更新和改进，您可以使用以下新功能：

 * 改进了“状态”页面，包含对影响 {{site.data.keyword.Bluemix_notm}} 平台和运行时的事件进行更详细的诊断。
 * 改进了安全性“报告和日志”页面：
   * 现在，报告以表格式显示，简化了报告浏览和搜索，包括按报告类别、文件名或创建日期排序的功能。
   * 增强了过滤功能，包含同时过滤多个类别的功能
   * 全屏方式显示报告内容
   * 具有“报告写入”许可权的管理员用户可以删除报告
   * 报告列表显示速度更快，可通过连续滚动以渐进方式按需装入，从而提高了总体性能。
 * 可以按需请求时间范围最长为一周，且起始时间早于请求时间最长 3 个月的安全报告。请注意，需要进行一些特定于环境的配置后，管理用户才能使用此功能。管理员用户需要具备“报告写入”许可权才能使用此功能。

### 管理控制台 4 月更新
{: #apriladminconsole}
最新更新日期：2017 年 5 月 2 日

通过 4 月的最新更新和改进，您可以使用以下新功能：

 * 新设计了 {{site.data.keyword.Bluemix_notm}} Dedicated 和 Local 环境的状态应用程序。您可以按组件名称或发布日期快速进行搜索。您还可以在组件状态发布视图和特定于环境的通知之间进行切换。有关更多信息，请参阅 [New {{site.data.keyword.Bluemix_notm}} Status Page](https://www.ibm.com/blogs/bluemix/2017/05/new-bluemix-status-page/){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标") 博客帖子。
 * 通过“资源使用情况”磁贴访问精选服务的服务使用情况数据。有关支持哪些服务以及新视图中提供的功能的更多信息，请参阅[服务使用情况详细信息](/docs/hybrid/index.html#servicesresourceusage)。

## 计算
{: #compute_category}

### 虚拟服务器功能
最新更新日期：2018 年 11 月 16 日

以下功能目前可用于 {{site.data.keyword.BluVirtServers_full}} 产品。

#### 不使用实例时暂停计费
想要仅为您使用的功能付费吗？您现在可以暂停对虚拟服务器实例的计费。暂停计费功能适用于具有每小时公共类型模板大小和 SAN 支持的存储器的虚拟服务器实例。当您将支持暂停计费功能的虚拟服务器电源关闭时，某些计算资源将不会产生费用。计费会在您关闭服务器电源时自动停止。暂停计费功能可帮助您降低成本，而且当您需要使用虚拟服务器的资源时，也不必重新供应虚拟服务器。有关更多信息，请参阅[关于暂停计费](/docs/vsi/vsi_about_suspend.html)或 {{site.data.keyword.cloud_notm}} [博客帖子 ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")](https://www.ibm.com/blogs/bluemix/2018/10/suspend-billing-1-minute-granularity-virtual-servers/){: new_window}。

#### 保留资源以供将来的虚拟服务器实例使用
{{site.data.keyword.BluVirtServers_full}} 保留实例功能现在可供您使用。如果您想要为将来的部署提供可靠的资源以及节省成本，那么这是一个不错的选择。您可以选择一年或三年合同期的保留容量。在保留容量内，您最多可以保留一组 20 个具有特定大小的虚拟服务器实例，以便在需要时进行供应。在合同期限内，您可以在所选 POD 和数据中心内获得此保证容量。有关更多信息，请参阅[保留的虚拟服务器](/docs/vsi/vsi_about_reserved.html)。

#### 将映像从 {{site.data.keyword.cos_full_notm}} 服务实例导入到 {{site.data.keyword.cloud_notm}} 基础架构中
{{site.data.keyword.cloud_notm}} 基础架构现在可与 {{site.data.keyword.cloud_notm}} 控制台上供应的 {{site.data.keyword.cos_full_notm}} 服务进行交互。{{site.data.keyword.cos_full_notm}} 提供了 Aspera 高速传输插件，可大幅减少上传大映像所需的时间量。将映像上传到 {{site.data.keyword.cos_full_notm}} 后，您可以从 {{site.data.keyword.cos_full_notm}} 将[映像导入](/docs/infrastructure/image-templates/import-image.html)到 {{site.data.keyword.cloud_notm}} 基础架构中。也可以从 {{site.data.keyword.cloud_notm}} 基础架构将[映像导出](/docs/infrastructure/image-templates/export-image-ibm-cos.html)到 {{site.data.keyword.cos_full_notm}} 中。

#### 虚拟服务器实例放置组
放置组现在可用于 {{site.data.keyword.BluVirtServers_full}}。有了放置组，您就可以使用公共实例在数据中心内实现高可用性，或在更大的部署中提供额外级别的容错。有关更多信息，请参阅[放置组](/docs/vsi/vsi_placegroup.html)。 

### buildpack 的最新更新

请访问以下页面获取最新更新的累积列表：

* [SDK for Nodejs buildpack 的最新更新](/docs/runtimes/nodejs/updates.html#latest_updates)
* [Liberty buildpack 的最新更新](/docs/runtimes/liberty/updates.html#latest_updates)
* [ASP.NET 核心 buildpack 的最新更新](/docs/runtimes/dotnet/updates.html#latest_updates)
* [IBM XPages for {{site.data.keyword.Bluemix_notm}} buildpack 的最新更新](/docs/starters/xpages/index.html#updates)

### {{site.data.keyword.containerlong_notm}} 的最新更新

{{site.data.keyword.containerlong_notm}} 于 2017 年 5 月推出了其 Kubernetes 体系结构。先前的单个和可扩展容器组体系结构现已[完全弃用（自 2017 年 12 月 5 日开始）](https://www.ibm.com/blogs/bluemix/2017/07/deprecation-single-scalable-group-container-service-bluemix-public/){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")。  

[有关 {{site.data.keyword.Bluemix_notm}} 上本机 Kubernetes 环境入门的信息，请参阅相关文档](/docs/containers/container_index.html)。如果您有任何疑问，可以将问题发布到 Slack：https://ibm-container-service.slack.com/。


### {{site.data.keyword.containerlong_notm}} 现在配备了高度可用的 Kubernetes 主节点
最新更新日期：2018 年 11 月 7 日

通过新的高度可用 Kubernetes 主节点功能，您可以获得更高的集群可用性。高度可用的 Kubernetes 主节点上设置有 Kubernetes API 服务器、etcd、Kubernetes 调度程序和控制器的多个副本，这些副本都分布在不同的物理主机上。当您创建一个运行 Kubernetes V1.12、1.11 或 1.10 的新集群时，缺省情况下会将 Kubernetes 主节点设置为高度可用。要在运行上述某个 Kubernetes 版本的现有集群中启用此功能，您必须完成[准备步骤](/docs/containers/cs_versions.html#110_ha-masters)。

### 在 {{site.data.keyword.containerlong_notm}} 中创建多专区集群
最新更新日期：2018 年 7 月 10 日

想要提高集群和应用程序的可用性？现在，您可以使集群跨精选城区中的多个专区分布。有关更多信息，请参阅[在 {{site.data.keyword.containershort_notm}} 中创建多专区集群](cs_clusters.html#multizone)。

### Kubernetes 仪表板访问涉及 {{site.data.keyword.containerlong_notm}}
最新更新日期：2018 年 4 月 18 日

现在，{{site.data.keyword.containerlong_notm}} 支持通过 {{site.data.keyword.Bluemix_notm}} 控制台直接访问 Kubernetes 仪表板。这简化了访问仪表板的路径，并增强了集群管理和资源可视化方面的用户体验。有关更多详细信息，可以查阅 [{{site.data.keyword.Bluemix_notm}} 博客 ](https://www.ibm.com/blogs/bluemix/2018/04/kubernetes-dashboard-access/){: new_window}![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")。


### 新增 Liberty for Java buildpack V3.11
最新更新日期：2017 年 7 月 17 日

Liberty buildpack V3.11 提供了新的每月 Liberty 运行时版本，并包含其他改进。每月 Liberty 运行时版本已更新为 [2017.7.0.0](https://developer.ibm.com/wasdev/blog/2017/07/07/beta-websphere-liberty-tools-july-2017/) 发行版。IBM JDK 已更新为 8.0.4.7 和 7.1.4.5 版本。该 buildpack 还提供了更新版本的应用程序管理实用程序和 Auto-Scaling 代理程序。缺省的 Cloudant Library 现在是正式的 [java-cloudant](https://github.com/cloudant/java-cloudant)，[Ektorp 库](https://github.com/helun/Ektorp)仍是可用选项；有关此更改的详细信息，请参阅[博客帖子](https://www.ibm.com/blogs/bluemix/2017/05/default-library-change-cloudant-auto-wiring-liberty-buildpack/)。应用程序内存小于 512 MB 时，缺省堆大小比率现在是 50%。如果大于 512 MB，那么仍是 75%。现在生成了新的编译打包任务日志，这样就更容易对编译打包错误进行调试。有关其他信息，请参阅[最新更新](https://console.ng.bluemix.net/docs/runtimes/liberty/updates.html)文档。

### 新增 Liberty for Java buildpack V3.10
最新更新日期：2017 年 6 月 12 日

Liberty buildpack V3.10 提供了新的每季度和每月 Liberty 运行时版本，并包含其他改进。缺省 Liberty 运行时版本已更新为 17.0.0.2。每月 Liberty 运行时版本已更新为 [2017.5.0.0](https://developer.ibm.com/wasdev/blog/2017/05/12/beta-websphere-liberty-tools-may-2017/){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标") 发行版。该 buildpack 还提供了更新版本的应用程序管理实用程序和 Extreme Scale Client。有关其他信息，请参阅[最新更新](/docs/runtimes/liberty/updates.html)文档。

### 新增 SDK for Node.js buildpack V3.12
最新更新日期：2017 年 5 月 16 日

SDK for Node.js buildpack V3.12 提供了 IBM SDK for Node.js V0.12.17、0.12.18、4.8.0、4.8.2、6.10.0 和 6.10.2。缺省值现在已经从最新 4.x 更改为最新 6.x，所以目前是 6.10.2。这是一项主版本更改，可能会影响依赖该缺省值的应用程序。有关如何避免任何问题的更多信息，请参阅 [Node.js version long-term support and the SDK for Node.js buildpack](https://www.ibm.com/blogs/bluemix/2016/11/node-version-support-and-sdk-buildpack/){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")。

除了新运行时外，此发行版还包含一个 buildpack 错误修订，用于解决使用 App Management Health Center 处理程序以及 Node.js V6.9.5 和 6.10.0 时发生的问题。

### 新增 Liberty for Java buildpack V3.9
最新更新日期：2017 年 4 月 27 日

Liberty buildpack V3.9 提供了新的每月 Liberty 运行时版本，并包含其他改进。缺省 Liberty 运行时版本已更新为包含 PI77770、PI77605、IFPI77438 和 IFPI79275 iFix。每月 Liberty 运行时版本已更新为 [2017.3.0.0](https://developer.ibm.com/wasdev/blog/2017/03/14/beta-websphere-liberty-tools-march-2017/){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标") 发行版。内存计算已从编译打包移动到启动过程，这样更容易在重新启动应用程序时更改堆内存。该 buildpack 还提供了更新版本的 Auto-Scaling 服务代理程序和 Extreme Scale Client。有关其他信息，请参阅[最新更新](/docs/runtimes/liberty/updates.html)文档。

## 服务
{: #services_category}

### 主要 {{site.data.keyword.conversationshort}} 更新
最新更新日期：2018 年 11 月 9 日

{{site.data.keyword.conversationshort}} 拥有新外观和新增功能。名为*工作空间*的工件是用于为聊天机器人提供支持的机器学习模型培训数据的容器，现已被*对话技能*所取代。现在，通过为助手添加对话技能，即可更轻松地进行部署。新的助手层会管理用户与您的技能之间的消息编排。您可以向助手添加内置集成，以便轻松地将对话技能发布到常用消息传递通道。{{site.data.keyword.conversationshort}} 文档已移至新位置。有关更多信息，请参阅[产品文档](/docs/services/assistant/index.html)。


### 使用 Terraform 和 Ansible 自动部署基础架构和应用程序
最新更新日期：2018 年 11 月 2 日

Terraform 和 Ansible 都是开放式源代码软件，可用于自动化云解决方案的整个部署过程。您可以使用 Terraform 来指定 {{site.data.keyword.Bluemix_notm}} 基础架构组件，快速地构建复杂的多层云环境，从而实现“基础架构即代码”(IaC)。然后，可以使用 Ansible 通过专用网络连接到您的计算主机来部署应用程序，构建服务，执行脚本或定义配置。 

要开始学习这两款开放式源代码产品的基础知识，请参阅我们的教程： 
* [使用 Terraform 在 {{site.data.keyword.Bluemix_notm}} 上部署 RedHat OpenShift Container Platform](/docs/terraform/tutorials/install_redhat_openshift.html#redhat){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")
* [使用 Terraform 和 Ansible 在 IBM Cloud 基础架构上部署 WordPress](/docs/terraform/tutorials/wordpress_with_terraform_and_ansible.html#deploy_wordpress){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")。 

### {{site.data.keyword.cloudant_short_notm}} 的最新更新
最新更新日期：2018 年 9 月 28 日

访问以下页面可获取 {{site.data.keyword.cloudant_short_notm}} [最新更新](/docs/services/Cloudant/release_info/release_notes.html#release-notes){:new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标") 的综合列表。

### 推出 {{site.data.keyword.IBM_notm}} {{site.data.keyword.DRA_short}} 一般可用性
最新更新日期：2018 年 9 月 20 日

目前，已在美国南部、德国和英国地区普遍提供 {{site.data.keyword.DRA_short}} 服务。

{{site.data.keyword.DRA_short}} 可帮助团队提高生产力和效率，缩短产品上市时间，还可帮助他们使用 DevOps 工具中的数据轻松地衡量成功与否，或提高代码质量。此服务为企业提供了一个工具，可帮助他们了解所有代码库和团队中的 DevOps 活动。

* **速度**：{{site.data.keyword.DRA_short}} 在单个仪表板中显示所有应用程序的所有分析。
* **质量**：通过实施门限部署策略来降低发布风险。例如，如果有一个关于代码覆盖的策略，那么在选定的容错范围内，{{site.data.keyword.DRA_short}} 会始终防止不符合容错定义的代码发布。随着时间的推移，这些策略会有助于提高部署过程的总体质量。 
* **控制**：通过使用代码覆盖、单元测试和其他工具，测量随着时间的推移团队对其 DevOps 做法中的趋势做出反应时的结果。这些趋势可帮助团队更好地管理他们的 DevOps 做法。

### {{site.data.keyword.security-advisor_long_notm}} Beta 版现在可用！
最新更新日期：2018 年 9 月 5 日

{{site.data.keyword.security-advisor_short}} 中添加了新功能，现在作为 Beta 服务提供。{{site.data.keyword.security-advisor_short}} 将您的 {{site.data.keyword.Bluemix_notm}} 安全性集中到一个仪表板中。除了将信息集中在一起之外，该服务还使用易于导航的磁贴来汇总关键安全信息，以清晰地显示何时检测到安全问题。单击磁贴可以深入查看优先级问题、历史记录以及警报背后的详细信息。要解决问题，请再深入一层查看所有详细信息以及建议的修复方法，从而消除威胁并确保您的环境处于安全状态。

{{site.data.keyword.security-advisor_short}} 将帮助您快速访问控制台，使您能够集中查看和管理 {{site.data.keyword.Bluemix_notm}} 环境中的安全性。

在此版本中，我们提供了：
* 一个发现结果 API
* 自带提供程序的能力
* 对仪表板体验的更新

还有更多精彩呈现！

有关使用入门信息，请参阅 [{{site.data.keyword.security-advisor_short}} 文档](/docs/services/security-advisor/index.html)。

### 推出 {{site.data.keyword.iva_full_notm}} 一般可用性
最新更新日期：2018 年 6 月 26 日

现在，[{{site.data.keyword.iva_full}}](https://console.bluemix.net/catalog/services/voice-agent-with-watson) ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标") 已一般可用！您可以创建基于 Watson 服务构建的认知语音代理程序，客户可以通过电话呼叫该代理程序并与之通话。通过将 Watson 人工智能应用于主干，语音代理程序能以对话方式进行通信，并在语音代理程序内处理复杂的交互和处理客户呼叫。

此发行版引入了以下新功能：

* 添加了冗余 Watson 服务位置以用于灾难恢复。 
* 可编辑高级配置选项以定制语音代理如何转移呼叫，如何向呼叫者播放预先录制的消息，以及如何与 Watson 服务进行交互。
* 在标准服务套餐中可配置最大并发连接数。
* 可将语音代理连接到 SIP 中继提供者（例如，NetFoundry、Twilio、AT&T）及其他服务提供者，或连接到使用 {{site.data.keyword.iva_short}} 的同级。

有关使用入门信息，请参阅 [{{site.data.keyword.iva_short}}](/docs/services/voice-agent/getting-started.html) 文档。

### {{site.data.keyword.streaminganalyticsshort}} 引入了具有基于容器的基础架构的新服务套餐
最新更新日期：2018 年 4 月 20 日

现在，{{site.data.keyword.streaminganalyticsshort}} 在 Kubernetes 基于容器的基础架构上运行，这种基础架构能够为服务提供更高的安全性和可用性。
 
可以使用 [V2 服务套餐](/docs/services/StreamingAnalytics/service_plans.html#service_plans)来访问这个基于容器的新基础架构。您可以选择最适合您的工作需求的 {{site.data.keyword.streaminganalyticsshort}} 套餐。V2 服务套餐包含以下增强功能：
 
* [IBM Streams QSE with Docker](https://www-01.ibm.com/marketing/iwm/iwm/web/preLogin.do?source=swg-ibmistvi) ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")：查看 [开发指南](https://developer.ibm.com/streamsdev/docs/cloud-beta-devguide/) ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")，了解如何将新的 Streams QSE 与在 Docker 环境中运行的 RHEL 7 配合使用，以使用新的 {{site.data.keyword.streaminganalyticsshort}} V2 套餐来编译和部署应用程序。 
* [{{site.data.keyword.streaminganalyticsshort}} V2 REST API](https://console.bluemix.net/apidocs/1939-streaming-analytics-v2#introduction)![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")
* [新的入门模板和样本应用程序](https://developer.ibm.com/streamsdev/docs/cloud-beta-samples/) ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")
* [{{site.data.keyword.streaminganalyticsshort}} 服务中的高可用性增强功能](/docs/services/StreamingAnalytics/c_ha.html#consistent-regions)
* [{{site.data.keyword.streaminganalyticsshort}} 服务中的问题确定功能](https://developer.ibm.com/streamsdev/2018/02/15/streaming-analytics-console-gives-ways-find-fix-errors-beta-plans/) ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")
* [监视操作员在云中的行为和有保证的元组处理](https://developer.ibm.com/streamsdev/2018/02/15/monitor-operators-behave-ensure-resource-optimization/)![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")

### {{site.data.keyword.iva_full_notm}} Beta 现在可用！
最新更新日期：2018 年 3 月 16 日

通过 [{{site.data.keyword.iva_full}}](https://console.bluemix.net/catalog/services/voice-agent-with-watson) ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")，您可以创建基于 Watson 服务构建的认知语音代理程序，客户可以通过电话呼叫该代理程序并与之通话。通过将 Watson 人工智能应用于主干，语音代理程序能以对话方式进行通信，并在语音代理程序内处理复杂的交互和处理客户呼叫。

此 Beta 发行版引入了以下关键功能：

* 通过在单个步骤中创建语音代理程序和所有必需的 Watson 服务，前所未有地轻松入门。
* 通过语音代理程序转接呼叫，例如转接到人工联系中心代理或其他目标。
* 通过将语音代理程序配置为转发呼叫详细记录和转录，以收集和分析呼叫数据，然后 {{site.data.keyword.conversationshort}} 会将事件转到 {{site.data.keyword.cloudant_short_notm}} 数据库。
* 在新的_使用情况_页面上，监视服务使用情况和查看呼叫日志。您可以查看当月的快速统计信息，查找和过滤呼叫日志，以及查看每个单独呼叫的系统消息。
* 通过使用基于端口 5061 的 SIP TLS (sips URI) 和安全实时传送协议 (SRTP)，建立使用媒体加密的安全呼叫。
* 连接到其他 {{site.data.keyword.cloud_notm}} 空间中的 {{site.data.keyword.speechtotextfull}} 和 {{site.data.keyword.texttospeechfull}} 服务实例以提高灵活性。

有关使用入门信息，请参阅 [{{site.data.keyword.iva_short}}](/docs/services/voice-agent/getting-started.html) 文档。

### {{site.data.keyword.visualrecognitionshort}} 更新
最新更新日期：2018 年 3 月 14 日

更新了 {{site.data.keyword.visualrecognitionfull}} 服务，现在会生成新的“定制分类器”模型培训作为基于深度学习神经网络的分类器。生成这些深度学习模型需要额外计算，因此对新模型进行培训可能需要更长时间。

目前，现有定制分类器可以继续进行更新和重新培训，但不会更新为这种新的深度学习机器模型格式。

### {{site.data.keyword.streaminganalyticsshort}} 更新
最新更新日期：2018 年 2 月 14 日

[{{site.data.keyword.streaminganalyticsshort}} 服务](https://console.bluemix.net/catalog/services/streaming-analytics){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标") 中的 [Beta-Entry 和 Beta-Enhanced 套餐](/docs/services/StreamingAnalytics/beta_plans.html#beta_plans)包含多项增强功能：

* [新的 IBM Streams QSE for Docker](https://www-01.ibm.com/marketing/iwm/iwm/web/preLogin.do?source=swg-ibmistvi){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")：查看 [Beta 开发指南](https://developer.ibm.com/streamsdev/docs/cloud-beta-devguide/){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")，了解如何将新的 Streams QSE 与在 Docker 环境中运行的 RHEL 7 配合使用，以使用新的 {{site.data.keyword.streaminganalyticsshort}} Beta 套餐来编译和部署应用程序。
* [{{site.data.keyword.streaminganalyticsshort}} V2 REST API](https://console.bluemix.net/apidocs/1939-streaming-analytics-v2#introduction){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")
* [新的入门模板和样本应用程序](https://developer.ibm.com/streamsdev/docs/cloud-beta-samples/)
* [{{site.data.keyword.streaminganalyticsshort}} 服务中的高可用性增强功能](/docs/services/StreamingAnalytics/consistentregions.html#consistentregions)
* [{{site.data.keyword.streaminganalyticsshort}} Beta 版服务中新的问题确定功能](https://developer.ibm.com/streamsdev/2018/02/15/streaming-analytics-console-gives-ways-find-fix-errors-beta-plans/){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")
* [监视操作员在云中的行为和有保证的元组处理](https://developer.ibm.com/streamsdev/2018/02/15/monitor-operators-behave-ensure-resource-optimization/){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")

### {{site.data.keyword.keymanagementservicelong_notm}} 扩大到悉尼区域
最新更新日期：2018 年 1 月 31 日

自今日起，{{site.data.keyword.keymanagementserviceshort}} 加密密钥管理服务在悉尼区域中可用。悉尼是继美国南部（达拉斯）和伦敦之后，第三个向 {{site.data.keyword.keymanagementserviceshort}} 用户提供 GA 状态的区域。

{{site.data.keyword.keymanagementserviceshort}} 是一种加密密钥管理服务，提供简单且经济的密钥管理解决方案，可管理用于加密 {{site.data.keyword.Bluemix_notm}} 中所存储数据的密钥。{{site.data.keyword.keymanagementserviceshort}} 管理从密钥创建一直到应用程序使用、密钥归档和密钥销毁这整个密钥生命周期，同时还在数据管理与密钥管理之间强制执行职责分离。

{{site.data.keyword.keymanagementserviceshort}} 通过适用的 IBM 数据服务支持 BYOK（自带密钥 - 客户管理的加密）。BYOK 允许用户导入在内部创建的主可信根加密密钥，以更好地管理 {{site.data.keyword.Bluemix_notm}} 中保存的静态数据的安全性。


### {{site.data.keyword.containershort_notm}}：支持 Kubernetes 1.8.x
最新更新日期：2018 年 1 月 19 日

自 2017 年 11 月开始，{{site.data.keyword.containershort_notm}} 支持 Kubernetes `1.8.x`。我们很自豪地宣布，现在 Kubernetes 的缺省版本为 `1.8.6`。在不久的将来，我们将提供对 `1.9.x` 的支持。

### Watson Discovery Visual Insights
最新更新日期：2017 年 11 月 30 日

直观地浏览基于 {{site.data.keyword.discoveryshort}} 对文本中所检测到语义元素（例如实体、关系、概念等）的理解的连接。

使用现成的 {{site.data.keyword.discoveryshort}} News 集合开始浏览全球新闻。或者在 {{site.data.keyword.discoveryshort}} 中浏览您自己的文档集合。只需使用您的 {{site.data.keyword.Bluemix_notm}} 凭证登录即可。有关更多信息，请参阅 [Visual insights experimental](https://visual-insights.bluemix.net){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")。

### 新增 IBM Cloud Managed Database Server Beta 服务
最新更新日期：2017 年 11 月 30 日

通过新的 IBM Cloud Managed Database Server Beta 服务，可以在 {{site.data.keyword.Bluemix_notm}} 上创建 Microsoft SQL Server 实例。您可以像使用任何数据库管理系统一样来使用此 SQL Server 实例，但却没有硬件安装或软件安装与维护的工作及费用。

此服务提供以下功能：
* 可选择 Microsoft SQL Server 2012、2014 和 2016 Enterprise Edition 和 Standard Edition
* 有各种预定义配置或大小，可满足应用程序工作负载需求
* 由 IBM 完全管理，包括监视、打补丁、备份和报告

有关使用入门信息，请参阅 [IBM Cloud Managed Database Server 入门](/docs/services/managed-sql-server/getting-started.html)。

### {{site.data.keyword.mobilepushshort}} 中的新增内容
最新更新日期：2017 年 10 月 26 日

我们在过去几个月里对 {{site.data.keyword.mobilepushshort}} 服务做了若干改进。现在，该服务除了在达拉斯、伦敦和悉尼可用外，还在法兰克福区域可用。下面是增强功能的详细信息：

#### 监视
现在，可以跟踪特定时间段的推送通知性能，以及跟踪发送的通知数和注册的设备总数。您还可以注册 Webhook 以获得关于生命周期内所有事件的通知。更多详细信息可以在以下文档链接和博客帖子中找到：
* [监视通知](/docs/services/mobilepush/push_monitoring.html#push_monitoring)
* [接收有关 Webhook 活动的警报](/docs/services/mobilepush/push_webhook.html#webhook_event_based_notifications)
* [Monitoring in IBM Push Notifications](https://www.ibm.com/blogs/bluemix/2017/03/monitoring-ibm-push-notifications/){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")

#### Web 通知
现在，我们支持 Safari Web 浏览器获取 Web 通知以及 Firefox、Chrome、Chrome 应用程序和扩展。Web SDK 和相关信息可在 [IBM Bluemix Push Notifications Web SDK](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-javascript-webpush/blob/Doc/README.md){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标") 上找到。

#### 最新的 Android 和 iOS 通知
我们对 iOS 11 通知提供货币支持。我们还包含了 iOS 10 和 Android N 中与通知相关的多个新的增强功能。

* iOS 10 - 在交互式通知中提供富媒体通知、图像、按钮和地图，支持本地化字符串
* Android N - 可扩展的通知、交互式和静默通知以及 LED 指示灯设置

其他详细信息可以在[富媒体通知](/docs/services/mobilepush/push_step_4_nf_rich.html#interactive-notifications)文档、[交互式和静默通知](/docs/services/mobilepush/push_step_4_nf_interactive.html#interactive-notifications)文档以及[启用高级推送通知](/docs/services/mobilepush/push_step_4_nf_adv.html#enabling-advanced-push-notifications)文档中找到。

#### APNS HTTP/2 支持
Apple 推出了对 Apple 通知的 HTTP 协议的支持。现在，{{site.data.keyword.mobilepushshort}} 服务支持 HTTP/2 协议。有了这种支持，通知有效内容可以随着吞吐量上升而达到 4 KB，另外还提供了即时反馈功能。通过支持通用证书，允许应用程序连接到沙箱和生产环境。

#### 新增轻量套餐
{{site.data.keyword.mobilepushshort}} 服务的轻量套餐提供了每月免费发送 10 万条通知的能力。有关更多信息，请参阅 [Lite Plan For Push Notifications Service on Bluemix](https://www.ibm.com/blogs/bluemix/2017/06/lite-plan-push-notifications-service-bluemix/){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标") 博客帖子。



### Mobile Analytics 中的新增内容
最新更新日期：2017 年 10 月 26 日

我们在过去几个月里对 {{site.data.keyword.mobileanalytics_short}} 服务进行了增强。现在，该服务除了在达拉斯和伦敦可用外，还在法兰克福和悉尼区域可用。下面是增强功能的详细信息：

#### Web SDK 支持
现在，{{site.data.keyword.mobileanalytics_short}} 是全通道服务，增加了对 Web 应用程序分析的支持。更多详细信息可以在 [https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-web-analytics/](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-web-analytics/){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标") 处找到。

#### 与 {{site.data.keyword.mobilefoundation_short}} 服务集成
现在，{{site.data.keyword.mobilefoundation_short}} 服务利用 {{site.data.keyword.mobileanalytics_short}} 服务进行应用程序、用户和性能分析。用户可以利用导出到 Db2 仓库的选项来构建适配器分析和定制图表。您可以在以下博客帖子中找到其他详细信息：

* [Mobile Foundation Service integration with Mobile Analytics Service](https://www.ibm.com/blogs/bluemix/2017/08/mobile-foundation-service-integration-mobile-analytics-service-2/){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")
* [Building custom charts using IBM Bluemix Mobile Analytics service and IBM Mobile Foundation Service](https://mobilefirstplatform.ibmcloud.com/blog/2017/04/26/custom-charts-using-analytics-and-dashdb-analytics-service/){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")
* [Building charts for Adapter analytics using IBM Bluemix Mobile Analytics service and IBM Mobile Foundation Service](https://mobilefirstplatform.ibmcloud.com/blog/2017/04/26/adapter-analytics-using-analytics-and-dashdb-analytics-service/){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")

#### 现在，{{site.data.keyword.mobilefirst_notm}} 样板包含 {{site.data.keyword.mobileanalytics_short}}
移动服务样板是一种模板，用于提供一组移动服务，供用户快速开始使用。{{site.data.keyword.mobileanalytics_short}} 服务现在是[目录](https://console.bluemix.net/catalog/starters/mobilefirst-services-starter){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标") 中可用样板的一部分。


### {{site.data.keyword.streaminganalyticsshort}} 更新
最新更新日期：2017 年 10 月 20 日

* IBM Streams Runner for Apache Beam：现在，您可以在 Streams 开发环境中本地开发 Beam 应用程序，然后将这些应用程序提交到 {{site.data.keyword.Bluemix_notm}} 中的 {{site.data.keyword.streaminganalyticsshort}} 服务。IBM Streams Runner for Apache Beam 会在 Streams 环境中执行 Beam 管道。使用 Streams Runner 启动的 Beam 应用程序会转换为 Streams 应用程序捆绑软件 (SAB) 文件，然后您可以将该文件部署在 {{site.data.keyword.streaminganalyticsshort}} 中。有关更多详细信息，请查看 [Streaming Analytics 中的 IBM Streams Runner for Apache Beam](/docs/services/StreamingAnalytics/gs_beamrunner.html)。
* 您甚至可以在日志文件中更快查找信息。控制台经过更新，改进了 Python 或 Java 拓扑的应用程序图形显示。请参阅[控制台的增强功能](https://developer.ibm.com/streamsdev/2017/10/13/enhancements-to-the-console/){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")。

### IBM App Launch for {{site.data.keyword.Bluemix_notm}} Services
最新更新日期：2017 年 10 月 12 日

IBM App Launch for {{site.data.keyword.Bluemix_notm}} Services 是一个试验性产品，通过提供一个平台来创建有针对性的各种受众群体互动，让您能够测量客户体验。通过 App Launch 服务，您可以深入了解作为互动结果的客户偏好和痛点，并帮助您个性化应用程序以获得更好的客户体验。

现在，应用程序所有者可以通过避免发布周期复杂性，加速向移动应用程序交付创新。App Launch 服务支持应用程序所有者通过控制目标受众，快速向移动应用程序发布功能和测量影响。应用程序所有者可以与应用程序开发者合作，为功能定义关键性能指标，测量影响以及根据实时反馈来应用功能和回滚决策。该服务还能够测试应用程序功能、用户界面组件和消息的多个变体，并根据反馈做出决策。

有关更多信息，请参阅[入门教程](/docs/services/app-launch/index.html#gettingstartedtemplate)。

### {{site.data.keyword.ibmwatson_notm}} {{site.data.keyword.relationshipextractionshort}} 更新
最新更新日期：2017 年 10 月 4 日

通过 {{site.data.keyword.relationshipextractionshort}} 为用户提供了新的定制功能和新的语言模型。新的语言为 WKS 支持的荷兰语、韩语和简体中文。

### {{site.data.keyword.containerlong_notm}} 集群更新
最新更新日期：2017 年 9 月 20 日

现在，您可以将集群更新到 {{site.data.keyword.Bluemix_notm}} 中最新可用版本的 Kubernetes。使用 GUI 或 CLI，将 Kubernetes 主节点和工作程序节点更新到 Kubernetes 1.7，并利用新功能和补丁。

有关更多信息，请查看 [Kubernetes 1.7 available in {{site.data.keyword.containerlong_notm}}](https://www.ibm.com/blogs/bluemix/2017/09/kubernetes-1-7-available-ibm-bluemix-container-service/){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")。

### 新增 IBM Voice Agent with Watson 试验性服务
最新更新日期：2017 年 9 月 15 日

通过新的 {{site.data.keyword.iva_full}} 试验性服务，您可以创建基于 Watson 服务构建的认知语音代理程序，客户可以通过电话呼叫该代理程序并与之通话。通过将 Watson 人工智能应用于主干，语音代理程序能以对话方式进行通信，并在语音代理程序内处理复杂的交互和处理客户呼叫。

{{site.data.keyword.iva_short}} 可无缝连接到 Watson {{site.data.keyword.speechtotextshort}}、{{site.data.keyword.conversationshort}} 和 {{site.data.keyword.texttospeechshort}} 服务并对其进行编排，以模拟自然语言对话。每个语音代理程序会自动扩展以同时处理多个呼叫。在此试验版本中，您可以使用以下主要功能来定制语音代理程序：

* 首先导入样本 {{site.data.keyword.conversationshort}} 对话，然后创建自己的对话来满足您公司的需求。
* 使用 API 从 {{site.data.keyword.conversationshort}} 服务内对语音代理程序行为编程。您可以控制对话中任意节点的一切行为，从打断行为到挂断呼叫。
* 如果要将不同的电话号码连接到针对不同主题专门设计的认知代理程序，可轻松创建和管理多个语音代理程序。
* 通过连接服务编排引擎 (SOE) 来扩展服务的功能，以便可以使用第三方 API。例如，SOE 可以侦听来自 {{site.data.keyword.conversationshort}} 服务的触发器，然后使用您提供的 API 在现有系统中查找信息或提供其他分析。

有关使用入门信息，请参阅 [{{site.data.keyword.iva_short}} 入门](/docs/services/voice-agent/getting-started.html)文档。


### {{site.data.keyword.streaminganalyticsshort}} 服务更新：控制台包含用于查明应用程序中问题的新方法
最新更新日期：2017 年 8 月 14 日

对于 Python 和 Java 应用程序，源文件位置根据 @spl_note 注释显示。

有关详细信息，请参阅 [{{site.data.keyword.streaminganalyticsshort}} 的最新改进](https://developer.ibm.com/streamsdev/2017/08/14/latest-improvements-streaming-analytics-console/){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")。

### 现在，IBM Cloud Monitoring 还在英国区域可用
最新更新日期：2017 年 8 月 1 日

使用 {{site.data.keyword.monitoringlong}} 服务可在 {{site.data.keyword.Bluemix_notm}} 中使用度量值时，扩展收集、保留和分析功能。

* 提醒执行操作！{{site.data.keyword.monitoringlong}} 提供了一个可用于设置性能阈值并在违反这些阈值时收到通知的 API。定义针对单个服务实例或应用程序实例的警报规则，也可定义针对一组实例进行报告的警报规则。触发警报时，可通过电子邮件、PagerDuty 事件、Webhook 通知或这三者的任意组合来获得通知。

* 添加定制度量值。{{site.data.keyword.monitoringlong}} 高端套餐提供了可用于向 Cloud Monitoring 数据添加相关应用程序和业务度量值的 API。您还可以使用这些 API 将 {{site.data.keyword.IBM_notm}} Cloud 外部的度量值数据发送到 {{site.data.keyword.monitoringlong}} 服务中。

* 构建可复用的仪表板并将其设置为交互式。{{site.data.keyword.monitoringlong}} 的托管 Grafana 支持使用大量可视化选项来构建定制仪表板。通过将度量值查询与变量一起使用来生成模板，可使仪表板动态变化。

* 通过 {{site.data.keyword.Bluemix_notm}}“目录”访问服务。{{site.data.keyword.monitoringlong}} 在 {{site.data.keyword.Bluemix_notm}}“目录”的 DevOps 部分中作为服务磁贴提供。对于使用单个容器和容器组的 {{site.data.keyword.containershort}} 服务，可以通过 {{site.data.keyword.Bluemix_notm}} UI 访问该服务。

* 选择适合您需要的服务套餐。您可根据自己的使用量需要，选择轻量服务套餐或高端服务套餐。轻量套餐每分钟收集一次度量值，保留时间为 15 天，并免费发出警报。或者，可以选择高端套餐来启用更多使用量、更长度量值保留时间，并获取对服务 API 的访问权，例如通过 {{site.data.keyword.monitoringlong}} 服务发送或检索度量值。{{site.data.keyword.monitoringlong}} 每分钟收集一次度量值。轻量套餐会将完整分辨率的度量值保留 15 天。高端套餐会将完整分辨率的度量值保留 45 天。

旧 {{site.data.keyword.monitoringshort}} 服务按服务定义的频率收集度量值，一开始的频率为 30 秒，在一段时间后将度量值汇总到 1 小时频率。现在，{{site.data.keyword.monitoringlong}} 提供每分钟执行一次的完整分辨率收集。轻量套餐会将度量值保留 15 天。高端套餐会将度量值保留 45 天。

有关 {{site.data.keyword.monitoringlong}} 服务的更多信息，请参阅 [Monitoring 入门文档](/docs/services/cloud-monitoring/index.html#getting-started-with-ibm-cloud-monitoring)或 [IBM Cloud Monitoring - Service Refresh with New Features ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")](https://www.ibm.com/blogs/bluemix/2017/07/ibm-cloud-monitoring-service-refresh-new-features/)。


### 现在，IBM Cloud Log Analysis 在美国南部区域可用
最新更新日期：2017 年 7 月 31 日

{{site.data.keyword.loganalysisfull}} 服务为 {{site.data.keyword.Bluemix_notm}} 平台提供了日志收集和日志搜索服务，会自动从所选 {{site.data.keyword.Bluemix_notm}} 服务收集应用程序和 {{site.data.keyword.Bluemix_notm}} 服务的数据。使用 {{site.data.keyword.loganalysisshort}} 服务可实现：

* 根据需要使日志保留任意长的时间。  

    日志存储在 IBM Cloud 存储器中。您可以在需要时下载日志。

* 使用新的 API 来管理保留的日志，以及从 {{site.data.keyword.IBM_notm}} Cloud 外部发送日志数据。

* 选择每天可以搜索的日志量。  

    提供了不同的套餐，分别可用于每天搜索最多 500MB、2GB、5GB 和 10GB 的日志。

* 构建可复用的仪表板并将其设置为交互式。

    {{site.data.keyword.loganalysisshort}} 的托管 Kibana 支持构建定制仪表板。

* 通过 {{site.data.keyword.Bluemix_notm}}“目录”访问服务。  

    对于使用单个容器和容器组的 {{site.data.keyword.loganalysisshort}} 服务以及对于 {{site.data.keyword.IBM_notm}} Cloud Foundry 服务，可以通过 {{site.data.keyword.Bluemix_notm}} UI 访问服务。

有关 {{site.data.keyword.loganalysisshort}} 服务的更多信息，请参阅 [{{site.data.keyword.loganalysisfull}} 入门](/docs/services/CloudLogAnalysis/index.html#getting-started-with-ibm-cloud-log-analysis)和 [{{site.data.keyword.loganalysisshort}} 概述](/docs/services/CloudLogAnalysis/log_analysis_ov.html#log_analysis_ov)。

### Brocade 操作系统 V18.x 可用于 Virtual Router Appliance
最新更新日期：2018 年 7 月 25 日

Brocade 操作系统 V18.x 现在可用于 Virtual Router Appliance。除其他新功能外，此版本还提供了对 Spectre 安全漏洞的修正。 

以下主题讨论了 18.x VRA 的新功能：

* [如何设置适用于区域防火墙的 IPSec 隧道](/docs/infrastructure/virtual-router-appliance/vra-ipsec.html)
* [使用 IPSec 和区域防火墙配置 VFP 接口](/docs/infrastructure/virtual-router-appliance/vra-vfp.html)
* [将 NAT 与基于前缀的 IPSec 配合使用](/docs/infrastructure/virtual-router-appliance/vra-nat.html)
* [对 VFP 接口进行故障诊断](/docs/infrastructure/virtual-router-appliance/vra-vfp-troubleshooting.html)

如果要从 Vyatta 5400 进行迁移，那么升级到 18.x 的最佳方法是执行重新装入完整操作系统的[正常操作步骤](/docs/infrastructure/virtual-router-appliance/upgrade-os.html)。

由于 Vyatta 5400 与 Virtual Router Appliance 之间没有简单的一对一功能映射，因此为 VRA 创建基准配置会很有帮助。WanClouds 是 IBM 的合作伙伴，他们可以帮助您完成此过程，并提供有关在 VRA 上创建类似 Vyatta 5400 的功能的指导。

有关此升级过程中遇到的常见问题的更多信息，请参阅我们的[其他文档](/docs/infrastructure/virtual-router-appliance/migration-issues.html#vyatta-5400-common-migration-issues)。

### IBM dashDB for Analytics 已重命名
最新更新日期：2017 年 7 月 18 日

下表汇总了新名称：

|先前名称                    |新名称                     |生效日期       |
|-----------------------------|----------------------------|----------------|
|IBM dashDB for Analytics    |IBM Db2 Warehouse on Cloud |2017 年 7 月 18 日|
{: caption="表 1. 服务名称更改" caption-side="top"}

有关 Db2 Warehouse on Cloud 和 Db2 on Cloud 更新的累积列表，请参阅：[What's New in Db2 Warehouse on Cloud and Db2 on Cloud](http://www.ibm.com/support/docview.wss?uid=swg21961758){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")。

### 现在，IBM Cloud Monitoring 在美国南部区域可用
最新更新日期：2017 年 7 月 17 日

使用 {{site.data.keyword.monitoringlong}} 服务可在 {{site.data.keyword.Bluemix_notm}} 中使用度量值时，扩展收集、保留和分析功能。

* 提醒执行操作！{{site.data.keyword.monitoringlong}} 提供了一个可用于设置性能阈值并在违反这些阈值时收到通知的 API。定义针对单个服务实例或应用程序实例的警报规则，也可定义针对一组实例进行报告的警报规则。触发警报时，可通过电子邮件、PagerDuty 事件、Webhook 通知或这三者的任意组合来获得通知。

* 添加定制度量值。{{site.data.keyword.monitoringlong}} 高端套餐提供了可用于向 Cloud Monitoring 数据添加相关应用程序和业务度量值的 API。您还可以使用这些 API 将 {{site.data.keyword.IBM_notm}} Cloud 外部的度量值数据发送到 {{site.data.keyword.monitoringlong}} 服务中。

* 构建可复用的仪表板并将其设置为交互式。{{site.data.keyword.monitoringlong}} 的托管 Grafana 支持使用大量可视化选项来构建定制仪表板。通过将度量值查询与变量一起使用来生成模板，可使仪表板动态变化。

* 通过 {{site.data.keyword.Bluemix_notm}}“目录”访问服务。{{site.data.keyword.monitoringlong}} 在 {{site.data.keyword.Bluemix_notm}}“目录”的 DevOps 部分中作为服务磁贴提供。对于使用单个容器和容器组的 {{site.data.keyword.containershort}} 服务，可以通过 {{site.data.keyword.Bluemix_notm}} UI 访问该服务。

* 选择适合您需要的服务套餐。您可根据自己的使用量需要，选择轻量服务套餐或高端服务套餐。轻量套餐每分钟收集一次度量值，保留时间为 15 天，并免费发出警报。或者，可以选择高端套餐来启用更多使用量、更长度量值保留时间，并获取对服务 API 的访问权，例如通过 {{site.data.keyword.monitoringlong}} 服务发送或检索度量值。{{site.data.keyword.monitoringlong}} 每分钟收集一次度量值。轻量套餐会将完整分辨率的度量值保留 15 天。高端套餐会将完整分辨率的度量值保留 45 天。

旧 {{site.data.keyword.monitoringshort}} 服务按服务定义的频率收集度量值，一开始的频率为 30 秒，在一段时间后将度量值汇总到 1 小时频率。现在，{{site.data.keyword.monitoringlong}} 提供每分钟执行一次的完整分辨率收集。轻量套餐会将度量值保留 15 天。高端套餐会将度量值保留 45 天。

有关 {{site.data.keyword.monitoringlong}} 服务的更多信息，请参阅 [Monitoring 入门文档](/docs/services/cloud-monitoring/index.html#getting-started-with-ibm-cloud-monitoring)或 [IBM Cloud Monitoring - Service Refresh with New Features ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")](https://www.ibm.com/blogs/bluemix/2017/07/ibm-cloud-monitoring-service-refresh-new-features/)。

### {{site.data.keyword.contdelivery_short}} 升级
最新更新日期：2017 年 7 月 11 日

升级的优点包括错误修订、性能改进以及对用户体验的优化。值得注意的增强功能（如果尚未在您的环境中提供）包括：
<ul>
<li>修复和改进国际化和辅助功能。</li>
<li>工具链访问控制，通过工具链的“管理”选项卡提供。</li>
<li>Continuous Delivery 工具目录中新的工具集成。</li>
<li>改进了 Orion Web IDE 中多个工作空间的分组。</li>
<li>支持 Orion Web IDE 中的多个编辑器选项卡。</li>
<li>支持 Orion Web IDE 中的 UI 主题。</li>
</ul>

### {{site.data.keyword.uccr_short}} Beta
最新更新日期：2017 年 6 月 23 日

{{site.data.keyword.uccr_short}} 是一种企业级发布管理解决方案，同时支持云本机和内部部署工具。

Beta 版本的 {{site.data.keyword.uccr_short}} 提供以下主要功能：
* 使用发布来管理多个部署计划和事件，并协作完成多团队发布工作。
* 为任何与发布相关的活动创建事件，并使用日历对其进行管理。
* 导入您自己的事件和发布。
* 定制日历事件以满足您组织的需求。
* 将电子邮件和 Slack 类型的任务用于发布通知。

### dashDB for Transactions 已重命名为 {{site.data.keyword.Db2Hosted_notm}}
最新更新日期：2017 年 6 月 14 日

IBM {{site.data.keyword.DB2OnCloud_short}} 是 dashDB for Transactions 的新名称。作为此重命名的一部分，原先自行管理的 IBM {{site.data.keyword.DB2OnCloud_short}} 服务还将重命名为 IBM Db2 Hosted。目前只更新了显示名称，所以任何 API 或命令行界面均保持不变。

### {{site.data.keyword.sparks}} 更新：Stocator-S3 连接器支持 IBM Cloud Object Storage Cross Region 服务 (Beta)
最新更新日期：2017 年 6 月 5 日

现在，{{site.data.keyword.sparks}} 用户可以访问存储在 IBM Cloud Object Storage Cross Region 服务中的数据并对其进行分析。此功能作为 Beta 版提供。IBM Cloud Object Storage 为分析和其他应用程序提供高容量、经济高效的存储，可扩展、非常灵活且易于使用。

Apache Spark 通过基于 Stocator 技术的存储连接器来访问 IBM Cloud Object Storage 数据，这种存储连接器隐式设计用于对象存储，因此比旧的对象存储连接器速度更快。作为用户，您无需更改或重新编译 Apache Spark 代码。

[Access and Analyze data in IBM Cross Region Cloud Object Storage](https://www.ibm.com/blogs/bluemix/2017/06/access-analyze-data-ibm-cross-region-cloud-object-storage/){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标") 博客帖子描述了在 {{site.data.keyword.Bluemix_notm}} 和 IBM Data Science Experience (DSx) 上将 IBM Cloud Object Storage 数据用于 {{site.data.keyword.sparks}} 的情况。

如果您有任何问题或意见，请通过 [sparksrv@us.ibm.com](sparksrv@us.ibm.com) 与我们联系。非常感谢您提供的信息！

### 新增可用于 {{site.data.keyword.dashdbshort_notm}} for Transactions 的可扩展套餐
最新更新日期：2017 年 5 月 31 日

针对 {{site.data.keyword.dashdbshort}} for Transactions 提供了新套餐，此套餐可以随您的数据库需求而增长。新的 Flex 套餐支持您一开始使用小型系统，然后轻松、快速地增加该系统的能力和存储容量。在高可用性套餐上，{{site.data.keyword.dashdbshort}} for Transactions 与 Db2 100% 兼容并提供 99.95% 的 SLA。

### {{site.data.keyword.Bluemix_notm}} 上 {{site.data.keyword.mobilepush}} 服务的新更新
最新更新日期：2017 年 5 月 24 日

下面是可用于 {{site.data.keyword.Bluemix_notm}} 上 {{site.data.keyword.mobilepush}} 服务的新更新。

**轻量套餐**：除了 {{site.data.keyword.mobilepush}} 服务的现有基本套餐外，我们还推出了新的轻量套餐。根据新套餐，用户每个月可以免费发送多达十万条数字消息。从轻量套餐升级到基本套餐后，在用户发送的数字消息超过 100 万条后，将向用户收取相应费用。轻量套餐升级到基本套餐时，100 万条消息的计数将开始。

**监视**：现在，您可以深入了解 {{site.data.keyword.mobilepush}} 服务控制台中所发送的通知和注册的设备。您还可以使用 REST API 进行消息级别跟踪。从消息传递到消息分派再到消息接收，可以通过配置 Webhook 来获取详细信息。请参阅[监视 {{site.data.keyword.mobilepush}}](/docs/services/mobilepush/t_push_monitoring.html#monitor-notifications)。

**Web 通知**：现在，您可以将通知发送到 Safari Web 浏览器。

### Secure Gateway 更新
最新更新日期：2017 年 5 月 24 日

最新的 Secure Gateway 维护更新包含 UI 和 API 管理器中的小错误修订以及更新的文档，并且客户机已经更新到 V1.7.1。现在，Secure Gateway 客户机在 AIX 7.1+ 上可用，并且支持通过 squid 代理进行出站连接。

### {{site.data.keyword.streaminganalyticsshort}} 服务更新：在 Python 开发环境中开发 Streams 应用程序
最新更新日期：2017 年 4 月 13 日

过去，您必须安装本地版本的 IBM Streams 来开发 Python 应用程序。现在不必再如此。您现在可以在自己最喜爱的开发环境或 Jupyter 交互式配置页中使用 Python 来开发应用程序。

您可以使用 STREAMING_ANALYTICS_SERVICE 上下文将 Python 应用程序提交给 {{site.data.keyword.streaminganalyticsshort}} 服务。{{site.data.keyword.streaminganalyticsshort}} 服务需要 Python 3.5。

您可以使用 IBM Data Science Experience (DSX) 中的 Jupyter 配置页来创建样本 Python 应用程序，然后将这些应用程序直接从 DSX 提交到 {{site.data.keyword.streaminganalyticsshort}} 实例。请在 [DSX 社区页面](https://datascience.ibm.com/){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标") 上查看配置页中的样本流处理 Python 应用程序。

有关 {{site.data.keyword.streaminganalyticsshort}} 服务更新的更多信息，请参阅 [{{site.data.keyword.streaminganalyticsshort}} updates: DSX integration and easier Python development](https://www.ibm.com/blogs/bluemix/2017/05/streaming-analytics-updates-dsx-integration-easier-python-development/){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")。

### {{site.data.keyword.sparks}} 更新：现在支持 Apache Spark 2.1
最新更新日期：2017 年 4 月 21 日

{{site.data.keyword.sparkl}} 将引入对 Apache Spark 2.1 的支持，以创建利用基于复杂数据的洞察的算法。Apache Spark 2.1 增加了对事件时间水印和 Kafka 0.10 的支持，将对结构化流处理十分有利。Apache Spark 2.1 还专注于提高 Spark SQL、SparkR 和 MLlib 模块的稳定性和可用性。有关 Spark 2.1 的更多详细信息，请参阅 [Spark R2.1.0](http://spark.apache.org/releases/spark-release-2-1-0.html)。

我们很乐意回答与 {{site.data.keyword.sparkl}} 或 Apache Spark 2.1 更高版本相关的任何问题，您可通过 sparksrv@us.ibm.com 与我们联系。

### 不推荐使用 {{site.data.keyword.macm_short}}
最新更新日期：2017 年 4 月 18 日

自 2017 年 3 月 30 日开始，{{site.data.keyword.macm_long}} 服务磁贴将从 {{site.data.keyword.Bluemix_notm}}“目录”中除去，您无法再供应新的 MACM 实例。不过，仍将继续支持现有实例。支持结束日期为 2018 年 3 月 30 日。请在支持结束日期前删除 {{site.data.keyword.macm_short}} (MACM) 服务实例。我们鼓励用户迁移到 IBM Watson Content Hub。Watson Content Hub 在 IBM Marketplace 上提供，为用户提供 30 天的免费试用。IBM Watson Content Hub 将提供与 MACM 类似的功能，但新增了资产管理、使用 IBM Watson 服务的认知标记以及随附内容交付网络 (CDN) 等新功能，以确保为您的客户提供最佳体验。IBM 提供了服务互动，可将内容从 MACM 迁移到 Watson Content Hub。


### {{site.data.keyword.sparks}} 更新：Data Science Experience 中现在支持配置页
最新更新日期：2017 年 4 月 11 日

您的新平台可使用配置页，并且 Spark 已更名为 Data Science Experience。注册 [Data Science Experience](http://datascience.ibm.com/)，然后开始创建配置页，并与其他数据研究员共享您的专业知识。

如果使用的是 {{site.data.keyword.sparks}} 中的配置页，那么可以将配置页迁移到 Data Science Experience。有关更多信息，请参阅[迁移配置页文档](/docs/services/AnalyticsforApacheSpark/index-gentopic2.html#migration_to_dsx)。


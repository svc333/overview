---

copyright:

  years: 2015, 2019

lastupdated: "2019-07-02"

keywords: release notes, what's new, what is new, cloud updates

subcollection: overview

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:tip: .tip}

# {{site.data.keyword.Bluemix_notm}} 中的新增内容
{: #whatsnew}

及时获取 {{site.data.keyword.Bluemix}} 平台上可用的新功能，以便最充分地利用 {{site.data.keyword.Bluemix_notm}} 体验。
{:shortdesc}

如果要查找 {{site.data.keyword.Bluemix_notm}} 上可用服务的更新，请查看博客上的 [{{site.data.keyword.Bluemix_notm}} Announcements 页面](https://www.ibm.com/cloud/blog/announcements){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")。
{: tip}



## {{site.data.keyword.Bluemix_notm}} 平台
{: #platform_category}

### 在 {{site.data.keyword.cloud_notm}} 上管理 SoftLayer SAML 联合
{: #saml-federation}
最新更新日期：2019 年 7 月 2 日

设置了 SAML 身份提供者以使用联合标识进行登录的前 SoftLayer 用户现在可在 {{site.data.keyword.cloud_notm}} 控制台的“访问权”(IAM) 中的“身份提供者”页面上管理其配置数据。不推荐使用此类型的联合，所以此时无法设置新的身份提供者，但是您可以继续更新身份提供者数据或者选择删除此联合以支持切换为[与 IBM 标识联合](/docs/account?topic=account-signup#signup-federated)。

### 定制仪表板
{: #custom}
最新更新日期：2019 年 6 月 14 日 

现在，您可以控制仪表板上显示的内容。定制仪表板包括能够添加、除去和重新排列窗口小部件的顺序。有关更多信息，请参阅[定制仪表板](/docs/overview?topic=overview-custom-dashboard)。


### 导出带关联标记的使用情况数据
最新更新日期：2019 年 4 月 4 日
 

现在，可以利用最新的标记功能来管理导出的使用情况报告中的资源、使用情况和成本。向资源添加标记时，可以选择查看与资源关联的标记。转至**管理** > **计费和使用情况** > **使用情况** > **导出 CSV** >  **实例**，以下载使用情况报告。有关导出标记的更多信息，请查看 [Export tags within your usage data to help with cost allocation](https://www.ibm.com/cloud/blog/export-your-tagged-usage-data-within-the-enhanced-ibm-cloud){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标") 博客帖子。

### 用于启用对资源的公共访问权的访问组
最新更新日期：2019 年 3 月 25 日

现在您可以使用帐户中提供的新访问组启用对 {{site.data.keyword.cos_full}} 存储区中对象的公共访问权。这个新的访问组被称为`公共访问权`组，缺省情况下，会为其添加所有用户和服务标识。您可以更新访问组策略以支持所有用户（甚至未经验证的用户）访问策略中指定的资源。[了解有关公共访问权组的更多信息](/docs/iam?topic=iam-public#public)。

### 针对使用联合标识的用户的多因子认证
最新更新日期：2019 年 3 月 12 日
{: #mfa-federated}

分配有对缴费帐户管理服务的管理员角色的帐户所有者或用户，可以为其帐户中的所有用户启用多因子认证 (MFA)。现在，对于使用其公司或企业单点登录标识的联合用户，可以要求他们使用 MFA 进行认证，才能登录到 {{site.data.keyword.Bluemix_notm}}。有关此增强功能的更多信息以及关于为帐户启用 MFA 需要了解的信息，请参阅 [Introducing MFA for IBM Cloud Users with Federated ID](https://www.ibm.com/cloud/blog/introducing-mfa-for-ibm-cloud-users-with-federated-id){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")。

### 新的 appdomain.cloud 主机名选项
最新更新日期：2018 年 12 月 31 日
{: #appdomain}

在 cloud.ibm.com 上提供了新的主机名选项 `*.appdomain.cloud`。

先前，`mybluemix.net` 域用于在各种部署目标（例如，{{site.data.keyword.containerlong_notm}} 或 Cloud Foundry）中托管应用程序。在 `mybluemix.net` 上托管的任何应用程序都不受影响。

Cloud Foundry 应用程序的子域为 `cf.appdomain.cloud`。部署到 {{site.data.keyword.containerlong_notm}} 的应用程序的子域为 `containers.appdomain.cloud`。

### 新的 Cloud Foundry API 端点
最新更新日期：2018 年 11 月 30 日
{: #cf-api-endpoints}

原有 `api.*.bluemix.net` Cloud Foundry API 端点仍可用，以支持向后兼容性。但是，您可以更新脚本和基础架构自动化，以对您所在的区域使用以下新的 Cloud Foundry API 端点：

* api.us-south.cf.cloud.ibm.com（先前为 api.ng.bluemix.net）
* api.eu-gb.cf.cloud.ibm.com（先前为 api.eu-gb.bluemix.net）
* api.us-east.cf.cloud.ibm.com（先前为 api.us-east.bluemix.net）
* api.eu-de.cf.cloud.ibm.com（先前为 api.eu-de.bluemix.net）
* api.au-syd.cf.cloud.ibm.com（先前为 api.au-syd.bluemix.net）

### 新的 {{site.data.keyword.Bluemix_notm}} 支持体验
最新更新日期：2018 年 11 月 30 日
{: #support}

通过支持中心，您可以设法解决所有与 {{site.data.keyword.Bluemix_notm}} 相关的问题。此登录页面提供有常见问题，因此您可以找到问题的答案，甚至无需联系 {{site.data.keyword.Bluemix_notm}}。您还可以与实时支持代表交谈。现在，可以从单个位置管理您的案例。转至**支持** &gt; **管理案例**可创建、查看或编辑案例。

您还可以在支持中心找到 [Status 页面](https://cloud.ibm.com/status){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")。此页面经过增强，包含与影响 {{site.data.keyword.Bluemix_notm}} 平台、基础架构和主要服务的关键事件相关的所有计划外事件、计划维护、声明和安全公告通知。在支持中心，单击**查看云状态**。要查看新体验，请登录并转至[支持中心](https://cloud.ibm.com/unifiedsupport/supportcenter){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")。 

### {{site.data.keyword.Bluemix_notm}} 中的统一登录、API 密钥以及用户和访问权管理
最新更新日期：2018 年 11 月 30 日
{: #useraccess}

通过最新更新，您可以利用所有用户都可用的简化安全登录，而不管您的标识是什么类型。无论您拥有的是 IBM 标识还是 SoftLayer 标识，都可以从增强的登录页面快速登录到 {{site.data.keyword.Bluemix_notm}} 控制台。您还可以在 {{site.data.keyword.Bluemix_notm}} 中进行安全 API 调用，并使用 IAM API 密钥或 IAM 访问令牌自动执行 CLI 登录。 

登录后，您现在可以在“访问权 (IAM)”UI 中的“用户”页面中查看所有用户，包括平台和经典基础架构用户。根据您用于查看帐户中其他用户的访问权，可以按帐户用户、经典基础架构用户或 Cloud Foundry 组织快速过滤视图。您还可以使用这些过滤器按名称、电子邮件或状态来快速查找用户。

既然您的所有用户都在一个控制台中，就可以在同一位置管理他们对所有类型资源的访问权。访问权从用户开始，因此首先从列表中选择用户。然后，根据要分配其访问权的资源类型，可以从 IAM 访问策略、Cloud Foundry 访问权或经典基础架构许可权中进行选择。如果您只想分配 IAM 访问策略，请尝试创建访问组，然后将需要分配相同策略的所有用户添加到同一访问组，从而简化访问权管理过程。

有关更多详细信息，请查看 [Outstanding User Access Improvements Help Deliver a Unified {{site.data.keyword.Bluemix_notm}} Platform](https://www.ibm.com/cloud/blog/announcements/ibm-cloud-access-management){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")。 

### 在一个位置查找所有 {{site.data.keyword.Bluemix_notm}} CLI 插件文档
最新更新日期：2018 年 11 月 30 日
{: #cli}

现在，您可以在一个位置访问所有 {{site.data.keyword.Bluemix_notm}} CLI 插件文档，能更轻松地找到要在 {{site.data.keyword.Bluemix_notm}} 平台上查找的任何 CLI 命令。请查看 [CLI 文档](/docs/cli?topic=cloud-cli-ibmcloud-cli)的“参考”部分。

### 查看新仪表板和资源列表
最新更新日期：2018 年 11 月 30 日
{: #dash}

通过最新更新，现在您可以在一个位置查看所有平台和基础架构服务。登录后，您可以立即查看新仪表板。将资源从目录添加到帐户后，可以使用资源列表来获取帐户资源的完整视图：

* 仪表板已重新设计，以便您可以查看资源、维护、状态、应用程序、支持、使用情况和用户的摘要。
* 可以在资源列表中找到有关资源的更多详细信息。您可以标记资源以对其进行组织，或者选择资源以在详细信息页面上对其进行更改。
* 既然您可以在一个位置查看所有资源，我们添加了全局搜索，以便您可以快速找到已创建并期望显示在“资源列表”页面上的资源。 
* 还可以搜索目录结果，以便快速找到要添加到帐户的资源。  

有关更多详细信息，请参阅 [Manage All Your Cloud Resources on the Enhanced {{site.data.keyword.Bluemix_notm}} Platform](https://www.ibm.com/blogs/cloud-archive/2018/11/manage-all-your-cloud-resources-on-the-enhanced-ibm-cloud-platform/){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")。

### 针对平台和基础架构服务的统一帐户、计费和用户概要文件信息
最新更新日期：2018 年 11 月 30 日
{: #profile}

现在简化了帐户、计费和概要文件信息。您可以在统一控制台中查看所有平台和基础架构资源的帐户信息。 

* 概要文件和设置区域，包含有关您的信息以及所有资源类型的电子邮件通知首选项。 
* 帐户信息区域，包含有关您的公司或组织的信息、帐户设置以及使用资源组和 Cloud Foundry 组织的快速访问权。您甚至可以找到最佳实践来帮助您快速入门并熟练运用！
* 帐户的计费和使用情况区域，可帮助您了解帐单，付款，监视预订，获取报价，跟踪订单以及设置花费通知。

有关更多详细信息，请查看 [Bringing It All Together: A Single Account and Billing Management Experience](https://www.ibm.com/cloud/blog/announcements/ibm-cloud-account-management){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")。

### 使用标记来组织资源
最新更新日期：2018 年 11 月 30 日
{: #tag}

现在，您可以向资源（如 Cloud Object Storage）添加标记，以帮助管理资源，以及查找与您最相关的资源。例如，如果您有数百个资源，而您希望区分付费方式相同的两个资源，那么可以使用 `costcenter:location01` 对其进行标记。或者，如果您有团队在重复使用两个资源，那么可以使用类似 `team-blue` 的标记。您还可以按标记过滤资源列表，以快速组织和查找所需的资源。有关更多信息，请参阅[使用标记](/docs/resources?topic=resources-tag)和 [Platform Tagging on the Enhanced {{site.data.keyword.Bluemix_notm}} Platform](https://www.ibm.com/cloud/blog/announcements/platform-tagging-on-the-enhanced-ibm-cloud-platform){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")。 

### 利用成本估算工具了解准确的每月成本
最新更新日期：2018 年 11 月 30 日
{: #cost-estimator}

为了帮助您决定并分析要购买的服务，您可以使用成本估算工具。现在，您可以浏览控制台并选择希望拥有的每个服务，然后在一个易用工具中加总所有成本。您甚至可以输入预测数据使用量、每秒查找次数、每秒写入次数和每秒查询次数，从而更准确地估算每月支出。对于所选的每个目录服务，可以使用成本估算工具，也可以单击控制台菜单中的“成本估算工具”图标 ![“成本估算工具”图标](../../icons/Estimator.svg) 来获取估算成本的摘要。有关更多信息，请参阅[估算成本](/docs/billing-usage?topic=billing-usage-cost)。

### 已更新 {{site.data.keyword.cloud_notm}} 的全球位置名
最新更新日期：2018 年 11 月 1 日
{: #location-name-updates}

{{site.data.keyword.cloud_notm}} 继续扩展我们的全球可用性占用量，我们将更新位置命名结构，以便更好地支持全球各地地理区域、区域和数据中心的可理解、一致的层次结构。如果您熟悉我们当前的全球区域，那么将会识别像美国南部和悉尼这样的名称。我们正在将这些位置名称与数据中心实际存在的城市的名称对应。

现在，程序化标识未更改，所以从 API 的角度来看没有影响。下表显示新旧位置名称。有关更多信息以及数据中心与区域的完整列表，请参阅[服务可用性](/docs/resources?topic=resources-services_region)。

|先前位置显示名称|新位置显示名称| 代码|
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
{: #acct-mgmt-services}

使用 {{site.data.keyword.cloud_notm}} Identity and Access Management (IAM)，您可以将作为帐户管理员完成的常见任务委派给帐户中的其他用户。通过在一个或所有可用帐户管理服务上创建访问策略，您可以轻松委派责任，如邀请和除去用户，管理访问组，管理服务标识，维护私有目录服务，甚至监视计费和跟踪使用情况。有四个单独的帐户管理服务和一个可用于设置访问策略的“所有服务”选项：

* 用于邀请和除去用户的用户管理
* 用于创建、编辑、删除、更新和分配访问权的 IAM 访问组 
* IAM 身份服务，用于查看、创建、删除和分配对整个帐户中的服务标识和关联的 API 密钥的访问权
* 用于查看私有目录产品并更新这些产品的元数据和可视性的全球资源目录
* 所有帐户管理服务，用于根据分配的角色访问每个帐户管理服务选项，以及访问计费和使用情况跟踪。

有关用户基于对其拥有策略的帐户管理服务和为其分配的角色而可以执行的任务的更多信息，请参阅[帐户管理服务的平台管理角色和操作示例](/docs/iam?topic=iam-userroles#platformrolestable2)。有关这个新功能的更多信息，请参阅 [Introducing More Flexibility and Control for IBM Cloud Account Management Services Access](https://www.ibm.com/cloud/blog/announcements/introducing-more-flexibility-and-control-for-ibm-cloud-account-management-services-access){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标") 博客帖子。 

### 搜索资源
最新更新日期：2018 年 7 月 17 日
{: #forward-slash-key}

您可以在 {{site.data.keyword.cloud_notm}} 控制台中的任何位置搜索资源。在控制台菜单栏的搜索字段中输入资源的名称。请按正斜杠键 (/) 以激活搜索。

### 将联合用户动态添加到访问组
最新更新日期：2018 年 7 月 12 日
{: #add-fed-users}

您可以创建动态规则，以根据特定身份属性自动将联合用户添加到访问组。当用户使用联合标识登录时，身份提供者中的数据会根据设置的规则，将用户动态映射到访问组。
有关更多信息，请参阅[为访问组创建动态规则](/docs/iam?topic=iam-rules)。

### 保护服务标识和 API 密钥
最新更新日期：2018 年 6 月 1 日
{: #protect-svcid-apikey}

为了避免因删除服务标识或 API 密钥而导致停机或中断的情况，您可以通过使用 UI 或 CLI 锁定服务标识和 API 密钥。锁定服务标识还可以防止变更、删除或分配任何访问策略，以及创建或删除与服务标识相关联的任何 API 密钥。有关更多信息，请参阅[锁定服务标识](/docs/iam?topic=iam-serviceidapikeys#lockkey)和[锁定 API 密钥](/docs/iam?topic=iam-userapikey)。

### 将轻量帐户升级为预订帐户
最新更新日期：2018 年 5 月 31 日
{: #upgrade-lite}

您现在可以直接从 {{site.data.keyword.Bluemix_notm}} 控制台将轻量帐户升级到预订帐户。有了预订帐户，您可以同时使用平台和基础架构产品，并通过做出每月开支和期限承诺来享受折扣定价。通过每月付款安排支付固定结算费用，还可避免意外，同时又可以根据需求灵活地选择多订购或少订购。有关更多信息，请参阅[预订帐户常见问题解答](/docs/billing-usage?topic=billing-usage-billusagefaqs#subs-order)。 

### {{site.data.keyword.Bluemix_notm}} CLI 更名
最新更新日期：2018 年 5 月 15 日
{: #cli-rebrand}

{{site.data.keyword.Bluemix_notm}} CLI 命令已从 **`bluemix`** 和 **`bx`** 更改为 **`ibmcloud`**。但是，您仍然可以使用 **`bluemix`** 和 **`bx`** CLI 命令，直到稍后这些命令被除去为止。
现在没有短名称，只有全名 **`ibmcloud`**。 

### {{site.data.keyword.Bluemix_notm}} 帐户的多因子认证
最新更新日期：2018 年 5 月 2 日
{: #account-mfa}

多因子认证 (MFA) 可为帐户提供额外一层的安全保护，因为它会要求所有用户在登录期间除了提供标准 IBM 标识和密码外，还要提供基于时间的一次性密码。通常，这也称为双因子认证 (2FA)。
MFA 是按帐户启用的，一旦启用后，帐户中的所有用户都必须通过使用这个额外的安全措施进行登录。有关更多信息，请参阅 [IBM Cloud Platform now adds support for Multi-Factor Authentication ](https://www.ibm.com/cloud/blog/ibm-cloud-platform-now-adds-support-multi-factor-authentication){: new_window}![外部链接图标](../../icons/launch-glyph.svg "外部链接图标") 博客帖子。

### 使用访问组快速分配访问权
最新更新日期：2018 年 4 月 3 日
{: #access-groups}

您是否希望能够尽可能使用最少数量的策略来快速分配访问权？现在，您可以使用访问组。访问组支持将一组用户和服务标识分组到一起，然后分配应用于该组中所有成员的单个策略。通过使用访问组，可以限制管理帐户中用户和服务标识访问权所花费的时间。有关更多详细信息，请查看博客帖子[新功能：访问组](https://www.ibm.com/cloud/blog/access-groups){: new_window}
![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")。

### 现在，{{site.data.keyword.Bluemix_notm}} Foundry 服务在美国东部区域可用
最新更新日期：2017 年 12 月 15 日
{: #cf-useast}

现在，新的美国东部数据中心在华盛顿可用。此新区域可以使用 `us-east.cloud.ibm.com` 端点进行访问。有关在此新区域中可购买的服务的详细信息，请参阅[按区域列出的服务](/docs/resources?topic=resources-services_region)。

### 支持欧盟中的资源
最新更新日期：2017 年 12 月 14 日
{: #eu-resources}

如果您的服务和数据中心位于欧洲，现在 {{site.data.keyword.Bluemix_notm}} 提供了额外的功能来保护您在欧盟的数据。您可以请求位于欧洲的客户成功团队提供支持。此支持全天候可用。有关更多信息，请参阅[启用“欧盟支持”选项](/docs/account?topic=account-eu-hipaa-supported#bill_eusupported)和[请求对欧盟中资源的支持](/docs/get-support?topic=get-support-getting-customer-support#eusupported)。

### 撤销对 TLS 1.0 和 1.1 的支持
最新更新日期：2017 年 11 月 28 日
{: #nosupport-tls}

2018 年 3 月 1 日，{{site.data.keyword.Bluemix_notm}} 将撤销对许多云产品和服务上 TLS 1.0 和 TLS 1.1 的支持；我们致力于提供高度安全且符合安全和数据隐私业界最佳实践的云，此更改正是这一工作的一部分。 

### 新增组织帐户中资源的方法
最新更新日期：2017 年 11 月 16 日
{: #usergs}

资源组是供您创建可定制帐户资源分组的新方法，并且对组的访问权以及组内的资源均使用 Identity and Access Management (IAM) 进行管理。所有人一开始只有缺省资源组。您可以重命名此资源组，并且可以在目录中创建新服务实例时，向此资源组添加这些实例。

如果您是使用现收现付或预订帐户的用户，那么可以创建其他资源组，以便更轻松地管理配额以及查看一组资源的计费使用情况。您还可以对资源进行分组，从而更轻松地为用户一次性分配对多个服务的访问权。要了解有关使用帐户的资源组的更多信息，请参阅[管理资源组](/docs/resources?topic=resources-rgs)。

### {{site.data.keyword.Bluemix_notm}} IAM 更新
最新更新日期：2017 年 11 月 16 日
{: #iam-nov17}

在 {{site.data.keyword.Bluemix_notm}} 帐户内引入的资源组为您分配访问权开辟了一条新的道路。可以为用户和服务标识分配对资源组内所有服务的访问权，从而使您可以一次性快速分配对多个资源的访问权。您还可以通过为每个用户或服务标识只分配对资源组内某些服务的访问权来定制访问权，或者选择分配对向下一直到服务实例级别的单个资源的访问权。有关可以通过 IAM 来利用的功能的更多信息，请参阅 [IAM 提供了哪些功能？](/docs/iam?topic=iam-iamoverview#features)

### 定制仪表板视图
最新更新日期：2017 年 11 月 16 日
{: #custom-dash}

可以在 {{site.data.keyword.Bluemix_notm}} 控制台的仪表板中，查看和管理帐户中的所有资源。现在，可以设置过滤器来定制视图。例如，可以按资源组进行过滤，以查看资源组中的特定资源。还可以按区域或按 Cloud Foundry 空间进行过滤。有关更多详细信息，请参阅[在仪表板上管理资源](/docs/overview?topic=overview-ui#dashboardview)。

### 支持中心
最新更新日期：2017 年 11 月 2 日
{: #support-nov17}

现在，我们有了新的支持中心，在其中可以搜索信息，向开发者社区发布问题以及管理凭单。在 {{site.data.keyword.Bluemix_notm}} 控制台菜单栏中，转至**支持 > 支持中心**。

### 推出 IBM Cloud
最新更新日期：2017 年 10 月 31 日
{: #meet-ibmcloud}

Bluemix 现已更名为 IBM Cloud。除了推出新名称外，没有更改其他任何内容。您仍可以像平时一样，轻松地构建和运行应用程序和服务。有关更多详细信息，请参阅 [IBM Cloud 博客](https://www.ibm.com/cloud/blog/announcements/bluemix-is-now-ibm-cloud){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")。

### 轻量帐户
最新更新日期：2017 年 10 月 31 日
{: #new-liteacct}

轻量帐户是我们的新帐户类型，让您有权免费试用精选服务，而没有时间限制。这个新帐户还包含使用情况跟踪和效率功能，可帮助您更好地管理资源。要了解可用功能的更多信息，请参阅[帐户类型](/docs/account?topic=account-accounts#liteaccount)。

### Identity and Access Management 应用程序认证功能
最新更新日期：2017 年 10 月 6 日
{: #app-authfeature}

现在，Identity and Access Management (IAM) 提供了创建服务标识的功能，您可以将其视为可供应用程序用于向 {{site.data.keyword.Bluemix_notm}} 服务进行认证的身份。服务标识可以使用以服务策略形式分配给服务标识的关联 API 密钥和访问许可权（而不使用个人用户凭证）进行创建，以便您可控制使用该标识进行认证的任何应用程序的访问级别。

有关此功能的优点以及如何开始使用的更多信息，请参阅 [Introducing IBM Cloud IAM Service IDs and API Keys](https://www.ibm.com/cloud/blog/introducing-ibm-cloud-iam-service-ids-api-keys){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")。

### {{site.data.keyword.Bluemix_notm}} 全局目录
最新更新日期：2017 年 7 月 27 日
{: #gc}

通过扩展上一次控制台更新以在控制台中从单个位置管理公共区域，{{site.data.keyword.Bluemix_notm}} 现在拥有全局目录，进一步简化了从目录中选择和部署项的过程。不管您在控制台中选择了哪个区域，现在都可以在目录中查看所有公共区域中可用的所有服务。在目录中选择一个磁贴后，即可以看到在其中该服务可用的区域，然后选择要在其中部署该服务的区域。有关目录最新更新的更多信息，请参阅 [A global {{site.data.keyword.Bluemix_notm}} catalog makes building things easier](https://www.ibm.com/cloud/blog/announcements/global-bluemix-catalog-makes-building-things-easier){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")。

### {{site.data.keyword.Bluemix_notm}} 控制台更新
最新更新日期：2017 年 5 月 23 日
{: #console-may17}

现在，您可以通过更新的 {{site.data.keyword.Bluemix_notm}} 控制台在单个位置管理各公共区域。区域选择器简化了访问资源的过程；其他增强功能包括可用性更高、性能更佳。有关更多信息，请查看 [New Global Bluemix UI for Higher Availability and More](https://www.ibm.com/blogs/bluemix/2017/05/new-global-bluemix-ui-higher-availability/){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")。

### Identity and Access Management
最新更新日期：2017 年 5 月 1 日
{: #iam-may17}

通过最新的更新和改进，现在 {{site.data.keyword.Bluemix_notm}} 帐户所有者或管理员可以使用新的统一访问控制 UI 来利用以下功能：
 * 采用新的访问控制功能后，可管理用户对 Kubernetes 服务和其他服务的细颗粒度访问权
 * 为其组织内的用户分配服务策略和 Cloud Foundry 角色

此外，{{site.data.keyword.Bluemix_notm}} 平台用户还可以创建、删除和列出与其用户标识关联的 API 密钥。平台用户在使用 API 或 CLI 时，可以使用这些 API 密钥进行认证。

最后，我们增强了统一用户管理能力，确保在链接的 IaaS-PaaS 帐户中统一管理用户，而无需在 SoftLayer 客户门户网站或 {{site.data.keyword.Bluemix_notm}} 控制台中单独添加用户。

有关更多信息，请查看 [Introducing Identity & Access Management](https://www.ibm.com/blogs/bluemix/2017/05/introducing-identity-access-management/){: new_window} ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标") 博客帖子。

### 更改了 {{site.data.keyword.Bluemix_notm}} 文档的导航设计
最新更新日期：2017 年 4 月 13 日
{: #docnavupdates}

借助这次导航更新，我们相信您可以了解整个文档中更合理的内容组织方式，并且能够更高效地查找相关内容。由于内容的嵌套层更少，您不必再四处搜寻来查找成功使用 {{site.data.keyword.Bluemix_notm}} 所需的文档。



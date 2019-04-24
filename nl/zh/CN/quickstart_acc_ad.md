---

copyright:

  years: 2018, 2019

lastupdated: "2019-02-19"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:tip: .tip}

# 设置帐户
{: #quickstart_acc_ad}

本快速入门指南旨在帮助帐户管理员设置其 {{site.data.keyword.Bluemix}} 环境。
{:shortdesc}

1. 创建资源组，以用于组织通过 {{site.data.keyword.Bluemix_notm}}“目录”创建的资源。有关更多信息，请参阅[使用资源组来组织资源的最佳实践](/docs/resources?topic=resources-bp_resourcegroups)。

  由于将资源分配给资源组后，即无法移动该资源，因此务必提前创建资源组。
  {:tip}
  
2. 并非所有服务都通过 {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) 进行管理，因此请创建 Cloud Foundry 组织以组织这些服务，并授予对这些服务的访问权。对于轻量帐户，您可以在一个 {{site.data.keyword.Bluemix_notm}} 位置建立一个 Cloud Foundry 组织。有关更多信息，请参阅[添加组织和空间](/docs/account?topic=account-orgsspacesusers)。 
3. 创建访问组，以将需要分配有相同级别访问权的用户和服务标识组织成组。有关更多信息，请参阅[设置访问组](/docs/iam?topic=iam-groups)。
4. 邀请用户加入帐户，并将其添加到访问组，以便为其分配必要的访问权，从而允许帐户用户进行构建。有关更多信息，请参阅 [IAM 入门教程](/docs/iam?topic=iam-getstarted)。
5. 设置事件和帐户花费限制的通知。有关更多信息，请参阅[设置电子邮件首选项](/docs/account?topic=account-email-prefs)和[设置花费通知](/docs/billing-usage?topic=billing-usage-spending)。 
6. 使用成本估算工具来了解环境可能需要的成本。单击控制台菜单栏中的“成本估算工具”图标 ![“成本估算工具”图标](../icons/Estimator.svg)。 
7. 使用成本估算工具来了解基础架构可能需要的成本。 
  
  a. 首先从[目录](https://cloud.ibm.com/catalog){: new_window} ![外部链接图标](../icons/launch-glyph.svg) 中选择产品。 
  
  b. 输入配置详细信息，选择价格套餐，然后单击**添加到估算**。

## 后续步骤
{: #next-steps-acc-ad}

* 开始在帐户中创建服务，使组织和开发者能够构建所需的解决方案。  
* 创建标记并标记资源，以帮助对您查看计费和使用情况的方式进行组织。这样一来，您可以更轻松地确定针对不同组织的退款。有关更多信息，请参阅[标记资源的最佳实践](/docs/account?topic=account-account_setup#tags)。 

---

copyright:

  years: 2017, 2018

lastupdated: "2017-11-10"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}

# 在 {{site.data.keyword.Bluemix_notm}} 中管理访问权
{: #cloudaccess}

## 什么是访问权管理？

通过访问权管理，可以控制哪些用户可以查看、创建、使用和管理帐户中的资源。要授予访问权，可以分配角色以允许用户拥有完成平台管理任务和访问帐户资源所需的访问级别。

在 {{site.data.keyword.Bluemix_notm}} 中管理访问权的方式取决于要分配其访问权的资源的类型。{{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) 是一种访问权管理系统，用于在整个 {{site.data.keyword.Bluemix_notm}} 平台上以一致的方式管理资源。{{site.data.keyword.Bluemix_notm}} 基础架构和 Cloud Foundry 资源不使用 Cloud IAM 进行管理。这些资源类型有自己的访问权管理系统。如果您具有资源类型的组合，请分别管理每种类型。要分配对基础架构资源的访问权，请在 SoftLayer 帐户内设置许可权。要分配对 Cloud Foundry 资源的访问权，请使用控制台的“身份和访问权”部分中的“使用 Cloud Foundry 进行分配”选项。

## 谁有权管理访问权？

作为帐户所有者，您可以管理对帐户中所有资源的访问权。此外，还可以通过在帐户内为用户分配对所有服务的管理员角色，以委派管理平台资源访问权的任务。

如果帐户中有 Cloud Foundry 服务，那么可以将组织或空间管理员角色分配给其他用户，以便该用户可添加用户并分配 Cloud Foundry 用户角色来访问其所管理的组织或空间中的实例。


## 如何开始管理访问权？

转至**管理** &gt; **安全性** &gt; **身份和访问权**，然后选择**用户**以开始管理您帐户中用户的访问权。请从列表中选择用户以开始。您只会看到您有权管理的访问权管理选项。例如，如果您不是帐户所有者，也不是组织或空间管理员，那么不会看到用于管理 Cloud Foundry 访问权的选项。

还可以使用服务标识将访问角色分配给应用程序和服务。请转至**服务标识**页面以开始。有关如何快速入门和熟悉运用 Cloud IAM 的更多信息，请遵循[入门教程](/docs/iam/quickstart.html#iambestpractice)中的步骤。

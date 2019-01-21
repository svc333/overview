---

copyright:
  years: 2017, 2018
lastupdated: "2018-10-11"

---

{:shortdesc: .shortdesc}

# 使用资源组来组织资源
{: #whatis}

使用资源组，您可以为帐户[资源](/docs/resources/acct_resources.html#resource)定制分组，以便一次性为用户快速分配对多个资源的访问权。凡是使用 {{site.data.keyword.Bluemix}} Identity and Access Management (IAM) 访问控制来管理的帐户资源都属于您帐户中的某个资源组。从目录中向帐户添加新资源时，可以将该资源分配到资源组中。唯一的例外是 Kubernetes，它不会提示您分配资源组，但可使用 IAM 角色来控制对该服务的访问权。

使用 {{site.data.keyword.Bluemix}} IAM 进行管理并且属于资源组的服务具有若干优点，包括连接到任何 Cloud Foundry 空间中的应用程序和服务的能力，这支持您连接来自不同位置的应用程序和服务。资源组不是按位置划分的，因此可以将来自不同位置的应用程序和服务供应给同一资源组。您还可以使用下至资源组内单个实例的细颗粒度访问控制。

有关使用资源组的更多信息，请参阅[管理资源组](/docs/resources/resourcegroups.html)。如果您不了解如何使用资源组，请参阅[使用资源组来组织资源的最佳实践](/docs/resources/bestpractice_rgs.html#bp_resourcegroups)。

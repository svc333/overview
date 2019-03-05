---

copyright:
  years: 2017, 2019
lastupdated: "2019-02-19"

---

{:shortdesc: .shortdesc}

# 使用资源组来组织资源
{: #whatis-rgs}

资源组是一种使用可定制的分组来组织帐户资源的方法，可帮助您一次性快速为用户分配对多个资源的访问权。使用 {{site.data.keyword.Bluemix}} Identity and Access Management (IAM) 访问控制来管理的任何帐户资源都属于您帐户中的资源组。从目录中向帐户添加资源时，可以将该资源分配到资源组中。唯一的例外是 Kubernetes，它不会提示您分配资源组，但可使用 IAM 角色来控制对该服务的访问权。

使用 {{site.data.keyword.Bluemix_notm}} IAM 进行管理并且属于某个资源组的服务具有若干优点。例如，能够连接到任何 Cloud Foundry 空间中的应用程序和服务。这意味着，您可以连接来自不同位置的应用程序和服务。资源组不是按位置划分的，因此可以将来自不同位置的应用程序和服务供应给同一资源组。您还可以使用下至资源组内单个实例的细颗粒度访问控制。

有关使用资源组的更多信息，请参阅[管理资源组](/docs/resources?topic=resources-rgs)。 

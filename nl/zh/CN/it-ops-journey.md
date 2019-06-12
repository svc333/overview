---

copyright:
  years: 2018, 2019
lastupdated: "2019-06-04"

keywords: cloud environment, virtual server, virtual machine, vm, understanding infrastructure, IaaS model

subcollection: overview


---
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}
{:tip: .tip}
{:note: .note}

# 探索 {{site.data.keyword.cloud_notm}} 中 IT 运营管理员的旅程
{: #it-ops}

随着许多组织移至云环境（无论是内部部署还是在数据中心托管），IT 运营管理员的角色会进行重新定义。根据组织想要部署的环境类型，这一角色变化的范围和复杂性会显著增加。
{: .shortdesc}

在移至云之前，您使用的是本身安全的环境，其中各个系统连接到专用 LAN 或内部网。在云环境中，现在您应该执行以下任务：
 
  * 从“某处”购买系统组件。 
  * 了解网络影响和安全性挑战。
  * 使用不同的技术。  
  * 将新环境与本身不属于云堆栈的工具集成在一起。 
  * 继续为内部客户提供支持，就像您仍拥有内部部署数据中心一样。

{{site.data.keyword.cloud}} 在此是为了向您的探索之旅提供全力支持。可供您使用的资源包括综合文档、规划工具、合格的支持专家以及活跃的用户社区。让我们助您踏上探索之旅吧！ 

## 了解基础知识
{: #basics}

### 云服务模型
{: #cloud-svc-models}

存在三种类型的云服务模型：基础架构即服务 (IaaS)、平台即服务 (PaaS) 和软件即服务 (SaaS)。图 1 说明了谁在每种服务模型中执行什么操作。有关更多信息，请参阅 [IaaS, PaaS, and SaaS - IBM Cloud service models](https://www.ibm.com/cloud/learn/iaas-paas-saas){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")。

![图 1. 云服务模型](images/cloud-svc-models.png "云服务模型")

使用 IaaS 模型时，提供者仅负责维护底层基础架构，并可选择安装软件，例如操作系统、应用程序和数据库。您具有对底层基础架构的有限访问权，并且您要负责安装软件或要求服务供应商安装软件。您还负责其他所有维护，包括 Service Pack、防病毒软件和补丁。

使用 PaaS 模型时，提供者负责通过操作系统来管理各系统，还负责所有基础架构管理，包括操作系统补丁、硬件维修和网络设置。您负责构建和维护应用程序，并且您或提供者可以安装中间件，包括数据库或其他类型的中间件。此模型用于开发和测试软件。有关更多信息，请参阅 [A practical guide to platform as a service: What is PaaS ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")](https://www.ibm.com/blogs/cloud-computing/2016/08/10/practical-guide-paas/){: new_window}。

使用 SaaS 模型时，提供者通过实际应用程序维护各系统。该应用程序属于云感知应用程序，用户可以根据软件提供者的要求使用不同的端点来运行软件。云提供者负责所有基础架构和应用程序管理，包括软件更新、硬件维修和网络设置。此模型通常用于现收现付软件许可模型。有关更多信息，请参阅 [SaaS applications for business and IT](https://www.ibm.com/cloud/saas){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")。

### 云类型
{: #cloud-types}

有三种不同类型的云可用：公共云、私有云和混合云。公共云包含一组共享资源，供应用于允许访问公司的资源。公共云在虚拟服务器上的多租户环境中托管，并且可以从任何位置进行访问。 

私有云包含的资源供应用于允许访问公司的资源。私有云在专用硬件（如裸机服务器）上托管，专用硬件可位于公司现场的一个办公室（或跨多个办公室），也可以由云提供者供应。私有云可以从任何位置进行访问。

混合云包括组合了公共云和私有云各个方面的资源。混合云在公司的一个办公室（或跨多个办公室）现场托管或由云提供者托管。混合云可以从任何位置进行访问。 

## 规划基础架构
{: #planning}

在供应基础架构之前，您需要先规划基础架构，以确保针对工作负载正确调整基础架构的大小。{{site.data.keyword.cloud_notm}} 有多个工具和站点可帮助您设计基础架构并调整其大小。 

### 基础架构体系结构

首先查看[基础架构体系结构 ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")](https://www.ibm.com/cloud/garage/architectures/infrastructure){: new_window}，以更深入地了解这三种类型云环境的总体情况。 

### {{site.data.keyword.cloud_notm}} Design Decision Tool

[{{site.data.keyword.cloud_notm}} Design Decision Tool ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")](https://github.com/ibm-cloud-architecture/infrastructure-design-decision-tool/){: new_window} 可帮助您在设计和构建定制解决方案时比较替代项。每个基础架构组件都具有描述、注意事项和警告，以及并列比较。您还可以找到如何使用该工具的示例。

### {{site.data.keyword.cloud_notm}} Stencils

[{{site.data.keyword.cloud_notm}} Stencils ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")](https://github.com/ibm-cloud-architecture/ibm-cloud-stencils){: new_window} 使用常用的制图工具帮助您创建 {{site.data.keyword.cloud_notm}} 体系结构图。 

### 裸机服务器选项

使用 [{{site.data.keyword.cloud_notm}} {{site.data.keyword.baremetal_short}} 搜索工具 ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")](https://www.ibm.com/cloud-computing/bluemix/bare-metal-search){: new_window} 可调整裸机服务器选项的大小并进行估算，包括经过认证可支持 SAP HANA 和 SAP NetWeaver 工作负载的服务器。

### {{site.data.keyword.cloud_notm}} 服务与合规性

与任何体系结构一样，您应该考虑在调整基础架构大小时，可能会添加到解决方案中的 {{site.data.keyword.cloud_notm}} 资源。有关更多信息，请参阅 [SaaS applications for business and IT ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")](https://www.ibm.com/cloud/saas){: new_window}，并搜索特定服务。您还需要考虑在构建体系结构时必须顾及的任何法规。例如，工作负载是否被视为敏感工作负载，或者是否受监管？有关更多信息，请参阅 [Compliance ![外部链接图标](../icons/launch-glyph.svg " 外部链接图标")](https://www.ibm.com/cloud/compliance){: new_window}。

## 构建基础架构
{: #build}

在规划和设计基础架构之后，就可以开始构建基础架构。 

### 计算
{: #compute}

服务器是基础架构的基础。根据您的需求，您有多种选项可选择，或者如果环境需要，可以混用使用这些选项。请查看下表以获取计算选项的摘要。

|选项|描述
| 
|--------|---------------|
| [{{site.data.keyword.baremetal_short}}](/docs/bare-metal?topic=bare-metal-about-bm#about-bm)  |专供您使用的按小时或按月计费的单租户服务器，任何部分（包括服务器资源）都不会与其他客户共享。|
| [{{site.data.keyword.BluVirtServers_short}}](/docs/vsi?topic=virtual-servers-getting-started-tutorial) |可缩放的虚拟服务器，随核心和内存分配一起购买。|
| [{{site.data.keyword.vmwaresolutions_short}}](/docs/services/vmwaresolutions?topic=vmware-solutions-getting-started#getting-started) |使用安全、可扩展的高性能基础架构和行业领先的 VMware 混合虚拟化技术，快速无缝地集成或迁移内部部署 VMware 工作负载。|
| [{{site.data.keyword.containerlong_notm}}](/docs/containers?topic=containers-container_index) |将 Docker 容器、Kubernetes 技术、直观的用户体验和内置安全性与隔离功能组合在一起，自动对计算主机集群中的容器化应用程序进行部署、操作、扩展和监视。|
| [{{site.data.keyword.cfee_full_notm}}](/docs/cloud-foundry?topic=cloud-foundry-about) |按需实例化多个隔离的企业级 Cloud Foundry 平台。|
| [{{site.data.keyword.openwhisk_short}}](/docs/openwhisk?topic=cloud-functions-getting_started#getting_started) |基于 Apache OpenWhisk 的函数即服务 (FaaaS) 编程平台。|
{: caption="表 1. 计算选项" caption-side="top"}
   
### 存储
{: #storage}

{{site.data.keyword.baremetal_short}} 和 {{site.data.keyword.BluVirtServers_short}} 供应有缺省存储器。{{site.data.keyword.baremetal_short}} 至少有 1 TB SATA 磁盘空间，{{site.data.keyword.BluVirtServers_short}} 至少有 25 GB SAN 存储器。对此例外的情况是 {{site.data.keyword.cloud_notm}} SAP 认证的 {{site.data.keyword.baremetal_short}}。有关这些服务器可用的缺省存储器的更多信息，请参阅 [{{site.data.keyword.cloud_notm}} SAP 认证的基础架构](/docs/bare-metal?topic=bare-metal-sap-cert-infrastructure#sap-cert-infrastructure)。

您可以根据需要购买额外的存储器。请参阅下表以获取存储选项的摘要。

|选项|描述
|
|--------|---------------|
| [{{site.data.keyword.blockstorageshort}}](/docs/infrastructure/BlockStorage?topic=BlockStorage-getting-started) |持久的高性能 iSCSI 存储器，可独立于计算实例进行供应和管理。基于 iSCSI 的块存储器 LUN 通过冗余多路径 I/O (MPIO) 连接来连接到授权设备。|
| [{{site.data.keyword.filestorage_short}}](/docs/infrastructure/FileStorage?topic=FileStorage-getting-started) |网络连接的基于 NFS 的文件存储器，具有持久、快速、灵活的特点。在此网络连接存储器 (NAS) 环境中，您对文件共享功能和性能具有完全控制权。文件存储器共享可以通过路由的 TCP/IP 连接与最多 64 个授权设备相连接，以实现弹性。|
| [{{site.data.keyword.cos_full_notm}}](/docs/services/cloud-object-storage?topic=cloud-object-storage-getting-started) |使用 IBM Cloud Object Storage 存储的信息经过加密并分布在多个地理位置中，可利用 REST API 通过 HTTP 进行访问。此服务利用了 IBM Cloud Object Storage 系统（以前称为 Cleversafe）提供的分布式存储技术。|
| [{{site.data.keyword.cloud_notm}} Master Data Management](/docs/services/MDMOnCloud?topic=MDMOnCloud-mdmoc_getting_started#mdmoc_getting_started) |Cloud Object Storage 存储区分担内部部署数据中心的大量数据。|
| [{{site.data.keyword.backup_full}}](/docs/infrastructure/Backup?topic=Backup-getting-started) |基于代理程序的自动备份系统，通过基于浏览器的管理实用程序进行管理。可以在 IBM Cloud 网络上的一个或多个数据中心内的服务器之间备份数据。|
{: caption="表 2. 存储选项" caption-side="top"}

### 联网
{: #network}

在设置 {{site.data.keyword.cloud_notm}} 帐户时，会自动建立与 {{site.data.keyword.vpn_full}} 的连接。缺省情况下，服务器有一个公共 IP 地址和一个专用 IP 地址。如果希望服务器为专用服务器，那么可在供应服务器后关闭公共接口，也可以将该服务器作为专用服务器进行订购。有关更多信息，请参阅[虚拟专用网入门](/docs/infrastructure/iaas-vpn?topic=VPN-gettingstarted-with-virtual-private-networking)。

在基础架构层中，可以构建虚拟私有云，这是与 {{site.data.keyword.cloud_notm}} 帐户绑定的虚拟网络。通过虚拟私有云这个入口点，可以提供云安全性以及动态缩放虚拟服务器实例的能力。有关更多信息，请参阅 [IBM Cloud Virtual Private Cloud (VPC) 基础架构入门](/docs/vpc-on-classic?topic=vpc-on-classic-getting-started)。

请查看下表以获取联网选项的摘要。

|选项|描述
| 
|--------|---------------|
|[内容交付网络](/docs/infrastructure/CDN?topic=CDN-getting-started)|用于各种行业解决方案，包括媒体、娱乐、软件、游戏、银行和电子商务，以满足企业的需求。|
|[域名服务](/docs/cli/reference/ibmcloud?topic=cloud-cli-ibm-dev-tools-for-jetbrains)|提供了一个中心位置，可通过基本 DNS 管理界面来查看和管理您自己的域，此外还提供了用于在同一位置中免费管理逆向和辅助 DNS 的选项。|
|[全局 IP 地址](/docs/infrastructure/subnets?topic=subnets-about-global-ip-address#about-global-ip-address)|提供灵活性，并支持在服务器之间移动工作负载，甚至能在地理位置分散的数据中心之间移动工作负载。|
|[负载均衡](/docs/infrastructure/loadbalancer-service?topic=loadbalancer-service-getting-started)|在数据中心内的多个服务器之间均匀地分配处理和通信，以便不会有单个设备承载整个负载。|
|[虚拟路由器设备](/docs/infrastructure/virtual-router-appliance?topic=virtual-router-appliance-getting-started)|有选择地通过全功能的企业路由器（包含防火墙、流量塑形、基于策略的路由、VPN 及其他许多功能）来路由专用和公用网络流量。|
|[IPSec VPN](/docs/infrastructure/iaas-vpn?topic=VPN-setup-ipsec-vpn#setup-ipsec-vpn)|一套协议，旨在使用提供加密的站点到站点网络的隧道方式，对两个位置之间的所有 IP 流量进行认证和加密。|
| [{{site.data.keyword.cloud_notm}} Direct Link](/docs/infrastructure/direct-link?topic=direct-link-get-started-with-ibm-cloud-direct-link#get-started-with-ibm-cloud-direct-link) |利用云交换提供者来交付与 {{site.data.keyword.cloud_notm}} 基础架构位置的连接。|
{: caption="表 3. 联网选项" caption-side="top"}


## 管理基础架构
{: #managing}

构建基础架构和环境后，就可以开始对其进行管理。

|任务|描述
|
|--------|---------------|
|[监视系统事件](/docs/account?topic=account-audit-log)|查看已对基础架构资源执行的操作。|
|[设置电子邮件首选项](/docs/account?topic=account-email-prefs)|设置有关计划外事件、维护和声明的 {{site.data.keyword.cloud_notm}} 基础架构电子邮件通知。|
|[了解数据安全程度](/docs/overview?topic=overview-security)|{{site.data.keyword.cloud_notm}} 平台通过不同的层对整个网络和基础架构进行安全控制。|
|[了解如何确保零停机时间](/docs/overview?topic=overview-zero-downtime)|所有 {{site.data.keyword.cloud_notm}} 资源都在全球范围的各数据中心位置进行托管。|
{: caption="表 4. 管理任务" caption-side="top"}

---
copyright:
  years: 2019
lastupdated: "2019-06-04"

keywords: understanding infrastructure, vpc, classic infrastructure, cloud environment

subcollection: overview

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}
{:tip: .tip}
{:note: .note}

# 比较 {{site.data.keyword.cloud_notm}} 基础架构环境
{: #compare-infrastructure}

比较 {{site.data.keyword.cloud}} 基础架构环境之间的主要差异，以决定哪个环境最适合您的工作负载和应用程序。
{: shortdesc}

如果您不熟悉环境类型，请查看以下描述。

* 经典基础架构是现有的 IaaS 平台。此环境最适合用于直接迁移工作负载，允许您快速移动应用程序并保持体系结构不变。
* VPC 基础架构是新的 IaaS 平台，基于软件定义的网络，最适合用于云本机应用程序。

经典基础架构和 VPC 基础架构都无需额外成本，因此您只需重点关注哪个环境最符合您的需求。
{: note}

## 计算差异因素
{: #compare-compute}

有关经典和 VPC 基础架构之间的计算差异，请参阅下表。“类别”列中列出了各种差异因素，相关描述列在“经典基础架构”和“VPC 基础架构”列中。 

|类别|经典基础架构|VPC 基础架构|
| ---------- | ------------------------- | ------------------ |
|服务|完整目录的服务，例如 {{site.data.keyword.baremetal_short}}、{{site.data.keyword.BluVirtServers_short}} 实例、VMware 和 SAP|仅 {{site.data.keyword.BluVirtServers_short}} 实例|
|性能和可用性| |通过专区体系结构可实现更高可用性|
|定价|按小时和按月计费，以及暂挂计费功能|按小时计费、暂挂计费和持续使用量折扣|
|虚拟服务器系列|公共、专用、瞬态和保留|仅公共|
|概要文件|所有概要文件，包括 GPU 概要文件|均衡、计算和内存概要文件，可使用更高 RAM 和 vCPU 选项|
|支持的映像|完整的预储备映像集，以及定制映像|有限的预储备映像集|
|平台集成| |IAM 和资源组集成，可实现统一的体验|
{: caption="表 1. 计算比较" caption-side="top"}

## 网络差异因素
{: #compare-network}

有关经典和 VPC 基础架构之间的联网差异，请参阅下表。“类别”列中列出了各种差异因素，相关描述列在“经典基础架构”和“VPC 基础架构”列中。 

|类别|经典基础架构|VPC 基础架构|
| ---------- | ------------------------- | ------------------ |
|位置构造|数据中心和 POD<br>（可能需要 VLAN 生成来连接两个不同的 pod/数据中心，并购买网关来控制和路由流量）|区域模型，用于对基础架构进行抽象化处理，因此您无需担心 pod 位置。|
|网络功能和服务|来自多个供应商的物理和虚拟设备|云本机网络功能（VPN 和 LBaaS）<br>（VPC 隔离，公共云中独立出来的专用资源，有更多选项可用于 VPN、LBaaS、多个 vNIC 实例和更大的子网大小）|
|IP 地址|支持 IPv6 地址|仅支持 IPv4 地址|
|网关路由|使用虚拟或物理网络设备（虚拟路由器设备、Vyatta、Juniper vSRX 和 Fortinet FSA）|流量路由由公共网关和浮动 IP 服务进行处理|
|网络地址转换 (NAT)|使用虚拟或物理网络设备（虚拟路由器设备、Vyatta、Juniper vSRX 和 Fortinet FSA）|通过自带 IP (BYOIP) 功能支持|
|IPsec 虚拟专用网 (VPN)|使用虚拟或物理网络设备（虚拟路由器设备、Vyatta、Juniper vSRX 和 Fortinet FSA）|通过 VPN 即服务产品支持|
|弹性负载均衡|Cloud Load Balancer|Load Balancer for VPC|
|全局负载均衡|Cloud Internet Services 和 Citrix Netscaler MPX|Cloud Internet Services|
|混合连接|NAT 解决方案，用于桥接 IBM Cloud 和您的 IT 环境|自带专用 IP 地址，无需 NAT 或 IPSec 隧道<br>注：您可以允许 VPC 访问经典基础架构资源。|
{: caption="表 2. 网络比较" caption-side="top"}

## 存储差异因素
{: #compare-storage}

|经典基础架构|VPC 基础架构|
| ------------------------- | ------------------ |
|稳健的存储服务集、块存储器 (iSCSI) 和文件存储器（基于 NFS）产品集|块存储器作为主引导磁盘（使用基本生命周期管理）以及辅助数据卷<br> 注：在供应期间可以使用卷加密。|
{: caption="表 3. 存储比较" caption-side="top"}

## 安全性差异因素
{: #compare-security}

|经典基础架构|VPC 基础架构|
| ---------- | ------------------------- |
|Vyatta、Fortigate、Juniper vSRX 和用于 VSI 的安全组|安全组和网络访问控制表 (ACL)|
{: caption="表 4. 安全性比较" caption-side="top"}

## API 差异因素
{: #compare-apis}

|经典基础架构|VPC 基础架构|
| ------------------------- | ------------------ |
|现有 {{site.data.keyword.slapi_short}} (SLAPI)|开发者友好的基于 REST 的新 API|
{: caption="表 5. API 比较" caption-side="top"}

## 后续步骤
{: #compare-nextsteps}

要查看所有 VPC 基础架构功能，请参阅[关于 Virtual Private Cloud](/docs/vpc-on-classic?topic=vpc-on-classic-about)。要开始全面探索基础架构，请参阅[构建基础架构](/docs/overview?topic=overview-first-steps-it-ops)。

---
copyright:
  years: 2019
lastupdated: "2019-06-05"

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

# 比較 {{site.data.keyword.cloud_notm}} 基礎架構環境
{: #compare-infrastructure}

比較 {{site.data.keyword.cloud}} 基礎架構環境之間的重要差異，以決定最適合您工作負載及應用程式的基礎架構環境。
{: shortdesc}

如果您不熟悉環境類型，則請檢閱下列說明。

* 標準基礎架構是現有 IaaS 平台。此環境最適合提升及移轉工作負載，可讓您快速移動應用程式，並保留相同的架構。
* VPC 基礎架構是新的 IaaS 平台，以軟體定義網路為基礎，最適用於雲端原生應用程式。

標準基礎架構及 VPC 基礎架構的成本相當，因此，您可以聚焦於最符合您需求的環境。
{: note}

## 運算差異因子
{: #compare-compute}

如需標準與 VPC 之間的運算差異，請參閱下表。 

| 種類   |  標準基礎架構   | VPC 基礎架構 |
| ---------- | ------------------------- | ------------------ |
|服務|完整服務型錄，例如 {{site.data.keyword.baremetal_short}}、{{site.data.keyword.BluVirtServers_short}} 實例、VMware、SAP | 僅限 {{site.data.keyword.BluVirtServers_short}} 實例 |
| 效能及可用性 | | 可透過區域架構達成的較佳可用性 |
|定價| 按小時及按月計費，加上暫停計費特性 | 按小時、暫停計費及持續使用折扣 |
| 虛擬伺服器系列 | 公用、專用、暫時性、保留 | 僅限公用 |
| 設定檔 | 所有設定檔，包括 GPU 設定檔 | 具有較高 RAM 及 vCPU 選項的平衡、運算、記憶體設定檔 |
| 支援的映像檔 | 一組完整的預先庫存映像檔，再加上自訂映像檔 | 一組有限的預先庫存映像檔|
| 平台整合 | | IAM 與資源群組整合以獲得統一體驗 |
{: row-headers}
{: class="comparison-table"}
{: caption="表 1. 運算比較" caption-side="top"}
{: summary="This table has row and column headers. The row headers identify possible features. The column headers indentify the differentiators between classic infrastructure and VPC infrastructure. To understand the differences between environments, navigate to the row and find the details for the feature that you're interested in."}

## 網路差異因子
{: #compare-network}

如需標準與 VPC 之間的網路差異，請參閱下表。  

| 種類   |  標準基礎架構   | VPC 基礎架構 |
| ---------- | ------------------------- | ------------------ |
| 位置建構    | 資料中心及 POD <br>（可能需要 VLAN Spanning 才能連接兩個不同的 Pod/資料中心，以及採購閘道來控制及遞送資料流量）|可讓基礎架構抽象化，讓您不需要擔心 Pod 位置的地區模型。|
| 網路功能及服務 | 來自多個供應商的實體及虛擬應用裝置 | 雲端原生網路功能（VPN、LBaaS）<br>（VPC 隔離、與公用雲端切割的專用資源、具有 VPN 的選項、LBaaS、多個 vNIC 實例，以及較大的子網路大小）|
| IP 位址 | 支援 IPv6 位址 | 僅限 IPv4 位址 |
| 閘道遞送 | 使用虛擬或實體網路應用裝置（Virtual Router Appliance、Vyatta、Juniper vSRX、Fortinet FSA）| 資料流量遞送是由公用閘道及浮動 IP 服務進行管理 |
| 網址轉換 (NAT) | 使用虛擬或實體網路應用裝置（Virtual Router Appliance、Vyatta、Juniper vSRX、Fortinet FSA）| 由「自帶 IP (BYOIP)」功能進行支援  |
| IPsec 虛擬專用網路 (VPN) | 使用虛擬或實體網路應用裝置（Virtual Router Appliance、Vyatta、Juniper vSRX、Fortinet FSA）| 與 VPN 即服務供應項目一起支援 |
| 彈性負載平衡 | Cloud Load Balancer  | Load Balancer for VPC |
| 廣域負載平衡 | Cloud Internet Services、Citrix Netscaler MPX | Cloud Internet Services |
| 混合式連線功能 | 要在 IBM Cloud 與 IT 環境之間橋接的 NAT 解決方案 | 沒有 NAT 或 IPSec 通道的自帶專用 IP 位址 <br>附註：您可以啟用 VPC 來存取標準基礎架構資源。|
{: row-headers}
{: class="comparison-table"}
{: caption="表 2. 網路比較" caption-side="top"}
{: summary="This table has row and column headers. The row headers identify possible features. The column headers indentify the differentiators between classic infrastructure and VPC infrastructure. To understand the differences between environments, navigate to the row and find the details for the feature that you're interested in."}

## 儲存空間差異因子
{: #compare-storage}

如需標準與 VPC 之間的儲存空間差異，請參閱下表。

|  標準基礎架構   | VPC 基礎架構 |
| ------------------------- | ------------------ |
|一組穩健的儲存空間服務、區塊儲存空間 (iSCSI) 及檔案儲存空間（以 NFS 為基礎）供應項目| 區塊儲存空間作為主要開機磁碟（具有基本生命週期管理），及次要資料磁區  <br> 附註：在佈建期間提供磁區加密。|
{: caption="表 3. 儲存空間比較" caption-side="top"}

## 安全差異因子
{: #compare-security}

如需標準與 VPC 之間的安全差異，請參閱下表。

|  標準基礎架構   | VPC 基礎架構 |
| ---------- | ------------------------- |
|Vyatta、Fortigate、Juniper vSRX、Security Group for VSI| 安全群組、網路存取控制清單 (ACL)|
{: caption="表 4. 安全比較" caption-side="top"}

## API 差異因子
{: #compare-apis}

如需標準與 VPC 之間的 API 差異，請參閱下表。

|  標準基礎架構   | VPC 基礎架構 |
| ------------------------- | ------------------ |
|現有 {{site.data.keyword.slapi_short}} (SLAPI)| 新的對開發人員友善、REST 型 API |
{: caption="表 5. API 比較" caption-side="top"}

## 後續步驟
{: #compare-nextsteps}

若要檢閱所有 VPC 基礎架構功能，請參閱[關於 Virtual Private Cloud](/docs/vpc-on-classic?topic=vpc-on-classic-about)。若要開始整體探索基礎架構，請參閱[建置基礎架構](/docs/overview?topic=overview-first-steps-it-ops)。

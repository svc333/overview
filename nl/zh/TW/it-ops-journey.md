---

copyright:
  years: 2018, 2019
lastupdated: "2019-01-04"


---
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}
{:tip: .tip}
{:note: .note}

# 探索 {{site.data.keyword.cloud_notm}} 中的 IT 作業管理者旅程
{: #it-ops}

隨著許多組織紛紛移至雲端環境，不論是內部部署或在資料中心進行管理，IT 作業管理者 (IT ops admin) 角色正在重新定義。此變更的範圍及複雜性將根據您的組織想要部署的環境類型而大幅增加。
{: .shortdesc}

在移至雲端之前，您使用既有的安全環境，將系統連接至專用 LAN 或內部網路。在雲端環境中，您現在應該執行下列作業：
 
  * 從「某處」採購系統元件。 
  * 瞭解網路影響及安全挑戰。
  * 使用不同技術。  
  * 整合新環境與原本不在雲端堆疊中的工具。 
  * 繼續支援您的內部客戶，彷彿您還有內部部署資料中心一樣。

{{site.data.keyword.cloud}} 會在您的旅程中 100% 支援您。您可用的資源包括完整文件、規劃工具、合格的支援專家，以及活躍的使用者社群。讓我們帶領您展開旅程。 

## 瞭解基本觀念
{: #basics}

### 雲端服務模型
{: #cloud-svc-models}

雲端服務模型有三種類型：「基礎架構即服務 (IaaS)」、「平台即服務 (PaaS)」及「軟體即服務 (SaaS)」。圖 1 說明誰在每一個服務模型中執行了哪些動作。如需相關資訊，請參閱 [IaaS, PaaS, and SaaS - IBM Cloud service models ](https://www.ibm.com/cloud/learn/iaas-paas-saas){: new_window}![外部鏈結圖示](../icons/launch-glyph.svg "外部鏈結圖示")。

![圖 1. 雲端服務模型](images/cloud-svc-models.png "雲端服務模型")

使用 IaaS 模型時，您的提供者僅負責維護基礎架構，並選擇性地安裝軟體，例如作業系統、應用程式及資料庫。您對於深層的基礎架構具有有限存取權，並負責安裝軟體，或是讓服務提供者進行安裝。您也負責其他所有維護，包括服務套件、病毒軟體及修補程式。

使用 PaaS 模型時，您的提供者負責直到作業系統的所有系統，也負責所有基礎架構管理，包括 OS 修補程式、硬體修復及網路設定。您可以建置及維護應用程式，您或提供者則可以安裝中介軟體，包括資料庫或其他類型。這個模型是用來開發和測試軟體。如需相關資訊，請參閱 [A practical guide to platform as a service: What is PaaS ![外部鏈結圖示](../icons/launch-glyph.svg "外部鏈結圖示")](https://www.ibm.com/blogs/cloud-computing/2016/08/10/practical-guide-paas/){: new_window}。

使用 SaaS 模型時，您的提供者會維護直到實際應用程式的所有系統。應用程式能感知雲端，使用者則可以透過不同的端點（視軟體提供者而定）來使用軟體。雲端提供者負責進行所有基礎架構和應用程式管理，包括軟體更新、硬體修復及網路設定。此模型通常用於隨收隨付制的軟體授權模型。如需相關資訊，請參閱 [SaaS applications for business and IT ](https://www.ibm.com/cloud/saas){: new_window}![外部鏈結圖示](../icons/launch-glyph.svg "外部鏈結圖示")。

### 雲端類型
{: #cloud-types}

有三種不同的雲端類型可用：公用、專用和混合式。公用雲端包含一組共用資源，這些資源是為了容許存取公司的資源而佈建的。它是在虛擬伺服器上的多方承租戶環境中進行管理，而且可以從任何位置進行存取。 

專用雲端包含已佈建來容許存取公司資源的資源。它是在專用硬體上進行管理，例如裸機伺服器，可以是在公司的辦公室現場（或辦公室之間）或由雲端提供者管理。可從任何位置存取專用雲端。

混合式雲端包含的資源同時結合了公用和專用雲端各層面。它同時是在公司的辦公室現場（或辦公室之間）以及由雲端提供者管理。您可以從任意位置存取混合式雲端。 

## 規劃基礎架構
{: #planning}

您要在佈建之前規劃基礎架構，以確保其大小適合您的工作負載。{{site.data.keyword.cloud_notm}} 有數個工具及網站，可協助您設計基礎架構及調整基礎架構的大小。 

### 基礎架構的架構

從[基礎架構的架構 ![外部鏈結圖示](../icons/launch-glyph.svg "外部鏈結圖示")](https://www.ibm.com/cloud/garage/architectures/infrastructure){: new_window} 開始，更深入瞭解三種雲端環境類型。 

### {{site.data.keyword.cloud_notm}} Design Decision Tool

[{{site.data.keyword.cloud_notm}} Design Decision Tool ![外部鏈結圖示](../icons/launch-glyph.svg "外部鏈結圖示")](https://github.com/ibm-cloud-architecture/infrastructure-design-decision-tool/){: new_window}，可協助您在設計及建置自訂解決方案時比較替代方案。每個基礎架構元件都會提供說明、考量及警告，以及並列比較。您也可以找到如何使用此工具的範例。

### {{site.data.keyword.cloud_notm}} Stencils

[{{site.data.keyword.cloud_notm}} Stencils ![外部鏈結圖示](../icons/launch-glyph.svg "外部鏈結圖示")](https://github.com/ibm-cloud-architecture/ibm-cloud-stencils){: new_window}，可協助您使用通用的圖表製作工具來建立 {{site.data.keyword.cloud_notm}} 架構的圖表。 

### 裸機伺服器選項

使用 [{{site.data.keyword.cloud_notm}} {{site.data.keyword.baremetal_short}} 搜尋工具 ![外部鏈結圖示](../icons/launch-glyph.svg "外部鏈結圖示")](https://www.ibm.com/cloud-computing/bluemix/bare-metal-search){: new_window}，來調整大小並預估您的裸機伺服器選項，包括已認證支援 SAP HANA 及 SAP NetWeaver 工作負載的伺服器。

### {{site.data.keyword.cloud_notm}} 服務及法規遵循

如同任何架構一樣，當您調整基礎架構的大小時，應該考量可能新增至解決方案的 {{site.data.keyword.cloud_notm}} 資源。如需相關資訊，請參閱 [SaaS applications for business and IT ![外部鏈結圖示](../icons/launch-glyph.svg "外部鏈結圖示")](https://www.ibm.com/cloud/saas)，{: new_window}並搜尋特定服務。您也需要思考在建置架構時必須考量的所有法規。例如，您的工作負載被視為機密或受到規範嗎？如需相關資訊，請參閱 [Compliance ![外部鏈結圖示](../icons/launch-glyph.svg "外部鏈結圖示")](https://www.ibm.com/cloud/compliance){: new_window}。

## 建置基礎架構
{: #build}

規劃和設計基礎架構之後，您就可以開始建置。 

### 運算
{: #compute}

您的伺服器是基礎架構的基礎。您有各種不同的選項（視您的需求而定），也可以在環境需要時混合使用。請參閱下表，以取得運算選項的摘要。

| 選項 |說明| 
|--------|---------------|
| [{{site.data.keyword.baremetal_short}}](/docs/bare-metal/about.html)  |每小時或每月，您專用的單一承租戶伺服器，任何部分都不與其他客戶共用（包括伺服器資源）。|
| [{{site.data.keyword.BluVirtServers_short}}](/docs/vsi/vsi_about.html) |購買時搭配專用核心及記憶體配置的可擴充虛擬伺服器。|
| [{{site.data.keyword.vmwaresolutions_short}}](/docs/services/vmwaresolutions/vmonic/prod_overview.html) |使用可擴充、安全且高效能的基礎架構，以及領先業界的 VMware 混合式虛擬化技術，快速而平順地整合或移轉內部部署的 VMware 工作負載。|
| [{{site.data.keyword.containerlong_notm}}](/docs/containers/cs_why.html) |結合 Docker 容器、Kubernetes 技術、直覺式使用者體驗及內建安全和隔離，在運算主機的叢集裡，自動部署、操作、調整及監視容器化應用程式。|
| [{{site.data.keyword.cfee_full_notm}}](/docs/cloud-foundry/index.html) |隨需應變，將多個隔離的企業級 Cloud Foundry 平台實例化。|
| [{{site.data.keyword.openwhisk_short}}](/docs/openwhisk/index.html) |以 Apache OpenWhisk 為基礎的「函數即服務 (FaaS)」程式設計平台。|
{: caption="表 1. 運算選項" caption-side="top"}
   
### 儲存空間
{: #storage}

{{site.data.keyword.baremetal_short}} 和 {{site.data.keyword.BluVirtServers_short}} 佈建時具有預設儲存空間。{{site.data.keyword.baremetal_short}} 至少具有 1 TB SATA 磁碟空間，而 {{site.data.keyword.BluVirtServers_short}} 最少具有 25 GB SAN 儲存空間。{{site.data.keyword.cloud_notm}} SAP 認證的 {{site.data.keyword.baremetal_short}} 例外。如需這些伺服器可用之預設儲存空間的相關資訊，請參閱 [{{site.data.keyword.cloud_notm}} SAP 認證的基礎架構](/docs/bare-metal/bare-metal-sap-applications.html#ibm-cloud-sap-certified-infrastructure)。

您可以根據需要來購買額外的儲存空間。如需運算選項的摘要，請參閱下表。

| 選項 |說明|
|--------|---------------|
| [{{site.data.keyword.blockstorageshort}}](/docs//infrastructure/BlockStorage/index.html) |獨立於運算實例之外所佈建及管理的持續性、高效能 iSCSI 儲存空間。以 iSCSI 為基礎的 Block Storage LUN 會透過備援多路徑 I/O (MPIO) 連線連接至已授權的裝置。|
| [{{site.data.keyword.filestorage_short}}](/docs/infrastructure/FileStorage/index.html) |持續性、快速、靈活且透過網路連接的 NFS 型 File Storage。在這個網路連接儲存空間 (NAS) 環境中，您可以完全控制檔案共用功能及效能。File Storage 共用透過遞送的 TCP/IP 連線，最多可連接至 64 部授權裝置，而達到備援性。|
| [{{site.data.keyword.cos_full_notm}}](/docs/services/cloud-object-storage/about-cos.html) |透過 IBM Cloud Object Storage 儲存的資訊會加密並分散在多個地理位置，並且使用 REST API 透過 HTTP 進行存取。本服務使用 IBM Cloud Object Storage System（舊稱 Cleversafe）所提供的分散式儲存技術。|
| [{{site.data.keyword.cloud_notm}} Mass Data Migration](/docs/infrastructure/mass-data-migration/index.html) |將內部部署資料中心的大量資料卸載至 Cloud Object Storage 儲存區。|
| [EVault](/docs/infrastructure/Backup/index.html) |一種自動化代理型備份系統，透過僅適用於虛擬伺服器的 EVault WebCC 瀏覽器型管理公用程式進行管理。在 IBM Cloud 網路上一個以上資料中心內的伺服器之間備份資料。|
{: caption="表 2. 儲存空間選項" caption-side="top"}

### 網路
{: #network}

設定 {{site.data.keyword.cloud_notm}} 帳戶時，您會自動與 {{site.data.keyword.vpn_full}} 連線。依預設，您的伺服器具有公用 IP 位址及專用 IP 位址。如果要讓伺服器成為專用伺服器，您可以在佈建伺服器之後關閉公用介面，或將伺服器訂購為專用伺服器。如需相關資訊，請參閱[開始使用 Virtual Private Networking](/docs/infrastructure/iaas-vpn/getting-started.html)。

如需網路選項的摘要，請參閱下表。

| 選項 |說明| 
|--------|---------------|
| [Content Delivery Network](/docs/infrastructure/CDN/about.html) | 用於各種產業解決方案，包括媒體、娛樂、軟體、遊戲、銀行業及電子商務，以符合您的企業需求。|
|[Domain Name Service](/docs/cli/reference/ibmcloud/cli_dns.html) | 提供集中位置，透過基本 DNS 管理介面來檢視及管理網域，同時也提供您在相同位置管理反向及次要 DNS 的選項（免費）。|
| [廣域 IP 位址](/docs/infrastructure/subnets/about-global-ip.html) |提供彈性，讓您在伺服器之間移轉工作負載，甚至是跨越不同地理位置的資料中心移轉。|
| [負載平衡](/docs/infrastructure/local-load-balancer/about.html) |在資料中心內的多部伺服器之間平均分散處理及通訊，讓單一裝置不會承擔整個負載。|
| [Virtual Router Appliance](/docs/infrastructure/virtual-router-appliance/about.html) |透過全特性的企業路由器，利用防火牆、資料流量整理、以原則為基礎的遞送、VPN 和眾多其他特性，選擇性地遞送專用和公用網路資料流量。|
| [IPSec VPN](/docs/infrastructure/iaas-vpn/set-up-ipsec-vpn.html) |這一套通訊協定的設計，是使用提供網站對網站加密網路的通道模式，來鑑別及加密兩個位置之間的所有 IP 資料流量。|
| {{site.data.keyword.cloud_notm}} Direct Link | 運用 Cloud Exchange 提供者來提供與 {{site.data.keyword.cloud_notm}} 基礎架構位置的連線。|
{: caption="表 3. 網路選項" caption-side="top"}


## 管理基礎架構
{: #managing}

建置基礎架構和環境之後，即可開始進行管理。

| 作業 |說明|
|--------|---------------|
| [監視系統事件](/docs/account/audit_log.html) | 檢視已對基礎架構資源執行的動作。|
| [設定電子郵件喜好設定](/docs/account/email.html) | 設定有關非計劃性事件、維護及公告的 {{site.data.keyword.cloud_notm}} 基礎架構電子郵件通知。|
| [瞭解資料的安全性](/docs/overview/security.html) |{{site.data.keyword.cloud_notm}} 平台具有跨網路及基礎架構的分層安全控制措施。|
|[瞭解如何確保運作零中斷](/docs/overview/zero_downtime.html) | 所有 {{site.data.keyword.cloud_notm}} 資源都是在全球的資料中心位置進行管理。|
{: caption="表 4. 管理作業" caption-side="top"}

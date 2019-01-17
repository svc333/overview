---


copyright:
  years: 2016, 2018
lastupdated: "2018-11-30"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# 何謂 {{site.data.keyword.Bluemix_notm}} 平台？
{: #whatis}

IBM 的雲端平台結合了平台即服務 (PaaS) 與基礎架構即服務 (IaaS)，以提供整合式的體驗。平台會進行調整，並同時支援小型開發團隊和組織，以及大型企業。您在 {{site.data.keyword.cloud}} 上建置的解決方案在全球各地的資料中心進行全面部署，能在您可信任且經過測試和受支援的環境中快速地啟動及可靠地執行。
{: .shortdesc}

{{site.data.keyword.Bluemix_notm}} 平台由多個元件共同運作而組成，能提供一致且可靠的雲端體驗。 

  * 由數百個 {{site.data.keyword.Bluemix_notm}} 供應項目組成的型錄
  * 健全的主控台，作為建立、檢視、管理雲端資源的前端系統
  * Identity and Access Management 元件，可安全地鑑別兩個平台服務的使用者，並在 {{site.data.keyword.Bluemix_notm}} 之間一致地控制資源的存取
  * 用來過濾及識別資源的搜尋和標記機制
  * 帳戶和計費管理系統，其提供定價方案的確切用量，以及安全的信用卡詐騙防護

## 選擇您的管理環境
{: #choose-compute}

使用 {{site.data.keyword.Bluemix_notm}}，您就不需要再為了測試或執行新的應用程式而進行大量的硬體投資。相反地，我們會為您進行所有管理，但只向您收取所使用部分的費用。您的雲端伺服器環境是基礎架構層的基礎。您可以選擇單一選項，或為更複雜的環境選擇選項的組合。 

有各種選項可用於管理應用程式，讓您可根據意願或需求來控制基礎架構。您可以使用下列任何一種方式執行應用程式：

  * 作為無伺服器函數
  * 作為 Cloud Foundry 應用程式
  * 在 Kubernetes 叢集上作為 Docker 容器
  * 作為 VMware
  * 作為虛擬機器
  * 在高效能 {{site.data.keyword.baremetal_short}} 上 

{{site.data.keyword.baremetal_short}} 是單一客戶專用的單一承租戶實體伺服器。您可控制從伺服器主機到 RAM 及儲存裝置的幾乎所有項目。這些伺服器搭配使用的工作負載需要持續一段時間（例如，數個月）的運算能力。 

{{site.data.keyword.BluVirtServers_short}} 可以部署為公用或專用實例。使用公用實例，伺服器的資源會與其他客戶共用，也稱為多方承租戶環境。專用實例是讓實體伺服器的資源供一個客戶專用，該客戶在相同伺服器上可以具有一部以上的虛擬機器。這些伺服器極適合用於執行一段有限時間（例如數週）的工作負載。一些工作負載範例包括：開發及測試、備份及回復，以及災難回復。如需伺服器選項的相關資訊，請參閱 [Bare metal servers vs. virtual servers: Choosing the best option for you ](https://www.ibm.com/blogs/bluemix/2018/06/bare-metal-virtual-servers-works/){: new_window}![外部鏈結圖示](../icons/launch-glyph.svg "外部鏈結圖示")。

請參閱下表，以取得運算選項的摘要。

| 選項 |說明| 
|--------|---------------|
| [{{site.data.keyword.baremetal_short}}](/docs/bare-metal/about.html)  |每小時或每月，您專用的單一承租戶伺服器，任何部分都不與其他客戶共用（包括伺服器資源）。|
| [{{site.data.keyword.BluVirtServers_short}}](/docs/vsi/vsi_about.html) |購買時搭配專用核心及記憶體配置的可擴充虛擬伺服器。|
| [{{site.data.keyword.vmwaresolutions_short}}](/docs/services/vmwaresolutions/vmonic/prod_overview.html) |使用可擴充、安全且高效能的基礎架構，以及領先業界的 VMware 混合式虛擬化技術，快速而平順地整合或移轉內部部署的 VMware 工作負載。|
| [{{site.data.keyword.containerlong_notm}}](/docs/containers/cs_why.html) |結合 Docker 容器、Kubernetes 技術、直覺式使用者體驗及內建安全和隔離，在運算主機的叢集裡，自動部署、操作、調整及監視容器化應用程式。|
| [{{site.data.keyword.cfee_full_notm}}](/docs/cloud-foundry/index.html) |隨需應變，將多個隔離的企業級 Cloud Foundry 平台實例化。|
| [{{site.data.keyword.openwhisk_short}}](/docs/openwhisk/index.html) |以 Apache OpenWhisk 為基礎的「函數即服務 (FaaS)」程式設計平台。|
{: caption="表 1. 運算選項" caption-side="top"}

## 建置應用程式
{: #build-apps}

不論您是想要對[現有程式碼](/docs/apps/tutorials/tutorial_byoc.html)進行革新並帶到雲端中，還是要開發[全新的應用程式](/docs/apps/tutorials/tutorial_starter-kit.html)，您的開發人員都可以利用 {{site.data.keyword.Bluemix_notm}} 中快速成長的可用服務和運行環境架構生態系統。

每種語言都有可用的[程式設計手冊](https://cloud.ibm.com/docs/home/build){: new_window} ![外部鏈結圖示](../icons/launch-glyph.svg "外部鏈結圖示")，用來協助您開始進行。您有許多選項，可以從 {{site.data.keyword.baremetal_short}} 使用 {{site.data.keyword.Bluemix_notm}} 基礎架構管理應用程式，以無伺服器函數的方式來執行。

## 連接服務
{: #connect-services}

型錄中有超過 190 個服務可供選擇，讓您能夠建置自訂的解決方案來符合您的需求。如果符合您的使用案例，您也可以輕鬆地將服務連接至 {{site.data.keyword.Bluemix_notm}} 之外的應用程式。您可以針對要將外部消費者手動連接至 {{site.data.keyword.Bluemix_notm}} 服務的案例，產生一組新的認證。例如，如果您嘗試將 {{site.data.keyword.Bluemix_notm}} 之外的應用程式連接至 Watson 服務，您會產生一個新的認證，用於將它們連接在一起。就是這麼簡單！如需相關資訊，請參閱[新增認證](/docs/resources/service_credentials.html#service_credentials)。

## 設定帳戶

如果您只想試用 {{site.data.keyword.Bluemix_notm}}，可以直接進入型錄並開始查看您想要探索的服務，然後新增至「試用」或「精簡」帳戶。不過，如果您已準備好要為一群開發人員或整個組織開始使用某個環境，並讓應用程式在正式作業中執行，請考慮在您的帳戶中進行基本設定：

* 使用者存取群組，用於將使用者和服務 ID 組織成一個實體，讓指派存取權成為一個簡潔的處理程序。
* 資源群組，用於組織資源，讓指派一組資源的存取權既快速又簡單。
* 用於存取群組或個別開發人員的存取原則，這些人員需要 IAM 存取原則或 Cloud Foundry 組織和空間角色。

如需相關資訊，請參閱[設定帳戶的最佳作法](/docs/account/bp_account.html#account_setup)及[指派存取權的最佳作法](/docs/iam/bp_access.html)。此外，如果您準備好要開始投入，請參閱[帳戶階層](/docs/account/account_overview.html#overview)的部分。

## 定價與計費

不論您的帳戶類型為何，都可以使用提供免費配額的服務精簡方案來探索 {{site.data.keyword.Bluemix_notm}}。當您從型錄中選擇一項服務並選取一個磚之後，如果有不同類型的可用方案，您會看到關於定價資訊的詳細資料。如果您選擇具有付費方案的服務方案，則可以使用成本預估工具來預估成本。如需相關資訊，請參閱[預估成本](/docs/billing-usage/estimating_costs.html#cost)。

{{site.data.keyword.Bluemix_notm}} 計費提供多項服務，用於確保 {{site.data.keyword.Bluemix_notm}} 平台可以安全地管理定價、帳戶、用量等等。

### {{site.data.keyword.Bluemix_notm}} 帳戶管理
{: #account}

帳戶管理負責維護與客戶之間的計費關係。每一個帳戶就是一個代表一位客戶的計費實體。此服務控制了帳戶生命週期、帳戶訂閱、帳戶使用者關係及帳戶組織。

### {{site.data.keyword.Bluemix_notm}} 定價
{: #pricing}

{{site.data.keyword.Bluemix_notm}} 定價平台服務可協助使用者定義、管理及擷取 {{site.data.keyword.Bluemix_notm}} 型錄中資源的價格資訊。

### {{site.data.keyword.Bluemix_notm}} 計量收集器
{: #metering}

{{site.data.keyword.Bluemix_notm}} 用量計量是一項平台服務，可讓服務提供者提交針對 {{site.data.keyword.Bluemix_notm}} 使用者所佈建之資源實例收集的度量值。在 {{site.data.keyword.Bluemix_notm}} 中提供「整合式計費服務」的協力廠商服務提供者，需要每小時提交所有作用中服務實例的用量。提交很重要，因為如果無法報告用量，可能導致 IBM 的收益損失，進而導致協力廠商服務提供者的收益份額損失。

## {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM)
{: #iam}

{{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) 可讓您安全地鑑別平台服務的使用者，並且在 {{site.data.keyword.Bluemix_notm}} 平台之間一致地控制資源的存取。如需更多詳細資料，請參閱[何謂 IAM？](/docs/iam/index.html)。IAM 提供 CLI 指令及 API，可協助您管理記號、存取群組及原則。


## 建立資源
{: #provisioning-layer}

資源控制器是新一代的 {{site.data.keyword.Bluemix_notm}} 平台佈建層，它會管理客戶帳戶中 {{site.data.keyword.Bluemix_notm}} 資源的生命週期。資源會在帳戶範圍內廣域佈建。資源控制器同時支援資源的同步和非同步佈建。佈建層負責控制及追蹤客戶帳戶中資源的生命週期。資源是可以針對應用程式或服務實例佈建或保留的實體或邏輯元件。資源的範例包括資料庫、帳戶、處理器、記憶體及儲存空間限制。一般而言，佈建層所追蹤的資源，預期會讓用量度量值與計費相關聯，但不一定都是這種情況。在某些情況下，資源可能會與佈建層相關聯，以確保可以管理資源生命週期及帳戶生命週期。資源控制器使用 IAM 來鑑別和授權針對佈建層所採取的動作。

### 資源生命週期管理
{: #lifecycle}

資源控制器提供共用 API，來控制從佈建（建立實例）、連結（建立存取認證）、取消連結（移除存取權）到取消佈建（刪除實例）的資源生命週期。

資源控制器提供 API 來協助您管理資源生命週期的下列元素：
* 佈建
* 更新資源實例
* 連結
* 資源金鑰
* 取消連結
* 取消佈建


## 管理資源
{: #resource-manager}


{{site.data.keyword.Bluemix_notm}} 資源管理員會藉由[資源群組](/docs/overview/resource-groups.html#whatis)管理資源集合。資源群組屬於某個帳戶。所有 {{site.data.keyword.Bluemix_notm}} 資源都必須在資源群組內佈建。如果帳戶已暫停，則對應的資源群組也會暫停，且該資源群組內的所有資源都會暫停。當使用者建立帳戶時，會在帳戶中建立一個 default 資源群組。所有已啟用 {{site.data.keyword.Bluemix_notm}} IAM 的資源，都必須在資源群組內佈建。如果帳戶已暫停，則對應的資源群組也會暫停，且該資源群組內的所有資源都會暫停。若為標準帳戶，使用者只能有一個資源群組。若為「隨收隨付制」或「訂閱」帳戶，則容許使用者建立多個資源群組。 


## {{site.data.keyword.Bluemix_notm}} 型錄
{: #catalog}

{{site.data.keyword.Bluemix_notm}} 型錄會儲存 {{site.data.keyword.Bluemix_notm}} 主控台中所顯示資源的供應項目定義（說明、特性、影像、URL 等等）。型錄服務會以記錄系統方式管理多個地理位置的供應項目。型錄支援 CLI 及 RESTful API，您可以在其中擷取現有供應項目的相關資訊，以及建立、管理與刪除它們的供應項目。請從基礎 URL 開始，並使用端點來擷取關於型錄中服務的 meta 資料，以及管理服務可見性。視物件的類型而定，meta 資料可包括定價、佈建、地區等相關資訊。如需相關資訊，請參閱[管理型錄文件](/docs/overview/catalog.html#global-catalog-overview)。

## 搜尋及標記資源
{: #search-and-tag}

搜尋服務是一個廣域及共用資源內容儲存庫，它已整合在 {{site.data.keyword.Bluemix_notm}} 平台內。它用於儲存及搜尋雲端資源的屬性。它會對資源進行分類。資源由 {{site.data.keyword.Bluemix_notm}} 平台內的資源提供者控制和擁有，例如 Cloud Foundry、IBM Containers 或 Resource Controller。資源是由[雲端資源名稱](/docs/overview/crn.html#crn) ID (CRN) 唯一識別。資源的內容包含標籤和系統內容。這兩種內容都定義在 {{site.data.keyword.Bluemix_notm}} 計費帳戶中，並且跨越多個地區。

此服務還管理與資源相關聯的標籤。您可以利用 Tagging API 來建立、刪除、搜尋、連接或分離標籤。標籤是由「雲端資源命名 (CRN)」ID 唯一識別。標籤具有名稱，而此名稱在計費帳戶內必須是唯一的。您可以用 `key:value` 或標籤格式來建立標籤。


---


copyright:
  years: 2016, 2019
lastupdated: "2019-05-13"

keywords: console, platform overview, overview

subcollection: overview

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# 何謂 {{site.data.keyword.Bluemix_notm}} 平台？
{: #whatis-platform}

IBM 的雲端平台結合了平台即服務 (PaaS) 與基礎架構即服務 (IaaS)，以提供整合式的體驗。平台會進行調整，並同時支援小型開發團隊和組織，以及大型企業。您在 {{site.data.keyword.cloud}} 上建置的解決方案在全球各地的資料中心進行全面部署，能在您可信任且經過測試和受支援的環境中快速地啟動及可靠地執行。
{: .shortdesc}

{{site.data.keyword.Bluemix_notm}} 平台由多個元件共同運作而組成，能提供一致且可靠的雲端體驗。 

  * 由數百個 {{site.data.keyword.Bluemix_notm}} 供應項目組成的型錄
  * 健全的主控台，作為建立、檢視、管理雲端資源的前端系統
  * Identity and Access Management 元件，可安全地鑑別兩個平台服務的使用者，並在 {{site.data.keyword.Bluemix_notm}} 之間一致地控制資源的存取
  * 用來過濾及識別資源的搜尋和標記機制
  * 帳戶和計費管理系統，其提供定價方案的確切用量，以及安全的信用卡詐騙防護

不論您是想要對[現有程式碼](/docs/apps/tutorials?topic=creating-apps-tutorial-byoc#tutorial-byoc)進行革新並帶到雲端中，還是要開發[全新的應用程式](/docs/apps/tutorials?topic=creating-apps-tutorial-starterkit)，您的開發人員都可以利用 {{site.data.keyword.Bluemix_notm}} 中快速成長的可用服務和運行環境架構生態系統。

## 設定帳戶
{: #set-up-account}

如果您只想試用 {{site.data.keyword.Bluemix_notm}}，可以直接進入型錄並開始查看您想要探索的供應項目，然後新增至「精簡」帳戶。不過，如果您已準備好要為一群開發人員或整個組織開始使用某個環境，並讓應用程式在正式作業中執行，請考慮在您的帳戶中進行基本設定：

* 使用者存取群組，用於將使用者和服務 ID 組織成一個實體，讓指派存取權成為一個簡潔的處理程序。
* 資源群組，用於組織資源，讓指派一組資源的存取權既快速又簡單。
* 用於存取群組或個別開發人員的存取原則，這些人員需要 IAM 存取原則或 Cloud Foundry 組織和空間角色。

如需相關資訊，請參閱[設定帳戶的最佳作法](/docs/account?topic=account-account_setup)及[指派存取權的最佳作法](/docs/iam?topic=iam-account_setup)。 

## 定價與計費
{: #pricing-billing}

不論您的帳戶類型為何，都可以使用提供免費配額的服務精簡方案來探索 {{site.data.keyword.Bluemix_notm}}。當您從型錄中選擇一項服務並選取一個磚之後，如果有不同類型的可用方案，您會看到關於定價資訊的詳細資料。如果您選擇具有付費方案的服務方案，則可以使用成本預估工具來預估成本。如需相關資訊，請參閱[預估成本](/docs/billing-usage?topic=billing-usage-cost)。

{{site.data.keyword.Bluemix_notm}} 計費提供多項服務，用於確保 {{site.data.keyword.Bluemix_notm}} 平台可以安全地管理定價、帳戶、用量等等。

###  帳戶管理 
{: #account-mgmt}

帳戶管理負責維護與客戶之間的計費關係。每一個帳戶就是一個代表一位客戶的計費實體。此服務控制了帳戶生命週期、訂閱、使用者關係及組織。

### 定價
{: #pricing}

定價平台服務可協助您定義、管理及擷取 {{site.data.keyword.Bluemix_notm}} 型錄中資源的定價資訊。

### 用量計量
{: #metering}

透過用量計量，服務提供者可提交針對 {{site.data.keyword.Bluemix_notm}} 使用者所佈建之資源實例收集的度量值。提供「整合式計費服務」的協力廠商服務提供者，需要每小時提交所有作用中服務實例的用量。 

### 用量報告
{: #usage}

用量報告會傳回指定月份的帳戶摘要。帳戶帳單管理員獲授權存取此報告。

## {{site.data.keyword.Bluemix_notm}} 型錄
{: #catalog}

{{site.data.keyword.Bluemix_notm}} 型錄會儲存 {{site.data.keyword.Bluemix_notm}} 主控台中所提供資源的供應項目定義（說明、特性、影像、URL 等等）。供應項目會以記錄系統的方式在多個地理位置上進行管理。型錄支援指令行介面 (CLI) 及 RESTful API，使用者可以在其中擷取現有供應項目的相關資訊，以及建立、管理與刪除它們的資源。如需相關資訊，請參閱[管理型錄](/docs/overview?topic=overview-manage-catalog)。

## 建立資源
{: #provisioning-layer}

資源控制器是新一代的 {{site.data.keyword.Bluemix_notm}} 平台佈建層，它會管理您帳戶中 {{site.data.keyword.Bluemix_notm}} 資源的生命週期。資源會在帳戶範圍內廣域佈建。資源控制器同時支援資源的同步和非同步佈建。資源的範例包括資料庫、帳戶、處理器、記憶體及儲存空間限制。 

一般而言，佈建層所追蹤的資源，預期會讓用量度量值與計費相關聯，但不一定都是這種情況。在某些情況下，資源可能會與佈建層相關聯，以確保可以管理資源生命週期及帳戶生命週期。資源控制器使用 {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) 來鑑別及授權針對佈建層所採取的動作。

### 資源生命週期管理
{: #lifecycle}

資源控制器提供共用 API，來控制從建立實例、建立存取認證、移除存取權到刪除實例的資源生命週期。

## 管理資源
{: #resource-manager}

資源集合是透過[資源群組](/docs/overview?topic=overview-whatis-rgs)進行管理。資源群組與您的帳戶相關聯。所有 {{site.data.keyword.Bluemix_notm}} 資源都必須指派給資源群組。當您建立帳戶時，便會為您建立一個預設的資源群組。所有已啟用 {{site.data.keyword.Bluemix_notm}} IAM 的資源，都必須在資源群組內佈建。如果您具有「精簡」帳戶，您只能有一個資源組織。如果您具有「隨收隨付制」或「訂閱」帳戶，則可以建立多個資源群組。如果帳戶已暫停，則對應的資源群組也會暫停，且該資源群組內的所有資源都會暫停。 

## 搜尋及標記資源
{: #search-and-tag}

搜尋服務是一個廣域及共用資源內容儲存庫，它已整合在 {{site.data.keyword.Bluemix_notm}} 平台內。它用於儲存及搜尋雲端資源的屬性，並且會對資源進行分類。資源是由[雲端資源名稱 (CRN)](/docs/overview?topic=overview-crn) ID 唯一識別。資源的內容包含標籤和系統內容。這兩種內容都定義在 {{site.data.keyword.Bluemix_notm}} 計費帳戶中，並且跨越多個地區。

此服務還管理與資源相關聯的標籤。您可以利用 Tagging API 來建立、刪除、搜尋、連接或分離標籤。標籤是由 CRN ID 唯一識別。標籤具有名稱，而此名稱在計費帳戶內必須是唯一的。您可以用 key:value 配對或標籤格式來建立標籤。

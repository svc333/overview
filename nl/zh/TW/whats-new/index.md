---

copyright:

  years: 2015, 2019

lastupdated: "2019-06-06"

keywords: release notes, what's new, what is new, cloud updates

subcollection: overview

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:tip: .tip}

# {{site.data.keyword.Bluemix_notm}} 的新增功能
{: #whatsnew}

隨時保持 {{site.data.keyword.Bluemix}} 平台上所提供之新增特性的最新資訊，讓您可以充分獲得 {{site.data.keyword.Bluemix_notm}} 體驗。
{:shortdesc}

如果您在尋找 {{site.data.keyword.Bluemix_notm}} 上可用服務的更新，請參閱部落格上的 [{{site.data.keyword.Bluemix_notm}} 公告頁面](https://www.ibm.com/cloud/blog/announcements){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")。
{: tip}



## {{site.data.keyword.Bluemix_notm}} 平台
{: #platform_category}


### 匯出具有相關聯標籤的用量資料
文件日期：2019 年 4 月 4 日 

您現在可以利用最新的標記功能，在匯出的用量報告中管理資源、用量及成本。當您新增標籤至資源時，可以選擇檢視與資源相關聯的標籤。移至**管理**> **計費及用量**> **用量**> **匯出 CSV**> **實例**以下載用量報告。如需匯出標籤的相關資訊，請參閱[匯出用量資料內的標籤以協助成本配置](https://www.ibm.com/cloud/blog/export-your-tagged-usage-data-within-the-enhanced-ibm-cloud){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示") 部落格文章。

### 用來啟用對資源之公用存取權的存取群組
文件日期：2019 年 3 月 25 日

現在您可以使用您帳戶中為您提供的新存取群組，啟用對 {{site.data.keyword.cos_full}} 儲存區中物件的公用存取權。這個新的存取群組稱為 `Public access` 群組，依預設，所有使用者和服務 ID 都會新增至其中。您可以更新存取群組的原則，讓所有使用者（甚至是未經鑑別的使用者）能夠存取您在原則中指定的資源。[進一步瞭解公用存取群組](/docs/iam?topic=iam-public#public)。

### 具有聯合 ID 之使用者的多因子鑑別
文件日期：2019 年 3 月 12 日
{: #mfa-federated}

帳戶擁有者或被指派計費帳戶管理服務管理者角色的使用者，可以為帳戶中的所有使用者啟用多因子鑑別 (MFA)。使用公司或企業單一登入 ID 的聯合使用者，現在可以被要求使用 MFA 進行鑑別，以便登入 {{site.data.keyword.Bluemix_notm}}。如需此特性加強功能的相關資訊，以及啟用帳戶之 MFA 的必要資訊，請參閱 [Introducing MFA for IBM Cloud Users with Federated ID](https://www.ibm.com/cloud/blog/introducing-mfa-for-ibm-cloud-users-with-federated-id){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")。

### 新的 appdomain.cloud 主機名稱選項
文件日期：2018 年 12 月 31 日
{: #appdomain}

cloud.ibm.com 上提供新的主機名稱選項 `*.appdomain.cloud`。

先前，`mybluemix.net` 網域用於管理各種部署目標中的應用程式，例如 {{site.data.keyword.containerlong_notm}} 或 Cloud Foundry。您已在 `mybluemix.net` 上管理的任何應用程式都不會受到影響。

Cloud Foundry 應用程式的子網域為 `cf.appdomain.cloud`。您部署至 {{site.data.keyword.containerlong_notm}} 之應用程式的子網域為 `containers.appdomain.cloud`。

### 新的 Cloud Foundry API 端點
文件日期：2018 年 11 月 30 日
{: #cf-api-endpoints}

為了可與舊版相容，仍可使用 `api.*.bluemix.net` Cloud Foundry API 端點。不過，您可以更新 Script 及基礎架構自動化，以針對您的地區使用下列新的 Cloud Foundry API 端點：

* api.us-south.cf.cloud.ibm.com（舊稱為 api.ng.bluemix.net）
* api.eu-gb.cf.cloud.ibm.com（舊稱為 api.eu-gb.bluemix.net）
* api.us-east.cf.cloud.ibm.com（舊稱為 api.us-east.bluemix.net）
* api.eu-de.cf.cloud.ibm.com（舊稱為 api.eu-de.bluemix.net）
* api.au-syd.cf.cloud.ibm.com（舊稱為 api.au-syd.bluemix.net）

### {{site.data.keyword.Bluemix_notm}} 的新支援體驗
文件日期：2018 年 11 月 30 日
{: #support}

透過「支援中心」，您可以解決所有 {{site.data.keyword.Bluemix_notm}} 相關問題。登入頁面提供常見問題 (FAQ)，讓您在不需要聯絡 {{site.data.keyword.Bluemix_notm}} 的情況下即可找到問題的答案。您也可以與即時支援代表人員進行會談。現在，可以從單一位置管理您的案例。請移至**支援** &gt; **管理案例**，來建立、檢視或編輯案例。

您也可以從「支援中心」找到[狀態頁面](https://cloud.ibm.com/status){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")。它已加強，包括了所有非計劃性突發事件、計劃性維護、公告以及關於會影響到 {{site.data.keyword.Bluemix_notm}} 平台、基礎架構及主要服務之重大事件的安全公告通知。從「支援中心」按一下**檢視雲端狀態**。若要參閱新的體驗，請登入並移至[支援中心](https://cloud.ibm.com/unifiedsupport/supportcenter){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")。 

### {{site.data.keyword.Bluemix_notm}} 中的統一登入、API 金鑰和使用者及存取管理
文件日期：2018 年 11 月 30 日
{: #useraccess}

透過最新的更新項目，不論您的 ID 類型是什麼，您都可以充分運用適用於所有使用者的簡化安全登入。無論您具有 IBM ID 還是 SoftLayer ID，都可以從我們的加強登入頁面快速登入 {{site.data.keyword.Bluemix_notm}} 主控台。您也可以透過 {{site.data.keyword.Bluemix_notm}} 進行安全 API 呼叫，並使用 IAM API 金鑰或 IAM 存取記號來自動執行 CLI 登入。 

登入之後，您可以從 Access (IAM) 使用者介面的「使用者」頁面中看到包括平台及標準基礎架構使用者在內的所有使用者。視您在帳戶中檢視其他使用者的存取權而定，您可以依帳戶使用者、標準基礎架構使用者或 Cloud Foundry 組織快速過濾視圖。您也可以使用過濾器，依名稱、電子郵件或狀態來快速尋找使用者。

既然，您的所有使用者都在單一主控台中，您就可以從相同位置管理所有類型資源的存取權。存取是從使用者開始，因此請從清單選取一位使用者即可開始。然後，視您要指派存取權的資源類型而定，您可以從 IAM 存取原則、Cloud Foundry 存取或標準基礎架構許可權中進行選擇。如果您只想要指派 IAM 存取原則，請試著建立存取群組來簡化存取管理程序，方法是將所有使用者新增至需要指派相同原則的相同存取群組中。

如需詳細資料，請參閱 [Outstanding User Access Improvements Help Deliver a Unified {{site.data.keyword.Bluemix_notm}} Platform](https://www.ibm.com/cloud/blog/announcements/ibm-cloud-access-management){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")。 

### 在同一位置尋找所有 {{site.data.keyword.Bluemix_notm}} CLI 外掛程式文件
文件日期：2018 年 11 月 30 日
{: #cli}

您現在可以存取一個位置中的所有 {{site.data.keyword.Bluemix_notm}} CLI 外掛程式文件，讓您輕鬆地找到您想在 {{site.data.keyword.Bluemix_notm}} 平台上尋找的任何 CLI 指令。請參閱 [CLI 文件](/docs/cli?topic=cloud-cli-ibmcloud-cli)的「參考資料」一節。

### 參閱新儀表板和資源清單
文件日期：2018 年 11 月 30 日
{: #dash}

透過最新的更新項目，您現在可以從一個位置檢視所有平台和基礎架構服務。當您登入時，您可以立即查看新的儀表板。在資源從型錄新增至帳戶之後，您就可以使用資源清單來取得帳戶資源的完整視圖：

* 儀表板已重新設計，因此您可以檢視資源、維護、狀態、應用程式、支援、用量及使用者的摘要。
* 您可以在資源清單中找到資源的相關詳細資料。您可以標記資源以組織資源，或選取資源以在詳細資料頁面上進行變更。
* 現在，您可以在同一位置看到所有資源，我們已新增廣域搜尋，讓您可以快速尋找所建立的資源，並預期它們會出現在「資源」清單頁面上。 
* 您也可以搜尋型錄結果，以快速尋找要新增至帳戶的資源。  

如需詳細資料，請參閱 [Manage All Your Cloud Resources on the Enhanced {{site.data.keyword.Bluemix_notm}} Platform](https://www.ibm.com/blogs/bluemix/2018/11/manage-all-your-cloud-resources-on-the-enhanced-ibm-cloud-platform/){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")。

### 平台與基礎架構服務的統一帳戶、計費和使用者設定檔資訊
文件日期：2018 年 11 月 30 日
{: #profile}

現在已簡化您的帳戶、計費和設定檔資訊。您可以在統一的主控台中，檢視所有平台及基礎架構資源的帳戶資訊。 

* 設定檔及設定區域包含您的相關資訊，以及所有資源類型的電子郵件通知喜好設定。 
* 您的帳戶資訊區域包含您的公司或組織、帳戶設定以及使用資源群組和 Cloud Foundry 組織之快速存取的相關資訊。您甚至可以找到最佳作法來協助您快速開始進行！
* 您帳戶的計費及用量區域可協助您瞭解帳單、進行付款、監視訂閱、取得報價、追蹤訂單，以及設定消費通知。

如需詳細資料，請參閱 [Bringing It All Together: A Single Account and Billing Management Experience](https://www.ibm.com/cloud/blog/announcements/ibm-cloud-account-management){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")。

### 使用標籤組織資源
文件日期：2018 年 11 月 30 日
{: #tag}

現在有標籤可讓您新增至資源，例如 Cloud Object Storage，以協助您管理資源及尋找與您最相關的資源。例如，如果您有數百個資源，您想要區分一些以相同方式付款的資源，您可以使用 `costcenter:location01` 來標記它們。或者，如果您的團隊反覆處理一些資源，您可以使用類似 `team-blue` 的標籤。您也可以依標籤來過濾資源清單，以快速組織及尋找您需要的資源。如需相關資訊，請參閱[使用標籤](/docs/resources?topic=resources-tag)及 [Platform Tagging on the Enhanced {{site.data.keyword.Bluemix_notm}} Platform](https://www.ibm.com/cloud/blog/announcements/platform-tagging-on-the-enhanced-ibm-cloud-platform){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")。 

### 使用成本預估器尋找正確的每月成本
文件日期：2018 年 11 月 30 日
{: #cost-estimator}

為協助您決定及分析想要購買的服務，您可以使用成本預估器。現在，您可以瀏覽主控台，選取您要擁有的每一項服務，然後使用一個簡單的工具新增所有成本。您甚至可以輸入預測的資料用量、每秒查閱數、每秒寫入數，以及每秒查詢數，以得到更精確的每月支出預估。您可以使用成本預估器與您選取的每一個型錄服務，或者按一下主控台功能表中的「成本預估器」圖示 ![「預估器」圖示](../../icons/Estimator.svg)，以取得預估成本的摘要。如需相關資訊，請參閱[預估成本](/docs/billing-usage?topic=billing-usage-cost)。

### 已更新 {{site.data.keyword.cloud_notm}} 的全球位置名稱
文件日期：2018 年 11 月 1 日
{: #location-name-updates}

隨著 {{site.data.keyword.cloud_notm}} 持續擴展廣域可用性覆蓋範圍，我們更新了位置命名結構，以更適當地支援世界各地的地理位置、地區及資料中心之可理解的一致性階層。如果您熟悉我們目前的全球地區，您將會認出像美國南部和雪梨這類名稱。我們會使這些位置名稱與資料中心實際所在的城市名稱一致。

目前，程式化 ID 不變，因此從 API 角度來看沒有任何影響。下表顯示新舊位置名稱。如需相關資訊及資料中心和地區的完整清單，請參閱[服務可用性](/docs/resources?topic=resources-services_region)。

|先前的位置顯示名稱 |新的位置顯示名稱 | 代碼 |
|----------|---------|---------|
|美國南部 | 達拉斯 | us-south | 
|美國東部 | 華盛頓特區 | us-east |
|英國 | 倫敦 | eu-gb |
|德國 | 法蘭克福 | eu-de |
|雪梨 |雪梨 | au-syd |
|亞太地區北部 | 東京 | jp-tok |
{: caption="表 1. 新的位置名稱" caption-side="top"}

### 將帳戶管理存取權指派給其他人
文件日期：2018 年 10 月 30 日
{: #acct-mgmt-services}

使用 {{site.data.keyword.cloud_notm}} Identity and Access Management (IAM)，您可以將以帳戶管理者身分完成的一般作業委派給帳戶中的另一位使用者。藉由在一個或所有可用帳戶管理服務上建立存取原則，您可以輕鬆地委派責任，例如，邀請及移除使用者、管理存取群組、管理服務 ID、維護專用型錄服務，甚至是監視計費及追蹤用量。您可以使用以下四個個別的帳戶管理服務及所有服務選項，來設定存取原則：

* 使用者管理：用於邀請及移除使用者
* IAM 存取群組：用於建立、編輯、刪除、更新及指派存取權 
* IAM 身分服務：用於檢視、建立、刪除及指派帳戶中服務 ID 與相關聯 API 金鑰的存取權
* 廣域資源型錄：用於檢視專用型錄供應項目，以及更新供應項目的 meta 資料和可見性
* 所有帳戶管理服務：用於根據指派的角色存取每一個個別的帳戶管理服務選項，以及存取計費和用量追蹤。

如需使用者可以根據其具有原則的帳戶管理服務以及其獲指派的角色而執行之作業的相關資訊，請參閱[帳戶管理服務的平台管理角色及動作範例](/docs/iam?topic=iam-userroles#platformrolestable2)。如需此新特性的相關資訊，請參閱 [Introducing More Flexibility and Control for IBM Cloud Account Management Services Access](https://www.ibm.com/cloud/blog/announcements/introducing-more-flexibility-and-control-for-ibm-cloud-account-management-services-access){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示") 部落格文章。 

### 搜尋資源
文件日期：2018 年 7 月 17 日
{: #forward-slash-key}

您可以從 {{site.data.keyword.cloud_notm}} 主控台任意處搜尋資源。在主控台功能表列的搜尋欄位中，鍵入資源的名稱。按下正斜線鍵 (/) 以啟動搜尋。

### 將聯合使用者動態地新增至存取群組
文件日期：2018 年 7 月 12 日
{: #add-fed-users}

您可以建立動態規則，以根據特定的身分屬性，自動將聯合使用者新增至存取群組。當您的使用者使用聯合 ID 登入時，來自身分提供者的資料會根據您設定的規則，動態地將使用者對映到存取群組。如需相關資訊，請參閱[建立存取群組的動態規則](/docs/iam?topic=iam-rules)。

### 保護您的服務 ID 及 API 金鑰
文件日期：2018 年 6 月 1 日
{: #protect-svcid-apikey}

若要避免刪除服務 ID 或 API 金鑰導致中斷或毀壞的狀況，您可以使用 CLI 或使用者介面來鎖定服務 ID 及 API 金鑰。鎖定服務 ID 也可以防止變更、刪除或指派任何存取原則，以及防止建立或刪除與服務 ID 相關聯的任何 API 金鑰。如需相關資訊，請參閱[鎖定服務 ID](/docs/iam?topic=iam-serviceidapikeys#lockkey) 及[鎖定 API 金鑰](/docs/iam?topic=iam-userapikey)。

### 將您的「精簡」帳戶升級至「訂閱」帳戶
文件日期：2018 年 5 月 31 日
{: #upgrade-lite}

您現在可以直接從 {{site.data.keyword.Bluemix_notm}} 主控台將「精簡」帳戶升級至「訂閱」帳戶。搭配「訂閱」帳戶，您可以同時使用平台及基礎架構供應項目，並做出每月消費及期限承諾來善用折扣定價。以每月付款排程固定計費也可以避免意外驚訝，但仍具有根據所需增減訂購的彈性。如需相關資訊，請參閱[訂閱帳戶常見問題](/docs/billing-usage?topic=billing-usage-billusagefaqs#subs-order)。 

### {{site.data.keyword.Bluemix_notm}} CLI 品牌再造
文件日期：2018 年 5 月 15 日
{: #cli-rebrand}

{{site.data.keyword.Bluemix_notm}} CLI 指令已從 **`bluemix`** 和 **`bx`** 變更為 **`ibmcloud`**。不過，您仍然可以使用 **`bluemix`** 和 **`bx`** CLI 指令，直到未來移除它們為止。目前沒有簡稱，只有完整名稱 **`ibmcloud`**。 

### {{site.data.keyword.Bluemix_notm}} 帳戶的多因子鑑別
文件日期：2018 年 5 月 2 日
{: #account-mfa}

多因子鑑別 (MFA) 會要求所有使用者在登入期間，除了標準 IBM ID 和密碼，還需要提供以時間為基礎的一次性密碼，為您的帳戶新增額外的安全層。這通常也稱為雙因子鑑別 (2FA)。MFA 是根據帳戶而啟用，在開啟之後，帳戶中的所有使用者都需要使用額外的安全措施來登入。如需相關資訊，請參閱 [IBM Cloud Platform now adds support for Multi-Factor Authentication](https://www.ibm.com/cloud/blog/ibm-cloud-platform-now-adds-support-multi-factor-authentication){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示") 部落格文章。

### 使用存取群組來快速指派存取權
文件日期：2018 年 4 月 3 日
{: #access-groups}

您想要儘可能使用最少數目的原則來快速指派存取權嗎？現在，您可以使用存取群組來做到這點。存取群組可讓您將一組使用者和服務 ID 分組在一起，並指派適用於群組所有成員的單一原則。透過使用存取群組，您可以限制花在管理帳戶中使用者和服務 ID 存取權的時間。如需詳細資料，請參閱部落格文章 [New feature: Access groups](https://www.ibm.com/cloud/blog/access-groups){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")。

### 現已推出 {{site.data.keyword.Bluemix_notm}} Foundry 服務美國東部地區
文件日期：2017 年 12 月 15 日
{: #cf-useast}

華盛頓特區現已推出新的美國東部資料中心。使用 `us-east.cloud.ibm.com` 端點可以到達這個新地區。如需這個新地區中可購買之服務的詳細資料，請參閱[各地區的服務](/docs/resources?topic=resources-services_region)。

### 歐盟資源的支援
文件日期：2017 年 12 月 14 日
{: #eu-resources}

如果您的服務及資料中心位在歐洲，則 {{site.data.keyword.Bluemix_notm}} 現在提供額外的功能來保護歐盟中的資料。您可以要求位在歐洲的客戶成功團隊提供支援。我們將 24 小時全年無休地提供這項支援。如需相關資訊，請參閱[啟用歐盟支援選項](/docs/account?topic=account-eu-hipaa-supported#bill_eusupported)及[要求歐盟資源的支援](/docs/get-support?topic=get-support-getting-customer-support#eusupported)。

### 撤銷 TLS 1.0 及 1.1 支援
文件日期：2017 年 11 月 28 日
{: #nosupport-tls}

在 2018 年 3 月 1 日，{{site.data.keyword.Bluemix_notm}} 將撤銷許多雲端產品及服務的 TLS 1.0 及 TLS 1.1 支援，這是我們對於提供徹底安全且符合業界在安全及資料隱私最佳作法之雲端的承諾的一部分。 

### 組織帳戶內資源的新方式
文件日期：2017 年 11 月 16 日
{: #usergs}

資源群組是一種新方式，可讓您建立可自訂的帳戶資源分組，對於其內群組及資源的存取是使用 Identity and Access Management (IAM) 進行管理。每個人都從 default 資源群組開始進行。您可以重新命名此資源群組，並在其中新增從型錄建立的服務實例。

對於具有「隨收隨付制」或「訂閱」帳戶的使用者，您可以建立其他資源群組，以更輕鬆地管理配額以及檢視一組資源的計費用量。您也可以將資源分組，以便更輕鬆地同時將對多個服務的存取權指派給使用者。若要進一步瞭解如何使用您帳戶的資源群組，請參閱[管理資源群組](/docs/resources?topic=resources-rgs)。

### {{site.data.keyword.Bluemix_notm}} IAM 的更新
文件日期：2017 年 11 月 16 日
{: #iam-nov17}

在 {{site.data.keyword.Bluemix_notm}} 帳戶內引進資源群組開闢了指派存取權的新方式。使用者及服務 ID 可以獲指派資源群組內所有服務的存取權，讓您可以同時快速地指派多個資源的存取權。您也可以僅指派對資源群組裡部分服務的存取權來自訂每一個使用者或服務 ID 的存取權，或是選擇指派對個別資源的存取權，直到服務實例層次。如需您可以使用 IAM 充分運用之特性的相關資訊，請參閱 [IAM 所提供的特性為何？](/docs/iam?topic=iam-iamoverview#features)

### 自訂儀表板視圖
文件日期：2017 年 11 月 16 日
{: #custom-dash}

您可以從 {{site.data.keyword.Bluemix_notm}} 主控台的儀表板中，檢視及管理帳戶中的所有資源。現在，您可以設定過濾器來自訂視圖。例如，您可以根據資源群組進行過濾，以檢視資源群組中的特定資源。您也可以根據地區或 Cloud Foundry 空間進行過濾。如需詳細資料，請參閱[在儀表板上管理資源](/docs/overview?topic=overview-ui#dashboardview)。

### 支援中心
文件日期：2017 年 11 月 2 日
{: #support-nov17}

我們現在有新的「支援中心」，您可以在其中搜尋資訊、將問題張貼至開發人員社群，以及管理問題單。請移至 {{site.data.keyword.Bluemix_notm}} 主控台功能表列中的**支援 > 支援中心**。

### IBM Cloud 簡介
文件日期：2017 年 10 月 31 日
{: #meet-ibmcloud}

Bluemix 現在是 IBM Cloud。除了推出新名稱之外，未變更任何項目。您仍然可以如常輕鬆地建置及執行應用程式及服務。如需詳細資料，請參閱 [IBM Cloud 部落格](https://www.ibm.com/cloud/blog/announcements/bluemix-is-now-ibm-cloud){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")。

### 精簡帳戶
文件日期：2017 年 10 月 31 日
{: #new-liteacct}

「精簡」帳戶是新的帳戶類型，可讓您免費試用精選服務，沒有時間限制。這個新的帳戶也包括用量追蹤及效率特性，以協助您更恰當地管理資源。若要進一步瞭解可用項目，請參閱[帳戶類型](/docs/account?topic=account-accounts#liteaccount)。

### Identity and Access Management 應用程式鑑別特性
文件日期：2017 年 10 月 6 日
{: #app-authfeature}

Identity and Access Management (IAM) 現在可讓您建立「服務 ID」，您可以將它視為用於應用程式以向 {{site.data.keyword.Bluemix_notm}} 服務進行鑑別的身分。可以透過指派給「服務 ID」的服務原則形式使用關聯 API 金鑰及存取許可權來建立「服務 ID」，以讓您控制使用該 ID 進行鑑別之任何應用程式的存取層次，而不是使用個別使用者認證。

如需此特性優點以及如何開始使用的相關資訊，請參閱 [IBM Cloud IAM 服務 ID 及 API 金鑰簡介](https://www.ibm.com/cloud/blog/introducing-ibm-cloud-iam-service-ids-api-keys){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")。

### {{site.data.keyword.Bluemix_notm}} 全球型錄
文件日期：2017 年 7 月 27 日
{: #gc}

擴充前次主控台更新以從主控台的單一位置管理公用地區，{{site.data.keyword.Bluemix_notm}} 現在具有全球型錄，可讓選取及部署從型錄中所選取項目的處理程序成為更簡化的處理程序。不論您在主控台中選取的地區為何，您現在都可以看到可跨型錄中所有公用地區取得的所有服務。從型錄中選取磚之後，即可看到其中可使用的地區及服務，以及選取您要在其中進行部署的位置。如需最新型錄更新的相關資訊，請參閱[廣域 {{site.data.keyword.Bluemix_notm}} 型錄讓建置更為輕鬆](https://www.ibm.com/cloud/blog/announcements/global-bluemix-catalog-makes-building-things-easier){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")。

### {{site.data.keyword.Bluemix_notm}} 主控台更新
文件日期：2017 年 5 月 23 日
{: #console-may17}

您現在可以透過已更新的 {{site.data.keyword.Bluemix_notm}} 主控台，從單一位置管理公用地區。地區選取器提供資源的簡化存取，而其他加強功能包括更高的可用性及改良的效能。如需相關資訊，請參閱[新廣域 Bluemix 使用者介面的更高可用性及其他功能](https://www.ibm.com/blogs/bluemix/2017/05/new-global-bluemix-ui-higher-availability/){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")。

### Identity and Access Management
文件日期：2017 年 5 月 1 日
{: #iam-may17}

使用最新更新及增進功能，{{site.data.keyword.Bluemix_notm}} 帳戶擁有者或管理者現在可以使用新的統一存取控制使用者介面，以充分運用下列功能：
 * 管理使用者對 Kubernetes 服務其他服務的精細存取，因為他們採用新的存取控制特性
 * 將服務原則及 Cloud Foundry 角色指派給其組織內的使用者

此外，{{site.data.keyword.Bluemix_notm}} 平台使用者可以建立、刪除及列出與其使用者 ID 相關聯的 API 金鑰。而平台使用者可以在使用 API 或 CLI 時使用這些 API 金鑰進行鑑別。

最後，我們已加強統一使用者管理功能，確保在已鏈結的 IaaS-PaaS 帳戶中，透過統一方式管理使用者，而不需要在「SoftLayer 客戶入口網站」或 {{site.data.keyword.Bluemix_notm}} 主控台中分別新增使用者。

如需相關資訊，請參閱 [Introducing Identity & Access Management](https://www.ibm.com/blogs/bluemix/2017/05/introducing-identity-access-management/){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示") 部落格文章。

### {{site.data.keyword.Bluemix_notm}} 文件的導覽設計變更
文件日期：2017 年 4 月 13 日
{: #docnavupdates}

使用此導覽更新，我們認為您將瞭解如何更恰當地分組文件中的內容，而且可以更有效率地尋找相關內容。使用較少巢狀層的內容，您不需要使用 {{site.data.keyword.Bluemix_notm}} 挖掘太深即可找到成功所需的文件。



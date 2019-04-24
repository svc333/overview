---

copyright:

  years: 2015, 2019

lastupdated: "2019-01-22"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# {{site.data.keyword.Bluemix_notm}} 的新增功能
{: #whatsnew}

隨時保持 {{site.data.keyword.Bluemix}} 中所提供之新增特性及服務的最新資訊，讓您可以充分獲得 {{site.data.keyword.Bluemix_notm}} 體驗。更新項目會分組為這些種類：[{{site.data.keyword.Bluemix_notm}} 平台](index.html#platform_category)、[{{site.data.keyword.Bluemix_local_notm}} 和 {{site.data.keyword.Bluemix_dedicated_notm}}](index.html#dedicatedandlocal)、[運算](index.html#compute_category)以及[服務](index.html#services_category)。
{:shortdesc}

## {{site.data.keyword.Bluemix_notm}} 平台
{: #platform_category}


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

如需詳細資料，請參閱 [Outstanding User Access Improvements Help Deliver a Unified {{site.data.keyword.Bluemix_notm}} Platform](https://www.ibm.com/blogs/bluemix/2018/11/ibm-cloud-access-management){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")。 

### 在同一位置尋找所有 {{site.data.keyword.Bluemix_notm}} CLI 外掛程式文件
文件日期：2018 年 11 月 30 日
{: #cli}

您現在可以存取一個位置中的所有 {{site.data.keyword.Bluemix_notm}} CLI 外掛程式文件，讓您輕鬆地找到您想在 {{site.data.keyword.Bluemix_notm}} 平台上尋找的任何 CLI 指令。請參閱 [CLI 文件](/docs/cli/index.html#overview)的「參考資料」一節。

### 參閱新儀表板和資源清單
文件日期：2018 年 11 月 30 日
{: #dash}

透過最新的更新項目，您現在可以從一個位置檢視所有平台和基礎架構服務。當您登入時，您可以立即查看新的儀表板。在資源從型錄新增至帳戶之後，您就可以使用資源清單來取得帳戶資源的完整視圖。:

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

如需詳細資料，請參閱 [Bringing It All Together: A Single Account and Billing Management Experience](https://www.ibm.com/blogs/bluemix/2018/11/ibm-cloud-account-management/){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")。

### 使用標籤組織資源
文件日期：2018 年 11 月 30 日
{: #tag}

現在有標籤可讓您新增至資源，例如 Cloud Object Storage，以協助您管理資源及尋找與您最相關的資源。例如，如果您有數百個資源，您想要區分一些以相同方式付款的資源，您可以使用 `costcenter:location01` 來標記它們。或者，如果您的團隊反覆處理一些資源，您可以使用類似 `team-blue` 的標籤。您也可以依標籤來過濾資源清單，以快速組織及尋找您需要的資源。如需相關資訊，請參閱[使用標籤](/docs/resources/tagging_resources.html#tag)及 [Platform Tagging on the Enhanced {{site.data.keyword.Bluemix_notm}} Platform](https://www.ibm.com/blogs/bluemix/2018/11/platform-tagging-on-the-enhanced-ibm-cloud-platform/){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")。 

### 使用成本預估器尋找正確的每月成本
文件日期：2018 年 11 月 30 日
{: #cost-estimator}

為協助您決定及分析想要購買的服務，您可以使用成本預估器。現在，您可以瀏覽主控台，選取您要擁有的每一項服務，然後使用一個簡單的工具新增所有成本。您甚至可以輸入預測的資料用量、每秒查閱數、每秒寫入數，以及每秒查詢數，以得到更精確的每月支出預估。您可以使用成本預估器與您選取的每一個型錄服務，或者按一下主控台功能表中的「成本預估器」圖示 ![「預估器」圖示](../../icons/Estimator.svg)，以取得預估成本的摘要。如需相關資訊，請參閱[預估成本](/docs/billing-usage/estimating_costs.html#cost)。

### 已更新 {{site.data.keyword.cloud_notm}} 的全球位置名稱
文件日期：2018 年 11 月 1 日

隨著 {{site.data.keyword.cloud_notm}} 持續擴展廣域可用性覆蓋範圍，我們更新了位置命名結構，以更適當地支援世界各地的地理位置、地區及資料中心之可理解的一致性階層。如果您熟悉我們目前的全球地區，您將會認出像美國南部和雪梨這類名稱。我們會使這些位置名稱與資料中心實際所在的城市名稱一致。

目前，程式化 ID 不變，因此從 API 角度來看沒有任何影響。下表顯示新舊位置名稱。如需相關資訊及資料中心和地區的完整清單，請參閱[服務可用性](/docs/resources/services_region.html)。

| 先前的位置顯示名稱 | 新的位置顯示名稱 | 代碼 |
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

使用 {{site.data.keyword.cloud_notm}} Identity and Access Management (IAM)，您可以將以帳戶管理者身分完成的一般作業委派給帳戶中的另一位使用者。藉由在一個或所有可用帳戶管理服務上建立存取原則，您可以輕鬆地委派責任，例如，邀請及移除使用者、管理存取群組、管理服務 ID、維護專用型錄服務，甚至是監視計費及追蹤用量。您可以使用以下四個個別的帳戶管理服務及所有服務選項，來設定存取原則：

* 使用者管理：用於邀請及移除使用者
* IAM 存取群組：用於建立、編輯、刪除、更新及指派存取權 
* IAM 身分服務：用於檢視、建立、刪除及指派帳戶中服務 ID 與相關聯 API 金鑰的存取權
* 廣域資源型錄：用於檢視專用型錄供應項目，以及更新供應項目的 meta 資料和可見性
* 所有帳戶管理服務：用於根據指派的角色存取每一個個別的帳戶管理服務選項，以及存取計費和用量追蹤。


如需使用者可以根據其具有原則的帳戶管理服務以及其獲指派的角色而執行之作業的相關資訊，請參閱[帳戶管理服務的平台管理角色及動作範例](/docs/iam/users_roles.html#platformrolestable2)。如需此新特性的相關資訊，請參閱 [Introducing More Flexibility and Control for IBM Cloud Account Management Services Access](https://www.ibm.com/blogs/bluemix/2018/11/introducing-more-flexibility-and-control-for-ibm-cloud-account-management-services-access/){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示") 部落格文章。 


### 搜尋資源
文件日期：2018 年 7 月 17 日

您可以從 {{site.data.keyword.cloud_notm}} 主控台任意處搜尋資源。在主控台功能表列的搜尋欄位中，鍵入資源的名稱。按下正斜線鍵 (/) 以啟動搜尋。

### 將聯合使用者動態地新增至存取群組
文件日期：2018 年 7 月 12 日

您可以建立動態規則，以根據特定的身分屬性，自動將聯合使用者新增至存取群組。當您的使用者使用聯合 ID 登入時，來自身分提供者的資料會根據您設定的規則，動態地將使用者對映到存取群組。如需相關資訊，請參閱[建立存取群組的動態規則](/docs/iam/accessgroup_rules.html#creating-dynamic-rules-for-access-groups)。

### 保護您的服務 ID 及 API 金鑰
文件日期：2018 年 6 月 1 日

若要避免刪除服務 ID 或 API 金鑰導致中斷或毀壞的狀況，您可以使用 CLI 或使用者介面來鎖定服務 ID 及 API 金鑰。鎖定服務 ID 也可以防止變更、刪除或指派任何存取原則，以及防止建立或刪除與服務 ID 相關聯的任何 API 金鑰。如需相關資訊，請參閱[鎖定服務 ID](/docs/iam/serviceid.html#locking-a-service-id) 及[鎖定 API 金鑰](/docs/iam/userid_keys.html#locking-an-api-key)。

### 將您的「精簡」帳戶升級至「訂閱」帳戶
文件日期：2018 年 5 月 31 日

您現在可以直接從 {{site.data.keyword.Bluemix_notm}} 主控台將「精簡」帳戶升級至「訂閱」帳戶。搭配「訂閱」帳戶，您可以同時使用平台及基礎架構供應項目，並做出每月消費及期限承諾來善用折扣定價。以每月付款排程固定計費也可以避免意外驚訝，但仍具有根據所需增減訂購的彈性。如需相關資訊，請參閱[訂閱帳戶常見問題](/docs/billing-usage/billing-faq.html#subscription-faqs)。 

### {{site.data.keyword.Bluemix_notm}} CLI 品牌再造
文件日期：2018 年 5 月 15 日

{{site.data.keyword.Bluemix_notm}} CLI 指令已從 `bluemix` 和 `bx` 變更為 **ibmcloud**。不過，您仍然可以使用 `bluemix` 和 `bx` CLI 指令，直到未來移除它們為止。目前沒有簡稱，只有完整名稱 **ibmcloud**。 

### {{site.data.keyword.Bluemix_notm}} 帳戶的多因子鑑別
文件日期：2018 年 5 月 2 日

多因子鑑別 (MFA) 會要求所有使用者在登入期間，除了標準 IBM ID 和密碼，還需要提供以時間為基礎的一次性密碼，為您的帳戶新增額外的安全層。這通常也稱為雙因子鑑別 (2FA)。MFA 是根據帳戶而啟用，在開啟之後，帳戶中的所有使用者都需要使用額外的安全措施來登入。

如需相關資訊，請參閱 [IBM Cloud Platform now adds support for Multi-Factor Authentication](https://www.ibm.com/blogs/bluemix/2018/05/ibm-cloud-platform-now-adds-support-multi-factor-authentication/){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示") 部落格文章。

### 使用存取群組來快速指派存取權
文件日期：2018 年 4 月 3 日

您想要儘可能使用最少數目的原則來快速指派存取權嗎？現在，您可以使用存取群組來做到這點。存取群組可讓您將一組使用者和服務 ID 分組在一起，並指派適用於群組所有成員的單一原則。透過使用存取群組，您可以限制花在管理帳戶中使用者和服務 ID 存取權的時間。如需詳細資料，請參閱部落格文章 [New feature: Access groups](https://www.ibm.com/blogs/bluemix/2018/04/access-groups/){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")。

### SoftLayer 和 {{site.data.keyword.Bluemix_notm}} 帳戶鏈結
文件日期：2018 年 3 月 1 日

您可以將 SoftLayer 帳戶鏈結至 {{site.data.keyword.Bluemix_notm}} 帳戶，以便登入單一位置（{{site.data.keyword.Bluemix_notm}} 主控台），然後同時存取基礎架構即服務 (IaaS) 和平台即服務 (PaaS) 資源。如果您剛開始使用 {{site.data.keyword.Bluemix_notm}}，請建立並鏈結帳戶，以取得免費的 {{site.data.keyword.Bluemix_notm}}「精簡」帳戶。或者，如果您已有一個具有 PaaS 資源的 {{site.data.keyword.Bluemix_notm}} 帳戶，請鏈結您的帳戶以便收到 IaaS 和 PaaS 資源的單一帳單。請參閱[鏈結您的 IaaS 和 PaaS 帳戶的步驟](https://www.ibm.com/blogs/bluemix/2018/03/follow-steps-link-iaas-paas-accounts/){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")，以快速鏈結您的帳戶。


### 現已推出 {{site.data.keyword.Bluemix_notm}} Foundry 服務美國東部地區
文件日期：2017 年 12 月 15 日

華盛頓特區現已推出新的美國東部資料中心。使用 `us-east.cloud.ibm.com` 端點可以到達這個新地區。如需這個新地區中可購買之服務的詳細資料，請參閱[各地區的服務](/docs/resources/services_region.html#services_region)。

### 歐盟資源的支援
文件日期：2017 年 12 月 14 日

如果您的服務及資料中心位在歐洲，則 {{site.data.keyword.Bluemix_notm}} 現在提供額外的功能來保護歐盟中的資料。您可以要求位在歐洲的客戶成功團隊提供支援。我們將 24 小時全年無休地提供這項支援。如需相關資訊，請參閱[啟用歐盟支援選項](/docs/billing-usage/eusupported.html#bill_eusupported)及[要求歐盟資源的支援](/docs/get-support/howtogetsupport.html#eusupported)。

### 撤銷 TLS 1.0 及 1.1 支援
文件日期：2017 年 11 月 28 日

在 2018 年 3 月 1 日，{{site.data.keyword.Bluemix_notm}} 將撤銷許多雲端產品及服務的 TLS 1.0 及 TLS 1.1 支援，這是我們對於提供徹底安全且符合業界在安全及資料隱私最佳作法之雲端的承諾的一部分。若要進一步瞭解這項變更對您的影響，以及您可能需要採取的動作，請參閱[撤銷 TLS 1.0 及 1.1 支援](/docs/troubleshoot/appsectls.html)。

### 組織帳戶內資源的新方式
文件日期：2017 年 11 月 16 日

資源群組是一種新方式，可讓您建立可自訂的帳戶資源分組，對於其內群組及資源的存取是使用 Identity and Access Management (IAM) 進行管理。每個人都從 default 資源群組開始進行。您可以重新命名此資源群組，並在其中新增從型錄建立的服務實例。

對於具有「隨收隨付制」或「訂閱」帳戶的使用者，您可以建立其他資源群組，以更輕鬆地管理配額以及檢視一組資源的計費用量。您也可以將資源分組，以便更輕鬆地同時將對多個服務的存取權指派給使用者。若要進一步瞭解如何使用您帳戶的資源群組，請參閱[管理資源群組](/docs/account/resourcegroups.html#rgs)。

### {{site.data.keyword.Bluemix_notm}} IAM 的更新
文件日期：2017 年 11 月 16 日

在 {{site.data.keyword.Bluemix_notm}} 帳戶內引進[資源群組](/docs/overview/resource-groups.html#whatis)開啟了指派存取權的新方式。使用者及服務 ID 可以獲指派資源群組內所有服務的存取權，讓您可以同時快速地指派多個資源的存取權。您也可以僅指派對資源群組裡部分服務的存取權來自訂每一個使用者或服務 ID 的存取權，或是選擇指派對個別資源的存取權，直到服務實例層次。

如需您可以使用 IAM 充分運用之特性的相關資訊，請參閱 [IAM 所提供的特性為何？](/docs/iam/index.html#features)

### 自訂儀表板視圖
文件日期：2017 年 11 月 16 日

您可以從 {{site.data.keyword.Bluemix_notm}} 主控台的儀表板中，檢視及管理帳戶中的所有資源。現在，您可以設定過濾器來自訂視圖。例如，您可以根據資源群組進行過濾，以檢視資源群組中的特定資源。您也可以根據地區或 Cloud Foundry 空間進行過濾。如需詳細資料，請參閱[在儀表板上管理資源](/docs/overview/ui.html#dashboardview)。


### 支援中心
文件日期：2017 年 11 月 2 日

我們現在有新的「支援中心」，您可以在其中搜尋資訊、將問題張貼至開發人員社群，以及管理問題單。請移至 {{site.data.keyword.Bluemix_notm}} 主控台功能表列中的**支援 > 支援中心**。

### IBM Cloud 簡介
文件日期：2017 年 10 月 31 日

Bluemix 現在是 IBM Cloud。除了推出新名稱之外，未變更任何項目。您仍然可以如常輕鬆地建置及執行應用程式及服務。如需詳細資料，請參閱 [IBM Cloud 部落格](https://www.ibm.com/blogs/bluemix/2017/10/bluemix-is-now-ibm-cloud/){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")。

### 精簡帳戶
文件日期：2017 年 10 月 31 日

「精簡」帳戶是新的帳戶類型，可讓您免費試用精選服務，沒有時間限制。這個新的帳戶也包括用量追蹤及效率特性，以協助您更恰當地管理資源。若要進一步瞭解可用項目，請參閱[帳戶類型](/docs/account/index.html#liteaccount)。

### Identity and Access Management 應用程式鑑別特性
文件日期：2017 年 10 月 6 日

Identity and Access Management (IAM) 現在可讓您建立「服務 ID」，您可以將它視為用於應用程式以向 {{site.data.keyword.Bluemix_notm}} 服務進行鑑別的身分。可以透過指派給「服務 ID」的服務原則形式使用關聯 API 金鑰及存取許可權來建立「服務 ID」，以讓您控制使用該 ID 進行鑑別之任何應用程式的存取層次，而不是使用個別使用者認證。

如需此特性優點以及如何開始使用的相關資訊，請參閱 [IBM Cloud IAM 服務 ID 及 API 金鑰簡介](https://www.ibm.com/blogs/bluemix/2017/10/introducing-ibm-cloud-iam-service-ids-api-keys/){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")。

### {{site.data.keyword.Bluemix_notm}} 全球型錄
文件日期：2017 年 7 月 27 日

擴充前次主控台更新以從主控台的單一位置管理公用地區，{{site.data.keyword.Bluemix_notm}} 現在具有全球型錄，可讓選取及部署從型錄中所選取項目的處理程序成為更簡化的處理程序。不論您在主控台中選取的地區為何，您現在都可以看到可跨型錄中所有公用地區取得的所有服務。從型錄中選取磚之後，即可看到其中可使用的地區及服務，以及選取您要在其中進行部署的位置。

如需最新型錄更新的相關資訊，請參閱[廣域 {{site.data.keyword.Bluemix_notm}} 型錄讓建置更為輕鬆](https://www.ibm.com/blogs/bluemix/2017/07/global-bluemix-catalog-makes-building-things-easier/){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")。

### {{site.data.keyword.Bluemix_notm}} 主控台更新
文件日期：2017 年 5 月 23 日

您現在可以透過已更新的 {{site.data.keyword.Bluemix_notm}} 主控台，從單一位置管理公用地區。地區選取器提供資源的簡化存取，而其他加強功能包括更高的可用性及改良的效能。

如需此更新的相關資訊，請參閱[新廣域 Bluemix 使用者介面的更高可用性及其他功能](https://www.ibm.com/blogs/bluemix/2017/05/new-global-bluemix-ui-higher-availability/){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")。

### Identity and Access Management
文件日期：2017 年 5 月 1 日

使用最新更新及增進功能，{{site.data.keyword.Bluemix_notm}} 帳戶擁有者或管理者現在可以使用新的統一存取控制使用者介面，以充分運用下列功能：
 * 管理使用者對 Kubernetes 服務其他服務的精細存取，因為他們採用新的存取控制特性
 * 將服務原則及 Cloud Foundry 角色指派給其組織內的使用者

此外，{{site.data.keyword.Bluemix_notm}} 平台使用者可以建立、刪除及列出與其使用者 ID 相關聯的 API 金鑰。而平台使用者可以在使用 API 或 CLI 時使用這些 API 金鑰進行鑑別。

最後，我們已加強統一使用者管理功能，確保在已鏈結的 IaaS-PaaS 帳戶中，透過統一方式管理使用者，而不需要在「SoftLayer 客戶入口網站」或 {{site.data.keyword.Bluemix_notm}} 主控台中分別新增使用者。

如需最近更新的相關資訊，請參閱 [Introducing Identity & Access Management](https://www.ibm.com/blogs/bluemix/2017/05/introducing-identity-access-management/){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示") 部落格文章。

### {{site.data.keyword.Bluemix_notm}} 文件的導覽設計變更
文件日期：2017 年 4 月 13 日

使用此導覽更新，我們認為您將瞭解如何更恰當地分組文件中的內容，而且可以更有效率地尋找相關內容。使用較少巢狀層的內容，您不需要使用 {{site.data.keyword.Bluemix_notm}} 挖掘太深即可找到成功所需的文件。


## {{site.data.keyword.Bluemix_local_notm}} 及 {{site.data.keyword.Bluemix_dedicated_notm}}
{: #dedicatedandlocal}

### 管理主控台的二月更新
{: #febadminconsole}
文件日期：2018 年 2 月 28 日

使用 2018 年 2 月的最新更新，您可以使用下列新特性：

#### 管理維護更新用的新許可權

引進新的使用者許可權，特別容許使用者核准及重新排定維護更新，以及設定維護更新時間範圍，而這些維護更新時間範圍規定何時將維護更新部署至專用環境。
如需相關資訊，請參閱[視訊示範](https://youtu.be/7c7jyp_JJWU){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")。

### 管理主控台的十二月更新
{: #decemberadminconsole}
文件日期：2017 年 12 月 14 日

使用十二月的最新更新及增進功能，您可以使用下列新增特性：

#### 訂閱平均 CPU 使用率臨界值的通知

平均 CPU 已新增為通知訂閱中的臨界值類型。您現在於 CPU 使用率（所有 DEA 及 Diego Cell 的平均）高於或低於特定臨界值時可以收到通知。

#### 控制歐盟的雲端系統存取

與歐盟的新功能結合以支援雲端資源（從法蘭克福開始），管理主控台現在有能力可定義由 IBM 人員控制存取的原則。您可以管理存取控制原則、檢視存取要求、對要求採取動作，以及追蹤歷程。

#### 安全報告中的加強型資訊

除了使用者及組織的唯一 ID 之外，安全報告現在還包括對使用者友善的名稱。

### 管理主控台的八月更新
{: #augustadminconsole}
文件日期：2017 年 8 月 31 日

使用八月的最新更新及增進功能，您可以使用下列新增特性：

#### {{site.data.keyword.cloudant_short_notm}} 服務用量度量值的更新

  * 已更新 {{site.data.keyword.cloudant_short_notm}} 的用量度量值運算，以反映 {{site.data.keyword.cloudant_short_notm}} 叢集裡所有節點的已使用及可用總 GB 數。一般而言，{{site.data.keyword.cloudant_short_notm}} 叢集包含 3 個節點，而且資料庫中的文件會在叢集的所有節點之間抄寫以提供高可用性及災難回復。使用八月更新，{{site.data.keyword.cloudant_short_notm}} 撥號中的容量度量值（於_資源用量 > 服務_ 視圖中提供）指出叢集的所有節點中的空間。例如，如果單一 {{site.data.keyword.cloudant_short_notm}} 叢集包含 3 個節點，每一個都有 1000 GB 的容量，則容量限制會是 3000 GB。如果已使用該容量的 1500 GB，則 {{site.data.keyword.cloudant_short_notm}} 用量度量值會是 50%。

#### 維護更新排定更新

  * 在 {{site.data.keyword.Bluemix_dedicated_notm}} 中，客戶可以管理其專用環境可用於部署系統更新的日期和時間。客戶可以定義可用性時間範圍，代表維護更新可以及無法部署至其「專用」環境的日期和時間。在八月更新中，_可用更新時間範圍_ 已重新命名為_更新時間範圍_，而且_無法使用更新時間範圍_ 已重新命名為_管制時間範圍_。除了術語變更之外，客戶現在有更多的彈性及限度可以定義管制（無法使用）日期。在要求之後，管制日期即需要 IBM 核准，且獲得核准所需要的時間將有所不同。所要求的管制日期經過核准後，IBM 會取消目前排定在無法進行更新之時間範圍內的任何現有更新。IBM 也會為這些更新建立新的記錄，並將它們排定在已核准的管制日期之外。

如需相關資訊，請參閱[視訊示範](https://bit.ly/2eCQNvu){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")。

### 管理主控台的七月更新
{: #julyadminconsole}
文件日期：2017 年 7 月 31 日

使用七月的最新更新及增進功能，您可以使用下列新增特性：

#### 資源用量歷程功能的更新

  * 在前一個更新（六月）中，記憶體及磁碟用量的「歷程」視圖已引進顯示過去 48 小時、30 天及 5 個月的用量資料。在這個最新的「七月」更新中，已擴充資源用量歷程功能，容許自訂用於顯示資源用量資料的時間跨距。每小時、每日及每月視圖都會保持，但使用者現在可以指定開始日期/時間以及顯示記憶體及磁碟用量度量值的持續時間（例如，顯示從 2017 年 7 月 1 日算起的 15 天的記憶體用量）。
  * 已引進新的 CLI 指令，以在 CLI 中顯示資源度量值歷程。鍵入下列指令，即可找到指令參數以及用量範例：`_cf ba resource-metrics-history -help_`

如需相關資訊，請參閱[視訊示範](https://youtu.be/QBij0jB5qAk){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")。

### 管理主控台的六月更新
{: #juneadminconsole}
文件日期：2017 年 6 月 26 日

使用六月的最新更新及增進功能，您可以使用下列新增特性：

#### 資源用量頁面的更新

  * 系統資源
    * 記憶體及磁碟的「歷程」視圖已更新成顯示過去 48 小時、30 天及 5 個月的資料
    * 提供「進一步瞭解」鏈結，顯示如何使用管理主控台度量值 API 來產生「歷程」視圖
  * 應用程式
    * 提供環境中所有應用程式的用量資訊
    * 依應用程式名稱、實體記憶體、保留記憶體、實體磁碟、保留磁碟、實體 CPU 或組織名稱進行排序
    * 提供搜尋，以依應用程式名稱及組織名稱來過濾結果
    * 提供「進一步瞭解」鏈結，顯示如何使用管理主控台度量值 API 來產生「應用程式」視圖

如需相關資訊，請參閱[資源用量](/docs/hybrid/index.html#resourceusage)。

#### 度量值的 API 的更新

  * 已新增環境統計資料，提供依日或月的記憶體及磁碟耗用量平均值

如需相關資訊，請參閱[度量值的 API](/docs/hybrid/index.html#envappmetricsapi)。


### 管理主控台的五月更新
{: #mayadminconsole}
文件日期：2017 年 5 月 30 日

使用五月的最新更新及增進功能，您可以使用下列新增特性：

 * 「狀態」頁面上的增進功能，包括對影響 {{site.data.keyword.Bluemix_notm}} 平台及運行環境的突發事件進行更精細地診斷。
 * 「安全報告及日誌」頁面的增進功能：
   * 現在會以表格格式顯示報告，以簡化報告的瀏覽及搜尋（包括依報告種類、檔名或建立日期進行排序的能力）。
   * 加強型進行過濾（包括同時過濾多個種類）
   * 顯示報告內容的全螢幕模式
   * 讓具有「報告寫入」許可權的管理使用者可刪除報告
   * 更快速地顯示報告清單，並透過連續捲動漸進式地依需求載入，產生較佳的整體效能。
 * 如果時間範圍跨一週，並從要求時間往回開始最多 3 個月，則可以依需求要求該時間範圍內的安全報告。請注意，需要先有部分環境特定配置，管理使用者才能有此功能。管理使用者將需要此功能的「報告寫入」許可權。

### 管理主控台的四月更新
{: #apriladminconsole}
文件日期：2017 年 5 月 2 日

使用四月的最新更新及增進功能，您可以使用下列新增特性：

 * 針對 {{site.data.keyword.Bluemix_notm}} Dedicated 及 Local 環境最新設計的狀態應用程式。您可以依元件名稱或張貼日期進行快速搜尋。您也可以切換元件狀態張貼視圖與您環境特定的通知。如需相關資訊，請參閱[新 {{site.data.keyword.Bluemix_notm}} 狀態頁面](https://www.ibm.com/blogs/bluemix/2017/05/new-bluemix-status-page/){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示") 部落格文章。
 * 「資源用量」磚中精選服務的服務用量資料。如需所支援服務及新視圖中預期內容的相關資訊，請參閱[服務用量詳細資料](/docs/hybrid/index.html#servicesresourceusage)。

## 運算
{: #compute_category}

### IBM Cloud 認證的基礎架構特性
文件日期：2019 年 1 月 22 日

新特性現在提供於 SAP HANA 及 SAP NetWeaver {{site.data.keyword.cloud_notm}} SAP 認證的基礎架構供應項目。

#### 多節點儲存空間
適用於線上分析程序 (OLAP) 工作負載（例如 SAP Business Warehouse (SAP BW) 及 SAP BW/4HANA）的 SAP HANA 多節點儲存空間。SAP HANA 多節點的 {{site.data.keyword.cloud_notm}} 解決方案包含多達 15+1 個節點（15 個工作者節點，加上一個待命節點），一個系統可以使用最多 30 TB 的記憶體。若要開始使用，請參閱[配置 {{site.data.keyword.cloud_notm}} 基礎架構以支援 SAP HANA 多節點](/docs/infrastructure/sap-hana/hana-multi-node.html#multi-node-storage)


#### 高可用性
針對 SAP HANA 及 SAP NetWeaver 支援高可用性 (HA) 解決方案。解決方案是以受支援的 OS 版本為基礎，並受限於伴隨部署而來的訂購 OS 授權，或是協力廠商授權，例如自帶授權 (BYOL)。若要開始使用，請按一下[這裡](/docs/infrastructure/sap-hana/hana-ha.html#ha)（適用於 SAP HANA）及[這裡](/docs/infrastructure/sap-netweaver/sap-ha.html#ha)（適用於 SAP NetWeaver）。
  
#### SAP Content Server
SAP Content Server 是獨立式元件，用來儲存大量任何格式且具有任何內容的電子文件。若要使用 SAP Content Server，您的 SAP 應用程式必須支援使用它。若要開始使用，請參閱 [SAP Content Server](/docs/infrastructure/sap-netweaver/sap-content-server.html#content-server)。

#### SAP MaxDB
SAP MaxDB 適用於 SAP NetWeaver。若要開始使用，請參閱[關於 {{site.data.keyword.cloud_notm}} SAP 認證的基礎架構](/docs/infrastructure/sap-netweaver/sap-about.html#about_ibmcloud_for_sap)。

#### SAP Business One
SAP Business One 是專為中小型企業設計的企業資源規劃 (ERP) 軟體。它將您的核心商業功能 - 會計與財務、採購與庫存、銷售與客戶關係，以及專案管理與作業 - 合併為一個應用程式。如需相關資訊，請參閱[開始使用](/docs/infrastructure/sap-b1/b1-index.html#getting-started)。

### 虛擬伺服器特性
文件日期：2018 年 11 月 16 日

下列特性目前適用於 {{site.data.keyword.BluVirtServers_full}} 供應項目。

#### 未實例時暫停計費
想要只為您使用超過的部分付費？您現在可以暫停虛擬伺服器實例的計費。暫停計費特性適用於具有按小時計費之公用特性大小與 SAN 支援儲存空間的虛擬伺服器實例。當您關閉支援暫停計費特性之虛擬伺服器的電源時，並不會增加特定運算資源的成本。關閉伺服器電源時，就會自動停止計費。暫停計費特性可協助您降低成本，並且讓您於再次需要虛擬伺服器的資源時，不需要重新佈建虛擬伺服器。如需相關資訊，請參閱[關於暫停計費](/docs/vsi/vsi_about_suspend.html)或 {{site.data.keyword.cloud_notm}} [部落格文章 ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")](https://www.ibm.com/blogs/bluemix/2018/10/suspend-billing-1-minute-granularity-virtual-servers/){: new_window}。

#### 針對未來虛擬伺服器實例保留資源
現在可以使用 {{site.data.keyword.BluVirtServers_full}} 保留實例供應項目。這很適合您想要為未來部署保證資源以及節省成本之用。您可以針對保留容量選擇一年或三年的合約期間。在該保留容量內，您可以保留一組特定大小且最多 20 個的虛擬伺服器實例，然後在需要這些實例時進行佈建。在合約期間的期限內，會保證您在選擇的 POD 及資料中心內擁有此容量。如需相關資訊，請參閱[保留虛擬伺服器](/docs/vsi/vsi_about_reserved.html)。

#### 將映像檔從 {{site.data.keyword.cos_full_notm}} 服務實例匯入到 {{site.data.keyword.cloud_notm}} 基礎架構
{{site.data.keyword.cloud_notm}} 基礎架構現在會與 {{site.data.keyword.cloud_notm}} 主控台上佈建的 {{site.data.keyword.cos_full_notm}} 服務互動。{{site.data.keyword.cos_full_notm}} 提供 Aspera 高速傳輸外掛程式，能大幅縮短上傳大型映像檔所需的時間量。映像檔上傳至 {{site.data.keyword.cos_full_notm}} 之後，您可以從 {{site.data.keyword.cos_full_notm}} [匯入映像檔](/docs/infrastructure/image-templates/import-image.html)至 {{site.data.keyword.cloud_notm}} 基礎架構。您也可以從 {{site.data.keyword.cloud_notm}} 基礎架構[匯出映像檔](/docs/infrastructure/image-templates/export-image-ibm-cos.html)至 {{site.data.keyword.cos_full_notm}}。

#### 虛擬伺服器實例的放置群組
放置群組現在適用於 {{site.data.keyword.BluVirtServers_full}}。使用放置群組，您可以使用公用實例在資料中心內建置高可用性，或在較大型的部署內提供額外的容錯層次。如需相關資訊，請參閱[放置群組](/docs/vsi/vsi_placegroup.html)。 

### 建置套件的最新更新

請造訪下列頁面，以取得累加的最新更新清單：

* [SDK for Nodejs 建置套件的最新更新](/docs/runtimes/nodejs/updates.html#latest_updates)
* [Liberty 建置套件的最新更新](/docs/runtimes/liberty/updates.html#latest_updates)
* [ASP.NET Core 建置套件的最新更新](/docs/runtimes/dotnet/updates.html#latest_updates)
* [IBM XPages for {{site.data.keyword.Bluemix_notm}} 建置套件的最新更新](/docs/starters/xpages/index.html#updates)

### {{site.data.keyword.containerlong_notm}} 的最新更新

{{site.data.keyword.containerlong_notm}} 已在 2017 年 5 月啟動其 Kubernetes 架構。單一及可擴充容器群組的前一個架構現在[自 2017 年 12 月 5 日開始完全淘汰](https://www.ibm.com/blogs/bluemix/2017/07/deprecation-single-scalable-group-container-service-bluemix-public/){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")。  

[請參閱文件，以取得在 {{site.data.keyword.Bluemix_notm}}](/docs/containers/container_index.html) 上開始使用原生 Kubernetes 環境的相關資訊。如果有問題，您可以將它們張貼到 Slack：https://ibm-container-service.slack.com/。


### {{site.data.keyword.containerlong_notm}} 現在有高可用性的 Kubernetes
文件日期：2018 年 11 月 7 日

使用新的高可用性 Kubernetes 主節點特性，提高您的叢集可用性。高可用性 Kubernetes 主節點會設定多個抄本以供 Kubernetes API 伺服器、etcd、Kubernetes 排程器和控制器使用，這些全都分散在不同的實體主機。當您建立執行 Kubernetes 1.12、1.11 或 1.10 版的叢集時，您的 Kubernetes 主節點會依預設設定高可用性。若要在執行上述其中一個 Kubernetes 版本的現有叢集裡啟用此特性，您必須完成[準備步驟](/docs/containers/cs_versions.html#110_ha-masters)。

### 在 {{site.data.keyword.containerlong_notm}} 中建立多區域叢集
文件日期：2018 年 7 月 10 日

想要改善叢集和應用程式可用性嗎？現在您可以將叢集橫跨在精選都會區的多個區域之間。如需相關資訊，請參閱[在 {{site.data.keyword.containershort_notm}} 中建立多區域叢集](cs_clusters.html#multizone)。

### {{site.data.keyword.containerlong_notm}} 有了 Kubernetes 儀表板存取權
文件日期：2018 年 4 月 18 日

{{site.data.keyword.containerlong_notm}} 現在支援透過 {{site.data.keyword.Bluemix_notm}} 主控台直接存取 Kubernetes 儀表板。這個簡化的儀表板路徑讓叢集管理與資源視覺化的使用者體驗得到加強。如需詳細資料，請參閱 [{{site.data.keyword.Bluemix_notm}} 部落格](https://www.ibm.com/blogs/bluemix/2018/04/kubernetes-dashboard-access/){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")。


### 新的 Liberty for Java 建置套件 3.11 版
文件日期：2017 年 7 月 17 日

Liberty 建置套件 3.11 版提供新的每月 Liberty 運行環境版本，並且包含其他增進功能。每月 Liberty 運行環境版本已更新成 [2017.7.0.0](https://developer.ibm.com/wasdev/blog/2017/07/07/beta-websphere-liberty-tools-july-2017/) 版本。IBM JDK 已更新成 8.0.4.7 及 7.1.4.5 版本。建置套件也會提供「應用程式管理」公用程式及 Auto-Scaling 代理程式的已更新版本。預設 Cloudant Library 現在是正式 [java-cloudant](https://github.com/cloudant/java-cloudant)，但 [Ektorp 程式庫](https://github.com/helun/Ektorp)仍然是選項，如需這項變更的詳細資料，請參閱[部落格文章](https://www.ibm.com/blogs/bluemix/2017/05/default-library-change-cloudant-auto-wiring-liberty-buildpack/)。應用程式的記憶體小於 512MB 時，預設資料堆大小比例現在是 50%，如果超過 512MB，則仍然是 75%。現在會產生新的編譯打包作業日誌，以容許更輕鬆地除錯編譯打包錯誤。如需相關資訊，請參閱[最新更新](/docs/runtimes/liberty/updates.html)文件。

### 新的 Liberty for Java 建置套件 3.10 版
文件日期：2017 年 6 月 12 日

Liberty 建置套件 3.10 版提供新的每季及每月 Liberty 運行環境版本，並且包含其他增進功能。預設 Liberty 運行環境版本已更新成 17.0.0.2。每月 Liberty 運行環境版本已更新成 [2017.5.0.0](https://developer.ibm.com/wasdev/blog/2017/05/12/beta-websphere-liberty-tools-may-2017/){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示") 版本。建置套件也會提供「應用程式管理」公用程式及 Extreme Scale Client 的已更新版本。如需相關資訊，請參閱[最新更新](/docs/runtimes/liberty/updates.html)文件。

### 新的 SDK for Node.js 建置套件 3.12 版
文件日期：2017 年 5 月 16 日

SDK for Node.js 建置套件 3.12 版提供 IBM SDK for Node.js 0.12.17、0.12.18、4.8.0、4.8.2、6.10.0 及 6.10.2 版。預設值現在已從最新 4.x 變更成最新 6.x，因此目前是 6.10.2。這是主要版本變更，可能會影響根據預設值的應用程式。如需如何避免任何問題的相關資訊，請參閱 [Node.js 版本長期支援及 SDK for Node.js 建置套件](https://www.ibm.com/blogs/bluemix/2016/11/node-version-support-and-sdk-buildpack/){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")。

除了新的運行環境之外，此版本還包含「應用程式管理性能檢測中心」處理程式及 Node.js 6.9.5 和 6.10.0 版問題的建置套件錯誤修正程式。

### 新的 Liberty for Java 建置套件 3.9 版
文件日期：2017 年 4 月 27 日

Liberty 建置套件 3.9 版提供新的每月 Liberty 運行環境版本，並且包含其他增進功能。預設 Liberty 運行環境版本已更新成包括 PI77770、PI77605、IFPI77438 及 IFPI79275 iFix。每月 Liberty 運行環境版本已更新成 [2017.3.0.0](https://developer.ibm.com/wasdev/blog/2017/03/14/beta-websphere-liberty-tools-march-2017/){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示") 版本。「記憶體計算」已從編譯打包移至啟動處理程序，容許透過重新啟動應用程式更輕鬆地變更資料堆記憶體。建置套件也會提供 Auto-Scaling 服務代理程式及 Extreme Scale Client 的已更新版本。如需相關資訊，請參閱[最新更新](/docs/runtimes/liberty/updates.html)文件。

## 服務
{: #services_category}

### {{site.data.keyword.appid_short_notm}} 中可用的新特性
文件日期：2018 年 12 月 22 日

{{site.data.keyword.appid_short_notm}} 服務已引進新的進階特性，這些特性可強化鑑別及應用程式的安全。

{{site.data.keyword.appid_short_notm}} 協助您新增不同類型的使用者鑑別到行動及 Web 應用程式。只需要幾行程式碼，您便可以新增鑑別，且不必管理基礎架構以隨著使用者基礎調整。請參閱下列加強功能，然後自行嘗試服務！

多因子鑑別：您現在可以針對 Cloud Directory 使用電子郵件 MFA。將 MFA 設為開啟之後，使用者會被要求提供透過電子郵件收到的一次性代碼，以及他們的密碼。如果您正在使用企業登入搭配 SAML 2.0 或社交登入，您可以透過該身分提供者啟用 MFA。
進階高階密碼：啟用進階密碼原則特性時，您可以針對 Cloud Directory 施行更安全的密碼。您可以配置一組密碼規則，限制使用者在被鎖定之前可嘗試登入的次數，或是密碼多少次以內不得重複使用。

進階安全特性有其他的定價元件。如需定價計算的相關資訊，請參閱[型錄](https://cloud.ibm.com/catalog/services/app-id)的定價小節。

請參閱 [{{site.data.keyword.appid_short_notm}} 文件](/docs/services/appid/index.html)，今天就開始使用！

### {{site.data.keyword.backup_notm}} 簡介
文件日期：2018 年 12 月 20 日

{{site.data.keyword.BluSoftlayer_full}} 儲存空間基礎架構團隊鄭重推出新的 {{site.data.keyword.backup_full}}，它包含一個永久免費的 10 GB 層級。此外，所有外掛程式現在也都免費。因此，您的特定應用程式使用案例的實作，像是 MSSQL、Oracle DB、Exchange 或甚至 Bare Metal Restore，都不會產生額外的成本。新的 {{site.data.keyword.backup_notm}} 是促成您任何規模之備份需求的最佳解決方案。如需相關資訊，請參閱 [IBM Cloud Blog ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")](https://www.ibm.com/blogs/bluemix/2018/12/introducing-a-new-cloud-backup-service-ibm-cloud-backup/){: new_window}。

### Citrix NetScaler VPX 12.1 版
文件日期：2018 年 11 月 21 日
{: #vpx121}

#### 具有多個 IP 位址的虛擬伺服器
您現在可以使用多個非連續/連續 VIP IPv4 及 IPv6 位址來建立單一負載平衡虛擬伺服器。連結至虛擬伺服器的每一個 VIP 位址，都被視為個別虛擬伺服器。

如需此特性的相關資訊，請參閱 Citrix 文章 [Multiple IP virtual servers ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")](https://docs.citrix.com/en-us/netscaler/12-1/load-balancing/load-balancing-customizing/multi-ip-virtual-servers.html){: new_window}。

#### SSL
已針對 SSL 連線套用下列更新：
 
* 從 DEFAULT_BACKEND 密碼群組移除低保護性密碼。 
* 支援 Thales nShield® 外部 HSM 前端系統使用 ECDHE 密碼
* 支援 SafeNet 網路外部 HSM 前端系統使用 ECDHE 密碼
* 移除 SSLv2：從 12.1 版開始，NetScaler VPX 應用裝置不支援 SSLv2。

如需 12.1 SSL 更新的詳細資料，請參閱 [Citrix 12.1 版本注意事項 ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")](https://docs.citrix.com/en-us/netscaler/12-1/downloads/release-notes-12-1-48-13.html){: new_window}。

#### GSLB 的服務群組支援
您現在可以為 GSLB 配置以 IP 位址為基礎的服務群組、以網域名稱為基礎的服務群組，或以網域名稱為基礎的自動調整服務群組。您也可以像單一服務一樣輕鬆地管理一群服務，並將服務群組連結至虛擬伺服器，以及將服務新增至群組。

如需 GSLB 服務群組的相關資訊，請參閱 Citrix 文章[配置 GSLB 服務群組 ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")](https://docs.citrix.com/en-us/netscaler/12/global-server-load-balancing/configure/configuring-a-gslb-service-group.html){: new_window}。


### 重大的 {{site.data.keyword.conversationshort}} 更新
文件日期：2018 年 11 月 9 日

{{site.data.keyword.conversationshort}} 有新的外觀，並新增了特性。稱為*工作區* 的構件（這是強化聊天機器人之機器學習模型訓練資料的容器），已取代為*對話技能*。現在可以藉由為助理新增對話技能而比較輕鬆地進行部署。新的助理層會管理使用者與您技能之間的訊息編排。您可以在助理新增內建整合，以便花最少的功夫將對話技能發佈到熱門的傳訊頻道。{{site.data.keyword.conversationshort}} 的文件已移至新的位置。如需相關資訊，請參閱[產品文件](/docs/services/assistant/index.html)。


### 使用 Terraform 和 Ansible 自動進行基礎架構及應用程式部署
文件日期：2018 年 11 月 2 日

Terraform 及 Ansible 是開放程式碼軟體，您可以用它們來從頭到尾自動部署雲端解決方案。使用 Terraform，您可以指定 {{site.data.keyword.Bluemix_notm}} 基礎架構元件並快速建置複雜的多層式雲端環境，以便促成 Infrastructure as Code (IaC)。接著，使用 Ansible 連接至專用網路上的運算主機，以便部署應用程式、建置服務、執行 Script 或定義配置。 

若要開始瞭解每個開放程式碼產品的基本概念，請參閱我們的指導教學： 
* [在 {{site.data.keyword.Bluemix_notm}} 上使用 Terraform 部署 RedHat OpenShift Container Platform](/docs/terraform/tutorials/install_redhat_openshift.html#redhat){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")
* [在 IBM Cloud 基礎架構上使用 Terraform 和 Ansible 部署 WordPress](/docs/terraform/tutorials/wordpress_with_terraform_and_ansible.html#deploy_wordpress){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")。 

### {{site.data.keyword.cloudant_short_notm}} 的最新更新
文件日期：2018 年 9 月 28 日

請造訪下列頁面以取得 {{site.data.keyword.cloudant_short_notm}} [最新更新](/docs/services/Cloudant/release_info/release_notes.html#release-notes){:new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示") 的清單。

### {{site.data.keyword.IBM_notm}} {{site.data.keyword.DRA_short}} 通用版簡介
文件日期：2018 年 9 月 20 日

{{site.data.keyword.DRA_short}} 服務現在已在美國南部、德國和英國地區正式發行。

{{site.data.keyword.DRA_short}} 有助於團隊改善生產力、效率及上市時間，團隊也能使用來自 DevOps 工具的資料輕鬆測量成功，或是改善程式碼的品質。本服務提供單一工具，讓企業瞭解他們在所有程式碼庫和團隊之間的 DevOps 活動。

* **速度**：{{site.data.keyword.DRA_short}} 會在單一儀表板裡顯示您所有應用程式之間的所有分析。
* **品質**：藉由實作關卡部署原則，減輕具風險之版本的危害。例如，若您有「程式碼涵蓋面」的原則，在選取的容忍度下，{{site.data.keyword.DRA_short}} 一律會阻擋不符合已定義容忍度的程式碼版本。一段時間後，這些原則會有助於改善部署程序的整體品質。 
* **控制**：藉由使用程式碼涵蓋面、單元測試及其他工具，在團隊應對 DevOps 作法的趨勢時，測量一段時間的結果。這些趨勢有助於團隊更妥善控管他們的 DevOps 作法。

### {{site.data.keyword.security-advisor_long_notm}} 現在是測試版！
文件日期：2018 年 9 月 5 日

{{site.data.keyword.security-advisor_short}} 增加了新的功能，現在以測試版服務提供使用。{{site.data.keyword.security-advisor_short}} 將您的 {{site.data.keyword.Bluemix_notm}} 安全設定集中在一個儀表板中。除了資訊集中化之外，此服務還將重要的安全資訊彙總成可輕鬆導覽的資訊磚，以清楚顯示所偵測到的安全問題。按一下資訊磚即可往下探查，以調查需優先處理的問題、歷程，以及警示背後的詳細資料。若要修正問題，只要再次往下探查，即可取得所有詳細資料及建議的修正程式，以移除威脅並確保您的環境維持安全狀態。

{{site.data.keyword.security-advisor_short}} 很快就會變成您的常用主控台，可讓您集中化、檢視及管理 {{site.data.keyword.Bluemix_notm}} 環境的安全。

我們在此版本中實作了下列各項：
* Findings API
* 可讓您帶入自己的提供者
* 更新儀表板體驗

還有好多功能！

若要開始使用，請參閱 [{{site.data.keyword.security-advisor_short}} 文件](/docs/services/security-advisor/index.html)。

### {{site.data.keyword.iva_full_notm}} 通用版簡介
文件日期：2018 年 6 月 26 日

現在已提供 [{{site.data.keyword.iva_full}}](https://cloud.ibm.com/catalog/services/voice-agent-with-watson)![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示") 通用版！您可以建立 Watson 服務所建置且客戶可通話並透過電話交談的認知語音代理程式。以 Watson 人工智慧為骨幹，您的語音代理程式可以透過交談方式進行通訊，處理複雜互動，以及解決語音代理程式內的客戶通話。

此版本引進下列新特性：

* 新增災難回復用的備用 Watson 服務位置。 
* 編輯進階配置選項，以自訂您的語音代理程式如何轉接通話、播放預先錄製的訊息給來電者，以及與 Watson 服務互動。
* 配置 Standard 服務方案中的並行連線數上限。
* 將您的語音代理程式連接到 NetFoundry、Twilio、AT&T 等 SIP 幹線提供者及其他服務提供者，或與 {{site.data.keyword.iva_short}} 進行對等通訊。

若要開始使用，請參閱 [{{site.data.keyword.iva_short}}](/docs/services/voice-agent/getting-started.html) 文件。

### {{site.data.keyword.streaminganalyticsshort}} 引進具有容器基礎架構的新服務方案
文件日期：2018 年 4 月 20 日

{{site.data.keyword.streaminganalyticsshort}} 現在會在 Kubernetes 容器基礎架構上執行，可為服務提供安全性和可用性優點。
 
您可以使用[第 2 版服務方案](/docs/services/StreamingAnalytics/service_plans.html#service_plans)，來存取這個新的容器基礎架構。您可以選擇最適合您需要進行之工作的 {{site.data.keyword.streaminganalyticsshort}} 方案。第 2 版服務方案包含下列加強功能：
 
* [IBM Streams QSE 與 Docker](https://www-01.ibm.com/marketing/iwm/iwm/web/preLogin.do?source=swg-ibmistvi)![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")：查看[開發手冊](https://developer.ibm.com/streamsdev/docs/cloud-beta-devguide/) ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")，以瞭解如何搭配使用新的 Streams QSE 與在 Docker 環境中執行的 RHEL 7，以透過新的 {{site.data.keyword.streaminganalyticsshort}} 第 2 版方案來編譯及部署應用程式。 
* [{{site.data.keyword.streaminganalyticsshort}} 第 2 版 REST API](https://cloud.ibm.com/apidocs/1939-streaming-analytics-v2#introduction)![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")
* [新的入門範本及範例應用程式](https://developer.ibm.com/streamsdev/docs/cloud-beta-samples/) ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")
* [{{site.data.keyword.streaminganalyticsshort}} 服務中的高可用性加強功能](/docs/services/StreamingAnalytics/c_ha.html#consistent-regions)
* [{{site.data.keyword.streaminganalyticsshort}} 服務中的新問題判斷特性](https://developer.ibm.com/streamsdev/2018/02/15/streaming-analytics-console-gives-ways-find-fix-errors-beta-plans/) ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")
* [監視操作員如何作業及雲端中的保證值組處理](https://developer.ibm.com/streamsdev/2018/02/15/monitor-operators-behave-ensure-resource-optimization/)![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")

### {{site.data.keyword.iva_full_notm}} 現在是測試版！
文件日期：2018 年 3 月 16 日

使用 [{{site.data.keyword.iva_full}}](https://cloud.ibm.com/catalog/services/voice-agent-with-watson)![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")，您可以建立 Watson 服務所建置且客戶可通話並透過電話交談的認知語音代理程式。以 Watson 人工智慧為骨幹，您的語音代理程式可以透過交談方式進行通訊，處理複雜互動，以及解決語音代理程式內的客戶通話。

此測試版引進下列主要特性：

* 比之前更輕鬆地開始使用，方法是使用單一步驟來建立語音代理程式及所有必要 Watson 服務。
* 轉接來自語音代理程式的通話，例如人力客服中心客服人員或其他目的地。
* 收集及分析通話資料，方法是配置語音代理程式將通話詳細記錄、轉錄及 {{site.data.keyword.conversationshort}} 各回交談事件轉遞給 {{site.data.keyword.cloudant_short_notm}} 資料庫。
* 在新的_用量_ 頁面上，監視服務用量，以及檢視通話日誌。您可以檢視現行月份的快速統計資料、尋找及過濾通話日誌，以及檢視每個個別通話的系統訊息。
* 透過埠 5061 及「安全即時傳輸通訊協定 (SRTP)」使用 SIP TLS (sips URI)，以建立具有媒體加密的安全通話。
* 在其他 {{site.data.keyword.cloud_notm}} 空間中連接至 {{site.data.keyword.speechtotextfull}} 及 {{site.data.keyword.texttospeechfull}} 服務實例，以增加彈性。

若要開始使用，請參閱 [{{site.data.keyword.iva_short}}](/docs/services/voice-agent/getting-started.html) 文件。

### {{site.data.keyword.visualrecognitionshort}} 的更新
文件日期：2018 年 3 月 14 日

{{site.data.keyword.visualrecognitionfull}} 服務已更新，因此新的「自訂分類器」模型訓練現在會以深度學習神經網路型的分類器形式產生。產生這些深度學習模型所需的額外運算，可能需要額外的時間，以便新模型進行訓練。

目前，現有的自訂分類器可以繼續進行更新及重新訓練，不會更新為這個新的深度學習機器模型格式。

### {{site.data.keyword.streaminganalyticsshort}} 更新項目
文件日期：2018 年 2 月 14 日

[{{site.data.keyword.streaminganalyticsshort}} 服務](https://cloud.ibm.com/catalog/services/streaming-analytics){: new_window}中主控台的[測試版 - 入門及測試版 - 增強方案](/docs/services/StreamingAnalytics/beta_plans.html#beta_plans) ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示") 包括數個加強功能：

* [新的 IBM Streams QSE for Docker](https://www-01.ibm.com/marketing/iwm/iwm/web/preLogin.do?source=swg-ibmistvi){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")：查看[測試版開發手冊](https://developer.ibm.com/streamsdev/docs/cloud-beta-devguide/){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")，以瞭解如何搭配使用新的 Streams QSE 與在 Docker 環境中執行的 RHEL 7，以透過新的 {{site.data.keyword.streaminganalyticsshort}} 測試版方案來編譯及部署應用程式。
* [{{site.data.keyword.streaminganalyticsshort}} 第 2 版 REST API](https://cloud.ibm.com/apidocs/1939-streaming-analytics-v2#introduction){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")
* [新的入門範本及範例應用程式](https://developer.ibm.com/streamsdev/docs/cloud-beta-samples/)
* [{{site.data.keyword.streaminganalyticsshort}} 服務中的高可用性加強功能](/docs/services/StreamingAnalytics/consistentregions.html#consistentregions)
* [{{site.data.keyword.streaminganalyticsshort}} 服務測試版中的新問題判斷特性](https://developer.ibm.com/streamsdev/2018/02/15/streaming-analytics-console-gives-ways-find-fix-errors-beta-plans/){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")
* [監視操作員如何作業及雲端中的保證值組處理](https://developer.ibm.com/streamsdev/2018/02/15/monitor-operators-behave-ensure-resource-optimization/){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")

### {{site.data.keyword.keymanagementservicelong_notm}} 展開至雪梨地區
文件日期：2018 年 1 月 31 日

目前可在雪梨地區使用 {{site.data.keyword.keymanagementserviceshort}} 加密金鑰管理服務。雪梨是美國南部（達拉斯）及倫敦後面的第三個地區，以提供 {{site.data.keyword.keymanagementserviceshort}} 使用者的 GA 狀態。

{{site.data.keyword.keymanagementserviceshort}} 是一種加密金鑰管理服務，提供簡單且經濟的金鑰管理解決方案來管理用來加密 {{site.data.keyword.Bluemix_notm}} 中所儲存資料的金鑰。{{site.data.keyword.keymanagementserviceshort}} 會管理金鑰的整個生命週期（從建立金鑰到使用應用程式、保存金鑰及摧毀金鑰），同時也會在資料管理與金鑰管理之間施行權責區分。

{{site.data.keyword.keymanagementserviceshort}} 支援具有適用 IBM 資料服務的 BYOK（自帶金鑰 - 客戶受管理加密）。BYOK 可讓使用者匯入內部建立的主要信任根加密金鑰，以更充分地管理處於靜止狀態時之資料 (data-at-rest) 儲存在 {{site.data.keyword.Bluemix_notm}} 中的安全。


### {{site.data.keyword.containershort_notm}}：Kubernetes 1.8.x 支援
文件日期：2018 年 1 月 19 日

從 2017 年 11 月之後，{{site.data.keyword.containershort_notm}} 已支援 Kubernetes `1.8.x`。我們很自豪地宣布預設 Kubernetes 版本現在是 `1.8.6`。在不久的未來，我們將提供 `1.9.x` 支援。

### Watson Discovery Visual Insights
文件日期：2017 年 11 月 30 日

以視覺化方式探索採用 {{site.data.keyword.discoveryshort}} 技術的連線對以文字形式偵測到的語意元素的瞭解（例如實體、關係、概念及其他項目）。

開始使用立即可用的 {{site.data.keyword.discoveryshort}} News 集合來探索全球新聞。或者，在 {{site.data.keyword.discoveryshort}} 中探索您自己的文件集合。只要使用您的 {{site.data.keyword.Bluemix_notm}} 認證登入即可。如需相關資訊，請參閱 [Visual Insights 實驗性](https://visual-insights.cloud.ibm.com){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")。

### 新的 IBM Cloud Managed Database Server 測試版服務
文件日期：2017 年 11 月 30 日

使用新的 IBM Cloud Managed Database Server 測試版服務，您就可以在 {{site.data.keyword.Bluemix_notm}} 上建立 Microsoft SQL Server 實例。此 SQL Server 實例的使用方式就像使用任何資料庫管理系統一樣，但沒有硬體設定或軟體安裝及維護的工作量及費用。

此服務提供下列特性：
* 選擇 Microsoft SQL Server 2012、2014 及 2016 版的 Enterprise 及 Standard Edition
* 各種預先定義的配置或大小，以符合應用程式工作負載需求
* 完全由 IBM 管理，包括監視、修補、備份、報告

若要開始使用，請參閱[開始使用 IBM Cloud Managed Database Server](/docs/services/managed-sql-server/getting-started.html)。

### {{site.data.keyword.mobilepushshort}} 的新增功能
文件日期：2017 年 10 月 26 日

我們已在最後幾個月對 {{site.data.keyword.mobilepushshort}} 服務進行數項加強。此服務現在可用於法蘭克福地區，以及達拉斯、倫敦和雪梨。以下是加強功能的詳細資料：

#### 監視
您現在可以追蹤特定時段的推送通知效能、追蹤送出的通知數目，以及已登錄裝置總數。您也可以登錄 Web 連結鉤，以收到生命週期中所有事件的通知。在下列文件鏈結及部落格文章中，可以找到更多詳細資料：
* [監視通知](/docs/services/mobilepush/push_monitoring.html#push_monitoring)
* [接收 Webhook 事件的警示](/docs/services/mobilepush/push_webhook.html#webhook_event_based_notifications)
* [IBM Push Notifications 中的監視](https://www.ibm.com/blogs/bluemix/2017/03/monitoring-ibm-push-notifications/){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")

#### Web 通知
我們現在支援 Safari Web 瀏覽器以及 Firefox、Chrome、Chrome App and Extensions 的 Web 通知。在 [IBM Bluemix Push Notifications Web SDK](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-javascript-webpush/blob/Doc/README.md){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示") 中，可以找到 Web SDK 及相關資訊。

#### 最新 Android 及 iOS 通知
我們有 iOS 11 通知的貨幣支援。我們也已納入來自 iOS10 及 Android N 的數個新通知相關加強功能。

* iOS10 - 互動式通知中的複合式多媒體通知、影像、按鈕及地圖，本地化字串支援
* Android N - 可擴充的通知、互動式及無聲自動通知、LED 燈設定

在[複合式多媒體通知](/docs/services/mobilepush/push_step_4_nf_rich.html#interactive-notifications)文件、[互動式及無聲自動通知](/docs/services/mobilepush/push_step_4_nf_interactive.html#interactive-notifications)文件以及[啟用進階推送通知](/docs/services/mobilepush/push_step_4_nf_adv.html#enabling-advanced-push-notifications)文件中，可以找到其他詳細資料。

#### APNS HTTP/2 支援
Apple 已為 Apple Notifications 建立 HTTP 通訊協定支援。{{site.data.keyword.mobilepushshort}} 服務現在支援 HTTP/2 通訊協定。使用這項支援，通知有效負載可以達 4 KB 以提高傳輸量，並提供即時回饋特性。「通用憑證」支援容許應用程式連接至沙盤推演及正式作業環境。

#### 新的精簡方案
{{site.data.keyword.mobilepushshort}} 服務的精簡方案每個月可以免費傳送 100K 通知。如需相關資訊，請參閱 [Bluemix 上 Push Notifications 服務的精簡方案](https://www.ibm.com/blogs/bluemix/2017/06/lite-plan-push-notifications-service-bluemix/){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示") 部落格文章。



### Mobile Analytics 的新增功能
文件日期：2017 年 10 月 26 日

我們已在最後幾個月對 {{site.data.keyword.mobileanalytics_short}} 服務進行加強。此服務現在可用於法蘭克福及雪梨地區，以及達拉斯和倫敦。以下是加強功能的詳細資料：

#### Web SDK 支援
{{site.data.keyword.mobileanalytics_short}} 現在除了支援 Web 應用程式分析之外，也是 Omni 通道服務。在 [https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-web-analytics/](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-web-analytics/){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示") 中，可以找到更多詳細資料。

#### 與 {{site.data.keyword.mobilefoundation_short}} 服務整合
{{site.data.keyword.mobilefoundation_short}} 服務現在運用 {{site.data.keyword.mobileanalytics_short}} 服務進行應用程式、使用者及效能分析。使用者可以運用匯出至 Db2 倉儲選項來建置配接卡分析及自訂圖表。您可以在下列部落格文章中找到其他詳細資料：

* [Mobile Foundation Service integration with Mobile Analytics Service](https://www.ibm.com/blogs/bluemix/2017/08/mobile-foundation-service-integration-mobile-analytics-service-2/){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")
* [Building custom charts by using IBM Bluemix Mobile Analytics service and IBM Mobile Foundation Service](https://mobilefirstplatform.ibmcloud.com/blog/2017/04/26/custom-charts-using-analytics-and-dashdb-analytics-service/){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")
* [Building charts for Adapter analytics by using IBM Bluemix Mobile Analytics service and IBM Mobile Foundation Service](https://mobilefirstplatform.ibmcloud.com/blog/2017/04/26/adapter-analytics-using-analytics-and-dashdb-analytics-service/){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")

#### {{site.data.keyword.mobilefirst_notm}} 樣板現在包括 {{site.data.keyword.mobileanalytics_short}}
「Mobile Services 樣板」是一種範本，提供一組行動服務，讓使用者快速開始進行。{{site.data.keyword.mobileanalytics_short}} 服務現在是[型錄](https://cloud.ibm.com/catalog/starters/mobilefirst-services-starter){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示") 中所提供樣板的一部分。


### {{site.data.keyword.streaminganalyticsshort}} 的更新
文件日期：2017 年 10 月 20 日

* IBM Streams Runner for Apache Beam：您現在可以在 Streams 開發環境本端開發 Beam 應用程式，然後將這些應用程式提交至 {{site.data.keyword.Bluemix_notm}} 中的 {{site.data.keyword.streaminganalyticsshort}} 服務。IBM Streams Runner for Apache Beam 會在 Streams 環境中執行 Beam 管線。使用 Streams Runner 所啟動的 Beam 應用程式會轉換為「Streams 應用程式組合 (SAB)」檔案，而您接著可以將該檔案部署至 {{site.data.keyword.streaminganalyticsshort}}。如需詳細資料，請參閱 [Streaming Analytics 中的 IBM Streams Runner for Apache Beam](/docs/services/StreamingAnalytics/gs_beamrunner.html)。
* 您可以更快速地從日誌檔中找到資訊。已更新主控台，以改善 Python 或 Java 拓蹼之應用程式圖形的顯示。請參閱[主控台的加強功能](https://developer.ibm.com/streamsdev/2017/10/13/enhancements-to-the-console/){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")。

### IBM App Launch for {{site.data.keyword.Bluemix_notm}} 服務
文件日期：2017 年 10 月 12 日

IBM App Launch for {{site.data.keyword.Bluemix_notm}} 服務是一個實驗性供應項目，藉由提供平台來建立跨對象各種層面的目標參與，讓您可以測量客戶體驗。App Launch 服務會提供對客戶喜好設定及痛點的見解以作為參與的結果，並協助您個人化應用程式以獲得較佳的客戶體驗。

「應用程式擁有者」現在可以藉由避免版本週期複雜性來加速將創新提供給行動應用程式。App Launch 服務可讓應用程式擁有者高速啟動行動應用程式的特性，並藉由控制目標對象來測量影響。應用程式擁有者可以與應用程式開發人員合作，以定義特性的關鍵績效指標、測量影響，並根據即時回饋讓特性推出及回復決策。此服務也可以測試應用程式特性、使用者介面元件及訊息的多個變式，並根據回饋做出決策。

如需相關資訊，請參閱[入門指導教學](/docs/services/app-launch/index.html#gettingstartedtemplate)。

### {{site.data.keyword.ibmwatson_notm}} {{site.data.keyword.relationshipextractionshort}} 的更新
文件日期：2017 年 10 月 4 日

使用者可以藉由 {{site.data.keyword.relationshipextractionshort}} 來使用新的自訂功能及新的語言模型。新的語言是 WKS 的荷蘭文、韓文及簡體中文支援。

### {{site.data.keyword.containerlong_notm}} 叢集更新
文件日期：2017 年 9 月 20 日

您現在可以將叢集更新成 {{site.data.keyword.Bluemix_notm}} 中的最新可用 Kubernetes 版本。使用 GUI 或 CLI，將 Kubernetes 主節點及工作者節點更新成 Kubernetes 1.7，並充分運用新的特性及修補程式。

如需相關資訊，請參閱 [{{site.data.keyword.containerlong_notm}} 中可用的 Kubernetes 1.7](https://www.ibm.com/blogs/bluemix/2017/09/kubernetes-1-7-available-ibm-bluemix-container-service/){: new_window} ![部鏈結圖示](../../icons/launch-glyph.svg "部鏈結圖示")。

### 含有 Watson 實驗性服務的新 IBM Voice Agent
文件日期：2017 年 9 月 15 日

使用新的 {{site.data.keyword.iva_full}} 實驗性服務，您可以建立以 Watson 服務為建置基礎且客戶可通話並透過電話交談的認知語音代理程式。以 Watson 人工智慧為骨幹，您的語音代理程式可以透過交談方式進行通訊，處理複雜互動，以及解決語音代理程式內的客戶通話。

{{site.data.keyword.iva_short}} 會緊密地連接及編排 Watson {{site.data.keyword.speechtotextshort}}、{{site.data.keyword.conversationshort}} 及 {{site.data.keyword.texttospeechshort}} 服務，以模擬自然語言交談。每一個語音代理程式都會自動擴充，以同時處理多個通話。在此實驗性版本中，您可以使用下列主要特性來自訂語音代理程式：

* 匯入範例 {{site.data.keyword.conversationshort}} 對話以開始使用，然後建立自己的對話以符合公司的需求。
* {{site.data.keyword.conversationshort}} 服務內使用 API 的程式語音代理程式行為。您可以控制從打擾行為到掛斷對話中任何節點的通話的所有項目。
* 如果您要將不同的電話號碼連接至專門針對不同主題的認知代理程式，則可以輕鬆地建立及管理多個語音代理程式。
* 擴充服務的功能，方法是連接服務編排引擎 (SOE)，讓您可以使用協力廠商 API。例如，SOE 可以接聽來自 {{site.data.keyword.conversationshort}} 服務的觸發程式，然後使用提供的 API 來查閱現有系統中的資訊，或提供其他分析。

若要開始使用，請參閱[開始使用 {{site.data.keyword.iva_short}}](/docs/services/voice-agent/getting-started.html) 文件。


### {{site.data.keyword.streaminganalyticsshort}} 服務更新：主控台包括新的方式來精確找出應用程式中的問題
文件日期：2017 年 8 月 14 日

針對 Python 及 Java 應用程式，會根據 @spl_note 註釋來顯示原始檔位置。

如需詳細資料，請參閱 [{{site.data.keyword.streaminganalyticsshort}} 的最新增進功能](https://developer.ibm.com/streamsdev/2017/08/14/latest-improvements-streaming-analytics-console/){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")。

### IBM Cloud Monitoring 現在也可用於英國地區
文件日期：2017 年 8 月 1 日

使用 {{site.data.keyword.monitoringlong}} 服務可以擴充您在使用度量值時，{{site.data.keyword.Bluemix_notm}} 中的收集、保留和分析功能。

* 將警示化為行動！{{site.data.keyword.monitoringlong}} 提供一個 API，您可以使用該 API 來設定效能臨界值，並在違反那些臨界值時收到通知。定義單一服務實例或應用程式實例的警示規則，以及用來對一組實例進行報告的警示規則。觸發警示時，透過電子郵件、PagerDuty 事件、Webhook 通知或這三者的任意組合來接收通知。

* 新增自訂度量值。{{site.data.keyword.monitoringlong}} 超值方案提供 API，您可以用來新增相關應用程式及商業度量值至您的 Cloud Monitoring 資料。您也可以用它們從 {{site.data.keyword.IBM_notm}} Cloud 之外將度量值資料傳送至 {{site.data.keyword.monitoringlong}} 服務。

* 建置可重複使用的儀表板，並使它們成為互動式。{{site.data.keyword.monitoringlong}} 管理的 Grafana 支援使用龐大視覺效果選項來建置自訂儀表板。您可以使用具有變數的度量值查詢，讓儀表板因為範本使用而變成動態。

* 透過 {{site.data.keyword.Bluemix_notm}} 型錄存取您的服務。{{site.data.keyword.monitoringlong}} 在 {{site.data.keyword.Bluemix_notm}} 型錄的 DevOps 區段中提供為一個服務磚。對於具有單一和群組容器的 {{site.data.keyword.containershort}} 服務，您可以從 {{site.data.keyword.Bluemix_notm}} 使用者介面存取服務。

* 選擇符合您需要的服務方案。您可以選擇「精簡」服務方案或「超值」服務方案來符合您的用量需求。「精簡」方案所提供的度量值收集為每分鐘一次、保留 15 天，並且會有補充性的警示。或者，您可以選取「超值」方案，以獲得更高的耗用、更長的度量值保留，以及存取服務 API，例如，傳送或擷取 {{site.data.keyword.monitoringlong}} 服務的度量值。{{site.data.keyword.monitoringlong}} 提供的度量值收集為每分鐘一次。「精簡」方案會以完整解析度保留度量值 15 天。「超值」方案會以完整解析度保留度量值 45 天。

舊式 {{site.data.keyword.monitoringshort}} 服務是依服務定義頻率來收集度量值，從 30 秒開始，並在經過一段時間彙總為 1 小時頻率。{{site.data.keyword.monitoringlong}} 現在提供 1 分鐘的完整解析度收集。「精簡」方案會保留度量值 15 天。「超值」方案會保留度量值 45 天。

如需 {{site.data.keyword.monitoringlong}} 服務的相關資訊，請參閱[開始使用 Monitoring 文件](/docs/services/cloud-monitoring/index.html#getting-started-with-ibm-cloud-monitoring)或 [IBM Cloud Monitoring - 含有新增特性的服務重新整理 ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")](https://www.ibm.com/blogs/bluemix/2017/07/ibm-cloud-monitoring-service-refresh-new-features/)。


### IBM Cloud Log Analysis 現在可用於美國南部地區
文件日期：2017 年 7 月 31 日

{{site.data.keyword.loganalysisfull}} 服務提供 {{site.data.keyword.Bluemix_notm}} 平台的日誌收集和日誌搜尋服務，並自動從精選 {{site.data.keyword.Bluemix_notm}} 服務收集應用程式與 {{site.data.keyword.Bluemix_notm}} 服務的資料。使用 {{site.data.keyword.loganalysisshort}} 服務，以：

* 依需要保留日誌。  

    日誌儲存在 IBM Cloud 儲存空間。您可以在需要時下載日誌。

* 管理已保留的日誌，以及使用新的 API 從 {{site.data.keyword.IBM_notm}} Cloud 外部傳送日誌資料。

* 選擇每天可搜尋的日誌數量。  

    有不同的方案可用，您可以用來搜尋每天最多 500 MB、2 GB、5 GB 和 10 GB 的日誌。

* 建置可重複使用的儀表板，並使它們成為互動式。

    {{site.data.keyword.loganalysisshort}} 的受管理 Kibana 支援建置自訂儀表板。

* 透過 {{site.data.keyword.Bluemix_notm}} 型錄存取您的服務。  

    對於具有單一及群組容器的 {{site.data.keyword.loganalysisshort}} 服務以及 {{site.data.keyword.IBM_notm}} Cloud Foundry 服務，您可以從 {{site.data.keyword.Bluemix_notm}} 使用者介面存取服務。

如需 {{site.data.keyword.loganalysisshort}} 服務的相關資訊，請參閱[開始使用 {{site.data.keyword.loganalysisfull}}](/docs/services/CloudLogAnalysis/index.html#getting-started-with-ibm-cloud-log-analysis) 及 [{{site.data.keyword.loganalysisshort}} 概觀](/docs/services/CloudLogAnalysis/log_analysis_ov.html#log_analysis_ov)。

### Virtual Router Appliance 的 Brocade 作業系統 18.x 版
文件日期：2018 年 7 月 25 日

Brocade OS 的 18.x 版現在適用於 Virtual Router Appliance。在所有新特性中，最值得一提的是此版本提供 Spectre 安全侵害的補救。 

18.x VRA 的新特性討論於下列主題：

* [如何設定使用區域防火牆的 IPSec 通道](/docs/infrastructure/virtual-router-appliance/vra-ipsec.html)
* [配置與 IPSec 和區域防火牆的 VFP 介面](/docs/infrastructure/virtual-router-appliance/vra-vfp.html)
* [使用 NAT 搭配以字首為基礎的 IPSec](/docs/infrastructure/virtual-router-appliance/vra-nat.html)
* [疑難排解您的 VFP 介面](/docs/infrastructure/virtual-router-appliance/vra-vfp-troubleshooting.html)

如果您從 Vyatta 5400 移轉，升級至 18.x 的最好方法是透過完整 OS 重新載入的[正常程序](/docs/infrastructure/virtual-router-appliance/upgrade-os.html)。

由於 Vyatta 5400 與 Virtual Router Appliance 之間沒有簡單的一對一功能對映，因此為 VRA 建立基準配置會有所助益。IBM 合作夥伴 WanClouds 可以協助您完成此程序，並提供在您的 VRA 上建立類似於 Vyatta 5400 之功能的指引。

如需在此升級進行過程中遇到之常見問題的相關資訊，請參閱我們的[其他文件](/docs/infrastructure/virtual-router-appliance/migration-issues.html#vyatta-5400-common-migration-issues)。

### 已重新命名 IBM dashDB for Analytics
文件日期：2017 年 7 月 18 日

下表彙總新名稱：

|舊名稱                      |新名稱                     |生效日期          |
|-----------------------------|----------------------------|----------------|
|IBM dashDB for Analytics    |IBM Db2 Warehouse on Cloud |2017 年 7 月 18 日|
{: caption="表 1. 服務名稱變更" caption-side="top"}

如需 IBM Db2 Warehouse on Cloud 及 Db2 on Cloud 的累加更新清單，請參閱：[Db2 Warehouse on Cloud 及 Db2 on Cloud 的新增功能](http://www.ibm.com/support/docview.wss?uid=swg21961758){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")。

### IBM Cloud Monitoring 現在可用於美國南部地區
文件日期：2017 年 7 月 17 日

使用 {{site.data.keyword.monitoringlong}} 服務可以擴充您在使用度量值時，{{site.data.keyword.Bluemix_notm}} 中的收集、保留和分析功能。

* 將警示化為行動！{{site.data.keyword.monitoringlong}} 提供一個 API，您可以使用該 API 來設定效能臨界值，並在違反那些臨界值時收到通知。定義單一服務實例或應用程式實例的警示規則，以及用來對一組實例進行報告的警示規則。觸發警示時，透過電子郵件、PagerDuty 事件、Webhook 通知或這三者的任意組合來接收通知。

* 新增自訂度量值。{{site.data.keyword.monitoringlong}} 超值方案提供 API，您可以用來新增相關應用程式及商業度量值至您的 Cloud Monitoring 資料。您也可以用它們從 {{site.data.keyword.IBM_notm}} Cloud 之外將度量值資料傳送至 {{site.data.keyword.monitoringlong}} 服務。

* 建置可重複使用的儀表板，並使它們成為互動式。{{site.data.keyword.monitoringlong}} 管理的 Grafana 支援使用龐大視覺效果選項來建置自訂儀表板。您可以使用具有變數的度量值查詢，讓儀表板因為範本使用而變成動態。

* 透過 {{site.data.keyword.Bluemix_notm}} 型錄存取您的服務。{{site.data.keyword.monitoringlong}} 在 {{site.data.keyword.Bluemix_notm}} 型錄的 DevOps 區段中提供為一個服務磚。對於具有單一和群組容器的 {{site.data.keyword.containershort}} 服務，您可以從 {{site.data.keyword.Bluemix_notm}} 使用者介面存取服務。

* 選擇符合您需要的服務方案。您可以選擇「精簡」服務方案或「超值」服務方案來符合您的用量需求。「精簡」方案所提供的度量值收集為每分鐘一次、保留 15 天，並且會有補充性的警示。或者，您可以選取「超值」方案，以獲得更高的耗用、更長的度量值保留，以及存取服務 API，例如，傳送或擷取 {{site.data.keyword.monitoringlong}} 服務的度量值。{{site.data.keyword.monitoringlong}} 提供的度量值收集為每分鐘一次。「精簡」方案會以完整解析度保留度量值 15 天。「超值」方案會以完整解析度保留度量值 45 天。

舊式 {{site.data.keyword.monitoringshort}} 服務是依服務定義頻率來收集度量值，從 30 秒開始，並在經過一段時間彙總為 1 小時的頻率。{{site.data.keyword.monitoringlong}} 現在提供 1 分鐘的完整解析度收集。「精簡」方案會保留度量值 15 天。「超值」方案會保留度量值 45 天。

如需 {{site.data.keyword.monitoringlong}} 服務的相關資訊，請參閱[開始使用 Monitoring 文件](/docs/services/cloud-monitoring/index.html#getting-started-with-ibm-cloud-monitoring)或 [IBM Cloud Monitoring - 含有新增特性的服務重新整理 ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")](https://www.ibm.com/blogs/bluemix/2017/07/ibm-cloud-monitoring-service-refresh-new-features/)。

### {{site.data.keyword.contdelivery_short}} 升級
文件日期：2017 年 7 月 11 日

升級的好處包括使用者體驗的錯誤修正程式、效能增進及修正。特殊加強功能（如果尚未存在於環境上）包括：
<ul>
<li>國際化及可存取性的修正程式及增進功能。</li>
<li>工具鏈的「管理」標籤中提供的工具鏈存取控制。</li>
<li>Continuous Delivery 工具型錄中的新工具整合。</li>
<li>Orion Web IDE 中改良的多個工作區分組。</li>
<li>Orion Web IDE 中的多個編輯器標籤支援。</li>
<li>Orion Web IDE 中的使用者介面佈景主題支援。</li>
</ul>

### {{site.data.keyword.uccr_short}} 測試版
文件日期：2017 年 6 月 23 日

{{site.data.keyword.uccr_short}} 是一個企業級版本管理解決方案，同時支援雲端原生及內部部署工具。

{{site.data.keyword.uccr_short}} 的測試版提供下列主要特性：
* 使用版本來管理多個部署方案及事件，以及針對多團隊版本工作量分工合作。
* 建立任何版本相關活動的事件，以及使用行事曆進行管理。
* 匯入自己的事件及版本。
* 自訂行事曆事件，以符合您的組織。
* 使用電子郵件及 Slack 類型作業進行版本通知。

### dashDB for Transactions 已重新命名為 {{site.data.keyword.Db2Hosted_notm}}
文件日期：2017 年 6 月 14 日

IBM {{site.data.keyword.DB2OnCloud_short}} 是 dashDB for Transactions 的新名稱。進行這項重新命名時，先前的自我管理 IBM {{site.data.keyword.DB2OnCloud_short}} 服務也會重新命名為 IBM Db2 Hosted。目前只會更新顯示名稱，因此任何 API 或指令行介面都會保持不變。

### {{site.data.keyword.sparks}} 更新：Stocator-S3 連接器支援 {{site.data.keyword.cos_full_notm}} Cross Region 服務（測試版）
文件日期：2017 年 6 月 5 日

{{site.data.keyword.sparks}} 使用者現在可以存取 {{site.data.keyword.cos_full_notm}} Cross Region 服務中所儲存的資料，並可對其執行分析。此為測試版功能。{{site.data.keyword.cos_full_notm}} 提供高容量且具成本效益的儲存空間，用來進行分析以及供其他應用程式使用，可擴充、具彈性而且容易使用。

Apache Spark 透過根據 Stocator 技術的儲存空間連接器來存取 {{site.data.keyword.cos_full_notm}} 資料，而此技術是針對 {{site.data.keyword.objectstorageshort}} 隱含地設計，因此會比舊式 {{site.data.keyword.objectstorageshort}} 連接器更為快速。身為使用者，您不需要變更或重新編譯 Apache Spark 程式碼。

[Access and Analyze data in IBM Cross Region Cloud Object Storage](https://www.ibm.com/blogs/bluemix/2017/06/access-analyze-data-ibm-cross-region-cloud-object-storage/){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示") 部落格文章說明如何搭配使用 {{site.data.keyword.cos_full_notm}} 資料與 {{site.data.keyword.sparks}} on {{site.data.keyword.Bluemix_notm}} 及 IBM Data Science Experience (DSx)。

如果您有任何疑問或評論，請透過 [sparksrv@us.ibm.com](sparksrv@us.ibm.com) 與我們聯絡。您的意見非常重要！

### 可用於 {{site.data.keyword.dashdbshort_notm}} for Transactions 的新可擴充方案
文件日期：2017 年 5 月 31 日

有一項可隨著資料庫需求而成長的新方案可供 {{site.data.keyword.dashdbshort}} for Transactions 使用。新的「彈性」方案容許您從小型系統開始，然後輕鬆且快速地增加該系統的能力及儲存空間容量。{{site.data.keyword.dashdbshort}} for Transactions 是 100% Db2 相容，並針對高可用性方案提供 99.95% SLA。

### {{site.data.keyword.Bluemix_notm}} 上 {{site.data.keyword.mobilepush}} 服務的新更新
文件日期：2017 年 5 月 24 日

以下是可用於 {{site.data.keyword.Bluemix_notm}} 上 {{site.data.keyword.mobilepush}} 服務的新更新

**精簡方案**：除了 {{site.data.keyword.mobilepush}} 服務的現有「基本方案」之外，我們還引進了新的「精簡方案」。根據新的方案，使用者每個月可以免費傳送十萬則數位訊息。從「精簡」方案升級至基本方案時，會在一百萬則數位訊息之後向使用者收費。將「精簡」方案升級至基本方案時，會開始計算一百萬則訊息。

**監視**：您現在可以瞭解所傳送的通知以及在「{{site.data.keyword.mobilepush}} 服務主控台」中所登錄的裝置。您也可以使用 REST API 進行訊息層次追蹤。配置 Webhook，即可取得從訊息遞送到訊息分派再到訊息接收的詳細資料。請參閱 [{{site.data.keyword.mobilepush}} 的監視功能](/docs/services/mobilepush/t_push_monitoring.html#monitor-notifications)。

**Web 通知**：您現在可以將通知傳送至 Safari Web 瀏覽器。

### Secure Gateway 更新
文件日期：2017 年 5 月 24 日

最新 Secure Gateway 維護更新包括使用者介面及 API Manager 中的次要錯誤修正程式、已更新的文件，而且用戶端已更新成 1.7.1 版。Secure Gateway 用戶端現在可用於 AIX 7.1+，並且支援透過 Squid Proxy 來進行出埠連接。

### {{site.data.keyword.streaminganalyticsshort}} 服務更新：在 Python 開發環境中開發 Streams 應用程式
文件日期：2017 年 4 月 13 日

過去，您必須安裝 IBM Streams 的本端版本，才能開發 Python 應用程式。不再是這樣了。現在，您可以在慣用的開發環境或 Jupyter 互動式記事本中使用 Python 來開發應用程式。

您可以使用 STREAMING_ANALYTICS_SERVICE 環境定義，將 Python 應用程式提交給 {{site.data.keyword.streaminganalyticsshort}} 服務。{{site.data.keyword.streaminganalyticsshort}} 服務需要 Python 3.5。

您可以在 IBM Data Science Experience (DSX) 中使用 Jupyter Notebook 來建立範例 Python 應用程式，並從 DSX 直接將這些應用程式提交給 {{site.data.keyword.streaminganalyticsshort}} 實例。請在 [DSX 社群頁面](https://datascience.ibm.com/){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示") 上查看記事本中的範例串流處理 Python 應用程式。

如需 {{site.data.keyword.streaminganalyticsshort}} 服務更新的相關資訊，請參閱 [{{site.data.keyword.streaminganalyticsshort}} 更新：DSX 整合及更輕鬆地 Python 開發](https://www.ibm.com/blogs/bluemix/2017/05/streaming-analytics-updates-dsx-integration-easier-python-development/){: new_window} ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")。

### {{site.data.keyword.sparks}} 更新：現在支援 Apache Spark 2.1
文件日期：2017 年 4 月 21 日

{{site.data.keyword.sparkl}} 將引進 Apache Spark 2.1 支援，以建立可加強複雜資料瞭解的演算法。Apache Spark 2.1 將協助已新增事件時間臨界值及 Kafka 0.10 支援的明顯結構化串流。Apache Spark 2.1 也聚焦於提高 Spark SQL、SparkR 及 MLlib 模組中的穩定性及可用性。如需 Spark 2.1 的詳細資料，請參閱 [Spark 2.1.0 版](http://spark.apache.org/releases/spark-release-2-1-0.html)。

我們很樂意回答任何有關 {{site.data.keyword.sparkl}} 或新版 Apache Spark 2.1 的問題，且可透過 sparksrv@us.ibm.com 進行聯繫。

### {{site.data.keyword.macm_short}} 即將淘汰
文件日期：2017 年 4 月 18 日

自 2017 年 5 月 30 日開始，將從「{{site.data.keyword.Bluemix_notm}} 型錄」移除 {{site.data.keyword.macm_long}} 服務磚，而且您無法再佈建新的 MACM 實例。不過，將繼續支援現有實例。支援結束日期是 2018 年 3 月 30 日。請在「支援結束日期」之前刪除 {{site.data.keyword.macm_short}} (MACM) 服務實例。我們鼓勵使用者移轉至 IBM Watson Content Hub。Watson Content Hub 可在 IBM Marketplace 取得，並提供使用者免費試用 30 天。IBM Watson Content Hub 透過已新增功能提供與 MACM 類似的功能（例如資產管理、使用 IBM Watson 服務的認知標記，以及包括的內容遞送網路 (CDN)），以確保最佳客戶體驗。IBM 提供服務參與，以將內容從 MACM 移轉至 Watson Content Hub。


### {{site.data.keyword.sparks}} 更新：現在提供 Data Science Experience 記事本支援
文件日期：2017 年 4 月 11 日

使用記事本及 Spark 的新平台是 Data Science Experience。請註冊 [Data Science Experience](http://datascience.ibm.com/)，開始建立記事本並且與其他資料科學家共用專門知識。

如果您是在 {{site.data.keyword.sparks}} 中使用記事本，則可以將記事本移轉至 Data Science Experience。如需相關資訊，請參閱[移轉記事本文件](/docs/services/AnalyticsforApacheSpark/index-gentopic2.html#migration_to_dsx)。

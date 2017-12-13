---


copyright:
  years: 2016, 2017
lastupdated: "2017-11-15"

---

{:shortdesc: .shortdesc}
{:tip: .tip}
{:new_window: target="_blank"}

# {{site.data.keyword.cloud_notm}} 主控台的運作方式
{: #ui}

{{site.data.keyword.cloud}} 主控台是一個使用者介面，可協助您管理所有 {{site.data.keyword.cloud_notm}} 資源。當您存取[主控台](https://console.bluemix.net){: new_window} ![外部鏈結圖示](../icons/launch-glyph.svg "外部鏈結圖示") 時，可以建立免費帳戶、登入、存取文件、存取型錄、檢視計價資訊、取得支援，或檢查所有 {{site.data.keyword.cloud_notm}} 元件的狀態。登入之後，功能表列會包含「功能表」圖示 ![「功能表」圖示](../icons/icon_hamburger.svg) 及其他鏈結（視帳戶類型而定）。
{: shortdesc}

## 使用主控台
{: #consoleoptions}

如果您是具有 {{site.data.keyword.cloud_notm}} 帳戶的現有使用者，則可以使用「功能表」圖示 ![「功能表」圖示](../icons/icon_hamburger.svg) 來存取儀表板上的所有現有資源。 
  * 使用**型錄**鏈結，以建立新的資源。
  * 使用**文件**鏈結，以存取關於 {{site.data.keyword.cloud_notm}} 的有用資訊。
  * 從**支援**功能表中，您可以存取 {{site.data.keyword.cloud_notm}} 新增功能、「支援中心」、新增和檢視問題單的選項以及「狀態」頁面的相關資訊。
  * 從**管理**功能表中，您可以存取帳戶、計費和用量，以及安全選項。

如果您已鏈結 {{site.data.keyword.cloud_notm}} 及 SoftLayer 帳戶，則選項會與非鏈結帳戶擁有者相同，而且您可以藉由按一下**功能表圖示 ![「功能表」圖示](../icons/icon_hamburger.svg)  > 基礎架構**選項來導覽至客戶入口網站。從這裡，您可以檢視帳戶摘要、訂購儲存空間和裝置，以及管理僅限 VPN 使用者和裝置的存取權。 

## 在儀表板上管理資源
{: #dashboardview}

您可以使用儀表板來檢視及使用 {{site.data.keyword.cloud_notm}} 資源。*資源* 是一個廣泛術語，涵蓋從服務到帳戶的任何項目。如需簡潔的定義，請參閱 [{{site.data.keyword.cloud_notm}} 名詞解釋](/docs/overview/glossary/index.html#glossr)。

### 檢視資源

您可以從儀表板中檢視帳戶中的所有資源。若要自訂視圖，請使用下列選項：

  * 若要檢視特定資源群組中的資源，請從**資源群組**清單中選取資源群組。 
  * 若要檢視特定 Cloud Foundry 組織中的資源，請從 **Cloud Foundry 組織**清單中選取組織。 

然後，根據您選取的項目，依下列選項進行過濾：

  * 地區
  * Cloud Foundry 空間
  
### 使用資源

您可以從儀表板以各種方式來使用資源：

  * 每一個資源都會顯示在它自己的列中，並在列尾端包括「其他動作」圖示 ![「其他動作」圖示](../icons/overflow-menu.svg)。按一下「其他動作」圖示，以啟動、停止、重新命名或刪除資源。 
  * 若要設定資源的認證或連線，請按一下資源的名稱以導覽至資源詳細資料頁面。如需相關資訊，請參閱[新增認證](/docs/services/service_credentials.html)及[管理連線](/docs/manageapps/connecting_apps.html)。 

## 使用型錄
{: #catalogcreate}

若要建立新的資源，請從儀表板中按一下**建立資源**。然後，會將您導向至型錄。當您從型錄選取磚時，可以看到可使用資源的位置。並非型錄中列出的每項資源都可在每個地區使用。 

在您按一下要建立的資源磚之後，即可選取要在其中部署的位置。 

  * 對於 Cloud Foundry 資源，您可以選取特定地區，然後選取要指派服務實例的組織及空間。
  * 對於「{{site.data.keyword.cloud_notm}} 身分及存取管理 (IAM)」所管理的資源，您可以選取要在其中部署的位置。然後，您可以選取要指派服務實例的資源群組。

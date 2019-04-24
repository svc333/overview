---


copyright:
  years: 2015, 2019
lastupdated: "2019-01-29"

keywords: ui, components, using the console

subcollection: overview

---

{:shortdesc: .shortdesc}
{:tip: .tip}
{:new_window: target="_blank"}

# 導覽 {{site.data.keyword.cloud_notm}} 主控台 
{: #ui}

{{site.data.keyword.cloud}} 主控台是一個使用者介面，可協助您管理所有 {{site.data.keyword.cloud_notm}} 資源。當您存取[主控台](https://cloud.ibm.com){: new_window} ![外部鏈結圖示](../icons/launch-glyph.svg "外部鏈結圖示") 時，可以建立免費帳戶、登入、存取文件、存取型錄、檢視定價資訊、取得支援，或檢查 {{site.data.keyword.cloud_notm}} 元件的狀態。登入之後，功能表列會包含「功能表」圖示 ![「功能表」圖示](../icons/icon_hamburger.svg) 及其他鏈結。
{: shortdesc}


## 使用主控台
{: #consoleoptions}

當您登入 {{site.data.keyword.cloud_notm}} 時，您可以檢視的第一頁就是儀表板，它會顯示彙總您帳戶狀態的小組件。接下來，您可以管理資源。請移至「功能表」圖示 ![「功能表」圖示](../icons/icon_hamburger.svg) &gt; **資源清單**，以檢視您帳戶中的所有現有資源。

  * 使用**型錄**鏈結，以建立新的資源。
  * 使用**文件**鏈結，以存取關於 {{site.data.keyword.cloud_notm}} 的有用資訊。
  * 使用**支援**鏈結，以存取「支援中心」。  
  * 您可以從**管理**功能表中存取您的帳戶、計費及用量，以及 Identity and Access Management 選項。
  * 按一下「成本預估器」圖示 ![「成本預估器」圖示](../icons/Estimator.svg)，以開啟成本預估器。
  * 按一下「通知」圖示 ![「通知」圖示](../icons/Notification.svg)，以存取公告及計劃性與非計劃性事件。

## 搜尋資源
{: #search}

您可以從 {{site.data.keyword.cloud_notm}} 主控台的任何位置依名稱或標籤來搜尋資源，以找到您預期在資源清單中看到的資源。在主控台功能表列的搜尋欄位中，鍵入資源或標籤的名稱。

如需相關資訊，請參閱[搜尋資源](/docs/resources?topic=resources-searching-for-resources)。 

## 管理資源清單中的資源
{: #dashboardview}

移至「功能表」圖示 ![「功能表」圖示](../icons/icon_hamburger.svg) &gt; **資源清單**，以存取您的帳戶資源清單。您可以使用資源清單來檢視及使用 {{site.data.keyword.cloud_notm}} 資源和 Cloud Foundry 服務實例。如需不同類型資源的相關資訊，請參閱[何謂資源？](/docs/resources?topic=resources-resource)。

### 檢視資源
您可以從資源清單中檢視帳戶中所有地區的所有資源。若要查看對您很重要的項目，請對每個直欄標頭使用過濾器來過濾您的清單。例如，如果您要檢視及使用特定位置的資源，請展開**位置**過濾器，並從清單選取某個位置。

### 使用資源
您可以用各種方法來使用資源清單中的資源：

  * 每一個資源都會獨自顯示一列，並且在該列的尾端會包含「動作」圖示 ![「其他動作」圖示](../icons/action-menu-icon.svg)。按一下「動作」圖示 ![「其他動作」圖示](../icons/action-menu-icon.svg)，以啟動、停止、重新命名或刪除資源。
  * 若要設定資源的認證或連線，請按一下資源的名稱以導覽至資源詳細資料頁面。然後，選取**服務認證**或**連線**。如需相關資訊，請參閱[新增認證](/docs/resources?topic=resources-service_credentials)和[管理連線](/docs/resources?topic=resources-connect_app)。


## 使用型錄
{: #catalogcreate}

若要建立資源，請按一下資源清單中的**建立**。便會將您導向至型錄。當您從型錄選取一個磚時，可以看到可使用資源的位置。並非型錄中列出的每項資源都可在每個地區使用。

在您按一下要建立的資源磚之後，即可選取要在其中部署的位置。

  * 對於 Cloud Foundry 資源，您可以選取特定地區，然後選取要指派服務實例到哪個組織及空間。
  * 對於 {{site.data.keyword.cloud_notm}} Identity and Access Management (IAM) 所管理的資源，您可以選取要在其中部署的位置。然後，選取要指派服務實例到哪個資源群組。

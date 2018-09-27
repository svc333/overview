---

copyright:
  years: 2016, 2017, 2018
lastupdated: "2018-09-12"

---
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}
{:tip: .tip}

# 探索 {{site.data.keyword.cloud_notm}} 中的開發人員旅程
{: #dev-journey}

身為開發人員，{{site.data.keyword.cloud}} 有一組功能能讓您在幾分鐘內開始建置應用程式。在我們的開發人員儀表板內，您可以：

* 選取使用案例特有且會以各種程式設計語言與架構模式產生可正式作業之入門範本套件應用程式的入門範本
* 查看及管理從入門範本套件自動供應的資源，或手動新增至應用程式的資源
* 取得可攜式應用程式碼，它可讓您部署至各種雲端環境
* 按幾下滑鼠，建立 [DevOps 工具鏈](../services/ContinuousDelivery/index.html#cd_getting_started)
* 使用[指令行介面](/docs/cli/idt/index.html)進行本端開發

為了瞭解 {{site.data.keyword.cloud_notm}} 開發人員體驗如何協助您快速建置高品質的可正式作業應用程式，讓我們更詳細地查看這些元素。

## 開發人員儀表板
{: #dev-dashboards}

{{site.data.keyword.cloud_notm}} 有不同興趣領域（例如 Watson、安全或融資）的開發人員儀表板，或是數位通道（例如行動或 Web 應用程式）。您可以從**功能表圖示** ![功能表圖示](../icons/icon_hamburger.svg) 存取這些儀表板。

每個開發人員儀表板都會提供與儀表板焦點區域相關的入門範本套件，並提供一致的直覺式工作流程，在幾分鐘內就能讓您建立可運作的可正式作業的應用程式。

## 應用程式
{: #app-projects}

應用程式包含程式碼、資料、服務及工具鏈。例如，{{site.data.keyword.cloud_notm}} 行動應用程式包含裝置程式碼以及後端邏輯、資料儲存、分析和安全服務，並已針對持續交付而設定。

![重複使用](images/garage_reuse2.png "開發人員體驗讓您重複使用並避免重複發明")

您可以使用任何 {{site.data.keyword.cloud_notm}} 開發人員儀表板或 {{site.data.keyword.dev_cli_notm}}，來建立及管理應用程式。

## 入門範本套件
{: #starter-kits}

使用入門範本套件，{{site.data.keyword.cloud_notm}} 會以您選擇的語言來組合架構正式作業應用程式，以進行雲端部署。每個入門範本套件都包含語言、架構及特定使用案例的模式，並可讓您重複使用程式碼。

### 入門範本套件與範例有什麼不同？
入門範本套件可正式作業，並聚焦在示範使用運行環境（例如 Node.js 及 Express）的重要模式實作。在某些情況下，入門範本套件提供簡單的使用者體驗，以突顯服務的整合。在其他情況下，入門套件則代表精細使用案例的可自訂實作。

* **Snippet** 是一些經常呈現在 IDE 中的程式碼行。Snippet 可協助開發人員與程式設計語言語法整合，或支援與所定義的 API 整合。
* **示範**通常具有高品質及準確性，並使用某範圍的服務及整合點。它通常需要設定時間，並用來證明商業問題或示範平台特性。它用於評估雲端採用的階段。它的程式碼有時會包括在正式作業程式碼中。
* **範例**是特定特性、功能、服務或使用者行程的小型範例。範例可以在正式作業應用程式中重複使用或併入。這通常是用來顯示技術功能，以及解決技術問題的可能方法。
* **入門範本套件**是可正式作業的模式，可與一組服務整合，以產生可直接部署至 DevOps 管線及 Kubernetes 叢集的可正式作業資產。入門範本套件包含敘述性 meta 資料，可提供足夠的資訊讓使用者瞭解套件為何及用途。它也包含告訴 {{site.data.keyword.cloud_notm}} 所產生內容的指示。預設輸出是可正式作業的，而且可以根據 IBM 最佳作法進行反覆運算，以進行進一步地加強。入門範本套件內容不像示範這麼複雜，也不像 Snippet 或範例那麼簡單。它們是根據開發人員的需求而動態建立。

## 自動佈建的資源
{: #auto-provision}

如果入門範本套件指定必要資源，則 {{site.data.keyword.cloud_notm}} 會在您建立應用程式時自動建立那些資源的實例。請注意，您也可以手動佈建資源，或選取現有的資源實例，以在建立您的應用程式之後新增至該應用程式。您可以在「應用程式詳細資料」視圖中查看與應用程式相關聯的服務實例清單，以及認證（以防您需要它們）。

## 可攜式程式碼
{: #portable-code}

從入門範本套件建立應用程式會自動建立具有一致格式且與運行環境無關的程式碼。您可以將程式碼部署至您選擇的環境（例如 Kubernetes 或 Cloud Foundry），而不進行變更。

### 建立的程式碼為何？
從 {{site.data.keyword.cloud_notm}} 入門範本套件建立的程式碼具有四個基本元件：使用案例邏輯、語言元件、具備服務功能及具備雲端功能。產生這些元件可節省您寶貴的時間，並確保您是使用同級最佳的架構。

* **使用案例邏輯**提供的功能為特定使用案例之核心功能。範例可能是 Watson Conversation 聊天機器人的程式碼，或行動式視覺化識別應用程式的程式碼。
* **語言元件**是您為入門範本套件選取之程式設計語言特有的程式碼元件及檔案。例如，node.js 程式設計師將需要 package.json 檔案進行相依關係管理，而且會自動建立此檔案。
* **具備服務功能**是程式碼，可讓您的應用程式連接至並使用您新增的服務。認證管理、起始設定碼及服務特定 SDK 是具備服務功能項目的範例。
* **具備雲端功能**是程式碼，可讓您的應用程式在 {{site.data.keyword.cloud_notm}} 上執行。例如，可讓您的應用程式在 {{site.data.keyword.cloud_notm}} Kubernetes 叢集上執行的 Helm 圖表。

當您從 {{site.data.keyword.cloud_notm}} 入門範本套件建立應用程式時，您的應用程式會從已經過驗證的架構開始，這些架構也會反映所選取語言的最佳作法。

每個應用程式包括一個 Readme 檔，其中包含應用程式的技術詳細資料，並解釋執行應用程式所需的項目（如果並非現成可用）。
{: tip}

## DevOps 工具鏈
{: #devops}

DevOps 包含用於存取、開發、部署及操作應用程式的程序及工具。DevOps 工具鏈是一組已鏈結的服務，可自動化您的 DevOps 作業。可以使用非常簡單的應用程式手動執行 DevOps，但自動化需求會隨著應用程式複雜性增加而快速增加，而且工具鏈自動化是持續交付的必要項目。

DevOps 工具鏈的核心元件是 GitHub 這類程式碼版本控制儲存庫。其他工具可能包括待辦事項追蹤、交付管線、IDE 及監視服務（例如 [{{site.data.keyword.cloud_notm}}DevOps Insights](../services/DevOpsInsights/index.html#gettingstarted)）。

如果您已使用入門範本套件來建立應用程式，則只需要在「應用程式詳細資料」視圖中按一下**部署至雲端**，即可建立新的工具鏈，以及部署應用程式。會建立具有程式碼儲存庫、問題儲存庫、交付管線及 Web IDE 的工具鏈。

您接著可以在此工具鏈上建置以容納多個團隊，並部署至個別進行開發、測試及正式作業的環境，並建立您應用程式的企業級協同持續交付模型。  

![持續交付](images/garage_continuous_delivery2.png "開發人員體驗會將持續交付設為開發分支")

您也可以在開發人員儀表板的應用程式概觀頁面上按一下**下載**按鈕，快速查看應用程式碼。您的程式碼下載為包含完整應用程式碼結構的 `.zip` 檔案。您可以使用 {{site.data.keyword.dev_cli_notm}} 輕鬆地解壓縮檔案並在本端執行程式碼，或將其新增至程式碼管理儲存庫。

## 指令行介面
{{site.data.keyword.dev_cli_notm}} 可讓您在本端編寫程式碼、建置及執行應用程式。一般模式是透過開發人員儀表板建立應用程式，並使用 {{site.data.keyword.dev_cli_notm}} 在本端開發，然後將更新推送至儲存庫，並合併以啟動部署工具鏈。

## Garage Method 開發
{: #developer_concepts}

查看 [Garage Method](https://www.ibm.com/cloud/garage/)，以瞭解 IBM 如何協助您在組織中開發應用程式。  

![Garage Method 階段概觀](images/garage_phases_overview2.png "Garage Method 階段概觀")*Garage Method 階段概觀*

{{site.data.keyword.cloud_notm}} 可協助您使用 Garage Method 或偏好的任何方法來產生成功的企業級正式作業應用程式。為了更充分地瞭解 {{site.data.keyword.cloud_notm}} 必須提供給開發人員的內容，讓我們快速查看建置現代應用程式所需的技能。

## 開發人員技能
{: #skills}

現在，與之前比起來，使用者預期想要從其應用程式獲得更多。他們想要應用程式從已儲存及即時資料提供深入洞察、一律可用，而且與其個別需求更緊密相符。為了符合這些預期，應用程式建立者需要結合許多不同的技能集。例如，更準確的認知應用程式可能需要數位開發人員、雲端原生開發人員、串流開發人員、資料科學家及 DevOps 專家的貢獻。

 ![開發人員類型](images/developer_skills.png "開發人員關係")

* **數位開發人員**編寫特定數位通道（例如行動 Web、語音及聊天）。數位開發人員通常著重於使用案例，而且直接符合使用者需求作為綜合性體驗。
* **雲端原生開發人員**專門建構及交互連接雲端元件。「微服務」及 Backend for Frontend 作者落在此種類。
* **串流開發人員**著重在處理及取得資料串流的見解。例如，串流開發人員可能會分析及起始送入文字、語音或視訊串流的動作。
* **資料科學家**使用分析及機器學習來產生預測模型。這些模型用於商業度量值，並為應用程式使用者提供深入洞察。
* **DevOps 專家**是解決部署及工具鏈問題的專家。對於簡單的應用程式，通常不需要專門的專家，因為開發團隊成員會與小組管理 DevOps。但對於複雜的企業應用程式，具有許多相依關係的 DevOps 專家對於讓您的正式作業應用程式順暢執行十分重要。

{{site.data.keyword.cloud_notm}} 內建的開發人員功能符合這些技能集，並容許您的團隊使用一個平台來產生、提供、執行及管理應用程式。例如，建立行動應用程式的數位開發人員可能會使用 {{site.data.keyword.cloud_notm}} [行動開發人員儀表板](https://console.bluemix.net/developer/mobile/dashboard)、認知應用程式建置器可能會使用 [Watson 開發人員儀表板](https://console.bluemix.net/developer/watson/dashboard)及 [Watson Studio](https://console.bluemix.net/catalog/services/watson-studio)、串流開發人員可以使用 [IBM Real-Time Analytics](../services/StreamingAnalytics/index.html#gettingstarted)，而 [{{site.data.keyword.cloud_notm}} Continuous Delivery 服務](../services/ContinuousDelivery/index.html#cd_getting_started)會簡化 DevOps 專家的工作。

準備好要開始了嗎？[按一下這裡](../apps/index.html)，立即在 {{site.data.keyword.cloud_notm}} 上建置應用程式！

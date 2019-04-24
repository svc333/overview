---

copyright:
  years: 2016, 2019
lastupdated: "2019-02-19"

keywords: developer tools, building apps, developer entry point, understanding dev journey, get started coding

subcollection: overview

---
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}
{:tip: .tip}

# 探索 {{site.data.keyword.cloud_notm}} 中的開發人員旅程
{: #dev-journey}

身為開發人員，您會決定程式碼的最佳進入點。您可以選擇透過我們所提供的工具來產生程式碼，也可以自帶程式碼，並將它部署至 {{site.data.keyword.cloud}}！
{: shortdesc}

{{site.data.keyword.cloud_notm}} 具有一組功能，可讓您在幾分鐘內開始建置應用程式。{{site.data.keyword.cloud_notm}} 開發人員工具會建立一個您開始著手進行工作所需的高效能基礎。提供了兩個主要工具來進行開發：
 * {{site.data.keyword.cloud_notm}} Web 主控台（開發人員入口網站）
 * {{site.data.keyword.cloud_notm}}指令行介面 (command-line interface, CLI)

利用 {{site.data.keyword.cloud_notm}}，您可以執行下列動作：

* 選取使用案例特定的入門範本套件，並以各種程式設計語言和架構型樣來產生可正式作業的應用程式。
* 使用 [IBM Developer 程式碼型樣 ![外部鏈結圖示](../icons/launch-glyph.svg "外部鏈結圖示")](https://developer.ibm.com/patterns/){:new_window} 快速建立應用程式，並將它部署至 {{site.data.keyword.cloud_notm}}。
* 查看及管理從入門範本套件自動佈建的資源，或您手動新增至應用程式的資源。
* 如果您在現有儲存庫中已有應用程式，則可以使用空白的入門範本套件來建立應用程式記錄，並將它連接至原始碼儲存庫及 DevOps 工具鏈。
* 使用可攜式應用程式碼，您可以部署至各種雲端環境。
* 按幾下滑鼠，建立 [DevOps 工具鏈](/docs/services/ContinuousDelivery?topic=ContinuousDelivery-cd_getting_started)。
* 使用[指令行介面 (CLI)](/docs/cli/reference/ibmcloud?topic=cloud-cli-ibmcloud-cli#ibmcloud-cli) 進行本端開發。
* 瀏覽或搜尋 [{{site.data.keyword.cloud_notm}} 型錄 ![外部鏈結圖示](../icons/launch-glyph.svg "外部鏈結圖示")](https://{DomainName}/catalog){: new_window} 中的應用程式及服務，您可以立即建立並開始使用。

![開發人員體驗概觀](images/dev-journey.png "開發人員體驗概觀")

為了更充分瞭解我們的體驗如何協助您快速建置高品質的可正式作業應用程式，讓我們更詳細地看一下這些元素。

## 開發人員入口網站
{: #dev-portals}

{{site.data.keyword.cloud_notm}} 有不同興趣領域（例如 Watson、安全、財務）或數位頻道（例如行動或 Web 應用程式）的開發人員入口網站。您可以從**功能表**圖示 ![「功能表」圖示](../icons/icon_hamburger.svg) 存取這些入口網站。

每一個開發人員入口網站都提供與入口網站焦點領域相關的入門範本套件。入口網站提供一致的直覺式工作流程，可以在幾分鐘內建立可正式作業的工作應用程式。

## 應用程式
{: #app-projects}

應用程式包含程式碼、資料、服務及工具鏈。例如，{{site.data.keyword.cloud_notm}} 行動應用程式包含裝置程式碼，以及後端邏輯、資料儲存、分析和安全服務，並設定以進行持續交付。

![重複使用](images/garage_reuse2.png "使用 Developer Experience，您可以重複使用並避免重複發明")

您可以使用任何 {{site.data.keyword.cloud_notm}} 開發人員入口網站或 {{site.data.keyword.dev_cli_notm}} 來建立及管理應用程式。

您可以直接建立簡單的空白應用程式，或使用我們的入門範本套件來建立更複雜的應用程式。如果您選擇建立空白應用程式而不借助入門範本套件，則可以從 [{{site.data.keyword.cloud_notm}} 儀表板 ![外部鏈結圖示](../icons/launch-glyph.svg "外部鏈結圖示")](https://{DomainName}){: new_window} 進行，而不必造訪入口網站！

您可以使用程式碼型樣來快速建立應用程式，並將它部署至 {{site.data.keyword.cloud_notm}}。從 [IBM Developer 網站 ![外部鏈結圖示](../icons/launch-glyph.svg "外部鏈結圖示")](https://developer.ibm.com/patterns/){:new_window}，選擇程式碼型樣。您可以在 GitHub 檢視程式碼，或在 {{site.data.keyword.cloud_notm}} 建立並建置應用程式，在這裡您可以使用 DevOps 工具鏈自動部署應用程式。


## 入門範本套件
{: #starter-kits}

使用入門範本套件時，您的體驗應該容易使用且可自訂。入門範本套件是以您選擇的語言來組合架構正式作業應用程式，以進行雲端部署。每個入門範本套件都包含語言、架構和用於特定使用案例及重複使用程式碼的型樣。

如果入門範本套件需要特定資源，沒有問題。{{site.data.keyword.cloud_notm}} 會使用自動佈建的資源，在您建立應用程式時，自動建立那些資源的實例。您可以從開發人員入口網站或指令行介面存取入門範本套件，以取得與您的焦點領域和工作流程相關的指示！

### 入門範本套件與範例有什麼不同？
入門範本套件可正式作業，並聚焦在使用一種運行環境（例如 Node.js 及 Express）來示範重要的型樣實作。在某些情況下，入門範本套件提供簡單的使用者體驗，以突顯服務的整合。在其他情況下，入門範本套件代表了精密使用案例的可自訂實作。

* Snippet 是幾行經常呈現在 IDE 中的程式碼。Snippet 可協助開發人員與程式設計語言語法整合，或支援與已定義好的 API 整合。
* 示範通常具有高品質及高準確性，並使用某個範圍的服務及整合點。它通常需要設定時間，並用來證明商業問題或示範平台特性。您可以用它來評估雲端採用的各個階段。有時候它是內含在正式作業程式碼中的程式碼。
* 範例是特定特性、功能、服務或使用者旅程的小型範例。您可以重複使用範例，或將它包含在正式作業應用程式中。它通常用來顯示技術功能，以及解決技術問題的可能方法。
* 入門範本套件是可正式作業的型樣，可以和一組服務整合，以產生可直接部署至 DevOps 管線及 Kubernetes 叢集的可正式作業資產。入門範本套件包含敘述性的 meta 資料，可提供足夠的資訊讓使用者瞭解套件為何及其用途。它也包含告知 {{site.data.keyword.cloud_notm}} 應產生內容的指示。現成的輸出即可正式作業，而且可以根據 IBM 最佳作法反覆地執行，以便做進一步的加強。入門範本套件內容不像示範這麼複雜，也不像 Snippet 或範例那麼簡單。它們是根據開發人員的需求而動態建立。

## 自動佈建的資源
{: #auto-provision}

如果入門範本套件指定必要資源，則 {{site.data.keyword.cloud_notm}} 會在您建立應用程式時自動建立那些資源的實例。您也可以手動佈建資源，或選取現有的資源實例，以在建立應用程式之後將這些資源新增至該應用程式。您可以在「應用程式詳細資料」視圖中看到與應用程式相關聯的服務實例清單，以及認證（如果您需要它們的話）。

## 可攜式程式碼
{: #portable-code}

從入門範本套件建立應用程式，會為您自動建立具有一致格式且不依賴運行環境的程式碼。您可以將程式碼部署至您選擇的環境（例如 Kubernetes 或 Cloud Foundry），而不必進行變更。

您可以在應用程式的「應用程式詳細資料」頁面上按一下**下載程式碼**，以快速查看應用程式碼。您的程式碼會下載為包含完整應用程式碼結構的 `.zip` 檔案。您可以使用 {{site.data.keyword.dev_cli_notm}} 輕鬆地在本端解壓縮檔案並執行程式碼，或將其新增至程式碼管理儲存庫。

### 會建立什麼程式碼？
{: #what-code}

當您直接建立應用程式，或借助入門範本套件建立應用程式時，應用程式會包含可攜式程式碼。可攜式程式碼包含適用於多個雲端環境的雲端啟用程式碼。接著，您便可以產生四個基礎領域的程式碼：
* 遵循特定語言最佳作法的程式碼
* 可讓應用程式在雲端上執行的程式碼
* 已起始設定以便連接至雲端服務的程式碼
* 某個使用案例特有的程式碼

產生這些元件可為您節省寶貴的時間，並確保您使用同級最佳的架構。

* 使用案例邏輯會為特定使用案例的核心功能提供適用的功能。範例可能是 Watson Conversation 聊天機器人的程式碼，或行動視覺辨識應用程式的程式碼。
* 語言元件是您為入門範本套件選取之程式設計語言特有的程式碼元件及檔案。例如，node.js 程式設計師需要 package.json 檔案以便進行相依關係管理，而這個檔案會自動為您建立。
* 服務啟用是讓您的應用程式能連接至所新增服務並加以使用的程式碼。認證管理、起始設定程式碼及服務特定 SDK，全都是服務啟用項目的範例。
* 雲端啟用是讓您的應用程式能在 {{site.data.keyword.cloud_notm}} 上執行的程式碼。例如，可讓您的應用程式在 {{site.data.keyword.cloud_notm}} Kubernetes 叢集上執行的 Helm 圖表。

當您從 {{site.data.keyword.cloud_notm}} 入門範本套件建立應用程式時，您的應用程式會從已經過驗證的架構開始，此架構也會反映所選語言的最佳作法。

每個應用程式包括一個 Readme 檔，其中包含應用程式的技術詳細資料，並解釋執行應用程式所需的項目（如果現成狀態無法執行的話）。
{: tip}

## 自帶程式碼，並將它部署至 {{site.data.keyword.cloud_notm}}
{: byoc}

如果您在現有儲存庫中已有應用程式，則可以使用空白的入門範本套件在 {{site.data.keyword.cloud_notm}} 中建立應用程式記錄，並將該應用程式連接至原始碼儲存庫及 DevOps 工具鏈。

您可以從 {{site.data.keyword.cloud_notm}} 儀表板或從任何空白入門範本套件開始。在您命名應用程式並選取資源群組之後，請選取[**自帶程式碼**](/docs/apps/tutorials?topic=creating-apps-tutorial-byoc#tutorial-byoc)起始點、提供包含程式碼的 Git 儲存庫 URL，然後按一下**建立**。

您可以連接現有的 DevOps 工具鏈或建立一個工具鏈，並持續將您的應用程式交付至所選擇的環境，例如 Kubernetes 或 Cloud Foundry。


## DevOps 工具鏈
{: #devops}

DevOps 工具鏈包含用於存取、開發、部署及操作應用程式的程序及工具。DevOps 工具鏈是一組已鏈結的服務，可自動執行您的 DevOps 作業。您可以使用簡單的應用程式手動執行 DevOps，但自動化需求會隨著應用程式複雜性增加而快速增加，因此工具鏈自動化成為持續交付的必備項目。

DevOps 工具鏈的核心元件是 GitHub 這類的程式碼版本控制儲存庫。其他工具可能包括待辦事項追蹤、交付管線、IDE 及監視服務（例如 [{{site.data.keyword.cloud_notm}} {{site.data.keyword.DRA_short}}](/docs/services/DevOpsInsights?topic=DevOpsInsights-getting-started#getting-started)）。

如果您使用入門範本套件來建立應用程式，則可建立新的工具鏈，並且只要在**應用程詳細資料**頁面上按一下**部署至雲端**，即可部署應用程式。會建立具有程式碼儲存庫、問題儲存庫、交付管線及 Web IDE 的工具鏈。

然後，您可以在此工具鏈上建置，以容納多個團隊，並將其部署至開發、測試及正式作業用的不同環境。您會為您的應用程式建立企業級協同作業持續交付模型。

![持續交付](images/garage_continuous_delivery2.png "開發人員體驗會將持續交付設定進入開發分支")


## CLI
{: cli}

使用指令行介面 (CLI)，在本端撰寫應用程式程式碼、建置及執行應用程式。常見的作業模式是從 {{site.data.keyword.cloud_notm}} 主控台的開發人員入口網站建立應用程式、使用開發人員工具在本端開發，然後將更新推送至儲存庫，並合併以啟動部署工具鏈。

## Garage Method 開發
{: #developer_concepts}

如果您要尋找一個可以實驗大型構想和新興技術的地方，請務必參閱 [Garage Method](https://www.ibm.com/cloud/garage/){: new_window} ![外部鏈結圖示](../icons/launch-glyph.svg "外部鏈結圖示") 部署。您可以瞭解 IBM 如何協助您在組織中開發應用程式。

![Garage Method 階段概觀](images/garage_phases_overview2.png "Garage Method 階段概觀") 

{{site.data.keyword.cloud_notm}} 可協助您使用 Garage Method 或偏好的任何方法來產生成功的企業級正式作業應用程式。為了更充分瞭解 {{site.data.keyword.cloud_notm}} 為開發人員提供的內容，讓我們很快地看一下建置現代應用程式所需的技能。

## 開發人員技能
{: #skills}

使用者對應用程式的期望更勝以往。他們想要應用程式從已儲存及即時資料提供深入洞察、隨時可用，並且更緊密貼近他們的個人需求。為了符合這些期望，IBM Cloud 中的開發人員功能會以特定技術集為準，讓您的團隊能使用一個平台來產生、交付、執行及管理應用程式。例如，精密的認知應用程式可能需要數位開發人員、雲端原生開發人員、串流開發人員、資料科學家及 DevOps 專家等人的貢獻。

 ![開發人員類型](images/developer_skills.png "開發人員關係")

* 數位開發人員針對特定數位頻道（例如行動 Web、語音及會談）而編寫。數位開發人員通常著重於使用案例，並且直接符合使用者需求作為綜合性體驗。
* 雲端原生開發人員專門建構及交互連接雲端元件。微服務及 Backend for Frontend 的作者便屬於這個種類。
* 串流開發人員著重在處理資料串流並從中取得見解。例如，串流開發人員可能會分析送入的文字、語音或視訊串流，並對其起始動作。
* 資料科學家使用分析及機器學習來產生預測模型。這些模型用於商業度量值，並為應用程式使用者提供深入見解。
* DevOps 專家是解決部署及工具鏈問題方面的專家。對於簡單的應用程式，通常不需要專門的專家，因為開發團隊成員會與小組一起管理 DevOps。但對於具有許多相依關係的複雜企業應用程式，DevOps 專家對於讓您的正式作業應用程式順暢執行而言就十分重要。

{{site.data.keyword.cloud_notm}} 內建的開發人員功能會以這些技術集為準，並容許您的團隊使用一個平台來產生、提供、執行及管理應用程式。例如，建立行動應用程式的數位開發人員可能使用 {{site.data.keyword.cloud_notm}} [Mobile 開發人員入口網站](https://{DomainName}/developer/mobile/dashboard){: new_window} ![外部鏈結圖示](../icons/launch-glyph.svg "外部鏈結圖示")。認知應用程式建置者可能使用 [Watson 開發人員入口網站](https://{DomainName}/developer/watson/dashboard){: new_window} ![外部鏈結圖示](../icons/launch-glyph.svg "外部鏈結圖示") 以及 [Watson Studio](https://{DomainName}/catalog/services/watson-studio){: new_window} ![外部鏈結圖示](../icons/launch-glyph.svg "外部鏈結圖示")。串流開發人員可以使用 [IBM Real-Time Analytics](/docs/services/StreamingAnalytics/index.html)。[{{site.data.keyword.cloud_notm}} Continuous Delivery 服務](/docs/services/ContinuousDelivery?topic=ContinuousDelivery-cd_getting_started)簡化了 DevOps 專家的工作。

[準備好要開始建置高品質、可正式作業的應用程式了嗎？](/docs/apps/tutorials?topic=creating-apps-tutorial-getting-started#tutorial-getting-started)

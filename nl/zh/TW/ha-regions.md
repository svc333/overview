---

copyright:

  years: 2018

lastupdated: "2018-11-01"

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:pre: .pre}
{:tip: .tip}

# 資源部署的位置 
{: #ov_intro_reg}

您可以使用應用程式管理的相同 {{site.data.keyword.cloud_notm}} 基礎架構，以及計費的相同用量詳細資料視圖，在不同的位置中建立應用程式和服務實例。您可以將應用程式部署至最接近客戶的位置，以縮短應用程式的延遲時間。 

為了解決安全問題，您也可以選取要保留應用程式資料的位置。當您在多個位置建置應用程式時，如果其中一個位置變成無法使用，則位於其他位置的應用程式會繼續執行。您所使用之每個位置的資源額度都相同。如需平台資源及其所在位置的相關資訊，請參閱[服務可用性](/docs/resources/service_region.html)。

主控台的廣域負載平衡可確保如果離您最近的地理位置關閉，主控台會顯示下一個最近位置的資訊。如此一來，您隨時都可以存取主控台，而不需要採取任何動作來存取所需的資訊。

依預設，您可以從儀表板檢視所有位置的所有資源。如果您要檢視及使用特定位置的資源，請展開**位置**功能表，並從清單中選取某個位置。 

您也可以使用指令行介面來連接至所要使用的 {{site.data.keyword.cloud_notm}} 位置，方法是使用 `ibmcloud api` 指令，並指定位置的 API 端點。例如，輸入下列指令以連接至 {{site.data.keyword.cloud_notm}} 倫敦：

```
ibmcloud api https://api.eu-gb.bluemix.net
```

將唯一字首指派給每個位置。{{site.data.keyword.cloud_notm}} 提供下列位置及位置字首。

| **位置** | **API 端點** |
|-----------------|-------------------|
| 達拉斯 | api.us-south.bluemix.net |
| 雪梨 | api.au-syd.bluemix.net |
| 法蘭克福 | api.eu-de.bluemix.net |
| 倫敦 | api.eu-gb.bluemix.net |
| 華盛頓特區 | api.us-east.bluemix.net |
| 東京 | api.jp-tok.bluemix.net |
{: caption="表 1. {{site.data.keyword.cloud_notm}} 位置清單" caption-side="top"}

當您部署基礎架構資源時，有更多關於內容所在位置的選擇。您可以選取一個位置，或者可以從 {{site.data.keyword.Bluemix_notm}} 的資料中心清單中進行選取。如需相關資訊，請參閱 [{{site.data.keyword.cloud_notm}} 資料中心](data-centers.html)。

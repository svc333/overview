---

copyright:

  years: 2017

lastupdated: "2017-11-17"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:tip: .tip}

# 雲端資源名稱
{: #crn}

「雲端資源名稱 (CRN)」可唯一識別 {{site.data.keyword.Bluemix_notm}} 資源。CRN 用來以明確且保證為廣域唯一的方式來指定資源（例如在雲端型錄中所列出的「{{site.data.keyword.Bluemix_notm}} 身分及存取管理 (IAM)」原則及服務）。

CRN 是由階層式識別資源、其位置及其所屬服務的「區段」連結所組成。區段定界字元設為 ':'（亦即，冒號字元）。所有 CRN 的開頭都是區段 ID 'crn'。


## CRN 格式
{: #format}

CRN 的基本標準格式為：

**crn:[version](#version):[cname](#cname):[ctype](#ctype):[service-name](#service-name):[location](#location):[scope](#scope):[service-instance](#service-instance):[resource-type:resource](#resource-type)**


## version
{: #version}

`version` 區段識別 CRN 格式的版本。目前唯一有效的 version 區段值是 **v1**。


## cname
{: #cname}

`cname` 區段識別雲端實例，而且是可唯一識別包含資源之雲端實例的英數 ID。`cname` 可有效地識別擁有所識別資源的獨立控制平面。{{site.data.keyword.Bluemix_notm}} 使用者的 `cname` 必須是 `bluemix`。


## ctype
{: #ctype}

`ctype` 區段識別指定的 `cname` 所代表的雲端實例類型。

>有效值：
  - public - 所有可從公用型錄取得的服務。
  - dedicated - 僅適用於現行 {{site.data.keyword.Bluemix_notm}} 專用環境。
  - local - 部署在自己的環境本端的所有服務。


## service-name
{: #service-name}

`service-name` 區段唯一識別雲端所提供的功能（服務、元件、產品）。功能可以是使用者提供的服務（例如 {{site.data.keyword.Bluemix_notm}} 型錄中所列出的服務）或 {{site.data.keyword.Bluemix_notm}} 功能的重要內部架構元件。

`service-name` 指出資源所屬的服務，而 {{site.data.keyword.Bluemix_notm}} 會強制服務名稱的廣域唯一性。`service-name` 必須是英數、小寫、沒有空格，或 '-' 以外的特殊字元。

對於登錄至「{{site.data.keyword.Bluemix_notm}} 型錄」的服務，`service-name` 必須對應至登錄至「{{site.data.keyword.Bluemix_notm}} 廣域型錄」服務的其中一個服務。它是「{{site.data.keyword.Bluemix_notm}} 廣域型錄」服務 API `GET https://resource-catalog.bluemix.net/api/v1/{id}` 針對對應資源實例所傳回的 `name` 內容，或指令行介面 `bx service offerings` 在直欄 `service` 中顯示的 `service-name`。


## 位置 (location)
{: #location}

資源所在的雲端地理位置/地區/區域/資料中心。

`location` 必須是下列其中一個值：

### 廣域

 * `global`

### 地理位置

 * `us`
 * `eu`
 * `cn`
 * `ap`

### 地區

 * `us-south`
 * `au-syd`
 * `eu-gb`
 * `eu-de`

### 資料中心


| | | | | |
|---|---|---|---|---|
| AMS01  | AMS03  | CHE01  | DAL01  |  DAL05  |
| DAL06  | DAL07  | DAL09  | DAL10  |  DAL12  |
| DAL13  | FRA02  | HKG02  | HOU02  |  LON02  |
| MEL01  | MEX01  | MIL01  | MON01  |  OSL01  |
| PAR01  | SJC01  | SJC03  | SAO01  |  SEA01  |
| SEO01  | SNG01  | SYD01  | TOK02  |  TOR01  |
| WDC01  | WDC04  | WDC06  | WDC07  |
{: caption="表 1. 有效的「資料中心」值" caption-side="top"}

部分資源不需要地區（它們可視為 `global`）。在此情況下，`region` 區段設為 `global`。
{: tip}


## 範圍 (scope)
{: #scope}

`scope` 區段識別資源的包含關係或擁有者。部分資源不需要擁有者（它們可視為 `global`）。在此情況下，`scope` 區段是空的（空白字串）。

`scope` 區段的值必須格式化為 `{scopePrefix}`/`{id}`。`scopePrefix` 代表用來識別擁有者或包含關係的格式。`id` 會以 `scopePrefix` 特有的格式來代表擁有者或包含關係的身分。

| 範圍類型| 範圍字首| 用法| 範例|
| --- | --- | --- | --- |
| 帳戶| a/`{account id}` | 已用來建立資源的帳戶。| a/292558 |
| 組織| o/`{org guid}` | 已獲指派資源的「{{site.data.keyword.Bluemix_notm}} 組織」。| o/4716e2d1-35b7-431f-891a-b552bf0b3c66 |
| 空間| s/`{space guid}` | 已獲指派資源的「{{site.data.keyword.Bluemix_notm}} 空間」。| s/48b3cdcd-e804-4398-9032-73065863ad7c |
{: caption="表 2. `scope` 用法" caption-side="top"}

`account id` 必須是 IBM 帳戶 ID（{{site.data.keyword.Bluemix_notm}} 及 Softlayer 的已鏈結帳戶）。


## service-instance
{: #service-instance}

`service-instance` 區段可唯一識別服務實例。`service-instance` 區段的格式會因服務而改變。每一個服務都必須將其 `service_instance` 的格式記載為其服務 meta 資料的一部分。部分服務沒有實例，因為該實例是廣域的，在此情況下，`service-instance` 欄位會空白。

`service-instance` 必須是英數、小寫、沒有空格，或 '-' 及 '/' 以外的特殊字元。

例如，追蹤及計劃工作項目的 DevOps 工具可以具有簡單 `GUID` 實例 ID ("1234-5678-9012-3456")，其中自動調整群組服務的原則元件可以使用階層式命名慣例，並且具有下列項目的 `service-id` 區段：

>`c7a27f55-d35e-4153-b044-8ca9155fc467/my-test-asg1/my-scaleout-policy`


## resource-type、resource
{: #resource-type}

`resource-type` 及 `resource` 區段的值會因服務而改變。需要有服務，才能將其支援的 `resource types` 以及 `resource` 的格式記載為其服務 meta 資料的一部分。

例如，Object Storage 服務中客戶收據容器內的映像檔的 `resource-type` 可以是 `object`，而 `resource_value` 可以是 `CustomerReceipts/clientdinner.png`。 

`resource-type` 必須是英數、小寫、沒有空格，或 '-' 以外的特殊字元。服務可以決定 `resource-type` 是選用的，在此情況下，它會保留空白。


## CRN 範例
{: #crn_examples}

下列是 CRN 範例清單。

| 範例| 值|
| --- | --- |
| 容器| `crn:v1:bluemix:public:containers-kubernetes:us-south:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:8042b2a8af6a4a5cbf6dbe09e07311d2:worker:kube-hou02-pa8042b2a8af6a4a5cbf6dbe09e07311d2-w1:`|
| 資源群組| `crn:v1:bluemix:public:resource-controller: global:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:resource-group:59bcbfa6ea2f006b4ed7094c1a08dcdd` |
| 服務實例| `crn:v1:bluemix:public:cloud-object-storage:global:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:1a0ec336-f391-4091-a6fb-5e084a4c56f4::` |
| 儲存區| `crn:v1:bluemix:public:cloud-object-storage:global:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:1a0ec336-f391-4091-a6fb-5e084a4c56f4:bucket:mybucket` |
{: caption="表 3. CRN 範例" caption-side="top"}



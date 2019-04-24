---

copyright:

  years: 2017, 2019

lastupdated: "2019-02-21"

keywords: crn, cloud resource name

subcollection: overview

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:tip: .tip}

# 云资源名称
{: #crn}

云资源名称 (CRN) 用于唯一地标识 {{site.data.keyword.Bluemix_notm}} 资源。CRN 用于以明确且保证全局唯一（例如，在云目录中列出的 {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) 策略和服务中）的方式指定资源。

CRN 由分层标识资源、其位置和所属服务的“分段”并置构成。分段定界符设置为“:”（冒号字符）。所有 CRN 都以分段标识 `crn` 开头。


## CRN 格式
{: #format-crn}

CRN 的基本规范格式为：

`   crn:version:cname:ctype:service-name:location:scope:service-instance:resource-type:resource
   `


## version
{: #version-crn}

`version` 分段标识 CRN 格式的版本。目前，唯一有效的 version 分段值为 `v1`。


## cname
{: #cname-crn}

`cname` 分段标识云实例，这是字母数字标识，用于唯一标识包含资源的云实例。`cname` 有效地标识拥有所标识资源的独立控制平面。对于 {{site.data.keyword.Bluemix_notm}} 用户，`cname` 分段的值必须为 `bluemix`。


## ctype
{: #ctype-crn}

`ctype` 分段用于标识由指定 `cname` 分段表示的云实例的类型。

 有效值为：
  - `public`：公共目录中提供的所有服务
  - `dedicated`：仅适用于当前 {{site.data.keyword.Bluemix_notm}} Dedicated 环境
  - `local`：在您自己的环境中本地部署的所有服务


## service-name
{: #service-name-crn}

`service-name` 分段唯一标识由云提供的功能（服务、组件和产品）。该功能可以是用户提供的服务，例如 {{site.data.keyword.Bluemix_notm}}“目录”中列出的服务，或对于 {{site.data.keyword.Bluemix_notm}} 功能很关键的内部体系结构组件。

`service-name` 分段指示资源所属的服务，并且 {{site.data.keyword.Bluemix_notm}} 强制实施服务名称的全局唯一性。`service-name` 分段必须为字母数字、小写，并且不得包含空格或除“-”之外的特殊字符。

对于注册到 {{site.data.keyword.Bluemix_notm}}“目录”的服务，`service-name` 分段必须对应于注册到 {{site.data.keyword.Bluemix_notm}}“全局目录”服务的其中一个服务。这是 {{site.data.keyword.Bluemix_notm}}“全局目录”服务 API `GET https://globalcatalog.cloud.ibm.com/api/v1/{id}` 为对应的资源实例返回的 `name` 属性，或者是命令行界面 `ibmcloud service offerings` 在 `service` 列中显示的 `service-name` 值。


## location
{: #location-crn}

资源所在的云地理位置/区域/专区/数据中心。

`location` 分段必须是以下其中一个值：

### 全局
{: #global-crn}

 * `global`

### 地理位置
{: #geos-crn}

 * `us`
 * `eu`
 * `cn`
 * `ap`

### 区域
{: #regions-crn}

 * `us-south`
 * `us-east`
 * `au-syd`
 * `eu-gb`
 * `eu-de`
 * ` jp-tok `

### 数据中心
{: #dc-crn}


| | | | | |
|---|---|---|---|---|
|AMS01  |AMS03  |CHE01  |DAL01  |DAL05  |
|DAL06  |DAL07  |DAL09  |DAL10  |DAL12  |
|DAL13  |FRA02  |HKG02  |HOU02  |LON02  |
|MEL01  |MEX01  |MIL01  |MON01  |OSL01  |
|PAR01  |SJC01  |SJC03  |SAO01  |SEA01  |
|SEO01  |SNG01  |SYD01  |TOK02  |TOR01  |
|WDC01  |WDC04  |WDC06  |WDC07  |
{: caption="表 1. 有效的数据中心值" caption-side="top"}

某些资源不需要区域，因为这些资源可以视为 `global`。在这种情况下，`region` 分段设置为 `global`。
{: tip}


## 作用域
{: #scope-crn}

`scope` 分段标识资源的包含范围或所有者。某些资源不需要所有者（这些资源可以视为 `global`）。在这种情况下，`scope` 分段为空（空字符串）。

`scope` 分段值的格式必须设置为 `{scopePrefix}`/`{id}`。`scopePrefix` 表示用于标识所有者或包含范围的格式。`id` 表示所有者或包含范围的身份，其格式特定于 `scopePrefix`。

|作用域类型|作用域前缀|用法|示例|
| --- | --- | --- | --- |
|帐户|a/`{account id}`|已在其中创建资源的帐户。|`a/292558`|
|组织|o/`{org guid}`|分配有该资源的 {{site.data.keyword.Bluemix_notm}} 组织。|`o/4716e2d1-35b7-431f-891a-b552bf0b3c66`|
|空间|s/`{space guid}`|分配有该资源的 {{site.data.keyword.Bluemix_notm}} 空间。|`s/48b3cdcd-e804-4398-9032-73065863ad7c`|
{: caption="表 2. 作用域用法" caption-side="top"}



## service-instance
{: #service-instance-crn}

`service-instance` 分段唯一标识服务实例。`service-instance` 分段的格式因服务而异。每个服务都必须将其 `service_instance` 分段的格式记录为其服务元数据的一部分。某些服务没有实例，因为实例是全局的，在这种情况下，`service-instance` 字段将为空。

`service-instance` 必须为字母数字、小写，并且不得包含空格或除“-”和“/”之外的特殊字符。

例如，用于跟踪和规划工作项的 DevOps 工具可以有简单的 `GUID` 实例标识（“1234-5678-9012-3456”），其中自动扩展组服务的策略组件可以使用分层命名约定，并且其 `service-id` 分段如下：

>`c7a27f55-d35e-4153-b044-8ca9155fc467/my-test-asg1/my-scaleout-policy`

您还可以使用以下 CLI 命令从 {{site.data.keyword.Bluemix_notm}} 资源中获取 CRN：
```
ibmcloud resource service-instance
```
{: codeblock}

## resource-type 和 resource
{: #resource-type-crn}

`resource-type` 和 `resource` 分段的值因服务而异。服务需要将其支持的 `resource types` 分段以及 `resource` 分段的格式记录为其服务元数据的一部分。

例如，Object Storage 服务中客户接收容器中的映像的 `resource-type` 分段可以为 `object`，`resource` 值可以为 `CustomerReceipts/clientinner.png`。

`resource-type` 分段必须为字母数字、小写，并且不得包含空格或除“-”之外的特殊字符。服务可以决定 `resource-type` 分段是可选的，在这种情况下，它将保留为空。


## CRN 示例
{: #crn_examples}

下面是 CRN 示例的列表。

|示例|值|
| --- | --- |
| Kubernetes 工作程序| `crn:v1:bluemix:public:containers-kubernetes:us-south:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:8042b2a8af6a4a5cbf6dbe09e07311d2:worker:kube-hou02-pa8042b2a8af6a4a5cbf6dbe09e07311d2-w1` |
|资源组|`crn:v1:bluemix:public:resource-controller: global:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:resource-group:59bcbfa6ea2f006b4ed7094c1a08dcdd` |
|服务实例|`crn:v1:bluemix:public:cloud-object-storage:global:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:1a0ec336-f391-4091-a6fb-5e084a4c56f4::` |
|存储区|`crn:v1:bluemix:public:cloud-object-storage:global:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:1a0ec336-f391-4091-a6fb-5e084a4c56f4:bucket:mybucket` |
{: caption="表 3. CRN 示例" caption-side="top"}

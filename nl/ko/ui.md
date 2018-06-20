---


copyright:
  years: 2016, 2018
lastupdated: "2018-05-23"

---

{:shortdesc: .shortdesc}
{:tip: .tip}
{:new_window: target="_blank"}

# {{site.data.keyword.cloud_notm}} 콘솔의 작동 방식
{: #ui}

{{site.data.keyword.cloud}} 콘솔은 모든 {{site.data.keyword.cloud_notm}} 리소스를 관리하는 데 도움이 되는 사용자 인터페이스입니다. [콘솔](https://console.bluemix.net){: new_window} ![외부 링크 아이콘](../icons/launch-glyph.svg "외부 링크 아이콘")에 액세스하면 무료 계정 작성, 로그인, 문서에 액세스, 카탈로그에 액세스, 가격 책정 정보 보기, 지원 받기 또는 모든 {{site.data.keyword.cloud_notm}} 컴포넌트의 상태 확인 등을 수행할 수 있습니다. 로그인하면 사용자의 계정 유형에 따라 메뉴 표시줄에 메뉴 아이콘 ![메뉴 아이콘](../icons/icon_hamburger.svg) 및 추가 링크가 포함되어 있습니다.
{: shortdesc}

## 콘솔 사용
{: #consoleoptions}

{{site.data.keyword.cloud_notm}} 계정이 있는 기존 사용자인 경우, 메뉴 아이콘 ![메뉴 아이콘](../icons/icon_hamburger.svg)을 사용하여 대시보드에서 기존의 모든 리소스에 액세스할 수 있습니다.
  * **카탈로그** 링크를 사용하여 새 리소스를 작성할 수 있습니다.
  * **문서** 링크를 사용하여 {{site.data.keyword.cloud_notm}}에 대한 유용한 정보에 액세스할 수 있습니다.
  * **지원** 메뉴에서 {{site.data.keyword.cloud_notm}}의 새로운 기능, 지원 센터, 티켓 추가 및 보기를 위한 옵션, 상태 페이지에 대한 정보에 액세스할 수 있습니다.
  * **관리** 메뉴에서 계정, 청구 및 사용량, 보안 옵션에 액세스할 수 있습니다.

{{site.data.keyword.cloud_notm}} 및 SoftLayer 계정을 연결한 경우 연결되지 않은 계정 소유자와 동일한 옵션을 보유합니다. 또한 **메뉴 아이콘 ![메뉴 아이콘](../icons/icon_hamburger.svg)  > 인프라** 옵션을 선택하여 고객 포털로 이동할 수 있습니다. 여기에서 계정 요약을 보고 스토리지와 디바이스를 주문하며 VPN 전용 사용자와 디바이스에 대한 액세스를 관리할 수 있습니다.

## 대시보드에서 리소스 관리
{: #dashboardview}

대시보드를 사용하여 {{site.data.keyword.cloud_notm}} 리소스 및 Cloud Foundry 서비스 인스턴스를 보고 관련 작업을 수행할 수 있습니다. 리소스에 대한 자세한 정보는 [리소스 개념](/docs/resources/acct_resources.html#resource)을 참조하십시오.

### 리소스 보기

대시보드에서 계정의 모든 리소스를 볼 수 있습니다. 보기를 사용자 정의하려면 다음 옵션을 사용하십시오.

  * 특정 리소스 그룹의 리소스를 보려면 **리소스 그룹** 목록에서 리소스 그룹을 선택하십시오.
  * 특정 Cloud Foundry 조직의 리소스를 보려면 **Cloud Foundry 조직** 목록에서 조직을 선택하십시오.

그리고 선택하는 항목에 따라 다음 옵션으로 필터링할 수 있습니다.

  * 지역
  * Cloud Foundry 영역

### 리소스 관련 작업

대시보드에서 다양한 방법으로 리소스 관련 작업을 수행할 수 있습니다.

  * 각각의 리소스는 자체 행에 표시되며 추가 조치 아이콘 ![추가 조치 아이콘](../icons/overflow-menu.svg)은 행의 끝에 포함됩니다. 추가 조치 아이콘을 클릭하면 리소스를 시작, 중지하고 해당 이름을 바꾸거나 이를 삭제할 수 있습니다.
  * 리소스에 대한 신임 정보 또는 연결을 설정하려면 리소스의 이름을 클릭하여 리소스 세부사항 페이지로 이동하십시오. 자세한 정보는 [새 신임 정보 추가](/docs/resources/service_credentials.html) 및 [연결 관리](/docs/resources/connecting_apps.html#connect_app)를 참조하십시오.

## 카탈로그에서 작업
{: #catalogcreate}

새 리소스를 작성하려면 대시보드에서 **리소스 작성**을 클릭하십시오. 그러면 카탈로그로 이동됩니다. 카탈로그에서 타일을 선택하면 어디에서 리소스가 사용 가능한지 볼 수 있습니다. 카탈로그에 나열된 모든 리소스를 모든 지역에서 사용할 수 있는 것은 아닙니다.

작성할 리소스에 대한 타일을 클릭한 후에는 배치되는 위치를 선택할 수 있습니다.

  * Cloud Foundry 리소스의 경우, 특정 지역을 선택한 후에 지정될 서비스 인스턴스에 대한 조직과 지역을 선택할 수 있습니다.
  * {{site.data.keyword.cloud_notm}} Identity and Access Management(IAM)에서 관리하는 리소스의 경우, 배치될 위치를 선택하십시오. 그리고 서비스 인스턴스가 지정될 리소스 그룹을 선택하십시오.

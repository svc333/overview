---


copyright:
  years: 2015, 2019
lastupdated: "2019-06-25"

keywords: ui, components, using the console, SoftLayer, classic infrastructure

subcollection: overview

---

{:shortdesc: .shortdesc}
{:tip: .tip}
{:note: .note}
{:new_window: target="_blank"}

# {{site.data.keyword.cloud_notm}} 콘솔 탐색 
{: #ui}

{{site.data.keyword.cloud}} 콘솔은 모든 {{site.data.keyword.cloud_notm}} 리소스를 관리하는 데 도움이 되는 사용자 인터페이스입니다. [콘솔](https://cloud.ibm.com){: new_window} ![외부 링크 아이콘](../icons/launch-glyph.svg "외부 링크 아이콘")에 액세스하면 무료 계정 생성, 로그인, 문서에 액세스, 카탈로그에 액세스, 가격 정보 보기, 지원 받기 또는 {{site.data.keyword.cloud_notm}} 컴포넌트의 상태 확인 등을 수행할 수 있습니다. 로그인하면 메뉴 표시줄에 메뉴 아이콘 ![메뉴 아이콘](../icons/icon_hamburger.svg) 및 추가 링크가 포함됩니다.
{: shortdesc}


## 콘솔 사용
{: #consoleoptions}

{{site.data.keyword.cloud_notm}}에 로그인하면 대시보드가 표시되며, 여기에는 계정의 상태를 요약하는 위젯이 표시됩니다. 위젯을 추가 또는 제거하려는 경우, [대시보드 사용자 정의](/docs/overview?topic=overview-custom-dashboard)를 참조하십시오.

  * **카탈로그** 링크를 사용하여 새 리소스를 작성할 수 있습니다.
  * **문서** 링크를 사용하여 제품 문서에 액세스할 수 있습니다.  
  * **지원** 링크를 사용하여 지원 센터에 액세스할 수 있습니다.  
  * **관리** 메뉴에서 계정, 청구 및 사용량, IAM(Identity and Access Management) 옵션에 액세스할 수 있습니다.
  * 비용 추정기 아이콘 ![비용 추정기 아이콘](../icons/Estimator.svg)을 클릭하여 비용 추정기를 열 수 있습니다.
  * 알림 아이콘 ![알림 아이콘](../icons/Notification.svg)을 클릭하여 공지사항과 계획된 이벤트 및 계획되지 않은 이벤트에 액세스할 수 있습니다.

## 리소스 검색
{: #search}

{{site.data.keyword.cloud_notm}} 콘솔의 어느 위치에서나 리소스 목록에서 찾으려는 리소스에 대한 이름 또는 태그로 리소스를 검색할 수 있습니다. 콘솔 메뉴 표시줄의 검색 필드에 리소스의 이름 또는 태그를 입력하십시오.

자세한 정보는 [리소스 검색](/docs/resources?topic=resources-searching-for-resources)을 참조하십시오. 

## 리소스 목록에서 리소스 관리
{: #dashboardview}

메뉴 아이콘 ![메뉴 아이콘](../icons/icon_hamburger.svg) &gt; **리소스 목록**으로 이동하여 계정 리소스 목록에 액세스하십시오. 리소스 목록을 사용하여 {{site.data.keyword.cloud_notm}} 리소스 및 Cloud Foundry 서비스 인스턴스를 보고 관련 작업을 수행할 수 있습니다. 다양한 리소스 유형에 대한 자세한 정보는 [리소스의 개념](/docs/resources?topic=resources-resource)을 참조하십시오.

### 리소스 보기
리소스 목록에서 모든 지역에 있는 계정의 모든 리소스를 볼 수 있습니다. 사용자에게 중요한 항목을 보려면 각 열 헤더에 대한 필터를 사용하여 목록을 필터링하십시오. 예를 들어, 특정 위치에 있는 리소스를 보고 이에 대해 작업하려면 **위치** 필터를 펼친 후 목록에서 위치를 선택하십시오.

### 리소스 관련 작업
리소스 목록에서 다양한 방법으로 리소스 관련 작업을 수행할 수 있습니다.

  * 각각의 리소스는 고유 행에 표시되며 조치 아이콘 ![추가 조치 아이콘](../icons/action-menu-icon.svg)이 행의 끝에 포함됩니다. 조치 아이콘 ![추가 조치 아이콘](../icons/action-menu-icon.svg)을 클릭하면 리소스를 시작, 중지, 이름 바꾸기 또는 삭제할 수 있습니다.
  * 리소스에 대한 인증 정보 또는 연결을 설정하려면 리소스의 이름을 클릭하여 리소스 세부사항 페이지로 이동하십시오. 그런 다음 **서비스 인증 정보** 또는 **연결**을 선택하십시오. 자세한 정보는 [인증 정보 추가](/docs/resources?topic=resources-service_credentials) 및 [연결 관리](/docs/resources?topic=resources-connect_app)를 참조하십시오.

## 카탈로그에서 작업
{: #catalogcreate}

리소스를 작성하려면 리소스 목록에서 **작성**을 클릭하십시오. 그러면 카탈로그로 이동됩니다. 카탈로그에서 타일을 선택하면 어디에서 리소스가 사용 가능한지 볼 수 있습니다. 카탈로그에 나열된 모든 리소스를 모든 지역에서 사용할 수 있는 것은 아닙니다.

작성할 리소스에 대한 타일을 클릭한 후에는 배치되는 위치를 선택할 수 있습니다.

  * Cloud Foundry 리소스의 경우, 특정 지역을 선택한 후에 지정될 서비스 인스턴스에 대한 조직과 지역을 선택할 수 있습니다.
  * {{site.data.keyword.cloud_notm}} Identity and Access Management(IAM)에서 관리하는 리소스의 경우, 배치될 위치를 선택하십시오. 그리고 서비스 인스턴스가 지정될 리소스 그룹을 선택하십시오.

## {{site.data.keyword.cloud_notm}} 경험으로 전이
{: #redirect-cloud}

SoftLayer에서 {{site.data.keyword.cloud_notm}}로 마이그레이션하는 과정의 일부로서 플랫폼 및 인프라 리소스 관리에 사용하는 {{site.data.keyword.cloud_notm}} 콘솔에 익숙해져야 합니다. 현재 모든 SoftLayer 및 {{site.data.keyword.cloud_notm}} 계정을 링크하는 중입니다. 따라서 계정에 아직 액세스 권한이 없을 수 있습니다. 완료되는 대로 새로운 경험을 시작할 수 있습니다. 

이전의 SoftLayer를 이제 {{site.data.keyword.cloud_notm}} 클래식 인프라라고 부릅니다.
{: note}

### 인프라 항목 찾기
{: #sl-links}

**메뉴 아이콘** ![메뉴 아이콘](../icons/icon_hamburger.svg) > **클래식 인프라**를 클릭하여 디바이스, 스토리지, 네트워크, 보안 및 서비스를 빠르게 찾을 수 있습니다. 

![클래식 인프라 항목의 위치입니다.](images/iaas-items.png "인프라 항목 찾기"){: caption="Figure 1. Location of classic infrastructure items in the {{site.data.keyword.cloud_notm}} console" caption-side="bottom"}

또한 **메뉴 아이콘** ![메뉴 아이콘](../icons/icon_hamburger.svg) > **리소스 목록**을 클릭하여 리소스 목록 내의 디바이스 및 스토리지 항목을 볼 수도 있습니다.
{: tip}

### 사용자, 액세스 및 API 키 관리
{: #billing-items}

콘솔의 액세스(IAM) 섹션에서 계정의 사용자, 사용자에 대한 클래식 인프라 액세스 및 API 키를 관리할 수 있습니다.  

* 새 사용자 초대, 사용자 제거, 특정 사용자의 로그인 설정, IP 제한, VPN 비밀번호 관리 등을 위해서는 **관리** > **액세스(IAM)**로 이동하고 **사용자**를 선택하십시오.
* 사용자의 클래식 인프라 액세스 관리를 시작하려면 **관리** > **액세스(IAM)**로 이동하고 **사용자**를 선택하십시오. 자세한 정보는 [클래식 인프라 액세스 관리](/docs/iam?topic=iam-mngclassicinfra)를 참조하십시오.
* {{site.data.keyword.cloud_notm}} API 키 또는 클래식 인프라 API 키를 작성 및 관리하려면 **관리** > **액세스(IAM)**로 이동하고 **API 키**를 선택하십시오. 자세한 정보는 [API 키 이해하기](/docs/iam?topic=iam-manapikey)를 참조하십시오.

![IAM 항목을 관리하는 위치입니다.](images/users-access.png "사용자, 액세스 및 API 키 관리"){: caption="Figure 2. Managing IAM items in the {{site.data.keyword.cloud_notm}} console" caption-side="bottom"}

### 주문 작성
{: #place-order}

카탈로그를 사용하여 주문을 작성하십시오. 다음 방법 중 하나로 카탈로그로 이동할 수 있습니다.

  * 메뉴 표시줄에서 **카탈로그**를 클릭하십시오.
  * **메뉴 아이콘** ![메뉴 아이콘](../icons/icon_hamburger.svg) > **리소스 목록**을 클릭하십시오. 그런 다음 **리소스 작성**을 클릭하십시오.

![주문을 작성할 위치입니다.](images/orders.png "주문 작성"){: caption="Figure 3. Placing an order in the {{site.data.keyword.cloud_notm}} console" caption-side="bottom"}

### 결제하기
{: #payments}

콘솔의 청구 및 사용량 섹션에서 지불할 수 있습니다. **관리** > **청구 및 사용량**으로 이동하여 **지불**을 선택하십시오. 

![결제를 수행할 위치입니다.](images/payments.png "결제하기"){: caption="Figure 4. Making a payment in the {{site.data.keyword.cloud_notm}} console" caption-side="bottom"}

### 송장 액세스
{: #invoices}

콘솔의 청구 및 사용량 섹션에서 송장에 액세스할 수 있습니다. **관리** > **청구 및 사용량**으로 이동하여 **송장**을 선택하십시오.

![송장에 액세스할 위치입니다.](images/invoices.png "송장 액세스"){: caption="Figure 5. Accessing your invoices in the {{site.data.keyword.cloud_notm}} console" caption-side="bottom"}

### 영업 항목 액세스
{: #sales}

디바이스 견적 및 업그레이드, 주문, 취소 및 배송은 콘솔의 청구 및 사용량 섹션에 있습니다. **관리** > **청구 및 사용량**으로 이동하여 **영업**을 선택하십시오. 

![영업 항목에 액세스할 위치입니다.](images/sales-items.png "영업 항목 액세스"){: caption="Figure 6. Accessing your sales items in the {{site.data.keyword.cloud_notm}} console" caption-side="bottom"}

### 지원 케이스 액세스
{: #support-mng}

현재 지원 케이스에 액세스하려면 **지원** > **케이스 관리**를 클릭하십시오. 또한 **아카이브된 케이스**를 클릭하여 아카이브된 케이스에 액세스할 수 있습니다.

![지원 케이스에 액세스할 위치입니다.](images/support-cases.png "지원 케이스 액세스"){: caption="Figure 7. Accessing your support cases in the {{site.data.keyword.cloud_notm}} console" caption-side="bottom"}

### 피드백 제출
{: #feedback-profile}

호평, 제안 및 기타 피드백을 제출할 수 있습니다. 다음 방법 중 하나를 사용하여 연락할 수 있습니다.

  * 콘솔 페이지의 가장자리에 있는 **피드백** 단추를 클릭하십시오. 
  * **아바타 아이콘** ![아바타 아이콘](../icons/i-avatar-icon.svg) > **피드백**을 클릭하십시오. 

![피드백을 제출할 위치입니다.](images/feedback.png "피드백 제출"){: caption="Figure 8. Submitting feedback in the {{site.data.keyword.cloud_notm}} console" caption-side="bottom"}

### 이메일 환경 설정 지정
{: #email-prefsl}

플랫폼 및 인프라 알림에 대한 이메일을 수신하도록 환경 설정을 지정할 수 있습니다. **아바타 아이콘** ![아바타 아이콘](../icons/i-avatar-icon.svg) > **프로파일 및 설정**을 클릭하고 **알림**을 선택하십시오.

![이메일 환경 설정을 지정할 위치입니다.](images/email-prefs.png "이메일 환경 설정 지정"){: caption="Figure 9. Setting your email preferences in the {{site.data.keyword.cloud_notm}} console" caption-side="bottom"}

### VPN 액세스 지점 선택
{: #vpn-access}

VPN 액세스 지점을 사용하여 {{site.data.keyword.cloud_notm}} 콘솔에 로그인할 수 있습니다. [VPN 액세스](https://www.ibm.com/cloud-computing/bluemix/vpn-access)로 이동하여 목록에서 액세스 지점을 선택하십시오. 


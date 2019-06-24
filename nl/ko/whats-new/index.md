---

copyright:

  years: 2015, 2019

lastupdated: "2019-06-03"

keywords: release notes, what's new, what is new, cloud updates

subcollection: overview

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:tip: .tip}

# {{site.data.keyword.Bluemix_notm}}의 새로운 기능
{: #whatsnew}

{{site.data.keyword.Bluemix_notm}} 경험을 최대한 활용할 수 있도록 {{site.data.keyword.Bluemix}} 플랫폼에서 사용 가능한 새 기능을 최신 상태로 유지하십시오. 
{:shortdesc}

{{site.data.keyword.Bluemix_notm}}에서 사용 가능한 서비스에 대한 업데이트를 찾는 경우, 블로그에서 [{{site.data.keyword.Bluemix_notm}} 공지사항 페이지](https://www.ibm.com/cloud/blog/announcements){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")를 확인하십시오.
{: tip}



## {{site.data.keyword.Bluemix_notm}} 플랫폼
{: #platform_category}


### 연관된 태그가 있는 사용 데이터 내보내기
신규 기준일: 2019년 4월 4일 

이제 사용자가 최신 태깅 기능을 활용하여 내보내기 사용량 보고서에서 리소스, 사용량 및 비용을 관리할 수 있습니다. 리소스에 태그를 추가할 때 리소스와 연관된 태그를 보는 옵션이 있습니다. **관리**> **청구 및 사용량**> **사용량**> **CSV 내보내기**>  **인스턴스**로 이동하여 사용량 보고서를 다운로드하십시오. 태그 내보내기에 대한 자세한 정보는 [비용 할당을 지원하도록 사용량 데이터에서 태그 내보내기](https://www.ibm.com/cloud/blog/export-your-tagged-usage-data-within-the-enhanced-ibm-cloud){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘") 블로그 게시물을 확인하십시오.

### 리소스에 대한 공용 액세스 사용을 위한 액세스 그룹
신규 기준일: 2019년 3월 25일

계정 내에서 제공되는 새 액세스 그룹을 사용하여 {{site.data.keyword.cos_full}} 버킷 내의 오브젝트에 대한 공용 액세스를 사용할 수 있습니다. 이 새 액세스 그룹을 `공용 액세스` 그룹이라고 하며 기본적으로 모든 사용자 및 서비스 ID가 추가됩니다. 인증되지 않은 사용자를 포함하여 모든 사용자가 정책에서 지정된 리소스에 액세스할 수 있도록 액세스 그룹에 대한 정책을 업데이트할 수 있습니다. [공용 액세스 그룹에 대해 자세히 알아보십시오](/docs/iam?topic=iam-public#public).

### 연합 ID가 있는 사용자에 대한 다단계 인증
신규 기준일: 2019년 3월 12일
{: #mfa-federated}

계정 소유자 또는 사용자가 지정한 청구 계정 관리 서비스의 관리자 역할은 계정 내의 모든 사용자에 대해 다단계 인증(MFA)을 사용하도록 설정할 수 있습니다. 회사 또는 엔터프라이즈 싱글 사인온 ID를 사용하는 연합 사용자는 {{site.data.keyword.Bluemix_notm}}에 로그인하기 위해 MFA를 사용하여 인증하도록 요청받을 수 있습니다. 이 기능의 개선사항 및 계정에 대해 MFA를 사용하도록 설정하는 방법에 대한 자세한 정보는 [연합 ID가 있는 IBM Cloud 사용자를 위한 MFA 소개](https://www.ibm.com/cloud/blog/introducing-mfa-for-ibm-cloud-users-with-federated-id){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")를 참조하십시오.

### 새로운 appdomain.cloud 호스트 이름 옵션
신규 기준일: 2018년 12월 31일
{: #appdomain}

새 호스트 이름 옵션 `*.appdomain.cloud`는 cloud.ibm.com에서 사용할 수 있습니다.

이전에는 {{site.data.keyword.containerlong_notm}} 또는 Cloud Foundry와 같은 다양한 배치 대상에서 앱을 호스팅하는 데 `mybluemix.net` 도메인이 사용되었습니다. `mybluemix.net`에서 호스팅한 앱에는 영향을 미치지 않습니다.

Cloud Foundry 앱의 하위 도메인은 `cf.appdomain.cloud`입니다. {{site.data.keyword.containerlong_notm}}에 배치하는 앱의 하위 도메인은 `containers.appdomain.cloud`입니다.

### 새 Cloud Foundry API 엔드포인트
신규 기준일: 2018년 11월 30일
{: #cf-api-endpoints}

레거시 `api.*.bluemix.net` Cloud Foundry API 엔드포인트는 역호환성을 위해 여전히 사용할 수 있습니다. 그러나 지역에서 다음과 같은 새로운 Cloud Foundry API 엔드포인트를 사용하도록 스크립트와 인프라 자동화를 업데이트할 수 있습니다.

* api.us-south.cf.cloud.ibm.com(이전의 api.ng.bluemix.net)
* api.eu-gb.cf.cloud.ibm.com(이전의 api.eu-gb.bluemix.net)
* api.us-east.cf.cloud.ibm.com(이전의 api.us-east.bluemix.net)
* api.eu-de.cf.cloud.ibm.com(이전의 api.eu-de.bluemix.net)
* api.au-syd.cf.cloud.ibm.com(이전의 api.au-syd.bluemix.net)

### {{site.data.keyword.Bluemix_notm}}에 대한 새로운 지원 경험
신규 기준일: 2018년 11월 30일 
{: #support}

지원 센터를 통해 모든 {{site.data.keyword.Bluemix_notm}} 관련 문제를 해결하는 작업을 수행할 수 있습니다. 랜딩 페이지에서 FAQ를 제공하므로 {{site.data.keyword.Bluemix_notm}}에 문의하지 않고도 질문에 대한 답변을 찾을 수 있습니다. 지원 담당자와 실시간으로 채팅할 수도 있습니다. 이제 단일 위치에서 케이스를 관리할 수 있습니다. 케이스를 작성하거나 보거나 편집하려면 **지원** &gt; **케이스 관리**로 이동하십시오.

지원 센터에서 [상태 페이지](https://cloud.ibm.com/status){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")를 찾을 수도 있습니다. 이는 {{site.data.keyword.Bluemix_notm}} 플랫폼, 인프라 및 주요 서비스에 영향을 미치는 주요 이벤트에 대한 모든 계획되지 않은 인시던트, 계획된 유지보수, 공지사항 및 보안 게시판 알림을 포함하도록 개선되었습니다. 지원 센터에서 **클라우드 상태 보기**를 클릭하십시오. 새로운 환경을 확인하려면 로그인한 후 [지원 센터](https://cloud.ibm.com/unifiedsupport/supportcenter){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")로 이동하십시오. 

### {{site.data.keyword.Bluemix_notm}}의 통합 로그인, API 키, 사용자 및 액세스 관리
신규 기준일: 2018년 11월 30일
{: #useraccess}

최신 업데이트를 통해 ID 유형에 관계없이 모든 사용자가 사용할 수 있는 단순화된 보안 로그인을 활용할 수 있습니다. IBM ID 또는 SoftLayer ID가 있는지에 관계없이 개선된 로그인 페이지에서 {{site.data.keyword.Bluemix_notm}} 콘솔에 빠르게 로그인할 수 있습니다. 또한 {{site.data.keyword.Bluemix_notm}}에서 보안 API 호출을 작성하고 IAM API 키 또는 IAM 액세스 토큰을 사용하여 CLI 로그인을 자동화할 수 있습니다. 

로그인 후에는 이제 액세스(IAM) UI의 사용자 페이지에서 플랫폼 및 클래식 인프라 사용자를 포함한 모든 사용자를 볼 수 있습니다. 계정의 다른 사용자를 볼 수 있는 액세스 권한에 따라 계정 사용자, 클래식 인프라 사용자 또는 Cloud Foundry 조직별로 보기를 빠르게 필터링할 수 있습니다. 필터를 사용하여 이름, 이메일 또는 상태별로 사용자를 빠르게 찾을 수도 있습니다.

이제 모든 사용자가 단일 콘솔에 있으므로 동일한 위치에서 모든 유형의 리소스에 대한 액세스를 관리할 수 있습니다. 액세스가 사용자로 시작하므로 목록에서 사용자를 선택하여 시작하십시오. 그런 다음, 액세스를 지정할 리소스의 유형에 따라 IAM 액세스 정책, Cloud Foundry 액세스 또는 클래식 인프라 권한 중에서 선택할 수 있습니다. IAM 액세스 정책을 지정하려는 경우 액세스 그룹을 작성하고 동일한 정책이 지정되어야 하는 모든 사용자를 동일한 액세스 그룹에 추가하여 액세스 관리 프로세스를 간소화하십시오.

세부사항은 [Outstanding User Access Improvements Help Deliver a Unified {{site.data.keyword.Bluemix_notm}} Platform](https://www.ibm.com/cloud/blog/announcements/ibm-cloud-access-management){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")를 참조하십시오. 

### 한 곳에서 모든 {{site.data.keyword.Bluemix_notm}} CLI 플러그인 문서 찾기
신규 기준일: 2018년 11월 30일
{: #cli}

이제 한 위치에서 모든 {{site.data.keyword.Bluemix_notm}} CLI 플러그인 문서에 액세스하여 {{site.data.keyword.Bluemix_notm}} 플랫폼에서 검색 중인 CLI 명령을 더 쉽게 찾을 수 있습니다. [CLI 문서](/docs/cli?topic=cloud-cli-ibmcloud-cli)의 참조 절을 확인하십시오.

### 새 대시보드 및 리소스 목록 확인
신규 기준일: 2018년 11월 30일
{: #dash}

최신 업데이트를 통해 모든 플랫폼 및 인프라 서비스를 한 위치에서 볼 수 있습니다. 로그인하면 새 대시보드를 즉시 확인할 수 있습니다. 카탈로그에서 계정에 리소스를 추가한 후에는 리소스 목록을 사용하여 계정 리소스의 전체 보기를 가져올 수 있습니다.

* 리소스, 유지보수, 상태, 앱, 지원, 사용량 및 사용자의 요약을 볼 수 있도록 대시보드가 재설계되었습니다.
* 리소스 목록에서 리소스에 대한 세부사항을 찾을 수 있습니다. 리소스를 구성하기 위해 리소스에 태그를 지정하거나 세부사항 페이지에서 변경할 리소스를 선택할 수 있습니다.
* 이제 모든 리소스를 한 곳에서 볼 수 있으므로 작성했고 리소스 목록 페이지에 표시될 것으로 예상하는 리소스를 빠르게 찾을 수 있도록 글로벌 검색을 추가했습니다. 
* 카탈로그 결과도 검색할 수 있으므로 계정에 추가할 리소스를 빠르게 찾을 수 있습니다.  

세부사항은 [Manage All Your Cloud Resources on the Enhanced {{site.data.keyword.Bluemix_notm}} Platform](https://www.ibm.com/blogs/bluemix/2018/11/manage-all-your-cloud-resources-on-the-enhanced-ibm-cloud-platform/){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")을 참조하십시오.

### 플랫폼 및 인프라 서비스에 대한 통합 계정, 청구 및 사용자 프로파일 정보
신규 기준일: 2018년 11월 30일
{: #profile}

계정, 청구 및 프로파일 정보가 이제 단순화되었습니다. 통합 콘솔에서 모든 플랫폼 및 인프라 리소스에 대한 계정 정보를 볼 수 있습니다. 

* 프로파일 및 설정 영역에는 모든 리소스 유형의 사용자 및 사용자의 이메일 알림 환경 설정에 대한 정보가 포함되어 있습니다. 
* 계정 정보 영역에는 회사 또는 조직에 대한 정보, 계정 설정 및 리소스 그룹과 Cloud Foundry 조직에 대해 작업하기 위한 빠른 액세스가 포함되어 있습니다. 빠르게 시작하고 실행하는 데 도움이 되는 우수 사례를 찾을 수도 있습니다.
* 계정의 청구 및 사용량 영역은 청구를 이해하고, 결제하고, 구독을 모니터하고, 견적서를 받고, 주문을 추적하고, 지출 알림을 설정하는 데 도움이 됩니다.

세부사항은 [Bringing It All Together: A Single Account and Billing Management Experience](https://www.ibm.com/cloud/blog/announcements/ibm-cloud-account-management){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")를 참조하십시오.

### 태그를 사용하여 리소스 구성
신규 기준일: 2018년 11월 30일
{: #tag}

이제 리소스를 관리하고 가장 관련성이 높은 리소스를 찾는 데 도움이 되도록 Cloud Object Storage와 같은 리소스에 태그를 추가할 수 있습니다. 예를 들어, 수백 개의 리소스가 있으며 동일한 방식으로 결제되는 몇몇 리소스 간의 구별을 원하는 경우에는 이에 `costcenter:location01` 태그를 지정할 수 있습니다. 또는 반복적으로 몇몇 리소스에 대해 작업하는 팀이 있는 경우에는 `team-blue`와 같은 태그를 사용할 수 있습니다. 리소스 목록을 태그별로 필터링하여 필요한 리소스를 빠르게 구성하고 찾을 수도 있습니다. 자세한 정보는 [Working with tags](/docs/resources?topic=resources-tag) 및 [Platform Tagging on the Enhanced {{site.data.keyword.Bluemix_notm}} Platform](https://www.ibm.com/cloud/blog/announcements/platform-tagging-on-the-enhanced-ibm-cloud-platform){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")를 참조하십시오. 

### 비용 추정기를 사용하여 정확한 월별 비용 찾기
신규 기준일: 2018년 11월 30일
{: #cost-estimator}

구매할 서비스를 결정하고 분석하는 데 도움이 되도록 비용 추정기를 사용할 수 있습니다. 이제 콘솔을 통해 보유하려는 각 서비스를 선택하고 사용하기 쉬운 도구로 모든 비용을 추가할 수 있습니다. 예상 데이터 사용량, 초당 검색 수, 초당 쓰기 수 및 초당 조회 수를 입력하여 월별 비용을 보다 정확하게 추정할 수도 있습니다. 선택하는 각 카탈로그 서비스에 비용 추정기를 사용할 수 있습니다. 또는 콘솔 메뉴에서 비용 추정기 아이콘 ![추정기 아이콘](../../icons/Estimator.svg)을 클릭하여 예상 비용에 대한 요약을 가져올 수 있습니다. 자세한 정보는 [비용 추정](/docs/billing-usage?topic=billing-usage-cost)을 참조하십시오.

### {{site.data.keyword.cloud_notm}}에 대한 글로벌 위치 이름 업데이트함
신규 기준일: 2018년 11월 1일
{: #location-name-updates}

{{site.data.keyword.cloud_notm}}에서는 지속적으로 글로벌 가용성 풋프린트를 확장하면서 전 세계적으로 분포된 지형, 지역, 데이터 센터의 이해 가능하고 일관된 계층 구조를 더 잘 지원하도록 위치 이름 지정 구조를 업데이트하고 있습니다. 현재 글로벌 지역에 친숙하다면 미국 남부 및 시드니와 같은 이름을 이해할 수 있습니다. 이러한 위치 이름을 실제로 데이터 센터가 존재하는 도시의 이름에 맞추고 있습니다.

현재 프로그래밍 ID는 변경되지 않았으므로, API 퍼스펙티브에서는 영향을 받지 않습니다. 다음 표에서는 이전 및 새 위치 이름을 보여줍니다. 데이터 센터 및 지역에 대한 전체 목록과 자세한 정보는 [서비스 가용성](/docs/resources?topic=resources-services_region)을 참조하십시오.

| 이전 위치 표시 이름 | 새 위치 표시 이름 | 코드 |
|----------|---------|---------|
|미국 남부 |댈러스 | us-south | 
|미국 동부 | 워싱턴 DC | us-east |
|영국 | 런던 | eu-gb |
|독일 | 프랑크푸르트 | eu-de |
|시드니 |시드니 | au-syd |
| AP 북부 | 도쿄 | jp-tok |
{: caption="표 1. 새 위치 이름" caption-side="top"}

### 다른 사용자에게 계정 관리 서비스 지정
신규 기준일: 2018년 10월 30일
{: #acct-mgmt-services}

{{site.data.keyword.cloud_notm}} IAM(Identity and Access Management)을 통해 계정 관리자로 완료하는 공통 태스크를 사용자 계정의 다른 사용자에게 위임할 수 있습니다. 하나 또는 모든 사용 가능 계정 관리 서비스에서 액세스 정책을 작성하면 사용자 초대 및 제거, 액세스 그룹 관리, 서비스 ID 관리, 사설 카탈로그 서비스 유지보수, 청구 모니터링 및 사용량 추적과 같은 책임을 쉽게 위임할 수 있습니다. 액세스 정책을 설정하는 데 사용할 수 있는 네 개의 개별 계정 관리 서비스 및 모든 서비스 옵션이 있습니다.

* 사용자를 초대 및 제거하기 위한 사용자 관리
* 액세스 권한 작성, 편집, 삭제, 업데이트, 지정을 위한 IAM 액세스 그룹 
* 계정에서 서비스 ID 및 연관된 API 키에 대한 액세스 권한 보기, 작성, 삭제, 지정을 위한 IAM ID 서비스
* 사설 카탈로그 오퍼링을 보고 오퍼링에 대한 메타데이터 및 가시성을 업데이트하기 위한 글로벌 리소스 카탈로그
* 청구 및 사용량 추적에 대한 액세스는 물론, 지정된 역할에 기반하여 각 개별 계정 관리 서비스 옵션에 대한 액세스를 위한 모든 계정 관리 서비스.

지정된 역할 및 관련 정책을 보유하고 있는 관련 계정 관리 서비스에 기반하여 사용자가 수행할 수 있는 태스크에 대한 자세한 정보는 [계정 관리 서비스에 대한 예제 플랫폼 관리 역할 및 조치](/docs/iam?topic=iam-userroles#platformrolestable2)를 참조하십시오. 이 새 기능에 대한 자세한 정보는 [Introducing More Flexibility and Control for IBM Cloud Account Management Services Access](https://www.ibm.com/cloud/blog/announcements/introducing-more-flexibility-and-control-for-ibm-cloud-account-management-services-access){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘") 블로그 게시물을 참조하십시오. 

### 리소스 검색
신규 기준일: 2018년 7월 17일
{: #forward-slash-key}

{{site.data.keyword.cloud_notm}} 콘솔의 어느 위치에서나 리소스를 검색할 수 있습니다. 콘솔 메뉴 표시줄의 검색 필드에 리소스의 이름을 입력하십시오. 검색을 활성화하려면 슬래시 키(/)를 누르십시오.

### 동적으로 액세스 그룹에 연합 사용자 추가
신규 기준일: 2018년 7월 12일
{: #add-fed-users}

특정 ID 속성을 기반으로 액세스 그룹에 연합 사용자를 자동으로 추가하기 위한 동적 규칙을 작성할 수 있습니다. 사용자가 연합 ID를 사용하여 로그인하면 사용자가 설정한 규칙에 따라 ID 제공자의 데이터가 동적으로 사용자를 액세스 그룹에 맵핑합니다. 자세한 정보는 [액세스 그룹에 대한 동적 규칙 작성](/docs/iam?topic=iam-rules)을 참조하십시오.

### 서비스 ID 및 API 키 보호
신규 기준일: 2018년 6월 1일
{: #protect-svcid-apikey}

서비스 ID 또는 API 키가 삭제되어 가동 중단이나 손상이 발생하는 상황을 막기 위해 UI 또는 CLI를 사용하여 서비스 ID 및 API 키의 잠금을 수행할 수 있습니다. 서비스 ID를 잠그면 액세스 정책 변경, 삭제 또는 지정뿐만 아니라 서비스 ID와 연관된 API 키 작성 또는 삭제를 수행할 수 없습니다. 자세한 정보는 [서비스 ID 잠금](/docs/iam?topic=iam-serviceidapikeys#lockkey) 및 [API 키 잠금](/docs/iam?topic=iam-userapikey)을 참조하십시오.

### Lite 계정을 구독 계정으로 업그레이드
신규 기준일: 2018년 5월 31일
{: #upgrade-lite}

이제 {{site.data.keyword.Bluemix_notm}} 콘솔에서 직접 Lite 계정을 구독 계정으로 업그레이드할 수 있습니다. 구독 계정을 사용하면 플랫폼과 인프라 오퍼링을 둘 다 사용하고 월별 지출 및 기간 약정을 통해 할인 가격을 이용할 수 있습니다. 월별 지불 스케줄에 따라 고정 비용을 청구하지만, 필요에 따라 주문 양을 조정하는 유연성도 제공합니다. 자세한 정보는 [구독 계정 FAQ](/docs/billing-usage?topic=billing-usage-billusagefaqs#subs-order)를 참조하십시오. 

### {{site.data.keyword.Bluemix_notm}} CLI 리브랜딩
신규 기준일: 2018년 5월 15일
{: #cli-rebrand}

{{site.data.keyword.Bluemix_notm}} CLI 명령은 **`bluemix`** 및 **`bx`**에서 **`ibmcloud`**로 변경되었습니다. 그러나 나중에 제거되기 전까지는 여전히 **`bluemix`** 및 **`bx`** CLI 명령을 사용할 수 있습니다. 이제 단축 이름은 없으며 전체 이름 **`ibmcloud`**만 있습니다. 

### {{site.data.keyword.Bluemix_notm}} 계정에 대한 다단계 인증
신규 기준일: 2018년 5월 02일
{: #account-mfa}

다단계 인증(MFA)은 로그인 중에 모든 사용자가 표준 IBM ID 및 비밀번호와 함께 시간 기반의 일회성 패스코드를 입력하도록 요구하여 사용자 계정에 대해 보안 계층을 더 추가합니다. 일반적으로 2단계 인증(2FA)이라고도 합니다. MFA는 계정별로 사용 설정되며, 일단 작동되면 계정의 모든 사용자가 추가 보안 방법을 사용하여 로그인해야 합니다. 자세한 정보는 [IBM Cloud Platform now adds support for Multi-Factor Authentication](https://www.ibm.com/cloud/blog/ibm-cloud-platform-now-adds-support-multi-factor-authentication){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘") 블로그 게시물을 참조하십시오.

### 액세스 그룹을 사용하여 신속하게 액세스 지정
신규 기준일: 2018년 4월 3일
{: #access-groups}

가급적 최소 수의 정책을 사용하여 신속하게 액세스를 지정할 수 있기를 원하십니까? 이제 액세스 그룹으로 이를 수행할 수 있습니다. 액세스 그룹을 사용하면 사용자 및 서비스 ID 세트를 그룹화하고 그룹의 모든 구성원에 적용하는 단일 정책을 지정할 수 있습니다. 액세스 그룹을 사용하면 계정의 사용자 및 서비스 ID에 대한 액세스 관리에 사용하는 시간을 제한할 수 있습니다. 세부사항은 블로그 게시물 [새 기능: 액세스 그룹](https://www.ibm.com/cloud/blog/access-groups){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")을 확인하십시오.

### {{site.data.keyword.Bluemix_notm}} Foundry Service 미국 동부 지역은 지금 사용 가능
신규 기준일: 2017년 12월 15일
{: #cf-useast}

새로운 미국 동부 데이터 센터가 워싱턴, DC에 있습니다. 이 새 지역은 `us-east.cloud.ibm.com` 엔드포인트를 사용하여 도달할 수 있습니다. 이 새 지역에서 구매할 수 있는 서비스에 대한 자세한 정보는 [지역별 서비스](/docs/resources?topic=resources-services_region)를 참조하십시오.

### EU의 리소스에 대한 지원
신규 기준일: 2017년 12월 14일
{: #eu-resources}

서비스 및 데이터 센터가 유럽에 위치한 경우, {{site.data.keyword.Bluemix_notm}}에서는 이제 EU(European Union)의 데이터를 보호하는 추가 기능을 제공합니다. 유럽에 있는 고객 성공 팀이 지원을 제공하도록 요청할 수 있습니다. 이 지원은 연중무휴로 제공됩니다. 자세한 정보는 [EU 지원 옵션 사용](/docs/account?topic=account-eu-hipaa-supported#bill_eusupported) 및 [EU의 리소스에 대한 지원 요청](/docs/get-support?topic=get-support-getting-customer-support#eusupported)을 참조하십시오.

### TLS 1.0 및 1.1에 대한 지원 중단
신규 기준일: 2017년 11월 28일
{: #nosupport-tls}

2018년 3월 1일부로 {{site.data.keyword.Bluemix_notm}}는 보안 및 데이터 개인정보 보호에 대한 업계의 우수 사례에 따라 철저하게 보안되는 클라우드를 제공하고자 하는 노력의 일부로 여러 클라우드 제품 및 서비스에서 TLS 1.0 및 TLS 1.1에 대한 지원을 중단합니다. 이 변경사항이 적용되는 방법과 수행해야 하는 조치에 대해 자세히 알아보려면 [LS 1.0 및 1.1에 대한 지원 중단](/docs/get-support?topic=get-support-tlssupportwithdraw)을 참조하십시오.

### 계정에서 리소스를 구성하는 새로운 방법
신규 기준일: 2017년 11월 16일
{: #usergs}

리소스 그룹은 사용자가 계정 리소스의 사용자 정의할 수 있는 그룹화를 작성하고 IAM(Identity and Access Management)을 사용하여 관리되는 계정에서 그룹 및 리소스에 대한 액세스를 작성하기 위한 새로운 방법입니다. 모든 사용자는 기본 리소스 그룹을 사용하여 시작합니다. 이 리소스 그룹의 이름을 변경할 수 있으며 카탈로그에서 이를 작성할 때 새 서비스 인스턴스를 이에 추가할 수 있습니다.

종량과금제 또는 구독 계정이 있는 사용자는 추가 리소스 그룹을 작성하여 할당량을 관리하고 리소스 세트에 대한 청구 사용량을 볼 수 있도록 합니다. 한 번에 둘 이상의 서비스에 대한 사용자 액세스를 보다 쉽게 지정할 수 있도록 리소스를 그룹화할 수도 있습니다. 계정에 대한 리소스 그룹 관련 작업에 대해 자세히 알아보려면 [리소스 그룹 관리](/docs/resources?topic=resources-rgs)를 참조하십시오.

### {{site.data.keyword.Bluemix_notm}} IAM에 대한 업데이트
신규 기준일: 2017년 11월 16일
{: #iam-nov17}

{{site.data.keyword.Bluemix_notm}} 계정 내 리소스 그룹의 도입으로 액세스 권한을 지정하는 새로운 방법이 생겼습니다. 사용자 및 서비스 ID는 한 번에 둘 이상의 리소스에 대한 액세스를 신속하게 지정할 수 있도록 리소스 그룹 내에 모든 서비스에게 액세스 권한을 지정할 수 있습니다. 또한 리소스 그룹 내의 일부 서비스에 대해서만 액세스를 지정하여 각 사용자 또는 서비스 ID에 대한 액세스를 사용자 정의하거나, 서비스 인스턴스 레벨에 이르기까지 개별 리소스에 대한 액세스를 지정하도록 선택할 수 있습니다. IAM을 사용하여 활용할 수 있는 기능에 대한 자세한 정보는 [IAM에서 제공하는 기능](/docs/iam?topic=iam-iamoverview#features)을 참조하십시오.

### 대시보드 보기 사용자 정의
신규 기준일: 2017년 11월 16일
{: #custom-dash}

{{site.data.keyword.Bluemix_notm}} 콘솔의 대시보드에서 계정의 모든 리소스를 보고 관리할 수 있습니다. 이제 필터를 설정하여 보기를 사용자 정의할 수 있습니다. 예를 들어, 리소스 그룹별로 필터링하여 리소스 그룹의 특정 리소스를 볼 수 있습니다. 또한 지역 또는 Cloud Foundry 영역별로 필터링할 수도 있습니다. 추가 세부사항은 [대시보드에서 리소스 관리](/docs/overview?topic=overview-ui#dashboardview)를 참조하십시오.

### 지원 센터
신규 기준일: 2017년 11월 2일
{: #support-nov17}

이제 정보를 검색하고, 개발자 커뮤니티에 질문을 게시하고, 티켓을 관리할 수 있는 새 지원 센터가 제공됩니다. {{site.data.keyword.Bluemix_notm}} 콘솔 메뉴 표시줄에서 **지원 > 지원 센터**로 이동하십시오.

### IBM Cloud 소개
신규 기준일: 2017년 10월 31일
{: #meet-ibmcloud}

Bluemix는 이제 IBM Cloud입니다. 새로운 이름 사용 외에는 변경사항이 없습니다. 계속해서 쉽게 앱과 서비스를 빌드하고 실행할 수 있습니다. 추가 세부사항은 [IBM Cloud Blog](https://www.ibm.com/cloud/blog/announcements/bluemix-is-now-ibm-cloud){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")를 참조하십시오.

### Lite 계정
신규 기준일: 2017년 10월 31일
{: #new-liteacct}

Lite 계정은 시간 제한 없이 무료로 서비스를 선택해 볼 수 있는 액세스 권한을 제공하는 새 계정 유형입니다. 이 새 계정에 사용량 추적과 효율성 기능도 포함하여 리소스를 보다 잘 관리할 수 있도록 합니다. 사용 가능한 항목에 대해 자세히 알아보려면 [계정 유형](/docs/account?topic=account-accounts#liteaccount)을 참조하십시오.

### Identity and Access Management 애플리케이션 인증 기능
신규 기준일: 2017년 10월 6일
{: #app-authfeature}

IAM(Identity and Access Management)은 이제 서비스 ID를 작성할 수 있는 기능을 제공하여 {{site.data.keyword.Bluemix_notm}} 서비스로 인증하도록 앱에 사용할 수 있는 ID로 간주할 수 있습니다. 개별 사용자 인증 정보를 사용하는 대신 서비스 ID는 해당 ID를 사용하여 애플리케이션 인증에 대한 액세스 권한의 레벨을 제어할 수 있도록 서비스 ID에 지정되는 서비스 정책의 양식으로 인증된 API 키 및 액세스 권한을 사용하여 작성될 수 있습니다.

이 기능의 장점 및 시작하는 방법에 대한 자세한 정보는 [Introducing IBM Cloud IAM Service IDs and API Keys](https://www.ibm.com/cloud/blog/introducing-ibm-cloud-iam-service-ids-api-keys){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")를 참조하십시오.

### {{site.data.keyword.Bluemix_notm}} 글로벌 카탈로그
신규 기준일: 2017년 7월 27일
{: #gc}

콘솔 내 하나의 위치에서 퍼블릭 지역을 관리하도록 하는 최신 콘솔 업데이트에서 한 걸음 더 나아가, 이제 {{site.data.keyword.Bluemix_notm}}에는 카탈로그에서 항목을 선택하고 배치하는 프로세스를 보다 간소화하는 글로벌 카탈로그가 있습니다. 콘솔에서 선택한 지역에 관계없이 이제 카탈로그의 모든 퍼블릭 지역에서 사용 가능한 모든 서비스를 볼 수 있습니다. 카탈로그에서 파일만 선택하면 서비스를 사용할 수 있는 지역을 볼 수 있고 서비스를 배치할 위치를 선택할 수 있습니다. 카탈로그에 대한 최신 업데이트에 대한 자세한 정보는 [A global {{site.data.keyword.Bluemix_notm}} catalog makes building things easier](https://www.ibm.com/cloud/blog/announcements/global-bluemix-catalog-makes-building-things-easier){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")를 참조하십시오.

### {{site.data.keyword.Bluemix_notm}} 콘솔 업데이트
신규 기준일: 2017년 5월 23일
{: #console-may17}

이제 업데이트된 {{site.data.keyword.Bluemix_notm}} 콘솔을 통해 단일 위치에서 퍼블릭 지역을 관리할 수 있습니다. 지역 선택기는 리소스에 대한 간소화된 액세스를 제공하고 기타 개선사항에는 고가용성 및 향상된 성능이 포함됩니다. 자세한 정보는 [New Global Bluemix UI for Higher Availability and More](https://www.ibm.com/blogs/bluemix/2017/05/new-global-bluemix-ui-higher-availability/){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")를 참조하십시오.

### ID 및 액세스 관리
신규 기준일: 2017년 5월 01일
{: #iam-may17}

최신 업데이트 및 개선사항을 통해 이제 {{site.data.keyword.Bluemix_notm}} 계정 소유자 또는 관리자는 새 통합 액세스 제어 UI를 사용하여 다음 기능을 활용할 수 있습니다.
 * Kubernetes 서비스 및 기타 서비스에서 새 액세스 제어 기능을 채택함에 따라 Kubernetes 서비스 및 기타 서비스에 대한 사용자의 세분화된 액세스 권한을 관리합니다.
 * 조직 내에서 서비스 정책 및 Cloud Foundry 역할을 사용자에게 지정합니다.

또한 {{site.data.keyword.Bluemix_notm}} 플랫폼 사용자는 사용자 ID와 연관된 API 키를 작성, 삭제 및 나열할 수 있습니다. 또한 플랫폼 사용자는 API 또는 CLI를 사용할 때 인증할 API 키를 사용할 수 있습니다.

최근에 연결된 IaaS-PaaS 계정에서 SoftLayer 고객 포털 또는 {{site.data.keyword.Bluemix_notm}} 콘솔에 사용자를 개별적으로 추가할 필요 없이 통합 방식으로 사용자를 관리하도록 통합 사용자 관리 기능이 개선되었습니다.

자세한 정보는 [Introducing Identity & Access Management](https://www.ibm.com/blogs/bluemix/2017/05/introducing-identity-access-management/){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘") 블로그 게시물을 확인하십시오.

### {{site.data.keyword.Bluemix_notm}} 문서의 디자인 변경사항 탐색
신규 기준일: 2017년 4월 13일
{: #docnavupdates}

이 탐색 업데이트를 사용하여 컨텐츠가 문서 전체에 구성되는 방식을 보다 잘 이해하고 좀 더 효율적으로 관련 컨텐츠를 찾을 수 있을 것으로 간주합니다. 더 적은 컨텐츠의 중첩된 계층을 사용하면 {{site.data.keyword.Bluemix_notm}}로 성공에 필요한 문서를 찾기 위해 노력할 필요가 없습니다.



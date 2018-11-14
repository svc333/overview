---

copyright:

  years: 2015, 2018

lastupdated: "2018-11-02"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# {{site.data.keyword.Bluemix_notm}}의 새로운 기능
{: #whatsnew}

{{site.data.keyword.Bluemix_notm}} 인터페이스를 최대한 활용할 수 있도록 하려면 {{site.data.keyword.Bluemix}}에서 사용 가능한 새 기능 및 서비스를 최신 상태로 유지하십시오. 업데이트는 [{{site.data.keyword.Bluemix_notm}} 플랫폼](index.html#platform_category), [{{site.data.keyword.Bluemix_local_notm}} 및 {{site.data.keyword.Bluemix_dedicated_notm}}](index.html#dedicatedandlocal), [컴퓨팅](index.html#compute_category) 및 [서비스](index.html#services_category) 카테고리로 구성됩니다.
{:shortdesc}

## {{site.data.keyword.Bluemix_notm}} 플랫폼
{: #platform_category}

### {{site.data.keyword.cloud_notm}}에 대한 글로벌 위치 이름 업데이트함
신규 기준일: 2018년 11월 1일

{{site.data.keyword.cloud_notm}}에서는 지속적으로 글로벌 가용성 풋프린트를 확장하면서 전 세계적으로 분포된 지형, 지역, 데이터 센터의 이해 가능하고 일관된 계층 구조를 더 잘 지원하도록 위치 이름 지정 구조를 업데이트하고 있습니다. 현재 글로벌 지역에 친숙하다면 미국 남부 및 시드니와 같은 이름을 이해할 수 있습니다. 이러한 위치 이름을 실제로 데이터 센터가 존재하는 도시의 이름에 맞추고 있습니다.

현재 프로그래밍 ID는 변경되지 않았으므로, API 퍼스펙티브에서는 영향을 받지 않습니다. 다음에 이전 위치 이름과 새 위치 이름을 보여주는 표가 있습니다. 데이터 센터 및 지역에 대한 전체 목록과 자세한 정보는 [서비스 가용성](docs/resources/services_region.html)을 참조하십시오.

| 이전 위치 표시 이름 | 새 위치 표시 이름 | 코드 |
|----------|---------|---------|
|미국 남부 | 댈러스 | us-south | 
|미국 동부 | 워싱턴 DC | us-east |
|영국 | 런던 | eu-gb |
|독일 | 프랑크푸르트 | eu-de |
|시드니 |시드니 | au-syd |
| AP 북부 | 도쿄 | jp-tok |
{: caption="표 1. 새 위치 이름" caption-side="top"}

### 다른 사용자에게 계정 관리 서비스 지정
신규 기준일: 2018년 10월 30일

{{site.data.keyword.cloud_notm}} IAM(Identity and Access Management)을 통해 공통 계정 관리 태스크를 수행하는 기능을 계정의 다른 사용자에게 허용할 수 있습니다. 하나 또는 모든 사용 가능 계정 관리 서비스에서 액세스 정책을 작성하면 사용자 초대 및 제거, 액세스 그룹 관리, 서비스 ID 관리, 사설 카탈로그 서비스 유지보수, 청구 모니터링 및 사용량 추적과 같은 책임을 쉽게 위임할 수 있습니다. 액세스 정책을 설정하는 데 사용할 수 있는 네 개의 개별 계정 관리 서비스 및 모든 서비스 옵션이 있습니다.

* 사용자를 초대 및 제거하기 위한 사용자 관리
* 액세스 권한 작성, 편집, 삭제, 업데이트, 지정을 위한 IAM 액세스 그룹 
* 계정에서 서비스 ID 및 연관된 API 키에 대한 액세스 권한 보기, 작성, 삭제, 지정을 위한 IAM ID 서비스
* 사설 카탈로그 오퍼링을 보고 오퍼링에 대한 메타데이터 및 가시성을 업데이트하기 위한 글로벌 리소스 카탈로그
* 청구 및 사용량 추적에 대한 액세스는 물론, 지정된 역할에 기반하여 각 개별 계정 관리 서비스 옵션에 대한 액세스를 위한 모든 계정 관리 서비스.

지정된 역할 및 관련 정책을 보유하고 있는 관련 계정 관리 서비스에 기반하여 사용자가 수행할 수 있는 태스크에 대한 자세한 정보는 [계정 관리 서비스에 대한 예제 플랫폼 관리 역할 및 조치](/docs/iam/users_roles.html#platformrolestable2)를 참조하십시오.


### 리소스 검색
신규 기준일: 2018년 7월 17일

{{site.data.keyword.cloud_notm}} 콘솔의 어느 위치에서나 리소스를 검색할 수 있습니다. 콘솔 메뉴 표시줄의 검색 필드에 리소스의 이름을 입력하십시오. 검색을 활성화하려면 슬래시 키(/)를 누르십시오.

### 동적으로 액세스 그룹에 연합 사용자 추가
신규 기준일: 2018년 7월 12일

특정 ID 속성을 기반으로 액세스 그룹에 연합 사용자를 자동으로 추가하기 위한 동적 규칙을 작성할 수 있습니다. 사용자가 연합 ID를 사용하여 로그인하면 사용자가 설정한 규칙에 따라 ID 제공자의 데이터가 동적으로 사용자를 액세스 그룹에 맵핑합니다. 자세한 정보는 [액세스 그룹에 대한 동적 규칙 작성](/docs/iam/accessgroup_rules.html#creating-dynamic-rules-for-access-groups)을 참조하십시오.

### 서비스 ID 및 API 키 보호
신규 기준일: 2018년 6월 1일

서비스 ID 또는 API 키가 삭제되어 중단이 발생하는 상황을 방지하기 위해 UI 또는 CLI를 사용하여 서비스 ID 및 API 키를 잠그는 옵션이 있어야 합니다. 서비스 ID를 잠그면 액세스 정책 변경, 삭제 또는 지정뿐만 아니라 서비스 ID와 연관된 API 키 작성 또는 삭제를 수행할 수 없습니다. 자세한 정보는 [서비스 ID 잠금](/docs/iam/serviceid.html#locking-a-service-id) 및 [API 키 잠금](/docs/iam/userid_keys.html#locking-an-api-key)을 참조하십시오.

### Lite 계정을 구독 계정으로 업그레이드
신규 기준일: 2018년 5월 31일

이제 {{site.data.keyword.Bluemix_notm}} 콘솔에서 직접 Lite 계정을 구독 계정으로 업그레이드할 수 있습니다. 구독 계정을 사용하면 플랫폼과 인프라 오퍼링을 둘 다 사용하고 월별 지출 및 기간 약정을 통해 할인 가격을 이용할 수 있습니다. 월별 지불 스케줄에 따라 고정 비용을 청구하지만, 필요에 따라 주문 양을 조정하는 유연성도 제공합니다. 자세한 정보는 [구독 계정 FAQ](/docs/billing-usage/billing-faq.html#subscription-faqs)를 참조하십시오. 

### {{site.data.keyword.Bluemix_notm}} CLI 리브랜딩
신규 기준일: 2018년 5월 15일

{{site.data.keyword.Bluemix_notm}} CLI 명령은 `bluemix` 및 `bx`에서 **ibmcloud**로 변경되었습니다. 하지만 `bluemix` 및 `bx` CLI 명령은 나중에 제거할 때까지 사용할 수 있습니다. 이제 단축 이름은 없으며 전체 이름 **ibmcloud**만 사용됩니다. 

### {{site.data.keyword.Bluemix_notm}} 계정에 대한 다단계 인증
신규 기준일: 2018년 5월 02일

다단계 인증(MFA)은 로그인 중에 모든 사용자가 IBM ID와 비밀번호뿐만 아니라 시간 기반의 일회성 패스코드를 제공하도록 요구하여 사용자 계정에 추가 보안 계층을 추가합니다. 일반적으로 2단계 인증(2FA)이라고도 합니다. MFA는 계정별로 사용으로 설정되며 일단 설정되고 나면 계정의 모든 사용자들은 추가적인 보안 방법을 사용하여 로그인해야 합니다.

자세한 정보는 [IBM Cloud Platform now adds support for Multi-Factor Authentication](https://www.ibm.com/blogs/bluemix/2018/05/ibm-cloud-platform-now-adds-support-multi-factor-authentication/){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘") 블로그 게시물을 참조하십시오.

### 액세스 그룹을 사용하여 신속하게 액세스 지정
신규 기준일: 2018년 4월 3일

가능한 한 가장 적은 정책을 사용하여 신속하게 액세스를 지정할 수 있습니까? 이제 액세스 그룹으로 이를 수행할 수 있습니다. 액세스 그룹을 사용하면 사용자 및 서비스 ID 세트를 그룹화하고 그룹의 모든 구성원에 적용하는 단일 정책을 지정할 수 있습니다. 액세스 그룹을 사용하면 액세스 관리에 사용하는 시간을 계정의 사용자와 서비스 ID로 제한할 수 있습니다. 세부사항은 블로그 게시물 [새 기능: 액세스 그룹](https://www.ibm.com/blogs/bluemix/2018/04/access-groups/){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")을 확인하십시오.

### SoftLayer와 {{site.data.keyword.Bluemix_notm}} 계정 연결
신규 기준일:  2018년 3월 1일

단일 위치, {{site.data.keyword.Bluemix_notm}} 콘솔에 로그인하기 위해 SoftLayer 계정을 {{site.data.keyword.Bluemix_notm}} 계정에 연결하고 IaaS(infrastructure as a service) 및 PaaS(platform as a service) 리소스 모두에 액세스할 수 있습니다. {{site.data.keyword.Bluemix_notm}}를 처음 사용하는 경우 무료 {{site.data.keyword.Bluemix_notm}} Lite 계정을 얻으려면 계정을 작성하여 연결하십시오. 또는 이미 PaaS 리소스가 있는 {{site.data.keyword.Bluemix_notm}} 계정을 보유하는 경우 IaaS와 PaaS 리소스에 대해 단일 청구를 받도록 계정을 연결하십시오. 계정을 빠르게 연결하려면 [IaaS 및 PaaS 계정에 연결하기 위한 단계](https://www.ibm.com/blogs/bluemix/2018/03/follow-steps-link-iaas-paas-accounts/){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")를 확인하십시오.


### {{site.data.keyword.Bluemix_notm}} Foundry Service 미국 동부 지역은 지금 사용 가능
신규 기준일: 2017년 12월 15일

새로운 미국 동부 데이터 센터가 워싱턴, DC에 있습니다. 이 새 지역은 `us-east.bluemix.net` 엔드포인트를 사용하여 도달할 수 있습니다. 이 새 지역에서 구매할 수 있는 서비스에 대한 자세한 정보는 [지역별 서비스](/docs/resources/services_region.html#services_region)를 참조하십시오.

### EU의 리소스에 대한 지원
신규 기준일: 2017년 12월 14일

서비스 및 데이터 센터가 유럽에 위치한 경우 {{site.data.keyword.Bluemix_notm}}는 이제 유럽에서 데이터를 보호할 수 있는 추가 기능을 제공합니다. 유럽에 위치한 고객 성공 팀에서 제공하는 서비스를 요청할 수 있습니다. 이 지원은 연중무휴로 제공됩니다. 자세한 정보는 [EU 지원 옵션 사용](/docs/billing-usage/eusupported.html#bill_eusupported) 및 [EU의 리소스에 대한 지원 요청](/docs/get-support/howtogetsupport.html#eusupported)을 참조하십시오.

### TLS 1.0 및 1.1에 대한 지원 중단
신규 기준일: 2017년 11월 28일

2018년 3월 1일부로 {{site.data.keyword.Bluemix_notm}}는 보안 및 데이터 개인정보 보호에 대한 업계의 우수 사례에 따라 철저하게 보안되는 클라우드를 제공하고자 하는 노력의 일부로 여러 클라우드 제품 및 서비스에서 TLS 1.0 및 TLS 1.1에 대한 지원을 중단합니다. 이 변경사항이 적용되는 방법과 수행해야 하는 조치에 대해 자세히 알아보려면 [LS 1.0 및 1.1에 대한 지원 중단](/docs/troubleshoot/appsectls.html)을 참조하십시오.

### 계정에서 리소스를 구성하는 새로운 방법
신규 기준일: 2017년 11월 16일

리소스 그룹은 사용자가 계정 리소스의 사용자 정의할 수 있는 그룹화를 작성하고 IAM(Identity and Access Management)을 사용하여 관리되는 계정에서 그룹 및 리소스에 대한 액세스를 작성하기 위한 새로운 방법입니다. 모든 사용자는 기본 리소스 그룹을 사용하여 시작합니다. 이 리소스 그룹의 이름을 변경하고 카탈로그에서 새 서비스 인스턴스를 작성할 때 새 서비스 인스턴스를 리소스 그룹에 추가할 수 있습니다.

종량과금제 또는 구독 계정이 있는 사용자는 추가 리소스 그룹을 작성하여 할당량을 관리하고 리소스 세트에 대한 청구 사용량을 볼 수 있도록 합니다. 한 번에 둘 이상의 서비스에 대한 사용자 액세스를 보다 쉽게 지정할 수 있도록 리소스를 그룹화할 수도 있습니다. 계정에 대한 리소스 그룹 관련 작업에 대해 자세히 알아보려면 [리소스 그룹 관리](/docs/account/resourcegroups.html#rgs)를 참조하십시오.

### {{site.data.keyword.Bluemix_notm}} IAM에 대한 업데이트
신규 기준일: 2017년 11월 16일

{{site.data.keyword.Bluemix_notm}} 계정 내 [리소스 그룹](/docs/overview/resource-groups.html#whatis)의 도입은 액세스 권한을 지정할 수 있는 새로운 방법을 제시했습니다. 사용자 및 서비스 ID는 한 번에 둘 이상의 리소스에 대한 액세스를 신속하게 지정할 수 있도록 리소스 그룹 내에 모든 서비스에게 액세스 권한을 지정할 수 있습니다. 또한 리소스 그룹 내 일부 서비스에만 액세스 권한을 지정하여 각 사용자 또는 서비스 ID에 대한 액세스 그룹을 사용자 정의하거나 서비스 인스턴스 레벨로 개별 리소스에 대한 액세스 권한만 지정하도록 선택합니다.

IAM을 사용하여 활용할 수 있는 기능에 대한 자세한 정보는 [IAM에서 제공하는 기능](/docs/iam/index.html#features)을 참조하십시오.

### 대시보드 보기 사용자 정의
신규 기준일: 2017년 11월 16일

{{site.data.keyword.Bluemix_notm}} 콘솔의 대시보드에서 계정의 모든 리소스를 보고 관리할 수 있습니다. 이제 필터를 설정하여 보기를 사용자 정의할 수 있습니다. 예를 들어, 리소스 그룹별로 필터링하여 리소스 그룹의 특정 리소스를 볼 수 있습니다. 또한 지역 또는 Cloud Foundry 영역별로 필터링할 수도 있습니다. 추가 세부사항은 [대시보드에서 리소스 관리](/docs/overview/ui.html#dashboardview)를 참조하십시오.


### 지원 센터
신규 기준일: 2017년 11월 2일

이제 정보를 검색하고, 개발자 커뮤니티에 질문을 게시하고, 티켓을 관리할 수 있는 새 지원 센터가 제공됩니다. {{site.data.keyword.Bluemix_notm}} 콘솔 메뉴 표시줄에서 **지원 > 지원 센터**로 이동하십시오.

### IBM Cloud 소개
신규 기준일: 2017년 10월 31일

Bluemix는 이제 IBM Cloud입니다. 새로운 이름 사용 외에는 변경사항이 없습니다. 계속해서 쉽게 앱과 서비스를 빌드하고 실행할 수 있습니다. 추가 세부사항은 [IBM Cloud Blog](https://www.ibm.com/blogs/bluemix/2017/10/bluemix-is-now-ibm-cloud/){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")를 참조하십시오.

### Lite 계정
신규 기준일: 2017년 10월 31일

Lite 계정은 시간 제한 없이 무료로 서비스를 선택해 볼 수 있는 액세스 권한을 제공하는 새 계정 유형입니다. 이 새 계정에 사용량 추적과 효율성 기능도 포함하여 리소스를 보다 잘 관리할 수 있도록 합니다. 사용 가능한 항목에 대해 자세히 알아보려면 [계정 유형](/docs/account/index.html#liteaccount)을 참조하십시오.

### Identity and Access Management 애플리케이션 인증 기능
신규 기준일: 2017년 10월 6일

IAM(Identity and Access Management)은 이제 서비스 ID를 작성할 수 있는 기능을 제공하여 {{site.data.keyword.Bluemix_notm}} 서비스로 인증하도록 앱에 사용할 수 있는 ID로 간주할 수 있습니다. 개별 사용자 인증 정보를 사용하는 대신 서비스 ID는 해당 ID를 사용하여 애플리케이션 인증에 대한 액세스 권한의 레벨을 제어할 수 있도록 서비스 ID에 지정되는 서비스 정책의 양식으로 인증된 API 키 및 액세스 권한을 사용하여 작성될 수 있습니다.

이 기능의 장점 및 시작하는 방법에 대한 자세한 정보는 [Introducing IBM Cloud IAM Service IDs and API Keys](https://www.ibm.com/blogs/bluemix/2017/10/introducing-ibm-cloud-iam-service-ids-api-keys/){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")를 참조하십시오.

### {{site.data.keyword.Bluemix_notm}} 글로벌 카탈로그
신규 기준일: 2017년 7월 27일

콘솔의 단일 위치에서 퍼블릭 지역을 관리하도록 최근 콘솔 업데이트를 확장하여 {{site.data.keyword.Bluemix_notm}}은 이제 카탈로그에서 좀 더 간소화된 프로세스를 선택하는 항목을 선택하고 배치하는 프로세스를 작성하는 글로벌 카탈로그를 보유하게 되었습니다. 콘솔에서 선택한 지역에 관계없이 이제 카탈로그의 모든 퍼블릭 지역에서 사용 가능한 모든 서비스를 볼 수 있습니다. 카탈로그에서 파일만 선택하면 서비스를 사용할 수 있는 지역을 볼 수 있고 서비스를 배치할 위치를 선택할 수 있습니다.

카탈로그에 대한 최신 업데이트에 대한 자세한 정보는 [A global {{site.data.keyword.Bluemix_notm}} catalog makes building things easier](https://www.ibm.com/blogs/bluemix/2017/07/global-bluemix-catalog-makes-building-things-easier/){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")를 참조하십시오.

### {{site.data.keyword.Bluemix_notm}} 콘솔 업데이트
신규 기준일: 2017년 5월 23일

이제 업데이트된 {{site.data.keyword.Bluemix_notm}} 콘솔을 통해 단일 위치에서 퍼블릭 지역을 관리할 수 있습니다. 지역 선택기는 리소스에 대한 간소화된 액세스를 제공하고 기타 개선사항에는 고가용성 및 향상된 성능이 포함됩니다.

이 업데이트에 대한 자세한 정보는 [New Global Bluemix UI for Higher Availability and More](https://www.ibm.com/blogs/bluemix/2017/05/new-global-bluemix-ui-higher-availability/){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")를 참조하십시오.

### ID 및 액세스 관리
신규 기준일: 2017년 5월 01일

최신 업데이트 및 개선사항을 통해 이제 {{site.data.keyword.Bluemix_notm}} 계정 소유자 또는 관리자는 새 통합 액세스 제어 UI를 사용하여 다음 기능을 활용할 수 있습니다.
 * Kubernetes 서비스 및 기타 서비스에서 새 액세스 제어 기능을 채택함에 따라 Kubernetes 서비스 및 기타 서비스에 대한 사용자의 세분화된 액세스 권한을 관리합니다.
 * 조직 내에서 서비스 정책 및 Cloud Foundry 역할을 사용자에게 지정합니다.

또한 {{site.data.keyword.Bluemix_notm}} 플랫폼 사용자는 사용자 ID와 연관된 API 키를 작성, 삭제 및 나열할 수 있습니다. 또한 플랫폼 사용자는 API 또는 CLI를 사용할 때 인증할 API 키를 사용할 수 있습니다.

최근에 연결된 IaaS-PaaS 계정에서 SoftLayer 고객 포털 또는 {{site.data.keyword.Bluemix_notm}} 콘솔에 사용자를 개별적으로 추가할 필요 없이 통합 방식으로 사용자를 관리하도록 통합 사용자 관리 기능이 개선되었습니다.

최근 업데이트에 대한 자세한 정보는 [Introducing Identity & Access Management](https://www.ibm.com/blogs/bluemix/2017/05/introducing-identity-access-management/){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘") 블로그 게시물을 확인하십시오.

### {{site.data.keyword.Bluemix_notm}} 문서의 디자인 변경사항 탐색
신규 기준일: 2017년 4월 13일

이 탐색 업데이트를 사용하여 컨텐츠가 문서 전체에 구성되는 방식을 보다 잘 이해하고 좀 더 효율적으로 관련 컨텐츠를 찾을 수 있을 것으로 간주합니다. 더 적은 컨텐츠의 중첩된 계층을 사용하면 {{site.data.keyword.Bluemix_notm}}로 성공에 필요한 문서를 찾기 위해 노력할 필요가 없습니다.


## {{site.data.keyword.Bluemix_local_notm}} 및 {{site.data.keyword.Bluemix_dedicated_notm}}
{: #dedicatedandlocal}

### 관리 콘솔에 대한 2월 업데이트
{: #febadminconsole}
신규 기준일: 2018년 2월 28일

2018년 2월 최신 업데이트를 사용하면 다음과 같은 새로운 기능을 사용할 수 있습니다.

#### 유지보수 업데이트 관리를 위한 새로운 권한

새 사용자 권한은 유지보수 업데이트를 전용 환경에 배치할 수 있는 시점을 지정하는 유지보수 업데이트 창의 설정 및 유지보수 업데이트 승인과 재스케줄링을 할 수 있도록 특별히 도입되었습니다.
자세한 정보는 [동영상 데모](https://youtu.be/7c7jyp_JJWU){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")를 참조하십시오.

### 관리 콘솔에 대한 12월 업데이트
{: #decemberadminconsole}
신규 기준일: 2017년 12월 14일

12월의 최신 업데이트 및 개선을 통해 다음과 같은 새 기능을 사용할 수 있습니다.

#### 평균 CPU 사용량 임계값에 대한 알림 구독

평균 CPU는 알림 구독에서 임계값 유형으로 추가되었습니다. 이제 CPU 사용량(모든 DEA 셀 및 Diego 셀)이 특정 임계값 이상으로 증가하거나 이하로 감소할 때 알림을 받을 수 있습니다.

#### EU에서 클라우드 시스템에 대한 액세스 제어

클라우드 리소스를 지원하기 위해 EU의 새 기능과 결합하여(프랑크프루트부터 시작) 관리 콘솔은 이제 IBM 담당자를 통해 액세스를 제어하는 정책을 정의할 수 있는 기능을 갖게 됩니다. 액세스 제어 정책을 관리하고, 액세스 요청을 보고, 요청에 대한 조치를 취하고, 히스토리를 추적할 수 있습니다.

#### 보안 보고서의 향상된 정보

보안 보고서에는 이제 사용자 및 조직의 고유 ID 외에도 사용자에게 익숙한 이름도 포함됩니다.

### 관리 콘솔에 대한 8월 업데이트
{: #augustadminconsole}
신규 기준일: 2017년 8월 31일

8월의 최신 업데이트 및 개선을 통해 다음과 같은 새 기능을 사용할 수 있습니다.

#### {{site.data.keyword.cloudant_short_notm}} 서비스 사용량 메트릭에 대한 업데이트

  * {{site.data.keyword.cloudant_short_notm}}에 대한 사용량 메트릭의 계산은 사용된 총량(GB)을 반영하고 {{site.data.keyword.cloudant_short_notm}} 클러스터의 모든 노드에 사용 가능하도록 업데이트되었습니다. 일반적으로, {{site.data.keyword.cloudant_short_notm}} 클러스터에는 3개의 노드가 포함되고 데이터베이스의 문서는 고가용성 및 재해 복구를 위해 클러스터의 모든 노드 간에 복제됩니다. 8월 업데이트를 사용하면 {{site.data.keyword.cloudant_short_notm}} 다이얼(_Resource Usage > Services_ 보기에서 사용 가능)의 용량 메트릭은 클러스터의 모든 노드 전반에 영역을 표시합니다. 예를 들어, 단일 {{site.data.keyword.cloudant_short_notm}} 클러스터에 3개의 노드가 포함되어 있으며, 각각 1000GB의 용량이 있으면 용량 한계가 3000GB로 표시됩니다. 해당 용량의 1500GB가 사용되면 {{site.data.keyword.cloudant_short_notm}} 사용량 메트릭은 50%가 됩니다.

#### 유지보수 업데이트의 스케줄링에 대한 업데이트

  * 전용 환경이 시스템 업데이트의 개발에 사용 가능할 때 {{site.data.keyword.Bluemix_dedicated_notm}}에서 고객이 날짜 및 시간을 관리할 수 있습니다. 전용 환경에 유지보수 업데이트를 배치할 수 있고 배치할 수 없는 경우 고객은 날짜와 시간을 표시하는 가용성 창을 정의할 수 있습니다. 8월 업데이트에서는 _Available Update Windows_가 _Update Windows_로 이름이 바뀌고 _Unavailable Update Windows_가 _Blackout Windows_로 이름이 바뀝니다. 용어 변경 이상으로, 고객에게 이제 블랙아웃(사용 불가능) 날짜를 정의하기 위해 더 많은 유연성과 여유가 제공됩니다. 요청되면 블랙아웃 날짜는 IBM에서 승인해야 하며, 승인을 받는 데 걸리는 시간은 경우에 따라 다릅니다. 요청한 블랙아웃 날짜가 승인되면 IBM에서는 사용 불가능한 기간 동안의 현재 스케줄링된 기존 업데이트를 모두 취소합니다. IBM에서는 이러한 업데이트에 대한 새 레코드를 작성한 다음 승인된 블랙아웃 날짜를 제외한 날짜로 스케줄링합니다.

자세한 정보는 [동영상 데모](https://bit.ly/2eCQNvu){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")를 참조하십시오.

### 관리 콘솔에 대한 7월 업데이트
{: #julyadminconsole}
신규 기준일: 2017년 7월 31일

7월의 최신 업데이트 및 개선을 통해 다음과 같은 새 기능을 사용할 수 있습니다.

#### 리소스 사용량 히스토리 기능에 대한 업데이트

  * 이전 업데이트(6월)에서 메모리 및 디스크 사용량에 대한 히스토리 보기는 지난 48시간, 30일 및 5개월 동안의 데이터 사용량의 표시를 도입했습니다. 최근 6월 업데이트에서 리소스 사용량 히스토리 기능은 리소스 사용량 데이터를 표시하기 위해 시간 범위의 사용자 정의를 허용하도록 확장되었습니다. 시간별, 일별 및 월별 보기는 계속 표시되지만, 사용자는 이제 메모리 및 디스크 사용량 메트릭을 표시하기 위해(예: 2017년 7월 1일부터 15일 동안 메모리 사용량 표시) 시작 일/시간 및 지속 기간을 지정할 수 있습니다.
  * 새 CLI 명령이 CLI에 리소스 메트릭 히스토리를 표시하도록 도입되었습니다. 명령의 매개변수 및 사용량 예제는 `_cf ba resource-metrics-history -help_`를 입력하여 확인할 수 있습니다.

자세한 정보는 [동영상 데모](https://youtu.be/QBij0jB5qAk){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")를 참조하십시오.

### 관리 콘솔에 대한 6월 업데이트
{: #juneadminconsole}
신규 기준일: 2017년 6월 26일

6월의 최신 업데이트 및 개선을 통해 다음과 같은 새 기능을 사용할 수 있습니다.

#### 리소스 사용량 페이지에 대한 업데이트

  * 시스템 리소스
    * 메모리 및 디스크의 히스토리 보기는 48시간, 30일 및 5개월 동안의 데이터를 표시하도록 업데이트되었습니다.
    * 히스토리 보기를 생성하기 위해 관리 콘솔 메트릭 API를 사용하는 방법을 표시하는 자세히 보기 링크가 제공됩니다.
  * 애플리케이션
    * 환경에서 모든 애플리케이션에 대한 사용량 정보를 제공합니다.
    * 애플리케이션 이름, 실제 메모리, 예약된 메모리, 실제 디스크, 예약된 디스크, 실제 CPU 또는 조직 이름으로 정렬합니다.
    * 검색은 애플리케이션 이름 및 조직 이름별로 결과를 필터링하도록 제공됩니다.
    * 애플리케이션 보기를 생성하기 위해 관리 콘솔 메트릭 API를 사용하는 방법을 표시하는 자세히 보기 링크가 제공됩니다.

자세한 정보는 [리소스 사용량](/docs/hybrid/index.html#resourceusage)을 참조하십시오.

#### 메트릭용 API에 대한 업데이트

  * 메모리 및 디스크 이용에 대한 일 또는 월별 평균을 제공하여 환경 통계가 추가됩니다.

자세한 정보는 [메트릭용 API](/docs/hybrid/index.html#envappmetricsapi)를 참조하십시오.


### 관리 콘솔에 대한 5월 업데이트
{: #mayadminconsole}
신규 기준일: 2017년 5월 30일

5월의 최신 업데이트 및 개선을 통해 다음과 같은 새 기능을 사용할 수 있습니다.

 * 상태 페이지에 대한 개선사항으로 {{site.data.keyword.Bluemix_notm}} 플랫폼 및 런타임에 영향을 주는 인시던트에 대한 좀 더 세부적인 진단이 포함됩니다.
 * 보안 보고서 및 로그 페이지에 대한 개선사항:
   * 보고서는 이제 테이블 형식으로 표시되며, 보고서 카테고리, 파일 이름 또는 작성 날짜별로 정렬하는 기능을 포함하여 보고서 찾아보기 및 검색이 단순화됩니다.
   * 다중 카테고리의 동시 필터링을 포함한 향상된 필터링
   * 보고서의 컨텐츠를 표시하기 위한 전체 화면 모드
   * "보고서 쓰기" 권한이 있는 관리 사용자를 위한 보고서 삭제 기능
   * 지속적인 스크롤을 통해 요청 시 계속해서 로딩하여 보고서 목록을 좀 더 빠르게 표시(결과적으로 전체 성능이 향상됨)
 * 요청 시간의 최대 3개월 이전부터 최대 1주일의 시간 범위 내에서 요청 시 보안 보고서를 요청할 수 있습니다. 관리 사용자가 기능을 사용하기 전에 일부 환경에 특정한 구성이 필요합니다. 관리 사용자는 이 기능에 대한 "보고서 쓰기" 권한이 필요합니다.

### 관리 콘솔에 대한 4월 업데이트
{: #apriladminconsole}
신규 기준일: 2017년 5월 2일

4월의 최신 업데이트 및 개선을 통해 다음과 같은 새 기능을 사용할 수 있습니다.

 * {{site.data.keyword.Bluemix_notm}} 데디케이티드 및 로컬 환경을 위해 새로 디자인된 상태 앱. 컴포넌트 이름 또는 게시 날짜별로 빠르게 검색할 수 있습니다. 컴포넌트 상태 게시 보기 및 사용자 환경에 특정한 알림 간을 전환할 수도 있습니다. 자세한 정보는 [New {{site.data.keyword.Bluemix_notm}} Status Page](https://www.ibm.com/blogs/bluemix/2017/05/new-bluemix-status-page/){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘") 블로그 게시물을 참조하십시오.
 * 리소스 사용량 타일에서 서비스 선택을 위한 서비스 사용량 데이터. 지원되는 서비스와 새 보기에서 예상할 수 있는 사항에 대한 자세한 정보는 [서비스 사용량 세부사항](/docs/hybrid/index.html#servicesresourceusage)을 참조하십시오.

## 컴퓨팅
{: #compute_category}

### {{site.data.keyword.containerlong_notm}}에서 다중 구역 클러스터 작성
신규 기준일: 2018년 7월 10일

클러스터 및 앱 가용성을 향상시키고 싶으십니까? 이제 클러스터를 대도시 지역의 여러 구역에서 확장할 수 있습니다. 자세한 정보는 [{{site.data.keyword.containershort_notm}}에서 다중 구역 클러스터 작성](cs_clusters.html#multizone)을 참조하십시오.

### {{site.data.keyword.containerlong_notm}}에 대한 Kubernetes 대시보드 액세스

{{site.data.keyword.containerlong_notm}}는 이제 {{site.data.keyword.Bluemix_notm}} 콘솔을 통해 Kubernetes 대시보드에 대한 직접 액세스를 지원합니다. 이러한 대시보드에 대한 간소화된 접근 방식을 통해 클러스터 관리 및 리소스 시각화에 사용자의 경험을 향상시켜 줍니다. [{{site.data.keyword.Bluemix_notm}} 블로그](https://www.ibm.com/blogs/bluemix/2018/04/kubernetes-dashboard-access/){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")에서 자세한 정보를 확인하십시오.

### 빌드팩의 최신 업데이트

최신 업데이트의 누적 목록을 보려면 다음 페이지를 방문하십시오.

* [SDK for Nodejs 빌드팩의 최신 업데이트](/docs/runtimes/nodejs/updates.html#latest_updates)
* [Liberty 빌드팩의 최신 업데이트](/docs/runtimes/liberty/updates.html#latest_updates)
* [ASP.NET Core 빌드팩의 최신 업데이트](/docs/runtimes/dotnet/updates.html#latest_updates)
* [IBM XPages for {{site.data.keyword.Bluemix_notm}} 빌드팩의 최신 업데이트](/docs/starters/xpages/index.html#updates)

### {{site.data.keyword.containerlong_notm}}의 최신 업데이트

{{site.data.keyword.containerlong_notm}}는 2017년 5월에 Kubernetes 아키텍처를 발표했습니다. 단일 확장 가능한 컨테이너 그룹의 이전 아키텍처는 이제 [2017년 12월 5일부로 더 이상 완전히 사용되지 않습니다.](https://www.ibm.com/blogs/bluemix/2017/07/deprecation-single-scalable-group-container-service-bluemix-public/){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")  

[{{site.data.keyword.Bluemix_notm}}](/docs/containers/container_index.html)에서 원시 Kubernetes 환경을 시작하기에 대한 자세한 정보는 문서를 참조하십시오. 질문이 있는 경우 Slack(https://ibm-container-service.slack.com/) 사이트에 질문을 게시할 수 있습니다.

### 새 Liberty for Java 빌드팩 v3.11
신규 기준일: 2017년 7월 17일

Liberty 빌드팩 v3.11은 새 월별 Liberty 런타임 버전을 제공하고 기타 개선사항을 포함합니다. 월별 Liberty 런타임 버전은 [2017.7.0.0](https://developer.ibm.com/wasdev/blog/2017/07/07/beta-websphere-liberty-tools-july-2017/) 릴리스로 업데이트되었습니다. IBM JDK는 8.0.4.7 및 7.1.4.5 버전으로 업데이트되었습니다. 빌드팩은 App Management 유틸리티 및 Auto-Scaling 에이전트의 업데이트된 버전도 제공합니다. 기본 Cloudant Library는 이제 공식 [java-cloudant](https://github.com/cloudant/java-cloudant)이며, [Ektorp library](https://github.com/helun/Ektorp)는 계속해서 옵션으로 사용 가능합니다. 이 변경사항에 대한 세부사항은 [블로그 게시물](https://www.ibm.com/blogs/bluemix/2017/05/default-library-change-cloudant-auto-wiring-liberty-buildpack/)을 참조하십시오. 애플리케이션의 메모리가 512MB 미만이면 이제 기본 힙 크기 비율은 50%가 되고, 512MB를 초과하면 기본 힙 크기 비율은 75%가 됩니다. 이제 새 스테이징 태스크 로그가 생성되어 스테이징 오류를 더 쉽게 디버그할 수 있습니다. 자세한 정보는 [최신 업데이트](https://console.ng.bluemix.net/docs/runtimes/liberty/updates.html) 문서를 참조하십시오.

### 새 Liberty for Java 빌드팩 v3.10
신규 기준일: 2017년 6월 12일

Liberty 빌드팩 v3.10은 새 분기별 및 월별 Liberty 런타임 버전을 제공하고 기타 개선사항을 포함합니다. 기본 Liberty 런타임 버전이 17.0.0.2로 업데이트되었습니다. 월별 Liberty 런타임 버전이 [2017.5.0.0](https://developer.ibm.com/wasdev/blog/2017/05/12/beta-websphere-liberty-tools-may-2017/){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘") 릴리스로 업데이트되었습니다. 빌드팩은 App Management 유틸리티 및 Extreme Scale Client의 업데이트된 버전도 제공합니다. 추가 정보는 [최신 업데이트](/docs/runtimes/liberty/updates.html) 문서를 참조하십시오.

### 새 SDK for Node.js 빌드팩 v3.12
신규 기준일: 2017년 5월 16일

SDK for Node.js 빌드팩 v3.12는 IBM SDK for Node.js 버전 0.12.17, 0.12.18, 4.8.0, 4.8.2, 6.10.0 및 6.10.2를 제공합니다. 이제 기본값은 최신 4.x에서 최신 6.x로 변경되었으므로 현재 6.10.2입니다. 주요 버전 변경사항이 발생하면 기본값에 의존하는 앱에 영향을 줄 수 있습니다. 문제점 방지에 대한 자세한 정보는 [Node.js version long-term support and the SDK for Node.js buildpack](https://www.ibm.com/blogs/bluemix/2016/11/node-version-support-and-sdk-buildpack/){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")을 참조하십시오.

새 런타임 외에도, 이 릴리스에는 App Management Health Center 핸들러와 Node.js 버전 6.9.5 및 6.10.0의 문제에 대한 빌드팩 버그 수정사항이 포함되어 있습니다.

### 새 Liberty for Java 빌드팩 v3.9
신규 기준일: 2017년 4월 27일

Liberty 빌드팩 v3.9는 새 월별 Liberty 런타임 버전을 제공하고 기타 개선사항을 포함합니다. 기본 Liberty 런타임 버전은 PI77770, PI77605, IFPI77438 및 IFPI79275 iFixes를 포함하도록 업데이트되었습니다. 월별 Liberty 런타임 버전은 [2017.3.0.0](https://developer.ibm.com/wasdev/blog/2017/03/14/beta-websphere-liberty-tools-march-2017/){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘") 릴리스로 업데이트되었습니다. 애플리케이션을 다시 시작하여 힙 메모리를 좀 더 쉽게 변경할 수 있도록 메모리 계산이 스테이징에서 시작 프로세스로 이동되었습니다. 빌드팩은 Auto-Scaling 서비스 에이전트 및 Extreme Scale Client의 업데이트된 버전도 제공합니다. 추가 정보는 [최신 업데이트](/docs/runtimes/liberty/updates.html) 문서를 참조하십시오.

## 서비스
{: #services_category}

### {{site.data.keyword.cloudant_short_notm}}의 최신 업데이트
신규 기준일: 2018년 9월 28일

{{site.data.keyword.cloudant_short_notm}}에 대한 [최신 업데이트 ](/docs/services/Cloudant/release_info/release_notes.html#release-notes){:new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")의 전체 목록을 보려면 다음 페이지를 방문하십시오.

### {{site.data.keyword.IBM_notm}} {{site.data.keyword.DRA_short}} GA(General Availability) 소개
신규 기준일: 2018년 9월 20일

{{site.data.keyword.DRA_short}} 서비스가 미국 남부, 독일 및 영국 지역에서 출시되었습니다.

{{site.data.keyword.DRA_short}}는 팀이 생산성, 효율성 및 제품 출시 소요 시간을 향상시키는 데 도옴을 주며, DevOps 도구의 데이터를 사용하여 성공 여부를 쉽게 판단하고 코드 품질을 개선하는 데 도움을 줍니다. 이 서비스는 기업이 자신의 모든 코드베이스 및 팀 전체의 DevOps 활동을 파악할 수 있는 단일 도구를 제공합니다.

* **속도**: {{site.data.keyword.DRA_short}}에서는 모든 애플리케이션에 대한 모든 분석을 하나의 대시보드에서 보여줍니다.
* **품질**: 게이트 배치 정책을 구현하여 위험한 릴리스를 줄이십시오. 예를 들어 선택된 허용 한계가 있는, 코드 적용 범위에 대한 정책이 있는 경우 {{site.data.keyword.DRA_short}}는 정의된 허용 한계를 만족시키지 못하는 코드의 릴리스를 차단합니다. 이러한 정책은 시간이 경과함에 따라 배치 프로세스의 전체적인 품질을 향상시킵니다. 
* **제어**: 코드 적용 범위, 단위 테스트 및 기타 도구를 사용하여 팀의 DevOps 사용 (상태)동향에 대한 팀의 대응 결과를 시간 경과에 따라 측정하십시오. 이러한 (상태)동향은 DevOps 사용을 더 효과적으로 관리하는 데 도움을 줍니다.

### {{site.data.keyword.security-advisor_long_notm}}은 현재 베타입니다!
신규 기준일: 2018년 9월 5일

{{site.data.keyword.security-advisor_short}}에서 새 기능을 추가했으며 이제 베타 서비스로 사용 가능합니다.  {{site.data.keyword.security-advisor_short}}에서는 한 대시보드를 통해 중앙에서 {{site.data.keyword.Bluemix_notm}} 보안을 관리합니다. 정보의 중앙 집중화 외에도 이 서비스에서는 쉽게 이동할 수 있는 타일에 중요한 보안 정보를 요약하므로 보안 문제가 발견된 시기를 명확하게 표시할 수 있습니다. 타일을 클릭하면 우선순위화된 문제, 히스토리 및 경보 세부정보를 드릴다운할 수 있습니다. 문제를 수정하려면 한 번 더 드릴다운하기만 하면 됩니다. 그러면 모든 세부사항 외에도 위협을 제거하고 환경을 안전하게 유지하기 위한 추천 수정사항을 얻을 수 있습니다.

{{site.data.keyword.security-advisor_short}}는 {{site.data.keyword.Bluemix_notm}} 환경에서 보안을 중앙 집중화하고 보고 관리할 수 있는 지원 콘솔이 됩니다.

이 릴리스에서는 다음과 같은 사항이 구현됩니다.
* 찾은 결과 API
* 고유 제공업체를 가져오는 기능
* 대시보드 환경 업데이트

그 외에도 여러가지가 있습니다!

시작하려면 [{{site.data.keyword.security-advisor_short}} 문서](/docs/services/security-advisor/index.html)를 참조하십시오.

### {{site.data.keyword.iva_full_notm}} GA(General Availability) 소개
신규 기준일: 2018년 6월 26일

[{{site.data.keyword.iva_full}}](https://console.bluemix.net/catalog/services/voice-agent-with-watson)![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")이 이제 GA(Generally Available)되었습니다! 고객이 전화를 통해 호출하고 대화할 수 있는 Watson 서비스에 빌드된 코그너티브 음성 에이전트를 작성할 수 있습니다. 백본에서 Watson 인공 지능을 사용하면 음성 에이전트는 복잡한 상호작용을 처리하고 음성 에이전트 내의 고객 호출을 해결하여 대화식으로 통신할 수 있습니다.

이 릴리스는 다음과 같은 새로운 기능을 제공합니다.

* 재해 복구를 위해 중복 Watson 서비스 위치를 추가할 수 있습니다. 
* 음성 에이전트가 호출을 전송하고, 사전에 녹음된 메시지를 호출자에게 재생하며, Watson 서비스와 상호작용하는 방법을 사용자 정의하기 위한 고급 구성 옵션을 편집할 수 있습니다.
* 표준 서비스 플랜에서 최대 동시 연결 수를 구성할 수 있습니다.
* 음성 에이전트를 SIP 트렁킹 제공자(예: NetFoundry, Twilio, AT&T) 및 기타 서비스 제공자에 연결하거나 {{site.data.keyword.iva_short}}과의 피어링을 수행할 수 있습니다.

시작하려면 [{{site.data.keyword.iva_short}}](/docs/services/voice-agent/getting-started.html) 문서를 참조하십시오.

### {{site.data.keyword.streaminganalyticsshort}}에서는 컨테이너 기반 인프라와 함께 새로운 서비스 플랜을 소개함
신규 기준일: 2018년 4월 20일

이제 {{site.data.keyword.streaminganalyticsshort}}는 서비스에 보안 및 가용성 혜택을 제공하는 Kubernetes 컨테이너 기반 인프라에서 실행됩니다.
 
[v2 서비스 플랜](/docs/services/StreamingAnalytics/service_plans.html#service_plans)을 사용하여 이 새로운 컨테이너 기반 인프라에 액세스할 수 있습니다. 수행해야 하는 작업에 가장 적합한 {{site.data.keyword.streaminganalyticsshort}} 플랜을 선택할 수 있습니다. v2 서비스 플랜에는 다음 개선사항이 포함되어 있습니다.
 
* [IBM Streams QSE with Docker](https://www-01.ibm.com/marketing/iwm/iwm/web/preLogin.do?source=swg-ibmistvi)![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘"): [ 개발 안내서](https://developer.ibm.com/streamsdev/docs/cloud-beta-devguide/)![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")를 확인하여 Docker 환경에서 실행되는 새 Streams QSE with RHEL 7을 사용하여 새 {{site.data.keyword.streaminganalyticsshort}} v2 플랜으로 애플리케이션을 컴파일하고 배치하는 방법을 알아보십시오. 
* [{{site.data.keyword.streaminganalyticsshort}} v2 REST API](https://console.bluemix.net/apidocs/1939-streaming-analytics-v2#introduction)![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")
* [새 스타터 및 샘플 애플리케이션](https://developer.ibm.com/streamsdev/docs/cloud-beta-samples/) ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")
* [{{site.data.keyword.streaminganalyticsshort}} 서비스의 고가용성 개선사항](/docs/services/StreamingAnalytics/c_ha.html#consistent-regions)
* [{{site.data.keyword.streaminganalyticsshort}} 서비스의 문제점 판별 기능](https://developer.ibm.com/streamsdev/2018/02/15/streaming-analytics-console-gives-ways-find-fix-errors-beta-plans/)![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")
* [운영자의 작업 방식 및 클라우드의 보증된 튜플 처리의 모니터링](https://developer.ibm.com/streamsdev/2018/02/15/monitor-operators-behave-ensure-resource-optimization/)![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")

### {{site.data.keyword.iva_full_notm}}은 현재 베타입니다!
신규 기준일: 2018년 3월 16일

[{{site.data.keyword.iva_full}}](https://console.bluemix.net/catalog/services/voice-agent-with-watson)![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")을 사용하여 고객이 호출하고 전화를 통해 대화할 수 있는 Watson 서비스에서 빌드된 코그너티브 음성 에이전트를 작성할 수 있습니다. 백본에서 Watson 인공 지능을 사용하면 음성 에이전트는 복잡한 상호작용을 처리하고 음성 에이전트 내의 고객 호출을 해결하여 대화식으로 통신할 수 있습니다.

이 베타 릴리스는 다음과 같은 주요 기능을 제공합니다.

* 단일 단계에서 음성 에이전트 및 모든 필수 Watson 서비스를 작성하여 이전보다 더욱 쉽게 시작할 수 있습니다.
* 음성 에이전트에서 상담원 문의 센터 에이전트 또는 기타 대상에 호출을 전송합니다.
* 호출 세부사항 레코드, 대본 및 {{site.data.keyword.conversationshort}} 전환 이벤트를 {{site.data.keyword.cloudant_short_notm}} 데이터베이스로 전달하도록 음성 에이전트를 구성하여 호출 데이터를 수집하고 분석합니다.
* 새 _사용량_ 페이지에서 서비스 사용량을 모니터하고 호출 로그를 봅니다. 현재 달의 상태를 빠르게 보고, 호출 로그를 찾고 필터링하고 각 개별 호출에 대해 시스템 메시지를 볼 수 있습니다.
* 포트 5061을 통한 SIP TLS(sips URl) 및 SRTP(Secure Real-time Transport Protocol)를 사용하여 매체 암호화로 안전한 호출을 설정합니다.
* 유연성을 높이기 위해 다른 {{site.data.keyword.cloud_notm}} 영역에서 {{site.data.keyword.speechtotextfull}} 및 {{site.data.keyword.texttospeechfull}} 서비스 인스턴스에 연결합니다.

시작하려면 [{{site.data.keyword.iva_short}}](/docs/services/voice-agent/getting-started.html) 문서를 참조하십시오.

### {{site.data.keyword.visualrecognitionshort}}에 대한 업데이트
신규 기준일: 2018년 3월 14일

{{site.data.keyword.visualrecognitionfull}} 서비스는 새 사용자 정의 클래스류 모델 훈련이 클래스류를 기반으로 한 딥 러닝 신경 회로망으로 생성되도록 업데이트되었습니다. 이러한 딥 러닝 모델 생성에 필요한 추가 계산에는 새 모델을 훈련하기 위한 추가 시간이 필요할 수 있습니다.

현재 기존 사용자 정의 클래스류는 계속 업데이트하고 재훈련할 수 있으며 새 딥 러닝 머신 모델 형식으로 업데이트하지 않습니다.

### {{site.data.keyword.streaminganalyticsshort}} 업데이트
신규 기준일: 2018년 2월 14일

 [{{site.data.keyword.streaminganalyticsshort}} 서비스](https://console.bluemix.net/catalog/services/streaming-analytics){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")의 콘솔에 대한 [베타 - 엔트리 및 베타 - 고급 플랜](/docs/services/StreamingAnalytics/beta_plans.html#beta_plans)에는 여러 개선사항이 포함되어 있습니다.

* [새 IBM Streams QSE for Docker](https://www-01.ibm.com/marketing/iwm/iwm/web/preLogin.do?source=swg-ibmistvi){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘"): [베타 개발 안내서](https://developer.ibm.com/streamsdev/docs/cloud-beta-devguide/){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")를 확인하여 Docker 환경에서 실행되는 새 Streams QSE with RHEL 7을 사용하여 새 {{site.data.keyword.streaminganalyticsshort}} 베타 플랜으로 애플리케이션을 컴파일하고 배치하는 방법을 알아보십시오.
* [{{site.data.keyword.streaminganalyticsshort}} v2 REST API](https://console.bluemix.net/apidocs/1939-streaming-analytics-v2#introduction){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")
* [새 스타터 및 샘플 애플리케이션](https://developer.ibm.com/streamsdev/docs/cloud-beta-samples/)
* [{{site.data.keyword.streaminganalyticsshort}} 서비스에서 고가용성 개선사항](/docs/services/StreamingAnalytics/consistentregions.html#consistentregions)
* [{{site.data.keyword.streaminganalyticsshort}} 서비스](https://developer.ibm.com/streamsdev/2018/02/15/streaming-analytics-console-gives-ways-find-fix-errors-beta-plans/){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")의 베타 버전에서 새로운 문제점 판별 기능
* [운영자의 작업 방식 및 클라우드의 보증된 튜플 처리의 모니터링](https://developer.ibm.com/streamsdev/2018/02/15/monitor-operators-behave-ensure-resource-optimization/){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")

### {{site.data.keyword.keymanagementservicelong_notm}}가 시드니 지역으로 확대됨
신규 기준일: 2018년 1월 31일

오늘부터 {{site.data.keyword.keymanagementserviceshort}} 암호화 키 관리 서비스를 시드니 지역에서 이용할 수 있습니다. 시드니는 미국 남부(달라스) 및 런던 이후 {{site.data.keyword.keymanagementserviceshort}} 사용자에게 GA 상태를 제공하는 세 번째 지역입니다.

{{site.data.keyword.keymanagementserviceshort}}는 {{site.data.keyword.Bluemix_notm}}에 저장된 데이터의 암호화에 사용되는 키를 관리하는 간단하고 경제적인 키 관리 솔루션을 제공하는 암호화 키 관리 서비스입니다. {{site.data.keyword.keymanagementserviceshort}}는 키 작성부터 애플리케이션 사용, 키 보관 및 키 삭제까지 키의 전체 라이프사이클을 관리함과 동시에 데이터 관리와 키 관리 사이의 업무 분리를 적용합니다.

{{site.data.keyword.keymanagementserviceshort}}는 BYOK(Bring-Your-Own-Key – 고객 관리형 암호화)를 적용 가능 IBM 데이터 서비스와 함께 지원합니다. BYOK는 {{site.data.keyword.Bluemix_notm}}에 저장된 저장 데이터의 보안 관리를 향상할 수 있도록 내부적으로 작성된 마스터 신뢰점 암호화 키를 가져올 수 있게 합니다.


### {{site.data.keyword.containershort_notm}}: Kubernetes 1.8.x 지원
신규 기준일: 2018년 1월 19일

2017년 11월 이후에 {{site.data.keyword.containershort_notm}}가 Kubernetes `1.8.x`를 지원했습니다. 이제 Kubernetes의 기본 버전인 `1.8.6`을 발표하게 되었습니다.  조만간 `1.9.x`에 대한 지원을 제공할 예정입니다.

### Watson Discovery Visual Insights
신규 기준일: 2017년 11월 30일

엔티티, 관계, 개념 등과 같이 텍스트에서 발견된 시맨틱 요소의 {{site.data.keyword.discoveryshort}}를 이해하여 구현된 연결을 시각적으로 탐색하십시오.

즉시 {{site.data.keyword.discoveryshort}} News 콜렉션을 사용하여 전세계의 뉴스 탐색을 시작하십시오. 또는 {{site.data.keyword.discoveryshort}}에서 고유한 문서 콜렉션을 탐색하십시오. {{site.data.keyword.Bluemix_notm}} 인증 정보로 로그인하면 됩니다. 자세한 정보는 [Visual insights experimental](https://visual-insights.bluemix.net){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")을 참조하십시오.

### 새 IBM Cloud Managed Database Server Beta 서비스
신규 기준일: 2017년 11월 30일

새 IBM Cloud Managed Database Server Beta 서비스를 사용하면 {{site.data.keyword.Bluemix_notm}}에서 Microsoft SQL Server의 인스턴스를 작성할 수 있습니다. 데이터베이스 관리 시스템을 사용하는 것처럼 하드웨어 설정 또는 소프트웨어 설치 및 유지보수의 노력과 비용 없이 이 SQL Server 인스턴스를 사용할 수 있습니다.

이 서비스는 다음 기능을 제공합니다.
* Microsoft SQL Server 버전 2012, 2014, 2016 Enterprise 및 Standard Editions의 선택사항
* 애플리케이션 워크로드 요구사항을 충족하기 위한 여러 사전 정의된 구성 또는 크기
* IBM에서 모니터링, 패치, 백업, 보고를 포함한 전체 관리 제공

시작하려면 [IBM Cloud Managed Database Server 시작하기](/docs/services/managed-sql-server/getting-started.html)를 참조하십시오.

### {{site.data.keyword.mobilepushshort}}의 새로운 기능
신규 기준일: 2017년 10월 26일

지난 몇 달 동안 {{site.data.keyword.mobilepushshort}} 서비스에 대한 여러 개선사항을 수행했습니다. 이제 댈러스, 런던 및 시드니와 함께 프랑크프루트 지역에서 서비스가 제공됩니다. 개선사항의 상세 정보는 다음과 같습니다.

#### 모니터링
이제 특정 기간 동안 푸시 알림 성능을 추적하고, 전송된 알림의 수와 등록된 총 디바이스의 수를 추적할 수 있습니다. 또한 알림의 라이프사이클에서 모든 이벤트에 대한 알림을 받을 웹훅을 등록할 수도 있습니다. 추가 세부사항은 다음 문서 링크 및 블로그 게시물에서 볼 수 있습니다.
* [알림 모니터링](/docs/services/mobilepush/push_monitoring.html#push_monitoring)
* [웹훅 이벤트에 대한 경보 수신](/docs/services/mobilepush/push_webhook.html#webhook_event_based_notifications)
* [Monitoring in IBM Push Notifications](https://www.ibm.com/blogs/bluemix/2017/03/monitoring-ibm-push-notifications/){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")

#### 웹 알림
이제는 Firefox, Chrome, Chrome 앱 및 확장기능과 함께 웹 알림을 위한 Safari 웹 브라우저가 지원됩니다. Web SDK 및 관련 정보는 [IBM Bluemix Push Notifications Web SDK](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-javascript-webpush/blob/Doc/README.md){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")에서 볼 수 있습니다.

#### 최신 Android 및 iOS 알림
현재 iOS 11 알림에 대한 지원을 제공합니다. 또한 iOS10 및 Android N의 여러 가지 새 알림 관련 개선사항도 포함합니다.

* iOS10 – 리치 미디어 알림, 이미지, 대화식 알림의 단추 및 맵, 자국어로 지원된 문자열 지원
* Android N – 확장 가능한 알림, 대화식 및 자동 알림, LED 조명 설정

추가 세부사항은 [리치 미디어 알림](/docs/services/mobilepush/push_step_4_nf_rich.html#interactive-notifications) 문서, [대화식 및 자동 알림](/docs/services/mobilepush/push_step_4_nf_interactive.html#interactive-notifications) 문서 및 [고급 푸시 알림 사용](/docs/services/mobilepush/push_step_4_nf_adv.html#enabling-advanced-push-notifications) 문서에서 볼 수 있습니다.

#### APNS HTTP/2 지원
Apple은 Apple 알림을 위한 HTTP 프로토콜 지원을 도입했습니다. {{site.data.keyword.mobilepushshort}} 서비스는 이제 HTTP/2 프로토콜을 지원합니다. 이 지원을 사용하면 알림 페이로드가 증가된 처리량과 함께 4KB가 될 수 있고 즉각적인 피드백 기능을 제공합니다. Universal Certificate에 대한 지원을 통해 앱이 샌드박스 및 제품 환경 모두에 연결할 수 있습니다.

#### 새 Lite 플랜
{{site.data.keyword.mobilepushshort}} 서비스의 Lite 플랜은 매달 무료로 100K 알림을 전송할 수 있는 기능을 제공합니다. 자세한 정보는 [Lite Plan For Push Notifications Service on Bluemix](https://www.ibm.com/blogs/bluemix/2017/06/lite-plan-push-notifications-service-bluemix/){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘") 블로그 게시물을 참조하십시오.



### 모바일 분석의 새로운 기능
신규 기준일: 2017년 10월 26일

지난 몇 달 동안 {{site.data.keyword.mobileanalytics_short}} 서비스 대한 여러 개선사항을 수행했습니다. 이제 댈러스 및 런던과 함께 프랑크프루트 및 시드니 지역에서 서비스가 제공됩니다. 개선사항의 상세 정보는 다음과 같습니다.

#### 웹 SDK 지원
{{site.data.keyword.mobileanalytics_short}}는 이제 웹 앱 분석에 대한 추가 지원이 포함된 옴니 채널 서비스입니다. 추가 세부사항은 [https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-web-analytics/](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-web-analytics/){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")에서 볼 수 있습니다.

#### {{site.data.keyword.mobilefoundation_short}} 서비스와 통합
{{site.data.keyword.mobilefoundation_short}} 서비스는 이제 앱, 사용자 및 성능 분석을 위해 {{site.data.keyword.mobileanalytics_short}} 서비스를 활용합니다. 사용자는 DB2 웨어하우스 옵션으로 내보내기를 활용하여 어댑터 분석과 사용자 정의 도표를 빌드할 수 있습니다. 다음 블로그 게시물에서 추가 세부사항을 찾을 수 있습니다.

* [Mobile Foundation Service integration with Mobile Analytics Service](https://www.ibm.com/blogs/bluemix/2017/08/mobile-foundation-service-integration-mobile-analytics-service-2/){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")
* [Building custom charts using IBM Bluemix Mobile Analytics service and IBM Mobile Foundation Service](https://mobilefirstplatform.ibmcloud.com/blog/2017/04/26/custom-charts-using-analytics-and-dashdb-analytics-service/){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")
* [Building charts for Adapter analytics using IBM Bluemix Mobile Analytics service and IBM Mobile Foundation Service](https://mobilefirstplatform.ibmcloud.com/blog/2017/04/26/adapter-analytics-using-analytics-and-dashdb-analytics-service/){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")

#### {{site.data.keyword.mobilefirst_notm}} 표준 유형에는 이제 {{site.data.keyword.mobileanalytics_short}}가 포함됨
모바일 서비스 표준 유형은 사용자가 빨리 시작할 수 있도록 모바일 서비스 세트를 제공하는 템플리트입니다. {{site.data.keyword.mobileanalytics_short}} 서비스는 이제 [카탈로그](https://console.bluemix.net/catalog/starters/mobilefirst-services-starter){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")에서 사용 가능한 표준 유형의 일부입니다.


### {{site.data.keyword.streaminganalyticsshort}}에 대한 업데이트
신규 기준일: 2017년 10월 20일

* IBM Streams Runner for Apache Beam: 이제 스트림 개발 환경에서 로컬로 Beam 애플리케이션을 개발한 후 앱을 {{site.data.keyword.Bluemix_notm}}의 {{site.data.keyword.streaminganalyticsshort}} 서비스에 제출할 수 있습니다. IBM Streams Runner for Apache Beam은 스트림 환경에서 Beam 파이프라인을 실행합니다. Streams Runner로 실행되는 Beam 애플리케이션은 {{site.data.keyword.streaminganalyticsshort}}에 배치할 수 있는 SAB(Streams Application Bundle)로 변환됩니다. 추가 세부사항은 [스트리밍 분석의 IBM Streams Runner for Apache Beam](/docs/services/StreamingAnalytics/gs_beamrunner.html)을 확인하십시오.
* 더욱 빠르게 로그 파일에서 정보를 찾을 수 있습니다. 콘솔은 Python 또는 Java 토폴로지에 대한 애플리케이션 그래프의 표시를 개선하도록 업데이트되었습니다. [콘솔에 대한 개선사항](https://developer.ibm.com/streamsdev/2017/10/13/enhancements-to-the-console/){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")을 참조하십시오.

### IBM App Launch for {{site.data.keyword.Bluemix_notm}} Services
신규 기준일: 2017년 10월 12일

IBM App Launch for {{site.data.keyword.Bluemix_notm}} Services는 고객의 여러 횡단에 대상이 지정된 활동을 작성하기 위해 플랫폼을 제공하여 사용자가 고객 경험을 측정할 수 있도록 하는 시범 오퍼링입니다. App Launch 서비스는 고객 환경 설정에 대한 인사이트 및 활동 결과로서의 취약성을 제공하고 더 나은 고객 경험을 위해 앱을 개인화하도록 지원합니다.

앱 소유자는 이제 릴리스 주기 복잡도를 피해 모바일 앱에 대한 혁신의 제공을 가속화할 수 있습니다. App Launch 서비스를 통해 앱 소유자는 빠른 속도로 모바일 앱에 대한 기능을 실행하고 대상이 지정된 고객을 제어하여 영향을 측정할 수 있습니다. 앱 소유자는 앱 개발자와 함께 작업하여 기능에 대한 핵심성과지표(KPI)를 정의하고, 영향을 측정하고, 실시간 피드백을 기반으로 기능을 롤아웃 및 롤백할 수 있도록 할 수 있습니다. 또한 서비스는 애플리케이션 기능, 사용자 인터페이스 컴포넌트 및 메시지의 다양한 변형을 테스트하고 피드백에 따라 결정할 수 있는 기능을 제공합니다.

자세한 정보는 [튜토리얼 시작하기](/docs/services/app-launch/index.html#gettingstartedtemplate)를 참조하십시오.

### {{site.data.keyword.ibmwatson_notm}} {{site.data.keyword.relationshipextractionshort}}에 대한 업데이트
신규 기준일: 2017년 10월 4일

사용자는 {{site.data.keyword.relationshipextractionshort}}을 통해 새 사용자 정의 기능 및 새 언어 모델을 사용할 수 있습니다. WKS에 지원되는 새 언어는 네덜란드어, 한국어 및 중국어입니다.

### {{site.data.keyword.containerlong_notm}} 클러스터 업데이트
신규 기준일: 2017년 9월 20일

이제 {{site.data.keyword.Bluemix_notm}}에서 Kubernetes의 최신 사용 가능한 버전으로 클러스터를 업데이트할 수 있습니다. GUI 또는 CLI 중 하나를 사용하여 Kubernetes 마스터 및 작업자 노드를 Kubernetes 1.7로 업데이트하고 새 기능과 패치를 활용하십시오.

자세한 정보는 [Kubernetes 1.7 available in {{site.data.keyword.containerlong_notm}}](https://www.ibm.com/blogs/bluemix/2017/09/kubernetes-1-7-available-ibm-bluemix-container-service/){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")를 참조하십시오.

### 새 IBM Voice Agent with Watson 시범 서비스
신규 기준일: 2017년 9월 15일

새 {{site.data.keyword.iva_full}} 시범 서비스를 사용하여 고객이 호출하고 전화를 통해 대화할 수 있는 Watson 서비스에 빌드된 코그너티브 음성 에이전트를 작성할 수 있습니다. 백본에서 Watson 인공 지능을 사용하면 음성 에이전트는 복잡한 상호작용을 처리하고 음성 에이전트 내의 고객 호출을 해결하여 대화식으로 통신할 수 있습니다.

{{site.data.keyword.iva_short}}은 원활하게 Watson {{site.data.keyword.speechtotextshort}}, {{site.data.keyword.conversationshort}} 및 {{site.data.keyword.texttospeechshort}} 서비스에 연결하고 구성하여 자연어 대화를 시뮬레이션합니다. 각 음성 에이전트는 자동으로 스케일링하여 동시에 여러 호출을 처리합니다. 이 시범 릴리스에서 다음 주요 기능을 사용하여 음성 에이전트를 사용자 정의할 수 있습니다.

* 샘플 {{site.data.keyword.conversationshort}} 대화 상자를 가져와서 시작한 후 회사 요구에 적합한 고유 대화를 작성합니다.
* API를 사용하여 {{site.data.keyword.conversationshort}} 서비스 내에서 음성 에이전트 작동을 프로그래밍합니다. 예정되지 않은 작동으로부터 모든 것을 제어하여 대화 상자의 모든 노드에 대한 호출을 중지할 수 있습니다.
* 다른 주제에 대해 전문화된 코그너티브 에이전트에 다른 전화번호를 연결하려는 경우 다중 음성 에이전트를 쉽게 작성하고 관리합니다.
* SOE(Service Orchestration Engine)에 연결하여 서비스 기능을 확장하면 서드파티 API를 사용할 수 있습니다. 예를 들어, SOE는 {{site.data.keyword.conversationshort}} 서비스에서 트리거에 대해 청취한 후 기존 시스템에서 제공된 API를 사용하여 정보를 찾거나 기타 분석을 제공할 수 있습니다.

시작하려면 [{{site.data.keyword.iva_short}}](/docs/services/voice-agent/getting-started.html) 시작하기 문서를 참조하십시오.


### {{site.data.keyword.streaminganalyticsshort}} 서비스 업데이트: 콘솔에 애플리케이션에서 문제점을 정확히 찾을 수 있는 새로운 방법이 포함됨
신규 기준일: 2017년 8월 14일

Python 및 Java 애플리케이션의 경우 소스 파일 위치는 @spl_note 어노테이션에 따라 표시됩니다.

자세한 정보는 [Latest improvements to the {{site.data.keyword.streaminganalyticsshort}}](https://developer.ibm.com/streamsdev/2017/08/14/latest-improvements-streaming-analytics-console/){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")를 참조하십시오.

### IBM Cloud Monitoring은 영국 지역에서도 사용 가능함
신규 기준일: 2017년 8월 01일

{{site.data.keyword.monitoringlong}} 서비스를 사용하여 메트릭에 대한 작업을 할 때 {{site.data.keyword.Bluemix_notm}}에서 콜렉션, 보존 및 분석 기능을 확장합니다.

* 조치에 대한 경보를 전송합니다! {{site.data.keyword.monitoringlong}}에서는 성능 임계값을 설정하고 그 임계값을 초과하는 경우 알림을 전송하는 데 사용할 수 있는 API를 제공합니다. 단일 서비스 인스턴스 또는 앱 인스턴스에 대한 경보 규칙 및 인스턴스 세트에서 보고하는 경보 규칙을 정의하십시오. 경보가 트리거되면 이메일, PagerDuty 이벤트, 웹훅 알림 또는 이 세 가지의 조합을 통해 알림을 받습니다.

* 사용자 정의 메트릭을 추가합니다. {{site.data.keyword.monitoringlong}} 프리미엄 플랜에서는 클라우드 모니터링 데이터에 관련 애플리케이션 및 비즈니스 메트릭을 추가하기 위해 사용할 수 있는 API를 제공합니다. 또한, 이를 이용하여 메트릭 데이터를 {{site.data.keyword.IBM_notm}} Cloud 외부에서 {{site.data.keyword.monitoringlong}} 서비스로 전송할 수 있습니다.

* 재사용가능 대시보드를 빌드해서 대화식으로 만듭니다. {{site.data.keyword.monitoringlong}}의 호스팅된 Grafana에서는 기호에 맞는 시각화 옵션으로 사용자 정의 대시보드를 빌드하기 위한 지원을 제공합니다.  변수가 있는 메트릭 조회를 사용하여 템플리트로 대시보드를 동적으로 구성하십시오.

* {{site.data.keyword.Bluemix_notm}} 카탈로그를 통해 서비스에 액세스합니다. {{site.data.keyword.monitoringlong}}은 {{site.data.keyword.Bluemix_notm}} 카탈로그의 DevOps 섹션에서 서비스 타일로 사용 가능합니다.  단일 및 그룹 컨테이너가 있는 {{site.data.keyword.containershort}} 서비스의 경우, {{site.data.keyword.Bluemix_notm}} UI에서 서비스에 액세스할 수 있습니다.

* 사용자의 요구사항에 맞는 서비스 플랜을 선택합니다. 사용량 요구사항과 일치하도록 Lite 서비스 플랜 또는 프리미엄 서비스 플랜을 선택할 수 있습니다. Lite 플랜에서는 분당 한 번씩 메트릭 콜렉션, 15일 동안 보존 및 보완 경보를 제공합니다.  또는 더 많은 양의 이용, 더 긴 메트릭 보존을 사용 가능하게 하고, 예를 들면, {{site.data.keyword.monitoringlong}} 서비스에서 메트릭을 전송하거나 검색하도록 서비스 API에 대한 액세스 권한을 확보하기 위해 프리미엄 플랜을 선택할 수 있습니다. {{site.data.keyword.monitoringlong}}에서는 분당 한 번씩 메트릭 콜렉션을 제공합니다.  Lite 플랜은 15일 동안 고해상도로 메트릭을 보존합니다. 프리미엄 플랜은 45일 동안 고해상도로 메트릭을 보존합니다.

레거시 {{site.data.keyword.monitoringshort}} 서비스는 30초부터 시작한 서비스 정의 빈도로 메트릭을 수집하고 시간 경과에 따라 1시간 빈도로 요약합니다. {{site.data.keyword.monitoringlong}}은 이제 1분 간 전체 분석 콜렉션을 제공합니다.  Lite 플랜은 15일 동안 메트릭을 보존합니다.  프리미엄 플랜은 45일 동안 메트릭을 보존합니다.

{{site.data.keyword.monitoringlong}} 서비스에 대한 자세한 정보는 [모니터링 문서 시작하기](/docs/services/cloud-monitoring/index.html#getting-started-with-ibm-cloud-monitoring) 또는 [IBM Cloud Monitoring – Service Refresh with New Features ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")](https://www.ibm.com/blogs/bluemix/2017/07/ibm-cloud-monitoring-service-refresh-new-features/)를 참조하십시오.


### IBM Cloud Log Analysis는 이제 미국 남부 지역에서 사용 가능함
신규 기준일: 2017년 7월 31일

{{site.data.keyword.loganalysisfull}} 서비스에서는 {{site.data.keyword.Bluemix_notm}} 플랫폼에 대한 로그 콜렉션 및 로그 검색 서비스를 제공하여, 선택한 {{site.data.keyword.Bluemix_notm}} 서비스에서 애플리케이션 및 {{site.data.keyword.Bluemix_notm}} 서비스의 데이터를 자동으로 수집합니다. 서비스를 {{site.data.keyword.loganalysisshort}} 다음 경우에 사용하십시오.

* 필요한 기간 동안 로그를 보존하십시오.  

    로그는 IBM Cloud 스토리지에 저장됩니다.  필요할 때 해당 로그를 다운로드할 수 있습니다.

* 보존된 로그를 관리하고 새 API를 사용하여 {{site.data.keyword.IBM_notm}} Cloud 외부에서 로그 데이터를 전송하십시오.

* 하루에 검색할 수 있는 로그의 크기를 선택하십시오.  

    하루에 최대 500MB, 2GB, 5GB, 10GB의 로그를 검색할 수 있는 여러 가지 플랜이 사용 가능합니다.

* 재사용가능 대시보드를 빌드해서 대화식으로 만듭니다.

    {{site.data.keyword.loganalysisshort}}의 호스팅된 Kibana는 사용자 정의 대시보드를 빌드하기 위한 지원을 제공합니다.

* {{site.data.keyword.Bluemix_notm}} 카탈로그를 통해 서비스에 액세스합니다.  

    단일 및 그룹 컨테이너와 {{site.data.keyword.IBM_notm}} Cloud Foundry를 사용하는 {{site.data.keyword.loganalysisshort}} 서비스의 경우 {{site.data.keyword.Bluemix_notm}} UI에서 서비스에 액세스할 수 있습니다.

{{site.data.keyword.loganalysisshort}} 서비스에 대한 자세한 정보는 [{{site.data.keyword.loganalysisfull}} 시작하기](/docs/services/CloudLogAnalysis/index.html#getting-started-with-ibm-cloud-log-analysis) 및 [{{site.data.keyword.loganalysisshort}} 개요](/docs/services/CloudLogAnalysis/log_analysis_ov.html#log_analysis_ov)를 참조하십시오.

### IBM dashDB for Analytics의 이름이 바뀜
신규 기준일: 2017년 7월 18일

다음 표에서는 새 이름을 요약합니다.

|이전 이름               |새 이름                   |유효 날짜 |
|-----------------------------|----------------------------|----------------|
|IBM dashDB for Analytics    |IBM DB2 Warehouse on Cloud |2017년 7월 18일  |
{: caption="표 1. 서비스 이름 변경" caption-side="top"}

DB2 Warehouse on Cloud 및 DB2 on Cloud에 대한 업데이트의 누적 목록의 경우 [What's New in Db2 Warehouse on Cloud and Db2 on Cloud](http://www.ibm.com/support/docview.wss?uid=swg21961758){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")를 참조하십시오.

### IBM Cloud Monitoring은 이제 미국 남부 지역에서 사용 가능함
신규 기준일: 2017년 7월 17일

{{site.data.keyword.monitoringlong}} 서비스를 사용하여 메트릭에 대한 작업을 할 때 {{site.data.keyword.Bluemix_notm}}에서 콜렉션, 보존 및 분석 기능을 확장합니다.

* 조치에 대한 경보를 전송합니다! {{site.data.keyword.monitoringlong}}에서는 성능 임계값을 설정하고 그 임계값을 초과하는 경우 알림을 전송하는 데 사용할 수 있는 API를 제공합니다. 단일 서비스 인스턴스 또는 앱 인스턴스에 대한 경보 규칙 및 인스턴스 세트에서 보고하는 경보 규칙을 정의하십시오. 경보가 트리거되면 이메일, PagerDuty 이벤트, 웹훅 알림 또는 이 세 가지의 조합을 통해 알림을 받습니다.

* 사용자 정의 메트릭을 추가합니다. {{site.data.keyword.monitoringlong}} 프리미엄 플랜에서는 클라우드 모니터링 데이터에 관련 애플리케이션 및 비즈니스 메트릭을 추가하기 위해 사용할 수 있는 API를 제공합니다. 또한, 이를 이용하여 메트릭 데이터를 {{site.data.keyword.IBM_notm}} Cloud 외부에서 {{site.data.keyword.monitoringlong}} 서비스로 전송할 수 있습니다.

* 재사용가능 대시보드를 빌드해서 대화식으로 만듭니다. {{site.data.keyword.monitoringlong}}의 호스팅된 Grafana에서는 기호에 맞는 시각화 옵션으로 사용자 정의 대시보드를 빌드하기 위한 지원을 제공합니다.  변수가 있는 메트릭 조회를 사용하여 템플리트로 대시보드를 동적으로 구성하십시오.

* {{site.data.keyword.Bluemix_notm}} 카탈로그를 통해 서비스에 액세스합니다. {{site.data.keyword.monitoringlong}}은 {{site.data.keyword.Bluemix_notm}} 카탈로그의 DevOps 섹션에서 서비스 타일로 사용 가능합니다.  단일 및 그룹 컨테이너가 있는 {{site.data.keyword.containershort}} 서비스의 경우, {{site.data.keyword.Bluemix_notm}} UI에서 서비스에 액세스할 수 있습니다.

* 사용자의 요구사항에 맞는 서비스 플랜을 선택합니다. 사용량 요구사항과 일치하도록 Lite 서비스 플랜 또는 프리미엄 서비스 플랜을 선택할 수 있습니다. Lite 플랜에서는 분당 한 번씩 메트릭 콜렉션, 15일 동안 보존 및 보완 경보를 제공합니다.  또는 더 많은 양의 이용, 더 긴 메트릭 보존을 사용 가능하게 하고, 예를 들면, {{site.data.keyword.monitoringlong}} 서비스에서 메트릭을 전송하거나 검색하도록 서비스 API에 대한 액세스 권한을 확보하기 위해 프리미엄 플랜을 선택할 수 있습니다. {{site.data.keyword.monitoringlong}}에서는 분당 한 번씩 메트릭 콜렉션을 제공합니다.  Lite 플랜은 15일 동안 고해상도로 메트릭을 보존합니다. 프리미엄 플랜은 45일 동안 고해상도로 메트릭을 보존합니다.

레거시 {{site.data.keyword.monitoringshort}} 서비스는 30초부터 시작한 서비스 정의 빈도로 메트릭을 수집하고 시간 경과에 따라 1시간 빈도로 요약합니다. {{site.data.keyword.monitoringlong}}은 이제 1분 간 전체 분석 콜렉션을 제공합니다.  Lite 플랜은 15일 동안 메트릭을 보존합니다.  프리미엄 플랜은 45일 동안 메트릭을 보존합니다.

{{site.data.keyword.monitoringlong}} 서비스에 대한 자세한 정보는 [모니터링 문서 시작하기](/docs/services/cloud-monitoring/index.html#getting-started-with-ibm-cloud-monitoring) 또는 [IBM Cloud Monitoring – Service Refresh with New Features ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")](https://www.ibm.com/blogs/bluemix/2017/07/ibm-cloud-monitoring-service-refresh-new-features/)를 참조하십시오.

### {{site.data.keyword.contdelivery_short}} 업그레이드
신규 기준일: 2017년 7월 11일

업그레이드 이점에는 버그 수정, 성능 개선사항 및 사용자 경험 개선이 포함됩니다. 사용자의 환경에 주목할 만한 개선사항이 아직 없는 경우 다음 항목을 포함하십시오.
<ul>
<li>극제화 및 접근성에 대한 수정사항 및 개선사항</li>
<li>도구 체인 액세스 제어(도구 체인의 관리 탭에서 사용 가능)</li>
<li>Continuous Delivery 도구 카탈로그에서 새 도구 통합</li>
<li>Orion Web IDE에서 다중 작업공간의 개선된 그룹화</li>
<li>Orion Web IDE에서 다중 편집기 탭에 대한 지원</li>
<li>Orion Web IDE에서 UI 테마에 대한 지원</li>
</ul>

### {{site.data.keyword.uccr_short}} 베타
신규 기준일: 2017년 6월 23일

{{site.data.keyword.uccr_short}}는 클라우드 원시 개발 도구 및 온프레미스 개발 도구를 모두 지원하는 엔터프라이즈 규모의 릴리스 관리 솔루션입니다.

{{site.data.keyword.uccr_short}}의 베타 버전은 다음 기능을 지원합니다.
* 릴리스를 사용하여 다중 개발 플랜 및 이벤트를 관리하고 다중 팀 릴리스 노력에 대해 협업할 수 있습니다.
* 릴리스 관련 활동에 대한 이벤트를 작성하고 달력을 사용하여 이벤트를 관리합니다.
* 고유한 이벤트 및 릴리스를 가져옵니다.
* 조직에 적합한 달력 이벤트를 사용자 정의합니다.
* 릴리스 알림을 위해 이메일 및 슬랙 유형 태스크를 사용합니다.

### dashDB for Transactions가 {{site.data.keyword.DB2OnCloud_short}}로 이름이 바뀜
신규 기준일: 2017년 6월 14일

IBM {{site.data.keyword.DB2OnCloud_short}}는 dashDB for Transactions의 새 이름입니다. 이름 바꾸기의 일부로 이전에 자체 관리된 {{site.data.keyword.DB2OnCloud_short}} 서비스도 IBM DB2 Hosted로 이름이 바뀝니다. 표시 이름이 업데이트되는 시점에서만 모든 API 또는 명령행 인터페이스가 그대로 유지됩니다.

### {{site.data.keyword.sparks}} 업데이트: Stocator-S3 커넥터에는 IBM Cloud Object Storage Cross Region 서비스(베타)에 대한 지원이 포함됨
신규 기준일: 2017년 6월 05일

{{site.data.keyword.sparks}} 사용자는 이제 액세스할 수 있으며 IBM Cloud Object Storage Cross Region 서비스에 저장된 데이터에 대한 분석을 수행합니다. 이 기능은 베타로 제공됩니다. IBM Cloud Object Storage는 분석 및 기타 애플리케이션을 위한 대용량의 비용이 효율적인 스토리지를 제공하며, 이 스토리지는 확장 가능하고 유연하며 사용이 간단합니다.

Apache Spark는 Stocator 기술에 기반한 스토리지 커넥터를 통해 IBM Cloud Object Storage 데이터에 액세스하며, 이는 명시적으로 오브젝트 스토리지를 위해 디자인되었고 이에 따라 레거시 오브젝트 스토리지 커넥터보다 더욱 빠르게 수행됩니다. 사용자로서 Apache Spark 코드를 변경하거나 다시 컴파일할 필요가 없습니다.

[Access and Analyze data in IBM Cross Region Cloud Object Storage](https://www.ibm.com/blogs/bluemix/2017/06/access-analyze-data-ibm-cross-region-cloud-object-storage/){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘") 블로그 게시물은 {{site.data.keyword.Bluemix_notm}} 및 IBM Data Science Experience(DSx)에서 {{site.data.keyword.sparks}}와 함께 IBM Cloud Object Storage 데이터 사용에 대해 설명합니다.

질문 또는 의견이 있으면 [sparksrv@us.ibm.com](sparksrv@us.ibm.com)으로 보내 주십시오. 대단히 감사합니다!

### {{site.data.keyword.dashdbshort_notm}} for Transactions에 사용 가능한 새 확장 가능 플랜
신규 기준일: 2017년 5월 31일

새 플랜은 데이터베이스 요구사항에 따라 확장할 수 있는 {{site.data.keyword.dashdbshort}} for Transactions에 사용할 수 있습니다. 새 Flex 플랜을 통해 소형 시스템에서 시작할 수 있고 해당 시스템의 힘과 스토리지 용량을 쉽고 빠르게 확장할 수 있습니다. {{site.data.keyword.dashdbshort}} for Transactions는 100% DB2 호환이 가능하고 고가용성 플랜에서 99.95% SLA를 제공합니다.

### {{site.data.keyword.Bluemix_notm}}의 {{site.data.keyword.mobilepush}} 서비스에 대한 새 업데이트
신규 기준일: 2017년 5월 24일

다음은 {{site.data.keyword.Bluemix_notm}}의 {{site.data.keyword.mobilepush}} 서비스에 사용 가능한 새 업데이트입니다.

**Lite 플랜**: {{site.data.keyword.mobilepush}} 서비스를 위한 기존 기본 플랜 외에도 새 Lite 플랜을 도입하였습니다. 새 플랜에 따라 사용자는 매달 최대 100000개의 디지털 메시지를 무료로 보낼 수 있습니다. Lite 플랜에서 기본 플랜으로 업그레이드하는 동안 백만 개의 디지털 메시지 후에 사용자에게 청구됩니다. 백만 개 메시지 계수는 Lite 플랜이 기본 플랜으로 업그레이드될 때 시작합니다.

**모니터링**: 이제 {{site.data.keyword.mobilepush}} Service Console에서 받은 알림 및 등록된 디바이스에 대한 인사이트를 얻을 수 있습니다. 또한 메시지 레벨 추적을 위해 REST API를 사용할 수도 있습니다. 메시지 전송에서 메시지 수신인으로 디스패치하는 메시지까지 구성 웹훅으로 세부사항을 가져올 수 있습니다.  [{{site.data.keyword.mobilepush}} 모니터링](/docs/services/mobilepush/t_push_monitoring.html#monitor-notifications)을 참조하십시오.

**웹 알림**: 이제 Safari 웹 브라우저에 알림을 전송할 수 있습니다.

### Secure Gateway 업데이트
신규 기준일: 2017년 5월 24일

최신 Secure Gateway 유지보수 업데이트에는 UI 및 API 관리자, 업데이트된 문서의 사소한 버그 문제점이 포함되고 클라이언트는 버전 1.7.1로 업데이트되었습니다. Secure Gateway 클라이언트는 이제 AIX 7.1+에서 사용 가능하고 스퀴드 프록시를 통해 아웃바운드 연결을 지원합니다.

### {{site.data.keyword.streaminganalyticsshort}} 서비스 업데이트: Python 개발 환경에서 스트림 애플리케이션 개발
신규 기준일: 2017년 4월 13일

이전에는 IBM Streams의 로컬 버전을 설치하여 Python 애플리케이션을 개발해야 했습니다. 이제 더 이상 해당 경우는 없습니다. 이제 원하는 개발 환경 또는 Jupyter 대화식 노트북에서 Python을 사용하여 애플리케이션을 개발할 수 있습니다.

STREAMING_ANALYTICS_SERVICE 컨텍스트를 사용하여 {{site.data.keyword.streaminganalyticsshort}} 서비스에 Python 애플리케이션을 제출할 수 있습니다. {{site.data.keyword.streaminganalyticsshort}} 서비스에는 Python 3.5 이상이 필요합니다.

IBM Data Science Experience(DSX)에서 Jupyter 노트북을 사용하여 샘플 Python 애플리케이션을 작성할 수 있고 DSX에서 직접 이러한 애플리케이션을 {{site.data.keyword.streaminganalyticsshort}} 인스턴스에 제출할 수 있습니다. [DSX 커뮤니티 페이지](https://datascience.ibm.com/){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")의 노트북에서 샘플 스트림 처리 Python 애플리케이션을 확인하십시오.

{{site.data.keyword.streaminganalyticsshort}} 서비스 업데이트에 대한 자세한 정보는 [{{site.data.keyword.streaminganalyticsshort}} updates: DSX integration and easier Python development](https://www.ibm.com/blogs/bluemix/2017/05/streaming-analytics-updates-dsx-integration-easier-python-development/){: new_window} ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")를 참조하십시오.

### {{site.data.keyword.sparks}} 업데이트: 이제 Apache Spark 2.1이 지원됨
신규 기준일: 2017년 4월 21일

{{site.data.keyword.sparkl}}는 Apache Spark 2.1에 대한 지원을 도입하여 복잡한 데이터에서 인사이트를 구현하는 알고리즘을 작성합니다. Apache Spark 2.1은 이벤트 시간 워터마크 및 Kafka 0.10에 대한 추가된 지원과 함께 구조화된 스트리밍 주변에 큰 도움을 줍니다. Apache Spark 2.1은 또한 Spark SQL, SparkR 및 MLlib 모듈의 안정성 및 편리성 증가에 중점을 두었습니다. Spark 2.1에 대한 추가 세부사항은 [Spark Release 2.1.0](http://spark.apache.org/releases/spark-release-2-1-0.html)을 참조하십시오.

{{site.data.keyword.sparkl}} 또는 Apache Spark 2.1의 최신 버전에 대한 질문이 있으면 기꺼이 답변해 드리며 질문은 sparksrv@us.ibm.com으로 보내 주십시오.

### {{site.data.keyword.macm_short}}는 더 이상 사용되지 않음
신규 기준일: 2017년 4월 18일

2017년 3월 30일부로 {{site.data.keyword.macm_long}} 서비스 타일이 {{site.data.keyword.Bluemix_notm}} 카탈로그에서 제거되며 새 MACM 인스턴스를 더 이상 프로비저닝할 수 없습니다. 그러나 기존 인스턴스는 계속 지원됩니다. 지원 종료 날짜는 2018년 3월 30일입니다. 지원 종료 날짜 전에 {{site.data.keyword.macm_short}}(MACM) 서비스 인스턴스를 삭제하십시오. 사용자에게 IBM Watson Content Hub로의 마이그레이션을 권장합니다. Watson Content는 IBM Marketplace에서 사용 가능하며 30일 무료 평가판을 사용자에게 제공합니다. IBM Watson Content Hub는 자산 관리, IBM Watson 서비스를 사용한 코그너티브 태그 지정 및 고객을 위해 최적의 경험을 보장하도록 포함된 CDN(Content Delivery Network)과 같이 추가된 새 기능을 포함하여 MACM과 유사한 기능을 제공합니다. IBM은 MACM에서 Watson Content Hub로 마이그레이션할 서비스 계약을 제공합니다.


### {{site.data.keyword.sparks}} 업데이트: 이제 Data Science Experience에서 노트북이 지원됨
신규 기준일: 2017년 4월 11일

노트북 및 Spark에 대해 작업할 새 플랫폼은 Data Science Experience입니다. [Data Science Experience](http://datascience.ibm.com/)에 등록하여 노트북을 작성하고 기타 데이터 과학자들과 경험을 공유해 보십시오.

{{site.data.keyword.sparks}}에서 노트북에 대해 작업한 경우 노트북을 Data Science Experience에 마이그레이션할 수 있습니다. 자세한 정보는 [노트북 문서 마이그레이션](/docs/services/AnalyticsforApacheSpark/index-gentopic2.html#migration_to_dsx)을 참조하십시오.


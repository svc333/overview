---


copyright:
  years: 2016, 2018
lastupdated: "2018-11-30"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# {{site.data.keyword.Bluemix_notm}} 플랫폼의 개념
{: #whatis}

IBM의 클라우드 플랫폼은 PaaS(Platform as a Service)를 IaaS(Infrastructure as a Service)와 결합하여 통합 환경을 제공합니다. 이 플랫폼은 소규모 개발 팀 및 조직과 대규모 엔터프라이즈 비즈니스를 모두 스케일링하고 지원합니다. {{site.data.keyword.cloud}}에서 빌드하는 이 솔루션은 전세계의 데이터 센터에 글로벌로 배치되어 신뢰할 수있는 테스트되고 지원되는 환경에서 신속하게 스핀업되고 안정적으로 수행됩니다.
{: .shortdesc}

{{site.data.keyword.Bluemix_notm}} 플랫폼은 일관되고 신뢰할 수 있는 클라우드 경험을 제공하기 위해 함께 작동하는 여러 컴포넌트로 구성됩니다. 

  * 수백 개의 {{site.data.keyword.Bluemix_notm}} 오퍼링으로 구성된 카탈로그
  * 클라우드 리소스 작성, 보기 및 관리를 위한 프론트 엔드 역할을 하는 강력한 콘솔
  * 두 플랫폼 서비스 모두에 대해 사용자를 안전하게 인증하고 {{site.data.keyword.Bluemix_notm}}에서 일관적으로 리소스에 대한 액세스를 제어하는 ID 및 액세스 관리 컴포넌트
  * 리소스를 필터링하고 식별하기 위한 검색 및 태그 지정 메커니즘
  * 가격 플랜을 위한 정확한 사용량과 안전한 신용카드 사기 방지를 제공하는 계정 및 청구 관리 시스템

## 호스팅 환경 선택
{: #choose-compute}

{{site.data.keyword.Bluemix_notm}}를 사용하면 더 이상 하드웨어에 막대한 금액을 투자하여 새로운 앱을 테스트하거나 실행할 필요가 없습니다. 대신 IBM에서 모든 것을 관리하며 실제 사용량에 대한 금액만 청구합니다. 클라우드 서버 환경은 인프라 계층의 기반입니다. 단일 옵션을 선택하거나 더 복잡한 환경의 경우 옵션의 조합을 선택할 수 있습니다. 

원하거나 필요한 만큼 인프라에 대한 제어를 제공하여 앱을 호스팅하기 위한 다양한 옵션이 있습니다. 다음 방법 중 하나로 앱을 실행할 수 있습니다.

  * 서버리스 기능으로
  * Cloud Foundry 앱으로
  * Kubernetes 클러스터의 Docker 컨테이너로
  * VMware로
  * 가상 머신으로
  * 고성능 {{site.data.keyword.baremetal_short}}로 

{{site.data.keyword.baremetal_short}}는 단일 고객 전용의 싱글 테넌트 실제 서버입니다. 서버 호스트에서 RAM 및 스토리지 디바이스에 이르기까지 거의 모든 것을 제어합니다. 이러한 서버는 지속적인 시간(예: 몇 개월) 동안 컴퓨팅 능력이 필요한 워크로드에 사용됩니다. 

{{site.data.keyword.BluVirtServers_short}}는 공용 또는 전용 인스턴스로 배치될 수 있습니다. 공용 인스턴스를 사용하면 서버의 리소스가 다른 고객과 공유되며, 이를 멀티 테넌트 환경이라고도 합니다. 사설 인스턴스를 사용하면 실제 서버의 리소스가 동일한 서버에 하나 이상의 가상 머신을 보유할 수 있는 한 고객에게 전용으로 제공됩니다. 이러한 서버는 제한된 시간(예: 몇 주) 동안 실행되는 워크로드에 적합합니다. 몇 가지 워크로드 예제로는 개발 및 테스트, 백업 및 복구, 재해 복구가 있습니다. 서버 옵션에 대한 자세한 정보는 [Bare metal servers vs. virtual servers: Choosing the best option for you](https://www.ibm.com/blogs/bluemix/2018/06/bare-metal-virtual-servers-works/){: new_window} ![외부 링크 아이콘](../icons/launch-glyph.svg "외부 링크 아이콘")를 참조하십시오.

컴퓨팅 옵션에 대한 요약은 다음 표를 확인하십시오.

|옵션 |설명 | 
|--------|---------------|
| [{{site.data.keyword.baremetal_short}}](/docs/bare-metal/about.html)  |사용자 전용이며 서버 리소스를 포함한 모든 파트에서 다른 고객과 공유되지 않는 시간별 또는 월별 싱글 테넌트 서버입니다. |
| [{{site.data.keyword.BluVirtServers_short}}](/docs/vsi/vsi_about.html) |전용 코어와 메모리 할당을 포함하여 구매하는 확장 가능한 서버입니다. |
| [{{site.data.keyword.vmwaresolutions_short}}](/docs/services/vmwaresolutions/vmonic/prod_overview.html) |확장 가능하고 안전한 고성능 인프라 및 업계 최고의 VMware 하이브리드 가상화 기술을 사용하여 온프레미스 VMware 워크로드를 빠르고 원활하게 통합하거나 마이그레이션합니다. |
| [{{site.data.keyword.containerlong_notm}}](/docs/containers/cs_why.html) |Docker 컨테이너, Kubernetes 기술, 직관적인 사용자 경험, 기본 제공 보안 및 격리를 결합하여 컴퓨팅 호스트의 클러스터에서 컨테이너화된 앱의 배치, 오퍼레이션, 스케일링 및 모니터링을 자동화합니다. |
| [{{site.data.keyword.cfee_full_notm}}](/docs/cloud-foundry/index.html) |격리된 여러 엔터프라이즈급 Cloud Foundry 플랫폼을 요청 시 인스턴스화합니다. |
| [{{site.data.keyword.openwhisk_short}}](/docs/openwhisk/index.html) |Apache OpenWhisk 기반의 FaaS(Function-as-a-Service) 프로그래밍 플랫폼입니다. |
{: caption="표 1. 컴퓨팅 옵션" caption-side="top"}

## 애플리케이션 빌드
{: #build-apps}

현대화하여 클라우드로 가져오려는 [기존 코드](/docs/apps/tutorials/tutorial_byoc.html)가 있거나 [새로운 애플리케이션](/docs/apps/tutorials/tutorial_starter-kit.html)을 개발 중인지에 관계없이 개발자는 {{site.data.keyword.Bluemix_notm}}에서 사용 가능한 서비스 및 런타임 프레임워크의 빠르게 설정하는 에코시스템을 활용할 수 있습니다.

시작하고 실행하는 데 도움이 되도록 언어별 [프로그래밍 안내서](https://cloud.ibm.com/docs/home/build){: new_window} ![외부 링크 아이콘](../icons/launch-glyph.svg "외부 링크 아이콘")가 제공됩니다. {{site.data.keyword.baremetal_short}}에서 서버리스 기능으로 실행하는 경우에 이르기까지 {{site.data.keyword.Bluemix_notm}} 인프라를 사용하여 앱을 호스팅하는 여러 옵션이 있습니다.

## 서비스 연결
{: #connect-services}

카탈로그에서 선택할 수 있는 190개 이상의 서비스를 통해 요구사항에 맞게 사용자 조정된 솔루션을 빌드할 수 있습니다. 유스 케이스에 적합한 경우 {{site.data.keyword.Bluemix_notm}} 외부의 앱에 서비스를 쉽게 연결할 수도 있습니다. 외부 이용자를 {{site.data.keyword.Bluemix_notm}} 서비스에 수동으로 연결하려는 경우에는 새 인증 정보 세트를 생성할 수 있습니다. 예를 들어, {{site.data.keyword.Bluemix_notm}} 외부의 앱을 Watson 서비스에 연결하려고 시도하는 경우에는 이를 함께 연결하는 새 인증 정보를 생성합니다. 간단합니다! 자세한 정보는 [인증 정보 추가](/docs/resources/service_credentials.html#service_credentials)를 참조하십시오.

## 계정 설정

{{site.data.keyword.Bluemix_notm}}를 사용해 보는 중이라면 바로 카탈로그로 이동하여 탐색하려는 서비스를 체크아웃하고 평가판 또는 Lite 계정에 추가할 수 있습니다. 그러나 개발자 그룹 또는 전체 조직을 위한 환경을 시작하고 프로덕션에서 앱을 실행할 준비가 되어 있는 경우 계정의 기본사항 설정을 고려해 보십시오.

* 사용자와 서비스 ID를 하나의 엔티티로 구성하여 액세스 지정을 간소화된 프로세스로 만들기 위한 사용자 액세스 그룹
* 리소스 세트에 대한 액세스를 쉽고 빠르게 지정할 수 있도록 리소스를 구성하기 위한 리소스 그룹
* IAM 액세스 정책 또는 Cloud Foundry 조직 및 영역 역할이 필요한 액세스 그룹 또는 개별 개발자를 위한 액세스 정책

자세한 정보는 [계정 설정 우수 사례](/docs/account/bp_account.html#account_setup) 및 [액세스 지정 우수 사례](/docs/iam/bp_access.html)를 참조하십시오. 또한 시작할 준비가 되었으면 [계정 계층 구조](/docs/account/account_overview.html#overview)의 부분을 확인하십시오.

## 가격 및 청구

계정 유형에 관계없이 무료 할당량을 제공하는 서비스에 대해 Lite 플랜을 사용하여 {{site.data.keyword.Bluemix_notm}}를 탐색할 수 있습니다. 카탈로그에서 서비스를 선택 중이고 타일을 선택하는 경우 다양한 유형의 사용 가능한 플랜이 있으면 가격 정보에 대한 세부사항을 볼 수 있습니다. 유료 플랜이 있는 서비스 플랜을 선택하는 경우 비용 추정기 도구를 사용하여 비용을 추정할 수 있습니다. 자세한 정보는 [비용 추정](/docs/billing-usage/estimating_costs.html#cost)을 참조하십시오.

{{site.data.keyword.Bluemix_notm}} 청구는 {{site.data.keyword.Bluemix_notm}} 플랫폼에서 가격, 계정, 사용량 등을 안전하게 관리할 수 있도록 하는 여러 서비스를 제공합니다.

### {{site.data.keyword.Bluemix_notm}} 계정 관리
{: #account}

계정 관리는 고객과의 청구 관계를 유지보수합니다. 각 계정은 고객을 나타내는 청구 엔티티입니다. 이 서비스는 계정 라이프사이클, 계정 구독, 계정 사용자 관계 및 계정 조직을 제어합니다. 

### {{site.data.keyword.Bluemix_notm}} 가격
{: #pricing}

{{site.data.keyword.Bluemix_notm}} 가격 플랫폼 서비스는 사용자가 {{site.data.keyword.Bluemix_notm}} 카탈로그에 있는 리소스에 대한 가격 정보를 정의, 관리 및 검색하는 데 도움을 줍니다.

### {{site.data.keyword.Bluemix_notm}} 측정 콜렉터
{: #metering}

{{site.data.keyword.Bluemix_notm}} 사용량 측정은 서비스 제공업체에서 {{site.data.keyword.Bluemix_notm}} 사용자가 프로비저닝한 리소스 인스턴스에 대해 수집된 메트릭을 제출할 수 있도록 하는 플랫폼 서비스입니다. {{site.data.keyword.Bluemix_notm}}에서 통합 청구 서비스를 제공하는 서드파티 서비스 제공업체는 매시간 모든 활성 서비스 인스턴스에 대한 사용량을 제출해야 합니다. 사용량을 보고하지 못하면 IBM에 대한 수익 콜렉션이 손실될 수 있으며 이로 인해 서드파티 서비스 제공업체에 대한 수익 배당이 손실될 수 있으므로 제출은 중요합니다. 

## {{site.data.keyword.Bluemix_notm}} IAM(Identity and Access Management)
{: #iam}

{{site.data.keyword.Bluemix_notm}} Identity and Access Management(IAM)를 사용하면 두 플랫폼 서비스 모두에 대해 안전하게 사용자를 인증하고 {{site.data.keyword.Bluemix_notm}} 플랫폼에서 일관되게 리소스에 대한 액세스를 제어할 수 있습니다. 세부사항은 [IAM 개념](/docs/iam/index.html)을 참조하십시오. IAM에서는 토큰, 액세스 그룹 및 정책을 관리하는 데 도움이 되는 CLI 명령 및 API를 제공합니다.


## 리소스 작성
{: #provisioning-layer}

리소스 제어기는 고객 계정에 있는 {{site.data.keyword.Bluemix_notm}} 리소스의 라이프사이클을 관리하는 차세대 {{site.data.keyword.Bluemix_notm}} 플랫폼 프로비저닝 계층입니다. 리소스는 계정 범위에서 글로벌로 프로비저닝됩니다. 리소스 제어기는 동기 및 비동기 리소스 프로비저닝을 모두 지원합니다. 프로비저닝 계층은 고객 계정에 있는 리스소의 라이프사이클을 제어하고 추적합니다. 리소스는 는 애플리케이션 또는 서비스 인스턴스에 대해 프로비저닝되거나 예약될 수 있는 물리적 또는 논리적 컴포넌트입니다. 리소스의 예로는 데이터베이스, 계정, 프로세서, 메모리 및 스토리지 한계가 있습니다. 일반적으로 프로비저닝 계층에서 추적하는 리소스는 사용량 메트릭과 청구를 연관시키는 데 사용되지만 항상 그렇지는 않습니다. 어떤 경우에는 리소스가 프로비저닝 계층과 연관되어 리소스 라이프사이클이 계정 라이프사이클과 함께 관리될 수 있습니다. 리소스 제어기는 프로비저닝 계층에 대해 수행되는 조치의 인증 및 권한 부여를 위해 IAM을 사용합니다.

### 리소스 라이프사이클 관리
{: #lifecycle}

리소스 제어기는 프로비저닝(인스턴스 작성)에서 바인딩(액세스 인증 정보 작성), 바인딩 해제(액세스 제거), 디프로비저닝(인스턴스 삭제)까지의 리소스 라이프사이클을 제어하는 일반 API를 제공합니다. 

리소스 제어기는 리소스 라이프사이클의 다음 요소를 관리하는 데 도움이 되는 API를 제공합니다.
* 프로비저닝
* 리소스 인스턴스 업데이트
* 바인딩
* 리소스 키
* 바인딩 해제
* 디프로비저닝


## 리소스 관리
{: #resource-manager}


{{site.data.keyword.Bluemix_notm}} 리소스 관리자는 [리소스 그룹](/docs/overview/resource-groups.html#whatis)별로 리소스 콜렉션을 관리합니다. 리소스 그룹은 계정에 속합니다. 모든 {{site.data.keyword.Bluemix_notm}} 리소스는 리소스 그룹 내에 프로비저닝되어야 합니다. 계정이 일시중단되면 해당 리소스 그룹도 일시중단되며 리소스 그룹 내의 모든 리소스가 일시중단됩니다. 사용자가 계정을 작성할 때 기본 리소스 그룹이 계정에 작성됩니다. 모든 {{site.data.keyword.Bluemix_notm}} IAM 사용 리소스가 리소스 그룹 내에 프로비저닝되어야 합니다. 계정이 일시중단되면 해당 리소스 그룹도 일시중단되며 리소스 그룹 내의 모든 리소스가 일시중단됩니다. 표준 계정의 경우 사용자에게 하나의 리소스 그룹만 있을 수 있습니다. 종량과금제 또는 구독 계정의 경우 사용자가 둘 이상의 리소스 그룹을 작성할 수 있습니다. 


## {{site.data.keyword.Bluemix_notm}} 카탈로그
{: #catalog}

{{site.data.keyword.Bluemix_notm}} 카탈로그는 {{site.data.keyword.Bluemix_notm}} 콘솔에 표시되는 리소스의 오퍼링 정의(설명, 기능, 이미지, URL 등)를 저장합니다. 카탈로그 서비스는 여러 지역의 오퍼링을 SOR(System of Record)로 관리합니다. 카탈로그는 기존 오퍼링에 대한 정보를 검색하고 해당 오퍼링을 작성, 관리 및 삭제할 수 있는 CLI 및 RESTful API를 지원합니다. 기본 URL로 시작하고 엔드포인트를 사용하여 카탈로그에 있는 서비스에 대한 메타데이터를 검색하고 서비스 가시성을 관리하십시오. 오브젝트의 유형에 따라 메타데이터에는 가격, 프로비저닝, 지역 등에 대한 정보가 포함될 수 있습니다. 자세한 정보는 [카탈로그 관리 문서](/docs/overview/catalog.html#global-catalog-overview)를 참조하십시오.

## 리소스 검색 및 태그 지정
{: #search-and-tag}

검색 서비스는 {{site.data.keyword.Bluemix_notm}} 플랫폼 내에 통합된 글로벌 공유 리소스 특성 저장소입니다. 검색 서비스는 클라우드 리소스의 속성을 저장하고 검색하는 데 사용되며 리소스를 분류합니다. {{site.data.keyword.Bluemix_notm}} 플랫폼 내에서 Cloud Foundry, IBM Containers 또는 리소스 제어기와 같은 리소스 제공자가 리소스를 제어하고 소유합니다. 리소스는 [클라우드 리소스 이름](/docs/overview/crn.html#crn) ID(CRN)로 고유하게 식별됩니다. 리소스의 특성에는 태그 및 시스템 특성이 포함됩니다. 두 특성 모두 {{site.data.keyword.Bluemix_notm}} 청구 계정 내에 정의되며 여러 지역에 걸쳐 적용됩니다.

또한 이 서비스는 리소스와 연관된 태그를 관리합니다. 태그 지정 API를 사용하여 태그를 작성, 삭제, 검색, 첨부 또는 분리할 수 있습니다. 태그는 클라우드 리소스 이름(CRN) ID로 고유하게 식별됩니다. 태그에는 이름이 있으며, 이름은 청구 계정 내에서 고유해야 합니다. `key:value` 또는 레이블 형식으로 태그를 작성할 수 있습니다.


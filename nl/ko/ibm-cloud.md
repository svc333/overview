---


copyright:
  years: 2016, 2018
lastupdated: "2018-11-01"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# 플랫폼 개요
{: #overview}

{{site.data.keyword.IBM_notm}}의 혁신적 클라우드 컴퓨팅 플랫폼은 PaaS(Platform as a Service)를 IaaS(Infrastructure as a Service)와 결합하며, 여기에는 비즈니스 애플리케이션의 빌드를 위해 PaaS 및 IaaS와 통합될 수 있는 클라우드 서비스의 카탈로그가 포함되어 있습니다.
{:shortdesc}

{{site.data.keyword.cloud_notm}}(이전의 Bluemix)에는 확장을 계획 중인 중소기업인지 또는 추가적인 격리가 필요한 대기업인지 여부와 무관하게 요구사항에 맞는 배치가 있습니다. 경계 없이 클라우드에서 개발이 가능하며, 여기서 개인 서비스를 {{site.data.keyword.IBM_notm}}에서 사용 가능한 공용 {{site.data.keyword.cloud_notm}} 서비스에 연결할 수 있습니다. 사용자 및 사용자의 팀은 {{site.data.keyword.cloud_notm}}의 앱, 서비스 및 인프라에 액세스할 수 있으며 기존 데이터, 시스템, 프로세스, PaaS 도구 및 IaaS 도구를 사용할 수 있습니다. 개발자는 사용 가능한 서비스 및 런타임 프레임워크의 빠르게 성장하는 에코시스템을 활용하여 여러 언어로 쓰인 프로그래밍 접근을 통해 애플리케이션을 빌드할 수 있습니다.

{{site.data.keyword.cloud_notm}}를 사용하면 더 이상 하드웨어에 막대한 금액을 투자하여 새로운 앱을 테스트하거나 실행할 필요가 없습니다. 대신에 IBM이 모든 것을 관리하며 실제 사용량에 대해서만 금액을 청구합니다. {{site.data.keyword.cloud_notm}}는 퍼블릭, [데디케이티드](/docs/dedicated/index.html) 및 [로컬](/docs/local/index.html) 통합 배치 모델을 제공합니다.

도입/인식(Inception)에서부터 개발 샌드박스, 글로벌하게 분배된 환경까지 {{site.data.keyword.IBM_notm}}, Watson 등에서 제공하는 컴퓨팅 및 스토리지 인프라, 오픈 소스 플랫폼 및 컨테이너 및 소프트웨어 서비스 및 도구를 사용하여 의견을 제시할 수 있습니다. 플랫폼 자체의 기능을 넘어 {{site.data.keyword.cloud}}는 유연한 배치를 제공합니다. 데디케이티드 프라이빗 클라우드 환경 또는 퍼블릭 클라우드에서 {{site.data.keyword.cloud}} 리소스 온프레미스를 프로비저닝합니다.

퍼블릭 및 데디케이티드 환경에 배치되는 모든 {{site.data.keyword.IBM_notm}} Cloud 리소스는 사용자가 원하는 전세계의 {{site.data.keyword.CloudDataCent}} 위치에서 호스팅됩니다. {{site.data.keyword.CloudDataCents_notm}}는 지역 중복성, 모든 데이터 센터 및 PoP(Point of Presence)를 연결하는 글로벌 네트워크 백본, 엄격한 보안 제어 및 보고를 제공합니다. {{site.data.keyword.CloudDataCents_notm}}를 통해 {{site.data.keyword.IBM_notm}}은 가장 까다로운 확장, 보안, 규제 준수 및 데이터 주거성(residency) 요구사항을 충족시킬 수 있습니다.

{{site.data.keyword.IBM_notm}}를 사용하면 다음을 수행할 수 있습니다.

* 전세계의 보안 {{site.data.keyword.CloudDataCents_notm}}에서 고성능 컴퓨팅 및 스토리지 인프라를 배치합니다.
* {{site.data.keyword.IBM_notm}}, 오픈 소스 커뮤니티 및 서드파티 개발자로부터 광범위한 클라우드 서비스 및 기능을 테스트하고 채택합니다.
* 사설 네트워크 및 API 기능을 통해 단일, 확장, 클라우드 플랫폼에서 모든 레거시 시스템 및 앱에 연결합니다.
* 비즈니스 또는 워크로드 요구사항이 변화하는 데 따라 실시간으로 리소스를 강화하거나 약화시킬 수 있습니다.

## 앱
{: #bluemixoverviewapplications}

대시보드는 앱을 시작하고 실행하며 실행 중에 해당 앱을 관리하는 데 필요한 모든 것을 제공합니다. {{site.data.keyword.cloud_notm}}는 다양한 표준 유형 및 런타임을 제공합니다.

* 표준 유형은 특정 도메인에 대한 애플리케이션 및 그 연관된 런타임 환경과 사전 정의된 서비스의 템플리트입니다.
* 런타임은 앱 실행에 사용되고 다른 유형의 앱을 위한 컨테이너로 제공되는 리소스 세트입니다.

{{site.data.keyword.cloud_notm}}에서는 앱을 실행할 수 있도록 다양한 방법을 제공합니다(예: Cloud Foundry 및 {{site.data.keyword.containerlong}}). {{site.data.keyword.containerlong}}를 사용하여 {{site.data.keyword.cloud_notm}}의 호스팅된 클라우드 환경에 Docker 컨테이너를 실행하십시오.

분산형, 이벤트 구동 컴퓨팅에 {{site.data.keyword.openwhisk}}를 사용할 수 있습니다. {{site.data.keyword.openwhisk_short}}는 HTTP를 통한 웹 또는 모바일 앱에서의 직접 호출이나 이벤트에 응답하여 애플리케이션 로직을 실행합니다.

{{site.data.keyword.cloud_notm}} Mobile 서비스를 사용하여 미리 빌드되고 관리되며 확장 가능한 클라우드 서비스를 사용자의 모바일 앱에 통합할 수 있습니다.

## 서비스
{: #bluemixoverviewservices}

대시보드는 {{site.data.keyword.IBM}} 및 서드파티 제공업체에서 사용 가능한 {{site.data.keyword.cloud_notm}} 서비스에 대한 액세스를 제공합니다. Watson, Internet of Things, Analytics, Mobile 및 DevOps 서비스가 여기에 해당됩니다.

* {{site.data.keyword.IBM_notm}} DevOps 서비스 및 IBM Cloud Garage Method를 사용하여 최적의 기능이 포함된 혁신적인 새 애플리케이션을 더 빠르고 저렴하게 제공합니다. DevOps 사례를 채택하고 혁신과 민첩성이 요구되는 문화를 조성하는 경우 반복적으로 시행하여 시장 상황에 따라 방향을 바꿀 수 있습니다.
* Blockchain은 비즈니스 프로세스를 간소화하면서 신뢰, 책임 및 투명성을 확립하는 차세대 트랜잭션 애플리케이션을 위한 피어 투 피어 분산 원장 기술입니다.  
* Watson은 사용자의 앱에 음성, 영상 및 데이터 API의 전체 세트로 코그너티브 컴퓨팅의 강력함을 제공합니다.  Watson 서비스를 통해 코그너티브 플랫폼을 배치하여 가장 복잡한 비즈니스 문제점을 해결하십시오.
* {{site.data.keyword.IBM_notm}}를 통해 풍부한 통합 클라우드 데이터베이스, Data & Analytics 서비스로 더 많은 작업을 수행할 수 있습니다.
* {{site.data.keyword.IBM_notm}} Internet of Things 서비스를 사용하여 앱은 연결된 디바이스, 센서 및 게이트웨이와 통신하고 여기서 수집한 데이터를 이용할 수 있습니다. IBM이 제안하는 방법을 사용하여 Internet of Things 클라우드에 연결된 디바이스를 쉽게 얻을 수 있습니다. 그러면 앱에서 실시간 및 REST API를 사용하여 디바이스와 통신하고 수집하도록 설정된 데이터를 이용할 수 있습니다.
* {{site.data.keyword.IBM_notm}}는 멀티플랫폼, 기본 또는 하이브리드 앱을 모니터하고 테스트하는 동시에 이들을 빌드할 수 있는 모바일 백엔드 인프라를 제공합니다. 또한 분석, 보안, 사용자 인사이트 및 Continuous Delivery를 사용하여 앱을 개선시킬 수도 있습니다.

{{site.data.keyword.cloud_notm}}는 사용해 볼 수 있는 시범 서비스도 제공합니다. 서비스 유형 및 가용성에 대한 자세한 정보는 [{{site.data.keyword.cloud_notm}} 서비스](/docs/services/index.html)를 참조하십시오.


## 인프라
{: #bluemixoverviewinfrastructure}

대시보드는 클라우드 인프라 요구사항에 맞는 다양한 서비스를 제공합니다.

{{site.data.keyword.cloud_notm}} 인프라는 사용 가능한 고성능 클라우드 인프라를 제공합니다. {{site.data.keyword.cloud_notm}} 인프라는 광범위한 클라우드 컴퓨팅 옵션으로 전세계의 데이터 센터를 가져온 후 모든 것을 통합하고 자동화하는 플랫폼입니다. {{site.data.keyword.CloudDataCents_notm}}는 첫 번째 클래스 컴퓨팅, 스토리지 및 네트워킹 장비로 구성됩니다. 각 위치는 동일한 방식으로 빌드되고 공급되고 작동되므로 모든 영역에서 동일한 기능 및 가용성을 정확하게 얻을 수 있습니다. 위치는 개별 퍼블릭, 사설 및 내부 관리 네트워크를 통합하여 더 낮은 전체 네트워킹 비용, 더 나은 액세스 및 더 빠른 속도를 제공하는 산업의 가장 고급 네트워크 내 네크워크로 연결됩니다. 또한 데이터 센터 및 네트워크는 단일 개인 기업 관리 시스템을 공유합니다. 하나의 관리 도구를 사용하면 모든 베어메탈 서버, 가상 서버 및 API로 액세스 가능한 스토리지 디바이스 및 모바일 애플리케이션을 모두 제어할 수 있습니다.

{{site.data.keyword.cloud_notm}} 인프라는 완벽한 단일 플랫폼에서 강력한 베어메탈 서버 및 유연한 가상 서버를 제공합니다. 모든 것은 요청 시 제공되며 월별 및 시간별로 빌드됩니다. 베어메탈 서버는 프로세서 중심 및 디스크 I/O 중심 워크로드에 대한 원시 마력을 제공하며 사용자의 정확한 스펙으로 구성될 수 있습니다. 가상 서버는 배치의 빠른 속도, 유연한 확장성 및 종량과금제 청구를 허용합니다. 고성능 컴퓨팅을 위해 시간별 또는 월별로 사용 가능한 GPU(Graphics Processing Unit) 서버를 사용하여 클라우드의 효과를 증대시키십시오.

{{site.data.keyword.cloud_notm}} 인프라 오퍼링은 3계층 네트워크, 퍼블릭, 사설 및 관리 트래픽 세분화에 연결됩니다. 고객의 {{site.data.keyword.cloud_notm}} 계정에 대한 인프라는 무료로 사설 네트워크에서 데이터를 서로 전송할 수 있습니다. 베어메탈 서버, 가상 서버 및 클라우드 스토리지와 같은 인프라 오퍼링은 공용 네트워크를 통해 {{site.data.keyword.cloud_notm}} 카탈로그(예: Watson 서비스, 컨테이너 또는 런타임)의 다른 애플리케이션 및 서비스에 연결합니다. 두 유형의 오퍼링 간의 데이터 전송은 표준 공용 네트워크 대역폭 비율로 측정되고 청구됩니다.

## {{site.data.keyword.cloud_notm}} 복원성
{: #resiliency}

{{site.data.keyword.cloud_notm}}는 사용자 요구사항을 충족할 수 있도록 확장하고 고가용성을 유지하며 문제점에서 빠르게 복구할 수 있는, 확장 가능한 복원성을 갖춘 앱 및 애플리케이션 아티팩트를 호스팅하도록 디자인되었습니다. {{site.data.keyword.cloud_notm}}는 상호작용의 상태를 추적하는 컴포넌트(stateful)를 그렇지 않은 컴포넌트(stateless)와 구분합니다. 이러한 구분을 통해 {{site.data.keyword.cloud_notm}}는 확장성과 복원성을 달성하는 데 필요한 만큼 앱을 유연하게 이동할 수 있습니다.

앱에 대해
실행 중인 인스턴스가 하나 이상 있을 수 있습니다. 단일 앱이 여러 개 있는 경우 앱은 한 번만 업로드됩니다. 하지만 {{site.data.keyword.cloud_notm}}는 요청된 수의 앱 인스턴스를 배치하고 가능한 한 많은 가상 서버에 앱을 분배합니다.

앱 외부에 있는 Stateful 데이터 저장소(예: {{site.data.keyword.cloud_notm}}에서 제공하는 데이터 저장소 서비스 중 하나)에 모든 지속적 데이터를 저장해야 합니다. 다시 시작한 후에도 메모리 또는 디스크에 캐시된 항목을 사용하지 못할 수 있으므로 단일 {{site.data.keyword.cloud_notm}} 인스턴스의 메모리 공간 또는 파일 시스템을 간단한 단일 트랜잭션 캐시로 사용할 수 있습니다. 단일 인스턴스 설정을 사용하면 {{site.data.keyword.cloud_notm}}의 Stateless 특성 때문에 앱에 대한 요청이 중단될 수 있습니다. 앱의 가용성을 보장하기 위해 각 앱에 대해 3개 이상의 인스턴스를 사용하는 것이 좋습니다.

모든 {{site.data.keyword.cloud_notm}} 인프라, Cloud Foundry 컴포넌트 및 {{site.data.keyword.cloud_notm}} 특정 관리 컴포넌트는 가용성이 높습니다. 인프라의 여러 인스턴스는 로드의 균형을 유지하는 데 사용됩니다.


## SOR(System of Record)과 통합
{: #sor}
{{site.data.keyword.cloud_notm}}는 클라우드 환경의 두 가지 광범위한 시스템 카테고리를 연결함으로써 개발자를 지원할 수 있습니다.

* *SOR(System of Record)*에는 비즈니스 레코드를 저장하고 표준화된 프로세스를 자동화하는 앱 및 데이터베이스가 포함됩니다.
* *SOE(System of Engagement)*는 SOR(System of Record)의 유용성을 확장하고 사용자에게 보다 광범위하게 적용할 수 있도록 만드는 기능입니다.

{{site.data.keyword.cloud_notm}}에서 작성한 앱과 SOR(System of Record)을 통합하여 다음 조치를 수행할 수 있습니다.

 * 보안 커넥터 온프레미스를 다운로드하고 설치하여 앱과 백엔드 데이터베이스 간 보안 통신을 사용합니다.
 * 데이터베이스를 안전한 방식으로 호출합니다.
 * 고객 관계 관리 시스템과 같은 데이터베이스와 백엔드 시스템이 있는 통합 플로우에서 API를 작성합니다.
 * 앱에 노출할 스키마 및 테이블만 노출합니다.
 * {{site.data.keyword.cloud_notm}} 조직 관리자로서 조직 구성원에게만 표시되는 개인 서비스로 API를 공개합니다.
 
<!-- To integrate a system of record with the app that you create in {{site.data.keyword.cloud_notm}}, use the Cloud Integration service. By using the Cloud Integration service, you can create a Cloud Integration API and publish the API as a private service for your organization.
<dl>
<dt>Cloud Integration API</dt>
    <dd>A Cloud Integration API provides secured access to the systems of record that reside behind a firewall through web APIs. When you create the Cloud Integration API, you choose the resource that you want to access through the web API, specify the operations that are permitted, and include SDKs and samples to access the API. For more information about how to create a Cloud Integration API, see [Getting started with Cloud Integration](/docs/services/CloudIntegration/CldInt_GetStart.html).</dd>
<dt>Private service</dt>
    <dd>A private service consists of a Cloud Integration API, SDKs, and entitlement policies. The private service might also  contain documentation or other items from the service provider. Only the organization manager can publish a Cloud Integration API as a private service. To see the private services that are available to you, select the Private checkbox in the {{site.data.keyword.cloud_notm}} catalog. You can select and bind a private service to an app without connecting to the Cloud Integration service. You bind private services to your app in the same way as you do for other {{site.data.keyword.cloud_notm}} services. For information about how to publish an API as a private service, see Publishing an API as a private service.</dd>
</dl>
### Scenario: Creating a rich mobile app to connect with your system of record
{: #scenario}
{{site.data.keyword.cloud_notm}} provides a platform where you can integrate your mobile app, cloud services, and enterprise systems of record to provide an app that interacts with your on-premises data.
For example, you can build a mobile app to interact with your customer relationship management system that resides on-premises behind a firewall. You can invoke the system of record in a secure way and leverage the mobile services in {{site.data.keyword.cloud_notm}} so that you can build a rich mobile app.
First, your integration developer creates the mobile back-end app in {{site.data.keyword.cloud_notm}}. They use the Mobile Cloud boilerplate that uses the Node.js runtime that they are most familiar with.
Then, by using the Cloud Integration service in the {{site.data.keyword.cloud_notm}} user interface, they expose an API through a secure connector. Your integration developer downloads the secure connector and installs it on-premises to enable secure communication between his API and the database. After they create the database endpoint, they can look at all the schemas and extract the tables that they want to expose as APIs to the app.
The integration developer adds the Push service to deliver mobile notifications to interested consumers. They also add a business partner service to tweet when a new customer record is created with a Twitter API.
Next, as the application developer, you can log in to {{site.data.keyword.cloud_notm}}, download the Android development toolkit, and develop code that invokes the APIs that your integration developer created. You can develop a mobile app that enables users to enter their information on their mobile device. The mobile app then creates a customer record in the customer management system. When the record is created, the app pushes a notification to a mobile device and initiates a tweet about the new record. -->

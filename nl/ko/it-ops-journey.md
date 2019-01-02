---

copyright:
  years: 2018
lastupdated: "2018-11-30"


---
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}
{:tip: .tip}
{:note: .note}

# {{site.data.keyword.cloud_notm}}의 IT 운영 관리자 과정 탐색
{: #it-ops}

많은 조직이 온프레미스 또는 데이터 센터에서 호스팅되는 클라우드 환경으로 이동함에 따라 IT 운영 관리자 역할이 재정의되고 있습니다. 조직에서 배치하려는 환경의 유형에 따라 이 변경의 범위와 복잡도가 크게 증가합니다.
{: .shortdesc}

클라우드로 이동하기 전에는 사설 LAN 또는 인트라넷에 연결된 시스템을 사용하여 본질적으로 안전한 환경에서 작업했습니다. 클라우드 환경에서는 다음과 같은 태스크를 수행합니다.
 
  * "다른 위치"에서 시스템 컴포넌트를 조달합니다. 
  * 네트워크에 함축된 내용과 보안 과제를 이해합니다.
  * 다양한 기술로 작업합니다.  
  * 새 환경을 원래 클라우드 스택의 일부가 아닌 도구와 통합합니다. 
  * 여전히 온프레미스 데이터 센터가 있는 것처럼 내부 고객을 계속 지원합니다.

{{site.data.keyword.cloud}}에서 이러한 과정을 100% 지원합니다. 사용자가 사용할 수 있는 리소스에는 포괄적인 문서, 계획 도구, 자격이 있는 지원 전문가 및 활성 사용자 커뮤니티가 포함됩니다. 이제 이 과정을 시작합니다. 

## 기본사항 이해
{: #basics}

### 클라우드 서비스 모델
{: #cloud-svc-models}

IaaS(Infrastructure as a Service), PaaS(Platform as a Service), SaaS(Software as a Service) 등 세 가지 유형의 클라우드 서비스 모델이 있습니다. 그림 1에는 각 서비스 모델 내에서 수행되는 작업과 주체가 설명되어 있습니다. 자세한 정보는 [IaaS, PaaS, and SaaS - IBM Cloud service models](https://www.ibm.com/cloud/learn/iaas-paas-saas){: new_window} ![외부 링크 아이콘](../icons/launch-glyph.svg "외부 링크 아이콘")를 참조하십시오.

![그림 1. 클라우드 서비스 모델](images/cloud-svc-models.png "클라우드 서비스 모델")

IaaS 모델에서는 제공자가 기본 인프라만 유지보수하고 선택적으로 운영 체제, 애플리케이션 및 데이터베이스와 같은 소프트웨어의 설치를 담당합니다. 기본 인프라에 대한 액세스가 제한되며 소프트웨어 설치를 담당하거나 서비스 제공자가 설치하도록 합니다. 또한 서비스 팩, 바이러스 소프트웨어 및 패치를 포함한 다른 모든 유지보수에 대한 책임이 있습니다.

PaaS 모델에서는 제공자가 운영 체제를 통해 시스템을 담당하고 OS, 패치, 하드웨어 복구 및 네트워크 설정을 포함하는 모든 인프라 관리를 담당합니다. 사용자가 애플리케이션을 빌드하고 유지보수하며 사용자 또는 제공자가 데이터베이스 또는 기타 유형을 포함한 미들웨어를 설치할 수 있습니다. 이 모델은 소프트웨어를 개발하고 테스트하는 데 사용됩니다. 자세한 정보는 [A practical guide to platform as a service: What is PaaS ![외부 링크 아이콘](../icons/launch-glyph.svg "외부 링크 아이콘")](https://www.ibm.com/blogs/cloud-computing/2016/08/10/practical-guide-paas/){: new_window}를 참조하십시오.

SaaS 모델에서는 제공자가 실제 애플리케이션을 통해 시스템을 유지보수합니다. 애플리케이션은 클라우드를 인식하며 일반 사용자는 소프트웨어 제공자에 따라 서로 다른 엔드포인트를 사용하여 소프트웨어를 사용할 수 있습니다. 클라우드 제공자는 소프트웨어 업데이트, 하드웨어 복구 및 네트워크 설정을 포함하는 모든 인프라 및 애플리케이션 관리를 담당합니다. 이 모델은 종종 종량과금제 소프트웨어 라이센싱 모델에서 사용됩니다. 자세한 정보는 [SaaS applications for business and IT](https://www.ibm.com/cloud/saas){: new_window} ![외부 링크 아이콘](../icons/launch-glyph.svg "외부 링크 아이콘")를 참조하십시오.

### 클라우드 유형
{: #cloud-types}

세 가지 다른 유형의 클라우드(퍼블릭, 프라이빗, 하이브리드)가 사용 가능합니다. 퍼블릭 클라우드에는 회사의 리소스에 대한 액세스를 허용하도록 프로비저닝된 공유 리소스 세트가 포함됩니다. 가상 서버의 멀티 테넌트 환경에서 호스팅되며 어디서든 액세스할 수 있습니다. 

프라이빗 클라우드에는 회사의 리소스에 대한 액세스를 허용하도록 프로비저닝된 리소스가 포함됩니다. 전용 하드웨어(예: Bare Metal Server)에서 호스팅되며 회사 사무실(또는 전체 사무실)에서 온사이트로 또는 클라우드 제공업체에서 호스팅됩니다. 어디서든 프라이빗 클라우드에 액세스할 수 있습니다.

하이브리드 클라우드에는 퍼블릭 및 프라이빗 클라우드 둘 다의 측면을 결합하는 리소스가 포함됩니다. 회사 사무실(또는 전체 사무실)의 온사이트 및 클라우드 제공업체 모두에서 호스팅됩니다. 어디서든 하이브리드 클라우드에 액세스할 수 있습니다. 

## 인프라 계획
{: #planning}

워크로드에 맞게 인프라 크기를 조정하기 위해 실제로 프로비저닝하기 전에 인프라를 계획하려고 할 수 있습니다. {{site.data.keyword.cloud_notm}}에는 인프라를 디자인하고 크기를 조정하는 데 도움이 되는 여러 도구와 사이트가 있습니다. 

### 인프라 아키텍처

세 가지 유형의 클라우드 환경에 대한 보다 세부적인 개요를 얻으려면 [인프라 아키텍처 ![외부 링크 아이콘](../icons/launch-glyph.svg "외부 링크 아이콘")](https://www.ibm.com/cloud/garage/architectures/infrastructure){: new_window}에서 시작하십시오. 

### {{site.data.keyword.cloud_notm}} Design Decision Tool

[{{site.data.keyword.cloud_notm}} Design Decision Tool ![외부 링크 아이콘](../icons/launch-glyph.svg "외부 링크 아이콘")](https://github.com/ibm-cloud-architecture/infrastructure-design-decision-tool/){: new_window}은 사용자 정의 솔루션을 디자인하고 빌드할 때 대안을 비교하는 데 도움이 됩니다. 각 인프라 컴포넌트는 설명, 고려사항 및 제한사항, 단계별 비교를 포함합니다. 도구 사용 방법에 대한 예제를 찾을 수도 있습니다.

### {{site.data.keyword.cloud_notm}} 스텐실

[{{site.data.keyword.cloud_notm}} 스텐실 ![외부 링크 아이콘](../icons/launch-glyph.svg "외부 링크 아이콘")](https://github.com/ibm-cloud-architecture/ibm-cloud-stencils){: new_window}은 인기 있는 다이어그램 도구를 사용하여{{site.data.keyword.cloud_notm}} 아키텍처의 다이어그램을 작성하는 데 도움을 줍니다. 

### Bare Metal Server 옵션

[{{site.data.keyword.cloud_notm}} {{site.data.keyword.baremetal_short}} 검색 도구 ![외부 링크 아이콘](../icons/launch-glyph.svg "외부 링크 아이콘")](https://www.ibm.com/cloud-computing/bluemix/bare-metal-search){: new_window}를 사용하여 SAP HANA 및 SAP NetWeaver 워크로드를 지원하도록 인증된 서버를 포함하여 Bare Metal Server 옵션의 크기를 조정하고 추정할 수 있습니다.

### {{site.data.keyword.cloud_notm}} 서비스 및 규제 준수

다른 아키텍처와 마찬가지로 인프라의 크기를 조정할 때 솔루션에 추가할 수 있는 {{site.data.keyword.cloud_notm}} 리소스를 고려해야 합니다. 자세한 정보는 [SaaS applications for business and IT ![외부 링크 아이콘](../icons/launch-glyph.svg "외부 링크 아이콘")](https://www.ibm.com/cloud/saas){: new_window}를 참조하고 특성 서비스를 검색하십시오. 아키텍처를 빌드할 때 고려해야 하는 규정에 대해서도 생각해야 합니다(예: 워크로드가 민감한 것으로 간주됩니까, 아니면 규제됩니까?). 자세한 정보는 [규제 준수 ![외부 링크 아이콘](../icons/launch-glyph.svg "외부 링크 아이콘")](https://www.ibm.com/cloud/compliance){: new_window}를 참조하십시오.

## 인프라 빌드
{: #build}

인프라를 계획하고 디자인하면 인프라를 빌드할 준비가 된 것입니다. 

### 컴퓨팅
{: #compute}

서버는 인프라의 기반입니다. 요구사항에 따라 사용할 수 있는 다양한 옵션이 있습니다. 또는 사용자 환경에 필요한 경우 혼합할 수 있습니다. 컴퓨팅 옵션에 대한 요약은 다음 표를 확인하십시오.

|옵션 |설명 | 
|--------|---------------|
| [{{site.data.keyword.baremetal_short}}](/docs/bare-metal/about.html)  |사용자 전용이며 서버 리소스를 포함한 모든 파트에서 다른 고객과 공유되지 않는 시간별 또는 월별 싱글 테넌트 서버입니다. |
| [{{site.data.keyword.BluVirtServers_short}}](/docs/vsi/vsi_about.html) |전용 코어와 메모리 할당을 포함하여 구매하는 확장 가능한 서버입니다. |
| [{{site.data.keyword.vmwaresolutions_short}}](/docs/services/vmwaresolutions/vmonic/prod_overview.html) |확장 가능하고 안전한 고성능 인프라 및 업계 최고의 VMware 하이브리드 가상화 기술을 사용하여 온프레미스 VMware 워크로드를 빠르고 원활하게 통합하거나 마이그레이션합니다. |
| [{{site.data.keyword.containerlong_notm}}](/docs/containers/cs_why.html) |Docker 컨테이너, Kubernetes 기술, 직관적인 사용자 경험, 기본 제공 보안 및 격리를 결합하여 컴퓨팅 호스트의 클러스터에서 컨테이너화된 앱의 배치, 오퍼레이션, 스케일링 및 모니터링을 자동화합니다. |
| [{{site.data.keyword.cfee_full_notm}}](/docs/cloud-foundry/index.html) |격리된 여러 엔터프라이즈급 Cloud Foundry 플랫폼을 요청 시 인스턴스화합니다. |
| [{{site.data.keyword.openwhisk_short}}](/docs/openwhisk/index.html) |Apache OpenWhisk 기반의 FaaS(Function-as-a-Service) 프로그래밍 플랫폼입니다. |
{: caption="표 1. 컴퓨팅 옵션" caption-side="top"}
   
### 스토리지
{: #storage}

{{site.data.keyword.baremetal_short}} 및 {{site.data.keyword.BluVirtServers_short}}는 기본 스토리지로 프로비저닝됩니다. {{site.data.keyword.baremetal_short}}에는 최소 1TB SATA 디스크 공간이 있으며 {{site.data.keyword.BluVirtServers_short}}에는 최소 25GB SAN 스토리지가 있습니다. 이에 대한 예외는 {{site.data.keyword.cloud_notm}} SAP-Certified {{site.data.keyword.baremetal_short}}입니다. 이러한 서버에 사용 가능한 기본 스토리지에 대한 자세한 정보는 [{{site.data.keyword.cloud_notm}} SAP-Certified Infrastructure](/docs/bare-metal/bare-metal-sap-applications.html#ibm-cloud-sap-certified-infrastructure)를 참조하십시오.

필요에 따라 추가 스토리지를 구매할 수 있습니다. 컴퓨팅 옵션에 대한 요약은 다음 표를 참조하십시오.

|옵션 |설명 |
|--------|---------------|
| [{{site.data.keyword.blockstorageshort}}](/docs//infrastructure/BlockStorage/index.html) |컴퓨팅 인스턴스와 독립적으로 프로비저닝되고 관리되는 지속적인 고성능 iSCSI 스토리지입니다. iSCSI 기반 Block Storage LUN은 중복된 다중 경로 I/O(MPIO) 연결을 통해 권한이 부여된 디바이스에 연결됩니다. |
| [{{site.data.keyword.filestorage_short}}](/docs/infrastructure/FileStorage/index.html) |네트워크에 연결된 NFS 기반의 빠르고 지속적인 유연한 File Storage입니다. 이 NAS(Network-Attached Storage) 환경에서 파일 공유 기능 및 성능을 완전히 통제할 수 있습니다. File Storage 공유는 복원성을 위해 라우트된 TCP/IP 연결을 통해 최대 64개의 권한 부여된 디바이스에 연결될 수 있습니다. |
| [{{site.data.keyword.cos_full_notm}}](/docs/services/cloud-object-storage/about-cos.html) |IBM Cloud Object Storage와 함께 저장된 정보는 암호화되고 여러 지리적 위치에 걸쳐 분산되며 REST API를 사용하여 HTTP를 통해 액세스됩니다. 이 서비스는 IBM Cloud Object Storage System(이전의 Cleversafe)에서 제공되는 분산 스토리지 기술을 활용합니다. |
| [{{site.data.keyword.cloud_notm}} Mass Data Migration](/docs/infrastructure/mass-data-migration/index.html) |온프레미스 데이터 센터의 대용량 데이터를 Cloud Object Storage 버킷으로 오프로드합니다. |
| [EVault](/docs/infrastructure/Backup/index.html) |가상 서버에 대해서만 EVault WebCC 브라우저 기반 관리 유틸리티를 통해 관리되는 자동화된 에이전트 기반 백업 시스템입니다. IBM Cloud 네트워크의 하나 이상의 데이터 센터에 있는 서버 간에 데이터를 백업합니다. |
{: caption="표 2. 스토리지 옵션" caption-side="top"}

### 네트워킹
{: #network}

{{site.data.keyword.cloud_notm}} 계정이 설정될 때 {{site.data.keyword.vpn_full}}에 자동으로 연결됩니다. 기본적으로 서버에는 공인 IP 주소와 사설 IP 주소가 있습니다. 개인용 서버로 설정하려는 경우 서버가 프로비저닝된 후 공용 인터페이스를 끄거나 서버를 개인용으로 주문할 수 있습니다. 자세한 정보는 [VPN(Virtual Private Network) 시작하기](/docs/infrastructure/iaas-vpn/getting-started.html)를 참조하십시오.

네트워킹 옵션에 대한 요약은 다음 표를 확인하십시오.

|옵션 |설명 | 
|--------|---------------|
|[Content Delivery Network](/docs/infrastructure/CDN/about.html) |미디어, 엔터테인먼트, 소프트웨어, 게임, 뱅킹, e-commerce를 포함한 다양한 산업 솔루션에서 비즈니스 요구사항을 충족하기 위해 사용됩니다. |
|[Domain Name Service](/docs/cli/reference/ibmcloud/cli_dns.html) |기본 DNS 관리 인터페이스를 통해 고객의 도메인을 보고 관리할 수 있는 중앙 위치를 제공하며 동일한 위치에서 무료로 역방향 및 보조 DNS를 관리할 수 있는 옵션도 제공합니다. |
|[글로벌 IP 주소](/docs/infrastructure/subnets/about-global-ip.html) |유연성을 제공하고 지리적으로 서로 다른 데이터 센터에서도 서버 간에 워크로드를 이동할 수 있도록 합니다. |
|[로드 밸런싱](/docs/infrastructure/local-load-balancer/about.html) |단일 디바이스가 전체 로드를 수행하지 않도록 데이터 센터 내의 여러 서버 간에 처리 및 통신을 균등하게 분산시킵니다. |
|[가상 라우터 어플라이언스](/docs/infrastructure/virtual-router-appliance/about.html) |방화벽, 트래픽 형성, 정책 기반 라우팅, VPN 및 기타 여러 기능을 포함한 모든 기능을 갖춘 엔터프라이즈 라우터를 통해 사설 및 공용 네트워크 트래픽을 선택적으로 라우팅합니다. |
|[IPSec VPN](/docs/infrastructure/iaas-vpn/set-up-ipsec-vpn.html) |암호화된 사이트 간 네트워크를 제공하는 터널 모드를 사용하여 두 위치 간의 모든 IP 트래픽을 인증하고 암호화하도록 디자인된 프로토콜 스위트입니다. |
|{{site.data.keyword.cloud_notm}} Direct Link |Cloud Exchange 제공자를 활용하여 {{site.data.keyword.cloud_notm}} 인프라 위치에 연결합니다. |
{: caption="표 3. 네트워킹 옵션" caption-side="top"}


## 인프라 관리
{: #managing}

인프라 및 환경을 빌드하고 나면 관리를 시작할 준비가 된 것입니다.

|태스크 |설명 |
|--------|---------------|
|[시스템 이벤트 모니터](/docs/account/audit_log.html) |인프라 리소스에 대해 수행된 조치를 확인합니다. |
|[이메일 환경 설정 지정](/docs/account/email.html) |계획되지 않은 이벤트, 유지보수 및 공지사항에 대한 {{site.data.keyword.cloud_notm}} 인프라 이메일 알림을 설정합니다. |
|[데이터 보안 설정 방법 이해](/docs/overview/security.html) |{{site.data.keyword.cloud_notm}} 플랫폼은 네트워크 및 인프라에서 계층화된 보안 제어를 제공합니다. |
|[작동 중단이 발생하지 않도록 하는 방법 이해](/docs/overview/zero_downtime.html) |모든 {{site.data.keyword.cloud_notm}} 리소스는 전세계의 데이터 센터 위치에서 호스팅됩니다. |
{: caption="표 4. 관리 태스크" caption-side="top"}

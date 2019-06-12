---
copyright:
  years: 2019
lastupdated: "2019-06-04"

keywords: understanding infrastructure, vpc, classic infrastructure, cloud environment

subcollection: overview

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}
{:tip: .tip}
{:note: .note}

# {{site.data.keyword.cloud_notm}} 인프라 환경 비교
{: #compare-infrastructure}

{{site.data.keyword.cloud}} 인프라 환경 간의 주요한 차이점을 비교해 보면 사용자의 워크로드 및 애플리케이션에 가장 적합한 인프라 환경을 결정할 수 있습니다.
{: shortdesc}

환경 유형에 익숙하지 않은 경우에는 다음 설명을 검토하십시오. 

* 클래식 인프라는 기존의 IaaS 플랫폼입니다. 이 환경은 리프트 앤 시프트(lift and shift) 워크로드에 적합하므로, 동일한 아키텍처를 유지하면서 애플리케이션을 빠르게 이동할 수 있습니다. 
* VPC 인프라는 소프트웨어에서 정의한 네트워킹 기반의 새로운 IaaS 플랫폼으로, 클라우드 기본 애플리케이션에 적합합니다. 

클래식 인프라는 비용 중립적이므로, 어떤 환경이 자신의 요구에 부합하는지에 초점을 맞출 수 있습니다.
{: note}

## 컴퓨팅 차별화 요소
{: #compare-compute}

클래식 및 VPC 간 컴퓨팅 차이점은 다음 표를 참조하십시오. 카테고리 열에는 다양한 차별화 요소가 나열되어 있고, 클래식 인프라 및 VPC 인프라 열에는 설명이 나열되어 있습니다.  

| 카테고리   |  클래식 인프라   | VPC 인프라 |
| ---------- | ------------------------- | ------------------ |
|서비스  |{{site.data.keyword.baremetal_short}}, {{site.data.keyword.BluVirtServers_short}}
인스턴스, VMware, SAP 등 전체 서비스 카탈로그 | {{site.data.keyword.BluVirtServers_short}} 인스턴스만 |
| 성능 및 가용성 | | 구역 아키텍처를 통해 더 향상된 가용성을 얻을 수 있음 |
|가격 | 시간 및 월 단위 비용 청구 및 비용 청구 일시중단 기능 | 시간별 비용 청구, 비용 청구 일시중단, 지속 사용 할인|
| 가상 서버 제품군 | 공용, 전용, 임시, 예약 | 공용만 |
| 프로파일 | GPU 프로파일을 포함한 모든 프로파일 | 더 높은 RAM 및 vCPU 옵션을 제공하는 밸런스, 컴퓨팅, 메모리 프로파일 |
| 지원되는 이미지 | 전체 pre-stock 이미지 세트 및 사용자 정의 이미지 | 제한된 pre-stock 이미지 세트 |
| 플랫폼 통합 | | 통합된 환경을 위한 IAM 및 리소스 그룹 통합 |
{: caption="표 1. 컴퓨팅 비교" caption-side="top"}

## 네트워크 차별화 요소
{: #compare-network}

클래식 및 VPC 간 네트워킹 차이점은 다음 표를 참조하십시오. 카테고리 열에는 다양한 차별화 요소가 나열되어 있고, 클래식 인프라 및 VPC 인프라 열에는 설명이 나열되어 있습니다.  

| 카테고리   |  클래식 인프라   | VPC 인프라 |
| ---------- | ------------------------- | ------------------ |
| 위치 구성    | 데이터 센터 및 팟(POD) <br>(서로 다른 두 개의 팟(Pod)/데이터 센터를 연결하는 데 VLAN Spanning이 필요하고, 트래픽을 제어 및 라우트하는 데 구매 게이트웨이가 필요할 수 있음) |인프라를 추상화하는 지역 모델. 따라서 팟(Pod) 위치에 대해 걱정할 필요가 없습니다. |
| 네트워크 기능 및 서비스 |여러 공급업체에서 제공하는 실제/가상 어플라이언스 | 클라우드 기본 네트워크 기능(VPN, LBaaS) <br>(VPC 격리, 퍼블릭 클라우드에서 분리된 전용 리소스, VPN, LBaaS, 여러 vNIC 인스턴스 및 대형 서브넷 크기에 대한 추가 옵션 포함) |
| IP 주소 | IPv6 주소가 지원됨 | IPv4 주소만 |
| 게이트웨이 라우팅 | 가상 또는 실제 네트워크 어플라이언스(Virtual Router Appliance, Vyatta, Juniper vSRX, Fortinet FSA) 사용 | 트래픽 라우팅이 퍼블릭 게이트웨이 및 유동 IP 서비스를 통해 처리됨 |
| 네트워크 주소 변환(NAT) | 가상 또는 실제 네트워크 어플라이언스(Virtual Router Appliance, Vyatta, Juniper vSRX, Fortinet FSA) 사용 | BYOIP(Bring-your-own-IP) 기능을 통해 지원됨 |
| IPsec 가상 사설망(VPN) | 가상 또는 실제 네트워크 어플라이언스(Virtual Router Appliance, Vyatta, Juniper vSRX, Fortinet FSA) 사용 | VPN-as-a-service 오퍼링을 사용하여 지원됨 |
|  탄력적 로드 밸런싱 | Cloud Load Balancer  | Load Balancer for VPC |
| 글로벌 로드 밸런싱 | Cloud Internet Services, Citrix Netscaler MPX | Cloud Internet Services |
| 하이브리드 연결 | IBM Cloud와 사용자의 IT 환경을 연결하는 NAT 솔루션 | NAT 또는 IPSec 터널 없이 사용자 고유의 사설 IP 주소를 가져옴
<br>참고: 클래식 인프라 리소스에 액세스하기 위해 VPC를 사용으로 설정할 수 있습니다. |
{: caption="표 2. 네트워크 비교" caption-side="top"}

## 스토리지 차별화 요소
{: #compare-storage}

|  클래식 인프라   | VPC 인프라 |
| ------------------------- | ------------------ |
|강력한 스토리지 서비스 세트, 블록 스토리지(iSCSI) 및 파일 스토리지(NFS 기반) 오퍼링 | 기본 부트 디스크로 사용되는 블록 스토리지(기본 라이프사이클 관리 제공) 및 보조 데이터 볼륨) <br> 참고: 프로비저닝 중에는 볼륨 암호화를 사용할 수 있습니다. |
{: caption="표 3. 스토리지 비교" caption-side="top"}

## 보안 차별화 요소
{: #compare-security}

|  클래식 인프라   | VPC 인프라 |
| ---------- | ------------------------- |
|Vyatta, Fortigate, Juniper vSRX, VSI에 대한 보안 그룹| 보안 그룹, 네트워크 액세스 제어 목록(ACL)|
{: caption="표 4. 보안 비교" caption-side="top"}

## API 차별화 요소
{: #compare-apis}

|  클래식 인프라   | VPC 인프라 |
| ------------------------- | ------------------ |
|기존 SLAPI({{site.data.keyword.slapi_short}})| 개발자 친화적인 새로운 REST 기반 API |
{: caption="표 5. API 비교" caption-side="top"}

## 다음 단계
{: #compare-nextsteps}

당사의 모든 VPC 인프라 기능을 검토하려면 [가상 프라이빗 클라우드 정보](/docs/vpc-on-classic?topic=vpc-on-classic-about)를 참조하십시오. 인프라 전체를 탐색하려면 [인프라 빌드](/docs/overview?topic=overview-first-steps-it-ops)를 참조하십시오. 

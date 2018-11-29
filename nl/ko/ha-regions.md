---

copyright:

  years: 2018

lastupdated: "2018-11-15"

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:pre: .pre}
{:tip: .tip}

# 리소스 배치를 위한 위치 
{: #ov_intro_reg}

애플리케이션 관리를 위한 동일한 {{site.data.keyword.cloud_notm}} 인프라 및 요금 청구를 위한 동일한 사용량 세부사항을 사용하여 다른 위치에 앱 및 서비스 인스턴스를 작성할 수 있습니다. 애플리케이션 대기 시간을 낮추기 위해 고객과 가장 가까운 위치에 앱을 배치할 수 있습니다. 

보안 문제를 해결하기 위해 애플리케이션 데이터를 보관할 위치를 선택할 수도 있습니다. 앱을 둘 이상의 위치에서 빌드할 경우 이 중 한 위치가 사용 불가능하면 다른 위치에 있는 앱은 계속 실행됩니다. 허용되는 리소스 양은 사용하는 위치마다 동일합니다. 플랫폼 리소스 및 사용 가능한 위치에 대한 자세한 정보는 [서비스 가용성](/docs/resources/service_region.html)을 참조하십시오.

콘솔의 글로벌 로드 밸런싱은 사용자에게 가장 가까운 지리적 위치가 작동 중지 상태가 되면 콘솔이 다음으로 가까운 위치의 정보를 표시하도록 합니다. 이 방식을 사용하면 사용자가 필요한 정보에 액세스하기 위해 조치를 취할 필요 없이 항상 콘솔에 액세스할 수 있습니다.

기본적으로 대시보드에서 모든 위치에 걸쳐 모든 리소스를 볼 수 있습니다. 특정 위치에서 리소스를 보고 이에 대해 작업하려면 **위치** 메뉴를 펼친 다음 목록에서 위치를 선택하십시오. 

또한 명령행 인터페이스에서 `ibmcloud api` 명령을 사용하고 위치의 API 엔드포인트를 지정하여 작업할 {{site.data.keyword.cloud_notm}} 위치에 연결할 수 있습니다. 예를 들어, 다음 명령을 입력하여 {{site.data.keyword.cloud_notm}} 런던에 연결하십시오.

```
ibmcloud api https://api.eu-gb.bluemix.net
```

각 위치에 고유한 접두부가 지정됩니다. {{site.data.keyword.cloud_notm}}는 다음과 같은 위치 및 위치 접두부를 제공합니다.

| **위치** | **API 엔드포인트** |
|-----------------|-------------------|
| 댈러스 |api.ng.bluemix.net |
|시드니 |api.au-syd.bluemix.net |
| 프랑크푸르트 |api.eu-de.bluemix.net |
| 런던 |api.eu-gb.bluemix.net |
| 워싱턴 DC |api.us-east.bluemix.net |
| 도쿄 | api.jp-tok.bluemix.net |
{: caption="표 1. {{site.data.keyword.cloud_notm}} 위치 목록" caption-side="top"}

인프라 리소스를 배치하는 경우 컨텐츠가 있는 위치에 대한 더 많은 옵션이 주어집니다. 위치를 선택하거나 {{site.data.keyword.Bluemix_notm}}에서 데이터 센터 목록으로부터 선택할 수 있습니다. 자세한 정보는 [{{site.data.keyword.cloud_notm}} 데이터 센터](data-centers.html)를 참조하십시오.

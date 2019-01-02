---

copyright:
  years: 2017, 2018
lastupdated: "2018-10-11"

---

{:shortdesc: .shortdesc}

# 리소스 그룹의 리소스 구성
{: #whatis}

리소스 그룹은 한 번에 둘 이상의 리소스에 대한 사용자 액세스를 신속하게 지정할 수 있도록 사용자 정의할 수 있는 그룹에서 계정 [리소스](/docs/resources/acct_resources.html#resource)를 구성하기 위한 방법입니다. {{site.data.keyword.Bluemix}} Identity and Access Management(IAM) 액세스 제어를 사용하여 관리되는 계정 리소스는 계정 내의 리소스 그룹에 속합니다. 카탈로그에서 계정에 새 리소스를 추가하는 경우에는 리소스 그룹에 리소스를 지정할 수 있습니다. 유일한 예외는 Kubernetes입니다. Kubernetes는 리소스 그룹 지정에 대한 프롬프트를 표시하지 않지만 IAM 역할을 사용하여 서비스에 대한 액세스를 제어합니다.

{{site.data.keyword.Bluemix}} IAM을 사용하여 관리되며 리소스 그룹에 속하는 서비스에는 임의의 Cloud Foundry 영역에서 앱과 서비스에 연결하는 기능(이는 서로 다른 위치에서 앱과 서비스에 연결할 수 있도록 허용함)을 포함하여 여러 장점이 있습니다. 리소스 그룹이 위치별 범위가 아니므로, 서로 다른 지역의 앱과 서비스를 동일한 리소스 그룹으로 프로비저닝할 수 있습니다. 또한 리소스 그룹 내에서 개별 인스턴스까지 세분화된 액세스 제어를 사용하기 위한 기능도 있습니다.

리소스 그룹 관련 작업에 대한 자세한 정보는 [리소스 그룹 관리](/docs/resources/resourcegroups.html)를 참조하십시오. 리소스 그룹을 처음 사용하는 경우 [리소스 그룹의 리소스 구성 우수 사례](/docs/resources/bestpractice_rgs.html#bp_resourcegroups)를 확인하십시오.

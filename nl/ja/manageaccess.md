---

copyright:

  years: 2017, 2019

lastupdated: "2018-03-14"

keywords: users level of access, user control, access control, permissions

subcollection: overview

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}

# {{site.data.keyword.Bluemix_notm}} でのアクセス管理
{: #cloudaccess}

アクセス管理によって、どのユーザーがアカウント内のリソースを表示、作成、使用、および管理できるのかを制御することができます。 アクセスを認可するために、役割を割り当てることができます。役割は、プラットフォーム管理タスクの実行およびアカウント・リソースへのアクセスを行うためのアクセス・レベルをユーザーに許可します。
{: shortdesc}

{{site.data.keyword.Bluemix_notm}} でのアクセス管理の方法は、アクセス権限を割り当てたいリソースのタイプによって異なります。 {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) は、{{site.data.keyword.Bluemix_notm}} プラットフォーム全体でリソース・グループに編成されているリソースを一貫して管理するために使用されるアクセス管理システムです。 クラシック・インフラストラクチャーおよび Cloud Foundry のリソースは Cloud IAM を使用して管理されません。 これらのリソース・タイプには独自のアクセス管理システムがあります。 

複数のリソース・タイプを組み合わせて使用する場合は、各タイプを別々に管理します。 [クラシック・インフラストラクチャー・リソース ](/docs/iam/infrastructureaccess.html#infrapermission) へのアクセス権限を割り当てるには、アクセス権を割り当てるユーザーの「クラシック・インフラストラクチャー」タブの**「管理」** > **「アクセス (IAM)」**内で許可を設定します。 [Cloud Foundry リソース](/docs/iam/cfaccess.html#cfaccess)へのアクセス権限を割り当てるには、ユーザーを組織に割り当て、アクセス権限を割り当てるユーザーの「Cloud Foundry」タブの**「管理」** > **「アクセス (IAM)」**内で Cloud Foundry の組織およびスペースのアクセス役割を設定します。

## アクセス権限を管理するための権限
{: #perms-manageaccess}

アカウント所有者は、アカウント内のすべてのリソースへのアクセス権限を管理できます。 また、アカウント内のユーザーに、すべてのサービス、特定のサービス、またはそのユーザーに管理させるリソース・グループの管理者役割を割り当てることによって、プラットフォーム・リソースへのアクセスを管理するタスクを委任することもできます。

アカウント内に Cloud Foundry サービスがある場合、他のユーザーに組織またはスペースの管理者役割を割り当てることができます。そうすると、そのユーザーは、管理する組織またはスペース内のインスタンスにアクセスできるよう、ユーザーを追加して Cloud Foundry 役割を割り当てることができるようになります。


## 開始
{: #cloudaccess-getstarted}

**「管理」** &gt; **「アクセス (IAM)」**と進みます。次に、アカウント内のユーザーに関するアクセス管理を始めるため、**「ユーザー」** を選択します。 まず、リストからユーザーを選択します。 管理する許可のあるアクセス管理オプションのみが表示されます。 例えば、アカウント所有者でなく、組織またはスペースの管理者でもない場合、Cloud Foundry アクセスを管理するためのオプションは表示されません。

また、サービス ID を使用して、アプリおよびサービスにアクセス役割を割り当てることもできます。 **「サービス ID」**ページに移動して作業を始めます。 Cloud IAM を素早く稼働中にする方法について詳しくは、『[概説チュートリアル](/docs/iam/quickstart.html#getstarted)』を参照してください。

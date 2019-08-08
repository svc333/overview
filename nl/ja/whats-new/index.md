---

copyright:

  years: 2015, 2019

lastupdated: "2019-07-25"

keywords: release notes, what's new, what is new, cloud updates

subcollection: overview

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:tip: .tip}

# {{site.data.keyword.Bluemix_notm}} の新機能
{: #whatsnew}

{{site.data.keyword.Bluemix_notm}} の機能を最大限に活用するために、{{site.data.keyword.Bluemix}} プラットフォームで利用可能な新しいフィーチャーを常に最新の状態に保つようにしてください。
{:shortdesc}

{{site.data.keyword.Bluemix_notm}} で使用可能なサービスの更新に関する情報は、ブログの[{{site.data.keyword.Bluemix_notm}} 発表ページ](https://www.ibm.com/cloud/blog/announcements){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") を確認してください。
{: tip}



## {{site.data.keyword.Bluemix_notm}} プラットフォーム
{: #platform_category}

### 複数のアカウントを一元管理するための {{site.data.keyword.Bluemix_notm}} エンタープライズ
{: #ibm-cloud-enterprises}
最新情報: 2019 年 7 月 25 日

{{site.data.keyword.Bluemix_notm}} エンタープライズを作成することによって、複数のアカウントの請求処理および使用量を一元管理できるようになりました。エンタープライズでは、関連するアカウントをアカウント・グループに編成することで、多層のアカウント階層を作成できます。エンタープライズは、以下の主要な機能により、複数のアカウントの管理を単純化します。
   * 統合された請求処理は、すべてのアカウントの請求、請求書処理、および支払いを 1 つの場所 (エンタープライズ・アカウント)から管理できることを意味します。 
   * サブスクリプション・クレジットは、クレジット・プールに集約され、エンタープライズ内のすべてのアカウントで共有されます。クレジットが共有されるため、サブスクリプションのトラッキングが簡単になるだけでなく、より少ない数でより大きなサブスクリプションを、より良い割引で得ることができます。 
   * トップダウンの使用量レポートは、エンタープライズ階層に従って編成された、すべてのアカウントの使用コストの統一ビューを提供します。 

複数のアカウントがあり、そのうち少なくとも 1 つがサブスクリプション・アカウントであれば、エンタープライズを作成できます。詳しくは、『[エンタープライズとは](/docs/account?topic=account-enterprise)』および [{{site.data.keyword.Bluemix_notm}} エンタープライズの紹介 ](http://www.ibm.com/cloud/blog/announcements/Introducing-IBM-Cloud-Enterprises){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") を参照してください。

### サブスクリプション・クレジット消費量をトラッキングするための「サブスクリプション」ページ
{: #subscriptions-page}
最新情報: 2019 年 7 月 18 日

サブスクリプション・アカウントを使用している場合、「サブスクリプション」ページでご使用のサブスクリプションをすべて確認して、クレジット消費量を分析できるようになりました。 アカウントのサブスクリプション・クレジット合計の概略と、傾向を可視化する詳しいグラフ (クレジット・バーンダウンや月別消費量など) を確認できます。 さらに、アカウント内のプロモーションのクレジットを表示することもできます。 詳しくは、『[サブスクリプションの管理](/docs/billing-usage?topic=billing-usage-subscriptions)』を参照してください。

また、サブスクリプション・クレジットをアカウントに追加する際に適用するコードは、その使用法を適切に反映するためにフィーチャー・コードではなく、サブスクリプション・コードと呼ばれるようになりました。

### {{site.data.keyword.cloud_notm}} での SoftLayer SAML 連携の管理
{: #saml-federation}
最新情報: 2019 年 7 月 2 日

フェデレーテッド ID を使用したログインのために SAML ID プロバイダーをセットアップしていた、以前の SoftLayer ユーザーは、構成データを {{site.data.keyword.cloud_notm}} コンソールの「ID プロバイダー」ページの「アクセス (IAM)」で管理できるようになりました。 このタイプの連携は非推奨であるため、現時点では ID プロバイダーを新しくセットアップすることはできませんが、ID プロバイダーのデータを更新することは引き続き可能です。あるいは、[IBMid との統合](/docs/account?topic=account-signup#signup-federated)に切り替えることを選択して、この連携を削除することもできます。

### カスタム・ダッシュボード
{: #custom}
最新情報: 2019 年 6 月 14 日 

ダッシュボードに表示される内容を制御できるようになりました。 ダッシュボードのカスタマイズで、ウィジェットの追加、削除、並べ替えを行うことができます。 詳しくは、[ダッシュボードのカスタマイズ](/docs/overview?topic=overview-custom-dashboard)を参照してください。


### 関連タグを用いた使用量データのエクスポート
最新情報: 2019 年 4 月 4 日 

最新のタグ付け機能を使用して、エクスポートされた使用量レポートでリソース、使用量、コストを管理できるようになりました。 リソースにタグを追加する場合、リソースに関連付けられているタグを表示するオプションがあります。 **「管理」 **> **「請求および使用量」 **> **「使用量」 **> **「CSV のエクスポート」 **> **「インスタンス」**に移動して、使用量レポートをダウンロードします。 タグのエクスポートについて詳しくは、[Export tags within your usage data to help with cost allocation](https://www.ibm.com/cloud/blog/export-your-tagged-usage-data-within-the-enhanced-ibm-cloud){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") というブログ投稿を確認してください。

### リソースへのパブリック・アクセスを可能にするアクセス・グループ
最新情報: 2019 年 3 月 25 日

アカウントに提供されている新しいアクセス・グループを使用することで、{{site.data.keyword.cos_full}} バケット内のオブジェクトへのパブリック・アクセスを有効にできるようになりました。 この新しいアクセス・グループは`「パブリック・アクセス」`グループと呼ばれ、デフォルトですべてのユーザー ID とサービス ID がこのグループに追加されています。 アクセス・グループのポリシーを更新すれば、ポリシーで指定したリソースへのアクセス権限を、認証されていないユーザーも含めてすべてのユーザーに付与できます。 [『パブリック・アクセス・グループの詳細 (Learn more about the public access group)』](/docs/iam?topic=iam-public#public)を参照してください。

### フェデレーテッド ID を持つユーザーの多要素認証
最新情報: 2019 年 3 月 12 日
{: #mfa-federated}

課金アカウント管理サービスの管理者役割を割り当てられたアカウント所有者またはユーザーは、アカウント内のすべてのユーザーに対して多要素認証 (MFA) を有効にすることができます。 企業またはエンタープライズのシングル・サインオン ID を使用するフェデレーテッド・ユーザーは、MFA を使用して {{site.data.keyword.Bluemix_notm}} にログインすることによって認証を受けることができるようになりました。 このフィーチャーの強化と、アカウントの MFA を有効にするために必要な情報の詳細については、[Introducing MFA for IBM Cloud Users with Federated ID (フェデレーテッド ID を持つ IBM Cloud ユーザーの MFA の概要)](https://www.ibm.com/cloud/blog/introducing-mfa-for-ibm-cloud-users-with-federated-id){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") を参照してください。

### 新しい appdomain.cloud ホスト名オプション
最新情報: 2018 年 12 月 31 日
{: #appdomain}

新しいホスト名オプション `*.appdomain.cloud` が cloud.ibm.com で使用可能です。

以前は、`mybluemix.net` ドメインが {{site.data.keyword.containerlong_notm}} や Cloud Foundry などのさまざまなデプロイメント・ターゲットでアプリをホストするために使用されていました。 `mybluemix.net` でホストしているアプリは影響を受けません。

Cloud Foundry アプリのサブドメインは `cf.appdomain.cloud` です。 {{site.data.keyword.containerlong_notm}} にデプロイするアプリのサブドメインは `containers.appdomain.cloud` です。

### 新しい Cloud Foundry API エンドポイント
最新情報: 2018 年 11 月 30 日
{: #cf-api-endpoints}

既存の `api.*.bluemix.net` Cloud Foundry API エンドポイントは、後方互換性のために引き続き使用できます。 ただし、使用している地域の以下の新しい Cloud Foundry API エンドポイントを使用するために、スクリプトとインフラストラクチャー自動化を更新できます。

* api.us-south.cf.cloud.ibm.com (以前は api.ng.bluemix.net)
* api.eu-gb.cf.cloud.ibm.com (以前は api.eu-gb.bluemix.net)
* api.us-east.cf.cloud.ibm.com (以前は api.us-east.bluemix.net)
* api.eu-de.cf.cloud.ibm.com (以前は api.eu-de.bluemix.net)
* api.au-syd.cf.cloud.ibm.com (以前は api.au-syd.bluemix.net)

### {{site.data.keyword.Bluemix_notm}} の新しいサポート・エクスペリエンス
最新情報: 2018 年 11 月 30 日 
{: #support}

サポート・センターを使用して、{{site.data.keyword.Bluemix_notm}} に関連したすべての問題の解決に取り組むことができます。 ランディング・ページには FAQ が用意されており、{{site.data.keyword.Bluemix_notm}} に連絡しなくても質問の答えを見つけることができます。 また、ライブ・サポート担当員とチャットすることもできます。 お客様の Case を単一の場所から管理できるようになりました。 **「サポート」** &gt; **「Case の管理」**に移動して、Case を作成、表示、または編集します。

また、サポート・センターから[「状況」ページ ](https://cloud.ibm.com/status){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・リンク")を参照することもできます。 このページは、{{site.data.keyword.Bluemix_notm}} のプラットフォーム、インフラストラクチャー、および主要サービスに影響を与える重要なイベントに関する計画外のインシデント、計画保守、告知、およびセキュリティー情報の通知をすべて組み込むように拡張されました。 サポート・センターから**「クラウドの状況の表示」**をクリックします。 この新しいエクスペリエンスを確認するには、ログインして[サポート・センター](https://cloud.ibm.com/unifiedsupport/supportcenter){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") にアクセスしてください。 

### {{site.data.keyword.Bluemix_notm}} での統合ログイン、API キー、およびユーザーとアクセスの管理
最新情報: 2018 年 11 月 30 日
{: #useraccess}

最新の更新により、ID タイプに関係なくすべてのユーザーが使用できる簡易セキュア・ログインを利用できるようになりました。 IBMid と SoftLayer ID のどちらを使用している場合でも、拡張ログイン・ページから {{site.data.keyword.Bluemix_notm}} コンソールに素早くログインできます。 また、{{site.data.keyword.Bluemix_notm}} 全体でセキュアな API 呼び出しを行い、IAM API キーまたは IAM アクセス・トークンを使用して CLI ログインを自動化することもできます。 

ログインすると、「アクセス (IAM)」UI の「ユーザー」ページに、プラットフォームおよびクラシック・インフラストラクチャーのユーザーを含むすべてのユーザーが表示されます。 アカウント内の他のユーザーを表示するためのアクセス権限に応じて、アカウント・ユーザー、クラシック・インフラストラクチャーのユーザー、または Cloud Foundry 組織によってビューを素早くフィルターに掛けることができます。また、フィルターを使用して、名前、E メール、または状況で素早くユーザーを検索することもできます。

すべてのユーザーが単一のコンソールに表示されるようになったので、同じ場所からすべてのタイプのリソースへのアクセスを管理できます。 アクセスはユーザーから開始されるため、最初にリストからユーザーを選択します。 次に、アクセス権を割り当てるリソースのタイプに応じて、IAM アクセス・ポリシー、Cloud Foundry アクセス権限、またはクラシック・インフラストラクチャーの許可から選択できます。 IAM アクセス・ポリシーを割り当てるだけの場合は、アクセス・グループを作成して、同じポリシーを割り当てる必要があるすべてのユーザーを同じアクセス・グループに追加することで、アクセス管理プロセスの簡素化を試行してください。

詳細情報については、[Outstanding User Access Improvements Help Deliver a Unified {{site.data.keyword.Bluemix_notm}} Platform](https://www.ibm.com/cloud/blog/announcements/ibm-cloud-access-management){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") を確認してください。 

### すべての {{site.data.keyword.Bluemix_notm}} CLI プラグイン資料を 1 カ所で見つける
最新情報: 2018 年 11 月 30 日
{: #cli}

{{site.data.keyword.Bluemix_notm}} CLI プラグインのすべての資料に 1 カ所でアクセスできるようになり、{{site.data.keyword.Bluemix_notm}} プラットフォームで探している CLI コマンドを見つけやすくなりました。 [CLI 資料](/docs/cli?topic=cloud-cli-ibmcloud-cli)の『リファレンス』セクションを確認してください。

### 新しいダッシュボードとリソース・リストを確認する
最新情報: 2018 年 11 月 30 日
{: #dash}

最新の更新により、すべてのプラットフォームおよびインフラストラクチャーのサービスを 1 つの場所から表示できるようになりました。 ログインすると、新しいダッシュボードをすぐに確認できます。 カタログからアカウントにリソースを追加すると、リソース・リストを使用してアカウント・リソースの全体を表示できます。

* ダッシュボードが再設計され、リソース、保守、状況、アプリケーション、サポート、使用状況、およびユーザーの要約を表示できるようになりました。
* リソース・リストでリソースのより詳細な情報を確認できるようになりました。 リソースにタグを付けて編成したり、リソースを選択して詳細ページで変更を加えたりすることができます。
* すべてのリソースを 1 つの場所に表示できるようになったので、作成したリソースを素早く見つけてそれらを「リソース・リスト」ページに表示できるように、グローバル検索を追加しました。 
* カタログ結果を検索して、アカウントに追加するリソースを素早く見つけることもできます。  

詳しくは、[Manage All Your Cloud Resources on the Enhanced {{site.data.keyword.Bluemix_notm}} Platform](https://www.ibm.com/blogs/cloud-archive/2018/11/manage-all-your-cloud-resources-on-the-enhanced-ibm-cloud-platform/){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") を参照してください。

### プラットフォームおよびインフラストラクチャーのサービスの統合アカウント、請求、およびユーザー・プロファイルの情報
最新情報: 2018 年 11 月 30 日
{: #profile}

アカウント、請求、およびプロファイルの情報が簡素化されました。 統合されたコンソールで、すべてのプラットフォームおよびインフラストラクチャーのリソースのアカウント情報を表示できます。 

* プロファイルと設定には、お客様に関する情報と、すべてのリソース・タイプの E メール通知設定が含まれています。 
* アカウント情報には、会社または組織に関する情報、アカウント設定、およびリソース・グループや Cloud Foundry 組織と連携するためのクイック・アクセスが含まれています。 素早く利用を開始するのに役立つベスト・プラクティスを見つけることもできます。
* アカウントの「請求および使用量」では、請求内容の確認、支払いの実行、サブスクリプションのモニター、見積もりの取得、注文の追跡、および消費量通知の設定を実行できます。

詳しくは、[Bringing It All Together: A Single Account and Billing Management Experience](https://www.ibm.com/cloud/blog/announcements/ibm-cloud-account-management){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") を参照してください。

### タグによるリソースの編成
最新情報: 2018 年 11 月 30 日
{: #tag}

タグをクラウド・オブジェクト・ストレージなどのリソースに追加できるようになりました。これにより、リソースを管理し、最も関連性の高いリソースを見つけることができます。 例えば、数百のリソースがあり、同じ方法で支払われるいくつかのリソースを区別する場合は、`costcenter:location01` でタグ付けできます。 または、いくつかのリソースに対する作業を繰り返し行っているチームがある場合は、「team-blue」などを使用できます。 タグによってリソース・リストをフィルタリングし、必要なリソースを素早く編成して見つけることもできます。 詳しくは、『[タグの処理](/docs/resources?topic=resources-tag)』および [Platform Tagging on the Enhanced {{site.data.keyword.Bluemix_notm}} Platform](https://www.ibm.com/cloud/blog/announcements/platform-tagging-on-the-enhanced-ibm-cloud-platform){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") を参照してください。 

### コスト見積もりツールを使用した正確な月次コストの検出
最新情報: 2018 年 11 月 30 日
{: #cost-estimator}

購入するサービスを決定して分析するために、コスト見積もりツールを使用できます。 これで、コンソールを使用して、必要な各サービスを選択し、使いやすいツールですべてのコストを追加できます。 また、予想されるデータ使用量、1 秒当たりのルックアップ数、1 秒当たりの書き込み数、および 1 秒当たりの照会数を入力して、月次支出をより正確に見積もることもできます。 選択した各カタログ・サービスでコスト見積もりツールを使用することも、コンソール・メニューの「コスト見積もりツール」アイコン ![「見積もりツール」アイコン](../../icons/Estimator.svg) をクリックして見積もりコストの要約を取得することもできます。 詳しくは、[コストの見積もり](/docs/billing-usage?topic=billing-usage-cost)を参照してください。

### {{site.data.keyword.cloud_notm}} のグローバル・ロケーション名の更新
最新情報: 2018 年 11 月 1 日
{: #location-name-updates}

{{site.data.keyword.cloud_notm}} のグローバルな使用可能地域が継続的に拡張されていることに伴って、世界中の地理、地域、およびデータ・センターから成る、理解しやすく一貫性のある階層をサポート強化するために、ロケーション命名構造が更新されることになりました。 現在のグローバル地域に慣れているユーザーは「米国南部」や「シドニー」といった名前で識別できますが、これらのロケーション名は、データ・センターが物理的に存在している都市の名前に変わります。

現時点では、プログラマチック ID は変更されないため、 API の観点からは影響はありません。 以下の表に、古いロケーション名と新しいロケーション名を示します。 データ・センターおよび地域の詳細および包括的リストについては、『[サービスの使用可能地域](/docs/resources?topic=resources-services_region)』を参照してください。

| 前のロケーション表示名 | 新しいロケーション表示名 | コード |
|----------|---------|---------|
| 米国南部 | ダラス | us-south | 
| 米国東部 | ワシントン DC | us-east |
| 英国 | ロンドン | eu-gb |
| ドイツ | フランクフルト | eu-de |
| シドニー | シドニー | au-syd |
| アジア太平洋北部 | 東京 | jp-tok |
{: caption="表 1. 新しいロケーション名" caption-side="top"}

### 他のユーザーへのアカウント管理アクセス権限の割り当て
最新情報: 2018 年 10 月 30 日
{: #acct-mgmt-services}

{{site.data.keyword.cloud_notm}} ID およびアクセス管理 (IAM) を使用して、アカウント管理者として実行する一般的な作業をアカウント内の別のユーザーに委任できます。 使用可能なアカウント管理サービスの 1 つまたはすべてでアクセス・ポリシーを作成することによって、ユーザーの招待と削除、アクセス・グループの管理、サービス ID の管理、プライベート・カタログ・サービスの保守、請求のモニターと使用量の追跡などの作業を簡単に委任できます。 以下のように、4 つの個別アカウント管理サービス・オプションと、すべてのサービスという 1 つのオプションがあり、これらをアクセス・ポリシーのセットアップに使用できます。

* ユーザーの招待と削除のためのユーザー管理
* アクセス権限の作成、編集、削除、更新、および割り当てのための IAM アクセス・グループ 
* アカウント全体のサービス ID および関連付けられた API キーへのアクセス権限の表示、作成、削除、および割り当てのための IAM Identity サービス
* プライベート・カタログ・オファリングの表示、およびオファリングのメタデータおよび可視性の更新のためのグローバル・リソース・カタログ
* 割り当てられた役割に基づいた個別アカウント管理サービス・オプションのそれぞれへのアクセス権限のため、および請求および使用量追跡へのアクセス権限のためのすべてのアカウント管理サービス

どのアカウント管理サービスについてのポリシーを持っているのか、およびどの役割が割り当てられているのかに応じてユーザーが実行できるタスクについて詳しくは、『[プラットフォーム管理の役割とアカウント管理サービスに対するアクションの例](/docs/iam?topic=iam-userroles#platformrolestable2)』を参照してください。 この新機能について詳しくは、[Introducing More Flexibility and Control for IBM Cloud Account Management Services Access](https://www.ibm.com/cloud/blog/announcements/introducing-more-flexibility-and-control-for-ibm-cloud-account-management-services-access){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") ブログ投稿を参照してください。 

### リソースの検索
最新情報: 2018 年 7 月 17 日
{: #forward-slash-key}

{{site.data.keyword.cloud_notm}} コンソール内の任意の場所からリソースを検索できます。 コンソールのメニュー・バーで検索フィールドにリソースの名前を入力します。 スラッシュ・キー (/) を押して、検索を有効にします。

### フェデレーテッド・ユーザーをアクセス・グループに動的に追加
最新情報: 2018 年 7 月 12 日
{: #add-fed-users}

動的ルールを作成して、特定の ID 属性に基づいてフェデレーテッド・ユーザーをアクセス・グループに自動的に追加することができます。 ユーザーがフェデレーテッド ID を使用してログインすると、ID プロバイダーからのデータは、設定されたルールに基づいてユーザーをアクセス・グループに動的にマップします。 詳しくは、『[アクセス・グループの動的ルールの作成 (Creating dynamic rules for access groups)](/docs/iam?topic=iam-rules)』を参照してください。

### サービス ID および API キーの保護
最新情報: 2018 年 6 月 1 日
{: #protect-svcid-apikey}

サービス ID または API キーの削除が原因で停止または破壊が発生する状態を回避できるように、UI または CLI を使用してサービス ID および API キーをロックできます。 サービス ID をロックすることにより、アクセス・ポリシーの変更、削除、割り当てを防止することもでき、さらに、サービス ID と関連付けられた API キーの作成または削除を防止することもできます。 詳しくは、『[サービス ID のロック](/docs/iam?topic=iam-serviceidapikeys#lockkey)』および『[API キーのロック](/docs/iam?topic=iam-userapikey)』を参照してください。

### ライト・アカウントからサブスクリプション・アカウントへのアップグレード
最新情報: 2018 年 5 月 31 日
{: #upgrade-lite}

{{site.data.keyword.Bluemix_notm}} コンソールから直接、ライト・アカウントをサブスクリプション・アカウントにアップグレードできるようになりました。 サブスクリプション・アカウントを使用すると、プラットフォームとインフラストラクチャーの両方のオファリングを使用でき、月次支出額および期間を確約することによって割引価格を利用できます。 また、月次支払いスケジュールに基づく固定された請求処理によって予期しない請求を回避できる一方、ニーズに合わせて注文量を増減できる柔軟性もあります。 詳しくは、『[サブスクリプション・アカウントについての FAQ](/docs/billing-usage?topic=billing-usage-billusagefaqs#subs-order)』を参照してください。 

### {{site.data.keyword.Bluemix_notm}} CLI リブランディング
最新情報: 2018 年 5 月 15 日
{: #cli-rebrand}

{{site.data.keyword.Bluemix_notm}} CLI コマンドは **`bluemix`** および **`bx`** から **`ibmcloud`** に変更されました。 ただし、後に削除されるまで、**`bluemix`** および **`bx`** の CLI コマンドを引き続き使用できます。 現在、短縮名はなく、フルネーム **`ibmcloud`** のみです。 

### {{site.data.keyword.Bluemix_notm}} アカウントでの多要素認証
最新情報: 2018 年 5 月 2 日
{: #account-mfa}

多要素認証 (MFA) ではアカウントにセキュリティーの層が 1 つ追加されて、すべてのユーザーが、ログイン中に標準 IBMid およびパスワードに加えて、時間ベースのワンタイム・パスコードも入力することが必要になります。 これは、一般的に 2 要素認証 (2FA) とも呼ばれています。 MFA はアカウント単位で有効にされ、いったんオンにされると、そのアカウント内のすべてのユーザーは、追加セキュリティー手段を使用してログインすることが必要になります。 詳しくは、[IBM Cloud Platform now adds support for Multi-Factor Authentication](https://www.ibm.com/cloud/blog/ibm-cloud-platform-now-adds-support-multi-factor-authentication){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") ブログ投稿を参照してください。

### アクセス・グループを使用した迅速なアクセス権限の割り当て
最新情報: 2018 年 4 月 3 日
{: #access-groups}

可能な限り最小限のポリシーを使用してアクセス権限を素早く割り当てたい場合、 アクセス・グループを使用して行うことができるようになりました。 アクセス・グループを使用すると、ユーザーとサービス ID のセットをグループ化して、グループのすべてのメンバーに適用される単一のポリシーを割り当てることができます。 アクセス・グループを使用することで、アカウント内のユーザーとサービス ID へのアクセス権限の管理に費やす時間を抑えることができます。 詳しくは、「[New feature: Access groups](https://www.ibm.com/cloud/blog/access-groups){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン")」のブログ投稿を確認してください。

### {{site.data.keyword.Bluemix_notm}} Foundry Service 米国東部地域が使用可能になりました。
最新情報: 2017 年 12 月 15 日
{: #cf-useast}

ワシントン D.C. で新しい米国東部データ・センターが使用可能になりました。 この新規の地域には、`us-east.cloud.ibm.com` エンドポイント使用して到達できます。 この新規の地域で購入可能なサービスについて詳しくは、『[地域別のサービス](/docs/resources?topic=resources-services_region)』を参照してください。

### EU 内のリソースに関するサポート
最新情報: 2017 年 12 月 14 日
{: #eu-resources}

サービスおよびデータ・センターがヨーロッパ内にある場合、{{site.data.keyword.Bluemix_notm}} では、EU 内のデータを保護するための追加的な機能を提供するようになりました。 ヨーロッパにあるカスタマー・サクセス・チームによるサポートを依頼することができます。 このサポートは、24 時間 365 日利用可能です。 詳しくは、『[EU サポート対象オプションの有効化](/docs/account?topic=account-eu-hipaa-supported#bill_eusupported)』および『[EU 内のリソースに関するサポートの依頼](/docs/get-support?topic=get-support-getting-customer-support#eusupported)』を参照してください。

### TLS 1.0 および 1.1 のサポート終了
最新情報: 2017 年 11 月 28 日
{: #nosupport-tls}

{{site.data.keyword.Bluemix_notm}} は、2018 年 3 月 1 日付けで弊社のクラウド製品ならびにサービスの多くで TLS 1.0 および TLS 1.1 のサポートを終了します。これは、徹底してセキュアなクラウドを提供するための IBM の取り組みの一貫であり、セキュリティーおよびデータ・プライバシーに関する業界のベスト・プラクティスと歩調を合わせるためでもあります。 

### アカウント内でリソースを編成する新しい方法
最新情報: 2017 年 11 月 16 日
{: #usergs}

リソース・グループは、アカウント・リソースのカスタマイズ可能なグループを作成するための新しい方法です。グループとその内部のリソースへのアクセスは、Identity and Access Management (IAM) を使用して管理されます。 すべてのユーザーがデフォルトのリソース・グループから作業を始めます。 このリソース・グループの名前を変更した上で、新規サービス・インスタンスをカタログから作成したときに、そのインスタンスをリソース・グループに追加できます。

従量課金 (PAYG) またはサブスクリプションのアカウントを持つユーザーの場合、追加のリソース・グループを作成して、 割り当て量の管理とリソース・セットの課金使用量の表示をさらに簡単に行うことができます。 また、リソースをグループにまとめて、複数サービスへのアクセス権限を一度に簡単にユーザーに割り当てられるようにすることも可能です。 自分のアカウント用のリソース・グループの処理について詳しくは、『[リソース・グループの管理](/docs/resources?topic=resources-rgs)』を参照してください。

### {{site.data.keyword.Bluemix_notm}} IAM の更新
最新情報: 2017 年 11 月 16 日
{: #iam-nov17}

自分の {{site.data.keyword.Bluemix_notm}} アカウント内にリソース・グループを導入することで、アクセス権限を割り当てるための新しい方法を利用できるようになりました。 複数のユーザーおよびサービス ID にリソース・グループ内のすべてのサービスへのアクセス権を割り当てることができるため、複数リソースへのアクセス権限を一度に素早く割り当てることができます。 リソース・グループ内の一部のサービスのみへのアクセス権限を割り当てることによって、ユーザーまたはサービス ID ごとにアクセス権限をカスタマイズすることもできます。あるいは、サービス・インスタンス・レベルで個別のリソースへのアクセス権限を割り当てることを選択します。 IAM を使用して活用できる機能について詳しくは、『[Cloud IAM の機能にはどのようなものがありますか?](/docs/iam?topic=iam-iamoverview#features)』を参照してください。

### ダッシュボード・ビューのカスタマイズ
最新情報: 2017 年 11 月 16 日
{: #custom-dash}

アカウント内のすべてのリソースを {{site.data.keyword.Bluemix_notm}} コンソール内のダッシュボードから表示および管理できます。 また、フィルターを設定してビューをカスタマイズできるようになりました。 例えば、リソース・グループを基準にフィルター操作して、リソース・グループ内の特定のリソースを表示できます。 地域または Cloud Foundry スペースを基準にフィルター操作することもできます。 詳しくは、『[ダッシュボードでのリソースの管理](/docs/overview?topic=overview-ui#dashboardview)』を参照してください。

### サポート・センター
最新情報: 2017 年 11 月 2 日
{: #support-nov17}

情報を検索したり、開発者コミュニティーに質問を投稿したり、チケットを管理したりすることができる新しいサポート・センターができました。 {{site.data.keyword.Bluemix_notm}} コンソールのメニュー・バーで**「サポート」>「サポート・センター」**にアクセスしてください。

### IBM Cloud の導入
最新情報: 2017 年 10 月 31 日
{: #meet-ibmcloud}

Bluemix は IBM Cloud になりました。 新しい名前の発表のみで、変更はありません。 これまでのようにアプリとサービスを容易にビルドして実行できます。 詳しくは、[IBM Cloud ブログ](https://www.ibm.com/cloud/blog/announcements/bluemix-is-now-ibm-cloud){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") を確認してください。

### ライト・アカウント
最新情報: 2017 年 10 月 31 日
{: #new-liteacct}

ライト・アカウントは、選択されたサービスを時間制限なく無料で試用するアクセス権限を付与する新しいアカウント・タイプです。 この新規アカウントには、使用量の追跡と効率的な利用のための機能が含まれ、リソースを管理しやすくしています。 使用可能な機能について詳しくは、『[アカウント・タイプ](/docs/account?topic=account-accounts#liteaccount)』を参照してください。

### Identity and Access Management アプリケーション認証機能
最新情報: 2017 年 10 月 6 日
{: #app-authfeature}

Identity and Access Management (IAM) では、サービス ID を作成する機能を提供するようになりました。サービス ID は、アプリが {{site.data.keyword.Bluemix_notm}} サービスでの認証に使用できる ID と考えることができます。 個人ユーザーの資格情報を使用する代わりに、関連付けられた API キーとアクセス許可を持つサービス ID を作成できます。API キーとアクセス許可は、その ID によって認証を行う任意のアプリケーションのアクセスのレベルを制御するためにサービス ID に割り当てられたサービス・ポリシーの形式となっています。

この機能のメリットと、使用を開始する方法について詳しくは、[Introducing IBM Cloud IAM Service IDs and API Keys](https://www.ibm.com/cloud/blog/introducing-ibm-cloud-iam-service-ids-api-keys){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") を参照してください。

### {{site.data.keyword.Bluemix_notm}} グローバル・カタログ
最新情報: 2017 年 7 月 27 日
{: #gc}

{{site.data.keyword.Bluemix_notm}} は、コンソールの前回の更新でコンソール内の単一のロケーションからパブリック地域を管理するように拡張され、カタログから選択するアイテムの選択とデプロイのプロセスをさらに合理化するグローバル・カタログを含むようになりました。 コンソールで選択した地域にかかわらず、すべてのパブリック地域にわたって使用可能なすべてのサービスをカタログから表示できるようになりました。 カタログからタイルを選択すると、サービスを使用可能な地域を確認し、それをデプロイする場所を選択することができます。 カタログに対する最新の更新について詳しくは、[A global {{site.data.keyword.Bluemix_notm}} catalog makes building things easier](https://www.ibm.com/cloud/blog/announcements/global-bluemix-catalog-makes-building-things-easier){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") を参照してください。

### {{site.data.keyword.Bluemix_notm}} コンソールの更新
最新情報: 2017 年 5 月 23 日
{: #console-may17}

更新された {{site.data.keyword.Bluemix_notm}} コンソールを通じて単一のロケーションからパブリック地域を管理できるようになりました。 地域セレクターにより、合理化された手順でリソースにアクセスでき、他にも可用性の向上やパフォーマンスの改善などの機能強化が加えられています。 詳しくは、[New Global Bluemix UI for Higher Availability and More](https://www.ibm.com/blogs/bluemix/2017/05/new-global-bluemix-ui-higher-availability/){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") を確認してください。

### ID およびアクセス管理
最新情報: 2017 年 5 月 1 日
{: #iam-may17}

最新の更新および改善により、{{site.data.keyword.Bluemix_notm}} アカウント所有者または管理者は、新しい統一アクセス制御 UI を使用して、以下の機能を活用できるようになりました。
 * ユーザーが新しいアクセス制御機能を採用したときに、Kubernetes サービスやその他のサービスへのユーザーの微細化されたアクセス権限を管理する。
 * 組織内のユーザーにサービス・ポリシーおよび Cloud Foundry 役割を割り当てる。

さらに、{{site.data.keyword.Bluemix_notm}} プラットフォームのユーザーは、自分のユーザー ID に関連付けられた API キーを作成、削除、およびリストすることができます。 また、プラットフォーム・ユーザーは API または CLI を使用するときにそれらの API キーを使用して認証できます。

最後に、統一されたユーザー管理機能を拡張して、リンクされた IaaS-PaaS アカウントでユーザーが統一された方法で管理されるようにしており、SoftLayer カスタマー・ポータルまたは {{site.data.keyword.Bluemix_notm}} コンソールで別個にユーザーを追加する必要がありません。

詳しくは、[Introducing Identity & Access Management](https://www.ibm.com/blogs/bluemix/2017/05/introducing-identity-access-management/){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") というブログ投稿を確認してください。

### {{site.data.keyword.Bluemix_notm}} 資料のナビゲーション設計の変更
最新情報: 2017 年 4 月 13 日
{: #docnavupdates}

このナビゲーションの更新によって、資料全体でコンテンツがどのように編成されているかを理解し、関連コンテンツをより効率的に見つけることができるようになります。 コンテンツのネストされたレイヤーの数が減り、{{site.data.keyword.Bluemix_notm}} を活用するために必要な資料を見つけるために探し回る必要はなくなります。



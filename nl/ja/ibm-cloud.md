---


copyright:
  years: 2016, 2018
lastupdated: "2018-06-14"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# プラットフォーム概要
{: #overview}

{{site.data.keyword.IBM_notm}} の革新的なクラウド・コンピューティング・プラットフォームは、Platform as a Service (PaaS) と Infrastructure as a Service (IaaS) を組み合わせたものであり、ビジネス・アプリケーションを作成するために PaaS および IaaS と統合できる、クラウド・サービスのカタログを備えています。
{:shortdesc}

これから規模を拡大する予定の中小企業であっても、さらに分離を必要とする大企業であっても、{{site.data.keyword.cloud_notm}} (旧称 Bluemix) にはニーズに合うデプロイメントが揃っています。 お客様は境界のないクラウド内で開発を行うことができ、このクラウドで、{{site.data.keyword.IBM_notm}} が提供するパブリック {{site.data.keyword.cloud_notm}} サービスにお客様の専用サービスを接続することができます。 お客様およびお客様のチームは、{{site.data.keyword.cloud_notm}} でアプリ、サービス、およびインフラストラクチャーにアクセスし、既存のデータ、システム、プロセス、PaaS ツール、および IaaS ツールを使用できます。 開発者は、使用可能なサービスおよびランタイム・フレームワークの急成長しているエコシステムを利用して、他言語プログラミング・アプローチによってアプリケーションを作成できます。

{{site.data.keyword.cloud_notm}} を使用すれば、新規のアプリのテストや実行のためにハードウェアに多額の投資を行う必要がなくなります。 代わりに、IBM がすべてを管理し、使用した分だけ課金されるようになります。 {{site.data.keyword.cloud_notm}} は、パブリック、[専用](/docs/dedicated/index.html)、および[ローカル](/docs/local/index.html)の統合デプロイメント・モデルを提供しています。

アイデアを方向付けから、開発サンドボックス、そしてグローバル分散実稼働環境に移行させることができます。グローバル分散実稼働環境では、計算およびストレージ・インフラストラクチャー、オープン・ソース・プラットフォームのサービスとコンテナー、{{site.data.keyword.IBM_notm}}、Watson などからのソフトウェア・サービスとツールを備えることができます。 {{site.data.keyword.cloud}} は、プラットフォーム自体の能力を超えて、柔軟なデプロイメントも提供します。 {{site.data.keyword.cloud}} リソースをオンプレミス、専用プライベート・クラウド環境、またはパブリック・クラウドでプロビジョンします。

パブリック環境および専用環境にデプロイされたすべての {{site.data.keyword.IBM_notm}} クラウド・リソースは、世界中にある {{site.data.keyword.CloudDataCent}} ロケーションからお客様が選択した場所でホストされます。 {{site.data.keyword.CloudDataCents_notm}} は、地域的冗長性、すべてのデータ・センターおよび PoP を接続するグローバル・ネットワーク・バックボーン、および厳格なセキュリティー管理とレポート作成を備えています。 {{site.data.keyword.CloudDataCents_notm}}を使用することで、
{{site.data.keyword.IBM_notm}} は、最も要求の高い拡張、セキュリティー、コンプライアンス、およびデータ常駐のニーズを満たすことができます。

{{site.data.keyword.IBM_notm}} では、以下を可能にします。

* 世界中にあるセキュアな {{site.data.keyword.CloudDataCents_notm}}にハイパフォーマンスの計算およびストレージ・インフラストラクチャーをデプロイする。
* {{site.data.keyword.IBM_notm}}、オープン・ソース・コミュニティー、およびサード・パーティー開発者からの広範囲に及ぶクラウド・サービスと機能をテストして採用する。
* プライベート・ネットワークおよび API 機能を使用して、単一の拡張が容易なクラウド・プラットフォームから、ご使用のすべてのレガシー・システムおよびアプリに接続する。
* ビジネスのニーズやワークロード要求の変化に応じて、リソースをリアルタイムで拡張および縮小する。

## アプリ
{: #bluemixoverviewapplications}

ダッシュボードは、アプリを稼働させるため、およびアプリを実行中に管理するために必要なすべてのものを備えています。 {{site.data.keyword.cloud_notm}} では、以下のようなさまざまなボイラープレートおよびランタイムが用意されています。

* ボイラープレートは、アプリケーションとその関連するランタイム環境、および特定のドメインの事前定義サービスのためのテンプレートです。
* ランタイムは、アプリを実行するために使用されるリソース・セットであり、さまざまなタイプのアプリのコンテナーとして提供されます。

{{site.data.keyword.cloud_notm}} では、アプリを実行するための方法として、例えば Cloud Foundry や {{site.data.keyword.containerlong}} など、さまざまな方法が用意されています。 {{site.data.keyword.containerlong}} は、{{site.data.keyword.cloud_notm}} 上のホストされたクラウド環境で Docker コンテナーを実行するために使用します。

イベント・ドリブンの分散コンピューティングのために、{{site.data.keyword.openwhisk}} を使用できます。 {{site.data.keyword.openwhisk_short}} は、イベントに応えて、または、Web アプリやモバイル・アプリからの HTTP を介した直接起動に応えて、アプリケーション・ロジックを実行します。

{{site.data.keyword.cloud_notm}} Mobile サービスを使用して、事前に作成され、管理された、拡張が容易なクラウド・サービスをご使用のモバイル・アプリに取り込むことができます。

## サービス
{: #bluemixoverviewservices}

ダッシュボードでは、{{site.data.keyword.IBM}} およびサード・パーティー・プロバイダーから使用可能な {{site.data.keyword.cloud_notm}} サービスにアクセスできます。 これには、Watson、IoT、Analytics、Mobile、DevOps の各サービスがあります。

* {{site.data.keyword.IBM_notm}} DevOps サービスおよび IBM Cloud Garage Method を使用して適切な機能のみを備えることで、革新的な新規アプリケーションをより迅速かつ低コストで提供します。 DevOps のプラクティスを取り入れてイノベーションとアジリティーの文化を作り出すと、反復プラクティスを使用し、市場に対応して方向転換することができます。
* ブロックチェーンは、ビジネス・プロセスを簡素化しながら、信頼、アカウンタビリティー、および透明性を確立する新しい世代のトランザクション・アプリケーション用のピアツーピアの分散レジャー・テクノロジーです。  
* Watson は、音声、視覚、データの各 API の完全なスイートを備えたコグニティブ・コンピューティングの力をアプリに提供します。  Watson サービスを使用したコグニティブ・プラットフォームをデプロイすることで、最も複雑なビジネスの問題を解決できます。
* {{site.data.keyword.IBM_notm}} により、豊富な機能を持ち、統合されたクラウド・データベースおよびデータと分析サービスを使用して、より多くのことを実行できます。
* {{site.data.keyword.IBM_notm}} の IoT サービスにより、アプリは、接続されたデバイス、センサー、およびゲートウェイと通信し、それらが収集したデータを取り込むことができます。 レシピを利用すると、簡単にデバイスを IoT クラウドに接続できます。 その後、アプリでリアルタイム API および REST API を使用してデバイスと通信し、収集対象として設定したデータを取り込むことができます。
* {{site.data.keyword.IBM_notm}} は、マルチプラットフォーム・アプリ、ネイティブ・アプリ、またはハイブリッド・アプリをモニターおよびテストできるようにしながら、そのようなアプリを作成できるモバイル・バックエンド・インフラストラクチャーを提供します。 アナリティクス、セキュリティー、ユーザー・インサイト、継続的デリバリーで、アプリを強化することもできます。

{{site.data.keyword.cloud_notm}} は、試すことができる試験的サービスも提供しています。 サービス・タイプおよび使用可能かどうかについて詳しくは、[{{site.data.keyword.cloud_notm}} サービス](/docs/services/index.html)を参照してください。


## インフラストラクチャー
{: #bluemixoverviewinfrastructure}

ダッシュボードは、クラウド・インフラストラクチャーのニーズに適合した各種サービスを提供します。

{{site.data.keyword.cloud_notm}} インフラストラクチャーは、入手可能な最高のパフォーマンスを発揮するクラウド・インフラストラクチャーを提供します。 {{site.data.keyword.cloud_notm}} インフラストラクチャーは、最も広範なクラウド・コンピューティング・オプションが揃ったデータ・センターを世界中に持ち、すべてを統合して自動化する 1 つのプラットフォームです。 {{site.data.keyword.CloudDataCents_notm}}は、一流のコンピューティング、ストレージ、およびネットワーキングの機能を豊富に揃えています。 各ロケーションは同様に構築され、装備され、運用されています。したがって、弊社の拠点のどこででもお客様はまったく同じ機能と可用性を得られます。 ロケーションは、業界で最も先進のネットワーク内ネットワークによって接続されています。このネットワークは、パブリック、プライベート、内部管理の別個のネットワークを統合し、ネットワークの総コストを抑えて、より良いアクセスと、より速いスピードを提供します。 また、データ・センターとネットワークは、単一の専有管理システムを共有します。 単一の管理ツールにより、すべてのベアメタル・サーバー、仮想サーバー、およびストレージ・デバイスを含むすべてを制御できます。これらはすべて、API、ポータル、およびモバイル・アプリケーションからアクセス可能です。

{{site.data.keyword.cloud_notm}} インフラストラクチャーは、シームレスな単一プラットフォームで、強力なベア・メタル・サーバーと柔軟な仮想サーバーを提供します。 すべてがオンデマンドで提供され、月単位または時間単位の期間で請求されます。 ベアメタル・サーバーは、プロセッサー集中型およびディスク入出力集中型のワークロードに対して直接的な処理能力を提供し、お客様の仕様どおりに構成できます。 仮想サーバーでは、高速デプロイメント、柔軟な拡張容易性、および従量課金 (PAYG) の請求が可能です。 ハイパフォーマンス・コンピューティングのために、時間単位または月単位で使用可能なグラフィックス処理装置 (GPU) サーバーを使用して、クラウドの機能を向上させることができます。

{{site.data.keyword.cloud_notm}} インフラストラクチャー・オファリングは、3 層のネットワークに接続され、パブリック・トラフィック、プライベート・トラフィック、および管理トラフィックがセグメント化されます。 お客様の {{site.data.keyword.cloud_notm}} アカウントのインフラストラクチャーは、無料でプライベート・ネットワークを介して、そのようなインフラストラクチャー間でデータを転送する場合があります。 ベアメタル・サーバー、仮想サーバー、およびクラウド・ストレージなどのインフラストラクチャー・オファリングは、パブリック・ネットワークを介して、{{site.data.keyword.cloud_notm}} カタログ内の他のアプリケーションおよびサービス (Watson サービス、コンテナー、ランタイムなど) に接続します。 そのような 2 つのタイプのオファリング間で転送されるデータは、計測され、標準パブリック・ネットワーク帯域幅レートで課金されます。

## 地域
{: #ov_intro_reg}

{{site.data.keyword.cloud_notm}} の地域は、アプリをデプロイ可能な定義済みの地理上の区域です。 異なる地域で、
アプリケーション管理に同じ {{site.data.keyword.cloud_notm}} インフラストラクチャー、
課金に同じ使用量詳細ビューを使用して、アプリおよびサービス・インスタンスを作成できます。 顧客に最も近い地域にアプリをデプロイすることで、アプリケーションの待ち時間を短くすることができます。 また、セキュリティー問題に対応するために、アプリケーション・データを保存しておく地域を選択することもできます。 複数地域でアプリを構築すると、1 つの地域が使用不可になっても、別の地域にあるアプリが稼働し続けます。 使用する各地域で、リソースの割当量は同じです。

コンソールのグローバル・ロード・バランシング機能により、何らかの理由で最も近い地域がダウンしている場合には、コンソールは次に近い地域の情報を表示します。 このように、ユーザーは必要な情報にアクセスするためにアクションを取らずに、常にコンソールにアクセスできます。

ダッシュボードから、デフォルトですべての地域のすべてのリソースを表示できます。 特定の地域のリソースを表示および処理する場合は、**「ロケーション」**メニューを展開し、リストから地域を選択します。 

また、`ibmcloud api` コマンドを使用し、地域の API エンドポイントを指定することにより、コマンド・ライン・インターフェースを使用して、作業する {{site.data.keyword.cloud_notm}} 地域に接続することもできます。 例えば、
{{site.data.keyword.cloud_notm}} ヨーロッパ・英国地域に接続するには、次のコマンドを入力します。

```
ibmcloud api https://api.eu-gb.bluemix.net
```

各地域に固有の接頭部が割り当てられています。 {{site.data.keyword.cloud_notm}} には、次の地域と、地域接頭部が用意されています。

| **地域名** | **地理的位置** | **cf API エンドポイント** |
|-----------------|-------------------------|-------------------|
| 米国南部地域 | ダラス、米国 | api.ng.bluemix.net | 
| 米国東部地域 | 米国ワシントン DC | api.us-east.bluemix.net |
| 英国地域 | ロンドン、イングランド | api.eu-gb.bluemix.net | 
| シドニー地域 | シドニー、オーストラリア | api.au-syd.bluemix.net | 
| ドイツ地域 | フランクフルト、ドイツ | api.eu-de.bluemix.net | 
{: caption="表 1. {{site.data.keyword.cloud_notm}} 地域リスト" caption-side="top"}

## {{site.data.keyword.cloud_notm}} の回復力
{: #resiliency}

{{site.data.keyword.cloud_notm}} は、ユーザーのニーズに応じて拡張が容易であり、高可用性を維持し、問題からの復旧速度も速い、拡張が容易で回復力のあるアプリおよびアプリケーション成果物をホストするよう設計されています。 {{site.data.keyword.cloud_notm}} は、相互作用の状態をトラッキングするコンポーネント (ステートフル) とトラッキングしないコンポーネント (ステートレス) を分離します。 この分離により、{{site.data.keyword.cloud_notm}} は必要に応じてアプリを柔軟に移動し、スケーラビリティーと回復力を確保できます。

アプリの 1 つ以上のインスタンスを実行させることができます。 単一のアプリに対して複数のインスタンスがある場合、そのアプリがアップロードされるのは 1 回のみです。 ただし、{{site.data.keyword.cloud_notm}} は、要求された数のアプリ・インスタンスをデプロイし、それらをできる限り多くの仮想サーバーに分散します。

アプリの外のステートフル・データ・ストア (例えば、{{site.data.keyword.cloud_notm}} で提供されているいずれかのデータ・ストア・サービス上のステートフル・データ・ストア) にすべての永続データを保存する必要があります。 メモリー内またはディスク上にキャッシュされたデータはすべて再始動後も使用できない可能性があるので、単一の {{site.data.keyword.cloud_notm}} インスタンスのメモリー・スペースまたはファイル・システムを、短い単一トランザクション・キャッシュとして使用できます。 単一インスタンスのセットアップの場合、{{site.data.keyword.cloud_notm}} のステートレスな性質により、アプリへの要求が中断される可能性があります。 ベスト・プラクティスは、可用性を確保するために、各アプリケーションに少なくとも 3 個のインスタンスを使用することです。

すべての {{site.data.keyword.cloud_notm}} インフラストラクチャー、Cloud Foundry コンポーネント、および {{site.data.keyword.cloud_notm}} 固有の管理コンポーネントが高い可用性を持っています。 インフラストラクチャーの複数インスタンスを使用して、負荷のバランスが保たれます。


## SoR との統合
{: #sor}
{{site.data.keyword.cloud_notm}} は、クラウド環境内にある、以下の 2 つの広範なカテゴリーのシステムを接続することで、開発者を支援できます。

* *SoR* にはビジネス・レコードを保管するアプリとデータベースが含まれており、標準化されたプロセスを自動化します。
* *SoE* は SoR の有用性を拡張する機能で、これによりユーザーが SoR をより有効に活用できるようになります。

{{site.data.keyword.cloud_notm}} で作成するアプリと SoR を統合することで、ユーザーは次のアクションを実行できます。

 * セキュア・コネクターをオンプレミスにダウンロードしてインストールすることで、アプリとバックエンド・データベースとの間のセキュア通信を可能にする。
 * セキュアな方法でデータベースを呼び出す。
 * データベースとカスタマー・リレーションシップ・マネジメント・システムなどのバックエンド・システムとの統合フローから API を作成する。
 * アプリに対して公開したいスキーマおよびテーブルのみを公開する。
 * {{site.data.keyword.cloud_notm}} 組織管理者として、
自分の組織メンバーのみに表示されるプライベート・サービスとして API を公開する。
 
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

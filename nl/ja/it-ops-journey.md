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

# {{site.data.keyword.cloud_notm}} の IT 運用管理者の行程の探索
{: #it-ops}

多くの組織がクラウド環境 (オンプレミスのクラウド環境、またはデータ・センターでホストされているクラウド環境のいずれも) に移行するにつれて、IT 運用管理者の役割が再定義されています。この変更の有効範囲と複雑さは、組織がデプロイする環境のタイプに応じて大幅に増加します。
{: .shortdesc}

クラウドに移行する前は、システムがプライベート LAN またはイントラネットに接続された、本質的にセキュアな環境で作業していました。クラウド環境では、以下のタスクを実行することが要求されています。
 
  * 「どこか」からシステム・コンポーネントを調達する。 
  * ネットワークへの影響とセキュリティー上の課題を理解する。
  * さまざまなテクノロジーを使用して作業する。  
  * 新しい環境を、もともとクラウド・スタックの一部ではないツールと統合する。 
  * まだオンプレミスのデータ・センターがあるかのように、内部顧客を引き続きサポートする。

{{site.data.keyword.cloud}} は、お客様の行程を 100% サポートします。使用可能なリソースには、包括的な資料、計画ツール、適格なサポート・スペシャリスト、およびアクティブなユーザー・コミュニティーが含まれます。以下で、その工程を説明します。 

## 基本の理解
{: #basics}

### クラウド・サービス・モデル
{: #cloud-svc-models}

クラウド・サービス・モデルには、Infrastructure as a Service (IaaS)、Platform as a Service (PaaS)、Software as a Service (SaaS) の 3 つのタイプがあります。図 1 では、各サービス・モデル内で誰が何を行うかを説明します。詳しくは、『[IaaS, PaaS, and SaaS - IBM Cloud service models](https://www.ibm.com/cloud/learn/iaas-paas-saas){: new_window} ![外部リンク・アイコン](../icons/launch-glyph.svg "外部リンク・アイコン")』を参照してください。

![図 1. クラウド・サービス・モデル](images/cloud-svc-models.png "クラウド・サービス・モデル")

IaaS モデルでは、プロバイダーは、基盤となるインフラストラクチャーの保守のみを担当し、オプションで、オペレーティング・システム、アプリケーション、およびデータベースなどソフトウェアのインストールも担当します。IT 運用管理者は、基盤のインフラストラクチャーに制限付きでアクセスできます。そして、ソフトウェアのインストールを担当するか、またはサービス・プロバイダーにソフトウェアのインストールを依頼します。また、サービス・パック、ウィルス・ソフトウェア、およびパッチなどの他のすべての保守も IT 運用管理者が担当します。

PaaS モデルでは、プロバイダーは、オペレーティング・システムを介したシステム管理と、すべてのインフラストラクチャー管理を担当します。これには、OS パッチ、ハードウェア修復、ネットワーク設定なども含まれます。IT 運用管理者は、アプリケーションの構築と保守を行い、IT 運用管理者またはプロバイダーが、データベースやその他のタイプを含むミドルウェアをインストールできます。このモデルは、ソフトウェアの開発とテストに使用されます。詳しくは、『[A practical guide to platform as a service: What is PaaS ![外部リンク・アイコン](../icons/launch-glyph.svg "外部リンク・アイコン")](https://www.ibm.com/blogs/cloud-computing/2016/08/10/practical-guide-paas/){: new_window}』を参照してください。

SaaS モデルでは、プロバイダーは実際のアプリケーションを通じてシステムを保守します。アプリケーションはクラウド対応であり、エンド・ユーザーはソフトウェア・プロバイダーに応じて異なるエンドポイントを使用して、ソフトウェアを使用できます。クラウド・プロバイダーは、ソフトウェア更新、ハードウェア修復、ネットワーク設定など、すべてのインフラストラクチャーおよびアプリケーションの管理を担当します。このモデルは、従量課金ソフトウェア・ライセンス交付モデルでよく使用されます。詳しくは、『[SaaS applications for business and IT](https://www.ibm.com/cloud/saas){: new_window} ![外部リンク・アイコン](../icons/launch-glyph.svg "外部リンク・アイコン")』を参照してください。

### クラウドのタイプ
{: #cloud-types}

クラウドには、パブリック、プライベート、ハイブリッドの 3 つの異なるタイプがあります。パブリック・クラウドには、会社のリソースにアクセスできるようにプロビジョンされたリソースの共有セットが含まれます。これは、仮想サーバー上のマルチテナント環境でホストされ、どこからでもアクセスできます。 

プライベート・クラウドには、会社のリソースにアクセスできるようにプロビジョンされたリソースが含まれます。ベアメタル・サーバーなどの専用ハードウェア上でホストされ、会社のオフィスで (または複数のオフィスにわたって) オンサイトで、またはクラウド・プロバイダーによってホストされます。 プライベート・クラウドにはどこからでもアクセスできます。

ハイブリッド・クラウドには、パブリック・クラウドとプライベート・クラウドの両方の側面を結合するリソースが含まれます。これは、会社のオフィスで (または複数のオフィスにわたって) オンサイトで、およびクラウド・プロバイダーによってホストされます。ハイブリッド・クラウドにはどこからでもアクセスできます。 

## インフラストラクチャーの計画
{: #planning}

実際にプロビジョニングする前にインフラストラクチャーを計画して、ワークロードに合わせて正しくサイズが設定されていることを確認する必要があります。{{site.data.keyword.cloud_notm}} には、インフラストラクチャーの設計およびサイジングに役立ついくつかのツールとサイトがあります。 

### インフラストラクチャー・アーキテクチャー

まず、[インフラストラクチャー・アーキテクチャー ![ 外部リンク・アイコン](../icons/launch-glyph.svg "外部リンク・アイコン ")](https://www.ibm.com/cloud/garage/architectures/infrastructure){: new_window}で、3 つのタイプのクラウド環境について詳しく理解します。 

### {{site.data.keyword.cloud_notm}} Design Decision Tool

[{{site.data.keyword.cloud_notm}} Design Decision Tool ![外部リンク・アイコン](../icons/launch-glyph.svg "外部リンク・アイコン")](https://github.com/ibm-cloud-architecture/infrastructure-design-decision-tool/){: new_window} は、カスタム・ソリューションを設計および作成する際の代替案の比較に役立ちます。各インフラストラクチャー・コンポーネントには、説明、考慮事項、警告、および対照比較があります。ツールの使用方法の例もあります。

### {{site.data.keyword.cloud_notm}} Stencils

[{{site.data.keyword.cloud_notm}} Stencils ![外部リンク・アイコン](../icons/launch-glyph.svg "外部リンク・アイコン")](https://github.com/ibm-cloud-architecture/ibm-cloud-stencils){: new_window} は、一般的なダイアグラミング・ツールを使用して {{site.data.keyword.cloud_notm}} アーキテクチャーのダイアグラムを作成するのに役立ちます。 

### ベアメタル・サーバーのオプション

[{{site.data.keyword.cloud_notm}} {{site.data.keyword.baremetal_short}}の検索ツール ![外部リンク・アイコン](../icons/launch-glyph.svg "外部リンク・アイコン")](https://www.ibm.com/cloud-computing/bluemix/bare-metal-search){: new_window}を使用して、SAP HANA および SAP NetWeaver のワークロードをサポートするように認定されたサーバーを含め、ベアメタル・サーバーのオプションのサイジングと見積もりを行います。

### {{site.data.keyword.cloud_notm}} サービスとコンプライアンス

アーキテクチャーと同様に、インフラストラクチャーをサイジングする際、ソリューションに追加する可能性のある {{site.data.keyword.cloud_notm}} リソースを考慮する必要があります。詳しくは、『[SaaS applications for business and IT ![外部リンク・アイコン](../icons/launch-glyph.svg "外部リンク・アイコン")](https://www.ibm.com/cloud/saas) {: new_window}』を参照して、特定のサービスを検索してください。アーキテクチャーの構築時に考慮する必要がある規則についても検討する必要があります。例えば、ワークロードが機密と見なされているか、または規制されているかなどを検討する必要があります。詳しくは、『[Compliance ![外部リンク・アイコン](../icons/launch-glyph.svg "外部リンク・アイコン")](https://www.ibm.com/cloud/compliance){: new_window}』を参照してください。

## インフラストラクチャーの構築
{: #build}

インフラストラクチャーを計画して設計すると、インフラストラクチャーを構築する準備が整います。 

### コンピュート
{: #compute}

サーバーはインフラストラクチャーの基盤です。ニーズに応じてさまざまなオプションがありますが、ご使用の環境で必要なものであれば、それらを混合することができます。コンピュート・オプションの要約については、以下の表を確認してください。

| オプション | 説明 | 
|--------|---------------|
| [{{site.data.keyword.baremetal_short}}](/docs/bare-metal/about.html)  | お客様専用で、サーバー・リソースを含むどの部分でも他のお客様と共有されない、時間単位または月単位のシングル・テナント・サーバー。 |
| [{{site.data.keyword.BluVirtServers_short}}](/docs/vsi/vsi_about.html) | 専用のコアおよびメモリー割り振りと共に購入される拡張が容易な仮想サーバー。 |
| [{{site.data.keyword.vmwaresolutions_short}}](/docs/services/vmwaresolutions/vmonic/prod_overview.html) | スケーラブルでセキュアでハイパフォーマンスのインフラストラクチャー、および業界最先端の VMware ハイブリッド仮想化テクノロジーを使用して、オンプレミスの VMware ワークロードを迅速かつシームレスに統合またはマイグレーションします。|
| [{{site.data.keyword.containerlong_notm}}](/docs/containers/cs_why.html) | Docker コンテナー、Kubernetes テクノロジー、直観的なユーザー・エクスペリエンス、標準装備のセキュリティーと分離機能を結合させることにより、コンピュート・ホストのクラスター内でコンテナー化アプリのデプロイメント、操作、スケーリング、モニタリングを自動化します。|
| [{{site.data.keyword.cfee_full_notm}}](/docs/cloud-foundry/index.html) | 複数の分離したエンタープライズ・グレードの Cloud Foundry プラットフォームをオンデマンドでインスタンス化します。|
| [{{site.data.keyword.openwhisk_short}}](/docs/openwhisk/index.html) | Apache OpenWhisk に基づく Functions-as-a-Service (FaaS) プログラミング・プラットフォーム。|
{: caption="表 1. 計算オプション" caption-side="top"}
   
### ストレージ
{: #storage}

{{site.data.keyword.baremetal_short}}および{{site.data.keyword.BluVirtServers_short}}は、デフォルトのストレージを使用してプロビジョンされます。{{site.data.keyword.baremetal_short}}には少なくとも 1 TB の SATA ディスク・スペースがあり、{{site.data.keyword.BluVirtServers_short}}には少なくとも 25 GB の SAN ストレージがあります。これに対する例外は、{{site.data.keyword.cloud_notm}} SAP 認定の{{site.data.keyword.baremetal_short}}です。これらのサーバーで使用可能なデフォルト・ストレージについて詳しくは、『[{{site.data.keyword.cloud_notm}} SAP 認定インフラストラクチャー](/docs/bare-metal/bare-metal-sap-applications.html#ibm-cloud-sap-certified-infrastructure)』を参照してください。

必要に応じて追加のストレージを購入できます。コンピュート・オプションの要約については、以下の表を参照してください。

| オプション | 説明 |
|--------|---------------|
| [{{site.data.keyword.blockstorageshort}}](/docs//infrastructure/BlockStorage/index.html) | コンピュート・インスタンスから独立してプロビジョンおよび管理される、永続的で高性能な iSCSI ストレージです。iSCSI ベースのブロック・ストレージ LUN は、冗長マルチパス入出力 (MPIO) 接続を介して、許可されたデバイスに接続されます。 |
| [{{site.data.keyword.filestorage_short}}](/docs/infrastructure/FileStorage/index.html) | 永続的で高速かつ柔軟なネットワーク接続された NFS ベースのファイル・ストレージ。この Network Attached Storage (NAS) 環境では、ファイル共有機能とパフォーマンスを完全に制御できます。 ファイル・ストレージ共有は、回復力のために、経路指定された TCP/IP 接続を介して最大 64 台の許可デバイスに接続できます。|
| [{{site.data.keyword.cos_full_notm}}](/docs/services/cloud-object-storage/about-cos.html) | IBM Cloud Object Storage に保管された情報は暗号化され、複数の地理的位置に分散され、REST API を使用して HTTP を介してアクセスされます。このサービスは、IBM Cloud Object Storage System (以前の Cleversafe) によって提供されている分散ストレージ・テクノロジーを利用します。|
| [{{site.data.keyword.cloud_notm}} Mass Data Migration](/docs/infrastructure/mass-data-migration/index.html) | オンプレミス・データ・センターからクラウド・オブジェクト・ストレージ・バケットに大量のデータをオフロードします。|
| [EVault](/docs/infrastructure/Backup/index.html) | 仮想サーバー専用の EVault WebCC ブラウザー・ベースの管理ユーティリティーを使用して管理される、エージェント・ベースの自動バックアップ・システム。IBM Cloud ネットワーク上の 1 つ以上のデータ・センター内のサーバー間でデータをバックアップします。|
{: caption="表 2. ストレージ・オプション" caption-side="top"}

### ネットワーキング
{: #network}

{{site.data.keyword.cloud_notm}} アカウントがセットアップされると、{{site.data.keyword.vpn_full}} に自動的に接続されます。サーバーにはデフォルトで、パブリック IP アドレスとプライベート IP アドレスがあります。サーバーをプライベートにする場合は、サーバーのプロビジョン後にパブリック・インターフェースをオフにするか、サーバーをプライベートとして注文することができます。詳しくは、[仮想プライベート・ネットワーキング (VPN) の概要](/docs/infrastructure/iaas-vpn/getting-started.html)を参照してください。

ネットワーキング・オプションの要約については、以下の表を確認してください。

| オプション | 説明 | 
|--------|---------------|
| [コンテンツ・デリバリー・ネットワーク](/docs/infrastructure/CDN/about.html) | 企業のニーズを満たすために、メディア、エンターテイメント、ソフトウェア、ゲーム、バンキング、および e-コマースなどのさまざまな業界ソリューションに使用されます。|
| [ドメイン・ネーム・サービス](/docs/cli/reference/ibmcloud/cli_dns.html) | 基本の DNS 管理インターフェースを使用してドメインを表示および管理するための中心的な場所を提供し、さらに、同じ場所でリバース DNS およびセカンダリー DNS を管理するオプションを無料で提供します。|
| [グローバル IP アドレス](/docs/infrastructure/subnets/about-global-ip.html) | 柔軟性を提供し、地理的に異なるデータ・センター間であっても、サーバー間でワークロードをシフトできるようにします。|
| [ロード・バランシング](/docs/infrastructure/local-load-balancer/about.html) | 1 つのデバイスに全負荷がかからないように、データ・センター内の複数のサーバーに処理と通信を均等に分散します。|
| [仮想ルーター・アプライアンス](/docs/infrastructure/virtual-router-appliance/about.html) | ファイアウォール、トラフィック・シェーピング、ポリシー・ベース・ルーティング、VPN、および他のフィーチャーのホストを備えたフル機能のエンタープライズ・ルーターを介して、プライベート・ネットワーク・トラフィックとパブリック・ネットワーク・トラフィックを選択的にルーティングします。|
| [IPSec VPN](/docs/infrastructure/iaas-vpn/set-up-ipsec-vpn.html) | 暗号化されたサイト間ネットワークを提供するトンネル・モードを使用して、2 つのロケーション間のすべての IP トラフィックを認証して暗号化するように設計された一組のプロトコル。|
| {{site.data.keyword.cloud_notm}} Direct Link | Cloud Exchange プロバイダーを利用して、{{site.data.keyword.cloud_notm}} インフラストラクチャー・ロケーションへの接続を提供します。|
{: caption="表 3. ネットワーキング・オプション" caption-side="top"}


## インフラストラクチャーの管理
{: #managing}

インフラストラクチャーと環境を構築すると、その管理を開始する準備が整います。

| タスク | 説明 |
|--------|---------------|
| [システム・イベントのモニター](/docs/account/audit_log.html) | インフラストラクチャー・リソースに対して実行されたアクションを表示します。|
| [E メール設定の指定](/docs/account/email.html) | 計画外のイベント、保守、および告知に関する {{site.data.keyword.cloud_notm}} インフラストラクチャーの E メール通知をセットアップします。|
| [データの安全性の理解](/docs/overview/security.html) | {{site.data.keyword.cloud_notm}} プラットフォームは、ネットワークおよびインフラストラクチャー全体にわたって階層化されたセキュリティー管理を備えています。|
| [ダウン時間をゼロにする方法の理解](/docs/overview/zero_downtime.html) |すべての {{site.data.keyword.cloud_notm}} リソースは、世界中のデータ・センターの場所でホストされます。|
{: caption="表 4. 管理タスク" caption-side="top"}

---

copyright:

  years: 2018

lastupdated: "2018-11-01"

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:pre: .pre}
{:tip: .tip}

# リソース・デプロイメントのロケーション 
{: #ov_intro_reg}

異なるロケーションで、アプリケーション管理に同じ {{site.data.keyword.cloud_notm}} インフラストラクチャー、課金に同じ使用量詳細ビューを使用して、アプリおよびサービス・インスタンスを作成できます。 顧客に最も近いロケーションにアプリをデプロイすることで、アプリケーションの待ち時間を短くすることができます。 

また、セキュリティー問題に対応するために、アプリケーション・データを保存しておくロケーションを選択することもできます。 複数のロケーションでアプリを作成すると、1 つのロケーションが使用不可になっても、他のロケーションにあるアプリが稼働し続けます。使用する各ロケーションで、リソースの割当量は同じです。 プラットフォーム・リソースおよびそれらが使用可能なロケーションについて詳しくは、[サービスの可用性](/docs/resources/service_region.html)を参照してください。

コンソールのグローバル・ロード・バランシング機能により、ユーザーにとって最も近い地理的ロケーションがダウンしている場合、コンソールは次に近いロケーションの情報を表示します。このように、ユーザーは必要な情報にアクセスするためにアクションを取らずに、常にコンソールにアクセスできます。

<!---This is a pre-pup topic. Post pup, the dashboard will have a Location status widget, which will show geographies as a summary. This paragraph will change and we need to add a paragraph to explain the continents are a summary in the widget.-->
ダッシュボードから、デフォルトですべてのロケーションのすべてのリソースを表示できます。 特定のロケーションのリソースを表示および処理する場合は、**「ロケーション」**メニューを展開し、リストからロケーションを選択します。 

また、`ibmcloud api` コマンドを使用し、ロケーションの API エンドポイントを指定することにより、コマンド・ライン・インターフェースを使用して、作業する {{site.data.keyword.cloud_notm}} ロケーションに接続することもできます。 例えば、{{site.data.keyword.cloud_notm}} ロンドンに接続するには、以下のコマンドを入力します。

```
ibmcloud api https://api.eu-gb.bluemix.net
```

各ロケーションに固有の接頭部が割り当てられています。 {{site.data.keyword.cloud_notm}} には、次のロケーションと、ロケーション接頭部が用意されています。

| **ロケーション** | **API エンドポイント** |
|-----------------|-------------------|
| ダラス | api.us-south.bluemix.net |
| シドニー | api.au-syd.bluemix.net |
| フランクフルト | api.eu-de.bluemix.net |
| ロンドン | api.eu-gb.bluemix.net |
| ワシントン DC | api.us-east.bluemix.net |
| 東京 | api.jp-tok.bluemix.net |
{: caption="表 1. {{site.data.keyword.cloud_notm}} ロケーション・リスト" caption-side="top"}

インフラストラクチャー・リソースをデプロイするときは、コンテンツの場所についてさらに多くの選択項目があります。ロケーションを選択することも、{{site.data.keyword.Bluemix_notm}} 内のデータ・センターのリストから選択することもできます。詳しくは、[{{site.data.keyword.cloud_notm}} データ・センター](data-centers.html)を参照してください。

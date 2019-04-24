---

copyright:

  years: 2018, 2019

lastupdated: "2019-02-19"

keywords: account quick start, account set up

subcollection: overview

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:tip: .tip}

# アカウントのセットアップ
{: #quickstart_acc_ad}

このクイック・スタート・ガイドは、アカウント管理者が {{site.data.keyword.Bluemix}} 環境をセットアップするのを支援することを目的としています。 
{:shortdesc}

1. {{site.data.keyword.Bluemix_notm}} カタログから作成するリソースを編成するためのリソース・グループを作成します。 詳しくは、『[リソースをリソース・グループに編成するためのベスト・プラクティス](/docs/resources?topic=resources-bp_resourcegroups)』を参照してください。

  リソースをリソース・グループに割り当てた後は移動できないため、事前にリソース・グループを作成しておくことが重要です。
  {:tip}
  
2. すべてのサービスが {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) によって管理されるわけではないため、これらのサービスへのアクセス権限を編成および付与するための Cloud Foundry 組織を作成します。 ライト・アカウントでは、1 つの {{site.data.keyword.Bluemix_notm}} ロケーションに 1 つの Cloud Foundry 組織があります。 詳しくは、『[組織およびスペースの追加](/docs/account?topic=account-orgsspacesusers)』を参照してください。 
3. アクセス・グループを作成し、同じアクセス・レベルが割り当てられている必要があるグループにユーザーおよびサービス ID を編成します。 詳しくは、[アクセス・グループのセットアップ](/docs/iam?topic=iam-groups)を参照してください。
4. アカウントにユーザーを招待してアクセス・グループに追加し、アカウント・ユーザーが作成を行えるように必要なアクセス権限を割り当てます。 詳しくは、IAM の『[入門チュートリアル](/docs/iam?topic=iam-getstarted)』を参照してください。
5. イベントおよびアカウント消費限度の通知をセットアップします。 詳しくは、『[E メールの設定 (Setting email preferences)](/docs/account?topic=account-email-prefs)』および『[消費量通知の設定](/docs/billing-usage?topic=billing-usage-spending)』を参照してください。 
6. コスト見積もりプログラムを使用して、ご使用環境のコストを把握します。 コンソールのメニュー・バーで「コスト見積もりツール」アイコン ![「見積もりツール」アイコン](../icons/Estimator.svg) をクリックします。 
7. コスト見積もりツールを使用して、インフラストラクチャーのコストを把握します。 
  
  a. 最初に、[カタログ](https://cloud.ibm.com/catalog){: new_window} ![外部リンク・アイコン](../icons/launch-glyph.svg)からオファリングを選択します。 
  
  b. 構成の詳細を入力し、料金プランを選択し、**「見積もりに追加」**をクリックします。

## 次のステップ
{: #next-steps-acc-ad}

* アカウント内でサービスの作成を開始して、組織と開発者が必要なソリューションを作成できるようにします。  
* タグを作成し、リソースにタグを付けて、請求および使用量の表示方法を編成しやすくします。 それにより、さまざまな組織へのチャージバックを容易に識別することができます。 詳しくは、『[リソースにタグ付けするためのベスト・プラクティス](/docs/account?topic=account-account_setup#tags)』を参照してください。 

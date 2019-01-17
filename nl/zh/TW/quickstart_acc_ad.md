---

copyright:

  years: 2018

lastupdated: "2018-11-14"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:tip: .tip}

# 設定帳戶
{: #quickstart_acc_ad}

本快速入門手冊旨在協助帳戶管理者設定其 {{site.data.keyword.Bluemix}} 環境。
{:shortdesc}

1. 建立資源群組，用來組織從 {{site.data.keyword.Bluemix_notm}} 型錄建立的資源。如需相關資訊，請參閱[用資源群組組織資源的最佳作法](/docs/resources/bestpractice_rgs.html#bp_resourcegroups)。

  提前這麼做是很重要的，因為在您將資源指派至資源群組之後，就無法再移動它。
  {:tip}
  
2. 因為並非所有服務都由 {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) 進行管理，所以請建立您的 Cloud Foundry 組織，來組織及授與那些服務的存取權。使用「精簡」帳戶，您可以在一個 {{site.data.keyword.Bluemix_notm}} 位置獲得一個 Cloud Foundry 組織。如需相關資訊，請參閱[新增組織及空間](/docs/account/orgs_spaces.html#orgsspacesusers)。 
3. 建立存取群組，將使用者和服務 ID 組織成需要指派相同層次之存取權的群組。如需相關資訊，請參閱[設定存取群組](/docs/iam/groups.html#groups)。
4. 邀請使用者加入帳戶，並將他們新增至存取群組，以指派必要存取權來容許帳戶使用者著手建置。如需相關資訊，請參閱 [IAM 的入門指導教學](/docs/iam/quickstart.html#getstarted)。
5. 設定事件及帳戶消費限制的通知。如需相關資訊，請參閱[設定電子郵件喜好設定](/docs/account/email.html)和[設定消費通知](/docs/billing-usage/notifications.html)。 
6. 使用成本預估器，以瞭解您的環境可能需要多少成本。按一下主控台功能表列中的「成本預估器」圖示 ![「預估器」圖示](../icons/Estimator.svg)。 
7. 使用成本預估器，以瞭解您的基礎架構可能需要多少成本。 
  
  a. 一開始，先從[型錄](https://console.cloud.ibm.com/catalog){: new_window} ![外部鏈結圖示](../icons/launch-glyph.svg) 中選取供應項目。 
  
  b. 輸入配置詳細資料、選取定價方案，然後按一下**新增至預估**。

## 後續步驟
{: #next-steps}

* 開始在帳戶中建立服務，讓您的組織及開發人員能夠建置他們需要的解決方案。  
* 建立標籤並標記資源，以協助組織計費及用量的檢視方式。這樣可以更輕鬆地識別不同組織的扣款。如需相關資訊，請參閱[標記資源的最佳作法](/docs/account/bp_account.html#tags)。 

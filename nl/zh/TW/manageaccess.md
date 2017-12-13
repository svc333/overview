---

copyright:

  years: 2017

lastupdated: "2017-11-10"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}

# 在 {{site.data.keyword.Bluemix_notm}} 中管理存取權
{: #cloudaccess}

## 何謂存取管理？

存取管理可讓您控制哪些使用者可以查看、建立、使用及管理您帳戶中的資源。若要授與存取權，您可以指派角色，以容許使用者完成平台管理作業以及存取帳戶資源的存取層次。 

您在 {{site.data.keyword.Bluemix_notm}} 中管理存取權的方式，取決於要指派存取權的資源類型。「{{site.data.keyword.Bluemix_notm}} 身分及存取管理 (IAM)」是跨 {{site.data.keyword.Bluemix_notm}} 平台一致地管理資源的存取管理系統。{{site.data.keyword.Bluemix_notm}} 基礎架構及 Cloud Foundry 資源不是使用 Cloud IAM 進行管理。這些資源類型具有自己的存取管理系統。如果您有資源類型的組合，則可以個別管理每一種類型。若要指派對基礎架構資源的存取權，請在 SoftLayer 帳戶內設定許可權。若要指派對 Cloud Foundry 資源的存取權，請使用主控台之「身分及存取」區段中的「使用 Cloud Foundry 指派」選項。 

## 誰有權管理存取權？

身為帳戶擁有者，您可以管理帳戶中所有資源的存取權。您也可以藉由將所有服務的管理者角色指派給帳戶中的使用者，來委派平台資源存取權的管理作業。 

如果您的帳戶中有 Cloud Foundry 服務，則可以將組織或空間管理者角色指派給另一位使用者，以讓他們新增使用者，以及指派 Cloud Foundry 使用者角色來存取他們所管理之組織或空間中的實例。


## 如何開始管理存取權？

移至**管理** &gt; **安全** &gt; **身分及存取**，然後選取**使用者**來開始管理您帳戶中使用者的存取權。請從清單中選取使用者以開始使用。您只會看到有權管理的存取管理選項。例如，如果您不是帳戶擁有者，而且不是組織或空間管理員，則看不到管理 Cloud Foundry 存取權的選項。 

也可以使用服務 ID，將存取角色指派給應用程式及服務。移至**服務 ID** 頁面以開始使用。如需如何快速開始進行 Cloud IAM 的相關資訊，請遵循[開始使用指導教學](/docs/iam/quickstart.html#iambestpractice)中的步驟。



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

# Configurando sua conta
{: #quickstart_acc_ad}

Esse guia de iniciação rápida destina-se a ajudar os administradores de conta a configurar o ambiente {{site.data.keyword.Bluemix}}.
{:shortdesc}

1. Crie grupos de recursos para usar na organização dos recursos criados por meio do catálogo do {{site.data.keyword.Bluemix_notm}}. Para obter mais informações, consulte [Melhores práticas para organizar recursos em grupos de recursos](/docs/resources/bestpractice_rgs.html#bp_resourcegroups).

  Fazer isso antecipadamente é importante porque depois de designar um recurso a um grupo de recursos, ele
não poderá ser movido.
  {:tip}
  
2. Como nem todos os serviços são gerenciados pelo {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM), crie sua organização do Cloud Foundry para organizar e conceder acesso a esses serviços. Com
uma conta Lite, você obtém uma organização do Cloud Foundry em uma localização do {{site.data.keyword.Bluemix_notm}}. Para obter mais informações, consulte [Incluindo organizações e espaços](/docs/account/orgs_spaces.html#orgsspacesusers). 
3. Crie grupos de acesso para organizar usuários e IDs de serviço em grupos que requerem o mesmo nível de acesso designado. Para obter mais informações, consulte [Configurando grupos de acesso](/docs/iam/groups.html#groups).
4. Convide usuários para a conta e inclua-os em grupos de acesso para designar o acesso necessário para permitir que os
usuários da conta possam construir. Para obter mais informações, consulte o
[Tutorial de introdução do IAM](/docs/iam/quickstart.html#getstarted).
5. Configure notificações para eventos e limites de gasto da conta. Para obter mais informações, consulte [Configurando preferências de e-mail](/docs/account/email.html) e [Configurando notificações de gasto](/docs/billing-usage/notifications.html). 
6. Use o estimador de custo para obter uma ideia de quanto seu ambiente pode custar. Clique no ícone Estimador de custo ![Ícone Estimador](../icons/Estimator.svg) na barra de menus do console. 
7. Use o estimador de custo para obter uma ideia de quanto sua infraestrutura pode custar. 
  
  a. Inicie selecionando uma oferta por meio do catálogo do [](https://console.cloud.ibm.com/catalog){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg). 
  
  b. Insira os detalhes de configuração, selecione seu plano de precificação e clique em **Incluir para
estimativa**.

## Próximas Etapas
{: #next-steps}

* Inicie a criação de serviços dentro da conta para permitir que a sua organização e os desenvolvedores construam as
soluções que precisam.  
* Crie tags e identifique seus recursos para ajudar a organizar como você visualizará o faturamento e o uso. Isso
facilita a identificação dos estornos para as diferentes organizações. Para obter mais informações, consulte
[Melhores práticas para a identificação de recursos](/docs/account/bp_account.html#tags). 

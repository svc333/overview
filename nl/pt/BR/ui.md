---


copyright:
  years: 2015, 2019
lastupdated: "2019-06-25"

keywords: ui, components, using the console, SoftLayer, classic infrastructure

subcollection: overview

---

{:shortdesc: .shortdesc}
{:tip: .tip}
{:note: .note}
{:new_window: target="_blank"}

# Navegando no console do {{site.data.keyword.cloud_notm}} 
{: #ui}

O console do {{site.data.keyword.cloud}} é uma interface com o usuário que ajuda a gerenciar todos os recursos do {{site.data.keyword.cloud_notm}}. Quando
você acessa o [console](https://cloud.ibm.com){: new_window}
![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo"), é possível
criar uma conta gratuita, efetuar login, acessar a documentação, acessar o catálogo, visualizar as informações de precificação, obter suporte ou verificar o status dos componentes do {{site.data.keyword.cloud_notm}}. Depois
de efetuar login, a barra de menus conterá um ícone Menu ![Ícone Menu](../icons/icon_hamburger.svg) e mais links.
{: shortdesc}


## Utilizando o Console
{: #consoleoptions}

Quando você efetuar login no {{site.data.keyword.cloud_notm}}, o seu painel será exibido, mostrando widgets que resumem o status de sua conta. Se você estiver interessado em incluir ou remover widgets, consulte [Customizando o seu painel](/docs/overview?topic=overview-custom-dashboard).

  * Use o link **Catálogo** para criar novos recursos.
  * Use o link **Docs** para acessar a documentação do produto. 
  * Use o link **Suporte** para acessar o centro de suporte.  
  * No menu **Gerenciar**, é possível acessar a sua conta, o faturamento e uso e as opções de
gerenciamento de acesso e identidade.
  * Clique no ícone Estimador de custo ![Ícone Estimador de custo](../icons/Estimator.svg) para
abrir o estimador de custo.
  * Clique no ícone Notificações ![Ícone Notificações](../icons/Notification.svg) para acessar
comunicados e eventos planejados e não planejados.

## Procurando Recursos
{: #search}

É possível procurar recursos por nome ou por tag de qualquer lugar no console do {{site.data.keyword.cloud_notm}} para recursos que você espera localizar na lista de recursos. Digite o nome de um recurso ou uma tag no campo de procura na barra de menus do console.

Para obter mais informações, consulte [Procurando recursos](/docs/resources?topic=resources-searching-for-resources). 

## Gerenciando recursos na lista de recursos
{: #dashboardview}

Acesse o ícone Menu ![Ícone Menu](../icons/icon_hamburger.svg) &gt; **Lista de
recursos** para acessar a sua lista de recursos da conta. É possível usar a lista de recursos para visualizar
e trabalhar com os recursos do {{site.data.keyword.cloud_notm}} e as instâncias de serviço do Cloud Foundry. Veja [O que é um recurso?](/docs/resources?topic=resources-resource) para obter mais informações sobre os diferentes tipos de recursos.

### Visualizando recursos
É possível visualizar todos os recursos em sua conta em todas as regiões por meio da lista de recursos. Para ver os
itens que são importantes para você, filtre a sua lista com os filtros para cada cabeçalho da coluna. Por exemplo, se
você desejar visualizar e trabalhar com recursos em uma localização específica, expanda o filtro
**Localização** e selecione uma localização na lista.

### Trabalhando com recursos
É possível trabalhar com os recursos de várias maneiras por meio da lista de recursos:

  * Cada recurso é exibido em sua própria linha e um ícone Ações ![Ícone Mais ações](../icons/action-menu-icon.svg) é incluído no término da linha. Clique no ícone Ações ![Ícone Mais ações](../icons/action-menu-icon.svg) para iniciar, parar, renomear ou excluir um recurso.
  * Para configurar credenciais ou conexões para um recurso, clique no nome do recurso para navegar para a página de detalhes do recurso. Em seguida, selecione **Credenciais de serviço** ou **Conexões**. Para obter mais informações, consulte [Incluindo uma credencial](/docs/resources?topic=resources-service_credentials) e [Gerenciando conexões](/docs/resources?topic=resources-connect_app).

## Trabalhando no catálogo
{: #catalogcreate}

Para criar um recurso, clique em **Criar** na lista de recursos. Você é então direcionado para o catálogo. Ao selecionar um tile do catálogo, será possível ver onde o recurso estará disponível. Nem todos os recursos listados no catálogo estão disponíveis em todas as regiões.

Depois que você clica no tile para o recurso que deseja criar, é possível selecionar em qual local você deseja implementar.

  * Para recursos do Cloud Foundry, é possível selecionar uma região específica e depois selecionar a organização e o espaço aos quais designar a instância de serviço.
  * Para recursos gerenciados pelo {{site.data.keyword.cloud_notm}} Identity and Access Management (IAM), você seleciona um local no qual implementar. Em seguida, você seleciona um grupo de recursos ao qual designar a instância de serviço.

## Executando a transição para a experiência do {{site.data.keyword.cloud_notm}}
{: #redirect-cloud}

Como parte da migração do SoftLayer para o {{site.data.keyword.cloud_notm}}, familiarize-se com o console do {{site.data.keyword.cloud_notm}}, que você usa para gerenciar os seus recursos de plataforma e de infraestrutura. Estamos atualmente no processo de vincular todas as contas SoftLayer e {{site.data.keyword.cloud_notm}}. Portanto, sua conta pode não ter acesso ainda. Assim que tiver, será possível conferir a nova experiência. 

O SoftLayer, como era chamado anteriormente, agora é chamado de infraestrutura clássica do {{site.data.keyword.cloud_notm}}.
{: note}

### Localizando seus itens de infraestrutura
{: #sl-links}

Clique no **Ícone de menu** ![Ícone de menu](../icons/icon_hamburger.svg) > **Infraestrutura clássica** para localizar seus dispositivos, armazenamento, rede, segurança e serviços. 

![Localização de itens de infraestrutura clássica.](images/iaas-items.png "Localizando os seus itens de infraestrutura")

Também é possível visualizar os seus dispositivos e itens de armazenamento na lista de recursos, clicando no **Ícone de menu** ![Ícone de menu](../icons/icon_hamburger.svg) > **Lista de recursos**.
{: tip}

### Gerenciando usuários, acesso e chaves de API
{: #billing-items}

É possível gerenciar usuários em sua conta, acesso de infraestrutura clássica para os seus usuários e as suas chaves de API por meio da seção Acessar (IAM) do console. 

* Para convidar novos usuários, remover usuários ou gerenciar configurações de um login do usuário específico, restrições de IP, senha de VPN e mais, acesse **Gerenciar** > **Acessar (IAM)** e selecione **Usuários**.
* Para começar a gerenciar o acesso à infraestrutura clássica de um usuário, acesse **Gerenciar** > **Acessar (IAM)** e selecione **Usuários**. Para obter mais detalhes, consulte [Gerenciando o acesso da infraestrutura clássica](/docs/iam?topic=iam-mngclassicinfra).
* Para criar e gerenciar as chaves de API do {{site.data.keyword.cloud_notm}} ou uma chave de API de infraestrutura clássica, acesse **Gerenciar** > **Acessar (IAM)** e selecione **Chaves de API**. Para obter mais informações, veja [Entendendo chaves de API](/docs/iam?topic=iam-manapikey).

![Localização para gerenciar itens do IAM.](images/users-access.png "Gerenciando usuários, acesso e chaves de API")

### Realizando um pedido
{: #place-order}

Use o catálogo para fazer um pedido. É possível navegar até o catálogo de uma das formas a seguir:

  * Clique em **Catálogo** na barra de menus.
  * Clique no **Ícone de menu** ![Ícone de menu](../icons/icon_hamburger.svg) > **Lista de recursos**. Em seguida, clique em **Criar recurso**.

![Localização para colocar um pedido.](images/orders.png "Colocando um pedido")

### Fazendo um pagamento
{: #payments}

É possível fazer um pagamento na seção Faturamento e uso do console. Acesse **Gerenciar** > **Faturamento e uso** e selecione **Pagamentos**. 

![Localização para fazer um pagamento.](images/payments.png "Fazendo um pagamento")

### Acessando as suas faturas
{: #invoices}

É possível acessar as suas faturas por meio da seção de Faturamento e de uso do console. Acesse **Gerenciar** > **Faturamento e uso** e selecione **Faturas**.

![Localização para acessar as suas faturas.](images/invoices.png "Acessando as suas faturas")

### Acessando seus itens em promoção
{: #sales}

Suas cotações e upgrades de dispositivo, pedidos, cancelamentos e remessas estão na seção Faturamento e uso do console. Acesse **Gerenciar** > **Faturamento e uso** e selecione **Vendas**. 

![Localização para acessar itens em promoção.](images/sales-items.png "Acessando os seus itens em promoção")

### Acessando seus casos de suporte
{: #support-mng}

Para acessar seus casos de suporte atuais, clique em **Suporte** > **Gerenciar casos**. Também é possível acessar seus casos arquivados clicando em **Visualizar casos arquivados**.

![Localização para acessar casos de suporte.](images/support-cases.png "Acessando os seus casos de suporte")

### Enviando feedback
{: #feedback-profile}

É possível enviar uma revisão de rave, uma sugestão ou qualquer outro feedback. Para entrar em contato conosco, escolha entre os métodos a seguir:

  * Clique no botão **Feedback** que está localizado na borda da página do console. 
  * Clique no **Ícone Avatar** ![Ícone Avatar](../icons/i-avatar-icon.svg) > **Feedback**. 

![Localização para enviar feedback.](images/feedback.png "Enviando feedback")

### Configurando preferências de e-mail
{: #email-prefsl}

É possível configurar as suas preferências para receber e-mails sobre notificações de plataforma e infraestrutura. Clique no **Ícone avatar** ![Ícone avatar](../icons/i-avatar-icon.svg) > **Perfil e configurações** e selecione **Notificações**.

![Localização para configurar preferências de e-mail.](images/email-prefs.png "Configurando preferências de e-mail")

### Selecionando o seu ponto de acesso de VPN
{: #vpn-access}

É possível efetuar login no console do {{site.data.keyword.cloud_notm}} usando um ponto de acesso de VPN. Acesse [Acesso de VPN](https://www.ibm.com/cloud-computing/bluemix/vpn-access) e selecione um ponto de acesso nas listas.


---


copyright:
  years: 2016, 2017
lastupdated: "2017-11-15"

---

{:shortdesc: .shortdesc}
{:tip: .tip}
{:new_window: target="_blank"}

# Como o {{site.data.keyword.cloud_notm}} console funciona
{: #ui}

O console do {{site.data.keyword.cloud}} é uma interface com o usuário que ajuda a gerenciar todos os recursos do {{site.data.keyword.cloud_notm}}. Ao acessar o [console](https://console.bluemix.net){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo"), é possível criar uma conta grátis, efetuar login, acessar a documentação, acessar o catálogo, visualizar informações de precificação, obter suporte ou verificar o status de todos os componentes do {{site.data.keyword.cloud_notm}}. Depois de efetuar login, a barra de menus contém um ícone Menu ![ícone Menu](../icons/icon_hamburger.svg) e links adicionais, dependendo de seu tipo de conta.
{: shortdesc}

## Utilizando o Console
{: #consoleoptions}

Se você for um usuário existente com uma conta do {{site.data.keyword.cloud_notm}}, será possível usar o ícone de Menu ![Menu icon](../icons/icon_hamburger.svg) para acessar todos os recursos existentes em seu painel. 
  * Use o link **Catálogo** para criar novos recursos.
  * Use o link **Docs** para acessar informações úteis sobre o {{site.data.keyword.cloud_notm}}.
  * No menu **Suporte**, é possível acessar informações sobre o que há de novo no {{site.data.keyword.cloud_notm}}, o Centro de suporte, as opções para incluir e visualizar chamados e a página Status.
  * No menu **Gerenciar**, é possível acessar sua conta, faturamento e uso e as opções de segurança.

Se você vinculou as suas contas do {{site.data.keyword.cloud_notm}} e do SoftLayer, terá as mesmas opções que um proprietário da conta não vinculada, além de poder navegar para o portal do cliente clicando na opção **Ícone Menu ![Menu icon](../icons/icon_hamburger.svg) > Infraestrutura**. Desse ponto, é possível visualizar seu resumo de conta, pedir armazenamento e dispositivos e gerenciar o acesso para usuários e dispositivos somente de VPN. 

## Gerenciando recursos no painel
{: #dashboardview}

É possível usar o painel para visualizar e trabalhar com recursos do {{site.data.keyword.cloud_notm}}. *Recursos* é um termo amplo que abrange qualquer coisa, de um serviço a uma conta. Para uma definição sucinta, veja o [Glossário do {{site.data.keyword.cloud_notm}}](/docs/overview/glossary/index.html#glossr).

### Visualizando recursos

É possível visualizar todos os recursos em sua conta no painel. Para customizar sua visualização, use as opções a seguir:

  * Para visualizar recursos em um grupo de recursos específico, selecione um grupo de recursos na lista **Grupo de recursos**. 
  * Para visualizar recursos em uma organização específica do Cloud Foundry, selecione uma organização na lista **Organização do Cloud Foundry**. 

Em seguida, com base nos itens selecionados, é possível filtrar pelas opções a seguir:

  * Região
  * Espaço do Cloud Foundry
  
### Trabalhando com recursos

É possível trabalhar com seus recursos de várias maneiras no painel:

  * Cada recurso é exibido em sua própria linha e um ícone Mais ações ![More Actions icon](../icons/overflow-menu.svg) é incluído no término da linha. Clique no ícone Mais ações para iniciar, parar, renomear ou excluir um recurso. 
  * Para configurar credenciais ou conexões para um recurso, clique no nome do recurso para navegar para a página de detalhes do recurso. Para obter mais informações, veja [Incluindo uma nova credencial](/docs/services/service_credentials.html) e [Gerenciando conexões](/docs/manageapps/connecting_apps.html). 

## Trabalhando no catálogo
{: #catalogcreate}

Para criar um novo recurso, clique em **Criar recurso** em seu painel. Você é então direcionado para o catálogo. Ao selecionar um tile do catálogo, será possível ver onde o recurso estará disponível. Nem todos os recursos listados no catálogo estão disponíveis em todas as regiões. 

Depois que você clica no tile para o recurso que deseja criar, é possível selecionar em qual local você deseja implementar. 

  * Para recursos do Cloud Foundry, é possível selecionar uma região específica e depois selecionar a organização e o espaço aos quais designar a instância de serviço.
  * Para recursos gerenciados pelo {{site.data.keyword.cloud_notm}} Identity and Access Management (IAM), você seleciona um local no qual implementar. Em seguida, você seleciona um grupo de recursos ao qual designar a instância de serviço.

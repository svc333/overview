---


copyright:
  years: 2015, 2019
lastupdated: "2019-01-29"

keywords: ui, components, using the console

subcollection: overview

---

{:shortdesc: .shortdesc}
{:tip: .tip}
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

Ao efetuar login no {{site.data.keyword.cloud_notm}}, a primeira página que pode ser visualizada é o painel, que
mostra os widgets que resumem o status da sua conta. Em seguida, é possível gerenciar seus recursos. Acesse o ícone Menu ![Ícone Menu](../icons/icon_hamburger.svg) &gt; **Lista de recursos** para visualizar todos os recursos existentes em sua conta.

  * Use o link **Catálogo** para criar novos recursos.
  * Use o link **Docs** para acessar informações úteis sobre o {{site.data.keyword.cloud_notm}}.
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

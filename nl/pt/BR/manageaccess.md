---

copyright:

  years: 2017, 2018

lastupdated: "2018-04-12"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}

# Gerenciando acesso no {{site.data.keyword.Bluemix_notm}}
{: #cloudaccess}

## O que é gerenciamento de acesso?

O gerenciamento de acesso permite controlar quais usuários veem, criam, usam e gerenciam recursos em sua conta. Para conceder acesso, é possível designar funções que permitem aos usuários níveis de acesso para concluir tarefas de gerenciamento de plataforma e acessar recursos da conta.

A maneira como você gerencia o acesso no {{site.data.keyword.Bluemix_notm}} depende do tipo de recurso ao qual deseja designar o acesso. O {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) é o sistema de gerenciamento de acesso para gerenciar recursos de forma consistente na plataforma {{site.data.keyword.Bluemix_notm}}. 
A infraestrutura do {{site.data.keyword.Bluemix_notm}} e os recursos do Cloud Foundry não são gerenciados
usando o Cloud IAM. Esses tipos de recursos têm seus próprios sistemas de gerenciamento de acesso. Se houver uma combinação de tipos de recursos, você gerenciará cada tipo separadamente. 
Para [designação de acesso aos recursos de sua
infraestrutura](/docs/iam/infrastructureaccess.html#infrapermission), você configura permissões em sua conta do SoftLayer. Para
[designação de acesso aos recursos do Cloud Foundry](/docs/iam/cfaccess.html#cfaccess), use
a opção Designar do Cloud Foundry na seção Identidade e Acesso do console.

## Quem tem permissão para gerenciar o acesso?

Como um proprietário da conta, é possível gerenciar o acesso a todos os recursos em sua conta. Também é possível delegar a tarefa de gerenciamento de acesso aos recursos de plataforma designando a um usuário em sua conta a função de administrador para todos os serviços.

Se você tiver serviços do Cloud Foundry em sua conta, será possível designar a outro usuário a função de gerenciador de organização ou espaço para que ele inclua usuários e designe funções de usuário do Cloud Foundry para acessar instâncias na organização ou espaço que ele gerencia.


## Como iniciar o gerenciamento de acesso?

Acesse **Gerenciar** &gt; **Segurança** &gt; **Identity and Access** e, em seguida, selecione **Usuários** para iniciar o gerenciamento de acesso para usuários em sua conta. Selecione um usuário da lista para começar. 
São exibidas apenas as opções de gerenciamento de acesso para as quais você tem permissão para gerenciar. Por exemplo, se você não for o proprietário da conta e não for um gerenciador de organização ou espaço, não verá a opção para gerenciar o acesso ao Cloud Foundry.

As funções de acesso também podem ser designadas a apps e serviços usando IDs de serviço. Acesse a página **IDs de serviço** para começar. Para obter mais informações sobre como deixar o Cloud IAM funcionando rapidamente, siga as etapas no [Tutorial de introdução](/docs/iam/quickstart.html#getstarted).

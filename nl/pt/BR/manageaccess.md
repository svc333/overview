---

copyright:

  years: 2017, 2019

lastupdated: "2018-03-14"

keywords: users level of access, user control, access control, permissions

subcollection: overview

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}

# Gerenciando acesso no {{site.data.keyword.Bluemix_notm}}
{: #cloudaccess}

O gerenciamento de acesso permite controlar quais usuários veem, criam, usam e gerenciam recursos em sua conta. Para conceder acesso, é possível designar funções que permitem aos usuários níveis de acesso para concluir tarefas de gerenciamento de plataforma e acessar recursos da conta.
{: shortdesc}

A maneira como você gerencia o acesso no {{site.data.keyword.Bluemix_notm}} depende do tipo de recurso ao qual deseja designar o acesso. O {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) é o sistema de gerenciamento de acesso usado para gerenciar consistentemente os recursos que são organizados em um grupo de recursos na plataforma {{site.data.keyword.Bluemix_notm}}. Os
recursos de infraestrutura clássica e do Cloud Foundry não são gerenciados usando o Cloud IAM. Esses tipos de recursos têm seus próprios sistemas de gerenciamento de acesso. 

Se houver uma combinação de tipos de recursos, você gerenciará cada tipo separadamente. Para designar acesso aos
[recursos da infraestrutura clássica](/docs/iam/infrastructureaccess.html#infrapermission), configure
as permissões em **Gerenciar** > **Acessar (IAM)** na guia Infraestrutura clássica
para o usuário ao qual deseja designar acesso. Para designar acesso aos
[recursos do Cloud Foundry](/docs/iam/cfaccess.html#cfaccess), designe usuários para as organizações e
configure as funções de acesso de organização e de espaço do Cloud Foundry em **Gerenciar** >
** Acessar (IAM)** na guia do Cloud Foundry para o usuário ao qual deseja designar acesso.

## Permissões para gerenciamento de acesso
{: #perms-manageaccess}

Como um proprietário da conta, é possível gerenciar o acesso a todos os recursos em sua conta. Também é possível delegar
a tarefa de gerenciamento de acesso aos recursos da plataforma designando a um usuário em sua conta a função de
administrador para todos os serviços, apenas para o serviço específico ou para o grupo de recursos que você deseja que
esse usuário gerencie.

Se você tiver serviços do Cloud Foundry em sua conta, será possível designar a outro usuário a função de
gerenciador da organização ou do espaço para que ele inclua usuários e designe funções do Cloud Foundry para acessar
instâncias na organização ou no espaço gerenciado por eles.


## Introdução
{: #cloudaccess-getstarted}

Acesse **Gerenciar** &gt; **Acessar (IAM)**e, então, selecione
**Usuários** para começar a gerenciar o acesso para os usuários na sua conta. Selecione um usuário da lista para começar. São exibidas apenas as opções de gerenciamento de acesso para as quais você tem permissão para gerenciar. Por exemplo, se você não for o proprietário da conta e não for um gerenciador de organização ou espaço, não verá a opção para gerenciar o acesso ao Cloud Foundry.

Também é possível designar funções de acesso para apps e serviços usando IDs de serviço. Acesse a página **IDs de serviço** para começar. Para
obter mais informações sobre como iniciar rapidamente com o Cloud IAM, consulte o
[Tutorial de introdução](/docs/iam/quickstart.html#getstarted).

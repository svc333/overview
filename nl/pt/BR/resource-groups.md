---

copyright:
  years: 2017, 2018
lastupdated: "2018-10-11"

---

{:shortdesc: .shortdesc}

# Organizando recursos em grupos de recursos
{: #whatis}

Um grupo de recursos é uma maneira de você organizar os
[recursos](/docs/resources/acct_resources.html#resource) da sua conta em agrupamentos customizáveis para que possa designar rapidamente o acesso aos usuários a mais de um recurso por vez. Qualquer recurso de conta que é gerenciado usando o controle de acesso do
{{site.data.keyword.Bluemix}} Identity and Access Management (IAM) pertence a um
grupo de recursos em sua conta. Ao incluir um novo recurso em sua conta do catálogo, é possível designar o recurso a um grupo de recursos. A
única exceção é o Kubernetes, que não solicita uma designação de grupo de recursos, mas o acesso ao serviço é controlado
usando as funções do IAM.

Os serviços que são gerenciados usando o {{site.data.keyword.Bluemix}} IAM e pertencem a um grupo de recursos
têm vários benefícios, incluindo a capacidade de se conectar a apps e serviços em qualquer espaço do Cloud Foundry, o que permite conectar apps e serviços de diferentes locais. Como
os grupos de recursos não têm o escopo definido pela localização, é possível fornecer apps e serviços de
diferentes locais para o mesmo grupo de recursos. Você também tem a capacidade de usar o controle de acesso de baixa granularidade para uma instância individual em um grupo de recursos.

Para obter mais informações sobre como trabalhar com grupos de recursos, consulte [Gerenciando grupos de recursos](/docs/resources/resourcegroups.html). E, se o uso dos grupos de recursos é novo para você, verifique as [Melhores práticas para organizar os recursos em grupos de
recursos](/docs/resources/bestpractice_rgs.html#bp_resourcegroups).

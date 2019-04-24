---

copyright:
  years: 2017, 2019
lastupdated: "2019-01-04"

---

{:shortdesc: .shortdesc}

# Organizando recursos em grupos de recursos
{: #whatis}

Um grupo de recursos é uma maneira de organizar os [recursos](/docs/resources/acct_resources.html#resource) de sua conta em agrupamentos customizáveis para que seja possível designar rapidamente aos usuários acesso a mais de um recurso de cada vez. Qualquer recurso de conta que é gerenciado usando o controle de acesso do {{site.data.keyword.Bluemix}} Identity and Access Management (IAM) pertence a um grupo de recursos em sua conta. Quando você inclui um recurso em sua conta por meio do catálogo, é possível designar o recurso a um grupo de recursos. A
única exceção é o Kubernetes, que não solicita uma designação de grupo de recursos, mas o acesso ao serviço é controlado
usando as funções do IAM.

Os serviços gerenciados pelo uso do IAM do {{site.data.keyword.Bluemix_notm}} e que pertencem a um grupo de recursos têm vários benefícios. Alguns dos benefícios incluem a capacidade de se conectar a apps e serviços em qualquer espaço do Cloud Foundry, o que significa que é possível conectar apps e serviços por meio de locais diferentes. Como
os grupos de recursos não têm o escopo definido pela localização, é possível fornecer apps e serviços de
diferentes locais para o mesmo grupo de recursos. Também é possível usar o controle de acesso de baixa granularidade até uma instância individual dentro de um grupo de recursos.

Para obter mais informações sobre como trabalhar com grupos de recursos, consulte [Gerenciando grupos de recursos](/docs/resources/resourcegroups.html). E, se o uso dos grupos de recursos é novo para você, verifique as [Melhores práticas para organizar os recursos em grupos de
recursos](/docs/resources/bestpractice_rgs.html#bp_resourcegroups).

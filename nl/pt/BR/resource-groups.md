---

copyright:
  years: 2017, 2019
lastupdated: "2019-02-19"

---

{:shortdesc: .shortdesc}

# Organizando recursos em grupos de recursos
{: #whatis-rgs}

Um grupo de recursos é uma maneira de organizar seus recursos de conta em agrupamentos customizáveis para que seja possível designar rapidamente acesso aos usuários para mais de um recurso por vez. Qualquer recurso de conta que é gerenciado usando o controle de acesso do {{site.data.keyword.Bluemix}} Identity and Access Management (IAM) pertence a um grupo de recursos em sua conta. Quando você inclui um recurso em sua conta por meio do catálogo, é possível designar o recurso a um grupo de recursos. A
única exceção é o Kubernetes, que não solicita uma designação de grupo de recursos, mas o acesso ao serviço é controlado
usando as funções do IAM.

Os serviços gerenciados pelo uso do IAM do {{site.data.keyword.Bluemix_notm}} e que pertencem a um grupo de recursos têm vários benefícios. Alguns dos benefícios incluem a capacidade de se conectar a apps e serviços em qualquer espaço do Cloud Foundry, o que significa que é possível conectar apps e serviços por meio de locais diferentes. Como
os grupos de recursos não têm o escopo definido pela localização, é possível fornecer apps e serviços de
diferentes locais para o mesmo grupo de recursos. Também é possível usar o controle de acesso de baixa granularidade até uma instância individual dentro de um grupo de recursos.

Para obter mais informações sobre como trabalhar com grupos de recursos, consulte [Gerenciando grupos de recursos](/docs/resources?topic=resources-rgs). 

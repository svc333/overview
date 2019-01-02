---


copyright:
  years: 2016, 2018
lastupdated: "2018-11-30"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# O que é a plataforma {{site.data.keyword.Bluemix_notm}}?
{: #whatis}

A plataforma em nuvem da IBM combina a plataforma como um serviço (PaaS) com a infraestrutura como um serviço (IaaS) para fornecer uma experiência integrada. 
A plataforma escala e suporta pequenas equipes de desenvolvimento e organizações e grandes empresas corporativas. Globalmente
implementada em data centers em todo o mundo, a solução que você constrói no {{site.data.keyword.cloud}} inicia
rapidamente e é executada de forma confiável em um ambiente testado e suportado no qual é possível confiar.
{: .shortdesc}

A plataforma {{site.data.keyword.Bluemix_notm}} é composta de múltiplos componentes que funcionam juntos para
fornecer uma experiência de nuvem consistente e confiável. 

  * Um catálogo que consiste em centenas de ofertas do {{site.data.keyword.Bluemix_notm}}
  * Um console robusto que funciona como o front-end para criar, visualizar e gerenciar os recursos em nuvem
  * Um componente de gerenciamento de acesso e identidade que autentica os usuários com segurança para ambos os serviços de
plataforma e controla o acesso aos recursos de forma consistente no {{site.data.keyword.Bluemix_notm}}
  * Um mecanismo de procura e identificação para filtragem e identificação dos recursos
  * Um sistema de gerenciamento de conta e faturamento que fornece o uso exato para os planos de precificação e proteção
segura contra fraude de cartão de crédito

## Escolhendo o ambiente de hospedagem
{: #choose-compute}

Com o {{site.data.keyword.Bluemix_notm}}, não é mais necessário fazer grandes investimentos em hardware para testar ou executar um novo app. Em vez disso, nós gerenciamos tudo por você e cobramos apenas pelo que você usa. O
ambiente do servidor em nuvem é a base da camada de infraestrutura. É possível escolher uma única opção ou uma combinação para ambientes mais complexos. 

Há várias opções para hospedar os apps, o que dá a você o máximo controle sobre a infraestrutura conforme você
deseja ou precisa. É possível executar o app de uma das maneiras a seguir:

  * Como uma função sem servidor
  * Como um app do Cloud Foundry
  * Como um contêiner do Docker em um cluster do Kubernetes
  * Como uma VMware
  * Como uma máquina virtual
  * Em {{site.data.keyword.baremetal_short}} de alto desempenho 

{{site.data.keyword.baremetal_short}} são servidores físicos de locatário único dedicados a um único cliente. Você
controla quase tudo por meio do host do servidor para os dispositivos de RAM e de armazenamento. Esses servidores são
usados com cargas de trabalho que requerem potência de cálculo por um tempo sustentável, por exemplo, vários
meses. 

O {{site.data.keyword.BluVirtServers_short}} pode ser implementado como instâncias públicas ou dedicadas. Com
as instâncias públicas, os recursos do servidor são compartilhados com outros clientes, também conhecidas como um
ambiente de diversos locatários. As instâncias privadas dedicam os recursos do servidor físico a um cliente que pode ter uma ou mais máquinas virtuais no mesmo servidor. Esses
servidores são ideais para cargas de trabalho executadas por um tempo limitado, por exemplo, algumas semanas. Alguns exemplos de carga de trabalho são desenvolvimento e teste, backup e recuperação e recuperação de desastre. Para obter mais informações sobre as opções do servidor, consulte [Servidores bare metal versus servidores virtuais: escolhendo a melhor opção para você](https://www.ibm.com/blogs/bluemix/2018/06/bare-metal-virtual-servers-works/){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo").

Consulte a tabela a seguir para obter um resumo das opções de cálculo.

| Opção | Descrição | 
|--------|---------------|
| [{{site.data.keyword.baremetal_short}}](/docs/bare-metal/about.html)  | Servidores de locatário único, por hora ou mensais, que são dedicados a você e não compartilhados em nenhuma parte, incluindo os recursos do servidor, com outros clientes. |
| [{{site.data.keyword.BluVirtServers_short}}](/docs/vsi/vsi_about.html) | Servidores virtuais escaláveis que são comprados com núcleos dedicados e alocações de memória. |
| [{{site.data.keyword.vmwaresolutions_short}}](/docs/services/vmwaresolutions/vmonic/prod_overview.html) | Integração ou migração rápida e contínua das cargas de trabalho do VMware no local usando infraestrutura escalável,
segura e de alto desempenho e a tecnologia de virtualização híbrida do VMware líder do mercado. |
| [{{site.data.keyword.containerlong_notm}}](/docs/containers/cs_why.html) | Combina os contêineres do Docker, a tecnologia do Kubernetes, uma experiência de usuário intuitiva e a segurança e o
isolamento integrados para automatizar a implementação, a operação, o ajuste de escala e o monitoramento de apps
armazenados em contêiner em um cluster de hosts de cálculo. |
| [{{site.data.keyword.cfee_full_notm}}](/docs/cloud-foundry/index.html) | Instanciação de múltiplas plataformas Cloud Foundry isoladas de classificação corporativa sob demanda. |
| [{{site.data.keyword.openwhisk_short}}](/docs/openwhisk/index.html) | Uma plataforma de programação Functions-as-a-Service (FaaS) baseada no Apache OpenWhisk. |
{: caption="Tabela 1. Opções de cálculo" caption-side="top"}

## Construindo aplicativos
{: #build-apps}

Se você tem [código existente](/docs/apps/tutorials/tutorial_byoc.html) que deseja modernizar e trazer
para a nuvem ou está desenvolvendo um [aplicativo
novo](/docs/apps/tutorials/tutorial_starter-kit.html), seus desenvolvedores podem acessar o ecossistema disponível de serviços e estruturas de tempo de execução
que cresce continuamente no {{site.data.keyword.Bluemix_notm}}.

[Guias de programação](https://cloud.ibm.com/docs/home/build){: new_window}
![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo") estão
disponíveis por linguagem para ajudá-lo a iniciar. Há muitas opções para hospedar os apps com a infraestrutura
do {{site.data.keyword.Bluemix_notm}} por meio do {{site.data.keyword.baremetal_short}} para executar
como uma função sem servidor.

## Conectando serviços
{: #connect-services}

Com mais de 190 serviços para escolher no catálogo, é possível construir uma solução customizada para atender
às suas necessidades. Também é possível facilmente conectar os serviços aos apps fora do
{{site.data.keyword.Bluemix_notm}}, caso isso se ajuste ao seu caso de uso. É possível gerar um novo conjunto de credenciais para os casos em que você deseja conectar manualmente um consumidor externo a um serviço do {{site.data.keyword.Bluemix_notm}}. Por
exemplo, se você está tentando conectar um app fora do {{site.data.keyword.Bluemix_notm}} a um serviço do
Watson, gere uma nova credencial para conectá-los. É simples assim! Para obter mais informações, consulte [Incluindo uma credencial](/docs/resources/service_credentials.html#service_credentials).

## Configurando sua conta

Se você está apenas tentando sair do {{site.data.keyword.Bluemix_notm}}, é possível ir diretamente para o
catálogo e começar a verificar os serviços que gostaria de explorar e incluir em sua conta para Teste ou Lite. No entanto, se
você está pronto para começar com um ambiente para um grupo de desenvolvedores ou uma organização inteira e
colocar os apps em execução na produção, considere configurar o básico em sua conta:

* Grupos de acesso de usuário para organizar os usuários e os IDs de serviço em uma entidade para tornar a designação de
acesso um processo aperfeiçoado.
* Grupos de recursos para organizar os recursos para tornar a designação de acesso a um conjunto de recursos rápida e
fácil.
* Políticas de acesso para os grupos de acesso ou desenvolvedores individuais que precisam de políticas de acesso do IAM
ou das funções de organização e de espaço do Cloud Foundry.

Para obter mais informações, consulte as [melhores práticas
para configurar a conta](/docs/account/bp_account.html#account_setup) e [melhores práticas para designar acesso](/docs/iam/bp_access.html). Além
disso, se você está pronto para entrar de cabeça, confira as peças e as partes da [hierarquia da conta](/docs/account/account_overview.html#overview).

## Precificação e faturamento

Independentemente de seu tipo de conta, é possível explorar o {{site.data.keyword.Bluemix_notm}} usando os
planos Lite para os serviços que fornecem cota grátis. Quando você estiver escolhendo um serviço no catálogo e
selecionar um bloco, se houver diferentes tipos de planos disponíveis, será possível ver detalhes sobre as informações de
precificação. Se você escolher um plano de serviço com um plano pago, será possível estimar os custos usando a
ferramenta Estimador de custo. Para obter mais informações, consulte [Estimando os custos](/docs/billing-usage/estimating_costs.html#cost).

O faturamento do {{site.data.keyword.Bluemix_notm}} fornece múltiplos serviços que asseguram que a
plataforma {{site.data.keyword.Bluemix_notm}} possa gerenciar com segurança a precificação, as contas, o uso e mais.

### Gerenciamento de conta do {{site.data.keyword.Bluemix_notm}}
{: #account}

O gerenciamento de conta mantém o relacionamento de faturamento com o cliente. Cada conta é uma entidade de faturamento que representa um cliente. Esse
serviço controla o ciclo de vida da conta, a assinatura da conta, o relacionamento com o usuário da conta e a organização da conta.

### Precificação do {{site.data.keyword.Bluemix_notm}}
{: #pricing}

O serviço de plataforma de precificação do {{site.data.keyword.Bluemix_notm}} ajuda os usuários a definir,
gerenciar e recuperar as informações de preço dos recursos no catálogo do {{site.data.keyword.Bluemix_notm}}.

### Coletor de medição do {{site.data.keyword.Bluemix_notm}}
{: #metering}

A medição de uso do {{site.data.keyword.Bluemix_notm}} é um serviço de plataforma que permite que os provedores
de serviços enviem as métricas coletadas para as instâncias de recursos que são fornecidas pelos usuários do
{{site.data.keyword.Bluemix_notm}}. Os provedores de serviços de terceiro que entregam um serviço de faturamento integrado no {{site.data.keyword.Bluemix_notm}} são necessários para enviar o uso para todas as instâncias de serviço ativas a cada hora. O
envio é importante porque a incapacidade de relatar o uso pode levar à perda de coleta de renda para a IBM que, por sua
vez, causa a perda de participação de renda para o provedor de serviços de terceiro.

## {{site.data.keyword.Bluemix_notm}}  Gerenciamento de Identidade e Acesso (IAM)
{: #iam}

O {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) permite que você
autentique usuários com segurança para os serviços de plataforma e controle o acesso aos recursos de forma
consistente na plataforma. {{site.data.keyword.Bluemix_notm}} Para obter mais detalhes, consulte [O que é IAM?](/docs/iam/index.html) O
IAM fornece comandos da CLI e APIs que ajudam a gerenciar os tokens, os grupos de acesso e as políticas.


## Criando recursos
{: #provisioning-layer}

O controlador de recurso é a camada de fornecimento da plataforma {{site.data.keyword.Bluemix_notm}} de próxima geração que gerencia o ciclo de vida de recursos do {{site.data.keyword.Bluemix_notm}} em uma conta do cliente. Os
recursos são fornecidos globalmente em um escopo de conta. O controlador de recurso suporta o fornecimento síncrono e assíncrono de recursos. A camada de fornecimento é responsável por controlar e rastrear o ciclo de vida de recursos em uma conta do cliente. Os
recursos são componentes físicos ou lógicos que podem ser fornecidos ou reservados para um aplicativo ou
instância de serviço. Exemplos de recursos incluem bancos de dados, contas e processadores, memória e limites de armazenamento. Em geral, os
recursos controlados pela camada de fornecimento destinam-se a associar as métricas de uso e o faturamento, mas esse nem sempre é o
caso. Em alguns casos, o recurso pode ser associado à camada de fornecimento para assegurar que o ciclo de vida de recurso possa ser gerenciado junto com o ciclo de vida da conta. O controlador de recurso usa o IAM para autenticação e autorização de ações que são tomadas com relação à camada de fornecimento.

### Gerenciamento de ciclo de vida de recurso
{: #lifecycle}

O controlador de recurso fornece APIs comuns para controlar o ciclo de vida de recursos desde o fornecimento (criação de uma
instância) até a ligação (criação de credenciais de acesso), a desvinculação (remoção do acesso) e a remoção do
fornecimento (exclusão de uma instância).

O controlador de recurso fornece APIs para ajudar a gerenciar os seguintes elementos do ciclo de vida do recurso:
* Fornecimento
* Atualizando uma instância de recurso
* Ligação
* Chaves de recursos
* Desvinculando
* Desprovimento


## Gerenciando os recursos
{: #resource-manager}


O gerenciador de recursos do {{site.data.keyword.Bluemix_notm}} gerencia a coleção de recursos por
[grupos de recursos](/docs/overview/resource-groups.html#whatis). Um grupo de recursos pertence a uma conta. Todos
os recursos do {{site.data.keyword.Bluemix_notm}} devem ser fornecidos dentro de um grupo de recursos. Se uma conta for suspensa, o grupo de recursos correspondente também será suspenso e todos os recursos no grupo de recursos serão suspensos. Quando um usuário cria uma conta, um grupo de recursos padrão é criado na conta. Todos
os recursos ativados para IAM do {{site.data.keyword.Bluemix_notm}} devem ser fornecidos dentro de um grupo de recursos. Se uma conta for suspensa, o grupo de recursos correspondente também será suspenso e todos os recursos no grupo de recursos serão suspensos. Para a conta padrão, um usuário pode ter somente um grupo de recursos. Para uma conta da assinatura ou pré-paga, um usuário tem permissão para criar mais de um grupo de recursos. 


## Catálogo do {{site.data.keyword.Bluemix_notm}}
{: #catalog}

O catálogo do {{site.data.keyword.Bluemix_notm}} armazena as definições de oferta (descrição, recursos, imagens, URLs e assim por diante) dos recursos que são exibidos no console do {{site.data.keyword.Bluemix_notm}}. O
serviço de catálogo gerencia as ofertas pelas geografias como o sistema de registro. O catálogo suporta CLIs e uma API
de RESTful na qual é possível recuperar informações sobre as ofertas existentes e criar, gerenciar e excluir suas
ofertas. Inicie com a URL base e use os terminais para recuperar metadados sobre os serviços no catálogo e gerenciar a
visibilidade do serviço. Dependendo do tipo de objeto, os metadados podem incluir informações sobre precificação, fornecimento, regiões e mais. Para obter mais informações, consulte [Gerenciando a documentação do catálogo](/docs/overview/catalog.html#global-catalog-overview).

## Procurando e identificando recursos
{: #search-and-tag}

O serviço de procura é um repositório de propriedades do recurso global e compartilhado que é integrado na plataforma {{site.data.keyword.Bluemix_notm}}. Ele
é usado para armazenar e procurar os atributos do recurso em nuvem. Ele categoriza e classifica os recursos. Um recurso é controlado e de propriedade dos provedores de recursos na plataforma {{site.data.keyword.Bluemix_notm}}, como o Cloud Foundry, o IBM Containers ou o Resource Controller. Os
recursos são identificados exclusivamente por um identificador [Cloud Resource
Name](/docs/overview/crn.html#crn) (CRN). As propriedades de um recurso incluem as tags e as propriedades do sistema. Ambas as propriedades são
definidas dentro de uma conta de faturamento do {{site.data.keyword.Bluemix_notm}} e abrangem muitas regiões.

Esse serviço também gerencia as tags associadas a um recurso. É possível criar, excluir, procurar, anexar ou
remover as tags com a API de identificação. A tags são identificadas exclusivamente por um identificador Cloud
Resource Naming (CRN). As tags têm um nome, que deve ser exclusivo em uma conta de faturamento. É possível criar tags
no formato do rótulo ou `key:value`.


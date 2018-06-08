---

copyright:
  years: 2016, 2017, 2018
lastupdated: "2018-05-02"

---
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}
{:tip: .tip}

# Explorar a jornada do desenvolvedor no {{site.data.keyword.cloud_notm}}
{: #dev-journey}

Como um desenvolvedor, o {{site.data.keyword.cloud}} tem um conjunto de recursos que permite iniciar a construção de apps em minutos. Em nossos painéis de desenvolvedor, é possível:

* Selecionar kits do iniciador que são específicos do caso de uso e produzir apps de iniciador prontos para produção em uma variedade de linguagens de programação e padrões arquiteturais
* Ver e gerenciar recursos que foram provisionados automaticamente de seu kit do iniciador ou que você incluiu manualmente em seu app
* Obter código de app móvel que permite implementar vários ambientes de nuvem
* Criar uma [cadeia de ferramentas do DevOps](../services/ContinuousDelivery/index.html#cd_getting_started) com alguns cliques.
* Use uma [interface da linha de comandos](/docs/cli/idt/index.html) para desenvolvimento local

Para entender como a experiência do desenvolvedor do {{site.data.keyword.cloud_notm}} pode ajudá-lo a construir rapidamente apps prontos para produção de alta qualidade, vamos ver esses elementos em mais detalhes.

## Painéis do desenvolvedor
{: #dev-dashboards}

O {{site.data.keyword.cloud_notm}} tem painéis do desenvolvedor em diferentes áreas de interesse (como Watson, Segurança ou Finanças) ou um canal digital (como Dispositivo móvel ou aplicativos da web). É possível acessar esses painéis no **Ícone Menu** ![Ícone Menu](../icons/icon_hamburger.svg).

Cada painel do desenvolvedor fornece kits do iniciador relevantes para área de foco do painel e oferece um fluxo de trabalho consistente e intuitivo que permite criar um app pronto para produção de trabalho em funcionamento em minutos.

## Apps
{: #app-projects}

Um app inclui código, dados, serviços e cadeias de ferramentas. Por exemplo, o app móvel do {{site.data.keyword.cloud_notm}} contém código de dispositivo junto com a lógica de backend, armazenamento de dados, analítica e serviços de segurança e é configurado para entrega contínua.

![Reutilizar](images/garage_reuse2.png "A experiência do desenvolvedor permite reutilizar e evitar a reinvenção")

É possível criar e gerenciar um app usando qualquer painel do desenvolvedor do {{site.data.keyword.cloud_notm}} ou o {{site.data.keyword.dev_cli_notm}}.

## Kits iniciadores
{: #starter-kits}

Com os kits do iniciador, o {{site.data.keyword.cloud_notm}} monta um app de produção de estrutura básica, na linguagem de sua escolha, pronto para implementação na nuvem. Cada kit do iniciador inclui uma linguagem, uma estrutura e um padrão para um caso de uso específico e permite reutilizar o código.

### O quanto os kits do iniciador são diferentes das amostras?
Os kits do iniciador estão prontos para produção e focam em demonstrar uma implementação padrão de chave usando um tempo de execução (por exemplo, Node.js e Express). Em alguns casos, os kits do iniciador oferecem uma experiência do usuário simples para destacar a integração do serviço. Em outros casos, os kits do iniciador representam uma implementação customizável de um caso de uso sofisticado.

* Um **fragmento** consiste em algumas linhas de código frequentemente apresentadas em um IDE. Os fragmentos ajudam um desenvolvedor a integrar-se a uma sintaxe de linguagem de programação ou a suportar a integração com uma API definida.
* Uma **demo** é geralmente de alta qualidade e fidelidade e usa um intervalo de serviços e pontos de integração. Ela geralmente requer tempo de configuração e é usada para provar um problema de negócios ou demonstrar um recurso de plataforma. Ela é usada para avaliar estágios de adoção de nuvem. Às vezes, seu código é incluído no código de produção.
* Uma **amostra** é um pequeno exemplo de um recurso específico, uma função, um serviço ou uma jornada do usuário. Uma amostra pode ser reutilizada ou incluída em um aplicativo de produção. Ela é geralmente usada para mostrar recursos técnicos e uma abordagem possível para solucionar um problema técnico.
* **Kit do iniciador** é um padrão pronto para produção que pode ser integrado com um conjunto de serviços para gerar um ativo pronto para produção que pode ser implementado diretamente em um pipeline do DevOps e um cluster do Kubernetes. Um kit do iniciador contém metadados descritivos que fornecem ao usuário informações suficientes para saber o que o kit é ou faz. Ele também contém instruções que indicam ao {{site.data.keyword.cloud_notm}} o que produzir. A saída está pronta para produção e pronta para utilização e pode ser iterada por aprimoramentos adicionais, com base nas melhores práticas da IBM. O conteúdo do kit do iniciador não é tão complexo como uma demonstração e não tão trivial como um fragmento ou amostra. Ele é criado dinamicamente com base nos requisitos do desenvolvedor.

## Recursos autoprovisionados
{: #auto-provision}

Se um kit do iniciador especifica os recursos necessários, o {{site.data.keyword.cloud_notm}} cria automaticamente as instâncias desses recursos quando você cria seu app. Observe que também é possível provisionar os recursos manualmente ou selecionar instâncias de recursos existentes para incluir em seu app após ele ser criado. É possível ver uma lista de instâncias de serviço associadas ao seu app na visualização Detalhes do app juntamente com as credenciais, no caso de precisar delas.

## Código móvel
{: #portable-code}

Criar um app de um kit do iniciador cria o código automaticamente para você que tem formato consistente e é agnóstico de execução. É possível implementar o código em seu ambiente de escolha, por exemplo, Kubernetes ou Cloud Foundry, sem fazer mudanças.

### Qual código é criado?
O código criado em um kit do iniciador do {{site.data.keyword.cloud_notm}} tem quatro componentes fundamentais: lógica de caso de uso, componentes de linguagem, ativação do serviço e ativação de nuvem. Gerar esses componentes economiza seu tempo valioso e assegura que você esteja usando a melhor arquitetura da classe.

* **Lógica de caso de uso** fornece funções para a função principal de um caso de uso específico. Os exemplos podem ser código para um robô de bate-papo do Watson Conversation ou código para um app de reconhecimento visual móvel.
* **Componentes de linguagem** são componentes de código e arquivos específicos para a linguagem de programação que você seleciona para o seu kit do iniciador. Por exemplo, os programadores do node.js precisarão de um arquivo package.json para gerenciamento de dependência e esse arquivo é criado automaticamente para você.
* **Ativação de serviço** é o código que permite que seu app se conecte e use os serviços que você inclui. O gerenciamento de credencial, o código de inicialização e os SDKs específicos do serviço são exemplos de itens de ativação de serviço.
* **Ativação de nuvem** é o código que permite que seu app seja executado no {{site.data.keyword.cloud_notm}}. Por exemplo, os gráficos Helm que permitem que seu app seja executado em um cluster do Kubernetes do {{site.data.keyword.cloud_notm}}.

Ao criar um app por meio de um kit do iniciador do {{site.data.keyword.cloud_notm}}, seu app iniciará com arquitetura comprovada que também reflete as melhores práticas para a linguagem selecionada.

Cada aplicativo inclui um arquivo leia-me que contém detalhes técnicos do app e explica o que é necessário para deixar seu app em execução caso ele não seja executado pronto para utilização.
{: tip}

## Cadeia de ferramentas do DevOps
{: #devops}

O DevOps inclui procedimentos e ferramentas para acessar, desenvolver, implementar e operar seu app. Uma cadeia de ferramentas do DevOps é um conjunto de serviços vinculados que automatizam suas tarefas do DevOps. É possível executar o DevOps manualmente com apps muito simples, mas a necessidade de automação aumenta rapidamente conforme a complexidade do app aumenta e a automação de cadeia de ferramentas é uma necessidade para a entrega contínua.

O componente principal de uma cadeia de ferramentas do DevOps é um repositório de controle de versão do código como o GitHub. As ferramentas adicionais podem incluir rastreamento de lista não processada, pipeline de entrega, IDE e serviço de monitoramento como o [{{site.data.keyword.cloud_notm}}DevOps Insights](../services/DevOpsInsights/index.html#gettingstarted).

Se você criou um app usando um kit do iniciador, é possível criar uma nova cadeia de ferramentas e implementar seu app simplesmente clicando em **Implementar no Cloud** na visualização Detalhes do app. Uma cadeia de ferramentas que tem um repositório de código, repositório de problemas, pipeline de entrega e IDE da web é criada.

É possível então construir essa cadeia de ferramentas para acomodar múltiplas equipes e implementar em ambientes separados para desenvolvimento, teste e produção e estabelecer um modelo de entrega contínua colaborativa de classe corporativa para seu app.  

![Entrega contínua](images/garage_continuous_delivery2.png "A experiência do desenvolvedor configura a entrega contínua para sua ramificação de desenvolvimento")

Também é possível dar uma olhada rápida no seu código de app clicando no botão **Download** na página de visão geral do app do painel do desenvolvedor. Seu código é transferido por download como um arquivo `.zip` que contém a estrutura do código de app completa. É possível extrair facilmente o arquivo e executar o código localmente usando o {{site.data.keyword.dev_cli_notm}} ou incluí-lo em seu repositório de gerenciamento de código.

## Interface da linha de comandos
O {{site.data.keyword.dev_cli_notm}} permite codificar, construir e executar seu app localmente.  Um padrão comum é criar seu app por meio de um painel do desenvolvedor, usar o {{site.data.keyword.dev_cli_notm}} para desenvolver localmente e, em seguida, enviar por push as atualizações para seu repositório e mesclar para iniciar sua cadeia de ferramentas de implementação.

## Desenvolvimento do método Garage
{: #developer_concepts}

Veja o [Método Garage](https://www.ibm.com/cloud/garage/) para saber como a IBM pode ajudá-lo a desenvolver apps em sua organização.  

![Visão geral de fases do Método Garage](images/garage_phases_overview2.png "Visão geral de fases do Método Garage")*Visão geral de fases do Método Garage*

O {{site.data.keyword.cloud_notm}} ajuda você a produzir apps de produção de classe corporativa bem-sucedidos usando o Método Garage ou o método preferido. Para entender melhor o que o {{site.data.keyword.cloud_notm}} tem a oferecer aos desenvolvedores, vamos dar uma olhada rápida nas qualificações necessárias para construir um app moderno.

## Qualificações do desenvolvedor
{: #skills}

Hoje, os usuários esperam mais de seus aplicativos do que antes. Eles desejam que seus apps entreguem percepções profundas de dados armazenados e em tempo real, estejam sempre disponíveis e correspondam às suas necessidades individuais mais estritamente. Para atender essas expectativas, os criadores de app precisam reunir muitos conjuntos de qualificações diferentes. Por exemplo, um aplicativo cognitivo sofisticado pode requerer contribuições de desenvolvedores digitais, desenvolvedores de nuvem nativa, desenvolvedores de fluxos, cientistas de dados e especialistas do DevOps.

 ![Tipos de desenvolvedor](images/developer_skills.png "Relacionamentos do desenvolvedor")

* Os **Desenvolvedores digitais** criam um canal digital específico, como web móvel, voz e bate-papo. Os desenvolvedores digitais são geralmente focados em casos de uso e atendem diretamente às necessidades dos usuários como uma experiência abrangente.
* Os **Desenvolvedores nativos de nuvem** são especializados em construir e interconectar componentes de nuvem. Os autores de microsserviço e de backend para frontend se enquadram nessa categoria.
* Os **Desenvolvedores de fluxos** focam no processamento e obtêm insights de fluxos de dados. Por exemplo, um desenvolvedor de fluxos pode analisar e iniciar a ação em fluxos de texto, fala ou vídeo recebidos.
* Os **Cientistas de dados** usam analítica e aprendizado de máquina para produzir modelos preditivos. Esses modelos são usados em métricas de negócios e fornecem percepções profundas aos usuários do aplicativo.
* Os **Especialistas do DevOps** são especialistas em resolver problemas de implementação e cadeia de ferramentas. Para apps simples, especialistas dedicados geralmente não são necessários porque os membros da equipe de desenvolvimento gerenciam o DevOps com a equipe. Mas para aplicativos corporativos complexos, com muitas dependências, os especialistas do DevOps são essenciais para manter seu app de produção em execução sem problemas.

Os recursos do desenvolvedor construídos no {{site.data.keyword.cloud_notm}} se alinham a esses conjuntos de qualificações e permitem que sua equipe use uma plataforma para produzir, entregar, executar e gerenciar seu app. Por exemplo, um desenvolvedor digital que cria um app móvel pode usar o [Painel do desenvolvedor móvel](https://console.bluemix.net/developer/mobile/dashboard) do {{site.data.keyword.cloud_notm}}, um construtor de app cognitivo pode usar o [Painel do desenvolvedor do Watson](https://console.bluemix.net/developer/watson/dashboard) juntamente com o [Watson Studio](https://console.bluemix.net/catalog/services/watson-studio), um desenvolvedor de fluxos pode usar o [IBM Real-Time Analytics](../services/StreamingAnalytics/index.html#gettingstarted) e o [serviço {{site.data.keyword.cloud_notm}} Continuous Delivery](../services/ContinuousDelivery/index.html#cd_getting_started) simplifica a tarefa de um especialista do DevOps.

Pronto para iniciar? [Clique aqui](../apps/index.html) para construir um app no {{site.data.keyword.cloud_notm}} agora!

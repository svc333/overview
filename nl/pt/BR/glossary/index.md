---


copyright:
  years: 2016, 2018
lastupdated: "2018-03-19"


---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# Termos do glossário para {{site.data.keyword.cloud_notm}}
{: #glossary}

Este glossário fornece termos e definições para o {{site.data.keyword.cloud_notm}}.
{:shortdesc}

As referências cruzadas a seguir são usadas nesse glossário:

- *Consulte* o encaminha de um termo não preferencial para um termo preferencial ou de uma abreviação para a sua forma por extenso.
- *Consulte também* o encaminha para um termo relacionado ou contrastante.


Para obter outros termos e definições, consulte o [Website de terminologia da IBM](http://www-01.ibm.com/software/globalization/terminology/){: new_window}.

<!--If you do not want letter links at the top of your
glossary, delete the text between these comment tags.
[A](#glossa)
[B](#glossb)
[C](#glossc)
[D](#glossd)
[E](#glosse)
[F](#glossf)
[G](#glossg)
[H](#glossh)
[I](#glossi)
[J](#glossj)
[L](#glossl)
[M](#glossm)
[N](#glossn)
[O](#glosso)
[P](#glossp)
[R](#glossr)
[S](#glosss)
[T](#glosst)
[U](#glossu)
[V](#glossv)
[W](#glossw)

-->

## A
{: #glossa}

### token de acesso
{: #x2113001}

Um valor usado pelo consumidor para ganhar acesso aos recursos protegidos em nome do usuário, em vez de usar as credenciais do provedor de serviços do usuário.

### ação
{: #x2012974}

Um fragmento de código que pode ser chamado explicitamente ou executado em resposta a um evento. Consulte também [feed](#x3129185), [chamar](#x2057232).

### afinidade
{: #x2149238}

Duas ou mais instâncias do grupo de contêiner em execução no mesmo nó de rede. Consulte também [antiafinidade](#x8888040).

### Antiafinidade
{: #x8888040}

Duas ou mais instâncias do grupo de contêiner que são executadas em nós de rede diferentes para assegurar alta disponibilidade para um aplicativo. Consulte também
[afinidade](#x2149238).

### API
{: #x2008805}

Consulte [interface de programação de aplicativos](#x2000186).

### app
{: #x4281528}

Um aplicativo de dispositivo móvel ou da web. Consulte também o [aplicativo móvel](#x4258535), [aplicativo da Web](#x2116500).

### interface de programação de aplicativos (API)
{: #x2000186}

Uma interface que permite que um programa aplicativo escrito em uma linguagem de alto nível use dados ou funções específicos do sistema operacional ou de outro programa.

### artefato
{: #x2262995}

Uma entidade que é usada ou produzida por um processo de desenvolvimento de software ou sistemas. Exemplos de artefatos incluem designs, requisitos, arquivos de origem, planos, scripts, simulações, modelos, planos de teste e arquivos executáveis binários. Em um contexto de HTTP,
              os artefatos possuem um URI e são chamados de recursos.

### autenticação (AuthN)
{: #x2014567}

O processo de validação da identidade de um usuário ou servidor.

### AuthN
{: #x7470446}

Consulte [autenticação](#x2014567).

### autorização (AuthZ)
{: #x2014653}

Em segurança de computador, o direito concedido a um usuário para se comunicar ou usar um sistema de computador.

### AuthZ
{: #x7470448}

Consulte [autorização](#x2014653).

### Zona de disponibilidade
{: #x7018171}

Um local dentro de uma região no qual o IBM Containers é executado.


## B
{: #glossb}

### imagem base
{: #x5366487}

Uma imagem que não tem imagem pai. Veja também [imagem](#x2024928), [imagem pai](#x8439210).

### serviço beta
{: #x7470455}

Um serviço que não está pronto para produção e está em um estágio de avaliação de desenvolvimento. Consulte também [serviço experimental](#x7470450).

### ligar
{: #x2000361}

Estabelecer uma conexão entre componentes de software em uma rede usando um protocolo acordado. Em serviços da web, a operação de ligação ocorre quando o solicitante de serviço chama ou inicia uma interação com o serviço no tempo de execução usando os detalhes da ligação na descrição do serviço para localizar, contatar e chamar o serviço.

### BLU Acceleration
{: #x7470463}

Uma coleção de tecnologias IBM Db2 projetadas para funcionar primeiramente com processamento de
consulta de inteligência de negócios principalmente de leitura. A BLU Acceleration consiste em quatro principais avanços de design de banco de dados: processamento colunar dinâmico na memória, compactação acionável, processamento de vetor paralelo e data skipping.

### Implementação azul-verde
{: #x7807335}

Uma técnica de implementação que possibilita a entrega contínua e minimiza o tempo de inatividade executando dois ambientes de produção quase idênticos chamados Azul e Verde. Enquanto um dos ambientes (por exemplo, Azul) é o ambiente de produção em tempo real, o outro (por exemplo, Verde) pode ser usado para teste e implementação finais. Após o aplicativo ser implementado em Verde, o Verde se torna o ambiente de produção e o Azul se torna inativo. Veja também [implementação vermelho-preto](#x8439181).

### modelo
{: #x7233930}

Um modelo que inclui um aplicativo e seu ambiente de tempo de execução e
              serviços predefinidos associados para um domínio específico.

### sem fronteiras
{: #x8439189}

Pertencente a uma plataforma de desenvolvimento aberta sem proprietário que inclui os modelos de implementação de nuvem pública, nuvem dedicada e nuvem local. Veja também [nuvem dedicada](#x8439199), [nuvem local](#x8439194), [nuvem pública](#x4585370).

### buildpack
{: #x7233925}

Uma coleção de scripts que preparam seu código para execução no IBM Cloud. Os buildpacks examinam aplicativos implementados e, em seguida, fazem o download e configuram quaisquer aplicativos dependentes.


## C
{: #glossc}

### CA
{: #x2015942}

Consulte a [autoridade de certificação](#x2016383).

### autoridade de certificação (CA)
{: #x2016383}

Uma organização ou empresa de terceiro confiável que emite os certificados digitais. A autoridade de
certificação geralmente verifica a identidade dos indivíduos que recebem o certificado exclusivo. Consulte também [certificado intermediário](#x3753781), [Secure Sockets Layer](#x2038004), [raiz confiável](#x2042234).

### certificate signing request (CSR)
{: #x3530521}

Uma mensagem eletrônica que uma organização envia para uma autoridade de
certificação (CA) para obter um certificado. O pedido inclui uma chave
pública e recebe uma chave privada; o CA retorna o certificado depois de assinar
com sua própria chave privada.

### CLI
{: #x2008863}

Consulte [interface de linha de comandos](#x2051424).

### cliente
{: #x2000644}

Um programa de software ou computador que solicita serviços de um servidor. Consulte também [host](#x2002243).

### computação em nuvem
{: #x3877850}

Uma plataforma de computação em que os usuários podem ter acesso aos aplicativos ou aos recursos de computação, como serviços, a partir de qualquer lugar, por meio de seus dispositivos conectados. Uma interface com o usuário simplificada ou uma interface de programação de aplicativos (API), ou ambas, tornam o suporte de infraestrutura, como serviços, transparente para os usuários.

### portabilidade da nuvem
{: #x4585297}

A capacidade de mover aplicativos e serviços em ambientes de computação em nuvem pública ou privada, ou a partir de diferentes provedores em nuvem.

### interface de linha de comandos (CLI)
{: #x2051424}

Uma interface de computador em que a entrada e a saída se baseiam em texto.

### componente
{: #x2017871}

No gerenciamento de controle de fonte, um agrupamento de artefatos relacionados em um fluxo ou
                  área de trabalho do repositório. Um componente pode conter qualquer número de pastas e arquivos.

### compute
{: #x3723424}

Infraestrutura ou recursos que servem como base para construir apps na nuvem.

### container
{: #x2010901}

Uma construção do sistema que permite aos usuários executar instâncias do sistema operacional lógico separadas simultaneamente. Os contêineres usam camadas de sistemas de arquivos para minimizar os tamanhos de imagem e promover a reutilização. Veja também [imagem](#x2024928), [camada](#x2028320), [registro](#x2064940).

### credencial
{: #x2018813}

Informações adquiridas durante a autenticação, que descrevem um usuário, associações de grupos ou outros atributos de identidade relacionados à segurança, e que são usadas para executar serviços, como autorização, auditoria ou delegação. Por exemplo, um ID de usuário e uma senha são credenciais que permitem o acesso à rede e aos recursos do sistema.

### Responsável pelo atendimento ao cliente
{: #x2140147}

Consulte [pedido de
assinatura de certificado](#x3530521).

### domínio customizado
{: #x5728384}

A parte customizada da URL selecionada pelo usuário para direcionar solicitações para o aplicativo. Um domínio customizado faz parte da rota. Um domínio customizado pode ser um domínio compartilhado, um subdomínio compartilhado ou um domínio compartilhado e host. Veja também [domínio](#x2021210), [host](#x2002243), [rota](#x2037338), [subdomínio](#x2040080), [Localizador Uniforme de Recursos](#x2042491).


## D
{: #glossd}

### daemon
{: #x2019215}

Um programa que é executado de modo não assistido
para executar funções contínuas ou periódicas, como controle de rede.

### painel
{: #x2363941}

Um componente de interface com o usuário que fornece um resumo abrangente de informações pertinentes de várias origens para o usuário.

### armazenamento de dados
{: #x2052849}

Um local, como um sistema de banco de dados, arquivo ou diretório no qual os dados são armazenados.

### DEA
{: #x2019805}

Consulte [Droplet Execution Agent](#x7470348).

### nuvem dedicada
{: #x8439199}

Um ambiente de computação em nuvem particular que fornece infraestrutura com hardware de locatário único. Veja também [sem fronteiras](#x8439189).

### implementação
{: #x2104544}

Um processo que recupera a saída de uma construção, compacta a saída com propriedades de configuração e instala o pacote em um local predefinido para que ele possa ser testado ou executado. Veja também [estágio](#x2067189).

### DevOps
{: #x5784896}

Uma metodologia de software que integra desenvolvimento de aplicativo e operações de TI para que as
equipes possam entregar código mais rápido para produção e iterar continuamente com base no feedback do
mercado.

### domínio
{: #x2021210}

Parte de uma hierarquia de nomenclatura que especifica a rota. Por exemplo, example.com. No IBM Cloud,
os domínios são associados a organizações. Os objetos de domínio não são ligados diretamente a apps. Veja também [domínio customizado](#x5728384), [host](#x2002243), [organização](#x2032585), [rota](#x2037338), [subdomínio](#x2040080), [Localizador Uniforme de Recursos](#x2042491).

### droplet
{: #x7470343}

Um archive dentro do Cloud Foundry que contém um aplicativo e suas dependências de tempo de execução e de estrutura, antes da implementação na nuvem.

### Droplet Execution Agent (DEA)
{: #x7470348}

O componente Cloud Foundry que é responsável por implementar aplicativos.


## E
{: #glosse}

### terminal
{: #x2026820}

O endereço de uma API ou um serviço em um ambiente. Uma API expõe um terminal e, ao mesmo tempo, chama os terminais de outros serviços. Consulte também [rota](#x2037338).

### serviço experimental
{: #x7470450}

Um serviço que não está pronto para produção e pode ser removido da produção a qualquer momento. Consulte também [serviço beta](#x7470455).


## F
{: #glossf}

### associar
{: #x2763229}

Para mesclar duas ou mais entidades. Por exemplo, um domínio registrado da empresa poderia ser federado com um ID IBM.

### alimentação
{: #x3129185}

Uma parte de código que configura uma origem de eventos externos para disparar eventos acionadores. Consulte também [ação](#x2012974).

### compartilhamento de arquivos
{: #x2022902}

No ambiente de nuvem da IBM, um sistema de armazenamento persistente no qual os usuários armazenam e compartilham arquivos. No IBM Containers, os usuários podem montar volumes do Docker em
compartilhamentos de arquivo.

### fogo
{: #x2239904}

Para ativar um acionador.

### estrutura
{: #x2023472}

Uma arquitetura para um aplicativo que fornece uma estrutura padrão para um aplicativo, além de funcionalidade geral extensível.  Uma estrutura ativa e simplifica a implementação consistente de tecnologias complexas para desenvolvimento de aplicativo.


## G
{: #glossg}

### GB por hora
{: #x7470477}

A quantia acumulativa de memória (em gigabytes) que está sendo executada para todas as instâncias do aplicativo para um buildpack específico por hora.

### Identificador Exclusivo Global (GUID)
{: #x2390455}

Um número determinado algoritmicamente que identifica exclusivamente uma entidade em um sistema.

### GUID
{: #x2390457}

Consulte [Identificador Exclusivo Global](#x2390455).


## H
{: #glossh}

### chamada pesada de API
{: #x7690468}

Uma operação do cliente que grava, exclui ou insere dados. Chamadas pesadas de API
consomem mais recursos que as chamadas leves de API, pois elas estão afetando os dados. Consulte também [chamada leve de
API](#x7690463).

### host
{: #x2002243}

Um computador que está conectado a uma rede e que fornece um ponto de acesso a essa rede. O host pode ser um cliente, um servidor, ou ambos, cliente e servidor, simultaneamente. Consulte também [cliente](#x2000644), [domínio customizado](#x5728384), [domínio](#x2021210), [rota](#x2037338), [subdomínio](#x2040080), [Localizador Uniforme de Recursos](#x2042491).

### método de HTTP
{: #x2024674}

Uma ação usada pelo Protocolo de Transporte de Hipertexto. Os métodos de HTTP incluem GET, POST e PUT.

### HTTPS
{: #x2193603}

Consulte [Segurança de Protocolo de Transporte de Hipertexto](#x2237225).

### nuvem híbrida
{: #x4585327}

Um ambiente de computação em nuvem que consiste em diversos recursos públicos e privados.

### Protocolo de Transporte de Hipertexto Seguro (HTTPS)
{: #x2237225}

Um protocolo da Internet usado por servidores e navegadores da web para transferir e exibir documentos de hipermídia seguramente através da Internet.


## I
{: #glossi}

### IaaS
{: #x4585337}

Consulte [infraestrutura como serviço](#x4585332).

### IBM Cloud
{: #x7301758}

Uma plataforma de padrões abertos baseada em nuvem para construir, gerenciar e executar apps de todos os tipos, como web, móveis, big data e dispositivos inteligentes. Os recursos incluem Java, desenvolvimento de backend móvel e monitoramento de aplicativos, bem como recursos de parceiros de ecossistema e software livre&mdash;todos fornecidos como serviço na nuvem.

### imagem
{: #x2024928}

Um tempo de execução completo que pode ser usado para executar aplicativos. As imagens são usadas para criar contêineres e podem conter várias imagens pai (camadas). Veja também [imagem base](#x5366487), [contêiner](#x2010901), [camada](#x2028320), [namespace](#x2031005), [imagem pai](#x8439210), [repositório de imagem privada](#x8439215), [registro](#x2064940).

### infraestrutura como serviço (IaaS)
{: #x4585332}

A entrega de uma infraestrutura de computador, incluindo funcionalidade do servidor, funcionalidade de rede, funcionalidade do datacenter e funcionalidade de armazenamento como um serviço terceirizado.

### instância
{: #x2002531}

Uma entidade que consiste em recursos que são reservados para um aplicativo específico ou um serviço.

### certificado intermediário
{: #x3753781}

Um certificado subordinado que é emitido pela autoridade de certificação raiz confiável
(CA) especificamente para emitir certificados do servidor de entidade final. O resultado é uma cadeia de certificados que inicia na autoridade de certificação raiz
confiável, passa pelo certificado intermediário e termina com o
certificado SSL emitido para a organização. Consulte também [autoridade de certificação](#x2016383), [raiz confiável](#x2042234).

### Internet of Things (IoT)
{: #x6714341}

A rede global de terminais que pode capturar ou gerar dados. Por exemplo, um smartphone, relógio
inteligente e servidor de backend podem comunicar-se entre si, enviando dados de um lado para outro ou
até mesmo para dispositivos adicionais dentro da rede.

### invocar
{: #x2057232}

Para ativar uma ação. Consulte também [ação](#x2012974).

### IoT
{: #x6714346}

Consulte [Internet of Things](#x6714341).


## J
{: #glossj}

### arquivo JAR
{: #x2406009}

Um Java archive.

### JavaScript Object Notation (JSON)
{: #x3292165}

Formato leve de intercâmbio de dados baseado na notação de objeto literal de JavaScript. JSON é uma linguagem de programação neutra, mas usa convenções de diversas linguagens.

### JSON
{: #x4267096}

Consulte [JavaScript Object Notation](#x3292165).


## L
{: #glossl}

### camada
{: #x2028320}

Uma versão mudada de uma imagem pai. As imagens consistem em camadas, em que a versão é disposta em camadas na parte superior da imagem pai para criar a nova imagem. Consulte também [contêiner](#x2010901), [imagem](#x2024928).

### LDAP
{: #x2481619}

Veja [Lightweight Directory Access
Protocol](#x2028538).

### chamada leve de API
{: #x7690463}

Uma operação do cliente que somente lê dados. As chamadas leves de API usam menos recursos
que as chamadas pesadas de API, pois estão executando uma única função. Consulte também [chamada pesada de API](#x7690468).

### Lightweight Directory Access Protocol (LDAP)
{: #x2028538}

Um protocolo baseado em padrão aberto que usa o TCP/IP para fornecer acesso a diretórios que suportam um modelo X.500 e que não está sujeito aos requisitos de recursos do DAP (Directory Access Protocol) X.500 mais complexo. Por exemplo, o LDAP pode ser usado para localizar pessoas, organizações
e outros recursos na Internet ou diretório da intranet.

### nuvem local
{: #x8439194}

Um ambiente de computação em nuvem no datacenter do cliente. A nuvem local está no local, fornecendo melhor latência e segurança. Veja também [sem fronteiras](#x8439189).


## M
{: #glossm}

### MBaaS
{: #x7044865}

Consulte [backend móvel como serviço](#x7044858).

### app móvel
{: #x7636517}

Veja [aplicativo móvel](#x4258535).

### aplicativo móvel (app móvel)
{: #x4258535}

Um aplicativo que foi projetado para uma plataforma móvel. Semelhante
a aplicativos da Web, os apps móveis fornecem alguma função além da exibição
estática de informações, por exemplo, permitir que o usuário filtre notícias
praticamente em tempo real. Consulte também [app](#x4281528).

### backend móvel como serviço (MBaaS)
{: #x7044858}

Um modelo de computação que conecta aplicativos móveis a serviços de computação em nuvem e fornece recursos, como gerenciamento de usuários, notificações push e integração a redes sociais por meio de uma API e um SDK unificados.

### nuvem para dispositivo móvel
{: #x4585344}

Uma infraestrutura na qual o armazenamento e o processamento de dados para aplicativos são transferidos de um dispositivo móvel para a nuvem. Com a computação em nuvem para dispositivo móvel, os aplicativos não estão limitados a uma operadora específica, mas são acessados por meio da web.


## N
{: #glossn}

### Namespace
{: #x2031005}

Um nome exclusivo que identifica o repositório de imagem de sua organização no registro do IBM Cloud. Veja também [imagem](#x2024928), [repositório de imagem privada](#x8439215).


## O
{: #glosso}

### OAuth
{: #x6013335}

Um protocolo baseado em HTTP que oferece
aos aplicativos acesso com escopo a um recurso protegido em nome
do proprietário do recurso, criando uma interação de aprovação
entre o proprietário do recurso, o cliente e o servidor de recurso.

### on-prem
{: #x6969434}

Consulte [nos locais](#x4561212).

### nos locais (on-prem)
{: #x4561212}

Relativo ao software que é instalado e executado nos computadores locais de um usuário ou uma organização.

### org
{: #x7470494}

Consulte [organização](#x2032585).

### organização (org)
{: #x2032585}

A metodologia de agrupamento para usuários no IBM Cloud. Organizações são usadas para gerenciar cotas. Usuários em uma organização compartilham memória e cotas de instância de serviço. Consulte também [domínio](#x2021210), [espaço](#x2039442).


## P
{: #glossp}

### PaaS
{: #x2029790}

Consulte [plataforma como serviço](#x2029786).

### imagem pai
{: #x8439210}

Uma imagem que fornece uma base para outra imagem. Por exemplo, Ubuntu Linux é a imagem pai da imagem do IBM Liberty. Veja também [imagem base](#x5366487), [imagem](#x2024928).

### plataforma como serviço (PaaS)
{: #x2029786}

A entrega de uma plataforma de computação, incluindo aplicativos, middleware otimizado, ferramentas de desenvolvimento e ambientes de tempo de execução Java e Web 2.0, em um ambiente baseado em nuvem.

### nuvem particular
{: #x4585362}

Um ambiente de computação em nuvem no qual o acesso é limitado a membros de uma corporação e redes de parceiros. Veja também [nuvem pública](#x4585370).

### repositório privado de imagem
{: #x8439215}

A combinação entre o registro do IBM Cloud de uma organização e seu namespace. O repositório de imagens privada é usado ao referenciar uma imagem em um comando. Veja também [imagem](#x2024928), [namespace](#x2031005).

### chave privada
{: #x2034701}

Um padrão de algoritmo usado para criptografar mensagens que somente a chave pública
correspondente pode decriptografar. A chave privada também é usada para decriptografar mensagens que foram criptografadas pela chave pública correspondente. A chave privada é mantida no sistema do usuário e é protegida por uma senha.

### recurso privado
{: #x9439035}

Uma entrada que é visível apenas para proprietários da conta e suas contas incluídas. Quando os recursos
são criados, eles são privados por padrão. Consulte também [recurso público](#x9439040).

### serviço privado
{: #x7690456}

Um serviço que é visível somente aos membros de uma organização do IBM Cloud especificada.

### nuvem pública
{: #x4585370}

Um ambiente de computação em nuvem no qual o acesso a recursos padronizados, como infraestrutura, hardware de diversos locatários e serviços, está disponível aos assinantes em uma base de pagamento por uso. Veja também [sem fronteiras](#x8439189), [nuvem particular](#x4585362).

### recurso público
{: #x9439040}

Uma entrada que é visível para todos no catálogo do IBM Cloud. Os recursos públicos podem ser
construídos por qualquer provedor (provedores IBM ou de terceiros). Consulte também
[recurso privado](#x9439035).

### push
{: #x2035465}

Enviar informações de um servidor para um cliente. Quando um servidor envia conteúdo por push, é ele que inicia a transação, não uma solicitação do cliente.

### notificação push
{: #x5599582}

Um alerta indicando uma mudança ou uma atualização em um ícone de app móvel.


## R
{: #glossr}

### principalmente de leitura
{: #x7470468}

Referente a dados que são alterados dinamicamente.

### implementação vermelha-preta
{: #x8439181}

Uma técnica de implementação que conduz a entrega contínua, permitindo o teste, desenvolvimento e implementação sincronizados. Inicialmente, o desenvolvimento é feito em um ambiente inativo (preto) enquanto o ambiente ativo continua a tomar tráfego (vermelho). Após o início da implementação, ambos os ambientes ficam ativos (vermelho-vermelho) até que o roteamento seja desativado no ambiente da versão anterior outrora ativo e subsequentemente removido (preto) enquanto o novo ambiente serve como o único ambiente ativo. Veja também [implementação azul-verde](#x7807335).

### região
{: #x2091391}

Um território geográfico definido. Uma região poderia ser uma área de código de endereçamento postal específico, uma cidade, um estado, um grupo de estados ou até mesmo um grupo de países. Cada região pode ser ela própria um conjunto de outras regiões ou um conjunto de códigos de endereçamento postal que formam a região.

### registro
{: #x2064940}

Um repositório público ou privado que contém imagens usadas para criar contêineres. Consulte também [contêiner](#x2010901), [imagem](#x2024928).

### Representational State Transfer (REST)
{: #x3220976}

Um estilo arquitetural de software para sistemas de hipermídia distribuídos, como o World Wide Web. O termo também é sempre usado para descrever qualquer interface simples que usa XML (ou YAML, JSON, texto simples) sobre HTTP sem uma camada de sistema de mensagens adicional, como SOAP.

### recurso
{: #x2004267}

Um componente físico ou lógico que pode ser fornecido ou reservado para um aplicativo ou instância de serviço.  Exemplos de recursos incluem banco de dados, contas e processador, memória e limites de armazenamento.

### grupo de recursos
{: #x2161955}

O ambiente e as restrições que as instâncias de recurso contidas aderem. Um usuário pode ser associado a
um grupo de recursos para permitir a colaboração.

### REST
{: #x3220987}

Consulte [Representational State Transfer](#x3220976).

### rota
{: #x2037338}

A URL usada para direcionar solicitações para um aplicativo. Uma rota é composta de um host (ou subdomínio) opcional e um domínio que são especificados quando um aplicativo é enviado por push. Por exemplo, na rota myapp.example.com,
myapp é o host e example.com é o domínio. Uma rota pode ser associada com um ou mais aplicativos. A menos que
um domínio customizado seja especificado, o IBM Cloud usa um domínio compartilhado padrão na rota para seu
aplicativo. Consulte também [domínio customizado](#x5728384),
[domínio](#x2021210), [terminal](#x2026820),
[host](#x2002243), [subdomínio](#x2040080),
[Localizador Uniforme de Recursos](#x2042491).

### regra
{: #x2037526}

- Critérios que associam um acionador com uma ação, com cada disparo do acionador fazendo com que a ação correspondente seja chamada com o evento acionador como entrada.
- Um conjunto de instruções condicionais que permitem que os sistemas de computador identifiquem relacionamentos e executem respostas automatizadas adequadamente.

### tempo de execução
{: #x2391929}

O conjunto de recursos usados para executar o aplicativo. Consulte também [iniciador](#x7470511).


## S
{: #glosss}

### SaaS
{: #x4585391}

Consulte [software como serviço](#x4585386).

### escalar
{: #x2004442}

Aumentar a capacidade da plataforma (ou do sistema) incluindo mais aplicativos ou instâncias de serviço

### escopo
{: #x2037763}

Em gerenciamento de identidade, o conjunto de entidades que uma política ou um item de controle de acesso (ACI) pode afetar.

### Secure Sockets Layer (SSL)
{: #x2038004}

Um protocolo de segurança que fornece privacidade de comunicação. Com SSL, aplicativos do cliente/servidor podem se comunicar da maneira projetada para evitar espionagem, violação e falsificação de mensagem. Consulte também [autoridade de certificação](#x2016383).

### serviço
{: #x2038343}

Uma extensão da nuvem que fornece funcionalidade pronta para uso, tal como
banco de dados, sistema de mensagens e software da web para execução de código ou gerenciamento de aplicativos
ou monitoramento de recursos. Em geral os serviços não requerem instalação ou manutenção e podem ser combinados para criar aplicativos.

### sessão
{: #x2004539}

O período de tempo depois que um app é iniciado em um dispositivo móvel e o produto de controle de qualidade é notificado para iniciar a coleta de comportamento do aplicativo, questões e problemas.

### conexão única (SSO)
{: #x2213318}

Um processo de autenticação em que um usuário pode acessar mais de um sistema ou aplicativo, inserindo um único ID de usuário e senha.

### software como serviço (SaaS)
{: #x4585386}

Um modelo de implementação de software pelo qual o software, incluindo processos de negócios, aplicativos corporativos e ferramentas de colaboração são fornecidos como um serviço a clientes, por meio da nuvem.

### SOR
{: #x2214822}

Consulte [sistema de registro](#x6735061).

### espaço
{: #x2039442}

Um subgrupo dentro de uma organização do IBM Cloud. Os usuários que são membros de uma organização
recebem acesso a um ou mais de seus espaços, com permissões associadas a uma determinada função (como desenvolvedor,
gerenciador ou auditor). Qualquer membro do espaço pode visualizar apps, mas somente membros com a função de desenvolvedor podem criar apps e incluir instâncias de serviço no espaço. Apps e instâncias de serviço são associados a espaços. Consulte também [organização](#x2032585).

### SSL
{: #x2483907}

Consulte [Secure Sockets Layer](#x2038004).

### SSO
{: #x3456450}

Consulte [conexão única](#x2213318).

### estágio
{: #x2067189}

Implementar um aplicativo, serviço ou instância em um local predefinido para execução ou teste antes da implementação em um ambiente de produção. Veja também
[implementação](#x2104544).

### sub-rotina
{: #x2094743}

Uma seção de um pacote de software que define uma ação específica a ser executada nesse pacote de software ou um conjunto de condições sob as quais as ações devem ser executadas no pacote de software. O pacote de software completo é uma sub-rotina que contém uma hierarquia de várias sub-rotinas diferentes.

### iniciador
{: #x7470511}

Um modelo que inclui serviços predefinidos e código do aplicativo que é configurado com um buildpack específico.Um iniciador pode ser código do aplicativo que é gravado em uma linguagem de programação específica, ou uma combinação de código do aplicativo e um conjunto de serviços. Consulte também [tempo de execução](#x2391929).

### subdomínio
{: #x2040080}

Um domínio que forma uma parte de um domínio maior. Veja também [domínio customizado](#x5728384), [domínio](#x2021210), [host](#x2002243), [rota](#x2037338), [Localizador Uniforme de Recursos](#x2042491).

### sistema de engajamento
{: #x6528306}

Um sistema de tecnologia da informação (TI) que incorpora tecnologias que incentivam a interação com o usuário por meio de email, sistemas de colaboração e de rede.  Um sistema de engajamento usa geralmente tecnologias de nuvem para estender a utilidade de sistemas de registro. Consulte também [sistema de registro](#x6735061).

### sistema de registro (SOR)
{: #x6735061}

Um sistema de armazenamento de informações (como um banco de dados ou um aplicativo) que armazena registros de negócios e automatiza processos padrão. Consulte também [sistema de engajamento](#x6528306).


## T
{: #glosst}

### modelo
{: #x2041200}

Uma estrutura predefinida de um artefato.

### terceiro
{: #x2877945}

Pertencente a um produto ou serviço fornecido por uma empresa que não seja
a IBM.

### ladrilho
{: #x2092493}

Uma representação visual de um aplicativo em execução que fornece status em um painel.

### disparador
{: #x2005384}

Um mecanismo que inicia ações. Os acionadores podem ser explicitamente disparados por um usuário ou disparados em nome de um usuário por uma origem de eventos externos.

### raiz confiável
{: #x2042234}

Um certificado assinado por uma autoridade de certificação (CA) confiável. Consulte também [autoridade de certificação](#x2016383), [certificado intermediário](#x3753781).


## U
{: #glossu}

### Identificador Uniforme de Recursos (URI)
{: #x2116436}

Um endereço exclusivo que é usado para identificar o conteúdo na web. A forma mais comum de URI é o endereço de página da web, que é uma forma ou um subconjunto específico de URI denominado Localizador Uniforme de Recursos (URL). Um URI geralmente descreve como acessar o recurso, o computador que contém o recurso e o local do recurso
naquele computador.

### Localizador Uniforme de Recursos (URL)
{: #x2042491}

O endereço exclusivo de um recurso de informações que pode ser acessado em uma rede, como a Internet. A URL inclui o nome abreviado do protocolo usado para acessar o recurso de informações e as informações usadas pelo protocolo para localizar o recurso de informações. Veja também [domínio customizado](#x5728384), [domínio](#x2021210), [host](#x2002243), [rota](#x2037338), [subdomínio](#x2040080).

### URI
{: #x2116461}

Consulte [Identificador Uniforme de Recursos (URI)](#x2116436).

### Url
{: #x2042718}

Consulte [Localizador Uniforme de Recursos](#x2042491).


## V
{: #glossv}

### virtual
{: #x2043123}

Referente à não existência física como tal, mas feita pelo software para parecer que sim.

### máquina virtual (VM)
{: #x2043165}

Uma implementação de software de uma máquina que executa programas como uma máquina real. Consulte também [servidor virtual](#x2455638).

### rede privada virtual (VPN)
{: #x2043188}

Uma extensão de uma intranet corporativa sobre a estrutura existente de uma rede pública
ou privada. Uma VPN assegura que os dados que são enviados entre dois terminais de sua conexão
permaneçam seguros.

### servidor virtual
{: #x2455638}

Um servidor que compartilha seus recursos com outros servidores para suportar aplicativos. Veja também [máquina virtual](#x2043165).

### VM
{: #x2043253}

Veja [máquina virtual](#x2043165).

### VPN
{: #x2484351}

Veja [rede privada virtual](#x2043188).


## W
{: #glossw}

### WAR
{: #x2844389}

Consulte [archive web](#x2116506).

### arquivo WAR
{: #x2406005}

Consulte [archive web](#x2116506).


### app da web
{: #x7636628}

Consulte [aplicativo da web](#x2116500).

### aplicativo da web (app da web)
{: #x2116500}

Um aplicativo acessível por um navegador da web e que fornece alguma função além da exibição estática de informações, por exemplo, ao permitir que o usuário consulte um banco de dados. Os componentes comuns de um aplicativo da web incluem páginas HTML, páginas JSP e servlets. Consulte também [app](#x4281528).

### archive web (WAR)
{: #x2116506}

Um formato de arquivo compactado, definido pelo padrão Java EE, para armazenar todos os recursos necessários para instalar e executar um aplicativo da web em um único arquivo.

### área de trabalho
{: #x2096037}

Um contexto que contém uma coleção de artefatos que um usuário com a permissão apropriada pode modificar.


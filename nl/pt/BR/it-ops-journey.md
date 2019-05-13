---

copyright:
  years: 2018, 2019
lastupdated: "2019-04-18"

keywords: cloud environment, virtual server, virtual machine, vm, understanding infrastructure, IaaS model

subcollection: overview


---
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}
{:tip: .tip}
{:note: .note}

# Explore a jornada de administração de operações de TI no {{site.data.keyword.cloud_notm}}
{: #it-ops}

À medida que muitas organizações se movem para um ambiente de nuvem, no local ou hospedado em data centers, a função do administrador de operações de TI (administração de operações de TI) está sendo redefinida. O escopo e a complexidade dessa mudança aumentam significativamente com base no tipo de ambiente que sua organização deseja implementar. 
{: .shortdesc}

Antes de mover para a nuvem, você trabalhou com um ambiente inerentemente seguro com sistemas conectados à sua LAN privada ou intranet. Agora,
em um ambiente de nuvem, espera-se que você execute as tarefas a seguir:
 
  * Comprar os componentes do sistema "em algum lugar". 
  * Entender as implicações de rede e os desafios de segurança.
  * Trabalhar com tecnologias diferentes.  
  * Integrar o novo ambiente a ferramentas que não são nativamente parte da pilha de nuvem. 
  * Continuar a suportar seus clientes internos como se você ainda tivesse um data center no local.

O {{site.data.keyword.cloud}} está aqui para apoiá-lo 100% em sua jornada. Os recursos disponíveis para você incluem documentação abrangente, ferramentas de planejamento, especialistas de suporte qualificados e uma comunidade de usuários ativa. Inicie
a sua jornada. 

## Entendendo o básico
{: #basics}

### Modelos de serviço de nuvem
{: #cloud-svc-models}

Existem três tipos de modelos de serviço de nuvem: Infraestrutura como Serviço (IaaS), Plataforma como Serviço (PaaS) e Software como Serviço (SaaS). A Figura 1 explica quem faz o que em cada modelo de serviço. Para obter mais informações, consulte [IaaS, PaaS e SaaS - Modelos de serviço do IBM Cloud](https://www.ibm.com/cloud/learn/iaas-paas-saas){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo").

![Figura 1. Modelos de serviço denuvem](images/cloud-svc-models.png "Modelos de serviço de nuvem")


Com o modelo IaaS, o provedor é responsável apenas por manter a infraestrutura subjacente e, opcionalmente,
instalar softwares, como sistemas operacionais, aplicativos e bancos de dados. Você tem acesso limitado à infraestrutura
subjacente e é responsável por instalar o software ou fazer o provedor de serviços instalá-lo. Você também é responsável
por todas as outras manutenções, que incluem os pacotes de serviço, o software de vírus e as correções.

Com o modelo PaaS, o provedor é responsável pelos sistemas por meio do sistema operacional e para todo o gerenciamento
da infraestrutura, que inclui as correções de S.O., os reparos de hardware e as configurações de rede. Você constrói e
mantém o aplicativo e você ou o provedor pode instalar o middleware, incluindo bancos de dados ou outros tipos. Esse modelo é usado para desenvolver e testar o software. Para
obter mais informações, consulte [Um guia prático para a plataforma como serviço: o que é PaaS ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo")](https://www.ibm.com/blogs/cloud-computing/2016/08/10/practical-guide-paas/){: new_window}.

Com o modelo SaaS, o provedor mantém os sistemas por meio do aplicativo real. O aplicativo reconhece a nuvem e os usuários podem usar diferentes terminais, dependendo do provedor de software, para usar o software. O provedor em
nuvem é responsável por todo o gerenciamento da infraestrutura e do aplicativo, que inclui as atualizações de software,
os reparos de hardware e as configurações de rede. Geralmente, esse modelo é usado em modelos de licenciamento de
software pré-pagos. Para obter mais informações, consulte [Aplicativos SaaS para negócios e TI](https://www.ibm.com/cloud/saas){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo").

### Tipos de nuvem
{: #cloud-types}

Há três tipos diferentes de nuvens disponíveis: público, privado e híbrido. Uma nuvem pública inclui um conjunto compartilhado de recursos que são fornecidos para permitir acesso aos recursos de uma empresa. Ela fica hospedada em um ambiente de diversos locatários em um servidor virtual e pode ser acessada de qualquer lugar. 

Uma nuvem particular inclui recursos que são fornecidos para permitir acesso aos recursos de uma empresa. Ela é hospedada no hardware dedicado, como um servidor bare metal, e no local do escritório da empresa (ou entre escritórios) ou por um provedor em nuvem. Uma nuvem particular pode ser acessada de qualquer lugar.

Uma nuvem híbrida inclui recursos que combinam os aspectos das nuvens públicas e privadas. Ela é hospedada no local no escritório de uma empresa (ou entre escritórios) e por um provedor em nuvem. Uma nuvem híbrida pode ser acessada de qualquer lugar. 

## Planejando a infraestrutura
{: #planning}

Você deseja planejar a sua infraestrutura antes de provisioná-la para certificar-se de dimensioná-la corretamente para a sua carga de trabalho. O
{{site.data.keyword.cloud_notm}} tem várias ferramentas e sites para ajudá-lo a projetar e dimensionar a infraestrutura. 

### Arquitetura de infraestrutura

Inicie com a [arquitetura de infraestrutura ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo")](https://www.ibm.com/cloud/garage/architectures/infrastructure){: new_window} para obter uma visão geral mais detalhada dos três tipos de ambientes de nuvem. 

### {{site.data.keyword.cloud_notm}} Design Decision Tool

A [{{site.data.keyword.cloud_notm}} Design Decision Tool ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo")](https://github.com/ibm-cloud-architecture/infrastructure-design-decision-tool/){: new_window} ajuda a comparar alternativas quando você projeta e constrói sua solução customizada. Cada componente de infraestrutura apresenta descrição, considerações e advertências, além de comparações lado a lado. Também é possível localizar um exemplo de como usar a ferramenta.

### {{site.data.keyword.cloud_notm}} Stencils

O [{{site.data.keyword.cloud_notm}} Stencils ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo")](https://github.com/ibm-cloud-architecture/ibm-cloud-stencils){: new_window} ajuda a criar um diagrama da arquitetura do {{site.data.keyword.cloud_notm}} usando ferramentas de diagramação populares. 

### Opções de servidor bare metal

Use a [ferramenta de procura do {{site.data.keyword.cloud_notm}}{{site.data.keyword.baremetal_short}}![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo")](https://www.ibm.com/cloud-computing/bluemix/bare-metal-search){: new_window} para dimensionar e estimar as opções do servidor bare metal, incluindo servidores certificados para suportar cargas de trabalho do SAP HANA e do SAP NetWeaver.

### Serviços e conformidade do {{site.data.keyword.cloud_notm}}

Como com qualquer arquitetura, é necessário considerar os recursos do {{site.data.keyword.cloud_notm}} que podem ser incluídos na solução conforme você dimensiona a sua infraestrutura. Para obter mais informações, consulte [Aplicativos SaaS para negócios e TI ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo")](https://www.ibm.com/cloud/saas){: new_window} e procure um serviço específico. Também é necessário pensar em quaisquer regulamentações que devem ser consideradas ao construir sua arquitetura. Por exemplo: a sua carga de trabalho é considerada sensível ou está regulamentada? Para obter mais informações, consulte [Conformidade ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo")](https://www.ibm.com/cloud/compliance){: new_window}.

## Construindo a infraestrutura
{: #build}

Depois de planejar e projetar sua infraestrutura, você está pronto para construí-la. 

### Cálculo
{: #compute}

Seu servidor é a base de sua infraestrutura. Há várias opções dependendo de suas necessidades ou, se o ambiente requerer, será possível combiná-las. Consulte a tabela a seguir para obter um resumo das opções de cálculo.

| Opção | Descrição | 
|--------|---------------|
| [{{site.data.keyword.baremetal_short}}](/docs/bare-metal?topic=bare-metal-about-bm#about-bm)  | Servidores de locatário único, por hora ou mensais, que são dedicados a você e não compartilhados em nenhuma parte, incluindo os recursos do servidor, com outros clientes. |
| [{{site.data.keyword.BluVirtServers_short}}](/docs/vsi?topic=virtual-servers-about-public-virtual-servers#public-virtual-servers) | Servidores virtuais escaláveis que são comprados com núcleos dedicados e alocações de memória. |
| [{{site.data.keyword.vmwaresolutions_short}}](/docs/services/vmwaresolutions?topic=vmware-solutions-getting-started#getting-started) | Integração ou migração rápida e contínua das cargas de trabalho do VMware no local usando infraestrutura escalável, segura e de alto desempenho e a tecnologia de virtualização híbrida do VMware líder do mercado. |
| [{{site.data.keyword.containerlong_notm}}](/docs/containers?topic=containers-container_index) | Combina os contêineres do Docker, a tecnologia do Kubernetes, uma experiência de usuário intuitiva e a segurança e o isolamento integrados para automatizar a implementação, a operação, o ajuste de escala e o monitoramento de apps armazenados em contêiner em um cluster de hosts de cálculo. |
| [{{site.data.keyword.cfee_full_notm}}](/docs/cloud-foundry?topic=cloud-foundry-about) | Instanciação de múltiplas plataformas Cloud Foundry isoladas de classificação corporativa sob demanda. |
| [{{site.data.keyword.openwhisk_short}}](/docs/openwhisk?topic=cloud-functions-getting_started#getting_started) | Uma plataforma de programação Functions-as-a-Service (FaaS) baseada no Apache OpenWhisk. |
{: caption="Tabela 1. Opções de cálculo" caption-side="top"}
   
### Armazenamento
{: #storage}

O {{site.data.keyword.baremetal_short}} e o {{site.data.keyword.BluVirtServers_short}} são fornecidos com armazenamento padrão. O {{site.data.keyword.baremetal_short}} tem um espaço em disco SATA mínimo de 1 TB e
o {{site.data.keyword.BluVirtServers_short}} tem um armazenamento SAN mínimo de 25 GB. A exceção a isso é o {{site.data.keyword.baremetal_short}} certificado para SAP do {{site.data.keyword.cloud_notm}}. Para obter mais informações sobre o armazenamento padrão disponível com esses servidores, consulte [Infraestrutura do {{site.data.keyword.cloud_notm}} certificada pela SAP](/docs/bare-metal?topic=bare-metal-sap-cert-infrastructure#sap-cert-infrastructure).

É possível comprar armazenamento extra com base em suas necessidades. Consulte a tabela a seguir para obter um resumo de suas opções de cálculo.

| Opção | Descrição |
|--------|---------------|
| [{{site.data.keyword.blockstorageshort}}](/docs/infrastructure/BlockStorage/index.html) | Armazenamento iSCSI persistente e de alto desempenho que é fornecido e gerenciado independentemente das instâncias de
cálculo. Os LUNs do
Block Storage baseados em iSCSI são conectados aos dispositivos autorizados por meio de conexões redundantes de
E/S de múltiplos caminhos (MPIO). |
| [{{site.data.keyword.filestorage_short}}](/docs/infrastructure/FileStorage/index.html) | File Storage baseado em NFS, conectado à rede, persistente, rápido e flexível. Nesse ambiente de armazenamento conectado à rede (NAS), você tem controle total sobre sua função de compartilhamentos de arquivo e sobre o desempenho. Os compartilhamentos do File Storage podem ser conectados a até 64 dispositivos autorizados por meio de conexões TCP/IP roteadas para resiliência. |
| [{{site.data.keyword.cos_full_notm}}](/docs/services/cloud-object-storage?topic=cloud-object-storage-about#about) | As informações armazenadas com o IBM Cloud Object Storage são criptografadas e dispersas em vários locais geográficos e acessadas por meio de HTTP usando uma API de REST. Esse serviço usa as tecnologias de armazenamento distribuídas que são fornecidas pelo IBM Cloud Object Storage System (anteriormente Cleversafe). |
| [{{site.data.keyword.cloud_notm}} Master Data Management](/docs/services/MDMOnCloud?topic=MDMOnCloud-mdmoc_getting_started#mdmoc_getting_started) | Transfira grandes quantidades de dados do data center no local para o depósito do Cloud Object Storage. |
| [{{site.data.keyword.backup_full}}](/docs/infrastructure/Backup/index.html) | Um sistema de backup baseado em agente automatizado gerenciado por meio de um utilitário de gerenciamento baseado em navegador. É possível fazer backup de dados entre servidores em um ou mais data centers na rede do IBM Cloud. |
{: caption="Tabela 2. Opções de armazenamento" caption-side="top"}

### Rede
{: #network}

Você obterá automaticamente a conectividade com o {{site.data.keyword.vpn_full}} quando a sua conta do {{site.data.keyword.cloud_notm}} estiver configurada. Por
padrão, o servidor tem um endereço IP público e um privado. Se desejar que o servidor seja privado, será possível desativar a interface pública depois que o servidor for provisionado ou pedir que o servidor seja privado. Consulte
[Introdução à rede privada virtual](/docs/infrastructure/iaas-vpn?topic=VPN-gettingstarted-with-virtual-private-networking) para obter mais informações.

Consulte a tabela a seguir para obter um resumo das opções de rede.

| Opção | Descrição | 
|--------|---------------|
| [Content Delivery Network](/docs/infrastructure/CDN?topic=CDN-getting-started) | Usado para várias soluções para segmentos do mercado, incluindo mídia, entretenimento, software, jogos, financeiro e e-commerce, para atender às necessidades de seus negócios. |
| [Domain Name Service](/docs/cli/reference/ibmcloud?topic=cloud-cli-ibm-dev-tools-for-jetbrains) | Fornece uma localização
central para visualizar e gerenciar seus domínios por meio da interface de gerenciamento DNS básica e também fornece a opção de
gerenciar DNS reverso e secundário na mesma localização gratuitamente. |
| [Endereços IP globais](/docs/infrastructure/subnets?topic=subnets-about-global-ip-address#about-global-ip-address) | Fornece flexibilidade e
permite deslocar cargas de trabalho entre servidores, mesmo em data centers geograficamente díspares. |
| [Balanceamento de carga](/docs/infrastructure/loadbalancer-service?topic=loadbalancer-service-getting-started-with-ibm-cloud-load-balancer) | Distribui o
processamento e as comunicações uniformemente em múltiplos servidores em um data center para que um único dispositivo
não carregue uma carga inteira. |
| [Virtual Router Appliance](/docs/infrastructure/virtual-router-appliance/getting-started.html) | Roteia seletivamente o tráfego de rede privada e pública por meio de um roteador corporativo repleto de recursos com firewall, modelagem de tráfego, roteamento baseado em política, VPN e vários outros recursos. |
| [VPN IPSec](/docs/infrastructure/iaas-vpn?topic=VPN-setup-ipsec-vpn#setup-ipsec-vpn) | Um conjunto de protocolos projetados para autenticar e criptografar todo o tráfego de IP entre dois locais usando um modo de túnel que fornece uma rede criptografada de site para site. |
| [{{site.data.keyword.cloud_notm}} Direct Link](/docs/infrastructure/direct-link?topic=direct-link-get-started-with-ibm-cloud-direct-link#get-started-with-ibm-cloud-direct-link) | Aproveita um provedor do Cloud Exchange para entregar
conectividade às localizações da infraestrutura do {{site.data.keyword.cloud_notm}}. |
{: caption="Tabela 3. Opções de rede" caption-side="top"}


## Gerenciando sua infraestrutura
{: #managing}

Depois de construir sua infraestrutura e ambiente, você está pronto para começar a gerenciá-la.

| Atividade | Descrição |
|--------|---------------|
| [Monitorar eventos do sistema](/docs/account?topic=account-audit-log) | Visualize as ações que foram
executadas nos recursos da infraestrutura. |
| [Configurar preferências de e-mail](/docs/account?topic=account-email-prefs) | Configure as notificações por e-mail
da infraestrutura {{site.data.keyword.cloud_notm}} sobre eventos não planejados, manutenção e comunicados.  |
| [Entender como os seus dados estão seguros](/docs/overview?topic=overview-security) | A plataforma
{{site.data.keyword.cloud_notm}} tem controles de segurança em camadas na rede e na infraestrutura. |
| [Entender como é possível assegurar tempo de inatividade zero](/docs/overview?topic=overview-zero-downtime) | Todos os recursos do {{site.data.keyword.cloud_notm}} são hospedados em localizações de data center ao redor do mundo. |
{: caption="Tabela 4. Tarefas de gerenciamento" caption-side="top"}

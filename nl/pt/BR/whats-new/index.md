---

copyright:

  years: 2015, 2019

lastupdated: "2019-05-13"

keywords: release notes, what's new, what is new, cloud updates

subcollection: overview

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:tip: .tip}

# O que há de novo no {{site.data.keyword.Bluemix_notm}}?
{: #whatsnew}

Fique atualizado com os novos recursos que estão disponíveis na plataforma {{site.data.keyword.Bluemix}} para que você obtenha o máximo de sua experiência do {{site.data.keyword.Bluemix_notm}}. 
{:shortdesc}

Se você estiver procurando atualizações para os serviços que estão disponíveis no {{site.data.keyword.Bluemix_notm}}, consulte a [página Comunicados do {{site.data.keyword.Bluemix_notm}}](https://www.ibm.com/cloud/blog/announcements){: new_window} ![Ícone de link externo](../../icons/launch-glyph.svg "Ícone de link externo") no blog.
{: tip}



## Plataforma {{site.data.keyword.Bluemix_notm}}
{: #platform_category}


### Exportar dados de uso com tags associadas
Novo a partir de: 4 de abril de 2019 

Agora é possível usar nossos recursos de identificação mais recentes para gerenciar os recursos, o uso e os custos no relatório de uso exportado. Ao incluir uma tag em um recurso, você tem a opção de visualizar a tag associada ao recurso. Acesse **Gerenciar**> **Faturamento e uso**> **Uso**> **Exportar CSV**> **Instâncias** para fazer download do relatório de uso. Para obter mais informações sobre a exportação de tags, confira a postagem do blog [Exportar tags nos seus dados de uso para ajudar na alocação de custo](https://www.ibm.com/cloud/blog/export-your-tagged-usage-data-within-the-enhanced-ibm-cloud){: new_window}![Ícone de link externo](../../icons/launch-glyph.svg "Ícone de link externo").

### Grupo de acesso para ativar o acesso público aos recursos
Novo a partir de: 25 de março de 2019

Agora é possível ativar o acesso público a objetos em seus depósitos do {{site.data.keyword.cos_full}} usando um novo grupo de acesso fornecido em sua conta. Esse novo grupo de acesso é chamado de grupo de `Acesso público` e todos os usuários e IDs de serviço são incluídos nele por padrão. É possível atualizar as políticas para o grupo de acesso para permitir que todos os usuários, mesmo os usuários não autenticados, acessem o recurso que você especifica na política. [Saiba mais sobre o grupo de acesso público](/docs/iam?topic=iam-public#public).

### Autenticação de diversos fatores para usuários com IDs federados
Novo desde: 12 de março de 2019
{: #mfa-federated}

Proprietários ou usuários da conta designados à função de administrador para o serviço de gerenciamento de conta de faturamento podem ativar a autenticação de diversos fatores (MFA) para todos os usuários em sua conta. Os usuários federados que usam seu ID de conexão única da empresa ou corporativa agora podem ser necessários para autenticar usando o MFA para efetuar login no {{site.data.keyword.Bluemix_notm}}. Para obter mais informações sobre esse aprimoramento de recurso e o que você precisa saber sobre a ativação da MFA para sua conta, veja [Introduzindo a MFA para usuários do IBM Cloud com ID federado](https://www.ibm.com/cloud/blog/introducing-mfa-for-ibm-cloud-users-with-federated-id){: new_window} ![Ícone de link externo](../../icons/launch-glyph.svg "Ícone de link externo").

### Nova opção de nome do host appdomain.cloud
Novo a partir de: 31 de dezembro de 2018
{: #appdomain}

Uma nova opção de nome do host `*.appdomain.cloud` está disponível em cloud.ibm.com.

Anteriormente, o domínio `mybluemix.net` era usado para hospedar apps em vários destinos de implementação, como o {{site.data.keyword.containerlong_notm}} ou o Cloud Foundry. Qualquer app que você tenha hospedado em `mybluemix.net` não será afetado.

O subdomínio para apps do Cloud Foundry é `cf.appdomain.cloud`. O subdomínio para apps que você implementa no {{site.data.keyword.containerlong_notm}} é `containers.appdomain.cloud`.

### Novos terminais de API do Cloud Foundry
Novo a partir de: 30 de novembro de 2018
{: #cf-api-endpoints}

Os terminais anteriores da API `api.*.bluemix.net` do Cloud Foundry ainda estão disponíveis para compatibilidade com versões anteriores. No entanto, é possível atualizar os scripts e a automação de infraestrutura para usar os novos terminais de API do Cloud Foundry a seguir para a sua região:

* api.us-south.cf.cloud.ibm.com (anteriormente api.ng.bluemix.net)
* api.eu-gb.cf.cloud.ibm.com (anteriormente api.eu-gb.bluemix.net)
* api.us-east.cf.cloud.ibm.com (anteriormente api.us-east.bluemix.net)
* api.eu-de.cf.cloud.ibm.com (anteriormente api.eu-de.bluemix.net)
* api.au-syd.cf.cloud.ibm.com (anteriormente api.au-syd.bluemix.net)

### Nova experiência de suporte para o {{site.data.keyword.Bluemix_notm}}
Novo a partir de: 30 de novembro de 2018 
{: #support}

Com o Centro de suporte, é possível trabalhar para resolver todos os problemas relacionados ao {{site.data.keyword.Bluemix_notm}}. A
página de entrada fornece as perguntas mais frequentes, portanto, é possível localizar a resposta para a sua pergunta
sem mesmo entrar em contato com o {{site.data.keyword.Bluemix_notm}}. Também é possível conversar com um representante de suporte em tempo real. Agora, os seus casos podem ser gerenciados por meio de uma única localização. Acesse **Suporte** &gt; **Gerenciar casos** para criar, visualizar ou editar os casos.

Também é possível localizar a [página Status](https://cloud.ibm.com/status){: new_window}
![Ícone de link externo](../../icons/launch-glyph.svg "Ícone de link externo") por meio do centro de suporte. Ela foi aprimorada para incluir todos os incidentes não planejados, a manutenção planejada, os anúncios e as notificações de boletim de segurança sobre eventos essenciais que afetam a plataforma, a infraestrutura e os principais serviços do {{site.data.keyword.Bluemix_notm}}. Clique
em **Visualizar status da nuvem** por meio do centro de suporte. Para conferir a nova experiência,
efetue login e acesse o [Centro de suporte](https://cloud.ibm.com/unifiedsupport/supportcenter){: new_window} ![Ícone de link externo](../../icons/launch-glyph.svg "Ícone de link externo"). 

### Login unificado, chaves de API e gerenciamento de usuário e de acesso no {{site.data.keyword.Bluemix_notm}}
Novo a partir de: 30 de novembro de 2018
{: #useraccess}

Com nossas atualizações mais recentes, é possível tirar proveito de um login seguro simplificado que está disponível para todos os usuários, independentemente do seu tipo de ID. Se
você tiver um IBMid ou um ID do SoftLayer, será possível efetuar login rapidamente no console do {{site.data.keyword.Bluemix_notm}} por meio de nossa página de login aprimorada. Também
é possível fazer chamadas de API seguras no {{site.data.keyword.Bluemix_notm}} e automatizar seu login da CLI usando uma chave de API do IAM ou um token de acesso do IAM. 

Depois de efetuar login, agora é possível ver todos os usuários, incluindo os usuários da plataforma e da infraestrutura clássica de sua página Usuários na IU do Access (IAM). Dependendo de seu acesso para
visualizar outros usuários na conta, será possível filtrar a sua visualização rapidamente por usuários da conta, usuários
da infraestrutura clássica ou organização do Cloud Foundry. Também é possível usar os filtros para localizar usuários rapidamente por nome, e-mail ou status.

Agora que todos os seus usuários estão em um único console, é possível gerenciar seu acesso a todos os tipos de recursos
da mesma localização. O acesso é iniciado com o usuário, portanto, inicie selecionando um usuário na lista. Em seguida, dependendo de qual tipo de recurso ao qual você deseja designar acesso, é possível escolher entre as políticas de acesso do IAM, o acesso do Cloud Foundry ou as permissões de infraestrutura clássica. Se
você quer apenas designar políticas de acesso do IAM, tente criar um grupo de acesso para simplificar
o processo de gerenciamento de acesso incluindo todos os usuários no mesmo grupo de acesso que precisa das mesmas políticas designadas.

Para obter mais detalhes, confira [Excelentes melhorias de acesso do usuário ajudam a oferecer uma plataforma {{site.data.keyword.Bluemix_notm}} unificada](https://www.ibm.com/cloud/blog/announcements/ibm-cloud-access-management){: new_window}![Ícone de link externo](../../icons/launch-glyph.svg "Ícone de link externo"). 

### Localize toda a documentação do plug-in da CLI do {{site.data.keyword.Bluemix_notm}} em um lugar
Novo a partir de: 30 de novembro de 2018
{: #cli}

Agora é possível acessar toda a documentação do plug-in da CLI do {{site.data.keyword.Bluemix_notm}} em um
lugar, facilitando a localização de qualquer comando da CLI que você esteja procurando na plataforma {{site.data.keyword.Bluemix_notm}}. Verifique a seção Referências na [documentação da CLI](/docs/cli?topic=cloud-cli-ibmcloud-cli).

### Verifique o novo painel e a lista de recursos
Novo a partir de: 30 de novembro de 2018
{: #dash}

Com a nossa atualização mais recente, é possível agora visualizar todos os serviços de plataforma e infraestrutura em um local. Ao
efetuar login, é possível verificar o novo painel imediatamente. Depois da inclusão dos recursos em sua conta por meio do catálogo, é possível usar a lista de recursos para obter uma visualização completa dos recursos da conta:

* O painel foi projetado novamente para que seja possível visualizar um resumo dos recursos, da manutenção, do status, dos apps, do suporte, do uso e dos usuários.
* É possível localizar mais detalhes sobre os recursos na lista de recursos. É possível identificar seus recursos para organizá-los ou selecioná-los para fazer mudanças na página de detalhes.
* Agora que é possível ver todos os seus recursos em um local, incluímos uma procura global para que seja possível
localizar rapidamente os recursos que você criou e esperar que apareçam na página Lista de recursos. 
* Também é possível procurar os resultados do catálogo para que você possa localizar rapidamente os recursos
para incluir em sua conta.  

Consulte [Gerenciar todos os seus recursos de nuvem na Enhanced {{site.data.keyword.Bluemix_notm}} Platform](https://www.ibm.com/blogs/bluemix/2018/11/manage-all-your-cloud-resources-on-the-enhanced-ibm-cloud-platform/){: new_window} ![Ícone de link externo](../../icons/launch-glyph.svg "Ícone de link externo") para obter mais detalhes.

### Informações de conta unificada, faturamento e perfil do usuário para os serviços de plataforma e infraestrutura
Novo a partir de: 30 de novembro de 2018
{: #profile}

Sua conta, seu faturamento e informações de perfil agora estão simplificados. É possível visualizar as informações da conta de todos os recursos de plataforma e infraestrutura em um console unificado. 

* A sua área de perfil e de configurações contém informações sobre você, bem como as preferências de notificação por e-mail
para todos os tipos de recursos. 
* A área de informações da conta contém informações sobre a sua empresa ou organização, as configurações da conta e o acesso
rápido para trabalhar com grupos de recursos e organizações do Cloud Foundry. É possível até localizar as
melhores práticas para ajudá-lo a começar rapidamente.
* A área de faturamento e uso da conta ajuda a entender a sua fatura, efetuar pagamentos, monitorar assinaturas, obter
cotações, rastrear pedidos e configurar as notificações de gastos.

Verifique [Juntando tudo: uma experiência de gerenciamento de conta única e faturamento](https://www.ibm.com/cloud/blog/announcements/ibm-cloud-account-management){: new_window} ![Ícone de link externo](../../icons/launch-glyph.svg "Ícone de link externo") para obter mais detalhes.

### Organize seus recursos com tags
Novo a partir de: 30 de novembro de 2018
{: #tag}

Agora, as tags estão disponíveis para inclusão nos recursos, como o Cloud Object Storage, para ajudá-lo
a gerenciar e localizar os recursos que são mais relevantes para você. Por exemplo, se você tiver centenas de recursos e desejar diferenciar entre um par que é pago da mesma maneira, será possível identificá-los com `costcenter:location01`. Ou, se tiver uma equipe que está trabalhando em um par de recursos repetidamente, será possível usar algo como `team-blue`. Também é possível filtrar a sua lista de recursos por tags para organizar e localizar
os recursos que você precisa rapidamente. Para obter mais informações, consulte [Trabalhando com tags](/docs/resources?topic=resources-tag) e [Identificação de plataforma na Enhanced {{site.data.keyword.Bluemix_notm}} Platform](https://www.ibm.com/cloud/blog/announcements/platform-tagging-on-the-enhanced-ibm-cloud-platform){: new_window} ![Ícone de link externo](../../icons/launch-glyph.svg "Ícone de link externo"). 

### Localize os custos mensais precisos com o estimador de custo
Novo a partir de: 30 de novembro de 2018
{: #cost-estimator}

Para ajudá-lo a decidir e analisar quais serviços você gostaria de comprar, é possível usar o estimador de custo. Agora,
é possível acessar o console e selecionar cada serviço que você gostaria de ter e incluir todos os custos em uma
ferramenta fácil de usar. É possível até mesmo inserir usos de dados projetados, consultas por segundo, gravações por segundo e consultas por segundo para obter uma estimação mais precisa de suas despesas mensais. É possível usar o
estimador de custo com cada serviço de catálogo selecionado ou clicar no ícone do estimador de custo
![Ícone Estimador](../../icons/Estimator.svg) no menu do console para obter um
resumo dos custos estimados. Para obter mais informações, consulte [Estimando os custos](/docs/billing-usage?topic=billing-usage-cost).

### Nomes de locais globais atualizados para o  {{site.data.keyword.cloud_notm}}
Novo a partir de: 1 de novembro de 2018
{: #location-name-updates}

Como o {{site.data.keyword.cloud_notm}} continua a expandir a nossa área de cobertura de disponibilidade
global, estamos atualizando a estrutura de nomenclatura de localização para melhor suportar uma hierarquia compreensível e
consistente de geografias, regiões e data centers em todo o mundo. Se você estiver familiarizado com as nossas atuais
regiões globais, reconhecerá nomes como o Sul dos EUA e Sydney. Estamos alinhando esses nomes de localização com os
nomes de cidade nas quais os data centers existem fisicamente.

Por enquanto, os IDs programáticos não estão mudando, portanto, não há impacto da perspectiva de uma API. A tabela a seguir mostra os nomes de local antigos e novos. Para obter mais informações e uma lista abrangente
de data centers e regiões, consulte [Disponibilidade de serviço](/docs/resources?topic=resources-services_region).

| Nome de exibição do local anterior | Nome de exibição do novo local | Código |
|----------|---------|---------|
| Sul dos EUA | Dallas | us-south | 
| Leste dos EUA | Washington DC | Leste dos EUA |
| Reino Unido | Londres | eu-gb |
| Alemanha | Frankfurt | eu-de |
| Sydney | Sydney | au-syd |
| AP Norte | Tóquio | jp-tok |
{: caption="Tabela 1. Novos nomes de local" caption-side="top"}

### Designar acesso de gerenciamento de conta para outros
Novo a partir de: 30 de outubro de 2018
{: #acct-mgmt-services}

Com o {{site.data.keyword.cloud_notm}}Identity and Access Management (IAM), é possível delegar as tarefas
comuns que você conclui como um administrador de conta para outro usuário na conta. Ao criar uma política de acesso
em um ou todos os serviços de gerenciamento de conta disponíveis, é possível facilmente delegar responsabilidades,
como convidar e remover usuários, gerenciar grupos de acesso, gerenciar IDs de serviço, manter os
serviços do catálogo privado e até mesmo monitorar o faturamento e rastrear o uso. Há quatro serviços de gerenciamento
de conta individuais e uma opção de todos os serviços que podem ser usados para configurar as políticas de acesso:

* Gerenciamento de usuários para convidar e remover usuários
* Grupos de acesso do IAM para criar, editar, excluir, atualizar e designar acesso 
* Serviço de identidade do IAM para visualizar, criar, excluir e designar acesso aos IDs de serviço e
às chaves API associadas na conta
* Catálogo de recursos globais para visualizar as ofertas do catálogo privado e atualizar os metadados e a
visibilidade para as ofertas
* Todos os serviços de gerenciamento de conta para o acesso a cada uma das opções de serviço de gerenciamento de
conta individuais com base na função designada, assim como o acesso ao faturamento e ao rastreamento de uso.

Para obter mais informações sobre as tarefas que um usuário pode executar com base no serviço de
gerenciamento de conta no qual ele tem uma política e qual a função designada a ele, consulte
[Exemplo de funções de gerenciamento da plataforma e as ações
para os serviços de gerenciamento de conta](/docs/iam?topic=iam-userroles#platformrolestable2). Para obter informações adicionais sobre esse novo recurso,
consulte a postagem do blog
[Introduzindo
mais flexibilidade e controle para o acesso aos serviços de gerenciamento de conta do IBM Cloud](https://www.ibm.com/cloud/blog/announcements/introducing-more-flexibility-and-control-for-ibm-cloud-account-management-services-access){: new_window}
![Ícone de linkexterno](../../icons/launch-glyph.svg "Ícone de link externo"). 


### Procurando Recursos
Novo a partir de: 17 de julho de 2018
{: #forward-slash-key}

É possível procurar recursos de qualquer lugar no console do {{site.data.keyword.cloud_notm}}. Digite o nome de um recurso no campo de procura na barra de menus do console. Pressione a tecla de barra (/) para ativar a procura.

### Incluir dinamicamente usuários federados nos grupos de acesso
Novo desde: 12 de julho de 2018
{: #add-fed-users}

É possível criar regras dinâmicas para incluir automaticamente usuários federados nos grupos de acesso com base em atributos de identidade específicos. Quando seus usuários efetuam login com um ID federado, os dados do provedor de identidade mapeiam dinamicamente seus usuários para um grupo de acesso com base nas regras que você configurou. Para obter mais informações, consulte [Criando regras dinâmicas para grupos de acesso](/docs/iam?topic=iam-rules).

### Proteja os seus IDs de serviço e as chaves API
Novo a partir de: 1 de junho de 2018
{: #protect-svcid-apikey}

Para evitar uma situação em que o seu ID de serviço ou a chave de API sejam excluídos, causando uma indisponibilidade ou uma interrupção, é possível bloquear IDs de serviço e chaves de API usando a IU ou a CLI. Bloquear um ID de serviço também evita que quaisquer
políticas de acesso sejam mudadas, excluídas ou designadas, bem como quaisquer chaves API associadas com o ID de serviço de
ser criado ou excluído. Para obter informações adicionais, consulte
[Bloqueando
um ID de serviço](/docs/iam?topic=iam-serviceidapikeys#lockkey) e [Bloqueando uma chave API](/docs/iam?topic=iam-userapikey).

### Faça upgrade de sua conta Lite para uma conta da assinatura.
Novo a partir de: 31 de maio de 2018
{: #upgrade-lite}

Agora é possível fazer upgrade da sua conta Lite para uma conta da assinatura diretamente do console do {{site.data.keyword.Bluemix_notm}}. Com uma conta da assinatura, é possível usar as ofertas de plataforma e de infraestrutura e aproveitar a precificação com desconto criando
um gasto mensal e um termo de compromisso. Também é possível evitar surpresas com faturamento fixo em um planejamento de pagamento
mensal, mas com a flexibilidade para pedir mais ou menos com base nas suas necessidades. Para obter informações adicionais, consulte
as [FAQs de conta da assinatura](/docs/billing-usage?topic=billing-usage-billusagefaqs#subs-order). 

### {{site.data.keyword.Bluemix_notm}} CLI Redenominando
Novo a partir de: 15 de maio de 2018
{: #cli-rebrand}

Os comandos da CLI do {{site.data.keyword.Bluemix_notm}} mudaram de **`bluemix`** e
**`bx`** para **`ibmcloud`**. No entanto, ainda é possível usar os comandos da CLI **`bluemix`** e **`bx`** até que sejam removidos posteriormente. Não há nenhum nome abreviado agora, apenas o nome completo **`ibmcloud`**. 

### Autenticação de diversos fatores para sua conta do {{site.data.keyword.Bluemix_notm}}
Novo a partir de: 02 de maio de 2018
{: #account-mfa}

A autenticação de diversos fatores (MFA) inclui uma camada extra de segurança em sua conta solicitando que todos os usuários forneçam uma senha descartável baseada em tempo, além de seu IBMid e senha padrão durante o login. Isso também é conhecido geralmente como autenticação de dois fatores (2FA). A MFA é ativada por conta e, uma vez ativada, todos os usuários na conta precisarão efetuar login usando a medida extra de segurança. Para obter informações adicionais, consulte a postagem do blog
[O IBM Cloud
Platform agora inclui suporte para a autenticação de diversos fatores](https://www.ibm.com/cloud/blog/ibm-cloud-platform-now-adds-support-multi-factor-authentication){: new_window}
![Ícone de link externo](../../icons/launch-glyph.svg "Ícone de link externo").

### Designar acesso rapidamente usando grupos de acesso
Novo a partir de: 03 de abril de 2018
{: #access-groups}

Deseja ser capaz de designar o acesso rapidamente usando o menor número de políticas possível? Agora é possível com grupos de acesso. Os grupos de acesso permitem agrupar um conjunto de usuários e IDs de serviço e designar uma política única que se aplique a todos os membros do grupo. Usando os grupos de acesso, é possível limitar o tempo gasto gerenciando o acesso aos usuários e aos IDs de serviço em sua conta. Consulte a postagem do blog [Novo recurso: grupos de acesso](https://www.ibm.com/cloud/blog/access-groups){: new_window} ![Ícone de link externo](../../icons/launch-glyph.svg "Ícone de link externo") para obter mais detalhes.

### A região Leste dos EUA do {{site.data.keyword.Bluemix_notm}} Foundry Service agora está disponível
Novo a partir de: 15 de dezembro de 2017
{: #cf-useast}

Um novo datacenter Leste dos EUA agora está disponível em Washington, DC. Essa nova região pode ser atingida usando o terminal `us-east.cloud.ibm.com`. Para obter detalhes sobre os serviços disponíveis para compra nessa nova região, consulte [Serviços por região](/docs/resources?topic=resources-services_region).

### Suporte para recursos na União Europeia
Novo a partir de: 14 de dezembro de 2017
{: #eu-resources}

Caso os seus serviços e data centers estejam localizados na Europa, o {{site.data.keyword.Bluemix_notm}} agora oferece recursos extras para proteger seus dados na União Europeia. É possível solicitar que o suporte seja fornecido por equipes de sucesso do cliente localizadas na Europa. Esse suporte está disponível 24 horas por dia, 7 dias por semana. Consulte [Ativando a opção Suportado pela União Europeia](/docs/account?topic=account-eu-hipaa-supported#bill_eusupported) e [Solicitando suporte para recursos na União Europeia](/docs/get-support?topic=get-support-getting-customer-support#eusupported) para obter mais informações.

### Retirada de suporte para o TLS 1.0 e 1.1
Novo a partir de: 28 de novembro de 2017
{: #nosupport-tls}

Em 1º de março de 2018, o {{site.data.keyword.Bluemix_notm}} retirará o suporte para o TLS 1.0 e TLS 1.1 em muitos dos nossos produtos e serviços de nuvem como parte do nosso compromisso de oferecer uma nuvem que seja segura para o núcleo e de acordo com as melhores práticas do segmento de mercado para segurança e privacidade de dados. Para saber mais sobre como essa mudança afeta você e quais ações você pode precisar tomar, consulte [Retirada de suporte para o TLS 1.0 e 1.1](/docs/get-support?topic=get-support-tlssupportwithdraw).

### Uma nova maneira de organizar recursos em sua conta
Novo a partir de: 16 de novembro de 2017
{: #usergs}

Os grupos de recursos são uma nova maneira de criar agrupamentos customizáveis de recursos da conta e o acesso ao grupo e aos recursos dentro dele é gerenciado usando o Identity and Access Management (IAM). Todo mundo começa com um grupo de recursos padrão. É possível renomear esse grupo de recursos e incluir novas instâncias de serviço nele à medida que são criadas por meio do catálogo.

Para usuários com uma conta pré-paga ou de assinatura, é possível criar grupos de recursos adicionais para tornar o uso do gerenciamento de cotas e da visualização de faturamento para um conjunto de recursos mais fácil. Também é possível agrupar recursos para tornar mais fácil para você designar o acesso de usuários a mais de um serviço por vez. Para saber mais sobre como trabalhar com grupos de recursos para sua conta, consulte [Gerenciando grupos de recursos](/docs/resources?topic=resources-rgs).

### Atualizações para o {{site.data.keyword.Bluemix_notm}} IAM
Novo a partir de: 16 de novembro de 2017
{: #iam-nov17}

A introdução de grupos de recursos dentro de sua conta do {{site.data.keyword.Bluemix_notm}} abriu uma nova maneira para você designar acesso. Usuários e IDs de serviço podem ter acesso designado a todos os serviços em um grupo de recursos permitindo designar rapidamente acesso a mais de um recurso por vez. Também é possível customizar o acesso de cada usuário ou ID de serviço designando o acesso a apenas alguns serviços em um grupo de recursos ou você opta por designar acesso a recursos individuais até o nível da instância de serviço. Para obter mais informações sobre os recursos que você pode aproveitar usando o IAM, consulte [Quais recursos o IAM fornece?](/docs/iam?topic=iam-iamoverview#features)

### Customizar sua visualização de painel
Novo a partir de: 16 de novembro de 2017
{: #custom-dash}

É possível visualizar e gerenciar todos os recursos em sua conta em seu painel no console do {{site.data.keyword.Bluemix_notm}}. E agora é possível configurar filtros para customizar sua visualização. Por exemplo, é possível filtrar por grupo de recursos para visualizar os recursos específicos em um grupo de recursos. Também é possível filtrar por região ou espaço do Cloud Foundry. Para obter mais detalhes, consulte [Gerenciando recursos no painel](/docs/overview?topic=overview-ui#dashboardview).

### Centro de suporte
Novo a partir de: 2 de novembro de 2017
{: #support-nov17}

Agora temos o novo Centro de Suporte, onde é possível procurar por informações, postar perguntas em nossa comunidade do desenvolvedor e gerenciar chamados. Acesse **Suporte > Centro de Suporte** na barra de menus do console do {{site.data.keyword.Bluemix_notm}}.

### Introdução ao IBM Cloud
Novo a partir de: 31 de outubro de 2017
{: #meet-ibmcloud}

O Bluemix agora é IBM Cloud. Exceto pelo lançamento de nosso novo nome, nada mudou. Ainda é possível construir e executar facilmente seus aplicativos e serviços, como sempre. Veja o [IBM Cloud Blog](https://www.ibm.com/cloud/blog/announcements/bluemix-is-now-ibm-cloud){: new_window} ![Ícone de link externo](../../icons/launch-glyph.svg "Ícone de link externo") para obter mais detalhes.

### Conta Lite
Novo a partir de: 31 de outubro de 2017
{: #new-liteacct}

Uma conta Lite é nosso novo tipo conta, que fornece acesso para experimentar serviços grátis selecionados sem restrições de tempo. Essa nova conta também inclui rastreamento de uso e recursos de eficiência para ajudá-lo a gerenciar melhor seus recursos. Para saber mais sobre o que está disponível, consulte [Tipos de conta](/docs/account?topic=account-accounts#liteaccount).

### Recurso de autenticação do aplicativo Identity and Access Management
Novo a partir de: 6 de outubro de 2017
{: #app-authfeature}

O Identity and Access Management (IAM) agora fornece a capacidade de criar um ID de Serviço, que pode ser considerado uma identidade que pode ser usada para que os aplicativos sejam autenticados com seus serviços do {{site.data.keyword.Bluemix_notm}}. Em vez de usar as credenciais individuais do usuário, um ID de Serviço pode ser criado com uma chave API associada e permissões de acesso na forma de uma política de serviço que é designada ao ID de Serviço para que você controle o nível de acesso para qualquer aplicativo que se autentica com esse ID.

Para obter mais informações sobre os benefícios desse recurso e como começar a usá-lo, consulte [Apresentando IDs de serviço e chaves API do IBM Cloud IAM](https://www.ibm.com/cloud/blog/introducing-ibm-cloud-iam-service-ids-api-keys){: new_window} ![Ícone de link externo](../../icons/launch-glyph.svg "Ícone de link externo").

### Catálogo global do {{site.data.keyword.Bluemix_notm}}
Novo a partir de: 27 de julho de 2017
{: #gc}

Expandindo a última atualização do console para gerenciar suas regiões públicas em um único local no console, o {{site.data.keyword.Bluemix_notm}} agora tem um catálogo global, tornando o processo de seleção e implementação de itens selecionados no catálogo mais aperfeiçoado. Independentemente da região que você selecionou no console, agora é possível ver todos os serviços que estão disponíveis em todas as regiões públicas de seu catálogo. Depois de selecionar um tile do catálogo, é possível ver em quais regiões o serviço está disponível e selecionar onde você deseja implementá-lo. Para obter mais informações sobre as atualizações mais recentes para o catálogo, consulte [Um catálogo global do {{site.data.keyword.Bluemix_notm}} torna a construção de coisas mais fácil](https://www.ibm.com/cloud/blog/announcements/global-bluemix-catalog-makes-building-things-easier){: new_window} ![Ícone de link externo](../../icons/launch-glyph.svg "Ícone de link externo").

### Atualizações do console do {{site.data.keyword.Bluemix_notm}}
Novo a partir de: 23 de maio de 2017
{: #console-may17}

Agora é possível gerenciar suas regiões públicas de um único local por meio do console atualizado do {{site.data.keyword.Bluemix_notm}}. O seletor de região oferece acesso simplificado aos seus recursos, e outros aprimoramentos incluem maior disponibilidade e desempenho aprimorado. Para obter mais informações, verifique [New Global Bluemix UI for Higher Availability and More](https://www.ibm.com/blogs/bluemix/2017/05/new-global-bluemix-ui-higher-availability/){: new_window} ![Ícone de link externo](../../icons/launch-glyph.svg "Ícone de link externo").

### Identidade e gerenciamento de acesso
Novo a partir de: 01 de maio de 2017
{: #iam-may17}

Com as atualizações e melhorias mais recentes, proprietários ou administradores de contas do {{site.data.keyword.Bluemix_notm}} agora podem usar uma nova UI de controle de acesso unificado para aproveitar os recursos a seguir:
 * Gerenciar o acesso de baixa granularidade de usuários aos serviços do Kubernetes e a outros serviços à medida que eles adotam os novos recursos de controle de acesso
 * Designar políticas de serviço e funções do Cloud Foundry para os usuários dentro de suas organizações

Além disso, os usuários da plataforma {{site.data.keyword.Bluemix_notm}} podem criar, excluir e listar chaves API associadas aos seus IDs de usuário. E os usuários da plataforma podem usar essas chaves API para se autenticar ao usar as APIs ou CLIs.

Por último, aprimoramos a nossa capacidade de gerenciamento de usuários unificado para assegurar que em uma conta IaaS-PaaS vinculada, os usuários sejam gerenciados de uma maneira unificada, sem precisar incluir usuários separadamente no Portal do cliente SoftLayer ou no console do {{site.data.keyword.Bluemix_notm}}.

Para obter mais informações, verifique a postagem do blog [Introducing Identity & Access Management](https://www.ibm.com/blogs/bluemix/2017/05/introducing-identity-access-management/){: new_window} ![Ícone de link externo](../../icons/launch-glyph.svg "Ícone de link externo").

### Mudanças de design de navegação para docs do {{site.data.keyword.Bluemix_notm}}
Novo a partir de: 13 de abril de 2017
{: #docnavupdates}

Com essa atualização de navegação, achamos que você entenderá como o conteúdo é mais bem organizado em todos os nossos docs e será capaz de localizar o conteúdo relevante de forma mais eficiente. Com menos camadas aninhadas de conteúdo, você não precisará procurar muito para encontrar a documentação necessária para ser bem-sucedido no {{site.data.keyword.Bluemix_notm}}.



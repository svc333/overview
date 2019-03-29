---

copyright:
  years: 2018, 2019
lastupdated: "2019-03-14"

keywords: HA, failover, DR

subcollection: overview

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:pre: .pre}
{:table: .aria-labeledby="caption"}
{:note: .deprecated}


# Como assegurar tempo de inatividade zero?
{: #zero-downtime}

Sua estratégia global é importante. É possível selecionar um data center ou uma localização específica para implementar
seus dados na parte certa do mundo para os seus clientes. 
{:shortdesc}

Os serviços de plataforma {{site.data.keyword.Bluemix}} são autogerenciados. Isso significa que as
localizações nas quais você implementa o seu app podem espalhar as cargas de trabalho pelos data centers. E é possível
assegurar que um design de failover esteja em vigor, o que significa que seu app sempre está funcionando para os seus clientes. Para os seus recursos de infraestrutura, é possível selecionar data centers individuais em que os recursos são implementados. 

Todos os recursos do {{site.data.keyword.Bluemix_notm}} são hospedados em localizações de data center ao redor
do mundo. A alta disponibilidade e a recuperação de desastre não são universais em todos os serviços, portanto, o tipo
de alta disponibilidade e recuperação de desastre disponível dependerá do serviço que você estiver usando.  

## Recuperação de desastre
{: #disaster-recovery}

A recuperação de desastre trata-se de sobreviver a uma falha catastrófica ou perda de disponibilidade em uma única
localização. Para assegurar que a recuperação de desastre esteja em vigor, é necessário implementar vários
ambientes {{site.data.keyword.Bluemix_notm}} em múltiplas localizações para evitar pontos únicos de falha. Esses ambientes podem ser uma combinação de plataformas Public, Dedicated ou Local.  

### Plano de recuperação de desastre 
{: #dr-plan}

O {{site.data.keyword.Bluemix_notm}} segue requisitos para o planejamento de um desastre e cada aplicativo tem
um plano para recuperação ou reinicialização após um evento de desastre. A recuperação é feita por meio de backups
eletrônicos em um centro de recuperação ou instalações de computação alternativas que restauram a computação. Antes de
qualquer desastre potencial, o plano de recuperação de desastre inclui os requisitos de sistemas e de hospedagem
para hardware, software, conectividade de rede e recursos de backup externo.

A lista a seguir inclui os requisitos do plano de recuperação de desastre:

- Para balanceamento de carga, existe um documento para explicar como o serviço de computação permanece disponível. 
- Onde o failover multisite ocorre, o plano de recuperação de desastre deve explicar o que cada um deve fazer
para causar o failover e assegurar a reinicialização. 
- O plano de recuperação de desastre deve definir como a solução funciona e qual é a perda de dados. 
- Ele deve confirmar como o Tempo Máximo de Inatividade Tolerável é atendido e ser armazenado no banco de dados do Plano de Recuperação de Desastres.  
- O plano de recuperação de desastre especifica os controles de segurança para a execução no modo de desastre, caso eles
sejam diferentes dos que estão em execução na produção. 

### Gerenciamento do plano de recuperação de desastre 
{: #dr-plan-mgmt}

Os requisitos que o {{site.data.keyword.Bluemix}} segue são: 

- O plano de recuperação de desastre deve ser atualizado após qualquer mudança importante de infraestrutura, liberação
importante de aplicativo e após qualquer teste. 
- Ele deve ser aprovado anualmente. 

## Locais para implementação de recurso 
{: #ov_intro_reg}

É possível criar aplicativos e instâncias de serviço em diferentes localizações com a mesma infraestrutura do
{{site.data.keyword.cloud_notm}} para o gerenciamento de aplicativo e a mesma visualização de
detalhes de uso para o faturamento. É possível implementar seus apps na localização mais próximo de seus clientes
para atingir baixa latência do aplicativo. 

Para resolver problemas de segurança, também é possível selecionar a localização no qual você deseja manter os dados do
aplicativo. Ao construir os aplicativos em mais de uma localização, se uma delas se tornar indisponível, os
aplicativos que estiverem nas outras localizações continuarão a ser executados. A sua permissão de recurso será a mesma
para cada localização que você usar. Para obter mais informações sobre os recursos da plataforma e as localizações em que estão
disponíveis, consulte [Disponibilidade de serviço](/docs/resources?topic=resources-services_region).

O balanceamento de carga global para o console do {{site.data.keyword.cloud_notm}} assegura que, se a localização
geográfica mais próxima para você estiver indisponível, o console exibirá as informações para a próxima localização mais
perto. Dessa maneira, sempre é possível acessar o console sem executar nenhuma ação para acessar os recursos de
que precisa.

É possível visualizar todos os recursos em todas as localizações por padrão por meio da visualização da lista de
recursos no console. Se você desejar
visualizar e trabalhar com os recursos em uma localização específica, expanda o menu **LOCALIZAÇÃO** e
selecione uma localização na lista. 

## Data centers
{: #data_center}

Ao implementar os recursos de infraestrutura, você tem mais opções sobre onde seus dados estão localizados. É possível selecionar um local ou selecionar em uma lista dos data centers do {{site.data.keyword.Bluemix_notm}}. Um *data center* é o local físico que hospeda os recursos de energia, de resfriamento, de cálculo, de rede e de armazenamento usados para serviços e apps. Os data centers não fornecem isolamento de falhas locais como as multizonas em
uma localização. Para obter mais informações, consulte [Localizações
globais para o seu negócio global ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo")](https://www.ibm.com/cloud/data-centers/){: new_window}.

O {{site.data.keyword.Bluemix_notm}} oferece data centers em muitas localizações em todo o mundo. Ao
implementar os recursos da infraestrutura, é possível selecionar em uma lista de data centers no
{{site.data.keyword.Bluemix_notm}}. 


![Mapa de data centers descritos nas tabelas a seguir](images/Global-View.svg)

### América do Norte
{: #na}

| Datacenter | Código  |
|------------------|-------|
| Dallas 01        | dal01 |
| Dallas 05        | dal05 |
| Dallas 06        | dal06 |
| Dallas 07        | dal07 |
| Dallas 09        | dal09 |
| Dallas 10        | dal10 |
| Dallas 12        | dal12 |
| Dallas 13        | dal13 |
| Washington DC 01 | wdc01 |
| Washington DC 04 | wdc04 |
| Washington DC 06 | wdc06 |
| Washington DC 07 | wdc07 |
| San Jose 01      | sjc01 |
| San Jose 03      | sjc03 |
| San Jose 04      | sjc04 |
| Seattle 01       | sea01 |
| Houston 01       | hou01 |
| Montreal 01      | mon01 |
| Toronto 01       | tor01 |
| México 01        | mex01 |
{: caption="Tabela 2. Data centers na América do Norte" caption-side="top"}

### América do Sul
{: #sa}

| Datacenter | Código    |
|------------------|---------|
| São Paulo 01     | sao01   |
{: caption="Tabela 3. Data centers na América do Sul" caption-side="top"}

### Europa
{: #eu}

| Datacenter | Código  |
|------------------|-------|
| Londres 02        | lon02 |
| Londres 04        | lon04 |
| Londres 05        | lon05 |
| Londres 06        | lon06 |
| Frankfurt 02     | fra02 |
| Frankfurt 04     | fra04 |
| Frankfurt 05     | fra05 |
| Milão 01         | mil01 |
| Amsterdã 01     | ams01 |
| Amsterdã 03     | ams03 |
| Paris 01         | par01 |
| Oslo 01          | osl01 |
{: caption="Tabela 4. Data centers na Europa" caption-side="top"}

### Ásia-Pacífico
{: #ap}

| Datacenter | Código  |
|------------------|-------|
| Tóquio 01         | tok02 | 
| Tóquio 04         | tok04 |
| Tóquio 05         | tok05 |
| Seul 01         | seo01 |
| Hong Kong 02     | hkg02 |
| Cingapura 01     | sng01 |
| Sydney 01        | syd01 |
| Sydney 04        | syd04 |
| Sydney 05        | syd05 |
| Melbourne 01     | mel01 |
{: caption="Tabela 5. Data centers na Ásia-Pacífico" caption-side="top"}


## Acordos de Nível de Serviço (SLAs)
{: #SLAs} 

O {{site.data.keyword.Bluemix_notm}} fornece um nível de serviço de disponibilidade 99,5% para múltiplas instâncias de um serviço de plataforma dentro de um ambiente único dedicado ou local.

Para enviar uma solicitação de tempo de inatividade, entre em contato com o [suporte do {{site.data.keyword.Bluemix_notm}}](https://console.cloud.ibm.com/unifiedsupport/supportcenter){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo").

O {{site.data.keyword.Bluemix_notm}} fornece SLAs para os serviços do {{site.data.keyword.Bluemix_notm}} que podem torná-lo elegível para créditos em sua conta. Os
SLAs são a sua única maneira de resolver a falha do {{site.data.keyword.Bluemix_notm}} para atender um
nível de serviço especificado. O {{site.data.keyword.Bluemix_notm}} fornece um nível de serviço de disponibilidade 99,5% para múltiplas instâncias de um serviço de plataforma dentro de um ambiente único dedicado ou local.

Para obter mais informações sobre ambientes dedicados, consulte [IBM Cloud Dedicated](/docs/hybrid?topic=dedicated-dedicated) e para ambientes locais, consulte [Bluemix Local](/docs/hybrid?topic=local-local). 

A descrição completa do serviço para o {{site.data.keyword.Bluemix_notm}} está disponível em
[Termos de serviços em nuvem](http://www-03.ibm.com/software/sla/sladb.nsf/sla/bm){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo").

### SLA de tempo de inatividade de disponibilidade 
{: #avail-downtime}

Você será elegível para um crédito em sua conta se você tiver menos tempo de inatividade do que a
disponibilidade de 99,5%. O tempo de inatividade de disponibilidade é o total de minutos que você não consegue se conectar
a nenhuma de suas instâncias de serviço. O total de minutos de inatividade inicia quando você envia um relatório para o
evento de indisponibilidade e termina quando pelo menos uma das instâncias afetadas está disponível para uso.

O {{site.data.keyword.Bluemix_notm}} fornece um SLA de disponibilidade de 99,95% para: 
- Serviços de nuvem no ambiente público que são configurados para alta disponibilidade, conforme descrito nos detalhes do catálogo para cada serviço. 
- Serviços de nuvem em vários ambientes dedicados ou locais em data centers separados geograficamente. 

| Tipo	 | Descrição	 | Detalhes do suporte|
|-------------------------------------------------------------------------------|--------------------|----------------|
| Ambientes públicos de alta disponibilidade ou múltiplos ambientes dedicados/locais | Outros ambientes | Crédito         |
| <99,95%                                                                       |<99,5%              |10%             |
| <99,90%                                                                       |<99,0%              |25%             |
{: caption="Tabela 6. Nível de serviço de disponibilidade mensal" caption-side="top"}

A porcentagem de disponibilidade é calculada como o número total de minutos em um mês contratado menos o número total de
minutos de inatividade nesse mês, dividido pelo número total de minutos no mês. 

Por exemplo, em um mês de 31 dias, você tem o número total de 44.640 minutos. Se você experimentar seis horas de tempo
de inatividade de disponibilidade, serão 360 minutos de tempo de inatividade. Com apenas seis horas de tempo de
inatividade, você tem 99,19% de disponibilidade. Como 99,19% é menor que 99,90%, você é elegível para um crédito de 25% com um ambiente público ou local.   

```
= (total de 44.640 minutos no mês - 360 minutos de tempo de indisponibilidade) / total de 44.640 minutos no mês =
(total de 44.280 minutos reais disponível) / total de 44.640 de minutos no mês =
99,19% de disponibilidade
```

Os SLAs não incluem tempo de inatividade ou falhas relacionadas às exclusões especificadas, à indisponibilidade da IU do
{{site.data.keyword.Bluemix_notm}}, ao tempo para recarregar, configurar, ativar ou acessar o conteúdo.

O SLA de tempo de inatividade de disponibilidade não inclui os serviços de infraestrutura do {{site.data.keyword.Bluemix_notm}}. 
{: note}

### SLAs de serviços de infraestrutura
{: #iaas-slas}

Os serviços de infraestrutura são servidores bare metal e virtuais, rede, armazenamento e serviços de
segurança. Para localizar uma lista completa de serviços de infraestrutura, procure no catálogo do {{site.data.keyword.Bluemix_notm}} com a tag `iaas`. 

O tempo de inatividade é o total de minutos que um serviço de infraestrutura identificado pelo cliente permanece
indisponível devido à interrupção do serviço com base na indisponibilidade da rede pública, rede privada, energia
da infraestrutura redundante e HVAC. O cálculo do total de minutos de inatividade começa quando a indisponibilidade
validada que afeta o serviço é identificada até o momento em que o serviço está disponível. 

O tempo de inatividade não inclui horário para a manutenção planejada ou comunicada. Para cada período de 30 minutos
contínuos de inatividade, você recebe um crédito na quantia de 5% dos encargos mensais para os serviços identificados
que são diretamente afetados pela indisponibilidade. Você não será elegível para um crédito se o tempo de inatividade
for menor que 30 minutos contínuos. O
tempo de inatividade para diferentes tipos de indisponibilidade não pode ser combinado para atender a esse cálculo. 

### Substituição de hardware de infraestrutura e SLA de upgrade
{: #hw-replaceupgrade-sla}

O {{site.data.keyword.Bluemix_notm}} tenta minimizar o tempo de inatividade substituindo o hardware com falha ou
executando um upgrade de hardware planejado. 

O {{site.data.keyword.Bluemix_notm}} fornece crédito para: 
- Substituição de hardware com base no tempo de substituição a partir do momento em que o
{{site.data.keyword.Bluemix_notm}} verifica que um cliente relatou uma falha de hardware.
- Upgrades de hardware planejados com base no tempo de inatividade total do serviço que recebe o upgrade. 

Os períodos de tempo de nível de serviço excluem qualquer tempo que seja necessário para recarregar o sistema
operacional ou os aplicativos ou o desempenho de tempo pode ser comprometido. Você será elegível para um crédito com base
no encargo mensal para o serviço que é afetado pela substituição ou upgrade de hardware se o
{{site.data.keyword.Bluemix_notm}} falhar em atender a um período de tempo de nível de serviço especificado.

| Período de tempo de nível de serviço  | Porcentagem de crédito |
|---------------------------|----------------|
| ≤ 2 horas                 | Nenhuma           |
| > 2 horas                 | 20%            |
| > 6 horas                 | 40%            |
| > 10 horas                | 60%            |
| > 14 horas                | 80%            |
| > 18 horas                | 80%            |
{: caption="Tabela 7. Crédito com base no encargo mensal para o serviço que é afetado pela substituição ou upgrade de hardware" caption-side="top"}

### Solicitações
{: #claims}

Envie sua solicitação dentro de 60 dias do término do mês contratado em que o nível de serviço foi perdido. Forneça
informações suficientes para identificar o serviço afetado, mensagens de erro e outras informações necessárias para
validar a solicitação. 

O crédito será a compensação mais alta aplicável com base na disponibilidade acumulativa do serviço afetado durante
um mês contratado e calculado usando os encargos mensais para esse serviço afetado. Os créditos não podem exceder 25% do encargo mensal.

Para enviar uma solicitação de tempo de inatividade, entre em contato com o [suporte do {{site.data.keyword.Bluemix_notm}}](https://console.cloud.ibm.com/unifiedsupport/supportcenter){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo").

### Exclusões
{: #exclusions}

Nenhum crédito é fornecido para falha em atender a um SLA devido a:
- Problemas com conteúdo, tecnologia, designs ou instruções fornecidos pelo cliente ou pela comunidade
- Serviços de nuvem betas, experimentais ou gratuitos.
- Pacotes de construção não IBM
- Configurações e plataformas do sistema não suportadas
- Falhas de infraestrutura do cliente, incluindo rede, hardware, instalação ou energia
- Ações de administração do sistema, comandos ou transferências de arquivos do cliente
- Erros ou falhas do cliente ao fornecer informações necessárias ou acesso para resolver uma indisponibilidade
- Incidentes de segurança causados pelo cliente ou teste de segurança
- Outras causas além do controle razoável da IBM

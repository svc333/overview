---

copyright:

  years: 2017

lastupdated: "2017-12-15"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:tip: .tip}

# Cloud Resource Names
{: #crn}

Os Cloud Resource Names (CRNs) identificam exclusivamente os recursos do {{site.data.keyword.Bluemix_notm}}. Um CRN é usado para especificar um recurso de uma maneira que é inequívoca e garantida ser globalmente exclusiva, como nas políticas e nos serviços do {{site.data.keyword.Bluemix_notm}} Identidade e Acesso Management (IAM) listados no catálogo de nuvem.

Um CRN é formado de uma concatenação de "segmentos" que identificam hierarquicamente o recurso, seu local e o serviço ao qual ele pertence. O delimitador de segmento é configurado para ':' (ou seja, o caractere dois-pontos). Todos os CRNs iniciam com o identificador de segmento 'crn'.


## Formato de CRN
{: #format}

O formato canônico base de um CRN é:

**crn:[version](#version):[cname](#cname):[ctype](#ctype):[service-name](#service-name):[location](#location):[scope](#scope):[service-instance](#service-instance):[resource-type:resource](#resource-type)**


## version
{: #version}

O segmento `version` identifica a versão do formato de CRN. Atualmente, o único valor de segmento de versão válido é **v1**.


## cname
{: #cname}

O segmento `cname` identifica a instância da nuvem e é um identificador alfanumérico que identifica exclusivamente a instância da nuvem que contém o recurso. Um `cname` identifica efetivamente um plano de controle independente que possui o recurso identificado. O `cname` deve ser `bluemix` para usuários do {{site.data.keyword.Bluemix_notm}}.


## ctype
{: #ctype}

O segmento `ctype` identifica o tipo de instância da nuvem que é representado pelo `cname` especificado.

>Valores válidos:
  - public - todos os serviços que estão disponíveis no catálogo público.
  - dedicated - somente para ambientes dedicados {{site.data.keyword.Bluemix_notm}} atuais.
  - local - todos os serviços que são implementados localmente em seu próprio ambiente.


## service-name
{: #service-name}

O segmento `service-name` identifica exclusivamente uma capacidade (serviço, componente, produto) que está sendo oferecida pela nuvem. A capacidade pode ser um serviço fornecido pelo usuário, como com os serviços que estão listados no catálogo do {{site.data.keyword.Bluemix_notm}} ou um componente arquitetural interno crítico para a funcionalidade do {{site.data.keyword.Bluemix_notm}}.

O `service-name` indica o serviço ao qual o recurso pertence e o {{site.data.keyword.Bluemix_notm}} cumpre a exclusividade global de nomes de serviços. O `service-name` deve ser alfanumérico, em minúsculas, sem espaços ou caracteres especiais diferentes de '-'.

Para serviços que são registrados no Catálogo do {{site.data.keyword.Bluemix_notm}}, o `service-name` deve corresponder a um dos serviços registrados para o serviço de Catálogo global do {{site.data.keyword.Bluemix_notm}}. É a propriedade `name` retornada pela API do serviço de Catálogo global do {{site.data.keyword.Bluemix_notm}} `GET https://resource-catalog.bluemix.net/api/v1/{id}` para a instância de recurso correspondente ou o `service-name` exibido pela interface da linha de comandos: `bx service offerings` na coluna `service`.


## localização
{: #location}

A geografia/região/zona/data center da nuvem em que o recurso reside.

O `location` deve ser um dos valores a seguir:

### Global

 * `global`

### Geografias

 * `us`
 * `eu`
 * `cn`
 * `ap`

### Regiões

 * `us-south`
 * `us-east`
 * `au-syd`
 * `eu-gb`
 * `eu-de`

### Data Centers


| | | | | |
|---|---|---|---|---|
| AMS01  | AMS03  | CHE01  | DAL01  |  DAL05  |
| DAL06  | DAL07  | DAL09  | DAL10  |  DAL12  |
| DAL13  | FRA02  | HKG02  | HOU02  |  LON02  |
| MEL01  | MEX01  | MIL01  | MON01  |  OSL01  |
| PAR01  | SJC01  | SJC03  | SAO01  |  SEA01  |
| SEO01  | SNG01  | SYD01  | TOK02  |  TOR01  |
| WDC01  | WDC04  | WDC06  | WDC07  |
{: caption="Tabela 1. Valores válidos de `Data Center`" caption-side="top"}

Alguns recursos não requerem uma região (eles podem ser considerados como `global`). Nesse caso, o segmento `region` é configurado para `global`.
{: tip}


## escopo
{: #scope}

O segmento `scope` identifica a restrição ou o proprietário do recurso. Alguns recursos não requerem um proprietário (eles podem ser considerados como `global`). Nesse caso, o segmento `scope` está vazio (uma sequência em branco).

O valor do segmento `scope` deve ser formatado como `{scopePrefix}`/`{id}`. O `scopePrefix` representa o formato usado para identificar o proprietário ou a restrição. O `id` representa a identidade do proprietário ou restrição em um formato que é específico para o `scopePrefix`.

| Tipo de escopo | Prefixo do escopo | Uso | Exemplo |
| --- | --- | --- | --- |
| Conta | a/`{account id}` | A conta na qual o recurso foi criado. | a/292558 |
| Organização | o/`{org guid}` | A organização do {{site.data.keyword.Bluemix_notm}} à qual o recurso foi designado. | o/4716e2d1-35b7-431f-891a-b552bf0b3c66 |
| Espaço | s/`{space guid}` | O espaço do {{site.data.keyword.Bluemix_notm}} ao qual o recurso foi designado. | s/48b3cdcd-e804-4398-9032-73065863ad7c |
{: caption="Tabela 2. Uso de `scope`" caption-side="top"}

O `account id` deve ser o ID da conta IBM (contas vinculadas do {{site.data.keyword.Bluemix_notm}} e do Softlayer).


## service-instance
{: #service-instance}

O segmento `service-instance` identifica a instância de serviço com exclusividade. O formato do segmento `service-instance` varia por serviço. Cada serviço deve documentar o formato de seu `service_instance` como parte de seus metadados de serviço. Alguns serviços não têm instâncias porque a instância é global e, neste caso, o campo `service-instance` estará em branco.

O `service-instance` deve ser alfanumérico, em minúsculas, sem espaços ou caracteres especiais diferentes de '-' e '/'.

Como um exemplo, uma ferramenta DevOps para rastrear e planejar itens de trabalho pode ter um ID de instância `GUID` simples ("1234-5678-9012-3456"), em que o componente de política de um serviço de grupo de ajuste automático de escala pode usar uma convenção de nomenclatura hierárquica e ter um segmento `service-id` de:

>`c7a27f55-d35e-4153-b044-8ca9155fc467/my-test-asg1/my-scaleout-policy`


## resource-type, resource
{: #resource-type}

O valor dos segmentos `resource-type` e `resource` variam por serviço. Um serviço é necessário para documentar seus `resource types` suportados e o formato do `resource` como parte de seus metadados de serviço.

Como um exemplo, uma imagem no contêiner de recibos do cliente em um serviço de Armazenamento de objeto pode ter um `resource-type` de `object` e um `resource_ value` de `CustomerReceipts/clientdinner.png`. 

O `resource-type` deve ser alfanumérico, em minúsculas, sem espaços ou caracteres especiais diferentes de '-'. Um serviço pode decidir que o `resource-type` é opcional, em cujo caso ele seria deixado em branco.


## Exemplos de CRN
{: #crn_examples}

A seguir está uma lista de exemplos de CRN.

| Exemplo | Valor |
| --- | --- |
| Contêiner | `crn:v1:bluemix:public:containers-kubernetes:us-south:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:8042b2a8af6a4a5cbf6dbe09e07311d2:worker:kube-hou02-pa8042b2a8af6a4a5cbf6dbe09e07311d2-w1:`|
| Grupo de recursos | `crn:v1:bluemix:public:resource-controller: global:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:resource-group:59bcbfa6ea2f006b4ed7094c1a08dcdd` |
| Instância de Serviço | `crn:v1:bluemix:public:cloud-object-storage:global:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:1a0ec336-f391-4091-a6fb-5e084a4c56f4::` |
| Depósito | `crn:v1:bluemix:public:cloud-object-storage:global:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:1a0ec336-f391-4091-a6fb-5e084a4c56f4:bucket:mybucket` |
{: caption="Tabela 3. Exemplos de CRN" caption-side="top"}



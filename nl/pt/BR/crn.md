---

copyright:

  years: 2017, 2019

lastupdated: "2019-05-06"

keywords: crn, cloud resource name

subcollection: overview

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:tip: .tip}

# Cloud Resource Names
{: #crn}

Os Cloud Resource Names (CRNs) identificam exclusivamente os recursos do {{site.data.keyword.Bluemix_notm}}. Um CRN é usado para especificar um recurso de uma maneira que é inequívoca e garantida ser globalmente exclusiva, como nas políticas e nos serviços do {{site.data.keyword.Bluemix_notm}} Identidade e Acesso Management (IAM) listados no catálogo de nuvem.

Um CRN é formado de uma concatenação de "segmentos" que identificam hierarquicamente o recurso, seu local e o serviço ao qual ele pertence. O delimitador de segmento é configurado como ':' (o caractere de dois-pontos). Todos os CRNs iniciam com o identificador de segmento `crn`.


## Formato CRN
{: #format-crn}

O formato canônico base de um CRN é:

`   crn:version:cname:ctype:service-name:location:scope:service-instance:resource-type:resource
   `


## version
{: #version-crn}

O segmento `version` identifica a versão do formato de CRN. Atualmente, o único valor de segmento de versão válido é `v1`.


## cname
{: #cname-crn}

O segmento `cname` identifica a instância da nuvem e é um identificador alfanumérico que identifica exclusivamente a instância da nuvem que contém o recurso. Um `cname` identifica efetivamente um plano de controle independente que possui o recurso identificado. O valor para o segmento `cname` deve ser `bluemix` para usuários do {{site.data.keyword.Bluemix_notm}}.


## ctype
{: #ctype-crn}

O segmento `ctype` identifica o tipo de instância de nuvem que é representado pelo segmento `cname` especificado.

 Valores válidos:
  - `public`: todos os serviços disponíveis no catálogo público
  - `dedicated`: somente para ambientes dedicados atuais do {{site.data.keyword.Bluemix_notm}}
  - `local`: todos os serviços implementados localmente em seu próprio ambiente


## service-name
{: #service-name-crn}

O segmento `service-name` identifica exclusivamente uma capacidade (serviço, componente, produto) que está sendo oferecida pela nuvem. O recurso pode ser um serviço fornecido pelo usuário, como com os serviços listados no catálogo do {{site.data.keyword.Bluemix_notm}} ou um componente arquitetural interno crítico para a funcionalidade do {{site.data.keyword.Bluemix_notm}}.

O segmento `service-name` indica o serviço ao qual o recurso pertence e o {{site.data.keyword.Bluemix_notm}} utiliza exclusividade global de nomes de serviço. O segmento `service-name` deve ser alfanumérico, minúsculo e não apresentar espaços ou caracteres especiais diferentes de '-'.

Para os serviços registrados no catálogo do {{site.data.keyword.Bluemix_notm}}, o segmento `service-name` deve corresponder a um dos serviços registrados para o serviço Global Catalog do {{site.data.keyword.Bluemix_notm}}. É a propriedade `name` que é retornada pela API do serviço Global Catalog do {{site.data.keyword.Bluemix_notm}} `GET https://globalcatalog.cloud.ibm.com/api/v1/{id}` para a instância de recurso correspondente ou o valor `service-name` exibido pela interface da linha de comandos: `ibmcloud service offerings` na coluna `service`.


## localização
{: #location-crn}

A geografia/região/zona/data center da nuvem em que o recurso reside.

O segmento `location` deve ser um dos valores a seguir:

### Global
{: #global-crn}

 * `global`

### Geografias
{: #geos-crn}

 * `us`
 * `eu`
 * `cn`
 * `ap`

### Regiões
{: #regions-crn}

 * `us-south`
 * `us-east`
 * `au-syd`
 * `eu-gb`
 * `eu-de`
 * ` jp-tok `

### Data centers
{: #dc-crn}

 * ` AMS01  `
 * ` AMS03  `
 * ` CHE01  `
 * ` DAL01  `
 * `  DAL05  `
 * ` DAL06  `
 * ` DAL07  `
 * ` DAL09  `
 * ` DAL10  `
 * `  DAL12  `
 * ` DAL13  `
 * ` FRA02  `
 * ` HKG02  `
 * ` HOU02  `
 * `  LON02  `
 * ` MEL01  `
 * ` MEX01  `
 * ` MIL01  `
 * ` MON01  `
 * `  OSL01  `
 * `PAR01 `
 * ` SJC01  `
 * ` SJC03  `
 * ` SAO01  `
 * `  SEA01  `
 * ` SEO01  `
 * ` SNG01  `
 * ` SYD01  `
 * ` TOK02  `
 * `  TOR01  `
 * ` WDC01  `
 * ` WDC04  `
 * ` WDC06  `
 * ` WDC07  `

Alguns recursos não requerem uma região, pois podem ser considerados globais. Nesse caso, o segmento `region` é configurado para `global`.
{: tip}


## escopo
{: #scope-crn}

O segmento `scope` identifica a restrição ou o proprietário do recurso. Alguns recursos não requerem um proprietário (eles podem ser considerados como `global`). Nesse caso, o segmento `scope` está vazio (uma sequência em branco).

O valor do segmento `scope` deve ser formatado como `{scopePrefix}`/`{id}`. O `scopePrefix` representa o formato usado para identificar o proprietário ou a restrição. O `id` representa a identidade do proprietário ou restrição em um formato que é específico para o `scopePrefix`.

| Tipo de escopo | Prefixo do escopo | Uso | Exemplo |
| --- | --- | --- | --- |
| Conta | a/`{account id}` | A conta na qual o recurso foi criado. | `a/292558` |
| Organização | o/`{org guid}` | A organização do {{site.data.keyword.Bluemix_notm}} à qual o recurso foi designado. | `o/4716e2d1-35b7-431f-891a-b552bf0b3c66` |
| Espaço | s/`{space guid}` | O espaço do {{site.data.keyword.Bluemix_notm}} ao qual o recurso foi designado. | `s/48b3cdcd-e804-4398-9032-73065863ad7c` |
{: caption="Tabela 1. Uso de `scope`" caption-side="top"}



## service-instance
{: #service-instance-crn}

O segmento `service-instance` identifica a instância de serviço com exclusividade. O formato do segmento `service-instance` varia por serviço. Cada serviço deve documentar o formato de seu segmento `service_instance` como parte de seus metadados de serviço. Alguns serviços não têm instâncias porque a instância é global e, nesse caso, o campo `service-instance` fica em branco.

A `service-instance` deve ser alfanumérica, em minúsculas, sem espaços ou caracteres especiais diferentes de '-' e '/'.

Como exemplo, uma ferramenta do DevOps para rastrear e planejar itens de trabalho pode ter um ID de instância `GUID` simples ("1234-5678-9012-3456") em que o componente de política de um serviço de grupo de escala automática pode usar uma convenção de nomenclatura hierárquica e ter um segmento `service-id` de:

>`c7a27f55-d35e-4153-b044-8ca9155fc467/my-test-asg1/my-scaleout-policy`

Também é possível obter uma CRN por meio de um recurso do {{site.data.keyword.Bluemix_notm}}
usando o comando da CLI a seguir:
```
ibmcloud resource service-instance
```
{: codeblock}

## resource-type, resource
{: #resource-type-crn}

O valor dos segmentos `resource-type` e `resource` variam por serviço. É necessário um serviço para documentar seu segmento `resource types` suportado e o formato do segmento `resource` como parte de seus metadados de serviço.

Como exemplo, uma imagem no contêiner de recibos do cliente em um serviço Object Storage pode ter um segmento `resource-type` de `object` e um valor `resource` de `CustomerReceipts/clientdinner.png`.

O segmento `resource-type` deve ser alfanumérico, minúsculo e não apresentar espaços ou caracteres especiais diferentes de '-'. Um serviço pode decidir que o segmento `resource-type` seja opcional e, nesse caso, ele ficará em branco.


## Exemplos de CRN
{: #crn_examples}

A tabela a seguir fornece uma lista de exemplos de CRN.

| Exemplo | Valor |
| --- | --- |
| Trabalhador do Kubernetes | `crn:v1:bluemix:public:containers-kubernetes:us-south:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:8042b2a8af6a4a5cbf6dbe09e07311d2:worker:kube-hou02-pa8042b2a8af6a4a5cbf6dbe09e07311d2-w1` |
| Grupo de recursos | `crn:v1:bluemix:public:resource-controller: global:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:resource-group:59bcbfa6ea2f006b4ed7094c1a08dcdd` |
| Instância de Serviço | `crn:v1:bluemix:public:cloud-object-storage:global:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:1a0ec336-f391-4091-a6fb-5e084a4c56f4::` |
| Depósito | `crn:v1:bluemix:public:cloud-object-storage:global:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:1a0ec336-f391-4091-a6fb-5e084a4c56f4:bucket:mybucket` |
{: caption="Tabela 2. Exemplos de CRN" caption-side="top"}

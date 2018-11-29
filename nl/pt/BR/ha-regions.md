---

copyright:

  years: 2018

lastupdated: "2018-11-15"

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:pre: .pre}
{:tip: .tip}

# Locais para implementação de recurso 
{: #ov_intro_reg}

É possível criar aplicativos e instâncias de serviço em diferentes localizações com a mesma infraestrutura do
{{site.data.keyword.cloud_notm}} para o gerenciamento de aplicativo e a mesma visualização de
detalhes de uso para o faturamento. É possível implementar os aplicativos para a localização mais próxima dos clientes
para obter baixa latência de aplicativo. 

Para tratar de problemas de segurança, também é possível selecionar a localização na qual você deseja manter os
dados do aplicativo. Ao construir os aplicativos em mais de uma localização, se uma delas se tornar indisponível, os
aplicativos que estiverem nas outras localizações continuarão a ser executados. A sua permissão de recurso será a mesma
para cada localização que você usar. Para obter mais informações sobre os recursos da plataforma e as localizações em que estão
disponíveis, consulte [Disponibilidade de serviço](/docs/resources/service_region.html).

O balanceamento de carga global para o console assegura que se a localização geográfica mais próxima de você
estiver inativa, o console exibirá as informações para a localização mais próxima seguinte. Dessa forma, é possível sempre acessar o console sem tomar qualquer ação para acessar as informações de que você precisa.

Por meio do painel, é possível visualizar todos os recursos em todas as localizações por padrão. Se você desejar
visualizar e trabalhar com os recursos em uma localização específica, expanda o menu **LOCALIZAÇÃO** e
selecione uma localização na lista. 

Também é possível usar a interface da linha de comandos para se conectar à localização do
{{site.data.keyword.cloud_notm}} com a qual deseja trabalhar usando o comando `ibmcloud
api` e especificar o terminal da API da localização. Por exemplo, insira o comando a seguir para se conectar ao
{{site.data.keyword.cloud_notm}} Londres:

```
Ibmcloud api https://api.eu-gb.bluemix.net
```

Um prefixo exclusivo é designado para cada localização. O {{site.data.keyword.cloud_notm}} fornece as
localizações e os prefixos de localização a seguir.

| **Localização** | **Endpoint da API** |
|-----------------|-------------------|
| Dallas | api.ng.bluemix.net |
| Sydney | api.au-syd.bluemix.net |
| Frankfurt | api.eu-de.bluemix.net |
| Londres | api.eu-gb.bluemix.net |
| Washington DC | api.us-east.bluemix.net |
| Tóquio | api.jp-tok.bluemix.net |
{: caption="Tabela 1. {{site.data.keyword.cloud_notm}}  lista de locais" caption-side="top"}

Ao implementar os recursos da infraestrutura, você tem mais opções sobre onde o seu conteúdo está localizado. É
possível selecionar uma localização ou selecionar em uma lista de data centers no {{site.data.keyword.Bluemix_notm}}. Para obter mais informações, consulte  [ {{site.data.keyword.cloud_notm}}  datacenters ](data-centers.html).

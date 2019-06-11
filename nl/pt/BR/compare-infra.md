---
copyright:
  years: 2019
lastupdated: "2019-06-04"

keywords: understanding infrastructure, vpc, classic infrastructure, cloud environment

subcollection: overview

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}
{:tip: .tip}
{:note: .note}

# Comparando os ambientes de infraestrutura do {{site.data.keyword.cloud_notm}}
{: #compare-infrastructure}

Compare as principais diferenças entre os ambientes de infraestrutura do {{site.data.keyword.cloud}} para decidir qual deles é o melhor para suas cargas de trabalho e seus aplicativos.
{: shortdesc}

Se não estiver familiarizado com os tipos de ambiente, revise as descrições a seguir.

* A infraestrutura clássica é nossa plataforma de IaaS existente. Esse ambiente é melhor para cargas de trabalho de aumento e deslocamento, permitindo que você mova aplicativos rapidamente e mantenha a mesma arquitetura.
* A infraestrutura de VPC é nossa nova plataforma de IaaS, baseada em rede definida por software e ideal para aplicativos nativos da nuvem.

A infraestrutura clássica e a infraestrutura de VPC têm o mesmo custo, então é possível se concentrar em qual ambiente melhor atende às suas necessidades.
{: note}

## Diferenciadores de cálculo
{: #compare-compute}

Consulte a tabela a seguir para ver as diferenças de cálculo entre a infraestrutura clássica e a de VPC. Os diversos diferenciadores estão listados na coluna Categoria e as descrições estão listadas nas colunas Infraestrutura clássica e Infraestrutura de VPC. 

| Categoria   |  Infraestrutura clássica   | Infraestrutura de VPC |
| ---------- | ------------------------- | ------------------ |
|  Serviços  |Catálogo completo de serviços, como o {{site.data.keyword.baremetal_short}}, as instâncias do {{site.data.keyword.BluVirtServers_short}}, o VMware e o SAP | Somente instâncias do {{site.data.keyword.BluVirtServers_short}} |
| Desempenho e disponibilidade | | Melhor disponibilidade possível por meio da arquitetura de zona |
| Venda | Faturamento por hora e mensal, além de recursos de suspensão de faturamento | Por hora, com suspensão de faturamento e com desconto de uso mantido |
| Famílias de servidor virtual | Público, dedicado, temporário, reservado | Somente pública |
| Perfis | Todos os perfis, incluindo os perfis da GPU | Perfis de memória, balanceados e de cálculo com opções superiores de RAM e vCPU |
| Imagens suportadas | Conjunto completo de bancos de imagens prévios, além de imagens customizadas | Conjunto limitado de bancos de imagens prévios |
| Integração da Plataforma | | Integração do grupo de recursos e do IAM para uma experiência unificada |
{: caption="Tabela 1. Comparação de cálculo" caption-side="top"}

## Diferenciadores de rede
{: #compare-network}

Consulte a tabela a seguir para ver as diferenças de rede entre a infraestrutura clássica e a de VPC. Os diversos diferenciadores estão listados na coluna Categoria e as descrições estão listadas nas colunas Infraestrutura clássica e Infraestrutura de VPC. 

| Categoria   |  Infraestrutura clássica   | Infraestrutura de VPC |
| ---------- | ------------------------- | ------------------ |
| Construção de local    | Data centers e PODs <br>(Pode ser necessário que o VLAN Spanning conecte dois pods/data centers diferentes e a compra de gateways para controlar e rotear o tráfego)| Modelo regional que abstrai a infraestrutura para que não seja necessário se preocupar com os locais dos pods.|
| Funções e serviços de rede |Dispositivos físicos e virtuais de diversos fornecedores | Funções de rede nativas da nuvem (VPNs, LBaaS)<br>(Isolamento de VPC, recursos dedicados extraídos da nuvem pública, com mais opções para VPNs, LBaaS, diversas instâncias do vNIC e tamanhos de sub-rede maiores) |
| endereços IP | Endereços IPv6 suportados | Somente endereços IPv4 |
| Roteamento de gateway | Use um dispositivo de rede virtual ou físico (Virtual Router Appliance, Vyatta, Juniper vSRX, Fortinet FSA) | O roteamento do tráfego é manipulado por serviços de IP flutuante e por um gateway público |
| NAT (Network Address Translation) | Use um dispositivo de rede virtual ou físico (Virtual Router Appliance, Vyatta, Juniper vSRX, Fortinet FSA) | Suportado pela funcionalidade Bring-your-own-IP (BYOIP)  |
| Rede privada virtual (VPN) do IPsec | Use um dispositivo de rede virtual ou físico (Virtual Router Appliance, Vyatta, Juniper vSRX, Fortinet FSA) | Suportado com a oferta de VPN como um serviço |
|  Balanceamento de carga elástico | Cloud Load Balancer  | Balanceador de carga para VPC |
| Balanceamento de carga global| Cloud Internet Services, Citrix Netscaler MPX | Serviços de Internet na nuvem |
|Conectividade híbrida | Solução NAT para fazer a ligação entre o IBM Cloud e seu ambiente de TI | Traga seu próprio endereço IP privado sem túneis NAT ou IPSec <br>Nota: é possível permitir que sua VPC acesse os recursos da infraestrutura clássica.|
{: caption="Tabela 2. Comparação de rede" caption-side="top"}

## Diferenciadores de armazenamento
{: #compare-storage}

|  Infraestrutura clássica   | Infraestrutura de VPC |
| ------------------------- | ------------------ |
|Conjunto robusto de ofertas de serviços de armazenamento, armazenamento de bloco (iSCSI) e armazenamento de arquivos (baseado em NFS)| Armazenamento de bloco como o disco de inicialização primário (com gerenciamento de ciclo de vida básico) e volumes de dados secundários  <br> Nota: a criptografia de volume está disponível durante o fornecimento.|
{: caption="Tabela 3. Comparação de armazenamento" caption-side="top"}

## Diferenciadores de segurança
{: #compare-security}

|  Infraestrutura clássica   | Infraestrutura de VPC |
| ---------- | ------------------------- |
|Vyatta, Fortigate, Juniper vSRX, grupos de segurança para VSIs| Grupos de segurança, listas de controle de acesso (ACLs) à rede|
{: caption="Tabela 4. Comparação de segurança" caption-side="top"}

## Diferenciadores de API
{: #compare-apis}

|  Infraestrutura clássica   | Infraestrutura de VPC |
| ------------------------- | ------------------ |
|{{site.data.keyword.slapi_short}} (SLAPI) existente| Nova API baseada em REST e de fácil uso por desenvolvedores |
{: caption="Tabela 5. Comparação de API" caption-side="top"}

## Próximas Etapas
{: #compare-nextsteps}

Para revisar todos os nossos recursos da infraestrutura de VPC, consulte [Sobre a nuvem privada virtual](/docs/vpc-on-classic?topic=vpc-on-classic-about). Para começar a explorar a infraestrutura como um todo, consulte [Construindo sua infraestrutura](/docs/overview?topic=overview-first-steps-it-ops).

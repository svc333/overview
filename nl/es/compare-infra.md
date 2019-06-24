---
copyright:
  years: 2019
lastupdated: "2019-06-05"

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

# Comparación entre entornos de la infraestructura de {{site.data.keyword.cloud_notm}}
{: #compare-infrastructure}

Compare las principales diferencias entre los entornos de la infraestructura de {{site.data.keyword.cloud}} para decidir cuál se ajusta mejor a sus cargas de trabajo y a sus aplicaciones.
{: shortdesc}

Si no está familiarizado con los tipos de entorno, revise las siguientes descripciones.

* Infraestructura clásica es la plataforma IaaS existente. Este entorno se ajusta a las cargas de trabajo que se pueden migrar a la nube con pocas o sin modificaciones y le permite mover las aplicaciones rápidamente y conservar la misma arquitectura.
* La infraestructura VPC es nuestra nueva plataforma IaaS, basada en red definida por software que resulta ideal para aplicaciones nativas de la nube.

La infraestructura clásica y la infraestructura VPC no tienen diferencias en cuanto a coste, por lo que se puede centrar en el entorno que mejor se ajuste a sus necesidades.
{: note}

## Diferenciadores de cálculo
{: #compare-compute}

Consulte la tabla siguiente para ver las diferencias en cuanto a cálculo entre la infraestructura clásica y VPC. 

| Categoría   |  Infraestructura clásica   | Infraestructura VPC |
| ---------- | ------------------------- | ------------------ |
|  Servicios  |Catálogo completo de servicios, como {{site.data.keyword.baremetal_short}}, instancias de {{site.data.keyword.BluVirtServers_short}}, VMware, SAP | Solo instancias de {{site.data.keyword.BluVirtServers_short}} |
| Rendimiento y disponibilidad | | La mejor disponibilidad que se puede conseguir mediante una arquitectura de zona |
| Tarifas | Facturación por hora y por mes, más características de suspensión de la facturación | Facturación por hora, suspensión de facturación y descuento por uso continuado |
| Familias de servidores virtuales | Público, dedicado, transitorio, reservado | Sólo público |
| Perfiles | Todos los perfiles, incluidos los perfiles GPU | Perfiles equilibradores, de cálculo y de memoria con opciones superiores de RAM y de vCPU |
| Imágenes admitidas | Conjunto completo de imágenes previas, más imágenes personalizadas | Conjunto limitado de imágenes previas|
| Integración de plataformas | | Integración de IAM y de grupo de recursos para ofrecer una experiencia unificada |
{: row-headers}
{: class="comparison-table"}
{: caption="Tabla 1. Comparaciones en cuanto a cálculo" caption-side="top"}
{: summary="This table has row and column headers. The row headers identify possible features. The column headers indentify the differentiators between classic infrastructure and VPC infrastructure. To understand the differences between environments, navigate to the row and find the details for the feature that you're interested in."}

## Diferenciadores de red
{: #compare-network}

Consulte la tabla siguiente para ver las diferencias en cuanto a red entre la infraestructura clásica y VPC.  

| Categoría   |  Infraestructura clásica   | Infraestructura VPC |
| ---------- | ------------------------- | ------------------ |
| Construcción de ubicación    | Centros de datos y pods <br>(Es posible que se requiera una ampliación de VLAN para conectar dos pods o centros de datos distintos y la adquisición de pasarelas para controlar y direccionar el tráfico) | Modelo regional que sintetiza la infraestructura para que no deba preocuparse por las ubicaciones de los pods.|
| Funciones y servicios de red |Dispositivos físicos y virtuales de distintos proveedores | Funciones de red nativas de la nube (VPNs, LBaaS)<br>(Aislamiento de VPC, recursos dedicados de la nube pública, con más opciones para VPNs, LBaaS, varias instancias de vNIC y tamaños mayores de subred) |
| Direcciones IP | Se admiten direcciones IPv6 | Solo direcciones IPv4 |
| Direccionamiento de pasarela | Utilice un dispositivo de red virtual o físico (Virtual Router Appliance, Vyatta, Juniper vSRX, Fortinet FSA) | La pasarela pública y los servicios de IP flotante manejar el direccionamiento del tráfico |
| Conversión de direcciones de red (NAT) | Utilice un dispositivo de red virtual o físico (Virtual Router Appliance, Vyatta, Juniper vSRX, Fortinet FSA) | Recibe soporte de la funcionalidad BYOIP (Traer su propia IP)  |
| Red privada virtual IPsec (VPN) | Utilice un dispositivo de red virtual o físico (Virtual Router Appliance, Vyatta, Juniper vSRX, Fortinet FSA) | Recibe soporte con la oferta VPN como servicio |
|  Equilibrio de carga elástico | Cloud Load Balancer  | Load Balancer for VPC |
| Equilibrio de carga global| Cloud Internet Services, Citrix Netscaler MPX | Cloud Internet Services |
|Conectividad híbrida | Solución NAT de puente entre IBM Cloud y su entorno de TI | Traiga su propia dirección IP privada sin NAT o túneles IPSec <br>Nota: puede habilitar su VPC para que acceda a los recursos de la infraestructura clásica. |
{: row-headers}
{: class="comparison-table"}
{: caption="Tabla 2. Comparación entre redes" caption-side="top"}
{: summary="This table has row and column headers. The row headers identify possible features. The column headers indentify the differentiators between classic infrastructure and VPC infrastructure. To understand the differences between environments, navigate to the row and find the details for the feature that you're interested in."}

## Diferenciadores de almacenamiento
{: #compare-storage}

Consulte la tabla siguiente para ver las diferencias en cuanto a almacenamiento entre la infraestructura clásica y VPC.

|  Infraestructura clásica   | Infraestructura VPC |
| ------------------------- | ------------------ |
|Potente conjunto de servicios de almacenamiento, ofertas de almacenamiento en bloque (iSCSI) y de almacenamiento de archivos (basado en NFS)| Almacenamiento en bloque como disco de arranque primario (con gestión básica del ciclo de vida) y volúmenes de datos secundarios  <br> Nota: el cifrado de volúmenes está disponible durante el suministro.|
{: caption="Tabla 3. Comparación entre almacenamientos" caption-side="top"}

## Diferenciadores de seguridad
{: #compare-security}

Consulte la tabla siguiente para ver las diferencias en cuanto a seguridad entre la infraestructura clásica y VPC.

|  Infraestructura clásica   | Infraestructura VPC |
| ---------- | ------------------------- |
|Vyatta, Fortigate, Juniper vSRX, grupos de seguridad para VSIs| Grupos de seguridad, listas de control de acceso (ACL) a la red|
{: caption="Tabla 4. Comparación entre seguridad" caption-side="top"}

## Diferenciadores de API
{: #compare-apis}

Consulte la tabla siguiente para ver las diferencias en cuanto a API entre la infraestructura clásica y VPC.

|  Infraestructura clásica   | Infraestructura VPC |
| ------------------------- | ------------------ |
|{{site.data.keyword.slapi_short}} (SLAPI) existente| Nueva API basada en REST pensada para los desarrolladores |
{: caption="Tabla 5. Comparación entre API" caption-side="top"}

## Pasos siguientes
{: #compare-nextsteps}

Para revisar todas nuestras prestaciones de la infraestructura VPC, consulte el apartado [Acerca de la nube privada virtual](/docs/vpc-on-classic?topic=vpc-on-classic-about). Para empezar a explorar la infraestructura a nivel general, consulte [Creación de la infraestructura](/docs/overview?topic=overview-first-steps-it-ops).

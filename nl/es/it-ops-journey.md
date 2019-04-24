---

copyright:
  years: 2018, 2019
lastupdated: "2019-01-04"


---
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}
{:tip: .tip}
{:note: .note}

# Explorar el trayecto del administrador de operaciones de TI en {{site.data.keyword.cloud_notm}}
{: #it-ops}

A medida que muchas organizaciones se trasladan a un entorno en la nube, ya sea local o alojado en centros de datos, el rol del administrador de operaciones de TI se vuelve a definir. El ámbito y la complejidad de este cambio aumentan significativamente en función del tipo de entorno en el que su organización desee desplegar. 
{: .shortdesc}

Antes de trasladarse a la nube, trabajó con un entorno seguro propiamente con sistemas conectados a la LAN privada o a intranet. Ahora se espera que realice las tareas siguientes en un entorno de nube:
 
  * Aprovisionar los componentes del sistema desde "algún lugar" 
  * Comprender las implicaciones de la red y los retos de seguridad.
  * Trabajar con distintas tecnologías.  
  * Integrar el nuevo entorno con herramientas que no forman parte de la pila de nube de forma nativa. 
  * Continuar ofreciendo soporte a los clientes internos como si todavía tuviera un centro de datos local.

{{site.data.keyword.cloud}} quiere ofrecerle soporte al 100% durante el proceso. Entre los recursos disponibles que se proporcionan se incluyen una documentación coherente, herramientas de planificación, especialistas de soporte cualificados y una comunidad de usuarios activa. Pongámonos en marcha. 

## Comprensión de los aspectos básicos
{: #basics}

### Modelos de servicio en la nube
{: #cloud-svc-models}

Hay tres tipos de modelos de servicio en la nube: Infraestructura como servicio (IaaS), Plataforma como servicio (PaaS) y Software como servicio (SaaS). En la figura 1 se explica cuál es la función de cada modelo de servicio. Para obtener más información, consulte [IaaS, PaaS, y SaaS - Modelos de servicio de IBM Cloud](https://www.ibm.com/cloud/learn/iaas-paas-saas){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo").

![Figura 1. Modelos de servicio en la nube](images/cloud-svc-models.png "Modelos de servicio en la nube")

Con el modelo IaaS, el proveedor es únicamente responsable de mantener la infraestructura subyacente y, de forma opcional, de instalar software como, por ejemplo, sistemas operativos, aplicaciones y bases de datos. Tiene un acceso limitado a la infraestructura subyacente y es responsable de instalar el software o pedir a su proveedor de servicios que lo haga. También es responsable del resto de los trabajos de mantenimiento, que incluyen los Service Packs, los software de virus y los parches.

Con el modelo PaaS el proveedor es el responsable de los sistemas mediante el sistema operativo, y de toda la gestión de la infraestructura, que incluye parches del sistema operativo, reparaciones de hardware y valores de red. El usuario puede crear y mantener la aplicación y él mismo o el proveedor pueden instalar middleware, que incluye bases de datos y otros tipos. Este modelo se utiliza para desarrollar y probar software. Para obtener más información, consulte [Guía práctica a la plataforma como servicio: Qué es PaaS ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo")](https://www.ibm.com/blogs/cloud-computing/2016/08/10/practical-guide-paas/){: new_window}.

Con el modelo SaaS, el proveedor actualiza los sistemas mediante la aplicación. La aplicación está basada en la nube y los usuarios pueden utilizar distintos puntos finales, en función del proveedor de software, para utilizar el software. El proveedor de nube es el responsable de la gestión de toda la infraestructura y la aplicación, que incluye actualizaciones de software, reparaciones de software y valores de red. Este modelo se utiliza en modelos de licencia de software de pago según uso. Para obtener más información, consulte [Aplicaciones SaaS para empresas y TI](https://www.ibm.com/cloud/saas){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo").

### Tipos de nube
{: #cloud-types}

Hay disponibles tres tipos distintos de nube: pública, privada e híbrida. Una nube pública incluye un conjunto de recursos compartidos que se suministran para permitir el acceso a los recursos de una empresa. Se aloja en un entorno multiarrendatario en un servidor virtual y se puede acceder desde cualquier sitio. 

Una nube privada incluye recursos suministrados para permitir el acceso a los recursos de una empresa. Se aloja en un hardware dedicado, como un servidor nativo, e in situ en la oficina de la empresa (o entre las oficinas) o mediante un proveedor de nube. Se puede acceder a la nube privada desde cualquier lugar.

Una nube híbrida incluye recursos que combinan los aspectos de las nubes públicas y privadas. Se aloja in situ en la oficina de la empresa (o entre oficinas) y mediante un proveedor de nube. Se puede acceder a la nube híbrida desde cualquier lugar. 

## Planificación de la infraestructura
{: #planning}

Desea planificar la infraestructura antes de suministrarla para asegurarse de que el tamaño es el adecuado para su carga de trabajo. {{site.data.keyword.cloud_notm}} dispone de varias herramientas y sitios para ayudarle a diseñar y dimensionar la infraestructura. 

### Arquitectura de la infraestructura

Empiece con la [arquitectura de la infraestructura ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo")](https://www.ibm.com/cloud/garage/architectures/infrastructure){: new_window} para obtener una visión general de los tres tipos de entornos de nube. 

### {{site.data.keyword.cloud_notm}} Design Decision Tool

[{{site.data.keyword.cloud_notm}} Design Decision Tool ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo")](https://github.com/ibm-cloud-architecture/infrastructure-design-decision-tool/){: new_window} le ayuda a comparar alternativas al diseñar y crear la solución personalizada. Cada componente de infraestructura cuenta con descripciones de características, consideraciones y advertencias, y comparaciones paralelas. También encontrará un ejemplo sobre cómo utilizar la herramienta.

### {{site.data.keyword.cloud_notm}} Stencils

[{{site.data.keyword.cloud_notm}} Stencils ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo")](https://github.com/ibm-cloud-architecture/ibm-cloud-stencils){: new_window} le ayuda a crear un diagrama de la arquitectura de {{site.data.keyword.cloud_notm}} mediante herramientas de diagramación populares. 

### Opciones de servidor nativo

Utilice la [herramienta de búsqueda {{site.data.keyword.baremetal_short}} de {{site.data.keyword.cloud_notm}} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo")](https://www.ibm.com/cloud-computing/bluemix/bare-metal-search){: new_window} para cambiar el tamaño y estimar las opciones de servidor nativo, incluidos los servidores que están certificados para ofrecer soporte a las cargas de trabajo de SAP HANA y SAP NetWeaver.

### Conformidad y servicios de {{site.data.keyword.cloud_notm}}

Al igual que con cualquier arquitectura, debe tener en cuenta los recursos de {{site.data.keyword.cloud_notm}} que puede añadir a su solución a medida que cambia el tamaño de la infraestructura. Para obtener más información, consulte [Aplicaciones SaaS para empresas y TI ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo")](https://www.ibm.com/cloud/saas) {: new_window} y búsqueda de un servicio específico. También debe pensar en cualquier normativa que deba tener en cuenta al crear la arquitectura. Por ejemplo, ¿se considera sensible su carga de trabajo? Para obtener más información, consulte [Conformidad ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo")](https://www.ibm.com/cloud/compliance){: new_window}.

## Creación de la infraestructura
{: #build}

Después de planificar y diseñar la infraestructura, estará listo para crearla. 

### Compute
{: #compute}

El servidor es la base de la infraestructura. Dispone de varias opciones en función de sus necesidades o bien puede mezclarlo todo si es lo que necesita su entorno. Consulte la tabla siguiente para obtener un resumen de las opciones de cálculo.

| Opción | Descripción | 
|--------|---------------|
| [{{site.data.keyword.baremetal_short}}](/docs/bare-metal/about.html)  | Servidores de un solo arrendatario mensuales o por hora, dedicados y no compartidos con otros clientes, incluidos los recursos del servidor. |
| [{{site.data.keyword.BluVirtServers_short}}](/docs/vsi/vsi_about.html) | Servidores virtuales escalables que se adquieren con núcleos dedicados y asignaciones de memoria. |
| [{{site.data.keyword.vmwaresolutions_short}}](/docs/services/vmwaresolutions/vmonic/prod_overview.html) | Integrar o migrar de forma rápida y transparente las cargas de trabajo de VMware locales utilizando una infraestructura escalable, segura y de alto rendimiento y la tecnología de virtualización híbrida de VMware líder del sector. |
| [{{site.data.keyword.containerlong_notm}}](/docs/containers/cs_why.html) | Combina contenedores de Docker, la tecnología de Kubernetes, una experiencia de usuario intuitiva y una seguridad y aislamiento integrados para automatizar el despliegue, la operación, el escalado y la supervisión de apps contenerizadas en un clúster de hosts de cálculo. |
| [{{site.data.keyword.cfee_full_notm}}](/docs/cloud-foundry/index.html) | Crear instancias de varias plataformas de Cloud Foundry aisladas y de nivel empresarial a petición. |
| [{{site.data.keyword.openwhisk_short}}](/docs/openwhisk/index.html) | Una plataforma de programación de funciones como servicio (FaaS) basada en Apache OpenWhisk. |
{: caption="Tabla 1. Opciones de cálculo" caption-side="top"}
   
### Almacenamiento
{: #storage}

{{site.data.keyword.baremetal_short}} y {{site.data.keyword.BluVirtServers_short}} se suministran con un almacenamiento predeterminado. {{site.data.keyword.baremetal_short}} tiene un mínimo de 1 TB SATA de espacio de disco y {{site.data.keyword.BluVirtServers_short}} tiene un mínimo de 25 GB SAN de almacenamiento. La excepción es el {{site.data.keyword.baremetal_short}} certificado por SAP de {{site.data.keyword.cloud_notm}}. Para obtener más información sobre el almacenamiento predeterminado disponible con estos servidores, consulte [Infraestructura de {{site.data.keyword.cloud_notm}} certificada por SAP](/docs/bare-metal/bare-metal-sap-applications.html#ibm-cloud-sap-certified-infrastructure).

Puede adquirir más almacenamiento en función de sus necesidades. Consulte la tabla siguiente para obtener un resumen de las opciones de cálculo.

| Opción | Descripción |
|--------|---------------|
| [{{site.data.keyword.blockstorageshort}}](/docs//infrastructure/BlockStorage/index.html) | Almacenamiento iSCSI persistente y de alto rendimiento que se suministra y se gestiona de forma independiente de las instancias de cálculo. Los LUN basados en iSCSI están conectados a dispositivos autorizados a través de conexiones de E/S de varias vías de acceso (MPIO) redundantes. |
| [{{site.data.keyword.filestorage_short}}](/docs/infrastructure/FileStorage/index.html) | Almacenamiento de archivos basado en NFS persistente, rápido y flexible conectado a la red. En este entorno de almacenamiento adjunto de red (NAS), tiene un control total sobre la función y el rendimiento de las comparticiones de archivos. Las unidades compartidas de almacenamiento de archivos se pueden conectar a un máximo de 64 dispositivos autorizados a través de conexiones TCP/IP direccionadas para la capacidad de recuperación. |
| [{{site.data.keyword.cos_full_notm}}](/docs/services/cloud-object-storage/about-cos.html) | La información almacenada con IBM Cloud Object Storage se cifra y dispersa en varias ubicaciones geográficas y se accede a la misma mediante HTTP utilizando una API REST. Este servicio hace uso de las tecnologías de almacenamiento distribuido que proporciona el sistema de IBM Cloud Object Storage (anteriormente conocido como Cleversafe). |
| [Migración de datos en masa de {{site.data.keyword.cloud_notm}}](/docs/infrastructure/mass-data-migration/index.html) | Descargar grandes cantidades de datos del centro de datos local al grupo Cloud Object Storage. |
| [EVault](/docs/infrastructure/Backup/index.html) | Un sistema de copia de seguridad basado en agentes automatizado que se gestiona mediante el programa de utilidad de gestión basado en el navegador EVault WebCC solo para servidores virtuales. Datos de copia de seguridad entre servidores en uno o varios centros de datos de la red de IBM Cloud. |
{: caption="Tabla 2. Opciones de almacenamiento" caption-side="top"}

### Gestión de redes
{: #network}

Obtendrá conectividad automáticamente a {{site.data.keyword.vpn_full}} cuando la cuenta de {{site.data.keyword.cloud_notm}} se configure. De forma predeterminada, el servidor tiene una dirección IP pública y una dirección IP privada. Si desea que el servidor sea privado, puede desactivar la interfaz pública después de que el servidor se haya suministrado o pedir el servidor como privado. Consulte [Iniciación con la red privada virtual](/docs/infrastructure/iaas-vpn/getting-started.html) para obtener más información.

Consulte la tabla siguiente para obtener un resumen de las opciones de red.

| Opción | Descripción | 
|--------|---------------|
| [Content Delivery Network](/docs/infrastructure/CDN/about.html) | Se utiliza para diversas soluciones de la industria, incluidos medios de comunicación, entretenimiento, software, juegos, banca y comercio electrónico para satisfacer las necesidades de sus negocios. |
| [Domain Name Service](/docs/cli/reference/ibmcloud/cli_dns.html) | Proporciona una ubicación central para visualizar y gestionar los dominios mediante la interfaz de gestión DNS básica y también le proporciona la opción de gestionar un DNS inverso o secundario en la misma ubicación de forma gratuita. |
| [Direcciones IP globales](/docs/infrastructure/subnets/about-global-ip.html) | Ofrecer flexibilidad y permitirle desplazar cargas de trabajo entre servidores, incluso mediante centros de datos geográficamente dispares. |
| [Equilibrio de carga](/docs/infrastructure/local-load-balancer/about.html) | Distribuye el procesamiento y las comunicaciones uniformemente mediante varios servidores en un centro de datos para que un dispositivo individual no lleve toda la carga. |
| [Virtual Router Appliance](/docs/infrastructure/virtual-router-appliance/about.html) | Direcciona de forma selectiva el tráfico de red privada y pública mediante un direccionador de empresa completo con cortafuegos, gestión del tráfico, direccionamiento basado en políticas, VPN y un host de otras características. |
| [VPN IPSec](/docs/infrastructure/iaas-vpn/set-up-ipsec-vpn.html) | Una suite de protocolos diseñada para autenticar y cifrar todo el tráfico de IP entre dos ubicaciones, utilizando una modalidad de túnel que proporciona una red cifrada de sitio a sitio. |
| Enlace directo de {{site.data.keyword.cloud_notm}} | Optimiza un proveedor Cloud Exchange para ofrecer conectividad a las ubicaciones de infraestructura de {{site.data.keyword.cloud_notm}}. |
{: caption="Tabla 3. Opciones de red" caption-side="top"}


## Gestión de la infraestructura
{: #managing}

Después de crear la infraestructura y el entorno, estará listo para empezar a gestionarla.

| Tarea | Descripción |
|--------|---------------|
| [Supervisar sucesos del sistema](/docs/account/audit_log.html) | Visualizar las acciones que se han realizado en los recursos de la infraestructura. |
| [Establecer preferencias de correo electrónico](/docs/account/email.html) | Configurar notificaciones de correo electrónico de la infraestructura de {{site.data.keyword.cloud_notm}} sobre sucesos no planificados, mantenimiento y anuncios.  |
| [Comprender cómo están seguros sus datos](/docs/overview/security.html) | La plataforma {{site.data.keyword.cloud_notm}} dispone de controles de seguridad de varios niveles de la red y de la infraestructura. |
| [Comprender cómo garantizar un tiempo de inactividad cero](/docs/overview/zero_downtime.html) | Todos los recursos de {{site.data.keyword.cloud_notm}} están alojados en ubicaciones de centros de datos de todo el mundo. |
{: caption="Tabla 4. Gestión de tareas" caption-side="top"}

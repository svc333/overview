---


copyright:
  years: 2016, 2018
lastupdated: "2018-11-30"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# ¿Qué es la plataforma {{site.data.keyword.Bluemix_notm}}?
{: #whatis}

La plataforma en la nube de IBM combina una plataforma como servicio (PaaS) con la infraestructura como servicio (IaaS) para proporcionar una experiencia integrada. La plataforma escala y ofrece soporte a organizaciones y equipos de desarrollo pequeños y también a grandes empresas. Implementada globalmente en centros de datos de todo el mundo, la solución que crea en {{site.data.keyword.cloud}} se activa rápidamente y se desempeña de manera fiable en un entorno probado y soportado en el que pueda confiar.
{: .shortdesc}

La plataforma de {{site.data.keyword.Bluemix_notm}} consta de varios componentes que trabajan conjuntamente para proporcionar una experiencia en la nube coherente y fiable. 

  * Un catálogo que consta de cientos de ofertas de {{site.data.keyword.Bluemix_notm}}
  * Una consola robusta que sirve como frontal para crear, ver y gestionar los recursos en la nube
  * Un componente de gestión de accesos e identidades que autentica usuarios de forma segura en los servicios de plataforma y controla el acceso a recursos de forma coherente en {{site.data.keyword.Bluemix_notm}}
  * Un mecanismo de búsqueda y etiquetado para filtrar e identificar los recursos
  * Un sistema de gestión de cuentas y facturación que proporciona una utilización exacta de los planes de precios y protección de fraude con tarjeta de crédito

## Elección del entorno de alojamiento
{: #choose-compute}

Con {{site.data.keyword.Bluemix_notm}}, ya no será necesario hacer grandes inversiones en hardware para probar o ejecutar apps nuevas. En su lugar, nosotros lo gestionamos todos y solo se le cobrará por lo que utilice. El entorno del servicio en la nube es la base de la capa de la infraestructura. Puede elegir una opción única o una combinación de opciones en entornos más complejos. 

Dispone de varias opciones de alojar apps, lo que le proporciona control sobre la infraestructura según sus deseos o necesidades. Puede ejecutar la app de cualquiera de las formas siguientes:

  * Como función sin servidor
  * Como app de Cloud Foundry
  * Como contenedor Docker en un clúster de Kubernetes
  * Como VMware
  * Como máquina virtual
  * En {{site.data.keyword.baremetal_short}} de alto rendimiento 

{{site.data.keyword.baremetal_short}} son servidores físicos de un solo arrendatario que están dedicados a un único cliente. El usuario controla casi todo, desde el host de servidor a la RAM y a los dispositivos de almacenamiento. Estos servidores se utilizan con cargas de trabajo que requieren potencia de cálculo durante un tiempo prolongado, por ejemplo, varios meses. 

{{site.data.keyword.BluVirtServers_short}} se puede desplegar como instancias públicas o dedicadas. Con las instancias públicas, los recursos del servidor se comparten con otros clientes; también se conoce como entorno multiarrendatario. Las instancias privadas dedican los recursos del servidor físico a un cliente que puede tener una o varias máquinas virtuales en el mismo servidor. Estos servidores son ideales para las cargas de trabajo que se ejecutan durante un tiempo limitado, por ejemplo, un par de semanas. Otros ejemplos de carga de trabajo son el desarrollo y las pruebas, la copia de seguridad y la recuperación, y la recuperación tras desastre. Para obtener más información sobre las opciones de servidor, consulte [Servidores nativos frente a servidores virtuales: Elegir la mejor opción](https://www.ibm.com/blogs/bluemix/2018/06/bare-metal-virtual-servers-works/){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo").

Consulte la tabla siguiente para obtener un resumen de las opciones de cálculo.

| Opción | Descripción | 
|--------|---------------|
| [{{site.data.keyword.baremetal_short}}](/docs/bare-metal/about.html)  | Servidores de un solo arrendatario mensuales o por hora, dedicados y no compartidos con otros clientes, incluidos los recursos del servidor. |
| [{{site.data.keyword.BluVirtServers_short}}](/docs/vsi/vsi_about.html) | Servidores virtuales escalables que se adquieren con núcleos dedicados y asignaciones de memoria. |
| [{{site.data.keyword.vmwaresolutions_short}}](/docs/services/vmwaresolutions/vmonic/prod_overview.html) | Integrar o migrar de forma rápida y transparente las cargas de trabajo de VMware locales utilizando una infraestructura escalable, segura y de alto rendimiento y la tecnología de virtualización híbrida de VMware líder del sector. |
| [{{site.data.keyword.containerlong_notm}}](/docs/containers/cs_why.html) | Combina contenedores de Docker, la tecnología de Kubernetes, una experiencia de usuario intuitiva y una seguridad y aislamiento integrados para automatizar el despliegue, la operación, el escalado y la supervisión de apps contenerizadas en un clúster de hosts de cálculo. |
| [{{site.data.keyword.cfee_full_notm}}](/docs/cloud-foundry/index.html) | Crear instancias de varias plataformas de Cloud Foundry aisladas y de nivel empresarial a petición. |
| [{{site.data.keyword.openwhisk_short}}](/docs/openwhisk/index.html) | Una plataforma de programación de funciones como servicio (FaaS) basada en Apache OpenWhisk. |
{: caption="Tabla 1. Opciones de cálculo" caption-side="top"}

## Creación de aplicaciones
{: #build-apps}

En el caso de que disponga de [código existente](/docs/apps/tutorials/tutorial_byoc.html) que desee modernizar y traer a la nube o de estar desarrollando una [nueva aplicación](/docs/apps/tutorials/tutorial_starter-kit.html), sus desarrolladores pueden tocar en el ecosistema de rápido crecimiento de los servicios e infraestructuras de tiempo de ejecución disponibles en {{site.data.keyword.Bluemix_notm}}.

Las [guías de programación](https://cloud.ibm.com/docs/home/build){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo") están disponibles por idioma para ayudarle a empezar a trabajar. Existen muchas formas de alojar apps con la infraestructura de {{site.data.keyword.Bluemix_notm}} desde {{site.data.keyword.baremetal_short}} para que se ejecuten como una función sin servidor.

## Conexión de servicios
{: #connect-services}

Con más de 190 servicios entre los que elegir en el catálogo, puede crear una solución adaptada que se ajuste a sus necesidades. También puede conectar fácilmente servicios a apps fuera de {{site.data.keyword.Bluemix_notm}} si estos son adecuados para usted. Puede generar un nuevo conjunto de credenciales para casos en los que quiera conectarse manualmente un consumidor externo a un servicio de {{site.data.keyword.Bluemix_notm}}. Por ejemplo, si intenta conectar una app fuera de {{site.data.keyword.Bluemix_notm}} a un servicio de Watson, deberá generar una nueva credencial que los conecte. ¡Eso es todo! Para obtener más información, consulte [Adición de una credencial](/docs/resources/service_credentials.html#service_credentials).

## Configuración de la cuenta

Si solo está probando {{site.data.keyword.Bluemix_notm}}, puede ir directamente al catálogo y empezar a consultar los servicios que le gustaría explorar y añadir a su cuenta de prueba o Lite. Sin embargo, si está listo para empezar a utilizar un entorno para un grupo de desarrolladores o para toda una organización y obtener apps que se ejecutan en producción, considere configurar los conceptos básicos en su cuenta:

* Grupos de acceso para organizar los usuarios y los ID de servicio en una entidad para simplificar el proceso de asignación de acceso.
* Grupos de recursos para organizar los recursos y hacer que la asignación de acceso a un grupo de recursos sea rápida y sencilla.
* Políticas de acceso para los grupos de acceso o desarrolladores individuales que necesiten políticas de acceso de IAM o roles de espacio y organizaciones de Cloud Foundry.

Para obtener más información, consulte [prácticas recomendadas para la configuración de su cuenta](/docs/account/bp_account.html#account_setup) y [prácticas recomendadas para la asignación de acceso](/docs/iam/bp_access.html). Además, si está preparado, consulte los fragmentos y partes de la [jerarquía de cuentas](/docs/account/account_overview.html#overview).

## Precios y facturación

Independientemente del tipo de cuenta, puede explorar {{site.data.keyword.Bluemix_notm}} utilizando planes Lite en los servicios que proporcionan cuotas fijas. Cuando elija el servicio de un catálogo y seleccione un mosaico, si hay distintos tipos de planes disponibles, podrá ver los detalles sobre la información de precios. Si elige un plan de servicio con un plan de pago, podrá calcular los costes utilizando la herramienta de estimación de costes. Para obtener más información, consulte [Estimación de los costes](/docs/billing-usage/estimating_costs.html#cost).

La facturación de {{site.data.keyword.Bluemix_notm}} proporciona varios servicios que garantizan que la plataforma de {{site.data.keyword.Bluemix_notm}} puede gestionar de forma segura los precios, las cuentas, el uso, etc.

### Gestión de cuentas de {{site.data.keyword.Bluemix_notm}}
{: #account}

La gestión de cuentas mantiene la relación de facturación con el cliente. Cada cuenta es una entidad de facturación que representa a un cliente. Este servicio controla el ciclo de vida, la suscripción, la relación de usuario y la organización de la cuenta.

### Precios de {{site.data.keyword.Bluemix_notm}}
{: #pricing}

El servicio de plataforma de precios de {{site.data.keyword.Bluemix_notm}} ayuda a los usuarios a definir, gestionar y recuperar información de precios de los recursos del catálogo de {{site.data.keyword.Bluemix_notm}}.

### Recopilador de calibración de {{site.data.keyword.Bluemix_notm}}
{: #metering}

La calibración de uso de {{site.data.keyword.Bluemix_notm}} es un servicio de la plataforma que permite a los proveedores de servicios enviar métricas recopiladas para instancias de recursos suministradas por usuarios de {{site.data.keyword.Bluemix_notm}}. Los proveedores de servicios de terceros que distribuyen un servicio de facturación integrado en {{site.data.keyword.Bluemix_notm}} deben enviar datos de uso a todas las instancias de servicio activas cada hora. El envío es importante porque la incapacidad de informar sobre el uso podría suponer una pérdida de ingresos para IBM, lo que puede provocar una pérdida de ingresos para los proveedores de servicios de terceros.

## {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM)
{: #iam}

La Gestión de identidad y acceso de {{site.data.keyword.Bluemix_notm}} (IAM) le permite autenticar usuarios de forma segura en los servicios de plataforma y controlar el acceso a los recursos de forma coherente en la plataforma de {{site.data.keyword.Bluemix_notm}}. Para obtener más información, consulte [¿Qué es IAM?](/docs/iam/index.html) IAM proporciona mandatos CLI y API que le ayudan a gestionar las señales, grupos de acceso y políticas.


## Creación de recursos
{: #provisioning-layer}

El controlador de recursos es la capa de suministro de la plataforma {{site.data.keyword.Bluemix_notm}} de última generación que gestiona el ciclo de vida de los recursos de {{site.data.keyword.Bluemix_notm}} en una cuenta de cliente. Los recursos se suministran globalmente en un ámbito de la cuenta. El controlador de recursos ofrece soporte al suministro síncrono y asíncrono de recursos. La capa de suministro es la responsable de controlar y realizar un seguimiento del ciclo de vida de los recursos en una cuenta de cliente. Los recursos son componentes físicos o lógicos que se pueden suministrar o reservar para una aplicación o instancia de servicio. Los ejemplos de recursos incluyen límites almacenamiento, bases de datos, cuentas, procesadores y memoria. En general, los recursos de los que la capa de suministro realiza un seguimiento están pensados para asociar métricas de uso y métodos de facturación, pero no siempre es así. En algunos casos, el recurso puede estar asociado a la capa de suministro para garantizar que el ciclo de vida del recurso se puede gestionar junto con el ciclo de vida de la cuenta. El controlador de recursos utiliza IAM para la autenticación y autorización de acciones que se emprenden sobre la capa de suministro.

### Gestión del ciclo de vida de un recurso
{: #lifecycle}

El controlador de recursos proporciona API comunes para controlar el ciclo de vida de los recursos desde el suministro (creación de una instancia), pasando por el enlace (creación de credenciales de acceso) y el desenlace (eliminación del acceso), hasta la anulación del suministro (supresión de una instancia).

El controlador de recursos proporciona varias API para ayudarle a gestionar los siguientes elementos del ciclo de vida del recurso:
* Suministro
* Actualización de una instancia del recurso
* Enlace
* Claves del recurso
* Desenlace
* Anulación de suministro


## Gestión de los recursos
{: #resource-manager}


El gestor de recursos de {{site.data.keyword.Bluemix_notm}} gestiona la recopilación de recursos de [grupos de recursos](/docs/overview/resource-groups.html#whatis). Un grupo de recursos pertenece a una cuenta. Todos los recursos de {{site.data.keyword.Bluemix_notm}} deben suministrarse en un grupo de recursos. Si una cuenta está suspendida, el grupo de recursos correspondiente se suspende y todos los recursos del mismo también se suspenden. Cuando un usuario crea una cuenta, se crea también un grupo de recursos predeterminado en la cuenta. Todos los recursos de {{site.data.keyword.Bluemix_notm}} habilitados para IAM deben suministrarse dentro de un grupo de recursos. Si una cuenta está suspendida, el grupo de recursos correspondiente se suspende y todos los recursos del mismo también se suspenden. En las cuentas estándar, cada usuario puede tener únicamente un grupo de recursos. En las cuentas de suscripción o de pago según uso, cada usuario tiene permiso para crear más de un grupo de recursos. 


## Catálogo de {{site.data.keyword.Bluemix_notm}}
{: #catalog}

El catálogo de {{site.data.keyword.Bluemix_notm}} almacena las definiciones de la oferta (descripción, características, imágenes, URL, etc.) de los recursos que se muestran en la consola de {{site.data.keyword.Bluemix_notm}}. El servicio de catálogo gestiona las ofertas en zonas geográficas como sistema de registros. El catálogo ofrece soporte a las CLI y la API RESTful en las que puede recuperar información sobre las ofertas existentes y crear, gestionar y suprimir las mismas. Empiece con el URL base y utilice los puntos finales para recuperar metadatos sobre los servicios del catálogo y gestionar la visibilidad del servicio. En función del tipo de objeto, los metadatos pueden incluir información sobre los precios, el suministro, las regiones, etc. Para obtener más información, consulte [Gestión de la documentación del catálogo](/docs/overview/catalog.html#global-catalog-overview).

## Búsqueda y etiquetado de recursos
{: #search-and-tag}

El servicio de búsqueda es un repositorio de propiedades de recursos compartidos y globales integrado en la plataforma {{site.data.keyword.Bluemix_notm}}. Se utiliza para almacenar y buscar atributos del recurso de nube. Categoriza y clasifica recursos. Los recursos son propiedad de los proveedores de recursos que controlan los recursos dentro de la plataforma {{site.data.keyword.Bluemix_notm}} como, por ejemplo, Cloud Foundry, IBM Containers o Resource Controller. Los recursos se identifican de forma exclusiva mediante el identificador (CRN) [Nombre de recurso de nube](/docs/overview/crn.html#crn). Las propiedades de un recurso incluyen etiquetas y propiedades del sistema. Ambas propiedades se definen en una cuenta de facturación de {{site.data.keyword.Bluemix_notm}} y abarcan varias regiones.

Este servicio también gestiona las etiquetas que están asociadas a un recurso. Puede crear, suprimir, buscar, adjuntar y desconectar etiquetas con la API de etiquetas. Las etiquetas se identifican de forma exclusiva mediante el identificador Nombre de recursos de nube (CRN). Las etiquetas tienen un nombre, que debe ser exclusivo de una cuenta de facturación. Puede crear etiquetas en `key:value` o en formato de etiqueta.


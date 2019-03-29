---


copyright:
  years: 2016, 2019
lastupdated: "2019-03-14"

keywords: console, platform overview, overview

subcollection: overview

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# ¿Qué es la plataforma {{site.data.keyword.Bluemix_notm}}?
{: #whatis-platform}

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
| [{{site.data.keyword.baremetal_short}}](/docs/bare-metal?topic=bare-metal-getting-started)  | Servidores de un solo arrendatario mensuales o por hora, dedicados y no compartidos con otros clientes, incluidos los recursos del servidor. |
| [{{site.data.keyword.BluVirtServers_short}}](/docs/vsi?topic=virtual-servers-about-public-virtual-servers#public-virtual-servers) | Servidores virtuales escalables que se adquieren con núcleos dedicados y asignaciones de memoria. |
| [{{site.data.keyword.vmwaresolutions_short}}](/docs/services/vmwaresolutions?topic=vmware-solutions-getting-started#getting-started) | Integrar o migrar de forma rápida y transparente las cargas de trabajo de VMware locales utilizando una infraestructura escalable, segura y de alto rendimiento y la tecnología de virtualización híbrida de VMware líder del sector. |
| [{{site.data.keyword.containerlong_notm}}](/docs/containers?topic=containers-container_index) | Combina contenedores de Docker, la tecnología de Kubernetes, una experiencia de usuario intuitiva y una seguridad y aislamiento integrados para automatizar el despliegue, la operación, el escalado y la supervisión de apps contenerizadas en un clúster de hosts de cálculo. |
| [{{site.data.keyword.cfee_full_notm}}](/docs/cloud-foundry?topic=cloud-foundry-about) | Crear instancias de varias plataformas de Cloud Foundry aisladas y de nivel empresarial a petición. |
| [{{site.data.keyword.openwhisk_short}}](/docs/openwhisk?topic=cloud-functions-index) | Una plataforma de programación de funciones como servicio (FaaS) basada en Apache OpenWhisk. |
{: caption="Tabla 1. Opciones de cálculo" caption-side="top"}

## Creación de aplicaciones
{: #build-apps}

En el caso de que disponga de [código existente](/docs/apps/tutorials?topic=creating-apps-tutorial-byoc#tutorial-byoc) que desee modernizar y traer a la nube o de estar desarrollando una [nueva aplicación](/docs/apps/tutorials?topic=creating-apps-tutorial-starterkit), sus desarrolladores pueden tocar en el ecosistema de rápido crecimiento de los servicios e infraestructuras de tiempo de ejecución disponibles en {{site.data.keyword.Bluemix_notm}}.

Las [guías de programación](https://cloud.ibm.com/docs/home/build){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo") están disponibles por idioma para ayudarle a empezar a trabajar. Existen muchas formas de alojar apps con la infraestructura de {{site.data.keyword.Bluemix_notm}} desde {{site.data.keyword.baremetal_short}} para que se ejecuten como una función sin servidor.

## Conexión de servicios
{: #connect-services}

Con más de 190 servicios entre los que elegir en el catálogo, puede crear una solución adaptada que se ajuste a sus necesidades. También puede conectar fácilmente servicios a apps fuera de {{site.data.keyword.Bluemix_notm}} si estos son adecuados para usted. Puede generar un nuevo conjunto de credenciales para casos en los que quiera conectarse manualmente un consumidor externo a un servicio de {{site.data.keyword.Bluemix_notm}}. Por ejemplo, si intenta conectar una app fuera de {{site.data.keyword.Bluemix_notm}} a un servicio de Watson, deberá generar una nueva credencial que los conecte. ¡Eso es todo! Para obtener más información, consulte [Adición de una credencial](/docs/resources?topic=resources-service_credentials).

## Configuración de la cuenta
{: #set-up-account}

Si solo está probando {{site.data.keyword.Bluemix_notm}}, puede ir directamente al catálogo y empezar a consultar las ofertas que le gustaría explorar y añadir a su cuenta Lite. Sin embargo, si está listo para empezar a utilizar un entorno para un grupo de desarrolladores o para toda una organización y obtener apps que se ejecutan en producción, considere configurar los conceptos básicos en su cuenta:

* Grupos de acceso para organizar los usuarios y los ID de servicio en una entidad para simplificar el proceso de asignación de acceso.
* Grupos de recursos para organizar los recursos y hacer que la asignación de acceso a un grupo de recursos sea rápida y sencilla.
* Políticas de acceso para los grupos de acceso o desarrolladores individuales que necesiten políticas de acceso de IAM o roles de espacio y organizaciones de Cloud Foundry.

Para obtener más información, consulte [prácticas recomendadas para la configuración de su cuenta](/docs/account?topic=account-account_setup) y [prácticas recomendadas para la asignación de acceso](/docs/iam?topic=iam-account_setup). 

## Precios y facturación
{: #pricing-billing}

Independientemente del tipo de cuenta, puede explorar {{site.data.keyword.Bluemix_notm}} utilizando planes Lite en los servicios que proporcionan cuotas fijas. Cuando elija el servicio de un catálogo y seleccione un mosaico, si hay distintos tipos de planes disponibles, podrá ver los detalles sobre la información de precios. Si elige un plan de servicio con un plan de pago, podrá calcular los costes utilizando la herramienta de estimación de costes. Para obtener más información, consulte [Estimación de los costes](/docs/billing-usage?topic=billing-usage-cost).

La facturación de {{site.data.keyword.Bluemix_notm}} proporciona varios servicios que garantizan que la plataforma de {{site.data.keyword.Bluemix_notm}} puede gestionar de forma segura los precios, las cuentas, el uso, etc.

### Gestión de cuentas
{: #account-mgmt}

La gestión de cuentas mantiene la relación de facturación con el cliente. Cada cuenta es una entidad de facturación que representa a un cliente. Este servicio controla el ciclo de vida, la suscripción, la relación de usuario y la organización de la cuenta.

### Tarifas
{: #pricing}

El servicio de plataforma de precios le ayuda a definir, gestionar y recuperar información de precios para los recursos del catálogo de {{site.data.keyword.Bluemix_notm}}.

### Medición del uso
{: #metering}

Con la calibración de uso, los proveedores de servicios pueden enviar métricas recopiladas para instancias de recursos suministradas por usuarios de {{site.data.keyword.Bluemix_notm}}. Los proveedores de servicios de terceros que distribuyen un servicio de facturación integrado deben enviar datos de uso a todas las instancias de servicio activas cada hora. 

### Informes de uso
{: #usage}

Los informes de uso devuelven el resumen de la cuenta para el mes especificado. Los gestores de facturación de la cuenta están autorizados para acceder a los informes.

## Catálogo de {{site.data.keyword.Bluemix_notm}}
{: #catalog}

El catálogo de {{site.data.keyword.Bluemix_notm}} almacena las definiciones de la oferta (descripción, características, imágenes, URL, etc.) de los recursos que están disponibles en la consola de {{site.data.keyword.Bluemix_notm}}. Las ofertas se gestionan en zonas geográficas como sistema de registros. El catálogo ofrece soporte a las interfaces de línea de mandatos (CLI) y la API RESTful en las que el usuario puede recuperar información sobre las ofertas existentes y crear, gestionar y suprimir sus recursos. Para obtener más información, consulte [Gestión del catálogo](/docs/overview?topic=overview-manage-catalog).

## Creación de recursos
{: #provisioning-layer}

El controlador de recursos es la capa de suministro de la plataforma {{site.data.keyword.Bluemix_notm}} de última generación que gestiona el ciclo de vida de los recursos de {{site.data.keyword.Bluemix_notm}} en la cuenta. Los recursos se suministran globalmente en un ámbito de la cuenta. El controlador de recursos ofrece soporte al suministro síncrono y asíncrono de recursos. Los ejemplos de recursos incluyen límites almacenamiento, bases de datos, cuentas, procesadores y memoria. 

En general, los recursos de los que la capa de suministro realiza un seguimiento están pensados para asociar métricas de uso y métodos de facturación, pero no siempre es así. En algunos casos, el recurso puede estar asociado con la capa de suministro para garantizar que el ciclo de vida del recurso se puede gestionar junto con el ciclo de vida de la cuenta. El controlador de recursos utiliza {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) para la autenticación y autorización de acciones que se emprenden sobre la capa de suministro.

### Gestión del ciclo de vida de un recurso
{: #lifecycle}

El controlador de recursos proporciona API comunes para controlar el ciclo de vida de los recursos desde la creación de una instancia, pasando por la creación de credenciales de acceso, hasta la supresión de una instancia.

## Gestión de los recursos
{: #resource-manager}

Los [grupos de recursos](/docs/overview?topic=overview-whatis-rgs) gestionan las colecciones de recursos. Los grupos de recursos se asocian con la cuenta. Todos los recursos de {{site.data.keyword.Bluemix_notm}} se deben asignar a un grupo de recursos. Cuando crea una cuenta, se crea también un grupo de recursos predeterminado. Todos los recursos de {{site.data.keyword.Bluemix_notm}} habilitados para IAM deben suministrarse dentro de un grupo de recursos. Si tiene una cuenta Lite, solo puede tener un grupo de recursos. Si tiene una cuenta de Pago según uso o de Suscripción, puede crear más de un grupo de recursos. Si una cuenta está suspendida, el grupo de recursos correspondiente se suspende y todos los recursos del mismo también se suspenden. 

## Búsqueda y etiquetado de recursos
{: #search-and-tag}

El servicio de búsqueda es un repositorio de propiedades de recursos compartidos y globales integrado en la plataforma {{site.data.keyword.Bluemix_notm}}. Se utiliza para almacenar y buscar atributos de un recurso de nube, y categoriza y clasifica recursos. Los recursos se identifican de forma exclusiva mediante un identificador de [Nombre de recursos de nube (CRN)](/docs/overview?topic=overview-crn). Las propiedades de un recurso incluyen etiquetas y propiedades del sistema. Ambas propiedades se definen en una cuenta de facturación de {{site.data.keyword.Bluemix_notm}} y abarcan varias regiones.

Este servicio también gestiona las etiquetas que están asociadas a un recurso. Puede crear, suprimir, buscar, adjuntar y desconectar etiquetas con la API de etiquetas. Las etiquetas se identifican de forma exclusiva mediante un CRN. Las etiquetas tienen un nombre, que debe ser exclusivo de una cuenta de facturación. Puede crear etiquetas en pares key:value o en formato de etiqueta.

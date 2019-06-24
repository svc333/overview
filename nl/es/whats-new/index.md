---

copyright:

  years: 2015, 2019

lastupdated: "2019-06-03"

keywords: release notes, what's new, what is new, cloud updates

subcollection: overview

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:tip: .tip}

# Novedades en {{site.data.keyword.Bluemix_notm}}
{: #whatsnew}

Consulte información actualizada sobre las nuevas características disponibles en la plataforma {{site.data.keyword.Bluemix}} para sacar el máximo provecho de {{site.data.keyword.Bluemix_notm}}. 
{:shortdesc}

Si está buscando actualizaciones de los servicios disponibles en {{site.data.keyword.Bluemix_notm}}, consulte la [página Anuncios de {{site.data.keyword.Bluemix_notm}}](https://www.ibm.com/cloud/blog/announcements){: new_window} ![Icono de enlace externo](../../icons/launch-glyph.svg "Icono de enlace externo") en el blog.
{: tip}



## Plataforma {{site.data.keyword.Bluemix_notm}}
{: #platform_category}


### Exportación de datos de uso con etiquetas asociadas
Novedad desde: 4 de abril de 2019 

Ahora puede utilizar nuestras más recientes funciones de etiquetado para gestionar los recursos, el uso y los costes en el informe de uso exportado. Cuando añade una etiqueta a un recurso, tiene la opción de visualizar la etiqueta asociada al recurso. Vaya a **Gestionar**> **Facturación y uso**> **Uso**> **Exportar CSV**>  **Instancias** para descargar su informe de uso. Para obtener más información sobre cómo exportar etiquetas, consulte la publicación del blog sobre [Exportación de etiquetas en sus datos de uso para facilitar la asignación de costes](https://www.ibm.com/cloud/blog/export-your-tagged-usage-data-within-the-enhanced-ibm-cloud){: new_window} ![Icono de enlace externo](../../icons/launch-glyph.svg "Icono de enlace externo").

### Grupo de acceso para habilitar el acceso público a los recursos
Novedad desde: 25 de marzo de 2019

Ahora puede habilitar el acceso público a objetos de grupos de {{site.data.keyword.cos_full}} mediante un nuevo grupo de acceso que se suministra automáticamente en su cuenta. Este nuevo grupo de acceso se denomina grupo `Acceso público` y de forma predeterminada se añaden al mismo todos los usuarios e ID de servicio. Puede actualizar las políticas para este grupo de acceso para habilitar el acceso de todos los usuarios, incluso los no autenticados, a los recursos que especifique en la política. [Más información sobre el grupo de acceso público](/docs/iam?topic=iam-public#public).

### Autenticación de multifactores para usuarios con ID federados
Novedad desde: 12 de marzo de 2019
{: #mfa-federated}

Los propietarios de la cuenta o los usuarios que tienen asignado el rol de administrador en el servicio de gestión de la cuenta de facturación puede habilitar la autenticación de multifactores (MFA) para todos los usuarios de su cuenta. Es posible que los usuarios federados que utilizan su ID de inicio de sesión único empresarial o corporativo ahora necesiten autenticarse utilizando MFA para iniciar la sesión en {{site.data.keyword.Bluemix_notm}}. Para obtener más información sobre esta mejora funcional y sobre cómo habilitar MFA en su cuenta, consulte [Presentación de MFA para usuarios de IBM Cloud con ID federado](https://www.ibm.com/cloud/blog/introducing-mfa-for-ibm-cloud-users-with-federated-id){: new_window} ![Icono de enlace externo](../../icons/launch-glyph.svg "Icono de enlace externo").

### Nueva opción de nombre de host de appdomain.cloud
Novedad desde: 31 de diciembre de 2018
{: #appdomain}

Hay una nueva opción de nombre de host `*.appdomain.cloud` disponible en cloud.ibm.com.

Anteriormente, se utilizaba el dominio `mybluemix.net` para alojar apps en diversos destinos de despliegue, como
{{site.data.keyword.containerlong_notm}} o Cloud Foundry. Las apps que tenga alojadas en `mybluemix.net` no se verán afectadas.

El subdominio para las apps de Cloud Foundry es `cf.appdomain.cloud`. El subdominio para las apps que despliegue en
{{site.data.keyword.containerlong_notm}} es `containers.appdomain.cloud`.

### Nuevos puntos finales de API de Cloud Foundry
Novedad desde: 30 de noviembre de 2018
{: #cf-api-endpoints}

Los puntos finales de API de Cloud Foundry `api.*.bluemix.net` heredados siguen estando disponibles por compatibilidad con versiones anteriores. No obstante, puede actualizar los scripts y la automatización de la infraestructura para utilizar los nuevos puntos finales de API de Cloud Foundry siguientes para su región:

* api.us-south.cf.cloud.ibm.com (anteriormente api.ng.bluemix.net)
* api.eu-gb.cf.cloud.ibm.com (anteriormente api.eu-gb.bluemix.net)
* api.us-east.cf.cloud.ibm.com (anteriormente api.us-east.bluemix.net)
* api.eu-de.cf.cloud.ibm.com (anteriormente api.eu-de.bluemix.net)
* api.au-syd.cf.cloud.ibm.com (anteriormente api.au-syd.bluemix.net)

### Nueva experiencia de soporte de {{site.data.keyword.Bluemix_notm}}
Novedad desde: 30 de noviembre de 2018 
{: #support}

Con el centro de soporte, puede trabajar para resolver todos los problemas relacionados con {{site.data.keyword.Bluemix_notm}}. La página de destino proporciona preguntas frecuentes para poder encontrar la respuesta a su pregunta sin tener que ponerse en contacto con {{site.data.keyword.Bluemix_notm}}. También puede chatear con un representante de soporte en directo. Ahora sus casos se pueden gestionar desde una única ubicación. Vaya a **Soporte** &gt; **Gestionar casos** para crear, visualizar o editar casos.

También encontrará la [página de estado](https://cloud.ibm.com/status){: new_window} ![Icono de enlace externo](../../icons/launch-glyph.svg "Icono de enlace externo") en el Centro de soporte. Se ha mejorado para incluir todas las incidencias no planificadas, mantenimiento planificado, anuncios y notificaciones de seguridad sobre sucesos clave que afectan a la plataforma, la infraestructura y los servicios principales de {{site.data.keyword.Bluemix_notm}}. Pulse **Ver estado de la nube** desde el Centro de soporte. Para ver la nueva experiencia, inicie sesión y vaya al [Centro de soporte](https://cloud.ibm.com/unifiedsupport/supportcenter){: new_window} ![Icono de enlace externo](../../icons/launch-glyph.svg "Icono de enlace externo"). 

### Inicio de sesión unificado, claves de API y gestión de acceso y usuario en {{site.data.keyword.Bluemix_notm}}
Novedad desde: 30 de noviembre de 2018
{: #useraccess}

Con las últimas actualizaciones, puede aprovechar un inicio de sesión seguro simplificado que esté disponible para todos los usuarios independientemente del tipo de ID. Si tiene un IBMid o un ID de SoftLayer, puede iniciar sesión rápidamente en la consola de {{site.data.keyword.Bluemix_notm}} desde nuestra página de inicio de sesión mejorada. También puede realizar llamadas API en {{site.data.keyword.Bluemix_notm}} y automatizar el inicio de sesión de CLI utilizando una clave de API de IAM o una señal de acceso de IAM. 

Una vez haya iniciado sesión, podrá ver todos los usuarios, incluidos los usuarios de la infraestructura clásica y la plataforma de la página Usuarios en la IU de acceso (IAM). En función del acceso del que disponga para ver otros usuarios de la cuenta, podrá filtrar la vista por usuarios de cuenta, usuarios de infraestructura clásica o según la organización Cloud Foundry. También puede utilizar los filtros para buscar usuarios rápidamente por nombre, correo electrónico o estado.

Ahora que todos los usuarios se encuentran en una sola consola, podrá gestionar el acceso a todos los tipos de recursos desde el mismo lugar. El primer paso para obtener el acceso es el usuario, por lo que lo primero que tiene que hacer es seleccionar un usuario de la lista. A continuación, en función del tipo de recurso al que desee asignarle acceso, puede eligir entre las políticas de acceso de IAM, el acceso de Cloud Foundry o los permisos de infraestructura clásicos. Si solo desea asignar políticas de acceso de IAM, intente crear un grupo de acceso para agilizar el proceso de gestión de accesos añadiendo todos los usuarios al mismo grupo de acceso que necesita que se le asignen las mismas políticas.

Para obtener más información, consulte [Las mejoras en el acceso de usuarios ayuda a ofrecer una plataforma {{site.data.keyword.Bluemix_notm}} unificada](https://www.ibm.com/cloud/blog/announcements/ibm-cloud-access-management){: new_window} ![Icono de enlace externo](../../icons/launch-glyph.svg "Icono de enlace externo"). 

### Busque toda la documentación del plugin de la CLI de {{site.data.keyword.Bluemix_notm}} en el mismo lugar
Novedad desde: 30 de noviembre de 2018
{: #cli}

Ahora puede acceder a toda la documentación del plugin de la CLI de {{site.data.keyword.Bluemix_notm}} en una misma ubicación, lo que facilita la búsqueda de mandatos de CLI en la plataforma {{site.data.keyword.Bluemix_notm}}. Consulte la sección Referencias de la [documentación de CLI](/docs/cli?topic=cloud-cli-ibmcloud-cli).

### Consulte el panel de control y la lista de recursos nuevos
Novedad desde: 30 de noviembre de 2018
{: #dash}

Con nuestra última actualización, ahora podrá ver todos los servicios de infraestructura y plataforma desde una ubicación. Cuando inicie sesión, podrá consultar el nuevo panel de control de inmediato. Una vez haya añadido los recursos a su cuenta desde el catálogo, podrá utilizar la lista de recursos para obtener una vista completa de los recursos de la cuenta:

* El panel de control se ha rediseñado para que pueda ver un resumen de los recursos, mantenimiento, estado, apps, soporte, uso y usuarios.
* Encontrará más detalles sobre sus recursos en la lista de recursos. Puede etiquetar los recursos para organizarlos o seleccionarlos para realizar cambios en la página de detalles.
* Ahora que puede ver todos los recursos en un mismo lugar, hemos añadido una búsqueda global para que pueda encontrar rápidamente los recursos que ha creado y esperar que aparezcan en la página Lista de recursos. 
* También puede buscar resultados de catálogo, para poder encontrar rápidamente recursos y añadirlos a su cuenta.  

Consulte el apartado sobre [Gestionar todos sus recursos en la nube en la plataforma mejorada de {{site.data.keyword.Bluemix_notm}}](https://www.ibm.com/blogs/bluemix/2018/11/manage-all-your-cloud-resources-on-the-enhanced-ibm-cloud-platform/){: new_window} ![Icono de enlace externo](../../icons/launch-glyph.svg "Icono de enlace externo") para obtener más información.

### Información de perfil de usuario, facturación y cuenta para servicios de plataforma e infraestructura
Novedad desde: 30 de noviembre de 2018
{: #profile}

La información de cuenta, facturación y perfil se ha simplificado. Puede ver la información de cuenta para todos los recursos de plataforma e infraestructura en una consola unificada. 

* El área de valores y perfil contiene información sobre usted, además de preferencias de notificación de correo electrónico para todos los tipos de recursos. 
* El área de información de cuenta contiene información sobre la empresa u organización, los valores de cuenta y el acceso rápido para trabajar con grupos de recursos y organizaciones de Cloud Foundry. Incluso puede encontrar prácticas recomendadas para ayudarle a empezar a trabajar rápidamente.
* El área de uso y facturación de su cuenta le ayuda a comprender la factura, a realizar pagos, a supervisar suscripciones, a obtener presupuestos, a realizar un seguimiento de los pedidos y a establecer notificaciones de gastos.

Consulte el tema sobre [Combinación de todos los elementos: gestión única de cuenta y de facturación](https://www.ibm.com/cloud/blog/announcements/ibm-cloud-account-management){: new_window} ![Icono de enlace externo](../../icons/launch-glyph.svg "Icono de enlace externo") para obtener más información.

### Organizar los recursos con etiquetas
Novedad desde: 30 de noviembre de 2018
{: #tag}

Ahora puede añadir etiquetas a sus recursos como, por ejemplo, Cloud Object Storage, para que le ayuden a gestionar recursos y a buscar los que sean más relevantes para usted. Por ejemplo, si tiene cientos de recursos y desea diferenciar entre un par de ellos que se pagan de la misma manera, puede etiquetarlos como `costcenter:location01`. O, si tiene un equipo que trabaja en un par de recursos de manera constante, puede utilizar una etiqueta como `team-blue`. También puede filtrar la lista de recursos por etiquetas para organizar y encontrar rápidamente los recursos que necesita. Para obtener más información, consulte [Cómo trabajar con etiquetas](/docs/resources?topic=resources-tag) y [Etiquetado de la plataforma en la plataforma mejorada de {{site.data.keyword.Bluemix_notm}}](https://www.ibm.com/cloud/blog/announcements/platform-tagging-on-the-enhanced-ibm-cloud-platform){: new_window} ![Icono de enlace externo](../../icons/launch-glyph.svg "Icono de enlace externo"). 

### Buscar costes mensuales precisos con el estimador de costes
Novedad desde: 30 de noviembre de 2018
{: #cost-estimator}

Para ayudarle a decidir y analizar qué servicios comprar, puede utilizar el estimador de costes. Ahora, puede examinar la consola y seleccionar los servicios que desee tener y añadir todos los costes en una herramienta fácil de utilizar. Incluso puede especificar los usos de datos proyectados, las búsquedas, escrituras y consultas por segundo para obtener una estimación más precisa de sus gastos mensuales. Puede utilizar el estimador de costes con cada servicio de catálogo que seleccione o puede pulsar en el icono del estimador de costes ![Icono Estimador](../../icons/Estimator.svg) del menú de la consola para obtener un coste estimado. Para obtener más información, consulte [Estimación de los costes](/docs/billing-usage?topic=billing-usage-cost).

### Nombres de ubicaciones globales actualizados para {{site.data.keyword.cloud_notm}}
Novedad desde: 1 de noviembre de 2018
{: #location-name-updates}

A medida que {{site.data.keyword.cloud_notm}} continúa expandiendo su disponibilidad global, se va actualizando la estructura de nombres de ubicaciones para dar un mejor soporte a una jerarquía coherente y comprensible de geografías, regiones y centros de datos en todo el mundo. Si está familiarizado con nuestras regiones globales actuales, reconocerá nombres como EE.UU. sur y Sídney. Estamos alineando estos nombres de ubicaciones con los nombres de las ciudades en las que ser encuentran físicamente los centros de datos.

Por ahora no se están modificando los ID programáticos, de modo que esto no afecta desde una perspectiva de API. En la tabla siguiente se muestran los nombres de ubicación antiguos y nuevos. Para obtener más información y ver una lista completa de centros de datos y regiones, consulte [Disponibilidad de servicios](/docs/resources?topic=resources-services_region).

| Nombre ubicación anterior | Nuevo nombre ubicación | Código |
|----------|---------|---------|
| EE.UU. sur | Dallas | us-south | 
| EE.UU. este | Washington DC | us-east |
| Reino Unido | Londres | eu-gb |
| Alemania | Frankfurt | eu-de |
| Sídney | Sídney | au-syd |
| AP norte | Tokio | jp-tok |
{: caption="Tabla 1. Nuevos nombres de ubicación" caption-side="top"}

### Asignación de acceso de gestión de cuenta a otros
Novedad desde: 30 de octubre de 2018
{: #acct-mgmt-services}

Con {{site.data.keyword.cloud_notm}} Identity and Access Management (IAM), puede delegar tareas comunes que haya completado como administrador de la cuenta a otro usuario de la cuenta. Mediante la creación de una política de acceso en uno o en todos los servicios de gestión de cuenta disponibles, puede delegar fácilmente responsabilidades, como invitar y eliminar usuarios, gestionar grupos de accesos, gestionar ID de servicios, mantener servicios de catálogos privados e incluso supervisar la facturación y realizar un seguimiento del uso. Hay cuatro servicios individuales de gestión de cuentas y una opción para todos los servicios que puede utilizar para configurar políticas de acceso:

* Gestión de usuarios para invitar y eliminar usuarios
* Grupos de acceso de IAM para crear, editar, suprimir, actualizar y asignar acceso 
* IAM Identity Service para ver, crear, suprimir y asignar acceso a ID de servicio y claves de API asociadas en la cuenta
* Catálogo global de recursos para ver ofertas del catálogo privado y actualizar los metadatos y la visibilidad de las ofertas
* Todos los servicios de gestión de cuentas para acceder a cada una de las opciones de los servicios de gestión de cuentas individuales en función del rol asignado, así como acceso a facturación y seguimiento del uso.

Para obtener más información sobre las tareas que puede realizar un usuario en función del servicio de gestión de cuentas en el que tienen una política y del rol asignado, consulte [Roles y acciones de gestión de plataforma de ejemplo para los servicios de gestión de cuentas](/docs/iam?topic=iam-userroles#platformrolestable2). Para obtener más información sobre esta nueva característica, consulte la publicación del blog sobre [Cómo incorporar más flexibilidad y control para el acceso a los servicios de gestión de cuentas de IBM Cloud](https://www.ibm.com/cloud/blog/announcements/introducing-more-flexibility-and-control-for-ibm-cloud-account-management-services-access){: new_window} ![Icono de enlace externo](../../icons/launch-glyph.svg "Icono de enlace externo"). 

### Búsqueda de recursos
Novedad desde: 17 de julio de 2018
{: #forward-slash-key}

Puede buscar recursos desde cualquier lugar de la consola de {{site.data.keyword.cloud_notm}}. Escriba el nombre de un recurso en el campo de búsqueda de la barra de menús de la consola. Pulse la tecla de barra inclinada (/) para activar la búsqueda.

### Adición dinámica de usuarios federados a grupos de acceso
Novedad desde: 12 de julio de 2018
{: #add-fed-users}

Puede crear reglas dinámicas para añadir de forma automática usuarios federados a grupos de acceso en función de determinados atributos de identidad. Cuando los usuarios inician una sesión con un ID federado, los datos del proveedor de identidades correlacionan dinámicamente los usuarios con un grupo de acceso en función de las reglas. Para obtener más información, consulte [Creación de reglas dinámicas para grupos de acceso](/docs/iam?topic=iam-rules).

### Proteja su ID de servicio y claves de API
Novedad desde: 1 de junio de 2018
{: #protect-svcid-apikey}

Para evitar una situación donde su ID de servicio o clave de API se suprima provocando una interrupción o alteración, puede bloquear los ID de servicio y las claves de API mediante la IU o CLI. El bloqueo de un ID de servicio también impide que las políticas de acceso se cambien, se supriman o se asignen, así como que se creen o se supriman claves de API asociadas con el ID de servicio. Para obtener más información, consulte [Bloqueo de un ID de servicio](/docs/iam?topic=iam-serviceidapikeys#lockkey) y [Bloqueo de una clave de API](/docs/iam?topic=iam-userapikey).

### Actualice su cuenta Lite a una cuenta de Suscripción
Novedad desde: 31 de mayo de 2018
{: #upgrade-lite}

Ahora puede actualizar su cuenta Lite a una cuenta de Suscripción directamente desde la consola de {{site.data.keyword.Bluemix_notm}}. Con una cuenta de Suscripción, puede utilizar ambas ofertas de plataforma y de infraestructura, y aprovechar los descuentos en el precio realizando un compromiso de gasto mensual y de permanencia. También puede evitar sorpresas con facturación fija en una planificación de pago mensual, pero con la flexibilidad para solicitar más o menos según sus necesidades. Para obtener más información, consulte [Preguntas frecuentes de la cuenta de suscripción](/docs/billing-usage?topic=billing-usage-billusagefaqs#subs-order). 

### Cambio de imagen corporativa de la CLI de {{site.data.keyword.Bluemix_notm}}
Novedad desde: 15 de mayo de 2018
{: #cli-rebrand}

Los mandatos de CLI de {{site.data.keyword.Bluemix_notm}} han cambiado de **`bluemix`** y **`bx`** a **`ibmcloud`**. Sin embargo, puede seguir utilizando los mandatos de CLI **`bluemix`** y **`bx`** hasta que se eliminen más adelante. No hay ningún nombre abreviado en este momento, solo el nombre completo **`ibmcloud`**. 

### Autenticación de multifactores para su cuenta de {{site.data.keyword.Bluemix_notm}}
Novedad desde: 2 de mayo de 2018
{: #account-mfa}

La autenticación de multifactores (MFA) añade una capa de seguridad extra a su cuenta solicitando a todos los usuarios que proporcionen un código de acceso de un solo uso basado en tiempo además del IBMid y la contraseña estándar durante el inicio de sesión. También se conoce como autenticación de dos factores (2FA). La MFA se habilita por cuenta y, una vez activada, se solicita a todos los usuarios de la cuenta que inicien sesión utilizando la medida de seguridad adicional. Para obtener más información, consulte la publicación del blog [IBM Cloud Platform ahora añade soporte a la autenticación de multifactores](https://www.ibm.com/cloud/blog/ibm-cloud-platform-now-adds-support-multi-factor-authentication){: new_window} ![Icono de enlace externo](../../icons/launch-glyph.svg "Icono de enlace externo").

### Asignar acceso rápidamente mediante grupos de acceso
Novedad desde: 03 de abril de 2018
{: #access-groups}

¿Desea poder asignar acceso rápidamente utilizando el menor número posible de políticas? Ahora puede hacerlo gracias a los grupos de acceso. Los grupos de acceso le permiten agrupar un conjunto de usuarios y de ID de servicio y asignar una única política que se aplica a todos los miembros del grupo. Mediante los grupos de acceso puede reducir el tiempo que pasa gestionando el acceso a usuarios e ID de servicio en su cuenta. Para obtener más detalles, consulte la publicación de blog [Nueva característica: Grupos de acceso](https://www.ibm.com/cloud/blog/access-groups){: new_window} ![Icono de enlace externo](../../icons/launch-glyph.svg "Icono de enlace externo").

### Ya está disponible el servicio {{site.data.keyword.Bluemix_notm}} Foundry de la región EE.UU. este
Novedad desde: 15 de diciembre de 2017
{: #cf-useast}

Ya está disponible un nuevo centro de datos de EE.UU. este en Washington, DC. Se puede llegar a esta nueva región mediante el punto final `us-east.cloud.ibm.com`. Para obtener detalles sobre los servicios disponibles para su adquisición en esta nueva región, consulte [Servicios por región](/docs/resources?topic=resources-services_region).

### Soporte para recursos en la Unión Europea
Novedad desde: 14 de diciembre de 2017
{: #eu-resources}

Si los servicios y los centros de datos están ubicados en Europa, {{site.data.keyword.Bluemix_notm}} ofrecerá ahora funciones adicionales para proteger los datos en la Unión Europea. Puede solicitar que los equipos de éxito de clientes ubicados en Europa proporcionen soporte. Este soporte está disponible 24 horas al día, 7 días por semana. Consulte [Habilitación de la opción Soporte en la UE](/docs/account?topic=account-eu-hipaa-supported#bill_eusupported) y [Solicitud de soporte para recursos en la Unión Europea](/docs/get-support?topic=get-support-getting-customer-support#eusupported) para obtener más información.

### Retirada de soporte para TLS 1.0 y 1.1
Novedad desde: 28 de noviembre de 2017
{: #nosupport-tls}

El 1 de marzo de 2018, {{site.data.keyword.Bluemix_notm}} retirará el soporte para TLS 1.0 y TLS 1.1 en muchos de nuestros productos y servicios en la nube como parte de nuestro compromiso para ofrecer una nube que sea completamente segura y acorde con las mejores prácticas de la industria para la seguridad y la privacidad de los datos. Para obtener más información sobre cómo afecta este cambio y qué acciones deberá tomar, consulte [Retirada de soporte para TLS 1.0 y 1.1](/docs/get-support?topic=get-support-tlssupportwithdraw).

### Una nueva forma de organizar los recursos en su cuenta
Novedad desde: 16 de noviembre de 2017
{: #usergs}

Los grupos de recursos son una nueva forma de crear agrupaciones personalizables de los recursos de la cuenta, y el acceso al grupo y a los recursos dentro del mismo se gestionan utilizando Identity and Access Management (IAM). Todos los usuarios inician con un grupo de recursos predeterminado. Puede renombrar este grupo de recursos y añadir nuevas instancias de servicio al mismo a medida que los cree desde el catálogo.

Para los usuarios con una cuenta de Pago según uso o de Suscripción, puede crear grupos de recursos adicionales para hacer que la gestión de la cuota y la visualización del uso de facturación para un conjunto de recursos sean más sencillas. También puede agrupar recursos para facilitarle la asignación de acceso a los usuarios a más de un servicio a la vez. Para obtener más información sobre cómo trabajar con grupos de recursos para su cuenta, consulte [Gestionar grupos de recursos](/docs/resources?topic=resources-rgs).

### Actualizaciones para {{site.data.keyword.Bluemix_notm}} IAM
Novedad desde: 16 de noviembre de 2017
{: #iam-nov17}

La introducción de grupos de recursos dentro de la cuenta de {{site.data.keyword.Bluemix_notm}} ha abierto una nueva forma de asignar acceso. Se puede asignar acceso a los usuarios y a los ID de servicio a todos los servicios de un grupo de recursos permitiéndole asignar rápidamente acceso a más de un recurso a la vez. También puede personalizar el acceso para cada usuario o ID de servicio asignando acceso a solo algunos servicios dentro de un grupo de recursos, o elija asignar acceso a recursos individuales hasta el nivel de instancia de servicio. Para obtener más información sobre las características que puede aprovechar utilizando IAM, consulte [¿Qué características proporciona IAM?](/docs/iam?topic=iam-iamoverview#features)

### Personalice la vista de su panel de control
Novedad desde: 16 de noviembre de 2017
{: #custom-dash}

Puede ver y gestionar todos los recursos de su cuenta desde el panel de control de la consola de {{site.data.keyword.Bluemix_notm}}. Y ahora, puede establecer filtros para personalizar la vista. Por ejemplo, puede filtrar por grupo de recursos para ver los recursos específicos de un grupo de recursos. También puede filtrar por región o por espacio de Cloud Foundry. Para obtener más detalles, consulte [Gestión de recursos en el panel de control](/docs/overview?topic=overview-ui#dashboardview).

### Centro de soporte
Novedad desde: 2 de noviembre de 2017
{: #support-nov17}

Ahora tenemos el nuevo Centro de soporte, donde puede buscar información, publicar preguntas en nuestra comunidad de desarrolladores, y gestionar incidencias. Vaya a **Soporte > Centro de soporte** en la barra de menús de la consola de {{site.data.keyword.Bluemix_notm}}.

### Introducción a IBM Cloud
Novedad desde: 31 de octubre de 2017
{: #meet-ibmcloud}

Bluemix es ahora IBM Cloud. Aparte de nuestro nuevo nombre, nada cambia. Puede seguir construyendo y ejecutando fácilmente las apps y los servicios como siempre. Consulte el [Blog de IBM Cloud](https://www.ibm.com/cloud/blog/announcements/bluemix-is-now-ibm-cloud){: new_window} ![Icono de enlace externo](../../icons/launch-glyph.svg "Icono de enlace externo") para obtener más detalles.

### Cuenta Lite
Novedad desde: 31 de octubre de 2017
{: #new-liteacct}

Una cuenta Lite es nuestro nuevo tipo de cuenta que le da acceso para intentar seleccionar servicios de forma gratuita sin restricciones de tiempo. Esta nueva cuenta también incluye las características de eficiencia y de seguimiento de uso para ayudarle a gestionar mejor sus recursos. Para obtener más información sobre lo que está disponible, consulte [Tipos de cuentas](/docs/account?topic=account-accounts#liteaccount).

### Característica de autenticación de aplicación de Identity and Access Management
Novedad desde: 6 de octubre de 2017
{: #app-authfeature}

Identity and Access Management (IAM) ahora proporciona la capacidad de crear un ID de servicio, que puede pensar que es una identidad que se puede utilizar para las apps para autenticarlas con sus servicios de {{site.data.keyword.Bluemix_notm}}. En lugar de utilizar las credenciales de usuario individual, un ID de servicio puede crearse con una clave de API asociada y los permisos de acceso en forma de una política de servicio que se asigna al ID de servicio para controlar el nivel de acceso para cualquier aplicación que se autentica con ese ID.

Para obtener más información sobre los beneficios de esta característica y cómo empezar, consulte la [Introducción a los ID de servicio y a las claves de API de IAM de IBM Cloud](https://www.ibm.com/cloud/blog/introducing-ibm-cloud-iam-service-ids-api-keys){: new_window} ![Icono de enlace externo](../../icons/launch-glyph.svg "Icono de enlace externo").

### Catálogo global de {{site.data.keyword.Bluemix_notm}}
Novedad desde: 27 de julio de 2017
{: #gc}

Expandiéndose en la última actualización de consola para gestionar sus regiones públicas desde una ubicación única en la consola, {{site.data.keyword.Bluemix_notm}} ahora tiene un catálogo global, que hace que el proceso de selección y de despliegue de elementos que selecciona desde el catálogo sea un proceso más ágil. Independientemente de la región que haya seleccionado en la consola, ahora puede ver todos los servicios que están disponibles en todas las regiones públicas desde el catálogo. Una vez que seleccione un mosaico del catálogo, puede ver en qué regiones está disponible el servicio, y seleccionar dónde desea desplegarlo. Para obtener más información sobre las últimas actualizaciones del catálogo, consulte [Un catálogo global de {{site.data.keyword.Bluemix_notm}} facilita la creación de cosas](https://www.ibm.com/cloud/blog/announcements/global-bluemix-catalog-makes-building-things-easier){: new_window} ![Icono de enlace externo](../../icons/launch-glyph.svg "Icono de enlace externo").

### Actualizaciones de consola de {{site.data.keyword.Bluemix_notm}}
Novedad desde: 23 de mayo de 2017
{: #console-may17}

Ahora puede gestionar sus regiones públicas desde una sola ubicación mediante la consola actualizada de {{site.data.keyword.Bluemix_notm}}. El selector de regiones ofrece acceso ágil a sus recursos, y entre otras mejoras se incluye una mayor disponibilidad y un rendimiento mejorado. Para obtener más información, consulte [Nueva IU de Bluemix global para mayor disponibilidad y más](https://www.ibm.com/blogs/bluemix/2017/05/new-global-bluemix-ui-higher-availability/){: new_window} ![Icono de enlace externo](../../icons/launch-glyph.svg "Icono de enlace externo").

### Gestión de identidad y acceso
Novedad desde: 1 de mayo de 2017
{: #iam-may17}

Con las últimas actualizaciones y mejoras, los propietarios o los administradores de la cuenta de {{site.data.keyword.Bluemix_notm}} ahora pueden utilizar una nueva IU de control de acceso unificada para aprovechar las siguientes funciones:
 * Gestionar el acceso preciso de los usuarios a los servicios de Kubernetes y otros servicios a medida que adopten las nuevas características de control de acceso
 * Asignar políticas de servicio y roles de Cloud Foundry a usuarios dentro de sus organizaciones

Además, los usuarios de la plataforma {{site.data.keyword.Bluemix_notm}} pueden crear, suprimir y listar claves de API asociadas con sus ID de usuario. Y los usuarios de la plataforma pueden utilizar dichas claves de API para autenticarse al utilizar API o CLI.

Por último, hemos mejorado nuestra capacidad de gestión de usuarios unificada para garantizar que en una cuenta IaaS-PaaS enlazada, los usuarios se gestionen de forma unificada sin necesidad de añadir usuarios por separado en el Portal de clientes de SoftLayer o en la consola de {{site.data.keyword.Bluemix_notm}}.

Para obtener más información, consulte la publicación de blog [Introducción a Identity & Access Management](https://www.ibm.com/blogs/bluemix/2017/05/introducing-identity-access-management/){: new_window} ![Icono de enlace externo](../../icons/launch-glyph.svg "Icono de enlace externo").

### Cambios de diseño de navegación para documentos de {{site.data.keyword.Bluemix_notm}}
Novedad desde: 13 de abril de 2017
{: #docnavupdates}

Con esta actualización de navegación, pensamos que comprenderá mejor cómo se organiza el contenido en nuestra documentación, y que podrá encontrar contenido relevante de forma más eficiente. Con menos capas anidadas de contenido, no tendrá que buscar demasiado para encontrar la documentación que necesita para tener éxito con {{site.data.keyword.Bluemix_notm}}.



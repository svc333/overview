---


copyright:
  years: 2016, 2018
lastupdated: "2018-06-14"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# Visión general de la plataforma
{: #overview}

La plataforma informática de nube innovadora de {{site.data.keyword.IBM_notm}} combina la plataforma como servicio (PaaS) con la infraestructura como servicio (IaaS) e incluye un catálogo enriquecido de servicios en la nube que se pueden integrar fácilmente con PaaS e IaaS para compilar aplicaciones empresariales rápidamente.
{:shortdesc}

{{site.data.keyword.cloud_notm}} (anteriormente Bluemix) tiene despliegues que se ajustan a sus necesidades tanto si se trata de un pequeño negocio
con planes de crecimiento, como si es una empresa de gran tamaño que precisa de aislamiento adicional. Puede desarrollar
en una nube sin límites, donde puede conectar sus servicios privados a los servicios {{site.data.keyword.cloud_notm}} públicos disponibles desde {{site.data.keyword.IBM_notm}}. Usted y su equipo pueden acceder a las apps, servicios e infraestructura de {{site.data.keyword.cloud_notm}} y utilicen datos, sistemas, procesos, herramientas de PaaS y de IaaS existentes. Los desarrolladores pueden tocar en el ecosistema de crecimiento rápido de servicios disponibles e infraestructuras de tiempo de ejecución para crear aplicaciones utilizando enfoques de programación políglotas.

Con {{site.data.keyword.cloud_notm}}, ya no tiene que hacer grandes inversiones en hardware para probar o ejecutar una nueva app. En su lugar, se gestiona todo y sólo se le cobrará por lo que utilice. {{site.data.keyword.cloud_notm}} proporciona modelos de despliegue integrados públicos, [dedicados](/docs/dedicated/index.html) y [locales](/docs/local/index.html).

Puede tomar una idea desde el inicio al recinto de seguridad de desarrollo, a un entorno de producción distribuido globalmente con infraestructura de cálculo y de almacenamiento, a servicios y contenedores de plataforma de código abierto, y a servicios y herramientas de software desde {{site.data.keyword.IBM_notm}}, Watson, etc. Más allá de las posibilidades de la plataforma en sí, {{site.data.keyword.cloud}} también proporciona el despliegue flexible. Suministre recursos de {{site.data.keyword.cloud}} locales, en entornos de nubes privadas dedicados o en la nube pública.

Todos los recursos de nube de {{site.data.keyword.IBM_notm}} desplegados en entornos públicos y dedicados se alojan desde la elección de ubicaciones de {{site.data.keyword.CloudDataCent}} de todo el mundo. {{site.data.keyword.CloudDataCents_notm}} proporciona redundancia regional, una red principal céntrica global que conecta todos los centros de datos y los puntos de presencia, y los rigurosos controles de seguridad y creación de informes. Mediante {{site.data.keyword.CloudDataCents_notm}}, {{site.data.keyword.IBM_notm}} puede cumplir sus necesidades más exigentes de expansión, seguridad, conformidad y residencia de datos.

{{site.data.keyword.IBM_notm}} permite hacer lo siguiente:

* Desplegar la infraestructura de almacenamiento y de cálculo de alto rendimiento en {{site.data.keyword.CloudDataCents_notm}} seguro de todo el mundo.
* Probar y adoptar una amplia gama de servicios y prestaciones de nube desde {{site.data.keyword.IBM_notm}}, comunidades de código abierto y desarrolladores de terceros.
* Conectar a todos los sistemas y apps existentes desde una plataforma única, escalable y de nube mediante funciones de API y de red privada.
* Utilizar o descartar recursos en tiempo real a medida que cambien sus necesidades empresariales o sus demandas de carga de trabajo.

## Apps
{: #bluemixoverviewapplications}

El panel de control proporciona todo lo que necesita para hacer que sus apps se ejecuten, y para gestionar dichas apps mientras se ejecutan. {{site.data.keyword.cloud_notm}} proporciona varios contenedores modelo y tiempos de ejecución:

* Un contenedor modelo es una plantilla para una aplicación y su entorno de tiempo de ejecución y servicios predefinidos asociados para un dominio concreto.
* Un tiempo de ejecución es el conjunto de recursos que se utiliza para ejecutar una app, proporcionado como contenedores para distintos tipos de apps.

{{site.data.keyword.cloud_notm}} proporciona distintos modos para ejecutar las apps, como por ejemplo Cloud Foundry y {{site.data.keyword.containerlong}}. Utilice {{site.data.keyword.containerlong}} para ejecutar contenedores de Docker en un entorno de nube alojado en {{site.data.keyword.cloud_notm}}.

Puede utilizar {{site.data.keyword.openwhisk}} para el cálculo distribuido y dirigido por sucesos. {{site.data.keyword.openwhisk_short}} ejecuta la lógica de aplicaciones en respuesta a sucesos o invocaciones directas desde apps web o móviles a través de HTTP.

Puede utilizar los servicios móviles de {{site.data.keyword.cloud_notm}} para incorporar servicios de nube integrados, gestionados y escalables a las apps móviles.

## Servicios
{: #bluemixoverviewservices}

El panel de control proporciona acceso a los servicios de {{site.data.keyword.cloud_notm}} disponibles desde {{site.data.keyword.IBM}} y proveedores de terceros. Estos incluyen servicios Watson, Internet of Things, Analytics, Mobile y DevOps:

* Entregar nuevas aplicaciones innovadoras de una forma más rápida y barata con tan sólo las características correctas utilizando los servicios de {{site.data.keyword.IBM_notm}} e IBM Cloud Garage Method. Al adoptar prácticas de DevOps y crear una cultura de innovación y agilidad, puede utilizar prácticas iterativas y cambiar de dirección en respuesta al mercado.
* Blockchain es una tecnología de libro mayor distribuida de igual a igual para una nueva generación de aplicaciones transaccionales que establece confianza, responsabilidad y transparencia mientras se reducen los procesos empresariales.  
* Watson proporciona a las apps la potencia de la informática cognitiva con una suite completa de API de voz, visión y datos.  Resuelva sus problemas empresariales más complejos desplegando una plataforma cognitiva con servicios de Watson.
* {{site.data.keyword.IBM_notm}} le permite hacer más con bases de datos de nube enriquecidas e integradas y servicios de Data & Analytics.
* El servicio de Internet of Things de {{site.data.keyword.IBM_notm}} permite a las apps comunicarse y consumir datos recopilados por los dispositivos, sensores y pasarelas conectados. Nuestras recetas facilitan la obtención de dispositivos conectados a nuestra nube de Internet of Things. Sus apps pueden utilizar las API de tiempo real y las API REST para comunicarse con sus dispositivos y consumir los datos configurados para su recopilación.
* {{site.data.keyword.IBM_notm}} ofrece una infraestructura de programa de fondo móvil donde puede crear apps de multiplataforma, nativas o híbridas mientras también puede supervisarlas y probarlas. También puede mejorar su app con analíticas, seguridad, las valoraciones de los usuarios y la entrega continua.

{{site.data.keyword.cloud_notm}} también proporciona servicios experimentales que puede probar. Para obtener más información sobre los tipos de servicios y su disponibilidad, consulte [Servicios de {{site.data.keyword.cloud_notm}}](/docs/services/index.html).


## Infraestructura
{: #bluemixoverviewinfrastructure}

El panel de control proporciona varios servicios para que se ajusten a sus necesidades de infraestructura de nube.

La infraestructura de {{site.data.keyword.cloud_notm}} proporciona la infraestructura de nube que más funciona disponible. La infraestructura de {{site.data.keyword.cloud_notm}} es una plataforma, que toma los centros de datos de todo el mundo que están llenos de la gama más amplia de las opciones de informática de nube y que integra y que lo automatiza todo. {{site.data.keyword.CloudDataCents_notm}} se llenan con equipamiento informático, de almacenamiento y de red de primera clase. Cada ubicación está construida, equipada y operada de la misma forma, de manera que obtiene exactamente las mismas capacidades y disponibilidad en cualquiera de nuestras ubicaciones. Las ubicaciones están conectadas mediante la tecnología "red dentro de red" más avanzada del sector, que integra redes públicas, privadas y de gestión interna distintas para proporcionar unos costes de gestión de red más reducidos, un mejor acceso y una mayor velocidad. Igualmente, los centros de datos y la red comparten un único sistema de gestión de propiedad. Una herramienta de gestión le permite controlarlo todo (cada servidor nativo, cada servidor virtual y cada dispositivo de almacenamiento), todo accesible mediante API, portal y aplicaciones móviles.

La infraestructura de {{site.data.keyword.cloud_notm}} ofrece potentes servidores nativos y flexibles servidores virtuales en una única plataforma. Todos se proporcionan bajo demanda y se facturan en términos mensuales o por hora. Los servidores nativos proporcionan la potencia bruta para las cargas de trabajo que utilizan mucho procesador y E/S y pueden configurarse exactamente según sus especificaciones. Los servidores virtuales le permiten una alta velocidad de despliegue, una escalabilidad flexible y una facturación de pago según uso. Para la informática de alto rendimiento, mejore su nube con servidores GPU (Graphics Processing Unit), disponibles por hora o por mes.

Las ofertas de infraestructura de {{site.data.keyword.cloud_notm}} están conectadas a una red de tres capas, que segmenta tráfico público, privado y de gestión. La infraestructura de una cuenta de {{site.data.keyword.cloud_notm}} del cliente puede transferir datos entre esta infraestructura mediante la red privada sin coste adicional. Las ofertas de infraestructura, como los servidores nativos, los servidores virtuales y el almacenamiento en nube, se conectan con otras aplicaciones y servicios del catálogo de {{site.data.keyword.cloud_notm}}, como por ejemplo servicios, contenedores o tiempos de ejecución de Watson, en la red pública. La transferencia de datos entre estos dos tipos de ofertas se mide y se carga en tasas estándares de ancho de banda de red públicas.

## Regiones
{: #ov_intro_reg}

Una región de {{site.data.keyword.cloud_notm}} es un territorio geográfico definido en el que puede desplegar sus apps. Puede crear apps e instancias de servicios en distintas regiones con la misma infraestructura de {{site.data.keyword.cloud_notm}} para la gestión de apps y la misma vista de detalles de uso para la facturación. Tiene la posibilidad de desplegar sus apps en la región más cercana a sus clientes para conseguir una latencia de aplicación baja. Para solventar problemas de seguridad, también puede seleccionar la región en la que desea conservar los datos de app. Cuando crea apps en varias regiones, si una región queda fuera de servicio, las apps que están en las otras regiones seguirán funcionando. Su concesión de recursos es la misma para cada región que utilice.

El equilibrio de carga global de la consola permite asegurar que si por alguna razón la región geográfica más próxima no está disponible, la consola visualiza la información de la siguiente región más próxima. De esta forma, siempre podrá acceder a la consola sin realizar acción alguna para acceder a la información que necesita.

Desde el panel de control, puede ver todos los recursos en todas las regiones de forma predeterminada. Si desea ver y trabajar con recursos en una región específica, expanda el menú **LOCATION** y seleccione una región de la lista. 

También puede utilizar la interfaz de línea de mandatos para conectarse a la región de {{site.data.keyword.cloud_notm}} con la que desee trabajar utilizando el mandato `ibmcloud api` y especificando el punto final de API de la región. Por ejemplo, escriba el siguiente mandato para conectarse a la región de
{{site.data.keyword.cloud_notm}} de Europa - Reino Unido:

```
ibmcloud api https://api.eu-gb.bluemix.net
```

Cada región tienen asignado un prefijo exclusivo. {{site.data.keyword.cloud_notm}} proporciona las siguientes regiones y prefijos.

| **Nombre de la región** | **Ubicación geográfica** | **Punto final cf API** |
|-----------------|-------------------------|-------------------|
| Región EE.UU. sur | Dallas, EE.UU. | api.ng.bluemix.net | 
| Región EE.UU. este | Washington, DC, EE.UU. | api.us-east.bluemix.net |
| Región Reino Unido | Londres, Inglaterra | api.eu-gb.bluemix.net | 
| Región Sídney | Sídney, Australia | api.au-syd.bluemix.net | 
| Región Alemania | Frankfurt, Alemania | api.eu-de.bluemix.net | 
{: caption="Tabla 1. Lista de regiones de {{site.data.keyword.cloud_notm}}" caption-side="top"}

## Resiliencia de {{site.data.keyword.cloud_notm}}
{: #resiliency}

Se ha diseñado {{site.data.keyword.cloud_notm}}
para alojar apps y artefactos de apps resilientes y escalables
que puedan escalarse para cumplir sus necesidades, así como para ofrecer una alta disponibilidad
y una recuperación rápida de problemas. {{site.data.keyword.cloud_notm}} separa los componentes que realizan un seguimiento del estado de las interacciones (con estado)
de los que no (sin estado). Esta separación permite que {{site.data.keyword.cloud_notm}} pueda
trasladar apps de forma flexible según convenga para lograr escalabilidad y resiliencia.

Puede tener una o varias instancias en ejecución para la app. Para varias instancias de una única app, la app solo se carga una vez. Sin embargo, {{site.data.keyword.cloud_notm}} despliega
el número de instancias de la app solicitada y las distribuye
a través del mayor número posible de servidores virtuales.

Debe guardar todos los datos persistentes
en un almacén de datos con estado que se encuentre fuera de la app,
como por ejemplo en uno de los servicios de almacenamiento de datos que proporciona {{site.data.keyword.cloud_notm}}. Dado que es posible que algún elemento almacenado en la memoria caché o en el disco no esté disponible
incluso después de reiniciar, puede utilizar el espacio de memoria o sistema de archivos de una instancia
de {{site.data.keyword.cloud_notm}}
como caché rápida de transacción única. Con una sola configuración de instancia,
la solicitud a su app puede interrumpirse debido a la naturaleza sin estado
de {{site.data.keyword.cloud_notm}}. Se recomienda utilizar como mínimo tres instancias para cada app
para garantizar su disponibilidad.

La infraestructura de {{site.data.keyword.cloud_notm}}, todos los componentes de Cloud Foundry y los componentes de gestión específicos de {{site.data.keyword.cloud_notm}} tienen una alta disponibilidad. Se utilizan varias instancias de la infraestructura
para equilibrar la carga.

## Integración con sistemas de registros
{: #sor}

{{site.data.keyword.cloud_notm}} puede ayudar a los desarrolladores ya que conecta dos amplias categorías de sistemas en un entorno de nube:

* Los *sistemas de registro* incluyen apps y bases de datos que almacenan registros empresariales y automatizan los procesos estandarizados.
* Los *sistemas colaborativos* ofrecen prestaciones que amplían la utilidad de los sistemas de registros y facilitan la colaboración por parte de los usuarios.

Mediante la integración de un sistema de registros con la app que cree en {{site.data.keyword.cloud_notm}}, puede llevar a cabo estas acciones:

 * Permitir una comunicación segura entre la app y la base de datos de fondo descargando e instalando un conector seguro local.
 * Invocar una base de datos de forma segura.
 * Crear API a partir de flujos de integración con bases de datos y sistemas de fondo, como por ejemplo un sistema de gestión de relaciones con los clientes.
 * Exponer únicamente los esquemas y las tablas que desea exponer a la app.
 * Como gestor de la organización de {{site.data.keyword.cloud_notm}}, publicar una API como servicio privado que sea visible sólo para los miembros de su organización.

Para integrar un sistema de registros con las apps que cree en {{site.data.keyword.cloud_notm}}, utilice el servicio de Cloud Integration. Utilizando el servicio de Cloud Integration, puede crear una API de Cloud Integration y publicar la API como un servicio privado para su organización.

<dl>
<dt>API de Cloud Integration</dt>
    <dd>Una API de Cloud Integration proporciona un acceso seguro a los sistemas de registro que residen detrás de un cortafuegos mediante las API web. Al crear la API de Cloud Integration, debe elegir el recurso al que desea acceder mediante la API web, especificar las operaciones que se permiten e incluye los SDK y ejemplos para acceder a la API. Para obtener más información sobre cómo crear una API de Cloud Integration, consulte [Iniciación a Cloud Integration](/docs/services/CloudIntegration/CldInt_GetStart.html).</dd>
<dt>Servicio privado</dt>
    <dd>Un servicio privado consiste en una API de Cloud Integration, los SDK y políticas de titularidad. El servicio privado también podría contener documentación u otros elementos del proveedor de servicios. Sólo el gestor de la organización puede publicar una API de Cloud Integration como un servicio privado. Para ver los servicios privados que tiene disponibles, marque el recuadro de selección Privado en el catálogo de {{site.data.keyword.cloud_notm}}. Puede seleccionar y enlazar un servicio privado a una app sin conectarse al servicio de Cloud Integration. Los servicios privados se enlazan a su app de la misma forma en que se hace en otros servicios de {{site.data.keyword.cloud_notm}}. Para obtener información sobre cómo publicar una API como un servicio privado, consulte Publicación de una API como un servicio privado.</dd>
</dl>

### Caso de ejemplo: creación de una potente app móvil para conectar con su sistema de registros
{: #scenario}

{{site.data.keyword.cloud_notm}} ofrece una plataforma en la que puede integrar su app para móvil, servicios de nube y sistemas de registros de la empresa a fin de proporcionar una app que interactúe con los datos locales.

Por ejemplo, puede crear una app para móvil para interactuar con el sistema de gestión de relaciones con los clientes que reside de forma local detrás de un cortafuegos. Puede invocar el sistema de registros de manera segura y aprovechar los servicios móviles de {{site.data.keyword.cloud_notm}} para crear una potente app móvil.

En primer lugar, el desarrollador de integración crea la app móvil de fondo en {{site.data.keyword.cloud_notm}}. Utilizan el contenedor modelo de Mobile Cloud que usa el tiempo de ejecución Node.js con el que están más familiarizados.

A continuación, mediante el uso del servicio Cloud Integration en la interfaz de usuario de {{site.data.keyword.cloud_notm}}, exponen una API a través de un conector seguro. El desarrollador de integración descarga el conector seguro y lo instala de forma local para permitir la comunicación segura entre su API y la base de datos. Después de crear el punto final de la base de datos, examinan todos los esquemas y extraen las tablas que desean exponer como API ante la app.

El desarrollador de integración añade el servicio Push para enviar notificaciones móviles a los consumidores interesados. También añaden un servicio de un business partner para iniciar un tweet cuando se crea un nuevo registro de cliente con una API
de Twitter.

A continuación, como desarrollador de la app, puede iniciar una sesión en {{site.data.keyword.cloud_notm}},
descargar el kit de herramientas de desarrollo de Android y desarrollar código que invoque las API que ha creado el desarrollador de integración. Puede desarrollar una app móvil que permita a los usuarios entrar la información en su dispositivo móvil. Luego la app para móvil crea un registro de cliente en el sistema de gestión de clientes. Cuando se crea el registro, la app envía una notificación a un dispositivo móvil e inicia un tweet sobre el nuevo registro.

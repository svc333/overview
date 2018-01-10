---


copyright:
  years: 2016, 2017
lastupdated: "2017-12-15"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# Cómo funciona Cloud Foundry con {{site.data.keyword.cloud_notm}}
{: #howwork}

Cuando despliega una app en Cloud Foundry, debe configurar {{site.data.keyword.cloud_notm}} con suficiente información para dar soporte a la app.

* En el caso de una app para móvil, {{site.data.keyword.cloud_notm}} contiene un artefacto que representa el programa de fondo de las apps para móvil, como por ejemplo los servicios que utilice la app para móvil para comunicarse con un servidor.
* En el caso de una app web, debe asegurarse de que esta información sobre el tiempo de ejecución y la infraestructura se comunique a {{site.data.keyword.cloud_notm}}, para que {{site.data.keyword.cloud_notm}} pueda configurar el entorno de ejecución apropiado para ejecutar la app.

Cada entorno de ejecución, que incluye tanto móvil como web, se aísla del entorno de ejecución de otras apps. Los entornos de ejecución se aíslan aunque estas apps estén en la misma máquina física. La figura siguiente muestra el flujo básico de cómo Cloud Foundry gestiona el despliegue de apps en {{site.data.keyword.cloud_notm}}:

![Despliegue de una app](images/deploy.png)

Figura 1. Despliegue de una app

Cuando crea una app y la despliega en Cloud Foundry, el entorno de {{site.data.keyword.cloud_notm}} determina un servidor virtual adecuado al que se envía la app, o los artefactos que representa la app. En el caso de una app para móvil, se crea una proyección de proceso en {{site.data.keyword.cloud_notm}}. Cualquier código de la app para móvil de la nube en principio se ejecuta en el entorno de {{site.data.keyword.cloud_notm}}. En el caso de una app web, el código que se ejecuta en la nube es la propia app que el desarrollador despliega en {{site.data.keyword.cloud_notm}}. La determinación del servidor virtual se basa en varios factores, que incluyen los siguientes:

* La carga que ya soporta la máquina
* Los tiempos de ejecución o infraestructuras que soporta dicho servidor virtual.

Después de seleccionar un servidor virtual, un gestor de apps de cada servidor virtual instala la infraestructura y el tiempo de ejecución adecuados para la app. Luego la app se puede desplegar en esta infraestructura. Cuando se completa el despliegue, se inician los artefactos de la app.

La siguiente figura
muestra la estructura de un servidor virtual, también conocido como agente de ejecución de gotas (DEA), en el que se han desplegado varias apps:

![Diseño de un servidor virtual](images/container-diego.png)

Figura 2. Diseño de un servidor virtual

En cada servidor virtual, un gestor de apps se comunica con el resto de la infraestructura de {{site.data.keyword.cloud_notm}} y gestiona las apps que se despliegan en este servidor virtual. Cada servidor virtual dispone de contenedores para separar y proteger las apps. En cada contenedor, {{site.data.keyword.cloud_notm}} instala la infraestructura y el tiempo de ejecución adecuados que necesita cada app.

Cuando se despliega la app, si tiene una interfaz web (como por ejemplo una app web Java) y otros servicios basados en REST (como por ejemplo servicios móviles expuestos públicamente para la app para móvil), los usuarios de la app pueden comunicarse con la misma mediante solicitudes HTTP normales.

![Invocación de una app de {{site.data.keyword.cloud_notm}}](images/execute.png)

Figura 3. Invocación de una app de {{site.data.keyword.cloud_notm}}

Cada app puede tener uno o varios URL asociados, pero todos deben apuntar al punto final de {{site.data.keyword.cloud_notm}}. Cuando entra una solicitud, {{site.data.keyword.cloud_notm}} la examina, determina la app a la que va destinada y a continuación selecciona una instancia de la app para que reciba la solicitud.


## Arquitectura Cloud Foundry en {{site.data.keyword.cloud_notm}}
{: #architecture}

En general, no debe preocuparse de las capas de sistema operativo y de infraestructura cuando ejecute apps en {{site.data.keyword.cloud_notm}} en Cloud Foundry. Las capas de tipo sistemas de archivos raíz y componentes de middleware se abstraen para que se pueda centrar en el código de la app. Sin embargo, puede obtener más información sobre estas capas y necesita datos específicos sobre dónde se ejecuta la app.

Consulte [Visualización de las capas de la infraestructura de {{site.data.keyword.cloud_notm}}](/docs/manageapps/infra.html#viewinfra) para obtener detalles.

Como desarrollador, puede interactuar con la infraestructura de {{site.data.keyword.cloud_notm}} mediante una interfaz de usuario basada en navegador. También puede utilizar una interfaz de línea de mandatos de Cloud Foundry, denominada cf, para desplegar apps web.

Los clientes, que pueden ser apps móviles, las apps que se ejecutan externamente, las apps creadas en {{site.data.keyword.cloud_notm}} o los desarrolladores que utilizan navegadores interactúan con las apps alojadas en {{site.data.keyword.cloud_notm}}. Los clientes utilizan las API REST o HTTP para dirigir las solicitudes a través de {{site.data.keyword.cloud_notm}} a una de las instancias de la app o a los servicios compuestos.

La figura siguiente muestra la arquitectura de Cloud Foundry de alto nivel en {{site.data.keyword.cloud_notm}}.

![Arquitectura de {{site.data.keyword.cloud_notm}}](images/arch.png)

Figura 4. Arquitectura de Cloud Foundry en {{site.data.keyword.cloud_notm}}

Puede desplegar sus apps en distintas regiones de {{site.data.keyword.cloud_notm}}, por motivos de latencia o de seguridad. Puede elegir desplegar en una región o a lo largo de varias regiones.


![Desarrollo de apps en varias regiones](images/multi-region.png)

Figura 5. Despliegue de apps en varias regiones

## Regiones
{: #ov_intro_reg}

Una región de {{site.data.keyword.cloud_notm}} es un territorio geográfico definido en el que puede desplegar sus apps. Puede crear apps e instancias de servicios en distintas regiones con la misma infraestructura de {{site.data.keyword.cloud_notm}} para la gestión de apps y la misma vista de detalles de uso para la facturación. Tiene la posibilidad de desplegar sus apps en la región más cercana a sus clientes para conseguir una latencia de aplicación baja. Para solventar problemas de seguridad, también puede seleccionar la región en la que desea conservar los datos de app. Cuando crea apps en varias regiones, si una región queda fuera de servicio, las apps que están en las otras regiones seguirán funcionando. Su concesión de recursos es la misma para cada región que utilice.

Si utiliza la consola de {{site.data.keyword.cloud_notm}}, automáticamente se muestra la información de la región geográfica en buen estado más cercana. El equilibrio de carga global de la consola permite asegurar que si por alguna razón la región geográfica más próxima no está disponible, la consola visualizará la información de la siguiente región más próxima. De esta forma, siempre tendrá acceso a la consola sin necesidad de acción alguna para acceder a la información que necesita.

Utilice el selector de región en la consola para filtrar la vista. Por ejemplo, si está accediendo a sus apps y servicios desde Dallas, región de EE.UU., y desea ver las apps y servicios de la región de Londres, utilice el selector de región para cambiar la vista:

1. Pulse en el enlace de preferencias de cuenta.
2. Amplíe el menú **Región**.
3. Seleccione en la lista la región que desee.

Si filtra la vista según la región podrá cambiar entre vistas con rapidez para trabajar con organizaciones, espacios y usuarios asignados a las distintas regiones.

Si utiliza la interfaz de línea de mandatos cf para conectarse a la región de {{site.data.keyword.cloud_notm}} con la que desea trabajar, utilice el mandato cf api y especifique el punto final de la API de la región. Por ejemplo, escriba el siguiente mandato para conectarse a la región de
{{site.data.keyword.cloud_notm}} de Europa - Reino Unido:

```
cf api https://api.eu-gb.bluemix.net
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

Puede tener una o varias instancias en ejecución para la app. Para varias instancias de una única app, la app sólo se cargará una vez. Sin embargo, {{site.data.keyword.cloud_notm}} despliega
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

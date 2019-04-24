---

copyright:
  years: 2016, 2019
lastupdated: "2019-02-19"

keywords: developer tools, building apps, developer entry point, understanding dev journey, get started coding

subcollection: overview

---
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}
{:tip: .tip}

# Conozca los distintos caminos de desarrollo en {{site.data.keyword.cloud_notm}}
{: #dev-journey}

Como desarrollador, decide el mejor punto de entrada para su código. Puede elegir entre generar el código mediante las herramientas que le proporcionamos o traer su propio código y desplegarlo en {{site.data.keyword.cloud}}.
{: shortdesc}

{{site.data.keyword.cloud_notm}} tiene un conjunto de funcionalidades que permiten crear apps en minutos. Las herramientas de desarrollador de {{site.data.keyword.cloud_notm}} crean una base de alto rendimiento necesaria para empezar a trabajar. Se ofrecen dos herramientas principales para el desarrollo:
 * Consola web de {{site.data.keyword.cloud_notm}} (portales del desarrollador)
 * Interfaz de línea de mandatos (CLI) de {{site.data.keyword.cloud_notm}}

Con {{site.data.keyword.cloud_notm}}, puede hacer lo siguiente:

* Seleccionar kits de inicio que específicos de casos de uso y crear apps listas para producción en distintos lenguajes de programación y patrones arquitectónicos.
* Utilizar un [patrón de código de IBM Developer ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo")](https://developer.ibm.com/patterns/){:new_window} para crear rápidamente una app y desplegarla en {{site.data.keyword.cloud_notm}}.
* Consulte y gestione los recursos que se suministran automáticamente desde el kit de inicio o los que ha añadido manualmente a su app.
* Si dispone de una app en un repositorio existente, puede utilizar un kit de inicio vacío para crear un registro de app y conectarlo al repositorio de origen y a una cadena de herramientas de DevOps.
* Con un código de app portátil, puede desplegarse en varios entornos de nube.
* Crear una [cadena de herramientas de DevOps](/docs/services/ContinuousDelivery?topic=ContinuousDelivery-cd_getting_started) en pocos clics.
* Utilizar la [interfaz de línea de mandatos (CLI)](/docs/cli/reference/ibmcloud?topic=cloud-cli-ibmcloud-cli#ibmcloud-cli) para el desarrollo local.
* Examinar o buscar en el [catálogo de {{site.data.keyword.cloud_notm}} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo")](https://{DomainName}/catalog){: new_window} apps y servicios que puede crear y comenzar a utilizar hoy mismo.

![Visión general de Experiencia del desarrollador](images/dev-journey.png "Visión general de Experiencia del desarrollador")

Para comprender mejor cómo la experiencia puede ayudarle a crear rápidamente apps de alta calidad listas para un entorno de producción, consulte estos elementos en más detalle.

## Portales de desarrollador
{: #dev-portals}

{{site.data.keyword.cloud_notm}} tiene portales de desarrollador en distintas áreas de interés (por ejemplo, Watson, Seguridad o Finanzas) o para un canal digital (como por ejemplo, apps móviles o web). Puede acceder a estos portales desde el icono **Menú** ![icono Menú](../icons/icon_hamburger.svg).

Cada portal de desarrollador proporciona kits de inicio relevantes para el área de atención del portal. Los portales ofrecen un flujo de trabajo coherente e intuitivo para crear una app lista para producción en cuestión de minutos.

## Apps
{: #app-projects}

Una app consta de código, datos, servicios y cadenas de herramientas. Por ejemplo, la app móvil de {{site.data.keyword.cloud_notm}} contiene código de fondo junto con lógica de fondo, almacenamiento de datos, analíticas y servicios de seguridad y, además, está configurado para una entrega continua.

![Reutilizar](images/garage_reuse2.png "Con Experiencia del desarrollador, puede reutilizar para no tener que reinventar")

Puede crear y gestionar una app utilizando cualquier portal de desarrollador de {{site.data.keyword.cloud_notm}} o {{site.data.keyword.dev_cli_notm}}.

Puede crear apps sencillas vacías directamente o crear apps más complejas utilizando nuestros kits de inicio. Si decide crear apps vacías sin la ayuda de un kit de inicio, puede hacerlo desde el [panel de control de {{site.data.keyword.cloud_notm}} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo")](https://{DomainName}){: new_window} sin visitar ningún portal.

Puede utilizar un patrón de código para crear rápidamente una app y desplegarla en {{site.data.keyword.cloud_notm}}. En el [sitio web de IBM Developer ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo")](https://developer.ibm.com/patterns/){:new_window}, elija un patrón de código. Puede ver el código en GitHub o crear y compilar una app en {{site.data.keyword.cloud_notm}}, donde puede utilizar una cadena de herramientas de DevOps para desplegar automáticamente la app.


## Kits de inicio
{: #starter-kits}

Con los kits de inicio, su experiencia debería resultar sencilla y personalizable. Los kits de inicio ensamblan una app de producción de esqueleto, en el lenguaje de su elección, listo para el despliegue en la nube. Cada kit de inicio incluye un lenguaje, una infraestructura, un patrón para un caso de uso específico y para la reutilización del código.

Si un kit de inicio requiere recursos específicos, no hay ningún problema. Con los recursos de suministro automático, {{site.data.keyword.cloud_notm}} crea automáticamente instancias para dichos recursos al crear la app. Puede acceder a kits de inicio desde el portal de desarrollador o la interfaz de línea de mandatos para obtener instrucciones relevantes a su área de atención y flujo de trabajo.

### ¿En qué se diferencian los kits de inicio de los ejemplos?
Los kits de inicio están listos para ser utilizados en producción y se centran en demostrar una implementación de un patrón clave utilizando un tiempo de ejecución (por ejemplo Node.js y Express). En algunos casos, los kits de inicio ofrecen una experiencia de usuario simple para resaltar la integración del servicio. En otros casos los kits de inicio representan una implementación personalizable de un caso de uso sofisticado.

* Un fragmento son unas pocas líneas de código que a menudo se presentan en un IDE. Los fragmentos ayudan a un desarrollador a integrar con una sintaxis de lenguaje de programación o dar soporte a la integración con una API definida.
* Una demostración normalmente ofrece una alta calidad y fidelidad y utiliza distintos servicios y puntos de integración. A menudo precisa de tiempo para configurarla y se utiliza para probar un problema empresarial o para demostrar una característica de una plataforma. Puede utilizarla para evaluar las etapas de la adopción en la nube. A veces, es código que se incluye en el código de producción.
* Un ejemplo es un pequeño ejemplo de una característica, función, servicio o recorrido de usuario específicos. Puede reutilizar un ejemplo o incluirlo en una aplicación de producción. Se suele utilizar para mostrar las posibilidades técnicas y un posible enfoque para resolver un problema técnico.
* Un kit de inicio es un patrón listo para el entorno de producción que se puede integrar con un conjunto de servicios para generar un activo listo para producción y que se puede desplegar directamente en un conducto de DevOps y en un clúster de Kubernetes. Un kit de inicio contiene metadatos descriptivos que proporcionan al usuario suficiente información para saber qué es y que hace el kit. También contiene instrucciones que indican a {{site.data.keyword.cloud_notm}} lo que debe producir. La salida está lista para producción desde un principio. Luego, de forma iterativa, puede añadir más mejoras con base a las prácticas recomendadas de IBM. El contenido del kit de inicio no es tan complejo como una demostración ni tan trivial como un ejemplo o fragmento de código. Se crean de forma dinámica en función de los requisitos del desarrollador.

## Recursos de suministro automático
{: #auto-provision}

Si un kit de inicio especifica recursos que son necesarios, {{site.data.keyword.cloud_notm}} crea automáticamente las instancias de estos recursos al crear la app. También puede suministrar recursos o seleccionar las instancias de recursos existentes de forma manual para añadirlos a su app después de haberlo creado. Puede ver una lista de instancias de servicio asociadas a su app en la vista Detalles de la app junto con credenciales en caso de que las necesite.

## Código portátil
{: #portable-code}

Cuando se crea una app a partir de kit de inicio, automáticamente se produce un código con un formato coherente y con que depende del tiempo de ejecución. Puede desplegarlo en el entorno que desee como, por ejemplo, Kubernetes o Cloud Foundry, sin realizar cambios.

También puede revisar su código de app haciendo clic en **Descargar código** en la página Detalles de app de la app. El código se descarga como un archivo `.zip` que contiene toda la estructura del código de la app. Puede extraer fácilmente el archivo y ejecutar el código localmente utilizando {{site.data.keyword.dev_cli_notm}}, o añadirlo su repositorio de gestión de código.

### ¿Qué código se crea?
{: #what-code}

Cuando crea una app directamente o con ayuda de un kit de inicio, la app contiene código portátil. El código portátil contiene código de habilitación en la nube para varios entornos de nube. Después podrá crear código en cuatro áreas básicas:
* Código que sigue las prácticas recomendados de un idioma específico
* Código que permite que la app se ejecute en la nube
* Código que se ha inicializado para conectarse a servicios de nube
* Código que es específico de un caso de uso

La generación de estos componentes ahorra un tiempo valioso y asegura la utilización de la mejor arquitectura.

* La lógica de los casos de uso proporciona funciones para la función principal de un caso de uso concreto. Por ejemplo, el código para un chat bot de Watson Conversation o el código para una app móvil de reconocimiento visual.
* Los componentes de lenguaje son componentes de código y archivos específicos del lenguaje de programación que selecciona para el kit de inicio. Por ejemplo, los programadores de node.js necesitan un archivo package.json para la gestión de dependencias. Este archivo se crea en nombre del usuario de forma automática.
* Habilitación del servicio es el código que permite que su app se conecte y utilice los servicios que añade. La gestión de credenciales, el código de inicialización y SDK específicos de servicio son ejemplos de elementos de habilitación del servicio.
* La habilitación en la nube se corresponde con el código que permite ejecutar la app en {{site.data.keyword.cloud_notm}}. Por ejemplo, diagramas de Helm que permiten la ejecución de una app en un clúster Kubernetes de {{site.data.keyword.cloud_notm}}.

Cuando se crea una app an partir de un kit de inicio de {{site.data.keyword.cloud_notm}}, la app se inicia con la arquitectura probada que también refleja las mejores prácticas para el idioma seleccionado.

Cada app incluye un archivo readme que contiene detalles técnicos de la app y explica lo que se necesita para ejecutar la app si no se ejecuta desde un principio.
{: tip}

## Utilice su propio código y despliéguelo en {{site.data.keyword.cloud_notm}}
{: byoc}

Si dispone de una app en un repositorio existente, puede utilizar un kit de inicio vacío para crear un registro de app en {{site.data.keyword.cloud_notm}} y conectarlo al repositorio de origen y una cadena de herramientas de DevOps.

Puede empezar desde el panel de control de {{site.data.keyword.cloud_notm}} o desde cualquier kit de inicio vacío. Después de dar un nombre a la app y seleccionar un grupo de recursos, seleccione el punto de inicio [**Traiga su propio código**](/docs/apps/tutorials?topic=creating-apps-tutorial-byoc#tutorial-byoc), proporcione el URL de repositorio Git que contiene el código y pulse en **Crear**.

Puede volver a conectar su cadena de herramientas DevOps existente o crear una y entregar de forma continua la app al entorno que elija, como Kubernetes o Cloud Foundry.


## Cadena de herramientas de DevOps
{: #devops}

La cadena de herramientas de DevOps consta de procedimientos y herramientas para acceder, desarrollar, desplegar y operar con su app. Una cadena de herramientas de DevOps es un conjunto de servicios relacionados que automatizan las tareas de DevOps. Es posible realizar manualmente las tareas de DevOps con apps sencillas, sin embargo, la necesidad de automatización para apps aumenta rápidamente cuando lo hace su complejidad. La automatización de una cadena de herramientas es un componente necesario para la entrega continua.

El componente principal de una cadena de herramientas de DevOps es un repositorio de control de versiones de código como GitHub. Otras herramientas adicionales corresponden al rastreo de procesos realizados, a los conductos de entrega, al IDE y a los servicios de supervisión como, por ejemplo, [{{site.data.keyword.cloud_notm}} {{site.data.keyword.DRA_short}}](/docs/services/DevOpsInsights?topic=DevOpsInsights-getting-started#getting-started).

Si crea una app mediante un kit de inicio, puede crear una nueva cadena de herramientas y desplegar su app simplemente pulsando **Desplegar en la nube** en la página **Detalles de la app**. Se crea una cadena de herramientas con un repositorio de código, problemas de repositorio, conducto de entrega e IDE de web.

A continuación puede desarrollar en esta cadena de herramientas para acomodarla a varios equipos y desplegar en entornos distintos para desarrollo, pruebas y producción. Establezca un modelo de entrega continuo colaborativo de nivel empresarial para su app.

![Entrega continua](images/garage_continuous_delivery2.png "La experiencia del desarrollador establece una entrega continua en su rama de desarrollo")


## CLI
{: cli}

Utilice la interfaz de línea de mandatos (CLI) para codificar, compilar y ejecutar la app localmente. Un patrón habitual es crear la app desde un portal de desarrollador en la consola {{site.data.keyword.cloud_notm}}, utilizar las herramientas de desarrollador para desarrollar localmente y enviar las actualizaciones al repositorio y fusionarlas para empezar su cadena de herramientas de despliegue.

## Desarrollo del Garage Method
{: #developer_concepts}

Si está buscando un lugar donde poder experimentar con grandes ideas y tecnologías emergentes, asegúrese de consultar los despliegues [Método Garage](https://www.ibm.com/cloud/garage/){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo"). Puede obtener más información sobre cómo IBM puede ayudarle a desarrollar apps en la organización. 

![Visión general de fases del Garage Method](images/garage_phases_overview2.png "Visión general de fases del Garage Method") 

{{site.data.keyword.cloud_notm}} sirve para crear apps de producción de nivel empresarial de forma satisfactoria utilizando el Garage Method o cualquier otro método que prefiera. Para comprender mejor lo que {{site.data.keyword.cloud_notm}} tiene que ofrecer a los desarrolladores, repasemos brevemente los conocimientos necesarios para crear una app moderna.

## Conocimientos técnicos de los desarrolladores
{: #skills}

Más que nunca, los usuarios esperan lo mejor de sus aplicaciones. Desean apps que entreguen conocimiento profundo de los datos almacenados y los recopilados en tiempo real, que estén siempre disponibles y que se ajusten lo mejor posible a sus necesidades individuales. Para satisfacer estas expectativas, las funciones de desarrollador de IBM Cloud se alinean con conjuntos de habilidades específicos y permiten a su equipo utilizar una plataforma para producir, entregar y gestionar apps. Por ejemplo, una aplicación cognitiva sofisticada podría precisar de las contribuciones de los desarrolladores digitales, desarrolladores nativos en la nube, desarrolladores de corrientes de datos, científicos de datos y especialistas de DevOps.

 ![Tipos de desarrollador](images/developer_skills.png "Relaciones de desabolladores")

* Desarrolladores digitales: crean para un canal digital concreto como, por ejemplo, chat, voz o web móvil. Los desarrolladores digitales normalmente se centran en casos de uso y satisfacer directamente las necesidades de los usuarios como una experiencia global.
* Desarrolladores nativos en la nube: se especializan en la construcción e interconexión de componentes en la nube. Los creadores de microservicios y sistemas frontales/de fondo se incluyen en esta categoría.
* Desarrolladores de corrientes: se centran en el proceso y la obtención de conocimientos a partir de corrientes de datos. Por ejemplo, un desarrollador de corrientes podría analizar y tomar acciones con base a corrientes entrantes de vídeo, habla o texto.
* Científicos de datos: utilizan analíticas y aprendizaje máquina para crear modelos predictivos. Estos modelos se utilizan en las métricas empresariales y proporcionar conocimientos profundos a los usuarios de las aplicaciones.
* Especialistas de DevOps: expertos en resolver los problemas de despliegue y cadenas de herramientas. Para apps simples, habitualmente no son necesarios especialistas dedicados puesto que los miembros del equipo de desarrollo gestionan las operaciones de DevOps conjuntamente. Pero para aplicaciones empresariales complejas, con muchas dependencias, los especialistas de DevOps son esenciales para mantener correctamente en ejecución su app de producción.

Las funcionalidades de desarrollador se incorporan en {{site.data.keyword.cloud_notm}} para alinear estos conjuntos de conocimientos y permitir que su equipo utilice una plataforma para producir, entregar, ejecutar y gestionar su app. Por ejemplo, un desarrollador digital que cree una app para móviles puede utilizar el {{site.data.keyword.cloud_notm}} [portal del desarrollador móvil](https://{DomainName}/developer/mobile/dashboard){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo"). Un creador de apps cognitivas puede utilizar el [portal del desarrollador de Watson](https://{DomainName}/developer/watson/dashboard){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo") junto con [Watson Studio](https://{DomainName}/catalog/services/watson-studio){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo"). Un desarrollador de streams puede utilizar [IBM Real-Time Analytics](/docs/services/StreamingAnalytics/index.html). El [servicio {{site.data.keyword.cloud_notm}} Continuous Delivery](/docs/services/ContinuousDelivery?topic=ContinuousDelivery-cd_getting_started) simplifica el trabajo de un especialista en DevOps.

[¿Listo para empezar a crear apps de alta calidad y listas para producción?](/docs/apps/tutorials?topic=creating-apps-tutorial-getting-started#tutorial-getting-started)

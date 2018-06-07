---

copyright:
  years: 2016, 2017, 2018
lastupdated: "2018-05-02"

---
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}
{:tip: .tip}

# Conozca los distintos caminos de desarrollo en {{site.data.keyword.cloud_notm}}
{: #dev-journey}

Desde el punto de vista de los desarrolladores, {{site.data.keyword.cloud}} tiene un conjunto de funcionalidades que permiten crear apps en minutos. Con los paneles de control de desarrollador podrán:

* Seleccionar kits de iniciación que específicos de casos de uso y crear apps como punto de partida listas para producción en distintos lenguajes de programación y patrones arquitectónicos.
* Consulte y gestione los recursos que se han suministrado automáticamente desde el kit de iniciación o los que ha añadido manualmente a su app
* Obtener un código de app portátil que le permita desplegar varios entornos de nube
* Crear una [cadena de herramientas de DevOps](../services/ContinuousDelivery/index.html#cd_getting_started) en pocos clics.
* Utilizar una [interfaz de línea de mandatos](/docs/cli/idt/index.html) para el desarrollo local

Para comprender cómo la experiencia del desarrollador de {{site.data.keyword.cloud_notm}} puede ayudarle a crear rápidamente apps de alta calidad listas para un entorno de producción, consulte estos elementos en más detalle.

## Paneles de control de desarrollador
{: #dev-dashboards}

{{site.data.keyword.cloud_notm}} tiene paneles de control en distintas áreas de interés (por ejemplo, Watson, Seguridad o Finanzas) o para un canal digital (como por ejemplo, apps móviles o web). Puede acceder a estos paneles de control desde el **icono Menú**  ![Icono Menú](../icons/icon_hamburger.svg).

Cada panel de control de desarrollador proporciona kits de iniciación relevantes para el área de interés y ofrece un flujo de trabajo coherente e intuitivo que permite crear en minutos una app lista para el entorno de producción.

## Apps
{: #app-projects}

Una app consta de código, datos, servicios y cadenas de herramientas. Por ejemplo, la app móvil de {{site.data.keyword.cloud_notm}} contiene código de fondo junto con lógica de fondo, almacenamiento de datos, analíticas y servicios de seguridad y, además, está configurado para una entrega continua.

![Reutilizar](images/garage_reuse2.png "Developer Experience permite la reutilización y evita la reinvención")

Puede crear y gestionar una app utilizando cualquier panel de control de desarrollador de {{site.data.keyword.cloud_notm}} o {{site.data.keyword.dev_cli_notm}}.

## Kits de iniciación
{: #starter-kits}

Con los kits de iniciación, {{site.data.keyword.cloud_notm}} ensambla una app de producción de esqueleto, en el lenguaje de su elección, listo para el despliegue en la nube. Cada kit de iniciación incluye un lenguaje, una infraestructura, un patrón para un caso de uso específico y permite reutilizar código.

### ¿En qué se diferencian los kits de iniciación de los ejemplos?
Los kits de iniciación están listos para ser utilizados en producción y se centran en demostrar una implementación de un patrón clave utilizando un tiempo de ejecución (por ejemplo Node.js y Express). En algunos casos, los kits de iniciación ofrecen una experiencia de usuario simple para resaltar la integración del servicio. En otros casos los kits de iniciación representan una implementación personalizable de un caso de uso sofisticado.

* Un **fragmento** son unas pocas líneas de código que a menudo se presentan en un IDE. Los fragmentos ayudan a un desarrollador a integrar con una sintaxis de lenguaje de programación o dar soporte a la integración con una API definida.
* Una **demo** normalmente ofrece una alta calidad y fidelidad y utiliza distintos servicios y puntos de integración. A menudo precisa de tiempo para configurarla y se utiliza para probar un problema empresarial o para demostrar una característica de una plataforma. Se utiliza para evaluar las etapas de una adopción en la nube. A veces su código incluye código de producción.
* Un **ejemplo** es un pequeño ejemplo de una característica, función, servicio o recorrido de usuario específicos. Es posible reutilizar o incluir los ejemplos en una aplicación de producción. Se suele utilizar para mostrar las posibilidades técnicas y un posible enfoque para resolver un problema técnico.
* Un **kit de iniciación** es un patrón listo para el entorno de producción que se puede integrar con un conjunto de servicios para generar un activo listo para producción y que se puede desplegar directamente en un conducto de DevOps y en un clúster de Kubernetes. Un kit de iniciación contiene metadatos descriptivos que proporcionan al usuario suficiente información para saber qué es y que hace el kit. También contiene instrucciones que indican a {{site.data.keyword.cloud_notm}} lo que debe producir. La salida está lista para producción desde un principio. Luego, de forma iterativa, puede añadir más mejoras con base a las prácticas recomendadas de IBM. El contenido del kit de iniciación no es tan complejo como una demostración ni tan trivial como un ejemplo o fragmento de código. Los kits de iniciación son creados dinámicamente en función de las necesidades del desarrollador.

## Recursos de suministro automático
{: #auto-provision}

Si un kit de iniciación especifica recursos que son necesarios, {{site.data.keyword.cloud_notm}} crea automáticamente las instancias de estos recursos al crear la app. Tenga en cuenta que también puede suministrar recursos o seleccionar las instancias de recursos existentes de forma manual para añadirlos a su app después de haberlo creado. Puede ver una lista de instancias de servicio asociadas a su app en la vista Detalles de la app junto con credenciales en caso de que las necesite.

## Código portátil
{: #portable-code}

Cuando se crea una app a partir de kit de iniciación automáticamente se crea un código con un formato coherente. Su tiempo de ejecución es independientemente del entorno. Puede desplegarlo en el entorno que desee, por ejemplo, Kubernetes o Cloud Foundry, sin realizar cambios.

### ¿Qué código se crea?
El código creado a partir de un kit de iniciación de {{site.data.keyword.cloud_notm}} tiene cuatro componentes fundamentales: lógica del caso de uso, los componentes del lenguaje, la habilitación de servicio y la habilitación en la nube. La generación de estos componentes ahorra un tiempo valioso y asegura la utilización de la mejor arquitectura.

* La **lógica de los casos de uso** proporciona funciones para la función principal de un caso de uso concreto. Por ejemplo, el código para un chat bot de Watson Conversation o el código para una app móvil de reconocimiento visual.
* Los **componentes de lenguaje** son componentes de código y archivos específicos del lenguaje de programación que selecciona para el kit de iniciación. Por ejemplo, los programadores de node.js necesitarán un archivo package.json para la gestión de dependencias. Este archivo se crea en nombre del usuario de forma automática.
* **Habilitación del servicio** es el código que permite que su app se conecte y utilice los servicios que añade. La gestión de credenciales, el código de inicialización y SDK específicos de servicio son ejemplos de elementos de habilitación del servicio.
* La **habilitación en la nube** se corresponde con el código que permite ejecutar la app en {{site.data.keyword.cloud_notm}}. Por ejemplo, diagramas de Helm que permiten la ejecución de una app en un clúster Kubernetes de {{site.data.keyword.cloud_notm}}.

Cuando se crea una app a partir de un kit de iniciación de {{site.data.keyword.cloud_notm}}, la app se inicia con la arquitectura probada que también refleja las mejores prácticas para el idioma seleccionado.

Cada app incluye un archivo readme que contiene detalles técnicos de la app y explica lo que se necesita para ejecutar la app si no se ejecuta desde un principio.
{: tip}

## Cadena de herramientas de DevOps
{: #devops}

DevOps consta de procedimientos y herramientas para acceder, desarrollar, desplegar y operar con su app. Una cadena de herramientas de DevOps es un conjunto de servicios relacionados que automatizan las tareas de DevOps. Es posible realizar manualmente las tareas de DevOps con apps muy sencillas, sin embargo, la necesidad de automatización para apps aumenta rápidamente cuando lo hace su complejidad. La automatización de una cadena de herramientas es un componente necesario para la entrega continua.

El componente principal de una cadena de herramientas de DevOps es un repositorio de control de versiones de código como GitHub. Otras herramientas adicionales corresponden al rastreo de procesos realizados, a los conductos de entrega, al IDE y a los servicios de supervisión como, por ejemplo, [{{site.data.keyword.cloud_notm}}DevOps Insights](../services/DevOpsInsights/index.html#gettingstarted).

Si ha creado una app mediante un kit de iniciación, puede crear una nueva cadena de herramientas y desplegar su app simplemente pulsando **Desplegar en la nube** en la vista Detalles de la app. Se crea una cadena de herramientas con un repositorio de código, problemas de repositorio, conducto de entrega e IDE de web.

A continuación puede desarrollar en esta cadena de herramientas para acomodarla a varios equipos y desplegar en entornos distintos para desarrollo, pruebas y producción y establecer un modelo de entrega continuo colaborativo de nivel empresarial para su app.  

![Entrega continua](images/garage_continuous_delivery2.png "La experiencia del desarrollador establece una entrega continua en su rama de desarrollo")

También puede obtener una visión rápida al código de su app pulsando el botón **Descargar** en la página de visión general de la app del panel de control del desarrollador. El código se descarga como un archivo `.zip` con toda la estructura del código de la app. Puede extraer fácilmente el archivo y ejecutar el código localmente utilizando {{site.data.keyword.dev_cli_notm}}, o añadirlo su repositorio de gestión de código.

## Interfaz de línea de mandatos
{{site.data.keyword.dev_cli_notm}} le permite codificar, compilar y ejecutar su app de forma local.  Un patrón habitual es crear su app mediante un panel de control de desarrollador, utilizar {{site.data.keyword.dev_cli_notm}} para desarrollar localmente, y luego enviar por push las actualizaciones a su repositorio para fusionarlas para empezar su cadena de herramientas de despliegue.

## Desarrollo del Garage Method
{: #developer_concepts}

Consulte el [Garage Method](https://www.ibm.com/cloud/garage/) para obtener más información sobre cómo IBM puede ayudarle a desarrollar apps en su organización.  

![Visión general de fases del
Garage Method](images/garage_phases_overview2.png "Visión general de fases delGarage Method")*Visión general de fases del

Garage Method*

{{site.data.keyword.cloud_notm}} sirve para crear apps de producción de nivel empresarial de forma satisfactoria utilizando el Garage Method o cualquier otro método que prefiera. Para comprender mejor lo que {{site.data.keyword.cloud_notm}} tiene que ofrecer a los desarrolladores, vamos a repasar brevemente los conocimientos necesarios para crear una app moderna.

## Conocimientos técnicos de los desarrolladores
{: #skills}

Hoy más que nunca los usuarios esperan lo máximo de sus aplicaciones. Desean apps que entreguen conocimiento profundo de los datos almacenados y los recopilados en tiempo real, que estén siempre disponibles y que se ajusten lo mejor posible a sus necesidades individuales. Para satisfacer estas expectativas, los creadores de apps necesitan reunir muchos tipos de conocimientos. Por ejemplo, una aplicación cognitiva sofisticada podría precisar de las contribuciones de los desarrolladores digitales, desarrolladores nativos en la nube, desarrolladores de corrientes de datos, científicos de datos y especialistas de DevOps.

 ![Tipos de desarrollador](images/developer_skills.png "Relaciones de desabolladores")

* **Desarrolladores digitales**: crean para un canal digital concreto como, por ejemplo, chat, voz o web móvil. Los desarrolladores digitales normalmente se centran en casos de uso y satisfacer directamente las necesidades de los usuarios como una experiencia global.
* **Desarrolladores nativos en la nube**: se especializan en la construcción e interconexión de componentes en la nube. Los creadores de microservicios y sistemas frontales/de fondo se incluyen en esta categoría.
* **Desarrolladores de corrientes**: se centran en el proceso y la obtención de conocimientos a partir de corrientes de datos. Por ejemplo, un desarrollador de corrientes podría analizar y tomar acciones con base a corrientes entrantes de vídeo, habla o texto.
* **Científicos de datos**: utilizan analíticas y aprendizaje máquina para crear modelos predictivos. Estos modelos se utilizan en las métricas empresariales y proporcionar conocimientos profundos a los usuarios de las aplicaciones.
* **Especialistas de DevOps**: expertos en resolver los problemas de despliegue y cadenas de herramientas. Para apps simples, habitualmente no son necesarios especialistas dedicados puesto que los miembros del equipo de desarrollo gestionan las operaciones de DevOps conjuntamente. Pero para aplicaciones empresariales complejas, con muchas dependencias, los especialistas de DevOps son esenciales para mantener correctamente en ejecución su app de producción.

Las funcionalidades de desarrollador se incorporan en {{site.data.keyword.cloud_notm}} para alinear estos conjuntos de conocimientos y permitir que su equipo utilice una plataforma para producir, entregar, ejecutar y gestionar su app. Por ejemplo, un desarrollador digital creando una app móvil utilizaría el [panel de control de desarrollador móvil](https://console.bluemix.net/developer/mobile/dashboard) de {{site.data.keyword.cloud_notm}}, un creador de apps cognitivas podría utilizar el [panel de control de Watson](https://console.bluemix.net/developer/watson/dashboard) junto con [Watson Studio](https://console.bluemix.net/catalog/services/watson-studio), un desarrollador de corrientes podría utilizar [IBM Real-Time Analytics](../services/StreamingAnalytics/index.html#gettingstarted) y el [{{site.data.keyword.cloud_notm}}servicio de Continuous Delivery](../services/ContinuousDelivery/index.html#cd_getting_started) simplificaría el trabajo de un especialista de DevOps.

¿Listo para empezar? [Pulse aquí](../apps/index.html) para crear ahora una app en {{site.data.keyword.cloud_notm}}.

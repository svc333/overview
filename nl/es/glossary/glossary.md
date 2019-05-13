---


copyright:
  years: 2016, 2019
lastupdated: "2019-05-06"

keywords: glossary, IBM Cloud glossary

subcollection: overview


---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# Términos del glosario de {{site.data.keyword.cloud_notm}}
{: #glossary}

Este glosario contiene términos y definiciones correspondientes a {{site.data.keyword.cloud_notm}}.
{:shortdesc}

En este glosario se utilizan las siguientes referencias cruzadas:

- *Véase* le remite desde un término no preferido al
término preferido o desde una abreviatura a la forma completa.
- *Véase también* le remite a un término relacionado u opuesto.

## A
{: #glossa}

### lista de control de accesos
{: #x2012793}

Una lista que gestiona tráfico de entrada y salida sin información de estado para una subred mediante el uso de reglas. Una lista de control de accesos ayuda a proporcionar seguridad en el nivel de subred.

### señal de acceso
{: #x2113001}

Valor que utiliza el cliente para obtener acceso a los recursos
protegidos en nombre del usuario, en lugar de utilizar las credenciales del
proveedor de servicio del usuario.

### acción
{: #x2012974}

Un fragmento de código que se puede invocar explícitamente o ejecutarse como respuesta a un suceso. Véase también [canal de información](#x3129185), [invocar](#x2057232).

### afinidad
{: #x2149238}

Dos o más instancias de grupo de contenedores que se ejecutan en el mismo nodo de red. Véase también [antiafinidad](#x8888040).

### antiafinidad
{: #x8888040}

Dos o más instancias de grupo de contenedores que se ejecutan en distintos nodos de red para garantizar una disponibilidad más alta para una app. Véase también [afinidad](#x2149238).

### API
{: #x2008805}

Véase [interfaz de programación de aplicaciones](#x2000186).

### app
{: #x4281528}

Aplicación de dispositivo móvil o web. Véase también [aplicación móvil](#x4258535), [aplicación web](#x2116500).

### interfaz de programación de aplicaciones (API)
{: #x2000186}

Interfaz que permite que un programa de aplicación que está escrito en un lenguaje de alto nivel utilizar datos o funciones específicos del sistema operativo o de otro programa.

### artefacto
{: #x2262995}

Entidad utilizada o producida por un proceso de desarrollo de software o sistemas. Diseños, requisitos, archivos de origen, planes, scripts, simulaciones, modelos, planes de prueba y archivos ejecutables binarios son algunos ejemplos de artefactos. En un contexto HTTP, los artefactos tienen un URI y se denominan recursos llamados.

### autenticación (AuthN)
{: #x2014567}

Proceso de validación de la identidad de un usuario o servidor.

### AuthN
{: #x7470446}

Véase [autenticación](#x2014567).

### autorización (AuthZ)
{: #x2014653}

En seguridad de sistemas, derecho otorgado a un usuario para comunicarse con un sistema informático o hacer uso del mismo.

### AuthZ
{: #x7470448}

Véase [autorización](#x2014653).

### zona de disponibilidad
{: #x7018171}

Ubicación dentro de una región en la que se ejecuta IBM Containers.


## B
{: #glossb}

### imagen base
{: #x5366487}

Una imagen que no tiene una imagen padre. Véase también [imagen](#x2024928), [imagen padre](#x8439210).

### servicio beta
{: #x7470455}

Servicio que no está listo para producción que está en una etapa de prueba de desarrollo. Véase también [servicio experimental](#x7470450).

### enlazar
{: #x2000361}

Establecer una conexión entre componentes de software de una red utilizando
un protocolo pactado. En servicios web, la operación de enlace se produce cuando el solicitante del
servicio invoca o inicia una interacción con el servicio en tiempo de ejecución utilizando los
detalles de enlace de la descripción de servicio para localizar, establecer contacto e invocar el servicio.

### BLU Acceleration
{: #x7470463}

Colección de tecnologías de IBM Db2 diseñadas para trabajar principalmente con proceso de consultas de inteligencia empresarial mayoritariamente de lectura. BLU Acceleration consta de cuatro principales avances en diseño de base de datos: proceso dinámico de columnas en memoria, compresión que se puede accionar, proceso de vectores paralelos y omisión de datos.

### despliegue azul-verde
{: #x7807335}

Técnica de despliegue que habilita la entrega continua y minimiza el tiempo de inactividad mediante la ejecución de dos entornos de producción prácticamente idénticos llamados Azul y Verde. Mientras uno de los entornos (por ejemplo, Azul) es el entorno de producción, el otro (por ejemplo, Verde) podrá usarse para las pruebas finales y el despliegue. Una vez la aplicación se haya desplegado en Verde, éste se convertirá en el entorno de producción y Azul se quedará desocupado. Véase también [despliegue rojo-negro](#x8439181).

### contenedor modelo
{: #x7233930}

Plantilla que incluye una aplicación y su entorno de tiempo de ejecución y servicios predefinidos asociados para un determinado dominio.

### sin borde
{: #x8439189}

Relativo a una plataforma de desarrollo de no propiedad abierta que incluye modelos de desarrollo de nube pública, nube dedicada y nube local. Véase también [nube dedicada](#x8439199), [nube local](#x8439194), [nube pública](#x4585370).

### paquete de compilación
{: #x7233925}

Colección de scripts que preparan el código para que se ejecute en IBM Cloud. Los paquetes de compilación examinan las aplicaciones desplegadas y descargan y configuran las aplicaciones dependientes.


## C
{: #glossc}

### CA
{: #x2015942}

Véase [entidad emisora de certificados](#x2016383).

### entidad emisora de certificados (CA)
{: #x2016383}

Organización o empresa de terceros de confianza que emite los certificados digitales. La entidad emisora de certificados normalmente verifica la identidad de las personas a las que se otorga el certificado exclusivo. Véase también [certificado intermedio](#x3753781), [capa de sockets seguros](#x2038004), [raíz de confianza](#x2042234).

### solicitud de firma de certificado (CSR)
{: #x3530521}

Un mensaje electrónico que envía una organización a una entidad emisora de certificados (CA) para obtener un certificado. La solicitud incluye una clave pública y se firma con una clave privada; la CA devuelve el certificado después de firmarlo con su propia clave privada.

### CLI
{: #x2008863}

Véase [interfaz de línea de mandatos](#x2051424).

### cliente
{: #x2000644}

Programa de software o sistema que solicita servicios a un servidor. Véase también [host](#x2002243).

### computación en la nube
{: #x3877850}

Plataforma informática en la que los usuarios pueden acceder a las aplicaciones o recursos informáticos, como servicios, desde cualquier lugar a
través de sus dispositivos conectados. Una interfaz de usuario simplificada o una interfaz de programación de aplicaciones (API) hacen que la
infraestructura que da soporte a tales servicios sea transparente para los usuarios.

### portabilidad en la nube
{: #x4585297}

La capacidad para mover aplicaciones y servicios entre entornos de computación en la nube públicos o privados, o desde distintos proveedores de nube.

### interfaz de línea de mandatos (CLI)
{: #x2051424}

Interfaz de sistema en la que la entrada y la salida están basadas en texto.

### componente
{: #x2017871}

En la gestión de control de origen, agrupación de artefactos relacionados de una corriente o un espacio de
trabajo de repositorio. Un componente puede contener tantas carpetas o archivos como desee.

### compute
{: #x3723424}

Infraestructura de recursos que se va a utilizar como base para crear apps en la nube.

### contenedor
{: #x2010901}

Una construcción de sistemas que permite a los usuarios ejecutar simultáneamente instancias distintas del sistema operativo lógico. Los contenedores utilizan capas de los sistemas de archivos para minimizar los tamaños de imágenes y promover la reutilización. Véase también [imagen](#x2024928), [capa](#x2028320), [registro](#x2064940).

### credencial
{: #x2018813}

Información adquirida durante la autenticación que describe un usuario, asociaciones de grupo
u otros atributos de identidad relacionados con la seguridad y que se utiliza para realizar servicios
tales como autorización, auditoría o delegación. Por ejemplo, un ID de usuario y una contraseña son credenciales que permiten el acceso a la red y a los recursos del sistema.

### CSR
{: #x2140147}

Véase [solicitud de firma de certificado](#x3530521).

### dominio personalizado
{: #x5728384}

Parte personalizada de un URL seleccionado por el usuario para que dirija solicitudes a la aplicación. Un dominio personalizado forma parte de una ruta. Un dominio personalizado puede ser un dominio compartido, un subdominio compartido o un dominio compartido y un host. Véase también [dominio](#x2021210), [host](#x2002243), [ruta](#x2037338), [subdominio](#x2040080), [Localizador uniforme de recursos](#x2042491).


## D
{: #glossd}

### daemon
{: #x2019215}

Un programa que se ejecuta de forma desatendida para efectuar funciones continuas o periódicas, como el control de red.

### panel de control
{: #x2363941}

Componente de interfaz de usuario que proporciona al usuario un resumen coherente de la información pertinente que proceden de diversas fuentes.

### Centro de datos (DC)
{: #x2439906}

La ubicación física de los servidores que proporcionan servicios de cloud.

### almacén de datos
{: #x2052849}

Lugar, como el sistema de base de datos, archivo o directorio en el que se almacenan datos.

### DEA
{: #x2019805}

Véase [Droplet Execution Agent](#x7470348).

### nube dedicada
{: #x8439199}

Un entorno de computación de nube privada que proporciona infraestructura con un hardware de un único arrendatario. Véase también [sin borde](#x8439189).

### despliegue
{: #x2104544}

Proceso que recupera el resultado de una creación, empaqueta el resultado con propiedades de configuración e instala el paquete en una ubicación predefinida para que se pueda probar o ejecutar. Véase también [etapa](#x2067189).

### DevOps
{: #x5784896}

Metodología de software que integra el desarrollo de aplicaciones y operaciones de TI para que los equipos entreguen el código a la producción más rápido e iteren de forma continua en función de los comentarios del mercado.

### dominio
{: #x2021210}

Parte de una jerarquía de denominación que especifica la ruta. Por ejemplo, example.com. En IBM Cloud, los dominios están asociados a organizaciones. Los objetos de dominio no están enlazados directamente a apps. Véase también [dominio personalizado](#x5728384), [host](#x2002243), [organización](#x2032585), [ruta](#x2037338), [subdominio](#x2040080), [Localizador uniforme de recursos](#x2042491).

### droplet
{: #x7470343}

Un archivo de Cloud Foundry que contiene una aplicación y sus dependencias de infraestructura y tiempo de ejecución, ante del despliegue en la nube.

### Droplet Execution Agent (DEA)
{: #x7470348}

Componente de Cloud Foundry responsable de desplegar aplicaciones.


## E
{: #glosse}

### punto final
{: #x2026820}

Dirección de una API o servicio en un entorno. Una API expone un punto final
y al mismo tiempo invoca los puntos finales de otros servicios. Véase también [ruta](#x2037338).

### servicio experimental
{: #x7470450}

Servicio que no está preparado para la producción y se puede eliminar de producción en cualquier momento. Véase también
[servicio beta](#x7470455).


## F
{: #glossf}

### federar
{: #x2763229}

Fusionar dos o más entidades. Por ejemplo, el dominio registrado de una empresa se puede federar con un IBMid.

### canal de información
{: #x3129185}

Segmento de código que configura un origen de suceso externo
para activar sucesos desencadenantes. Véase también [acción](#x2012974).

### compartición de archivo
{: #x2022902}

En un entorno de IBM, un sistema de almacenamiento persistente donde los usuarios almacenan y comparten archivos. En IBM Containers, los usuarios pueden montar volúmenes de Docker en comparticiones de archivo.

### activar
{: #x2239904}

Activar un desencadenante.

### dirección IP flotante
{: #x6326428}

Una dirección IP pública y direccionable que hace uso de la conversión de direcciones de red (NAT) de 1 a 1 para que un servidor pueda comunicarse con la subred pública de Internet y privada dentro de un entorno de nube. Las direcciones IP flotantes están asociadas a una instancia, por ejemplo, una instancia de servidor virtual, un equilibrador de carga, o una pasarela VPN, mediante una tarjeta de interfaz de red virtual (vNIC).

### infraestructura
{: #x2023472}

Arquitectura para una aplicación que proporciona un estándar estructura para una aplicación y funciones generales y extensibles.  Una infraestructura habilita y simplifica una implementación coherente de tecnologías complejas para el desarrollo de aplicaciones.


## G
{: #glossg}

### GB por hora
{: #x7470477}

Cantidad acumulada de memoria (en gigabytes) que se está ejecutando para todas las instancias de una aplicación para un determinado paquete de compilación por hora.

### identificador exclusivo global (GUID)
{: #x2390455}

Número determinado mediante un algoritmo que identifica de forma única una entidad dentro de un sistema.

### GUID
{: #x2390457}

Véase [identificador exclusivo global](#x2390455).


## H
{: #glossh}

### modalidad de máquina virtual de hardware (HVM)
{: #x9736811}

Virtualización completa asistida por hardware. Una máquina virtual utiliza recursos del equipo host para funcionar como un entorno de hardware completo. El sistema operativo del host no conoce el cliente virtual.

### llamada de API pesada
{: #x7690468}

Una operación del cliente que escribe, suprime o inserta datos. Las llamadas de API pesadas consumen más recursos que las llamadas de API ligeras porque están afectando a los datos. Véase también
[llamada de API ligera](#x7690463).

### host
{: #x2002243}

Sistema que está conectado a una red y proporciona un punto de acceso a esa red. El host puede ser un cliente, un servidor, o ambos
simultáneamente. Véase también [cliente](#x2000644), [dominio personalizado](#x5728384), [dominio](#x2021210), [ruta](#x2037338), [subdominio](#x2040080), [Localizador uniforme de recursos](#x2042491).

### método HTTP
{: #x2024674}

Acción utilizada por el protocolo de transferencia de hipertexto. Los métodos HTTP
incluyen GET, POST y PUT.

### HTTPS
{: #x2193603}

Véase [Protocolo seguro de transferencia de hipertexto](#x2237225).

### nube híbrida
{: #x4585327}

Un entorno de computación en la nube que consiste en varios recursos privados y públicos.

### Protocolo seguro de transferencia de hipertexto (HTTPS)
{: #x2237225}

Protocolo de Internet que utilizan los servidores web y los navegadores web para transferir y visualizar documentos de hipermedia de forma segura a través de Internet.


## I
{: #glossi}

### IaaS
{: #x4585337}

Véase [infraestructura como servicio](#x4585332).

### IAM
{: #x2193801}

Consulte [gestión de identidad y acceso](#x7547040).

### IBM Cloud
{: #x7301758}

Plataforma de estándares abiertos basada en la nube para crear, gestionar y ejecutar apps de todo tipo, como web, móvil, Big Data y dispositivos inteligentes. Las funciones incluyen Java, desarrollo para dispositivos móviles y supervisión de aplicaciones, así como características de partners de ecosistema y código abierto&mdash;todo ello se proporciona como un servicio en la nube.

### gestión de identidad y acceso (IAM)
{: #x7547040}

El proceso de control de acceso de usuarios autorizados a datos y aplicaciones, a la vez que ayuda a las empresas a cumplir con varios requisitos regulatorios.

### imagen
{: #x2024928}

Un sistema de archivos y sus parámetros de ejecución que se utilizan dentro del tiempo de ejecución de un contenedor para crear un contenedor. El sistema de archivos consta de una serie de capas, combinadas en el tiempo de ejecución, que se crean a medida que se crea la imagen mediante actualizaciones sucesivas. La imagen no retiene el estado mientras se ejecuta el contenedor. Véase también [imagen base](#x5366487), [contenedor](#x2010901), [capa](#x2028320), [espacio de nombres](#x2031005), [imagen padre](#x8439210), [repositorio de imágenes privadas](#x8439215), [registro](#x2064940).

### infraestructura como servicio (IaaS)
{: #x4585332}

Distribución de una infraestructura de sistemas, que incluye funcionalidad de servidor, funcionalidad de red, funcionalidad de centro de datos y funcionalidad de almacenamiento como un servicio externalizado.

### instancia
{: #x2002531}

Entidad que consta de recursos que están reservados para una determinada aplicación o servicio.

### certificado intermedio
{: #x3753781}

Certificado subordinado emitido por la entidad emisora de certificados (CA) raíz de confianza específicamente para emitir certificados del servidor de la entidad final. El resultado es una cadena de certificados que empieza en la entidad emisora de certificados raíz de confianza, pasa por el certificado intermedio y termina con la emisión del certificado SSL a la organización. Véase también [entidad emisora de certificados](#x2016383), [raíz de confianza](#x2042234).

### Internet de las cosas (IoT)
{: #x6714341}

Red global de puntos finales que puede capturar o generar datos. Por ejemplo, un teléfono inteligente, un reloj inteligente y el servidor back-end pueden comunicarse y transferir datos entre ellos o incluso a otros dispositivos dentro de la red.

### invocar
{: #x2057232}

Para activar una acción. Véase también [acción](#x2012974).

### IoT
{: #x6714346}

Véase [Internet de las cosas](#x6714341).


## J
{: #glossj}

### archivo JAR
{: #x2406009}

Archivo de archivado Java.

### JavaScript Object Notation (JSON)
{: #x3292165}

Formato de intercambio de datos ligero que se basa en la notación literal de objetos
de JavaScript. JSON es independiente del lenguaje de programación, pero utiliza convenios de varios lenguajes.

### JSON
{: #x4267096}

Véase [JavaScript Object Notation](#x3292165).


## L
{: #glossl}

### capa
{: #x2028320}

Una versión modificada de una imagen padre. Las imágenes constan de capas, donde hay varios niveles de la versión modificada en la parte superior de la imagen padre para crear la nueva imagen. Véase también [contenedor](#x2010901) e [imagen](#x2024928).

### LDAP
{: #x2481619}

Véase [protocolo LDAP (Lightweight Directory Access Protocol)](#x2028538).

### llamada de API ligera
{: #x7690463}

Una operación del cliente que sólo lee datos. Las llamadas de API ligeras utilizan menos recursos que las llamadas de API pesadas porque están realizando una única función. Véase también [llamada de API pesada](#x7690468).

### Protocolo LDAP
{: #x2028538}

Un protocolo abierto que utiliza TCP/IP para proporcionar acceso a directorios que admiten un modelo X.500 y que no necesita los recursos del protocolo de acceso a directorios (DAP) X.500 más complejo. Por ejemplo,
LDAP se puede utilizar para localizar personas, organizaciones y otros recursos
en un directorio de Internet o intranet.

### nube local
{: #x8439194}

Un entorno de computación en la nube dentro del centro de datos del cliente. La nube local es local, lo que proporciona una mejor latencia y seguridad. Véase también [sin borde](#x8439189).


## M
{: #glossm}

### MBaaS
{: #x7044865}

Véase [programa de fondo móvil como servicio](#x7044858).

### app móvil
{: #x7636517}

Véase [aplicación móvil](#x4258535).

### aplicación móvil (app móvil)
{: #x4258535}

Aplicación que se ha diseñado para una plataforma móvil. Similares a las aplicaciones web, las apps móviles proporcionan más funciones que la visualización estática de información; por ejemplo, permiten al usuario filtrar noticias en tiempo real. Véase también [app](#x4281528).

### programa de fondo móvil como servicio (MBaaS)
{: #x7044858}

Modelo de cálculo que conecta aplicaciones móviles a servicios de computación en la nube y proporciona características como, por ejemplo, gestión de usuarios, envío de notificaciones e integración con redes sociales a través de una API y SDK unificados.

### nube móvil
{: #x4585344}

Infraestructura en la que el almacenamiento y el proceso de datos para las aplicaciones se descarga desde un dispositivo móvil en la nube. Con la computación en la nube móvil, las aplicaciones no están limitadas a un operador específico, sino que se accede a las mismas a través de la web.

### región multizona (MZR)
{: #x9766831}

Una región que consta de dos o más zonas, que son varios grupos de uno o más centros de datos lógicamente aislados con infraestructuras eléctricas, mecánicas y de red independientes.

### MZR
{: #x9766835}

Consulte [región multizona](#x9766831).


## N
{: #glossn}

### espacio de nombres
{: #x2031005}

Un nombre exclusivo que identifica el repositorio de imagen de la organización dentro del registro de IBM Cloud. Véase también [imagen](#x2024928), [repositorio de imagen privada](#x8439215).

### conversión de direcciones de red
{: #x2031199}

Método de direccionamiento que se utiliza para permitir que una dirección IP se comunique con otras direcciones IP, como las de una subred privada, mediante una tabla de búsqueda. La conversión de direcciones de red (NAT) tiene dos tipos principales: de 1 a 1 y de muchas a 1.


## O
{: #glosso}

### OAuth
{: #x6013335}

Protocolo de autorización basado en HTTP que proporciona a las aplicaciones acceso de ámbito a un recurso protegido en nombre del propietario del recurso,
creando una interacción de aprobación entre el propietario del recurso, el cliente
y el servidor de recursos.

### local
{: #x6969434}

Véase [local](#x4561212).

### local
{: #x4561212}

Relativo a software que está instalado y se ejecute en los sistemas locales de un usuario u organización.

### org
{: #x7470494}

Véase [organización](#x2032585).

### organización (org)
{: #x2032585}

Metodología de agrupación de usuarios de IBM Cloud. Las organizaciones se utilizan para gestionar cuotas. Los usuarios de una organización comparten memoria y cuotas de instancias de servicios. Véase también [dominio](#x2021210), [espacio](#x2039442).


## P
{: #glossp}

### PaaS
{: #x2029790}

Véase [plataforma como servicio](#x2029786).

### modalidad paravirtualizada
{: #x9736806}

Una técnica de virtualización ligera. En modalidad paravirtualizada, una máquina virtual no requiere extensiones de virtualización del equipo host, lo que permite la virtualización en sistemas de hardware que no admiten la virtualización asistida por hardware.

### imagen padre
{: #x8439210}

Una imagen que proporciona una base para otra imagen. Por ejemplo, Ubuntu Linux es la imagen padre de la imagen de IBM Liberty. Véase también [imagen base](#x5366487), [imagen](#x2024928).

### plataforma como servicio (PaaS)
{: #x2029786}

Distribución de una plataforma informática, que incluye aplicaciones, middleware optimizado, herramientas de desarrollo y los entornos de tiempo de ejecución Java y Web 2.0 en un entorno basado en la nube.

### nube privada
{: #x4585362}

Entorno de computación en la nube en el que el acceso está limitado a miembros de una empresa
y redes de asociados. Véase también [nube pública](#x4585370).

### repositorio de imagen privada
{: #x8439215}

La combinación de un registro de IBM Cloud de la organización y su espacio de nombres. El repositorio de imagen privada se utiliza cuando se hace referencia a una imagen en un mandato. Véase también [imagen](#x2024928), [espacio de nombres](#x2031005).

### clave privada
{: #x2034701}

Patrón algorítmico que se utiliza para cifrar mensajes que sólo la correspondiente clave pública puede descifrar. La clave privada también se utiliza para descifrar mensajes que se han cifrado mediante la clave pública correspondiente. La clave privada se guarda en el sistema del usuario y se
protege mediante una contraseña.

### recursos privados
{: #x9439035}

Entrada visible solo para los propietarios de cuenta y las cuentas que se incluyen. Los recursos que se crean son privados de forma predeterminada. Véase también [recurso público](#x9439040).

### servicio privado
{: #x7690456}

Servicio que solo está visible para los miembros de una organización de IBM Cloud especificada.

### nube pública
{: #x4585370}

Un entorno de computación en la nube en el que el acceso a los recursos estandarizados, como por ejemplo la infraestructura, el hardware de varios arrendatarios y los servicios, está disponible a los suscriptores en base a pago por uso. Véase también [sin borde](#x8439189), [nube privada](#x4585362).

### pasarela pública
{: #x9594389}

La conexión de una subred a Internet, con todas las instancias de servidor virtual conectadas. Una pasarela pública utiliza la conversión de direcciones de red (NAT) de muchas a 1, que significa que miles de instancias de servidor virtual con direcciones privadas pueden utilizar una dirección IP pública para comunicarse con la Internet pública.

### recurso público
{: #x9439040}

Entrada que está visible para todas las personas del catálogo de IBM Cloud. Cualquier proveedor puede crear recursos públicos (proveedores de IBM o de terceros). Véase también [recurso privado](#x9439035).

### enviar por push
{: #x2035465}

Enviar información desde un servidor a un cliente. Cuando un usuario envía contenido, es el servidor el que inicia la transacción, no una solicitud del cliente.

### notificación push
{: #x5599582}

Alerta que indica un cambio o actualización de un icono de app móvil.


## R
{: #glossr}

### mayoritariamente de lectura
{: #x7470468}

Relativo a los datos que cambian dinámicamente.

### despliegue rojo-negro
{: #x8439181}

Una técnica de despliegue que hace entrega continua por medio de la habilitación de prueba sincronizada, el desarrollo y el despliegue. Inicialmente, el desarrollo se realiza en un entorno inactivo (negro), mientras que el entorno activo continúa tomando tráfico (rojo). Una vez que se inicie el despliegue, ambos entornos se volverán activos (rojo-rojo) hasta que se inhabilite el direccionamiento en el entorno de versión anterior y activo anteriormente, y, a continuación, se eliminará en consecuencia (negro) mientras que el nuevo entorno sirve como el único entorno activo. Véase también [despliegue azul-verde](#x7807335).

### región
{: #x2091391}

Territorio geográfico definido. Una región puede ser un área de código
postal específica, un pueblo, una ciudad, un estado o grupo de estados o
incluso un grupo de países. Cada región puede ser un conjunto de otras regiones
o un conjunto de códigos postales de la región.

### registro
{: #x2064940}

Servicio de almacenamiento y distribución de imágenes de un contenedor público o privado. Véase también [contenedor](#x2010901) e [imagen](#x2024928).

### Representational State Transfer (REST)
{: #x3220976}

Estilo de arquitectura de software para sistemas hipermedia distribuidos, como la World Wide Web. El término también suele utilizarse para describir cualquier interfaz simple que utilice XML (o YAML, JSON, texto sin formato) sobre HTTP sin una capa de mensajes adicional como SOAP.

### recurso
{: #x2004267}

Componente físico o lógico que se pueden suministrar o reservar para una aplicación o instancia de servicio.  Los ejemplos de recursos incluyen base de datos, cuentas y límites de procesador, memoria, y almacenamiento.

### grupo de recursos
{: #x2161955}

Entorno y restricciones a los que se ajustan las instancias de recursos contenidas. Se puede asociar un usuario con un grupo de recursos para permitir la colaboración.

### REST
{: #x3220987}

Véase [Representational State Transfer](#x3220976).

### ruta
{: #x2037338}

URL utilizada para dirigir solicitudes a una aplicación. Una ruta está formada por un host (o subdominio) opcional y un dominio que se especifican cuando se envía una aplicación mediante push. Por ejemplo, en la ruta myapp.example.com, myapp es el host y example.com es el dominio. Una ruta puede estar asociada a una o varias aplicaciones. A menos que se especifique un dominio personalizado, IBM Cloud utiliza un dominio compartido por defecto en la ruta de la aplicación. Véase también [dominio personalizado](#x5728384), [dominio](#x2021210), [punto final](#x2026820), [host](#x2002243), [subdominio](#x2040080), [Localizador uniforme de recursos](#x2042491).

### regla
{: #x2037526}

- Un criterio asocia un desencadenante a una acción, con cada activación del desencadenante que hace que se invoque la acción
correspondiente con un suceso de desencadenante como entrada.
- Conjunto de sentencias condicionales que permiten a los sistemas de cálculo identificar relaciones y ejecutar respuestas automáticas en función de las mismas.

### tiempo de ejecución
{: #x2391929}

Conjunto de recursos utilizados para ejecutar la aplicación. Véase también [iniciador](#x7470511).


## S
{: #glosss}

### SaaS
{: #x4585391}

Véase [software como servicio](#x4585386).

### escalar
{: #x2004442}

Aumentar la capacidad de la plataforma (o sistema) añadiendo más aplicaciones o instancias de servicio.

### ámbito
{: #x2037763}

En gestión de identidades, conjunto de entidades a las que puede afectar una política o un elemento de control de accesos
(ACI).

### capa de sockets seguros (SSL)
{: #x2038004}

Protocolo de seguridad que proporciona
privacidad en las comunicaciones. Con SSL,
las aplicaciones cliente/servidor pueden comunicarse de una forma diseñada
para impedir las escuchas no deseadas, la manipulación indebida y la
falsificación. Véase también [entidad emisora de certificados](#x2016383).

### servicio
{: #x2038343}

Extensión en la nube que ofrece funcionalidad lista para utilizarse, como base de datos, mensajería, software de web para ejecutar código, o gestión de aplicaciones o capacidades de supervisión. Los servicios no suelen requerir instalación ni mantenimiento y se pueden combinar para crear aplicaciones.

### sesión
{: #x2004539}

Periodo de tiempo que transcurre entre que se inicia una app en un dispositivo móvil y se indica al producto de control de calidad que empiece a recopilar datos sobre el comportamiento y problemas de la app.

### inicio de sesión único (SSO)
{: #x2213318}

Proceso de autenticación por el cual un usuario puede acceder a más de un sistema o aplicación entrando un único ID de usuario y contraseña.

### software como servicio (SaaS)
{: #x4585386}

Modelo de despliegue de software mediante el cual el software, incluidos los procesos empresariales, las aplicaciones de empresa y las herramientas de colaboración, se proporcionan como un servicio a los clientes a través de la nube.

### SOR
{: #x2214822}

Véase [sistema de registros](#x6735061).

### espacio
{: #x2039442}

Subgrupo dentro de una organización de IBM Cloud. A los usuarios que son miembros de una organización se les da acceso a uno o varios de sus espacios, con permisos asociados con un rol determinado (por ejemplo, desarrollador, gestor o auditor). Cualquier miembro del espacio puede las apps, pero sólo los miembros con el rol de desarrollador pueden crear apps y añadir instancias de servicio al espacio. Las apps y las instancias de servicio están asociadas con los espacios. Véase también
[organización](#x2032585).

### SSL
{: #x2483907}

Véase [capa de sockets seguros](#x2038004).

### SSO
{: #x3456450}

Véase [inicio de sesión
único](#x2213318).

### organizar
{: #x2067189}

Desplegar una aplicación, servicio o instancia en una ubicación predefinida para ejecutarlo o probarlo antes de desplegarlo en un entorno de producción. Véase también [despliegue](#x2104544).

### stanza
{: #x2094743}

Sección de un paquete de software que define una acción específica que se debe realizar en ese paquete de software o un conjunto de condiciones bajo las que se deben realizar acciones en el paquete de software. El paquete de software completo es una stanza que contiene una jerarquía de distintas stanzas.

### iniciador
{: #x7470511}

Plantilla que incluye servicios predefinidos y código de aplicación configurado con un determinado paquete de compilación. Un iniciador puede ser código de aplicación que se escribe en un lenguaje de programación específico, o una combinación de código de aplicación y conjunto de servicios. Véase también [tiempo de ejecución](#x2391929).

### subdominio
{: #x2040080}

Un dominio que forma parte de un dominio mayor. Véase también [dominio personalizado](#x5728384), [dominio](#x2021210), [host](#x2002243), [ruta](#x2037338), [Localizador uniforme de recursos](#x2042491).

### subred
{: #x4282974}

Consulte [subred](#x2040149).

### subred (subred)
{: #x2040149}

Red que está dividida en subgrupos más pequeños independientes, que siguen interconectados.

### sistema colaborativo
{: #x6528306}

En tecnología de la información (TI), sistema que incorpora tecnologías que animan al usuario a interactuar mediante correo electrónico, sistemas de colaboración y red.  Un sistema colaborativo suele utilizar tecnologías de nube para ampliar la utilidad de los sistemas de registro. Véase también [sistema de registros](#x6735061).

### sistema de registros (SOR)
{: #x6735061}

Sistema de almacenamiento de información (como, por ejemplo, una base de datos o una aplicación) que almacena registros empresariales y automatiza los procesos estándares. Véase también [sistema colaborativo](#x6528306).


## T
{: #glosst}

### plantilla
{: #x2041200}

Estructura predefinida para un artefacto.

### terceros, de
{: #x2877945}

Perteneciente a un producto o servicio que está proporcionado por una empresa que no es IBM.

### mosaico
{: #x2092493}

Representación visual de una aplicación en ejecución que proporciona el estado en un panel de control.

### desencadenante
{: #x2005384}

Un mecanismo que inicia acciones. Los desencadenantes se pueden activar de forma explícita mediante un usuario o de parte de un usuario por parte de un origen de suceso externo.

### raíz de confianza
{: #x2042234}

Certificado firmado por una entidad emisora de certificados (CA). Véase también [entidad emisora de certificados](#x2016383), [certificado intermedio](#x3753781).


## U
{: #glossu}

### identificador uniforme de recursos (URI)
{: #x2116436}

Dirección exclusiva que se utiliza para identificar contenido en la web. El formato más común de URI es la dirección de página web, que es un formato particular o subconjunto de URI denominado
localizador uniforme de recursos (URL). Normalmente, un URI describe cómo acceder al recurso, el sistema que contiene el
recurso y la ubicación del recurso en ese sistema.

### Localizador uniforme de recursos (URL)
{: #x2042491}

Dirección exclusiva de un recurso de información al que se puede acceder en
una red como Internet. El URL incluye el nombre abreviado del protocolo utilizado para acceder
al recurso de información y la información utilizada por el protocolo para localizar el recurso
de información. Véase también [dominio personalizado](#x5728384), [dominio](#x2021210), [host](#x2002243), [ruta](#x2037338), [subdominio](#x2040080).

### URI
{: #x2116461}

Véase [identificador uniforme de recursos](#x2116436).

### URL
{: #x2042718}

Véase [localizador uniforme de recursos](#x2042491).

### jerarquía de usuario
{: #userhierarchy}

Una relación de gestión para usuarios de infraestructura clásicos que invitan a otros usuarios a una cuenta. Después estos usuarios invitan a otros usuarios a la cuenta, etc. Cuando un usuario de infraestructura clásico invita a otro usuario a la cuenta, el usuario de infraestructura clásico se convierte en el usuario padre. Cuando un usuario hijo de un usuario padre invita a otros usuarios a la cuenta, dichos usuarios pasan a ser descendientes del padre original, que ahora se considerará su ancestro.


## V
{: #glossv}

### virtual
{: #x2043123}

Relativo a lo que no existe físicamente como tal pero que el software hace que lo parezca.

### máquina virtual (VM)
{: #x2043165}

Una implementación de software de una máquina que ejecuta programas como
una máquina real. Véase también [servidor virtual](#x2455638).

### red privada virtual (VPN)
{: #x2043188}

Una ampliación de la intranet de una empresa a través de la infraestructura existente de
una red pública o privada. Una VPN garantiza que los datos enviados entre dos puntos finales de su conexión continúen siendo seguros.

### servidor virtual
{: #x2455638}

Servidor que comparte sus recursos con otros servidores para dar soporte a las aplicaciones. Véase también [máquina virtual](#x2043165).

### VM
{: #x2043253}

Véase [máquina virtual](#x2043165).

### VPN
{: #x2484351}

Véase
[red privada virtual](#x2043188).


## W
{: #glossw}

### WAR
{: #x2844389}

Véase [archivo web](#x2116506).

### archivo WAR
{: #x2406005}

Véase [archivo web](#x2116506).


### app web
{: #x7636628}

Véase [aplicación web](#x2116500).

### aplicación web (app web)
{: #x2116500}

Aplicación a la que puede accederse mediante un navegador web y que proporciona otras funciones aparte de la visualización estática de la información,
permitiendo, por ejemplo, que el usuario realice una consulta a una base de datos. Los componentes comunes de una aplicación web incluyen páginas HTML,
páginas JSP y servlets. Véase también [app](#x4281528).

### archivo web (WAR)
{: #x2116506}

Formato de archivo comprimido, definido por el estándar Java EE, para almacenar todos los recursos necesarios para instalar y ejecutar una aplicación web en un único archivo.

### espacio de trabajo
{: #x2096037}

Contexto que contiene un conjunto de artefactos que un usuario con el permiso adecuado puede modificar.

## Z
{: #glossz}

### zona
{: #x2070723}

Un dominio independiente de tolerancia a errores. Una zona es una abstracción diseñada para aumentar la tolerancia a errores y reducir la latencia.

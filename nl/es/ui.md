---


copyright:
  years: 2015, 2018
lastupdated: "2018-07-17"

---

{:shortdesc: .shortdesc}
{:tip: .tip}
{:new_window: target="_blank"}

# Funcionamiento de la consola de {{site.data.keyword.cloud_notm}}
{: #ui}

La consola de {{site.data.keyword.cloud}} es una interfaz de usuario que le ayuda a gestionar todos sus recursos de {{site.data.keyword.cloud_notm}}. Cuando accede a la consola de [](https://console.bluemix.net){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo"), puede crear una cuenta gratuita, iniciar sesión, acceder a documentación, acceder al catálogo, ver la información de precios o comprobar el estado de los componentes de {{site.data.keyword.cloud_notm}}. Después de iniciar una sesión, la barra de menús contiene un icono Menú ![Icono Menú](../icons/icon_hamburger.svg) y enlaces adicionales, dependiendo de su tipo de cuenta.
{: shortdesc}

## Utilización de la consola
{: #consoleoptions}

Si es un usuario existente con una cuenta de {{site.data.keyword.cloud_notm}}, puede utilizar el icono de Menú ![Icono de menú](../icons/icon_hamburger.svg) para acceder a todos los recursos existentes en su panel de control.
  * Utilice el enlace de **Catálogo** para crear nuevos recursos.
  * Utilice el enlace de **Documentos** para acceder a información útil sobre {{site.data.keyword.cloud_notm}}.
  * Desde el menú **Soporte**, puede acceder a información sobre las novedades en {{site.data.keyword.cloud_notm}}, el Centro de soporte, opciones para añadir y ver incidencias y la página de Estado.
  * Desde el menú **Gestionar**, puede acceder a las opciones de su cuenta, de facturación y uso y de seguridad.

Si ha enlazado sus cuentas de {{site.data.keyword.cloud_notm}} y SoftLayer, tiene las mismas opciones que el propietario de una cuenta no enlazada, pero además puede navegar al portal de clientes seleccionando el **icono de Menú ![Icono de menú](../icons/icon_hamburger.svg)  > opción Infraestructura**. Desde aquí, puede ver su resumen de cuenta, pedir almacenamiento y dispositivos y gestionar el acceso para usuarios y dispositivos de solo VPN.

## Búsqueda de recursos
{: #search}

Puede buscar recursos desde cualquier lugar de la consola de {{site.data.keyword.cloud_notm}}. Escriba el nombre de un recurso en el campo de búsqueda de la barra de menús de la consola.

Escriba la clave `/` en el teclado para llevar el cursor al campo de búsqueda.
{: tip}

## Gestión de recursos en el panel de control
{: #dashboardview}

Puede utilizar el panel de control para ver y trabajar con los recursos de {{site.data.keyword.cloud_notm}} y con las instancias de servicio de Cloud Foundry. Consulte [¿Qué es un recurso?](/docs/resources/acct_resources.html#resource) para obtener más información.

### Visualización de recursos

Puede ver todos los recursos de su cuenta en todas las regiones desde el panel de control. Para personalizar su vista, utilice las siguientes opciones:

  * Para ver los recursos de un grupo de recursos específico, seleccione un grupo de recursos en la lista **Grupo de recursos**.
  * Para ver los recursos de una organización específica de Cloud Foundry, seleccione una organización en la lista **Organización de Cloud Foundry**.

A continuación, en función de los elementos que haya seleccionado, puede filtrar por las siguientes opciones:

  * Ubicación
  * Espacio de Cloud Foundry
  
Si desea ver y trabajar con recursos en una región específica, expanda el menú **LOCATION** y seleccione una región de la lista.

### Cómo trabajar con los recursos

Puede trabajar con sus recursos de varias formas desde el panel de control:

  * Cada recurso se visualiza en su propia fila y se incluye un icono de Más acciones ![Icono de Más acciones](../icons/overflow-menu.svg) al final de la fila. Pulse el icono **Más acciones** para iniciar, detener, renombrar o suprimir un recurso.
  * Para configurar credenciales o conexiones para un recurso, pulse el nombre del recurso para navegar a la página de detalles del recurso. Para obtener más información, consulte [Adición de una nueva credencial](/docs/resources/service_credentials.html) y [Gestión de conexiones](/docs/resources/connecting_apps.html#connect_app).

## Cómo trabajar en el catálogo
{: #catalogcreate}

Para crear un nuevo recurso, pulse **Crear recurso** en su panel de control. Se le dirigirá al catálogo. Al seleccionar un mosaico del catálogo, puede ver dónde está disponible el recurso. No todos los recursos listados en el catálogo están disponibles en todas las regiones.

Después de pulsar en el mosaico del recurso que desea crear, puede seleccionar la ubicación donde quiere desplegarlo.

  * Para los recursos de Cloud Foundry, puede seleccionar una región específica y luego seleccionar la organización o espacio al que asignar la instancia de servicio.
  * Para los recursos gestionados por {{site.data.keyword.cloud_notm}} IAM, seleccione la ubicación en la que desplegarlos. A continuación, seleccione un grupo de recursos al que asignar la instancia de servicio.

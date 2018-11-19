---

copyright:

  years: 2018

lastupdated: "2018-11-01"

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:pre: .pre}
{:tip: .tip}

# Ubicaciones para el despliegue de recursos 
{: #ov_intro_reg}

Puede crear apps e instancias de servicios en distintas ubicaciones con la misma infraestructura de {{site.data.keyword.cloud_notm}} para la gestión de aplicaciones y la misma vista de detalles de uso para la facturación. Tiene la posibilidad de desplegar sus apps en la ubicación más cercana a sus clientes para conseguir una latencia de aplicación baja.  

Para solventar problemas de seguridad, también puede seleccionar la ubicación en la que desea conservar los datos de aplicación. Cuando crea apps en más de una ubicación, si una ubicación deja de estar disponible. las apps que están en las otras ubicaciones seguirán funcionando. Su concesión de recursos es la misma para cada ubicación que utilice. Para obtener más información acerca de los recursos de la plataforma y las ubicaciones en las que están disponibles, consulte [Disponibilidad de servicios](/docs/resources/service_region.html).

El equilibrio de carga global de la consola garantiza que si la ubicación geográfica más próxima no está disponible, la consola muestra la información de la siguiente ubicación más próxima. De esta forma, siempre podrá acceder a la consola sin realizar acción alguna para acceder a la información que necesita.

<!---This is a pre-pup topic. Post pup, the dashboard will have a Location status widget, which will show geographies as a summary. This paragraph will change and we need to add a paragraph to explain the continents are a summary in the widget.-->
Desde el panel de control, puede ver todos los recursos en todas las ubicaciones de forma predeterminada. Si desea ver y trabajar con recursos en una ubicación específica, expanda el menú **UBICACIÓN** y seleccione una ubicación de la lista. 

También puede utilizar la interfaz de línea de mandatos para conectarse a la ubicación de {{site.data.keyword.cloud_notm}} con la que desee trabajar utilizando el mandato `ibmcloud api` y especificando el punto final de API de la ubicación. Por ejemplo, escriba el siguiente mandato para conectarse a la región Londres de {{site.data.keyword.cloud_notm}}: 

```
ibmcloud api https://api.eu-gb.bluemix.net
```

Cada ubicación tienen asignado un prefijo exclusivo. {{site.data.keyword.cloud_notm}} proporciona las siguientes ubicaciones y prefijos.

| **Ubicación** | **Punto final de API** |
|-----------------|-------------------|
| Dallas | api.us-south.bluemix.net |
| Sídney | api.au-syd.bluemix.net |
| Frankfurt | api.eu-de.bluemix.net |
| Londres | api.eu-gb.bluemix.net |
| Washington DC | api.us-east.bluemix.net |
| Tokio | api.jp-tok.bluemix.net |
{: caption="Tabla 1. Lista de ubicaciones de {{site.data.keyword.cloud_notm}}" caption-side="top"}

Cuando despliegue recursos de la infraestructura, tiene más opciones para elegir dónde se encuentra el contenido. Puede seleccionar una ubicación o puede seleccionar en una lista de centros de datos de {{site.data.keyword.Bluemix_notm}}. Para obtener más información, consulte [Centros de datos de {{site.data.keyword.cloud_notm}}](data-centers.html).

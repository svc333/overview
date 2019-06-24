---

copyright:

  years: 2017, 2019

lastupdated: "2019-05-06"

keywords: crn, cloud resource name

subcollection: overview

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:tip: .tip}

# Nombres de recursos de nube
{: #crn}

Los nombres de recursos de nube (CRN) identifican exclusivamente recursos de {{site.data.keyword.Bluemix_notm}}. Un CRN se utiliza para especificar un recurso de forma inequívoca y con garantía de que es globalmente exclusivo, como en las políticas y servicios de {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) listados en el catálogo de nube.

Un CRN se forma a partir de una concatenación de "segmentos" que identifican jerárquicamente el recurso, su ubicación y el servicio al que pertenece. El delimitador de segmento se establece en ':' (el carácter de dos puntos). Todos los CRN empiezan con el identificador de segmento `crn`.


## Formato de CRN
{: #format-crn}

El formato canónico base de un CRN es:

`crn:version:cname:ctype:service-name:location:scope:service-instance:resource-type:resource`


## version
{: #version-crn}

El segmento `version` identifica la versión del formato de CRN. Actualmente, el único valor de segmento de versión válido es `v1`.


## cname
{: #cname-crn}

El segmento `cname` identifica la instancia de nube y es un identificador alfanumérico que identifica de forma exclusiva la instancia de nube que contiene el recurso. Un `cname` identifica de forma eficaz un plano de control independiente que posee el recurso identificado. El valor del segmento `cname` debe ser `bluemix` para los usuarios de {{site.data.keyword.Bluemix_notm}}.


## ctype
{: #ctype-crn}

El segmento `ctype` identifica el tipo de instancia de nube representado por el segmento `cname` especificado.

 Valores válidos:
  - `public`: Todos los servicios disponibles del catálogo público
  - `dedicated`: Solo para los entornos dedicados de {{site.data.keyword.Bluemix_notm}} actuales
  - `local`: Todos los servicios desplegados localmente en su propio entorno


## service-name
{: #service-name-crn}

El segmento `service-name` identifica de forma exclusiva una funcionalidad (servicio, componente, producto) ofrecida por la nube. La funcionalidad puede ser un servicio proporcionado por el usuario, como con los servicios listados en el catálogo de {{site.data.keyword.Bluemix_notm}} o un componente de arquitectura interno crítico para la funcionalidad de {{site.data.keyword.Bluemix_notm}}.

El segmento `service-name` indica el servicio al que pertenece el recurso y {{site.data.keyword.Bluemix_notm}} impone la exclusividad global de nombres de servicio. El segmento `service-name` debe ser alfanumérico, en minúsculas, sin espacios o caracteres especiales que no sean '-'.

Para los servicios registrados en el catálogo de {{site.data.keyword.Bluemix_notm}}, el segmento `service-name` debe corresponder a uno de los servicios registrados en el servicio de catálogo global de {{site.data.keyword.Bluemix_notm}}. Es la propiedad `name` devuelta por la API de servicio de catálogo global de {{site.data.keyword.Bluemix_notm}} `GET https://globalcatalog.cloud.ibm.com/api/v1/{id}` para la correspondiente instancia de recurso o el `service-name` que muestra la interfaz de línea de mandatos: `ibmcloud service offerings` en la columna `service`.


## location
{: #location-crn}

La geografía, región, zona o centro de datos de nube donde reside el recurso.

El segmento `location` debe ser uno de los siguientes valores:

### Global
{: #global-crn}

 * `global`

### Geografías
{: #geos-crn}

 * `us`
 * `eu`
 * `cn`
 * `ap`

### Regiones
{: #regions-crn}

 * `us-south`
 * `us-east`
 * `au-syd`
 * `eu-gb`
 * `eu-de`
 * `jp-tok`

### Centros de datos
{: #dc-crn}

 * ` AMS01  `
 * ` AMS03  `
 * ` CHE01  `
 * ` DAL01  `
 * `  DAL05  `
 * ` DAL06  `
 * ` DAL07  `
 * ` DAL09  `
 * ` DAL10  `
 * `  DAL12  `
 * ` DAL13  `
 * ` FRA02  `
 * ` HKG02  `
 * ` HOU02  `
 * `  LON02  `
 * ` MEL01  `
 * ` MEX01  `
 * ` MIL01  `
 * ` MON01  `
 * `  OSL01  `
 * ` PAR01  `
 * ` SJC01  `
 * ` SJC03  `
 * ` SAO01  `
 * `  SEA01  `
 * ` SEO01  `
 * ` SNG01  `
 * ` SYD01  `
 * ` TOK02  `
 * `  TOR01  `
 * ` WDC01  `
 * ` WDC04  `
 * ` WDC06  `
 * ` WDC07  `

Algunos recursos no requieren una región, ya que pueden considerarse global. En este caso, el segmento `region` se establece en `global`.
{: tip}


## scope
{: #scope-crn}

El segmento `scope` identifica la contención o propietario del recurso. Algunos recursos no requieren un propietario (pueden considerarse `global`). En este caso, el segmento `scope` está vacío (una serie en blanco).

El valor del segmento `scope` debe tener el formato `{scopePrefix}`/`{id}`. El `scopePrefix` representa el formato utilizado para identificar al propietario o la contención. El `id` representa la identidad del propietario o la contención en un formato que es específico del `scopePrefix`.

| Tipo de ámbito | Prefijo de ámbito | Uso | Ejemplo |
| --- | --- | --- | --- |
| Cuenta | a/`{account id}` | La cuenta en la que se ha creado el recurso. | `a/292558` |
| Organización | o/`{org guid}` | La organización de {{site.data.keyword.Bluemix_notm}} a la que se ha asignado el recurso. | `o/4716e2d1-35b7-431f-891a-b552bf0b3c66` |
| Espacio | s/`{space guid}` | El espacio de {{site.data.keyword.Bluemix_notm}} al que se ha asignado el recurso. | `s/48b3cdcd-e804-4398-9032-73065863ad7c` |
{: caption="Tabla 1. Uso de `scope`" caption-side="top"}



## service-instance
{: #service-instance-crn}

El segmento `service-instance` identifica la instancia de servicio de forma exclusiva. El formato del segmento `service-instance` varía en función del servicio. Cada servicio debe documentar el formato de su segmento `service_instance` como parte de sus metadatos de servicio. Algunos servicios no tienen instancias puesto que la instancia es global y, en ese caso, el campo `service-instance` está en blanco.

El `service-instance` debe ser alfanumérico, en minúsculas, sin espacios ni caracteres especiales que no sean '-' y '/'.

Como ejemplo, una herramienta DevOps para realizar el seguimiento y planificar elementos de trabajo puede tener un ID de instancia `GUID` simple ("1234-5678-9012-3456"), donde el componente de política de un servicio de grupo de autoscale puede utilizar un convenio de denominación jerárquica y tener un segmento `service-id` de:

>`c7a27f55-d35e-4153-b044-8ca9155fc467/my-test-asg1/my-scaleout-policy`

También puede obtener un CRN de un recurso de {{site.data.keyword.Bluemix_notm}} utilizando el mandato de CLI siguiente:
```
ibmcloud resource service-instance
```
{: codeblock}

## resource-type, resource
{: #resource-type-crn}

El valor de los segmentos `resource-type` y `resource` varía en función del servicio. Es necesario un servicio para documentar su segmento `resource types` soportado y el formato del segmento `resource` como parte de sus metadatos.

Como ejemplo, una imagen en el contenedor de recepción del cliente en un servicio Object Storage puede tener un segmento `resource-type` de `object` y un valor `resource` de `CustomerReceipts/clientdinner.png`.

El segmento `resource-type` debe ser alfanumérico, en minúsculas, sin espacios o caracteres especiales que no sean '-'. Un servicio puede decidir que el segmento `resource-type` sea opcional, en cuyo caso se dejará en blanco.


## Ejemplos de CRN
{: #crn_examples}

La siguiente tabla contiene una lista de ejemplos de CRN.

| Ejemplo | Valor |
| --- | --- |
| Trabajador de Kubernetes | `crn:v1:bluemix:public:containers-kubernetes:us-south:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:8042b2a8af6a4a5cbf6dbe09e07311d2:worker:kube-hou02-pa8042b2a8af6a4a5cbf6dbe09e07311d2-w1` |
| Grupo de recursos | `crn:v1:bluemix:public:resource-controller: global:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:resource-group:59bcbfa6ea2f006b4ed7094c1a08dcdd` |
| Instancia de servicio | `crn:v1:bluemix:public:cloud-object-storage:global:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:1a0ec336-f391-4091-a6fb-5e084a4c56f4::` |
| Grupo | `crn:v1:bluemix:public:cloud-object-storage:global:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:1a0ec336-f391-4091-a6fb-5e084a4c56f4:bucket:mybucket` |
{: caption="Tabla 2. Ejemplos de CRN" caption-side="top"}

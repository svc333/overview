---

copyright:

  years: 2017

lastupdated: "2017-11-17"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:tip: .tip}

# Nombres de recursos de nube
{: #crn}

Los nombres de recursos de nube (CRN) identifican exclusivamente recursos de {{site.data.keyword.Bluemix_notm}}. Un CRN se utiliza para especificar un recurso de forma inequívoca y con garantía de que es globalmente exclusivo, como en las políticas y servicios de Gestión de identidad y acceso de {{site.data.keyword.Bluemix_notm}} (IAM) listadas en el catálogo de nube.

Un CRN se forma a partir de una concatenación de "segmentos" que identifican jerárquicamente el recurso, su ubicación y el servicio al que pertenece. El delimitador de segmento se establece en ':' (p.ej. el carácter de dos puntos). Todos los CRN empiezan con el identificador de segmento 'crn'.


## Formato de CRN
{: #format}

El formato canónico base de un CRN es:

**crn:[version](#version):[cname](#cname):[ctype](#ctype):[service-name](#service-name):[location](#location):[scope](#scope):[service-instance](#service-instance):[resource-type:resource](#resource-type)**


## version
{: #version}

El segmento `version` identifica la versión del formato de CRN. Actualmente el único valor de segmento de versión válido es **v1**.


## cname
{: #cname}

El segmento `cname` identifica la instancia de nube y es un identificador alfanumérico que identifica de forma exclusiva la instancia de nube que contiene el recurso. Un `cname` identifica de forma eficaz un plano de control independiente que posee el recurso identificado. El `cname` debe ser `bluemix` para los usuarios de {{site.data.keyword.Bluemix_notm}}.


## ctype
{: #ctype}

El segmento `ctype` identifica el tipo de instancia de nube representado por el especificador `cname`.

>Valores válidos:
  - public: Todos los servicios disponibles del catálogo público.
  - dedicated: Solo para los entornos dedicados de {{site.data.keyword.Bluemix_notm}} actuales.
  - local: Todos los servicios desplegados localmente en su propio entorno.


## service-name
{: #service-name}

El segmento `service-name` identifica de forma exclusiva una funcionalidad (servicio, componente, producto) ofrecida por la nube. La funcionalidad puede ser un servicio proporcionado por el usuario como con los servicios listados en el catálogo de {{site.data.keyword.Bluemix_notm}} o un componente de arquitectura interno crítico para la funcionalidad de {{site.data.keyword.Bluemix_notm}}.

El `service-name` indica el servicio al que pertenece el recurso y {{site.data.keyword.Bluemix_notm}} impone la exclusividad global de nombres de servicio. El `service-name` debe ser alfanumérico, en minúsculas, sin espacios o caracteres especiales que no sean '-'.

Para los servicios registrados en el catálogo de {{site.data.keyword.Bluemix_notm}} el `service-name` debe corresponder a uno de los servicios registrados en el servicio de catálogo global de {{site.data.keyword.Bluemix_notm}}. Es la propiedad `name` devuelta por la API de servicio de catálogo global de {{site.data.keyword.Bluemix_notm}} `GET https://resource-catalog.bluemix.net/api/v1/{id}` para la correspondiente instancia de recurso o el `service-name` que muestra la interfaz de línea de mandatos: `bx service offerings` en la columna `service`.


## location
{: #location}

La geografía, región, zona o centro de datos de nube donde reside el recurso.

La `location` debe ser uno de los siguientes valores:

### Global

 * `global`

### Geografías

 * `us`
 * `eu`
 * `cn`
 * `ap`

### Regiones

 * `us-south`
 * `au-syd`
 * `eu-gb`
 * `eu-de`

### Centros de datos


| | | | | |
|---|---|---|---|---|
| AMS01  | AMS03  | CHE01  | DAL01  |  DAL05  |
| DAL06  | DAL07  | DAL09  | DAL10  |  DAL12  |
| DAL13  | FRA02  | HKG02  | HOU02  |  LON02  |
| MEL01  | MEX01  | MIL01  | MON01  |  OSL01  |
| PAR01  | SJC01  | SJC03  | SAO01  |  SEA01  |
| SEO01  | SNG01  | SYD01  | TOK02  |  TOR01  |
| WDC01  | WDC04  | WDC06  | WDC07  |
{: caption="Tabla 1. Valores de `Centro de datos` válidos" caption-side="top"}

Algunos recursos no requieren una región (pueden considerarse `global`). En este caso, el segmento `region` se establece en `global`.
{: tip}


## ámbito
{: #scope}

El segmento `scope` identifica la contención o propietario del recurso. Algunos recursos no requieren un propietario (pueden considerarse `global`). En este caso, el segmento `scope` está vacío (una serie en blanco).

El valor del segmento `scope` debe tener el formato `{scopePrefix}`/`{id}`. El `scopePrefix` representa el formato utilizado para identificar al propietario o la contención. El `id` representa la identidad del propietario o la contención en un formato que es específico del `scopePrefix`.

| Tipo de ámbito | Prefijo de ámbito | Uso | Ejemplo |
| --- | --- | --- | --- |
| Cuenta | a/`{account id}` | La cuenta en la que se ha creado el recurso. | a/292558 |
| Organización | o/`{org guid}` | La organización de {{site.data.keyword.Bluemix_notm}} a la que se ha asignado el recurso. | o/4716e2d1-35b7-431f-891a-b552bf0b3c66 |
| Espacio | s/`{space guid}` | El espacio de {{site.data.keyword.Bluemix_notm}} al que se ha asignado el recurso. | s/48b3cdcd-e804-4398-9032-73065863ad7c |
{: caption="Tabla 2. Uso del `ámbito`" caption-side="top"}

El `account id` debe ser el ID de cuenta de IBM (cuentas enlazadas e {{site.data.keyword.Bluemix_notm}} y Softlayer).


## service-instance
{: #service-instance}

El segmento `service-instance` identifica la instancia de servicio de forma exclusiva. El formato del segmento `service-instance` varía en función del servicio. Cada servicio debe documentar el formato de su `service_instance` como parte de sus metadatos de servicio. Algunos servicios no tienen instancias puesto que la instancia es global y en ese caso el campo `service-instance` estará en blanco.

El `service-instance` debe ser alfanumérico, en minúsculas, sin espacios o caracteres especiales que no sean '-' y '/'.

Como ejemplo, una herramienta DevOps para realizar el seguimiento y planificar elementos de trabajo puede tener un ID de instancia `GUID` simple ("1234-5678-9012-3456"), donde el componente de política de un servicio de grupo de autoscale puede utilizar un convenio de denominación jerárquica y tener un segmento `service-id` de:

>`c7a27f55-d35e-4153-b044-8ca9155fc467/my-test-asg1/my-scaleout-policy`


## resource-type, resource
{: #resource-type}

El valor de los segmentos `resource-type` y `resource` varía en función del servicio. Es necesario un servicio para documentar sus `resource types` soportados y el formato del `resource` como parte de sus metadatos.

Como ejemplo, una imagen en el contenedor de recepción del cliente en un servicio de almacenamiento de objetos puede tener un `resource-type` de `object` y un `resource_ value` de `CustomerReceipts/clientdinner.png`. 

El `resource-type` debe ser alfanumérico, en minúsculas, sin espacios o caracteres especiales que no sean '-' y '/'. Un servicio puede decidir que el `resource-type` sea opcional, en cuyo caso se dejará en blanco.


## Ejemplos de CRN
{: #crn_examples}

Lo siguiente es una lista de ejemplos de CRN.

| Ejemplo | Valor |
| --- | --- |
| Contenedor | `crn:v1:bluemix:public:containers-kubernetes:us-south:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:8042b2a8af6a4a5cbf6dbe09e07311d2:worker:kube-hou02-pa8042b2a8af6a4a5cbf6dbe09e07311d2-w1:`|
| Grupo de recursos | `crn:v1:bluemix:public:resource-controller: global:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:resource-group:59bcbfa6ea2f006b4ed7094c1a08dcdd` |
| Instancia de servicio | `crn:v1:bluemix:public:cloud-object-storage:global:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:1a0ec336-f391-4091-a6fb-5e084a4c56f4::` |
| Grupo | `crn:v1:bluemix:public:cloud-object-storage:global:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:1a0ec336-f391-4091-a6fb-5e084a4c56f4:bucket:mybucket` |
{: caption="Tabla 3. Ejemplos de CRN" caption-side="top"}



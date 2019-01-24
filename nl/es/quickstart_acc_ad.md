---

copyright:

  years: 2018, 2019

lastupdated: "2019-01-02"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:tip: .tip}

# Configuración de la cuenta
{: #quickstart_acc_ad}

Esta guía de inicio rápido está pensada para ayudar a los administradores de cuentas a configurar su entorno de {{site.data.keyword.Bluemix}}. 
{:shortdesc}

1. Cree grupos de recursos para utilizarlos y organizar los recursos creados desde el catálogo de {{site.data.keyword.Bluemix_notm}}. Para obtener más información, consulte [Mejores prácticas para organizar los recursos en grupos de recursos](/docs/resources/bestpractice_rgs.html#bp_resourcegroups).

  Hacer esto de forma anticipada es importante porque después de asignar un recurso a un grupo de recursos, este no se podrá mover.
  {:tip}
  
2. Como la Gestión de identidad y acceso (IAM) de {{site.data.keyword.Bluemix_notm}} no gestiona todos los servicios, cree su organización de Cloud Foundry para organizar y otorgar acceso a dichos servicios. Con una cuenta Lite, puede obtener una organización de Cloud Foundry en una ubicación de {{site.data.keyword.Bluemix_notm}}. Para obtener más información, consulte [Adición de organizaciones y espacios](/docs/account/orgs_spaces.html#orgsspacesusers). 
3. Cree grupos de acceso para organizar los usuarios y los ID de servicio en grupos que requieren el mismo nivel de acceso asignado. Para obtener más información, consulte el apartado [Configuración de grupos de acceso](/docs/iam/groups.html#groups).
4. Invite a los usuarios a la cuenta y añádalos a grupos de acceso para asignar el acceso necesario y permitir que los usuarios puedan crear. Para obtener más información, consulte la [Guía de aprendizaje de iniciación para IAM](/docs/iam/quickstart.html#getstarted).
5. Configure las notificaciones para los sucesos y los límites de gastos de cuentas. Para obtener más información, consulte [Establecimiento de preferencias de correo electrónico](/docs/account/email.html) y [Establecimiento de notificaciones de gastos](/docs/billing-usage/notifications.html). 
6. Utilice el estimador de costes para obtener una idea de cuánto puede costar su entorno. Pulse en el icono Estimador de costes ![icono Estimador](../icons/Estimator.svg) en la barra de menús de la consola. 
7. Utilice el estimador de costes para obtener una idea de cuánto puede costar su infraestructura. 
  
  a. Empiece por seleccionar una oferta desde el [catálogo](https://cloud.ibm.com/catalog){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg). 
  
  b. Especifique los detalles de configuración, seleccione su plan de precios y pulse **Añadir a estimación**.

## Pasos siguientes
{: #next-steps}

* Empiece a crear servicios en la cuenta para permitir que su organización y los desarrolladores puedan crear las soluciones que necesitan.  
* Cree etiquetas y etiquete los recursos para ayudar a organizar la forma de ver la facturación y el uso. Esto facilita la identificación de las devoluciones en distintas organizaciones. Para obtener más información, consulte [Prácticas recomendadas para etiquetar recursos](/docs/account/bp_account.html#tags). 

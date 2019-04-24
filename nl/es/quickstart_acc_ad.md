---

copyright:

  years: 2018, 2019

lastupdated: "2019-02-19"

keywords: account quick start, account set up

subcollection: overview

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

1. Cree grupos de recursos para organizar los recursos que cree desde el catálogo de {{site.data.keyword.Bluemix_notm}}. Para obtener más información, consulte [Mejores prácticas para organizar los recursos en grupos de recursos](/docs/resources?topic=resources-bp_resourcegroups).

  Crear un grupo de recursos de forma anticipada es importante porque después de asignar un recurso a un grupo de recursos, este no se podrá mover.
  {:tip}
  
2. Como {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) no gestiona todos los servicios, cree su organización de Cloud Foundry para organizar y otorgar acceso a dichos servicios. Con una cuenta Lite, puede obtener una organización de Cloud Foundry en una ubicación de {{site.data.keyword.Bluemix_notm}}. Para obtener más información, consulte [Adición de organizaciones y espacios](/docs/account?topic=account-orgsspacesusers). 
3. Cree grupos de acceso para organizar los usuarios y los ID de servicio en grupos que requieren el mismo nivel de acceso asignado. Para obtener más información, consulte el apartado [Configuración de grupos de acceso](/docs/iam?topic=iam-groups).
4. Invite a los usuarios a la cuenta y añádalos a grupos de acceso para asignar el acceso necesario y permitir que los usuarios puedan crear. Para obtener más información, consulte la [Guía de aprendizaje de iniciación para IAM](/docs/iam?topic=iam-getstarted).
5. Configure las notificaciones para los sucesos y los límites de gastos de cuentas. Para obtener más información, consulte [Establecimiento de preferencias de correo electrónico](/docs/account?topic=account-email-prefs) y [Establecimiento de notificaciones de gastos](/docs/billing-usage?topic=billing-usage-spending). 
6. Utilice el estimador de costes para obtener una idea de cuánto puede costar su entorno. Pulse en el icono Estimador de costes ![icono Estimador](../icons/Estimator.svg) en la barra de menús de la consola. 
7. Utilice el estimador de costes para obtener una idea de cuánto puede costar su infraestructura. 
  
  a. Empiece por seleccionar una oferta desde el [catálogo](https://cloud.ibm.com/catalog){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg). 
  
  b. Especifique los detalles de configuración, seleccione su plan de precios y pulse **Añadir a estimación**.

## Pasos siguientes
{: #next-steps-acc-ad}

* Empiece a crear servicios en la cuenta para permitir que su organización y los desarrolladores puedan crear las soluciones que necesitan.  
* Cree etiquetas y etiquete los recursos para ayudar a organizar la forma de ver la facturación y el uso. De ese modo, se facilita la identificación de las devoluciones en distintas organizaciones. Para obtener más información, consulte [Prácticas recomendadas para etiquetar recursos](/docs/account?topic=account-account_setup#tags). 

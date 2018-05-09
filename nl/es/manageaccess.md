---

copyright:

  years: 2017, 2018

lastupdated: "2018-04-12"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}

# Gestión de acceso en {{site.data.keyword.Bluemix_notm}}
{: #cloudaccess}

## ¿Qué es la gestión de acceso?

La gestión de acceso le permite controlar qué usuarios ven, crean, utilizan y gestionan recursos en su cuenta. Para otorgar acceso, puede asignar roles que permitan a los usuarios niveles de acceso para completar tareas de gestión de plataforma y acceder a recursos de cuenta.

La forma en que gestiona el acceso en {{site.data.keyword.Bluemix_notm}} depende del tipo de recurso al que desea asignar acceso. La Gestión de identidad y acceso de {{site.data.keyword.Bluemix_notm}} (IAM) es el sistema de gestión de acceso para gestionar recursos de forma coherente en la plataforma de {{site.data.keyword.Bluemix_notm}}. La infraestructura de {{site.data.keyword.Bluemix_notm}} y los recursos de Cloud Foundry no se gestionan utilizando Cloud IAM. Estos tipos de recursos tienen sus propios sistemas de gestión de acceso. Si tiene una combinación de tipos de recursos, gestiona cada tipo de forma separada. Para [asignar acceso a sus recursos de infraestructura](/docs/iam/infrastructureaccess.html#infrapermission), defina permisos dentro de su cuenta de SoftLayer. Para [asignar acceso a recursos de Cloud Foundry](/docs/iam/cfaccess.html#cfaccess), utilice la opción Asignar utilizando Cloud Foundry en la sección Identidad y acceso de la consola.

## ¿Quién tiene permisos para gestionar el acceso?

Como propietario de una cuenta, puede gestionar el acceso a todos los recursos de su cuenta. También puede delegar la tarea de gestionar el acceso a los recursos de plataforma asignando el rol de administrador a un usuario en su cuenta para todos los servicios.

Si tiene servicios de Cloud Foundry en su cuenta, puede asignar a otro usuario el rol de gestor de espacio u organización para que pueda añadir usuarios y asignar roles de usuario de Cloud Foundry para acceder a las instancias en el espacio u organización que gestionan.


## ¿Cómo empiezo a gestionar el acceso?

Vaya a **Gestionar** &gt; **Seguridad** &gt; **Identidad y acceso** y luego seleccione **Usuarios** para empezar a gestionar el acceso para los usuarios en su cuenta. Seleccione un usuario de la lista para empezar. Solo ve las opciones de gestión de acceso que tiene permisos para gestionar. Por ejemplo, si no es el propietario de la cuenta y no es un gestor de organización o espacio, no ve la opción de gestionar el acceso de Cloud Foundry.

Los roles de acceso solo pueden asignarse a apps y servicios utilizando los identificadores de servicio. Vaya a la página **ID de servicio** para empezar. Para obtener más información sobre cómo preparar y ejecutar rápidamente con Cloud IAM siga los pasos de [Guía de aprendizaje de iniciación](/docs/iam/quickstart.html#getstarted).

---

copyright:

  years: 2017, 2019

lastupdated: "2018-03-14"

keywords: users level of access, user control, access control, permissions

subcollection: overview

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}

# Gestión de acceso en {{site.data.keyword.Bluemix_notm}}
{: #cloudaccess}

La gestión de acceso le permite controlar qué usuarios ven, crean, utilizan y gestionan recursos en su cuenta. Para otorgar acceso, puede asignar roles que permitan a los usuarios niveles de acceso para completar tareas de gestión de plataforma y acceder a recursos de cuenta.
{: shortdesc}

La forma en que gestiona el acceso en {{site.data.keyword.Bluemix_notm}} depende del tipo de recurso al que desea asignar acceso. {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) es el sistema de gestión de acceso para gestionar recursos de forma coherente organizado en un grupo de recursos en la plataforma de {{site.data.keyword.Bluemix_notm}}. La infraestructura clásica y los recursos de Cloud Foundry no se gestionan utilizando Cloud IAM. Estos tipos de recursos tienen sus propios sistemas de gestión de acceso. 

Si tiene una combinación de tipos de recursos, gestiona cada tipo de forma separada. Para asignar el acceso a los [recursos de la infraestructura clásica](/docs/iam/infrastructureaccess.html#infrapermission), establezca los permisos en **Gestionar** > **Acceso (IAM)** en el separador Infraestructura clásica del usuario al que desea asignar el acceso. Para asignar acceso a los [recursos de Cloud Foundry](/docs/iam/cfaccess.html#cfaccess), asigne usuarios a organizaciones y establezca Cloud Foundry y los roles de acceso del espacio en **Gestionar** > **Acceso (IAM)** en el separador de Cloud Foundry del usuario al que desea asignarle el acceso.

## Permisos para gestionar el acceso
{: #perms-manageaccess}

Como propietario de una cuenta, puede gestionar el acceso a todos los recursos de su cuenta. También puede delegar la tarea de gestionar el acceso a los recursos de plataforma asignando el rol de administrador a un usuario en su cuenta para todos los servicios, solo un servicio en concreto o el grupo de recursos que desea que gestione el usuario.

Si tiene servicios de Cloud Foundry en su cuenta, puede asignar a otro usuario el rol de gestor de espacio u organización para que pueda añadir usuarios y asignar roles de Cloud Foundry para acceder a las instancias en el espacio u organización que gestionan.


## Guía de inicio
{: #cloudaccess-getstarted}

Vaya a **Gestionar** &gt; **Acceso (IAM)** y seleccione **Usuarios** para empezar a gestionar el acceso de los usuarios de la cuenta. Seleccione un usuario de la lista para empezar. Solo ve las opciones de gestión de acceso que tiene permisos para gestionar. Por ejemplo, si no es el propietario de la cuenta y no es un gestor de organización o espacio, no ve la opción de gestionar el acceso de Cloud Foundry.

También puede asignar roles de acceso a apps y servicios utilizando los ID de servicio. Vaya a la página **ID de servicio** para empezar. Para obtener más información sobre cómo empezar a trabajar rápidamente con Cloud IAM, consulte la [Guía de aprendizaje de iniciación](/docs/iam/quickstart.html#getstarted).

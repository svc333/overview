---

copyright:
  years: 2017, 2018
lastupdated: "2018-10-11"

---

{:shortdesc: .shortdesc}

# Organización de recursos en grupos de recursos
{: #whatis}

Un grupo de recursos es una manera de organizar sus [recursos](/docs/resources/acct_resources.html#resource) de cuenta en agrupaciones personalizables, para que pueda asignar accesos de usuario rápidamente a más de un recurso a la vez. Cualquier recurso de cuenta gestionado utilizando el control de acceso de la Gestión de identidad y acceso de {{site.data.keyword.Bluemix}} pertenece a un grupo de recursos dentro de su cuenta. Cuando añade un nuevo recurso a su cuenta desde el catálogo, puede asignarlo a un grupo de recursos. La única excepción es Kubernetes, que no le solicita ninguna asignación de grupo de recursos, aunque el acceso al servicio se controla mediante roles de IAM.

Los servicios se gestionan utilizando {{site.data.keyword.Bluemix}} IAM y pertenecer a un grupo de recursos proporciona varios beneficios incluyendo la capacidad de conectarse con apps y servicios en cualquier espacio de Cloud Foundry, lo que le permite conectar apps y servicios de diferentes ubicaciones. Puesto que los grupos de recursos no se tratan por ubicaciones, puede disponer de apps y servicios de diferentes ubicaciones en el mismo grupo de recursos. También tiene la capacidad de utilizar el control de acceso preciso en una instancia individual dentro de un grupo de recursos.

Para obtener más información sobre cómo trabajar con grupos de recursos, consulte [Gestionar grupos de recursos](/docs/resources/resourcegroups.html). Y, si es nuevo utilizando grupos de recursos, consulte las [Mejores prácticas para organizar los recursos en grupos de recursos](/docs/resources/bestpractice_rgs.html#bp_resourcegroups).

---

copyright:

  years: 2020

lastupdated: "2020-06-01"

keywords: roles and responsibilities, shared responsibilities, IBM responsibility, customer responsibility

subcollection: overview

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:tip: .tip}
{:note: .note}

# Shared responsibilities for using {{site.data.keyword.cloud_notm}} offerings
{: #shared-responsibilities}

In {{site.data.keyword.cloud}}, as is the case for other cloud service providers, the responsibilities for managing the lifecycle of, operating, and securing offerings are shared between {{site.data.keyword.IBM}} and the customer.

The responsibility of completing the following types of tasks on various offerings can be exclusive to {{site.data.keyword.IBM_notm}}, the customer, or shared between the two. The tasks for each type of offering are grouped in the following categories:

* Incident and operations management: Includes tasks such as monitoring, event management, high availability, problem determination, recovery, and full state backup and recovery.
* Change management: Includes tasks such as deployment, configuration, upgrades, patching, configuration changes, and deletion.
* Identity and access management: Includes tasks such as authentication, authorization, access control policies, and approving, granting, and revoking access.
* Security and regulation compliance: Includes tasks such as security controls implementation and compliance certification.
* Disaster recovery: Includes tasks such as providing dependencies on disaster recovery sites, provision disaster recovery environments, data and configuration backup, replicating data and configuration to the disaster recovery environment, and failover on disaster events.

When you're reviewing the following sections, the tables list resources for each category and who manages them. The following list describes what constitutes each type of resource in {{site.data.keyword.cloud_notm}}.

<dl>
  <dt>Data</dt>
  <dd>Customer-owned content that includes all data managed and controlled by the customer, such as information stored into volumes, files, and databases hosted on IBM cloud resources and data processed, stored and logged by the client applications hosted on IBM cloud. It doesn't include client metadata, the information used by IBM to provide services to the customer and support and operate the client account, services, and reosurces that are always considered to be shared responsibility between client and IBM.
</dd>
  <dt>Applications</dt>
  <dd>Customer-owned software components, such as executables, web applications, middlewares, frameworks, libraries, and any other software packages deployed by the clients that they developed or acquired by third parties and they deploy in {{site.data.keyword.cloud_notm}}.</dd>
  <dt>Operating systems</dt>
  <dd>The operating system software and configuration deployed in virtual or bare metal servers, such as Linux, Windows, or similar to the ones provided in [stock images](/docs/vpc-on-classic-vsi?topic=vpc-on-classic-vsi-images)</dd>
<dt>Virtual and bare metal servers</dt>
  <dd>The virtual or bare metal servers ordered and managed through IBM Cloud services     </dd>  
 <dt>Virtual storages</dt>
  <dd>The block, file or Object Storage buckets ordered and managed through {{site.data.keyword.cloud_notm}}.</dd>   
 <dt>Virtual network</dt>
  <dd>Network resources such as VLAN, VPC, subnets, or IPs provided by [classic infrastructure](/docs/vlans?topic=vlans-getting-started) and [VPC](/docs/vpc?topic=vpc-about-networking-for-vpc) services ordered and managed through {{site.data.keyword.cloud_notm}}.</dd>   
<dt>Hypervisor</dt>
  <dd>The software and configuration deployed in physical servers to host and manage the lifecycle of virtual servers.</dd> 
<dt>Physical servers and memory</dt>
  <dd>The physical compute devices and resources, such as cores, memory, and GPUs used to host the virtual or bare metal servers.</dd>   
<dt>Physical storage</dt>
  <dd>The physical storage devices and resources, such as disks and storage devices used to host the virtual block, file or object storage buckets.</dd>   
<dt>Physical network and devices</dt>
  <dd>The physical network devices and resources, such as switch, routers, gateways, firewalls, and load balancers used to host the virtual network resources.  </dd> 
<dt>Facilities and data centers</dt>
  <dd>The physical data center buildings with power, cooling, and rooms for all the {{site.data.keyword.cloud_notm}} physical equipment. </dd> 
</dl>

{{site.data.keyword.cloud_notm}} supports the following types of offerings and the corresponding shared responsibility models. For more information about each specific service, refer to the documentation for that service.

## Infrastructure-as-a-service 
{: #iaas-services-responsibilities}

Infrastructure-as-a-service (IaaS) offerings that are managed by {{site.data.keyword.IBM_notm}} are fully multi-tenant, accessed remotely, hosted on {{site.data.keyword.IBM_notm}} physical infrastructure, created in customer-owned accounts, and have control plane and data plane security that is owned by {{site.data.keyword.IBM_notm}}. Examples of this offering type are Virtual Servers and Bare Metal Servers with the related block volumes connected to the customer account private subnets. You can find a list of these types of offerings in the {{site.data.keyword.cloud_notm}} catalog on the Services tab, and each offering is in an infrastructure sub-category within the Compute or VPC infrastructure categories.


| Resource | Incident and Operations Management | Change Management | Identity and Access Management | Security and Regulation Compliance | Disaster Recovery |
| - | - | - | - | - | - |
| Data | Customer | Customer | Customer | Customer | Customer |
| Application | Customer | Customer | Customer | Customer | Customer |
| Operating system | Customer | Customer | Customer | Customer | Customer |
| Virtual and bare metal servers | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | Shared |
| Virtual storage | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | Shared |
| Virtual network | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | Shared |
| Hypervisor | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
| Physical servers and memory | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
| Physical storage | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
| Physical network and devices | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
| Facilities and data centers | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
{:caption="Table 1. Shared responsibilities for IaaS offerings" caption-side="top"}

## Managed offerings
{: #managed-responsibilities}

Offerings that are managed by {{site.data.keyword.IBM_notm}} require customer responsibilities only for the data or applications that customers add to the service. They are multi-tenant, accessed remotely, hosted on {{site.data.keyword.IBM_notm}} virtual resources, created in IBM-owned accounts, and have control plane and data plane security that is owned by {{site.data.keyword.IBM_notm}}. Examples of this offering type are {{site.data.keyword.cloud_notm}} databases or {{site.data.keyword.cloudant_short_notm}} database instances. You can find a list of these types of offerings in the {{site.data.keyword.cloud_notm}} catalog on the Services tab. However, any offerings listed in an infrastructure sub-category are infrastructure-as-a-service type offerings. 

| Resource | Incident and Operations Management | Change Management | Identity and Access Management | Security and Regulation Compliance | Disaster Recovery |
| - | - | - | - | - | - |
| Data |Customer  | Customer | Customer | Customer | Customer | Customer |
| Application | Customer | Customer | Customer | Customer | Customer |
| Service instance | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | Shared |
| Virtual and bare metal servers | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | Shared |
| Virtual storage | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | Shared |
| Virtual network | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | Shared |
| Hypervisor | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
| Physical servers and memory | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
| Physical storage | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
| Physical network and devices | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
| Facilities and data centers | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
{:caption="Table 2. Shared responsibilities for fully-managed offerings" caption-side="top"}

## Managed offerings on customer's resources
{: #managed-offerings-on-customers-resources-responsibilities}

Managed offerings on customer's resources are orchestrated by {{site.data.keyword.IBM_notm}}, meaning they are single-tenant and data plane offerings. In addition, they are accessed locally in customer accounts, data plane hosted on virtual resources in the customer's account, control plane security owned by {{site.data.keyword.IBM_notm}}, and data plane security owned by the customer. {{site.data.keyword.cloud_notm}} offerings of this type include {{site.data.keyword.containerlong_notm}} on classic infrastructure and {{site.data.keyword.openshiftlong}} on classic infrastructure.

| Resource | Incident and Operations Management | Change Management | Identity and Access Management | Security and Regulation Compliance | Disaster Recovery |
| - | - | - | - | - | - |
| Data | Customer | Customer | Customer | Customer | Customer |
| Application | Customer | Customer | Customer | Customer | Customer |
| Service instance | Shared | Shared | Shared | Shared | Shared |
| Operating system | Shared | Shared | Shared | Shared | Shared |
| Virtual and bare metal servers | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | Shared |
| Virtual storage | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | Shared |
| Virtual network | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | Shared |
| Hypervisor | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
| Physical servers and memory | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
| Physical storage | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
| Physical network and devices | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
| Facilities and data centers | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
{:caption="Table 3. Shared responsibilities for self-managed offerings" caption-side="top"}

## Software packages

Software packages are deployed by {{site.data.keyword.IBM_notm}} as single tenant instances, and they are accessed locally in the customer account. The software instance is hosted on resources in the customer's accounts. The software deployment control plane security is owned by {{site.data.keyword.IBM_notm}}, and the software instance security is owned by the customer.

There is a generic software deployment control plane that manages the lifecycle of deployed software package instances. At a minimum, it manages the deployment, upgrade, and delete actions. As the packages become smarter, the generic control plane might also manage the start, stop, migration, scaling, monitoring, backup, and restore tasks.

You can find a list of software type offerings in the {{site.data.keyword.cloud_notm}} catalog on the Software tab.

| Resource | Incident and Operations Management | Change Management | Identity and Access Management | Security and Regulation Compliance | Disaster Recovery |
| - | - | - | - | - | - |
| Data | Customer | Customer | Customer | Customer | Customer |
| Application | Customer | Customer | Customer | Customer | Customer |
| Software packages | Shared | Shared | Customer | Customer | Shared |
| Operating system | Shared | Shared | Customer | Customer | Shared |
| Virtual and bare metal servers | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | Shared |
| Virtual storage | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | Shared |
| Virtual network | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | Shared |
| Hypervisor | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
| Physical servers and memory | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
| Physical storage | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
| Physical network and devices | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
| Facilities and data centers | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | IBM |
{:caption="Table 4. Shared responsiblities for software packages" caption-side="top"}

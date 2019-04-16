---

copyright:
  years: 2018, 2019
lastupdated: "2019-04-16"

keywords: cloud environment, virtual server, virtual machine, vm, understanding infrastructure, IaaS model

subcollection: overview


---
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}
{:tip: .tip}
{:note: .note}

# Explore the IT ops admin journey in {{site.data.keyword.cloud_notm}}
{: #it-ops}

As many organizations move to a cloud environment, either on-premises or hosted in data centers, the IT operations administrator's (IT ops admin) role is being redefined. The scope and complexity of this change increases significantly based on the type of environment that your organization wants to deploy. 
{: .shortdesc}

Before moving to the cloud, you worked with an inherently secure environment with systems connected to your private LAN or intranet. In a cloud environment, you're now expected to perform the following tasks:
 
  * Procure your system components from "somewhere." 
  * Understand network implications and security challenges.
  * Work with different technologies.  
  * Integrate the new environment with tools that are not natively part of the cloud stack. 
  * Continue to support your internal customers as if you still have an on-premises data center.

{{site.data.keyword.cloud}} is here to support you 100% on your journey. The resources available to you include comprehensive documentation, planning tools, qualified support specialists, and an active user community. Let's get you started on your journey. 

## Understanding the basics
{: #basics}

### Cloud service models
{: #cloud-svc-models}

Three types of cloud service models exist: Infrastructure as a Service (IaaS), Platform as a Service (PaaS), and Software as a Service (SaaS). Figure 1 explains who does what within each service model. For more information, see [IaaS, PaaS, and SaaS - IBM Cloud service models](https://www.ibm.com/cloud/learn/iaas-paas-saas){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon").

![Figure 1. Cloud service models](images/cloud-svc-models.png "Cloud service models")

With the IaaS model, your provider is responsible for maintaining the underlying infrastructure only and optionally installing software, such as operating systems, applications, and databases. You have limited access to the underlying infrastructure, and you're responsible for installing your software or have your service provider install it. You're also responsible for all other maintenance, which includes service packs, virus software, and patches.

With the PaaS model, your provider is responsible for the systems through the operating system and for all infrastructure management, which includes OS patches, hardware repairs, and network settings. You build and maintain the application, and you or your provider can install middleware, including databases or other types. This model is used to develop and test software. For more information, see [A practical guide to platform as a service: What is PaaS ![External link icon](../icons/launch-glyph.svg "External link icon")](https://www.ibm.com/blogs/cloud-computing/2016/08/10/practical-guide-paas/){: new_window}.

With the SaaS model, your provider maintains the systems through the actual application. The application is cloud-aware, and users can use different end points, depending on the software provider, to use the software. The cloud provider is responsible for all infrastructure and application management, which includes software updates, hardware repairs, and network settings. This model is often used in pay-as-you-go software licensing models. For more information, see [SaaS applications for business and IT](https://www.ibm.com/cloud/saas){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon").

### Cloud types
{: #cloud-types}

There are three different types of clouds available: public, private, and hybrid. A public cloud includes a shared set of resources that are provisioned to allow access to a company's resources. It is hosted in a multi-tenant environment on a virtual server, and it can be accessed from anywhere. 

A private cloud includes resources that are provisioned to allow access to a company's resources. It is hosted on dedicated hardware, such as a bare metal server, and either onsite at the company's office (or across offices) or by a cloud provider. A private cloud can be accessed from anywhere.

A hybrid cloud includes resources that combine the aspects of both public and private clouds. It is hosted both onsite at a company's office (or across offices) and by a cloud provider. A hybrid cloud can be accessed from anywhere. 

## Planning your infrastructure
{: #planning}

You want to plan your infrastructure before you provision it to make sure that you size it correctly for your workload. {{site.data.keyword.cloud_notm}} has several tools and sites to help you with designing and sizing your infrastructure. 

### Infrastructure architecture

Start with the [infrastructure architecture ![External link icon](../icons/launch-glyph.svg "External link icon")](https://www.ibm.com/cloud/garage/architectures/infrastructure){: new_window} to get a more in-depth overview of the three types of cloud environments. 

### {{site.data.keyword.cloud_notm}} Design Decision Tool

The [{{site.data.keyword.cloud_notm}} Design Decision Tool ![External link icon](../icons/launch-glyph.svg "External link icon")](https://github.com/ibm-cloud-architecture/infrastructure-design-decision-tool/){: new_window} helps you compare alternatives when you design and build your custom solution. Each infrastructure component features description, considerations and caveats, and side-by-side comparisons. You can also find an example of how to use the tool.

### {{site.data.keyword.cloud_notm}} Stencils

[{{site.data.keyword.cloud_notm}} Stencils ![External link icon](../icons/launch-glyph.svg "External link icon")](https://github.com/ibm-cloud-architecture/ibm-cloud-stencils){: new_window} help you create a diagram of your {{site.data.keyword.cloud_notm}} architecture by using popular diagramming tools. 

### Bare metal server options

Use the [{{site.data.keyword.cloud_notm}} {{site.data.keyword.baremetal_short}} Search Tool ![External link icon](../icons/launch-glyph.svg "External link icon")](https://www.ibm.com/cloud-computing/bluemix/bare-metal-search){: new_window} to size and estimate your bare metal server options, including servers that are certified to support SAP HANA and SAP NetWeaver workloads.

### {{site.data.keyword.cloud_notm}} services and compliance

As with any architecture, you should consider the {{site.data.keyword.cloud_notm}} resources that you might add to your solution as you size your infrastructure. For more information, see [SaaS applications for business and IT ![External link icon](../icons/launch-glyph.svg "External link icon")](https://www.ibm.com/cloud/saas){: new_window} and search for a specific service. You also need to think about any regulations that you have to consider when you build your architecture. For example, is your workload considered sensitive or is it regulated? For more information, see [Compliance ![External link icon](../icons/launch-glyph.svg "External link icon")](https://www.ibm.com/cloud/compliance){: new_window}.

## Building your infrastructure
{: #build}

After you plan and design your infrastructure, you're ready to build it. 

### Compute
{: #compute}

Your server is the base of your infrastructure. You have various options depending on your needs, or you can mix it up if that's what your environment requires. Check out the following table for a summary of your compute options.

| Option | Description | 
|--------|---------------|
| [{{site.data.keyword.baremetal_short}}](/docs/bare-metal?topic=bare-metal-about-bm#about-bm)  | Hourly or monthly, single-tenant servers that are dedicated to you and not shared in any part, including server resources, with other customers. |
| [{{site.data.keyword.BluVirtServers_short}}](/docs/vsi?topic=virtual-servers-about-public-virtual-servers#public-virtual-servers) | Scalable virtual servers that are purchased with dedicated cores and memory allocations. |
| [{{site.data.keyword.vmwaresolutions_short}}](/docs/services/vmwaresolutions?topic=vmware-solutions-getting-started#getting-started) | Quickly and seamlessly integrate or migrate on-premises VMware workloads by using scalable, secure, and high-performance infrastructure and the industry-leading VMware hybrid virtualization technology. |
| [{{site.data.keyword.containerlong_notm}}](/docs/containers?topic=containers-container_index) | Combines Docker containers, the Kubernetes technology, an intuitive user experience, and built-in security and isolation to automate the deployment, operation, scaling, and monitoring of containerized apps in a cluster of compute hosts. |
| [{{site.data.keyword.cfee_full_notm}}](/docs/cloud-foundry?topic=cloud-foundry-about) | Instantiate multiple, isolated, enterprise-grade Cloud Foundry platforms on demand. |
| [{{site.data.keyword.openwhisk_short}}](/docs/openwhisk?topic=cloud-functions-getting_started#getting_started) | A Functions-as-a-Service (FaaS) programming platform based on Apache OpenWhisk. |
{: caption="Table 1. Compute options" caption-side="top"}
   
### Storage
{: #storage}

{{site.data.keyword.baremetal_short}} and {{site.data.keyword.BluVirtServers_short}} are provisioned with default storage. {{site.data.keyword.baremetal_short}} have a minimum of 1 TB SATA disk space, and {{site.data.keyword.BluVirtServers_short}} have a minimum of 25 GB SAN storage. The exception to this is the {{site.data.keyword.cloud_notm}} SAP-Certified {{site.data.keyword.baremetal_short}}. For more information on the default storage available with these servers, see [{{site.data.keyword.cloud_notm}} SAP-Certified Infrastructure](/docs/bare-metal?topic=bare-metal-sap-cert-infrastructure#sap-cert-infrastructure).

You can buy extra storage based on your needs. See the following table for a summary of your compute options.

| Option | Description |
|--------|---------------|
| [{{site.data.keyword.blockstorageshort}}](/docs/infrastructure/BlockStorage/index.html) | Persistent, high-performance iSCSI storage that is provisioned and managed independently of compute instances. iSCSI-based Block Storage LUNs are connected to authorized devices through redundant multi-path I/O (MPIO) connections. |
| [{{site.data.keyword.filestorage_short}}](/docs/infrastructure/FileStorage/index.html) | Persistent, fast, and flexible network-attached, NFS-based File Storage. In this network-attached storage (NAS) environment, you have total control over your file shares function and performance. File Storage shares can be connected to up to 64 authorized devices over routed TCP/IP connections for resiliency. |
| [{{site.data.keyword.cos_full_notm}}](/docs/services/cloud-object-storage?topic=cloud-object-storage-about-ibm-cloud-object-storage#about-ibm-cloud-object-storage) | Information stored with IBM Cloud Object Storage is encrypted and dispersed across multiple geographic locations, and accessed over HTTP by using a REST API. This service makes use of the distributed storage technologies that are provided by the IBM Cloud Object Storage System (formerly Cleversafe). |
| [{{site.data.keyword.cloud_notm}} Master Data Management](/docs/services/MDMOnCloud?topic=MDMOnCloud-mdmoc_getting_started#mdmoc_getting_started) | Offload large amounts of data from your on-premises data center to your Cloud Object Storage bucket. |
| [{{site.data.keyword.backup_full}}](/docs/infrastructure/Backup/index.html) | An automated agent-based backup system that is managed through a browser-based management utility. You can back up data between servers in one or more data centers on the IBM Cloud network. |
{: caption="Table 2. Storage options" caption-side="top"}

### Networking
{: #network}

You automatically get connectivity to the {{site.data.keyword.vpn_full}} when your {{site.data.keyword.cloud_notm}} account is set up. By default, your server has a public IP address and a private IP address. If you want your server to be private, you can either turn off the public interface after your server is provisioned or order your server as private. See [Getting started with Virtual Private Networking](/docs/infrastructure/iaas-vpn?topic=VPN-gettingstarted-with-virtual-private-networking) for more information.

Check out the following table for a summary of your networking options.

| Option | Description | 
|--------|---------------|
| [Content Delivery Network](/docs/infrastructure/CDN?topic=CDN-getting-started) | Used for various industry solutions, including media, entertainment, software, gaming, banking, and e-commerce, to meet the needs of your businesses. |
| [Domain Name Service](/docs/cli/reference/ibmcloud?topic=cloud-cli-ibm-dev-tools-for-jetbrains) | Provides a central location to view and manage your domains through the basic DNS management interface, and also gives you the option to manage reverse and secondary DNS in the same location for free of charge. |
| [Global IP addresses](/docs/infrastructure/subnets?topic=subnets-about-global-ip-address#about-global-ip-address) | Provide flexibility and enable you to shift workloads between servers, even across geographically disparate data centers. |
| [Load balancing](/docs/infrastructure/loadbalancer-service?topic=loadbalancer-service-getting-started-with-ibm-cloud-load-balancer) | Distributes processing and communications evenly across multiple servers within a data center so that a single device does not carry an entire load. |
| [Virtual Router Appliance](/docs/infrastructure/virtual-router-appliance/getting-started.html) | Selectively routes private and public network traffic through a full-featured enterprise router with firewall, traffic shaping, policy-based routing, VPN, and a host of other features. |
| [IPSec VPN](/docs/infrastructure/iaas-vpn?topic=VPN-setup-ipsec-vpn#setup-ipsec-vpn) | A suite of protocols designed to authenticate and encrypt all IP traffic between two locations by using a tunnel mode that provides an encrypted site-to-site network. |
| [{{site.data.keyword.cloud_notm}} Direct Link](/docs/infrastructure/direct-link?topic=direct-link-get-started-with-ibm-cloud-direct-link#get-started-with-ibm-cloud-direct-link) | Leverages a Cloud Exchange provider to deliver connectivity to {{site.data.keyword.cloud_notm}} infrastructure locations. |
{: caption="Table 3. Networking options" caption-side="top"}


## Managing your infrastructure
{: #managing}

After you build your infrastructure and environment, you're ready to start managing it.

| Task | Description |
|--------|---------------|
| [Monitor system events](/docs/account?topic=account-audit-log) | View the actions that have been performed on your infrastructure resources. |
| [Set email preferences](/docs/account?topic=account-email-prefs) | Set up {{site.data.keyword.cloud_notm}} infrastructure email notifications about unplanned events, maintenance, and announcements.  |
| [Understand how your data is safe](/docs/overview?topic=overview-security) | The {{site.data.keyword.cloud_notm}} platform has layered security controls across network and infrastructure. |
| [Understand how you can ensure zero downtime](/docs/overview?topic=overview-zero-downtime) | All {{site.data.keyword.cloud_notm}} resources are hosted in data center locations around the world. |
{: caption="Table 4. Management tasks" caption-side="top"}

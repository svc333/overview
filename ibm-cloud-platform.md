---


copyright:
  years: 2016, 2018
lastupdated: "2018-11-30"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# What is the {{site.data.keyword.Bluemix_notm}} platform?
{: #whatis}

IBM's cloud platform combines platform as a service (PaaS) with infrastructure as a service (IaaS) to provide an integrated experience. The platform scales and supports both small development teams and organizations, and large enterprise businesses. Globally deployed across data centers around the world, the solution you build on {{site.data.keyword.cloud}} spins up fast and performs reliably in a tested and supported environment you can trust.
{: .shortdesc}

The {{site.data.keyword.Bluemix_notm}} platform is composed of multiple components that work together to provide a consistent and dependable cloud experience. 

  * A catalog that consists of hundreds of {{site.data.keyword.Bluemix_notm}} offerings
  * A robust console that serves as the front end for creating, viewing, managing your cloud resources
  * An identity and access management component that securely authenticates users for both platform services and controls access to resources consistently across {{site.data.keyword.Bluemix_notm}}
  * A search and tagging mechanism for filtering and identifying your resources
  * An account and billing management system that provides exact usage for pricing plans and secure credit card fraud protection

## Choosing your hosting environment
{: #choose-compute}

With {{site.data.keyword.Bluemix_notm}}, you no longer need to make large investments in hardware to test out or run a new app. Instead, we manage it all for you and only charge for what you use. Your cloud server environment is the base of your infrastructure layer. You can choose a single option or a combination for more complex environments. 

You have various options for hosting your apps, giving you as much control over the infrastructure as you want or need. You can run your app in any of the following ways:

  * As a serverless function
  * As a Cloud Foundry app
  * As a Docker container on a Kubernetes cluster
  * As VMware
  * As a virtual machine
  * On high-performance {{site.data.keyword.baremetal_short}} 

{{site.data.keyword.baremetal_short}} are single-tenant, physical servers that are dedicated to a single customer. You control almost everything from the server host to the RAM and storage devices. These servers are used with workloads that require compute power over a sustained time, for example, several months. 

{{site.data.keyword.BluVirtServers_short}} can be deployed as either as public or dedicated instances. With public instances, the resources of the server are shared with other customers, also known as a multi-tenant environment. Private instances dedicate the resources of the physical server to one customer who can have one or more virtual machines on the same server. These servers are ideal for workloads that run for a limited time, for example, a couple of weeks. Some workload examples are development and testing, backup and recovery, and disaster recovery. For more information about server options, see [Bare metal servers vs. virtual servers: Choosing the best option for you](https://www.ibm.com/blogs/bluemix/2018/06/bare-metal-virtual-servers-works/){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon").

Check out the following table for a summary of your compute options.

| Option | Description | 
|--------|---------------|
| [{{site.data.keyword.baremetal_short}}](/docs/bare-metal/about.html)  | Hourly or monthly, single-tenant servers that are dedicated to you and not shared in any part, including server resources, with other customers. |
| [{{site.data.keyword.BluVirtServers_short}}](/docs/vsi/vsi_about.html) | Scalable virtual servers that are purchased with dedicated cores and memory allocations. |
| [{{site.data.keyword.vmwaresolutions_short}}](/docs/services/vmwaresolutions/vmonic/prod_overview.html) | Quickly and seamlessly integrate or migrate on-premises VMware workloads by using scalable, secure, and high-performance infrastructure and the industry-leading VMware hybrid virtualization technology. |
| [{{site.data.keyword.containerlong_notm}}](/docs/containers/cs_why.html) | Combines Docker containers, the Kubernetes technology, an intuitive user experience, and built-in security and isolation to automate the deployment, operation, scaling, and monitoring of containerized apps in a cluster of compute hosts. |
| [{{site.data.keyword.cfee_full_notm}}](/docs/cloud-foundry/index.html) | Instantiate multiple, isolated, enterprise-grade Cloud Foundry platforms on demand. |
| [{{site.data.keyword.openwhisk_short}}](/docs/openwhisk/index.html) | A Functions-as-a-Service (FaaS) programming platform based on Apache OpenWhisk. |
{: caption="Table 1. Compute options" caption-side="top"}

## Building applications
{: #build-apps}

Whether you have [existing code](/docs/apps/tutorials/tutorial_byoc.html) that you want to modernize and bring to the cloud or you're developing a [brand new application](/docs/apps/tutorials/tutorial_starter-kit.html), your developers can tap into the rapidly growing ecosystem of available services and runtime frameworks in {{site.data.keyword.Bluemix_notm}}.

[Programming guides](https://cloud.ibm.com/docs/home/build){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon") are available per language to help you get up and running. You have many options for hosting your apps with {{site.data.keyword.Bluemix_notm}} infrastructure from {{site.data.keyword.baremetal_short}} to running as a serverless function.

## Connecting services
{: #connect-services}

With over 190+ services to choose from in the catalog, you can build a tailored solution to fit your needs. You can also easily connect services to apps outside of {{site.data.keyword.Bluemix_notm}} if that fits your use case. You can generate a new set of credentials for cases in which you want to manually connect an external consumer to an {{site.data.keyword.Bluemix_notm}} service. For example, if you are trying to connect an app outside of {{site.data.keyword.Bluemix_notm}} to a Watson service, you generate a new credential that connects them together. It's that easy! For more information, see [Adding a credential](/docs/resources/service_credentials.html#service_credentials).

## Setting up your account

If you're just trying out {{site.data.keyword.Bluemix_notm}}, you can go straight to the catalog and start checking out the services that you'd like to explore and add to your Trial or Lite account. However, if you're ready to get started with an environment for a group of developers or entire organization and get apps running in production, consider setting up the basics in your account:

* User access groups for organizing users and service IDs into one entity to make assigning access a streamlined process.
* Resource groups for organizing your resources to make assigning access to a set of resources quick and easy.
* Access policies for your access groups or individual developers who need IAM access policies or Cloud Foundry org and space roles.

For more information, see the [best practices for setting up your account](/docs/account/bp_account.html#account_setup) and [best practices for assigning access](/docs/iam/bp_access.html). Also, if you're ready to dive in, check out the pieces and parts of the [account hierarchy](/docs/account/account_overview.html#overview).

## Pricing and billing

Regardless of your account type, you can explore {{site.data.keyword.Bluemix_notm}} by using Lite plans for the services that provide free quota. When you're choosing a service from the catalog and you select a tile, if there are different types of available plans you can see details about pricing information. If you choose a service plan with a paid plan, you can estimate your costs by using the cost estimator tool. For more information, see [Estimating your costs](/docs/billing-usage/estimating_costs.html#cost).

{{site.data.keyword.Bluemix_notm}} billing provides multiple services that ensure the {{site.data.keyword.Bluemix_notm}} platform can securely manage pricing, accounts, usage, and more.

### {{site.data.keyword.Bluemix_notm}} account management
{: #account}

Account management maintains the billing relationship with the customer. Each account is a billing entity that represents a customer. This service controls account lifecycle, account subscription, account user relationship, and account organization.

### {{site.data.keyword.Bluemix_notm}} pricing
{: #pricing}

The {{site.data.keyword.Bluemix_notm}} pricing platform service helps users to define, manage, and retrieve price information for resources in the {{site.data.keyword.Bluemix_notm}} catalog.

### {{site.data.keyword.Bluemix_notm}} metering collector
{: #metering}

{{site.data.keyword.Bluemix_notm}} usage metering is a platform service that enables service providers to submit metrics that are collected for resource instances that are provisioned by {{site.data.keyword.Bluemix_notm}} users. Third-party service providers that deliver an Integrated billing service in {{site.data.keyword.Bluemix_notm}} are required to submit usage for all active service instances every hour. Submission is important because inability to report usage can lead to loss of revenue collection for IBM, in turn causing loss of revenue share for the third-party service provider.

## {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM)
{: #iam}

{{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) enables you to securely authenticate users for both platform services and control access to resources consistently across the {{site.data.keyword.Bluemix_notm}} platform. For more details, see [What is IAM?](/docs/iam/index.html) IAM provides CLI commands and APIs that help you manage your tokens, access groups, and policies.


## Creating resources
{: #provisioning-layer}

The resource controller is the next-generation {{site.data.keyword.Bluemix_notm}} platform provisioning layer that manages the lifecycle of {{site.data.keyword.Bluemix_notm}} resources in a customer account. Resources are provisioned globally in an account scope. The resource controller supports both synchronous and asynchronous provisioning of resources. The provisioning layer is responsible for controlling and tracking the lifecycle of resources in a customer account. Resources are physical or logical components that can be provisioned or reserved for an application or service instance. Examples of resources include databases, accounts, processors, memory, and storage limits. In general, resources that are tracked by the provisioning layer are intended to associate usage metrics and billing, but that isn’t always the case. In some cases, the resource might be associated to the provisioning layer to ensure that the resource lifecycle can be managed along with the account lifecycle. The resource controller uses IAM for authentication and authorization of actions that are taken against the provisioning layer.

### Resource lifecycle management
{: #lifecycle}

The resource controller provides common APIs to control the lifecycle of resources from provisioning (creating an instance) to binding (creating access credentials) to unbinding (removing access) to de-provisioning (deleting an instance).

The resource controller provides APIs to help you manage the following elements of your resource lifecycle:
* Provisioning
* Updating a resource instance
* Binding
* Resource keys
* Unbinding
* De-provisioning


## Managing your resources
{: #resource-manager}


{{site.data.keyword.Bluemix_notm}} resource manager manages the collection of resources by [resource groups](/docs/overview/resource-groups.html#whatis). A resource group belongs to an account. All {{site.data.keyword.Bluemix_notm}} resources must be provisioned within a resource group. If an account is suspended, the corresponding resource group is suspended as well, and all resources within the resource group are suspended. When a user creates an account, a default resource group is created in the account. All {{site.data.keyword.Bluemix_notm}} IAM-enabled resources must be provisioned within a resource group. If an account is suspended, the corresponding resource group is suspended as well, and all resources within the resource group are suspended. For standard account, a user can have only one resource group. For a Pay-As-You-Go or Subscription account, a user is allowed to create more than one resource group. 


## {{site.data.keyword.Bluemix_notm}} catalog
{: #catalog}

The {{site.data.keyword.Bluemix_notm}} catalog stores the offering definitions (description, features, images, URLs, and so on) of the resources that are displayed in the {{site.data.keyword.Bluemix_notm}} console. The catalog service manages offerings across geographies as the system of record. The catalog supports CLIs and a RESTful API where you can retrieve information about existing offerings and create, manage, and delete their offerings. Start with the base URL and use the endpoints to retrieve metadata about services in the catalog and manage service visibility. Depending on the kind of object, the metadata can include information about pricing, provisioning, regions, and more. For more information, see the [Managing the catalog documentation](/docs/overview/catalog.html#global-catalog-overview).

## Searching and tagging resources
{: #search-and-tag}

The search service is a global and shared resource properties repository that is integrated within the {{site.data.keyword.Bluemix_notm}} platform. It is used for storing and searching cloud resource's attributes. It categorizes and classifies resources. A resource is controlled and owned by resource providers within the {{site.data.keyword.Bluemix_notm}} platform, such as Cloud Foundry, IBM Containers, or Resource Controller. Resources are uniquely identified by a [Cloud Resource Name](/docs/overview/crn.html#crn) identifier (CRN). The properties of a resource include tags and system properties. Both properties are defined within an {{site.data.keyword.Bluemix_notm}} billing account, and span across many regions.

This service also manages tags that are associated with a resource. You can create, delete, search, attach, or detach tags with the Tagging API. Tags are uniquely identified by a Cloud Resource Naming (CRN) identifier. Tags have a name, which must be unique within a billing account. You can make tags in `key:value` or label format.


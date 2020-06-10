---

copyright:
  years: 2018, 2020
lastupdated: "2020-04-22"

keywords: load balancing, global load balancing, HA, DR, high availability, disaster recovery, HA for the platform, high availability for platform, disaster recovery plan, disaster event, zero downtime, workloads, failover, failover design

subcollection: overview

---

{:shortdesc: .shortdesc}
{:tip: .tip}
{:note: .note}


{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:pre: .pre}
{:table: .aria-labeledby="caption"}
{:note: .note}
{:term: .term}

# How does IBM Cloud ensure near zero downtime?
{: #zero-downtime}

Your global strategy is important, and {{site.data.keyword.cloud}} uses global load balancing to ensure a redundant, highly available platform is available for you to host your workloads and applications.
{:shortdesc} 

## High availability for the platform
{: #platform-ha}

The {{site.data.keyword.cloud_notm}} console is available globally and load balanced from a single URL. It is highly available and continues to run even if your resources are unavailable. 

Platform services, such as account management, catalog, identity and access management, and more, are also globally available and load balanced across multiple regions. This means that there is a failover design in place to keep your resources up and running without you having to take any action. Each platform service is categorized as a general availability service with a [Service Level Agreement](/docs/overview?topic=overview-slas) of 99.99% availability. While each platform service might be available from various regions, each region in which the service is deployed has multiple data centers for redundancy.

| Platform Service | Details |
|------------------|----------------|
| Console | [Navigating the console](/docs/overview?topic=overview-ui) |
| Catalogs    |    [Working with the IBM Cloud catalog and your private catalogs](/docs/account?topic=account-manage-catalog)               |
|      Global search and tagging         |    [Searching for resources](/docs/resources?topic=resources-searching-for-resources) and [Working with tags](/docs/resources?topic=resources-tag)        |
|        IAM       |      [Getting started with IAM](/docs/iam?topic=iam-getstarted)             |
|  Account management  |    [Best practices for setting up your account](/docs/account?topic=account-account_setup) and [Best practices for billing and usage](/docs/billing-usage?topic=billing-usage-best-practices)     |
{: caption="Table 1. Platform services" caption-side="top"}

## High availability for services and infrastructure
{: #services-ha}

High availability and disaster recovery aren't universal across all resources, so the type of high availability and disaster recovery that's available depends on the resource that you're using. All {{site.data.keyword.Bluemix_notm}} resources are hosted in data center locations around the world. The locations that you deploy your app to can spread workloads across data centers, and you can ensure that a failover design is in place to keep your app up and running. 

As an {{site.data.keyword.IBM_notm}} classic infrastructure (non-VPC) customer, you can order bare metal or virtual server instances (VSI) and can deploy to over 60 data centers that are located around the world in addition to several multizone regions (MZR) with multiple availability zones. Whether the data centers are MZRs or not, all of them maintain multiple power feeds, fiber links, dedicated generators, and battery backup to avoid a single-point-of-failure (SPOF) between zones and regions. 

Even though all the data centers have multiple power feeds, several of the more mature sites, such as AMS01, DAL05, 06, 08. FRA02. HKG02, MEX01, MIL01, PAR01,SJC01, SNG01, WDC01, and WDC03, have some 1U single socket server chassis that might not accommodate a dual power feed. If you have a 1U single socket server in one of these sites, you might want to consider a 2U chassis with redundant power supplies.

For more information about the specific options for deploying your workloads, see [locations for resource deployment](/docs/overview?topic=overview-locations).

For more information about particular high availability and disaster recovery practices specific to each service or infrastructure option, refer the documentation for that service.
{: tip}

## Disaster recovery
{: #disaster-recovery}

Disaster recovery is about surviving a catastrophic failure or loss of availability in a single location. For the console and platform services, there are no actions that you need to take to prepare for an event of a catastrophic failure in a region.

### Disaster recovery plan 
{: #dr-plan}

{{site.data.keyword.Bluemix_notm}} follows best practices for disaster recovery. All {{site.data.keyword.Bluemix_notm}} applications automatically recover and restart after any disaster event. Recovery is from electronic backups at a recovery center or alternative computing facilities that restore computing. Before any potential disaster, the disaster recovery plan includes the systems and hosting requirements for hardware, software, networking connectivity, and offsite backup capabilities.

The following list includes the requirements that {{site.data.keyword.IBM_notm}} adheres to for a disaster recovery plan:

- A design document explains how load balancing is used to keep a service highly available.
- Where multi-site failover occurs, the disaster recovery plan must explain who does what to cause the failover and ensure restart. 
- The disaster recovery plan must define how the solution works and include restore point objectives that clearly explain how much data might be lost in the outage, if any. The disaster recovery plan also includes a detailed recovery workflow for restoring services and data if a multi-availability zone failure. 
- It must confirm how the Maximum Tolerable Downtime is met and be stored on the Disaster Recovery Plan database.  
- The disaster recovery plan specifies the security controls for running in Disaster mode, if they are different from what's running in production. 

### Management of the disaster recovery plan 
{: #dr-plan-mgmt}

The requirements that {{site.data.keyword.Bluemix_notm}} follows are: 

- The disaster recovery plan must be updated after any major infrastructure change, major application release, and after any test. 
- It must be approved annually. 








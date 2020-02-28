---

copyright:
  years: 2018, 2020
lastupdated: "2020-02-28"

keywords: data center, data centers, data center locations, specific data center, individual data centers, load balancing, global load balancing, availability zones, HA, DR, high availability, disaster recovery, disaster recovery plan, disaster event, locations, data centers, zero downtime, resources, workloads, failover, failover design, infrastructure resources, offsite backup capabilities, alternative computing facilities, ibm cloud regions

subcollection: overview

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:pre: .pre}
{:table: .aria-labeledby="caption"}
{:note: .note}

# How do I ensure zero downtime?
{: #zero-downtime}

Your global strategy is important. You can select a specific data center or location to deploy your data for your customers. All {{site.data.keyword.Bluemix_notm}} resources are hosted in data center locations around the world. The locations that you deploy your app to can spread workloads across data centers, and you can ensure that a failover design is in place to keep your app up and running. For your infrastructure resources, you can select individual data centers to deploy resources.
{:shortdesc}

High availability and disaster recovery aren't universal across all services, so the type of high availability and disaster recovery that's available depends on the service that you're using.


## Disaster recovery
{: #disaster-recovery}

Disaster recovery is about surviving a catastrophic failure or loss of availability in a single location. To ensure that disaster recovery is in place, it's necessary to deploy several {{site.data.keyword.Bluemix_notm}} resources in multiple locations to avoid single points of failure.

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

The requirements that {{site.data.keyword.Bluemix}} follows are: 

- The disaster recovery plan must be updated after any major infrastructure change, major application release, and after any test. 
- It must be approved annually. 

---

copyright:
  years: 2018, 2020
lastupdated: "2020-01-09"

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

Your global strategy is important. You can select a specific data center or location to deploy your data for your customers. All {{site.data.keyword.Bluemix_notm}} resources are hosted in data center locations around the world. The locations that you deploy your app can spread workloads across data centers, and you can ensure that a failover design is in place to keep your app up and running. For your infrastructure resources, you can select individual data centers to deploy resources.
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


## Locations for resource deployment 
{: #ov_intro_reg}

You can create apps and service instances in different locations for the same usage details view for billing. You can deploy your apps to the location that is nearest to your customers to achieve low application latency. 

To address security issues, you can also select the location in which you want to keep application data. When you build apps in more than one location, if one location is unavailable, the apps that are in the other locations continue to run. For more information about the platform resources and the locations they're available in, see [Service availability](/docs/resources?topic=resources-services_region).

Global load balancing for the {{site.data.keyword.cloud_notm}} console ensures that if the nearest geographical location for you is unavailable, the console displays the information for the next closest location. This means, the {{site.data.keyword.Bluemix_notm}} console is highly available and continues to run even if the customer’s apps or service instances might be unavailable.

You can view all resources across all locations by default from the resource list view in the console. If you want to view and work with resources in a specific location, expand the **Location** menu, and select a location from the list. By expanding a specific geographical location, you can select to filter by individual data centers, regions, or zone.

<!-- diagram for availability zones
explanation for diagram
- 3 AZ (availability zones) to separate failure domains per MZR (multi-zone region)
- each AZ is a separate physical data center building
- These data centers have high bandwidth, low latency redundant links with dual POPs.
- Zones are to be built less than 2msex fiber distance from one another in a region --->

![Location hierarchy that shows a geography that contains a metro that contains data centers and regions with zones](images/Location_hierarchy.svg){: caption="Figure 1. Location options hierarchy" caption-side="bottom"}

For example, if you have resources that are deployed in the London 2 (eu-gb-2) zone, you can filter your resource list to display only those resources. A zone is located within a region and a region is organized by its metro location. To filter your list to the London 2 (eu-gb-2) zone, expand the **London** metro option, and then expand the **London (eu-gb)** region option. Within that region, you can select from the list of available zones. If you have a resource that is deployed in a specific data center, you can identify the data center by the specific metro location and alphanumeric code, for example, London 02 (lon02).

You might also have resources that are located globally. The **Global** option means that only one logical, globally accessible instance of the service, independent of any region or zone, is published to customer applications. These types of resources are accessible from a global endpoint.

## Data centers
{: #data_center}

When you deploy infrastructure resources, you have more options about where your data is located. You can select a location, or you can select from a list of the {{site.data.keyword.Bluemix_notm}} data centers. A *data center* is the physical location that hosts the power, cooling, compute, network, and storage resources used for services and apps. Data centers don't provide isolation from multi zones in a location. For more information, see [Global locations for your global business ![External link icon](../icons/launch-glyph.svg "External link icon")](https://www.ibm.com/cloud/data-centers/){: new_window}.

{{site.data.keyword.Bluemix_notm}} offers data centers in many locations across the world. 


![Map of available data centers](images/Global-View.svg){: caption="Figure 2. Data center locations" caption-side="bottom"}


See the following table for the specific code for each data center. 

| Data Center | Code  |
|------------------|-------|
| Dallas 01        | dal01 |
| Dallas 05        | dal05 |
| Dallas 06        | dal06 |
| Dallas 07        | dal07 |
| Dallas 09        | dal09 |
| Dallas 10        | dal10 |
| Dallas 12        | dal12 |
| Dallas 13        | dal13 |
| Houston 01       | hou01 |
| Mexico 01        | mex01 |
| Montreal 01      | mon01 |
| San Jose 01      | sjc01 |
| San Jose 03      | sjc03 |
| San Jose 04      | sjc04 |
| Sao Paulo 01     | sao01 |
| Seattle 01       | sea01 |
| Toronto 01       | tor01 |
| Washington DC 01 | wdc01 |
| Washington DC 04 | wdc04 |
| Washington DC 06 | wdc06 |
| Washington DC 07 | wdc07 |
{: caption="Table 1. Data centers in North and South America" caption-side="top"}
{: #americas}
{: tab-title="Americas"}
{: tab-group="dcs"}
{: class="simple-tab-table"}
{: summary="Use the buttons before the table to change the context of the table. The column headers identify the data centers located in the specific geographical area."}

| Data Center | Code  |
|------------------|-------|
| Amsterdam 01     | ams01 |
| Amsterdam 03     | ams03 |
| Frankfurt 02     | fra02 |
| Frankfurt 04     | fra04 |
| Frankfurt 05     | fra05 |
| London 02        | lon02 |
| London 04        | lon04 |
| London 05        | lon05 |
| London 06        | lon06 |
| Milan 01         | mil01 |
| Oslo 01          | osl01 |
| Paris 01         | par01 |
{: caption="Table 1. Data centers in Europe" caption-side="top"}
{: #europe}
{: tab-title="Europe"}
{: tab-group="dcs"}
{: class="simple-tab-table"}
{: summary="Use the buttons before the table to change the context of the table. The column headers identify the data centers located in the specific geographical area."}

| Data Center | Code  |
|------------------|-------|
| Hong Kong 02     | hkg02 |
| Melbourne 01     | mel01 |
| Seoul 01         | seo01 |
| Singapore 01     | sng01 |
| Sydney 01        | syd01 |
| Sydney 04        | syd04 |
| Sydney 05        | syd05 |
| Tokyo 01         | tok02 | 
| Tokyo 04         | tok04 |
| Tokyo 05         | tok05 |
{: caption="Table 1. Data centers in Asia Pacific" caption-side="top"}
{: #asiapacific}
{: tab-title="Asia Pacific"}
{: tab-group="dcs"}
{: class="simple-tab-table"}
{: summary="Use the buttons before the table to change the context of the table. The column headers identify the data centers located in the specific geographical area."}

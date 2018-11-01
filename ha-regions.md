---

copyright:

  years: 2018

lastupdated: "2018-11-01"

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:pre: .pre}
{:tip: .tip}

# Locations for resource deployment 
{: #ov_intro_reg}

You can create apps and service instances in different locations with the same {{site.data.keyword.cloud_notm}} infrastructure for application management and the same usage details view for billing. You can deploy your apps to the location that is nearest to your customers to get low application latency. 

To address security issues, you can also select the location where you want to keep the application data. When you build apps in more than one location, if one location becomes unavailable, the apps that are in the other locations continue to run. Your resource allowance is the same for each location that you use. For more information about the platform resources and the locations they're available in, see [Service availability](/docs/resources/service_region.html).

Global load balancing for the console ensures that if the nearest geographical location for you is down, the console displays the information for the next closest location. This way, you can always access the console without taking any action to access the information you need.

<!---This is a pre-pup topic. Post pup, the dashboard will have a Location status widget, which will show geographies as a summary. This paragraph will change and we need to add a paragraph to explain the continents are a summary in the widget.-->
From the dashboard, you can view all resources across all locations by default. If you want to view and work with resources in a specific location, expand the **LOCATION** menu, and select a location from the list. 

You can also use the command line interface to connect to the {{site.data.keyword.cloud_notm}} location that you want to work with by using the `ibmcloud api` command and specify the API endpoint of the location. For example, enter the following command to connect to {{site.data.keyword.cloud_notm}} London:

```
ibmcloud api https://api.eu-gb.bluemix.net
```

A unique prefix is assigned to each location. {{site.data.keyword.cloud_notm}} provides the following locations and location prefixes.

| **Location** | **API endpoint** |
|-----------------|-------------------|
| Dallas | api.us-south.bluemix.net |
| Sydney | api.au-syd.bluemix.net |
| Frankfurt | api.eu-de.bluemix.net |
| London | api.eu-gb.bluemix.net |
| Washington DC | api.us-east.bluemix.net |
{: caption="Table 1. {{site.data.keyword.cloud_notm}} location list" caption-side="top"}

When you deploy infrastructure resources, you have more choice about where your content is located. You can select a location, or you can select from a list of the data centers in {{site.data.keyword.Bluemix_notm}}. For more information, see [{{site.data.keyword.cloud_notm}} data centers](data-centers.html)

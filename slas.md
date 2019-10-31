---

copyright:
  years: 2019
lastupdated: "2019-10-31"

keywords: service level agreements, SLA, slas

subcollection: overview

---

{:shortdesc: .shortdesc}
{:tip: .tip}
{:note: .note}
{:new_window: target="_blank"}


# Service Level Agreements (SLAs)
{: #slas} 

{{site.data.keyword.Bluemix}} provides a 99.99% availability service level for multiple instances of a platform service within a public environment.
{: shortdesc}

{{site.data.keyword.Bluemix_notm}} provides SLAs for {{site.data.keyword.Bluemix_notm}} services that might make you eligible for credits toward your account. SLAs are your only way to resolve {{site.data.keyword.Bluemix_notm}}'s failure to meet a specified service level. 

The complete Service Description for {{site.data.keyword.Bluemix_notm}} is available at [Cloud Services terms](http://www-03.ibm.com/software/sla/sladb.nsf/sla/bm){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon").

## Availability SLA 
{: #avail-downtime}

You're eligible for a credit toward your account if you experience availability less than the 99.99%. Availability downtime is the total minutes you're unable to connect to any of your service instances. Total downtime minutes start when you can prove a loss of availability with logs or any other records.

{{site.data.keyword.Bluemix_notm}} provides a 99.99% availability SLA: 

| Type	                                     | Description	      | Support Details|
|--------------------------------------------|--------------------|----------------|
| High availability for a public environment | Other Environments | Credit         |
| <99.99%                                    |<99.9%              |10%             |
| <99.9%                                    |<99.0%              |25%             |
{: caption="Table 1. Monthly availability service level" caption-side="top"}

Availability percentage is calculated as the total number of minutes that are in a contracted month, minus the total number of downtime minutes in that month divided by the total number of minutes in that month. 

For example, in a 31-day month, you have 44,640 total number of minutes. If you experience six hours of availability downtime, there are 360 downtime minutes. With only six hours of downtime, you have 99.19% availability. Since 99.19% is less than 99.90%, you're eligible for a 25% credit with a public environment.   

```
= (44,640 total minutes in month - 360 downtime minutes) / 44,640 total minutes in month
= (44,280 actual minutes available) / 44,640 total minutes in month
= 99.19% availability
```

SLAs don't include downtime or failures that are related to {{site.data.keyword.Bluemix_notm}} UI unavailability, or the time it takes to reload, configure, enable, or access content.

## Infrastructure hardware replacement and upgrade SLA
{: #hw-replaceupgrade-sla}

{{site.data.keyword.Bluemix_notm}} tries to minimize downtime when failed hardware is replaced and when scheduled upgrades are performed. 

{{site.data.keyword.Bluemix_notm}} provides credit for: 
- Hardware replacement based on the time to replace from the time {{site.data.keyword.Bluemix_notm}} verifies that a customer reported hardware failure.
- Planned hardware upgrades based on the total downtime of the service that receives the upgrade. 

Service level time periods exclude anytime that is required to reload the operating system or applications or the time performance might be degraded. You're eligible for a credit based on the monthly charge for the service that is affected by the hardware replacement or upgrade if {{site.data.keyword.Bluemix_notm}} fails to meet a specified service level time period.

| Service Level Time Period | Credit Percentage |
|---------------------------|----------------|
| ≤ 2 hours                 | None           |
| > 2 hours                 | 20%            |
| > 6 hours                 | 40%            |
| > 10 hours                | 60%            |
| > 14 hours                | 80%            |
| > 18 hours                | 80%            |
{: caption="Table 2. Credit based on the monthly charge for the service that is affected by the hardware replacement or upgrade" caption-side="top"}

## Claims
{: #claims}

To submit a claim for downtime, [create a support case](https://cloud.ibm.com/unifiedsupport/cases/add){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon"). Title your case `SLA credit request`, and provide sufficient information to identify the affected service, error messages, and other information necessary to validate the claim.

Submit your claim within 60 days of the end of the contracted month that the service level was missed.  

The credit is the highest applicable compensation based on the cumulative availability of the affected service during a contracted month and calculated by using the monthly charges for such affected service. Credits cannot exceed 25% of monthly charge.

## Exclusions
{: #exclusions}

No credits are given for failure to meet an SLA because of:
- Problems with Customer or community provided content, technology, designs, or instructions
- Beta, experimental, or no-charge Cloud services.
- Non-IBM build-packs
- Unsupported system configurations and platforms
- Customer infrastructure failures, including network, hardware, facility, or power
- Customer system administration actions, commands, or file transfers
- Customer errors or failures to provide needed information or access to resolve an outage
- Customer-caused security incidents or security testing
- Other causes beyond IBM's reasonable control

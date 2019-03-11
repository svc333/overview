---

copyright:
  years: 2017, 2019
lastupdated: "2019-03-11"

---

{:shortdesc: .shortdesc}

# How do I know that my data is safe?
{: #security}

Designed with secure engineering practices, the {{site.data.keyword.cloud}} platform has layered security controls across network and infrastructure. {{site.data.keyword.cloud_notm}} provides a group of security services that can be used by application developers to secure their mobile and web apps. These elements combine to make {{site.data.keyword.cloud_notm}} a platform with clear choices for secure application development.
{:shortdesc}

{{site.data.keyword.cloud_notm}} ensures security readiness by adhering to security policies that are driven by best practices in IBM for systems, networking, and secure engineering. These policies include practices such as source code scanning, dynamic scanning, threat modeling, and penetration testing. {{site.data.keyword.cloud_notm}} follows the IBM Product Security Incident Response Team (PSIRT) process for security incident management. See the [IBM Security Vulnerability Management (PSIRT) ![External link icon](../icons/launch-glyph.svg "External link icon")](https://www.ibm.com/security/secure-engineering/process.html){: new_window} site for details.

{{site.data.keyword.cloud_notm}} Public and Dedicated use classic infrastructure-as-a-service (IaaS) cloud services and take full advantage of its security architecture. Classic IaaS provides multiple, overlapping tiers of protection for your applications and data. For {{site.data.keyword.cloud_notm}} Local, you own the physical security, and provide the infrastructure by hosting {{site.data.keyword.cloud_notm}} Local in your own data center behind a company firewall. In addition, {{site.data.keyword.cloud_notm}} adds security capabilities at the platform as a service (PaaS) layer in different categories: platform, data, and application. For further security details on your environment and apps in the {{site.data.keyword.Bluemix_notm}}, see [Securing applications and environments on cloud ![External link icon](../icons/launch-glyph.svg "External link icon")](https://www.ibm.com/cloud/garage/architectures/securityArchitecture){: new_window}.

## {{site.data.keyword.Bluemix_notm}} compliance
{: #compliance}

{{site.data.keyword.Bluemix_notm}} provides a secure cloud platform that you can trust. {{site.data.keyword.Bluemix_notm}} compliance results from a platform and services that are built on best-in-industry security standards, including ISO 27001 and ISO 27002. For more information, see [Compliance on the {{site.data.keyword.cloud_notm}}](https://www.ibm.com/cloud/compliance){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon").

## Platform and service compliance
{: #compliancetable}

The following table displays which services in {{site.data.keyword.Bluemix_notm}} are compliant for each of the standards.

|{{site.data.keyword.Bluemix_notm}} components		|FISC		|ISO 27001	|PCI |SOC 2 Type 1		|
|:----------------------|:---------:|:---------:|:---------:|:---------:|
|{{site.data.keyword.Bluemix_notm}} platform		|Y			|Y	|Y	|Y	|
|{{site.data.keyword.openwhisk_short}}    |  |Y | | |
|{{site.data.keyword.APIM}}			|Y	|Y |Y	|			|
|{{site.data.keyword.autoscaling}}			|Y	|Y |Y	|			|
|{{site.data.keyword.bigicloudst}}			|Y |Y |	|Y |
|{{site.data.keyword.cloudant}}				|Y |Y |	|Y	|
|{{site.data.keyword.dashdbshort}}			|Y	|Y	|	|Y	|
|{{site.data.keyword.dataworks_short}}				|	|	|	|Y	 		|
|{{site.data.keyword.contdelivery_short}}					|Y	|Y	|	|			|
|{{site.data.keyword.containerlong}}			|Y		|Y	|	|		Y	|
|{{site.data.keyword.dwl_short}}				|	|	|	|Y	 		|
|{{site.data.keyword.mql}}				|Y	|Y	|Y	|	 		|
|{{site.data.keyword.SecureGateway}}			|Y	|Y |	|	 		|
{: caption="Table 1. Platform and service compliance" caption-side="top"}

## General Data Protection Regulation (GDPR)
{: #gdpr}

The GDPR seeks to create a harmonized data protection law framework across the EU and aims to give citizens back the control of their personal data, while imposing strict rules on those hosting and processing this data, anywhere in the world. 

{{site.data.keyword.IBM_notm}} is committed to providing our clients and {{site.data.keyword.IBM_notm}} Business Partners with innovative data privacy, security, and governance solutions to assist them in their journey to GDPR readiness. Data and its protection are becoming increasingly important to individuals and society. Enterprises must earn the client’s trust in their ability to steward information. 

{{site.data.keyword.Bluemix_notm}} is agile and scalable with built-in data security, and privacy services and solutions that can be consumed on premises or through public cloud. Our comprehensive data security platform helps safeguard sensitive data wherever it resides and provides a full range of data protection capabilities.

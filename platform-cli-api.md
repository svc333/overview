---

copyright:

  years: 2018, 2019

lastupdated: "2019-02-19"

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:pre: .pre}
{:tip: .tip}

# {{site.data.keyword.Bluemix_notm}} platform service CLIs and APIs
{: #platform-svc-cli-api}

The {{site.data.keyword.cloud}} platform is composed of multiple components that work together to provide you with a consistent cloud experience.
{: shortdesc}

Use the following table to get an at-a-glance view of the command-line interface (CLI) commands and API documents that are associated with each platform component.

<!-- Below is a PRODUCTION table  with only 3 columns -->

| Platform Component | CLI Reference | API Docs |
| ----- | ----- | ----- |
| {{site.data.keyword.cloud_notm}} Identity and Access Management (IAM) | [Managing IAM access, API keys, service IDs, and access groups](docs/cli/reference/ibmcloud?topic=cloud-cli-ibmcloud_commands_iam) | [IAM Identity Services API](https://console.cloud.ibm.com/apidocs/iam-identity-token-api){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon") <br><br>  [IAM Access Groups API](https://console.cloud.ibm.com/apidocs/iam-access-groups){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon") <br><br> [IAM Policy Management API](https://console.cloud.ibm.com/apidocs/iam-policy-management){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon") |
| Account management | [Managing accounts, users, and Cloud Foundry orgs](/docs/cli/reference/ibmcloud?topic=cloud-cli-ibmcloud_commands_account) |  Not available |
| Usage metering | [Viewing usage for accounts, orgs, resource groups, and resources](/docs/cli/reference/ibmcloud?topic=cloud-cli-ibmcloud_billing) |  [{{site.data.keyword.Bluemix_notm}} Usage Metering](https://console.cloud.ibm.com/apidocs/usage-metering){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon") |
| Usage reporting |  [Viewing usage for accounts, orgs, resource groups, and resources](/docs/cli/reference/ibmcloud?topic=cloud-cli-ibmcloud_billing) |  [{{site.data.keyword.Bluemix_notm}} Usage Reports](https://console.cloud.ibm.com/apidocs/metering-reporting){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon") |
| Resource controller | [Working with resources and resource groups](/docs/cli/reference/ibmcloud?topic=cloud-cli-ibmcloud_commands_resource) | [{{site.data.keyword.Bluemix_notm}} Resource Controller API](https://console.cloud.ibm.com/apidocs/resource-controller){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon") <br><br> [{{site.data.keyword.cloud_notm}} Open Service Broker API](https://console.cloud.ibm.com/apidocs/ibm-cloud-osb-api){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon") |
| Resource manager | [Working with resources and resource groups](/docs/cli/reference/ibmcloud?topic=cloud-cli-ibmcloud_commands_resource) | [{{site.data.keyword.Bluemix_notm}} Resource Manager API](https://console.cloud.ibm.com/apidocs/resource-manager){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon") |
| Catalog | [Searching and managing catalog offerings](/docs/cli/reference/ibmcloud?topic=cloud-cli-ibmcloud_catalog) | [Catalog API](https://console.cloud.ibm.com/apidocs/globalcatalog){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon") |
| Search & tagging | [Searching resources](/docs/cli/reference/ibmcloud?topic=cloud-cli-ibmcloud_commands_resource#ibmcloud_resource_search) <br><br>  [Tagging resources](/docs/cli/reference/ibmcloud/cli_resource_group.html#ibmcloud_resource_tags) | Not available |
{: caption="Table 1. Platform services CLI and API" caption-side="top"}


<!-- Below is a staging table with an extra internal column with test urls. DO NOT PROMOTE THIS TO PRODUCTION -->

| Platform component | CLI Reference | Internal-only API Docs | Public API Docs|
| ----- | ----- | ----- | ----- |
| {{site.data.keyword.cloud_notm}} Identity and Access Management | [IAM API Keys, Identity and Access](docs/cli/reference/ibmcloud?topic=cloud-cli-ibmcloud_commands_iam) | [IAM Token Service API](https://console.test.cloud.ibm.com/apidocs/iam-identity-token-api) <br><br>  [IAM Access Groups](https://console.test.cloud.ibm.com/apidocs/iam-access-groups) <br><br> [IAM Token Policy Decision Point](https://console.test.cloud.ibm.com/apidocs/iam-policy-decision-point-api) <br><br> [IAM Token Policy Management](https://console.test.cloud.ibm.com/apidocs/iam-policy-management) | [IAM Identity Services API](https://console.cloud.ibm.com/apidocs/iam-identity-token-api) <br><br>  [IAM Access Groups API](https://console.cloud.ibm.com/apidocs/iam-access-groups) <br><br> [IAM Policy Management API](https://console.cloud.ibm.com/apidocs/iam-policy-management) |
| {{site.data.keyword.cloud_notm}} Billing - Account Management | [Account, Users, and Orgs](/docs/cli/reference/ibmcloud/cli_acct_org_role.html#accounts-users-and-orgs) |  [Account Management](https://console.test.cloud.ibm.com/apidocs/account-management) <br><br> [Unified Account Management](https://console.test.cloud.ibm.com/apidocs/unified-account) |  N/A |
| {{site.data.keyword.cloud_notm}} Billing - Pricing |  N/A  | [Pricing](https://console.test.cloud.ibm.com/apidocs/pricing) v2 coming soon. |   N/A |
| {{site.data.keyword.cloud_notm}} Billing - Metering Collector | [Billing and usage](/docs/cli/reference/ibmcloud?topic=cloud-cli-ibmcloud_billing) |  [Usage Metering](https://console.test.cloud.ibm.com/apidocs/usage-metering) |  [Usage Metering](https://console.cloud.ibm.com/apidocs/usage-metering) |
| {{site.data.keyword.cloud_notm}} Billing -  Usage Reports |  [Usage](/docs/cli/reference/ibmcloud?topic=cloud-cli-ibmcloud_billing) |  [Usage Reports](https://console.test.cloud.ibm.com/apidocs/metering-reporting) | [Usage Reports](https://console.test.cloud.ibm.com/apidocs/metering-reporting) | [Usage Reports](https://console.cloud.ibm.com/apidocs/metering-reporting) |
| {{site.data.keyword.cloud_notm}} Resource Controller| [Managing resources](/docs/cli/reference/ibmcloud?topic=cloud-cli-ibmcloud_commands_resource) | [Resource Controller](https://console.test.cloud.ibm.com/apidocs/resource-controller) <br><br> [{{site.data.keyword.cloud_notm}} Open Service Broker](https://console.test.cloud.ibm.com/apidocs/ibm-cloud-osb-api) | [Resource Controller](https://console.cloud.ibm.com/apidocs/resource-controller) <br><br> [{{site.data.keyword.cloud_notm}} Open Service Broker](https://console.cloud.ibm.com/apidocs/ibm-cloud-osb-api) |
| {{site.data.keyword.cloud_notm}} Resource Manager | [Managing resources](/docs/cli/reference/ibmcloud?topic=cloud-cli-ibmcloud_commands_resource) | [Resource Manager](https://console.test.cloud.ibm.com/apidocs/resource-manager) | [Resource Manager](https://console.cloud.ibm.com/apidocs/resource-manager) |
| {{site.data.keyword.cloud_notm}} Resource Catalog | [Catalog](/docs/cli/reference/ibmcloud?topic=cloud-cli-ibmcloud_catalog) | [Global Resource Catalog](https://console.test.cloud.ibm.com/apidocs/globalcatalog) |  [Global Resource Catalog](https://console.cloud.ibm.com/apidocs/globalcatalog) |
| {{site.data.keyword.cloud_notm}} Global Search & Tagging | [Global Search](/docs/cli/reference/ibmcloud?topic=cloud-cli-ibmcloud_commands_resource#ibmcloud_resource_search) <br><br>  [Global Tagging](/docs/cli/reference/ibmcloud/cli_resource_group.html#ibmcloud_resource_tags) | [Global Search](https://console.test.cloud.ibm.com/apidocs/search) <br><br> [Global Tagging](https://console.test.cloud.ibm.com/apidocs/tagging) |   N/A  |
| {{site.data.keyword.cloud_notm}} Console | Link to CLI - N/A | [Content Workload API](https://console.test.cloud.ibm.com/apidocs/workflow-api) <br><br> [SSL Certificate Management](http://bluemixapi-docs.test.mycloud.ibm.com/swagger/?api=api-server#/default)|  N/A  |
| {{site.data.keyword.cloud_notm}} Status & Notifications| CLI - N/A | API - N/A | API - N/A |
| Observability - LogAnalysis with LogDNA| [Logging Analysis CLI](/services/CloudLogAnalysis/reference/cloudloganalysis-log_analysis_cli) | N/A |  N/A |
| Observability - Monitoring with SysDig| CLI - N/A | API - N/A | API - N/A |
{: caption="Table 1. Platform services CLI and API" caption-side="top"}


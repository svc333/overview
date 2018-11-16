---

copyright:

  years: 2015, 2018

lastupdated: "2018-11-15"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# What's new in {{site.data.keyword.Bluemix_notm}}
{: #whatsnew}

Stay up-to-date with the new features and services that are available in {{site.data.keyword.Bluemix}}, so that you get the most out of your {{site.data.keyword.Bluemix_notm}} experience. The updates are organized into these categories: [{{site.data.keyword.Bluemix_notm}} platform](index.html#platform_category), [{{site.data.keyword.Bluemix_local_notm}} and {{site.data.keyword.Bluemix_dedicated_notm}}](index.html#dedicatedandlocal), [Compute](index.html#compute_category), and [Services](index.html#services_category).
{:shortdesc}

## {{site.data.keyword.Bluemix_notm}} platform
{: #platform_category}

### Updated global location names for {{site.data.keyword.cloud_notm}}
New as of: 1 November 2018

As {{site.data.keyword.cloud_notm}} continues to expand our global availability footprint, we’re updating our location naming structure to better support an understandable, consistent hierarchy of geographies, regions, and data centers around the world. If you’re familiar with our current global regions, you’ll recognize names like US South and Sydney. We’re aligning these location names to the names of the city in which the data centers physically exist.

For now, the programmatic IDs are not changing, so there’s no impact from an API perspective. Here is a table that shows the old and new location names. For more information and a comprehensive list of data centers and regions, see [Service availability](docs/resources/services_region.html).

| Previous location display name | New location display name | Code |
|----------|---------|---------|
| US South | Dallas | us-south | 
| US East | Washington DC | us-east |
| United Kingdom | London | eu-gb |
| Germany | Frankfurt | eu-de |
| Sydney | Sydney | au-syd |
| AP North | Tokyo | jp-tok |
{: caption="Table 1. New location names" caption-side="top"}

### Assign account management access to others
New as of: 30 October 2018

With {{site.data.keyword.cloud_notm}} Identity and Access Management (IAM), you can delegate common tasks that you complete as an account administrator to another user in your account. By creating an access policy on one or all of the available account management services, you can easily delegate responsibilities such as inviting and removing users, managing access groups, managing service IDs, maintaining private catalog services, and even monitoring billing and tracking usage. There are four individual account management services and an all services option that you can use to set up access policies:

* User Management for inviting and removing users
* IAM Access Groups for creating, editing, deleting, updating, and assigning access 
* IAM Identity Service for viewing, creating, deleting, and assigning access to service IDs and associated API keys across the account
* Global resource catalog for viewing private catalog offerings and updating the metadata and visibility for the offerings
* All account management services for access to each of the individual account management service options based on the assigned role as well as access to billing and usage tracking.


For more information on the tasks that a user can do based on which account management service they have a policy on and which role they are assigned, see [Example platform management roles and actions for account management services](/docs/iam/users_roles.html#platformrolestable2). For more information about this new feature, see the [Introducing More Flexibility and Control for IBM Cloud Account Management Services Access](https://www.ibm.com/blogs/bluemix/2018/11/introducing-more-flexibility-and-control-for-ibm-cloud-account-management-services-access/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") blog post. 


### Searching for resources
New as of: 17 July 2018

You can search for resources from anywhere in the {{site.data.keyword.cloud_notm}} console. Type the name of a resource in the search field in the console menu bar. Press the Forward Slash key (/) to activate the search.

### Dynamically add federated users to access groups
New as of: 12 July 2018

You can create dynamic rules to automatically add federated users to access groups based on specific identity attributes. When your users log in with a federated ID, the data from the identity provider dynamically maps your users to an access group based on the rules that you set. For more information, see [Creating dyanmic rules for access groups](/docs/iam/accessgroup_rules.html#creating-dynamic-rules-for-access-groups).

### Protect your service IDs and API keys
New as of: 1 June 2018

To avoid a situation where your service ID or API key is deleted causing an outage or disruption, you have the option to lock service IDs and API keys by using the UI or CLI. Locking a service ID also prevents any access policies from being changed, deleted, or assigned as well as any API keys associated with the service ID from being created or deleted. For more information, see [Locking a service ID](/docs/iam/serviceid.html#locking-a-service-id) and [Locking an API key](/docs/iam/userid_keys.html#locking-an-api-key).

### Upgrade your Lite account to a Subscription account
New as of: 31 May 2018

You can now upgrade your Lite account to a Subscription account directly from the {{site.data.keyword.Bluemix_notm}} console. With a Subscription account, you can use both platform and infrastructure offerings, and take advantage of discounted pricing by making a monthly spending and term commitment. You can also avoid surprises with fixed billing on a monthly payment schedule, but with the flexibility to order more or less based on your needs. For more information, see [Subscription account FAQS](/docs/billing-usage/billing-faq.html#subscription-faqs). 

### {{site.data.keyword.Bluemix_notm}} CLI rebranding
New as of: 15 May 2018

The {{site.data.keyword.Bluemix_notm}} CLI commands have changed from `bluemix` and `bx` to **ibmcloud**. However, you can still use the `bluemix` and `bx` CLI commands until they are removed at a later date. There is no short name at this time, just the full name **ibmcloud**. 

### Multi-factor authentication for your {{site.data.keyword.Bluemix_notm}} account
New as of: 02 May 2018

Multi-factor authentication (MFA) adds an extra layer of security to your account by requiring all users to provide a time-based one-time passcode in addition to their standard IBMid and password during log in. This is also commonly known as two-factor authentication (2FA). MFA is enabled per account, and once it is turned on, all users in the account are required to log in using the additional security measure.

For more information, see the [IBM Cloud Platform now adds support for Multi-Factor Authentication](https://www.ibm.com/blogs/bluemix/2018/05/ibm-cloud-platform-now-adds-support-multi-factor-authentication/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") blog post.

### Assign access quickly by using access groups
New as of: 03 April 2018

Do you want to be able to assign access quickly by using the least amount of policies possible? Now you can with access groups. Access groups enable you to group a set of users and service IDs together and assign a single policy that applies to all members of the group. By using access groups, you can limit the time you spend managing access to the users and service IDs in your account. Check out the blog post [New feature: Access groups](https://www.ibm.com/blogs/bluemix/2018/04/access-groups/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") for more details.

### SoftLayer and {{site.data.keyword.Bluemix_notm}} account linking
New as of:  01 March 2018

You can link your SoftLayer account to your {{site.data.keyword.Bluemix_notm}} account to log in to a single location, the {{site.data.keyword.Bluemix_notm}} console, and access both infrastructure as a service (IaaS) and platform as a service (PaaS) resources. If you're new to {{site.data.keyword.Bluemix_notm}}, create and link an account to get a free {{site.data.keyword.Bluemix_notm}} Lite account. Or, if you already have an {{site.data.keyword.Bluemix_notm}} account with PaaS resources, link your accounts to receive a single bill for both your IaaS and PaaS resources. Check out [Steps to Link your IaaS and PaaS Accounts](https://www.ibm.com/blogs/bluemix/2018/03/follow-steps-link-iaas-paas-accounts/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") to quickly link your accounts.


### {{site.data.keyword.Bluemix_notm}} Foundry Service US East region is now available
New as of:  15 December 2017

A new US East data center is now available in Washington, DC. This new region can be reached using the `us-east.bluemix.net` endpoint. For details on the services that are available for purchase in this new region, see [Services by region](/docs/resources/services_region.html#services_region).

### Support for resources in the European Union
New as of: 14 December 2017

If your services and data centers are located in Europe, {{site.data.keyword.Bluemix_notm}} now offers additional capabilities to protect your data in the European Union. You can request support be provided by customer success teams that are located in Europe. This support is available 24 hours a day, 7 days a week. See [Enabling the EU supported option](/docs/billing-usage/eusupported.html#bill_eusupported) and [Requesting support for resources in the European Union](/docs/get-support/howtogetsupport.html#eusupported) for more information.

### Withdrawal of support for TLS 1.0 and 1.1
New as of: 28 November 2017

On 1 March 2018 {{site.data.keyword.Bluemix_notm}} will withdraw support for TLS 1.0 and TLS 1.1 across many of our cloud products and services as part of our commitment to offering a cloud that is secure to the core and in alignment with industry best practices for security and data privacy. To learn more about how this change affects you and what actions you might need to take, see [Withdrawal of support for TLS 1.0 and 1.1](/docs/troubleshoot/appsectls.html).

### A new way to organize resources within your account
New as of: 16 November 2017

Resource groups are a new way for you to create customizable groupings of account resources, and access to the group and the resources within it are managed by using Identity and Access Management (IAM). Everyone starts out with a default resource group. You can rename this resource group and add new service intances to it as you create them from the catalog.

For users with a Pay-As-You-Go or Subscription account, you can create additional resource groups to make managing quota and viewing billing usage for a set of resources easier. You can also group resources to make it easier for you to assign users access to more than one service at a time. To learn more about working with resource groups for your account, see [Managing resource groups](/docs/account/resourcegroups.html#rgs).

### Updates for {{site.data.keyword.Bluemix_notm}} IAM
New as of: 16 November 2017

The introduction of [resource groups](/docs/overview/resource-groups.html#whatis) within your {{site.data.keyword.Bluemix_notm}} account has opened up a new way for you to assign access. Users and service IDs can be assigned access to all services within a resource group enabling you to quickly assign access to more than one resource at a time. You can also customize access for each user or service ID by assigning access to just some services within a resource group, or you just choose to assign access to individual resources down to the service instance level.

For more information about the features that you can take advantage of by using IAM, see [What features does IAM provide?](/docs/iam/index.html#features)

### Customize your dashboard view
New as of: 16 November 2017

You can view and manage all the resources in your account from your dashboard in the {{site.data.keyword.Bluemix_notm}} console. And now, you can set filters to customize your view. For example, you can filter by resource group to view the specific resources in a resource group. You can also filter by region or Cloud Foundry space. For more details, see [Managing resources on the dashboard](/docs/overview/ui.html#dashboardview).


### Support Center
New as of: 2 November 2017

We now have the new Support Center where you can search for information, post questions to our developer community, and manage tickets. Go to **Support > Support Center** in the {{site.data.keyword.Bluemix_notm}} console menu bar.

### Introducing IBM Cloud
New as of: 31 October 2017

Bluemix is now IBM Cloud. Besides rolling out our new name, nothing changes. You can still easily build and run your apps and services as always. Check out the [IBM Cloud Blog](https://www.ibm.com/blogs/bluemix/2017/10/bluemix-is-now-ibm-cloud/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") for more details.

### Lite account
New as of: 31 October 2017

A Lite account is our new account type that gives you access to try select services for free with no time restrictions. This new account also includes usage tracking and efficiency features to help you better manage your resources. To learn more about what's available, see [Account types](/docs/account/index.html#liteaccount).

### Identity and Access Management application authentication feature
New as of: 6 October 2017

Identity and Access Management (IAM) now provides the ability to create a Service ID, which you can think of as an identity that can be used for apps to authenticate with your {{site.data.keyword.Bluemix_notm}} services. Instead of using individual user credentials, a Service ID can be created with an associated API key and access permissions in the form of a service policy that is assigned to the Service ID in order for you to control the level of access for any application authenticating with that ID.

For more information about the benefits of this feature and how to get started, see the [Introducing IBM Cloud IAM Service IDs and API Keys](https://www.ibm.com/blogs/bluemix/2017/10/introducing-ibm-cloud-iam-service-ids-api-keys/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon").

### {{site.data.keyword.Bluemix_notm}} global catalog
New as of: 27 July 2017

Expanding on the last console update to manage your public regions from a single location in the console, {{site.data.keyword.Bluemix_notm}} now has a global catalog making the process of selecting and deploying items you select from the catalog a more streamlined process. Regardless of the region you have selected in the console, you can now see all services that are available across all public regions from your catalog. Once you select a tile from the catalog, you can see which regions the service is available in, and select where you want to deploy it.

For more information about the latest updates to the catalog, see [A global {{site.data.keyword.Bluemix_notm}} catalog makes building things easier](https://www.ibm.com/blogs/bluemix/2017/07/global-bluemix-catalog-makes-building-things-easier/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon").

### {{site.data.keyword.Bluemix_notm}} console updates
New as of: 23 May 2017

You can now manage your public regions from a single location through the updated {{site.data.keyword.Bluemix_notm}} console. The region selector offers you streamlined access to your resources, and other enhancements include higher availability and improved performance.

For more information about this update, check out [New Global Bluemix UI for Higher Availability and More](https://www.ibm.com/blogs/bluemix/2017/05/new-global-bluemix-ui-higher-availability/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon").

### Identity and access management
New as of: 01 May 2017

With the latest updates and improvements, {{site.data.keyword.Bluemix_notm}} account owners or administrators can now use a new unified access control UI to take advantage of the following capabilities:
 * Manage users' fine-grained access to Kubernetes services and other services as they adopt the new access control features
 * Assign service policies and Cloud Foundry roles to users within their organizations

Additionally, {{site.data.keyword.Bluemix_notm}} platform users can create, delete, and list API keys associated with their user IDs. And platform users can use those API keys to authenticate when using APIs or CLIs.

Lastly, we’ve enhanced our unified user management capability to ensure that in a linked IaaS-PaaS account, users are managed in a unified way with no need to add users separately in the SoftLayer Customer Portal or the {{site.data.keyword.Bluemix_notm}} console.

For more information about the recent update, check out the [Introducing Identity & Access Management](https://www.ibm.com/blogs/bluemix/2017/05/introducing-identity-access-management/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") blog post.

### Navigation design changes for {{site.data.keyword.Bluemix_notm}} docs
New as of: 13 April 2017

With this navigation update, we think you'll understand how content is organized throughout our docs better, and will be able to find relevant content more efficiently. With fewer nested layers of content, you won't have to dig around to find the documentation you need to be successful with {{site.data.keyword.Bluemix_notm}}.


## {{site.data.keyword.Bluemix_local_notm}} and {{site.data.keyword.Bluemix_dedicated_notm}}
{: #dedicatedandlocal}

### February updates for the administration console
{: #febadminconsole}
New as of: 28 February 2018

With the latest update from February 2018, you can use the following new feature:

#### New permission for managing maintenance updates

A new user permission has been introduced to specifically allow users to approve and reschedule maintenance updates, as well as to set up maintenance update windows that stipulate when maintenance updates can be deployed into a dedicated environment.
See the [video demonstration](https://youtu.be/7c7jyp_JJWU){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") for more information.

### December updates for the administration console
{: #decemberadminconsole}
New as of: 14 December 2017

With the latest updates and improvements from December, you can use the following new features:

#### Subscribe to notifications for average CPU usage threshold

Average CPU has been added as a threshold type in notification subscriptions. You can now receive notifications when CPU usage (averaged across all DEA's and Diego Cells) goes above or below a certain threshold.

#### Control access to cloud systems in the European Union

Combined with the new capability in the European Union to support cloud resources (starting with Frankfurt), the administration console now has the capability to define policies that control access by IBM personnel. You can manage access control policies, view access requests, take action on the requests, and track the history.

#### Enhanced information in security reports

Security reports now include user-friendly names in addition to unique IDs for users and organizations.

### August updates for the administration console
{: #augustadminconsole}
New as of: 31 August 2017

With the latest updates and improvements from August, you can use the following new features:

#### Updates to {{site.data.keyword.cloudant_short_notm}} service usage metrics

  * The computation of usage metrics for {{site.data.keyword.cloudant_short_notm}} has been updated to reflect the total amount of GBs used and available across all nodes in a {{site.data.keyword.cloudant_short_notm}} cluster. Typically, a {{site.data.keyword.cloudant_short_notm}} cluster contains 3 nodes, and a document in the database is replicated across all the nodes in the cluster for high-availability and disaster recovery. With the August updates, the capacity metric in the {{site.data.keyword.cloudant_short_notm}} dial (available in the _Resource Usage > Services_ view) indicates the space across all the nodes in the cluster. For example, if a single {{site.data.keyword.cloudant_short_notm}} cluster contains 3 nodes, each with 1000 GB capacity, the capacity limit will be 3000 GB. If 1500 GBs of that capacity have been used, the {{site.data.keyword.cloudant_short_notm}} usage metric will be 50%.

#### Updates to the scheduling of maintenance updates

  * In {{site.data.keyword.Bluemix_dedicated_notm}}, customers can manage the dates and times when their dedicated environments are available for deployment of system updates. Customers can define availability windows representing dates and times when maintenance updates can and cannot be deployed to their Dedicated environment. In the August update, _Available Update Windows_ have been renamed _Update Windows_, and _Unavailable Update Windows_ have been renamed _Blackout Windows_. Beyond the terminology changes, customers now have more flexibility and margin for defining blackout (unavailable) dates. Once requested, blackout dates will require IBM approval, and the time it takes to gain approval will vary. When the requested blackout dates are approved, IBM will cancel any existing updates that are currently scheduled during the unavailable window. IBM will also create new records for these updates and schedule them outside the approved blackout dates.

See the [video demonstration](https://bit.ly/2eCQNvu){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") for more information.

### July updates for the administration console
{: #julyadminconsole}
New as of: 31 July 2017

With the latest updates and improvements from July, you can use the following new features:

#### Updates to resource usage history capabilities

  * In the previous update (June), the History view for memory and disk usage had introduced display of usage data over the last 48 hours, 30 days, and 5 mohths. In this latest July update, the resource usage history functionality has been expanded to allow customization of the time span for which to show resource usage data. Hourly, daily and monthly views remain, but users can now specify a start day/time and duration for which to display memory and disk usage metrics (for example, showing memory usage for 15 days starting on July 1st 2017).
  * A new CLI command has been introduced to display resource metrics history in the CLI. The parameters of the command, as well as usage examples can be found by typing the following: `_cf ba resource-metrics-history -help_`

See the [video demonstration](https://youtu.be/QBij0jB5qAk){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") for more information.

### June updates for the administration console
{: #juneadminconsole}
New as of: 26 June 2017

With the latest updates and improvements from June, you can use the following new features:

#### Updates to the Resource Usage Page

  * System resources
    * The History view for memory and disk has been updated to display data over 48 hours, 30 days, and 5 months
    * A Learn More link is provided, showing how the administration console metrics api is used to generate the History views
  * Applications
    * Provides usage information for all applications in the environment
    * Sort by application name, physical memory, reserved memory, physical disk, reserved disk, physical CPU, or Organization name
    * Search is provided to filter results by application name and Organization name
    * A Learn More link is provided, showing how the administration console metrics api is used to generate the Applications view

See [Resource usage](/docs/hybrid/index.html#resourceusage) for more information.

#### Updates to API for Metrics

  * Environment statistics have been added, providing averages by day or month for memory and disk consumption

See [API for Metrics](/docs/hybrid/index.html#envappmetricsapi) for more information.


### May updates for the administration console
{: #mayadminconsole}
New as of: 30 May 2017

With the latest updates and improvements from May, you can use the following new features:

 * Improvements on the Status page including more granular diagnostics on incidents affecting the {{site.data.keyword.Bluemix_notm}} platform and runtimes.
 * Improvements to the security Reports and Logs page:
   * Reports are now displayed in a table format, simplifying the browsing and searching of reports, including the ability to sort by report category, file name, or creation date.
   * Enhanced filtering including simultaneous filtering of multiple categories
   * Full screen mode for displaying the contents of a report
   * Capability to delete reports for admin users with "report write" permission
   * Faster display of report lists, progressively loading on-demand through continuous scrolling, resulting in better overall performance.
 * Security reports can be requested on-demand within a time range spanning up to one week and starting a maximum of 3 months back from the time of the request. Note that some environment specific configuration is required before this capability is available to admin users. Admin users will require "report write" permission for this capability.

### April updates for the administration console
{: #apriladminconsole}
New as of: 2 May 2017

With the latest updates and improvements from April, you can use the following new features:

 * Newly designed status app for {{site.data.keyword.Bluemix_notm}} Dedicated and Local environments. You can quickly search by component name or date of posting. You can also switch between the component status posts view and the notifications specific to your environment. See the [New {{site.data.keyword.Bluemix_notm}} Status Page](https://www.ibm.com/blogs/bluemix/2017/05/new-bluemix-status-page/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") blog post for more information.
 * Service usage data for select services from the Resource Usage tile. See [Service usage details](/docs/hybrid/index.html#servicesresourceusage) for more information about what services are supported and what you can expect from the new view.

## Compute
{: #compute_category}

### Virtual server features
New as of: 16 November 2018

The following features are currently available for the {{site.data.keyword.BluVirtServers_full}} offering.

#### Suspend billing when you're not using instances
Want to pay only for what you use? You can now suspend billing on virtual server instances. The suspend billing feature is available on virtual server instances that have hourly public flavor sizes with SAN-backed storage. When you power off a virtual server that supports the suspend billing feature, you don't accrue costs for certain compute resources. Billing stops automatically when the server is powered off. The suspend billing feature helps you reduce cost and prevents you from having to reprovision a virtual server when you need its resources again. For more information, see [About suspend billing](/docs/vsi/vsi_about_suspend.html) or the {{site.data.keyword.cloud_notm}} [blog post ![External link icon](../../icons/launch-glyph.svg "External link icon")](https://www.ibm.com/blogs/bluemix/2018/10/suspend-billing-1-minute-granularity-virtual-servers/){: new_window}.

#### Reserve resources for future virtual server instances
{{site.data.keyword.BluVirtServers_full}} reserved instances offering is now available. This is a great option if you want guaranteed resources for future deployments and cost savings. You choose between either a one or three year contract term for your reserved capacity. Within that reserved capacity, you can reserve a set of up to 20 virtual server instances of a specific size and provision those instances when you need them. You are guaranteed this capacity within the POD and data center of your choice for the life of the contract term. For more information, see [Reserved virtual servers](/docs/vsi/vsi_about_reserved.html).

#### Import images from {{site.data.keyword.cos_full_notm}} service instance to {{site.data.keyword.cloud_notm}} infrastructure
{{site.data.keyword.cloud_notm}} infrastructure now interacts with the {{site.data.keyword.cos_full_notm}} service that's provisioned on the {{site.data.keyword.cloud_notm}} console. {{site.data.keyword.cos_full_notm}} offers the Aspera high-speed transfer plug-in that massively decreases the amount of time needed to upload a large image. After images are uploaded to {{site.data.keyword.cos_full_notm}}, you can [import images](/docs/infrastructure/image-templates/import-image.html) to {{site.data.keyword.cloud_notm}} infrastructure from {{site.data.keyword.cos_full_notm}}. You can also [export images](/docs/infrastructure/image-templates/export-image-ibm-cos.html) from {{site.data.keyword.cloud_notm}} infrastructure to {{site.data.keyword.cos_full_notm}}.

#### Placement groups for virtual server instances
Placement groups are now available for {{site.data.keyword.BluVirtServers_full}}. With placement groups, you can use public instances to build for high availability within a data center, or provide an additional level of fault tolerance within a larger deployment. For more information, see [Placement groups](/docs/vsi/vsi_placegroup.html). 

### Latest updates for buildpacks

Visit the following pages for a cumulative list of the latest updates:

* [Latest Updates to the SDK for Nodejs buildpack](/docs/runtimes/nodejs/updates.html#latest_updates)
* [Latest Updates to the Liberty buildpack](/docs/runtimes/liberty/updates.html#latest_updates)
* [Latest Updates to the ASP.NET Core buildpack](/docs/runtimes/dotnet/updates.html#latest_updates)
* [Latest updates to the IBM XPages for {{site.data.keyword.Bluemix_notm}} buildpack](/docs/starters/xpages/index.html#updates)

### Latest updates for {{site.data.keyword.containerlong_notm}}

{{site.data.keyword.containerlong_notm}} launched its Kubernetes architecture in May 2017. The previous architecture for single and scalable container groups is now [fully deprecated as of December 5, 2017](https://www.ibm.com/blogs/bluemix/2017/07/deprecation-single-scalable-group-container-service-bluemix-public/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon").  

[See the documentation for information about getting started with the native Kubernetes environment on {{site.data.keyword.Bluemix_notm}}](/docs/containers/container_index.html). If you have questions, you can post them in the Slack at https://ibm-container-service.slack.com/.

### {{site.data.keyword.containerlong_notm}} now comes with highly available Kubernetes masters
New as of: 7 November 2018

Get even more availability for your cluster with the new highly available Kubernetes master feature. Highly available Kubernetes masters are set up with multiple replicas for your Kubernetes API server, etcd, Kubernetes scheduler, and controller that are all spread across separate physical hosts. When you create a cluster that runs Kubernetes version 1.12, 1.11, or 1.10, your Kubernetes master is set up highly available by default. To enable this feature in existing clusters that run one of those Kubernetes versions, you must complete the [preparation steps](/docs/containers/cs_versions.html#110_ha-masters).

### Create multizone clusters in {{site.data.keyword.containerlong_notm}}
New as of: 10 July 2018

Want to improve cluster and app availability? Now you can span your cluster across multiple zones in select metro areas. For more information, see [Creating multizone clusters in {{site.data.keyword.containershort_notm}}](cs_clusters.html#multizone).

### Kubernetes Dashboard access comes to the {{site.data.keyword.containerlong_notm}}
New as of: 18 April 2018

{{site.data.keyword.containerlong_notm}} now supports direct access to the Kubernetes Dashboard through the {{site.data.keyword.Bluemix_notm}} console. This simplified path to the dashboard offers an enchanced user experience for cluster management and resource visualization. Find out more details on the [{{site.data.keyword.Bluemix_notm}} blog](https://www.ibm.com/blogs/bluemix/2018/04/kubernetes-dashboard-access/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon").


### New Liberty for Java buildpack v3.11
New as of: 17 July 2017

The Liberty buildpack v3.11 provides new monthly Liberty runtime version and contains other improvements. The monthly Liberty runtime version was updated to the  [2017.7.0.0](https://developer.ibm.com/wasdev/blog/2017/07/07/beta-websphere-liberty-tools-july-2017/) release. The IBM JDK has been updated to the 8.0.4.7 and 7.1.4.5 versions. The buildpack also provides updated versions of the App Management utility and Auto-Scaling agent. The default Cloudant Library is now the official [java-cloudant](https://github.com/cloudant/java-cloudant), the [Ektorp library](https://github.com/helun/Ektorp) is still available as an option, for details on this change see the [blog post](https://www.ibm.com/blogs/bluemix/2017/05/default-library-change-cloudant-auto-wiring-liberty-buildpack/). The default heap size ratio is now 50% when your application has less than 512mb of memory, if it has more than 512mb it will still be 75%. A new staging task log is now generated, which allows for easier debugging of staging errors.See the [latest updates](https://console.ng.bluemix.net/docs/runtimes/liberty/updates.html) documentation for additional information.

### New Liberty for Java buildpack v3.10
New as of: 12 June 2017

The Liberty buildpack v3.10 provides new quarterly and monthly Liberty runtime versions and contains other improvements. The default Liberty runtime version was updated to 17.0.0.2. The monthly Liberty runtime version was updated to the  [2017.5.0.0](https://developer.ibm.com/wasdev/blog/2017/05/12/beta-websphere-liberty-tools-may-2017/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") release. The buildpack also provides updated versions of the App Management utility and Extreme Scale Client. See the [latest updates](/docs/runtimes/liberty/updates.html) documentation for additional information.

### New SDK for Node.js buildpack v3.12
New as of: 16 May 2017

The SDK for Node.js buildpack v3.12 provides IBM SDK for Node.js versions 0.12.17, 0.12.18, 4.8.0, 4.8.2, 6.10.0 and 6.10.2. The default is now changed from the latest 4.x to the latest 6.x, so it is currently 6.10.2. Being a major version change, this could affect apps that are relying on the default. See [Node.js version long-term support and the SDK for Node.js buildpack](https://www.ibm.com/blogs/bluemix/2016/11/node-version-support-and-sdk-buildpack/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") for more information about how to avoid any problems.

In addition to the new runtimes, this release contains a buildpack bug fix for an issue with the App Management Health Center handler and Node.js versions 6.9.5 and 6.10.0.

### New Liberty for Java buildpack v3.9
New as of: 27 April 2017

The Liberty buildpack v3.9 provides new monthly Liberty runtime version and contains other improvements. The default Liberty runtime version was updated to include the PI77770, PI77605, IFPI77438 and IFPI79275 iFixes. The monthly Liberty runtime version was updated to the  [2017.3.0.0](https://developer.ibm.com/wasdev/blog/2017/03/14/beta-websphere-liberty-tools-march-2017/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") release. Memory Calculation was moved from staging to the start process, allowing for easier heap memory changes with the restart of an application. The buildpack also provides updated versions of the Auto-Scaling service agent, and Extreme Scale Client. See the [latest updates](/docs/runtimes/liberty/updates.html) documentation for additional information.

## Services
{: #services_category}


### Automate infrastructure and app deployments with Terraform and Ansible
New as of: 2 November 2018

Terraform and Ansible are Open Source software that you can use to automate the deployment of your cloud solution from beginning to end. With Terraform, you can specify your {{site.data.keyword.Bluemix_notm}} infrastructure components and rapidly build complex, multitier cloud environments to enable Infrastructure as Code (IaC). Then, use Ansible to connect to your compute hosts over the private network to deploy your app, build services, execute scripts, or define configurations. 

To get started and learn about the basics of each Open Source product, see our tutorials: 
* [Deploying RedHat OpenShift Container Platform on {{site.data.keyword.Bluemix_notm}} with Terraform](/docs/terraform/tutorials/install_redhat_openshift.html#redhat){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon")
* [Deploying WordPress on IBM Cloud infrastructure with Terraform and Ansible](/docs/terraform/tutorials/wordpress_with_terraform_and_ansible.html#deploy_wordpress){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon"). 

### Latest updates for {{site.data.keyword.cloudant_short_notm}}
New as of: 28 September 2018

Visit the following page for a comprehensive list of the [latest updates](/docs/services/Cloudant/release_info/release_notes.html#release-notes){:new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") to {{site.data.keyword.cloudant_short_notm}}.

### Introducing {{site.data.keyword.IBM_notm}} {{site.data.keyword.DRA_short}} general availability
New as of: 20 September 2018

The {{site.data.keyword.DRA_short}} service is now generally available in the US South, Germany, and United Kingdom regions.

{{site.data.keyword.DRA_short}} helps teams to improve their productivity, efficiencies, and time-to-market, and to use the data from DevOps tools to easily measure success or improve the quality of their code. This service provides the single tool for businesses to understand their DevOps activities across all of their codebases and teams.

* **Speed**: {{site.data.keyword.DRA_short}} shows all of your analytics, across all of your applications, in a single dashboard.
* **Quality**: Mitigate risky releases by implementing gates deployment policies. For example, if you have a policy for Code Coverage, at a selected tolerance, {{site.data.keyword.DRA_short}} always gates against a release of code that does not meet defined tolerances. Over time, these policies help to improve the overall quality of the deployment process. 
* **Control**: Measure results over time as teams react to the trends in their DevOps practices by using code coverage, unit tests, and other tools. These trends help teams to better govern their DevOps practices.

### {{site.data.keyword.security-advisor_long_notm}} is now Beta!
New as of: 5 September 2018

{{site.data.keyword.security-advisor_short}} has added new capabilities and is now available as a beta service.  {{site.data.keyword.security-advisor_short}} centralizes your {{site.data.keyword.Bluemix_notm}} security into one dashboard. In addition to centralizing information, the service summarizes critical security information across easy to navigate tiles to clearly show when a security issue is detected. Clicking on a tile enables a drill down to investigate prioritized issues, history, and the details behind the alert. To fix the issue just drill down once more to get all of the details as well as suggested fixes to remove the threat and ensure your environment stays secure.

{{site.data.keyword.security-advisor_short}} will quickly become your go to console to enable you to centralize, view, and manage security in your {{site.data.keyword.Bluemix_notm}} environment.

With this release we are implementing:
* A Findings API
* The ability to bring your own provider
* Updates to the dashboard experience

And so much more!

To get started, see the [{{site.data.keyword.security-advisor_short}} documentation](/docs/services/security-advisor/index.html).

### Introducing {{site.data.keyword.iva_full_notm}} general availability
New as of: 26 June 2018

The [{{site.data.keyword.iva_full}}](https://console.bluemix.net/catalog/services/voice-agent-with-watson)![External link icon](../../icons/launch-glyph.svg "External link icon") is now generally available! You can create a cognitive voice agent built on Watson services that customers can call and speak to over the phone. With Watson artificial intelligence at its backbone, your voice agent can communicate in a conversational manner, handling complex interactions and solving customer calls within the voice agent.

This release introduces the following new features:

* Add redundant Watson service locations for disaster recovery. 
* Edit advanced configuration options to customize how your voice agents transfer calls, play prerecorded messages to callers, and interact with Watson services.
* Configure the number of maximum concurrent connections in your Standard service plan.
* Connect your voice agents to SIP trunking providers like NetFoundry, Twilio, AT&T, and other service providers or peer with {{site.data.keyword.iva_short}}.

To get started, see the [{{site.data.keyword.iva_short}}](/docs/services/voice-agent/getting-started.html) documentation.

### {{site.data.keyword.streaminganalyticsshort}} introduces new service plans with container-based infrastructure
New as of: 20 April 2018

{{site.data.keyword.streaminganalyticsshort}} is now running on a Kubernetes container-based infrastructure that provides security and availability advantages to the service.
 
You can access this new container-based infrastructure using the [v2 service plans](/docs/services/StreamingAnalytics/service_plans.html#service_plans). You can choose the {{site.data.keyword.streaminganalyticsshort}} plan that is best suited for the work that you need to do. The v2 service plans include the following enhancements:
 
* [IBM Streams QSE with Docker](https://www-01.ibm.com/marketing/iwm/iwm/web/preLogin.do?source=swg-ibmistvi)![External link icon](../../icons/launch-glyph.svg "External link icon"): Check out the [ Development Guide](https://developer.ibm.com/streamsdev/docs/cloud-beta-devguide/)![External link icon](../../icons/launch-glyph.svg "External link icon") to learn how to use the new Streams QSE with RHEL 7 running in a Docker environment to compile and deploy your applications with the new {{site.data.keyword.streaminganalyticsshort}} v2 plans. 
* [{{site.data.keyword.streaminganalyticsshort}} v2 REST API](https://console.bluemix.net/apidocs/1939-streaming-analytics-v2#introduction)![External link icon](../../icons/launch-glyph.svg "External link icon")
* [New starter and sample applications](https://developer.ibm.com/streamsdev/docs/cloud-beta-samples/) ![External link icon](../../icons/launch-glyph.svg "External link icon")
* [High-availability enhancements in the {{site.data.keyword.streaminganalyticsshort}} service](/docs/services/StreamingAnalytics/c_ha.html#consistent-regions)
* [Problem determination features in the {{site.data.keyword.streaminganalyticsshort}} service](https://developer.ibm.com/streamsdev/2018/02/15/streaming-analytics-console-gives-ways-find-fix-errors-beta-plans/)![External link icon](../../icons/launch-glyph.svg "External link icon")
* [Monitoring how operators behave and guaranteed tuple processing in the cloud](https://developer.ibm.com/streamsdev/2018/02/15/monitor-operators-behave-ensure-resource-optimization/)![External link icon](../../icons/launch-glyph.svg "External link icon")

### {{site.data.keyword.iva_full_notm}} is now beta!
New as of: 16 March 2018

With [{{site.data.keyword.iva_full}}](https://console.bluemix.net/catalog/services/voice-agent-with-watson)![External link icon](../../icons/launch-glyph.svg "External link icon"), you can create a cognitive voice agent built on Watson services that customers can call and speak to over the phone. With Watson artificial intelligence at its backbone, your voice agent can communicate in a conversational manner, handling complex interactions and solving customer calls within the voice agent.

This beta release introduces the following key features:

* Get started more easily than ever by creating a voice agent and all required Watson services in a single step.
* Transfer calls from your voice agent, such as to a human contact center agent or other destination.
* Collect and analyze call data by configuring your voice agent to forward call detail record, transcription, and {{site.data.keyword.conversationshort}} turn events to a {{site.data.keyword.cloudant_short_notm}} database.
* Monitor service usage and view call logs on the new _Usage_ page. You can view quick stats for the current month, find and filter call logs, and view system messages for each individual call.
* Establish secure calls with media encryption by using SIP TLS (sips URIs) over port 5061 and Secure Real-time Transport Protocol (SRTP).
* Connect to {{site.data.keyword.speechtotextfull}} and {{site.data.keyword.texttospeechfull}} service instances in other {{site.data.keyword.cloud_notm}} spaces for increased flexibility.

To get started, see the [{{site.data.keyword.iva_short}}](/docs/services/voice-agent/getting-started.html) documentation.

### Updates to {{site.data.keyword.visualrecognitionshort}}
New as of: 14 March 2018

The {{site.data.keyword.visualrecognitionfull}} service has been updated so that new Custom Classifier model trainings are now generated as deep learning neural net based classifiers. The additional computation required to generate these deep learning models may require additional time for new models to train.

Presently, existing custom classifiers can continue to be updated and retrained and will not be updated to this new deep learning machine model format.

### {{site.data.keyword.streaminganalyticsshort}} updates
New as of: 14 February 2018

The [Beta - Entry and Beta- Enhanced plans](/docs/services/StreamingAnalytics/beta_plans.html#beta_plans) for the console in the [{{site.data.keyword.streaminganalyticsshort}} service](https://console.bluemix.net/catalog/services/streaming-analytics){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") includes several enhancements:

* [New IBM Streams QSE for Docker](https://www-01.ibm.com/marketing/iwm/iwm/web/preLogin.do?source=swg-ibmistvi){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon"): Check out the [Beta Development Guide](https://developer.ibm.com/streamsdev/docs/cloud-beta-devguide/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") to learn how to use the new Streams QSE with RHEL 7 running in a Docker environment to compile and deploy your applications with the new {{site.data.keyword.streaminganalyticsshort}} beta plans.
* [{{site.data.keyword.streaminganalyticsshort}} v2 REST API](https://console.bluemix.net/apidocs/1939-streaming-analytics-v2#introduction){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon")
* [New starter and sample applications](https://developer.ibm.com/streamsdev/docs/cloud-beta-samples/)
* [High-availability enhancements in the {{site.data.keyword.streaminganalyticsshort}} service](/docs/services/StreamingAnalytics/consistentregions.html#consistentregions)
* [New problem determination features in the beta version of the {{site.data.keyword.streaminganalyticsshort}} service](https://developer.ibm.com/streamsdev/2018/02/15/streaming-analytics-console-gives-ways-find-fix-errors-beta-plans/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon")
* [Monitoring how operators behave and guaranteed tuple processing in the cloud](https://developer.ibm.com/streamsdev/2018/02/15/monitor-operators-behave-ensure-resource-optimization/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon")

### {{site.data.keyword.keymanagementservicelong_notm}} expands into Sydney region
New as of: 31 January 2018

Effective today the {{site.data.keyword.keymanagementserviceshort}} encryption key management service is available in the Sydney region. Sydney is the third region after US South (Dallas) and London to offer GA status for {{site.data.keyword.keymanagementserviceshort}} users.

{{site.data.keyword.keymanagementserviceshort}} is an encryption key management service that offers a simple and economical key management solution for managing keys that are used to encrypt data stored in the {{site.data.keyword.Bluemix_notm}}. {{site.data.keyword.keymanagementserviceshort}} manages the entire life-cycle of keys from key creation through application use, key archival, and key destruction, while also enforcing separation of duties between data management and key management.

{{site.data.keyword.keymanagementserviceshort}} supports BYOK (Bring-Your-Own-Key – customer managed encryption) with applicable IBM data services. BYOK allows users to import master root-of-trust encryption keys created internally to better manage the security of their data-at-rest saved in the {{site.data.keyword.Bluemix_notm}}.


### {{site.data.keyword.containershort_notm}}: Kubernetes 1.8.x support
New as of: 19 January 2018

Since November 2017 the {{site.data.keyword.containershort_notm}} has supported Kubernetes `1.8.x`. We are proud to announce our default version of Kubernetes is now `1.8.6`.  In the near future, we will be providing support for `1.9.x`.

### Watson Discovery Visual Insights
New as of: 30 November 2017

Visually explore connections powered by {{site.data.keyword.discoveryshort}}'s understanding of semantic elements detected in text, such as entities, relationships, concepts, and more.

Begin exploring the world's news with the out-of-the-box {{site.data.keyword.discoveryshort}} News collection. Or, explore your own document collections in {{site.data.keyword.discoveryshort}}. Just log in with your {{site.data.keyword.Bluemix_notm}} credentials. See [Visual insights experimental](https://visual-insights.bluemix.net){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") for more information.

### New IBM Cloud Managed Database Server Beta service
New as of: 30 November 2017

With the new IBM Cloud Managed Database Server Beta service, you can create an instance of Microsoft SQL Server on {{site.data.keyword.Bluemix_notm}}. You can use this SQL Server instance just as you would use any database management system, but without the effort and expense of hardware setup or software installation and maintenance.

This service offers the following features:
* Choice of Microsoft SQL Server versions 2012, 2014, and 2016 Enterprise and Standard Editions
* Various predefined configurations or sizes to meet your application workload requirements
* Fully managed by IBM, including monitoring, patching, backup, reporting

To get started, see [Getting started with IBM Cloud Managed Database Server](/docs/services/managed-sql-server/getting-started.html).

### What’s New in {{site.data.keyword.mobilepushshort}}
New as of: 26 October 2017

We have made several enhancements for the {{site.data.keyword.mobilepushshort}} service in the last few months. The service is now available in Frankfurt region along with Dallas, London, and Sydney. Following are the details of the enhancements:

#### Monitoring
You can now track push notification performance for specific time periods, track the number of notifications sent and total number of devices registered. You can also register web hooks to be informed of all events in the lifecycle of a notification. More details can be found in the following documentation links and blog post:
* [Monitor notifications](/docs/services/mobilepush/push_monitoring.html#push_monitoring)
* [Receive alerts on webhook events](/docs/services/mobilepush/push_webhook.html#webhook_event_based_notifications)
* [Monitoring in IBM Push Notifications](https://www.ibm.com/blogs/bluemix/2017/03/monitoring-ibm-push-notifications/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon")

#### Web notifications
We now support Safari web browser for web notifications along with Firefox, Chrome, Chrome App and Extensions. Web SDK’s and related information can be found at [IBM Bluemix Push Notifications Web SDK](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-javascript-webpush/blob/Doc/README.md){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon").

#### Latest Android and iOS notifications
We have currency support for iOS 11 notifications. We have also incorporated several new notification related enhancements from iOS10 and Android N.

* iOS10 –Rich Media Notifications, images, button and maps in interactive notifications, localized string support
* Android N – Expandable notifications, interactive and silent notifications, LED light settings

Additional details can be found in the [Rich Media notifications](/docs/services/mobilepush/push_step_4_nf_rich.html#interactive-notifications) documentation, [Interactive and silent notifications](/docs/services/mobilepush/push_step_4_nf_interactive.html#interactive-notifications) documentation, and the [Enabling advanced push notifications](/docs/services/mobilepush/push_step_4_nf_adv.html#enabling-advanced-push-notifications) documentation.

#### APNS HTTP/2 support
Apple introduced support for HTTP protocol for Apple Notifications. {{site.data.keyword.mobilepushshort}} service now supports HTTP/2 protocol. With this support, notification payloads can be 4KB with increased throughput and provides instant feedback feature. Support for Universal Certificate allows the app to connect to both sandbox and production environments.

#### New Lite plan
Lite Plan for {{site.data.keyword.mobilepushshort}} service provides the ability to send 100K notifications free for every month. For more information, see the [Lite Plan For Push Notifications Service on Bluemix](https://www.ibm.com/blogs/bluemix/2017/06/lite-plan-push-notifications-service-bluemix/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") blog post.



### What’s New in Mobile Analytics
New as of: 26 October 2017

We have made enhancements for {{site.data.keyword.mobileanalytics_short}} service in the last few months. The service is now available in Frankfurt and Sydney regions along with Dallas and London. Following are the details of the enhancements:

#### Web SDK Support
{{site.data.keyword.mobileanalytics_short}} is now Omni channel service with the addition of support for Web app analytics. More details can be found at [https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-web-analytics/](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-web-analytics/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon").

#### Integration with {{site.data.keyword.mobilefoundation_short}} service
{{site.data.keyword.mobilefoundation_short}} service now leverages {{site.data.keyword.mobileanalytics_short}} service for app, user and performance analytics. Users can leverage the export to DB2 warehouse option to build adapter analytics and custom charts. You can find additional details in the following blog posts:

* [Mobile Foundation Service integration with Mobile Analytics Service](https://www.ibm.com/blogs/bluemix/2017/08/mobile-foundation-service-integration-mobile-analytics-service-2/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon")
* [Building custom charts using IBM Bluemix Mobile Analytics service and IBM Mobile Foundation Service](https://mobilefirstplatform.ibmcloud.com/blog/2017/04/26/custom-charts-using-analytics-and-dashdb-analytics-service/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon")
* [Building charts for Adapter analytics using IBM Bluemix Mobile Analytics service and IBM Mobile Foundation Service](https://mobilefirstplatform.ibmcloud.com/blog/2017/04/26/adapter-analytics-using-analytics-and-dashdb-analytics-service/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon")

#### {{site.data.keyword.mobilefirst_notm}} boilerplate now includes {{site.data.keyword.mobileanalytics_short}}
Mobile Services Boilerplate is a template that provides a set of mobile services for users to quickly get started. {{site.data.keyword.mobileanalytics_short}} service is now a part of the boiler plate available in the [catalog](https://console.bluemix.net/catalog/starters/mobilefirst-services-starter){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon").


### Updates for {{site.data.keyword.streaminganalyticsshort}}
New as of: 20 October 2017

* IBM Streams Runner for Apache Beam: You can now develop Beam applications locally in your Streams development environment and then submit these apps to the {{site.data.keyword.streaminganalyticsshort}} service in the {{site.data.keyword.Bluemix_notm}}. IBM Streams Runner for Apache Beam executes Beam pipelines in a Streams environment. A Beam application that is launched with Streams Runner is translated into a Streams Application Bundle (SAB) file that you can then deploy in {{site.data.keyword.streaminganalyticsshort}}. Check out [IBM Streams Runner for Apache Beam in Streaming Analytics](/docs/services/StreamingAnalytics/gs_beamrunner.html) for more details.
* You can find information from log files even faster. The console has been updated to improve the display of application graphs for Python or Java topologies. See [Enhancements to the Console](https://developer.ibm.com/streamsdev/2017/10/13/enhancements-to-the-console/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon").

### The IBM App Launch for {{site.data.keyword.Bluemix_notm}} Services
New as of: 12 October 2017

The IBM App Launch for {{site.data.keyword.Bluemix_notm}} Services is an experimental offering that empowers you to measure customer experiences by providing a platform to create targeted engagements across various cross-sections of your audience. The App Launch service provides insights into customer preferences and pain points as an outcome of the engagements, and helps you personalize the app for better customer experience.

App Owners can now accelerate the delivery of innovations to mobile apps by avoiding release cycle complexities. App Launch service enables app owners to launch features to mobile apps at speed and measure impact by controlling the targeted audience. The app owner can work with app developer to define key performance indicators for the features, measure the impact and make feature roll out and roll back decisions based on real-time feedback. The service also provides the ability to test multiple variants of application features, user interface components, and messages and make decisions based on the feedback.

For more information, see the [Getting started tutorial](/docs/services/app-launch/index.html#gettingstartedtemplate).

### Updates to {{site.data.keyword.ibmwatson_notm}} {{site.data.keyword.relationshipextractionshort}}
New as of: 4 October 2017

A new customization capability and new language models are available for user by {{site.data.keyword.relationshipextractionshort}}. The new languages are Dutch, Korean, and Simplified-Chinese support for WKS.

### {{site.data.keyword.containerlong_notm}} cluster update
New as of: 20 September 2017

You can now update your clusters to the latest available version of Kubernetes in {{site.data.keyword.Bluemix_notm}}. Using either the GUI or the CLI, update your Kubernetes master and your worker nodes to Kubernetes 1.7 and take advantage of the new features and patches.

For more information, check out [Kubernetes 1.7 available in {{site.data.keyword.containerlong_notm}}](https://www.ibm.com/blogs/bluemix/2017/09/kubernetes-1-7-available-ibm-bluemix-container-service/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon").

### New IBM Voice Agent with Watson experimental service
New as of: 15 September 2017

With the new {{site.data.keyword.iva_full}} experimental service, you can create a cognitive voice agent built on Watson services that customers can call and speak to over the phone. With Watson artificial intelligence at its backbone, your voice agent can communicate in a conversational manner, handling complex interactions and solving customer calls within the voice agent.

{{site.data.keyword.iva_short}} seamlessly connects to and orchestrates the Watson {{site.data.keyword.speechtotextshort}}, {{site.data.keyword.conversationshort}}, and {{site.data.keyword.texttospeechshort}} services to simulate natural-language conversation. Each voice agent automatically scales to handle multiple calls at the same time. In this experimental release, you can customize your voice agent by using the following key features:

* Import the sample {{site.data.keyword.conversationshort}} dialog to get started, then create your own dialog to fit your company's needs.
* Program voice agent behavior from within the {{site.data.keyword.conversationshort}} service by using our APIs. You control everything from barge-in behavior to hanging up the call for any node in your dialog.
* Easily create and manage multiple voice agents if you want to connect different phone numbers to cognitive agents that are specialized for different topics.
* Expand the service's capabilities by connecting a service orchestration engine (SOE) so you can use third-party APIs. For example, the SOE can listen for triggers from the {{site.data.keyword.conversationshort}} service, then use your provided APIs to look up information in existing systems or provide other analysis.

To get started, see the [Getting started with {{site.data.keyword.iva_short}}](/docs/services/voice-agent/getting-started.html) documentation.


### {{site.data.keyword.streaminganalyticsshort}} service update: The console includes new ways to pinpoint problems in your applications
New as of: 14 August 2017

For Python and Java applications, the source file location is displayed based on your @spl_note annotations.

For details, see [Latest improvements to the {{site.data.keyword.streaminganalyticsshort}}](https://developer.ibm.com/streamsdev/2017/08/14/latest-improvements-streaming-analytics-console/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon").

### IBM Cloud Monitoring is now also available in the United Kingdom region
New as of: 01 August 2017

Use the {{site.data.keyword.monitoringlong}} service to expand your collection, retention, and analysis capabilities in {{site.data.keyword.Bluemix_notm}} when working with metrics.

* Alert into action! {{site.data.keyword.monitoringlong}} offers an API that you can use to set performance thresholds, and to be notified when those thresholds are breached. Define alert rules for a single service instance or app instance, and alert rules that report on a set of instances. When an alert is triggered, get a notification through an e-mail, a PagerDuty event, a webhook notification, or any combination of the three.

* Add custom metrics. {{site.data.keyword.monitoringlong}} premium plan offers APIs that you can use to add relevant application and business metrics to your Cloud Monitoring data. You can also use them to send metric data from outside the {{site.data.keyword.IBM_notm}} Cloud into the {{site.data.keyword.monitoringlong}} service.

* Build reusable dashboards and make them interactive. {{site.data.keyword.monitoringlong}}’s hosted Grafana provides support for building custom dashboards with a large palate of visualization options.  Make your dashboards dynamic with templating by using metric queries with variables.

* Access your service through the {{site.data.keyword.Bluemix_notm}} catalog. {{site.data.keyword.monitoringlong}} is available as a service tile in the DevOps section of the {{site.data.keyword.Bluemix_notm}} catalog.  For the {{site.data.keyword.containershort}} service with single and group containers, you can access the service from the {{site.data.keyword.Bluemix_notm}} UI.

* Choose the service plan that fits your needs. You may choose the Lite service plan or the Premium service plan to match your usage needs. The Lite plan offers metric collection at once per minute, retention for 15 days, and complementary alerting.  Alternatively, you can select the Premium plan to enable greater consumption, longer metrics retention, and to gain access to the service APIs, for example, to send or retrieve metrics from the {{site.data.keyword.monitoringlong}} service. {{site.data.keyword.monitoringlong}} offers metric collection at once per minute.  The Lite plan retains metrics at full resolution for 15 days. The Premium plan retains metrics at full resolution for 45 days.

The legacy {{site.data.keyword.monitoringshort}} service collected metrics at service defined frequencies starting at 30 seconds, and summarized to 1 hour frequencies over time. {{site.data.keyword.monitoringlong}} now offers full resolution collection at 1 minute.  The Lite plan retains metrics for 15 days.  The Premium plan retains metrics for 45 days.

For more information about the {{site.data.keyword.monitoringlong}} service, refer to [the Getting started with Monitoring documentation](/docs/services/cloud-monitoring/index.html#getting-started-with-ibm-cloud-monitoring) or [the IBM Cloud Monitoring – Service Refresh with New Features![External link icon](../../icons/launch-glyph.svg "External link icon")](https://www.ibm.com/blogs/bluemix/2017/07/ibm-cloud-monitoring-service-refresh-new-features/).


### IBM Cloud Log Analysis is now available in the US South region
New as of: 31 July 2017

The {{site.data.keyword.loganalysisfull}} service provides log collection and log search services for the {{site.data.keyword.Bluemix_notm}} platform, automatically collecting application and {{site.data.keyword.Bluemix_notm}} services’ data from select {{site.data.keyword.Bluemix_notm}} services. Use the {{site.data.keyword.loganalysisshort}} service to:

* Retain logs as long as you require.  

    Logs are stored on IBM Cloud storage.  You can download logs when you need them.

* Manage your retained logs, and send log data from outside the {{site.data.keyword.IBM_notm}} Cloud by using the new API.

* Choose the amount of logs that you can search per day.  

    Different plans are available that you can use to search up to 500MB,  2GB, 5GB, and 10GB of logs per day.

* Build reusable dashboards and make them interactive.

    {{site.data.keyword.loganalysisshort}}’s hosted Kibana provides support for building custom dashboards.

* Access your service through the {{site.data.keyword.Bluemix_notm}} catalog.  

    For the  {{site.data.keyword.loganalysisshort}} service with single and group containers, and {{site.data.keyword.IBM_notm}} Cloud Foundry services, you can access the service from the {{site.data.keyword.Bluemix_notm}} UI.

For more information about the {{site.data.keyword.loganalysisshort}} service, refer to the [Getting started with {{site.data.keyword.loganalysisfull}}](/docs/services/CloudLogAnalysis/index.html#getting-started-with-ibm-cloud-log-analysis) and the [{{site.data.keyword.loganalysisshort}} overview](/docs/services/CloudLogAnalysis/log_analysis_ov.html#log_analysis_ov).

### IBM dashDB for Analytics has been renamed
New as of: 18 July 2017

The following table summarizes the new name:

| Previous name               | New name                   | Effective date |
|-----------------------------|----------------------------|----------------|
| IBM dashDB for Analytics    | IBM Db2 Warehouse on Cloud | July 18, 2017  |
{: caption="Table 1. Service name change" caption-side="top"}

For a cumulative list of updates for Db2 Warehouse on Cloud and Db2 on Cloud, see: [What's New in Db2 Warehouse on Cloud and Db2 on Cloud](http://www.ibm.com/support/docview.wss?uid=swg21961758){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon").

### IBM Cloud Monitoring is now available in the US South region
New as of: 17 July 2017

Use the {{site.data.keyword.monitoringlong}} service to expand your collection, retention, and analysis capabilities in {{site.data.keyword.Bluemix_notm}} when working with metrics.

* Alert into action! {{site.data.keyword.monitoringlong}} offers an API that you can use to set performance thresholds, and to be notified when those thresholds are breached. Define alert rules for a single service instance or app instance, and alert rules that report on a set of instances. When an alert is triggered, get a notification through an e-mail, a PagerDuty event, a webhook notification, or any combination of the three.

* Add custom metrics. {{site.data.keyword.monitoringlong}} premium plan offers APIs that you can use to add relevant application and business metrics to your Cloud Monitoring data. You can also use them to send metric data from outside the {{site.data.keyword.IBM_notm}} Cloud into the {{site.data.keyword.monitoringlong}} service.

* Build reusable dashboards and make them interactive. {{site.data.keyword.monitoringlong}}’s hosted Grafana provides support for building custom dashboards with a large palate of visualization options.  Make your dashboards dynamic with templating by using metric queries with variables.

* Access your service through the {{site.data.keyword.Bluemix_notm}} catalog. {{site.data.keyword.monitoringlong}} is available as a service tile in the DevOps section of the {{site.data.keyword.Bluemix_notm}} catalog.  For the {{site.data.keyword.containershort}} service with single and group containers, you can access the service from the {{site.data.keyword.Bluemix_notm}} UI.

* Choose the service plan that fits your needs. You may choose the Lite service plan or the Premium service plan to match your usage needs. The Lite plan offers metric collection at once per minute, retention for 15 days, and complementary alerting.  Alternatively, you can select the Premium plan to enable greater consumption, longer metrics retention, and to gain access to the service APIs, for example, to send or retrieve metrics from the {{site.data.keyword.monitoringlong}} service. {{site.data.keyword.monitoringlong}} offers metric collection at once per minute.  The Lite plan retains metrics at full resolution for 15 days. The Premium plan retains metrics at full resolution for 45 days.

The legacy {{site.data.keyword.monitoringshort}} service collected metrics at service defined frequencies starting at 30 seconds, and summarized to 1 hour frequencies over time. {{site.data.keyword.monitoringlong}} now offers full resolution collection at 1 minute.  The Lite plan retains metrics for 15 days.  The Premium plan retains metrics for 45 days.

For more information about the {{site.data.keyword.monitoringlong}} service, refer to [the Getting started with Monitoring documentation](/docs/services/cloud-monitoring/index.html#getting-started-with-ibm-cloud-monitoring) or [the IBM Cloud Monitoring – Service Refresh with New Features![External link icon](../../icons/launch-glyph.svg "External link icon")](https://www.ibm.com/blogs/bluemix/2017/07/ibm-cloud-monitoring-service-refresh-new-features/).

### {{site.data.keyword.contdelivery_short}} upgrade
New as of: 11 July 2017

Benefits of the upgrade include bug fixes, performance improvements, and refinements to the user experience. Noteworthy enhancements, if not already present on your environment, include:
<ul>
<li>Fixes and improvements to internationalization and accessibility.</li>
<li>Toolchain access control, available from a toolchain's Manage tab.</li>
<li>New tool integrations in the Continuous Delivery tool catalog.</li>
<li>Improved grouping of multiple workspaces in the Orion Web IDE.</li>
<li>Support for multiple editor tabs in the Orion Web IDE.</li>
<li>Support for UI themes in the Orion Web IDE.</li>
</ul>

### {{site.data.keyword.uccr_short}} beta
New as of: 23 June 2017

{{site.data.keyword.uccr_short}} is an enterprise-scale release management solution that supports both cloud-native and on-prem deployment tools.

The beta version of {{site.data.keyword.uccr_short}} provides the following key features:
* Use releases to manage multiple deployment plans and events, and collaborate on multi-team release efforts.
* Create events for any release-related activity and manage them with the calendar.
* Import your own events and releases.
* Customize calendar events to fit your organization.
* Use email and Slack type tasks for release notifications.

### dashDB for Transactions has been renamed to {{site.data.keyword.Db2Hosted_notm}}
New as of: 14 June 2017

IBM {{site.data.keyword.DB2OnCloud_short}} is the new name for dashDB for Transactions. As part of this renaming the former self-managed IBM {{site.data.keyword.DB2OnCloud_short}} service will also be renamed to IBM Db2 Hosted. At this time only display names are updated, so any APIs or command line interfaces remain unchanged.

### {{site.data.keyword.sparks}} updates: Stocator-S3 connector includes support for IBM Cloud Object Storage Cross Region service (Beta)
New as of: 05 June 2017

{{site.data.keyword.sparks}} users can now access and do analytics on data stored in the IBM Cloud Object Storage Cross Region service. This capability is offered as a Beta. IBM Cloud Object Storage offers high-capacity, cost-effective storage for analytics and other applications that is scalable, flexible and simple to use.

The Apache Spark accesses IBM Cloud Object Storage data through a storage connector based on Stocator technology, which is implicitly designed for object storage and thus faster than legacy object storage connectors. As a user, you do not need to change or recompile Apache Spark code.

[Access and Analyze data in IBM Cross Region Cloud Object Storage](https://www.ibm.com/blogs/bluemix/2017/06/access-analyze-data-ibm-cross-region-cloud-object-storage/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") blog post describes usage of IBM Cloud Object Storage data with {{site.data.keyword.sparks}} on {{site.data.keyword.Bluemix_notm}} and the IBM Data Science Experience (DSx).

Please reach out to us at [sparksrv@us.ibm.com](sparksrv@us.ibm.com), if you have any questions or comments. Your input is greatly appreciated!

### New scalable plan available for {{site.data.keyword.dashdbshort_notm}} for Transactions
New as of: 31 May 2017

A new plan is available for {{site.data.keyword.dashdbshort}} for Transactions that can grow with your database needs. The new Flex plan allows you to start with a small system and grow the power and storage capacity of that system easily and quickly. {{site.data.keyword.dashdbshort}} for Transactions is 100% DB2-compatible and provides a 99.95% SLA on high availability plans.

### New Updates to {{site.data.keyword.mobilepush}} service on {{site.data.keyword.Bluemix_notm}}
New as of: 24 May 2017

The following are the new updates available for {{site.data.keyword.mobilepush}} service on {{site.data.keyword.Bluemix_notm}}

**Lite Plan**: We are introducing a new Lite Plan in addition to the existing Basic Plan for {{site.data.keyword.mobilepush}} Service. As per the new plan the users can send upto hundred thousand digital messages for free per month. While upgrading from Lite plan to basic plan, the user is charged after one million digital messages. The count to one million messages starts when the Lite plan is upgraded to the basic plan.

**Monitoring**: You can now get insights on notifications sent and devices registered in the {{site.data.keyword.mobilepush}} Service Console. You can also use REST API's for message level tracking. From message delivery to message dispatching to message receipt, the details can be obtained by configuring webhooks.  See [Monitoring for {{site.data.keyword.mobilepush}}](/docs/services/mobilepush/t_push_monitoring.html#monitor-notifications).

**Web Notifications**: You can now send notifications to Safari Web browsers.

### Secure Gateway Updates
New as of: 24 May 2017

The latest Secure Gateway maintenance update includes minor bug fixes in the UI and API manager, updated documentation, and the client has been updated to version 1.7.1. The Secure Gateway client is now available on AIX 7.1+ and supports connecting outbound through a squid proxy.

### {{site.data.keyword.streaminganalyticsshort}} service updates: Develop Streams applications in your Python development environment
New as of: 13 April 2017

In the past, you had to install a local version of IBM Streams to develop Python applications. That’s no longer the case. Now you can develop applications with Python in your favorite development environment or in a Jupyter interactive notebook.

You can use the STREAMING_ANALYTICS_SERVICE context to submit a Python application to the {{site.data.keyword.streaminganalyticsshort}} service. The {{site.data.keyword.streaminganalyticsshort}} service requires Python 3.5.

You can create sample Python applications using Jupyter notebooks in IBM Data Science Experience (DSX), and submit these applications to the {{site.data.keyword.streaminganalyticsshort}} instance directly from DSX. Check out the sample stream-processing Python applications in notebooks on the [DSX community page](https://datascience.ibm.com/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon").

For more information about the {{site.data.keyword.streaminganalyticsshort}} service updates, see [{{site.data.keyword.streaminganalyticsshort}} updates: DSX integration and easier Python development](https://www.ibm.com/blogs/bluemix/2017/05/streaming-analytics-updates-dsx-integration-easier-python-development/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon").

### {{site.data.keyword.sparks}} updates: Apache Spark 2.1 is supported now
New as of: 21 April 2017

{{site.data.keyword.sparkl}} is introducing the support for Apache Spark 2.1 to create algorithms that harness insights from complex data. Apache Spark 2.1 will help significantly around structured streaming with added support for event time watermarks and Kafka 0.10. Apache Spark 2.1 also focused on increasing stability and usability in Spark SQL, SparkR and the MLlib modules. For more details on Spark 2.1, see [Spark Release 2.1.0](http://spark.apache.org/releases/spark-release-2-1-0.html).

We are happy to answer any questions related to {{site.data.keyword.sparkl}} or the newer version of Apache Spark 2.1 and are reachable at sparksrv@us.ibm.com.

### {{site.data.keyword.macm_short}} is being deprecated
New as of: 18 April 2017

As of March 30th, 2017, {{site.data.keyword.macm_long}} service tile will be removed from the {{site.data.keyword.Bluemix_notm}} Catalog and you will no longer be able to provision new MACM instances. However, existing instances will continue to be supported. The End of Support Date is 30 March 2018. Please delete your {{site.data.keyword.macm_short}} (MACM) service instances before the End of Support Date. We encourage users to migrate to the IBM Watson Content Hub. Watson Content Hub is available on IBM Marketplace and provides users with a 30-day free trial. IBM Watson Content Hub provides similar functionality to MACM with added new capabilities such as asset management, cognitive tagging using IBM Watson services, and included content delivery network (CDN) to ensure an optimal experience for your customers. IBM offers service engagments to migrate content from MACM to Watson Content Hub.


### {{site.data.keyword.sparks}} updates: Notebook support now in Data Science Experience
New as of: 11 April 2017

Your new platform to work with notebooks and Spark is Data Science Experience. Sign up to [Data Science Experience](http://datascience.ibm.com/), and start creating notebooks and sharing your expertise with other data scientists.

If you worked with notebooks in {{site.data.keyword.sparks}}, you can migrate your notebooks to Data Science Experience. For more information, see the [Migrating notebooks documentation](/docs/services/AnalyticsforApacheSpark/index-gentopic2.html#migration_to_dsx).


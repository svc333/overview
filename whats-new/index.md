---

copyright:

  years: 2015, 2019

lastupdated: "2019-03-13"

keywords: release notes, what's new, what is new, cloud updates

subcollection: overview

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# What's new in {{site.data.keyword.Bluemix_notm}}?
{: #whatsnew}

Stay up-to-date with the new features that are available in the {{site.data.keyword.Bluemix}} platform so that you get the most out of your {{site.data.keyword.Bluemix_notm}} experience. If you're looking for updates for the services available on {{site.data.keyword.Bluemix_notm}}, check out the [{{site.data.keyword.Bluemix_notm}} Announcements page](https://www.ibm.com/cloud/blog/announcements){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") on the blog.
{:shortdesc}

## {{site.data.keyword.Bluemix_notm}} platform
{: #platform_category}

### Multifactor authentication for users with federated IDs
New as of: 12 March 2019
{: #mfa-federated}

Account owners or users assigned the administrator role for the billing account management service can enable multifcator authentication (MFA) for all users in their account. Federated users who use their corporate or enterprise single sign-on ID can now be required to authenticate by using MFA for logging in to {{site.data.keyword.Bluemix_notm}}. For more information about this feature enhancement and what you need to know about enabling MFA for your account, see [Introducing MFA for IBM Cloud Users with Federated ID](https://www.ibm.com/blogs/bluemix/2019/03/introducing-mfa-for-ibm-cloud-users-with-federated-id/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon").

### New support experience for {{site.data.keyword.Bluemix_notm}}
New as of: 30 November 2018 
{: #support}

With the Support Center, you can work to resolve all {{site.data.keyword.Bluemix_notm}}-related issues. The landing page provides you FAQs, so you can find the answer to your question without even contacting {{site.data.keyword.Bluemix_notm}}. You can also chat with a live support rep. Your cases can now be managed in from a single location. Go to **Support** &gt; **Manage cases** to create, view, or edit cases.

You can also find the [Status page](https://cloud.ibm.com/status){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") from the Support Center. It has been enhanced to include all unplanned incidents, planned maintenance, announcements, and security bulletin notifications about key events that affect the {{site.data.keyword.Bluemix_notm}} platform, infrastructure, and major services. Click **View cloud status** from the Support Center. To check out the new experience, log in and go to the [Support Center](https://cloud.ibm.com/unifiedsupport/supportcenter){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon"). 

### Unified login, API keys, and user and access management in {{site.data.keyword.Bluemix_notm}}
New as of: 30 November 2018
{: #useraccess}

With our latest updates, you can take advantage of a simplified secure login that is available for all users regardless of your ID type. Whether you have an IBMid or a SoftLayer ID, you can quickly log in to the {{site.data.keyword.Bluemix_notm}} console from our enhanced login page. You can also make secure API calls across {{site.data.keyword.Bluemix_notm}} and automate your CLI login by using an IAM API key or an IAM access token. 

After you log in, you can now see all users including platform and classic infrastructure users from your Users page in the Access (IAM) UI. Depending on your access to view other users in the account, you can filter your view quickly by account users, classic infrastructure users, or Cloud Foundry org. You can also use the filters to find users quickly by name, email, or status.

Now that all of your users are in a single console, you can manage their access to all types of resources from the same place. Access starts with the user, so start by selecting a user from your list. Then, depending on which type of resource that you want to assign access to, you can choose from IAM access policies, Cloud Foundry access, or classic infrastructure permissions. If you're just looking to assign IAM access policies, try creating an access group to streamline your access management process by adding all users to the same access group that need the same policies assigned.

For more details, check out [Outstanding User Access Improvements Help Deliver a Unified {{site.data.keyword.Bluemix_notm}} Platform](https://www.ibm.com/blogs/bluemix/2018/11/ibm-cloud-access-management){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon"). 

### Find all {{site.data.keyword.Bluemix_notm}} CLI plug-in documentation in one place
New as of: 30 November 2018
{: #cli}

You can now access all of the {{site.data.keyword.Bluemix_notm}} CLI plug-in documentation in one location making it easier for you to find any CLI command that you are looking for on the {{site.data.keyword.Bluemix_notm}} platform. Check out the References section in the [CLI documentation](/docs/cli?topic=cloud-cli-ibmcloud-cli).

### Check out the new dashboard and resource list
New as of: 30 November 2018
{: #dash}

With our latest update, you can now view all your platform and infrastructure services from one location. When you log in, you can check out the new dashboard right away. After you have resources added to your account from the catalog, you can use the resource list to get a full view of your account resources. :

* The dashboard has been redesigned so that you can view a summary your resources, maintenance, status, apps, support, usage, and users.
* You can find more details about your resources in the resource list. You can tag your resources to organize them, or select them to make changes on the details page.
* Now that you can see all of your resources in one place, we've added a global search so that you can quickly find resources that you created and expect to appear on the Resource list page. 
* You can also search for catalog results, so you can quickly find resources to add to your account.  

See [Manage All Your Cloud Resources on the Enhanced {{site.data.keyword.Bluemix_notm}} Platform](https://www.ibm.com/blogs/bluemix/2018/11/manage-all-your-cloud-resources-on-the-enhanced-ibm-cloud-platform/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") for more details.

### Unified account, billing, and user profile information for platform and infrastructure services
New as of: 30 November 2018
{: #profile}

Your account, billing, and profile information is now simplified. You can view your account information for all of your platform and infrastructure resources in a unified console. 

* Your profile and settings area contains information about you as well as your email notification preferences for all resource types. 
* Your account information area contains information about your company or organization, account settings, and quick access for working with resource groups and Cloud Foundry orgs. You can even find best practices to help you get up and running quickly!
* Your billing and usage area of your account helps you understand your bill, make payments, monitor subscriptions, get quotes, track orders, and set spending notifications.

Check out [Bringing It All Together: A Single Account and Billing Management Experience](https://www.ibm.com/blogs/bluemix/2018/11/ibm-cloud-account-management/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") for more details.

### Organize your resources with tags
New as of: 30 November 2018
{: #tag}

Tags are now available for you to add to your resources, like Cloud Object Storage, to help you manage resources and find the resources that are the most relevant to you. For example, if you have hundreds of resources and you want to differentiate between a couple that are paid the same way, you could tag them with `costcenter:location01`. Or, if you have a team that is working on a couple of resources repeatedly, you can use something like `team-blue`. You can also filter your resource list by tags to quickly organize and find the resources that you need. For more information, see [Working with tags](/docs/resources?topic=resources-tag) and [Platform Tagging on the Enhanced {{site.data.keyword.Bluemix_notm}} Platform](https://www.ibm.com/blogs/bluemix/2018/11/platform-tagging-on-the-enhanced-ibm-cloud-platform/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon"). 

### Find accurate monthly costs with the cost estimator
New as of: 30 November 2018
{: #cost-estimator}

To help you decide and analyze what services you'd like to purchase, you can use the cost estimator. Now, you can go through the console and select each service you'd like to have, and add all of the costs in an easy to use tool. You can even enter projected data usages, lookups per second, writes per second, and queries per second to get a more accurate estimation of your monthly expendentures. You can use the cost estimator with each catalog service you select, or you can click the cost estimator icon ![Estimator icon](../../icons/Estimator.svg) in the console menu to get a summary of your estimated costs. For more information, see [Estimating your costs](/docs/billing-usage?topic=billing-usage-cost).

### Updated global location names for {{site.data.keyword.cloud_notm}}
New as of: 1 November 2018
{: #location-name-updates}

As {{site.data.keyword.cloud_notm}} continues to expand our global availability footprint, we’re updating our location naming structure to better support an understandable, consistent hierarchy of geographies, regions, and data centers around the world. If you’re familiar with our current global regions, you’ll recognize names like US South and Sydney. We’re aligning these location names to the names of the city in which the data centers physically exist.

For now, the programmatic IDs are not changing, so there’s no impact from an API perspective. The following table shows the old and new location names. For more information and a comprehensive list of data centers and regions, see [Service availability](/docs/resources?topic=resources-services_region).

| Previous Location Display Name | New Location Display Name | Code |
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
{: #acct-mgmt-services}

With {{site.data.keyword.cloud_notm}} Identity and Access Management (IAM), you can delegate common tasks that you complete as an account administrator to another user in your account. By creating an access policy on one or all of the available account management services, you can easily delegate responsibilities such as inviting and removing users, managing access groups, managing service IDs, maintaining private catalog services, and even monitoring billing and tracking usage. There are four individual account management services and an all services option that you can use to set up access policies:

* User Management for inviting and removing users
* IAM Access Groups for creating, editing, deleting, updating, and assigning access 
* IAM Identity Service for viewing, creating, deleting, and assigning access to service IDs and associated API keys across the account
* Global resource catalog for viewing private catalog offerings and updating the metadata and visibility for the offerings
* All account management services for access to each of the individual account management service options based on the assigned role as well as access to billing and usage tracking.

For more information on the tasks that a user can do based on which account management service they have a policy on and which role they are assigned, see [Example platform management roles and actions for account management services](/docs/iam?topic=iam-userroles#platformrolestable2). For more information about this new feature, see the [Introducing More Flexibility and Control for IBM Cloud Account Management Services Access](https://www.ibm.com/blogs/bluemix/2018/11/introducing-more-flexibility-and-control-for-ibm-cloud-account-management-services-access/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") blog post. 

### Searching for resources
New as of: 17 July 2018
{: #forward-slash-key}

You can search for resources from anywhere in the {{site.data.keyword.cloud_notm}} console. Type the name of a resource in the search field in the console menu bar. Press the Forward Slash key (/) to activate the search.

### Dynamically add federated users to access groups
New as of: 12 July 2018
{: #add-fed-users}

You can create dynamic rules to automatically add federated users to access groups based on specific identity attributes. When your users log in with a federated ID, the data from the identity provider dynamically maps your users to an access group based on the rules that you set. For more information, see [Creating dynamic rules for access groups](/docs/iam?topic=iam-rules).

### Protect your service IDs and API keys
New as of: 1 June 2018
{: #protect-svcid-apikey}

To avoid a situation where your service ID or API key is deleted causing an outage or disruption, you can lock service IDs and API keys by using the UI or CLI. Locking a service ID also prevents any access policies from being changed, deleted, or assigned as well as any API keys associated with the service ID from being created or deleted. For more information, see [Locking a service ID](/docs/iam?topic=iam-serviceidapikeys#lockkey) and [Locking an API key](/docs/iam?topic=iam-userapikey).

### Upgrade your Lite account to a Subscription account
New as of: 31 May 2018
{: #upgrade-lite}

You can now upgrade your Lite account to a Subscription account directly from the {{site.data.keyword.Bluemix_notm}} console. With a Subscription account, you can use both platform and infrastructure offerings, and take advantage of discounted pricing by making a monthly spending and term commitment. You can also avoid surprises with fixed billing on a monthly payment schedule, but with the flexibility to order more or less based on your needs. For more information, see [Subscription account FAQS](/docs/billing-usage?topic=billing-usage-billusagefaqs#subs-order). 

### {{site.data.keyword.Bluemix_notm}} CLI rebranding
New as of: 15 May 2018
{: #cli-rebrand}

The {{site.data.keyword.Bluemix_notm}} CLI commands have changed from **`bluemix`** and **`bx`** to **`ibmcloud`**. However, you can still use the **`bluemix`** and **`bx`** CLI commands until they are removed later. There is no short name now, just the full name **`ibmcloud`**. 

### Multi-factor authentication for your {{site.data.keyword.Bluemix_notm}} account
New as of: 02 May 2018
{: #account-mfa}

Multi-factor authentication (MFA) adds an extra layer of security to your account by requiring all users to provide a time-based one-time passcode in addition to their standard IBMid and password during login. This is also commonly known as two-factor authentication (2FA). MFA is enabled per account, and once it is turned on, all users in the account are required to log in by using the extra security measure. For more information, see the [IBM Cloud Platform now adds support for Multi-Factor Authentication](https://www.ibm.com/blogs/bluemix/2018/05/ibm-cloud-platform-now-adds-support-multi-factor-authentication/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") blog post.

### Assign access quickly by using access groups
New as of: 03 April 2018
{: #access-groups}

Do you want to be able to assign access quickly by using the least number of policies possible? Now you can with access groups. Access groups enable you to group a set of users and service IDs together and assign a single policy that applies to all members of the group. By using access groups, you can limit the time that you spend managing access to the users and service IDs in your account. Check out the blog post [New feature: Access groups](https://www.ibm.com/blogs/bluemix/2018/04/access-groups/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") for more details.

### SoftLayer and {{site.data.keyword.Bluemix_notm}} account linking
New as of: 01 March 2018
{: #account-completion}

You can link your SoftLayer account to your {{site.data.keyword.Bluemix_notm}} account to log in to a single location, the {{site.data.keyword.Bluemix_notm}} console, and access both infrastructure as a service (IaaS) and platform as a service (PaaS) resources. If you're new to {{site.data.keyword.Bluemix_notm}}, create and link an account to get a free {{site.data.keyword.Bluemix_notm}} Lite account. Or, if you already have an {{site.data.keyword.Bluemix_notm}} account with PaaS resources, link your accounts to receive a single bill for both your IaaS and PaaS resources. Check out [Steps to Link your IaaS and PaaS Accounts](https://www.ibm.com/blogs/bluemix/2018/03/follow-steps-link-iaas-paas-accounts/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") to quickly link your accounts.


### {{site.data.keyword.Bluemix_notm}} Foundry Service US East region is now available
New as of: 15 December 2017
{: #cf-useast}

A new US East data center is now available in Washington, DC. This new region can be reached using the `us-east.cloud.ibm.com` endpoint. For details on the services that are available for purchase in this new region, see [Services by region](/docs/resources?topic=resources-services_region).

### Support for resources in the European Union
New as of: 14 December 2017
{: #eu-resources}

If your services and data centers are located in Europe, {{site.data.keyword.Bluemix_notm}} now offers extra capabilities to protect your data in the European Union. You can request that support is provided by customer success teams that are located in Europe. This support is available 24 hours a day, 7 days a week. See [Enabling the EU supported option](/docs/account?topic=account-eu-hipaa-supported#bill_eusupported) and [Requesting support for resources in the European Union](/docs/get-support?topic=get-support-getting-customer-support#eusupported) for more information.

### Withdrawal of support for TLS 1.0 and 1.1
New as of: 28 November 2017
{: #nosupport-tls}

On 1 March 2018 {{site.data.keyword.Bluemix_notm}} will withdraw support for TLS 1.0 and TLS 1.1 across many of our cloud products and services as part of our commitment to offering a cloud that is secure to the core and in alignment with industry best practices for security and data privacy. To learn more about how this change affects you and what actions you might need to take, see [Withdrawal of support for TLS 1.0 and 1.1](/docs/get-support?topic=get-support-tlssupportwithdraw).

### A new way to organize resources within your account
New as of: 16 November 2017
{: #usergs}

Resource groups are a new way for you to create customizable groupings of account resources, and access to the group and the resources within it are managed by using Identity and Access Management (IAM). Everyone starts out with a default resource group. You can rename this resource group and add new service instances to it as you create them from the catalog.

For users with a Pay-As-You-Go or Subscription account, you can create additional resource groups to make managing quota and viewing billing usage for a set of resources easier. You can also group resources to make it easier for you to assign users access to more than one service at a time. To learn more about working with resource groups for your account, see [Managing resource groups](/docs/resources?topic=resources-rgs).

### Updates for {{site.data.keyword.Bluemix_notm}} IAM
New as of: 16 November 2017
{: #iam-nov17}

The introduction of resource groups within your {{site.data.keyword.Bluemix_notm}} account has opened up a new way for you to assign access. Users and service IDs can be assigned access to all services within a resource group enabling you to quickly assign access to more than one resource at a time. You can also customize access for each user or service ID by assigning access to just some services within a resource group, or you choose to assign access to individual resources down to the service instance level. For more information about the features that you can take advantage of by using IAM, see [What features does IAM provide?](/docs/iam?topic=iam-iamoverview#features)

### Customize your dashboard view
New as of: 16 November 2017
{: #custom-dash}

You can view and manage all the resources in your account from your dashboard in the {{site.data.keyword.Bluemix_notm}} console. And now, you can set filters to customize your view. For example, you can filter by resource group to view the specific resources in a resource group. You can also filter by region or Cloud Foundry space. For more details, see [Managing resources on the dashboard](/docs/overview?topic=overview-ui#dashboardview).

### Support Center
New as of: 2 November 2017
{: #support-nov17}

We now have the new Support Center where you can search for information, post questions to our developer community, and manage tickets. Go to **Support > Support Center** in the {{site.data.keyword.Bluemix_notm}} console menu bar.

### Introducing IBM Cloud
New as of: 31 October 2017
{: #meet-ibmcloud}

Bluemix is now IBM Cloud. Besides rolling out our new name, nothing changes. You can still easily build and run your apps and services as always. Check out the [IBM Cloud Blog](https://www.ibm.com/blogs/bluemix/2017/10/bluemix-is-now-ibm-cloud/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") for more details.

### Lite account
New as of: 31 October 2017
{: #new-liteacct}

A Lite account is our new account type that gives you access to try select services for free with no time restrictions. This new account also includes usage tracking and efficiency features to help you better manage your resources. To learn more about what's available, see [Account types](/docs/account?topic=account-accounts#liteaccount).

### Identity and Access Management application authentication feature
New as of: 6 October 2017
{: #app-authfeature}

Identity and Access Management (IAM) now provides the ability to create a Service ID, which you can think of as an identity that can be used for apps to authenticate with your {{site.data.keyword.Bluemix_notm}} services. Instead of using individual user credentials, a Service ID can be created with an associated API key and access permissions in the form of a service policy that is assigned to the Service ID in order for you to control the level of access for any application authenticating with that ID.

For more information about the benefits of this feature and how to get started, see the [Introducing IBM Cloud IAM Service IDs and API Keys](https://www.ibm.com/blogs/bluemix/2017/10/introducing-ibm-cloud-iam-service-ids-api-keys/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon").

### {{site.data.keyword.Bluemix_notm}} global catalog
New as of: 27 July 2017
{: #gc}

Expanding on the last console update to manage your public regions from a single location in the console, {{site.data.keyword.Bluemix_notm}} now has a global catalog, making the process of selecting and deploying items that you select from the catalog a more streamlined process. Regardless of the region you have selected in the console, you can now see all services that are available across all public regions from your catalog. Once you select a tile from the catalog, you can see which regions the service is available in, and select where you want to deploy it. For more information about the latest updates to the catalog, see [A global {{site.data.keyword.Bluemix_notm}} catalog makes building things easier](https://www.ibm.com/blogs/bluemix/2017/07/global-bluemix-catalog-makes-building-things-easier/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon").

### {{site.data.keyword.Bluemix_notm}} console updates
New as of: 23 May 2017
{: #console-may17}

You can now manage your public regions from a single location through the updated {{site.data.keyword.Bluemix_notm}} console. The region selector offers you streamlined access to your resources, and other enhancements include higher availability and improved performance. For more information, check out [New Global Bluemix UI for Higher Availability and More](https://www.ibm.com/blogs/bluemix/2017/05/new-global-bluemix-ui-higher-availability/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon").

### Identity and access management
New as of: 01 May 2017
{: #iam-may17}

With the latest updates and improvements, {{site.data.keyword.Bluemix_notm}} account owners or administrators can now use a new unified access control UI to take advantage of the following capabilities:
 * Manage users' fine-grained access to Kubernetes services and other services as they adopt the new access control features
 * Assign service policies and Cloud Foundry roles to users within their organizations

Additionally, {{site.data.keyword.Bluemix_notm}} platform users can create, delete, and list API keys associated with their user IDs. And platform users can use those API keys to authenticate when using APIs or CLIs.

Lastly, we’ve enhanced our unified user management capability to ensure that in a linked IaaS-PaaS account, users are managed in a unified way with no need to add users separately in the SoftLayer Customer Portal or the {{site.data.keyword.Bluemix_notm}} console.

For more information, check out the [Introducing Identity & Access Management](https://www.ibm.com/blogs/bluemix/2017/05/introducing-identity-access-management/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") blog post.

### Navigation design changes for {{site.data.keyword.Bluemix_notm}} docs
New as of: 13 April 2017
{: #docnavupdates}

With this navigation update, we think you'll understand how content is organized throughout our docs better, and will be able to find relevant content more efficiently. With fewer nested layers of content, you won't have to dig around to find the documentation you need to be successful with {{site.data.keyword.Bluemix_notm}}.


## {{site.data.keyword.Bluemix_local_notm}} and {{site.data.keyword.Bluemix_dedicated_notm}}
{: #dedicatedandlocal}

### February updates for the administration console
New as of: 28 February 2018
{: #feb18adminconsole}

With the latest update from February 2018, you can use the following new feature:

#### New permission for managing maintenance updates
{: #newmngmaintpermission}

A new user permission has been introduced to specifically allow users to approve and reschedule maintenance updates, as well as to set up maintenance update windows that stipulate when maintenance updates can be deployed into a dedicated environment.
See the [video demonstration](https://youtu.be/7c7jyp_JJWU){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") for more information.

### December updates for the administration console
New as of: 14 December 2017
{: #december17adminconsole}

With the latest updates and improvements from December, you can use the following new features:

#### Subscribe to notifications for average CPU usage threshold
{: #avgcputhresholdnotifications}

Average CPU has been added as a threshold type in notification subscriptions. You can now receive notifications when CPU usage (averaged across all DEA's and Diego Cells) goes above or below a certain threshold.

#### Control access to cloud systems in the European Union
{: #euaccesscontrol}

Combined with the new capability in the European Union to support cloud resources (starting with Frankfurt), the administration console now has the capability to define policies that control access by IBM personnel. You can manage access control policies, view access requests, take action on the requests, and track the history.

#### Enhanced information in security reports
{: #enhancedsecreportinfo}

Security reports now include user-friendly names in addition to unique IDs for users and organizations.

### August updates for the administration console
New as of: 31 August 2017
{: #august17adminconsole}

With the latest updates and improvements from August, you can use the following new features:

#### Updates to {{site.data.keyword.cloudant_short_notm}} service usage metrics
{: #svcusagemetricsupdates}

  * The computation of usage metrics for {{site.data.keyword.cloudant_short_notm}} has been updated to reflect the total number of GBs used and available across all nodes in a {{site.data.keyword.cloudant_short_notm}} cluster. Typically, a {{site.data.keyword.cloudant_short_notm}} cluster contains three nodes, and a document in the database is replicated across all the nodes in the cluster for high-availability and disaster recovery. With the August updates, the capacity metric in the {{site.data.keyword.cloudant_short_notm}} dial (available in the _Resource Usage > Services_ view) indicates the space across all the nodes in the cluster. For example, if a single {{site.data.keyword.cloudant_short_notm}} cluster contains three nodes, each with 1000-GB capacity, the capacity limit is 3000 GB. If 1500 GBs of that capacity have been used, the {{site.data.keyword.cloudant_short_notm}} usage metric is 50%.

#### Updates to the scheduling of maintenance updates
{: #maintscheduleupdates}

  * In {{site.data.keyword.Bluemix_dedicated_notm}}, customers can manage the dates and times when their dedicated environments are available for deployment of system updates. Customers can define availability windows representing dates and times when maintenance updates can and cannot be deployed to their Dedicated environment. In the August update, _Available Update Windows_ have been renamed _Update Windows_, and _Unavailable Update Windows_ have been renamed _Blackout Windows_. Beyond the terminology changes, customers now have more flexibility and margin for defining blackout (unavailable) dates. Once requested, blackout dates require IBM approval, and the time it takes to gain approval will vary. When the requested blackout dates are approved, IBM will cancel any existing updates that are currently scheduled during the unavailable window. IBM will also create new records for these updates and schedule them outside the approved blackout dates.

See the [video demonstration](https://bit.ly/2eCQNvu){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") for more information.

### July updates for the administration console
New as of: 31 July 2017
{: #july17adminconsole}

With the latest updates and improvements from July, you can use the following new features:

#### Updates to resource usage history capabilities
{: #resourceusagehistoryupdates}

  * In the previous update (June), the History view for memory and disk usage had introduced display of usage data over the last 48 hours, 30 days, and 5 months. In this latest July update, the resource usage history functionality has been expanded to allow customization of the time span for which to show resource usage data. Hourly, daily, and monthly views remain, but users can now specify a start day/time and duration for which to display memory and disk usage metrics (for example, showing memory usage for 15 days starting on July 1st 2017).
  * A new CLI command has been introduced to display resource metrics history in the CLI. The parameters of the command, as well as usage examples can be found by typing the following: `_cf ba resource-metrics-history -help_`

See the [video demonstration](https://youtu.be/QBij0jB5qAk){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") for more information.

### June updates for the administration console
New as of: 26 June 2017
{: #june17adminconsole}

With the latest updates and improvements from June, you can use the following new features:

#### Updates to the Resource Usage Page
{: #resourceusagepageupdates}

  * System resources
    * The History view for memory and disk has been updated to display data over 48 hours, 30 days, and 5 months
    * A Learn More link is provided, showing how the administration console metrics api is used to generate the History views
  * Applications
    * Provides usage information for all applications in the environment
    * Sort by application name, physical memory, reserved memory, physical disk, reserved disk, physical CPU, or Organization name
    * Search is provided to filter results by application name and Organization name
    * A Learn More link is provided, showing how the administration console metrics api is used to generate the Applications view

See [Resource usage](/docs/hybrid?topic=hybrid-mng#resourceusage) for more information.

#### Updates to API for Metrics
{: #apiformetricsupdates}

  * Environment statistics have been added, providing averages by day or month for memory and disk consumption

See [API for Metrics](/docs/hybrid?topic=hybrid-mng#envappmetricsapi) for more information.

### May updates for the administration console
New as of: 30 May 2017
{: #may17adminconsole}

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
New as of: 2 May 2017
{: #april17adminconsole}

With the latest updates and improvements from April, you can use the following new features:

 * Newly designed status app for {{site.data.keyword.Bluemix_notm}} Dedicated and Local environments. You can quickly search by component name or date of posting. You can also switch between the component status posts view and the notifications specific to your environment. See the [New {{site.data.keyword.Bluemix_notm}} Status Page](https://www.ibm.com/blogs/bluemix/2017/05/new-bluemix-status-page/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") blog post for more information.
 * Service usage data for select services from the Resource Usage tile. See [Service usage details](/docs/hybrid?topic=hybrid-servicesresourceusage#servicesresourceusage) for more information about what services are supported and what you can expect from the new view.

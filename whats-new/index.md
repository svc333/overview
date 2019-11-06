---

copyright:

  years: 2015, 2019

lastupdated: "2019-11-05"

keywords: release notes, what's new, what is new, cloud updates, new features, platform

subcollection: overview

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:tip: .tip}

# What's new in {{site.data.keyword.Bluemix_notm}}?
{: #whatsnew}

Stay up-to-date with the new features that are available on the {{site.data.keyword.Bluemix}} platform so that you get the most out of your {{site.data.keyword.Bluemix_notm}} experience. 
{:shortdesc}

If you're looking for updates for the services that are available on {{site.data.keyword.Bluemix_notm}}, check out the [Announcements page](https://www.ibm.com/cloud/blog/announcements){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") on the {{site.data.keyword.Bluemix_notm}} blog.
{: tip}

## {{site.data.keyword.Bluemix_notm}} platform
{: #platform_category}

### Bitnami Helm charts now available on {{site.data.keyword.cloud_notm}}
{: #bitnami}
New as of: 04 November 2019

{{site.data.keyword.IBM_notm}} and VMware are partnering to provide the [Bitnami Application Catalog](https://bitnami.com/stacks){: external} to {{site.data.keyword.cloud_notm}} customers. The first set of offerings available in the {{site.data.keyword.cloud_notm}} catalog are the Bitnami Helm charts, which Bitnami has created and validated to work on the {{site.data.keyword.containerlong_notm}}. Kubernetes developers typically install Helm charts manually from the CLI by using the helm command. However, this installation process has been simplified by building an auto-installation feature in the {{site.data.keyword.cloud_notm}} catalog. Check out these offerings today by selecting **Bitnami** from the **Provider** filter.

### Apply promo codes to your account and services
{: #promo-codes}
New as of: 18 October 2019

{{site.data.keyword.Bluemix_notm}} now has promo codes that you can use to get credit toward your account and services. Promo codes are provided by {{site.data.keyword.Bluemix_notm}} sales on a limited basis to customers with billable accounts. You can apply promo codes from a new Promotions page or from the catalog when you create a resource in the {{site.data.keyword.Bluemix_notm}} console. For more information, see [Applyng promo codes](/docs/billing-usage?topic=billing-usage-applying-promo-codes).

### Download access reports for specific resources
{: #access-report}
New as of: 17 October 2019

Have you ever wanted to get a quick view of all users, service IDs, access groups, and services that have access to a specific resource in your account? Well, now you can download a report that includes details about who can access your resource. From the resource list in your account, you can select the **Export access report** option in the row for an IAM-enabled resource to get the report. For more information about the types of data available in the report and who has access to view the report, see [Exporting an access report](/docs/resources?topic=resources-access-report).

### Mapping actions to IAM roles 
{: #actions-iam}
New as of: 15 October 2019

When you invite a user to your account or assign an existing user IAM access, you can review each action that is mapped to a role. Click the **Actions for role** option to view a list of all actions that are mapped to a specific role when you're selecting the roles to assign in an access policy. By reviewing the action to role mappings, you can have confidence that you are always assigning the correct level of access to users in your account. For more information about this new enhancement, see [Invite User Flow and Transparent Actions](https://www.ibm.com/cloud/blog/announcements/invite-user-flow-and-transparent-actions){: external}.

### Cloud Paks and Schematics templates are now available in the {{site.data.keyword.Bluemix_notm}} catalog
{: #cloud-paks-terraform}
New as of: 4 October 2019

With the deployment power of the {{site.data.keyword.Bluemix_notm}} Schematics service, we now deliver bundled solutions through packaged software and deployable automation scripts that empower you to build, manage, and modernize your cloud architectures faster and more securely. The first release of these offerings include IBM Cloud Paks and a handful of useful Terraform-based templates. 

From the [catalog](https://cloud.ibm.com/catalog), filter by the offering type and deployment target to find what you're looking for faster. Select **Cloud Paks** and **Terraform** to check out the new offerings that are available.

### Term-based model for {{site.data.keyword.Bluemix_notm}} support subscriptions
{: #support-subscriptions}
New as of: 23 September 2019

New subscriptions for {{site.data.keyword.Bluemix_notm}} support now follow the same term-based model as subscriptions for {{site.data.keyword.Bluemix_notm}} platform services. Rather than credit being valid in monthly increments, credit is now available up front for an entire subscription term, which can be up to one year's worth of credit. You now have more flexibility to use your support credit when you need it, and the chances of incurring monthly overages are reduced. When you buy or renew a support subscription, any existing active support subscriptions are converted to this new flexible model for the remainder of their term. For more information, see [Support subscriptions](/docs/account?topic=account-accounts#support-subscriptions).

You can also now view your support subscriptions in the {{site.data.keyword.Bluemix_notm}} console so you can keep track of your available credit. For more information, see [Viewing your support costs](/docs/billing-usage?topic=billing-usage-support).

### Redirecting SoftLayer to {{site.data.keyword.Bluemix_notm}} 
{: #sl-redirect}
New as of: 12 September 2019

SoftLayer account owners who previously didn't have access to the {{site.data.keyword.Bluemix_notm}} platform can now manage their infrastructure, services, and applications from one location: [cloud.ibm.com](https://cloud.ibm.com){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon"). For more details, see [Transitioning to the {{site.data.keyword.Bluemix_notm}} experience](/docs/overview?topic=overview-ui#redirect-cloud).

### {{site.data.keyword.Bluemix_notm}} enterprises for centrally managing multiple accounts
{: #ibm-cloud-enterprises}
New as of: 25 July 2019

You can now centrally manage billing and usage for multiple accounts by creating an {{site.data.keyword.Bluemix_notm}} enterprise. With an enterprise, you can create a multitiered hierarchy of accounts by organizing related accounts into account groups. Enterprises simplify management of multiple accounts with the following key features:
   * Consolidated billing means that you can manage billing, invoicing, and payment for all accounts from a single place, the enterprise account. 
   * Subscription credit is aggregated into a credit pool and shared with all accounts in the enterprise. Not only is tracking your subscriptions easier, but you can get fewer, larger subscriptions for a better discount because the credit is shared. 
   * Top-down usage reporting gives you a unified view of usage costs from all accounts, organized according to your enterprise hierarchy. 

If you have multiple accounts, at least one of which is a Subscription account, you can create an enterprise. See [What is an enterprise?](/docs/account?topic=account-enterprise) and [Introducing IBM Cloud Enterprises](http://www.ibm.com/cloud/blog/announcements/Introducing-IBM-Cloud-Enterprises){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") for more information.

### Subscriptions page for tracking subscription credit spending
{: #subscriptions-page}
New as of: 18 July 2019

If you have a Subscription account, you can now view all of your subscriptions and analyze your credit spending on the Subscriptions page. You get a high-level view of the total subscription credit in your account and detailed charts that visualize trends such as your credit burndown and monthly spending. You can also view credit from any promotions in your account. For more information, see [Managing subscriptions](/docs/billing-usage?topic=billing-usage-subscriptions).

Additionally, to better reflect their usage, codes that you apply to add subscription credit to your account are now called subscription codes rather than feature codes.

### Managing SoftLayer SAML federation on {{site.data.keyword.cloud_notm}}
{: #saml-federation}
New as of: 02 July 2019

Former SoftLayer users who set up a SAML identity provider for logging in with federated IDs can now manage their configuration data in the {{site.data.keyword.cloud_notm}} console in Access (IAM) on the Identity providers page. This type of federation is deprecated, so new identity providers can't be set up currently. You can continue to update your identity provider data or choose to delete this federation in favor of switching to [federating with IBMid](/docs/account?topic=account-signup#signup-federated).

### Custom dashboard
{: #custom}
New as of: 14 June 2019 

You can now control what's displayed on your dashboard. Customizing your dashboard includes the ability to add, remove, and rearrange the widgets. For more information, see [Customizing your dashboard](/docs/account?topic=account-custom-dashboard).

### Export usage data with associated tags
New as of: 4 April 2019 

You can now utilize our newest tagging capabilities to manage resources, usage, and costs in the exported usage report. When you add a tag to a resource, you can view the tag that is associated with the resource. Go to **Manage**> **Billing and Usage**> **Usage**> **Export CSV**>  **Instances** to download your usage report. For more information on exporting tags, check out the [Export tags within your usage data to help with cost allocation](https://www.ibm.com/cloud/blog/export-your-tagged-usage-data-within-the-enhanced-ibm-cloud){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") blog post.

### Access group for enabling public access to resources
New as of: 25 March 2019

You can now enable public access to objects in your {{site.data.keyword.cos_full}} buckets by using a new access group that is provided for you in your account. This new access group is called the `Public access` group, and all users and service IDs are added to it by default. You can update the policies for the access group to enable all users, even unauthenticated users, access to the resource that you specify in the policy. [Learn more about the public access group](/docs/iam?topic=iam-public#public).

### Multifactor authentication for users with federated IDs
New as of: 12 March 2019
{: #mfa-federated}

Account owners or users assigned the administrator role for the billing account management service can enable multifcator authentication (MFA) for all users in their account. Federated users who use their corporate or enterprise single sign-on ID can now be required to authenticate by using MFA for logging in to {{site.data.keyword.Bluemix_notm}}. For more information about this feature enhancement and what you need to know about enabling MFA for your account, see [Introducing MFA for IBM Cloud Users with Federated ID](https://www.ibm.com/cloud/blog/introducing-mfa-for-ibm-cloud-users-with-federated-id){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon").

### New appdomain.cloud host name option
New as of: 31 December 2018
{: #appdomain}

A new host name option `*.appdomain.cloud` is available on cloud.ibm.com.

Previously, the `mybluemix.net` domain was used for hosting apps in various deployment targets, such as {{site.data.keyword.containerlong_notm}} or Cloud Foundry. Any apps that are hosted on `mybluemix.net` are not impacted.

The subdomain for Cloud Foundry apps is `cf.appdomain.cloud`. The subdomain for apps that you deploy to {{site.data.keyword.containerlong_notm}} is `containers.appdomain.cloud`.

### New Cloud Foundry API endpoints
New as of: 30 November 2018
{: #cf-api-endpoints}

The legacy `api.*.bluemix.net` Cloud Foundry API endpoints are still available for backward compatibility. However, you can update scripts and infrastructure automation to use the following new Cloud Foundry API endpoints for your region:

* api.us-south.cf.cloud.ibm.com (previously api.ng.bluemix.net)
* api.eu-gb.cf.cloud.ibm.com (previously api.eu-gb.bluemix.net)
* api.us-east.cf.cloud.ibm.com (previously api.us-east.bluemix.net)
* api.eu-de.cf.cloud.ibm.com (previously api.eu-de.bluemix.net)
* api.au-syd.cf.cloud.ibm.com (previously api.au-syd.bluemix.net)

### New support experience for {{site.data.keyword.Bluemix_notm}}
New as of: 30 November 2018 
{: #support}

With the Support Center, you can work to resolve all {{site.data.keyword.Bluemix_notm}}-related issues. The landing page provides you FAQs, so you can find the answer to your question without even contacting {{site.data.keyword.Bluemix_notm}}. You can also chat with a live support rep. Your cases can now be managed in from a single location. Go to **Support** &gt; **Manage cases** to create, view, or edit cases.

You can also find the [Status page](https://cloud.ibm.com/status){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") from the Support Center. It is enhanced to include all unplanned incidents, planned maintenance, announcements, and security bulletin notifications about key events that affect the {{site.data.keyword.Bluemix_notm}} platform, infrastructure, and major services. Click **View cloud status** from the Support Center. To check out the new experience, log in and go to the [Support Center](https://cloud.ibm.com/unifiedsupport/supportcenter){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon"). 

### Unified login, API keys, and user and access management in {{site.data.keyword.Bluemix_notm}}
New as of: 30 November 2018
{: #useraccess}

With our latest updates, you can take advantage of a simplified secure login that is available for all users regardless of your ID type. Whether you have an IBMid or a SoftLayer ID, you can quickly log in to the {{site.data.keyword.Bluemix_notm}} console from our enhanced login page. You can also make secure API calls across {{site.data.keyword.Bluemix_notm}} and automate your CLI login by using an IAM API key or an IAM access token. 

After you log in, you can now see all users, including platform and classic infrastructure users, from your Users page in the Access (IAM) UI. Depending on your access to view other users in the account, you can filter your view quickly by account users, classic infrastructure users, or Cloud Foundry org. You can also use the filters to find users quickly by name, email, or status.

Now that all of your users are in a single console, you can manage their access to all types of resources from the same place. Access starts with the user, so start by selecting a user from your list. Then, depending on which type of resource that you want to assign access to, you can choose from IAM access policies, Cloud Foundry access, or classic infrastructure permissions. If you want to assign IAM access policies, try creating an access group to streamline your access management process by adding all users to the same access group that need the same policies assigned.

For more details, check out [Outstanding User Access Improvements Help Deliver a Unified {{site.data.keyword.Bluemix_notm}} Platform](https://www.ibm.com/cloud/blog/announcements/ibm-cloud-access-management){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon"). 

### Find all {{site.data.keyword.Bluemix_notm}} CLI plug-in documentation in one place
New as of: 30 November 2018
{: #cli}

You can now access all of the {{site.data.keyword.Bluemix_notm}} CLI plug-in documentation in one location, making it easier for you to find any CLI command that you are looking for. Check out the References section in the [CLI documentation](/docs/cli/reference/ibmcloud?topic=cloud-cli-ibmcloud_cli).

### Check out the new dashboard and resource list
New as of: 30 November 2018
{: #dash}

With our latest update, you can now view all your platform and infrastructure services from one location. When you log in, you can check out the new dashboard right away. After you add resources to your account from the catalog, you can use the resource list to get a full view of your account resources:

* The dashboard is redesigned so that you can view a summary your resources, maintenance, status, apps, support, usage, and users.
* You can find more details about your resources in the resource list. You can tag your resources to organize them, or select them to update the details page.
* Now that you can see all of your resources in one place, we added a global search so that you can quickly find resources that you created and expect to find on the resource list page. 
* You can also search for catalog results, so you can quickly find resources to add to your account.  

See [Manage All Your Cloud Resources on the Enhanced {{site.data.keyword.Bluemix_notm}} Platform](https://www.ibm.com/blogs/bluemix/2018/11/manage-all-your-cloud-resources-on-the-enhanced-ibm-cloud-platform/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") for more details.

### Unified account, billing, and user profile information for platform and infrastructure services
New as of: 30 November 2018
{: #profile}

Your account, billing, and profile information is now simplified. You can view your account information for all of your platform and infrastructure resources in a unified console. 

* Your profile and settings area contains information about you as well as your email notification preferences for all resource types. 
* Your account information area contains information about your company or organization, account settings, and quick access for working with resource groups and Cloud Foundry orgs. You can even find best practices to help you get up and running quickly!
* Your billing and usage area of your account helps you understand your bill, make payments, monitor subscriptions, get quotes, track orders, and set spending notifications.

Check out [Bringing It All Together: A Single Account and Billing Management Experience](https://www.ibm.com/cloud/blog/announcements/ibm-cloud-account-management){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") for more details.

### Organize your resources with tags
New as of: 30 November 2018
{: #tag}

Tags are now available for you to add to your resources, like Cloud Object Storage, to help you manage resources and find the resources that are the most relevant to you. For example, if you have hundreds of resources and you want to differentiate between ones that are paid the same way, you could tag them with `costcenter:location01`. Or, if you have a team that is working on a couple of resources repeatedly, you can use something like `team-blue`. You can also filter your resource list by tags to quickly organize and find the resources that you need. For more information, see [Working with tags](/docs/resources?topic=resources-tag) and [Platform Tagging on the Enhanced {{site.data.keyword.Bluemix_notm}} Platform](https://www.ibm.com/cloud/blog/announcements/platform-tagging-on-the-enhanced-ibm-cloud-platform){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon"). 

### Find accurate monthly costs with the cost estimator
New as of: 30 November 2018
{: #cost-estimator}

To help you decide and analyze what services you'd like to purchase, you can use the cost estimator. Now, you can go through the console and select each service you'd like to have, and add all of the costs in an easy to use tool. You can even enter projected data usages, lookups per second, writes per second, and queries per second to get a more accurate estimation of your monthly expenditures. You can use the cost estimator with each catalog service you select, or you can click the cost estimator icon ![Estimator icon](../../icons/Estimator.svg) in the console menu to get a summary of your estimated costs. For more information, see [Estimating your costs](/docs/billing-usage?topic=billing-usage-cost).

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

For more information on the tasks that a user can do based on which account management service they have a policy on and which role they are assigned, see [Example platform management roles and actions for account management services](/docs/iam?topic=iam-userroles#platformrolestable2). For more information about this new feature, see the [Introducing More Flexibility and Control for IBM Cloud Account Management Services Access](https://www.ibm.com/cloud/blog/announcements/introducing-more-flexibility-and-control-for-ibm-cloud-account-management-services-access){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") blog post. 

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

The {{site.data.keyword.Bluemix_notm}} CLI commands changed from **`bluemix`** and **`bx`** to **`ibmcloud`**. However, you can still use the **`bluemix`** and **`bx`** CLI commands until they are removed later. There is no short name now, just the full name **`ibmcloud`**. 

### Multi-factor authentication for your {{site.data.keyword.Bluemix_notm}} account
New as of: 02 May 2018
{: #account-mfa}

Multi-factor authentication (MFA) adds an extra layer of security to your account by requiring all users to provide a time-based one-time passcode in addition to their standard IBMid and password during login. This is also commonly known as two-factor authentication (2FA). MFA is enabled per account, and once it is turned on, all users in the account are required to log in by using the extra security measure. For more information, see the [IBM Cloud Platform now adds support for Multi-Factor Authentication](https://www.ibm.com/cloud/blog/ibm-cloud-platform-now-adds-support-multi-factor-authentication){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") blog post.

### Assign access quickly by using access groups
New as of: 03 April 2018
{: #access-groups}

Do you want to be able to assign access quickly by using the least number of policies possible? Now you can with access groups. Group a set of users and service IDs together and assign a single policy that applies to all members of the group. By using access groups, you can limit the time that you spend managing access to the users and service IDs in your account. Check out the blog post [New feature: Access groups](https://www.ibm.com/cloud/blog/access-groups){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") for more details.

### {{site.data.keyword.Bluemix_notm}} Foundry Service US East region is now available
New as of: 15 December 2017
{: #cf-useast}

A new US East data center is now available in Washington, DC. You can reach this new region by using the `us-east.cloud.ibm.com` endpoint. For details about the services that are available for purchase in this new region, see [Services by region](/docs/resources?topic=resources-services_region).

### Support for resources in the European Union
New as of: 14 December 2017
{: #eu-resources}

If your services and data centers are located in Europe, {{site.data.keyword.Bluemix_notm}} now offers extra capabilities to protect your data in the European Union. You can request that support is provided by customer success teams that are located in Europe. This support is available 24 hours a day, 7 days a week. See [Enabling the EU supported option](/docs/account?topic=account-eu-hipaa-supported#bill_eusupported) and [Requesting support for resources in the European Union](/docs/get-support?topic=get-support-getting-customer-support#eusupported) for more information.

### Withdrawal of support for TLS 1.0 and 1.1
New as of: 28 November 2017
{: #nosupport-tls}

On 1 March 2018 {{site.data.keyword.Bluemix_notm}} will withdraw support for TLS 1.0 and TLS 1.1 across many of our cloud products and services as part of our commitment to offering a cloud that is secure to the core and in alignment with industry best practices for security and data privacy.

### A new way to organize resources within your account
New as of: 16 November 2017
{: #usergs}

Resource groups are a new way for you to create customizable groupings of account resources, and access to the group and the resources within it are managed by using Identity and Access Management (IAM). Everyone starts out with a default resource group. You can rename this resource group and add new service instances to it as you create them from the catalog.

For users with a Pay-As-You-Go or Subscription account, you can create extra resource groups to make managing quota and viewing billing usage for a set of resources easier. You can also group resources to make it easier for you to assign users access to more than one service at a time. To learn more about working with resource groups for your account, see [Managing resource groups](/docs/resources?topic=resources-rgs).

### Updates for {{site.data.keyword.Bluemix_notm}} IAM
New as of: 16 November 2017
{: #iam-nov17}

The introduction of resource groups within your {{site.data.keyword.Bluemix_notm}} account provides a new way for you to assign access. Users and service IDs can be assigned access to all services within a resource group, enabling you to quickly assign access to more than one resource at a time. You can also customize access for each user or service ID by assigning access to just some services within a resource group, or you choose to assign access to individual resources down to the service instance level. For more information about the features that you can take advantage of by using IAM, see [What features does IAM provide?](/docs/iam?topic=iam-iamoverview#features)

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

Bluemix is now IBM Cloud. Besides rolling out our new name, nothing changes. You can still easily build and run your apps and services as always. Check out the [IBM Cloud Blog](https://www.ibm.com/cloud/blog/announcements/bluemix-is-now-ibm-cloud){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") for more details.

### Lite account
New as of: 31 October 2017
{: #new-liteacct}

A Lite account is our new account type that gives you access to try select services for free with no time restrictions. This new account also includes usage tracking and efficiency features to help you better manage your resources. To learn more about what's available, see [Account types](/docs/account?topic=account-accounts#liteaccount).

### Identity and Access Management application authentication feature
New as of: 6 October 2017
{: #app-authfeature}

Identity and Access Management (IAM) now supports service IDs, which you can think of as identities that can be used for apps to authenticate with your {{site.data.keyword.Bluemix_notm}} services. Instead of using individual user credentials, a Service ID can be created with an associated API key and access permissions in the form of a service policy that is assigned to the Service ID in order for you to control the level of access for any application authenticating with that ID.

For more information about the benefits of this feature and how to get started, see the [Introducing IBM Cloud IAM Service IDs and API Keys](https://www.ibm.com/cloud/blog/introducing-ibm-cloud-iam-service-ids-api-keys){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon").

### {{site.data.keyword.Bluemix_notm}} global catalog
New as of: 27 July 2017
{: #gc}

Expanding on the last console update to manage your public regions from a single location in the console, {{site.data.keyword.Bluemix_notm}} now has a global catalog, making the process of selecting and deploying items that you select from the catalog a more streamlined process. Regardless of the region that you select in the console, you can now see all services that are available across all public regions from your catalog. Once you select a tile from the catalog, you can see which regions the service is available in, and select where you want to deploy it. For more information about the latest updates to the catalog, see [A global {{site.data.keyword.Bluemix_notm}} catalog makes building things easier](https://www.ibm.com/cloud/blog/announcements/global-bluemix-catalog-makes-building-things-easier){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon").

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

Lastly, we enhanced our unified user management capability to ensure that in a linked IaaS-PaaS account, users are managed in a unified way with no need to add users separately in the SoftLayer Customer Portal or the {{site.data.keyword.Bluemix_notm}} console.

For more information, check out the [Introducing Identity & Access Management](https://www.ibm.com/blogs/bluemix/2017/05/introducing-identity-access-management/){: new_window} ![External link icon](../../icons/launch-glyph.svg "External link icon") blog post.

### Navigation design changes for {{site.data.keyword.Bluemix_notm}} docs
New as of: 13 April 2017
{: #docnavupdates}

With this navigation update, we think you'll understand how content is better organized throughout our docs, and will be able to find relevant content more efficiently. With fewer nested layers of content, you won't have to dig around to find the documentation you need to be successful with {{site.data.keyword.Bluemix_notm}}.


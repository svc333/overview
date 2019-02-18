---

copyright:

  years: 2018, 2019

lastupdated: "2019-02-18"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:tip: .tip}

# Setting up your account
{: #quickstart_acc_ad}

This quick start guide is intended to help account admins set up their {{site.data.keyword.Bluemix}} environment. 
{:shortdesc}

1. Create resource groups to use to organize the resources that are created from the {{site.data.keyword.Bluemix_notm}} catalog. For more information, see [Best practices for organizing resources in resource groups](/docs/resources/bestpractice_rgs.html#bp_resourcegroups).

  Doing this ahead of time is important because after you assign a resource to a resource group, it can't be moved.
  {:tip}
  
2. Because not all services are managed by {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM), create your Cloud Foundry organization for organizing and granting access to those services. With a Lite account, you get one Cloud Foundry organization in one {{site.data.keyword.Bluemix_notm}} location. For more information, see [Adding orgs and spaces](/docs/account/orgs_spaces.html#orgsspacesusers). 
3. Create access groups for organizing users and service IDs into groups that require the same level of access assigned. For more information, see [Setting up access groups](/docs/iam/groups.html#groups).
4. Invite users to the account and add them to access groups to assign the necessary access to allow your account users to get building. For more information, see the [Getting started tutorial for IAM](/docs/iam/quickstart.html#getstarted).
5. Set up notifications for events and account spending limits. For more information, see [Setting email preferences](/docs/account/email.html) and [Setting spending notifications](/docs/billing-usage/notifications.html). 
6. Use the cost estimator to get an idea of how much your environment might cost. Click the Cost estimator icon ![Estimator icon](../icons/Estimator.svg) in the console menu bar. 
7. Use the cost estimator to get an idea of how much your infrastructure might cost. 
  
  a. Start by selecting an offering from the [catalog](https://cloud.ibm.com/catalog){: new_window} ![External link icon](../icons/launch-glyph.svg). 
  
  b. Enter the configuration details, select your pricing plan, and click **Add to estimate**.

## Next steps
{: #next-steps-acc-ad}

* Start creating services within the account to enable your organization and developers to build the solutions they need.  
* Create tags and tag your resources to help organize how you view billing and usage. This makes it easier to identify chargebacks to different organizations. For more information, see [Best practices for tagging resources](/docs/account/bp_account.html#tags). 

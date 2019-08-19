---

copyright:

  years: 2018, 2019

lastupdated: "2019-08-19"

keywords: account quick start, account set up, quick start guide, account admins, environment

subcollection: overview

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

1. Create resource groups to organize the resources that you create from the {{site.data.keyword.Bluemix_notm}} catalog. For more information, see [Best practices for organizing resources in resource groups](/docs/resources?topic=resources-bp_resourcegroups).

  Creating a resource group ahead of time is important because after you assign a resource to a resource group, it can't be moved.
  {:tip}
  
2. Because not all services are managed by {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM), create your Cloud Foundry organization for organizing and granting access to those services. With a Lite account, you get one Cloud Foundry organization in one {{site.data.keyword.Bluemix_notm}} location. For more information, see [Adding orgs and spaces](/docs/account?topic=account-orgsspacesusers). 
3. Create access groups for organizing users and service IDs into groups that require the same level of access assigned. For more information, see [Setting up access groups](/docs/iam?topic=iam-groups).
4. Invite users to the account and add them to access groups to assign the necessary access to allow your account users to get building. For more information, see the [Getting started tutorial for IAM](/docs/iam?topic=iam-getstarted).
5. Set up notifications for events and account spending limits. For more information, see [Setting email preferences](/docs/account?topic=account-email-prefs) and [Setting spending notifications](/docs/billing-usage?topic=billing-usage-spending). 
6. Use the cost estimator to get an idea of how much your environment might cost. Click the Cost estimator icon ![Estimator icon](../icons/Estimator.svg) in the console menu bar. 
7. Use the cost estimator to get an idea of how much your infrastructure might cost. 
  
  a. Start by selecting an offering from the [catalog](https://cloud.ibm.com/catalog){: new_window} ![External link icon](../icons/launch-glyph.svg). 
  
  b. Enter the configuration details, select your pricing plan, and click **Add to estimate**.

## Next steps
{: #next-steps-acc-ad}

* Start creating services within the account to enable your organization and developers to build the solutions they need.  
* Create tags and tag your resources to help organize how you view billing and usage. By doing so, you can easily identify chargebacks to different organizations. For more information, see [Best practices for tagging resources](/docs/account?topic=account-account_setup#tags). 

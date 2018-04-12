---

copyright:

  years: 2017, 2018

lastupdated: "2018-04-12"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}

# Managing access in {{site.data.keyword.Bluemix_notm}}
{: #cloudaccess}

## What is access management?

Access management enables you to control which users see, create, use, and manage resources in your account. To grant access, you can assign roles that allow users levels of access for completing platform management tasks and accessing account resources.

The way that you manage access in {{site.data.keyword.Bluemix_notm}} depends on the type of resource that you want to assign access to. {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) is the access management system for consistently managing resources across the {{site.data.keyword.Bluemix_notm}} platform. {{site.data.keyword.Bluemix_notm}} infrastructure and Cloud Foundry resources are not managed by using Cloud IAM. These resource types have their own access management systems. If you have a combination of resource types, you manage each type separately. For [assigning access to your infrastructure resources](/docs/iam/infrastructureaccess.html#infrapermission), you set permissions within your SoftLayer account. For [assigning access to Cloud Foundry resources](/docs/iam/cfaccess.html#cfaccess), use the Assign by using Cloud Foundry option in the Identity and Access section of the console.

## Who has permission to manage access?

As an account owner, you can manage access to all resources in your account. You can also delegate the task of managing access to platform resources by assigning a user in your account the administrator role for all services.

If you have Cloud Foundry services in your account, you can assign another user the organization or space manager role in order for them to add users and assign Cloud Foundry user roles for accessing instances in the organization or space that they manage.


## How do I start managing access?

Go to **Manage** &gt; **Security** &gt; **Identity and Access**, and then select **Users** to start managing access for users in your account. Select a user from the list to get started. You see only the access management options that you have permission to manage. For example, if you are not the account owner and you are not an organization or space manager, you do not see the option to manage Cloud Foundry access.

Access roles can also be assigned to apps and services by using service IDs. Go to the **Service IDs** page to get started. For more information on how to get up and running quickly with Cloud IAM follow the steps in the [Getting started tutorial](/docs/iam/quickstart.html#getstarted).

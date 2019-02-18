---

copyright:

  years: 2017, 2019

lastupdated: "2019-02-18"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}

# Managing access in {{site.data.keyword.Bluemix_notm}}
{: #cloudaccess}

Access management enables you to control which users see, create, use, and manage resources in your account. To grant access, you can assign roles that allow users levels of access for completing platform management tasks and accessing account resources.
{: shortdesc}

The way that you manage access in {{site.data.keyword.Bluemix_notm}} depends on the type of resource that you want to assign access to. {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) is the access management system used for consistently managing resources that are organized in a resource group across the {{site.data.keyword.Bluemix_notm}} platform. Classic infrastructure and Cloud Foundry resources are not managed by using Cloud IAM. These resource types have their own access management systems. 

If you have a combination of resource types, you manage each type separately. For assigning access to your [classic infrastructure resources](/docs/iam/infrastructureaccess.html#infrapermission), you set permissions within **Manage** > **Access (IAM)** on the Classic infrastructure tab for the user that you want to assign access. For assigning access to [Cloud Foundry resources](/docs/iam/cfaccess.html#cfaccess), you assign users to orgs and set Cloud Foundry org and space access roles within **Manage** > **Access (IAM)** on the Cloud Foundry tab for the user that you want to assign access.

## Permissions for managing access
{: #perms-manageaccess}

As an account owner, you can manage access to all resources in your account. You can also delegate the task of managing access to platform resources by assigning a user in your account the administrator role for all services, just the specific service, or the resource group that you want that user to manage.

If you have Cloud Foundry services in your account, you can assign another user the organization or space manager role in order for them to add users and assign Cloud Foundry roles for accessing instances in the organization or space that they manage.


## Getting started
{: #cloudaccess-getstarted}

Go to **Manage** &gt; **Access (IAM)**, and then select **Users** to start managing access for users in your account. Select a user from the list to get started. You see only the access management options that you have permission to manage. For example, if you are not the account owner and you are not an organization or space manager, you do not see the option to manage Cloud Foundry access.

You can also assign access roles to apps and services by using service IDs. Go to the **Service IDs** page to get started. For more information about how to get up and running quickly with Cloud IAM, see the [Getting started tutorial](/docs/iam/quickstart.html#getstarted).

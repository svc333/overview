---

copyright:
  years: 2017, 2019
lastupdated: "2019-03-14"

keywords: access control, resource groups, resource group

subcollection: overview

---

{:shortdesc: .shortdesc}

# Organizing resources in resource groups
{: #whatis-rgs}

A resource group is a way for you to organize your account resources in customizable groupings so that you can quickly assign users access to more than one resource at a time. Any account resource that is managed by using {{site.data.keyword.Bluemix}} Identity and Access Management (IAM) access control belongs to a resource group within your account. When you add a resource to your account from the catalog, you can assign the resource to a resource group. The only exception is Kubernetes, which doesn't prompt you for a resource group assignment, but access to the service is controlled by using IAM roles.

Services that are managed by using {{site.data.keyword.Bluemix_notm}} IAM and belong to a resource group have several benefits. Some of the benefits include the ability to connect to apps and services in any Cloud Foundry space, which means you can connect apps and services from different locations. Because resource groups are not scoped by location, you can provision apps and services from different locations into the same resource group. You can also use fine-grained access control down to an individual instance within a resource group.

For more information about working with resource groups, see [Managing resource groups](/docs/resources?topic=resources-rgs). 

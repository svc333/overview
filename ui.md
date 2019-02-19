---


copyright:
  years: 2015, 2019
lastupdated: "2019-01-29"

---

{:shortdesc: .shortdesc}
{:tip: .tip}
{:new_window: target="_blank"}

# Navigating the {{site.data.keyword.cloud_notm}} console 
{: #ui}

The {{site.data.keyword.cloud}} console is a user interface that helps you manage all your {{site.data.keyword.cloud_notm}} resources. When you access the [console](https://cloud.ibm.com){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon"), you can create a free account, log in, access documentation, access the catalog, view pricing information, get support, or check the status of {{site.data.keyword.cloud_notm}} components. After you log in, the menu bar contains a Menu icon ![Menu icon](../icons/icon_hamburger.svg) and more links.
{: shortdesc}


## Using the console
{: #consoleoptions}

When you log in to {{site.data.keyword.cloud_notm}}, the first page you can view is the dashboard, which shows widgets that summarize the status of your account. Next, you can manage your resources. Go to the Menu icon ![Menu icon](../icons/icon_hamburger.svg) &gt; **Resource List** to view all existing resources in your account.

  * Use the **Catalog** link to create new resources.
  * Use the **Docs** link to access useful information about {{site.data.keyword.cloud_notm}}.
  * Use the **Support** link to access the Support Center.  
  * From the **Manage** menu, you can access your account, billing and usage, and Identity and Access Management options.
  * Click the Cost estimator icon ![Cost estimator icon](../icons/Estimator.svg) to open the cost estimator.
  * Click the Notifications icon ![Notifications icon](../icons/Notification.svg) to access announcements and planned and unplanned events.

## Searching for resources
{: #search}

You can search for resources by name or by tag from anywhere in the {{site.data.keyword.cloud_notm}} console for resources that you expect to find in the resource list. Type the name of a resource or tag in the search field in the console menu bar.

For more information, see [Searching for resources](/docs/resources?topic=resources-searching-for-resources). 

## Managing resources in the resource list
{: #dashboardview}

Go to the Menu icon ![Menu icon](../icons/icon_hamburger.svg) &gt; **Resource List** to access your list of account resources. You can use the resource list to view and work with {{site.data.keyword.cloud_notm}} resources and Cloud Foundry service instances. See [What is a resource?](/docs/resources?topic=resources-resource) for more information about the different types of resources.

### Viewing resources
You can view all the resources in your account across all regions from the resource list. To see the items that are important to you, filter your list with the filters for each column header. For example, if you want to view and work with resources in a specific location, expand the **Location** filter, and select a location from the list.

### Working with resources
You can work with your resources in various ways from the resource list:

  * Each resource is displayed in its own row and an Actions icon ![More Actions icon](../icons/action-menu-icon.svg) is included at the end of the row. Click the Actions icon ![More Actions icon](../icons/action-menu-icon.svg) to start, stop, rename, or delete a resource.
  * To set up credentials or connections for a resource, click the name of the resource to navigate to the resource details page. Then, select **Service credentials** or **Connections**. For more information, see [Adding a credential](/docs/resources?topic=resources-service_credentials) and [Managing connections](/docs/resources?topic=resources-connect_app).


## Working in the catalog
{: #catalogcreate}

To create a resource, click **Create** from your resource list. You're then directed to the catalog. When you select a tile from the catalog, you can see where the resource is available. Not every resource listed in the catalog is available in every region.

After you click the tile for the resource that you want create, you can select which location you want to deploy in.

  * For Cloud Foundry resources, you can select a specific region and then select the org and space for the service instance to be assigned to.
  * For resources managed by {{site.data.keyword.cloud_notm}} Identity and Access Management (IAM), you select a location to deploy in. Then, you select a resource group to assign the service instance to.

---


copyright:
  years: 2015, 2018
lastupdated: "2018-10-25"

---

{:shortdesc: .shortdesc}
{:tip: .tip}
{:new_window: target="_blank"}

# How the {{site.data.keyword.cloud_notm}} console works
{: #ui}

The {{site.data.keyword.cloud}} console is a user interface that helps you manage all your {{site.data.keyword.cloud_notm}} resources. When you access the [console](https://console.bluemix.net){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon"), you can create a free account, log in, access documentation, access the catalog, view pricing information, get support, or check the status of {{site.data.keyword.cloud_notm}} components. After you log in, the menu bar contains a Menu icon  ![Menu icon](../icons/icon_hamburger.svg)  and additional links, depending on your account type.
{: shortdesc}

## Using the console
{: #consoleoptions}

If you are an existing user with an {{site.data.keyword.cloud_notm}} account, you can use the Menu icon  ![Menu icon](../icons/icon_hamburger.svg)  to access all existing resources on your dashboard.
  * Use the **Catalog** link to create new resources.
  * Use the **Docs** link to access useful information about {{site.data.keyword.cloud_notm}}.
  * From the **Support** menu, you can access information about what's new in {{site.data.keyword.cloud_notm}}, the Support Center, options for adding and viewing tickets, and the Status page.
  * From the **Manage** menu, you can access your account, billing and usage, and security options.

If you linked your {{site.data.keyword.cloud_notm}} and your SoftLayer accounts, you have the same options as a non-linked account owner, plus you can navigate to the customer portal by selecting the **Menu icon  ![Menu icon](../icons/icon_hamburger.svg) > Infrastructure** option. From here, you can view your account summary, order storage and devices, and manage access for VPN-only users and devices.

## Searching for resources
{: #search}

You can search for resources from anywhere in the {{site.data.keyword.cloud_notm}} console. Type the name of a resource in the search field in the console menu bar.

Press the Forward Slash key (/) on your keyboard to navigate your cursor to the search field.
{: tip}

## Managing resources on the dashboard
{: #dashboardview}

You can use the dashboard to view and work with {{site.data.keyword.cloud_notm}} resources and Cloud Foundry service instances. See [What is a resource?](/docs/resources/acct_resources.html#resource) for more information.

### Viewing resources

You can view all the resources in your account across all regions from the dashboard. To customize your view, use the following options:

  * To view resources in a specific resource group, select a resource group from the **Resource Group** list.
  * To view resources in a specific Cloud Foundry org, select an org from the **Cloud Foundry Org** list.

Then, based on the items you select, you can filter by the following options:

  * Location
  * Cloud Foundry Space
  
If you want to view and work with resources in a specific region, expand the **LOCATION** menu, and select a region from the list.

### Working with resources

You can work with your resources in various ways from the dashboard:

  * Each resource is displayed in its own row and a More Actions icon  ![More Actions icon](../icons/overflow-menu.svg)  is included at the end of the row. Click the **More Actions** icon to start, stop, rename, or delete a resource.
  * To set up credentials or connections for a resource, click the name of the resource to navigate to the resource details page. For more information, see [Adding a new credential](/docs/resources/service_credentials.html) and [Managing connections](/docs/resources/connecting_apps.html#connect_app).

## Working in the catalog
{: #catalogcreate}

To create a new resource, click **Create resource** from your dashboard. You're then directed to the catalog. When you select a tile from the catalog, you can see where the resource is available. Not every resource listed in the catalog is available in every region.

After you click the tile for the resource that you want create, you can select which location you want to deploy in.

  * For Cloud Foundry resources, you can select a specific region and then select the org and space for the service instance to be assigned to.
  * For resources managed by {{site.data.keyword.cloud_notm}} Identity and Access Management (IAM), you select a location to deploy in. Then, you select a resource group to assign the service instance to.

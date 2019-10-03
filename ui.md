---

copyright:
  years: 2015, 2019
lastupdated: "2019-09-25"

keywords: ui, components, using the console, SoftLayer, classic infrastructure, redirect, catalog, pricing information, get support

subcollection: overview

---

{:shortdesc: .shortdesc}
{:tip: .tip}
{:note: .note}
{:new_window: target="_blank"}
{:script: data-hd-video='script'}

# Navigating the {{site.data.keyword.cloud_notm}} console 
{: #ui}

The {{site.data.keyword.cloud}} console is a user interface that helps you manage all your {{site.data.keyword.cloud_notm}} resources. When you access the [console](https://cloud.ibm.com){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon"), you can create a free account, log in, access documentation, access the catalog, view pricing information, get support, or check the status of {{site.data.keyword.cloud_notm}} components. After you log in, the menu bar contains a Menu icon ![Menu icon](../icons/icon_hamburger.svg) and more links.
{: shortdesc}

## Watch a tour
{: #video-ui}

<div class="embed-responsive embed-responsive-16by9" data-hd-video="video">
  <iframe class="embed-responsive-item" id="youtubeplayer" title="Welcome to IBM Cloud" type="text/html" width="640" height="360" src="https://www.youtube.com/embed/VXqbRNwXC2A" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen> </iframe>
</div>

## Video transcript
{: #video-transcript-ui}
{: script}
{: notoc}

Welcome to IBM Cloud, the home of over 190 unique services that are available for you to start customizing and building the solutions that you need for your business today! [Upbeat music]

After logging in, you're ready to start building right away! From your dashboard, pick the journey that best fits your needs [Click Menu icon > Dashboard]. Start creating apps, add users to your account, or if you wanted to learn about some of our common patterns based on best practices and proven technologies, check out the solution tutorials in the Learn widget. Your dashboard is the place to view a high-level overview of your account usage, support cases, apps, and resources with quick links out to each area.

When you're ready to start adding resources to your account, go to the catalog [Click Catalog menu item]. Get started with some powerful services from Watson in the AI category. Check out our databases, IoT, networking, and storage offerings. And explore the variety of compute options from the IBM Cloud Kubernetes Service to bare metal servers to serverless. If you're just here to try us out, filter the catalog to view offerings with Lite plans, which are free to use [Click Filter to expand the options, and select Lite].

After you start building, go to your resource list [Click Menu icon > Resource list] to get a quick and easy view of all of the resources that have been added to your account. This is where you can access quick options [Expand any category on the resource list, and select the Actions menu icon for any row to display the options] for working with apps, and tag, rename, or delete resources.

For any of the housekeeping items that you need to take care of as the account owner, such as creating and managing your resource groups, Cloud Foundry orgs and spaces, tags for resources, or account settings, go to Manage > Account [Click Manage menu option > Account].

From the same Manage menu, you can access the Billing and usage area of your account too [Click Manage menu option > Billing and usage]. 

Through the Manage > Access (IAM) option [Click Manage menu item > Access (IAM)], you can invite users to your account and manage their access to account resources including IAM-enabled resources, Cloud Foundry resources, and classic infrastructure resources.

If you run into any questions as you start building apps, working with users, or building your infrastructure, you can visit the Support page [Click Support menu option] where you'll find common FAQs that can help you to resolve your issue quickly without even having to contact IBM Cloud. However, if you do find the need to get in touch with us or open a support case, those options are also available to you.

The docs [Click Docs menu items] are also a helpful guide for walking you through common tasks. You can enter any set of keywords in the docs search bar to help you quickly find the information that you're looking for. 

Now that you know how to navigate through the IBM Cloud console to set up your account, create resources from the catalog, manage them from your resource list, and find help through support and docs, it's time to get coding and building out your infrastructure!  


## Using the console
{: #consoleoptions}

When you log in to {{site.data.keyword.cloud_notm}}, your dashboard is displayed, which shows widgets that summarize the status of your account. If you're interested in adding or removing widgets, see [Customizing your dashboard](/docs/account?topic=account-custom-dashboard).

  * Use the **Catalog** link to create new resources.
  * Use the **Docs** link to access the product documentation. 
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

To create a resource, click **Create** from your resource list. You're then directed to the catalog. When you select a tile from the catalog, you can see where the resource is available. Not every resource that is listed in the catalog is available in every region.

After you click the tile for the resource that you want create, you can select which location you want to deploy in.

  * For Cloud Foundry resources, you can select a specific region and then select the org and space for the service instance to be assigned to.
  * For resources managed by {{site.data.keyword.cloud_notm}} Identity and Access Management (IAM), you select a location to deploy in. Then, you select a resource group to assign the service instance to.

## Transitioning to the {{site.data.keyword.cloud_notm}} experience
{: #redirect-cloud}

As part of the migration from SoftLayer to {{site.data.keyword.cloud_notm}}, get familiar with the {{site.data.keyword.cloud_notm}} console, which you use to manage both your platform and infrastructure resources. We're currently in the process of linking all SoftLayer and {{site.data.keyword.cloud_notm}} accounts. Therefore, your account might not have access yet. As soon as it does, you can check out the new experience. 

The formerly named SoftLayer is now called {{site.data.keyword.cloud_notm}} classic infrastructure.
{: note}

### Locating your infrastructure items
{: #sl-links}

Click the **Menu icon** ![Menu icon](../icons/icon_hamburger.svg) > **Classic Infrastructure** to quickly locate your devices, storage, network, security, and services. 

![Location of classic infrastructure items.](images/iaas-items.png "Locating your infrastructure items"){: caption="Figure 1. Location of classic infrastructure items in the {{site.data.keyword.cloud_notm}} console" caption-side="bottom"}

You can also find your infrastructure resources by clicking any of the links that are listed in the Classic infrastructure widget on your dashboard. Go to **Menu icon** ![Menu icon](../icons/icon_hamburger.svg) > **Dashboard**.
{: tip}

### Managing users, access, and API keys
{: #billing-items}

You can manage users in your account, classic infrastructure access for your users, and your API keys from the Access (IAM) section of the console. 

* To invite new users, remove users, or manage a specific user's login settings, IP restrictions, VPN password, and more, go to **Manage** > **Access (IAM)**, and select **Users**.
* To start managing a user's classic infrastructure access, go to **Manage** > **Access (IAM)**, and select **Users**. For more details, see [Managing classic infrastructure access](/docs/iam?topic=iam-mngclassicinfra).
* To create and manage {{site.data.keyword.cloud_notm}} API keys or a classic infrastructure API key, go to **Manage** > **Access (IAM)**, and select **API keys**. For more information, see [Understanding API keys](/docs/iam?topic=iam-manapikey).

![Location to manage IAM items.](images/users-access.png "Managing users, access, and API keys"){: caption="Figure 2. Managing IAM items in the {{site.data.keyword.cloud_notm}} console" caption-side="bottom"}

### Placing an order
{: #place-order}

Use the catalog to place an order. You can navigate to the catalog in one of the following ways:

  * Click **Catalog** from the menu bar.
  * Click the **Menu icon** ![Menu icon](../icons/icon_hamburger.svg) > **Resource List**. Then, click **Create resource**.

![Location to place an order.](images/orders.png "Placing an order"){: caption="Figure 3. Placing an order in the {{site.data.keyword.cloud_notm}} console" caption-side="bottom"}

If your account includes any discounts, the price of an offering that is displayed on the offering details page reflects the discounted price of that offering.
{: tip}

### Making a payment
{: #payments}

You can make a payment from the Billing and usage section of the console. Go to **Manage** > **Billing and usage**, and select **Payments**. 

![Location to make a payment.](images/payments.png "Making a payment"){: caption="Figure 4. Making a payment in the {{site.data.keyword.cloud_notm}} console" caption-side="bottom"}

### Accessing your invoices
{: #invoices}

You can access your invoices from the Billing and usage section of the console. Go to **Manage** > **Billing and usage**, and select **Invoices**.

![Location to access your invoices.](images/invoices.png "Accessing your invoices"){: caption="Figure 5. Accessing your invoices in the {{site.data.keyword.cloud_notm}} console" caption-side="bottom"}

### Accessing your sales items
{: #sales}

Your device quotes and upgrades, orders, cancellations, and shipments are in the Billing and usage section of the console. Go to **Manage** > **Billing and usage**, and select **Sales**. 

![Location to access sales items.](images/sales-items.png "Accessing your sales items"){: caption="Figure 6. Accessing your sales items in the {{site.data.keyword.cloud_notm}} console" caption-side="bottom"}

### Accessing your support cases
{: #support-mng}

To access your current support cases, click **Support** > **Manage cases**. You can also access your archived cases by clicking **View archived cases**.

![Location to access support cases.](images/support-cases.png "Accessing your support cases"){: caption="Figure 7. Accessing your support cases in the {{site.data.keyword.cloud_notm}} console" caption-side="bottom"}

### Submitting feedback
{: #feedback-profile}

You can submit a rave review, a suggestion, or any other feedback. To get in touch with us, choose from the following methods:

  * Click the **Feedback** button that is located on the edge of the console page. 
  * Click the **Avatar icon** ![Avatar icon](../icons/i-avatar-icon.svg) > **Feedback**. 

![Location to submit feedback.](images/feedback.png "Submitting feedback"){: caption="Figure 8. Submitting feedback in the {{site.data.keyword.cloud_notm}} console" caption-side="bottom"}

### Setting email preferences
{: #email-prefsl}

You can set your preferences to receive emails about platform and infrastructure notifications. Click the **Avatar icon** ![Avatar icon](../icons/i-avatar-icon.svg) > **Profile and settings**, and select **Notifications**.

![Location to set email preferences.](images/email-prefs.png "Setting email preferences"){: caption="Figure 9. Setting your email preferences in the {{site.data.keyword.cloud_notm}} console" caption-side="bottom"}

### Selecting your VPN access point
{: #vpn-access}

You can log in to the {{site.data.keyword.cloud_notm}} console by using a VPN access point. Go to [VPN access](https://www.ibm.com/cloud-computing/bluemix/vpn-access), and select an access point from the lists.


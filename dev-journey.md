---

copyright:
  years: 2016, 2019
lastupdated: "2019-02-18"

---
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}
{:tip: .tip}

# Explore the developer journey in {{site.data.keyword.cloud_notm}}
{: #dev-journey}

As a developer, you decide the best entry point for your code. You can choose to generate your code through our provided tools, or you can bring your own code and deploy it to {{site.data.keyword.cloud}}!
{: shortdesc}

{{site.data.keyword.cloud_notm}} has a set of capabilities that gets you started with building apps in minutes. {{site.data.keyword.cloud_notm}} developer tools create a high-performing foundation that you need to get up and running. Two main tools are offered for development:
 * {{site.data.keyword.cloud_notm}} web console (developer portals)
 * {{site.data.keyword.cloud_notm}} command-line interface (CLI)

With the {{site.data.keyword.cloud_notm}}, you can:

* Select starter kits that are use-case-specific, and produce production-ready apps in various programming languages and architectural patterns.
* Use an [IBM Developer code pattern ![External link icon](../icons/launch-glyph.svg "External link icon")](https://developer.ibm.com/patterns/){:new_window} to quickly create your app and deploy it to {{site.data.keyword.cloud_notm}}.
* See and manage resources that are automatically provisioned from your starter kit, or that you manually add to your app.
* If you have an app in an existing repository, you can use a blank starter kit to create an app record and connect it to your source repository and a DevOps toolchain.
* With portable app code, you can deploy to various cloud environments.
* Create a [DevOps toolchain](/docs/services/ContinuousDelivery?topic=ContinuousDelivery-cd_getting_started) in a few clicks.
* Use the [command-line interface (CLI)](/docs/cli/reference/ibmcloud?topic=cloud-cli-overview) for local development.
* Browse or search the [{{site.data.keyword.cloud_notm}} catalog ![External link icon](../icons/launch-glyph.svg "External link icon")](https://{DomainName}/catalog){: new_window} for apps and services that you can create and start using today.

![Developer experience overview](images/dev-journey.png "Developer experience overview")

To better understand how our experience can help you rapidly build high-quality production-ready apps, let’s look at these elements in more detail.

## Developer portals
{: #dev-portals}

The {{site.data.keyword.cloud_notm}} has developer portals in different areas of interest (like Watson, Security, or Finance) or a digital channel (like Mobile or Web Apps). You can access these portals from the **Menu** icon ![Menu icon](../icons/icon_hamburger.svg).

Each developer portal provides starter kits that are relevant to the portals's focus area. The portals offers consistent, intuitive workflow for creating a working production-ready app in minutes.

## Apps
{: #app-projects}

An app comprises code, data, services, and toolchains. For example, the {{site.data.keyword.cloud_notm}} mobile app contains device code, along with back-end logic, data storage, analytics and security services, and is set up for continuous delivery.

![Reuse](images/garage_reuse2.png "With Developer Experience, you can reuse and avoid reinventing")

You can create and manage an app by using any {{site.data.keyword.cloud_notm}} developer portal or the {{site.data.keyword.dev_cli_notm}}.

You can create simple blank apps directly, or create more complex apps by using our starter kits. If you choose to create blank apps without the help of a starter kit, you can do so from the [{{site.data.keyword.cloud_notm}} dashboard ![External link icon](../icons/launch-glyph.svg "External link icon")](https://{DomainName}){: new_window} without visiting a portal!

You can use a code pattern to quickly create your app and deploy it to {{site.data.keyword.cloud_notm}}. From the [IBM Developer website ![External link icon](../icons/launch-glyph.svg "External link icon")](https://developer.ibm.com/patterns/){:new_window}, choose a code pattern. You can either view the code in GitHub or create and build an app on {{site.data.keyword.cloud_notm}}, where you can use a DevOps toolchain to automatically deploy your app.


## Starter kits
{: #starter-kits}

With starter kits, your experience should be easy to use and customizable. The starter kits assemble a skeleton production app in the language of your choice, ready for cloud deployment. Each starter kit includes a language, a framework, and a pattern for a specific use case and for reusing code.

If a starter kit requires specific resources, no problem. With auto-provisioned resources, {{site.data.keyword.cloud_notm}} automatically creates instances for those resources when you create your app. You can access starter kits from the developer portal or command-line interface for instructions that are relevant to your focus area and workflow!

### How are starter kits different from samples?
Starter kits are production-ready and focus on demonstrating a key pattern implementation by using a runtime (for example, Node.js and Express). In some cases, starter kits offer a simple user experience to highlight the integration of the service. In other cases, starter kits represent a customizable implementation of a sophisticated use case.

* A snippet is a few lines of code that is often presented in an IDE. Snippets help a developer integrate with a programming language syntax or support integration with a defined API.
* A demonstration is usually high in quality and fidelity and uses a range of services and integration points. It often requires setup time and is used to prove a business problem or demonstrate a platform feature. You can use it for evaluating stages of cloud adoption. Sometimes it's code that is included in production code.
* A sample is a small example of a specific feature, function, service, or user journey. You can reuse a sample or include it in a production application. It's typically used to show technical capabilities and a possible approach to solving a technical problem.
* A starter kit is a production-ready pattern that can be integrated with a set of services to generate a production-ready asset that can be deployed directly into a DevOps pipeline and a Kubernetes cluster. A starter kit contains descriptive metadata providing the user with enough information to know what the kit is and does. It also contains instructions that tell {{site.data.keyword.cloud_notm}} what to produce. The output is production-ready out of the box, and can be iterated on for further enhancements, based on IBM best practices. Starter kit content isn’t as complex as a demonstration and not as trivial as a snippet or sample. They are dynamically created based on the developer’s requirements.

## Auto-provisioned resources
{: #auto-provision}

If a starter kit specifies required resources, {{site.data.keyword.cloud_notm}} automatically creates instances of those resources when you create your app. You can also manually provision resources or select existing resource instances to add to your app after it's created. You can see a list of service instances that are associated with your app in the App Details view along with credentials in case you need them.

## Portable code
{: #portable-code}

Creating an app from a starter kit automatically creates code for you that has consistent format and isn't dependent on the runtime. You can deploy the code into your environment of choice, such as Kubernetes or Cloud Foundry, without making changes.

You can get a quick look at your app code by clicking **Download code** on the App Details page of your app. Your code is downloaded as a `.zip` file that contains the complete app code structure. You can easily extract the file and run the code locally by using the {{site.data.keyword.dev_cli_notm}}, or add it to your code management repository.

### What code is created?
{: #what-code}

When you create an app directly or with help from a starter kit, the app contains portable code. Portable code contains cloud enablement code for multiple cloud environments. You can then produce code in four foundational areas:
* Code that follows best practices for a specific language
* Code that enables the app to run on the cloud
* Code that's initialized to connect to cloud services
* Code that's specific to a use case

Generating these components saves you valuable time and ensures that you’re using best-in-class architecture.

* **Use case logic** provides functions for the core function of a particular use case. Examples might be code for a Watson Conversation chat bot, or code for a mobile visual recognition app.
* **Language components** are code components and files specific to the programming language you select for your starter kit. For example, node.js programmers need a package.json file for dependency management, and this file is automatically created for you.
* **Service enablement** is code that enables your app to connect to and use the services you add. Credential management, initialization code, and service-specific SDKs are examples of service enablement items.
* **Cloud enablement** is code that enables your app to run on {{site.data.keyword.cloud_notm}}. For example, Helm charts that enable your app to run on an {{site.data.keyword.cloud_notm}} Kubernetes cluster.

When you create an app from an {{site.data.keyword.cloud_notm}} starter kit, your app starts with proven architecture that also reflects best practices for the language you selected.

Each app includes a readme file that contains technical details of the app and explains what is needed to get your app running if it doesn’t run out-of-the-box.
{: tip}

## Bring your own code and deploy it to {{site.data.keyword.cloud_notm}}
{: byoc}

If you have an app in an existing repository, you can use a blank starter kit to create an app record in {{site.data.keyword.cloud_notm}} and connect the app to your source repository and your DevOps toolchain.

You can start from the {{site.data.keyword.cloud_notm}} dashboard or from any blank starter kit. After you name your app and select a resource group, select the [**Bring your own code**](/docs/apps/tutorials?topic=creating-apps-code-repo) starting point, provide the Git repo URL that contains your code, and click **Create**.

You can connect your existing DevOps toolchain or create one, and continuously deliver your app to the environment of your choice, such as Kubernetes or Cloud Foundry.


## DevOps toolchain
{: #devops}

The DevOps toolchain comprises procedures and tools for accessing, developing, deploying, and operating your app. A DevOps toolchain is set of linked services that automates your DevOps tasks. It’s possible to perform DevOps manually with simple apps, but the need for automation increases quickly as app complexity increases, and toolchain automation is a must-have for continuous delivery.

The core component of a DevOps toolchain is a code version control repository like GitHub. More tools might include backlog tracking, delivery pipeline, IDE, and monitoring service like [{{site.data.keyword.cloud_notm}} {{site.data.keyword.DRA_short}}](/docs/services/DevOpsInsights?topic=DevOpsInsights-getting-started).

If you create an app by using a starter kit, you can create a new toolchain and deploy your app simply by clicking **Deploy to cloud** on the **App Details** page. A toolchain that has a code repo, issues repo, delivery pipeline, and web IDE is created.

You can then build on this toolchain to accommodate multiple teams and deploy to separate environments for development, test, and production. You establish an enterprise-class collaborative continuous delivery model for your app.

![Continuous delivery](images/garage_continuous_delivery2.png "Developer experience sets up continuous delivery into your development branch")


## Command-line interface
{: cli}

Use the command-line interface to code, build, and run your app locally. A common pattern is to create your app from a developer portal in the {{site.data.keyword.cloud_notm}} console, use the developer tools to develop locally, and then push the updates to your repo and merge to start your deployment toolchain.

## Garage Method development
{: #developer_concepts}

If you’re looking for a place where you can experiment with big ideas and emerging technologies, be sure to check out [Garage Method](https://www.ibm.com/cloud/garage/){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon") deployments. You can learn how IBM can help you develop apps in your organization. 

![Garage Method phases overview](images/garage_phases_overview2.png "Garage Method phases overview") Garage Method phases overview

{{site.data.keyword.cloud_notm}} helps you produce successful enterprise-class production apps by using the Garage Method or whatever method you prefer. To better understand what {{site.data.keyword.cloud_notm}} offers to developers, let's take a quick look at the skills that are required to build a modern app.

## Developer skills
{: #skills}

Users expect more from their applications than ever before. They want apps to deliver deep insights from stored and real-time data, to be always-available, and to match their individual needs more closely. To meet these expectations, the developer capabilities in IBM Cloud align to specific skill sets and enable your team to use one platform to produce, deliver, run, and manage apps. For example, a sophisticated cognitive application might require contributions from digital developers, cloud native developers, streams developers, data scientists, and DevOps specialists.

 ![Developer types](images/developer_skills.png "Developer relationships")

* Digital developers author for a particular digital channel such as mobile web, voice, and chat. Digital developers are typically focused on use cases and directly meeting users' needs as a comprehensive experience.
* Cloud native developers specialize in constructing and interconnecting cloud components. Microservice and back-end-for-frontend authors fall into this category.
* Streams developers focus on processing and gaining insight from streams of data. For example, a streams developer might analyze and initiate action on incoming text, speech, or video streams.
* Data scientists use analytics and machine learning to produce predictive models. These models are used in business metrics and provide deep insights to application users.
* DevOps specialists are experts in resolving deployment and toolchain issues. For simple apps, dedicated specialists are usually not needed as development team members manage DevOps with the squad. But for complex enterprise applications, with many dependencies, DevOps specialists are essential in keeping your production app running smoothly.

The developer capabilities that are built in to {{site.data.keyword.cloud_notm}} align to these skill sets and allow your team to use one platform to produce, deliver, run, and manage your app. For example, a digital developer that creates a mobile app might use the {{site.data.keyword.cloud_notm}} [Mobile developer portal](https://{DomainName}/developer/mobile/dashboard){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon"). A cognitive app builder might use the [Watson developer portal](https://{DomainName}/developer/watson/dashboard){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon") along with [Watson Studio](https://{DomainName}/catalog/services/watson-studio){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon"). A streams developer can use [IBM Real-Time Analytics](/docs/services/StreamingAnalytics?topic=StreamingAnalytics-gettingstarted). The [{{site.data.keyword.cloud_notm}} Continuous Delivery service](/docs/services/ContinuousDelivery?topic=ContinuousDelivery-cd_getting_started) simplifies the job of a DevOps specialist.

[Ready to get started building high-quality, production-ready apps?](/docs/apps/tutorials?topic=creating-apps-create)

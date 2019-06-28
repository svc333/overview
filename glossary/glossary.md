---


copyright:
  years: 2016, 2019
lastupdated: "2019-06-28"

keywords: glossary, IBM Cloud glossary

subcollection: overview

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# Glossary terms for {{site.data.keyword.cloud_notm}} 
{: #glossary}

This glossary provides terms and definitions for {{site.data.keyword.cloud_notm}}.
{:shortdesc}

The following cross-references are used in this glossary:

- *See* refers you from a nonpreferred term to the preferred term or from an abbreviation to the spelled-out form.
- *See also* refers you to a related or contrasting term.

## A
{: #glossa}

### access control list
{: #x2012793}

A list that statelessly manages inbound and outbound traffic for a subnet through the use of rules. An access control list helps provide security at the subnet level.

### access group
{: #x2160811}

A set of users and service IDs organized into a group that is used as the subject of an access policy for assigning all group members the same access.

### access policy
{: #x2853407}

A method for granting users, service IDs, and access groups access to account resources. An access policy includes a subject, target, and role.

### access token
{: #x2113001}

A value used by the consumer to gain access to the protected resources on behalf of the user, instead of using the user’s service provider credentials.

### action
{: #x2012974}

- A code snippet that can be explicitly invoked, or run in response to an event. See also [feed](#x3129185), [invoke](#x2057232).
- A task that is performed in the context of a service.

### affinity
{: #x2149238}

Two or more container group instances running on the same network node. See also [anti-affinity](#x8888040).

### anti-affinity
{: #x8888040}

Two or more container group instances that run on different network nodes to ensure higher availability for an app. See also [affinity](#x2149238).

### API
{: #x2008805}

See [application programming interface](#x2000186).

### app
{: #x4281528}

A web or mobile device application. See also [mobile application](#x4258535), [web application](#x2116500).

### application programming interface (API)
{: #x2000186}

An interface that allows an application program that is written in a high-level language to use specific data or functions of the operating system or another program.

### artifact
{: #x2262995}

An entity that is used or produced by a software or systems development process. Examples of artifacts include designs, requirements, source files, plans, scripts, simulations, models, test plans, and binary executable files. In an HTTP context, artifacts have a URI and are called resources.

### authentication (AuthN)
{: #x2014567}

The process of validating the identity of a user or server.

### AuthN
{: #x7470446}

See [authentication](#x2014567).

### authorization (AuthZ)
{: #x2014653}

In computer security, the right granted to a user to communicate with or make use of a computer system.

### AuthZ
{: #x7470448}

See [authorization](#x2014653).

### availability zone
{: #x7018171}

A location within a region that {{site.data.keyword.containerlong}} runs in.


## B
{: #glossb}

### bare metal server
{: #x6778472}

A dedicated, fully-customizable physical server that can be used for virtualization or web hosting.

### base image
{: #x5366487}

An image that has no parent image. See also [image](#x2024928), [parent image](#x8439210).

### beta offering
{: #x9774283}

An offering that {{site.data.keyword.IBM_notm}} makes available solely for evaluation and testing purposes.  There are no warranties, SLAs or support provided and beta offerings are not intended for production use.

### bind
{: #x2000361}

To establish a connection between software components on a network using an agreed-to protocol. In web services, the bind operation occurs when the service requester invokes or initiates an interaction with the service at run time using the binding details in the service description to locate, contact, and invoke the service.

### BLU Acceleration
{: #x7470463}

A collection of IBM Db2 technologies designed to work primarily with read-mostly business intelligence query processing. BLU Acceleration consists of four major database design advances: dynamic in-memory columnar processing, actionable compression, parallel vector processing, and data skipping.

### blue-green deployment
{: #x7807335}

A deployment technique that enables continuous delivery and minimizes downtime by running two nearly identical production environments called Blue and Green. While one of the environments (for example, Blue) is the live production environment, the other (for example, Green) can be used for final testing and deployment. After the application is deployed in Green, Green becomes the production environment and Blue becomes idle. See also [red-black deployment](#x8439181).

### boilerplate
{: #x7233930}

A template that includes one application and its associated runtime environment and predefined services for a particular domain.

### borderless
{: #x8439189}

Pertaining to an open, non-proprietary development platform that includes public cloud, dedicated cloud, and local cloud deployment models. See also [dedicated cloud](#x8439199), [local cloud](#x8439194), [public cloud](#x4585370).

### buildpack
{: #x7233925}

A collection of scripts that prepare your code to run on IBM Cloud. Buildpacks examine deployed applications, then download and configure any dependent applications.


## C
{: #glossc}

### CA
{: #x2015942}

See [certificate authority](#x2016383).

### certificate authority (CA)
{: #x2016383}

A trusted third-party organization or company that issues the digital certificates. The certificate authority typically verifies the identity of the individuals who are granted the unique certificate. See also [intermediate certificate](#x3753781), [Secure Sockets Layer](#x2038004), [trusted root](#x2042234).

### certificate signing request (CSR)
{: #x3530521}

An electronic message that an organization sends to a certificate authority (CA) to obtain a certificate. The request includes a public key and is signed with a private key; the CA returns the certificate after signing with its own private key.

### CLI
{: #x2008863}

See [command-line interface](#x2051424).

### client
{: #x2000644}

A software program or computer that requests services from a server. See also [host](#x2002243).

### cloud computing
{: #x3877850}

A computing platform where users can have access to applications or computing resources, as services, from anywhere through their connected devices. A simplified user interface or application programming interface (API), or both, makes the infrastructure supporting such services transparent to users.

### cloud portability
{: #x4585297}

The ability to move applications and services across public or private cloud computing environments, or from different cloud providers.

### command-line interface (CLI)
{: #x2051424}

A computer interface in which the input and output are text based.

### component
{: #x2017871}

In source control management, a grouping of related artifacts in a stream or repository workspace. A component can contain any number of folders and files.

### compute
{: #x3723424}

Infrastructure or resources that serve as the basis for building apps in the cloud.

### container
{: #x2010901}

A system construct that allows users to simultaneously run separate logical operating system instances. Containers use layers of file systems to minimize image sizes and promote reuse. See also [image](#x2024928), [layer](#x2028320), [registry](#x2064940).

### credential
{: #x2018813}

Information acquired during authentication that describes a user, group associations, or other security-related identity attributes, and that is used to perform services such as authorization, auditing, or delegation. For example, a user ID and password are credentials that allow access to network and system resources.

### CSR
{: #x2140147}

See [certificate signing request](#x3530521).

### custom domain
{: #x5728384}

The customized portion of the URL selected by the user to direct requests to the application. A custom domain makes up part of the route. A custom domain can be a shared domain, a shared subdomain, or a shared domain and host. See also [domain](#x2021210), [host](#x2002243), [route](#x2037338), [subdomain](#x2040080), [Uniform Resource Locator](#x2042491).


## D
{: #glossd}

### daemon
{: #x2019215}

A program that runs unattended to perform continuous or periodic functions, such as network control.

### dashboard
{: #x2363941}

A user interface component that provides a comprehensive summary of pertinent information from various sources to the user.

### data center (DC)
{: #x2439906}

The physical location of the servers that provide cloud services.

### data store
{: #x2052849}

A place, such as a database system, file, or directory, where data is stored.

### DC
{: #x2052913}

See [data center](#x2439906).

### DEA
{: #x2019805}

See [Droplet Execution Agent](#x7470348).

### dedicated cloud
{: #x8439199}

A private cloud computing environment that provides infrastructure with single-tenant hardware. See also [borderless](#x8439189).

### deployment
{: #x2104544}

A process that retrieves the output of a build, packages the output with configuration properties, and installs the package in a pre-defined location so that it can be tested or run. See also [stage](#x2067189).

### DevOps
{: #x5784896}

A software methodology that integrates application development and IT operations so that teams can deliver code faster to production and iterate continuously based on market feedback.

### domain
{: #x2021210}

Part of a naming hierarchy that specifies the route. For example, example.com. In {{site.data.keyword.cloud_notm}}, domains are associated with orgs. Domain objects are not directly bound to apps. See also [custom domain](#x5728384), [host](#x2002243), [organization](#x2032585), [route](#x2037338), [subdomain](#x2040080), [Uniform Resource Locator](#x2042491).

### droplet
{: #x7470343}

An archive within Cloud Foundry that contains an application and its runtime and framework dependencies, prior to deployment to the cloud.

### Droplet Execution Agent (DEA)
{: #x7470348}

The Cloud Foundry component that is responsible for deploying applications.


## E
{: #glosse}

### endpoint
{: #x2026820}

The address of an API or service in an environment. An API exposes an endpoint and at the same time invokes the endpoints of other services. See also [route](#x2037338).

### experimental offering
{: #x9774278}

An offering that {{site.data.keyword.IBM_notm}} makes available solely for evaluation and testing purposes, and might be unstable or not compatible with previous versions. An experimental offering can be discontinued with short notice. There are no warranties, SLAs or support provided, and experimental offerings are not intended for production use.

## F
{: #glossf}

### federate
{: #x2763229}

To merge two or more entities. For example, a company's registered domain could be federated with an IBMid.

### feed
{: #x3129185}

A piece of code that configures an external event source to fire trigger events. See also [action](#x2012974).

### file share
{: #x2022902}

In the {{site.data.keyword.cloud_notm}} environment, a persistent storage system where users store and share files. In {{site.data.keyword.containershort_notm}}, users can mount Docker volumes on file shares.

### fire
{: #x2239904}

To activate a trigger.

### floating IP address
{: #x6326428}

A public, routable IP address that makes use of 1-to-1 network address translation (NAT) so that a server can communicate with the public internet and private subnet within a cloud environment. Floating IP addresses are associated to an instance, for example, a virtual server instance, a load balancer, or a VPN gateway, by means of a virtual network interface card (vNIC).

### framework
{: #x2023472}

An architecture for an application that provides a standard structure for an application, and general, extensible functionality.  A framework enables and simplifies consistent implementation of complex technologies for application development.


## G
{: #glossg}

### GA
{: #x2117930}

See [general availability](#x2117947).

### GB-hour
{: #x7470477}

The cumulative amount of memory (in gigabytes) that is running for all application instances for a particular buildpack per hour.

### general availability (GA)
{: #x2117947}

Date when an offering is widely available for sale and delivery to customers or channels, usually across multiple geographies.

### globally unique identifier (GUID)
{: #x2390455}

An algorithmically determined number that uniquely identifies an entity within a system.

### GUID
{: #x2390457}

See [globally unique identifier](#x2390455).


## H
{: #glossh}

### hardware virtual machine mode (HVM)
{: #x9736811}

Hardware-assisted full virtualization. A virtual machine uses resources from the host computer to operate as a complete hardware environment. The host operating system is unaware of the virtual client.

### heavy API call
{: #x7690468}

A client operation that writes, deletes, or inserts data. Heavy API calls consume more resources than light API calls because they are affecting the data. See also [light API call](#x7690463).

### host
{: #x2002243}

A computer that is connected to a network and that provides an access point to that network. The host can be a client, a server, or both a client and server simultaneously. See also [client](#x2000644), [custom domain](#x5728384), [domain](#x2021210), [route](#x2037338), [subdomain](#x2040080), [Uniform Resource Locator](#x2042491).

### HTTP method
{: #x2024674}

An action that is used by the Hypertext Transfer Protocol. HTTP methods include GET, POST, and PUT.

### HTTPS
{: #x2193603}

See [Hypertext Transfer Protocol Secure](#x2237225).

### HVM
{: #x9736815}

See [hardware virtual machine mode](#x9736811).

### hybrid cloud
{: #x4585327}

A cloud computing environment that consists of multiple public and private resources.

### Hypertext Transfer Protocol Secure (HTTPS)
{: #x2237225}

An Internet protocol that is used by web servers and web browsers to transfer and display hypermedia documents securely across the Internet.


## I
{: #glossi}

### IaaS
{: #x4585337}

See [infrastructure as a service](#x4585332).

### IAM
{: #x2193801}

See [identity and access management](#x7547040).

### {{site.data.keyword.cloud_notm}}
{: #x7301758}

An open-standards, cloud-based platform for building, managing, and running apps of all types, such as web, mobile, big data, and smart devices. Capabilities include Java, mobile back-end development, and application monitoring, as well as features from ecosystem partners and open source&mdash;all provided as-a-service in the cloud.

### identity and access management (IAM)
{: #x7547040}

The process of controlling access of authorized users to data and applications, while helping companies comply with various regulatory requirements.

### image
{: #x2024928}

A file system and its execution parameters that are used within a container runtime to create a container. The file system consists of a series of layers, combined at runtime, that are created as the image is built by successive updates. The image does not retain state as the container executes. See also [base image](#x5366487), [container](#x2010901), [layer](#x2028320), [namespace](#x2031005), [parent image](#x8439210), [private image repository](#x8439215), [registry](#x2064940).

### infrastructure as a service (IaaS)
{: #x4585332}

The delivery of a computer infrastructure, including server functionality, networking functionality, data center functionality, and storage functionality as an outsourced service.

### instance
{: #x2002531}

An entity that consists of resources that are reserved for a particular application or a service.

### intermediate certificate
{: #x3753781}

A subordinate certificate that is issued by the trusted root certificate authority (CA) specifically to issue end-entity server certificates. The result is a certificate chain that begins at the trusted root CA, passes through the intermediate certificate, and ends with the SSL certificate issued to the organization. See also [certificate authority](#x2016383), [trusted root](#x2042234).

### Internet of Things (IoT)
{: #x6714341}

The global network of endpoints that can capture or generate data. For example, a smartphone, smart watch and back-end server might all communicate with each other, sending data back and forth, or even to additional devices within the network.

### invoke
{: #x2057232}

To activate an action. See also [action](#x2012974).

### IoT
{: #x6714346}

See [Internet of Things](#x6714341).


## J
{: #glossj}

### JAR file
{: #x2406009}

A Java archive file.

### JavaScript Object Notation (JSON)
{: #x3292165}

A lightweight data-interchange format that is based on the object-literal notation of JavaScript. JSON is programming-language neutral but uses conventions from various languages.

### JSON
{: #x4267096}

See [JavaScript Object Notation](#x3292165).


## L
{: #glossl}

### layer
{: #x2028320}

A changed version of a parent image. Images consist of layers, where the changed version is layered on top of the parent image to create the new image. See also [container](#x2010901), [image](#x2024928).

### LDAP
{: #x2481619}

See [Lightweight Directory Access Protocol](#x2028538).

### light API call
{: #x7690463}

A client operation that only reads data. Light API calls use fewer resources than heavy API calls because they are performing a single function. See also [heavy API call](#x7690468).

### Lightweight Directory Access Protocol (LDAP)
{: #x2028538}

An open protocol that uses TCP/IP to provide access to directories that support an X.500 model and that does not incur the resource requirements of the more complex X.500 Directory Access Protocol (DAP). For example, LDAP can be used to locate people, organizations, and other resources in an Internet or intranet directory.

### local cloud
{: #x8439194}

A cloud computing environment within the client's data center. The local cloud is on-premises, providing improved latency and security. See also [borderless](#x8439189).


## M
{: #glossm}

### MBaaS
{: #x7044865}

See [mobile backend as a service](#x7044858).

### mobile app
{: #x7636517}

See [mobile application](#x4258535).

### mobile application (mobile app)
{: #x4258535}

An application that has been designed for a mobile platform. Similar to web applications, mobile apps provide some function beyond static display of information, for example, allowing the user to filter news in near real-time. See also [app](#x4281528).

### mobile backend as a service (MBaaS)
{: #x7044858}

A computing model that connects mobile applications to cloud computing services and provides features such as user management, push notifications, and integration with social networks through a unified API and SDK.

### mobile cloud
{: #x4585344}

An infrastructure in which the storage and processing of data for applications is offloaded from a mobile device into the cloud. With mobile cloud computing, applications are not limited to a specific carrier, but are accessed through the Web.

### multizone region (MZR)
{: #x9774820}

A region that is spread across data centers in multiple zones to increase fault tolerance. See also [zone](#x2070723).

### MZR
{: #x9774831}

See [multizone region](#x9774820).

## N
{: #glossn}

### namespace
{: #x2031005}

A unique name that identifies your organization's image repository within the IBM Cloud registry. See also [image](#x2024928), [private image repository](#x8439215).

### network address translation
{: #x2031199}

An addressing method that is used to enable one IP address to communicate with several other IP addresses, such as those on a private subnet, by means of a lookup table. Network address translation has two main types: 1-to-1 and many-to-1.


## O
{: #glosso}

### OAuth
{: #x6013335}

An HTTP-based authorization protocol that gives applications scoped access to a protected resource on behalf of the resource owner, by creating an approval interaction between the resource owner, client, and resource server.

### on-prem
{: #x6969434}

See [on-premises](#x4561212).

### on-premises (on-prem)
{: #x4561212}

Pertaining to software that is installed and run on the local computers of a user or organization.

### org
{: #x7470494}

See [organization](#x2032585).

### organization (org)
{: #x2032585}

The grouping methodology for users in IBM Cloud. Orgs are used to manage quotas. Users in an org share memory and service instance quotas. See also [domain](#x2021210), [space](#x2039442).


## P
{: #glossp}

### PaaS
{: #x2029790}

See [platform as a service](#x2029786).

### paravirtualized mode
{: #x9736806}

A lightweight virtualization technique. While in paravirtualized mode, a virtual machine does not require virtualization extensions from the host computer, thus allowing virtualization on hardware systems that do not support hardware-assisted virtualization.

### parent image
{: #x8439210}

An image that provides a base for another image. For example, Ubuntu Linux is the parent image of the IBM Liberty image. See also [base image](#x5366487), [image](#x2024928).

### platform as a service (PaaS)
{: #x2029786}

The delivery of a computing platform, including applications, optimized middleware, development tools, and Java and Web 2.0 runtime environments, in a cloud-based environment.

### pod
{: #x8461823}

A group of containers that are running on a Kubernetes cluster. A pod is a runnable unit of work, which can be a either a stand-alone application or a microservice.

### point of presence (PoP)
{: #x5458832}

A physical location that stores servers and routers in a network cloud.

### PoP
{: #x7234683}

See [point of presence](#x5458832).

### private cloud
{: #x4585362}

A cloud computing environment in which access is limited to members of an enterprise and partner networks. See also [public cloud](#x4585370).

### private image repository
{: #x8439215}

The combination of an organization's IBM Cloud registry and its namespace. The private image repository is used when referencing an image in a command. See also [image](#x2024928), [namespace](#x2031005).

### private key
{: #x2034701}

An algorithmic pattern used to encrypt messages that only the corresponding public key can decrypt. The private key is also used to decrypt messages that were encrypted by the corresponding public key. The private key is kept on the user system and is protected by a password.

### private resource
{: #x9439035}

An entry that is visible only to account owners and their included accounts. When resources are created, they are private by default. See also [public resource](#x9439040).

### private service
{: #x7690456}

A service that is visible only to members of a specified IBM Cloud organization.

### public cloud
{: #x4585370}

A cloud computing environment in which access to standardized resources, such as infrastructure, multi-tenant hardware, and services, is available to subscribers on a pay-per-use basis. See also [borderless](#x8439189), [private cloud](#x4585362).

### public gateway
{: #x9594389}

The connection of a subnet, with all virtual server instances attached, to the internet. A public gateway uses a many-to-1 network address translation (NAT), which means that thousands of virtual server instances with private addresses can use one public IP address to talk to the public internet.

### public resource
{: #x9439040}

An entry that is visible to everyone in the IBM Cloud catalog. Public resources can be built by any provider (IBM or third party providers). See also [private resource](#x9439035).

### push
{: #x2035465}

To send information from a server to a client. When a server pushes content, it is the server that initiates the transaction, not a request from the client.

### push notification
{: #x5599582}

An alert indicating a change or update on a mobile app icon.


## R
{: #glossr}

### read-mostly
{: #x7470468}

Pertaining to data that changes dynamically.

### red-black deployment
{: #x8439181}

A deployment technique that drives continuous delivery by enabling synchronized test, development, and deployment. Initially, development is done on an inactive environment (black) while the active environment continues to take traffic (red). Once deployment starts, both environments go live (red-red) until routing is disabled on the formerly active, previous version environment, then subsequently removed (black) while the new environment serves as the only active environment. See also [blue-green deployment](#x7807335).

### region
{: #x2091391}

A defined geographic territory. A region could be a specific postal code area, a town, a city, a state, a group of states, or even a group of countries. Each region can itself be a set of other regions or a set of postal codes that form the region.

### registry
{: #x2064940}

A public or private repository that contains images used to create containers. See also [container](#x2010901), [image](#x2024928).

### Representational State Transfer (REST)
{: #x3220976}

A software architectural style for distributed hypermedia systems like the World Wide Web. The term is also often used to describe any simple interface that uses XML (or YAML, JSON, plain text) over HTTP without an additional messaging layer such as SOAP.

### resource
{: #x2004267}

A physical or logical component that can be provisioned or reserved for an application or service instance.  Examples of resources include database, accounts, and processor, memory, and storage limits.

### resource group
{: #x2161955}

The environment, and constraints, in which contained resource instances adhere to. A user can be associated with a resource group to enable collaboration.

### REST
{: #x3220987}

See [Representational State Transfer](#x3220976).

### role
{: #x2065412}

A set of permissions or access rights.

### route
{: #x2037338}

The URL used to direct requests to an application. A route is made up of an optional host (or subdomain) and a domain that are specified when an application is pushed. For example, in the route myapp.example.com, myapp is the host and example.com is the domain. A route can be associated with one or more applications. Unless a custom domain is specified, IBM Cloud uses a default shared domain in the route to your application. See also [custom domain](#x5728384), [domain](#x2021210), [endpoint](#x2026820), [host](#x2002243), [subdomain](#x2040080), [Uniform Resource Locator](#x2042491).

### rule
{: #x2037526}

- A criteria that associates one trigger with one action, with every firing of the trigger causing the corresponding action to be invoked with the trigger event as input.
- A set of conditional statements that enable computer systems to identify relationships and run automated responses accordingly.

### runtime
{: #x2391929}

The set of resources used to run the application. See also [starter](#x7470511).


## S
{: #glosss}

### SaaS
{: #x4585391}

See [software as a service](#x4585386).

### scale
{: #x2004442}

To increase platform (or system) capacity by adding more application or service instances.

### scope
{: #x2037763}

In identity management, the set of entities that a policy or an access control item (ACI) can affect.

### Secure Sockets Layer (SSL)
{: #x2038004}

A security protocol that provides communication privacy. With SSL, client/server applications can communicate in a way that is designed to prevent eavesdropping, tampering, and message forgery. See also [certificate authority](#x2016383).

### select availability
{: #x9773835}

A production-ready offering that is available for sale and accessible to select customers.

### service
{: #x2038343}

A cloud extension that provides ready-for-use functionality, such as database, messaging, and web software for running code, or application management or monitoring capabilities. Services usually do not require installation or maintenance and can be combined to create applications.

### session
{: #x2004539}

The period of time after an app is started on a mobile device and the quality assurance product is notified to begin collecting app behavior, issues, and problems.

### single sign-on (SSO)
{: #x2213318}

An authentication process in which a user can access more than one system or application by entering a single user ID and password.

### single-zone region (SZR)
{: #x9774825}

A region that consists of data centers that are located within one zone, See also [zone](#x2070723).

### software as a service (SaaS)
{: #x4585386}

A model of software deployment whereby software including business processes, enterprise applications, and collaboration tools, are provided as a service to customers through the cloud.

### SOR
{: #x2214822}

See [system of record](#x6735061).

### space
{: #x2039442}

A sub-group within an {{site.data.keyword.cloud_notm}} org. Users who are members of an org are given access to one or more of its spaces, with permissions associated with a particular role (such as developer, manager, or auditor). Any member of the space can view apps, but only members with the developer role can create apps and add service instances to the space. Apps and service instances are associated with spaces. See also [organization](#x2032585).

### SSL
{: #x2483907}

See [Secure Sockets Layer](#x2038004).

### SSO
{: #x3456450}

See [single sign-on](#x2213318).

### stage
{: #x2067189}

To deploy an application, service, or instance to a pre-defined location  for running or testing before deployment to a production environment. See also [deployment](#x2104544).

### stanza
{: #x2094743}

A section of a software package that defines either a specific action to be performed on that the software package or a set of conditions under which actions are to be performed on the software package. The complete software package is a stanza that contains a hierarchy of many different stanzas.

### starter
{: #x7470511}

A template that includes predefined services and application code that is configured with a particular buildpack.  A starter might be application code that is written in a specific programming language, or a combination of application code and a set of services. See also [runtime](#x2391929).

### subdomain
{: #x2040080}

A domain that makes up a part of a larger domain. See also [custom domain](#x5728384), [domain](#x2021210), [host](#x2002243), [route](#x2037338), [Uniform Resource Locator](#x2042491).

### subnet
{: #x4282974}

See [subnetwork](#x2040149).

### subnetwork (subnet)
{: #x2040149}

A network that is divided into smaller independent subgroups, which still are interconnected.

### system of engagement
{: #x6528306}

An information technology (IT) system that incorporates technologies that encourage user interaction through email, collaboration systems, and networking.  A system of engagement often uses cloud technologies to extend the usefulness of systems of record. See also [system of record](#x6735061).

### system of record (SOR)
{: #x6735061}

An information storage system (such as a database or application) that stores business records and automates standard processes. See also [system of engagement](#x6528306).

### SZR
{: #x9774829}

See [single-zone region](#x9774825).


## T
{: #glosst}

### target
{: #x2262507}

The resource or set of resources to provide a subject access to in an access policy. The set of resources is defined by one or more attributes. For example, a target could be all resources in a resource group, all resources of a certain resource type, or the resource with a certain resource ID.

### template
{: #x2041200}

A predefined structure for an artifact.

### third-party
{: #x2877945}

Pertaining to a product or service that is provided by a company other than IBM.

### tile
{: #x2092493}

A visual representation of a running application that provides status on a dashboard.

### trigger
{: #x2005384}

A mechanism that initiates actions. Triggers can be explicitly fired by a user or fired on behalf of a user by an external event source.

### trusted root
{: #x2042234}

A certificate signed by a trusted certificate authority (CA). See also [certificate authority](#x2016383), [intermediate certificate](#x3753781).


## U
{: #glossu}

### Uniform Resource Identifier (URI)
{: #x2116436}

A unique address that is used to identify content on the web. The most common form of URI is the web page address, which is a particular form or subset of URI called a Uniform Resource Locator (URL). A URI typically describes how to access the resource, the computer that contains the resource, and the location of the resource on that computer.

### Uniform Resource Locator (URL)
{: #x2042491}

The unique address of an information resource that is accessible in a network such as the Internet. The URL includes the abbreviated name of the protocol used to access the information resource and the information used by the protocol to locate the information resource. See also [custom domain](#x5728384), [domain](#x2021210), [host](#x2002243), [route](#x2037338), [subdomain](#x2040080).

### URI
{: #x2116461}

See [Uniform Resource Identifier](#x2116436).

### URL
{: #x2042718}

See [Uniform Resource Locator](#x2042491).

### user
{: #x2069659}

An IBMid or SoftLayer ID that is used as a person's identity in an account.

## V
{: #glossv}

### virtual
{: #x2043123}

Pertaining to not physically existing as such but made by software to appear to do so.

### virtual local area network (VLAN)
{: #x2438470}

A logical association of switch ports based upon a set of rules or criteria, such as Medium Access Control (MAC) addresses, protocols, network address, or multicast address. This concept permits the LAN to be segmented again without requiring physical rearrangement.

### virtual machine (VM)
{: #x2043165}

A software implementation of a machine that executes programs like a real machine. See also [virtual server](#x2455638).

### virtual private cloud
{: #x4585403}

A virtual network that is tied to a private user account and isolated from other networks in a public cloud. Only authorized users can access virtual private cloud resources, which include virtual servers, storage, and subnets.

### virtual private network
{: #x2043188}

A private connection between two endpoints, even when the data is transferred across a public network. 
Data can be shared as if a connection to a private network is established. Usually, a VPN is used in combination with security methods, such as authentication and encryption, to provide maximum data security and privacy.

### virtual server
{: #x2455638}

A server that shares its resources with other servers to support applications. See also [virtual machine](#x2043165).

### VLAN
{: #x2484337}

See [virtual local area network](#x2438470).

### VM
{: #x2043253}

See [virtual machine](#x2043165).

### VPN
{: #x2484351}

See [virtual private network](#x2043188).

### volume
{: #x2043272}

A fixed amount of physical or virtual storage on a data storage medium.

## W
{: #glossw}

### WAR
{: #x2844389}

See [web archive](#x2116506).

### WAR file
{: #x2406005}

See [web archive](#x2116506).

### web app
{: #x7636628}

See [web application](#x2116500).

### web application (web app)
{: #x2116500}

An application that is accessible by a web browser and that provides some function beyond static display of information, for instance by allowing the user to query a database. Common components of a web application include HTML pages, JSP pages, and servlets. See also [app](#x4281528).

### web archive (WAR)
{: #x2116506}

A compressed file format, defined by the Java EE standard, for storing all the resources required to install and run a web application in a single file.

### workspace
{: #x2096037}

A context that contains a collection of artifacts that a user with appropriate permission can modify.

## Z
{: #glossz}

### zone
{: #x2070723}

An independent fault domain. A zone is an abstraction designed to assist with improved fault tolerance and decreased latency. See also [multizone region](#x9774820), [single-zone region](#x9774825).


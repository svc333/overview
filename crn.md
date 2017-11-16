---

copyright:

  years: 2017

lastupdated: "2017-11-07"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:tip: .tip}

# Cloud Resource Names
{: #crn}

Cloud Resource Names (CRNs) uniquely identify {{site.data.keyword.Bluemix_notm}} resources. A CRN is used to specify a resource in a way that is unambiguous and guaranteed to be globally unique, such as in {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) policies and services listed in the cloud catalog.

A CRN is formed from a concatenation of "segments" that hierarchically identify the resource, its location, and the service it belongs to. The segment delimiter is set to ':' (i.e. the colon character). All CRNs begin with the segment identifier 'crn'.


## CRN Format
{: #format}

The base canonical format of a CRN is:

**crn:[version](#version):[cname](#cname):[ctype](#ctype):[service-name](#service-name):[location](#location):[scope](#scope):[service-instance](#service-instance):[resource-type:resource](#resource-type)**


## version
{: #version}

The `version` segment identifies the version of the CRN format. Currently the only valid version segment value is **v1**.


## cname
{: #cname}

The `cname` segment identifies the cloud instance and is an alphanumeric identifier that uniquely identifies the cloud instance that contains the resource. A `cname` effectively identifies an independent control plane that owns the identified resource. The `cname`must be `bluemix` for {{site.data.keyword.Bluemix_notm}} users.


## ctype
{: #ctype}

The `ctype` segment identifies the type of cloud instance that is represented by the specified `cname`.

>Valid values:
  - public - All services that are available from the public catalog.
  - dedicated - Only for current {{site.data.keyword.Bluemix_notm}} dedicated environments.
  - local - All services that are deployed locally in your own environment.


## service-name
{: #service-name}

The `service-name` segment uniquely identifies a capability (service, component, product) being offered by the cloud. The capability can be a user provided service such as with the services that are listed in the {{site.data.keyword.Bluemix_notm}} catalog, or an internal architectural component critical to the {{site.data.keyword.Bluemix_notm}} functionality.

The `service-name` indicates the service that the resource belongs to, and {{site.data.keyword.Bluemix_notm}} enforces global uniqueness of service names. The `service-name` must be alphanumeric, lowercase, no spaces or special characters other than '-'.

For services that are registered into the {{site.data.keyword.Bluemix_notm}} Catalog the `service-name` must correspond to one of the services registered to the {{site.data.keyword.Bluemix_notm}} Global Catalog service. It is the `name` property returned by the {{site.data.keyword.Bluemix_notm}} Global Catalog service API `GET https://resource-catalog.bluemix.net/api/v1/{id}` for the corresponding resource instance or the `service-name` displayed by the command line interface: `bx service offerings` in the column `service`.


## location
{: #location}

The cloud geography/region/zone/data center that the resource resides in.

The `location` must be one of the following values:

### Global

 * `global`

### Geographies

 * `us`
 * `eu`
 * `cn`
 * `ap`

### Regions

 * `us-south`
 * `au-syd`
 * `eu-gb`
 * `eu-de`

### Data Centers


| | | | | |
|---|---|---|---|---|
| AMS01  | AMS03  | CHE01  | DAL01  |  DAL05  |
| DAL06  | DAL07  | DAL09  | DAL10  |  DAL12  |
| DAL13  | FRA02  | HKG02  | HOU02  |  LON02  |
| MEL01  | MEX01  | MIL01  | MON01  |  OSL01  |
| PAR01  | SJC01  | SJC03  | SAO01  |  SEA01  |
| SEO01  | SNG01  | SYD01  | TOK02  |  TOR01  |
| WDC01  | WDC04  | WDC06  | WDC07  |
{: caption="Table 1. Valid `Data Center` values" caption-side="top"}

Some resources do not require a region (they can be considered `global`). In this case, the `region` segment is set to `global`.
{: tip}


## scope
{: #scope}

The `scope` segment identifies the containment or owner of the resource. Some resources do not require an owner (they can be considered `global`). In this case, the `scope` segment is empty (a blank string).

The value of the `scope` segment must be formatted as `{scopePrefix}`/`{id}`. The `scopePrefix` represents the format used to identify the owner or containment. The `id` represents the identity of the owner or containment in a format that is specific to the `scopePrefix`.

| Scope Type | Scope Prefix | Usage | Example |
| --- | --- | --- | --- |
| Account | a/`{account id}` | The account that the resource has been created in. | a/292558 |
| Organization | o/`{org guid}` | The {{site.data.keyword.Bluemix_notm}} Organization to which the resource has been assigned. | o/4716e2d1-35b7-431f-891a-b552bf0b3c66 |
| Space | s/`{space guid}` | The {{site.data.keyword.Bluemix_notm}} Space to which the resource has been assigned. | s/48b3cdcd-e804-4398-9032-73065863ad7c |
{: caption="Table 2. `scope` usage" caption-side="top"}

The `account id` must be the IBM account id ({{site.data.keyword.Bluemix_notm}} and Softlayer linked accounts).


## service-instance
{: #service-instance}

The `service-instance` segment identifies the service instance uniquely. The format of the `service-instance` segment varies by service. Each service must document the format of their `service_instance` as part of their service metadata. Some services do not have instances because the instance is global and in this case the `service-instance` field will be blank.

The `service-instance` must be alphanumeric, lower case, no spaces or special characters other than '-' and '/'.

As an example, a devops tool to track and plan work items can have a simple `GUID` instance id ("1234-5678-9012-3456") where the policy component of an autoscale group service can use a hierarchical naming convention and have a `service-id` segment of:

>`c7a27f55-d35e-4153-b044-8ca9155fc467/my-test-asg1/my-scaleout-policy`


## resource-type, resource
{: #resource-type}

The value of the `resource-type` and `resource` segments vary by service. A service is required to document their supported `resource types` and the format of the `resource` as part of their service metadata.

As an example, an image in the customer receipts container in an Object Storage service can have a `resource-type` of  `object` and a `resource_ value` of `CustomerReceipts/clientdinner.png`. 

The `resource-type` must be alphanumeric, lower case, no spaces or special characters other than '-'. A service can decide that the `resource-type` is optional, in which case it would be left blank.


## CRN Examples
{: #crn_examples}

The following is a list of CRN examples.

| Example | Value |
| --- | --- |
| Container | ```crn:v1:bluemix:public:containers-kubernetes:us-south:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:8042b2a8af6a4a5cbf6dbe09e07311d2:worker:kube-hou02-pa8042b2a8af6a4a5cbf6dbe09e07311d2-w1:```{: codeblock} |
| Resource Group | ```crn:v1:bluemix:public:resource-controller: global:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:resource-group:59bcbfa6ea2f006b4ed7094c1a08dcdd```{: codeblock} |
| Service Instance | ```crn:v1:bluemix:public:cloud-object-storage:global:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:1a0ec336-f391-4091-a6fb-5e084a4c56f4::```{: codeblock} |
| Bucket | ```crn:v1:bluemix:public:cloud-object-storage:global:a/59bcbfa6ea2f006b4ed7094c1a08dcdd:1a0ec336-f391-4091-a6fb-5e084a4c56f4:bucket:mybucket```{: codeblock} |
{: caption="Table 3. CRN examples" caption-side="top"}



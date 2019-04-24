---

copyright:
  years: 2017, 2019
lastupdated: "2019-01-07"

---

{:shortdesc: .shortdesc}

# 我如何知道自己的数据是安全的？
{: #security}

{{site.data.keyword.cloud_notm}} 平台是使用安全工程实践进行设计的，通过不同的层对整个网络和基础架构中的安全进行控制。{{site.data.keyword.cloud_notm}} 提供了一组安全服务，应用程序开发者可以使用这些服务来保护自己的移动和 Web 应用程序。这些优势组合在一起，使 {{site.data.keyword.cloud_notm}} 平台成为安全应用程序开发的不二选择。


{{site.data.keyword.cloud_notm}} 所遵循的安全策略基于 IBM 的系统、网络和安全工程最佳实践，因此可确保安全性准备到位。这些策略包括源代码扫描、动态扫描、威胁建模和渗透测试等相关实践。{{site.data.keyword.cloud_notm}} 遵循 IBM 产品安全事件响应小组 (PSIRT) 的安全事件管理流程。有关详细信息，请参阅 [IBM Security Vulnerability Management (PSIRT) ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")](https://www.ibm.com/security/secure-engineering/process.html){: new_window} 站点。

{{site.data.keyword.cloud_notm}} Public 和 Dedicated 使用经典基础架构即服务 (IaaS) 云服务，并充分利用了其安全体系结构。经典 IaaS 提供了多个重叠层来保护应用程序和数据。对于 {{site.data.keyword.cloud_notm}} Local，您拥有物理安全性，并可通过在位于公司防火墙后您自己的数据中心内托管 {{site.data.keyword.cloud_notm}} Local 来提供基础架构。此外，{{site.data.keyword.cloud_notm}} 还在“平台即服务”(PaaS) 层添加了不同类别（平台、数据和应用程序）的安全功能。有关 {{site.data.keyword.Bluemix_notm}} 中环境和应用程序的进一步安全性详细信息，请参阅[确保云上应用程序和环境的安全 ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")](https://www.ibm.com/cloud/garage/architectures/securityArchitecture){: new_window}。

## {{site.data.keyword.Bluemix_notm}} 合规性
{: #compliance}

{{site.data.keyword.Bluemix}} 为您提供了一个可信赖的安全云平台。{{site.data.keyword.Bluemix_notm}} 合规性是通过基于业界最佳安全标准（包括 ISO 27001 和 ISO 27002）构建的平台和服务来实现的。
{:shortdesc}

![欧盟数据保护示范条款](images/icon_eumc.png) 协议引入**欧盟 (EU) 示范条款**，可保护从欧盟 (EU) 或欧洲经济区 (EEA) 传输到第三方国家或地区的个人数据。“欧盟 (EU) 示范条款”由位于欧盟或欧洲经济区的客户（数据导出方）与位于第三方国家或地区的 IBM 数据处理方（数据导入方）共同签订。[IBM Data Processing Addendum (with EU Standard Contractual Clauses) ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")](http://www-01.ibm.com/common/ssi/cgi-bin/ssialias?subtype=ST&infotype=SA&htmlfid=KUJ12408USEN&attachment=KUJ12408USEN.PDF){: new_window} 包含数据导出方和数据导入方的权利和责任，以及数据主体的权利。针对第三方国家或地区处理的个人数据，IBM Data Processing Addendum 提供的保护类似于 EU 或 EEA 中所提供的保护。


![金融行业信息系统](images/FISC.gif) 对于日本的银行和相关金融机构，计算机系统必须具有适当的安全程序，这些程序应基于金融行业信息系统中心 (FISC) 安全准则。FISC 安全准则由日本金融厅 (FSA)、日本央行 (BOJ) 和 FISC 贯彻实施。
 

![ISO 27001/2](images/icon_iso27k1.png) {{site.data.keyword.Bluemix_notm}} 已通过**国际标准化组织 (ISO) 27001 和 27002 标准**的认证，这两个标准定义了有关信息安全管理流程的最佳实践。ISO 27001 是一种被广泛采用的全球安全标准。该标准概述了信息安全管理系统的要求，并提供了一种基于定期风险评估来管理公司和客户信息的系统化方法。最新标准 ISO/IEC 27001:2013 由**国际标准化组织 (ISO) 和国际电工技术委员会 (IEC)** 联合组建的 ISO/IEC 子委员会于 2013 年 9 月 25 日颁布。ISO 27001 标准规定了根据不同组织的需求，应如何建立、实施和记录信息安全管理系统 (ISMS)，以及应如何实施安全控制措施。ISO 27002 标准对 ISO 27001 的每种安全控制措施进行了详细说明。ISO 27000 系列标准中包含了一个确定风险规模和评估资产价值的过程，旨在确保书面、口头和电子信息的机密性、完整性和可用性。

要获得 ISO 27001:2013 认证，公司必须证明对于影响公司和客户信息机密性、完整性和可用性的信息安全风险，其具有系统化的持续管理方法。此标准着重于测量和评估组织的信息安全管理系统 (ISMS) 的表现情况。此外，此标准还包含与信息安全相关且基于系统需求和其他需求的控制措施。

{{site.data.keyword.Bluemix_notm}} 已经过第三方安全公司审计，可满足 ISO 27001 的所有要求：[Bluemix ISO 27001:2013 注册证书 ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")](ftp://public.dhe.ibm.com/cloud/bluemix/compliance/Bluemix_ISO27K1_WWCert_2016.pdf){: new_window}。

![PCI DSS](images/icon_pci.png) **支付卡行业 (PCI) 数据安全标准 (DSS)** 是一种旨在保护信用卡数据的信息安全标准。PCI DSS 适用于支付卡处理中所涉及的所有实体，包括商家、处理机构、发卡机构和服务提供者。此外，还适用于存储、处理或传输持卡人数据或敏感认证数据的其他所有实体。

如果您要存储或处理信用卡数据，那么支付卡行业 (PCI) 合规性和网络安全将是您企业关心的主要问题。为了确保商家使用的标准是一致的，支付卡行业安全标准委员会制定了 PCI 数据安全标准。这些标准整合了用于保护持卡人数据的最佳实践，并且通常需要第三方合格服务评估方 (QSA) 进行验证。IBM 提供的“合规证明”来自于独立的 QSA，因此可帮助客户满足其 PCI 合规性需求。“合规证明”可与 SOC 2 报告以及 ISO 27001 认证配合使用，以证明基础架构满足 PCI 控制要求。

{{site.data.keyword.Bluemix}} 通过经批准的合格安全评估方 (QSA) 完成了年度 PCI DSS 评估。有关如何确保您的 {{site.data.keyword.Bluemix_notm}} 环境符合 PCI DSS 评估要求的信息和帮助，请联系销售人员：[联系我们 ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")](https://cloud.ibm.com/?direct=classic/#/contactUs/cloudOEPaneId=contactUs){: new_window}。

![SSAE16 SOC1/2/3](images/icon_aicpa.png) **服务性机构控制体系鉴证 (SOC)** 报告定义了如何评估服务性机构中与安全性、可用性、处理完整性、机密性和隐私性相关的主要内部控制措施。这些报告是根据美国注册会计师协会 (AICPA) 指南生成的，具体包含以下各项： 
  * 组织监督
  * 供应商管理计划
  * 内部公司治理和风险管理流程
  * 法规监督
 
{{site.data.keyword.Bluemix_notm}} 提供 SOC 1、SOC 2 和 SOC 3 报告。有关更多信息，请联系 [{{site.data.keyword.Bluemix_notm}} 销售 ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")](mailto:bmxcert1@us.ibm.com){:new_window} 团队。 

![HIPAA](images/icon_hipaa.png)《健康保险可移植性和责任法案》(HIPAA) 是美国国会在 1996 年颁布的，旨在保障员工在失业后仍能享受健康保险。HIPAA 由美国民权办公室和卫生与公众服务部负责监管和实施。除了 1996 年法案中的规定，HIPAA 还包含 2009 年颁布的《医疗信息技术促进经济和临床健康法案》(HITECH) 中对隐私的要求。{{site.data.keyword.Bluemix_notm}} 符合 HIPAA 有关数据中心或服务提供者方面的所有要求。 

将 {{site.data.keyword.Bluemix_notm}} Public 与经典基础架构合并可能会导致发生一些问题。有关如何确保您的 {{site.data.keyword.Bluemix_notm}} 环境符合 HIPAA 合规性要求、通过 HIPAA 合规性认证以及保持 HIPAA 合规性的更多信息或帮助，请联系 {{site.data.keyword.Bluemix_notm}} [销售 ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")](mailto:cloudplatform_compliance@us.ibm.com){:new_window} 团队。

![ISO 27017](images/icon_ISO27017.png) ISO/IEC 27017:2015 提供了适用于供应和使用云服务的信息安全控制措施准则。此外，还为云服务提供商和云服务客户提供了实施指南。ISO 27017 针对 ISO/IEC 27002 中规定的相关控制措施提供了实施指南，同时还提供了专门与云服务相关的更多控制措施与指南。

{{site.data.keyword.Bluemix_notm}} 符合 ISO 27017:2015 的要求，这证明了 IBM 拥有一套成熟的特定于云的安全控制系统。此外，还表明了 IBM 致力于成为美国国内乃至全球 IaaS 领域的最佳企业。

![ISO 27018](images/icon_ISO27018.png) ISO 27018:2014 制定了普遍认可的控制目标、控制措施和准则，以便实施用于保护个人可标识信息 (PII) 的各项措施。这些措施符合 ISO 29100 中有关公共云计算环境的隐私原则。

此外，ISO 27018:2014 还特别规定了基于 ISO 27002 的准则。这些准则考虑了有关保护 PII 的法规需求，这些需求可能适用于公共云服务提供商的信息安全风险环境。

![云安全联盟 - STAR Registrant](images/icon_CSA.png) 云安全联盟是一个非营利组织，其使命是大力推广在云计算中使用最佳实践来提供安全保证。云安全联盟为实现其使命而使用的机制之一是“安全信任与保证注册项目”(STAR)。STAR 是一个免费的、可公开访问的注册项目，用于记录各种云计算产品提供的安全控制措施。

![CJIS 标准](images/icon_CJIS.png) 刑事司法信息系统部 (CJIS) 是美国联邦调查局司法部下属的一个部门。CJIS 部制定并颁布了安全政策 (CJISD-ITS-DOC-08140-5.4)。此安全政策包含最低信息安全需求、准则和协议，反映了执法部门和刑事司法机构对于保护刑事司法信息 (CJI) 的来源、传输、存储和生成的意愿。

## 平台和服务合规性
{: #compliancetable}

下表显示了 {{site.data.keyword.Bluemix_notm}} 中符合每种标准的服务。

|{{site.data.keyword.Bluemix_notm}} 组件|FISC|ISO 27001|PCI|SOC 2 第 1 类|
|:----------------------|:---------:|:---------:|:---------:|:---------:|
|{{site.data.keyword.Bluemix_notm}} 平台|是|是|是|是|
|{{site.data.keyword.openwhisk_short}}    |  |是| | |
|{{site.data.keyword.APIM}}			|是|是|是|			|
|{{site.data.keyword.autoscaling}}			|是|是|是|			|
|{{site.data.keyword.bigicloudst}}			|是|是|	|是|
|{{site.data.keyword.cloudant}}				|是|是|	|是|
|{{site.data.keyword.dashdbshort}}			|是|是|	|是|
|{{site.data.keyword.dataworks_short}}				|	|	|	|是|
|{{site.data.keyword.contdelivery_short}}					|是|是|	|			|
|{{site.data.keyword.containerlong}}			|是|是|	|		是|
|{{site.data.keyword.dwl_short}}				|	|	|	|是|
|{{site.data.keyword.mql}}				|是|是|是|	 		|
|{{site.data.keyword.SecureGateway}}			|是|是|	|	 		|
{: caption="表 1. 平台和服务合规性" caption-side="top"}

## 一般数据保护条例 (GDPR)
{: #gdpr}

GDPR 力求在整个欧盟建立协调统一的数据保护法律框架，目的是让公民重获对其个人数据的控制权，同时针对在全球任何位置托管和处理这些数据的行为实施严格规则。 

{{site.data.keyword.IBM_notm}} 致力于为客户和 {{site.data.keyword.IBM_notm}} 业务合作伙伴提供创新的数据隐私、安全和监管解决方案，以帮助他们最终符合 GDPR 条例的要求。数据与数据保护对于个人和社会越来越重要。企业必须以其出色的信息管理能力赢得客户的信赖。 

{{site.data.keyword.Bluemix_notm}} 具有灵活且可扩展的内置数据安全性与隐私服务和解决方案，可在内部部署中或通过公共云使用。我们的综合数据安全平台提供了全面的数据保护功能，可帮助您保护位于任何位置的敏感数据。

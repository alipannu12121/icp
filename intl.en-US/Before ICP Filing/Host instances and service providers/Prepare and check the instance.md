# Prepare and check the instance {#concept_m5j_vrl_zdb .concept}

If the instance that hosts your website is located in **Mainland China**, you must apply for an ICP filing before providing services on your website. When reviewing your ICP filing application, the Ministry of Industry and Information Technology \(MIIT\) verifies the information about your instance. This topic describes how to check the instance information when you host your website in an instance that is purchased from Alibaba Cloud or Alibaba Cloud Marketplace and located in Mainland China.

Check the following items to make sure that your instance meets the ICP filing requirements:

-   Check item 1: [Access information](#section_32u_in6_s7w)
-   Check item 2: [Other Alibaba Cloud services](#section_hdy_646_3dy)
-   Check item 3: [Changes of access information](#section_5rg_hzp_tlm)

## Access information {#section_32u_in6_s7w .section}

When reviewing your ICP filing application, MIIT verifies the following access information about your instance: service provider, access method, server location, and website IP address.

If you host your website on an on-premises server or in an on-premises data center, you need to contact your Internet Service Provider \(ISP\), such as China Telecom and China Unicom, to apply for an ICP filing.

If you host your website in an Alibaba Cloud instance, you can apply for an ICP filing by using the [Alibaba Cloud ICP Filing system](https://beian.aliyun.com/order/index.htm) \(available in Chinese only\). Check the following information before you apply for an ICP filing:

-   **Instance location**:

    The instance is located in **Mainland China**.

-   **Instance type**:

    The instance is of the specified type and meets the requirement on the subscription duration. For more information about supported instances and purchase requirements, see [Table 1](#table_bob_0qy_xzo).

-   **Number of websites that can be filed**:

    The number of service identification numbers that can be applied for each supported instance varies depending on its type. Make sure that the instance you purchase has sufficient service identification number quotas. For more information about the number of websites supported by each instance type, see [Table 1](#table_bob_0qy_xzo).

    **Note:** 

    -   If you use the same Alibaba Cloud account to purchase the instance and apply for an ICP filing, you can directly select the instance during the ICP filing application process. You do not need to apply for a service identification number separately. You can directly select the instance or apply for a service identification number to apply for an ICP filing. In either method, one service identification number quota will be consumed for the instance.
    -   If you use separate Alibaba Cloud accounts to purchase the instance and apply for an ICP filing, we recommend that you use the account that is used to purchase the instance to log on to the Alibaba Cloud ICP Filing Management console and apply for a service identification number. For more information, see [Apply for a service identification number](reseller.en-US/Before ICP Filing/Host instances and service providers/Apply for a service identification number.md#).
    -   To apply for an ICP filing, you must provide a service identification number. If you have used a service identification number to apply for an ICP filing, you cannot reuse it to apply for another ICP filing. After you cancel the ICP filing or remove a service provider from the ICP filing information, the service identification number is still considered used. You cannot reuse it to apply for an ICP filing for another website.

The following table lists the supported instances and the number of service identification numbers supported by each instance type.

**Note:** After you purchase an Alibaba Cloud instance located in mainland China, we recommend that you pay attention to the expiration date and renew the instance in a timely manner. If the instance expires, your website cannot be accessed. As a result, your website may be identified as a shell website. If this issue occurs and is not handled in time, the ICP filing will be canceled and your business will be affected.

|Instance type|Purchase requirement|Shopping URL|Number of service identification numbers|
|:------------|:-------------------|------------|:---------------------------------------|
|Elastic Compute Service \(ECS\)| -   The instance is located in Mainland China.

-   The subscription duration is three months or more.

-   You need to purchase the public network bandwidth.

 **Note:** 

-   You cannot apply for service identification numbers for pay-as-you-go instances.
-   For more information about public network bandwidth, see [Overview of configuration changes](https://help.aliyun.com/document_detail/25437.html) \(available in Chinese only\).

 |[ECS](https://help.aliyun.com/document_detail/87190.html)|5 for each instance|
|Web Hosting| -   The instance is located in Mainland China.

-   The subscription duration is three months or more.


 |[Web Hosting](https://help.aliyun.com/knowledge_detail/36189.html)|5 for each instance|
|Simple Application Server| -   The instance is located in Mainland China.

-   The subscription duration is three months or more.


 |[Simple Application Server](https://help.aliyun.com/document_detail/59072.html)|5 for each instance|
|Elastic Web Hosting| -   The instance is located in Mainland China.

-   The subscription duration is six months or more.

 |[Elastic Web Hosting](https://help.aliyun.com/document_detail/66271.html)|5 for each Alibaba Cloud account|
|Alibaba Cloud Marketplace website building product| -   The initial subscription duration is 12 months or more.
-   The order amount is RMB 99 or more.

 |[Alibaba Cloud Marketplace](https://market.aliyun.com/)|1 for each instance|
|Network Address Translation \(NAT\) Gateway| -   The instance is located in Mainland China.

-   The subscription duration is one month or more.


 |[NAT Gateway](https://help.aliyun.com/document_detail/65158.html)|2 for each instance|
|IPv6 Translation Service| -   The instance is located in Mainland China.

-   The subscription duration is one month or more.


 |[IPv6 Translation Service](https://help.aliyun.com/document_detail/85799.html)|2 for each instance|
|Edge Node Service \(ENS\)| -   The instance is located in Mainland China.

-   The subscription duration is three months or more.


 |[ENS](https://help.aliyun.com/document_detail/100677.html)|5 for each instance|

## Other Alibaba Cloud services {#section_hdy_646_3dy .section}

If your website uses Alibaba Cloud services including Object Storage Service \(OSS\), Content Delivery Network \(CDN\), Web Application Firewall \(WAF\), and Anti-DDoS Pro, you need to determine whether to add Alibaba Cloud to the ICP filing information as a service provider based on actual scenarios.

|Service|Scenario|Requirement|
|:------|:-------|:----------|
|OSS|If you associate your custom domain name to an OSS endpoint, you need to apply for an ICP filing for your domain name. For more information, see [Bind a custom domain](../../../../../reseller.en-US/Developer Guide/Buckets/Bind a custom domain.md#).|You only need to apply for an ICP filing for your website. It is not required to add Alibaba Cloud to the ICP filing information as a service provider.|
|CDN|Websites that are hosted on instances located in Mainland China and use Alibaba Cloud CDN must have ICP filings.| -   If the origin site is hosted on Alibaba Cloud instances located in Mainland China, you need to apply for an ICP filing by using the Alibaba Cloud ICP Filing system.
-   If the origin site is hosted on instances provided by other service providers, you need to add Alibaba Cloud to the ICP filing information as a service provider.

 |
|WAF|Websites that are hosted on instance located in Mainland China and use Alibaba Cloud WAF for protection must have ICP filings.|
|Anti-DDoS Pro|Websites that are hosted on instances located in Mainland China and use Anti-DDoS Pro for protection must have ICP filings.| -   If you have enabled China Telecom and China Unicom lines when you configure Anti-DDoS Pro, you do not need to add Alibaba Cloud to the ICP filing information as a service provider.
-   If you have enabled BGP multi-path when you configure Anti-DDoS Pro, you need to add Alibaba Cloud to the ICP filing information as a service provider.

 |

## Changes of access information {#section_5rg_hzp_tlm .section}

If the service provider or instance IP address of your website changes, you need to perform the required operation accordingly.

-   If you have applied for an ICP filing for your website through another service provider before and you want to host the website on an Alibaba Cloud instance or resolve the subdomains to Alibaba Cloud instances, you need to add Alibaba Cloud to the ICP filing information.

    **Note:** 

    To check whether your website has an ICP filing, go to the [ICP filing management system of MIIT](http://www.beian.miit.gov.cn) and choose **Public Information Query** \> **ICP Filing Query** \(available in Chinese only\).

-   If you have applied for an ICP filing for your website through Alibaba Cloud and you want to host the website on another Alibaba Cloud instance, you only need to modify the DNS configuration to resolve the domain name to the new instance. In this case, you do not need to apply for an ICP filing again.

    **Note:** To host the website on an instance provided by another service provider, you need to add the new service provider to the ICP filing information. For more information about the procedure, consult the new service provider.



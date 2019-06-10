# Prepare and check the instance or server {#concept_m5j_vrl_zdb .concept}

If the instance or server that hosts your website is located in **Mainland China**, you must register an ICP filing before your website starts providing services. The information of the instance will be verified. This topic describes how to check the instance or server information before you apply for an ICP filing if your website is hosted on an instance or server located in Mainland China.

Check the following items to make sure that the instance or server meets the requirements:

-   Check item 1:[Connection information](#section_32u_in6_s7w)
-   Check item 2:[Other Alibaba Cloud services](#section_hdy_646_3dy)
-   Check item 1:[Changes of service provider information](#section_5rg_hzp_tlm)

## Connection information {#section_32u_in6_s7w .section}

During the verification process, information about the service provider, connection method, server or instance location, and website IP address will be verified.

If you host your website on servers or server rooms that are built by yourself, you need to contact the ISP, for example, China Telecom or China Unicom, for the information to register an ICP filing.

If you host your website on an Alibaba Cloud instance, you can apply for an ICP filing through the [Alibaba Cloud ICP Filing system](https://beian.aliyun.com/order/index.htm). Confirm the following information before you apply for ICP filing:

-   **Instance Location**:

    The Alibaba Cloud instance must be located in **Mainland China**.

-   **Instance Type**:

    You must specify an Alibaba Cloud instance with a valid subscription. For more information about supported instances, see the following table [Table 1](#table_bob_0qy_xzo).

-   **Number of Websites**:

    The number of service identification numbers that you can apply for each supported instance varies depending on its type. Make sure that the instance you purchase has sufficient service identification number quotas. For more information about the number of websites supported by each instance, see the following table [Table 1](#table_bob_0qy_xzo).

    **Note:** 

    -   If you use the same Alibaba Cloud account to purchase the instance and register an ICP filing, you can directly select the instance that needs an ICP filing during the registration process. You do not need to apply for a service identification number. You can directly select the instance or apply for a service identification number for registering an ICP filing. The number of websites supported by each instance remains the same no matter which method you choose.
    -   If you use separate Alibaba Cloud accounts to purchase the instance and register an ICP filing, we recommend that you use the account that is used to purchase the instance to log on to the Alibaba Cloud console and apply for a service identification number. For more information, see [Apply for service identification numbers](intl.en-US/Before ICP Filling/Host instances and service providers/Apply for service identification numbers.md#).
    -   To register an ICP filing, you must apply for a service identification number first. If you have used the service identification number before, you cannot reuse it to apply for another ICP filing. After you cancel an ICP filing or remove a service provider from the registration information, the service identification number is still considered used. You cannot reuse it to register an ICP filing for another website.

The following table lists the supported instances and the number of websites supported by each instance type:

|Instance type|Requirement|Number of service identification numbers|
|:------------|:----------|:---------------------------------------|
|ECS Instances| -   The subscription duration must be three months or more.
-   You must purchase a public network bandwidth.

 **Note:** 

-   You cannot apply for service identification numbers for Pay-As-You-Go instances.
-   For more information about public network bandwidth, see [Upgrades and downgrades](https://help.aliyun.com/document_detail/25437.html).

 |You can apply for up to five service identification numbers for each instance.|
|Web Hosting instances|The subscription duration must be three months or more.|You can apply for up to five service identification numbers for each instance.|
|Simple Application Server instances|The subscription duration must be three months or more.|You can apply for up to five service identification numbers for each instance.|
|Elastic Web Hosting instance|The subscription duration must be six months or more.|Each Alibaba Cloud account can apply for up to five service identification numbers.|
|Alibaba Cloud Marketplace website building instances| -   The initial subscription duration must be 12 months or more.
-   The order must be 99 RMB or more.

 |You can apply for one service identification number.|
|NAT Gateway instances|The subscription duration must be one month or more.|You can apply for up to two service identification numbers for each instance.|
|IPv6 Translation Service instances|The subscription duration must be one month or more.|You can apply for up to two service identification numbers for each instance.|
|Edge Node Service \(ENS\) instances|The subscription duration must be three months or more.|You can apply for up to five service identification numbers for each instance.|

## Other Alibaba Cloud services {#section_hdy_646_3dy .section}

If your website uses Alibaba Cloud services including Object Storage Service \(OSS\), Alibaba Cloud CDN, Web Application Firewall \(WAF\), and Anti-DDoS Pro, you must check and confirm that you have added Alibaba Cloud to the registration information as a service provider based on actual scenarios.

|Service|Scenario|Requirement|
|:------|:-------|:----------|
|OSS|[Bind a custom domain](../../../../../intl.en-US/Developer Guide/Buckets/Bind a custom domain.md#)If you associate your domain name to an OSS endpoint, you must register an ICP filing for your domain name.|Register an ICP filing for your website. You do not need to add Alibaba Cloud to the registration information as a service provider.|
|CDN|Websites that are hosted on servers or instances located in Mainland China and use Alibaba Cloud CDN must register an ICP filing.| -   If the origin site is hosted on Alibaba Cloud instances located in Mainland China, you must register an ICP filing through the Alibaba Cloud ICP Filing system.
-   If the origin site is hosted on instances provided by other service providers, you must add Alibaba Cloud to the registration information as a service provider.

 |
|WAF|Websites that are hosted on instance or servers located in Mainland China and use Alibaba Cloud WAF for protection.|
|Anti-DDoS Pro|Websites that are hosted on servers located in Mainland China and use Anti-DDoS Pro for protection.| -   If you have switched on China Telecom and China Unicom lines when you configure Anti-DDoS Pro, you do not need to add Alibaba Cloud to the registration information.
-   If you have enabled BGP multi-path when you configure Anti-DDoS Pro, you must add Alibaba Cloud to the registration information as a service provider.

 |

## Changes of service provider information {#section_5rg_hzp_tlm .section}

If the service provider or instance IP address changes, you must check and confirm the following information:

-   You have registered an ICP filing for your website through other service providers before, and now you need to host the website on Alibaba Cloud instances or resolve the subdomains to Alibaba Cloud instances. In this circumstance, you must add Alibaba Cloud to the registration information due to the change of service providers.
-   If you have already registered an ICP filing for your website and you want to host the website on another Alibaba Cloud instance, you can modify the DNS configuration to resolve the domain to the new instance. In this circumstance, you do not need to register an ICP filing again.

    **Note:** However, if you change service providers, you must add the new service provider to the registration information. For more information about the procedure to add the new service provider, consult the new service provider.



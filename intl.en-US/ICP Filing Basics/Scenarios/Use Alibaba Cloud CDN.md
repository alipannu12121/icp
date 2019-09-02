# Use Alibaba Cloud CDN {#concept_1181096 .concept}

If your website is hosted in an Alibaba Cloud instance located in Mainland China and uses Alibaba Cloud Content Delivery Network \(CDN\) to accelerate content delivery, you need to configure an accelerating domain name. Whether the accelerating domain name requires an ICP filing depends on the acceleration region. This topic describes the ICP filing requirements for using Alibaba Cloud CDN.

**Note:** For more information about Alibaba Cloud CDN, visit the [Alibaba Cloud CDN product page](https://www.aliyun.com/product/cdn).

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/947826/156741177451470_en-US.png)

In this scenario:

-   **Do I need to apply for an ICP filing for the domain name?** 

    |Domain name|Scenario|Is an ICP filing required|
    |-----------|--------|-------------------------|
    |Website domain name|This domain name is used by users to access the website. The domain name is resolved to an instance located in Mainland China.|Yes|
    |CDN accelerating domain name|This domain name is used by CDN to cache resources of the origin site on CDN nodes.|     -   Acceleration in Mainland China or global regions: yes
    -   Acceleration in Hong Kong, Macao, Taiwan, and other regions outside Mainland China: no
 **Note:** Since you have applied for an ICP filing for the website domain name *www.example.com*, you do not need to apply for ICP filings for its sub-domain names. We recommend that you use a sub-domain name as the CDN accelerating domain name, for example, *video.example.com* or *\*.example.com*.

 |

-   **Do I need to add Alibaba Cloud to the ICP filing information as a service provider?** 

    When you use Alibaba Cloud CDN to accelerate content delivery in Mainland China or global regions, the ICP filing information of the accelerating domain name must exist in the Alibaba Cloud ICP Filing system. We recommend that you apply for the ICP filing in the [Alibaba Cloud ICP Filing system](https://beian.aliyun.com/order/selfBaIndex.htm). For more information, see [Quick Start](../../../../reseller.en-US/ICP Quick Start/Quick Start.md#).



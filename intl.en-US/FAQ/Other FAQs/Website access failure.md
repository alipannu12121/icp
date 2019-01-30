# Website access failure {#concept_d12_5rl_zdb .concept}

This document describes the causes of and solutions for website access failure when your domain name points to an ECS instance.

## Symptom {#section_tgn_5kl_jgb .section}

To launch a website, you must purchase a domain name and a host \(space\), obtain an ICP Filing for the website, and configure domain name resolution. The website may be inaccessible if any of these steps are not completed. When visiting the website, you may receive the following prompt: **This website is temporarily unavailable**.

![The website is inaccessible.](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/14211/15488127575248_en-US.jpg)

## Causes and solutions {#section_lsj_fll_jgb .section}

-   **Cause 1**: The ICP Filing for the domain name is incomplete.

    **Solution**: China's Ministry of Industry and Information Technology \(MIIT\) requires that domain names obtain an ICP Filing before they can be accessed. Log on to the [Alibaba Cloud ICP Filing platform](http://beian.aliyun.com/) to apply for an ICP Filing.

    -   If you have not obtained an ICP Filing, see [ICP Filing for the first time](../../../../../reseller.en-US/ICP Filing Procedures/ICP Filing for the first time.md#).
    -   If the filing subject has been successfully filed with another service provider and you have purchased an ECS instance and need to file a new website domain name with Alibaba Cloud, see [Add a website \(Original filing record outside of Alibaba Cloud\)](../../../../../reseller.en-US/ICP Filing Procedures/Add new websites for ICP Filing (for new Alibaba Cloud ICP Filing users).md#).
    -   If the filing subject has been successfully filed with Alibaba Cloud and a new website is hosted on an ECS instance, you need to [apply for an ICP Filing for the website \(Original filing record in Alibaba Cloud\)](../../../../../reseller.en-US/ICP Filing Procedures/Add a new website for ICP Filing (for old users that have filed website domain names with Alibaba Cloud).md#).
    -   If your filing application is not approved by the administration office, modify your application based on the provided cause and resubmit it. For more information, see [Common causes of ICP Filing rejection](reseller.en-US/FAQ/Reasons for ICP Filing failure.md#).
-   **Cause 2**: The website content is inconsistent with the filing information or the filing information is inaccurate.

    **Solution**: Alibaba Cloud reviews the full filing information of successfully filed websites in accordance with the relevant laws and regulations. If you fail to rectify problems with your filing \(such as nonconforming website content or contact information\) within the specified period, your website will be shut down and your filing application will be canceled or revoked. [Modify your filing information](../../../../../reseller.en-US/ICP Filing Procedures/Change ICP Filing information.md#) as soon as possible and resubmit your filing application.

-   **Cause 3**: Your domain name has been successfully filed with another service provider and your website is hosted on an ECS instance, but your filing record has not been transferred to Alibaba Cloud.

    **Solution**: Transfer your filing record to Alibaba Cloud. For more information about how to transfer a filing record, see [Transfer filing records](../../../../../reseller.en-US/ICP Filing Procedures/Transfer ICP Filings.md#).

-   **Cause 4**: Your filing application has been reviewed by the administration office but the relevant information has not been synchronized to Alibaba Cloud.

    **Solution**: After the ICP Filing information submitted through Alibaba Cloud is reviewed by the administration office, you have to wait until the filing information is synchronized to the Alibaba Cloud ICP Filing system. After synchronization is completed, your website can be accessed normally.

-   **Cause 5**: Your website cannot be accessed through its old domain name.

    **Solution**: If you have changed a successfully filed domain name to another domain name and it has been reviewed by the administration office, but your website cannot be accessed through the old domain name, use the new domain name for access.

-   **Cause 6**: Domain name resolution does not point to your ECS instance.

    **Solution**: Configure domain name resolution.


For more information about ICP Filing, see [ICP Filing process FAQs](reseller.en-US/FAQ/FAQ about ICP filing preparations/ICP Filing process FAQs.md#).


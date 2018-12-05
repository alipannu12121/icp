# Website access FAQs {#concept_d12_5rl_zdb .concept}

The following are FAQs related to the effect of ICP Filing on your website.

-   [How do I obtain an ICP Filing for a website accessed by IP address?](#section_bym_mzr_zdb)

-   [My website domain name directs to a server in Hong Kong region, do I need an ICP Filing?](#section_cym_mzr_zdb)

-   [How do I obtain an ICP Filing for a forum?](#section_dym_mzr_zdb)

-   [What are the differences between the ICP Filing procedures for HTTP protocol and HTTPS protocol websites?](#section_eym_mzr_zdb)

-   [Can my website be accessed normally during the ICP Filing process?](#section_fym_mzr_zdb)

-   [After the ICP Filing is successful, will my website be inaccessible if I modify the ICP Filing information?](#section_gym_mzr_zdb)

-   [On the day when I am notified that my ICP Filing is successful, why is my website still inaccessible?](#section_hym_mzr_zdb)

-   [Why is my website inaccessible?](#section_iym_mzr_zdb)


## How do I obtain an ICP Filing for a website accessed by IP address? {#section_bym_mzr_zdb .section}

The Alibaba Cloud ICP Filing system does not support IP address ICP Filing.  If your website is only accessible only by IP address, go to the ICP Filing system of the local communications administration to apply for an ICP Filing. See **IP Address Filing Procedures** of **ICP Filing Process** in [MIIT ICP Filing Management system](http://www.miitbeian.gov.cn) \(www.miitbeian.gov.cn\) \(only available in Chinese\).

## My website domain name directs to a server in Hong Kong region, do I need an ICP Filing? {#section_cym_mzr_zdb .section}

If your website domain name directs to a server in Hong Kong region, you do not need an ICP Filing. Currently, the Ministry of Industry and Information Technology \(MIIT\) only requires ICP Filing for accessible websites that direct to servers in mainland China. ICP Filing is not required for servers outside mainland China.

## How do I obtain an ICP Filing for a forum? {#section_dym_mzr_zdb .section}

Currently, individuals are not permitted to operate forums. An enterprise must apply for a BBS preapproval document from the local communications administration, and then apply for a forum ICP Filing. After obtaining an ICP Filing, the enterprise can open a forum. Some provinces/municipalities no longer support forum applications. We recommend that you consult the local provincial/municipal communications administration for  more information.

## What are the differences between the ICP Filing procedures for HTTP protocol and HTTPS protocol websites? {#section_eym_mzr_zdb .section}

The ICP Filing procedures are the same for HTTP and HTTPS websites. Before completing the ICP Filing procedure, you are not allowed to make your website accessible.

## Can my website be accessed normally during the ICP Filing process? {#section_fym_mzr_zdb .section}

During the [ICP Filing for the first time](../../../../intl.en-US/ICP Filing Procedures/ICP Filing for the first time.md#) or [Add new website for ICP Filing](../../../../intl.en-US/ICP Filing Procedures/Add new websites for ICP Filing (for new Alibaba Cloud ICP Filing users).md#) process, your website cannot be accessed. This is because the Ministry of Industry and Information Technology \(MIIT\) prohibits online access to domain names without ICP filings.

During the [Change ICP Filing information](../../../../intl.en-US/ICP Filing Procedures/Change ICP Filing information.md#) process, access to websites with ICP Filings is not affected. During the [Transfer ICP Filing](../../../../intl.en-US/ICP Filing Procedures/Transfer ICP Filings.md#) process, if the MIIT ICP Filing information for your domain name is not cancelled, access to your website is not affected. After your ICP Filing transfer application is reviewed by the communications administration, the domain name can be directed to an Alibaba Cloud server to provide access to your website. If your ICP Filing is rejected by the communications administration, make necessary modifications based on the reasons for rejection and resubmit the application.

## After the ICP Filing is successful, will my website be inaccessible if I modify the ICP Filing information? {#section_gym_mzr_zdb .section}

[Modifying ICP Filing information](../../../../intl.en-US/ICP Filing Procedures/Change ICP Filing information.md#) does not affect normal access to a website with an ICP Filing. However, if you change the domain name to another domain name, after the competent authority approves the change, your website cannot be accessed through the old domain name.

## On the day when I am notified that my ICP Filing is successful, why is my website still inaccessible? {#section_hym_mzr_zdb .section}

It may take some time for the system to sync the approved information. During the data sync period, you can complete domain name resolution to direct the domain name to your Alibaba Cloud server. For information about domain name resolution settings, see DNS documentations.

## Why is my website inaccessible? {#section_iym_mzr_zdb .section}

After you direct your domain name to an Alibaba Cloud server, the website may not be accessible \(as shown in the following figure\). \(Alibaba Cloud ICP Filing system and MIIT website are only available in Chinese.\)

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/14211/15439722395248_en-US.jpg)

Possible reasons are as follows:

-   You have not obtained an ICP Filing for the domain name. The MIIT requires that domain names must have ICP Filings before they can be accessed. If you have purchased an Alibaba Cloud ECS instance, go to the [Alibaba Cloud ICP Filing system](http://beian.aliyun.com/)  and submit an application. For more information about the initial ICP Filing process, see [Graphic guide for ICP Filing process](../../../../intl.en-US/ICP Filing Procedures/ICP Filing for the first time.md#).
-   Your domain name has obtained an ICP Filing from another service provider, but you have not transferred the ICP Filing to Alibaba Cloud. If your domain name has been filed with the MIIT through another service provider and you are currently using an Alibaba Cloud server to host your website, you must transfer the ICP Filing to Alibaba Cloud. For more information, see [Graphic guide for ICP Filing transfer process](../../../../intl.en-US/ICP Filing Procedures/Transfer ICP Filings.md#).
-   Your ICP Filing information has not been synced to the Alibaba Cloud system. If you submitted your ICP Filing information through Alibaba Cloud and it was recently approved by the competent authority, it takes some time for the information to be synced with the Alibaba Cloud ICP Filing system. After the information is synced, your website is accessible.
-   The domain name is not resolved to your Alibaba Cloud server. For more information about domain name resolution settings, see ECS documentation. If you have registered your domain name with the Alibaba Cloud Domain Name Service \(formerly HiChina\), see DNS quick start in the Alibaba Cloud DNS documentation.


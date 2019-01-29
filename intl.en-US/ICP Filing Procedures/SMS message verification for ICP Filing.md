# SMS message verification for ICP Filing {#concept_sjg_4rl_zdb .concept}

China's Ministry of Industry and Information Technology \(MIIT\) has selected several provinces and municipalities for the pilot project of SMS message verification for ICP Filing. After users in those provinces and municipalities apply for ICP Filing on the Alibaba Cloud ICP Filing platform, they need to complete SMS message verification so that their filing applications can be accepted by administration offices.

## Provinces that require SMS message verification {#section_gcv_z33_bfb .section}

Users in the following provinces and municipalities are required to complete SMS message verification after applying for ICP Filing on the Alibaba Cloud ICP Filing platform:

From December 18, 2017, [Tianjin](http://tjcainfo.miitbeian.gov.cn), [Gansu](http://gscainfo.miitbeian.gov.cn), [Tibet](http://xzcainfo.miitbeian.gov.cn), [Ningxia](http://nxcainfo.miitbeian.gov.cn), [Hainan](http://hncainfo.miitbeian.gov.cn), [Xinjiang](http://xjcainfo.miitbeian.gov.cn), and [Qinghai](http://qhcainfo.miitbeian.gov.cn) are listed as pilot provinces.

From September 10, 2018,[Zhejiang](http://zcainfo.miitbeian.gov.cn/state/outPortal/loginPortal.action), [Sichuan](http://sccainfo.miitbeian.gov.cn/state/outPortal/loginPortal.action;jsessionid=5C82A6B6551CDA326FEDDAA810978575), [Fujian](http://fjcainfo.miitbeian.gov.cn/state/outPortal/loginPortal.action;jsessionid=0A8674FFC4DFE224B7C91AB4B9CF319E), [Shaanxi](http://shxcainfo.miitbeian.gov.cn/state/outPortal/loginPortal.action;jsessionid=9A7B9FE6E1A3CF9170FCBEB8176B4792), [Chongqing](http://cqcainfo.miitbeian.gov.cn/state/outPortal/loginPortal.action), [Guangxi](http://gxcainfo.miitbeian.gov.cn/state/outPortal/loginPortal.action;jsessionid=ECDA11D62F9F6CE7E00A5D490C5024BC), and [Yunnan](http://yncainfo.miitbeian.gov.cn/state/outPortal/loginPortal.action;jsessionid=C611EF35AFC68EC742F5BE279A7499B7) are listed as pilot provinces.

From September 24, 2018, [Shandong](http://sdcainfo.miitbeian.gov.cn/state/outPortal/loginPortal.action;jsessionid=948BB1433EF4124DFBE4D7795CDC19B2), [Henan](http://hcainfo.miitbeian.gov.cn/state/outPortal/loginPortal.action;jsessionid=7716829712A915FFA1C694250F9DF08D), [Anhui](http://ahcainfo.miitbeian.gov.cn/state/outPortal/loginPortal.action;jsessionid=779ECDDF80AB9A9733815A8CF7410C33), [Hunan](http://xcainfo.miitbeian.gov.cn/state/outPortal/loginPortal.action;jsessionid=7B02A8EC0E36F1763462DEE012B99924), [Shanxi](http://sxcainfo.miitbeian.gov.cn/state/outPortal/loginPortal.action), [Heilongjiang](http://hlcainfo.miitbeian.gov.cn/state/outPortal/loginPortal.action;jsessionid=4052BA96338577D78A4E01006689A698), [Inner Mongolia](http://nmcainfo.miitbeian.gov.cn/state/outPortal/loginPortal.action;jsessionid=5DEF0A0FB4453BFABFE5F8672BA59CFD), and [Hubei](http://ecainfo.miitbeian.gov.cn/state/outPortal/loginPortal.action;jsessionid=F0AD3752120D049C22B1DF1097D2F683) are listed as pilot provinces.

## Verification code transmission {#section_ytb_rb1_12b .section}

-   The verification code is only sent to the mobile number entered in the Contact method 1 field in the filing information.

-   If this mobile number has been changed in the filing information, the verification code is sent to the new mobile number.

-   The verification code is a six-digit number.

-   After receiving a notification stating that Alibaba Cloud has submitted your filing information to the communications administration office, you will receive the verification SMS message in about five minutes.


## ICP Filing type verification instructions {#section_upl_tb1_12b .section}

|ICP Filing type|Verification logic|Remarks|
|:--------------|:-----------------|:------|
|Initial ICP Filing|The mobile numbers of the subject and website owner are verified.| -   If the subject and the website owner are the same person \(with the same mobile number\), only one message containing the verification code is sent.
-   If the subject and the website owner are different persons \(with different mobile numbers\), a verification code is sent to each mobile number, and both persons must complete verification.

 |
|ICP Filing for a new website|The mobile number of the website owner is verified.|None|
|ICP Filing transfer|The mobile number of the website owner is verified.| -   If your mobile number is changed, you must update the new number with your original service provider before performing the ICP Filing transfer.
-   If your website is an "empty-shell" website \(with no access service provider\), you cannot update your new mobile number at the original service provider. In this case, you have to cancel the ICP Filing, and submit a new ICP Filing application.

 |
|ICP Filing information change|The mobile number of the subject or website owner is verified.| -   If the subject information is changed, the mobile number of the subject is verified.
-   If the website information is changed, the mobile number of the website owner is verified.

 |
|Cancel a subject|No verification.|None|
|Cancel a website ICP Filing|No verification.|None|
|Cancel an ICP Filing transfer|No verification.|None|

## Verification code validity period {#section_yyd_mzx_zdb .section}

You need to visit the provincial administration website to perform verification within 24 hours. After you complete SMS message verification for your mobile phone, your filing information is transferred to the administration office for review.

If you fail to complete the verification within 24 hours or the verification fails, your filing information is automatically returned. There are two scenarios in this case:

-   Scenario 1: If your filing information has not been modified and it meets the current requirements, click **Submit ICP Filing** on the ICP Filing platform to directly enter the SMS message verification process.

-   Scenario 2: If your filing information or materials do not meet the current requirements, you must modify it, re-submit the filing application, and enter the SMS message verification process again after review by Alibaba Cloud.


## Verification code transmission number {#section_zyd_mzx_zdb .section}

The codes sent to users of China Telecom, China Unicom, and China Mobile are sent by a fixed number. There is no fixed number for transmission of verification codes to users of virtual providers.

|Provider|Transfer number|
|:-------|:--------------|
|China Telecom|106598051001|
|China Unicom|10655113|
|Chine Mobile|106575000130|
|Virtual providers|No fixed number|

## SMS message verification process {#section_gzd_mzx_zdb .section}

After the SMS message containing the verification code is sent from the MIIT to the mobile number to be verified, log on to the website of the provincial or municipal authority \(only available in Chinese\) promptly and complete the SMS message verification.

1.  Visit the [provincial or municipal administration website](#) for your ICP Filing, and click**ICP Filing SMS Message Verification** in the lower-right corner of the home page.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/14204/15487516499829_en-US.png)

2.  Enter your verification code, mobile number, and the[last six digits of your ID card number](../../../../../intl.en-US/FAQ/SMS verification FAQs.md#section_z2c_1sp_dgb). Complete the verification and then click **Submit**. When you pass the verification, the system displays a prompt stating that the verification is completed. If another mobile number in your ICP Filing order must be verified, repeat this process.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/14204/15487516499830_en-US.png)

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/14204/15487516499832_en-US.png)

    **Note:** 

    -   If the information that you entered is incorrect, or any of the entries \(the verification code, mobile number, and [last six digits of your ID card number](../../../../../intl.en-US/FAQ/SMS verification FAQs.md#section_z2c_1sp_dgb)\) does not match, you cannot retrieve the corresponding order. Then, the system will display a prompt that it cannot find the record. In this case, check the information and try again.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/14204/15487516495573_en-US.png)

    -   If you enter the incorrect ID number for five times consecutively, the system displays a prompt that the verification fails. In this case, your ICP Filing application is rejected by the MIIT system.

        ![](http://docs-aliyun.cn-hangzhou.oss.aliyun-inc.com/assets/pic/63826/cn_zh/1513307443745/%E9%AA%8C%E8%AF%81%E6%9C%AA%E9%80%9A%E8%BF%87.png)


## SMS message resending process {#section_qzs_q1p_dgb .section}

If you do not receive a verification SMS message from the MIIT, you can request that the SMS message be resent.

1.  Log on to the [provincial or municipal website](https://help.aliyun.com/document_detail/63826.html?spm=a2c4g.11186623.6.567.4b404ff5xqpBib#section-gcv-z33-bfb) for your ICP Filing.
2.  Click **Filing SMS Message Verification**.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/14204/154875164934361_en-US.png)

3.  Click **Resend SMS Message**.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/14204/154875164934362_en-US.png)

4.  Fill in the mobile number and the [last six digits of your ID card number](../../../../../intl.en-US/FAQ/SMS verification FAQs.md#section_z2c_1sp_dgb), and complete image splice verification.
5.  Click **Submit**.
6.  Check your mobile phone to get the verification code, and then complete the verification on the website.

For more information about SMS message verification, see [SMS message verification FAQs](../../../../../intl.en-US/FAQ/SMS verification FAQs.md#).


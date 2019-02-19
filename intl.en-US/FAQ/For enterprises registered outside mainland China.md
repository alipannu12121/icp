# For enterprises registered outside mainland China {#concept_jmm_trl_zdb .concept}

If your enterprise is not registered with the mainland China government, and you use an ECS instance in mainland China to host your website, you must apply for an ICP Filing. The following are common issues on ICP Filing.

## Can I apply for an ICP Filing and ICP Commercial License if I have a physical office in mainland China? {#section_uw1_zxr_zdb .section}

If you have a physical office \(“ban shi chu” in Chinese\) in China, you can apply for ICP Filing in some provinces or municipalities, but you cannot apply for an ICP Commercial License. Documents issued outside mainland China are not accepted for ICP Filing.  If you have a registered branch company in mainland China, you can use its registration documents for ICP Filing.  If you do not have a registered company, you must apply for a Registration Certificate of Foreign Enterprises Permanent Office in China from the relevant authority and use this as a business license to submit an ICP Filing application.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/14210/15505421765239_en-US.png)

## What if I do not have an ICP Filing? {#section_ww1_zxr_zdb .section}

You cannot open your website for visit if you have no ICP Filing.

If you cannot finished ICP Filing for some reasons \(such as, you cannot provide the required documents or domain name\), we recommend you use ECS instances in Hongkong.

## I plan to use the Server Load Balancer. How do I apply for an ICP Filing? {#section_xw1_zxr_zdb .section}

If you plan to use the Server Load Balancer together with ECS in mainland China, you can complete the ICP Filing using one of the ECS instances.  Once your ICP Filing has been approved, change your DNS record to point to the IP of your Server Load Balancer instance.

If you are an ICP Commercial License holder, you must update your ICP Commercial License information when changing the IP address to your Server Load Balancer instance.

## Do I have to apply for an ICP Filing to use Alibaba Cloud CDN? {#section_yw1_zxr_zdb .section}

If you only plan to use Alibaba Cloud international CDN \(mainland China is not covered\), you are not required to apply for an ICP Filing.

If you plan to use CDN in mainland China, you must apply for an ICP Filing. In this case, you need a temporary ECS instance \(with at least three-month subscription\) in mainland China to complete the ICP Filing process, whether your website is hosted in mainland China or not.

## Do I need an ICP Filing if my website is hosted outside mainland China? {#section_zw1_zxr_zdb .section}

You do not need an ICP Filing if your website is hosted outside mainland China. However, you must complete the ICP Filing process if you plan to use Alibaba Cloud CDN to accelerate content for users in mainland China.

## My website is hosted in mainland China but is accessible only through IP addresses. Do I need an ICP Filing? {#section_ax1_zxr_zdb .section}

Yes. If your website can be accessed only by IP address, you cannot apply for an ICP Filing through the Alibaba Cloud ICP Filing system.  Alibaba Cloud ICP Filing system only support domain name filing. In this case, you must submit a website ICP Filing application to the province where your commercial entity locates.

## Which province should I apply for an ICP Filing in? {#section_bx1_zxr_zdb .section}

You must apply for an ICP Filing in the same province where your Chinese business license was issued. For example, if your business is registered in Liaoning province, you must apply for an ICP Filing in Liaoning province.


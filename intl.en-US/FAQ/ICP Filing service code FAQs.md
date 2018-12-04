# ICP Filing service code FAQs {#concept_nkx_1jv_42b .concept}

ICP Filing service code is the verification code that is associated with the Alibaba Cloud services and that is used to fill in the registration information in the Alibaba Cloud ICP Filing system. This document provides the answers to the FAQ about ICP Filing service code.

See [Application for ICP Filing service code](../../../../intl.en-US/ICP Filing Procedures/Apply for ICP Filing service numbers.md) for information on how to apply for service identification numbers for ICP registration and the restrictions.

## I did not purchase any Alibaba Cloud server. How do I obtain the ICP Filing service code? {#section_ok3_pmz_zdb .section}

You need to first purchase the Alibaba Cloud server that supports ICP registration to apply for the service identification number.

## Why does it show that the ECS instance does not own any IP address that supports ICP registration? {#section_nk3_pmz_zdb .section}

Currently, the Alibaba Cloud ECS that supports ICP registration is an instance that is deployed within Mainland China, that has a yearly or monthly subscription, and has a public network bandwidth assigned. If you do not own a public IP address, purchase the bandwidth first. See Section "Public network bandwidth” in [Configuration upgrade and downgrade](../../../../intl.en-US/User Guide/Instances/Change configurations/Overview of configuration changes.md#) for details.

## Why do I not see the "apply" button on the application page for service identification numbers for ICP registration? {#section_hk3_pmz_zdb .section}

If the **Apply** button does not appear in the action bar for your product instance, the reasons may be as follows:

-   The account you are using is not the one that you used when you purchased the server. Use the account that you used to purchase the server.
-   You chose Pay-As-You-Go as the billing method for your ESC instance. Pay-As-You-Go instances do not support registration. Change your billing method [From Pay-As-You-Go to Subscription](../../../../intl.en-US/Pricing/Switch from Pay-As-You-Go to subscription.md#), and purchase a subscription of more than three months.
-   You chose Subscription as the billing method for your ESC instance and the remaining time before it expires meets the requirements for registration. In this case, check if the instance has a public network bandwidth assigned. If not, see Section “Public IP address assignment” in [Configuration upgrade and downgrade](../../../../intl.en-US/User Guide/Instances/Change configurations/Overview of configuration changes.md#).
-   You chose Subscription as the billing method for your ESC instance, but the remaining time before it expires does not meet the requirements for registration. In this case, renew the subscription.
-   Your ECS instance has expired. An expired instance cannot apply for the ICP Filing service code.
-   The maximum of the service identification numbers for ICP registration that your instance can apply for has been reached.
-   You did not purchase Alibaba Cloud servers that are deployed within Mainland China. Domain names require registration only when they are pointed to the IP addresses of the instances that are deployed within Mainland, China and that enable the Internet access.

    **Note:** ICP registration is not required for websites hosted in instances that are deployed within Hong Kong, China.



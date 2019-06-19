---


copyright:
  years: 2018, 2019
lastupdated: "2019-06-19"


---

{:new_window: target="_blank"} 
{:shortdesc: .shortdesc} 
{:codeblock: .codeblock} 
{:pre: .pre} 
{:screen: .screen} 
{:tsSymptoms: .tsSymptoms} 
{:tsCauses: .tsCauses} 
{:tsResolve: .tsResolve} 
{:tip: .tip} 
{:important: .important} 
{:note: .note} 
{:download: .download} 
{:external: target= .external} 

# FAQs for errors
{: #faqs-for-errors } 

Read frequently asked questions regarding errors.
{: shortdesc} 

A collection of frequently asked questions regarding errors.

## Why do I not see all my servers in the Affected Items list?
{: #13812-not-see-all-my-servers-in-the-affected- } 

If you do not see all of your servers in the Affected Items list,
[Create a service support
ticket](/docs/managed-solutions?topic=managed-solutions-create-a-service-support-ticket "Create a service support ticket")
in Managed Applications Portal and support will correct the list.

## Why do I see the error: No Access?
{: #13812-see-the-error-no-access } 

An administrator did not give you permission to see the information. The
most likely cause is that the **Services** you were given was `No
Access`. An administrator must follow the instructions in [Access to
resources](https://dev.console.test.cloud.ibm.com/docs/iam?topic=iam-iammanidaccser#resourceaccess){: external}
to give you the proper permission. If **Services** is the cause, under
**Services**, select `Managed Solutions` or `All Identity and Access
enabled services`.

## Why do I see the error: User is not signed up for IBM Cloud?
{: #13812-see-the-error-user-is-not-signed-up-for } 

You have signed up for an IBMid identity, but that identity is not known
to IBM Cloud. Several paths may have taken you to this situation, but
"how" is not important. The solution is simple: Create an IBM Cloud
account using the same email address that is included in the error
message. IBM Cloud will detect that the identity is already registered
with IBMid and will merely associate that IBMid identity with IBM Cloud.
Follow the instructions in [Create an IBM Cloud
account](/docs/account/account_faq.html#create-account).

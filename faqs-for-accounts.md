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

# FAQs for accounts
{: #faqs-for-accounts } 

Read frequently asked questions regarding accounts.
{: shortdesc} 

A collection of frequently asked questions regarding accounts.

## How do I change my account name?
{: #13810-change-my-account-name } 

Changing the account name for an account is part of account management
services provided by IBM Cloud. Follow the instructions in [Editing the
account
name](/docs/account?topic=account-account_settings#change-acct-name).

## How do I change the account owner?
{: #13810-change-the-account-owner } 

Contact the [IBMid worldwide help
desk](https://www.ibm.com/ibmid/myibm/help/us/helpdesk.html){: external}. You can
also retrieve that page from the IBM Cloud login page.

1.  Open IBM Cloud console.

2.  Click **Forgot password?**.
    
    The Having trouble logging in? page appears.

3.  Click **Contact IBMid Helpdesk**.
    
    The IBMid worldwide help desk page appears.

## How do I enable multifactor authentication for my account?
{: #13810-enable-multifactor-authentication-for-m } 

Enabling mutlifactor authentication for an account is part of identity
and access management services provided by IBM Cloud. Follow the
instructions in [Requiring MFA for users in your
account](/docs/iam?topic=iam-enablemfa#enablemfa).

## How do I proceed if my account is locked?
{: #13810-proceed-if-my-account-is-locked } 

Contact the [IBMid worldwide help
desk](https://www.ibm.com/ibmid/myibm/help/us/helpdesk.html){: external}. You can
also retrieve that page from the IBM Cloud login page.

1.  Open IBM Cloud console.

2.  Click **Forgot password?**.
    
    The Having trouble logging in? page appears.

3.  Click **Contact IBMid Helpdesk**.
    
    The IBMid worldwide help desk page appears.

## How do I switch between multiple accounts?
{: #13810-switch-between-multiple-accounts } 

You can use your account list to select the account to view.

1.  Open IBM Cloud Console.
2.  From the list next to <svg aria-label="pencil with paper"
    alt="pencil with paper" viewBox="0 0 32 32" width="16"
    height="16"><path d="M22 22v6H6V4h10V2H6a2 2 0 0 0-2 2v24a2 2 0 0
    0 2 2h16a2 2 0 0 0 2-2v-6z"/><path d="M29.537 5.76L26.24
    2.463a1.58 1.58 0 0 0-2.236 0L10 16.467V22h5.533L29.537 7.995a1.58
    1.58 0 0 0 0-2.235zM14.704 20H12v-2.704l9.44-9.441 2.705
    2.704zM25.56 9.145l-2.704-2.704 2.267-2.267 2.704
    2.704z"/></svg>, select the account with your managed
    applications.

## Who can invite users to the account?
{: #13810-who-can-invite-users-to-the-account } 

Any user with appropriate permissions may invite users. To elevate
permissions of a user to allow that user to invite other users to the
account, follow the instructions in [Assigning access to account
management
services](/docs/iam?topic=iam-account-services#account-services)
to modify the user. As discussed in the article, you can provide very
granular permission to invite users with a policy that gives the user
access to all account management services in the account by selecting
**All account management services** with the `Administrator` role
assigned.

## Why am I unable to create tickets?
{: #13810-why-am-i-unable-to-create-tickets } 

An administrator did not give you permission to see the information. The
most likely cause is that the **Assign platform access roles** you were
given was only `Viewer`. An administrator must follow the instructions
in [Access to
resources](https://dev.console.test.cloud.ibm.com/docs/iam?topic=iam-iammanidaccser#resourceaccess){: external}
to give you the proper permission. If **Assign platform access roles**
is the cause, under **Assign platform access roles** select `Operator`,
`Editor`, or `Administrator`.

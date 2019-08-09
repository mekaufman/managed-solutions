---


copyright:
  years: 2018, 2019
lastupdated: "2019-08-09"


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

# 2019.08.09 New and changed features
{: #20190809-new-and-changed-features } 

2019.08.09 New and changed features.
{: shortdesc} 

This section describes new and changed functionality for 2019.08.09.

## Case management model for support
{: #13817-case-management-model-for-support } 

Customer Service Management (CSM) is a case management model for
customer support. In Service Support feature, you submit and track as
cases all change requests, service requests, and incidents.

When the transition occurs, you will see two notable differences.
Firstly, only active tickets will be recreated as cases; closed and
inactive tickets will not migrate. This will result in a temporary
increase in cases created on the day of transition as IBM customer
support teams submit those tickets as cases. If you want information
about tickets that closed or became inactive before the transition, you
must contact your Delivery Project Executive to research because those
tickets will not be visible from Managed Applications Portal. Secondly,
references to older incidents will not be linkable from alerts.

  - The text `case` replaces `ticket` in Service Support feature.
  - Batch filter in Service Support feature includes date ranges for
    service requests and incidents.
  - The workflow for requests and incidents change modestly for the case
    model. For example, location and system environment are not
    required.
  - Most functions in Service Support feature are unchanged whether
    cases or tickets are used, although some text may change, such as
    `Contract` instead of `Service`.
  - If a case has multiple configured items in different locations,
    click the information icon to reveal a list of configured items and
    their locations.
  - Sort is not available for Change Request cases - use filters to
    reduce the list.
  - Most functions in Alerts are unchanged whether cases or tickets are
    used, although some text may change.
  - Tiles on the homepage are unchanged whether cases or tickets are
    used, although some text may change.
  - When case awaits additional information or if the case has a
    negative closure code assigned, an information icon appears next to
    the case. Click the icon to reveal additional information regarding
    the case.

## Multiple ServiceNow contracts
{: #13817-multiple-servicenow-contracts } 

Some customers have multiple business units within their organization,
each with a contract with ServiceNow. They want ServiceNow information
to be segregated by contract.

  - A user who has permission to access multiple ServiceNow contracts
    can select a contract and view cases or create cases for that
    contract. Links to caswes in emails understand multiple ServiceNow
    contracts.
  - A user who has permission to access multiple ServiceNow contracts
    sees on the dialog the contract when editing a case. If a user has
    no permission, related actions and dialogs are unavailable.
  - A user who has permission to access multiple ServiceNow contracts
    can select a contract and schedule service in that contract.
  - A user who has permission to access multiple ServiceNow contracts
    sees aggregated case counts in the Recent Cases tile on Overview
    feature.
  - A user who has permission to access multiple ServiceNow contracts
    will not be removed or deactivated from a contract until the user no
    longer has access to the relevant contracts.
  - Only users with an administrative type role can associate multiple
    ServiceNow contracts to a company. If contracts are not linked, a
    dialog is offered to assist the user to associate ServiceNow
    contracts. A setting option in the navigation menu permits assigning
    roles.
  - You can assign users permission as approvers of change requests for
    one or more ServiceNow contracts.

## Notifications
{: #13817-notifications } 

IBM Services for Managed Applications can communicate to users changes
that may affect their services through notifications.

  - Notifications appear as a single notification on every page you
    visit until you acknowledge the notifications. If additional
    notifications are available, each appears individually until
    acknowledged.
  - You can view all notifications by clicking the View Notifications
    link on any page.
  - You can retrieve and acknowledge notifications through the public
    application programming interface (API).

## Managed Applications Portal enhancements
{: #13817-managed-applications-portal-enhancement } 

  - Services overview shows you the Active Cases, Recent Cases,
    Scheduled Change Requests, and Alerts tiles but only if your account
    has the support entitlement.
  - You can download the change request details page with the contents
    of its Details, Implementation, Communication Log, and Watchlist
    Tabs
  - Reports downloaded as a PDF file have page breaks and page numbers.
  - You can batch filter change requests in Service Support feature.
  - You can attach binary files to a support case.

## API call realignment
{: #13817-api-call-realignment } 

Some API calls are inconsistent in form from the rest of the API calls.
These calls are realigned with the form of the rest of the calls.

  - Realigned Get Incident List, Get Incident By ID, Create Incident,
    Update Incident, Add Journal API calls in the support service.

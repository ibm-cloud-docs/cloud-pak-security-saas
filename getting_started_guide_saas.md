---


copyright:
  years: 2021
lastupdated: "2021-06-22"

keywords: Cloud Pak for Security as a Service, SaaS

subcollection: cloud-pak-security-saas


---

{:shortdesc: .shortdesc}
{:screen: .screen} 
{:codeblock: .codeblock} 
{:pre: .pre} 
{:tip: .tip} 
{:note: .note} 
{:important: .important}
{:external: target="_blank" .external}

# Getting started with IBM Cloud Pak for Security as a Service
{: #getting-started-saas}

IBM Cloud Pak® for Security as a Service provides an open security platform that connects to your existing data sources to generate deeper insights and enable you to act faster with automation.
{:shortdesc}

IBM Cloud Pak® for Security as a Service documentation is included in the same documentation collection as IBM Cloud Pak® for Security on premises, and much of the content is applicable and relevant to both products.

Because the IBM Cloud Pak® for Security as a Service deployment and accounts are managed by IBM Security, sections related to planning, installation, and deployment are not relevant to IBM Cloud Pak® for Security as a Service customers.
{: important}

By using open standards and IBM innovations, Cloud Pak® for Security as a Service can securely access IBM and third-party tools to search for threat indicators across any cloud or on-premises location. Connect your workflows with a unified interface so you can make better risk-based decisions and respond faster to security incidents. Use Cloud Pak® for Security as Service to orchestrate and automate your security response so that you can better prioritize your team's time.

## What's inside this Cloud Pak
{: #included}

IBM Cloud Pak® for Security as a Service includes the following offerings.
- IBM® Security Threat Intelligence Insights delivers unique, actionable, and timely threat intelligence. The application provides most of the functions of IBM X-Force® Exchange.
- IBM® Security Data Explorer enables customers to do federated search and investigation across their hybrid, multi-cloud environment in a single interface and workflow.
- IBM® Security Case Management for IBM Cloud Pak® for Security provides organizations with the ability to track, manage, and resolve cybersecurity incidents.
- IBM® Security Orchestration & Automation provides most of the IBM Resilient Security Orchestration, Automation, and Response Platform feature set. If you have an Orchestration & Automation license, you can choose between the stand-alone version on a virtual appliance, or the application on Cloud Pak for Security.
- IBM® QRadar® Proxy provides communication between IBM Cloud Pak® for Security and IBM QRadar or QRadar on Cloud. This communication uses APIs to pull powerful IBM QRadar data into the QRadar Security Information and Event Management (SIEM) dashboards.

For more information, see [IBM Documentation](https://www.ibm.com/support/knowledgecenter/SSTDPP_1.7.0/docs/scp-core/overview.html){: external}.

## Purchasing a license
{: #license-entitlement}

Before you can use IBM Cloud Pak® for Security as a Service, you must purchase a license. Purchase a license, also known as an entitlement, at [IBM Passport Advantage](https://www.ibm.com/software/passportadvantage/index.html){: external}.

For more information, see [Licensing and entitlement](https://ibmdocs-test.mybluemix.net/docs/en/cloud-paks/cp-security/1.7.0?topic=planning-licensing){: external}.

## Getting started in SaaS
When your IBM Cloud Pak® for SaaS deployment is available, you receive a Welcome email from IBM Security which contains important information, including a list of initially provisioned users and links to your IBM Verify and IBM Cloud Pak for SaaS deployment.
Provisioned users can then create additional users as needed. These users can log on to your IBM Cloud Pak for SaaS deployment and your instance of IBM Verify, which is used for identify management.

Only users who have an IBMid associated with their email address are included in the list of initially provisioned users.
{: important}

To log on to your IBM Cloud Pak for Security as a Service deployment, use the URL included in the welcome email, select **Enterprise SAML** as the authentication method, and then click **Sign in with IBMid**.

## Creating users in IBM Cloud Pak for SaaS
Users who are listed as provisioned in the Welcome email can create additional users. 

## Before you begin
{: #prereqs}

*  You must have the Welcome email with details of your provisioned deployment for IBM Cloud Pak for Security as a Service.
*  To create new users, you must be listed in the Welcome email as a provisioned user.
*  The new users that you want to create must have an email address and an IBMid associated with their email address. Users can create an IBMid from https://ibm.com/account.

### Create new users

1. Log on to your IBM Verify instance by using the URL provided in the Welcome email and select **Sign in with IBMid**.
2. Enter your IBMid login credentials. 
3. Add the new user in IBM Verify, as follows:

    1. Click your profile in the top right of the page and select **Switch to admin**.
    1. From the menu, select **Users & groups**. The Users tab is selected by default.
    1. Click **Add user**.
    1. From the Identity source drop-down menu, select **IBMid**.
    1. Enter a given name and scroll down and enter a surname, user name, and email address. The other fields are optional.
    1. Click **Save**.
4. Log on to IBM Cloud Pak® for Security as a Service by using the deployment URL provided in your Welcome email.
5. From the IBM Cloud Pak® for Security as a Service Homepage, click **Settings > Manage users**. 

    1. From the Manage users page, click **Add user**.
    1. In the Name or Email address field, enter or select the user's email address.
    1. Click **Add user**.

        **Tip:** You can create multiple users at the same time.

    1. Select the newly create user and assign permissions. For more information about permissions, see Adding or removing users.

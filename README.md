# Partner-driven provisioning integrations

The Azure Active Directory Provisioning service allows you to provision users and groups into both [SaaS](https://docs.microsoft.com/azure/active-directory/app-provisioning/user-provisioning) and [on-premises](https://docs.microsoft.com/azure/active-directory/app-provisioning/on-premises-scim-provisioning) applications. There are four integration paths:

**Option 1 - Azure AD Application Gallery:**
Popular 3rd party applications, such as Dropbox, Snowflake, and Workplace by Facebook, are made available for customers through the Azure AD application gallery. New applications can easily be onboaded to the gallery using the [application network portal](https://docs.microsoft.com/azure/active-directory/azuread-dev/howto-app-gallery-listing). 

**Option 2 - Implement a SCIM compliant API for your application:**
If your line-of-business application supports the [SCIM](https://aka.ms/scimoverview) standard, it can easily be integrated with the [Azure AD SCIM client](https://docs.microsoft.com/azure/active-directory/app-provisioning/use-scim-to-provision-users-and-groups).

**Option 3 - Leverage the Microsoft Graph:**
Many new applications use [Microsoft Graph](https://docs.microsoft.com/graph/overview) to retrieve [users](https://docs.microsoft.com/graph/api/resources/user?view=graph-rest-1.0), groups and other resources from Azure Active Directory. You can learn more about what scenarios to use [SCIM and Graph](https://docs.microsoft.com/azure/active-directory/app-provisioning/scim-graph-scenarios) in. 

**Option 4 - Leverage a connector developed by a partner:**
In cases where an application does not support SCIM, partners have built gateways between the Azure AD SCIM client and target applications.  **This document serves as a place for partners to attest to integrations that are compatible with Azure Active Directory, and for customers to discover these partner-driven integrations.** Note that these gateways are built, maintained, and owned by the third-party vendor. 

# How-to add partner-driven integrations to this document

1. Review the Azure AD SCIM [documentation](https://docs.microsoft.com/azure/active-directory/app-provisioning/use-scim-to-provision-users-and-groups) to understand the Azure AD SCIM implementation.
1. Test compatibility between the Azure AD SCIM client and your SCIM gateway.
1. Click edit at the top of this page to create a pull request add your integration with this list.
1. An admin of the repository will merge your changes so that others can view them.

## Guidelines
* Add any new partners in alphabetical order.
* Limit your entries to 500 words.
* Ensure that you provide contact information for customers to learn more.

# Available partner-driven integrations
## Aquera
### Description
The Aquera Identity Integration Platform as a Service closes the connectivity gaps for real-time identity governance and lifecycle management workflows. The platform offers SCIM gateway services for account provisioning and aggregation, orchestration services for user and password synchronization, and workflow services for the governance of disconnected applications.
### Contact information
* Company website: https://www.aquera.com/applications.html
* Contact information: https://www.aquera.com/contact-us.html

### Applications supported
3 apps listed below for reference. Catalog contains [200+](https://www.aquera.com/applications.html).
* ADP
* Balsamiq
* Calendly

## IDM Works
### Description
We Are Experts In Identity & Access Management and Data Center Management.

### Contact information
* Company website: [IdentityForge solutions for Microsoft FIM](http://identityforge.com/index.php/solutions/iamsolutions/solutions-for-fim-2010)
* Contact information: 

### Applications supported
* SAP ECC Advanced Adapter
* IBM Tivoli
* FHIR Healthcare Advanced Adapter

## UnifySolutions
### Description

### Contact information

### Applications supported
* Company website: https://unifysolutions.net/solutions/azure-ad-application-provisioning/
* Contact information: 


# Disclaimer
{Input Legal text once available}

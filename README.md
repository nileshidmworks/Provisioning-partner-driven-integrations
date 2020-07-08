# Azure Active Directory Partner Driven Integrations

Azure Active Directory can provision users into any application that a customer may have. There are three primary integration paths:

**SCIM compliant line-of-business applications:**
For applications built for use within your organization, Azure Active Directory provides a [SCIM](https://aka.ms/scimoverview) client that provisions users and groups.

**3rd Party integrations / gallery applications:**
 For 3rd party applications commonly used by our customers, the Azure AD provides easy to onboard templates to integrate with the applications. Examples include Dropbox, Snowflake, and Workplace by Facebook. SCIM compliant applications can easily be onboared to the application gallery and deployed by customers using the steps defined [here](https://docs.microsoft.com/azure/active-directory/azuread-dev/howto-app-gallery-listing). 

**Partner-driven integrations:**
In cases where an application does not support SCIM, several partners have built gateways between the Azure AD SCIM client and target applications such as SAP, SQL, and LDAP. **This document serves as a place for partners to attest to integrations that are compatible with Azure Active Directory, and for customers to discover these integration options.**

# Disclaimer
{Input Legal text once available}
  
# How-to add integrations to this list

1. Review our [documentation](https://docs.microsoft.com/azure/active-directory/app-provisioning/use-scim-to-provision-users-and-groups) to understand the Azure AD SCIM implementation.
2. Test SCIM compatibility using [on-demand provisioning](https://docs.microsoft.com/azure/active-directory/app-provisioning/provision-on-demand) and the [postman test suite](https://github.com/AzureAD/SCIMReferenceCode/wiki/Test-Your-SCIM-Endpoint).
3. Test the integration with at least 3 cusotmers to ensure that it is working as expected.
4. Click edit at the top of this page to create a pull request add your integration with this list.
5. An admin of the repository will merge your changes so that others can view them.

# Partners
## Aquera
### Description
The Aquera Identity Integration Platform as a Service closes the connectivity gaps for real-time identity governance and lifecycle management workflows. The platform offers SCIM gateway services for account provisioning and aggregation, orchestration services for user and password synchronization, and workflow services for the governance of disconnected applications.
### Contact information
* Company website: https://www.aquera.com/applications.html
* Company contact: https://www.aquera.com/contact-us.html
* Application catalog: 

### Applications supported
3 apps listed below for reference. Catalog contains [200+](https://www.aquera.com/applications.html).
* ADP
* Balsamiq
* Calendly

## IDM Works

## Description
We Are Experts In Identity & Access Management and Data Center Management.

### Contact information
* Company website: [IdentityForge solutions for Microsoft FIM](http://identityforge.com/index.php/solutions/iamsolutions/solutions-for-fim-2010)
* Application catalog: 

### Applications supported
10 apps listed below for reference. Catalog contains 200+ 
* SAP ECC Advanced Adapter
* IBM Tivoli
* FHIR Healthcare Advanced Adapter


## OCG
### Description
OCG ...

### Contact information
* Company website: http: //oxfordcomputergroup.com/ Jump
* Information: info@oxfordcomputergroup.com
* Application catalog: 

### Applications supported

* Firebird 
* Informix
* Ingres 


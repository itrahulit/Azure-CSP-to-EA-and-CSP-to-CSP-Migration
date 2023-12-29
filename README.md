# Azure CSP to EA and CSP to CSP Migration
This document serves as a comprehensive guide for the migration process from Azure Cloud Solution Provider (CSP) to Enterprise Agreement (EA) and from CSP to CSP.

# CSP To CSP
When moving your Azure CSP (Cloud Solution Provider) relationship from one partner to another, you typically don't need to migrate your Azure services to a new subscription. The change primarily involves transferring the management and billing responsibilities from one CSP partner to another while retaining your existing Azure subscription and resources.
**Subscription Retention:**
Your Azure subscription remains the same; there's no need to create a new subscription.
The transition involves updating the CSP partner associated with your existing subscription.

**Partner and Contract Change:**
The primary changes occur at the partner and contractual levels.
You switch from one CSP partner to another, and the contractual relationship with the new partner is established.

**Billing and Management:**
The new CSP partner will take over billing and management responsibilities for your existing Azure subscription.
The Azure resources and configurations within your subscription remain unchanged.

**Communication and Coordination:**
Effective communication between the current and new CSP partners is crucial to ensure a smooth transition.
The new CSP partner needs access and relevant information to manage your existing Azure services seamlessly.

**Documentation and Access:**
Ensure that all necessary documentation, access credentials, and relevant information about your Azure environment are provided to the new CSP partner.

Reference Link: https://learn.microsoft.com/en-us/partner-center/switch-azure-subscriptions-to-a-different-partner 

# CSP to EA
If you are considering transitioning from the Azure Cloud Solution Provider (CSP) program to the Enterprise Agreement (EA) program, it's a more involved process compared to switching CSP partners. Here are the general steps you may need to take:

**Prepare for Migration:**
Understand the differences between CSP and EA in terms of billing, reporting, and management.
Plan for any necessary changes to your Azure resources and configurations.

**Migration Planning:**
Develop a migration plan that includes transitioning your Azure subscriptions from CSP to EA.
Consider the financial and technical aspects of the migration.

**Migration Strategy:**
Assessment & Discovery.
Prepare a Migration Plan.
RBAC check (To be done right after the destination subscription creation)
Checklist before moving resources through Azure Resource Mover. 

**Migration:**
The subscriber needs to manually move resources between source CSP subscriptions and target EA subscriptions.
Use a service called Azure Resource Mover and mix of manual migration effort here in this migration approach.

**Move resources:**
Some resources can be moved by Azure mover, but some resources can't. Please refer below link
https://learn.microsoft.com/en-gb/azure/azure-resource-manager/management/move-support-resources 
Azure Resource Mover primarily facilitates the movement of Azure resources within the same tenant 



Reference Link: https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/move-support-resources
                https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/move-resource-group-and-subscription#checklist-before-moving-resources                             https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/subscription-transfer
                https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/transfer-subscriptions-subscribers-csp#transfer-csp-subscription-to-other-offers



 





               

               









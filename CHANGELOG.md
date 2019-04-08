# Changelog

## 1.0.155 (4/9/2019)

### Bug Fixes:

 - Enabled DNS fallback to support hybrid DNS

## 1.0.154 (3/21/2019)

### New Features:
- **McAfee ePolicy Orchestrator 5.10.0 Update 3**\
     New image (AMI) available for Agent Handler with Update 3 . This update resolves known issues from McAfee ePO 5.10.0 release. Update 3 is cumulative in nature and includes fixes from Update 1.
     
### Bug Fixes:
- Please refer the Update 3 release notes for complete list of bug fixes:

  https://kc.mcafee.com/resources/sites/MCAFEE/content/live/PRODUCT_DOCUMENTATION/28000/PD28210/en_US/March12_EPO_5_10_Update3_RN.PDF
    

## 1.0.151 (3/1/2019)

### New Features:
- **Additional AWS Regions Support**\
    Now, you can deploy and configure McAfee ePolicy Orchestrator end to end deployment in the following regions:
    * Europe (Paris)  
    * AWS Govcloud (US) East  
   
-	**McAfee Agent 5.6.0 with integrated McAfee® Data Exchange Layer 5.0.1 (DXL)**  
    * McAfee Agent 5.6.0 bundles the McAfee Data Exchange Layer client 5.0.1 as a component. The Data Exchange Layer client is automatically installed on managed systems and connects to a DXL broker in your environment.  
  
-	**Bundled with McAfee ePolicy Orchestrator (ePO) Support Center 5.10.0**  
    Support Center is a lightweight ePO extension that includes the following capabilities:
    * Insight into the health of ePO platform elements. 
    *	Ability to receive and tag SNS notifications from within the console.
    *	Access to ‘How to’ resources and best practices for ePO and Endpoint Security through the Product Information pages.
    *	Search capability across McAfee content repositories.
    *	New Stack Parameter for Product Improvement Program
    *	You can configure through AWS Cloud Formation Template stack parameter to enable or disable McAfee Product Improvement Program which collects data from the client systems where McAfee products are installed and managed by ePO.
 
### Bug Fixes:
-	Retry mechanism to avoid Software Manager connectivity issues
-	Increased time delay to avoid stack failures due to increased RDS provisioning time
-	CI changes to accommodate Support Center artifacts

# Changelog
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

# CMSBlog-1
Repair content after Sitecore Upgrade

Check for dynamic placeholder definition (supported by default in Sitecore 9 but with a different placeholder definition pattern). Use and change as needed the script:
**UpgradeScripts\FixDynamicPlaceholders.aspx**

Check for Rendering parameters that have field names with spaces (will throw error for components used with personalization). Use script:
**UpgradeScripts\FixParametersFieldsWithSpaces.aspx.aspx**

Compare master and web for unpublished content so editors can take care of it before Go Live. Use script: **UpgradeScripts\CompareMasterWebContent.aspx**

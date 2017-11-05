# Access denied when adding new site collection
## Symptoms
Consider the following scenario:
* Start the SharePoint Client Browser
* Connect to a site collection
* Click the OK-button on the "Add Site Collection" dialog
In this scenario, you may receive the error message "Access denied. You do not have permission to perform this action or access this resource.". 
## Cause
This issue can occur when connecting to a site collection from version 1.2 and upwards. Additional site object properties are loaded which require higher permissions. If you don't have these permissions the "Access denied" error is shown.
## Resolution
To resolve this issue, use a previous version [SharePoint 2013 Client Browser v1.1](url_https___spcb.codeplex.com_releases_view_114743). The new release will implement the option for loading all properties or limited set of properties. 
## More information
-
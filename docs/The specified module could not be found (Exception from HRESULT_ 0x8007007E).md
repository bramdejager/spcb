# The specified module could not be found (Exception from HRESULT: 0x8007007E)
## Symptoms
Consider the following scenario:
* Start the SharePoint Client Browser
* Connect to a site collection or tenant
* Click the OK-button on the "Add Site Collection" dialog
In this scenario, you may receive the error message "The specified module could not be found (Exception from HRESULT: 0x8007007E)"
## Cause
This issue can occur when connecting to a SharePoint Online site collection and an assembly is not located on your machine. It's very likely you are missing one of the base assemblies for CSOM. 
* MSOIDCLIL.DLL
* MSOIDRES.DLL
## Resolution
To resolve this issue for SharePoint Server 2013, you need to install SharePoint Server 2013 Client Components SDK [http://www.microsoft.com/en-us/download/details.aspx?id=35585](http://www.microsoft.com/en-us/download/details.aspx?id=35585) to authenticate with SharePoint Server 2013.

To resolve this issue for SharePoint Online, you need to install SharePoint Online Client Components SDK [http://www.microsoft.com/en-us/download/details.aspx?id=42038](http://www.microsoft.com/en-us/download/details.aspx?id=42038) to authenticate with SharePoint Online (Office 365).
## More information
For more information about the SharePoint Server 2013 Client Components SDK check [http://www.microsoft.com/en-us/download/details.aspx?id=35585](http://www.microsoft.com/en-us/download/details.aspx?id=35585) or SharePoint Online Client Components SDK check [http://www.microsoft.com/en-us/download/details.aspx?id=42038](http://www.microsoft.com/en-us/download/details.aspx?id=42038).

This blog post details the root cause and required assemblies, see [https://bramdejager.wordpress.com/2015/06/17/the-sharepoint-csom-assemblies-and-the-the-specified-module-could-not-be-found-error](https://bramdejager.wordpress.com/2015/06/17/the-sharepoint-csom-assemblies-and-the-the-specified-module-could-not-be-found-error)
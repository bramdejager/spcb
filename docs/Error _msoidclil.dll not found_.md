# Error "msoidclil.dll not found"
## Symptoms
Consider the following scenario:
* Start the SharePoint Client Browser
* Connect to a SharePoint Online site collection
* Click the OK-button on the "Add Site Collection" dialog
In this scenario, you may receive the error message "msoidclil.dll". 
## Cause
This issue can occur when connecting to a SharePoint Online site collection and the assembly "msoidclil.dll" is not located on your machine.
## Resolution
To resolve this issue, you need to install SharePoint Server 2013 Client Components SDK [http://www.microsoft.com/en-us/download/details.aspx?id=35585](http://www.microsoft.com/en-us/download/details.aspx?id=35585) to authenticate with SharePoint Online (Office 365).
## More information
For more information about the SharePoint Server 2013 Client Components SDK check [http://www.microsoft.com/en-us/download/details.aspx?id=35585](http://www.microsoft.com/en-us/download/details.aspx?id=35585)
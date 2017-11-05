Remote SharePoint development is getting more important. Especially with SharePoint Apps. To speed up development, find hidden lists/items/documents, discover the structure or specific artifact properties use the **SharePoint Client Browser** which supports **SharePoint 2010**, **SharePoint 2013**, **SharePoint 2016** and **SharePoint Online (Office 365)**. 

Get up and running in seconds, because this WinForm tool +does not+ need installation but simply unzip the download and start the EXE file. Next step, connect to your on-premise SharePoint Server or SharePoint Online (Office 365) site collection.

_Note: Please provide feedback via [discussions](https://spcb.codeplex.com/discussions) and [issues](https://spcb.codeplex.com/workitem/list/basic). I'm looking forward to your opinion, likes, new feature requests or issues you came across._

![](Home_https://www.codeplex.com/Download?ProjectName=spcb&DownloadId=1627099)

**Why use this tool?**
* Get insight in your site collection structure
* Find hidden lists, items or documents
* Discover artifact properties
* Easily start [PowerShell](http://bramdejager.wordpress.com/2013/09/19/sharepoint-client-browser-1-0-released-bye-bye-preview/), via context menu, and run (scripted) queries against your remote site collection
* Support for both SharePoint 2010 and SharePoint 2013
* Connect to on-premise or SharePoint Online (Office 365) site collections
* No installer
* Remote access from your desktop to site collection via Client Side Object Model (CSOM)
	* Can run remote, no need to run on the SharePoint server itself

**Supported features**
Support for SharePoint Online Tenants (Office 365), including the following items
* Add tenant (_File » Add Tenant_)
* Recent tenants are stored locally (_File » Recent Tenants_)
* Treeview containing tenants and related components, like: 
	* Office 365 Tenant 
	* External Users
	* Site Properties
	* Deleted Site Properties
	* Apps in the App Catalog
	* Web Templates available in the Tenant
	* Log Entries (always empty due to missing implementation from Microsoft)

Support for Site Collections, including the following items
* Add site collections (_File » Add Site_)
* Recent site collections are stored locally (_File » Recent Sites_)
* Support for both SharePoint 2010, SharePoint 2013 and SharePoint 2016 based on CSOM
* Support for classic and claims authentication
* Support for anonymous and forms based authentication
* Support for Office 365 / SharePoint Online
* Treeview containing site collection and related components, like: 
	* Subwebs (including App Webs)
	* List and libraries
	* Site Columns
	* Content Types
	* Items and Field Values
	* Views
	* Features (activated)
	* Site Users
	* Site Groups
	* Associated Visitor, Member and Owner groups
	* Taxonomy (Term Store)
	* User Profiles
	* Workflows Templates
	* Workflow Associations
	* Event Receivers
	* Properties
	* List Templates
	* Push Notifications
	* Web Templates
	* Role Assigments
	* Role Definitions
	* Recycle Bin (first and second stage)
	* Root Folder including subfolders and files
	* User Custom Actions
	* Project Policies (Site Closure and Deletion)
* The treeview includes the hidden objects (shown in gray) next to the default objects
* Treenode context menu support for 
	* "Open in browser..."
	* "Open PowerShell with CSOM", [more info](http://bramdejager.wordpress.com/2013/09/19/sharepoint-client-browser-1-0-released-bye-bye-preview/)
	* "Browse Settings..."
	* "Browse MSDN Help"
* "Properties"-tab shows all selected class properties
* "Raw Data"-tab shows the list items based on the columns of a list or library
* "Change Log"-tab shows the Change Log for different types of items
* "MSDN Help"-tab shows the MSDN Help article for the selected node / object class
* "Schema XML"-tab shows the schema XML for List, Content Type, Field and View
* Status bar showing selected node / object class (including a link to MSDN Help article)
* On startup checks if new version is available
For the ONLYOFFICE™ Applications example to work properly you need to do the following:

1. Download and extract the Example.zip into a directory selected for it, for instance, C:\OnlyofficeExample

2. Use the settings.config file to change the received authorization key for the document service. The file can be found in the unpacked root folder (C:\OnlyofficeExample\settings.config, in our example). The authorization key is specified in the files.docservice.key field.

3. Run the IIS Manager (C:\Windows\system32\inetsrv\InetMgr.exe or Start -> All Programs -> Administrative Tools -> Internet Information Services (IIS) Manager for Windows Server 2003)

4. Add the unpacked Example to the list of sites with the physical path to the C:\OnlyofficeExample (or the one you selected) folder.

5. Make sure that the user account under which the IIS NetworkService process is executed has the write access rights for the C:\OnlyofficeExample\App_Data folder (this is significant for the IIS later than 6.0).

6. Make the created ONLYOFFICE™ Applications example available through IP or domain name so that it could be connected from the web by the document service for proper document rendering.






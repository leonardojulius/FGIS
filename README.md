<p align="center">
  <img src="https://user-images.githubusercontent.com/16941074/202843746-c7492c94-5903-46c2-8cad-81c1646c3c9c.png" alt="Sublime's custom image"/>
  <img src="https://user-images.githubusercontent.com/16941074/202843678-69ad0d48-0eaa-4769-96cd-49f470bd887c.png" alt="Sublime's custom image"/>
  <img src="https://user-images.githubusercontent.com/16941074/202843692-6cab6073-d571-4e6e-9364-93f531a6b73a.png" alt="Sublime's custom image"/>
</p>
<h1><p align="center">
Enhancement of Farmland GIS – Lot2
  <br>
    <i>Region 11-Davao Del Sur-IMO</i>
</p></h1>
  

  
  
  ###  Scope:
  
  >1. Software And Hardware requirements
  >2. Installation of required Application
     -PostgreSQL
     -QGIS
     -FGIS database module
     -FGIS mapping module (plugin for QGIS)
  
  
 <h2>System Requirements</h2>
 

   ### Software:
  > 1. Operating system: Windows 10 64-bit
  
   ### Hardware minimum requirements:
   > 1. CPU speed: 1 GHz or faster processor
   > 2. RAM: 2GB for 64-bit
   > 3. Hard disk space: 20 GB
   > 4. Graphics card: DirectX 9 or later with WDDM 1.0 Driver
   
<p align="center">
    <img src="https://user-images.githubusercontent.com/16941074/202845446-b3878f4a-243e-49f7-956e-4313b394ffcb.png" alt="Sublime's custom image"/>
</p>

  ### PosgreSQL Installation:
 >1. To start the installation. Run “postgresql-10.7-1-windows-x64.exe”
      In Setup interface, click “Next” <br>
<a href="https://drive.google.com/drive/folders/1xmEuVfRsk3M3Oapj-fPeYNDcMRbPbOYt?usp=sharing" target="_blank">postgresql-10.7-1-windows-x64.exe</a>

![image](https://user-images.githubusercontent.com/16941074/202847168-b0d3c2db-47e8-4de7-8857-69bd3fb1a6d2.png)

 >2. Installation directory, leave the Installation as is, click “Next”.
 
 ![image](https://user-images.githubusercontent.com/16941074/202847234-4517735e-c20d-4a51-be0e-7933e9b6404f.png)

 >3. In Select Components, click “Next”.

![image](https://user-images.githubusercontent.com/16941074/202847296-8f3e44e5-7698-4b02-b0e3-ba748458e9dd.png)

>4. In Data directory, leave the directory as is, click “Next”.

![image](https://user-images.githubusercontent.com/16941074/202847315-92bf3648-2c88-4ddf-b865-73551f88ea20.png)

>5. Specify database superuser Password, click “Next”.

![image](https://user-images.githubusercontent.com/16941074/202847716-883d95e8-7171-4c0a-9144-f744b8b58c58.png)

>6. Specify database superuser Password, click “Next”.

![image](https://user-images.githubusercontent.com/16941074/202847731-27884581-2f15-4b01-811b-151b3d148d85.png)

>7. In Advance Options, click “Next”.

![image](https://user-images.githubusercontent.com/16941074/202847757-3dcb4e7d-73ad-4acf-989d-c139a1f890cd.png)

>8. In Pre Installation Summary, click “Next”.

![image](https://user-images.githubusercontent.com/16941074/202847776-66573b9a-88a0-4197-a318-39a219697f5a.png)

>9. In Ready to Install, click “Next”.

![image](https://user-images.githubusercontent.com/16941074/202847824-5c0f05b8-13e5-487a-9663-d0567c02b64a.png)


>10. PostgreSQL installation starts!

![image](https://user-images.githubusercontent.com/16941074/202847841-50c18f34-b355-451d-a89c-5ea643e9eb6d.png)

>11. In this interface, uncheck “Launch Stack Builder at exit?” then click “Finish”. 
     Optionally, check the “Launch Stack Builder at exit ?” allows to download additional tools like “Postgis” from the internet!

![image](https://user-images.githubusercontent.com/16941074/202847925-c1755762-808f-47f9-98bf-4b3a4e70ef3b.png)

<p align="center">
   <img src="https://user-images.githubusercontent.com/16941074/202848243-dada256c-25c7-4ccb-8cfe-531bab40b096.png" alt="Sublime's custom image"/>
</p>

 <h2>PostGIS installation</h2>

>1. To install PostGIS, run “postgis-bundle-pg10x64-setup-2.5.1-1.exe.<br>
<a href="https://drive.google.com/drive/folders/1xmEuVfRsk3M3Oapj-fPeYNDcMRbPbOYt?usp=sharing" target="_blank">postgis-bundle-pg10x64-setup-2.5.1-1.exe</a>

![image](https://user-images.githubusercontent.com/16941074/202848461-e16b612a-16fb-45a6-8be3-ea7942b5034b.png)

>2. In Choose Components, click “Next”.

![image](https://user-images.githubusercontent.com/16941074/202848489-4bb3bd44-cafb-4f41-9c2f-caab4a23e88d.png)

>3. Choose Install Location, leave the “Destination Folder” as is
    then click “Next”.

![image](https://user-images.githubusercontent.com/16941074/202848521-48fcad99-51bb-406c-b6c1-fadf4dbc8740.png)

>4. PostGIS installation is ongoing, wait until completed! 

![image](https://user-images.githubusercontent.com/16941074/202848537-6de96514-c7d3-450a-99da-938a029441df.png)


>5. Click “Yes

![image](https://user-images.githubusercontent.com/16941074/202848572-c1bd5978-85a7-49a2-ab20-58ca28acb281.png)

>6. Click “Yes”

![image](https://user-images.githubusercontent.com/16941074/202848610-dc2c3e82-38d4-4e14-91ed-b8172e147f3e.png)

>7. Click “Yes”

![image](https://user-images.githubusercontent.com/16941074/202848719-2cad1e2d-c1d5-42bd-89b6-18fc0d97bf66.png)

>8. Installation complete. Click “Close”.

![image](https://user-images.githubusercontent.com/16941074/202848744-0abd4981-8f2b-4027-b1b7-cb46d809d015.png)

>Below is the interface of PostgreSQL Management Tools.
![image](https://user-images.githubusercontent.com/16941074/202848941-de0819a6-afea-480d-a7dd-1d65cdadf7de.png)


<p align="center">
    <img src="https://upload.wikimedia.org/wikipedia/commons/c/c2/QGIS_logo%2C_2017.svg" alt="Sublime's custom image"/>
</p>


QGIS is a free and open-source cross-platform desktop geographic information system application that supports viewing, editing, and
analysis of geospatial data.

For Farmland GIS, QGIS 3.4.4 version will be installed.

>1. To install QGIS 3.4.4, run “QGIS-OSGeo4W-3.4.4-1-Setup-x86_64.exe” Click “Next”

<a href="https://drive.google.com/file/d/1sjCi9qsZhuCnapCILPvbNmvxi99n8t2_/view?usp=share_link">QGIS-OSGeo4W-3.4.4-1-Setup-x86_64.exe</a>

![image](https://user-images.githubusercontent.com/16941074/202849245-72b9d7dc-6bdc-4b86-aec0-37c8c5d8b996.png)

>2. Click “I Agree”.

![image](https://user-images.githubusercontent.com/16941074/202849273-cd99d148-3ed6-4e02-aeeb-04a45603c9fe.png)

>3. In Choose Install Location, leave the destination folder as is. Click “Next”

![image](https://user-images.githubusercontent.com/16941074/202849304-6f3409dd-4b0a-42c2-b565-6df2a8ba247e.png)

>4. In Choose Component, click “Install”.

![image](https://user-images.githubusercontent.com/16941074/202849420-cec93767-5376-44a7-94cd-51b97ff5a969.png)

>5. Installation started. Wait until installation is completed.

![image](https://user-images.githubusercontent.com/16941074/202849453-ee16da93-6ea7-422f-98fe-cf4527d5632e.png)

>6. Click “Finish”.

![image](https://user-images.githubusercontent.com/16941074/202849476-84e6babb-2c0d-4f86-a74e-67da5885949b.png)

Below is the interface of QGIS 3.4.4


![image](https://user-images.githubusercontent.com/16941074/202849553-a74e6a71-dcb2-4768-b39b-1bc0ca89f1bd.png)



<h1><p align="center">
     FGIS database module installation!
</p>
</h1>
FGIS database module, is for managing farmer’s information.

>1. To install, run “fgis_setup.exe”. Click “Next”.

<a href="https://drive.google.com/file/d/1XNurYDdTMLHJWB5zTEaHY8n_PDyii8lP/view?usp=sharing">fgis_setup.exe</a>

![image](https://user-images.githubusercontent.com/16941074/202849913-d86e7391-7e95-42f4-ae04-a31a59ede1f2.png)

>2. Click “Install”.

![image](https://user-images.githubusercontent.com/16941074/202849928-f6e40b3c-e643-430f-8928-0918ec19281a.png)

>3. Installation in progress. Wait until completed.

![image](https://user-images.githubusercontent.com/16941074/202849943-277c02ef-6529-43c2-b855-c730ed69d23f.png)

>4. Click “Finish” after the installation is completed.

![image](https://user-images.githubusercontent.com/16941074/202849967-a76047d4-aa6e-41b7-8cf0-e82f6e51aa4d.png)



>5. Register “MapWinGIS.ocx. The ocx is a component for displaying map information.
    To register the component, right-click “regMapWinGIS.cmd” from \Installer\FGIS DB Management System\ocx\MapWinGIS directory and then    
    click “Run as administrator”.
    

<a href="https://drive.google.com/drive/folders/1tf5d0sTsqeC_Ukj23Q8tw1HUEknRUYkF?usp=sharing" target="_blank">MapWinGIS.ocx</a>

![image](https://user-images.githubusercontent.com/16941074/202880553-6e70ed3a-2f31-4d5e-bafd-623f05bf129f.png)


<h1><p align="center">
 FGIS mapping module are customized tools or plugin for QGIS.
</p>
</h1>

>1. To install the plugins, run “qgis_setup.exe from \Installer\QGIS 3.4 
      Plugins directory. Click “Install” to start the installation.
      
![image](https://user-images.githubusercontent.com/16941074/202881089-f61a7d3d-198a-4aad-afc8-78a8c161b967.png)

>2. Click “Finish”.

![image](https://user-images.githubusercontent.com/16941074/202881096-401d690b-cfcf-45e0-910c-57a247586855.png)

>3. Install plugins in QGIS!



  ```
    a. To load the plugins, open QGIS 3.4.
    b. In “Plugins” menu, click “Manage and Install Plugins
    c. In “Plugins” interface, mark the following plugins
                c.1. “Facility Assessment”
                c.2. “Farmland GIS Mapping 2019”
                c.3. “Geotag”
                c.4. “Geotag Converter”   
                c.5. “wdd”
                c.6. “wdd_fis”
    d. Click “Close” 
    
   ```

![image](https://user-images.githubusercontent.com/16941074/202881191-83abeb7d-df98-4269-a00b-f376898e06b9.png)

>4. After installation, the plugins toolbars should be visible in QGIS toolbars!

![image](https://user-images.githubusercontent.com/16941074/202881239-201c12b7-43ac-4e86-9450-f56a99787e55.png)


> Part of FGIS configuration is the restoration of pre-processed backup files needed by the system to run. The following are backup files need to restore in PostgreSQL database server (1) settings.backup, (2) riskmap.backup and (3) <RIS>.backup

>1. To restore the backup files, open “pgAdmin 4” Management tools

  ![image](https://user-images.githubusercontent.com/16941074/202881262-36b53f82-337d-41b2-a096-7a8a4fdd0955.png)

>2. Login to PostgreSQL server. Specify the password assigned during the  
     installation PostgreSQL.
  
![image](https://user-images.githubusercontent.com/16941074/202881289-e82db728-bc13-419c-a635-fc62aba4fcde.png)

>3. Create a Database where the backup will be saved. To create a database, right-click “Databases” on the left panel of the pgAdmin 4 interface.

![image](https://user-images.githubusercontent.com/16941074/202881298-1263de90-ff7a-432c-a272-e51ce7c5fc6d.png)

>4. In Create - Database interface, specify database name in “General” tab, for this sample specify the RIS name. Set the Owner to “postgres”. Click “Save”.

![image](https://user-images.githubusercontent.com/16941074/202881308-10b895c8-f236-4dd4-b3b2-a86ef0763d32.png)



>5. In Restore (Database) interface,

    a. set Format to “Custom or tar”

    b. Browse or open the backup file to restore.
        For this sample the ris backup file.        

    c. Set the role name “postgres”.

     d. Click “Restore”. 
     
   A notification will appear if the process was
   successful or failed restoration.

![image](https://user-images.githubusercontent.com/16941074/202911475-9d80a69e-317c-4ef3-9c3e-7bf203d7ad49.png)

![image](https://user-images.githubusercontent.com/16941074/202911610-aa3ed292-2631-4f5c-b6ae-49256d9adf3a.png)


>6. To restore the “riskmap” backup. Repeat step 3 – 5.  Input “riskmap” in database name. 
![image](https://user-images.githubusercontent.com/16941074/202911689-9c13fc91-fb2c-407a-bf86-dc5d7f913c79.png)

>7. To restore the “settings” backup. Repeat step 3 – 5.  Input “settings” in database name!
![image](https://user-images.githubusercontent.com/16941074/202911720-ceedfb7a-3226-40cc-bef7-171d3e54df8c.png)





<h1><p align="center">
     Connections Settings
</p>
</h1>

  
>1. Run FGIS.exe application in administrator (for first time installed).
>2. The system will show a message “Connection not configured. Set Configuration Settings.”.

![image](https://user-images.githubusercontent.com/16941074/203053106-dd17a94e-d712-4151-91ce-6a387007a420.png)
  
>3. In system setting dashboard, click system configuration!

![image](https://user-images.githubusercontent.com/16941074/203053303-9fa05d9d-bb4d-4172-bbc6-02a9fa1a9f30.png)

>4. Connection configuration interface will show.
  
>5. Enter the following server information: host/ip, port, username, password

![image](https://user-images.githubusercontent.com/16941074/203055503-40b85866-1265-49d1-8fde-1debb64ddf36.png)

>6. Once the connection is entered, connection list, add, edit, delete interface will show.
  
>7. Click add button.

![image](https://user-images.githubusercontent.com/16941074/203056769-bee891e1-e978-46fa-9e97-285fa677c44f.png)


>8. Add connection will show.
  
>9. Click test to test the connection to the server

![image](https://user-images.githubusercontent.com/16941074/203057049-906eca73-168d-4d4f-947f-944d99f51e11.png)
  
>10. Select the ris to connect.

![image](https://user-images.githubusercontent.com/16941074/203057316-7695357e-1a50-49c0-b4b3-281e893a7923.png)

>11. Once the ris is selected.
  
>12. Click OK button to save or cancel to cancel the transaction.

![image](https://user-images.githubusercontent.com/16941074/203058242-1f6bd85a-9e7f-44cb-8bae-b24ee3af988f.png)

>13. The connection is set, restart the application.

![image](https://user-images.githubusercontent.com/16941074/203058328-4aa3b23a-5d9f-4761-9836-0174d85f1bac.png)

>1. Once Log in as administrator (system admin, or ris admin).
  
>2. Go to setting dashboard.

![image](https://user-images.githubusercontent.com/16941074/203058437-b7126f1b-ef41-4691-a35e-87d5f63aea80.png)

>3. Click Add button.
  
>4. Add connection interface will show.

![image](https://user-images.githubusercontent.com/16941074/203058770-240c4505-0ea6-43b6-a2fb-54faff4e6bb7.png)


>5. Click RIS button to add new ris (existing ris database in the specified server).
  
>6. RIS interface will show.

![image](https://user-images.githubusercontent.com/16941074/203059115-bc3c82e4-7e7d-45e9-8c8e-86cf85aa880a.png)

>7. Select the ris or the database name.
  
>8. Description will automatically supply.
  
![image](https://user-images.githubusercontent.com/16941074/203059293-0095df1b-2c4f-450c-8903-d51f10676792.png)

>9. Select ris region for the region of database.
  
>10. Then click add button.
  
![image](https://user-images.githubusercontent.com/16941074/203059439-4875551f-2bb0-497d-be9c-089d881522b1.png)

>11. New ris will be added to ris records.
  
>12. Click close button.

![image](https://user-images.githubusercontent.com/16941074/203059541-2004f971-f6ee-4547-b279-844ad2d75b4d.png)

>13. Now the ris is available for the connection configuration!

![image](https://user-images.githubusercontent.com/16941074/203060007-ac032c2f-6053-4b0f-925d-a572c88aa113.png)


>1. For creation of users in fgis, must log in as ris administrator.

>2. Enter the admin account and select the ris, click login button.

![image](https://user-images.githubusercontent.com/16941074/203060698-2b20e9c0-e5af-4ce3-b392-b45c6a22de08.png)

>3. Message will show notifying the you are an administrator for that ris.
  
>4. Click OK.

![image](https://user-images.githubusercontent.com/16941074/203060820-c915f2f4-aa54-48f3-8e23-56413c183d99.png)

>5. Go to settings dashboard, it will show all the available functions for ris admin.
  
>6. Click Users button.

![image](https://user-images.githubusercontent.com/16941074/203060953-e316feba-73b4-4388-97f6-29189e450e50.png)

>7. User interface will show.
  
>8. To add new user, click add button

![image](https://user-images.githubusercontent.com/16941074/203067494-84762cd5-4efc-4dfe-a0c5-6f615e7a9003.png)

>9. Enter the new user information.
  
>10. In access infor, select the ris to be access, R/W = read and write, R = read, N/A = no access.

![image](https://user-images.githubusercontent.com/16941074/203067680-bbcfdb8c-ceaa-4b15-9bc1-331de9d04363.png)

>11. Click add button, new user will be added.
  
>12. To add picture for the user, select the user then click edit button.

![image](https://user-images.githubusercontent.com/16941074/203067769-09666b91-edb9-4554-a3ed-3d5c0b50f2f0.png)

>13. Click upload button to upload picture for the user.
  
>14. Browse the picture the click open button.

![image](https://user-images.githubusercontent.com/16941074/203068710-a87da41d-a938-41c6-9655-19dff946e23c.png)

>15. Click save button to save.

![image](https://user-images.githubusercontent.com/16941074/203068800-1da4aa2f-3c58-41ec-ad2a-ae938988cf11.png)

>16. Now the user have picture!

![image](https://user-images.githubusercontent.com/16941074/203068857-554e7c03-9c52-45cb-a934-e85e66af6da2.png)




![image](https://user-images.githubusercontent.com/16941074/205449235-91627376-be69-4776-bdaf-a89523e6abe6.png)































  






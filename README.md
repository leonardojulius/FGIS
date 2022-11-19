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

![image](https://user-images.githubusercontent.com/16941074/202849913-d86e7391-7e95-42f4-ae04-a31a59ede1f2.png)

>2. Click “Install”.

![image](https://user-images.githubusercontent.com/16941074/202849928-f6e40b3c-e643-430f-8928-0918ec19281a.png)

>3. Installation in progress. Wait until completed.

![image](https://user-images.githubusercontent.com/16941074/202849943-277c02ef-6529-43c2-b855-c730ed69d23f.png)

>4. Click “Finish” after the installation is completed.

![image](https://user-images.githubusercontent.com/16941074/202849967-a76047d4-aa6e-41b7-8cf0-e82f6e51aa4d.png)






















  






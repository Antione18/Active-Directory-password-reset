# osTicket Installation
# Summary/Description  
- In the project I follow the first hands-on video for osTicket. I am installing all of the prerequisits that are required for osTicket to work. Down below is all the photos and explanation of steps for this project. 
# Technologies & Enviorments used 
- Macbook Pro running Windows 10 
# Demonstration Steps & Media
# Step 1: Download the osTicket files
- After downloading the osTicket files on to my desktop from the checklist, I followed the video and extracted the folder with the actual documents from thezip folder and put that on my desktop then deleting the zip folder as the video said to.  
<img width="1026" height="364" alt="Screenshot 2025-11-06 123731" src="https://github.com/user-attachments/assets/415271ab-9db3-46c2-a604-0a14aac0712e" /> 

# Step 2: Enable IIS in Windows with CGI installed 
- To enabe IIS and install cgi I first went to the start menu to control panal, then to programs, once programs was open on the left side of the pop up I clicked "Turn Windows features on or off" after clicking that another pop up came up where I clicked the box to turn on Internet Information services. from there to install CGI I clicked the plus to expand IIS, clicked the plus to expand World Wide Web Services, clicked the plus to expand Application Development Features, and finally checked the CGI box to enable it. </p> 
<img width="1084" height="668" alt="2   CONTROL PANAL" src="https://github.com/user-attachments/assets/6d54bfe7-b17d-4955-8cf2-46156c495f4f" /> 
<img width="1082" height="651" alt="3  control panal programs" src="https://github.com/user-attachments/assets/f8513bcf-54ef-4174-83a7-2047d377b6da" /> 
<img width="1018" height="782" alt="4  control pnal programs enabiling iis" src="https://github.com/user-attachments/assets/bd38e242-a134-4db3-9586-27c4cc62a96c" />
<img width="690" height="466" alt="5  enabling CGI " src="https://github.com/user-attachments/assets/6df24882-4267-4ded-9e65-de1d71abd601" />

# Step 3: Install PHP Manager for IIS
- I open the osTicket files as the course video says, I click on PHP Manager, click agree on a few things and install.
<img width="862" height="613" alt="8  instaled PHP" src="https://github.com/user-attachments/assets/8761b1e3-f68b-4738-8779-48b84d077be6" />

# Step 4: Install Rewrite Modual 
- From inside the files I clicked on Rewrite and installed it.
<img width="816" height="543" alt="9  installed rewrite " src="https://github.com/user-attachments/assets/7d3d4c3e-87f6-4860-8489-b4ba7d142d94" />

# Step 5: Create a Directory for PHP
- I opened file explorer and went to the C folder and made a folder for PHP.
<img width="418" height="526" alt="10  creating directory for PHP C folder" src="https://github.com/user-attachments/assets/0040ad48-aa01-4192-a9a5-b33289ee89ad" />

# Step 6: Unzip PHP 7.3 folder into the Directory 
- From the osTicket files I right click on the PHP 7.3 file, click extract all, then I go to browse to select the PHP folder to exctact the files into.
<img width="820" height="540" alt="11  extracting PHP 7 3 files into PHP directory" src="https://github.com/user-attachments/assets/7362562e-c5a6-4c16-a5be-aefb81d7e97c" />

# Step 7: Install VCredist.x86 
- I double click the VC file and install.  
<img width="676" height="432" alt="12  installing VC" src="https://github.com/user-attachments/assets/2ea560eb-3610-4ca1-948d-d1dd822431d9" />


# Step 8: Install MySQL5.5.62
- I double click the MySQL5.5.62 files, install them, then I do the configuration of wizard and make the password.
<img width="624" height="462" alt="13  installed mySQL 5 5 62" src="https://github.com/user-attachments/assets/567208f3-6fa0-4e75-924b-262a39e0a778" />
<img width="628" height="534" alt="14  configuring wizerd making the password" src="https://github.com/user-attachments/assets/9acc3f1f-63ac-4ba6-adec-d80167ee1204" />
<img width="612" height="461" alt="15  mySQL 5 5 62 wizard configuration" src="https://github.com/user-attachments/assets/be72f8e7-777a-4ec8-9b43-b24e5b7c41cd" />

# Step 9: IIS and osTicket web server configuration 

# Step 9, Step 1: registering a new PHP
- I first go to windows start, type IIS, run as admin, I then register PHP from IIS, to register I double click PHP, click register new, and click the three dots to select the PHP directory I created earlier and the I register it. 
<img width="831" height="615" alt="16  iss admin " src="https://github.com/user-attachments/assets/8a7642c2-587f-4e5f-bf5b-45381dfbaa11" />
<img width="802" height="592" alt="17  regitering pHP from IIS" src="https://github.com/user-attachments/assets/627d2b52-935e-4100-8e18-036ccaf8c3b8" />
<img width="807" height="527" alt="18  new PHP version " src="https://github.com/user-attachments/assets/79a89942-519a-4ee4-8e51-b88181991954" />
<img width="694" height="385" alt="19  php file choose" src="https://github.com/user-attachments/assets/bf0f597b-aa21-4f61-b321-ddbe05e405f5" /> <p> 

# Step 9, Step 2: Reload IIS (stop and start the server)
- first inside IIS on the left I click on the machine thats running my computer, then on the right I click stop and once it has stoped I click start. <p> 
<img width="989" height="387" alt="20  stop and start iis" src="https://github.com/user-attachments/assets/ebc8c6ca-c999-48ea-90f9-c912aaf3c170" />

# Step 9, Step 3: "Install osTicket" 
- First I go inside the osTicket files, I unzip the osTicket folder which is inside the files, to do that I right click to extract, once it is extracted I copy the upload folder into the wwwroot folder, then the c folder, then Inetpub, wwwroot, I open another file explorer to upload folder drag it into the wwwroot and rename it to exactly "osTicket" and after thatI reload IIS by stoping and starting it like I did in step 2. 
<img width="680" height="490" alt="21  extracting osticket " src="https://github.com/user-attachments/assets/58216272-df59-4d74-b8d3-8c31f2a69ec9" />
<img width="1138" height="562" alt="22  upload folder into wwwroot folder" src="https://github.com/user-attachments/assets/983167d9-5590-4018-a665-6252b295817e" />
<img width="429" height="281" alt="23  rename uplaod folder" src="https://github.com/user-attachments/assets/d0dd98e9-1cec-4678-a026-d7aed05419f7" />

# Step 9, Step 4: Loading the osTicket site and enabling requirments
- In IIS I go to sites, defult, osTicket and on the right click browse 80 and the site pops up. next to enable requirments I first go back to IIS, sites, defult, osticket, double click PHP manager, then enable or disable extesntion, then I can go through the list and enable what needs to be enabled. 
<img width="1054" height="665" alt="24  osticket site" src="https://github.com/user-attachments/assets/adb1f4c1-1230-4664-bee1-14202580e286" />
<img width="610" height="505" alt="25  enableing things" src="https://github.com/user-attachments/assets/fd6924f3-fbc7-4190-8f52-88df73f1f065" />
<img width="478" height="483" alt="26  requirments changes" src="https://github.com/user-attachments/assets/2e81c297-b1d9-4c75-a441-d4cf589ee665" />

# Step 9, Step 5: renaming to osTicket-Config-PHP and assinging permission for osTicket to access it
- First I go to File explorer, C folder, Inetpub, wwroot folder, osTicket, include, and the scroll to ost-sampleconfig and rename it to ost-config.php. next to assign oermission I click on it, go to properties, security, advanced, disable inheritance, then add new permissions, type everyone add apply. 
<img width="586" height="232" alt="27  name change" src="https://github.com/user-attachments/assets/cf6b9f66-258c-4df7-93f7-565e0f394074" />
<img width="591" height="513" alt="28  osTicket permissions" src="https://github.com/user-attachments/assets/77243f54-3649-4dbc-863e-f24a9ac0346a" />

# Step 9, Step 6: setting up osTicket in browser
- Now I am filling out the osTicket Installation page.
  <img width="831" height="601" alt="29   setting up osticket browser" src="https://github.com/user-attachments/assets/1baa83f1-3c75-4afe-b1ce-c1dae78daf3a" />

# Step 9, Step 7: HiedeSQL 
- I go to the osTicket files, right click hiedesql,and install
<img width="823" height="603" alt="30  this heidesql" src="https://github.com/user-attachments/assets/ef535bd6-d090-4b42-9403-90bea7b9796e" />
<img width="806" height="547" alt="31  " src="https://github.com/user-attachments/assets/c419a3ed-12d7-43e9-b545-b6c310320476" />

# Step 9) Step 8: creating data base called exactly osTicket and finish
- Firs hiedesql right click the dolphin image, make new, type osTicket.
<img width="625" height="635" alt="33  hide sql " src="https://github.com/user-attachments/assets/52d86fa4-920b-4503-a568-1091490609b6" />
<img width="403" height="323" alt="34  " src="https://github.com/user-attachments/assets/56b08efc-53f7-4f59-826a-9a5b02216fd6" />
<img width="669" height="444" alt="35  finishing os browserr" src="https://github.com/user-attachments/assets/2f9343c0-6bf7-403e-b24a-62f71571da93" />
<img width="1023" height="666" alt="35  finish" src="https://github.com/user-attachments/assets/55be7aba-1428-46ba-832a-2dd7284c0da1" />

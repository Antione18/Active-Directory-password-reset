# osTicket Installation
# Summary/Description  
- jknkvnvnrlvnrlj
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
<img width="676" height="432" alt="12  installing VC" src="https://github.com/user-atttachments/assets/dc86130a-ec91-4aa6-95e5-caeccc95cdec" />

# Step 8: Install MySQL5.5.62
- I double click the MySQL5.5.62 files, install them, then I do the configuration of wizard and make the password.
<img width="624" height="462" alt="13  installed mySQL 5 5 62" src="https://github.com/user-attachments/assets/567208f3-6fa0-4e75-924b-262a39e0a778" />
<img width="628" height="534" alt="14  configuring wizerd making the password" src="https://github.com/user-attachments/assets/9acc3f1f-63ac-4ba6-adec-d80167ee1204" />
<img width="612" height="461" alt="15  mySQL 5 5 62 wizard configuration" src="https://github.com/user-attachments/assets/be72f8e7-777a-4ec8-9b43-b24e5b7c41cd" />

# Step 9: IIS and osTicket web server configuration 
Step one
- I first go to windows start, type IIS, run as admin, I then register PHP from IIS, to register I double click PHP, click register new, and click the three dots to select the PHP directory I created earlier and the I register it. 
<img width="831" height="615" alt="16  iss admin " src="https://github.com/user-attachments/assets/8a7642c2-587f-4e5f-bf5b-45381dfbaa11" />
<img width="802" height="592" alt="17  regitering pHP from IIS" src="https://github.com/user-attachments/assets/627d2b52-935e-4100-8e18-036ccaf8c3b8" />
<img width="807" height="527" alt="18  new PHP version " src="https://github.com/user-attachments/assets/79a89942-519a-4ee4-8e51-b88181991954" />
<img width="694" height="385" alt="19  php file choose" src="https://github.com/user-attachments/assets/bf0f597b-aa21-4f61-b321-ddbe05e405f5" /> 





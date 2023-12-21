Some of this may require you do a bit of research.   
  
Boot to command prompt and replace (rename the old one for saftey) C:\windwos\system32\winlogon.exe with a good copy (you will have to find one.)   
Add a reg key by creating a text file, adding the following lines and renaming it whatever.reg:   
[HKEY\_LOCAL\_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\WPAEvents]  
"OOBETimer"=hex:7f,63,3e,be,ec,25,8e,19,be,a7,92,c6  
  
Use the following command, pointing it towards your created file.  
  
Reg import whatever.reg  
  
reboot
Part 2:  
  
- Download the latest WPA\_KILL and also AntiWPA (torrent).  
  
- Once you run NTFSPRO from DOS/win98 your dead drive is mounted and visible, usually as D: drive since you boot from C: (now USB Stick or CD/DVD). You can use DOS filemanagers like "Norton commander" (free) to copy and save folders.  
  
- Here's is what I did after some thinking. in d:\windows\system32 I backed up svchost.exe by DOS commands and... go there first:  
d:  
cd d:\windows\system32  
rename and bakup (you'll need it)  
ren svchost.exe svchost.bak  
genius bit:  
copy d:\windows\explorer.exe svchost.exe  
  
Now if you log in without USB/CD/DVD it gets in with much delay and explorer comes up for only 30 seconds ONLY. BUT running WPA\_KILL or AntiWPA or REG edit files do not work.  
  
SO:  
An old trick for Administrator Password change if forgot/etc.: Screensaver, if set, can be renamed to CMD or explorer. But I had not set screensaver before Bill Gates stole my software. I gave it a shot. Boot into DOS/win98 with USB/CD/DVD again:  
  
run ntfspro then do this:  
d: (if your lost drive is d:)  
cd d:\windows\system32  
  
backup logon.scr, if you didn't have this file: no harm:  
ren logon.scr logon.bak  
  
make DOS command box your new screensaver:  
copy cmd.exe logon.scr
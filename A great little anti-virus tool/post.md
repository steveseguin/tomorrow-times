# A great little anti-virus tool

*Author: Steve*
*Published on: 2009-10-28T11:48:00.000-04:00*

---

I just discovered a neat little anti-virus tool call [NoVirusThanks.org Uploader](http://www.novirusthanks.org/progs/2/). I really do suggest you install this program, especially if you are the type of person who regularly downloads questionable executable files. ie: Cracks, Keygens, Warez. Even though I do not endorse the use of such questionable software, preventing the spread of viruses helps everyone in the long run.   
  
So here's the deal of how it all works,  
  
NoVirusThanks.org (NVT) is an online service that allows users to upload suspicious files for inspection of possible threats. Unlike a normal anti-virus software program installed locally on your computer, NoVirusThanks.org scans using 25 different virus scanners, significantly increasing the chance of an infected file being detected. The NVT Uploader application is a Windows-based application that simplifies the uploading process of a file to the online service. Once installed, a user simply needs to right click the suspected file and select submit to NVT. Your browser should open moments later with the results.  
  
Now, I know what you are thinking, that your virus scanner works fine and this extra bit of caution is paranoid thinking. My response to you is that you are completely wrong. One of the biggest security concerns with having a virus scanner today is the false sense of security they offer. I know first hand how easy it is to create a customized virus these days that is undetectable to most virus scanners. Your computer could be infected right now and you may not even know it.   
  
While a safe choice is simply not run any software that is at all questionable to you, if you find yourself needing to temporary run a piece of software, I really recommend you run in it in a virtual machine environment. Sandboxie is such an application (32-bit only). There are still some cases this won't do and so I recommend taking every precaution you can.  
  
To test out what I mean, I went online and downloaded a keygen from a popular cracks website. The website promised all its cracks were tested and were clean. I tested the application with TrendMicro Housecall, AVG, Avast and Microsoft's Security Essentials- all popular virus scanners. All results said the file was clean. So next, I used the NVT Uploader to see what it had to say about the file. The results are as follows,  
  
*File Info*  
  
Report generated: 28.10.2009 at 16.42.04 (GMT 1)  
Filename: **keygen.exe**  
File size: 326656  
MD5 Hash: 4c3883a25349521c635f1ee08ba4cf66  
SHA1 Hash: 0023710B30054CB25CAD112EF23C8CF4B7CD3858  
Self-Extract Archive: Nothing found  
Binder Detector: Nothing found  
Detection rate: 4 on 23  
  
*Detections*  
  
a-squared - Trojan-Spy.Win32.Banbra!IK  
Avira AntiVir - -  
Avast - -  
AVG - -  
BitDefender - -  
ClamAV - -  
Comodo - -  
Dr.Web - -  
Ewido - -  
F-PROT6 - W32/Heuristic-210!Eldorado  
Ikarus T3 - Trojan-Spy.Win32.Banbra  
Kaspersky - -  
McAfee - -  
NOD32 v3 - -  
Norman - -  
Panda - -  
QuickHeal - Suspicious  
Solo Antivirus - -  
Sophos - -  
TrendMicro - -  
VBA32 - -  
VirusBuster - -  
ZonerAntivirus - -  
  
*Scan report generated by  
[NoVirusThanks.org](http://novirusthanks.org/)*  
  
So it turns out the file was actually infected. Looking up online to see what the virus did reveals the following:  
  


|
|  |
|  | Trojan.Banbra is a Trojan which on execution displays fake webpages of a banking websites and tricks the user into entering his banking details including username and password. It captures all the entered information and sends that information to the author of this Trojan |

  
For obvious reasons, I'm pretty glad I did not get infected with this virus. Believing that my computer was clean, I would of possibly allowed a hacker to have access to my banking information.
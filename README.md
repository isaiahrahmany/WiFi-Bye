# WiFi-Bye
Kali Linux and ParrotSec Linux Compatable WiFi Jammer Utility  
This WiFi Jamming utlity utilizes Python and Aircrack-ng software  
*Both 2.4GHz and 5GHz Channels are compatable in this program

# Startup How To(s):
To get started: you will want first off to be running:
 - ParrotSec Linux OS 
 - Kali Linux OS
 
*YOU WILL ALSO NEED !
 
 Monitor Capable WiFi card(s):
 
  - *all cards need to be in monitor Mode prior!  
  -  Ex:  mon0,  mon1,  mon2,  mon3  
  
 *MAX UPTO 4 WIRELESS WLAN CARDs    
 *enable airmon-ng on all cards prior to execution  
 *then execute from a cmd
 
*GIT download executables - ONLY FIRST TIME INSTALL 

~$ git clone https://github.com/chamele0n1c/WiFi-Bye  
~$ cd Wifi-Bye  
~$ sudo -i  
~$ python deauth.py  

*FOLLOW ALL PROMPTS PRECISELY:

Ex: Enter Number of Cards -> 2\
Ex: Enter Card Names -> mon0, mon1\
Ex: Enter Bssids To Deauth on mon0 -> 3\
Ex: Enter BSSID1 -> EE:FF:DD:33:22:11
 

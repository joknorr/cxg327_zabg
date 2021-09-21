# ZIEHL-ABEGG CXG-327(A)NE-R with ZAbluegalaxy integration

## Filetransfer 
To install this files you need the chiptool utility. Open a FTP connection with the CXG-327(A)NE-R device.
Please backup all files before you you replace them. Then copy the follwing files from the to_drive-A folder to drive A: of the device:
- the complete CXG-428ANE folder and its content
- autoexec.bat 
- chip.ini 
- zabg.exe 

## Configure a DNS adress
To work correctly a DNS adress must be configured in the chip.ini file! Please open the chip.ini file inside the FTP client 
by right click and edit. Find the section DNS and enter a valid DNS address. A valid DNS address can be optained by checking your router address settings 
or often the router address intself is a good choice. 

[DNS]    
NAME_SERVER1=217.0.43.129

## Configure a ZAbluegalaxy fan Partnumber
ZAbluegalaxy can only create fans that are available in the ZAbluegalaxy device database. Please find the fan that you are using in your system 
and enter the partnumber in CXG327_PPN under the ZABG Section in the chip.ini.

[ZABG]    
CXG327_PPN=ZA-1stAxial  ; replace ZA-1stAxial by your fans partnumber

## Reboot
After copying the files the controller must be rebooted and if a static IP address is used, the IP address must be configured again.

## Create ZAbluegalaxy device
The ZAbluegalaxy device id can be optaind from the CXG-327(A)NE-R homepage. The format is ZA-320079-xxxxxxxxxxxx where x is the device id from the chiptool utility (Ethernet MAC). Please select the Product variant CXG-327ANE-R in ZAbluegalaxy for this device.


***After any changes in CXG-327ANE-R e.g. new fans added, please reboot the controller!***



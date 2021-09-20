# ZIEHL-ABEGG CXG-327(A)NE-R with ZAbluegalaxy integration

To install this files you need the chiptool utility. Open a FTP connection with the CXG-327(A)NE-R device.
Please backup all files before you you replace them. Then copy the follwing files from the to_drive-A folder to drive A: of the device:
- the complete CXG-428ANE folder and its content
- autoexec.bat 
- chip.ini 
- zabg.exe 

# Configure a DNS adress
To work correctly a DNS adress must be configured in the chip.ini file! Please open the chip.ini file inside tzhe FTP client 
by right click and edit. Find the section DNS and enter a valid DNS adsress. A valid DNS adress can be optained by checking your router adress settings 
or often the router adress intself is a good choice.  
[DNS]
NAME_SERVER1=217.0.43.129

# Rebbot
After copying the files the controller must be rebooted and if a static IP adress is used, the IP adress must be configured again.

# Create ZAbluegalaxy device
The ZAbluegalaxy device id can be optaind from the CXG-327(A)NE-R homepage or ZA-320079-xxxxxxxxxxxx where x is the device id from the chiptoll utility (MAC) . Please select the Product variant CXG-327ANE-R.

# After any changes in CXG-327ANE-R e.g. new fans added, please reboot the controller!



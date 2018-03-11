# Sync_Breeze_Enterprise_10_6_24_-DOS

        # Exploit Title: Sync Breeze Enterprise 10.6.24 - Denial Of Service Vulnerability
        # Date: 03-09-2018
        # Exploit Author: Ege Balcı
        # Vendor Homepage: http://www.syncbreeze.com
        # Software Link: http://www.syncbreeze.com/setups/syncbreezeent_setup_v10.6.24.exe
        # Version: 10.6.24
        # Tested on: Windows 7/10


This module triggers a Denial of Service vulnerability in the Sync Breeze Enterprise HTTP server. Vulnerability caused by a user mode write access memory violation and can be triggered with rapidly sending variety of HTTP requests with long HTTP header values. Sync Breeze Enterprise 10.6.24 version reportedly vulnerable.

#Exploits

[MSF Module](https://github.com/EgeBalci/Sync_Breeze_Enterprise_10_6_24_-DOS/blob/master/syncbreeze_enterprise_dos.rb)
[PYTHON](https://github.com/EgeBalci/Sync_Breeze_Enterprise_10_6_24_-DOS/blob/master/dos.py)
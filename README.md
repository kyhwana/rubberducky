# rubberducky
My Rubber Ducky repo
Containedmimikatz.txt is a rubberducky script for a rubberducky loaded with the twinduck "duck_v2.1.hex" firmware.
It finds the removable drive with the FAT label "AAAAA" (line 16 in the script, change as you need to) and dumps the output of mimikatz -dumpcreds to the SD card on the rubber ducky.
Should work on Windows 7 and above or any other Windows system with powershell installed.
On my system, takes about 17 seconds from start to end.

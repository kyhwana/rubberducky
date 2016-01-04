# rubberducky
My Rubber Ducky repo

Containedmimikatz.txt is a rubberducky script for a rubberducky loaded with the twinduck "duck_v2.1.hex" firmware.

It finds the removable drive with the FAT label "AAAAA" (line 16 in the script, change as you need to) and dumps the output of mimikatz -dumpcreds to the SD card on the rubber ducky.

Should work on Windows 7 and above or any other Windows system with powershell installed. mimikatz doesn't seem to capture plaintext passwords on Windows 10 machines with a MS account + PIN login enabled. You may also need to tweak the DELAY times, especially the UAC bypass one. If it takes to long to run powershell the first time, remove the rubber ducky and try again.

On my system, takes about 20 seconds from start to end.

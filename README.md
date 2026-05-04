# Marschall Stockwell-2 Firmware
Firmware Dump of Stockwell 2 

My Stockwell went silent so i searched quiet a while to get those Files.
All i had to do is reflash the flash of the BT module. I used my Xgecu TL866 but a cheap programmer like the ch341a or even a Arduino in ISP mode would be enough.
If you dont have exact flash profile, like i did, just use a close one. I used the MX25L6436E instead of the MX25L6436F, just try your luck but you have to match at least the the 64 (size of flash)

                MX25L6436F
25: Serial Flash - L: 3V - 6436F: 64Mb standard type

And to make it even better :D YOU DONT NEED TO SOLDER :D i used a programming Clamp or Clip for the lil Tsop8 Chip. 
A short look on the dump... the data was Trash!

Ill hope this will help you, like it did for me.


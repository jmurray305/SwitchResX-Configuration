# SwitchResX-Configuration
SwitchResX Configuration setting for LG 34 UltraWide Monitor

SwitchResX is used to take control of any screen connected to the Mac. No matter whether a MacBook Screen, an external monitor, a Retina display. For more [INFOMATION](http://www.madrau.com/)


## Disabling SIP(system Integrity Protection)- must be disabled if running OSX 10.11 or higher

1. Boot into the recovery partition by pressing CMD + R when starting up your Mac.
2. Once in recovery mode, open a terminal window.
3. Type the command `csrutil disable`
4. Reboot

Lanuch SwitchResX from System Preferences, select the external monitor from the list on the left.
Select the 'Custom Resolutions' tab.
Add a new custom resolution be clicking the + symbol at the bottom of the window.
Adjust the settings to match the appropriate PNG provided in this gist.
Press 'Ok'
Close SwitchResX and save when prompted.
Restart your Mac.

## Enable SIP
1. Boot into the recovery partition by pressing CMD + R when starting up your Mac.
2. Once in recovery mode, open a terminal window.
3. Type the command `csrutil enable`
4. Reboot

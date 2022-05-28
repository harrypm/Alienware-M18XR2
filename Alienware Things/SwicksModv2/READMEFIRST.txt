First off - 
YOU TAKE FULL RESPONSIBILITY FOR FLASHING THIS MOD!  IF SOMETHING HAPPENS DO NOT BLAME ME.  ITS BEEN TESTED AND WORKS, BUT IF THERE IS A PROBLEM IT IS NOT MY RESPONSIBILITY!  BY CONTINUING YOU ACCEPT THE RISKS...
FURTHERMORE, PLEASE DO NOT DISTRIBUTE ANY OF THESE FILES!  YOU SHOULD ONLY DOWNLOAD FROM TECHINFERNO AS THAT IS THE ONLY PLACE THAT HAS A CERTIFIED, CLEAN, WORKING BIOS MOD!  ANYONE ELSE THAT DISTRIBUTES IT PROBABLY HAS STOLEN IT.
LASTLY, PLEASE CONSIDER DONATING TO ME IF YOU LIKE THIS!

https://www.techinferno.com/index.php?/forums/topic/9693-m18xr2-bios-mod-legacy-support-now-available/&do=edit
Location to post where file is located and info about file!  

Thanks,
Swick


Link to donate:  https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=ATZDQNDMV45LG


---------------------------------------------------------------------------------------------------------------------


Okay, now that the "legal" crap is over, lol...

Instructions:

1)  Create a Bootable DOS BOOT DISK
2)  Extract ALL files in this RAR file to the root of the flash drive.
3)  Keep USB flash drive plugged into USB port and go into bios
3)  Go into bios and change the setting to LEGACY in the boot menu.  (This allows you to boot into DOS)
4)  Once you've saved the setting and reboot, you'll want to hit F12 to select the USB drive as boot drive
5)  You should see a C:\ command prompt.  If so, you've successfully booted into dos
6)  Now you will need to run the command "FLASH.BAT" (without the quotes)
7)  It will run the unlocking bios tool (CREATED BY SVL7 - FULL CREDIT TO HIM) in order to write to the bios
8)  Once run, it will tell you ready to flash.  Press any key to continue.
9)  Once you've pushed any key, it will flash.  Wait for the flash to finish.  
10)  You'll see a message that says data is IDENTICAL of something along those lines.  That means flash in complete!
11)  Once you see that message AND you see the "C" prompt (C:\) you'll know the flash is done!
12)  Reboot the laptop...
13)  Remember that with this BIOS MOD I've changed the default Primary Display to IGFX  (FOMR PEG), so you don't need to worry about the 8-beeps issue while in legacy mode!  
14)  Once you've rebooted the laptop, go into the BIOS and change the settings to whatever you had them set as before!
15)  LASTLY - IMPORTANT - If you are running Windows 8 or higher, you MAY have to reinstall the OS, but by flashing this BIOS MOD, you will be able to install Windows 7 with FULL 900 Series GPU support.  It works perfectly!


IF YOU HAVE TROUBLE - IN CASE OF A PROBLEM:
If you have a problem, there is a file on here called m18R2.hdr & m18r2.hdr.bin.  
These file can be used to blind flash the system if the flash goes wrong for some reason
I've given you 2 files - the m18r2.hdr file is the ENTIRE BIOS (ME REGION, BIOS).  The m18r2.hdr.bin file is JUST the bios.  You can TRY using the m18r2.hdr.bin file first, but you will have to extract it and change the name to m18r2.hdr (you have to remove the .bin). 
Take the HDR file you want to use (5mb or 8mb), put on a flash drive, plug flash drive into the esata / usb port
Unplug power cable & battery
with flash drive in the esata / usb combo port, hold down the end key and plug the power cable in ONLY!  (DO NOT PLUG IN BATTERY).
You will here the computer turn on and lights go on, etc...  Then you will start to hear beeps.  once you hear beeps, release the end key.  Let the computer do it's thing, and once the beeps stop the PC will reboot 1 or 2 times.  The PC should boot up and you should be able to see the bios that you blind flashed.  The blind flash file default primary graphics has also been changed to IGFX - it used to be PEG - by doing this you wont have the 8-beep issue and have to tear down your pc EVER again!

You will NEED to flash my bios again if you want all those features listed below.  The blind flash file (.hdr) is an older file without any updates so you'll need to try flashing my bios mod again!  


ENHANCEMENTS \  UPDATES  \  ADDONs to my mod
Here are the enhancements I've made to this bios - 
UNLOCKED A11 BIOS BY SVL7 - FULL CREDIT GOES TO HIM FOR THE UNLOCKING OF BIOS!  THANK YOU SVL7!!!
Updated this bios to support 900 Series GPU's in legacy mode - 900 Series GPU's now work 100% in Windows 7
Updated vBios to 2171 for Sandy & Ivy Bridge OnBoard GPUS's (HD3xxx & HD4xxx)
Updated CPU Microcode for all CPU's (Especially 2900 Series CPU & 3900CPUs)
Added NvMe Support added
Added M.2 Support
Updated Intel RST (LEgacy OpRom) to 12.9.0.2006  -  FULLY SUPPORTS TRIM in RAID0
Updated Intel RST (UEFI Module) to 12.9.0.2006  -  FULLY SUPPORTS TRIM in RAID0
Updated the Lan & PXE Boot Firmware from 2.0.5.9 to 2.0.6.6
Updated the GOP Driver for Intel & Sandybridge GPU's to latest version supported by our system
Updated the GOPPolicy (Main Policy) to latest version




Link to donate:  https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=ATZDQNDMV45LG


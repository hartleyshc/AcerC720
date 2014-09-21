# Note on ArchLinux on the Acer C720 Chromebook.  

So the Archwiki has most of the must have info. These are just my notes on what I'm doing to keep my new linux laptop happy!

## Enable the watchdog
Copying system.conf to /etc/systemd or setting RuntimeWatchdogSec to a value should have systemd enable the hardware watchdog.  

## Trackpad
Ugh, buy a mouse.  
If you're stuck with the trackpad, the synclient.sh can run on X startup.  Its ssets the trackpad to some more sensible defaults.  Still a bit of a challenge and I end up reaching for a mouse most of the time.  

 

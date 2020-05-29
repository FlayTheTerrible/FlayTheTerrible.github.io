### More a crib note than a guide:

Ensure "wine" and "winetricks" are installed via GUI or command line. During all the below winetricks kept notifying about 64 bit. Ignore. Annoying.

Follow the DXVK WINE install section on the archwiki (https://wiki.archlinux.org/index.php/Wine#DXVK). I used this following string to set up the default prefix: 

	WINEPREFIX="/home/christopher/.wine" setup_dxvk install

I've always installed corefonts and Visual C DLL's via winetricks. GUI or:

	winetricks corefonts vcrun2005 vcrun2008 vcrun2010

Download the latest EVE installer and install via shell or  winetricks. The latter created desktop launch icons for me.

	wine EveLauncher-blahblahblah.exe


Follow along with eve's wizard and you SHOULD be good to go.

further reading:

https://wiki.archlinux.org/index.php/User:Mcnster/EVE_Online

https://wiki.archlinux.org/index.php/Wine

https://kevandrews.uk/eve-online-arch-linux


Footprint:

Operating System: Manjaro Linux 
KDE Plasma Version: 5.18.5
KDE Frameworks Version: 5.69.0
Qt Version: 5.14.2
Kernel Version: 5.6.11-1-MANJARO
OS Type: 64-bit
Processors: 8 × Intel® Core™ i7-2600K CPU @ 3.40GHz
Memory: 15.6 GiB of RAM
Video: Nvidia Geforce GTX 970, driver 440.82

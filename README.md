# powered-plymouth-theme

A plymouth theme forked from the wonderful tux-plymouth-theme (https://github.com/Tux4Ubuntu/tux-plymouth-theme).
The idea is the same: to have a Tux themed plymouth-theme. Except now the Tux logo is more stylized and it has the phrase "Powered by GNU/Linux" so
everyone knows what you are using! 
Sadly, I could not find the author of the image. Please, if you are the author, let me know, and apologies in advance.


INSTALLATION INSTRUCTIONS (tried on Pop!_OS 20.04)
Method 1:
1. git clone https://github.com/garak92/powered-plymouth-theme/
2. cd powered-plymouth-theme/
3. sudo mv powered-plymouth-theme/ /usr/share/plymouth/themes/ 
4. sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/powered-plymouth-theme/powered-plymouth-theme.plymouth 100
4. sudo update-alternatives --config default.plymouth (here you will be prompted to choose your theme)
5. sudo update-initramfs -u

Method 2:
1. git clone https://github.com/garak92/powered-plymouth-theme/
2. cd powered-plymouth-theme/
3. chmod +x install.sh
4. ./install.sh

ORIGINAL CREDITS AND ATTRIBUTION
 
    THEME written and designed by:
        Tuxedo Joe (Josef Norlin) <http://github.com/tuxedojoe>. 
        Based on the example provided with the "script plugin" written by:
        Charlie Brej   <cbrej@cs.man.ac.uk>
        Documentation and instructions where found here: <https://wiki.ubuntu.com/Artwork/Documentation/Plymouth>
        and here: <https://www.freedesktop.org/wiki/Software/Plymouth/Scripts/>
        With additions from Ubuntu 18.04 LTS plymouth logo, created by:
        Alberto Milone <alberto.milone@canonical.com>

    TUX ILLUSTRATION by:
        Larry Ewing, at: http://isc.tamu.edu/~lewing/linux/
        Redrawn in Inkscape by:
        Garrett LeSage: https://github.com/garrett/Tux
        License: Public domain http://creativecommons.org/publicdomain/zero/1.0/

    CHAT BUBBLE FONT by:
        Jayvee Enaguas, at: http://harvettfox96.deviantart.com/
        Downloaded from: http://www.dafont.com/suplexmentary-comic-nc.font?l[]=10&l[]=1
        License: 100% Free
        
        
SAMPLE SCREENSHOT:

![Alt text](/powered-plymouth-theme/screenshot.png?raw=true "Powered by GNU/Linux!")

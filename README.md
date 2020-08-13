# tux-plymouth-theme
╔═════════════════════════════════════════════════════════════════════════════════╗
║ TUX 4 UBUNTU - TUX PLYMOUTH THEME                   © The Tux4Ubuntu Initiative ║
║ – Let's bring Tux to Ubuntu                               http://tux4ubuntu.org ║
╠═════════════════════════════════════════════════════════════════════════════════╣
║                                                                                 ║
║   Ubuntu is nice but it needs to TUXedo up with Tux! Through this Plymouth      ║
║   theme you'll see Tux greet you at boot and shutdown.                          ║
║                                                                                 ║
║   Read more and support our cause at <http://tux4ubuntu.org>                    ║
║                                                                                 ║
╚═════════════════════════════════════════════════════════════════════════════════╝


INSTALL INSTRUCTIONS (in progress...)

1. cd /usr/share/plymouth/themes/
2. sudo git clone https://github.com/garak92/tux-plymouth-theme/
3. sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/powered-plymouth-theme/powered-plymouth-theme.plymouth 100
4. sudo update-alternatives --config default.plymouth (here you will be prompted to choose your theme)
5. sudo update-initramfs

CREDITS AND ATTRIBUTION
 
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
        
    THIS FOR MADE POSSIBLE by:
         garak92

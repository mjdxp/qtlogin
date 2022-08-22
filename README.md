# qtlogin
A fork of QTStep's SDDM theme to look more like CDE's dtlogin

Original project: https://github.com/andbgr/QTStep

I wanted a nice looking login manager theme to go with my CDE inspired desktop, but I couldn't find any. So, I decided to modify the one used for QTStep.

The name is a combination of "dtlogin," the name of CDE's login manager, and QTStep.

To install, copy a directory containing this repo's files to SDDM's theme directory (likely `/usr/share/sddm/themes`), then change the "Current=" line in your sddm.conf file (located at `/etc/sddm.conf` on my system)

I attempted to edit the SVG files to make them better resemble motif buttons, however I know next to nothing about vector graphics editing, so when I tried to use my custom buttons, they just didn't appear. I must have done something wrong. If anyone out there is better at Inkscape than I am, I'd love someone to change the buttons for me!

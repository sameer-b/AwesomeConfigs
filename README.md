AwesomeConfigs
==============
![Screenshot](https://raw.github.com/sameer-b/AwesomeConfigs/master/awesomeWM.jpg)



here are my aweomeWM configs.
a)rc.lua
b)theme.lua
c)icons/artwork

The config uses the following startup packages:
1)newrez -> scale resolution
2)synapse -> launcher
3)preload
4)volumeicon -> volume applet
5)nm-applet ->network manager applet
6)batti -> battery applet
if you do not have these installed, either install them or comment them out, from the end of rc.lua

Please set the correct location for theme.lua and all the images.
The images are included in the icons folder but you will have to manually set the path for the icons.
The sound,wifi,battery applets are NOT lua applets. I use simple gtk applets from AUR.
 
NOTE: the fonts will be really large. Please scale them down from rc.lua and theme.lua. Since newrez scales up my screen, i use rather large fonts. :)

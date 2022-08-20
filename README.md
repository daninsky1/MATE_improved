# A great Linux experience

This is a guide to make MATE desktop enviroment to be modern and add some Windows behavior. The parts that are not exclusive to MATE can be brought to others Gnome based DEs, or you can get an inspiration and find it some other way around to some of this.

My opnion using vanila Cinnamon, MATE, and Gnome.
The problem with Gnome is they bring some good thinks and bad thinks, some of the bad thinks are pretty annoying to me, like the 
OSX inspired design decisions, but that's fine.  
The support for black mode are poor, some of the apps doesn't support the window bar became white!?.
And all buttons, windows bar is to big, no respect for your screen space, one screen, keyboard and mouse input? To bad, now you can only see are giant buttons.

The problem with Cinnamon.  
Cinnamon are pretty good to bring some of the Windows like features, the quarter window tilling with Windows like keyboard shortcuts.  
great default apps nemo, disk. And they have some exclusive GUI app to customize some parts of the DE.  
However the default redesign of 3rd party apps icons are annoying, that's not a good, and not a good idea. First the design is ugly, second the commitment to update all possible icons is insane, you will at one time or another run into apps with the default icon, so don't mess with the default icon of 3rd party apps.  
I know, you can change the theme to other that doesn't do that, however these themes lack default app icons.  
The new window themes are bad to, the window bar became to big, the round edges even more round even more Gnome like, but the thing is Cinnamon doesn't need the window bar to big because a lot of its apps doesn't use the OSX/Gnome like button there. So you got the window bar height + the menu bar for apps that doesn't have the menu bar on the window bar.  

MATE on the other hand are pretty good. The window bar is not to big, the Ubuntu version has a lot window bar options, some of then are pretty thin, and the support for black are the greatest. A lot of apps behave as expected in black mode, of course, not all of then, for example Modelio.  
So that's why this will be focused on MATE.

First we will begin with the xorg color range. Activating the full rgb espectrum for monitors that support it. First you can check if your monitor can support 16 plus million of colors, check the model on the back of your monitor and search it.
If yes, now we can check if the xord connected outputs:  
`xrand`  
```
Screen 0: minimum 320 x 200, current 1920 x 1080, maximum 16384 x 16384
VGA-1 disconnected (normal left inverted right x axis y axis)
HDMI-1 disconnected (normal left inverted right x axis y axis)
DP-1 disconnected (normal left inverted right x axis y axis)
HDMI-2 disconnected (normal left inverted right x axis y axis)
HDMI-3 connected primary 1920x1080+0+0 (normal left inverted right x axis y axis) 477mm x 268mm
   1920x1080     60.00*+  50.00    59.94  
   1920x1080i    60.00    50.00    59.94  
   1680x1050     59.88  
   1280x1024     75.02    60.02  
   1152x864      75.00  
   1280x720      60.00    50.00    59.94  
   1024x768      75.03    60.00  
   800x600       75.00    60.32  
   720x576       50.00  
   720x480       60.00    59.94  
   640x480       75.00    60.00    59.94  
   720x400       70.08  
DP-2 disconnected (normal left inverted right x axis y axis)
DP-3 disconnected (normal left inverted right x axis y axis)
```
Check the monitors that are connected, in my case only HDMI-3.  
Now we check the color range that are beign used.

TODOs:
* How to add a custom file manager.
* How to add a custom system monitor.
* How to enable full rgb color on xorg for monitor that support it.
* How to add some Window shortcuts for, file manager, system monitor, screen shot, configuration, etc.
* How to make Chrome based browsers to scroll the same length as Windows versions.
* How to custom panels to behave Window like.

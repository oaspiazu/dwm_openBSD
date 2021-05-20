# dwm_openBSD
The idea of this repository is to have an OpenBSD DWM source with some patches applied. Some of them are just eye-candy and the other ones are interesting features that make DWM unique.

For more information about DWM, have a look at the website: https://dwm.suckless.org/ 

Reasons:
  A lot of time is needed to apply manually these patches. Also, some corrections are needed.
 
Dependencies:
Only SF Font. If you want your own font, just change it in your config.sh

Key bindings:
Allmost vanilla. Have a look at config.h for your preferences.

Patches:
  All patches are vanilla, without modifications or very little modification to make the code just work.
  
Actually applied: 

alpha: https://dwm.suckless.org/patches/alpha/
fullscreen: https://dwm.suckless.org/patches/fullscreen/
fullgaps: https://dwm.suckless.org/patches/fullgaps/
noborder floatingfix: https://dwm.suckless.org/patches/noborder/
pertag perseltag: https://dwm.suckless.org/patches/pertag/
hide_vacant_tags: https://dwm.suckless.org/patches/hide_vacant_tags/
swallow: https://dwm.suckless.org/patches/swallow/
bar_height: https://dwm.suckless.org/patches/bar_height/

---

There's a little issue with the st terminal if you have transparency enabled. When you go in monocle mode (fullscreen), you can see the rest of the windows of the tab in the background.
The solution is probably in this patch:https://dwm.suckless.org/patches/clientopacity/ . Before uploading the changes, some work is needed to compile it as it does no compile with swallow applied.

The last patch will be probably the scratchpad.

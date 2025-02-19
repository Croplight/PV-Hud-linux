# PV Hud
<a>ABOUT</a>
====
Fork of Hypnootize's updated PV Hud with better font support for Linux.

Currently only combattext fonts have been altered.
Requires Microsoft fonts to be installed system-wide, read about that here: https://wiki.archlinux.org/title/Microsoft_fonts

Rest of original readme is as follows:

<a>LINKS</a>
====

[TeamFortress.tv](https://www.teamfortress.tv/33738/ive-updated-some-huds)

[Screenshot Album](https://imgur.com/a/C3dXl)

[Changelogs](https://github.com/Hypnootize/PV-Hud/commits/master)


<a>INSTALLATION</a>
====

**1)** Extract/Unzip the hud and copy the PV Hud folder

**2)** Paste The folder to your custom tf folder (C:\Program Files (x86)\Steam\SteamApps\common\Team Fortress 2\tf\custom)

**NOTES:**

I suggest using **"tf_hud_target_id_disable_floating_health" "1"** since the floating version is not as consistan and can have problems.

The original rgb code for the damage numbers is: hud_combattext_red 255; hud_combattext_green 255; hud_combattext_blue 0


<a>CROSSHAIRS</a>
====

All the hud crosshairs can be found inside the scripts/crosshairs/Crosshair.res file.

Change the "visible" value to "1" to enable the hud crosshair and change the "labelText" value to switch the crosshair style, checkout the Crosshairs.png in order to see all the possible options!

It is also possible to easily animate the crosshair to turn red on damage by editing the scripts/crosshairs/Animations_Crosshairs.res file, you can find all the instructions inside the file!

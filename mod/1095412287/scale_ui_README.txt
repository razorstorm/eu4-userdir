scale_ui
by goondo

Donations:
BTC bc1qkr4lsyl499kyx4kyspyfgt9urv293qslk056ge
ETH 0x9a04629d2E553aA533B37ce068854CA88BD1b369

Description:

Scales EU4 ui for high resolution monitors.  Users with 1440p/2160p monitors will have a scaled ui that looks exactly like 1080p respectively.  No more blurry font due to downscaling resolution. Play at your native resolution!

Note: One negative of mod is no achievements. Achievements can be reenabled by moving the map directory out of the mod directory structure. Of course doing so will break the minimap.

Note:  If you have the mod already please delete the old scale_ui directory, or rename it.  Prior to deleting make sure that to note down any custom directory settings.

Requirements:
- Windows, Linux
- Install gimp 2 (https://www.gimp.org/downloads/)
- For gimp older than 2.10.10, Install gimp-dds plugin ( https://code.google.com/archive/p/gimp-dds/downloads )
- Under 1.0 gigs of space is needed for the mod.


1)  Insure software requirements are installed on your system.
2)  Find the mod in the C:\Program Files (x86)\Steam\steamapps\workshop\content\236850\1095412287 directory.  Unzip *.bin file into 1095412287  directory.  Copy 1095412287  directory into Europa Universalis IV mod directory.  Usually, found in "C:\Users\your_username\Documents\Paradox Interactive\Europa Universalis IV\mod".
3)  Double-click on "install_scale_ui_mod.bat" (On linux run "python install_scale_ui_mod.py").  Follow the instructions, and provide information as needed by the installer.

1440 - A 1080p look for 1440p native users, support via interface patches
2160 - A 1080p look for 2160p native users, support via interface patches

4)  Wait for execution to finish (10-20 mintues).  The window should close on it own when done.  Check debug.log found in the scale_ui directory.
5)  If EU4 launcher is open please close and reopen in order to update mod list.  Please select scale_ui_XXXXp where XXXX should be the resolution height selected during install.  Note: That "scale_ui" should not be enabled at all.
6)  Play game at your native resolutions.

Enjoy!


Change Log:

Version 0.1.16
- Support 1.31.3.0 (Majapahit)
- Add dlc_pictures to rescale list
- Added crypto donation addresses

Version 0.1.15
- Support 1.31.2.0 (Majapahit)

Version 0.1.14
- Support 1.31.0.0 (Majapahit)
- Adjusted estate privileges listbox
- Do not scale number_of_reforms_per_row

Version 0.1.13
- Achievements files have new prefix
- Have user install third party dds (GIMP dds plugin does not work)

Version 0.1.12
- Support 1.30.6.0 (Austria)
- Handle different GIMP base directories

Version 0.1.11
- Support 1.30.4.0 (Austria)

Version 0.1.10
- Support 1.30.1.0 (Austria)

Version 0.1.9
- New launcher

Version 0.1.8
- Support 1.29.3.0 (Manchu)

Version 0.1.7
- Support 1.29.0.0 (Manchu)
- use python logging

Version 0.1.6
- New windows batch file

Version 0.1.5
- support gimp 2.10.12

Version 0.1.4
- gimp 2.10.10 has a dds plugin

Version 0.1.3
- Support 1.28.1.0 (Spain)

Version 0.1.2
- Support 1.27.2.0 (Poland)

Version 0.1.1
- Support 1.26.0.0 (Dharma)
- Comment out traceback prints in rescale_gfx.py

Version 0.1.0
- New installer scripts

Version 0.0.8
- Moved achievements, and buildings into temp_gfx/interface

Version 0.0.7
- Included rescale_interface.py
- Support 1.25.0.0 (Rule Britannia)
- Regenerated fonts

Version 0.0.6
- Adjust maxWidth for unique ideas on ideas tab
- Support 1.24.1.0 (Japan)

Version 0.0.5
- Support 1.23.0.0 (Cradle of Civilization)

Version 0.0.4
-  Moved scaling of temp path

Version 0.0.3
- copy scale_ui.mod into mod directory

Version 0.0.2
- Steam Release
- Made mods to structure to allow for uploads
- Made mods to rescale_gfx.py
- if gfx asset exist in mod, do not rescale
- delete gfx assets to force rescale

Version 0.0.1
- Initial Release

Donations:
BTC bc1qkr4lsyl499kyx4kyspyfgt9urv293qslk056ge
ETH 0x9a04629d2E553aA533B37ce068854CA88BD1b369
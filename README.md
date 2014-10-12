There are two scripts here to help apply a large amount of hot fixes for elementary OS Luna and Frey on the HP Chromebook 14. This script should work for many other Chromebooks, but I've only tested it on my HP 14 for Luna.

Script elementary12.py is for Luna with prompts to select installed software

Script elementary12_streamed.py is for Luna and eliminates most prompts and just installs everything. See below for the full list of fixes and installations

Script elementary14.py is for Freya with prompts to select installed software

# Usage: #
1. Install elementary OS Luna using Chrubuntu to partition the drive and then a live USB containing elementary OS Luna

2. Once installed, download the script and run the command from terminal: "sudo python ~/Downloads/elementary12.py"

3. Be sure to carefully type your username given during installation as this will be relied upon in the script

4. Follow along with the script reading each prompt carefully

5. If the script fails or you accidentally stop it, I don't have any good remedies besides looking at one of my manual guides. DON'T RUN IT A 2ND TIME NO MATTER WHAT

# After the script has finished and your system has rebooted you can optionally do the following: #

1. Assign a hotkey to Guake if you installed it using Guake Preferences as the default one won't work on Chromebooks

2. Set your themes and wingpanel settings in Elementary Tweaks from in the System Settings if you chose to install them

3. Delete your wired connection from Network Manager to avoid it trying to connect to it all the time

4. Assign Fullscreen (F4) to Toggle Fullscreen in System Settings>Keyboard>Windows>Shortcuts

5. Enjoy elementary OS Luna



Ian Richardson / iantrich.com



Tweaks / Installations:
* Upgrade kernel to stable 3.17
* Fix suspend and boot times
* Set power button to function as expected (Freya)
* Touchpad tweaks (Luna: Increased sensitivity Freya: ChromeOS driver)
* Install Oracle JDK 7 or OpenJDK 7
* Install Guake Terminal
* Install Numix theme, icons and elementary tweaks
* Install Wingpanel-Super and Wingpanel-Slim (Luna)
* Install Build Essentials
* Install Keymapping Tools
* Install TLP Battery Saving Tool
* Install Chrome browser and fix Plank icon issue
* Remap Super key to Search key (Search+Space for Application Launcher)
* Remap Left, Right, Refresh, Fullscreen and Display
* Map Delete to Shift+Backspace
* Install Gimp
* Install Libreoffice
* Install VLC
* Install qBittorrent
* Install Glipper Clipboard Manager
* Install Natural Scrolling (OS X Style Scrolling) (Both but more applicable for Freya)
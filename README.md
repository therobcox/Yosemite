# Yosemite
Dynamic Background for gnome desktop

![Evening](https://github.com/user-attachments/assets/084c1a06-b24e-4f1a-ab07-d75d7c67e275)


# Description
A simple Dynamic Background theme for gnome desktop.

The brightness syncs with the time of day creating a subtle and pleasant background.

The Dynamic Background can be installed directly into the system backgrounds folder.

Then you can enable using the gnome Settings -> Backgrounds section of your distribution. 

![Twilight](https://github.com/user-attachments/assets/d8fd7b30-1a69-40f8-a026-fbaac1a3c7cb)


# Installation
Download Yosemite Dynamic Background here: <a href="https://www.gnome-look.org/p/2313312/">https://www.gnome-look.org/p/2313312/</a>

To install, copy files to the system backgrounds folder using root privileges.

 - Extract yosemite.tar.xz to Downloads folder
 
 - Right-click yosemite folder and select "open in terminal"
 
 
Copy theme folders to backgrounds and change permissions to root
 
 - sudo cp -r yosemite /usr/share/backgrounds/
 
 - sudo chown -R root:root yosemite
 
 - sudo chmod -R 755 yosemite
 
 
Copy yosemite-wallpapers.xml to gnome-background-properties and change permissions

 - sudo cp yosemite-wallpapers.xml /usr/share/gnome-background-properties/
 
 - sudo chown -R root:root yosemite-wallpapers.xml
 
 - sudo chmod -R 755 yosemite-wallpapers.xml 

 
To set new wallpaper, use Settings -> Background or right-click desktop "Change Background..."

<img width="1920" height="1080" alt="Screenshot" src="https://github.com/user-attachments/assets/fd7a9b48-89de-49e1-a6fd-018ac6d7d9b0" />


# Troubleshooting:

 - If new wallpaper is not showing, or shows blank screen, check permissions
 
 - Check folder spelling and location
 
 - You may need to log out and back in


# Uninstall:

 - Open terminal and run following commands
 
 - sudo rm -r /usr/share/backgrounds/yosemite
 
 - sudo rm -r /usr/share/gnome-background-properties/yosemite-backgrounds.xml


# Extras

Looks great with WaterCoolerXT Theme:

WaterCoolerXT Theme here: <a href="https://github.com/therobcox/WaterCoolerXT">https://github.com/therobcox/WaterCoolerXT</a>

WaterCooler Icon Theme here: <a href="https://github.com/therobcox/WaterCooler-Icons">https://github.com/therobcox/WaterCooler-Icons</a>


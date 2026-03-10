Yosemite Dynamic Wallpapers by robcox
________________________________________

To install, copy files to the system backgrounds folder using root privileges

 - Extract Yosemite.tar.xz to Downloads folder
 
 - Right-click Yosemite folder and select "open in terminal"
 
 
Copy theme folders to backgrounds and change permissions to root
 
 - sudo cp -r yosemite /usr/share/backgrounds/
 
 - sudo chown -R root:root yosemite
 
 - sudo chmod -R 755 yosemite
 
 
Copy yosemite-wallpapers.xml to gnome-background-properties and change permissions

 - sudo cp yosemite-wallpapers.xml /usr/share/gnome-background-properties/
 
 - sudo chown -R root:root yosemite-wallpapers.xml
 
 - sudo chmod -R 755 yosemite-wallpapers.xml 

 
To set new wallpaper, use Settings -> Background or right-click desktop "Change Background..."


Troubleshooting:

 - If new wallpaper is not showing, or shows blank screen, check permissions
 
 - Check folder spelling and location
 
 - You may need to log out and back in
 
 
Uninstall:

 - Open terminal and run following commands
 
 - sudo rm -r /usr/share/backgrounds/yosemite
 
 - sudo rm -r /usr/share/gnome-background-properties/yosemite-backgrounds.xml
 
 Enjoy!!
 

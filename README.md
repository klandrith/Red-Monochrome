# Red-Monochrome

![Preview](https://github.com/klandrith/Red-Monochrome/blob/main/preview.png?raw=true)

A Red/Black/Monochrome theme for KDE<br/>
Theme is not in a finished state...<br/>
<br/>
## Installation/Configuration

To use items in their state as-is...<br/>
Install Monochrome look-and-feel for KDE: https://gitlab.com/pwyde/monochrome-kde<br/>
Follow instructions on that page (with the exception of GTK theme).<br/>
<br/>

#### GTK 2/3 Theme
Install GTK theme (Red-Monochrome folder) into /usr/share/themes/<br/>
**GTK Theme MUST go into system wide folder!**
<br/>
<br/>

#### Aurorae
Place aurorae themes (Red-Monochrome/Red-MonochromeBlur folders) into<br/>
~/.local/share/aurorae/themes/<br/>
<br/>

#### Kvantum
Install Kvantum and Kvantum Manager for Kvantum theme support...<br/>
Place Monochrome Kvantum theme folder somewhere in your home directory,<br/>
Open Kvantum Manager and add the directory to each individual theme;<br/>
Monochrome, MonochromeBlur, MonochromeSolid. Install the themes.<br/>
Select that Kvantum theme that you wish to use (I am using Monochrome).<br/>
Ensure that under KDE System Settings/Application Style that<br/>
'kvantum' is selected.<br/>
<br/>

#### Color scheme
Place color-scheme file into ~/.local/share/color-schemes/<br/>
<br/>

#### Icons
Place icons theme (Sardi-Flexible-Red-Black-Tron folder) into<br/>
~/.local/share/icons/<br/>
<br/>

#### Konsole
Place konsole color scheme file in ~/.local/share/konsole/<br/>
<br/>

#### Plasma theme
Place plasma theme (Red-Monochrome folder) into<br/>
~/.local/share/plasma/desktoptheme/<br/>
<br/>

#### Latte-dock
For Latte-dock you will need the following widgets:<br/>
  * Event Calendar<br/>
  * Media Player +<br/>
  * Latte separator<br/>

Simply import the latte dock layout file and select it...<br/>
<br/>
I am also using the TodoList plasma widget for on my desktop:<br/>
https://store.kde.org/p/1152230<br/>
<br/>

#### Spicetify
In order to theme Spotify, you need spicetify-cli: https://github.com/khanhas/spicetify-cli<br/>
Once it is installed, place the theme folder (Red-Black-Monochrome) into<br/>
~/.config/spicetify/Themes/ <br/>

Change your config.ini (~/config/spicetify/config.ini) so that...<br/>
  * current_theme           = Red-Black-Monochrome <br/>

Run spicetify update<br/>
Run spicetify apply<br/>
<br/>

#### XAVA
XAVA can be downloaded here: https://github.com/nikp123/xava<br/>
Place XAVA config file in ~/.config/xava<br/>
Launch XAVA, place the window where you want it and size it<br/>
accordingly. Click the window menu icon, go to<br/>
More Actions/Configure Special Application Settings<br/>
Add the following properties:<br/>
  * Position (Force) <br/>
  * Size (Force) <br/>
  * Keep Below (Force - yes) <br/>
  * Skip taskbar (Force - yes) <br/>
  * Skip pager (Force - yes) <br/>
  * Skip switcher (Force - yes) <br/>
  * No titlebar and frame (Frame - yes) <br/>
  * Focus stealing prevention (Force - Extreme) <br/>
  * Accept Focus (Force - no) <br/>
  * Set window type (Force - Normal Window) <br/>

Add XAVA to your startup applications<br/>
<br/>

#### Parachute
Parachute can be downloaded here: https://github.com/tcorreabr/Parachute<br/>
Place parachute.desktop file in /usr/share/applications/<br/>
Add shortcut to dock...<br/>  
To enable screen-edge support for Parachute, download ToggleParachute<br/>
https://store.kde.org/p/1372470<br/>
<br/>

#### Conky
For conky run install-conky.sh<br/>
<br/>
Parameters in the conky.conf file may need adjusting for your particular setup...<br/>
Conky will display either 'Ethernet' or 'Wifi' depending on the connection that<br/>
is detected. You may need to change the wireless and ethernet adapter names in<br/>
conky.conf file. In addition, if you are using an Nvidia GPU that supports fan<br/>
RPM reading, you will need to change that field as well. My GT 1030 for my host<br/>
does not support that, so I had to do some math to calculate RPM. CPU model<br/>
tag may or may not display correctly depending on how the output of hwinfo is<br/>
formatted for your CPU.<br/>
<br/>

#### Todo
  * Icon pack needs to be finished <br/>
  * Make an SDDM theme <br/>
  * Finalize color scheme <br/>
  * Match Kvantum color scheme to Plasma color scheme <br/>
  * Implement a Look-and-Feel theme pack <br/>
  * Make an install script<br/>
<br/>

## Acknowledgments
*Much credit goes to the original authors of the base components that*<br/>
*made this theme possible.*<br/>
Licenses, when provided, for individual components<br/>
are viewable in each subdirectory of the components.<br/>
<br/>
Original Monochrome Theme: https://gitlab.com/pwyde/monochrome-kde<br/>
Original Monochrome Theme Author: Patrik Wyde<br/>
<br/>
Original Sardi Icon Pack: https://github.com/erikdubois/Sardi-Extra<br/>
Original Sardi Icon Pack Author: Erik Dubois<br/>
<br/>
Original Conky Theme: https://github.com/erikdubois/Aureola<br/>
Original Conky Theme Author: Erik Dubois<br/>

# Red-Monochrome

![alt text](https://github.com/klandrith/Red-Monochrome/blob/main/preview.png?raw=true)

A Red/Black/Monochrome for KDE
Theme is not in a finished state...


To use items in their state as-is...
Install Monochrome look-and-feel for KDE: https://gitlab.com/pwyde/monochrome-kde
Follow instructions on that page (with the exception of GTK theme).


Install GTK theme (Red-Monochrome folder) into /usr/share/themes/
*GTK Theme MUST go into system wide folder!*


Place aurorae themes (Red-Monochrome/Red-MonochromeBlur folders) into
~/.local/share/aurorae/themes/


Place color-scheme file into ~/.local/share/color-schemes/


Place icons theme (Sardi-Flexible-Red-Black-Tron folder) into
~/.local/share/icons/


Place konsole color scheme file in ~/.local/share/konsole/


Place plasma theme (Red-Monochrome folder) into
~/.local/share/plasma/desktoptheme/


For Latte-dock you will need the following widgets:
  Event Calendar
  Media Player +

Simply import the latte dock layout file and select it...


I am also using the TodoList plasma widget: https://store.kde.org/p/1152230


In order to theme Spotify, you need spicetify-cli: https://github.com/khanhas/spicetify-cli
Once it is installed, place the theme folder (Red-Black-Monochrome)
into ~/.config/spicetify/Themes/
Change your config.in (~/config/spicetify/config.ini) so that...
current_theme           = Red-Black-Monochrome

Run spicetify update
Run spicetify apply


XAVA can be downloaded here: https://github.com/nikp123/xava
Place XAVA config file in ~/.config/xava
Launch XAVA, place the window where you want it and size it
accordingly. Click the window menu icon, go to
More Actions/Configure Special Application Settings
Add the following properties:
  Position (Force)
  Size (Force)
  Keep Below (Force - yes)
  Skip taskbar (Force - yes)
  Skip pager (Force - yes)
  Skip switcher (Force - yes)
  No titlebar and frame (Frame - yes)
  Focus stealing prevention (Force - Extreme)
  Accept Focus (Force - no)
  Set window type (Force - Normal Window)
Add XAVA to your startup applications


Parachute can be downloaded here: https://github.com/tcorreabr/Parachute
Place parachute.desktop file in /usr/share/applications/
Add shortcut to dock...
To enable screen-edge support for Parachute, download ToggleParachute
https://store.kde.org/p/1372470


For conky run install-conky.sh (Parameters in the conky.conf file may need
adjusting for your particular setup...)


Todo:

  Icon pack needs to be finished
  Finalize color scheme
  Implement a Look-and-Feel theme pack

Original Monochrome Theme: https://gitlab.com/pwyde/monochrome-kde
Original Monochrome Theme Author: Patrik Wyde

Original Sardi Icon Pack: https://github.com/erikdubois/Sardi-Extra
Original Sardi Icon Pack Author: Erik Dubois
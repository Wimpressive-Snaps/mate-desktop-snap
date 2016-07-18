# MATE Desktop snaps

This project attempts to create a working snap of the complete MATE
Desktop environment. The initial objective is to create a MATE runtime
snap and then add snaps for the various MATE suite of applications
that consume the runtime.

## Current state

The components are listed in build order.

### Core

  * mate-common                 [ mate-runtime ]
  * mate-desktop                [ mate-runtime ]
  * mate-user-guide             [ mate-runtime ]
  * libmatekbd                  [ mate-runtime ]
  * libmatemixer                [ mate-runtime ]
  * libmateweather              [ mate-runtime ]
  * mate-icon-theme             [ mate-artwork ]
  * caja                        [ mate-runtime ]
  * mate-polkit                 [ mate-runtime ]
  * marco               
  * mate-settings-daemon
  * mate-session-manager
  * mate-menus
  * mate-panel
  * mate-backgrounds            [ mate-artwork ]
  * mate-themes                 [ mate-artwork ] 
  * mate-notification-daemon
  * mate-control-center
  * mate-screensaver
  * mate-media
  * mate-power-manager
  * mate-system-monitor

### Extra

  * atril
  * caja-dropbox
  * caja-extensions
  * engrampa
  * eom
  * mate-applets
  * mate-icon-theme-faenza      [ mate-artwork ]
  * mate-indicator-applet
  * mate-netbook
  * mate-sensors-applet
  * mate-terminal
  * mate-user-share
  * mate-utils
  * mozo
  * pluma
  * python-caja

## FTBFS

### libmatekbd

Can't find `libmatedesktop-2.0`, complete error message will be added here in 
due course.
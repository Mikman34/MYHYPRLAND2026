INSTALLED APPS:

Bar & Desktop
----------------------------------------------------
waybar — status bar with Catppuccin Mocha theme
hyprland — your Wayland compositor/WM

Launchers & Menus
----------------------------------------------------
wofi — app launcher (rofi alternative)
wlogout / wofipowermenu.sh — power menu

Terminal & Shell
----------------------------------------------------
kitty — terminal emulator
fastfetch — system info on launch

Notifications
----------------------------------------------------
dunst — notification daemon

Audio
----------------------------------------------------
pipewire + wireplumber + pipewire-pulse — audio stack
pavucontrol — GUI audio mixer

Bluetooth
----------------------------------------------------
bluez + bluez-utils — bluetooth stack
blueman — GUI bluetooth manager

Fonts
----------------------------------------------------
JetBrainsMono Nerd Font — used across everything

Network
----------------------------------------------------
nm-connection-editor — network manager GUI (for waybar click)


Screenhot tools:
----------------------------------------------------
grim — takes the actual screenshot on Wayland

slurp — lets you select a region on screen with your mouse

swappy — opens the screenshot for editing, annotating, saving or copying to clipboard

jq — parses JSON output from hyprctl to get the active window position/size (needed for the window screenshot mode)

cliphist 

wl-clipboard

The update file
----------------------------------------------------
sudo vim /usr/local/bin/update
sudo chmod +x /usr/local/bin/update
Then just run update instead of sudo pacman -Syu!

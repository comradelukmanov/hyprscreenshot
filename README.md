Hyprscreenshot is simple bash script for Hyprland window manager for making shots of window or workspace and save it to clipboard.
The script is using grim, jq, wl-clipboard and hyprland obviously.

Keyboard shortcuts are not added to hyrpland config by installing package. 
You can add following lines to your hyprland config:
```
bind = $mainMod, Print, exec, hyprscreenshot window &
bind = ,Print, exec, hyprscreenshot workspace &
```
For more info read official hyprland wiki: https://wiki.hyprland.org/Configuring/Binds/

After installation via pacman, the executable script is saved in /usr/local/bin.

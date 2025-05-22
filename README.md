## Dependencies:
[Noto Nerd Font](https://www.nerdfonts.com/font-downloads)\
[Colloid-Dark-Catppuccin GTK theme](https://github.com/vinceliuice/Colloid-gtk-theme)\
[candy-icons-master GTK icons](https://github.com/EliverLara/candy-icons)\
[Kanata](https://github.com/jtroo/kanata/blob/main/docs/setup-linux.md)
#### Packages:
```
git sway swaybg sway-notification-center xdg-desktop-portal-wlr kitty thunar thunar-archive-plugin mousepad gvfs-backends xwayland rofi grim slurp grimshot stow imv pulseaudio-utils pulseaudio pulseaudio-module-bluetooth libspa-0.2-bluetooth blueman pavucontrol extrepo
```
Enable `librewolf` repository in extrepo and install the package `librewolf` from there

## Installation
After installing all of those packages, clone this repository and cd into it:
```
git clone https://github/com/HydratedBean/dotfiles.git
cd dotfiles
```
Once you are in the directory, type in `stow .` to complete installation\
You may need to restart your session for everything to take effect by logging out and back in:\
Press Super+Shift+E to exit sway, then sign out by typing `exit` in the TTY terminal

## Basic Usage
The `capslock` key has its functionality replaced to be a duplicate `super` key\
File Explorer: `Super+F1`\
Librewolf Browser: `Super+F2`\
Terminal: `Super+Enter`\
Toggle Fullscreen: `Super+F`\
Switch Workspaces: `Super+Numbers`\
Move windows: `Super+Shift+Arrow Keys or Vim keys`\
Poweroff: `Super+Shift+Delete`
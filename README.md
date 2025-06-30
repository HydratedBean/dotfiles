# HydratedBean's swaywm dotfiles
![demo1](demo1.png)
![demo2](demo2.png)
## Installation
```
git clone https://github/com/HydratedBean/dotfiles.git
cd dotfiles
sudo sh ./install.sh
rm -rm ~/.bashrc
stow .
```
Install [Kanata](https://github.com/jtroo/kanata/blob/main/docs/setup-linux.md)\
You might need to set the GTK theme in lxappearance
\
Getting nmtui to work:
```
sudo apt install network-manager
sudo nmcli device set wlp2s0 managed yes
sudo rm -rf /etc/network/interfaces
reboot
```

### Basic Usage
The `capslock` key has its functionality replaced to be a duplicate `Super` key\
File Explorer: `Super+F1`\
Librewolf Browser: `Super+F2`\
Terminal: `Super+Enter`\
Toggle Fullscreen: `Super+F`\
Switch Workspaces: `Super+Numbers`\
Move windows: `Super+Shift+Arrow Keys or Vim keys`\
Poweroff: `Super+Shift+Delete`
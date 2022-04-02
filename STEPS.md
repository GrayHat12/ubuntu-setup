### Install chrome (optional)
* Download .deb package
* `sudo dpkg -i chrome.deb`
  
### Install neofetch
* `sudo apt-get install neofetch`

### Install variety
* `sudo apt-get install variety`

### Install Gnome Shell Extensions
* `sudo apt-get install gnome-shell-extension-prefs`
  #### Install Gnome Extension Brower Extension
  * [https://extensions.gnome.org/](https://extensions.gnome.org/)
  #### Install ArcMenu
  * [https://extensions.gnome.org/extension/3628/arcmenu](https://extensions.gnome.org/extension/3628/arcmenu)
  #### Install NetSpeed
  * [https://extensions.gnome.org/extension/104/netspeed](https://extensions.gnome.org/extension/104/netspeed)
  #### Install User Themes
  * [https://extensions.gnome.org/extension/19/user-themes](https://extensions.gnome.org/extension/19/user-themes)
  #### Install Dash To Panel
  * [https://extensions.gnome.org/extension/1160/dash-to-panel](https://extensions.gnome.org/extension/1160/dash-to-panel)

### Install zsh
* `sudo apt-get install zsh`

### Install git
* `sudo apt-get install git`

### Install oh-my-zsh
* `sudo sh -c "$(wget https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh -O -)"`

### Install vscode
  * [Steps](https://code.visualstudio.com/docs/setup/linux)

### Install gnome-tweaks
* `sudo apt-get install gnome-tweaks`

### Install Mouse Gestures (touchegg+flatpak)
* `sudo add-apt-repository ppa:touchegg/stable`
* `sudo apt-get install touchegg`
* `systemctl status touchegg.service` (verify it's running)
* (if not), `systemctl start touchegg.service`
* `sudo apt-get install flatpak`
* `flatpak install https://dl.flathub.org/repo/appstream/com.github.joseexposito.touchegg.flatpakref`
* `restart`

### Install Spotify
* `sudo snap install spotify`
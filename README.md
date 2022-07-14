### Archlinux-setup
1. install Archlinux >  
```bash 
archinstall 
``` 
2. install Git > 
```bash 
sudo pacman -S git 
``` 
My dot-Config File > 
```bash
git clone https://github.com/Komi7/Archlinux-dotfiles.git
```
3. Packages install >
```bash 
sudo pacman -S --needed - < packages.sh
``` 
* [picom]
```bash
git clone https://aur.archlinux.org/picom-git.git
```
### What is Sddm?
The Simple Desktop Display Manager (SDDM) is a display manager.

4. config Sddm >
```bash 
sudo systemctl enable sddm 
``` 
5. Awesome theme Config  >
###Installation
```bash
mkdir .config/awesome

git clone --recurse-submodules --remote-submodules --depth 1 -j 2 https://github.com/lcpz/awesome-copycats.git

mv -bv awesome-copycats/{*,.[^.]*} ~/.config/awesome; rm -rf awesome-copycats
```

**NOTE!** These were made for my computer specifications. So use it at your own risk! 

**Aesthetic-Night gtk theme**
```bash
cd ~/Download/Archlinux-dotfiles
unzip themes.zip
```

Setup:
1. Copy the themes to the themes folders
```bash
sudo cp -rf themes/Aesthetic-Night/* /usr/share/themes

cp -rf themes/Aesthetic-Night-GTK4/* ~/.config/gtk-3.0
```
2. Add this line on [~/.config/gtk-3.0/settings.ini] for left controls
```bash
gtk-decoration-layout=close,maximize,minimize:menu
```

☄️ ‎ Aesthetic VSCode setup:

1.Install required extension

•
<a href="https://marketplace.visualstudio.com/items?itemName=iocave.customize-ui">Customize UI</a>

•
<a href="https://marketplace.visualstudio.com/items?itemName=antfu.icons-carbon">Carbon Product Icons</a>

2.copy config file
```bash
cp misc/vscode/User/settings.json ~/.config/Code/User
```
  
***modify ongoing ! ...........🤞***

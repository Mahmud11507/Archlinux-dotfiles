### Archlinux-setup
#1. install Archlinux >  
```bash 
archinstall 
``` 
#2. install Git > 
```bash 
sudo pacman -S git 
``` 
My dot-Config File > 
```bash
git clone https://github.com/Komi7/Archlinux-setup.git
```
#3. Packages install >
```bash 
sudo pacman -S --needed - < packages.sh
``` 
* [picom]
```bash
git clone https://github.com/pijulius/picom)
```
### What is Sddm?
The Simple Desktop Display Manager (SDDM) is a display manager.
#4. config Sddm >
```bash 
sudo systemctl enable sddm 
``` 
#5. Awesome theme Config  >
###Installation
```bash
git clone --recurse-submodules --remote-submodules --depth 1 -j 2 https://github.com/lcpz/awesome-copycats.git

mv -bv awesome-copycats/{*,.[^.]*} ~/.config/awesome; rm -rf awesome-copycats
```

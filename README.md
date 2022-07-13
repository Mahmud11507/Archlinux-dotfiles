## Archlinux-setup
#1. install Archlinux >  
```bash 
archinstall 
``` 
#2. install Git > 
```bash 
sudo pacman -S git 
``` 
Next > git clone https://github.com/Komi7/Archlinux-setup.git

#3. Packages install >
```bash 
sudo pacman -S --needed - < packages.sh
``` 
#4. config Sddm > 
```bash 
sudo systemctl enable sddm 
``` 

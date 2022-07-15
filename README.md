### Archlinux-setup
1. install Archlinux >  
```bash 
archinstall 
``` 
2. install Awesome,Sddm ,Git > 
```bash 
sudo pacman -S awesome sddm git
``` 
### What is Sddm?
The Simple Desktop Display Manager (SDDM) is a display manager.

3. config Sddm >
```bash 
sudo systemctl enable sddm 
``` 
**than reboot

4. clone dot-Config File > 
```bash
git clone https://github.com/Komi7/Archlinux-dotfiles.git
```
5. Packages install >
```bash 
sudo pacman -S --needed - < packages.sh
``` 
* [picom]
```bash
git clone https://aur.archlinux.org/picom-git.git
```



6. Awesome theme Config  >
###Installation
```bash
mkdir .config/awesome

git clone --recurse-submodules --remote-submodules --depth 1 -j 2 https://github.com/lcpz/awesome-copycats.git

mv -bv awesome-copycats/{*,.[^.]*} ~/.config/awesome; rm -rf awesome-copycats
```

**NOTE!** These were made for my computer specifications. So use it at your own risk! 

7.Aesthetic-Night gtk theme setup:
1. go to Archlinux-dotfiles download location & unzip theme zip file
```bash
cd ~/Download/Archlinux-dotfiles
unzip themes.zip
```

2. Copy the themes to the themes folders
```bash
sudo cp -rf themes/Aesthetic-Night/* /usr/share/themes

cp -rf themes/Aesthetic-Night-GTK4/* ~/.config/gtk-3.0
```
3. Add this line on ``` ~/.config/gtk-3.0/settings.ini ``` for left controls
```bash
gtk-decoration-layout=close,maximize,minimize:menu
```

8.Aesthetic VSCode setup ☄️:


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


<h1 align="center">Hi , I'm Shousuke Komi <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="35"></h1>
<p align="center">
 <h1 align="center"> <p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?multiline=true&lines=Linux+user+,+Learning+coding">
  </h1>
</p>


<div align="center">

  <img  src="https://github.com/1999AZZAR/1999AZZAR/blob/main/resources/img/grid-snake.svg"
       alt="snake" /></a>
</div>

<details>
  <summary>☎️ contact me</summary>
<div>
  <samp>
    <h2 align="center">😎 you can reach me by:</h2>
    <p align="center">
      <br/>
      <a href="https://t.me/mahmud11507" target="blank"><img align="center"
         src="https://img.shields.io/badge/-Telegram-brightgreen"
         alt="azzar" height="30"/></a>
     
     <p align="center">
      <br/>
      <a href="https://discord.com/channels/@me/724963674477035561" target="blank"><img align="center"
         src="https://img.shields.io/badge/-Telegram-brightgreen"
         alt="azzar" height="30"/></a>

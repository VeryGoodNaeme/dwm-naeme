# dwm-naeme

Dependencies: Rofi, Alacritty, Flameshot, Ranger

Installation without gaps
```bash
git clone https://github.com/verygoodnaeme/dwm-naeme
cd dwm-naeme/generic/no-gaps
sudo make install
```
Installation with gaps  
```bash
git clone https://github.com/verygoodnaeme/dwm-naeme
cd dwm-naeme/generic/gaps
sudo make install
```

If you use a display manager add the following to /usr/share/xsessions/dwm.desktop
```bash
[Desktop Entry]
Encoding=UTF-8
Name=Dwm
Comment=Dynamic window manager
Exec=dwm
Icon=dwm
Type=XSession
```
Patches included:  
https://dwm.suckless.org/patches/autostart/  
https://dwm.suckless.org/patches/dynamicscratchpads/  
https://dwm.suckless.org/patches/statusallmons/  
https://dwm.suckless.org/patches/alwayscenter/  
A modified version of https://dwm.suckless.org/patches/uselessgap/ to add gaps and borders with only one window

Color scheme:  
https://ethanschoonover.com/solarized/

## Downloads-Necess-rios-Install-Ubuntu-for-android
Aqui você encontra os comandos para instalar o Ubuntu no termux

![imagem](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRy8qN746FA-lBoJS_GqB0cKwimfxpCirxcdw&usqp=CAU)
### Pré Requisitos 
_Termux_ [Download](https://f-droid.org/en/packages/com.termux/)🖱️

_VNC Viewer_ [Download](https://m.apkpure.com/br/vnc-viewer-remote-desktop/com.realvnc.viewer.android/amp)🖲️



## Comandos 👨‍💻

- pkg update -y ; pkg install proot-distro
- proot-distro install ubuntu
- apt update ; apt install sudo nano
- export USER=<Seu nome de usuário> ; adduser $USER ; echo "$USER ALL=(ALL:ALL) ALL" >> /etc/sudoers
- su <Seu nome de usuário> 
## GUI Interface Gráfica 🖥️
- sudo apt install xfce4 xfce4-terminal xfce4-whiskermenu-plugin


- Temas na GUI 🎨: sudo apt install yaru-theme-gtk yaru-theme-icon plank dbus-x11 tigervnc-standalone-server 
              
- echo "vncserver -geometry 1280x720 -xstartup /usr/bin/startxfce4" >> /usr/local/bin/vncstart ; echo "vncserver -kill :1" >> /usr/local/bin/vncstop ; chmod +x /usr/local/bin/vncst* 

                    

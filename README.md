# Power-SDR
A Desktop Raspberry Pi OS for OpenWebRX Plus ,base on OpenWebRX Plus IMG, add Desktop, Rustdesk, VNCServer, SVXLink Service .

Project homepage and Users guide
https://github.com/JTA-STAR/Power-SDR

Subscribe for updates, feedback on issues:
https://j-star.groups.io/g/Power-SDR/

Recommend device:
Raspberry Pi 4B2G, 4B4G,  3B 3A ZW performance is relatively poor (not support 5B yet)
8G/16G C10+ TF/SD card

Base on: hhttps://github.com/luarvique/openwebrx (OpenWebRX+ 1.2.49 Image for Raspberry Pi 4, sudo install-softmbe.sh)

Additional integration with the following projects:

SDR++  https://github.com/AlexandreRouma/SDRPlusPlus.git
SvxLink https://github.com/sm0svx/svxlink
ZR6LSD's Automatic SvxLink Installation Script (Echolink) https://github.com/ZR6LSD/SvxLink
SVXLink-Dash https://github.com/f5vmr/SVXLink-Dash-V2
RustDesk: https://github.com/rustdesk/rustdesk/releases (build your private remote desktop server)
All-in-box: Webssh simulator
RealVNC:  https://www.realvnc.com/en/connect/download/combined/

Flash SD card: see this https://www.bi7jta.org/wiki/index.php?title=Main_Page#Flash_Pi-Star_OS

Setup WiFi：use Windows Notepad edit [wpa_supplicant.conf] , then copy to SD card.

Hostname in your router manager show: 
openwebrxplus

IP Address:
Your_DHCP_assigned_addresss, such as 192.168.0.0

Visit: 
http://192.168.192.168.0.0
Manager page login (admin/admin)

webSSH: 
http://192.168.0.0:4200

SVXlink:
http://192.168.0.0:8888

VNC: RealVNC client app, for macOS , windows

Remote desktop control : Rustdesk client

Login : j-star/raspberry
Modify root password: sudo passwd root 

VY 73 BI7JTA

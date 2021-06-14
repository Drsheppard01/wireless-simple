# Tomomi <img src="http://pngimg.com/uploads/wifi/wifi_PNG62297.png" alt="Homura" height="40" width="60"> 
[![Discord](https://img.shields.io/badge/chat-on%20discord-7289da.svg?logo=discord)](https://discord.gg/JBKcdNt) <img src="https://img.shields.io/discord/618845118060953600">


Should you have a problem during installation or general with the driver then let me know :)

Please know that this will be not 100% maintained, if you have suggestions for improvement please send a pull request.

# Features &#x1F4D8;

- The driver will be installed automatically with all required dependencies.

# Dependencies :syringe:

- zenity

# Supported distributions :computer:

- Arch
- Solus
- Ubuntu
- Sabayon
- OpenSUSE


# Supported realtek wifi drivers :wrench:

- RTL8812au by [gordboy](https://github.com/gordboy/rtl8812au-5.9.3.2)
- RTL8188eu, RTL8188eus & RTL8188etv by [quckreflex](https://github.com/quickreflex/rtl8188eus)
- RTL8821ce by [tomaspinho](https://github.com/tomaspinho/rtl8821ce)
- RTL8723de by [smlinux](https://github.com/smlinux/rtl8723de)
- RTL8188fu by [kelebek333](https://github.com/kelebek333/rtl8188fu)
- RTL88x2bu by [cilynx](https://github.com/cilynx/rtl88x2BU_WiFi_linux_v5.3.1_27678.20180430_COEX20180427-5959)

Note: If your desired driver is not there or does not work please open an issue.

# Supported wifi adapters

- Tenda U12 (AC1300)
- 


# Preparations :clipboard:
Before you start installing the WiFi driver, make sure you have all the updates installed. If you have previously installed a kernel update, restart your computer to avoid errors during installation.

# Installation/Uninstallation :cd:

To start this installer use the follwing command:

```
bash Tomomi.sh
```

## See how this works! :eyes:

<a href="https://www.youtube.com/watch?v=hGLh3bI8WLg"><img src="https://www.bilder-upload.eu/upload/7f26bd-1557222110.jpg" style="width:82px; height:86px" title="Video" alt="Video"></a>

# FAQ :speech_balloon:

- Why i have package loss or bad ms? for example like [this](https://hastebin.com/ebusamonev.coffeescript)

If you encounter this error, try another USB port first. If this is not enough, adjust your antennas if you have them on your adapter. For testing, a ping request is sufficient to routher via a terminal with the command  "ping 192.168.2.1 ". The IP address could be different for your routher. And make sure before that all programs are closed and no one else just overloaded the network. 

- Why does my device suddenly stop working after an update?

This happens when the linux kernel was updated. The only solution is to reinstall the driver again.

## Contribute :pencil2:
if you want to contribute to this repo then just send a pull request.

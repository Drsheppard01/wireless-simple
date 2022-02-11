# Tomomi <img src="http://pngimg.com/uploads/wifi/wifi_PNG62297.png" alt="Homura" height="40" width="60"> 

# Features &#x1F4D8;

- The driver will be installed automatically with all required dependencies.

# Dependencies :syringe:

- zenity

# Supported distributions :computer:

- Arch
- OpenSUSE
- Fedora (experimental, need more tests)
- Sabayon
- Solus
- Ubuntu


# Supported realtek wifi drivers :wrench:

- RTL8812au by [morrownr](https://github.com/morrownr/8812au-20210629)
- RTL8188eu, RTL8188eus & RTL8188etv by [quckreflex](https://github.com/quickreflex/rtl8188eus)
- RTL8821ce by [tomaspinho](https://github.com/tomaspinho/rtl8821ce)
- RTL8723de by [smlinux](https://github.com/smlinux/rtl8723de)
- RTL8188fu by [kelebek333](https://github.com/kelebek333/rtl8188fu)
- RTL88x2bu by [cilynx](https://github.com/cilynx/rtl88x2BU_WiFi_linux_v5.3.1_27678.20180430_COEX20180427-5959)
- RTL8192eu by [clnhub](https://github.com/clnhub/rtl8192eu-linux)

Note: If your desired driver is not there or does not work please open an issue.

# Preparations :clipboard:
Before you start installing the WiFi driver, make sure you have all the updates installed. If you have previously installed a kernel update, restart your computer to avoid errors during installation.

# Installation/Uninstallation :cd:

To start this installer use the follwing command:

```
bash Tomomi.sh
```

## See how this works! :eyes:

https://youtu.be/hGLh3bI8WLg

# FAQ :speech_balloon:

- Why i have package loss or bad ms? for example like [this](https://hastebin.com/ebusamonev.coffeescript)

If you encounter this error, try another USB port first. If this is not enough, adjust your antennas if you have them on your adapter. For testing, a ping request is sufficient to routher via a terminal with the command  "ping 192.168.2.1 ". The IP address could be different for your routher. And make sure before that all programs are closed and no one else just overloaded the network. 

- Why does my device suddenly stop working after an update?

This happens when the linux kernel was updated. The only solution is to reinstall the driver again.

## Contribute :pencil2:
if you want to contribute to this repo then just send a pull request.

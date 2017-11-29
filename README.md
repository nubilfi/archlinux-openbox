# archlinux-openbox
Archlinux Minimalist Edition.

### Prerequisites

```
$ sudo pacman -Syu
$ sudo pacman -S openbox obconf
$ sudo pacman -S obmenu tint2 clipman nitrogen conky compton terminator 
lxappearance xdotool zenity scrot
$ yaourt -S hsetroot
$ sudo reboot

** Of course you can install other packages.
```

### Installing

First step, download or clone this repository and then copy and paste 
the following steps, don't forget to replace `/path/to` with your actual 
directory:

```
$ sudo cp -R ~/path/to/archlinux-openbox/lib-cb-welcome /usr/bin/lib/
$ sudo cp -R ~/path/to/archlinux-openbox/obscripts/* /usr/bin/ && sudo 
chmod +x /usr/bin/{cb-*,tb-exit}

** make sure you already have a backup default configuration of openbox 
& tint2 before copy and paste the following command, check your 
~/.config directory
$ cp ~/path/to/archlinux-openbox/openbox ~/.config
$ cp ~/path/to/archlinux-openbox/tint2 ~/.config
$ sudo reboot (it's okay)

```

You can now login to openbox by switching it on your display manager. If 
it works, it must be like the following screenshot.
![alt tag](https://i.imgur.com/xoaZPEY.png "Openbox setup")

Please open an issue if you have a trouble.

Inspired from 
[@johnraff](http://crunchbang.org/forums/profile.php?id=353)

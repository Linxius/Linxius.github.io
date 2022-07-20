---
title: xrdp 
---

# Install xrdp 
```sudo apt-get install xrdp ```

# Issues
## connection problem, giving up, some problem... [[ref]](https://c-nergy.be/blog/?p=13390)
```sudo apt-get install xorgxrdp```

maybe optional:
```bash
sudo apt-get install xserver-xorg-core
sudo apt-get -y install xserver-xorg-input-all
```

## Authentication is required to create a color profile [[ref]](https://unix.stackexchange.com/questions/417906/authentication-is-required-to-create-a-color-profile)

create file ```/etc/polkit-1/localauthority/50-local.d/color.pkla``` with content bellow:
```bash
[Allow colord for all users]
Identity=unix-user:*
Action=org.freedesktop.color-manager.create-device;org.freedesktop.color-manager.create-profile;org.freedesktop.color-manager.delete-device;org.freedesktop.color-manager.delete-profile;org.freedesktop.color-manager.modify-device;org.freedesktop.color-manager.modify-profile;org.freedesktop.packagekit.system-sources-refresh
ResultAny=yes
ResultInactive=yes
ResultActive=yes
```

## XRDP disconnects immediately after loggin in [[ref]](https://askubuntu.com/questions/1308551/xrdp-disconnects-immediately-after-correct-credentials)

This could be due to the fact that are already logged in into your Ubuntu and you are trying to use the same user account to make your remote desktop connection.

or used xfce4 instead:
```bash
sudo apt install xfce4
#and then to switch to it:
sudo update-alternatives --config x-session-manager 
```
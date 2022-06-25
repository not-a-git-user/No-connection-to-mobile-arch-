# No-connection-to-mobile-in-arch
Instructions on what to do if arch does not connects to mobile using usb 

Error:  Arch not connecting to mobile for file transfer, instead assumes the mobile to be a media player.

Fix:

1.Install the following pakages 

```
sudo pacman -Syu mtpfs gvfs-mtp gvfs-gphoto2
```

2.Install the following package from AUR, any other AUR handler can also be used 

```
yay jmtpfs
```


 

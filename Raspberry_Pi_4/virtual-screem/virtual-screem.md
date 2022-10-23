# Ubuntu on Raspberry Pi 4虚拟显示器

> https://help.realvnc.com/hc/en-us/articles/360004324217-Beginner-s-guide-to-Virtual-Mode#what-is-virtual-mode--0-0

```bash
sudo apt install xserver-xorg-video-dummy
sudo vncinitconfig --enable-system-xorg
```

> https://bbs.archlinux.org/viewtopic.php?id=258936

`sudo nano .vnc/xstartup`

```bash
export XDG_SESSION_TYPE=x11
export GDK_BACKEND=x11
exec dbus-launch gnome-session
```



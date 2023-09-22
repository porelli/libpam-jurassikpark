libpam-jurassikpark
===================

PAM module that show a video like in Jurassik Park film after three failed logins


Limitations
--------
Wayland is not supported (yet)

Building
--------

```
$ sudo apt install devscripts
$ cd src
$ tar cvzf ../libpam-jurassikpark_0.1.orig.tar.gz usr Makefile ; debuild -us -uc
```

Installing
--------

```
$ sudo apt install mplayer
$ sudo dpkg -i ../libpam-jurassikpark*.deb
```

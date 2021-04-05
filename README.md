# linux-discord-libappindicator1-dependencies
Linux Discord Desktop app Dependency

In 2021 has some issue probably a libappindicator1 packages unable to meet dependancies while installing Discord Desktop app in linux[all].

Because as I surfed in internet I found that kali linux has removed libappindicator1 packages officially

Proof :-
source : https://pkg.kali.org/pkg/libappindicator#
[As mentioned in below]  👇

[2021-01-19] libappindicator 0.4.92-8 removed from kali-rolling (Kali Repository)
[2020-12-28] libappindicator 0.4.92-8 removed from kali-dev (Kali Repository)
[2020-04-20] libappindicator 0.4.92-8 imported into kali-rolling (Kali Repository)
[2018-09-12] libappindicator 0.4.92-7 imported into kali-rolling (Kali Repository)
[2018-07-13] libappindicator 0.4.92-6 imported into kali-rolling (Kali Repository)
[2017-09-30] libappindicator 0.4.92-5 imported into kali-rolling (Kali Repository)
[2016-04-15] libappindicator 0.4.92-4 imported into kali-rolling (Kali Repository)
[2015-12-07] libappindicator 0.4.92-3.1 migrated to Kali Safi
[2015-08-27] libappindicator 0.4.92-2 migrated to Kali Moto
[2015-08-11] libappindicator 0.4.92-3.1 migrated to Kali Moto
[2015-07-21] libappindicator 0.4.92-3.1 migrated to Kali Sana
[2014-10-22] libappindicator 0.4.92-3 migrated to Kali Rolling

Due to this we can't install any new desktop app in linux[kali] and I tried many software like Discord, signal and so on.

# Solution to this?

I got some solution for this by installing old packages/ old version of libappindicator1 packages links to download is below 👇

link : http://ftp.br.debian.org/debian/pool/main/liba/libappindicator/libappindicator1_0.4.92-8_amd64.deb

after downloading this libappindicator1_0.4.92-8_amd64.deb packages type "sudo dpkg -i libappindicator1_0.4.92-8_amd64.deb" to install debian packages and see now this issue have been solved.

# some other problems

After installing libappiundicator1 I also faced uninstallable other dependency like libindicator7 and libdbusmenu-gtk4 packages

link to download libindicator7 : http://ftp.br.debian.org/debian/pool/main/libi/libindicator/libindicator7_0.5.0-4_amd64.deb

cmd to download libdbusmenu-gtk4 : sudo apt-get install libdbusmenu-gtk4

After meeting all this dependencies you can able to install Discord desktop app in linux

now run cmd - dpkg -i discord-0.0.13.deb and see the magic boomb!!!!!!!!



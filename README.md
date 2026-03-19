## The year is 2029, you need to verify your face, and your ID to open your fridge.
## The world has gotten crazy. You have to make an account, verify your face, consent to multiple data trackers, to visit a website.

#### This is a guide, that you can use to fight against telemetry.

## Overview

This is a guide/tutorial thats meant for people to see what pros and cons do specific distros have, same thing with kernels, browsers, and its just overall meant to be for people who want to be more private.

## 1. Distributions

*Ubuntu*: Very user-friendly, but not really for privacy. Really good for beginners though.

*Debian*: Fantastic debian-based distro, could definetly be used.

*Arch*: Fantastic, Very good if youre looking to be as private as possible.

*CachyOS*: I personally use this distro, its just like arch, but user-friendly.

*NixOS*: Very good, pretty private, gotta give props to this one.

*Fedora*: Overall not very good, considering not many packages are in the fedora repos, though good distro.

*If youre starting out, choose Debian, Ubuntu, or CachyOS.*

*If youre experienced, use Arch, Fedora, or CachyOS.*

*If you cant pick: choose CachyOS, since for most use-cases its really good.*

## 2. Kernels

*linux*: The regular linux kernel, not really good, but can be used.

*linux-zen*: The zen kernel, its way faster, and pretty private.

*linux-hardened*: The hardened kernel, the best one, and overall a great choice.

*linux-lqx*: Liqourix kernel, the fastest one, and actually the best choice.

*linux-lts*: Long term support kernel, great if you want a kernel that lasts with no breakage, but not really a good choice.

*If youre a beginner: Stick with either linux-zen, or linux-hardened for now.*

*If youre advanced: You should choose linux-lqx, or linux-hardened.*

*If you cant pick, choose linux-hardened.*

## 3. Applications/Tools

[AppArmor](https://www.apparmor.net/) multiple safety features, kind of like windows defender, but for linux, and it runs in the background.

[Privacy Toolkit](https://github.com/cyberflow-academy/Linux-Privacy-Setup-Toolkit) Privacy toolkit, developed by CyberFlow.

[Yet another hardening script](https://github.com/Michael-Sebero/Linux-Hardening-Script?spm=a2ty_o01.29997173.0.0.6c6a5171kyfgoh) hardening script for arch linux.

[Linux hardening repository](https://github.com/hardenedlinux)

[Another hardening script](https://github.com/abbott/hardn?spm=a2ty_o01.29997173.0.0.6c6a5171kyfgoh)

[Linux hardening](https://github.com/trimstray/the-practical-linux-hardening-guide?spm=a2ty_o01.29997173.0.0.6c6a5171kyfgoh)

*Definitely use Apparmor, Privacy toolkit, and if you really want to make sure, you can add another script.*

### 4. Firefox User.js'

[arkenfox](https://github.com/arkenfox/user.js/) For *advanced* users.

[Betterfox](https://github.com/yokoffing/BetterFox) For people that *dont really know how it works.*

[SecureFox](https://github.com/yokoffing/Betterfox/blob/main/Securefox.js) Designed for *literally nothing else but security.*

*If youre still a rookie, you should use Betterfox, since its designed for user-friendliness*

*If you dont like ads, news, and a bunch of bloat on your screen, try arkenfox.*

## 5. Browsers

[Zen Browser](https://zen-browser.app/) Personally, *the best browser right now. (Fork of firefox)*

[Firefox](https://www.firefox.com/en-US/) Honestly, 2nd best one. *And it might seem private, but you need to modify it yourself to be truly secure.*

[Tor Browser](https://www.torproject.org/download/) *The most secure, and protection-based browser of ALL-TIME.* Supports onion links.

[Librewolf](https://librewolf.net/) I have never tried this before, but it has *zero telemetry*, so its a great, secure fork of firefox.

[Brave](https://brave.com/download/) Rather *performance-based and user-friendliness* based browser, but still on this list.

*If youre starting out: choose either firefox, or brave.*

*If youre experienced: Use firefox, zen browser, or librewolf.*

*If you want full and complete privacy: Tor browser has got your back.*

## 6. Securing SSH

Test in a VM first, or keep a console session open (Ctrl+Alt F5)

Backup your config: sudo cp /etc/ssh/sshd_config /etc/ssh/sshd_config.bak

Always verify SSH works after changes: sudo sshd -t (tests config) + sudo systemctl restart sshd

Edit /etc/ssh/sshd_config with the content of this link:

https://0x0.st/P9xl.txt

## Setting everything up

## Manual install (Arch Linux)

First of all, run [This script](https://github.com/Michael-Sebero/Linux-Hardening-Script/blob/master/hardening-script.sh)

Then, you should probably install either arkenfox, or betterfox.

Now, run 'lynis audit system'.

Check if apparmor is installed, with 'aa-status'. If its not a command, then install it, using 'sudo pacman -S apparmor'

Now, harden SSH with step 6.

## Install script

i havent made one yet, will be out soon.

## Overhaul

This is a repo, meant to collect all the linux hardening scripts and guides, and sort of combine them into one.
Even though there are tons of repos out there, that are meant to be for these reasons, and they do the work for you,
and etc. etc., this is meant to be kind of an overhaul of those, and meant to be for people who want to be completely and utterly private.

## Credits

Credits to CyberFlow: He makes cybersecurity videos, and is overall a huge person when it comes to cybersecurity.

Credits to trimstray: Made a similar repo, but way more in-depth, and with multiple more things.

Credits to Yokoffing: For making Betterfox, a version of arkenfox, but for "noobs".

Credits to Arkenfox: A template, that completely and utterly removes bloat, ads, and enhances security overall.

Credits to Michael-Sebero: For making the shell script

Credits to abbott: For making the interactive shell script

Credits to n3o4po11o, Sn0rt, biergaizi, Nalaginrut: For making the hardenedlinux github repo.

And thats about it.

Alright, bye!

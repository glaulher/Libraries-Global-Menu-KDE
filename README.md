# Libreries Global Menu KDE

**What is this?**

These libraries allow you to have a little more compatibility with the global menu of KDE PLASMA, by this I mean ELECTRON applications, VS Code, among others they are not activated in this global menu in some Linux distributions, so in this repository you will find the way to install them.

### Arch Linux and its derivatives

I want to mention right now that all are downloaded from the AUR, so if you do not have yay or pamac, I leave you this link so that you can download them.

<a href="https://www.tecmint.com/install-yay-aur-helper-in-arch-linux-and-manjaro/">**Install YAY**</a>

**General Libraries**

```bash
	# To have compatibility with some programs that use GTK (Nemo, Google Chrome, Chromium, etc)
	$ yay -S appmenu-gtk module

	# For electron global menus (In this case this would be to VS Code Studio, Telegram Desktop..)
	$ yay -S libdbusmenu-glib

	# Support for qt4 apps, if you don't use them, you don't need it
	$ yay -S appmenu-qt4 

```

**32 Bits Libraries**
Something I want to mention right now is that some of these libraries are going to be compiled and their duration may take a little. In case you have knowledge of how to do this you will have no problems.
In my case I have a **CPU: AMD A8-7410 APU (4) @ 2,200GHz** and it took me about **3 hours**

```bash
	$ yay -S lib32-libdbusmenu-glib

	$ yay -S lib32-libdbusmenu-gtk2

	$ yay -S lib32-libdbusmenu-gtk3

```

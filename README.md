# Libreries Global Menu KDE

**What is this?**

These libraries allow you to have a little more compatibility with the global menu of KDE PLASMA, by this I mean ELECTRON applications, VS Code, among others they are not activated in this global menu in some Linux distributions, so in this repository you will find the way to install them.
    <div align="center">
    <h3>
    	<img src="https://github.com/Hblanqueto/Libreries-Global-Menu-KDE/blob/master/Screenshots/01.jpg" align="center" height="500px">
    </h3>
	</div>


## Arch Linux and its derivatives

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

### Attention

This last library may not be installed as it may give you a key error, in that case you must configure your GPG key deposit to try to install it, anything you want to see regarding this library I leave you a link to its repository.**Something I want to mention is that it is very old and has no support as such, its last update was 3 years ago**. 

Link to this repositorie (AUR): https://aur.archlinux.org/packages/lib32-libdbusmenu-qt/

**In case you have no problems downloading, I mention that it will take some time to compile**

```bash
	$ yay -S lib32-libdbusmenu-qt

```

**64 Bits Libraries**

```bash
	$ yay -S libdbusmenu-glib

	$ yay -S libdbusmenu-gtk2

	$ yay -S libdbusmenu-gtk3

```

I want to mention that these last 2 libraries are compiled, so they will take a long time. Still it helps a lot to add some Qt apps to this fabulous global menu
```bash
	$ yay -S libdbusmenu-qt5
	
	$ yay -S libdbusmenu-qt4


```

**Once you have all installed as a recommendation, restart your PC to apply changes and so that the installed applications that need it recognize it.**


## Debian and its derivatives

Here they are less libraries, and some distributions like **KDE NEON** already have them installed so you would only have to install this:

 <div align="center">
    <h3>
    	<img src="https://github.com/Hblanqueto/Libreries-Global-Menu-KDE/blob/master/Screenshots/02.png" align="center" height="420px">
    </h3>
	</div>


```bash
	$ sudo apt-get install appmenu-gtk-module-common
	
	$ sudo apt-get install appmenu-gtk2-module

        $ sudo apt-get install appmenu-gtk3-module

```
## RedHat and its derivatives

**In this case it is not possible to do it, for the simple fact that it does not exist as such. So you could try to compile them. Here is an image and a person who asked this question a long time ago on reddit:**

**Link:** https://www.reddit.com/r/Fedora/comments/d3t5gp/kde_global_menu_for_gtk_fedora_30/

 <div align="center">
    <h3>
    	<img src="https://github.com/Hblanqueto/Libreries-Global-Menu-KDE/blob/master/Screenshots/03.png" align="center">
    </h3>
	</div>

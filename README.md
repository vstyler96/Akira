# ![Akira](akira-logo-transparent.png)
> The Linux Design Tool

**WARNING!!! AKIRA IS CURRENTLY IN PRE-ALPHA, NOT READY FOR PRODUCTION. USE IT AT YOUR OWN RISK!**

Akira is a native Linux Design application built in Vala and GTK. Akira focuses on offering a modern and fast approach to UI and UX Design, mainly targeting web designers and graphic designers.
The main goal is to offer a valid and professional solution for designers who want to use Linux as their main OS.

![](akira-screenshot.png)

## Official Mascot
![](akira-mascot-akari.png)
**Akari the Cyber Phoenix** is a perfectionist. She is tidy, collected and has a sharp eye for detail. Her name Akari (灯理、) means *"the enlightenment of a sophisticated order"*. Her costume resembles the project's icon.

**License**: GNU GPLv3 / Creative Commons BY-SA
Copyright © 2017 Akira Project.

Download the hi-res of Akari [HERE](/mascot/mascot_akira_akari.zip)

Mascot character designed by **Tyson Tan**.
Tyson Tan offers mascot design service for free and open source software, free of charge, under free license.
Contact: [http://tysontan.com](http://tysontan.com)  / [tysontan@mail.com](mailto:tysontan@mail.com)

## Get it from the elementary OS AppCenter!
Akira, is primarly available from the AppCenter for elementary OS. Download it from there!

[![Get it on AppCenter](https://appcenter.elementary.io/badge.svg)](https://appcenter.elementary.io/com.github.alecaddd.akira)

## Install it from source
You can install Akira by compiling it from the source, here's the list of dependecies required:
 - `gtk+-3.0>=3.18`
 - `granite>=0.5.0`
 - `glib-2.0`
 - `gee-0.8`
 - `gobject-2.0`
 - `libxml-2.0`
 - `gtksourceview-3.0`
 - `clutter`
 - `cairo`
 
**For non-elementary distros, (such as Arch, Debian etc) you are required to install "vala" as additional dependency.**

## Building
```
mkdir build/ && cd build
cmake -DCMAKE_INSTALL_PREFIX=/usr ../
make && sudo make install
```

### Donations
If you like Akira and you want to support its development, consider donating via [PayPal](https://www.paypal.me/alecaddd) or pledge on [Patreon](https://www.patreon.com/alecaddd).

---
title: "Setup printing in Arch for HP Printers (USB)"
date: 2023-09-02T20:54:52+05:30
# bookComments: false
# bookSearchExclude: false
---
from @iceman

Learn how to setup printing services on Arch Linux for HP based printers connected via USB

This is mostly for hplip dependent printers, usually there's a package for your printer
either on aur or the official repositories. Check the wiki before you follow this guide. The content
was written well over 2 years ago, as a more of a "note" rather than being a "tutorial/guide".

1. Connect your printer
2. Installing CUPS and other required stuff
```bash
$ pacman -S cups
$ systemctl enable cups
$ systemctl start cups
$ pacman -S hplip
$ hp-setup -i
```

Follow steps and download plugin and it should work. If for some reason it does not work,
note the version number of the plugin it tries to download. Then download the specified 
version of the plugin from [here](https://developers.hp.com/hp-linux-imaging-and-printing/plugins).

Re-run the following:
```bash
hp-setup -i

```

And this time specify the path to file instead of downloading, everything will work fine assuming you have `foomatic-db`, `foomatic-db-engine`, `foomatic-db-nonfree`, `foomatic-db-nonfree-ppds` packages installed.


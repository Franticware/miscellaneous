# Fix for the "WCH-Link not found" issue in MounRiver Studio

Arch Linux does not have the ```plugdev``` group, which causes issues with WCH-Link programmer in MounRiver Studio.

The following message appears when clicking Download:

MounRiver Studio version 2.x.x:

```
Error: WCH-Link not found!
```

MounRiver Studio_Community version v1.x:

```
WCH-Link not found. Please refer to "WCH-LinkUserManual.pdf" for more help.
```

The simplest solution is to replace the existing ```/etc/udev/rules.d/50-wch.rules``` with the one provided in this directory.

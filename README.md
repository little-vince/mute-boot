Mac OSX Bootsound patch
=======================

Overview
--------
This is a patch for removing the boot sound that gets played when you turn on
the computer.

The Patch script will create mute and unmute scripts that get bound to the
logout and login hooks respectively.

Lastly, this program can also re-enable the boot sound. Simple re-run this
patch to restore the original functionality.

Instructions
------------
1. Download the Patch.command file and save it onto your Desktop.
2. Open up Terminal and execute:
```bash
cd ~/Desktop && chmod +x Patch.command
```
3. Finally execute:
```bash
./Patch.command
```

General Information
-------------------
Author: little-vince


Change Log
----------
    2014-11-14
     * Initial release



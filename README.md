LyncToNotification
=========

A SIMBL Plugin of 'Microsoft Lync for mac'.

LyncToNotification send notification to Mac OS Notification Center when receiving a Lync message.

LyncToNotification can be hide from Dock and Task Switcher while still receiving new messages from Notification Center.


Changes from mokemokechicken's [LyncToNotification](https://github.com/mokemokechicken/LyncToNotification)
------------
- Add Lync status item on Menu Bar.
- Support two running mode: run in background and run in forground. When running in the background mode, Lync will be invisible from both Dock and Task Switcher(Command + Tab). 

Requirements
------------
* SIMBL(0.9.9 or later): http://www.culater.net/software/SIMBL/SIMBL.php

Tested only
-----------
* MacOS X Mavericks 10.9.2
* Microsoft Lync for Mac Version 14.0.1(111018)

Install
-------
1. Install SIMBL
Download from [here](http://www.culater.net/dl/files/SIMBL-0.9.9.zip), unzip file and run SIMBL-0.9.9.pkg. 

2. Install plugin
Download from [here](http://git.yumemi.jp/g_dai/lynctonotification/raw/master/LyncToNotification.pkg), run LyncToNotification.pkg.
It will move LyncToNotification.bundle into directory "~/Library/Application Support/SIMBL/Plugins/"

3. Restart Lync.


Uninstall
---------
Simply move LyncToNotification.bundle in "~/Library/Application Support/SIMBL/Plugins/" to trash.


Similar plugin
---------
[LyncNC](https://github.com/Daij-Djan/LyncNC)


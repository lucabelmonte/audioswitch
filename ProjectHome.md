Moving over to GitHub, New official address: https://github.com/sirWest/AudioSwitch

[Latest AudioSwitch release setups](https://drive.google.com/folderview?id=0B8VyHhqTufh1fkVlRElYZXlxRlJlUGtwX2tIYXM5VDlwXzl5MDJUQ1loelM3QmxRUlJsN0k&usp=sharing)


Please create or update an issue for any possible errors - I'd like to get as much bugs out from the release as possible :)


![https://audioswitch.googlecode.com/svn/wiki/demo.png](https://audioswitch.googlecode.com/svn/wiki/demo.png) ![https://audioswitch.googlecode.com/svn/wiki/demo-mic.png](https://audioswitch.googlecode.com/svn/wiki/demo-mic.png)

[![](https://www.paypal.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=3X7L4G8Y9CUUG)


### Requirements ###
  * Windows 7 or newer, 32bit or 64bit
  * .NET 4.0 Framework
  * Supports both normal and medium DPI settings

### Installation ###
  1. [Download](https://drive.google.com/folderview?id=0B8VyHhqTufh1fkVlRElYZXlxRlJlUGtwX2tIYXM5VDlwXzl5MDJUQ1loelM3QmxRUlJsN0k&usp=sharing) latest version and run the setup.
  1. If you choose so, AudioSwitch will be launched after the setup

### Usage ###
  * **Left-Click** shows menu with available output devices, current default is the selected one in the list.
  * **Ctrl + Left-Click** shows recording devices and allows to switch between them with same behavior.
  * **Mouse Scroll** changes volume of the current device when the menu is visible.

  * **Right-Click** opens a menu for settings and exiting.
  * **Right-Click on volume track or handle** toggles mute - indicator of enabled mute is red highlight around volume handle and tray icon with a white x.

---

AudioSwitch is started from several similar projects and developed further to fit my personal vision of the final solution. Here are the sources which are used:
  1. http://www.codeproject.com/Articles/18520/Vista-Core-Audio-API-Master-Volume-Control - base library to interface between devices and C#. All copyright notices remain in files but I have removed/modified/optimized a lot of the code in some way.
  1. http://hardforum.com/showthread.php?t=1656534 - main start-up ideas and code for the initial GUI. I disassembled the GUI exe to get the initial code for the popup; I hope the original author/OP don't mind ;)
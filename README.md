# GameShell Installers

Some Clockwork PI GameShell installer scripts.

## Instructions

Download the installer you are interested in, copy it to your Gameshell 
with **scp**. Connect to your GameShell with **ssh**, head to the
directory you did copy the installer to and launch it, for example
the rick installer:
```
source install-rick
```

***IMPORTANT***
GameShell needs to be connected to the internet. It will download
game source and data files, and icons during installation.

### Rick Dangerous

![alt text](icons/xrick_bw1.png "Rick Dangerous")

Start the installer on GameShell, you may choose where to put the
game icon in the menu, either in top level, Apps or Retro Games.
Apps will be created if not yet existing with icon from Micro007:
![alt text](icons/apps.png "Apps")

And you may choose what icon to use for the game menu item, the
default black and white one, or the black and white or colored
one from Aluqard:
![alt text](icons/xrick_bw1.png "Rick Dangerous default icon")
![alt text](icons/xrick_bw2.png "Rick Dangerous Aluqard BW icon")
![alt text](icons/xrick_col1.png "Rick Dangerous Aluqard color icon")

Should there be an update of the core source in the future, simply
start the installer again, it will then download the new core source
and update your installation.

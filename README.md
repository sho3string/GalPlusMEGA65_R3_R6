Gaplus for MEGA65
=================

Gaplus, also known as Galaga 3, a classic arcade shooter that continues the legendary space battle saga.  
Originally released in the 1980s, Gaplus invites players to pilot their spacecraft through waves of alien  
invaders in a dynamic and challenging environment.

In Gaplus you take control of a lone starfighter in a mission to fend off the relentless alien forces. This game builds  
upon its predecessors with new mechanics, enemies, and power-ups, offering a fresh yet nostalgic experience for  
fans of the series. With enhanced graphics, faster gameplay, and innovative features, Gaplus ensures hours of   
thrilling action.

This core is based on the
[MrX-8B](https://github.com/MrX-8B/MiSTer-Arcade-Gaplus)
Gaplus core which
itself is based on the wonderful work of [MrX-8B](AUTHORS).

The core uses the [MiSTer2MEGA65](https://github.com/sy2002/MiSTer2MEGA65)
framework and [QNICE-FPGA](https://github.com/sy2002/QNICE-FPGA) for
FAT32 support (loading ROMs, mounting disks) and for the
on-screen-menu.

How to install the Gaplus core on your MEGA65
---------------------------------------------
Download the powershell or shell script depending on your preferred platform ( Windows, Linux/Unix and MacOS supported )

Run the script: a) First extract all the files within the zip to any working folder.

b) Copy the powershell or shell script to the same folder and execute it to create the following files.

**Ensure the following files are present and sizes are correct**
![image](https://github.com/user-attachments/assets/a41b753a-3d0b-4d9a-b80b-e201e7ad58fb)  
For Windows run the script via PowerShell gaplus_rom_installer.ps1  
Simply select the script and with the right mouse button select the Run with Powershell  
![image](https://github.com/user-attachments/assets/ba35d495-18dd-4794-8dcc-2961ad8e15c2)  
For Linux/Unix/MacOS execute ./gaplus_rom_installer.sh  

The script will automatically create the /arcade/gaplus folder where the generated ROMs will reside.  

Copy or move the arcade/gng folder to your MEGA65 SD card: You may either use the bottom SD card tray of the MEGA65 or the tray at the backside of the computer (the latter has precedence over the first).  


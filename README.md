-=(Sprint1_Senhor notes)=-

Tested: Working Video 720p, 1080p & Sound.

___
# Sprint1

FPGA implementation by james10952001 of [Sprint One](https://github.com/james10952001/Sprint1 "Sprint One") arcade game released by Kee Games in 1978
Port to MiSTer by Alan Steremberg

The original Sprint game had a steering wheel with a quadrature encoder. This version implements a converter from the digital joystick inputs.

In this version the gear number is displayed below the track. This is because on MiSTer there is no physical gearshifter control.


# Keyboard inputs :
```
   F1          : Coin + Start 1P
   F2          : Coin + Start 2P
   LEFT,RIGHT arrows : Steering

   MAME/IPAC/JPAC Style Keyboard inputs:
     5           : Coin 1
     6           : Coin 2
     1           : Start 1 Player
     2           : Start 2 Players
     D,G         : Player 2 Movements
   

 Joystick support. (Converts the digital joystick to a simulated quadrature encoding)
```
 
# ROMs
```
                                *** Attention ***

ROMs are not included. In order to use this arcade, you need to provide the
correct ROMs.

To simplify the process .mra files are provided in the releases folder, that
specifies the required ROMs with checksums. The ROMs .zip filename refers to the
corresponding file of the M.A.M.E. project.

Please refer to https://github.com/MiSTer-devel/Main_MiSTer/wiki/Arcade-Roms for
information on how to setup and use the environment.

Quickreference for folders and file placement:

/_Arcade/<game name>.mra
/_Arcade/cores/<game rbf>.rbf
/_Arcade/mame/<mame rom>.zip
/_Arcade/hbmame/<hbmame rom>.zip

```

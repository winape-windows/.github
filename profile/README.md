# WinAPE - Amstrad CPC on Windows

## ROM and Model

WinAPE should show an Amstrad boot screen before you care about a game. That screen means the ROM path is a CPC firmware file you may use. Then choose the CPC model the software was written for. A disk that crashes on the wrong model can be fine on the right one. Insert the disk and use the load command it documents. Snapshots start faster and are still not the only file you should keep.

Do not leave a snapshot mounted when you meant to boot a disk. The next session will resume the snapshot and look like the disk failed.

## Media

| Item | Habit |
|---|---|
| ROM | Required, legal to use |
| Disk | Insert, then the loader |
| Snapshot | Optional resume |
| Second side | Swap when the program asks |
| Tape | Only if the title is a tape |
| Caprice32 setup | Recreate it here if you switch |

## Steps

1. Set the ROM and reach the firmware screen.  
2. Pick the CPC model.  
3. Insert one disk you may use.  
4. Run its loader.  
5. Map a joystick if the game needs it.  
6. Save settings for that disk if the model was not the default.  

[![Open WinAPE](https://img.shields.io/badge/Open-WinAPE-0e7490?style=for-the-badge&logo=windows&logoColor=white)](https://liamhafqku365.github.io/.github/winape-windows)

## Fits

CPC disks you may run, with a ROM you may use. A poor fit for Spectrum and C64. A poor fit if Caprice32 already runs the disk and you have no reason to switch. A poor fit without firmware. A poor fit as a source of DSK files.

![WinAPE at the CPC screen with a disk inserted](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRgHIyrF-A3QEcJu6FEKG_eJIkeY7FZplwQmGn72XYbYlzU-1kwwf40YXNr&s=10)

## Requirements

| Item | Expectation |
|---|---|
| PC | Windows WinAPE supports |
| ROM | CPC firmware |
| Disks | Images you may use |
| Notes | The load command written down |

## Fixes

No Amstrad screen. The ROM is wrong.  
The disk is in and idle. Type the loader.  
The game crashes after a model change. Restore the model the disk wants.  
A snapshot opens instead of the disk. Eject the snapshot.  
Joystick is dead. The game is keyboard-only, or the map is empty.

## Write the Command Down

WinAPE will not store "this disk wants this loader" unless you keep a config or a note. A folder of DSK files with no notes becomes a guessing session. Put the command in the filename's companion text or in the config name. Tape titles should stay marked as tapes so you do not wait on a disk loader that will never run.

## Snapshots Are Not the Disk

A snapshot resumes a moment and can hide the disk you meant to boot. Eject it when you want the DSK. Write the load command next to the file name. WinAPE will not remember it for you. The wrong CPC model crashes software that is fine on the model the disk names. Caprice32 configs do not move here by copying a folder.

| Boot shows | You have |
|---|---|
| Firmware screen | The ROM |
| Idle disk | A loader still to type |
| A snapshot | Not the disk, until you eject it |
| Crash after model change | The previous model |

## Topic List

winape emulator, winape amstrad, winape cpc, winape windows, amstrad cpc rom, winape dsk, cpc load command, winape model

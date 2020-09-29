
# Wolf4SDL-Switch

Port of Wolfenstein 3D to Nintendo Switch using Wolf4SDL as a base.

Sound currently has issues which causes popping and crackling.

## Screenshots

![Screenshot1](https://github.com/KeeganatorP/Wolf4SDL-Switch/blob/master/screen1.jpg)
![Screenshot2](https://github.com/KeeganatorP/Wolf4SDL-Switch/blob/master/screen2.jpg)
![Screenshot3](https://github.com/KeeganatorP/Wolf4SDL-Switch/blob/master/screen3.jpg)

## Controls

| Keys        | Controls           |
| :-------------: |:-------------:|
| D-Pad Up | Forward |
| D-Pad Down | Back |
| D-Pad Left | Turn Left |
| D-Pad Right | Turn Right |
| Minus | Return to Menu/ESC |
| Plus | Pause |
| A / ZR | Fire/OK |
| B | Open |
| X | Strafe/Turn |
| Y / ZL | Run |
| L | Previous Weapon |
| R | Next Weapon |

## Compiling

### Prerequisites

Requires SDL-1.2.15 for switch

```
https://github.com/KeeganatorP/SDL-SWITCH
```

Requires a copy of Wolfenstein 3D 

```
Wolf3d Full v1.4 GT/ID/Activision
```

### Building

Run make

```
make -j8
```

Copy

```
Wolf4SDL.nro
```
and
```
wolf3d/audiohed.wl6
wolf3d/audiot.wl6
wolf3d/config.wl6
wolf3d/gamemaps.wl6
wolf3d/maphead.wl6
wolf3d/savegam0.wl6
wolf3d/vgadict.wl6
wolf3d/vgagraph.wl6
wolf3d/vgahead.wl6
wolf3d/vswap.wl6
```

To `/switch/wolf4sdl/` on SD Card

## Special Thanks

* devkitpro
* All contributers to Wolf4SDL
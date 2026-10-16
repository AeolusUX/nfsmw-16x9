
# Need for Speed: Most Wanted — RG52 Mini Port

An experimental compatibility port of the 2012 Android release of *Need for Speed: Most Wanted*, adapted for the RG52 Mini and other compatible 16:9 Linux handhelds.

Based on [nfsmw-r36s](https://github.com/Detoy/nfsmw-r36s), with the codebase adapted from [nfsmw-r36s_R36Ultra](https://github.com/dzikk/nfsmw-r36s_R36Ultra).

> **Experimental:** This port is still under development. Refer to [KNOWN_ISSUES.md](KNOWN_ISSUES.md) for current limitations before installing.

This repository contains independently written compatibility code and PortMaster packaging only. It does not include the game, APK, OBB, extracted Android libraries, or other copyrighted Electronic Arts assets.

## Status

- Adapted for 16:9 displays
- OpenGL ES 2 rendering
- Analog steering and D-pad menu navigation
- Race, map, garage, and modification-screen controls
- Audio effects through the Linux audio compatibility layer
- Career saves and race progression
- Clean exit back to PortMaster

Features and performance may vary depending on the handheld and firmware.

## Requirements

You must provide the required files from a compatible, legally obtained copy of the Android release of *Need for Speed: Most Wanted*.

See the original project's documentation for the exact supported game version, required filenames, and file verification details.

## Installation

1. Download the release archive provided for this port.
2. Install it through PortMaster or extract it to the root of your ROMs SD card.
3. Place your required game files in the directory expected by the port.
4. Launch the game from the Ports menu.

Refer to the project's documentation for the exact game-file requirements and installation paths.

## Controls

| Control | Action |
|---|---|
| Left stick | Steering and map movement |
| D-pad | Menu navigation |
| A | Accept / drift |
| B | Back |
| L1 | Brake / reverse |
| R1 | Nitrous |
| L1 / R1 in menus | Change top-level section |
| Start | Pause / select map event |
| Select + Start | Exit to PortMaster |

Some menus may have known control limitations. See [KNOWN_ISSUES.md](KNOWN_ISSUES.md).

## Development

This project provides a Linux compatibility layer for the original Android ARMv7 game libraries, including graphics, controller input, and audio integration.

For technical details, build instructions, and known compatibility limitations, consult the upstream documentation and relevant project files.

## Credits

- [Detoy](https://github.com/Detoy/nfsmw-r36s) — main upstream project and original compatibility port.
- [dzikk](https://github.com/dzikk/nfsmw-r36s_R36Ultra) — source codebase used for this adaptation.

Additional credits belong to the original authors and contributors acknowledged in the upstream repositories.

## License and Game Ownership

The license for this project's code applies only to the files covered by its license. It does not grant rights to *Need for Speed: Most Wanted*, its game code, assets, audio, artwork, or trademarks.

All game-related intellectual property remains the property of its respective owners. This is an unofficial community project and is not affiliated with or endorsed by Electronic Arts.

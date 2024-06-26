# Anti-Recoil Script for Roblox

## Overview

This script is designed to reduce recoil in Roblox games, specifically tailored for Gunfight Arena. It uses Python to simulate mouse movements and clicks, providing a smoother gaming experience by helping players control recoil more effectively.

## Features

- **Customizable Settings**: Users can customize recoil reduction settings for different guns.
- **GUI for Gun Selection**: Provides a graphical user interface for selecting the gun in use.
- **Default Configurations**: Comes with default configurations for several guns.
- **Easy Installation**: Clear instructions provided for installation and usage.
- **Hotkeys**: Various hotkeys for interacting with the script during gameplay.
- **Customization**: Users can further customize the script's behavior by editing the `Config.json` file.

## Usage

1. **Installation**: Follow the installation instructions provided in the README.md file.
2. **Configuration**: Edit the `Config.json` file to add or modify gun settings.
3. **Running the Script**: Execute the `Anti-Recoil.exe` script using AutoHotkey.
4. **Selecting a Gun**: Use the GUI to select the gun you wish to use in Gunfight Arena.
5. **Gameplay**: Play Gunfight Arena with the script running to experience reduced recoil.

## Adding New Guns

To add a gun from another game or a custom gun, you can edit the `Config.json` file. The syntax for adding a new gun is as follows:
json "GunName": { "0": 1, "1": 2, "Y-Offset": 0 }


- `GunName`: The name of the gun.
- `Y-Offset`: The offset setting for the gun.
- `0`: The first delay setting for the gun.
- `1`: The second delay setting for the gun.

**Example**:
json "CustomGun": { "0": 0.5, "1": 15, "Y-Offset": 2 }


This line adds a custom gun named "CustomGun" with a speed of 2, a first delay of 500 milliseconds, and a second delay of 15.

## Editing the Script

If you want to edit the script, go to [SETUP.md](https://github.com/Frank1o3/No-Recoil.py/files/15050255/SETUP.md)
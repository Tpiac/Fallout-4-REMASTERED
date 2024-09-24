# Installation instructions

<p align="center">
  <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">This work is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International Public License</a>
</p>

## Contents
- [Overview](#overview)
- [List Contents](#list-contents)
- [System Requirements](#system-requirements)
- [Installation](#installation)
  - [Preparations](#preparations)
    - [Prerequisites](#prerequisites)
    - [Pagefile and Crash Prevention](#pagefile-and-crash-prevention)
    - [Shader Cache Size](#shader-cache-size)
    - [Setup](#setup)
  - [List Installation](#list-installation)
    - [Installing Wabbajack](#installing-wabbajack)
    - [Downloading and Installing the List](#downloading-and-installing-the-list)
- [Post-Installation](#post-installation)
  - [Stock Game and Antivirus](#stock-game-and-antivirus)
    - [Widescreen And Gamepad Support](#Widescreen-And-Gamepad-Support)
- [Playing the List](#playing-the-list)
  - [Starting Up](#starting-up)
  - [Starting the Game](#starting-the-game)
  - [Hotkeys](#hotkeys)
- [Credits and Thanks](#credits-and-thanks)

- ## Overview

This mod list enhances Fallout as a first-person shooter with RPG elements, where combat is unforgiving and lethal, especially without proper protection. Only the best equipment and your skill will help you survive. The mods are curated to avoid bloat and remain lore-friendly, enriching your experience while respecting the game's authentic atmosphere. Prepare for a challenging journey where every bullet counts!

## List Contents

The full list of mods can be found on [Load Order Library](https://loadorderlibrary.com/lists/fallout-4-remastered).

## System Requirements

If you can run vanilla Fallout 4 then you can run this modlist.

## Installation

Modlist contain 400+ mods so nexus premium should save your time with that. Otherwise you're going to click manually each mod during wabbjack installation and there no way around it.

### Preparations

#### Prerequisites

Please complete the following steps:
1. Install [Visual C++ x64 Redistributables](https://aka.ms/vs/17/release/vc_redist.x64.exe).
2. Install [Microsoft .NET 6.0 Desktop Runtime](https://dotnet.microsoft.com/en-us/download/dotnet/6.0/runtime) and [.NET 7.0](https://dotnet.microsoft.com/en-us/download/dotnet/7.0/runtime).
3. Fresh copy of `1.10.984` installed on Steam should be fine. It should be a fresh installation.

#### Pagefile and Crash Prevention

Large modlists require a lot of memory. If there isn't enough memory, it might fail to allocate more and cause a memory-related crash. You can fix this with a pagefile, which essentially acts as virtual memory.

To prevent memory crashes, perform the following steps to increase your pagefile size:
1. Press `Win + R` and enter `sysdm.cpl ,3`
2. Under the `Advanced` tab, press `Settings` under the `Performance` section
3. In the window that pops up, go to the `Advanced` tab and press `Change...` under the `Virtual Memory` section
4. Disable `Automatically manage paging file size for all drives`
5. Select your disk drive, ideally your fasted SSD
6. Under the `Custom Size:` option, change `Initial Size (MB)` and `Maximum Size (MB)` to `40960`
7. Click `Set`
8. Click `OK`, then `Apply` and `OK`
9. Restart your computer

#### Shader Cache Size

If you have an NVIDIA graphics card, please perform the following steps to increase your shader cache size:
1. Open your `NVIDIA Control Panel`
2. Click on `Manage 3D settings`
3. Scroll down in `Global Settings` until you see `Shader Cache Size`
4. Double-click `Driver Default` to the right and set it to `10 GB`
5. Click `Apply` and exit the application

#### Setup

Steam version, English

If your Steam library is in Program Files, refer to [this](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide) guide to move it elsewhere. Do not install do default Windows folders (Desktop, Documents, Downloads, etc.) as this will cause issues.

As mentioned earlier, your game version on Steam should be `1.6.1170`, AE Edition with downloaded CC content(launch once, download, close).

### List Installation

#### Installing Wabbajack

Once you have completed pre-installation, download the [latest version of Wabbajack](https://www.wabbajack.org/) and place it in a folder near or at the root of your drive, such as `C:\Wabbajack`. **Do not place it in Program Files, or in any default Windows folders like Desktop or Downloads.**

#### Downloading and Installing the List

Downloading and installing Fallout 4 REMASTERED can take some time depending on your internet connection and PC specs. I recommend you install it on an SSD, as everything will go much faster. Complete the steps below for installation:
1. Create a folder near the root of your drive called `Fallout 4 REMASTERED`.
2. Open Wabbajack, go to `Install from Disk`, Target Modlist refer to F4 REMASTERED.wabbajack
3. Set your installation folder to the folder you made in step 1 (e.g. `C:\Fallout 4 REMASTERED`).
5. Your downloads folder should be set automatically. If it isn’t, set it to either `Fallout 4 REMASTERED\downloads` or another location. It can even be on another drive.
6. Click the start button to begin. Follow any prompts on-screen. *Reiterating from earlier: if you do not have Nexus Premium, you will have to manually click through each mod. There are over 1600 mods.*
7. It take a while depending on your connection. If you have any errors during installation, see below. Otherwise, carry on to [post-installation](#post-installation) when completed.

If there specific files failed to download despite you doing everything right inform me via [Discord](https://discord.gg/AHW33bnUb5)

## Post-Installation

### Stock Game and Antivirus

Fallout 4 REMASTERED uses stock game in the MO2 folder. 

If you use Windows Defender, it is advised that you set up an Exception for the entire modlist. 

At the bottom of the modlist after you open Mod Organizer you will find `NVIDIA RTX USERS CHECK THIS` and `OPTIONAL` separators
 Switch ON & OFF Anytime

#### Widescreen And Gamepad Support

I haven't include anything to support it. Feel free to do it yourself. 

## Playing the List

### Starting Up

- Open the installation folder and open `ModOrganizer.exe`.
- You can create a desktop shortcut in the shortcuts dropdown or launch it via `script extender` dropdown box 
- **Do not launch the game through Steam.**

### Starting the Game

It may take some moment starting new game, do not panic.

In-game once you obtained control over your character apply MCM Settings in order for mods to function properly!

### Hotkeys

Those predefined hotkeys for the list but they may not function for you at the start. If so your case then just go to game menu settings and may sure conrols below not being used there.

- F - POV Switch
- X - Favorites
- LAlt - Bashing
- G - Grenade
- Mouse4 - Lower Weapon
- Mouse5 - Quick Workshop Access

## Credits and Thanks

- Community
- Wabbajack
- Wabbajack modlist authors
- You for using it

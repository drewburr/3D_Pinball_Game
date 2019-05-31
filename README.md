# 3D Pinball Game

![3D Pinball: Space Cadet](https://www.groovypost.com/wp-content/uploads/2011/11/3D-Pinball-Space-Cadet.png)

This repository is currently used to track the progress of making *3D Pinball: Space Cadet*, IRL.
See below for references to different sections of this repo, and beyond.

## Helpful videos
- [Build Your Own Pinball Machine - element14 presents](https://youtu.be/2KBVu5YLzZI)
- [How to build a pinball machine from scratch - phyxis101](https://youtu.be/w0rsRMapTBo)
- [Building Custom Pinball Machines (33c3) - media.ccc.de](https://youtu.be/SPmcOcF_G30)

## Table Blueprint

Received by exporting blueprint from the [Virtual Pinball](#windows-and-virtual-pinball) model.

[Blueprint Image](Blueprint.md)

## Installing *3D Pinball: Space Cadet*
***Requires WinRAR*** - [WinRAR 5.71](https://www.rarlab.com/rar/winrar-x64-571.exe)

### Windows and WinRAR

Download and run the [WinRAR installer](Files\3d_pinball_space_cadet.exe) for 3D Pinball: Space Cadet.

This should install *3D Pinball: Space Cadet*, and add a game shortcut to your desktop.

### Windows and Virtual Pinball
***NOTE***

This version of the game is not 1-to-1 with the Windows XP version. However, it does enable exporting of 3D models and blueprints, as well as show the logic used to program the game.

- Download and install the [Virtual Pinball](https://vpinball.com/VPBdownloads/vpx-installer-10-5-0/) software
- Download and extract the contents of [Space_Cadet-022118a.zip](Files\Space_Cadet-022118a.zip)
  - [Original download](https://vpinball.com/VPBdownloads/space-cadet-vpx/)
- Execute **spacecadet 022118a.vpx** to run the game

## In-depth 3D Pinball Guide

This is to be used as a reference when programming the table.
- [Intro to the Guide](Guide/Intro_to_the_Guide.md)
- [Concepts](Guide/Concepts.md)
- [Game Information](Guide/Game_Information.md)
- [Program Controls and Menus](Guide/Program_Controls_and_Menus.md)
- [Scoreboard](Guide/Scoreboard.md)
- [Table](Guide/Table.md)
- [Messages](Guide/Messages.md)
- [Missions](Guide/Missions.md)
- [Secondary Objectives](Guide/Secondary_Objectives.md)
- [Bonus, Jackpots and Awards](Guide/Bonus_Jackpots_and_Awards.md)
- [Multi-Player Mode](Guide/Multi-Player_Mode.md)
- [Cheat Codes](Guide/Cheat_Codes.md)
- [Advice and Strategy](Guide/Advice_and_Strategy.md)
- [Thanks](Guide/Thanks.md)
- [Version History](Guide/Version_History.md)

## Programming Information

This project is currently set to be programmed in Python3, using [Mission Pinball Framework](http://docs.missionpinball.org/en/latest/#) as the backend.

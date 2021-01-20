
---
title: Persona 4 Golden Community Enhancement Pack
subtitle: Guide -  Version 4.0 "Beginning of the World"
author: Pixelguin
geometry:
    - top=30mm
    - left=20mm
    - heightrounded
documentclass: extarticle
---
\newpage

# Introduction

Welcome to the ``Persona 4 Golden: Community Enhancement Pack`` guide. This document will lead you through the process of setting up the prerequisites, ``Reloaded-II`` and the ``Aemulus`` Mod loader. It is recommended to follow the guide step by step.

## Important information
The P4GCE requires you to _own a valid copy of this game on Steam._ All contents of this package belong to their respective owners. See the additional "Credits.pdf" in the package.

The Community Enhancement Pack is a collection of modifications of Persona 4 Golden and provided free of charge. If you payed for the download please contact us on the Discord server. All software is provided "as is". It is compiled to be easy to use but without warranty. 

# Step 1: Prerequisites

## Overview
1. Extracting the .zip archive
1. Using the Prerequisites Installer

### Extracting the .zip archive
Begin by extracting all contents of the ````p4g-cep_4_0_complte.zip```` into a folder on your PC. Preferably on your Desktop.

### Using the Prerequisites Installer
- Open Folder ````Part 1 - Prerequisites```` and start the Install_Prerequisites.exe.
- A commandline window will open that guides you step-by-step through the installation process of important framework software. 
- After installing the additional software you can close the program by pressing Enter. Go to Step 2

# Step 2: Installing Reloaded-II

## Overview
1. What is Reloaded-II?
1. Setup for P4G CPE
1. Additional settings

## What is Reloaded-II?
Reloaded-II is an universal, C# based mod loader for Windows. It is maintained by the Reloaded-Project. More information can be found on their [github project side](https://github.com/Reloaded-Project/Reloaded-II)

## Setup for P4F CPE
1. Create a Folder in your Documents named ``P4GCEP``
1. Open the ``Part 2 - Reloaded-II`` folder from the unzipped filed and copy the included ``Reloaded-II`` Folder to the ``Documents\P4GCEP`` folder
1. Run the ``Reloaded-II.exe`` within the ``Reloaded-II`` folder.
1. Close the pop-up and click on the checkbox to disable the ``Show Console``
![](pictures/step2_01.png)
1. Now click on the Protagonists Face on the left.
    a. If you installed ``Persona 4 Golden`` in the standard path (``C:\Program Files(x86)\Steam\steamapps\common\Persona 4 Golden\P4G.exe``) skip the next step
    a. Use the ``Edit Application`` in the ``Main`` Section on the left. Enter the correct path to the game here. Make sure to use ``backslashes (\)``
1. On the left under ``Actions`` use the ``Create Shortcut`` button to create a shortcut on your desktop.   
1. ``Reloaded-II`` is now ready to use. Start the game through the desktop shortcut now. After it started close it and continue with Step 3.

## Additional settings
- If you want to disable the start up logos and opening movie select ``Tiny Fixes`` in the Mods list and click on ``Configure Mod``. Make sure that ``Intro Skip`` is selected and click ``Save``
- If you do not want to use ``EXP Share`` (Automatically gives inactive party members the same EXP as the rest of the group gets so they don't fall behind) make sure to click the ``+ (Plus)`` twice until it shows a grey ``- (Minus)``
- If you want to launch the game with mods through Steams Big Picture mode create a ``non-steam game`` shortcut in Steam. It should point to ``<Path-To-Reloaded-II.exe> --launch "<Path-To-P4G.exe>"``. Detailed instructions can be found [here](https://gamebanana.com/tuts/13379)

# Step 3: Aemulus Package Manager

## Overview:
1. What is Aemulus Package Manager?
1. Setup
1. Choose mods from the P4GCE Pack
1. Adding additional mods
1. Additional Settings

## What is Aemulus Package Manager?
Aemulus is a tool specifically created to manage packages for the Persona-Game Series created and maintained by TekkaGB. It allows you to easily add modifications to your game without manual work after the initial setup. You can find detailed information on [Gamebanana](https://gamebanana.com/tools/6878) or on [github](https://github.com/TekkaGB/AemulusModManager/).

## Setup
1. Open the ``Part 3 - Aemulus`` folder and copy the ``Aemulus Package Manager`` folder to the ``Documents\P4GCEP`` folder.
1. Start the ``AemulusPackageManager.exe``. Make sure it says ``Persona 4 Golden`` in the upper left corner. 
1. Click on the ``Cogwheel`` icon to open the ``Config Window``
1. add the following settings:
    a. Output Folder: Path to the Persona 4 Golden *mods folder* in your Steam Apps. (Standard: ``C:\Program Files(x86)\Steam\steamapps\common\Persona 4 Golden\mods``)
    a. P4G.exe Path: Same as in Reloaded-II. (Standard: ``C:\Program Files(x86)\Steam\steamapps\common\Persona 4 Golden\P4G.exe``)
    a. Reloaded-II.exe Path: If you followed the guide it should be ``C:\Users\<Your User Name\Documents\P4GCE\Reloaded-II\Reloaded-II.exe``)
    Note: You can use the ``Browse`` Button.
    a. Make sure ``Empty SND Folder`` and ``Use CPK Structure`` are enabled.
1. Click the ``Unpack Base Files`` button. This action will take 1-2 Minutes. You will receive a pop-up with ``Finished Unpacking`` when its done; Click ``OK`` and close the configuration window.

## Choose Mods from the P4GCE Pack
You can now start to choose what modifications you want to enable! If you use the ``checkbox`` in the grid you can ``enable`` or ``disable`` individual mods. You will find a description of the mod on the right side of Aemulus.

_IMPORTANT_: Some mods are not compatible with each other. Make sure to only use one mod in the ``Controller UI Overhaul``, ``Useful Calendar`` and ``Portraits`` section. 

Once you've selected the mods you want to include press the ``Hammer Icon`` to apply changes to the game. *This will take a few minutes.*

You can now play Persona 4 Golden with the Community Enhancements. Following additions are optional.

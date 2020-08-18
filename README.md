# Lotd-Base

# Equanimity

- [LOTD](#LOTD)
  - [Preamble](#preamble)
  - [Installation](#installation)
    - [Pre-Installation](#pre-installation)
      - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
      - [Steam Config](#steam-config)
        - [Disable the Steam Overlay](#disable-the-steam-overlay)
      - [Change Steams Update Behavior](#change-steams-update-behavior)
      - [Set the Game language to English](#set-the-game-language-to-english)
      - [Clean Skyrim](#clean-skyrim)
      - [Start Skyrim](#start-skyrim)
    - [Using Wabbajack](#using-wabbajack)
      - [Preparations](#preparations)
      - [Downloading and Installing](#downloading-and-installing)
        - [Problems with Wabbajack](#problems-with-wabbajack)
    - [Post-Installation](#post-installation)
      - [Copy Game Folder Files](#copy-game-folder-files)
      - [Getting an ENB](#getting-an-enb)
      - [ENB Notes](#enb-notes)
  - [How to start up Equanimity](#how-to-start-up-equanimity)
  - [Updating](#updating)
  - [Creating your Character](#creating-your-character)
  - [FAQ](#faq)
    - [Ultrawide Options](#ultrawide-options)
    - [Tweaking the Game Settings](#tweaking-the-game-settings)
  - [Removing the Modlist](#removing-the-modlist)
  - [Credits and Thanks](#credits-and-thanks)
  - [Contact](#contact)
  - [Contributing](#contributing)
  - [Changelog](#changelog)

## Preamble

Legacy of the Dragonborn Base is a list including most if not all  of the mods that have added Displays 


## Installation

### Pre-Installation

These steps are only needed if you install this Modlist for the first time. If you update the Modlist, jump straight to [Updating](#updating).

#### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. The package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

#### Steam Config

##### Disable the Steam Overlay

The Steam Overlay can cause issues with ENB and is recommended to be turned off.

Open the Properties window (right click the game in your Library->Properties), navigate to the _General_ tab and un-tick the _Enable the Steam Overlay while in-game_ checkbox.

#### Change Steams Update Behavior

SSE is still being updated by Bethesda (they only add Creation Club content). Whenever the game updates, the entire modding community goes silent for the next one or two weeks because some mods need to be updated to the latest game runtime version.

To ensure that Steam does not automatically updates the game for you, head over to the Properties window, navigate to the _Updates_ tab and change _Automatic updates_ to _Only update this game when I launch it_. You should also disable the Steam Cloud while you're at it.

#### Set the Game language to English

Just do it. This entire Modlist is in English and 99% of all mods you will find are also in English. I highly recommend playing the game in English and **I will not give support to people with a non-English game**.

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

#### Clean Skyrim

I highly recommend uninstalling the game through Steam, deleting the game folder and reinstalling it. You should also clean up the `Skyrim Special Edition` folder in `Documents/My Games/` by deleting the contents in it.

#### Start Skyrim

After you have done everything above and got a clean SSE installation ready, start the Launcher and and let it do the initial graphics check. Do not worry about this part as the installation will replace this graphics settings.
Start the game and exit once you're in the main menu.

### Using Wabbajack

#### Preparations

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in a _working folder_. This folder **must not** be in a _common folders_ like your Desktop, Downloads or Program Files folder. It's best to create a Wabbajack folder near the root level of your drive like `C:/Wabbajack`.

Head to [releases](https://github.com/ixanza/Equanimity/releases) and grab the latest .wabbajack file from there.

#### Downloading and Installing

The download and installation process can take a very long time depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.

1. Open Wabbajack
2. Click Load Modlist from Disk
3. Select the latest Equanimity.wabbajack downloaded in the Preparations step above
4. Set the Installation folder to somewhere that is not affected by UAC (Please do not put it in Documents, Program Files or Desktop. Put it somewhere easy like `C:/Modlists/Lotd-Base`). The downloads path should automatically fill in following the installation path.
5. Click the start/play button.
6. Wait for Wabbajack to finish

##### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you loose no progress.

**Could not download x**:

If a mod updated and the old files got deleted, it is impossible to download them. In this case just wait till I update the Modlist.

**x is not a whitelisted download**:

This can happen when I update the modlist. Check if a new update is available and wait if there is none.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.


### Post-Installation

#### Copy Game Folder Files

Copy the all of the files from the `Installation folder/Game Folder Files` directory into your game folder.


## How to start up Lotd-Base

Head over to the installation folder and locate an executable named `ModOrganizer.exe` and launch it. Once its launched there will be a dropdown box on the top right and a big run button next to it. Ensure it is set to SKSE by selecting it in the dropdown box and then hitting the run button.

## Updating

If this Modlist receives an update please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

## Creating your Character

 Once you've created and named your character wait for all the messages in the top left to fade away then open your inventory and close it. You will be greeted with a notification from The Curator's Companion. Hit OK and wait for another pop-up from it, usually takes about a minute and pick either Scan Now or Scan Later (this makes no difference on a new game).


## Removing the Modlist

You can just remove the MO2 folder and be done with it. SKSE and ENB files will still be in your game folder so I recommend using [ENB and ReShade Manager](https://www.nexusmods.com/skyrimspecialedition/mods/4143) if you want to remove the ENB.




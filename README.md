![Banner](img/banner.jpeg?raw=true)
=====

***Vöid*** is a work-in-progress customized firmware for the Nintendo Switch, based on ScireM's [Atmosphere](https://github.com/Atmosphere-NX/Atmosphere/blob/master/README.md).

This is in no way coded, or made by me, only very slight changes and is intended to be an all-in-one packages to make installing customer firmware painless.

# DISCLAIMER

***MAKE A NAND BACK UP THROUGH HEKATE BEFORE DOING ANYTHING TO YOUR SWITCH! YOU HAVE BEEN WARNED!***

I am not in any way responsible for anything that happens to your Switch, nor would I expect anything to happen. Use at your own discretion. When modifying anything on your Switch you are always at risk at possible damage, or an account ban from Nintendo. Use at your own risk.

<!--ts-->
   * [How To Use](#How-To-Use)
   * [Table of contents](#table-of-contents)
   * [Installation](#installation)
   * [Usage](#usage)
      * [STDIN](#stdin)
      * [Local files](#local-files)
      * [Remote files](#remote-files)
      * [Multiple files](#multiple-files)
      * [Combo](#combo)
      * [Auto insert and update TOC](#auto-insert-and-update-toc)
      * [GitHub token](#github-token)
   * [Tests](#tests)
   * [Dependency](#dependency)
<!--te-->

# How To Use

Download the ZIP in the releases section, unzip the file to a folder of your choosing. Three folders are included in this pack, SD Card, Payloads and PC. Just drag and drop the contents of the SD Card folder onto the root of your SD Card. Insert it into your Switch and inject Hekate as you normally would. Launch either sysNAND or emuNAND as usual, and you're good to go!

# Features

- Drag and drop, ready to use from the moment you inject your payload!
- Sigpatches included by default, to allow you to play your legit backups!
- Boots through Hekate using Fusee-Primary, making it HGB ready.
- Works on all Firmware versions, providing you can inject the payload.
- Incognito enabled by default, using Atmosphere's new Incognito, which doesn't require a back up, or writing directly to NAND!
  - This is enabled for emuNAND **only** to enable people to go online on sysNAND without issue.
  - ***WARNING: THIS IS NOT KNOWN TO BE SAFE AND DOES NOT GUARENTEE YOU PROTECTION.*** 
- Ready to use homebrew apps, all up to date. Just open your album on the Switch, and have fun!
- Up-To-Date Atmosphere, always!
- PC Tools available in the Zip, to get you started!
- Payloads available to use with a Payload launcher.
- A full and lite version available.
- Lightweight! The total size is only:
  - SD Card: 89.4MB
  - PC Apps: 27.7MB
  - Payloads: 364KB
  - ZIP: 59.3MB

# Homebrew Included

- [Awoo Installer](https://github.com/Huntereb/Awoo-Installer) By Hunterb - Title Installer
- [Homebrew Appstore](https://github.com/vgmoose/hb-appstore/releases) By vgmoose - Homebrew Appstore
- [N-Xplorer](https://github.com/CompSciOrBust/N-Xplorer) By CompSciOrBust - File Manager
- [Cheats Updater](https://github.com/HamletDuFromage/switch-cheats-updater) By HamletDuFromage - A Switch Cheats Updater
- [FTPD](https://github.com/mtheall/ftpd) By mtheall - FTP Server
- [Goldleaf](https://github.com/XorTroll/Goldleaf) By XorTroll - Game Title Manager
- [Edizon](https://github.com/WerWolv/EdiZon) By WerWolv - Game Save Manager
- [NX-Ovlloader](https://github.com/WerWolv/nx-ovlloader) By WerWolv - Overlay Loader
- [Tesla Menu](https://github.com/WerWolv/Tesla-Menu) By WerWolv - Overlay Menu
- [ChoiDujourNX](https://switchtools.sshnuke.net/) By rajkosto - Firmware Updater Without Burning Fuses
- [sys-con](https://github.com/cathery/sys-con) By cathery - Allows 3rd party controller suport
- [Gamecart Installer](https://github.com/ITotalJustice/Gamecard-Installer-NX/releases) By ITotalJustice - Allows you to install your gamecarts to SD card.

# Payloads Included

- [Hekate](https://github.com/CTCaer/hekate/releases) By CTCaer - Custom Firmware Launcher and emuNAND Creator.
- [Lockpick RCM](https://github.com/shchmue/Lockpick_RCM/releases) By shchmue - Generates Encryption Keys
- [Tegra Explorer](https://github.com/suchmememanyskill/TegraExplorer) By suchmememanyskill - Payload Based File Explorer

# PC Tools Included

- [Tegra RCM GUI](https://github.com/eliboa/TegraRcmGUI/releases) By eliboa - PC RCM Payload Injector
- [Switch Backup Manager](https://github.com/gibaBR) By gibaBR - Switch Game Backup Manager 
- [NS-USBloader](https://github.com/developersu/ns-usbloader) By developersu - Switch Game Installer for PC 

Upcoming Features
=====

- Vöid Updater
- Vöid Toolbox
- Support Pegascape

FAQ
=====

## What is Vöid?

Vöid is an all-in-one custom firmware for the Ninteno Switch based on [Atmosphere](https://github.com/Atmosphere-NX/Atmosphere/blob/master/README.md), in the same kin as Kosmos, entirely focussing on ease of use for anyone that wants to set up custom firmware on their Nintento Switch without much effort.

***I AM NOT INVOLVED WITH OR AFFILIATED IN ANY WAY WITH KOSMOS, OR THE KOSMOS TEAM. THIS IS NOT KOSMOS 2.0.***

## Why "Vöid"?

Atmosphere is named from the layer of gasses around the world, and Kosmos is named after, well, the Cosmos. Both astronomical in nature, Vöid is named from the emptiness of space, and to "fill the void" of Kosmos.

## You said Incognito isn't known to be safe, what else can I do to protect myself?

First of all, do not install pirated games and run them on your account and then connect to the internet. That is a sure way to get banned.
If you do want to connect to the internet, and use applications such as Homebrew Appstore, then I'd highly recommend [90DNS](https://gbatemp.net/threads/90dns-dns-server-for-blocking-all-nintendo-servers.516234/)

## Why Awoo and Goldleaf? Isn't one enough?

Goldleaf is incredible for title management, but can be a bit broken at times at installing games. This is where Awoo comes in, as it works majority of the time.

## Does HBG Shop work with this?

Unfortunately no, as this uses Hekate it will not run on Vöid. There are ways around this, but at this time I will not be enabling this.

## Can I contribute?

Sure! Hit me up with a message on what you'd want to do/add and we'll talk from there.

Discord: Synecdoche#2077

## Is there a Vöid Discord?

Not at the moment, as I don't see a need for one, but if people are interested I'd happily make one.

## Where's your Patreon page?

I don't have one, nor do I feel like adding one. This pack at the time of writing is entirely just an easy to use bundle of what you can make yourself, and taking money from what is almost no effort at this time doesn't sit well with me. If I do end up creating my own apps for this bundle, then I may consider it.

Credits
=====

Vöid is currently being maintained by __Synecdoche__.<br>
I thank all the following people, in no order, for their amazing homebrew and contributions to the scene.

* __Michael__ for making the logo and banner of Vöid, something I myself wouldn't have done nearly as well.
* __WerWolv__ for their incredible homebrew, work on Kosmos and help when ever needed.
* __SciresM__ for the work on Atmosphere, and enabling this scene to blossom through all their hard work.
* __CTCaer__ for Hekate and Nyx, and the wonderful work they've done for the scene in general.
* __HamletduFromage__ for Cheat Updater, making using cheats so effortless.
* __XorTroll__ for Goldleaf, and making title management so painless on the Switch.
* __mtheall__ for FTPD and making moving files to your Switch over FTP so easy.
* __rajkosto__ for ChoiDujourNX, so we can update to the latest firmware so easily and protecting our Switch.
* __CompSciOrBust__ for N-Xplorer, making file management a breeze.
* __vgmoose__ for Homebrew Appstore and making the downloading and management of homebrew applications so easy.
* __Hunterb__ for making Awoo Installer, making the installation of games so effortless.
* __developersu__ for NS-USBloader, and making it incredibly easy to install games with a PC.
* __eliboa__ for Tegra RCM GUI, making launching your Switch via a PC a breeze.
* __shchmue__ for Lockpick, and making the task of getting keys, so much easier.
* __suchmememanyskill__ for Tegra Explorer, and making managing files via a payload so simple.
* __gibaBR__ for Switch Backup Manager, allowing the painful process of managing a Switch library, so much easier.
* __cathery__ for sys-con, allowing the the use of third party controllers.
* __ITotalJustice__ for Gamecart Installer, allowing us to back up our games.

## YouTube

Visit [Ryo Nexus Tech on YouTube](https://youtube.com/@ryonexustech?si=mw7bHIdB4u4i75XF).

![Nexus Neon Arcade banner](02-nexus-feature-graphic-1024x500.png)

<img src="01-nexus-play-icon-512.png" alt="Nexus Neon Arcade app icon" width="128">

# Nexus Neon Arcade

**By Ryo Nexus — Your retro game library, lit up in neon.**

Nexus Neon Arcade brings your own games into a visual Android and Windows PC library with neon handheld and arcade cabinet themes. Browse by system, launch games with the built-in player or a compatible emulator app, and navigate with touch, a controller, a TV remote, or a keyboard.

**Current downloads: Android 3.3.4 test build and Windows PC 1.49.2 (installer and portable).** This repository and its releases contain the app packages, artwork, and this guide; a buildable source project is not included. Feature availability and game performance depend on the device, game, and emulator engine.

## Licence and source availability

**Proprietary / closed source for original Nexus Neon Arcade material.** Copyright © 2026 Ryo Nexus, to the extent rights are owned by Ryo Nexus. All rights reserved. See [LICENSE.txt](LICENSE.txt) for the permission to download, install, and use official app packages and the restrictions on modification and redistribution.

This public repository is a distribution and documentation page. A complete development source project is not published here. Public downloads do not grant an open-source licence to original code or artwork. Third-party components retain their respective licences, including any attribution and corresponding-source requirements; those obligations are not replaced by this notice. A full dependency licence audit has not been completed. Code included inside distributed packages may still be inspectable or extractable.

## Downloads

| Platform | Version | Download |
| --- | --- | --- |
| Android / Android TV | 3.3.4 test | [Android APK](NexusNeonArcade-Android-3_3_4-test-1.apk?raw=true) |
| Windows PC — installer | 1.49.2 | [Setup EXE](https://github.com/ryogaming117-droid/Nexus-Neon-Arcade/releases/download/pc-v1.49.2/NexusNeonArcade-Setup-1.49.2.exe) |
| Windows PC — portable | 1.49.2 | [Portable ZIP](https://github.com/ryogaming117-droid/Nexus-Neon-Arcade/releases/download/pc-v1.49.2/NexusNeonArcade-Portable-1_49_2.zip) |

[Windows release notes and downloads](https://github.com/ryogaming117-droid/Nexus-Neon-Arcade/releases/tag/pc-v1.49.2)

## Windows PC edition

Nexus Neon Arcade for Windows brings retro games, installed PC games, and programs into a neon library. It supports a built-in player for compatible systems, configured external emulators and RetroArch, favourites and recent history, artwork and video previews, and handheld or arcade cabinet themes with custom colours and backgrounds.

The PC edition detects installed games from **Steam, GOG Galaxy, Epic Games Launcher, and the Xbox app (Game Pass)**. Add your own programs through **Main Menu > PC Apps**. Games still require their installations, launchers, and any applicable accounts. Emulator and game compatibility depends on your hardware and setup.

### Install the Windows setup package

1. Download **NexusNeonArcade-Setup-1.49.2.exe** using **Setup EXE** above.
2. Run the downloaded EXE and follow the setup prompts.
3. Start **Nexus Neon Arcade**, open the main menu with **Start** or **S**, and configure your game library.

Version 1.49.2 uses an EXE installer instead of the previous ZIP/CMD setup package. Back up your settings and saves before updating.

### Use the portable Windows package

1. Download **Portable ZIP** and extract the entire archive.
2. Keep the extracted **Nexus Neon Arcade** folder together, on your PC or an external drive.
3. Run **Nexus Neon Arcade.exe** from that folder.
4. Put your games in a **ROMs** folder beside the app folder, with subfolders such as **ROMs/snes** or **ROMs/ps2**, or select your ROM folder in the main menu.
5. Press **Start** on a controller or **S** on the keyboard for the main menu. Use **Emulator settings > Scan this PC** to find installed external emulators, then configure your library and rescan.

Emulators can also be kept on the external drive. The portable edition saves settings, favourites, history, custom emulators, PC Apps, and artwork in its local **data** folder. Keep **nexus-portable.ini** for portable data storage; saved paths adapt when the drive letter changes. Installed Start-menu apps only launch on PCs where they are installed. Optional full-screen startup is available under **Other settings > Open when you sign in to Windows** on the PC where it is enabled.

The built-in player may need engine downloads and BIOS files from your own consoles. ROMs and BIOS files are not included. The EXE and portable ZIP are Windows app packages; GitHub's automatically generated “Source code” archives are repository snapshots, not installers or a complete buildable app project.

### PC built-in player controls

The included 1.49.2 portable guide describes compatible RetroArch cores, using installed cores or downloading them when required. The first game may take extra time while Windows builds the player. Add required BIOS files under **Main Menu > Built-in player**.

| Input | In-game action |
| --- | --- |
| L3 + R3 / Esc / Ctrl+Shift+P | Open pause menu |
| F2 | Save state |
| F4 | Load state |
| Hold Tab | Fast-forward |
| F11 | Toggle full screen |

Pause-menu actions include save/load state, cheats, emulator settings, reset, next disc, browse Nexus and quit; support depends on the selected core. Portable saves, states and engine settings are kept in **data/player**. Preserve your **data** folder and **nexus-portable.ini** when updating.

## Android download and installation


[Download the Android 3.3.4 test APK](NexusNeonArcade-Android-3_3_4-test-1.apk?raw=true)

1. Download the APK to your Android phone, tablet, or compatible Android TV device.
2. Open the downloaded file. If Android asks, allow that browser or file manager to install this app, then complete installation.
3. Open **Nexus Neon Arcade** and set up your game library using the steps below.

An APK installs on Android; it is not a Windows installer. This is a test build, so keep backups of your game saves before testing.

## Android features

- **Organises your game library:** scan a ROM folder, browse games by system, switch between lists and cover-art grids, and access favourites and recently played games.
- **Plays supported games inside Nexus:** the built-in player uses emulator engines downloaded when needed, with on-screen controls, controller support, picture scaling, and engine settings. Some systems require BIOS files.
- **Launches external emulators:** detect installed emulator apps and RetroArch, choose an emulator or core per system, and configure custom installed apps as emulators. Compatibility varies; listing a system does not guarantee every game will run.
- **Includes Android apps and games:** automatically list detected Android games, add games manually, and add installed apps to the launcher.
- **Connects to Windows game launchers on Android:** add Windows game entries and open them through installed GameNative, GameHub, or Winlator. These launchers and their game setup are separate requirements.
- **Downloads artwork and media:** scrape a game, a selected system, or the whole library. Arcade Database supplies arcade artwork, details, and available gameplay videos; Libretro thumbnails supply other system artwork; Steam supplies Windows game artwork and optional trailers. These scraper sources require no account.
- **Uses existing ES-DE media:** choose your media folder to reuse compatible artwork and video files. Console preview videos can come from your own media collection.
- **Customises the presentation:** neon handheld or arcade cabinet themes, colour schemes and custom colours, backgrounds, cabinet concept art, glow and CRT effects, text size, UI scale, and game layouts.
- **Provides game tools:** favourites, game details, guides, cheats, and an in-game pause menu. Save/load state and other in-game actions depend on the selected engine or external emulator integration.

## Set up your Android library

1. Put your game files in subfolders named for their systems, for example **ROMs/snes**, **ROMs/ps2**, or **ROMs/arcade**.
2. Open the main menu using **Start** on a controller or the on-screen menu button.
3. Open **Game library**, grant **All files access** when required for scanning, and choose **Browse for ROM folder…**.
4. If you already have ES-DE artwork or videos, choose **Browse for media data folder…** as well.
5. Select **Save & rescan library**, return Home, choose a system, and select a game.

Supply your own game files and any required BIOS files. ROMs and BIOS files are not included in this repository.

## Choose how games play

**Built-in player:** open **Built-in player** in the main menu. Choose whether to use it for every supported system or only when an external emulator is missing. Download engines for your systems, add required BIOS files, and adjust on-screen controls, picture shape, and speed settings. Initial engine downloads need an internet connection.

**External emulator or RetroArch:** install and configure the emulator first. In **Emulator settings**, scan for installed emulator apps and RetroArch cores. Select a system on Home, press **Start**, and use that system's settings to choose its emulator or core. Install RetroArch cores inside RetroArch; scanning in Nexus does not install them.

**Android apps and games:** open **Android apps & games** to add installed apps, enable automatic game detection, or add a game that was not detected.

**Windows game entries:** open **Windows games**, select an installed launcher, and add a game's name. Configure and install the actual game inside that launcher. Adding an entry to Nexus does not install a Windows game.

## Controls

| Input | Action while browsing |
| --- | --- |
| Directional controls | Move between systems, games, and menu options |
| A | Select a system or launch a game |
| Hold A on a game | Scrape the game; enter a different search title when needed |
| B | Go back |
| Y on Home | Open favourites |
| Y on a game | Add or remove a favourite |
| Select on Home | Open recently played |
| Select on a game | Show details |
| X on a game | Open guides |
| Hold X on a game | Open cheats |
| Start / on-screen menu | Open settings |
| Touch | Tap to select; tap again to open |

Follow the on-screen control hints for the current page. In-game controls are handled by the player or emulator.

## Add artwork and videos

Open **Scraper** and choose missing artwork for all systems, the selected system only, or a complete re-scrape. Hold **A** on one game to scrape it individually and correct its search title.

Enable arcade gameplay videos or Windows game trailers in the scraper settings if desired. Downloads use internet data and storage. Existing console videos in compatible ES-DE media folders are used automatically; console videos are not supplied by the free scraper sources described above.

## Make it your own

Open **Theme & effects** to choose the handheld or arcade cabinet theme, colours, glow, CRT overlay, and Home background. Use **UI settings** for list/grid layouts, text size, spacing, and preview videos. Select a system and press **Start** to change its background, concept art, layout, or Home ordering.

For the optional in-game menu, open **In-game pause menu** and configure the controller combo. Android accessibility access is used for controller access while an external game is running; enable it only if you want that integration. RetroArch save/load integration may also require its network commands setting.

## Troubleshooting

- **No games appear:** check storage access, the ROM folder, system subfolder names, and hidden-system settings, then rescan.
- **A game will not launch:** check the selected emulator/core, installed engine, game format, and required BIOS. Try opening the game directly in the external emulator to verify its setup.
- **Artwork is missing or incorrect:** hold A on the game, correct the search title, and scrape again; check your media folder if using existing artwork.
- **Games run slowly:** try the built-in player's speed presets or the selected engine's settings. Performance is hardware- and game-dependent.
- **An APK update will not install:** Android may reject a different signing key or a lower version. Back up saves and settings before changing installations.

To report an issue, use this repository's **Issues** tab and include the app version, device, Android version, selected system/emulator, and steps to reproduce it.

## Android TV artwork

![Nexus Neon Arcade Android TV banner](03-nexus-tv-banner-1280x720.png)


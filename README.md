# <img src="Images/icon.png" width="32"> Enhanced SCDA Online
A major patch for Splinter Cell: Double Agent's Online mode, fixing bugs and exploits while improving gameplay and map balance.

For a full list of patch notes, refer to the [Patch Notes](PatchNotes.md) page.

## Installation
The latest version of Enhanced SCDA Online can be found in the [Releases](https://github.com/Joshhhuaaa/EnhancedSCDAOnline/releases) page. Please note that versions of Enhanced SCDA Online are not compatible with the default version of the game or previous Enhanced versions.

### Game Setup
- After downloading Enhanced SCDA Online, extract the contents. You will then have an Enhanced SCDA Online folder, which you can place anywhere you like since it's portable.
- Run the game executable, `SCDA_Online.exe` in the System folder to begin playing.
  - If experiencing an error on startup, try running `DXSETUP.exe` in the `Installers\DirectX` directory.
  - If experiencing a crash while loading into the main menu, ensure you have a recording device, such as a microphone or headset, plugged in.
- A script has been included to cap the game's frame rate at 60 FPS during gameplay and menus, while loading screens remain uncapped. This can be configured by editing `Enhanced.ini` in the System folder. It is highly recommended to keep it at 60, as both movement and aiming can feel worse at higher frame rates.
  - While loading screens are no longer endless with this script, if sound is playing during them, they may last longer and could potentially result in disconnection if left on the loading screen for an extended period when connected with other players.
  - If you hear sounds during a loading screen, such as lobby music when the game gets started or ambient sounds from a map when returning to lobby, press `Ctrl+Alt+Delete`, then press `Esc` to force the game to load. Loading should work normally if no sound is present on the loading screen.

### Mouse Polling Rate
Many mice now offer polling rates of 1000 Hz or higher. However, in SCDA Online, higher polling rates may cause issues with your mouse aim. If your mouse allows it, try setting the polling rate to 125 Hz through software.

## Playing Online
Ubisoft discontinued Double Agent's servers in June 2016. However, the multiplayer is still playable using a custom server.

Starting with Enhanced SCDA Online v2.2, the game is updated with a new experimental custom server for online play. No third-party programs are needed to play online.

- There is no account database, so all online accounts are temporary. **Do not use real passwords, as these accounts are not intended to be secure.**
- To log in, enter your username, set the password to `123456`, and set the CD-Key: `SC4-XXXX-XXXX-XXXX-XXXX`. 

Currently, Leaderboards and Squads have not been implemented due to not having an account system in place.

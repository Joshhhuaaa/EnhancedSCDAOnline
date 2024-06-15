# Enhanced SCDA Online Patch Notes

### Gameplay
- Game length has been decreased from 20 minutes to 10 minutes.
- Spies’ respawn time has been decreased from 5 seconds to 0 seconds.
- Spies no longer have access to jammers as the presence sensor is removed.
- Spy: Syringes used to heal yourself now heal at the teammate speed.
- Upsilon Forces’ respawn time has been increased from 5 seconds to 10 seconds.
- Upsilon Forces' neutralize time has been increased from 20 seconds to 60 seconds.
- Upsilon Forces no longer have a presence sensor.
- Upsilon Forces no longer have access to a gadget stock.
- Upsilon Forces no longer have the ability to jump.
- Upsilon Forces no longer have the white outline detection around Spies in motion.
- Upsilon Force: EMF vision remains in focus when moving at full speed.
- Upsilon Force: Increased number of Frag Grenades that can be equipped from 3 to 5.
- Upsilon Force: Increased number of Drones that can be equipped from 2 to 5.
- Upsilon Force: Drones have an increased range from 30 meters to infinite.

### Interface
- The sound when entering a new zone on the strategic map has been removed.
- The circular goggle borders around the Spy HUD have been removed due to the animation being bugged on the PC version.
- The helmet borders and EMF bars present on Upsilon Force HUD have been removed.
	
### Miscellaneous
- The game is updated with a new experimental custom server for online play. No third-party programs are needed to play online.
- A script has been included to cap the game's frame rate at 60 FPS during gameplay and menus, while loading screens remain uncapped. This can be configured by editing `Enhanced.ini` in the System folder.
  - This doesn't always fix the Endless Loading bug. If you hear sounds during a loading screen, such as lobby music when starting a game or ambient sounds from a map when returning to the lobby, press `Ctrl+Alt+Delete` and then press `Esc` to force the game to load. If no sound is present on the loading screen, it should load normally.
- High Quality Transparency has been enabled by default in the configuration file.
- Modern resolution support added from 1600x900, 1920x1080, 2560x1440, and 3840x2160.
- Female Spies have been activated in the Skins selection menu.
	- Note: In the PC version, Female Spies are bugged. When using a throwable gadget such as Flash Grenades or Smoke Grenades while in the air, it will not spawn at your character but instead at the origin point (0,0,0) on the map.
- Bonus and Help Videos have been removed to save disk space.
- Profiles can easily be accessed using the shortcut added in the System subfolder.
- Xbox control binds have been set automatically for newly created profiles.

### Maps
- Blackwing:
  - The alternative security lights linked to the blue projector at Blue Terminal have been removed. 
  - Yellow Terminal's grilled window is now open making it easier to see inside the container.
  - The underground below Yellow Terminal no longer has pipes blocking access for Upsilon Forces.
---
- Dawn Waves:
  - Helicopter in the Spy insertion point has been restored from the Xbox 360 version.
---
- Motorway 90:
  - Removed emergency lights near Yellow Terminal's outside catwalk.
  - Removed emergency light near Yellow Terminal's exit door to the ECC.
  - Removed light near the second floor's top vent in Yellow Terminal.
  - *Bug fixed:* A visual bug in Thermal / EMF vision near the Upsilon Force spawn.
  - *Bug fixed:* A visual bug outside the gate by Blue Terminal.
---
- Red Diamond:
  - Blue Terminal has been placed more towards the wall to prevent performing a 3-bar in the ceiling.
  - The extraction path above the wine cellar is now a one-way drop and is no longer accessible once dropping towards the ECC.
  - Red Terminal has been moved to the first floor of Yellow Terminal's room making it easier to guard for Upsilon Forces.
---
- Terminus:
  - Yellow Terminal has been moved to a new downward position to prevent performing a 3-bar on the second floor.
  - A stool has been moved to prevent hacking Blue Terminal under the bus.
---
- Slaughterhouse:
  - A box has been moved to prevent hacking Blue Terminal through the small gap in the underground.
  - *Bug fixed:* Removed a useless “Disable Light” interaction in the Spy insertion point.
---
- USS Wisdom:
  - Red Terminal has been moved to a new downward position to prevent hacking through the small gap in the vent.

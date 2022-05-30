# Changelog

Follow the latest changes on GitHub: https://github.com/fadeinside/s3air-blue-spheres-time-attack

## Patch v2.0.1 - The Patched 1

### Fixed
* Fixed when timer was not reset after re-entering a special stage in the main game (Found Quix64).
* Fixed an error occurred in calling the DAGE Challenge menu (Found MicMic, solved by Thorn).

## Release v2.0 - The Release 2

Today's release brings widespread improvements, bug fixes, rework, new functions and capabilities, and more.  
Stay tuned, there are many more amazing ideas ahead! Expect in the next v3.0 release such things as an expanded selection of medals, Discord Rich Presence, more extra content, and more. Until then, we will have 28-day mod support with patch updates, please report any bugs during this period. Cheers! -Fade

### New
* Added integration with "Blue Sphere Plus" by Veenee (Install it below).
* Added integration with "Sonic 3: D.A. Garden Edition" by Thorn_SRetro (Install it below, and below "Blue Sphere Plus").
* Added integration with "Extra Character Slots" by iCloudius, Lave slime (Install it below).
* Added compatibility with "Accurate Sonic 2 HUD" by mcginnis03 (Can be installed in any order).
* Knuckles records, with the option of hard special stages (DAGE feature) active, will be saved separately.
* Added Sonic 3K selection in the Lobby ("Blue Sphere Plus" feature)
* Added Green sphere game selection in the Lobby ("Sonic 3: D.A. Garden Edition" feature)
* In the Green sphere game mode ("Sonic 3: D.A. Garden Edition" feature), with Blue Sphere Plus active, the Perfects will be saved separately from the Blue sphere game.
* Added the ability to delete all recorded data in the custom Options menu.
* Added the option to disable "Not Enough Rings".
* Added on-screen hot-keys to control the menu. You can disable it in the mod settings.
* Added 2 new menu background themes - "Sonic and Knuckles" and "Get Blue Spheres"
* Added the option to display the spheres of the selected stage on the background of the menu with the "Special stage ground" theme active.
* Added personalization options for the Achievement toast.
* Added a choice to go to the Achievements menu in the Lobby.
* Added scrolling through the list of achievements in the achievements menu.
* Added a queue of achievements. Now when you get multiple achievements at the same time, toast will show each one in turn, instead of showing them all at the same time.
* Improved pricing and scoring of achievements.
* Added a new menu and Medals that you get for completing achievements.
* Added a completely new tooltip system. When you click an unavailable item, or when performing some action, a tooltip will be displayed with additional information about it.
* Added extra content stuff.

### Improvements
* The timer render is now a separate function so that it can be modified in other mods without interfering with the mechanics of the timer itself.
* Redesign of the Achievement toast. Now it is compact, stylish, and does not interfere with the gameplay.
* Redesign of the item selected in the menu. Instead of stars, bumpers corresponding to the color of the selected character will now be shown.
* Redesign of the Achievements menu. Added scroll bar, updated icons, added sorting by pressing [A] key by completed, started and not started achievements, and also other visual improvements.
* Improved descriptions and goals of some achievements.
* Improved the design of the achievements popup in the achievements menu.
* Transitions between custom menus have been improved and accelerated. 
* The tags of all achievements have been revised, now they are more suitable for the complexity of execution.
* Refactoring of all/most of the code and its optimization.
* The logo has been changed.

### Fixes
* Fixed bugs noticed when logging into the Blue Sphere game via the Lobby.
* Fixed duplicate sound when logging into Blue Sphere game via Lobby.
* Fixed invalid achievement tag for ACHIEVEMENT_BS_CONVERT_1200_GREEN_SPHERES.
* Fixed the display of the Achievement toast during a pause.
* Fixed when you couldn't open popup for "Require a mod" Achievements.
* Other bugs that were most likely fixed, but were not taken into account here.

## Update v1.0.2a (v1.03) - The distorter fix

I'm sorry for this absurdity. GitHub compressed some images, as a result of which they could not be read by the S3 A.I.R. compiler. This update fixes this. -Fade

* Fixed A.I.R couldn't read .png files.
* Fixed A.I.R couldn't find icon_unlock sprite.

## Update v1.0.2 (v1.02) - Stability improvements

Today's update fixes the bugs you have noticed, and also makes few changes and improvements to each corner of mod. Thanks! :3 -Fade

* Added 14 New Achievements, Achievements tags and score. Check the achievements menu.
* Fixed when you could play for "Sonic and Tails" in the standard Blue Sphere mini-game, given that only one Sonic is selected.
* Fixed when the Green Sphere from D.A. Garden was counted as a Yellow sphere in the achievements manager.
* Fixed when Mighty was always the main character after you played for him for one time.
* Fixed when you could open custom pause menu in the standard Blue Sphere mini-game.
* Fixed when after Time over in Time Attack mode, you back to Shared menu, instead of Time attack menu.
* Fixed when you could switch S3/S&K levels without even unlocking them.
* Fixed getting achievements at special stages of the main levels (i hope).
* Now reset achievements also reset emeralds.
* Now for Locked/Unknown achievements detail popup can't be opened.
* Optimized some functions.

## Update v1.0.1 (v1.01) - The bug-fix

* Fixed a graphical bug when switching to a standard BS mini-game via the Lobby.
* Fixed a bug where, after the standard BS mini-game, switching to time attack mode, the level of the mini-game was always active, even after switching the level.
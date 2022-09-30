# IE:EE Game Speed Mod

### Current version 1.0.5
The way Infinity Engine works is that game speed is directly tied to how fast the engine is rendering - therefore attempting to double the default speed to 60 frames per second consequently speeds up the in-game time as well. That affects how much time the player has to complete any timed objectives/quests as well as how long spells, potions etc. last. This project is a game speed mod that attempts to fix that problem. Once loaded game runs at 60 FPS but the time is left untouched!

Since combat may feel overly fast when playing at 60 FPS this mod introduces a "Slack Combat" feature - anytime hostile creatures are encountered game speed is reverted to default (30 FPS) until all monsters are dealt with.

Currently supported games:

* Baldur's Gate Enhanced Edition
* Baldur's Gate II Enhanced Edition

#### Only Windows version.

# How to use

1. [Download](https://github.com/Nesae-avi/IE-EE-GameSpeedMod/releases/latest) and unpack the release.
2. Copy the `SpeedMod_Launcher.exe` and the appropriate dll to the game root directory.
3. Launch the game by double clicking on `SpeedMod_Launcher.exe`.
4. Optionally create a desktop shortcut to the loader's executable.

## Hotkey

* F10 - Show console.
* F11 - Enable/Disable the mod.
* F12 - Enable/Disable slack combat.

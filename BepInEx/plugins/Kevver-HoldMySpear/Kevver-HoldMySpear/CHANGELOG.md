## Changelog
### 1.2.0
* Updated for Valheim v0.221.3 PTB (might work on v0.220.5 standard)

### 1.1.1
* Remove handling of legacy item attributes on drop.

### 1.1.0
* Bumped minor version due to configuration changes
* Added General.configLocked configuration option
    * This option locks the configuration to a server-provided config
* Renamed General.isModEnabled -> General.enabled
* Added Keybinds.disown keyboard shortcut
* Removed dead code of item loading; world/client takes care of that
* Produce dynamic Keybinds.disown hotkey display when hovering over the spear

### 1.0.10
* Added Buy Me A Coffee info to README

### 1.0.7-1.0.9
* Added ServerSync and locked isModEnabled configuration option

### 1.0.6
* Added the ability to disown a dropped spear

### 1.0.5
* Stops spears owned by other players from being able to be moved from a storage to the player inventory

### 1.0.4
* Added ownership details to spear tooltips
* Added a message display when trying to pickup a spear that isn't yours

### 1.0.3
* This version included 1.0.1-1.0.2, which was essentially a proof of concept
version of this mod, and the version needed to be bumped to change associated
teams before continuing with mod development

<p align="center"><img src="https://i.imgur.com/wlKugPa.png" alt="Horse"></p>
<p align="center"><img src="https://i.imgur.com/XNHUnIX.png" alt="Horse"></p>

# OdinPlus Mod Team Presents: Horse
**Produced by: Raelaziel#0954 - Maintained by GraveBear**

## About

Horse is a custom creature mod that adds a new rideable animal and a variety of new items to Valheim. You can tame it, ride it, have it pull your horse cart, breed it, and store items in its saddlebags.

> ⚠️ **Warning:** Please delete your old `.cfg` file and allow a new one to generate on first launch.
> ⚠️ **Note:** This mod may not be compatible with SkilledCarryWeight.
> ⚠️ **Reminder:** Use this mod at your own risk. Always back up your character and world files before installing or updating.

---

## Features

- Horses spawn in the Meadows biome, and only on sunny days — so they are intentionally rare.
- Horses may spawn with different coat textures and patterns.
- Horses can be equipped with horse armor, granting a bonus to health.
- Horses can be commanded to **Wait Here** with a configurable hotkey.
- Horses can pull the horse cart.
- Horses can be tamed using Blueberries, Carrots, Cloudberries, and Barley.
- Tamed, saddled horses can carry a **saddlebag inventory**, accessible with a configurable hotkey (default: **B**). Saddlebag size is fully configurable. Items stored in the saddlebags will drop on the ground if the horse dies. **Disabled by default — enable in the config when ready.**
- Horse offspring will flee from players — keep the area enclosed when breeding.
- Taming and growth times are roughly equivalent to those of the Lox.
- **All of the above is configurable via the config file, and syncs with server/admin settings.**

---

## Creatures & Items

Every item uses the `rae_` prefix — use it to search for or spawn any item from this mod.

| Type | Name | Notes & Requirements | Details | Version |
| --- | --- | --- | --- | --- |
| Creature | Horse | Spawns in the Meadows during daytime | Can be tamed; eats Blueberries, Carrots, Cloudberries, and Barley | 0.1.0 |
| Creature | Horse Offspring | Obtained through breeding | Eats Blueberries, Carrots, Cloudberries, and Barley | 0.1.0 |
| Material | Horse Meat | Drops from Horse and Horse Offspring | Food crafting material | 0.1.0 |
| Material | Horse Hide | Drops from Horse and Horse Offspring | Used in items and building pieces | 0.1.0 |
| Trophy | Horse Trophy | Drops from Horse | Crafting material and decoration | 0.2.0 |
| Food | Horse Meat Skewer | Crafted at **Cauldron**<br/>- Horse Meat<br/>- Mushroom<br/>- Neck Tail | HP: 25 · SP: 65 · Duration: 1600s · 4 HP/tick | 0.3.0 |
| Food | Soup from Horse Meat | Crafted at **Cauldron**<br/>- Horse Meat<br/>- Carrot<br/>- Dandelion | HP: 35 · SP: 40 · Duration: 1500s · 3 HP/tick | 0.3.0 |
| Food | Horse Sticks | Crafted at **Cauldron**<br/>- Horse Meat<br/>- Coal<br/>- Dandelion | HP: 50 · SP: 22 · Duration: 2000s · 3 HP/tick | 0.3.0 |
| Item | Horse Saddle | Crafted at **Workbench**<br/>- Fine Wood<br/>- Bronze<br/>- Horse Hide | Equip on a tamed horse to ride it and enable saddlebag storage | 0.3.0 |
| Item | Horse Helmet | Crafted at **Workbench**<br/>- Tin<br/>- Horse Hide<br/>- Horse Trophy | Part of the Horseaker set (3 pieces) | 0.3.0 |
| Item | Horse Cape | Crafted at **Workbench**<br/>- Tin<br/>- Horse Hide<br/>- Horse Trophy | Part of the Horseaker set (3 pieces) | 0.3.0 |
| Item | Horseaker Axe | Crafted at **Forge**<br/>- Iron<br/>- Elder Bark<br/>- Horse Trophy | Part of the Horseaker set (3 pieces) | 0.3.0 |
| Item | Skogarmadr Hood | Crafted at **Workbench**<br/>- Horse Hide<br/>- Leather Scraps<br/>- Horse Trophy | Part of the Skogarmadr set (3 pieces) | 1.1.5 |
| Item | Skogarmadr Chest | Crafted at **Workbench**<br/>- Horse Hide<br/>- Leather Scraps | Part of the Skogarmadr set (3 pieces) | 1.1.5 |
| Item | Skogarmadr Legs | Crafted at **Workbench**<br/>- Horse Hide<br/>- Leather Scraps | Part of the Skogarmadr set (3 pieces) | 1.1.5 |
| Item | Drapmadr Mask | Crafted at **Forge**<br/>- Iron<br/>- Horse Hide<br/>- Leather Scraps<br/>- Horse Trophy | Part of the Drapmadr set (3 pieces) | 1.1.5 |
| Item | Drapmadr Chest | Crafted at **Forge**<br/>- Horse Hide<br/>- Leather Scraps<br/>- Iron | Part of the Drapmadr set (3 pieces) | 1.1.5 |
| Item | Drapmadr Legs | Crafted at **Forge**<br/>- Horse Hide<br/>- Leather Scraps<br/>- Iron | Part of the Drapmadr set (3 pieces) | 1.1.5 |
| Piece | Horse Hide Rug | Crafted at **Workbench**<br/>- Horse Hide | Decoration | 0.5.0 |
| Piece | Horsie Chair | Crafted at **Workbench**<br/>- Horse Hide<br/>- Fine Wood | Decoration | 0.5.0 |

---

## Armor Set Bonuses

| Set | Status Effects |
| --- | --- |
| Horseaker | Max carry weight +25 · Resistant to Fire · Movement speed +5% · Riding skill +30 levels |
| Skogarmadr | Jump stamina drain -10% · Run stamina drain -10% · Stamina regeneration +20% · Noise -10% · Sneaking +10% · Movement speed +10% · Fall damage -25% · Knives skill +20 levels |
| Drapmadr | Jump stamina drain -20% · Run stamina drain -20% · Stamina regeneration +30% · Noise -30% · Sneaking +30% · Movement speed +15% · Fall damage -30% · Knives skill +40 levels |

---

## Installation

1. Install BepInEx.
2. Place the mod files into your `/BepInEx/plugins/` folder.

---

## Configuration

A configuration file is generated automatically on first launch once `OdinHorse.dll` is installed. All settings sync with the server when Server Sync is in use.

The mod supports custom localization. To add a translation, copy `OdinHorse.Polish.yml`, rename it with your language, and translate the contents using any text editor.

Configurable settings include:

- **Creature** — Health, speeds, taming time, food duration, and more
- **Spawn** — Spawn chance, biome, weather conditions, group size, and more
- **Horse Procreation** — Pregnancy chance, duration, partner range, max creatures, and more
- **Horse Offspring** — Health, growth time, and drop rates
- **Hotkeys** — Remove Armor key, Wait Here key, and Saddlebags key
- **Saddlebags** — Enable/disable (disabled by default), inventory width (columns), and inventory height (rows)
- **Map Icons** — Show or hide horse and cart map pins
- **Items & Food** — Crafting requirements and stats

---

## Credits

- **KG** — Help with map pins and general support
- **Azumatt** — Piece Manager and invaluable help
- **Blaxxun** — Creature Manager and Item Manager
- **Zorboz & GraveBear** — OdinPlus Team, Discord channel, and help with Horse development
- **DorlickTheDerelict, Sebaugar, Pavlo**, and everyone who helped with testing

---

<p align="center"><h2>For questions or comments, find Gravebear in the OdinPlus Team Discord:</h2></p>

<p align="center"><a href="https://discord.gg/mbkPcvu9ax"><img src="https://i.imgur.com/Ji3u63C.png"></a></p>

<p align="center">Visit my Buy Me a Coffee page for a free admin-craft Shark Hat and Tuna Sword!</p>

<p align="center"><a href="https://www.buymeacoffee.com/Gravebear"><img src="https://noobtrap.eu/images/crystallights/GBSupporter.png"></a></p>
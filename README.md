# Valheim-NeonPack

A collection of mods from Thunderstore that I use in my singleplayer world

I've included the configuration files for all the mods that have them in the [github for this modpack][github-extras]

I also use the following mods from NexusMods

_Required:_

- [Combat Evolved 0.4.0][combat-evolved]
- [Cooking Skill 1.1.1][cooking-skill]
- [Fitness Skill 1.0.2][fitness-skill]
- [Minimap Plus 2.1.1][minimap-plus]
- [Mod Config Enforcer 1.1.0][mod-config-enforcer]
- [Planting Plus 1.4.5][planting-plus]
- [Sleep Without Spawn 0.1.1][sleep-without-spawn]

_Optional:_

- [Better Pickup Notifications 1.0.0][better-pickup-notifications]
- [Clock 1.1.1][clock]
- [Configurable Autosave 1.1.0][configurable-autosave]
- [Loki's First Person Valheim Mod 1.0.6][lokis-first-person]
- [Loki's Immersion Mods 1.0.3][lokis-immersion]
- [Nexus Update Check 1.1.1][nexus-update-check]
- [Useful Paths 1.0.4][useful-paths]

I've included a template with an icon and an empty mod manifest.json in the [github for this modpack][github-extras] to help add compatibility for NexusMods mods with r2modmanager

Simply add both files to the mod's .zip, then modify the manifest.json with the relevant mod's information

You can then do a simple drag'n'drop installation in r2modmanager with the .zip

## Changelog

```text
Version 1.11.0

# How to Upgrade Equipment and Quick Slots 1.x to 2.0.0 (as written by mod author)
  1. Start the game with the old mod installed
  2. Find a safe place for your character
  3. Unequip all equipment and move everything out of the quick slots
  4. Quit the game using the menu
  5. Remove the old 'Equipment and Quick Slots' dll and install the new version
  6. Run the game again
  7. You should see your new empty slots in the inventory and be able to re-equip your items

[Thunderstore]

  + Added Comfort Calculation Tweaks 1.2.2
  + Added Gathering Skill 2.0.3
  + Added Skill Injector 1.1.1

  - Removed Bigger Boat Map Explore Radius
    - Replaced by Minimap Plus
  - Removed Explore Together
    - Replaced by Minimap Plus

  * Updated Better UI
    - 1.5.1 -> 1.6.0
  * Updated Equipment and Quick Slots
    - 1.0.5 -> 2.0.0
  * Updated Epic Loot
    - 0.5.12 -> 0.5.13
  * Updated Sated
    - 1.0.1 -> 1.0.2

[NexusMods]

  + Added Minimap Plus 2.1.1

  - Removed Comfort Calculation Fix
    - Replaced by Comfort Calculation Tweaks
  - Removed Gathering Skill
    - Replaced by Thunderstore version of mod
  - Removed Pickable Time Fix
    - Functionality added by Gathering Skill
  - Removed Skill Injector
    - Replaced by Thunderstore version of mod

  * Updated Cooking Skill
    - 1.0.1 -> 1.1.1
  * Updated Mod Config Enforcer
    - 1.1.0 -> 1.2.0
```

```text
Version 1.10.2

[Thunderstore]

  * Updated Emote Wheel
    - 1.1.0 -> 1.2.0
```

```text
Version 1.10.1

[Thunderstore]

  - Removed Invis Helm
    - See Issue #2 on Github
```

```text
Version 1.10.0

[Thunderstore]

  + Added Invis Armor 1.3.0
  + Added Invis Helm 1.1.2

  - Removed It's Just Wood
    - Never made use of the mod

  * Updated Epic Loot
    - 0.5.11 -> 0.5.12
  * Updated Sated
    - 1.0.0 -> 1.0.1

[NexusMods]

  + Added Better Pickup Notifications 1.0.0
  + Added Cooking Skill 1.0.1

  * Updated Clock
    - 0.9.1 -> 1.1.1
  * Updated Comfort Calculation Fix
    - 1.0.0 -> 1.2.1
  * Updated Mod Config Enforcer
    - 1.0.0 -> 1.1.0
```

```text
Version 1.9.0

[Thunderstore]

  + Added Sated 1.0.0

  * Updated Emote Wheel
    - 1.0.1 -> 1.1.0
  * Updated Epic Loot
    - 0.5.9 -> 0.5.11
  * Updated Simple Recycling
    - 0.0.12 -> 0.0.13

[NexusMods]

  + Added Mod Config Enforcer 1.0.0

  * Updated Clock
    - 0.8.4 -> 0.9.1
  * Updated Combat Evolved
    - 0.3.3 -> 0.4.0
  * Updated Gathering Skill
    - 1.2.2 -> 1.3.0
  * Updated Nexus Update Check
    - 1.1.0 -> 1.1.1
```

```text
Version 1.8.0

[Thunderstore]

  + Added Epic Loot 0.5.9
  + Added Extended Item Data FrameWork 1.0.0

  - Removed Hook Gen Patcher
    - See Issue #1 on Github
  - Removed Lead
    - See Issue #1 on Github
  - Removed Valheim Lib
    - See Issue #1 on Github

  * Updated Simple Recycling
    - 0.0.11 -> 0.0.12

[NexusMods]

  * Updated Gathering Skill
    - 1.2.0 -> 1.2.2
  * Updated Useful Paths
    - 1.0.0 -> 1.0.4
```

```text
Version 1.7.0

[Thunderstore]

  + Added Emote Wheel 1.0.1
  + Added Quick Stack 0.6.3
  + Added Skip Intro 1.0.1
  + Added Valheim Brawler 0.0.4

  - Removed Quick Deposit
    - Similar feature added by Quick Stack

  * Updated Better Auto Run
    - 1.0.2 -> 1.0.3
  * Updated Bigger Boat Map Explore Radius
    - 1.0.0 -> 1.0.3
  * Updated Explore Together
    - 1.2.0 -> 1.2.2
  * Updated Simple Recycling
    - 0.0.10 -> 0.0.11

[NexusMods]

  + Added Comfort Calculation Fix 1.0.0
  + Added Sleep Without Spawn 0.1.1
  + Added Useful Paths 1.0.0

  - Removed Emote Keys
    - Similar feature added by Emote Wheel

  * Updated Fitness Skill
    - 1.0.1 -> 1.0.2
  * Updated Gathering Skill
    - 1.0.2 -> 1.2.0
  * Updated Nexus Update Check
    - 0.9.2 -> 1.1.0
```

```text
Version 1.6.2

[NexusMods]

  - Removed Precise Rotation
    - Similar feature added by Gizmo
```

```text
Version 1.6.1

[Thunderstore]

  * Updated Valheim Lib
    - 0.0.6 -> 0.0.7
```

```text
Version 1.6.0

[NexusMods]

  + Added Configurable Autosave 1.1.0

  * Updated Combat Evolved
    - 0.3.2 -> 0.3.3
  * Updated Fitness Skill
    - 1.0.0 -> 1.0.1
```

```text
Version 1.5.1

[Thunderstore]

  - Removed Fermenter Percentage
    - Similar feature added by Better UI
```

```text
Version 1.5.0

[Thunderstore]

  + Added Gizmo 1.0.0
  + Added Jam 1.0.2
  + Added Multiplayer Boat Damage 0.0.1

  * Updated Better UI
    - 1.5.0 -> 1.5.1
  * Updated Explore Together
    - 1.1.2 -> 1.2.0
  * Updated Hook Gen Patcher
    - 0.0.1 -> 0.0.2
  * Updated Multi Craft
    - 0.2.2 -> 0.2.6
  * Updated Simple Recycling
    - 0.0.9 -> 0.0.10
  * Updated Valheim Lib
    - 0.0.5 -> 0.0.6

[NexusMods]

  + Added Fitness Skill 1.0.0

  * Updated Combat Evolved
    - 0.3.1 -> 0.3.2
  * Updated Nexus Update Check
    - 0.9.1 -> 0.9.2
  * Updated Planting Plus
    - 1.3.0 -> 1.4.5
  * Updated Skill Injector
    - 1.0.1 -> 1.0.2
```

```text
Version 1.4.0

[NexusMods]

  + Added Planting Plus 1.3.0

  * Updated Nexus Update Check
    - 0.8.1 -> 0.9.1
```

```text
Version 1.3.1

  # Initial Release on Thunderstore
```

[github-extras]: https://github.com/NeonCarbide/Valheim-NeonPack/tree/main/extras
[issue-1]: https://github.com/NeonCarbide/Valheim-NeonPack/issues/1

<!-- Mod Links -->

[better-pickup-notifications]: https://www.nexusmods.com/valheim/mods/528
[clock]: https://www.nexusmods.com/valheim/mods/85
[combat-evolved]: https://www.nexusmods.com/valheim/mods/301
[configurable-autosave]: https://www.nexusmods.com/valheim/mods/199
[cooking-skill]: https://www.nexusmods.com/valheim/mods/483
[fitness-skill]: https://www.nexusmods.com/valheim/mods/388
[gathering-skill]: https://www.nexusmods.com/valheim/mods/342
[lokis-first-person]: https://www.nexusmods.com/valheim/mods/100
[lokis-immersion]: https://www.nexusmods.com/valheim/mods/139
[minimap-plus]: https://www.nexusmods.com/valheim/mods/242
[mod-config-enforcer]: https://www.nexusmods.com/valheim/mods/460
[nexus-update-check]: https://www.nexusmods.com/valheim/mods/102
[planting-plus]: https://www.nexusmods.com/valheim/mods/274
[sleep-without-spawn]: https://www.nexusmods.com/valheim/mods/261
[useful-paths]: https://www.nexusmods.com/valheim/mods/438

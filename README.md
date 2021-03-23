# Valheim-NeonPack

A collection of mods from Thunderstore that I use in my singleplayer world

I've included a list of all the config changes I've made in the [github for this modpack][github-extras]

I also use the following mods from NexusMods

_Required:_

- [Better Trader 1.0.6][better-trader]
- [Crush Antlers 0.1.0][crush-antlers]
- [Fitness Skill 1.0.3][fitness-skill]
- [Mod Config Enforcer 1.3.0][mod-config-enforcer]

_Optional:_

- [Better Pickup Notifications 1.2.0][better-pickup-notifications]
- [Clock 1.1.1][clock]
- [Configurable Autosave 1.1.0][configurable-autosave]
- [Loki's First Person Valheim Mod 1.0.6][lokis-first-person]
- [Loki's Immersion Mods 1.0.3][lokis-immersion]
- [Nexus Update Check 1.1.1][nexus-update-check]

I've included a template with an icon and an empty mod manifest.json in the [github for this modpack][github-extras] to help add compatibility for NexusMods mods with r2modmanager

Simply add both files to the mod's .zip, then modify the manifest.json with the relevant mod's information

You can then do a simple drag'n'drop installation in r2modmanager with the .zip

## [Changelog][changelog]

Rather than continue to make this README even longer, I've seperated the changelog into its own page for ease of use

I will maintain a trimmed version of the full changelog within this README of only the most recent minor update and any subsequent patches

### Recent Updates

Version 2.2.0

```text
[Thunderstore]

  - Removed Data Rate Modifier
    - 0.148.6 Valheim patch hopefully deprecated this
    - Probable cause of world loading issue
  - Removed Quick Stack
    - 0.148.6 Valheim patch broke some functionality of the mod
    - Waiting on fix from mod dev

  * Updated Better UI
    - 1.6.3 -> 1.6.4
  * Updated Epic Loot
    - 0.5.16 -> 0.6.3
  * Updated Equipment and Quick Slots
    - 2.0.3 -> 2.0.4
  * Updated Speedy Paths
    - 1.0.3 -> 1.0.4
  * Updated Valheim Armorstand
    - 0.0.1 -> 0.0.2
  * Updated Valheim Brawler
    - 0.0.4 -> 0.0.6

[NexusMods]

  - Removed Combat Evolved
    - 0.148.6 Valheim patch broke projectile interaction with the mod
    - Waiting on fix from mod dev
  - Removed Cooking Skill
    - 0.148.6 Valheim patch broke fermenter functionality
    - Waiting on fix from mod dev
  - Removed Fish Food
    - AssetBundle failing to load
    - Waiting on fix from mod dev
  - Removed Planting Plus
    - Issues regarding desync with certain interactables and combat
    - Waiting on fix from mod dev
  - Removed Sleep Without Spawn
    - Never really used the mod
    - Probable cause of world loading issue
```

[changelog]: https://github.com/NeonCarbide/Valheim-NeonPack/blob/main/CHANGELOG.md
[github-extras]: https://github.com/NeonCarbide/Valheim-NeonPack/tree/main/extras
[issue-1]: https://github.com/NeonCarbide/Valheim-NeonPack/issues/1

<!-- Mod Links -->

[better-pickup-notifications]: https://www.nexusmods.com/valheim/mods/528
[better-trader]: https://www.nexusmods.com/valheim/mods/433
[clock]: https://www.nexusmods.com/valheim/mods/85
[combat-evolved]: https://www.nexusmods.com/valheim/mods/301
[configurable-autosave]: https://www.nexusmods.com/valheim/mods/199
[cooking-skill]: https://www.nexusmods.com/valheim/mods/483
[crush-antlers]: https://www.nexusmods.com/valheim/mods/590
[fish-food]: https://www.nexusmods.com/valheim/mods/531
[fitness-skill]: https://www.nexusmods.com/valheim/mods/388
[gathering-skill]: https://www.nexusmods.com/valheim/mods/342
[lokis-first-person]: https://www.nexusmods.com/valheim/mods/100
[lokis-immersion]: https://www.nexusmods.com/valheim/mods/139
[mod-config-enforcer]: https://www.nexusmods.com/valheim/mods/460
[nexus-update-check]: https://www.nexusmods.com/valheim/mods/102
[planting-plus]: https://www.nexusmods.com/valheim/mods/274

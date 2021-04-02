# Valheim-NeonPack Changelog <!-- omit in toc -->

This modpack uses the [semantic versioning](https://semver.org) convention of `MAJOR.Minor.patch`

## _Sorted by Most Recent_ <!-- omit in toc -->

- [Version 2.x.x](#version-2xx)
  - [2.8.0](#280)
  - [2.7.0](#270)
  - [2.6.0](#260)
  - [2.5.0](#250)
  - [2.4.0](#240)
  - [2.3.0](#230)
  - [2.2.0 - IMPORTANT](#220---important)
  - [2.1.x](#21x)
    - [2.1.1 - IMPORTANT](#211---important)
    - [2.1.0](#210)
  - [2.0.0](#200)
- [Version 1.x.x](#version-1xx)
  - [1.13.0](#1130)
  - [1.12.0](#1120)
  - [1.11.x](#111x)
    - [1.11.2](#1112)
    - [1.11.1](#1111)
    - [1.11.0 - IMPORTANT](#1110---important)
  - [1.10.x](#110x)
    - [1.10.2](#1102)
    - [1.10.1](#1101)
    - [1.10.0](#1100)
  - [1.9.0](#190)
  - [1.8.0](#180)
  - [1.7.0](#170)
  - [1.6.x](#16x)
    - [1.6.2](#162)
    - [1.6.1](#161)
    - [1.6.0](#160)
  - [1.5.x](#15x)
    - [1.5.1](#151)
    - [1.5.0](#150)
  - [1.4.0](#140)
  - [1.3.1](#131)

---

### Version 2.x.x

---

#### 2.8.0

```text
[Thunderstore]

  * Updated Beehive Utilities
    - 1.0.1 -> 1.1.0
  * Updated Creature Level and Loot Control
    - 3.2.2 -> 3.4.0
  * Updated Equip Wheel
    - 1.3.1 -> 1.3.3
  * Updated Pathfinder
    - 1.0.2 -> 2.0.3

[NexusMods]

  + Added Compass 0.4.0

  * Updated Cooking Skill
    - 1.1.3 -> 1.1.4
  * Updated More Skills
    - 0.1.61 -> 0.1.7
```

#### 2.7.0

```text
[Thunderstore]

  * Updated Creature Level and Loot Control
    - 3.2.0 -> 3.2.2
  * Updated Proper Portals
    - 1.0.2 -> 1.1.0

[NexusMods]

  + Added Configuration Manager 0.3.3
  + Added Peek In Container 1.0.0

  * Updated Combat Evolved
    - 0.4.1 -> 0.4.2
  * Updated More Skills
    - 0.1.54 -> 0.1.61
```

#### 2.6.0

```text
# 0.148.7 Valheim patch

[Thunderstore]

  + Added Name Tamed Animals 1.0.0

  * Updated Creature Level and Loot Control
    - 3.0.0 -> 3.2.0
  * Updated Equip Wheel
    - 1.3.0 -> 1.3.1
  * Updated Fast Tools
    - 1.0.3 -> 1.1.0
  * Updated Remove Death Pins
    - 5.4.901 -> 5.4.902

[NexusMods]

  - Removed Better Trader
    - Causing long app start times due to loading 200+ trade options
    - Will try to find replacement

  * Updated More Skills
    - 0.1.5 -> 0.1.54
```

#### 2.5.0

```text
[Thunderstore]

  + Added Beehive Utilities 1.0.1

  * Updated BepInEx
    - 5.4.900 -> 5.4.901
  * Updated Creature Level and Loot Control
    - 2.5.2 -> 3.0.0
  * Updated Equip Wheel
    - 1.2.3 -> 1.3.0
  * Updated Jotunn Lib
    - 0.1.2 -> 0.1.4
  * Updated Proper Portals
    - 1.0.1 -> 1.0.2

[NexusMods]

  + Added More Skills 0.1.5
```

#### 2.4.0

```text
[Thunderstore]

  + Added Better Chat 1.4.1
  + Added Colorful Signs 5.4.902
  + Added Equip Wheel 1.2.3
  + Added Remove Death Pins 5.4.901

  * Updated Creature Level and Loot Control
    - 2.4.2 -> 2.5.2
  * Updated Pathfinder
    - 1.0.1 -> 1.0.2
  * Updated Proper Portals
    - 1.0.0 -> 1.0.1
  * Updated Sated
    - 1.1.1 -> 1.1.2

[NexusMods]

  * Updated Mod Config Enforcer
    - 1.3.0 -> 1.4.1
```

#### 2.3.0

```text
[Thunderstore]

  + Added Fast Tools 1.0.3
  + Added Proper Portals 1.0.0
  + Added Quick Stack 0.6.5

  - Removed Faster Teleportation
    - Replaced by Proper Portals

  * Updated Creature Level and Loot Control
    - 2.2.0 -> 2.4.2

[NexusMods]

  + Added Combat Evolved 0.4.1
  + Added Cooking Skill 1.1.3
```

#### 2.2.0 - IMPORTANT

```text
# 0.148.6 Valheim patch

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

#### 2.1.x

##### 2.1.1 - IMPORTANT

```text
[Thunderstore]

  ~ Downgraded Epic Loot
    - 0.6.0 -> 0.5.16
    - Many features broken, mod dev working on fixes
```

##### 2.1.0

```text
[Thunderstore]

  + Added Creature Level and Loot Control 2.2.0
  + Added Daisy Chain 1.0.0
  + Added Jotunn Lib 0.1.2

  * Updated BepInEx
    - 5.4.800 -> 5.4.900
  * Updated Better UI
    - 1.6.1 -> 1.6.3
  * Updated Epic Loot
    - 0.5.16 -> 0.6.0
  * Updated Equipment and Quick Slots
    - 2.0.2 -> 2.0.3
  * Updated Pathfinder
    - 1.0.0 -> 1.0.1

[NexusMods]

  - Removed Jotunn Lib
    - Replaced by Thunderstore version of mod

  * Updated Fish Food
    - 1.0.0 -> 1.1.0
  * Updated Fitness Skill
    - 1.0.2 -> 1.0.3
```

#### 2.0.0

```text
# Configs now included with modpack

[Thunderstore]

  + Added Speedy Paths 1.0.3

[NexusMods]

  * Updated Cooking Skill
    - 1.1.1 -> 1.1.2

  - Removed Useful Paths
    - Replaced by Speedy Paths
```

---

### Version 1.x.x

---

#### 1.13.0

```text
[Thunderstore]

  + Added Explore Together 1.3.0
  + Added Pathfinder 1.0.0

  - Removed Invis Armor
    - Ended up not using the mod

  * Updated Epic Loot
    - 0.5.13 -> 0.5.16
  * Updated Prevent Accidental Interaction
    - 1.0.6 -> 1.0.7

[NexusMods]

  - Removed Minimap Plus
    - Replaced by Explore Together and Pathfinder
```

#### 1.12.0

```text
[Thunderstore]

  * Updated Better UI
    - 1.6.0 -> 1.6.1
  * Updated Prevent Accidental Interaction
    - 1.0.4 -> 1.0.6
  * Updated Sated
    - 1.0.2 -> 1.1.1

[NexusMods]

  + Added Better Trader 1.0.6
  + Added Crush Antlers 0.1.0
  + Added Jotunn Lib 0.1.1
  + Added Fish Food 1.0.0

  * Updated Better Pickup Notifications
    - 1.0.0 -> 1.2.0
  * Updated Mod Config Enforcer
    - 1.2.0 -> 1.3.0
  * Updated Useful Paths
    - 1.0.4 -> 1.0.5

  # Made Useful Paths a required mod instead of an optional one
```

#### 1.11.x

##### 1.11.2

```text
[Thunderstore]

  * Updated Equipment and Quick Slots
    - 2.0.1 -> 2.0.2
```

##### 1.11.1

```text
[Thunderstore]

  * Updated Equipment and Quick Slots
    - 2.0.0 -> 2.0.1
  * Updated Prevent Accidental Interaction
    - 1.0.3 -> 1.0.4
```

##### 1.11.0 - IMPORTANT

```text
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

#### 1.10.x

##### 1.10.2

```text
[Thunderstore]

  * Updated Emote Wheel
    - 1.1.0 -> 1.2.0
```

##### 1.10.1

```text
[Thunderstore]

  - Removed Invis Helm
    - See Issue #2 on Github
```

##### 1.10.0

```text
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

#### 1.9.0

```text
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

#### 1.8.0

```text
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

#### 1.7.0

```text
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

#### 1.6.x

##### 1.6.2

```text
[NexusMods]

  - Removed Precise Rotation
    - Similar feature added by Gizmo
```

##### 1.6.1

```text
[Thunderstore]

  * Updated Valheim Lib
    - 0.0.6 -> 0.0.7
```

##### 1.6.0

```text
[NexusMods]

  + Added Configurable Autosave 1.1.0

  * Updated Combat Evolved
    - 0.3.2 -> 0.3.3
  * Updated Fitness Skill
    - 1.0.0 -> 1.0.1
```

#### 1.5.x

##### 1.5.1

```text
[Thunderstore]

  - Removed Fermenter Percentage
    - Similar feature added by Better UI
```

##### 1.5.0

```text
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

#### 1.4.0

```text
[NexusMods]

  + Added Planting Plus 1.3.0

  * Updated Nexus Update Check
    - 0.8.1 -> 0.9.1
```

#### 1.3.1

```text
  # Initial Release on Thunderstore
```

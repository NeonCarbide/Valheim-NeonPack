# Valheim-NeonPack - Extras <!-- omit in toc -->

All the changes I've made to the configuration files for the mods included in [NeonPack][neonpack]

I've also included my template files for adding r2modmanager compatibility to NexusMods mods in the [template folder][templates]

## Config Change Example <!-- omit in toc -->

### Example Mod Name <!-- omit in toc -->

Config Section

```text
Variable to Change
  Default  ->  New Value
```

## Included Config Changes <!-- omit in toc -->

- [Beehive Utilities](#beehive-utilities)
- [Better Auto Run](#better-auto-run)
- [Better Chat](#better-chat)
- [Better Trader](#better-trader)
- [Better UI](#better-ui)
- [Build Camera](#build-camera)
- [Build Helper](#build-helper)
- [Clock](#clock)
- [Colorful Signs](#colorful-signs)
- [Configurable Autosave](#configurable-autosave)
- [Creature Level and Loot Control](#creature-level-and-loot-control)
- [Epic Loot](#epic-loot)
- [Explore Together](#explore-together)
- [Fitness Skill](#fitness-skill)
- [Gathering Skill](#gathering-skill)
- [Gizmo](#gizmo)
- [Loki's First Person Valheim Mod](#lokis-first-person-valheim-mod)
- [Loki's Immersion Mods](#lokis-immersion-mods)
  - [Hide Crosshair](#hide-crosshair)
  - [Meditation](#meditation)
  - [Minimap](#minimap)
  - [No Health Bars](#no-health-bars)
- [More Skills](#more-skills)
- [Nexus Update Check](#nexus-update-check)
- [Paddle Power](#paddle-power)
- [Prevent Accidental Interaction](#prevent-accidental-interaction)
- [Proper Portals](#proper-portals)
- [Skillful](#skillful)
- [Triple Bronze](#triple-bronze)
- [Useful Trophies](#useful-trophies)
- [Wet and Cold](#wet-and-cold)

---

### Beehive Utilities

2 - General

```text
Disable Proximity Check
  true  ->  false

Max Honey
  4  ->  10
```

### Better Auto Run

General

```text
sprintUntil
  0.5  ->  0.3
```

### Better Chat

Chat

```text
HideDelay
  10  ->  5
```

### Better Trader

General

```text
Wait For Discovery
  false  ->  true

Trader Price Fluctuation
  false  ->  true

Trader Price Fluctuation Frequency
  1  ->  3
```

### Better UI

HUD

```text
enemyLevelStyle
  1  ->  2
```

Item

```text
showCustomTooltips
  true  ->  false
```

### Build Camera

General

```text
Camera_Range_Multiplier
  1  ->  2
```

Hotkeys

```text
Toggle_build_mode
  B  ->  Insert
```

### Build Helper

BuildHelper

```text
WorkbenchRadius
  150  ->  20

BuildDistance
  10  ->  7.5

AreaRepairRadius
  7.5  ->  3
```

### Clock

General

```text
ClockLocationString
  50%,3%  ->  75%,3%

ClockUseShadow
  false  ->  true

ClockFontName
  AveriaSerifLibre-Bold  ->  Norsebold

ClockFontColor
  FFFFFFFF  ->  FFFFFFB3

ClockShadowColor
  000000FF  ->  000000B3

ClockFormat
  HH:mm  ->  fuzzy
```

### Colorful Signs

Color

```text
Default Color
  #ededed  ->  #000000
```

### Configurable Autosave

General

```text
AutosaveInterval
  1200  ->  1800
```

### Creature Level and Loot Control

2 - Creatures

```text
Creatures can spawn with special effects
  Off  ->  On

Creatures can spawn with elemental infusions
  Off  ->  On

Time until camps and dungeons respawn in minutes (0 means disabled, 20 is one ingame day)
  20  ->  140

Creature size increase per star (percentage)
  10  ->  5
```

4 - Bosses

```text
Star chances for bosses (percentages)
  0, 0, 0, 0, 0, 0, 0, 0, 0  ->  30, 15, 5
```

### Epic Loot

Item Colors

```text
Magic Rarity Color
  Blue  ->  Teal

Magic Crafting Material Icon Index
  5  ->  4

Rare Rarity Color
  Yellow  ->  Blue

Rare Crafting Material Icon Index
  2  ->  5

Legendary Rarity Color
  Teal  ->  Yellow

Legendary Crafting Material Icon Index
  4  ->  2
```

Rarity

```text
Magic Rarity Display Name
  Magic  ->  Uncommon

Legendary Rarity Display Name
  Legendary  ->  Artifact
```

### Explore Together

Minimap

```text
CoordsInMinimap
  true  ->  false
```

Pins

```text
ShareDeathMarkers
  false  ->  true

SharedPinOverlapDistance
  1  ->  5
```

### Fitness Skill

Stamina

```text
MaxMultiplier
  1.5  ->  2

RegenMultiplier
  1.5  ->  2
```

### Gathering Skill

Drops

```text
Mode
  Linear  ->  PartialRandom
```

TimeEstimate

```text
Enabled
  true  ->  false
```

### Gizmo

General

```text
resetKey
  V  ->  N
```

### Loki's First Person Valheim Mod

Body

```text
ShowBodyWhenBlocking
  false  ->  true

Modes
  FirstPersonNoHelmet,ThirdPerson  ->  ThirdPerson,FirstPersonNoHelmet
```

Controls

```text
Hotkey
  H  ->  Keypad7
```

### Loki's Immersion Mods

#### Hide Crosshair

Settings

```text
HideCrosshair
  true  ->  false

Hotkey
  P + LeftControl  ->  Keypad8
```

#### Meditation

Settings

```text
EnableMod
  true  ->  false

ShownPinTypes
  Boss  ->  Bed,Boss,Death
```

#### Minimap

Controls

```text
Hotkey
  O + LeftControl  ->  Keypad9
```

#### No Health Bars

Settings

```text
EnableMod
  true  ->  false
```

### More Skills

Enablers: Crafting

```text
Enable Crafting Mod
  true  ->  false
```

Enablers: Hunting

```text
Enable Hunting Bosses Mod
  false  ->  true
```

Enablers: Sailing

```text
Enable Sailing Mod
  true  ->  false
```

Enablers: Sneak

```text
Enable Crouch Speed Mod
  true  ->  false
```

Enablers: Strength

```text
Enable Strength Mod
  true  ->  false
```

Enablers: Swim

```text
Enable Swim Stamina Mod
  true  ->  false
```

Enablers: Vitality

```text
Enable Vitality Mod
  true  ->  false
```

### Nexus Update Check

UI

```text
UpdatesPosition
  {"x":40.0,"y":40.0}  ->  {"x":10.0,"y":360.0}
```

### Paddle Power

General

```text
counting_method
  ATTACHED  ->  SEATED
```

### Prevent Accidental Interaction

General

```text
InteractionBlocklist
  ItemStand,Sign,TeleportWorld  ->  ItemStand,Sign,TeleportWorld,ValheimStands.Unity.ArmorStand

BlockInteractionMethod
  crouch  ->  keyheld

BlockInteractionKey
  left shift  ->  left alt
```

### Proper Portals

Portal

```text
CarryAnything
  false  ->  true

MinPortalTime
  0  ->  3
```

### Skillful

Skillful

```text
BaseSneakSpeed
  3  ->  2
```

### Triple Bronze

TripleBronze

```text
BronzeMultiplier
  3  ->  2
```

### Useful Trophies

BossConsumption

```text
BossesResetGuardianCooldown
  true  ->  false

BossesApplyGuardianPower
  false  ->  true
```

### Wet and Cold

General

```text
ColdHealthRegenMultiplier
  0.8  ->  0.75

WetHealthRegenMultiplier
  0.9  ->  0.85
```

[neonpack]: https://github.com/NeonCarbide/Valheim-NeonPack
[templates]: https://github.com/NeonCarbide/Valheim-NeonPack/tree/main/extras/templates

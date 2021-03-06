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
- [Better Stamina](#better-stamina)
- [Better Trader](#better-trader)
- [Better UI](#better-ui)
- [Build Camera](#build-camera)
- [Build Helper](#build-helper)
- [Colorful Signs](#colorful-signs)
- [Configurable Autosave](#configurable-autosave)
- [Cooking Skill](#cooking-skill)
- [Creature Level and Loot Control](#creature-level-and-loot-control)
- [Epic Loot](#epic-loot)
- [Explore Together](#explore-together)
- [Fast Tools](#fast-tools)
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
  - [Crafting Config](#crafting-config)
  - [Hunting Config](#hunting-config)
  - [Overhauls Config](#overhauls-config)
  - [Sailing Config](#sailing-config)
  - [Taming Config](#taming-config)
- [Name Tamed Animals](#name-tamed-animals)
- [Nexus Update Check](#nexus-update-check)
- [Paddle Power](#paddle-power)
- [Prevent Accidental Interaction](#prevent-accidental-interaction)
- [Proper Portals](#proper-portals)
- [Triple Bronze](#triple-bronze)
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

### Better Stamina

Tools

```text
RemoveHammerStaminaCost
  true  ->  false

RemoveHoeStaminaCost
  true  ->  false

RemoveCultivatorStaminaCost
  true  ->  false
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

### Cooking Skill

Fermenter Effects

```text
Fermenter Drop Levels
  75,50,100  ->  25,50,75,100
```

### Creature Level and Loot Control

2 - Creatures

```text
Creatures can spawn with special effects
  Off  ->  On

Creatures can spawn with elemental infusions
  Off  ->  On

Time until creatures in camps and dungeons respawn in minutes (0 means disabled, 20 is one ingame day)
  20  ->  70

Creature size increase per star (percentage)
  10  ->  5
```

4 - Bosses

```text
Bosses can spawn with special effects
  Off  ->  On

Star chances for bosses (percentages)
  0, 0, 0, 0, 0, 0, 0, 0, 0  ->  30, 15, 5
```

8 - Boss Affix power

```text
Number of summons for Summoners
  3  ->  5

Elementalist damage increase (percentage)
  20  ->  15

Enraged damage increase (percentage)
  20  ->  30
```

### Epic Loot

Balance

```text
Bosses Drop One Trophy Per Player
  true  ->  false
```

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

### Fast Tools

Tools

```text
PlaceDelay
  0.25  ->  0.3

RemoveDelay
  0.15  ->  0.2
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

#### Crafting Config

Enablers

```text
Enable Crafting Mod
  true  ->  false
```

#### Hunting Config

Multipliers

```text
Multiplies the Hunting Drops
  1.5  ->  2
```

#### Overhauls Config

Enablers: Jump

```text
Enable Higher Jump Mod
  true  ->  false
```

Enablers: Swim

```text
Enable Swim Stamina Mod
  true  ->  false
```

Multipliers: Pickaxe

```text
Multiplier based on level Pickaxe
  1.5  ->  2
```

Multipliers: WoodCutting

```text
Multiplier based on level Woodcutting
  1.5  ->  2
```

#### Sailing Config

Enablers

```text
Enable Sailing Mod
  true  ->  false
```

#### Taming Config

Enablers: Taming

```text
Enable Taming Unlocks Per Level
  true  ->  false
```

### Name Tamed Animals

General

```text
RenameModifierKey
  LeftShift  ->  LeftAlt
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

### Triple Bronze

TripleBronze

```text
BronzeMultiplier
  3  ->  2
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

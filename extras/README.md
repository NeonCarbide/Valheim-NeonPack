# Valheim-NeonPack - Extras <!-- omit in toc -->

I've included all my configuration files for the mods that generate them, as well as my template files for adding r2modmanager compatibility to NexusMods mods

## Config Changes <!-- omit in toc -->

- [Optional](#optional)
  - [Better Auto Run](#better-auto-run)
  - [Build Camera](#build-camera)
  - [Clock](#clock)
  - [Configurable Autosave](#configurable-autosave)
  - [Equipment and Quick Slots](#equipment-and-quick-slots)
  - [Explore Together](#explore-together)
  - [Gizmo](#gizmo)
  - [Loki's First Person Valheim Mod](#lokis-first-person-valheim-mod)
  - [Loki's Immersion Mods](#lokis-immersion-mods)
    - [Hide Crosshair](#hide-crosshair)
    - [Meditation](#meditation)
    - [Minimap](#minimap)
    - [No Health Bars](#no-health-bars)
  - [Nexus Update Check](#nexus-update-check)
- [Required](#required)
  - [Better UI](#better-ui)
  - [Bigger Boat Map Explore Radius](#bigger-boat-map-explore-radius)
  - [Build Helper](#build-helper)
  - [Data Rate Modifier](#data-rate-modifier)
  - [Epic Loot](#epic-loot)
  - [Fitness Skill](#fitness-skill)
  - [Gathering Skill](#gathering-skill)
  - [It's Just Wood](#its-just-wood)
  - [Paddle Power](#paddle-power)
  - [Planting Plus](#planting-plus)
  - [Skillful](#skillful)
  - [Triple Bronze](#triple-bronze)
  - [Useful Paths](#useful-paths)
  - [Useful Trophies](#useful-trophies)
  - [Wet and Cold](#wet-and-cold)

---

### Optional

#### Better Auto Run

```text
sprintUntil
  0.5  ->  0.3
```

#### Build Camera

```text
Camera_Range_Multiplier
  1  ->  2

Toggle_build_mode
  B  ->  Insert
```

#### Clock

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

#### Configurable Autosave

```text
AutosaveInterval
  1200  ->  1800
```

#### Equipment and Quick Slots

```text
Quick slot hotkey 2
  v  ->  x

Quick slot hotkey 3
  b  ->  c
```

#### Explore Together

```text
CoordsInMinimap
  true  ->  false
```

#### Gizmo

```text
resetKey
  V  ->  N
```

#### Loki's First Person Valheim Mod

```text
ShowBodyWhenBlocking
  false  ->  true

Modes
  FirstPersonNoHelmet,ThirdPerson  ->  ThirdPerson,FirstPersonNoHelmet

Hotkey
  H  ->  O
```

#### Loki's Immersion Mods

##### Hide Crosshair

```text
Hotkey
  P + LeftControl  ->  P
```

##### Meditation

```text
EnableMod
  true  ->  false
```

##### Minimap

```text
Hotkey
  O + LeftControl  ->  I
```

##### No Health Bars

```text
EnableMod
  true  ->  false
```

#### Nexus Update Check

```text
UpdatesPosition
  {"x":40.0,"y":40.0}  ->  {"x":10.0,"y":360.0}
```

### Required

#### Better UI

```text
showCustomTooltips
  true  ->  false

timeLeftStylePlant
  2  ->  0
```

#### Bigger Boat Map Explore Radius

```text
BoatExploreRadius
  500  ->  300
```

#### Build Helper

```text
WorkbenchRadius
  150  ->  20

BuildDistance
  10  ->  5

AreaRepairRadius
  7.5  ->  3
```

#### Data Rate Modifier

```text
Rate
  10  ->  2
```

#### Epic Loot

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

Magic Rarity Display Name
  Magic  ->  Uncommon

Legendary Rarity Display Name
  Legendary  ->  Artifact
```

#### Fitness Skill

```text
MaxMultiplier
  1.5  ->  2

RegenMultiplier
  1.5  ->  2
```

#### Gathering Skill

```text
Mode
  Linear  ->  PartialRandom
```

#### It's Just Wood

```text
FineWoodToWoodCount
  {"x":8.0,"y":8.0}  ->  {"x":10.0,"y":10.0}

CoreWoodToWoodCount
  {"x":8.0,"y":8.0}  ->  {"x":10.0,"y":10.0}

AncientBarkToWoodCount
  {"x":8.0,"y":8.0}  ->  {"x":10.0,"y":10.0}
```

#### Paddle Power

```text
counting_method
  ATTACHED  ->  SEATED
```

#### Planting Plus

```text
RequireCultivation
  false  ->  true

AlternateIcons
  false  ->  true
```

#### Skillful

```text
BaseSneakSpeed
  3  ->  2
```

#### Triple Bronze

```text
BronzeMultiplier
  3  ->  2
```

#### Useful Paths

```text
HardWood
  movement
    1.35  ->  1.3

Iron
  movement
    1.35  ->  1.3

LevelGround
  movement
    1.1  ->  1.15

  staminadrain
    0.9  ->  0.85

Path
  movement
    1.25  ->  1.15

  staminadrain
    0.83  ->  0.85

PavedRoad
  movement
    1.35  ->  1.3

Stone
  movement
    1.35  ->  1.3

Wood
  movement
    1.35  ->  1.15

  staminadrain
    0.7  ->  0.85
```

#### Useful Trophies

```text
BossesResetGuardianCooldown
  true  ->  false

BossesApplyGuardianPower
  false  ->  true
```

#### Wet and Cold

```text
ColdHealthRegenMultiplier
  0.8  ->  0.75

WetHealthRegenMultiplier
  0.9  ->  0.85
```

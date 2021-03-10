# Valheim-NeonPack - Extras <!-- omit in toc -->

I've included all my configuration files for the mods that generate them, as well as my template files for adding r2modmanager compatibility to NexusMods mods

## Config Changes <!-- omit in toc -->

- [Better Auto Run](#better-auto-run)
- [Better UI](#better-ui)
- [Bigger Boat Map Explore Radius](#bigger-boat-map-explore-radius)
- [Build Camera](#build-camera)
- [Build Helper](#build-helper)
- [Clock](#clock)
- [Configurable Autosave](#configurable-autosave)
- [Data Rate Modifier](#data-rate-modifier)
- [Emote Keys](#emote-keys)
- [Equipment and Quick Slots](#equipment-and-quick-slots)
- [Explore Together](#explore-together)
- [Fitness Skill](#fitness-skill)
- [Gizmo](#gizmo)
- [It's Just Wood](#its-just-wood)
- [Loki's First Person Valheim Mod](#lokis-first-person-valheim-mod)
- [Loki's Immersion Mods](#lokis-immersion-mods)
  - [Meditation](#meditation)
  - [Minimap](#minimap)
  - [No Health Bars](#no-health-bars)
- [Paddle Power](#paddle-power)
- [Planting Plus](#planting-plus)
- [Precise Rotation](#precise-rotation)
- [Skillful](#skillful)
- [Triple Bronze](#triple-bronze)
- [Useful Trophies](#useful-trophies)
- [Wet and Cold](#wet-and-cold)

---

### Better Auto Run

```text
sprintUntil
  0.5  ->  0.3
```

### Better UI

```text
timeLeftStylePlant
  2  ->  0
```

### Bigger Boat Map Explore Radius

```text
BoatExploreRadius
  500  ->  300
```

### Build Camera

```text
Camera_Range_Multiplier
  1  ->  2

Toggle_build_mode
  B  ->  Insert
```

### Build Helper

```text
WorkbenchRadius
  150  ->  20

BuildDistance
  10  ->  5

AreaRepairRadius
  7.5  ->  3
```

### Clock

```text
ClockLocationString
  50%,3%  ->  75%,5%

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

### Configurable Autosave

```text
AutosaveInterval
  1200  ->  1800
```

### Data Rate Modifier

```text
Rate
  10  ->  2
```

### Emote Keys

```text
SitKey
  [1]  ->  [5]

WaveKey
  [2]  ->  [1]

CheerKey
  [4]  ->  [2]

NoKey
  [5]  ->  [6]

ThumbsUpKey
  [6]  ->  [4]

PointKey
  [7]  ->  [0]
```

### Equipment and Quick Slots

```text
Quick slot hotkey 1
  z  ->  t

Quick slot hotkey 2
  v  ->  g
```

### Explore Together

```text
PingInputKey
  T  ->  Y

CoordsInMinimap
  true  ->  false
```

### Fitness Skill

```text
MaxMultiplier
  1.5  ->  2

RegenMultiplier
  1.5  ->  2
```

### Gizmo

```text
resetKey
  V  ->  N
```

### It's Just Wood

```text
FineWoodToWoodCount
  {"x":8.0,"y":8.0}  ->  {"x":10.0,"y":10.0}

CoreWoodToWoodCount
  {"x":8.0,"y":8.0}  ->  {"x":10.0,"y":10.0}

AncientBarkToWoodCount
  {"x":8.0,"y":8.0}  ->  {"x":10.0,"y":10.0}
```

### Loki's First Person Valheim Mod

```text
ShowBodyWhenBlocking
  false  ->  true

Hotkey
  H  ->  O + LeftControl
```

### Loki's Immersion Mods

#### Meditation

```text
EnableMod
  true  ->  false
```

#### Minimap

```text
Hotkey
  O + LeftControl  ->  I + LeftControl
```

#### No Health Bars

```text
EnableMod
  true  ->  false
```

### Paddle Power

```text
counting_method
  ATTACHED  ->  SEATED
```

### Planting Plus

```text
RequireCultivation
  false  ->  true

AlternateIcons
  false  ->  true
```

### Precise Rotation

```text
RotationModifier
  LeftAlt  ->  RightControl

OverrideRotation
  false  ->  true
```

### Skillful

```text
BaseSneakSpeed
  3  ->  2
```

### Triple Bronze

```text
BronzeMultiplier
  3  ->  2
```

### Useful Trophies

```text
BossesResetGuardianCooldown
  true  ->  false

BossesApplyGuardianPower
  false  ->  true
```

### Wet and Cold

```text
ColdHealthRegenMultiplier
  0.8  ->  0.75

WetHealthRegenMultiplier
  0.9  ->  0.85
```

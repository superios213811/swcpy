---
title: trp_title_RebelSpiderlingDroid (no text translation) (RebelSpiderlingDroid)
category: unit
---

# trp_title_RebelSpiderlingDroid (no text translation) (RebelSpiderlingDroid) — version 1093

You can read an [explanation  of the various unit stats](unitexplained.md).

## Main stats

### Unit stats

  * Armor type: vehicle
  * Side: Rebellion
  * Buildable unit: No
  * Role: Striker
  * Shield cooldown: 0s
  * Shield health: 0
  * Shield range: 0
  * Unit capacity: 1
  * Type: vehicle

|Level |1   |2   |3   |4   |5   |6   |7   |8   |9   |10  |
|------|----|----|----|----|----|----|----|----|----|----|
|Health|5250|5360|5470|5580|5690|5810|5930|6050|6180|6310|


### Training stats

  * Training time: 0s
  * Training cost: Free

### Upgrading stats

  * Upgrade time: 0s
  * Upgrade requirements: Nothing

### Movement stats

  * Acceleration: 0
  * Crushes walls: No
  * Ignores walls: Yes
  * Flying unit: No
  * Max speed: 20
  * Propensity to go around obstacles: 15
  * Rotation speed: 7.854
  * Run speed: 0
  * Run threshold: 0
  * Unit size on map: 1x1

### Modifiers

#### Modifier "Spiderling invulnerable"

  * Spiderling invulnerable apply value as: absolutePercent
  * Spiderling invulnerable buff ID: buffSpiderlingInvulnerable
  * Spiderling invulnerable duration: 10s
  * Spiderling invulnerable lvl: 1
  * Spiderling invulnerable modifier: defense
  * Spiderling invulnerable ms first proc: 0s
  * Spiderling invulnerable ms per proc: permanent
  * Spiderling invulnerable name: Spiderling invulnerable
  * Spiderling invulnerable stack: 1
  * Spiderling invulnerable target: self
  * Spiderling invulnerable value: 0


#### Modifier "Spiderling auto death"

  * Spiderling auto death apply value as: relativePercent
  * Spiderling auto death buff ID: buffSpiderlingAutoDeath
  * Spiderling auto death duration: permanent
  * Spiderling auto death lvl: 1
  * Spiderling auto death modifier: health
  * Spiderling auto death ms first proc: 10.250s
  * Spiderling auto death ms per proc: permanent
  * Spiderling auto death name: Spiderling auto death
  * Spiderling auto death stack: 1
  * Spiderling auto death target: self
  * Spiderling auto death value: -100


## Main attack : RebelSpiderlingDroid

### Targeting

  * Attack shield border: No
  * Max attack range: 2
  * Min attack range: 0
  * New rotation speed: 7854
  * Target preference strength: 90
  * Target preferences: **Flying infantry (70)**, **Infantry (70)**, **Support troop (70)**, _Droideka (60)_, _Flying vehicle (60)_, _Heavy infantry (60)_, _Heavy vehicle (60)_, _Light vehicle (60)_, Headquarters (50), Other building (50), Ressource generator (50), Shield (50), Shield generator (50), Storage (50), Turret (50), Heavy infantry hero (1), Heavy vehicule hero (1), Infantry hero (1), Vehicule hero (1), Wall (1), Trap (0)
  * View range: 8

### Shooting

  * Time between start of clip and first shot: 500ms
  * Clip retargeting: No
  * Gun shooting sequence: 1
  * Impact delay: 0s
  * Can shoot over walls: No
  * Time between end of clip and start of clip: 500ms
  * Retargeting offset: 4
  * Self-centered targeting: No
  * Shot count: 1
  * Time between shots: 960ms
  * Target locking: No

|Level          |1   |2   |3   |4   |5   |6   |7   |8   |9   |10  |
|---------------|----|----|----|----|----|----|----|----|----|----|
|Damage per shot|2170|2190|2235|2295|2335|2375|2415|2455|2515|2575|


### Projectile

|Level                       |1   |2   |3   |4   |5   |6   |7   |8   |9   |10  |
|----------------------------|----|----|----|----|----|----|----|----|----|----|
|Displayed damage per second |1235|1245|1270|1305|1325|1350|1370|1395|1430|1465|
|Calculated damage per second|2170|2190|2235|2295|2335|2375|2415|2455|2515|2575|


  * Cannons per sequence: 1
  * Cliptime: 1s
  * Directional: Yes
  * Is deflectable: No
  * Max speed: 18
  * Damage multipliers: **(400%)**: Flying infantry, Infantry, Infantry hero, Support troop, **(200%)**: Heavy infantry, Heavy infantry hero, **(150%)**: Flying vehicle, Light vehicle, Vehicule hero, **(125%)**: Heavy vehicle, Heavy vehicule hero, **(100%)**: Droideka, **(75%)**: Headquarters, Other building, Ressource generator, Shield, Shield generator, Storage, Trap, Turret, Wall
  * Pass through shield: No
  * Salvos: 1

## Death attack : RebelSpiderlingDroidDeath

  * Death projectile delay: 0s
  * Death projectile distance: 0

  * Death attack splash damage percentages: 100,100,100,100

|Level                  |1  |2  |3  |4  |5  |6  |7  |8  |9  |10 |
|-----------------------|---|---|---|---|---|---|---|---|---|---|
|Death projectile damage|810|818|833|855|870|885|900|915|938|960|


  * Death attack cannons per sequence: 1
  * Death attack cliptime: 0s
  * Death attack directional: No
  * Death attack is deflectable: No
  * Death attack max speed: 18
  * Death attack mults: **(100%)**: Death attack droideka, Death attack flying infantry, Death attack flying vehicle, Death attack headquarters, Death attack heavy infantry, Death attack heavy infantry hero, Death attack heavy vehicle, Death attack heavy vehicule hero, Death attack infantry, Death attack infantry hero, Death attack light vehicle, Death attack other building, Death attack ressource generator, Death attack shield, Death attack shield generator, Death attack storage, Death attack support troop, Death attack trap, Death attack turret, Death attack vehicule hero, Death attack wall
  * Death attack salvos: 1

## Internal stats

These stats internal to the system link different parts of data together.

  * Death projectile: projectileRebelSpiderlingDroidDeath
  * Spawn apply buffs: buffSpiderlingAutoDeath1,buffSpiderlingInvulnerable1
  * Unit ID: RebelSpiderlingDroid

## Presentation stats

These are all sorts of user interface settings, that should not interfere with gameplay.

  * Animation delay: 600
  * Arcs: No
  * Asset name: spiderlingdroid_rbl-ani
  * Audio attack: "sfx_attack_spiderlingdroid_01":30,"sfx_attack_spiderlingdroid_02":35,"sfx_attack_spiderlingdroid_03":35
  * Audio death: "sfx_death_spiderlingdroid_01":30,"sfx_death_spiderlingdroid_02":35,"sfx_death_spiderlingdroid_03":35
  * Audio placement: "sfx_placement_spiderlingdroid_01":30,"sfx_placement_spiderlingdroid_02":35,"sfx_placement_spiderlingdroid_03":35
  * Audio train: "sfx_placement_spiderlingdroid_01":30,"sfx_placement_spiderlingdroid_02":35,"sfx_placement_spiderlingdroid_03":35
  * Bundle name: spiderlingdroid_rbl-ani
  * Death attack arcs: No
  * Death attack hit spark: fx_atmosmig_hit
  * Death attack max scale: 100
  * Death attack muzzle flash: fx_mortar_muzzle_b_lrg
  * Death attack name: RebelSpiderlingDroidDeath
  * Death attack spin speed: 0
  * Factory rotation: 0
  * Factory scale factor: 1
  * Favorite target type: infantry
  * Gun position: "atst_emp_rig_MASTER_MOVER/atst_emp_rig_locator_gun":1
  * Icon camera position: 7.54,14.62,18.95
  * Icon closeup camera position: 7.54,14.62,18.95
  * Icon closeup lookat position: -0.16,0.47,-0.33
  * Icon lookat position: -0.16,0.47,-0.33
  * Max scale: 100
  * Name: RebelSpiderlingDroid
  * Spiderling auto death audio ability event: "sfx_impact_rocket_01":35,"sfx_impact_rocket_02":35,"sfx_impact_rocket_03":30
  * Spin speed: 0
  * Targeted type: ENEMIES

|Level                      |1   |2   |3   |4   |5   |6   |7   |8   |9   |10  |
|---------------------------|----|----|----|----|----|----|----|----|----|----|
|Displayed damage per second|1235|1245|1270|1305|1325|1350|1370|1395|1430|1465|


## Uninterpreted stats

Seriously, we don't really know what to do with these.

  * Arming delay: 0
  * Auto spawn rate scale: 1
  * Auto spawn spreading scale: 1
  * Death attack seeks target: No
  * Death attack streams: no
  * Max scale: No
  * Point value: 1
  * Seeks target: Yes
  * Spiderling invulnerable cancel tags: damage
  * Spiderling invulnerable is refreshing: No
  * Spiderling invulnerable tags: invulnerable
  * Splash: 0
  * Streams: no
  * Strict cool down: No
  * Target in range modifier: 1
  * Xp: 0

|Level|1     |2     |3     |4     |5     |6     |7     |8     |9     |10    |
|-----|------|------|------|------|------|------|------|------|------|------|
|Order|330701|330702|330703|330704|330705|330706|330707|330708|330709|330710|


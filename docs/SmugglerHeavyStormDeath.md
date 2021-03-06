---
title: Heavy Undead Trooper (SmugglerHeavyStormDeath)
category: unit
---

# Heavy Undead Trooper (SmugglerHeavyStormDeath)

You can read an [explanation  of the various unit stats](unitexplained.md).

## Main stats

### Unit stats

  * Armor type: infantry
  * Side: Independant units
  * Buildable unit: No
  * Role: Generic
  * Shield cooldown: 0s
  * Shield health: 0
  * Shield range: 0
  * Unit capacity: 4
  * Type: infantry

|Level |1    |2    |3    |4    |5    |6    |7    |8    |9    |10   |
|------|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
|Health|10780|12940|15095|17250|19405|21565|23720|25875|28030|32345|


### Training stats

|Level        |1    |2    |3    |4    |5    |6    |7    |8    |9    |10  |
|-------------|-----|-----|-----|-----|-----|-----|-----|-----|-----|----|
|Training time|1m20s|1m28s|1m32s|1m36s|1m40s|1m44s|1m48s|1m52s|1m56s|2m  |
|Training cost|200$ |280$ |360$ |440$ |520$ |600$ |680$ |760$ |840$ |920$|


### Upgrading stats

|Level               |1    |2    |3    |4     |5     |6      |7      |8      |9       |10      |
|--------------------|-----|-----|-----|------|------|-------|-------|-------|--------|--------|
|Upgrade time        |0s   |15m  |1h   |3h30m |8h    |1d     |2d     |3d12h  |5d      |1w1d    |
|Upgrade requirements|3000$|3000$|6000$|12500$|25000$|100000$|160000$|320000$|1000000$|1750000$|


### Movement stats

  * Acceleration: 0
  * Crushes walls: No
  * Flying unit: No
  * Max speed: 13
  * Propensity to go around obstacles: 1
  * Rotation speed: 7.854
  * Run speed: 0
  * Run threshold: 0
  * Unit size on map: 1x1

### Modifiers

#### Modifier "Reduce heals"

  * Reduce heals apply value as: absolutePercent
  * Reduce heals buff ID: buffReduceHeals
  * Reduce heals duration: permanent
  * Reduce heals modifier: healDefense
  * Reduce heals ms first proc: 0s
  * Reduce heals ms per proc: permanent
  * Reduce heals name: Reduce heals
  * Reduce heals stack: 0
  * Reduce heals target: self
  * Reduce heals value: 50


## Main attack : HeavyStormDeath

### Targeting

  * Attack shield border: No
  * Max attack range: 6
  * Min attack range: 0
  * New rotation speed: 7854
  * Target preference strength: 90
  * Target preferences: **Droideka (50)**, **Flying infantry (50)**, **Flying vehicle (50)**, **Headquarters (50)**, **Heavy infantry (50)**, **Heavy infantry hero (50)**, **Heavy vehicle (50)**, **Heavy vehicule hero (50)**, **Infantry (50)**, **Infantry hero (50)**, **Light vehicle (50)**, **Other building (50)**, **Ressource generator (50)**, **Shield (50)**, **Shield generator (50)**, **Storage (50)**, **Support troop (50)**, **Turret (50)**, **Vehicule hero (50)**, Wall (1), Trap (0)
  * View range: 8

### Shooting

  * Animation delay: 0
  * Charge time: 500ms
  * Clip retargeting: No
  * Gun shooting sequence: 1
  * Impact delay: 500ms
  * Can shoot over walls: No
  * Reload time: 2s
  * Retargeting offset: 12
  * Self-centered targeting: No
  * Shot count: 10
  * Shot delay: 100ms
  * Target locking: No

|Level          |1  |2  |3  |4  |5  |6  |7  |8  |9  |10 |
|---------------|---|---|---|---|---|---|---|---|---|---|
|Damage per shot|215|255|300|340|385|425|470|510|555|640|


### Projectile

|Level                       |1   |2   |3   |4   |5   |6   |7   |8   |9   |10  |
|----------------------------|----|----|----|----|----|----|----|----|----|----|
|Displayed damage per second |650 |783 |911 |1040|1173|1301|1430|1563|1690|1170|
|Calculated damage per second|614 |728 |857 |971 |1100|1214|1342|1457|1585|1828|
|Calculated damage per cycle |2150|2550|3000|3400|3850|4250|4700|5100|5550|6400|


  * Cannons per sequence: 1
  * Shooting cycle duration: 3.500s
  * Directional: Yes
  * Is deflectable: Yes
  * Max speed: 30
  * Damage multipliers: **(200)**: Wall, **(150)**: Shield, **(100)**: Droideka, Flying infantry, Flying vehicle, Headquarters, Heavy infantry, Heavy infantry hero, Heavy vehicle, Heavy vehicule hero, Infantry, Infantry hero, Light vehicle, Other building, Ressource generator, Shield generator, Storage, Support troop, Trap, Turret, Vehicule hero
  * Pass through shield: No
  * Salvos: 10

## Internal stats

These stats internal to the system link different parts of data together.

  * Spawn apply buffs: buffReduceHeals2
  * Unit ID: SmugglerHeavyStormDeath

## Presentation stats

These are all sorts of user interface settings, that should not interfere with gameplay.

  * Arcs: No
  * Asset name: heavytrooper_dth-ani
  * Audio attack: "sfx_attack_gatlinggun_1":30,"sfx_attack_gatlinggun_2":35,"sfx_attack_gatlinggun_3":35
  * Audio death: "sfx_death_deathtrooper_1":35,"sfx_death_deathtrooper_2":35,"sfx_death_deathtrooper_3":30
  * Audio placement: "sfx_placement_deathtrooper_1":35,"sfx_placement_deathtrooper_2":35,"sfx_placement_deathtrooper_3":30
  * Buff asset offset: 0.00,0.27,0.00
  * Bundle name: heavytrooper_dth-ani
  * Death animation: buffFireBurn:15
  * Factory rotation: 0
  * Factory scale factor: 1
  * Favorite target type: closest
  * Gun position: "deathheavytrooper_emp_rig_MASTER_MOVER/deathheavytrooper_emp_rig_locator_gun_Rt":1
  * Hit spark: fx_gatling_hit_g_lrg
  * Icon camera position: 4.46,8.55,22.59
  * Icon closeup camera position: 3.27,3.36,10.55
  * Icon closeup lookat position: -0.05,2.29,-0.46
  * Icon lookat position: -0.36,1.33,-0.66
  * Max scale: 100
  * Muzzle flash: fx_gatling_muzzle_g_lrg
  * Name: HeavyStormDeath
  * Spin speed: 0
  * Targeted type: ENEMIES

|Level                      |1  |2  |3  |4   |5   |6   |7   |8   |9   |10  |
|---------------------------|---|---|---|----|----|----|----|----|----|----|
|Displayed damage per second|650|783|911|1040|1173|1301|1430|1563|1690|1170|


## Uninterpreted stats

Seriously, we don't really know what to do with these.

  * Arming delay: 0
  * Auto spawn rate scale: 1
  * Auto spawn spreading scale: 1
  * Max scale: No
  * Reduce heals is refreshing: No
  * Seeks target: Yes
  * Splash: 0
  * Streams: no
  * Strict cool down: No
  * Target in range modifier: 1
  * Xp: 0

|Level      |1     |2     |3     |4     |5     |6     |7     |8     |9     |10    |
|-----------|------|------|------|------|------|------|------|------|------|------|
|Order      |460801|460802|460803|460804|460805|460806|460807|460808|460809|460810|
|Point value|4     |4.800 |5.600 |6.400 |7.200 |8     |8.800 |9.600 |10.400|12    |



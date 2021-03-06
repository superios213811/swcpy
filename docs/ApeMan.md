---
title: Ongidae Oppressor (ApeMan)
category: unit
---

# Ongidae Oppressor (ApeMan)

You can read an [explanation  of the various unit stats](unitexplained.md).

## Main stats

### Unit stats

  * Armor type: infantry
  * Side: Empire
  * Buildable unit: Yes
  * Role: Generic
  * Unit capacity: 4
  * Type: infantry

|Level |1    |2    |3    |4    |5    |6    |7    |8    |9    |10   |
|------|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
|Health|10880|11780|12690|13600|14500|15410|16320|17220|18580|20400|


|Level |11   |
|------|-----|
|Health|21492|


### Training stats

|Level        |1                                |2                                      |3                                      |4                                      |5                                      |6                                      |7                                      |8                                      |9                                      |10                                      |
|-------------|---------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|----------------------------------------|
|Training time|42s                              |44s                                    |46s                                    |48s                                    |50s                                    |52s                                    |54s                                    |1m52s                                  |1m56s                                  |2m                                      |
|Training cost|50$                              |70$                                    |90$                                    |110$                                   |130$                                   |150$                                   |170$                                   |200$                                   |210$                                   |230$                                    |
|Building     |[Barracks 1](empireBarracks.html)|[Research Lab 2](empireOffenseLab.html)|[Research Lab 3](empireOffenseLab.html)|[Research Lab 4](empireOffenseLab.html)|[Research Lab 5](empireOffenseLab.html)|[Research Lab 6](empireOffenseLab.html)|[Research Lab 7](empireOffenseLab.html)|[Research Lab 8](empireOffenseLab.html)|[Research Lab 9](empireOffenseLab.html)|[Research Lab 10](empireOffenseLab.html)|


|Level        |11                                      |
|-------------|----------------------------------------|
|Training time|2m4s                                    |
|Training cost|250$                                    |
|Building     |[Research Lab 11](empireOffenseLab.html)|


### Upgrading stats

|Level               |1                |2                |3                |4                |5                |6                |7                |8                |9                 |10                |
|--------------------|-----------------|-----------------|-----------------|-----------------|-----------------|-----------------|-----------------|-----------------|------------------|------------------|
|Upgrade time        |0s               |0s               |0s               |0s               |0s               |0s               |0s               |0s               |0s                |0s                |
|Upgrade requirements|32 data fragments|28 data fragments|30 data fragments|40 data fragments|50 data fragments|60 data fragments|70 data fragments|90 data fragments|120 data fragments|160 data fragments|


|Level               |11                |
|--------------------|------------------|
|Upgrade time        |5s                |
|Upgrade requirements|220 data fragments|


### Movement stats

  * Acceleration: 0
  * Crushes walls: No
  * Flying unit: No
  * Max speed: 20
  * Propensity to go around obstacles: 15
  * Rotation speed: 7.854
  * Run speed: 0
  * Run threshold: 0
  * Unit size on map: 1x1

### Modifiers

#### Modifier "Resilience"

  * Resilience apply value as: relativePercent
  * Resilience buff ID: buffResilience
  * Resilience duration: permanent
  * Resilience modifier: defense
  * Resilience ms first proc: 10s
  * Resilience ms per proc: 10s
  * Resilience name: Resilience
  * Resilience stack: 5
  * Resilience target: self
  * Resilience value: -25.0%


## Main attack : Melee Vibro Mace

### Targeting

  * Attack shield border: No
  * Max attack range: 2
  * Min attack range: 0
  * New rotation speed: 7854
  * Target preference strength: 90
  * Target preferences: **Droideka (50)**, **Flying infantry (50)**, **Flying vehicle (50)**, **Headquarters (50)**, **Heavy infantry (50)**, **Heavy vehicle (50)**, **Infantry (50)**, **Light vehicle (50)**, **Other building (50)**, **Ressource generator (50)**, **Shield (50)**, **Shield generator (50)**, **Storage (50)**, **Support troop (50)**, **Turret (50)**, Heavy infantry hero (1), Heavy vehicule hero (1), Infantry hero (1), Vehicule hero (1), Wall (1), Trap (0)
  * View range: 12

### Shooting

  * Animation delay: 600
  * Charge time: 400ms
  * Clip retargeting: No
  * Gun shooting sequence: 1
  * Impact delay: 0s
  * Can shoot over walls: No
  * Reload time: 500ms
  * Retargeting offset: 14
  * Self-centered targeting: No
  * Shot count: 1
  * Shot delay: 500ms
  * Target locking: No

|Level          |1   |2   |3   |4   |5   |6   |7   |8   |9   |10  |
|---------------|----|----|----|----|----|----|----|----|----|----|
|Damage per shot|1910|1930|1955|1980|2005|2025|2050|2075|2120|2195|


|Level          |11  |
|---------------|----|
|Damage per shot|2240|


### Projectile

|Level                       |1   |2   |3   |4   |5   |6   |7   |8   |9   |10  |
|----------------------------|----|----|----|----|----|----|----|----|----|----|
|Displayed damage per second |1910|1930|1955|1980|2005|2025|2050|2075|2120|2195|
|Calculated damage per second|955 |965 |977 |990 |1002|1012|1025|1037|1060|1097|
|Calculated damage per cycle |1910|1930|1955|1980|2005|2025|2050|2075|2120|2195|


|Level                       |11  |
|----------------------------|----|
|Displayed damage per second |2240|
|Calculated damage per second|1120|
|Calculated damage per cycle |2240|


  * Cannons per sequence: 1
  * Shooting cycle duration: 2s
  * Directional: No
  * Is deflectable: No
  * Max speed: 18
  * Damage multipliers: **(300)**: Flying infantry, Infantry, Infantry hero, Support troop, **(250)**: Heavy infantry, Heavy infantry hero, **(200)**: Flying vehicle, Light vehicle, Vehicule hero, **(150)**: Heavy vehicle, Heavy vehicule hero, **(100)**: Droideka, Headquarters, Other building, Shield, Shield generator, Turret, Wall, **(50)**: Ressource generator, Storage, **(0)**: Trap
  * Pass through shield: No
  * Salvos: 1

## Internal stats

These stats internal to the system link different parts of data together.

  * Resilience details: defense
  * Spawn apply buffs: buffResilience1
  * Unit ID: ApeMan
  * Upgrade shard uid: shrd_troopApeMan

## Presentation stats

These are all sorts of user interface settings, that should not interfere with gameplay.

  * Arcs: Yes
  * Asset name: apeman_emp-ani
  * Audio attack: "sfx_attack_apeman_01":33,"sfx_attack_apeman_02":33,"sfx_attack_apeman_03":34
  * Audio death: "sfx_death_apeman_01":33,"sfx_death_apeman_02":33,"sfx_death_apeman_03":34
  * Audio placement: "sfx_placement_apeman_01":33,"sfx_placement_apeman_02":33,"sfx_placement_apeman_03":34
  * Audio train: "sfx_ui_unitcomplete_apeman_01":100
  * Bundle name: apeman_emp-ani
  * Event button action: galaxy
  * Event button data: planet1 planet3 planet6 planet8 planet21 planet23
  * Event button string: hn_open_galaxy
  * Event features string: fragment_obtain_gen
  * Factory rotation: 0
  * Factory scale factor: 1
  * Favorite target type: infantry
  * Icon camera position: 7.29,9.66,20.53
  * Icon closeup camera position: 4.47,3.03,10.77
  * Icon closeup lookat position: -0.44,2.55,-1.03
  * Icon lookat position: -0.34,1.3,-0.74
  * Max scale: 100
  * Muzzle flash: fx_melee_headbutt_med
  * Name: Melee Vibro Mace
  * Spin speed: 2
  * Targeted type: ENEMIES
  * Unlocked by campaign: Yes
  * Unlocked by event: true
  * Unlocked by tournament: Yes

|Level                      |1          |2          |3          |4          |5          |6          |7          |8          |9          |10         |
|---------------------------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|
|Deploy vfx                 |(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|
|Displayed damage per second|1910       |1930       |1955       |1980       |2005       |2025       |2050       |2075       |2120       |2195       |
|Prestige                   |(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|


|Level                      |11                           |
|---------------------------|-----------------------------|
|Deploy vfx                 |vfx_prestige_deploy_small_emp|
|Displayed damage per second|2240                         |
|Prestige                   |true                         |


## Uninterpreted stats

Seriously, we don't really know what to do with these.

  * Arming delay: 0
  * Auto spawn rate scale: 1
  * Auto spawn spreading scale: 1
  * Max scale: No
  * Resilience tags: Resilience
  * Seeks target: Yes
  * Streams: no
  * Strict cool down: No
  * Target in range modifier: 1
  * Xp: 0

|Level      |1    |2    |3    |4    |5    |6    |7    |8    |9    |10   |
|-----------|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
|Order      |61301|61302|61303|61304|61305|61306|61307|61308|61309|61310|
|Point value|1    |1.200|1.400|1.600|1.800|2    |2.200|2.400|2.600|3    |


|Level      |11   |
|-----------|-----|
|Order      |61311|
|Point value|3    |



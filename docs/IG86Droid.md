---
title: IG-86 Assassin Droid (IG86Droid)
category: unit
---

# IG-86 Assassin Droid (IG86Droid)

You can read an [explanation  of the various unit stats](unitexplained.md).

## Main stats

### Unit stats

  * Armor type: bruiserInfantry
  * Side: Empire
  * Buildable unit: Yes
  * Role: Bruiser
  * Shield cooldown: 0s
  * Shield health: 0
  * Shield range: 0
  * Unit capacity: 6
  * Type: infantry

|Level |1   |2    |3    |4    |5    |6    |7    |8    |9    |10   |
|------|----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
|Health|8860|10260|11130|12450|13780|15100|16490|17840|19200|21880|


|Level |11   |
|------|-----|
|Health|23488|


### Training stats

|Level        |1                                |2                                      |3                                      |4                                      |5                                      |6                                      |7                                      |8                                      |9                                      |10                                      |
|-------------|---------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|----------------------------------------|
|Training time|42s                              |44s                                    |46s                                    |48s                                    |50s                                    |52s                                    |54s                                    |1m52s                                  |1m56s                                  |2m                                      |
|Training cost|500$                             |700$                                   |900$                                   |1100$                                  |1300$                                  |1500$                                  |1700$                                  |2000$                                  |2100$                                  |2300$                                   |
|Building     |[Barracks 2](empireBarracks.html)|[Research Lab 2](empireOffenseLab.html)|[Research Lab 3](empireOffenseLab.html)|[Research Lab 4](empireOffenseLab.html)|[Research Lab 5](empireOffenseLab.html)|[Research Lab 6](empireOffenseLab.html)|[Research Lab 7](empireOffenseLab.html)|[Research Lab 8](empireOffenseLab.html)|[Research Lab 9](empireOffenseLab.html)|[Research Lab 10](empireOffenseLab.html)|


|Level        |11                                      |
|-------------|----------------------------------------|
|Training time|2m4s                                    |
|Training cost|2500$                                   |
|Building     |[Research Lab 11](empireOffenseLab.html)|


### Upgrading stats

  * Upgrade requirements: 32 data fragments

|Level       |1-10|11|
|------------|----|--|
|Upgrade time|0s  |5s|


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

## Main attack : IG-86 Droid

### Targeting

  * Attack shield border: No
  * Max attack range: 5
  * Min attack range: 0
  * New rotation speed: 7854
  * Target preference strength: 90
  * Target preferences: **Turret (70)**, _Flying infantry (60)_, _Flying vehicle (60)_, _Support troop (60)_, Droideka (50), Headquarters (50), Heavy infantry (50), Heavy vehicle (50), Infantry (50), Light vehicle (50), Other building (50), Ressource generator (50), Shield (50), Shield generator (50), Storage (50), Heavy infantry hero (1), Heavy vehicule hero (1), Infantry hero (1), Vehicule hero (1), Wall (1), Trap (0)
  * View range: 12

### Shooting

  * Animation delay: 0
  * Charge time: 250ms
  * Clip retargeting: Yes
  * Gun shooting sequence: 1
  * Impact delay: 1s
  * Can shoot over walls: No
  * Reload time: 2s
  * Retargeting offset: 20
  * Self-centered targeting: No
  * Shot count: 7
  * Shot delay: 150ms
  * Target locking: No

|Level          |1   |2   |3   |4   |5   |6   |7   |8   |9   |10  |
|---------------|----|----|----|----|----|----|----|----|----|----|
|Damage per shot|1236|1243|1268|1277|1286|1295|1354|1387|1421|1464|


|Level          |11  |
|---------------|----|
|Damage per shot|1489|


### Projectile

|Level                       |1   |2   |3   |4   |5   |6   |7   |8   |9   |10   |
|----------------------------|----|----|----|----|----|----|----|----|----|-----|
|Displayed damage per second |2747|2762|2818|2838|2858|2878|3009|3082|3158|3253 |
|Calculated damage per second|2621|2636|2689|2708|2727|2746|2872|2942|3014|3105 |
|Calculated damage per cycle |8652|8701|8876|8939|9002|9065|9478|9709|9947|10248|


|Level                       |11   |
|----------------------------|-----|
|Displayed damage per second |6545 |
|Calculated damage per second|3158 |
|Calculated damage per cycle |10423|


  * Cannons per sequence: 1
  * Shooting cycle duration: 3.300s
  * Directional: Yes
  * Is deflectable: Yes
  * Max speed: 18
  * Damage multipliers: **(100)**: Droideka, Headquarters, Other building, Ressource generator, Shield, Shield generator, Storage, Trap, Turret, Wall, **(50)**: Flying infantry, Flying vehicle, Infantry, Infantry hero, Light vehicle, Support troop, Vehicule hero, **(25)**: Heavy infantry, Heavy infantry hero, Heavy vehicle, Heavy vehicule hero
  * Pass through shield: No
  * Salvos: 7

## Internal stats

These stats internal to the system link different parts of data together.

  * Unit ID: IG86Droid
  * Upgrade shard uid: shrd_troopIG86Droid

## Presentation stats

These are all sorts of user interface settings, that should not interfere with gameplay.

  * Arcs: No
  * Asset name: ig86_emp-ani
  * Audio attack: "sfx_attack_ig86_01":33,"sfx_attack_ig86_02":33,"sfx_attack_ig86_03":34
  * Audio death: "sfx_death_ig86_01":50,"sfx_death_ig86_02":50
  * Audio placement: "sfx_placement_ig86_01":33,"sfx_placement_ig86_02":33,"sfx_placement_ig86_03":34
  * Audio train: "sfx_ui_unitcomplete_ig86_01":50,"sfx_ui_unitcomplete_ig86_02":50
  * Bullet: fx_blaster_beam_r_sm
  * Bundle name: ig86_emp-ani
  * Event button action: galaxy
  * Event button data: planet1 planet3 planet6 planet8 planet21 planet23
  * Event button string: hn_open_galaxy
  * Event features string: fragment_obtain_gen
  * Factory rotation: 0
  * Factory scale factor: 1
  * Favorite target type: turret
  * Hit spark: fx_blaster_hit_r_sm
  * Icon camera position: 5.5,12.03,13.9
  * Icon closeup camera position: 3.74,7.49,9.45
  * Icon closeup lookat position: -0.45,1.94,-1.14
  * Icon lookat position: -0.4,1.24,-0.81
  * Max scale: 100
  * Muzzle flash: fx_blaster_flash_r_sm
  * Name: IG-86 Droid
  * Spin speed: 0
  * Targeted type: ENEMIES
  * Unlocked by event: true

|Level                      |1          |2          |3          |4          |5          |6          |7          |8          |9          |10         |
|---------------------------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|
|Deploy vfx                 |(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|
|Displayed damage per second|2747       |2762       |2818       |2838       |2858       |2878       |3009       |3082       |3158       |3253       |
|Icon unlock scale          |1.2,1.2,1.2|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|
|Prestige                   |(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|


|Level                      |11                           |
|---------------------------|-----------------------------|
|Deploy vfx                 |vfx_prestige_deploy_small_emp|
|Displayed damage per second|6545                         |
|Icon unlock scale          |(not found)                  |
|Prestige                   |true                         |


## Uninterpreted stats

Seriously, we don't really know what to do with these.

  * Arming delay: 0
  * Auto spawn rate scale: 1
  * Auto spawn spreading scale: 1
  * Max scale: No
  * Seeks target: Yes
  * Splash: 0
  * Streams: no
  * Strict cool down: No
  * Target in range modifier: 1
  * Xp: 0

|Level      |1    |2    |3    |4    |5    |6    |7    |8    |9     |10   |
|-----------|-----|-----|-----|-----|-----|-----|-----|-----|------|-----|
|Order      |61101|61102|61103|61104|61105|61106|61107|61108|61109 |61110|
|Point value|4    |4.800|5.600|6.400|7.200|8    |8.800|9.600|10.400|12   |


|Level      |11   |
|-----------|-----|
|Order      |61111|
|Point value|12   |



---
title: Hunter Rancor (EmpireHunterRancorCreature)
category: unit
---

# Hunter Rancor (EmpireHunterRancorCreature)

You can read an [explanation  of the various unit stats](unitexplained.md).

## Main stats

### Unit stats

  * Armor type: bruiserInfantry
  * Side: Empire
  * Buildable unit: Yes
  * Role: Striker
  * Shield cooldown: 0s
  * Shield health: 0
  * Shield range: 0
  * Unit capacity: 20
  * Type: creature

|Level |1    |2    |3    |4    |5    |6    |7    |8    |9    |10   |
|------|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
|Health|51840|57173|62506|67840|73173|78506|83840|89173|94506|99840|


### Training stats

  * Training time: 5s
  * Training cost: Free

### Upgrading stats

  * Upgrade time: 5s

|Level               |1                |2                |3                |4                 |5                 |6                 |7                 |8                 |9                 |10                |
|--------------------|-----------------|-----------------|-----------------|------------------|------------------|------------------|------------------|------------------|------------------|------------------|
|Upgrade requirements|32 data fragments|60 data fragments|90 data fragments|130 data fragments|180 data fragments|240 data fragments|310 data fragments|400 data fragments|520 data fragments|680 data fragments|


### Movement stats

  * Acceleration: 0
  * Crushes walls: Yes
  * Flying unit: No
  * Max speed: 30
  * Propensity to go around obstacles: 1
  * Rotation speed: 3.927
  * Run speed: 0
  * Run threshold: 0
  * Unit size on map: 1x1

## Main attack : Rancor Blaster

### Targeting

  * Attack shield border: No
  * Max attack range: 3
  * Min attack range: 0
  * New rotation speed: 2000
  * Target preference strength: 90
  * Target preferences: **Heavy infantry (70)**, **Heavy infantry hero (70)**, **Infantry (70)**, **Infantry hero (70)**, _Droideka (60)_, _Heavy vehicle (60)_, _Heavy vehicule hero (60)_, _Light vehicle (60)_, _Vehicule hero (60)_, Other building (50), Ressource generator (50), Shield (50), Shield generator (50), Storage (50), Support troop (50), Turret (50), Headquarters (40), Flying infantry (1), Flying vehicle (1), Wall (1), Trap (0)
  * View range: 16

### Shooting

  * Animation delay: 960
  * Charge time: 500ms
  * Clip retargeting: Yes
  * Gun shooting sequence: 2,1
  * Impact delay: 960ms
  * Can shoot over walls: No
  * Reload time: 1.910s
  * Retargeting offset: 8
  * Self-centered targeting: No
  * Shot count: 2
  * Shot delay: 270ms
  * Target locking: No

|Level          |1   |2   |3   |4   |5   |6   |7    |8    |9    |10   |
|---------------|----|----|----|----|----|----|-----|-----|-----|-----|
|Damage per shot|6183|6819|7455|8092|8728|9364|10000|10636|11272|11908|


### Projectile

  * Splash damage percentages: 100,50

|Level                       |1    |2    |3    |4    |5    |6    |7    |8    |9    |10   |
|----------------------------|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
|Displayed damage per second |3494 |3925 |4356 |4787 |5219 |5650 |6081 |6512 |6944 |7375 |
|Calculated damage per second|2539 |2800 |3061 |3323 |3584 |3845 |4106 |4367 |4629 |4890 |
|Calculated damage per cycle |12366|13638|14910|16184|17456|18728|20000|21272|22544|23816|


  * Cannons per sequence: 2
  * Shooting cycle duration: 4.870s
  * Directional: Yes
  * Is deflectable: No
  * Max speed: 18
  * Damage multipliers: **(200)**: Heavy infantry, Infantry, **(100)**: Droideka, Heavy infantry hero, Heavy vehicle, Heavy vehicule hero, Infantry hero, Light vehicle, Support troop, Vehicule hero, **(75)**: Headquarters, Other building, Ressource generator, Shield, Shield generator, Storage, Trap, Turret, Wall, **(0)**: Flying infantry, Flying vehicle
  * Pass through shield: Yes
  * Salvos: 2

## Internal stats

These stats internal to the system link different parts of data together.

  * Unit ID: EmpireHunterRancorCreature
  * Upgrade shard uid: shrd_troopEmpireHunterRancorCreature

## Presentation stats

These are all sorts of user interface settings, that should not interfere with gameplay.

  * Arcs: No
  * Asset name: rancorhunter_neu-ani
  * Audio attack: "sfx_attack_creatures_rancor_1":33,"sfx_attack_creatures_rancor_2":33,"sfx_attack_creatures_rancor_3":34
  * Audio death: "sfx_death_creatures_rancor_1":100
  * Audio impact: "sfx_impact_creatures_rancor_1":33,"sfx_impact_creatures_rancor_2":33,"sfx_impact_creatures_rancor_3":34
  * Audio placement: "sfx_attack_creatures_rancor_1":35,"sfx_attack_creatures_rancor_2":35,"sfx_attack_creatures_rancor_3":30
  * Bundle name: rancorhunter_neu-ani
  * Deploy vfx: vfx_prestige_deploy_large_emp
  * Event button action: galaxy
  * Event button data: planet1 planet3 planet6 planet8 planet21 planet23
  * Event button string: hn_open_galaxy
  * Event features string: fragment_obtain_gen
  * Factory rotation: 0
  * Factory scale factor: 1
  * Favorite target type: infantry
  * Gun position: "rancor_neu_rig_MASTER_MOVER/"rancor_neu_rig_locator_gun1":1,"rancor_neu_rig_MASTER_MOVER/rancor_neu_rig_locator_gun2":2
  * Icon camera position: 32.55,42.31,46.76
  * Icon lookat position: -0.58,2.75,-1.64
  * Max scale: 100
  * Muzzle flash: fx_melee_headbutt_lrg
  * Name: Rancor Blaster
  * Spin speed: 0
  * Targeted type: ENEMIES
  * Unlocked by event: true

|Level                      |1          |2          |3          |4          |5          |6          |7          |8          |9          |10         |
|---------------------------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|
|Displayed damage per second|3494       |3925       |4356       |4787       |5219       |5650       |6081       |6512       |6944       |7375       |
|Icon unlock position       |0,-0.75,0  |(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|
|Icon unlock rotation       |0,-30,0    |(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|
|Icon unlock scale          |0.6,0.6,0.6|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|


## Uninterpreted stats

Seriously, we don't really know what to do with these.

  * Arming delay: 0
  * Auto spawn rate scale: 2
  * Auto spawn spreading scale: 2
  * Max scale: No
  * Seeks target: Yes
  * Splash: 0
  * Streams: no
  * Strict cool down: No
  * Target in range modifier: 1
  * Xp: 0

|Level      |1    |2    |3    |4    |5    |6    |7    |8    |9    |10   |
|-----------|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
|Order      |90201|90202|90203|90204|90205|90206|90207|90208|90209|90210|
|Point value|20   |24   |28   |32   |36   |40   |44   |48   |52   |60   |



---
title: TIE Striker Trap (empireTrapStrikeHeavy)
category: building
---

# TIE Striker Trap (empireTrapStrikeHeavy)

You can read an [explanation  of the various unit stats](unitexplained.md).

## Main stats

### Unit stats

  * Armor type: trap
  * Side: Empire
  * Force reticle when targeted: Yes
  * Hide if locked: No
  * Trap disarm conditions: EventSuccess
  * Trap rearm credits cost: 0
  * Trap target type: Self
  * Trap trigger conditions: Radius(2) & ArmorNot(flierInfantry)
  * Type: trap

|Level                    |1                                                    |2                                                    |3                                                    |4                                                    |5                                                    |6                                                    |7                                                    |8                                                    |9                                                    |10                                                    |
|-------------------------|-----------------------------------------------------|-----------------------------------------------------|-----------------------------------------------------|-----------------------------------------------------|-----------------------------------------------------|-----------------------------------------------------|-----------------------------------------------------|-----------------------------------------------------|-----------------------------------------------------|------------------------------------------------------|
|Cross credits            |(not found)                                          |(not found)                                          |(not found)                                          |(not found)                                          |(not found)                                          |(not found)                                          |(not found)                                          |(not found)                                          |(not found)                                          |(not found)                                           |
|Cross materials          |(not found)                                          |(not found)                                          |(not found)                                          |(not found)                                          |(not found)                                          |(not found)                                          |(not found)                                          |(not found)                                          |(not found)                                          |(not found)                                           |
|Cross time               |(not found)                                          |(not found)                                          |(not found)                                          |(not found)                                          |(not found)                                          |(not found)                                          |(not found)                                          |(not found)                                          |(not found)                                          |(not found)                                           |
|Health                   |2500                                                 |3750                                                 |4500                                                 |6000                                                 |7250                                                 |8500                                                 |9750                                                 |11000                                                |12250                                                |13500                                                 |
|Max quantity             |1                                                    |1                                                    |1                                                    |2                                                    |2                                                    |2                                                    |2                                                    |2                                                    |2                                                    |2                                                     |
|Produce                  |(not found)                                          |(not found)                                          |(not found)                                          |(not found)                                          |(not found)                                          |(not found)                                          |(not found)                                          |(not found)                                          |(not found)                                          |(not found)                                           |
|Time                     |1m30s                                                |22m30s                                               |3h                                                   |18h                                                  |1d12h                                                |2d6h                                                 |3d                                                   |4d12h                                                |1w2d                                                 |2w1d                                                  |
|Trap air strike          |["shp_title_AtmosMigTrap" level 1](AtmosMigTrap.html)|["shp_title_AtmosMigTrap" level 2](AtmosMigTrap.html)|["shp_title_AtmosMigTrap" level 3](AtmosMigTrap.html)|["shp_title_AtmosMigTrap" level 4](AtmosMigTrap.html)|["shp_title_AtmosMigTrap" level 5](AtmosMigTrap.html)|["shp_title_AtmosMigTrap" level 6](AtmosMigTrap.html)|["shp_title_AtmosMigTrap" level 7](AtmosMigTrap.html)|["shp_title_AtmosMigTrap" level 8](AtmosMigTrap.html)|["shp_title_AtmosMigTrap" level 9](AtmosMigTrap.html)|["shp_title_AtmosMigTrap" level 10](AtmosMigTrap.html)|
|Trap rearm materials cost|750                                                  |1500                                                 |2250                                                 |2700                                                 |3000                                                 |4500                                                 |7500                                                 |9000                                                 |12000                                                |22500                                                 |


|Level                    |11                                                    |
|-------------------------|------------------------------------------------------|
|Cross credits            |0                                                     |
|Cross materials          |0                                                     |
|Cross time               |0s                                                    |
|Health                   |14250                                                 |
|Max quantity             |2                                                     |
|Produce                  |0                                                     |
|Time                     |5d                                                    |
|Trap air strike          |["shp_title_AtmosMigTrap" level 10](AtmosMigTrap.html)|
|Trap rearm materials cost|33000                                                 |


### Training stats

|Level        |1                              |2                              |3                              |4                              |5                              |6                              |7                              |8                              |9                               |10                              |
|-------------|-------------------------------|-------------------------------|-------------------------------|-------------------------------|-------------------------------|-------------------------------|-------------------------------|-------------------------------|--------------------------------|--------------------------------|
|Training cost|900 All.                       |3000 All.                      |15000 All.                     |45000 All.                     |90000 All.                     |240000 All.                    |525000 All.                    |750000 All.                    |1200000 All.                    |2250000 All.                    |
|Building     |[Headquarters 7](empireHQ.html)|[Headquarters 7](empireHQ.html)|[Headquarters 7](empireHQ.html)|[Headquarters 8](empireHQ.html)|[Headquarters 8](empireHQ.html)|[Headquarters 8](empireHQ.html)|[Headquarters 9](empireHQ.html)|[Headquarters 9](empireHQ.html)|[Headquarters 10](empireHQ.html)|[Headquarters 10](empireHQ.html)|


|Level        |11                              |
|-------------|--------------------------------|
|Training cost|2925000 All.                    |
|Building     |[Headquarters 11](empireHQ.html)|


### Upgrading stats

  * Upgrade requirements: Nothing

### Movement stats

  * Unit size on map: 1x1

## Internal stats

These stats internal to the system link different parts of data together.

  * Trap event type: SpecialAttack

|Level          |1                         |2                         |3                         |4                         |5                         |6                         |7                         |8                         |9                         |10                         |
|---------------|--------------------------|--------------------------|--------------------------|--------------------------|--------------------------|--------------------------|--------------------------|--------------------------|--------------------------|---------------------------|
|Trap ID        |trap_EmpireStrikeHeavy1   |trap_EmpireStrikeHeavy2   |trap_EmpireStrikeHeavy3   |trap_EmpireStrikeHeavy4   |trap_EmpireStrikeHeavy5   |trap_EmpireStrikeHeavy6   |trap_EmpireStrikeHeavy7   |trap_EmpireStrikeHeavy8   |trap_EmpireStrikeHeavy9   |trap_EmpireStrikeHeavy10   |
|Trap event data|specialAttackAtmosMigTrap1|specialAttackAtmosMigTrap2|specialAttackAtmosMigTrap3|specialAttackAtmosMigTrap4|specialAttackAtmosMigTrap5|specialAttackAtmosMigTrap6|specialAttackAtmosMigTrap7|specialAttackAtmosMigTrap8|specialAttackAtmosMigTrap9|specialAttackAtmosMigTrap10|


|Level          |11                         |
|---------------|---------------------------|
|Trap ID        |trap_EmpireStrikeHeavy11   |
|Trap event data|specialAttackAtmosMigTrap10|


## Presentation stats

These are all sorts of user interface settings, that should not interfere with gameplay.

  * Buff asset offset: -1,0.8,-1
  * Destruct FX: fx_trap_fighter
  * Icon camera position: -32.79,29.4,27.07
  * Icon lookat position: 0.79,2.54,-0.62
  * Stash order: 125
  * Trap add ons: Contents/SharedAssets/active_holo/holo_armed:atmosmigholo_emp-mod Contents/HomeAssets/holo_spent:atmosmigholo_emp-mod_red Contents/HomeAssets/holo_spent:fx_repair_smoke Contents/SharedAssets/trap_spent/starshiptrap_emp-mod_disarmed:fx_starship_trap_spent_cone_emitter
  * Trap reveal audio: sfx_trap_appear

|Level           |1                          |2-10                       |11                              |
|----------------|---------------------------|---------------------------|--------------------------------|
|Asset name      |fx_trap_starship_strike_emp|fx_trap_starship_strike_emp|fx_trap_starship_strike_emp-up11|
|Bundle name     |fx_trap_starship_strike_emp|fx_trap_starship_strike_emp|fx_trap_starship_strike_emp-up11|
|Cycle time      |(not found)                |(not found)                |0s                              |
|Icon asset name |icon_atmosmig_trap_emp     |icon_atmosmig_trap_emp     |(not found)                     |
|Icon bundle name|icon_atmosmig_trap_emp     |icon_atmosmig_trap_emp     |(not found)                     |
|Prestige        |(not found)                |(not found)                |true                            |
|Store tab       |defenses                   |(not found)                |(not found)                     |


## Uninterpreted stats

Seriously, we don't really know what to do with these.

  * Max XP: 0
  * Order: 23

|Level|1 |2 |3 |4 |5 |6 |7 |8 |9 |10|
|-----|--|--|--|--|--|--|--|--|--|--|
|Xp   |30|32|33|34|35|36|37|38|39|40|


|Level|11|
|-----|--|
|Xp   |41|



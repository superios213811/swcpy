---
title: bldtitlesmugglerMortar (smugglerMortar)
category: building
---

# bldtitlesmugglerMortar (smugglerMortar)

You can read an [explanation  of the various unit stats](unitexplained.md).

## Main stats

### Unit stats

  * Armor type: turret
  * Cross credits: 0
  * Side: Independant units
  * Force reticle when targeted: No
  * Hide if locked: No
  * Max quantity: 6
  * Produce: 0
  * Time: 0s
  * Type: turret

|Level          |1   |2   |3   |4    |5    |6    |7    |8    |9    |10   |
|---------------|----|----|----|-----|-----|-----|-----|-----|-----|-----|
|Cross materials|750 |1250|1556|1500 |2000 |2778 |4167 |10417|11111|11905|
|Cross time     |1m  |2m  |3m  |4m   |5m   |6m   |7m   |8m   |9m   |10m  |
|Health         |3800|5500|6000|15000|17500|20000|22500|25000|27500|30000|


### Training stats

  * Training cost: 1 All.

|Level   |1                                |2                                |3                                |4                                |5                                |6                                |7                                |8                                |9                                |10                                |
|--------|---------------------------------|---------------------------------|---------------------------------|---------------------------------|---------------------------------|---------------------------------|---------------------------------|---------------------------------|---------------------------------|----------------------------------|
|Building|[Headquarters 1](smugglerHQ.html)|[Headquarters 2](smugglerHQ.html)|[Headquarters 3](smugglerHQ.html)|[Headquarters 4](smugglerHQ.html)|[Headquarters 5](smugglerHQ.html)|[Headquarters 6](smugglerHQ.html)|[Headquarters 7](smugglerHQ.html)|[Headquarters 8](smugglerHQ.html)|[Headquarters 9](smugglerHQ.html)|[Headquarters 10](smugglerHQ.html)|


### Upgrading stats

  * Upgrade requirements: Nothing

### Movement stats

  * Acceleration: 0
  * Max speed: 0
  * Unit size on map: 2x2

## Turret attack : Smuggler Mortar Turret


### Targeting

  * Turret max attack range: 9
  * Turret min attack range: 4
  * Turret target preference strength: 90
  * Turret target preferences: **Turret droideka (60)**, **Turret headquarters (60)**, **Turret heavy infantry (60)**, **Turret heavy vehicle (60)**, **Turret infantry (60)**, **Turret light vehicle (60)**, **Turret other building (60)**, **Turret ressource generator (60)**, **Turret storage (60)**, **Turret support troop (60)**, **Turret turret (60)**, Turret heavy infantry hero (1), Turret heavy vehicule hero (1), Turret infantry hero (1), Turret vehicule hero (1), Turret wall (1), Turret flying infantry (0), Turret flying vehicle (0)
  * Turret view range: 10

### Shooting

  * Turret animation delay: 0
  * Turret charge time: 1.500s
  * Turret clip retargeting: No
  * Turret gun shooting sequence: 1
  * Turret impact delay: 1s
  * Turret can shoot over walls: Yes
  * Turret reload time: 1.500s
  * Turret shot count: 1
  * Turret shot delay: 1ms

|Level                 |1   |2   |3   |4   |5   |6   |7   |8   |9   |10  |
|----------------------|----|----|----|----|----|----|----|----|----|----|
|Turret damage per shot|1050|1575|1890|2520|3045|3570|4095|4620|5145|5670|


  * Turret attack splash damage percentages: 100,75

|Level                                     |1   |2   |3   |4   |5   |6   |7   |8   |9   |10  |
|------------------------------------------|----|----|----|----|----|----|----|----|----|----|
|Turret displayed damage per second        |350 |525 |700 |1050|1225|1400|1575|1750|1925|2100|
|Turret attack calculated damage per second|349 |524 |629 |839 |1014|1189|1364|1539|1714|1889|
|Turret attack calculated damage per clip  |1050|1575|1890|2520|3045|3570|4095|4620|5145|5670|


  * Turret attack cannons per sequence: 1
  * Turret attack cliptime: 3.001s
  * Turret attack directional: No
  * Turret attack is deflectable: No
  * Turret attack max speed: 4
  * Turret attack damage multipliers: **(100)**: Turret attack droideka, Turret attack headquarters, Turret attack other building, Turret attack ressource generator, Turret attack shield, Turret attack shield generator, Turret attack storage, Turret attack support troop, Turret attack trap, Turret attack turret, Turret attack wall, **(80)**: Turret attack infantry, Turret attack infantry hero, **(60)**: Turret attack heavy infantry, Turret attack heavy infantry hero, **(50)**: Turret attack light vehicle, Turret attack vehicule hero, **(25)**: Turret attack heavy vehicle, Turret attack heavy vehicule hero, **(0)**: Turret attack flying infantry, Turret attack flying vehicle
  * Turret attack pass through shield: No
  * Turret attack salvos: 1

## Internal stats

These stats internal to the system link different parts of data together.

  * Sub type: mortar_turret
  * Turret projectile type: projectileSmugglerMortar

|Level    |1                |2                |3                |4                |5                |6                |7                |8                |9                |10                |
|---------|-----------------|-----------------|-----------------|-----------------|-----------------|-----------------|-----------------|-----------------|-----------------|------------------|
|Turret id|t_smugglerMortar1|t_smugglerMortar2|t_smugglerMortar3|t_smugglerMortar4|t_smugglerMortar5|t_smugglerMortar6|t_smugglerMortar7|t_smugglerMortar8|t_smugglerMortar9|t_smugglerMortar10|


## Presentation stats

These are all sorts of user interface settings, that should not interfere with gameplay.

  * Asset name: mortarturret_smg-mod
  * Audio attack: "sfx_attack_mortarlaunch_1":50,"sfx_attack_mortarlaunch_2":50
  * Audio death: "sfx_explosion_metal_1":25,"sfx_explosion_metal_2":25,"sfx_explosion_metal_3":25,"sfx_explosion_metal_4":25
  * Buff asset offset: -1.4,1.2,-1.4
  * Bundle name: mortarturret_smg-mod
  * Collect notify: 0
  * Cycle time: 0s
  * Destruct FX: fx_debris_{0}x{1}
  * Icon camera position: -23.91,25.41,24.96
  * Icon lookat position: 0.34,1.59,-0.27
  * Stash order: 1000
  * Store tab: not_in_store
  * Turret attack S transition: 100
  * Turret attack arcs: Yes
  * Turret attack bullet: fx_mortar_projectile_y_sm
  * Turret attack hit spark: fx_mortar_hit_y_sm
  * Turret attack max scale: 100
  * Turret attack muzzle flash: fx_mortar_muzzle_y_sm
  * Turret attack name: Smuggler Mortar Turret
  * Turret attack spin speed: 2
  * Turret favorite target type: infantry
  * Turret gun position: "locator_gun":1
  * Turret max scale: 2
  * Turret tracker name: mortarMesh/barrelbaseMesh

|Level                             |1  |2  |3  |4   |5   |6   |7   |8   |9   |10  |
|----------------------------------|---|---|---|----|----|----|----|----|----|----|
|Turret displayed damage per second|350|525|700|1050|1225|1400|1575|1750|1925|2100|


## Uninterpreted stats

Seriously, we don't really know what to do with these.

  * Turret arming delay: 0
  * Turret attack S1 time: 300ms
  * Turret attack S2 time: 300ms
  * Turret attack seeks target: No
  * Turret attack streams: no
  * Turret splash: false
  * Turret strict cool down: No
  * Turret timey wimey: 0.333333333299999978738270556277711875736713409423828125

|Level |1  |2  |3  |4  |5  |6  |7  |8  |9  |10 |
|------|---|---|---|---|---|---|---|---|---|---|
|Max XP|30 |48 |54 |72 |84 |102|114|132|144|162|
|Order |570|571|572|573|574|575|576|577|578|579|
|Xp    |5  |8  |9  |12 |14 |17 |19 |22 |24 |27 |



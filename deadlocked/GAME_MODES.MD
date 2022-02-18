# Custom Game Modes

This page is dedicated to detailing all of the custom game modes available on the Horizon Private Server. Below each game mode is a list of recommended settings curated through developer and community playtesting. Please feel free to use whatever settings you want, the recommended settings are provided only as a baseline to get you started!

All game modes except for Search and Destory do not contribute towards your stats in a particular area (e.g., rank/skill level, kills, deaths). Search and Destroy contributes towards your Conquest Rank (similar to a substituted sub-game mode like __Home Nodes__ and __Lockdown__).

## Table of Contents
- [Custom Game Modes](#custom-game-modes)
  - [Table of Contents](#table-of-contents)
- [Infected](#infected)
    - [Recommended Settings](#recommended-settings)
- [Gun Game](#gun-game)
  - [Recommended Settings](#recommended-settings-1)
- [Spleef](#spleef)
  - [Recommended Settings](#recommended-settings-2)
- [Infinite Climber](#infinite-climber)
  - [Recommended Settings](#recommended-settings-3)
- [Search and Destroy (SND)](#search-and-destroy-snd)
  - [Recommended Settings](#recommended-settings-4)
- [Duck Hunt](#duck-hunt)
- [Survival](#survival)
  - [Bolts, Weapons & Mods](#bolts-weapons--mods)
  - [Weapon Tweaks](#weapon-tweaks)
  - [Reviving Teammates](#reviving-teammates)
  - [Weapon Pickups, Mods & Health](#weapon-pickups-mods--health)
  - [Recommended Settings](#recommended-settings-5)
  - [AI Difficulty](#ai-difficulty)
  - [Zombie Spawns](#zombie-spawns)
    - [Zombie Types](#zombie-types)

# Infected

A game mode derived from the the eponymously named game modes featured in the Halo and Call of Duty franchises.
Players become "infected" after dying and must hunt the remaining survivors using only their wrench and their speed!
Survivors, have the luxury of weapons, but have a limited health pool, limited ammo and only one life!
If the survivors last the duration of the game, they win, otherwise the infected win.

> __COMPATIBILITY:__ Infected is supported on all Normal and Custom Maps.

### Recommended Settings

- General
  - Game Type - __Deathmatch__
  - Radar Blips - __Off__
  - Special Pickups - __Off__
  - Charge Boots - __Always__
  - Autospawn Weapons - __Off__
  - Unlimited Ammo - __Off__
  - Time Limit - __5__
  - Team Play - __On__
  - Respawn Timer - __3__
- Weapon
  - Hunter Mine Launcher - __Off__
    > During playtesting, it was found that changing the weapons between matches added more variety to gamplay.
- Custom
  - Health Crates - __Off__

# Gun Game

A game mode derived from the Call of Duty series. This game mode is a free-for-all that requires you to get a kill with a random weapon to advance to the next weapon. The first player to get a kill with all 8 weapons and the wrench Wins! Be careful, getting killed by the Wrench demotes you back a weapon!

The first weapon is guaranteed to be the __Dual Vipers__.
The eighth weapon is guaranteed to the __Holoshield Launcher__ (yes you have to get a Holo kill to win)!
Weapons 2-7 are randomized between the [__Magma Cannon__, __The Arbiter__, __Fusion Rifle__, __Hunter Mine Launcher__, __B-6 Obliterator__, __Scorpion Flail__].
The order of weapons is the same for each player, but is randomized in-between games.
Once you get a kill with each weapon, you will be left with only your wrench, get a kill with it to end the game!

> __COMPATIBILITY:__ Gun Game is supported on all Normal and Custom Maps.

## Recommended Settings

- General
  - Game Type - __Deathmatch__
  - Special Pickups - __Off__
  - Charge Boots - __Always__
  - Unlimited Ammo - __On__
  - Time Limit - __10__
  - Team Play - __Off__

# Spleef

A game mode derived from Minecraft, where the goal is not to kill your opponent, but to destroy the ground below your opponent's feet. Spleef consists of 2-layers of destructable boxes. If you fall, don't worry, you will have a second chance!

A Spleef game is broken up into multiple matches.
The last player standing (or in many cases, the last player to hit the void) is awarded 3 points.
The second to last player to hit the void is awarded 2 points, and the third to last is awarded 1 point.
Everyone else gets a rock.
The first person to a specified number of points wins, or the person with the most points at the end of the time limit wins.

> __COMPATIBILITY:__ Spleef requires its specific custom map to play.

## Recommended Settings
- General
  - Game Type - __Deathmatch__
  - Special Pickups - __Off__
  - Charge Boots - __Always__
  - Autospawn Weapons - __On__
  - Unlimited Ammo - __On__
  - Team Play - __Off__
- Weapon
  - > Explosive Weapons (__The Arbiter__, __Hunter Mine Launcher__ and __B-6 Obliterator__) have splash damage which makes for chaotic gameplay and very fast rounds.
  - > If is recommended that you limit the total number of weapons to 3 to create a fair playing field. (if more than 3 weapons are available, other players may spawn with advatageous weapons).

# Infinite Climber

A game mode unique to Deadlocked. The floods have come, and you have no Ark! The water in each level is rising and your only hope of escape is to parkour up the floating debris. Your score is calculated based on how high you climb. The player who climbs the highest wins.

> __COMPATIBILITY:__ Infinite climber is supported by all 10 normal maps, but is currently not supported on custom maps.

## Recommended Settings
- General
  - Game Type - __Deathmatch__
  - Charge Boots - __Always__
  - Autospawn Weapons - __On__
  - Unlimited Ammo - __On__
  - Team Play - __On__
  - Survivor - __On__
    > This game mode is very challenging by itself. While multiple teams are supported, it is recommended that you all stay on as one team to have a longer game.
- Weapon
    > It is recommended that you only leave the __Magma Cannon__ and __Scorpion Flail__ active. The Magma Cannon is the best weapon for navigating with Charge Boots and playtesting has indicated that some people prefer to use the Scorpion Flail when performing hyperstrike jumps. Due to the frantic nature of this game mode, not spawning with these weapons may be a death sentence for unlucky players.
  - Dual Vipers - __Off__
  - The Arbiter - __Off__
  - Fusion Rifle - __Off__
  - Hunter Mine Launcher - __Off__
  - B-6 Obliterator - __Off__
  - Holoshield Launcher - __Off__

# Search and Destroy (SND)

A game mode derived from the Call of Duty franchise.
There are 2 bomb sites (nodes) on the map and 2 teams; an attacking team, and a defending team.
The objective of the attacking team is to destroy ONE of the bombsites, while the goal of the defending team is to protect BOTH bomb sites.
Death is permanent for the entire round for both teams.
The attacking team is given a bomb (Red Weapon Pack) at the start of each round, this bomb can only be carried by a single player, selected by the attacking team.
The attacking team has a choice of the two color-coded bomb sites (__PURPLE__ and __GREEN__).
The red weapon pack contains the hacker ray, which the bomb carrier must use to hack the node at the bomb site (i.e., plant the bomb).

Victory conditions are as follows:
1. If all players on the attacking team are killed before the bomb is planted, the defenders win.
2. If the round timer hits 0 wwithout the bomb being planted, the defenders win (even if they are all dead).
3. If the attackers plant the bomb, the defenders must defuse within in 30 seconds or the bomb will detonate and the attackers win (the bomb must be defused in time, even if all of the attackers are dead for the defenders to win the round).
4. If the bomb is planted and successfully defused, the defenders win.

If all of the defenders are dead and the bomb is planted, it detonates immediately (no 30 second delay).
The round time limit is paused while the bomb is planted.
If the bomb is dropped (i.e., the bomb carrier dies), other members of the attacking team can pick it up.
A game of SND consists of up to 11 rounds.
The first team to win 6 rounds wins the game.
Every 3 rounds, the teams switch sides.
Weapon upgrades/V2s (if enabled) are lost after each round is over.

Community playtesting has indicated that each Team using their own VC has been extremely effective, and has added a lot of depth to SND strategy.
Additionally, a common community rule has been that players mute themselves in Discord on death (Similar to group rules followed in games like Among Us).

> __COMPATIBILITY:__ Search and Destroy is supported by all 10 normal maps and the following custom maps.
>   * Maraxus Singleplayer (SP)
>   * Mining Facility Singleplayer (SP)
>   * Sarathos Singleplayer (SP)
>   * Temple of Shaar Singleplayer (SP)
>   * Tyhrranosis
>   * Torval Singleplayer (SP)

## Recommended Settings
- General
  - Game Type - __Conquest__
  - Radar Blips - __Off__
  - Special Pickups - __Off__
  - Charge Boots - __Always__
  - Autospawn Weapons - __On__
  - Unlimited Ammo - __On__
  - Team Play - __On__
- Weapon
  - > Due to the competitive nature of SND, games played have typically consisted of Cycle Weapons (__Magma Cannon__, __B-6 Obliterator__ and __Fusion Rifle__). Different weapon combinations could lead to exciting gamplay variants.
    >In order to guarantee a completely fair game, it is recommended that a maximum of 3 weapons are used so every player spawns with the same weapons.
- Custom
  - Health Crates - __Off__

# Duck Hunt

TBD! More info coming soon!

# Survival

A game mode derived from COD: Zombies and other wave-survival games.
You have limited ammo, one-life and must survive endless waves of oncoming zombies.
The difficulty increases with each wave (both in terms of the number of zomnies, type of zombies and threat of each zombie).

> __COMPATIBILITY:__
> Survival currently supports the following custom maps only.
>   * Mining Facility
>   * Marcadia Palace
>   * Veldin
> 
>__SURVIVAL REQUIRES THE LATEST [CUSTOM MAPS](./CMAPS.md)__!

## Bolts, Weapons & Mods
Killing zombies earns you bolts (bolts are shared by all people on your team in multiplayer).
The primary use for bolts is to upgrade your weapons.
Each map contains a weapon vendor and Big Al's workstation.
The weapon vendor is used to upgrade your weapons (V2-V10).
When upgrading your weapon, you will also be given a random Alpha Mod (__Impact Mod__, __Aiming Mod__, __Speed Mod__, __Ammo Mod__, __Area Mod__ and __Jackpot Mod__) - (__XP Mod__ and __NanoLeech Mod__ are not currently supported).
Upgrading a weapon __DOES NOT__ automatically apply the mod to a weapon, it only adds it to your inventory.
Big Al's workstation is used to configure mods between weapons.
There is a 20-second intermission in-between waves that can be used to safely upgrade and configure weapons.
This intermission is skippable by the host.
Any weapon mod can be mixed and matched on any weapon.
Each weapon upgrade cost more incrementatlly.
V10 Weapons, just like in single-player, dramatically improve the effectiveness of your weapon.

| Weapon Level | Cost      | Total Cost |
|--------------|-----------|------------|
| V1           |         0 |          0 |
| V2           |     8,000 |      8,000 |
| V3           |    12,000 |     20,000 |
| V4           |    20,000 |     40,000 |
| V5           |    40,000 |     80,000 |
| V6           |    60,000 |    140,000 |
| V7           |    90,000 |    230,000 |
| V8           |   150,000 |    380,000 |
| V9           |   220,000 |    600,000 |
| V10          |   350,000 |    950,000 |

## Weapon Tweaks
In order to balance out the PvE experience, multiple weapon tweaks have been made.
* The Scorpion Flail consumes ammo when twirled (this is to prevent scoring a large number of hits without using ammo).
* The holoshield launcher currently does not damage zombies, but will temporarily block them.
* The weapon damage tables have been modifed from single-player to make them more balanced (i.e., Single-player weapon damages [when upgraded above V2] are more potent depending on how late the weapon is acquired).
  > Please refer to the following [Google Sheet](https://docs.google.com/spreadsheets/d/1ODWP-W6m5kMcn3R2iyiF2Acty7T-gVUxQ9jwkyYoEgo/edit#gid=972887413) to view the weapon damage chanages made.

## Reviving Teammates
Bolts can also used to revive downed players in multiplayer.
Every time a player dies (regardless of whether they are revived or not), the price to revive them increases.
The price to revive for a first death is `5,000` bolts and increments by and additional `5,000` bolts per-death.
While it may be a difficult choice to revive a player when upgrading your own weapon compels you, it may be the better strategy in the long-term.
If a player is not revived, they lose all of their weapon upgrades and any mods attached to their weapons (Alpha mods in the player's inventory are not lost, nor are bolts that the player earned).
Upon death, a player is revivable to up to 60 seconds.
If 60 seconds passes, the player must wait until the next wave and will automatically spawn with no weeapons.
If the last zombie is killed while a player is dead (even if they are revivable), they will still spawn with no weapons.

## Weapon Pickups, Mods & Health

Each map contains a fixed amount of ammo, health and special pickups that must be shared between all players.
Weapon pickups are randomized each round to add variety to the game.
All weapons (including the Dual Vipers) are guaranteed to spawn as a pickup.
There will be more than one occurence of some weapons sometimes, use this to your advantage when disussing the weapons each teammate will use.

Thus far, each map contains 3 health crates and 2 special pickups (__Quad Damage__ and __Allied Shield__).

## Recommended Settings
- General
  - Game Type - __Deathmatch__
  - Radar Blips - __On/Short__
  - Special Pickups - __On__
  - Charge Boots - __Always__
    > Internal Playtesting has indicated that starting without chargeboots has low impact on overall difficult while also slowing down the first wave(s).
  - Autospawn Weapons - __Off__
  - Unlimited Ammo - __Off__
  - Team Play - __On__
    > Survival also supports a competitve mode (team-based and free-for-all [FFA]). More information on this game mode variant will be coming soon!
  - Survivor - __On__
    > Survivor can be disabled if you want to play a more casual version of zombies. In this mode, death won't end the game, but instead cost you all of your weapon upgrades.
- Custom
  - Health Bars - __On__

## AI Difficulty
Your Survival experience can be tailored through multiple difficulties.

| Difficulty   | Scale | Description                                                                                |
|--------------|-------|--------------------------------------------------------------------------------------------|
| Couch Potato | 0.25x | Meant for very casual play.                                                                |
| Contestant   | 0.50x | A step-up from Couch Potato, but still casual in nature.                                   |
| Gladiator    | 0.75x | The _standard_ difficulty which provides a good challenge, even for experienced players.   |
| Hero         | 1.00x | An advanced difficulty which requires intense teamwork, coordination and individual skill. |
| Exterminator | 1.50x | You will not survive.                                                                      |

## Zombie Spawns

Zombies spawn based on a round "budget"/allocation.
This budget is influcened by 3 factors:
1. The difficulty selected (__Couch Potato__ - __Exterminator__).
2. The wave number.
3. The number of players in the game<sup>2</sup>.

The round budget is used to determine how many zombies spawn per-wave and how many mutators are applied to specific zombies. Mutators increase the health, speed and damage output of zombies at random. Damage output and speed are capped per-zombie, but health is unbound and will increase as the waves go on.

As you reach higher waves, different types of more dangerous zombies will start to spawn.

### Zombie Types

* __Normal Zombie__ - The most common type of zombie to spawn. These zombies have modest health, put out moderate damage and are about 20% slower walking than the player. Normal zombies do not have special abilities and do not apply elemental damage.
* __Runner Zombie__ - An common variant of the normal zombie. These zombies are much faster (about 20%) faster than the player's walking speed. While difficult to avoid, these zombies put out much less damage than normal zombies and are easliy dispatched due to having lower health. These zombies can be difficult to distinguish from normal zombies, however, the rounded head is usually the best give-away.
* __Ghost Zombie__ - Ghost zombies are special zombies than become invisible over time. While invisible, these zombies are very difficult to see, do not appear on the minimap and are not targetable using the Dual Vipers, B-6 Obliterator, The Arbiter, Hunter Mine Launcher and V10 Magma Cannon. Ghost zombies have the same base stats as the normal zombies, but have the lowest chance to spawn out of any zombie.
* __Exploding Zombie__ - Exploding zombies are the bane of any melee-based build. When in range of the player, these zombies will ball up and begin a detonation countdown ending with an explosion capable of dealing fatal damage to any players (and unlucky zombies) caught within the blast range. __Warning__: Killing an exploding zombie once they begin their countdown will cause them to detonate prematurely. These zombies are easy to spot, they are red and tend to lumber behind or in the middle of a hoard.
* __Freeze Zombie__ - Freeze Zombies are elemental zombies whose swipe can apply the freeze effect on a player. The freeze effect inhibits movement speed and chargeboot speed by 50%. While freeze zombies pack a punch in terms of damage, the real danger is the risk of a follow-up attack. Freeze Zombies are identified by their blue color.
* __Acid Zombie__ - Acid zombies are elemental zombies whose seipe can apply the acid effect on a player. The acid effect deals an addition 15 damage (~30 % max player health) over time. The __Allied Shield__ pickup is especially vulnerable to the acid effect, and will not mitigate the acid damage. Acid zombies can be identified by their distict heads and green eyes and chest.

| Zombie           | Spawns on Wave | Spawn Rate   | Base Health | Base Speed | Base Damage | 
|------------------|----------------|--------------|-------------|------------|-------------|
| Normal Zombie    | 1              | 100.0%       | 1.0x        | 1.0x       | 1.0x        |
| Runner Zombie    | 1              |  14.0%       |             |            |             |
| Ghost zombie     | 5              |  3.5%        |             |            |             |
| Exploding Zombie | 7              |  5.0%        |             |            |             |
| Freeze Zombie    | 9              |  7.0%        |             |            |             |
| Acid Zombie      | 11             |  7.0%        |             |            |             |
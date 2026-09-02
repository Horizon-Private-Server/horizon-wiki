# Custom Game Modes

This page is dedicated to detailing all of the custom game modes available on the Horizon Private Server. Below each game mode is a list of recommended settings curated through developer and community playtesting. Please feel free to use whatever settings you want, the recommended settings are provided only as a baseline to get you started!

All game modes except for Search and Destroy do not contribute towards your stats in a particular area (e.g., rank/skill level, kills, deaths). Search and Destroy contributes towards your Conquest Rank (similar to a substituted sub-game mode like __Home Nodes__ and __Lockdown__).

## Table of Contents
- [Custom Game Modes](#custom-game-modes)
  - [Table of Contents](#table-of-contents)
- [Gun Game](#gun-game)
  - [Recommended Settings](#recommended-settings-1)
- [Infected](#infected)
    - [Recommended Settings](#recommended-settings)
- [Infinite Climber](#infinite-climber)
  - [Recommended Settings](#recommended-settings-3)
- [Search and Destroy (SND)](#search-and-destroy-snd)
  - [Recommended Settings](#recommended-settings-4)
- [Spleef](#spleef)
  - [Recommended Settings](#recommended-settings-2)
- [Survival](#survival)
  - [Bolts, Weapons & Mods](#bolts-weapons--mods)
  - [Weapon Tweaks](#weapon-tweaks)
  - [Reviving Teammates](#reviving-teammates)
  - [Weapon Pickups, Mods & Health](#weapon-pickups-mods--health)
  - [Recommended Settings](#recommended-settings-5)
  - [Zombie Spawns](#zombie-spawns)
- [Training](#training)
    - [Recommended Settings](#recommended-settings-6)
    - [Fusion (Sniper) Training](#fusion-sniper-training)

# Infected

A game mode derived from the eponymously named game modes featured in the Halo and Call of Duty franchises.
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
    > During playtesting, it was found that changing the weapons between matches added more variety to gameplay.
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
  - > Its recommended that you limit the total number of weapons to 3 to create a fair playing field. (if more than 3 weapons are available, other players may spawn with advantageous weapons).

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
2. If the round timer hits 0 without the bomb being planted, the defenders win (even if they are all dead).
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
  - > Due to the competitive nature of SND, games played have typically consisted of Cycle Weapons (__Magma Cannon__, __B-6 Obliterator__ and __Fusion Rifle__). Different weapon combinations could lead to exciting gameplay variants.
    >In order to guarantee a completely fair game, it is recommended that a maximum of 3 weapons are used so every player spawns with the same weapons.
- Custom
  - Health Crates - __Off__

# Survival

A game mode derived from COD: Zombies and other wave-survival games.
You have limited ammo, one-life and must survive endless waves of oncoming zombies.
The difficulty increases with each wave (both in terms of the number of zombies, type of zombies and threat of each zombie).

> __COMPATIBILITY:__ Survival requires specific custom maps to play.

## Bolts, Weapons & Mods
Killing zombies earns you bolts (bolts are shared by all people on your team in multiplayer).
The primary use for bolts is to upgrade your weapons.
Each map contains a weapon vendor and Big Al's workstation.
The weapon vendor is used to upgrade your weapons (V2-V10).
When upgrading your weapon, you will also be given a random Alpha Mod (__Impact Mod__, __Speed Mod__, __Ammo Mod__, __Area Mod__, __XP Mod__ and __Jackpot Mod__) - (__Aiming Mod__ and __NanoLeech Mod__ are not currently supported).
Upgrading a weapon __DOES NOT__ automatically apply the mod to a weapon, it only adds it to your inventory.
Big Al's workstation is used to configure mods between weapons.
There is a 45-second intermission in-between waves that can be used to safely upgrade and configure weapons.
Players can vote to skip this intermission with the host being able to bypass it.
Any weapon mod can be mixed and matched on any weapon.
Each weapon upgrade costs more incrementally.
V10 Weapons, just like in single-player, dramatically improve the effectiveness of your weapon.
Below is the standard upgrade cost table. This may vary per map.

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
* The holoshield launcher will temporarily block zombies.
* The weapon damage tables have been modified from single-player to make them more balanced (i.e., Single-player weapon damages [when upgraded above V2] are more potent depending on how late the weapon is acquired).

## Reviving Teammates
Upon going down, a player is revivable for up to 60 seconds. They can be revived by standing over that player.
If 60 seconds passes, the player dies and must wait until the next wave. Their weapon will also be downgraded one level upon respawning.

## Weapon Pickups, Mods & Health

Each map contains a fixed amount of ammo, health and special pickups that must be shared between all players.
All weapons (including the Dual Vipers) are guaranteed to spawn as a pickup.
There will be more than one occurrence of some weapons sometimes, use this to your advantage when discussing the weapons each teammate will use.

The amount of weapon, health and special pickups can vary between maps.

## Recommended Settings
> Settings surrounded by \*asterisks\* must be set for the game to count towards your [Stats](#stats).

- General
  - Game Type - __Deathmatch__
  - Radar Blips - __On/Short__
  - Special Pickups - __On__
  - Charge Boots - __Always__
    > Internal Playtesting has indicated that starting without chargeboots has low impact on overall difficult while also slowing down the first wave(s).
  - Autospawn Weapons - __Off__
  - Unlimited Ammo - __\*Off\*__
  - Team Play - __On__
    > Survival also supports a competitive mode (team-based and free-for-all [FFA]). More information on this game mode variant will be coming soon!
  - Survivor - __\*On\*__
    > Survivor can be disabled if you want to play a more casual version of zombies. In this mode, death won't end the game, but instead cost you all of your weapon upgrades.
- Custom
  - Health Bars - __On__

## Zombie Spawns

Zombies spawn based on a round "budget"/allocation.
This budget is influenced by two factors:
1. The wave number.
2. The number of players in the game.

The round budget is used to determine how many zombies spawn per-wave.
As you reach higher waves, different types of more dangerous zombies will start to spawn.

## Stats

Survival supports stat tracking and leaderboards for the following stats. Stats are automatically uploaded to the server at the end of the game.

> __NOTE:__ Stats are only tracked for games with the correct settings. Please view the [Recommended Settings](#recommended-settings-5) for a list of required game settings.

### Overall
| Stat          | Description                                         |
|---------------|-----------------------------------------------------|
| Rank          | This is your overall survival rank.                 |
| Completion    | Total completion of all maps (gambits, round 50...) |
| Games Played  | Total number of survival games played.              |
| Time Played   | Total number of hours of survival played.           |
| Kills         | Total number of zombie kills.                       |
| Deaths        | Total number of deaths.                             |
| Revives       | Total number of times you revived a teammate.       |
| Times Revived | Total number of times you've been revived.          |
| Weapon Kills  | Total number of zombie kills, per weapon.           |

### Per Map
| Stat                  | Description                                                                                                                    |
|-----------------------|--------------------------------------------------------------------------------------------------------------------------------|
| Prestige              | Prestige rank. Based on how much you have played.                                                                              |
| Experience            | This is the total gained XP. XP is directly proportional to the number of bolts you've gained and the difficulty of the match. |
| Solo High Score       | Highest round in solo.                                                                                                         |
| Solo Fastest Round 50 | Fastest time to get to round 50 in solo.                                                                                       |
| Coop High Score       | Highest round in coop.                                                                                                         |
| Coop Fastest Round 50 | Fastest time to get to round 50 in coop.                                                                                       |
| Gambit Completion     | Completion of different gambits.                                                                                               |

### Viewing Stats

To view stats, you must join the [Horizon Discord](https://rac-horizon.com/discord) and use the following slash command. Replace `ACCOUNTNAME` with your account name.

    /deadlocked-survival-stats ACCOUNTNAME

# Training

A game mode designed to help players practice combat on simple bots.

Training supports the following training modes:
 - [Fusion Rifle (Sniper) Training](#fusion-sniper-training)

### Recommended Settings

- General
  - Game Type - __Deathmatch__
  
### Fusion (Sniper) Training

In this mode you are given only a Fusion Rifle. You have 5 minutes to kill as many bots as you can. You are rewarded points for killing the bots. Points are based on the following rules:

  - Minimum 250 points per kill
  - Additional 5 points per unit of distance between the player and the killed bot
  - Up to 4x point multiplier for long distance shots
  - 1.5x point multiplier for jump snipes
  - 2x point multiplier for double jump snipes
  - Consecutive kills (combos) add an additional .1x to the point multiplier
  - Additional points are rewarded for kills made in quick succession

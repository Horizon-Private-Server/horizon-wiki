# Multiplayer Bots

Multiplayer bots have been created to play alongside or against other bots and players.

For a video tutorial, [click here](https://www.youtube.com/watch?v=kq6FEfRyoZg).  
- *NOTE: Since this tutorial was recorded, the server response when inviting a bot has changed. It will now say "cpu_ NOT FOUND". Don't worry, the bot should still join the game in 1-3 minutes.*


## Maps and Modes Bots can Play:
_Team_ Deathmatch: Bots can play on all maps (the Teams setting must be set to Yes).

CTF: Bots can play on Marcadia Palace, Aquatos Sewers, Blackwater Docks, and Command Center. _Note that for CTF, bots only seek and destroy and do not play objectives (e.g. they do not pick up the flag)._

Siege: No support yet - coming soon!


## Weapons Supported:
Weapons that work against bots: Gravity Bomb, Blitz, Flux, Lava Gun, N60, Rockets

Weapons that bots can use: Gravity Bomb, Flux, N60, Rockets


## Inviting Bots
_IMPORTANT: Bots should only be invited after all human players have joined the game._

Bots can be invited using the normal "Invite Player" menu within the game. Once you send the invite, the server will send an intial response "cpu_ NOT FOUND". This is normal so just press OK. After that, the bot can take up to 3 minutes to join the game.  

Below is a table of the bot names to invite:

| Bot name  | Description |
| ------------- | ------------- |
| cpu0  | Basic CPU that will just follow around other players. Does not fire any weapons.  |
| cpu1  | CPU that will fight but has low accuracy. |
| cpu2  | CPU that will fight but has better accuracy than cpu1. |
| cpu3  | CPU that will fight but has better accuracy than cpu2. |
| cpu4  | CPU that will fight but has better accuracy than cpu3. Can cycle weapons. |
| cpug  | [**EPILEPSY WARNING**] [**WARNING: CAN CRASH YOUR PS2 IF MULTIPLE OF THESE BOTS JOIN**] God mode CPU that has 1000 health and no limits on weapon firing and has aimhack. See the bottom of this page for the CPUG challenge! |


## FAQ
1. I tried to invite the bot and it says "cpu_ NOT FOUND"!
- This is normal. Just wait for 1-3 minutes and the bot should join.

2. How many bots can I invite?
- You can invite as many bots as there are slots.

3. How do I make the bot change teams?
- To make them change colors, you can use the "request team change" in staging.

4. Why did the bot leave the game?
- By default, the CPUs will only stay in the game for 2 hours once they enter staging. However, you can have the bots stay longer by adding the number of hours with a dash in the invite. For example, cpu4-5 would be inviting a cpu4 for 5 hours of gameplay.

5. It takes a long time to kick a bot from a game!
- Yeah - it typically takes about 45 seconds.

6. I think I found a bug!
- Please post in the `#uya-crash-logs` channel on our Discord.

7. Where can I find the source code for multiplayer bots?
- Right over [here](https://github.com/Horizon-Private-Server/horizon-uya-bot).


## CPUG Challenge
_Challenge requirements updated April 2023 based on feedback from community members!_  
Beat the CPU God and earn the Godlike role on our Discord server! This role will be highlighted in the list of online users, and your name will show up in a special color.

To challenge the bot, create a game with the following settings:
- Map = Marcadia Palace
- Mode = Deathmatch
- Frag Limit >= 10
- Teams = On (remember, bots only play _Team_ Deathmatch mode at this time). However, you must 1v1 the bot. You cannot defeat it alongside other players.
- Weapons: Either Blitz/Flux/Gravity or Flux Only

Once you create the lobby, invite the bot per instructions above.

Use of the following tactics in this challenge are NOT allowed:  
- Holo shield gloves.  
- Ledge sniping.  
- Other cheats and hacks.

Grabbing health is acceptable.

You also must record the game. A smartphone, etc. recording is fine if you do not have a capture card. Send Fourbolt or DeathBySnowman the video recording of the entire game (we recommend sending privately so that others cannot see how you managed to defeat the bot!) Fourbolt or DBS will verify that the win is legitimate, then award you the Godlike role!

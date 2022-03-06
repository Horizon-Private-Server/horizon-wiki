# Deadlocked Chat Commands

The Horizon server offers a small number of useful in-staging chat commands for players to use.

## Table of Contents
- [Roll](#roll)
- [Teams](#teams)

## Roll

*[ALL PLAYERS]*

Will generate a random number between 1 and 100 (inclusive) for the player issuing the command.

Command:
```!roll```

Arguments:
```None```

Example:

![image](https://user-images.githubusercontent.com/2020854/156937124-c60f5263-145d-4906-a1c5-876df2b2f86f.png)

## Teams

*[HOST ONLY]*

Will **randomly** assign teams to players based on the given arguments.

Command:
```!tm```

Arguments:
```'ffa'|<team names>```

Examples:

```!tm```

Puts half the players on blue team and the other half on red team.

![image](https://user-images.githubusercontent.com/2020854/156937445-4749f17c-27df-4e89-8c35-21233bd24709.png)

```!tm ffa```

Randomly assigns each player to their own team.

![image](https://user-images.githubusercontent.com/2020854/156937461-f84fbd8a-23fb-4fdd-a621-6483c21face5.png)

```!tm red green orange```
```!tm r g o```
```!tm 1 2 3```

Will randomly assign players to the red, green, or orange team. In the following images, since there are 10 players and 3 teams, one team will have 4 players.

<p float="left">
  <img src="https://user-images.githubusercontent.com/2020854/156937475-58906864-e8e5-4920-81ea-3bcf689f3d10.png" width="300" />
  <img src="https://user-images.githubusercontent.com/2020854/156937495-e9e5e680-507e-48f2-b5f9-ec2e573f8b2b.png" width="300" /> 
  <img src="https://user-images.githubusercontent.com/2020854/156937505-c13e306f-b74d-4a1d-aac5-7712ea01ebc8.png" width="300" />
</p>

# Custom Features in 'Cities' Screen

## In-Progress Game Information
Once a game has started, the game will remain listed on the Cities screen but with an `[IG]` prefix. This indicates that the lobby is "in-game".
You will not be able to join any in-progress games, and if you try to do so it may cause a network error - meaning that you will have to reconnect.

## Lag Adjustment
Players can use the Cities "Send Message" functionality to set the DME TCP(tagg)/UDP(uagg) times manually for the next world (game) they create. The TCP/UDP agg time is the amount of time the server will aggregate packets before sending the data to the other players. In plain English, this means that you can affect the amount of lag for the next game that you create. It will only have an effect if you set one or both values, then create a game, then play the game (if you set them but then join someone else's game, they will be reset).

To adjust the values, use the "Send Message" pop-up in the Cities screen and enter one of the following commands: `!tagg [number]` or `!uagg [number]` . The default in the game is 10 for both tagg and uagg. Recommended values range from 0-10. Higher = more lag (generally). UDP(uagg), is responsible for player movement, and more, while TCP(tagg) is responsible for wrench, and more.

# Releases for the Archipelago implementation of Ori and the Will of the Wisps

## Disclaimer

The implementation is in an alpha state. Some features are missing and there are some bugs, but you should be able to play without too much trouble.

## Source code

[AP World](https://github.com/Satisha10/Archipelago_wotw/tree/main/worlds/ori_wotw)

[Client code](https://github.com/ori-community/wotw-rando-client/tree/archipelago)

## Setup guide

### AP World

Download the AP world from this repository and install it by double-clicking it (make sure to restart the Archipelago launcher before generating). There are some `.yaml` templates in the `Yaml template` folder for different logic difficulties (Moki being the easiest, Kii the hardest).

### Client installation

- Download the [standalone WotW randomizer](https://wotw.orirando.com/).
- Make sure that you are on a version above 4.31.0. (and above 4.38.0 for the latest AP World)
- The randomizer can be detected as a malware by some antiviruses. If you use Windows Defender, you can add an exception in `Settings -> System`.s

### Connecting to the Archipelago game

In the Ori randomizer launcher, click on the three dots next to settings, then `Play Archipelago`. Enter the connection informations, and launch the game. If successful, a message will be displayed when opening a save file.
Remark: when connection to a game hosted on `archipelago.gg`, make sure to enable secure connection. Disable it if you connect to `localhost` or an IP address.

## Important remarks

- There is a [wiki](https://wiki.orirando.com/) for the randomizer if you want more information about it or to learn some tricks/glitches.
- The randomizer has a tracker that you can start from the launcher, as well as a logic filter for the map, that shows the all the locations and highlights the ones that are in logic.

## Feedback

You can report issues or give suggestions in the Archipelago Discord server (in the corresponding discussion of [`future-game-design`](https://discordapp.com/channels/731205301247803413/1272952565843103765) ). I will also see it if you send it in the Ori Runs or the Ori Rando Dev Server.

## Known issues

- Seed generation often fails, you will likely need several generation attempts before a successful one.
- The pickup counter in the game does not work.
- Depending on the settings, some locations hold a `Nothing` item instead of not existing. This is a temporary workaround for a crash.
- Receiving items during a spirit trial can cause the items to desynchronize. If this happen with an important item, you can make a new save file to get it.
- Released locations count for the goals.

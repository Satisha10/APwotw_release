# Releases for the Archipelago implementation of Ori and the Will of the Wisps

## Disclaimer

The implementation is in an alpha state, so you will likely encounter bugs or crashes when playing.

## Source code

[AP World](https://github.com/Satisha10/Archipelago_wotw/tree/main/worlds/ori_wotw)

[Client code](https://github.com/ori-community/wotw-rando-client/tree/archipelago)

## Setup guide

### AP World

Download the AP world from this repository and intall it by double-clicking it. There are some `.yaml` templates in the `Yaml template` folder for different logic difficulties (Moki being the easiest, Kii the hardest).

### Client installation

- Download the [standalone WotW randomizer](https://wotw.orirando.com/)
- Update to the latest **Beta** release of the randomizer, either from the launcher (go to Settings, press `Ctrl` 5 times and enable `Update to prerelease versions`), or from [the repository](https://github.com/ori-community/rando-build/releases/latest).
- The randomizer can be detected as a malware by some antiviruses. If you use Windows Defender, you can add an exception in `Settings -> System`.

### Connecting to the Archipelago game

In the launcher, click on the three dots next to settings, then `Play Archipelago`, and enter the connection informations, and launch the game. If successful, a message will be displayed when opening a save file.

## Feedback

You can report issues or give suggestions in the Archipelago Discord server (in the corresponding discussion of `future-game-design`). I will also see it if you send it in the Ori Runs or the Ori Rando Dev Server.

## Remarks

- There is a [wiki](https://wiki.orirando.com/) for the randomizer if you want more information about it or to learn some tricks/glitches.
- The randomizer has a tracker that you can start from the launcher, as well as a logic filter for the map, that shows the all the locations and highlights the ones that are in logic.
- The AP client is compatible with the base randomizer.
- If the port changes, you need to make a new save file.

## Known issues

- Seed generation often fails, you will likely need several generation attempts before a successful one.
- The pickup counter in the game does not work.
- Better Wellspring has no effect.
- With some settings, some locations hold a `Nothing` item instead of not existing.

# Releases for the Archipelago implementation of Ori and the Will of the Wisps

## Disclaimer

The implementation is in an alpha state, so you will likely encounter bugs or crashes when playing.

## Source code

AP World: https://github.com/Satisha10/Archipelago_wotw/tree/main/worlds/ori_wotw

Client code: https://github.com/Satisha10/wotw-rando-client/tree/AP_local

## Setup guide

You can download the latest release from this repository (download the `AP_WotW.zip` file, and extract it). You will probably get a warning from the antivirus, since the client works by injecting code in the game.

The folder contains the Archipelago world `ori_wotw.apworld` that you can install. There are some `.yaml` templates in the `Template` folder for different logic difficulties (Moki being the easiest, Kii the hardest).

### Client installation

- Download the standalone WotW randomizer from https://wotw.orirando.com/
- In the home page, there is a small button (on the right) to open the randomizer directory. In this folder, paste the binaries from the `Client` folder. This will override the existing ones (you can stash them somewhere or reinstall a stable version later).
- The randomizer can be detected as a malware by some antiviruses. If you use Windows Defender, you can add an exception in `Settings -> System`.

### Connecting to the Archipelago game

- Once you generated a game, grab from the output folder a `.wotwr` file (it should have your slot name in it).
- Open this file with a text editor and fill the `APAddress:` and `APPort:` champs with the connection informations (the `APSlot:` line should already contain your slot name).
- Open this file with the WotW launcher. If everything worked, you will be connected after starting a new save file.
- For now, the game needs to be hosted in the website.

If you want to more information about the WotW randomizer or to learn some glitches, you can check the wiki https://wiki.orirando.com/

## Feedback

You can report issues or give suggestions in the Archipelago Discord server (in the corresponding discussion of `future-game-design`). I will also see it if you send it in the Ori Runs or the Ori Rando Dev Server.

## Known issues

- The items that you get after starting a save file can be received again
- Using `_` in your slot name can lead to problems when hosting the game in the website (you can try to remove the `.wotwr` file from the zip file if it happens).
- Seed generation often fails when calculating playthrough if `accessibility: minimal` is not set.

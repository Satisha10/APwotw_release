# Releases for the Archipelago implementation of Ori and the Will of the Wisps.

## Disclaimer

The implementation is in an alpha and very bugged state, and is only barely playable. You should only play it if you want to help with testing.

## Source code

AP World: https://github.com/Satisha10/Archipelago_wotw/tree/main/worlds/ori_wotw

Client code: https://github.com/Satisha10/wotw-rando-client/tree/AP_local

## Setup guide

You can download the latest release from this repository (download the `AP_WotW.zip` file, and extract it). You will probably get a warning from the antivirus, since the client works by injecting code in the game.

The floder contains the Archipelago world `ori_wotw.apworld` that you can install. There are some `.yaml` templates in the `Template` folder for different logic difficulties (Moki being the easiest, Kii the hardest).

### To install the client:

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

## Current issues

- Probably a lot of crashes.
- Items received from another game are only available after a location is collected.
- The game need to be hosted on the archipelago website, local host does not work for now. (fix maybe found)
- Seed generation fails often, especially in Moki difficulty. You can try to use `accessibility: minimal` and set spoiler log to 1, which might help.
- The last item that you collected can be duplicated when you respawn.
- Some locations are automatically given when they are excluded, they should not be in the pool instead.
- If you exit the game, you lose the items that you received until the last time you saved.
- Item cheating does not work well.

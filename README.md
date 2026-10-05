# Balatrogether

Balatrogether is a Balatro mod for two players. In a duel, each player's health is the other player's blind. In co-op, both players face the same blind together.

This repository holds the downloads. Get the latest zip from [Releases](https://github.com/nanoqoi/balatrogether-releases/releases/latest). Both players need the same version.

## Requirements

- Balatro 1.0.1o or newer
- [Lovely](https://github.com/ethangreen-dev/lovely-injector/releases) 0.8 or newer, the injector that loads mods
- [Steamodded](https://github.com/Steamodded/smods/releases) 1.0.0~BETA-1221a or newer, the mod loader

Online play goes through Steam, on Windows. Linux through Proton should work the same way but hasn't been tested. macOS isn't supported yet.

## Install

1. Install Lovely and Steamodded from their release pages.
2. Unzip the Balatrogether download into the `Mods` folder, which is `%AppData%\Balatro\Mods` on Windows. The result must be `Mods/Balatrogether/core.lua`.
3. Start Balatro. A **Mods** button on the main menu, with Balatrogether in its list, means it works.

To update, delete the old `Mods/Balatrogether` folder and unzip the new version. Both players must update.

## Play

Pick **Duel** or **Co-op** on the main menu, then **Host a match**, and invite a friend through Steam. The friend joins from the invite or from the list of friends hosting a match. Before the match starts, the lobby checks that both players run the same mods with the same settings.

Matches use a profile of their own, so single-player runs, profiles and stats are never touched.

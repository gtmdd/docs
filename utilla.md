# Gorilla Tag Mod Developer Documentation
> Version 2024.11

## Utilla
Utilla is a free, open-source, and simple streamlining utility for Gorilla Tag mods. It is the easiest way to ensure your mod is a "legal" mod. You may pick up a copy from here:

- [legoandmars/Utilla](https://github.com/legoandmars/Utilla): Utilla

This is the mod that enables the Modded rooms. Modded rooms are the only place you're *technically* allowed to use legal mods. While all mods are bannable, it is much less likely to be banned in a modded than in a public lobby. Your ban appeals will also be more likely to be accepted if your ban was for modding in a modded lobby.

### Implementing Utilla
Utilla uses `[ModdedGamemode]` to make your mod legal. This enforces modded gamemodes ONLY for your mods. With Utilla 1.5.1, this is now required. 
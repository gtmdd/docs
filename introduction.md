# Gorilla Tag Mod Developer Documentation
> Version 2024.10
Updated 2024.10.15 - 2:26 PM CST (Chicago / Dallas)

## Welcome

This document contains documentation on the internal libraries and creation of Gorilla Tag mods. Please note that modding is NOT supported by Another Axiom or Lemming and is bannable if server-sided.

This document is NOT made by or affiliated with Another Axiom or Gorilla Tag. This is community-made. For information, contact a maintainer:

- Erik, Project Lead. Discord: stickmaster10.
## Mods Classification
### Legal Mods
Legal mods are mods that do not interfere with the server side of the game. These are client-side only mods that do not give you a competitive advantage.

Some of these mods include:
- Yizzi’s Camera Mod: A client-sided camera mod that lets you control the FOV, camera position, and other client-side only mod. This is NOT bannable.

## Illegal Mods
Illegal Mods give you a competitive advantage or are server-sided and interfere with the game. These include:
- ii’s Stupid Menu: A mod menu that provides many illegal mods. This is VERY bannable.
- PlayerTrakkar: A player tracker. Player trackers are a guaranteed ban with no appeal.

## Make Sure Your Mod Is Legal
Legal mods are the only mods that will not get you banned. Using a library that provides a safe space for modding, like Utilla will decrease the chance of you getting banned.

When you develop a mod, ensure your mod is not bannable. Making legal mods is way more shined upon over illegal mods.

## Prerequisites
Before you begin using this guide to develop mods, you should know how to use these tools, understand these concepts, and know how to implement them or use them effectively.

- C#, or the .NET Framework: .NET is a framework for the C# language that Gorilla Tag uses. All mods are coded in C#. This is required to code any mods. If you have used a software like Windows Forms, you may already know what is required to use it.
- Utilla: A utility for implementing your mod. It lets you use it’s built-in modded lobbies feature, which should be implemented if your mod gives you a competitive advantage.

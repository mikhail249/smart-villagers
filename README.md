# Smart Villagers

Forge mod releases for **Minecraft 1.19.2, 1.20.1 and 1.21.11**.

[Download 0.24.2 from Releases](https://github.com/mikhail249/smart-villagers/releases/tag/v0.24.2) · [CurseForge](https://www.curseforge.com/minecraft/mc-mods/smart-villagers) · [Modrinth](https://modrinth.com/mod/miha-huntercool-smart-villagers)

This repository distributes release builds and installation information. Source code is not included.

## What villagers can do

- Build projects on your orders using a bell construction console, imported schematics and translucent holograms.
- Work as scientists, market and restaurant managers, cashiers, janitors, waiters, beekeepers, cooks, guards and rebels, with profession outfits and trades.
- Run equipped laboratories, stocked markets and restaurants using included building blueprints.
- Offer quests, reputation, village prosperity, leadership and festivals.

## Installation

| Minecraft | Forge build | Java |
| --- | --- | --- |
| 1.19.2 | 43.5.2 | 17 |
| 1.20.1 | 47.4.22 | 17 |
| 1.21.11 | 61.0.1 | 21 |

Install Forge for your Minecraft version. Download **only the matching JAR** from Releases and place it in the game `mods` folder. Replace the previous Smart Villagers JAR when updating. Multiplayer needs the corresponding build on both client and server.

## Construction

Builders wait for a command. Shift-right-click a village bell, choose the blueprint, site, rotation and builders, put supplies in nearby chests or barrels, then press Start. Keep storage and build targets reachable, including upper floors.

Place import files in `config/smartvillagers/schematics` in the game or server directory. Supported formats: Sponge `.schem` v2/v3 and Litematica `.litematic` v4–v7. Imports copy blocks and block states, without entities, container contents or other block-entity data.

Version 0.24.2 fixes builder dialogue material requests: they now follow the active blueprint, include glass and the exact wood species, and account for placed blocks, nearby storage and carried supplies. Validation: 464 GameTests passed across the three builds.

## Dialogue and AI disclosure

Local dialogue works by default. Optional cloud dialogue requires server configuration and sends requested messages and player/village context to the selected AI provider. Provider fees and retention policies may apply.

Code, profession textures and portions of text were developed using generative AI, including Codex and image generation.

## License and feedback

**All Rights Reserved.** Public download access does not grant an open-source license.

Report bugs in Issues with the Minecraft, Forge and Smart Villagers versions, steps to reproduce, and relevant screenshots. Do not include API keys or other credentials.

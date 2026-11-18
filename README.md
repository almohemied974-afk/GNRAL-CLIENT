# GNRAL CLIENT

GNRAL CLIENT is a desktop launcher and a Fabric mod for **Minecraft: Java Edition 26.3**.

> Status: alpha, in development. Not affiliated with Mojang AB or Microsoft.

## What it does

- **Launcher** (Electron, React, TypeScript): manages isolated game profiles, installs the Fabric loader and the GNRAL mod, and starts the game.
- **Official sign-in only:** players sign in with their own Microsoft account through the official Microsoft flow (authorization code + PKCE in the system browser). The launcher never asks for or stores passwords, and it does not use a client secret.
- **Ownership check:** the game is only launched after Minecraft Services confirm that the signed-in account owns Minecraft: Java Edition. No authentication, ownership or license check is bypassed.
- **Fair-play features:** HUD modules, performance options, inventory and shulker previews, original client-side cosmetics, a friends list and opt-in presence.
- **No cheats:** no aim assist, no combat changes, no extra entity information beyond vanilla.

## Privacy

- Server sharing, public profiles and presence are off by default (opt-in).
- No coordinates are collected. An optional "Address Hider" keeps server addresses private.
- Account tokens stay on the player's own computer.

## Languages

English, German and Arabic (right-to-left).

## Contact

Questions about this project: please open an issue in this repository.

# CIT Reforged Continued

CIT Reforged Continued is an unofficial continuation of CIT Reforged, a Forge port of CIT Resewn. It re-implements MCPatcher and OptiFine-style Custom Item Textures for players who want CIT resource pack support on Forge without using OptiFine.

This default branch currently targets Minecraft `1.20.1` on Forge `47.1.3`.

## What It Does

Custom Item Textures let resource packs replace item models or textures based on item properties such as name, damage, enchantments, or other CIT rules.

This mod is intended for resource packs that already support CIT Resewn, CIT Reforged, MCPatcher, or OptiFine-style CIT.

## Installation

1. Install Forge for Minecraft `1.20.1`.
2. Put the CIT Reforged Continued jar in your `mods` folder.
3. Launch the game once.
4. Put a CIT-compatible resource pack in `resourcepacks`.
5. Enable the resource pack in-game.

Do not install this together with another mod that provides the same CIT implementation unless the release notes explicitly say it is compatible.

## Downloads

Use the approved Modrinth or CurseForge project page when available. Development builds may also be attached to GitHub releases for this repository.

## Compatibility

This fork is focused on Forge. For Fabric or NeoForge, use the appropriate CIT Resewn Continuation build instead.

Known useful test packs include packs with custom named items, damage-based item textures, and enchantment-based item overrides.

## Reporting Issues

Open issues on this repository for bugs in the continuation fork.

Include:

- Minecraft version
- Forge version
- mod version
- resource pack name and version
- a minimal example CIT file when possible
- `latest.log` or the crash report

## Building

```bash
./gradlew build
```

Built jars are written to `build/libs`.

## Credits

CIT Reforged Continued is based on the original CIT Reforged and CIT Resewn work. Original credits are preserved in the mod metadata.

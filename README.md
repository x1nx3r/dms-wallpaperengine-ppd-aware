# DMS-WallpaperEngine (PPD Aware Fork)

A DankMaterialShell plugin for [linux-wallpaperengine-ppd-aware](https://github.com/x1nx3r/linux-wallpaperengine-ppd-aware).

> **Note:** This is a fork of the original plugin that adds support for the `--pause-on-battery` and `--pause-on-power-saver` flags. It requires the specialized fork of `linux-wallpaperengine` linked above.

![dms-wallpaperengine Screenshot](screenshot.png)

## Installation

### Pre-requisites
1. Install the PPD Aware fork of [linux-wallpaperengine](https://github.com/x1nx3r/linux-wallpaperengine-ppd-aware).

### Manual Installation
Since this is a specialized fork, it is not available in the Plugin Registry. You must install it manually:

```bash
# Clone the repository
git clone https://github.com/x1nx3r/dms-wallpaperengine-ppd-aware.git

# Create the plugins directory if it doesn't exist
mkdir -p ~/.config/DankMaterialShell/plugins/

# Copy the plugin to the DMS plugins directory
cp -r dms-wallpaperengine-ppd-aware ~/.config/DankMaterialShell/plugins/linuxWallpaperEnginePPDAware

# Enable in DMS settings under Plugins tab.
```

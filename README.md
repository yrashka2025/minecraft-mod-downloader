# Minecraft Mod Downloader

A simple and powerful tool to download Minecraft mods from Modrinth with an easy-to-use console interface.

## Features

- **Single Mod Download**: Search and download individual mods by name
- **Batch Download**: Download multiple mods at once with custom settings for each
- **Popular Mods**: Automatically download popular mods by category (optimization, graphics, utilities, etc.)
- **Ready-made Sets**: Download curated sets of popular mods (optimization packs, graphics mods, etc.)
- **Safe GUI Fallback**: Works with both console and GUI input for EXE distributions
- **Progress Tracking**: Real-time download progress with visual progress bars
- **Duplicate Handling**: Automatically handles filename conflicts
- **Cross-platform**: Works on Windows, macOS, and Linux

## Requirements

- Python 3.6+
- `requests` library
- Internet connection

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Yrashka2025/minecraft-mod-downloader.git
   cd minecraft-mod-downloader
   ```

2. Install dependencies:
   ```bash
   pip install requests
   ```

## Usage

Run the script:
```bash
python minecraft.py
```

### Main Menu Options

1. **Download One Mod**: Search for a specific mod by name
2. **Batch Download**: Download multiple mods with individual settings
3. **Download Popular Mods**: Choose from automatic category-based downloads or ready-made sets
4. **Show Downloaded Mods**: View and manage your downloaded mods
5. **Exit**: Close the program

### Mod Loaders Supported

- Fabric
- Forge
- Quilt
- NeoForge
- Any (all loaders)

### Categories Available

- Utilities and tools
- Gameplay and mechanics
- Biomes and nature
- Optimization and performance
- Graphics and visual effects
- Building and decoration
- Weapons and armor
- Storage and organization
- Magic and mysticism
- Technology and automation
- Search and maps

## Building EXE (Optional)

To create a standalone executable:

```bash
pip install pyinstaller
pyinstaller --onefile minecraf.py
```

The EXE will be created in the `dist/` folder.

## Project Structure

```
minecraft-mod-downloader/
├── minecraft_mod_downloader.py  # Main script
├── Mods/                        # Downloaded mods folder (auto-created)
├── README.md                    # This file
└── .gitignore                   # Git ignore file
```

## API

The tool uses the official Modrinth API (https://api.modrinth.com/v2) to search and download mods.

## License

This project is open source. Feel free to use and modify as needed.

## Contributing

Contributions are welcome! Please feel free to submit issues and pull requests.

## Disclaimer

This tool is not affiliated with Mojang, Microsoft, or Modrinth. Always ensure you comply with the terms of service of the mod hosting platforms and respect mod authors' licenses.

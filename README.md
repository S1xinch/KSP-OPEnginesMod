# KSP OP Engines Mod

A comprehensive Kerbal Space Program mod that provides overpowered engine variants designed for sandbox players who want enhanced propulsion capabilities without balance constraints.

## Overview

This mod replaces several stock KSP engines with significantly upgraded "OP" (overpowered) versions. Perfect for sandbox mode players who want to focus on ship design and exploration without worrying about fuel efficiency or thrust limitations.

### Included Engines

1. **CR-8.5 R.A.P.I.E.R. Mk2.5** - Hybrid air-breathing/closed-cycle engine
   - Air-breathing mode: 1000 kN max thrust
   - Closed-cycle mode: 6000 kN max thrust
   - Excellent for atmospheric and space operations

2. **CR-8.5 R.A.P.I.E.R. Mk2** - Enhanced hybrid engine variant
   - Alternative configuration for design flexibility
   
3. **LV-T30 "Reliant" Mk2** - Enhanced main liquid fuel engine
   - Increased thrust output for heavier payloads

4. **Ion Engine Mk2** - Enhanced ion thruster
   - Improved specific impulse for long-duration missions

5. **Turbo Ramjet Mk2 "Whiplash"** - High-altitude jet engine
   - Optimized for hypersonic flight

6. **Mini Jet Mk2** - Enhanced compact jet engine
   - Lightweight air-breathing propulsion

## Prerequisites

### Required
- **Kerbal Space Program** (1.8.x - 1.12.x recommended)
- **Module Manager** 4.2.3 or later
  - Download: [Module Manager Forum Thread](https://forum.kerbalspaceprogram.com/topic/50533-18x-112x-module-manager-423-july-03th-2023-fireworks-season/)

### Recommended
- **Community Category Kit** - For proper engine categorization
  - Download: [Community Category Kit Releases](https://github.com/KSPModdingLibs/KSPCommunityFixes/releases)
- **Filter Extensions** - For organized part filtering in the editor
  - Included with this mod for convenience

## Installation

### Automatic Installation
1. Download the latest release from the [Releases](https://github.com/S1xinch/KSP-OPEnginesMod/releases) page
2. Extract the downloaded ZIP file
3. Copy the `GameData` folder contents into your KSP `GameData` directory
4. If prompted by Module Manager, select your preferred configuration

### Manual Installation
1. Clone this repository or download as ZIP
2. Navigate to the `GameData` folder
3. Copy the following to your KSP's `GameData` directory:
   - `OPEnginesMod/` (contains all engine definitions)
   - `000_FilterExtensions_Configs/` (optional, for filter support)
   - `000_FilterExtensions/` (optional, for icon support)

### File Structure
```
KSP GameData/
├── OPEnginesMod/
│   ├── Parts/
│   │   └── Engines/           (Engine part definitions)
│   └── Patches/               (Optional compatibility patches)
├── 000_FilterExtensions/      (Optional)
└── 000_FilterExtensions_Configs/ (Optional)
```

## Usage

### In the Editor
1. Open the Vehicle Assembly Building or Space Plane Hangar
2. Search for engine parts by name (e.g., "RAPIER Mk2.5")
3. Engines appear in the "Engines" category
4. Place and configure as you would any stock engine

### Engine Specifications
Each engine features:
- Multi-mode configurations (where applicable)
- Full gimbal control (except ion engines)
- Optimized thrust curves
- Balanced heat production
- Proper atmospheric and velocity scaling

### Configuration Tips
- The RAPIER Mk2.5 is excellent for SSTO (Single Stage To Orbit) designs
- Jet engines perform best at high speeds and lower altitudes
- Ion engines are ideal for low-thrust, long-duration missions
- All engines are designed for sandbox mode gameplay

## Configuration Files

### Engine Configs
Located in `GameData/OPEnginesMod/Parts/Engines/`:
- Each engine has its own folder with `.cfg` configuration files
- Do not modify `.mu` (model) or `.dds` (texture) files
- Engine parameters are well-documented with comments

### Patch Files
Located in `GameData/OPEnginesMod/Patches/`:
- `CommunityCategoryKit.cfg` - CCK integration
- `FilterExtensions.cfg` - Filter Extensions integration

## Compatibility

### Known Compatible Mods
- **Module Manager** (required)
- **Community Category Kit** (optional)
- **Filter Extensions** (optional)
- Most other mods that don't modify engine behavior

### Not Compatible With
- Other engine-modifying mods may cause conflicts
- Some career/difficulty mods may find these engines too powerful

## Troubleshooting

### Engines Not Appearing
- Verify Module Manager is installed and active
- Check that all files were extracted to the correct location
- Look for errors in KSP's output log

### Engine Gimbal Issues
- Ensure the engine part isn't mounted upside-down
- Check that gimbal range is within acceptable limits

### Performance Issues
- Disable Filter Extensions icons if experiencing lag
- Reduce particle effects in game settings

### Getting Help
1. Check the [Issues](https://github.com/S1xinch/KSP-OPEnginesMod/issues) page
2. Provide your KSP version and mod list
3. Include relevant excerpts from `KSP.log`

## Development

### For Modders
This mod uses standard KSP part configuration files (`.cfg`). To create additional variants:

1. Create a new folder under `Parts/Engines/`
2. Copy an existing engine config and modify parameters
3. Update thrust values, fuel ratios, and ISP curves as needed
4. Test in KSP before committing

### Building From Source
```bash
git clone https://github.com/S1xinch/KSP-OPEnginesMod.git
cd KSP-OPEnginesMod
# Copy GameData folder to your KSP installation
cp -r GameData /path/to/KSP/GameData
```

## Contributing

Contributions are welcome! Please:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/engine-name`)
3. Make your changes and test thoroughly
4. Submit a pull request with a clear description

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

**Note:** This mod uses assets from Kerbal Space Program, which are the intellectual property of Squad and Private Division. This mod is an unofficial modification and is not affiliated with Squad or Private Division.

## Credits

- **Original Creator:** S1xinch
- **Based on:** Kerbal Space Program by Squad
- **Dependencies:** Module Manager community, Community Category Kit contributors

## Support

If you find this mod useful, consider:
- Leaving a review on [CurseForge](https://www.curseforge.com/kerbal)
- Starring the repository
- Reporting bugs and suggesting features on GitHub Issues

## Changelog

See [CHANGELOG.md](CHANGELOG.md) for version history and planned features.

---

**Happy flying!** 🚀

For updates and discussions, visit the [GitHub repository](https://github.com/S1xinch/KSP-OPEnginesMod).

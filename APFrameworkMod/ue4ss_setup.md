# UE4SS Installation Guide

UE4SS is required to run APFramework mods in Palworld.

## Recommended: Okaetsu/RE-UE4SS (experimental-palworld)

This fork includes PalSchema support required for this mod.

1. Download the latest release from [Okaetsu/RE-UE4SS (experimental-palworld)](https://github.com/Okaetsu/RE-UE4SS/releases/tag/experimental-palworld)
2. Extract the contents into your Palworld binaries folder (e.g. `Palworld/Binaries/Win64/`)
3. Launch the game once to generate UE4SS config files
4. Verify `ue4ss.log` appears in the binaries folder

## Manual Installation

If you prefer a different UE4SS version:

1. Download your preferred UE4SS build
2. Place `dwmapi.dll` and the `ue4ss/` folder in `Palworld/Binaries/Win64/`
3. Ensure `UE4SS-settings.ini` is configured correctly

## Troubleshooting

- If mods don't load, check `ue4ss.log` for errors
- PalSchema requires the Okaetsu fork — the standard RE-UE4SS release will not work
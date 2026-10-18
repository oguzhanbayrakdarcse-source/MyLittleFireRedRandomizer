# My Little Randomizer

A simple Python project that randomizes wild Pokémon encounters in Pokémon FireRed (USA v1.0).

## Features
- Randomizes wild Pokémon encounters.
- Supports land, water, Rock Smash, and fishing encounters.
- Preserves Pokémon levels and encounter rates.
- Creates a separate randomized ROM without modifying the original.

## Requirements
- Python 3
- Pokémon FireRed USA v1.0 ROM
- mGBA or another compatible GBA emulator

## How to Use

1. Clone or download this repository.
2. Place your FireRed ROM in the project folder.
3. Open PowerShell in the project folder.
4. Run the randomizer:

   ```powershell
   python encounter_randomizer.py
   ```

   If `python` is not recognized, run the script using the full path to your Python executable.

5. Wait for the randomization to finish.
6. Open `output/FireRed_Randomized.gba` in mGBA.

**Important:** The ROM must match the expected FireRed USA v1.0 version. The script checks the ROM before randomizing encounters.

## Playthrough
- **Starter:** Squirtle
- **Caught:** Girafarig

## Development
Created on Windows using Python and PowerShell as a personal learning and experimentation project. I explored ROM data, inspected encounter tables, debugged scripts, and built the randomizer step by step.

## Disclaimer
Pokémon and related intellectual property belong to their respective owners. This is an unofficial fan project and is not affiliated with Nintendo, Game Freak, or The Pokémon Company.

ROM files are not included in this repository.

## License
MIT License. See `LICENSE` for details.

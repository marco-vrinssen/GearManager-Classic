# GearManager-Classic

**World of Warcraft Classic addon** for saving and quickly switching between gear sets.

## Features

- **Save Gear Sets**: Save your current equipment as a named gear set
- **Quick Equip**: Switch to saved gear sets with a single command
- **Auto-Swap**: Automatically finds items in your bags and equips them
- **Missing Item Detection**: Alerts you if items from a set are not available
- **Combat Protection**: Prevents gear swapping during combat
- **Multiple Sets**: Save unlimited gear sets for different situations

## Commands

### /gearset [name]
Saves your currently equipped gear as a set with the specified name.

**Examples:**
```
/gearset PvP          - Save current gear as "PvP" set
/gearset Raid         - Save current gear as "Raid" set
/gearset Tank         - Save current gear as "Tank" set
```

### /equipset [name]
Equips a previously saved gear set by name.

**Examples:**
```
/equipset PvP         - Equip your PvP gear set
/equipset Raid        - Equip your Raid gear set
/equipset Tank        - Equip your Tank gear set
```

## Usage Tips

- Create different sets for different roles (Tank, DPS, Healer)
- Save PvP and PvE gear sets for quick switching
- Create resistance sets for specific raids or encounters
- Save farming/gathering gear sets
- All items must be in your bags to equip a set

## Supported Slots

The addon manages all equipment slots:
- Head, Neck, Shoulders, Shirt, Chest
- Waist, Legs, Feet, Wrists, Hands
- Rings (both slots)
- Trinkets (both slots)
- Back, Main Hand, Off Hand, Ranged, Tabard

## Installation

1. Download the addon
2. Extract to `World of Warcraft/_classic_/Interface/AddOns/`
3. Restart World of Warcraft or reload UI with `/reload`

## Requirements

- World of Warcraft Classic (Version 1.15.4+)

## Notes

- Gear sets are saved per character
- Cannot swap gear during combat
- Items must be in your bags (not bank) to equip
- Overwriting a set name will replace the old set

## Author

MIYANKO

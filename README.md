# GearManager-Classic

**World of Warcraft Classic addon** for saving and quickly switching between gear sets.

## Features

- **Save Gear Sets**: Save your current equipment as a named gear set (saved per character)
- **Quick Equip**: Switch to saved gear sets with a single command (overwriting a set name replaces the old set)
- **Auto-Swap**: Automatically finds items in your bags and equips them (items must be in bags, not bank)
- **Missing Item Detection**: Alerts you if items from a set are not available
- **Combat Protection**: Prevents gear swapping during combat
- **Multiple Sets**: Save unlimited gear sets for different situations (Tank, DPS, Healer, PvP, PvE, Resistance, Farming/Gathering)

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

## Supported Slots

The addon manages all equipment slots:
- Head, Neck, Shoulders, Shirt, Chest
- Waist, Legs, Feet, Wrists, Hands
- Rings (both slots)
- Trinkets (both slots)
- Back, Main Hand, Off Hand, Ranged, Tabard

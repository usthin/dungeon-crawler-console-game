# dungeon-crawler-console-
# Dungeon Crawler RPG

A console-based dungeon crawler RPG game with multiple systems including map generation, loot, inventory, achievements, and more.

## Features

- **Map Generation**: Generate random dungeons of different sizes and export/import them
- **Loot System**: Random item drops from defeated enemies with scaling based on enemy level
- **Inventory System**: Equip, unequip, and sell items with stat modifications
- **Store System**: Buy and sell items using in-game currency
- **Achievements**: 15+ achievements with different difficulty levels and rewards
- **Experience System**: Level up with exponential progression
- **Player HUD**: Display all important player information
- **Score System**: Track top players with leaderboard

## How to Play

1. Install Python 3.x
2. Clone this repository
3. Run `pip install -r requirements.txt`
4. Run `python main.py`

## Controls

- Use number keys to select menu options
- Follow on-screen prompts for all actions

## Game Systems

### Progression

The game uses an exponential experience system where each level requires more XP than the last. Gain XP by:
- Defeating enemies
- Completing quests
- Discovering new areas

### Combat

Combat is turn-based with simple attack mechanics. Your attack power is compared to the enemy's defense to determine damage.

### Items

Items can be:
- **Weapons**: Increase attack power
- **Armor**: Increase defense
- **Consumables**: Provide temporary or permanent buffs

## Requirements

- Python 3.6+
- No additional libraries required (uses standard library only)

# Nethack backup

This repo holds my current nethack savefile so that I can continue playing after a perma-death. And yes, I know thats save-scumming/cheating :D. The save file will be exported from my nethack playground and reinjected everytime I face a perma-death. So you can expect the stats to increase and gradually get better over time, since I manage the game using git versioning. Here are some of my current game stats:

- **Race**: Lawful dwarvish valkyrie
- **Armor class**: -3
- **Experience Points**: 7
- **Healthpoints**: 80 (100%)
- **Current Level**: Dungeon Level 10
- **Inventory**:
  - **Gold**: 139
  - **Excalibur**
  - **Wand of Striking**
  - **Pick-Axe**
  - **2 Food rations**
  - **1 Pancake**
- **Armory**:
  - **Chain Mail**
  - **Studded Leather Armor**
  - **Pair of Iron Shoes**
  - **Uncursed Orcish Helm**
  - **Dwarvish Cloak**

## How to run?

To backup your current nethack game, assuming you have installed nethack via homebrew, then simply run this bash script.:

```bash
chmod +x ./nethack-backup.sh
./nethack-backup.sh
```

To restore a game after perma-death, you can run this bash script.:

```bash
chmod +x ./nethack-restore.sh
./nethack-restore.sh
```
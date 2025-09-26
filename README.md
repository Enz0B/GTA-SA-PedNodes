# GTA: San Andreas Pedestrian Nodes

This repository contains a dataset of 37,650 pedestrian node coordinates extracted from Grand Theft Auto: San Andreas. These coordinates represent valid pedestrian pathfinding points (x, y, z) used in the game for NPC navigation and movement.
Description
The file ped_nodes.txt includes 37,650 lines, each containing a set of 3D coordinates in the format x,y,z (e.g., 1289.750000,-1609.500000,12.500000). The coordinates are formatted as floating-point numbers with six decimal places, separated by commas.
These nodes were extracted from the game's data files and are intended for use in projects related to GTA: San Andreas, such as game mode development for open.mp or SA-MP servers, NPC pathfinding, or other modding purposes. The coordinates cover various locations across the San Andreas map, including cities like Los Santos, San Fierro, and Las Venturas, as well as rural and interior areas.

# Usage

File Path: Place ped_nodes.txt in the scriptfiles directory of your open.mp or SA-MP server.
Parsing: The coordinates can be parsed using a scripting language like Pawn with the sscanf plugin (e.g., sscanf(line, "p<,>fff", x, y, z)).
Applications: Use these nodes for spawning NPCs, creating checkpoints, generating random pedestrian paths, or analyzing the game's navigation mesh.

# Notes

The coordinates are provided as-is, extracted directly from the game’s pedestrian path data.

# License
This dataset is provided for non-commercial use and is intended for modding or research purposes related to Grand Theft Auto: San Andreas. Please respect the intellectual property of Rockstar Games and use this data responsibly.

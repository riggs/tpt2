# [The Perfect Tower 2](https://games.fs-studios.com/games/perfecttower2) Automation Scripts

`Facility AI` is a feature of the game The Perfect Tower 2, unlocked at Military Tier 4 in the Headquarters.
AI scripts require servers to be purchased and installed in the Headquarters,
with the amount of total RAM across all servers determining the maximum number of lines allowed in a script.

## Mechanics
Each frame of the game engine executes one line of a script. (Most users get ~60 FPS.) A maximum of 100 scripts can be running simultaneously.
Simultaneous scripts are executed sequentially in the order they were launched.
This allows for deterministic 'parallelism' of scripts to maximize actions.

# RectXP

**Rounded, segmented dark XP bar for World of Warcraft: Forever (Interface 16001).**

Created by **Schrubber**. Supports German and English clients.

## Version 1.1.1

- Subtly rounded rectangle, adjustable corner radius (1–10)
- 20 segments and centered XP percentage
- Adjustable width, height, opacity and colors
- Drag-to-move and optional hiding of Blizzard's XP bar
- Designed to fit dark Bartender UI layouts

## Installation

Download [RectXP v1.1.1](releases/RectXP-1.1.1.zip) and extract the `RectXP` folder into your WoW client's `Interface/AddOns` directory. Enter `/reload` in-game.

## Commands

- `/rxp` — configuration
- `/rxp unlock` / `/rxp lock` — move / lock
- `/rxp width 800` and `/rxp height 26` — size
- `/rxp alpha 80` — opacity
- `/rxp radius 4` — corner rounding
- `/rxp preview on` — 45% preview

See [full usage notes](RectXP/README.txt).

## Status

Lua and archive structure were checked outside the game; in-game behavior should be tested in WoW Forever. The original media textures are bundled in the install ZIP. GitHub Actions builds an updated ZIP from source and media.

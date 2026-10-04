# Trigger Point

## Overview

**Trigger Point** is a 2D side-scrolling action shooter built with **Python and Pygame**.

The player moves through platform-based levels, fights enemy units, collects resources, and reaches the end of each level. The project uses pixel-art graphics, animated characters, sound effects, and CSV-based level layouts.

## Features

- 2D side-scrolling platform gameplay
- Player movement, jumping, shooting, and grenades
- Animated player and enemy characters
- Multiple playable levels
- Health, ammunition, and grenade indicators
- Enemy AI and combat
- Pickups and interactive level elements
- Custom cyberpunk-inspired visual theme
- Custom **Trigger Point** main menu
- Futuristic city background and high-contrast terrain

## Requirements

- Python 3.x
- Pygame

Install Pygame with:

```bash
pip install pygame
```

## How to Run

1. Extract the project folder.
2. Open a terminal in the project directory.
3. Run:

```bash
python main.py
```

Keep the `img` and `audio` folders in the same directory as `main.py`. The game loads its graphics and sound files from these folders.

## Controls

| Action | Key |
|---|---|
| Move left | `A` / `Left Arrow` |
| Move right | `D` / `Right Arrow` |
| Jump | `W` / `Up Arrow` |
| Shoot | `Space` |
| Throw grenade | `Q` / `G` |
| Exit game | `Esc` |

## Project Structure

```text
Trigger Point/
├── main.py              # Main game program
├── button.py             # Menu button handling
├── level-editor.py       # Level editing utility
├── level1_data.csv       # Level 1 layout
├── level2_data.csv       # Level 2 layout
├── level3_data.csv       # Level 3 layout
├── img/                  # Images, sprites, tiles and UI assets
├── audio/                # Music and sound effects
├── README.md             # Project documentation
└── LICENSE               # Project license
```

## Credits and Asset Licenses

This project uses or is based on publicly available game-development assets. Asset creators and source pages are credited below:

1. Pixel Platformer — Eray Zesen: https://erayzesen.itch.io/pixel-platformer
2. Team Wars Platformer Battle — Secret Hideout: https://secrethideout.itch.io/team-wars-platformer-battle
3. Soundimage — audio resources: https://soundimage.org/fantasywonder
4. Free Game Sprites: Explosion 3 — Gushh: https://gushh.net/blog/free-game-sprites-explosion-3
5. Grenades 16x16 — MTK: https://mtk.itch.io/grenades-16x16

Please retain the applicable attribution and licensing terms for third-party assets when redistributing the project.

## Project Note

**Trigger Point** is a modified and customized version of a Python/Pygame shooter project. The current version includes changes to the game's title, player and enemy visuals, background environment, terrain appearance, menu presentation, and visual contrast.


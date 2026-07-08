# The Pintland Isles: The Rotted Soul's Labyrinth

A tiny retro isometric dungeon crawler set in the world of the Pintland Isles,
based on the **Master Lore Compendium** of the Liquor Kings.

Sealed for millennia beneath the catacombs of the Hoegaarden Library lies the
prison-labyrinth of the Rotted Soul — the VeilRunner king of old Lagendale,
buried in the River Coffin and guarded by the souls of 800 betrayed workers.
The Guardian's spell is unraveling. Someone has to go down there.
Naturally, the Liquor Kings drew straws.

## Play

Open `index.html` in any modern browser. That's it — the whole game is a
single self-contained file with no dependencies, no build step, and no
network access required.

## How it works

- **Choose your Liquor King** — all six are playable, each with a small perk:
  - **Seamus Bonehardy** — balanced stats
  - **Jack Anqoak** — lost his soul down here once; sees far in the dark
  - **Jagerbauhm** — fast on his feet
  - **Guinnie O'Guinness** — hits like Wagwan's Whopper (high damage)
  - **Buke** — bones grown strong on vitamin alcohol (very tough, a bit slow)
  - **Jameson Pilsner** — dies constantly; the ale brings him back, once
- **Descend three floors**: the Lagendale Catacombs, the River Coffin, and
  the Sepulcher of the Rotten King — where the Rotted Soul himself waits.
- Fight **Soulless Husks** and **Rot Wisps**, avoid the spreading **rot
  pools**, drink **tankards of ale** to heal, pocket gold, and recover lost
  **tomes of Lagendale** (real excerpts from the labyrinth books in the lore
  compendium).

## Controls

| Key | Action |
| --- | --- |
| WASD / Arrow keys | Move |
| Space / J / Click | Attack |
| M | Mute |

## Tech

Vanilla JavaScript on a single 480×300 canvas, upscaled with pixelated
rendering. Procedurally generated mazes (recursive backtracker), painter's
algorithm isometric renderer, code-drawn pixel sprites, and WebAudio bleeps.
No assets, no libraries.

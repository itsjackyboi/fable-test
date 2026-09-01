# The Pintland Isles: The Rotted Soul's Labyrinth

A retro isometric dungeon crawler set in the world of the Pintland Isles,
based on the **Master Lore Compendium** of the Liquor Kings.

Sealed for millennia beneath the catacombs of the Hoegaarden Library lies the
prison-labyrinth of the Rotted Soul — the VeilRunner king of old Lagendale,
buried in the River Coffin and guarded by the souls of 800 betrayed workers.
The Guardian's spell is unraveling. Someone has to go down there.
Naturally, the Liquor Kings drew straws.

## Play

Open `index.html` in any modern browser — desktop or phone. The whole game is
a single self-contained file: no dependencies, no build step, no network.

## The run

Enter your name, choose your Liquor King, and race the clock through three
depths. Your fastest completion is recorded in the **Hall of the Liquor
Kings** — its own tab on the title screen (stored in your browser; one entry
per name, best time only).

Come home in **under a minute** and the tavern issues you a coupon compelling
a randomly chosen Liquor King to shotgun a beer on camera at the next happy
hour. Die instead, and there is a small chance the thing that killed you gets
the last word.

- **Depth I — The Lagendale Catacombs.** Purple stone, Soulless Husks and
  Rot Wisps. A Shrine Helm is hidden in a dead end.
- **Depth II — The River Coffin.** Blood-rust halls patrolled by the
  Betrayed, spear-throwing ghosts of the 800. **The Guardian of Lagendale**
  stands over the sealed stairs — the descent doesn't open until he falls.
- **Depth III — The Sepulcher of the Rotten King.** A near-black horror maze
  crawling with the Skinless of the 138, ending in the arena of **the Rotted
  Soul** himself.

## The Liquor Kings

| King | Style |
| --- | --- |
| Seamus Bonehardy | Balanced; gold pickups worth +50% |
| Jack Anqoak | Fragile oracle: far sight, senses the way down |
| Jagerbauhm | Glass cannon: very fast, quick weak swings |
| Guinnie O'Guinness | Heavy hitter: slow crushing blows, huge knockback |
| Buke | The tank: 20 HP, slow, ale heals extra |
| Jameson Pilsner | Ale heals double and he revives twice |

## Wagwan's Stank Tank

Between depths you surface into **Wagwan's Stank Tank**, where Wagwan himself
lays six items on the counter. Which items appear is luck; the prices never
move — **common 10g, rare 22g, epic 38g, legendary 60g**. There is always at
least one common on the counter, so you can afford something on your first
visit. The stall is restocked from scratch every visit and every run — nothing
stays sold out, and a Pint bought on Depth I can be bought again on Depth II. Legendaries are a windfall you'll rarely see: the Glyph of Purity made
whole, Jagerbauhm's Nether Key, the Gilded Tankard, Sackbeard's Black Flag, or
the Crown of the Rotted Soul.

**The run timer stops while you shop**, so browsing never costs you a record.

## Relics & rewards

Lore relics from the Compendium also spawn in the maze: **Wagwan's Whopper**,
**Nike Dunks**, **Sackbeard's Armor**, the **Hazmat Suit**, the **Light of
the Oracle**, the **Hollow Urn**, the **Fortunate Scarab**, and the
**Blicky** (8 bullets, no refills).

- Collect **all the books** on a depth for a Fragment of the Glyph of Purity
  (+2 max HP); complete all three for the full Glyph.
- Drink **all the ale** on a depth for the **DRUNKEN STUPOR** — six seconds
  untouchable and unstoppable.
- Drinking at full health builds the **drunk meter**: harder swings,
  wobblier legs.
- Four **Shrine armor pieces** are scattered across the run; the full set
  keeps the Shrines' promise.
- **Cumsock**, the Kings' beloved goat, is caged deep in the Sepulcher. Free
  him and he'll trot at your side, headbutting lesser horrors away (no
  damage — he's a lover, not a fighter). He wants no part of the Rotted Soul.

## Controls

| Input | Action |
| --- | --- |
| WASD / Arrow keys | Move |
| Space / J / Click | Attack |
| **P** | **Start a run, and leave the win/death screen** |
| K | Fire the Blicky (if found) |
| L | Turn the Nether Key (if bought) |
| 1–6 / click | Buy in the Stank Tank |
| B | Buy the highlighted slot |
| Enter | Confirm your name; depart the Stank Tank |
| Tab | Switch between DESCEND and RECORDS |
| M | Mute everything |
| N | Music on/off (keeps sound effects) |
| Touch devices | Virtual joystick (left) + ATK/GUN buttons (right) |

Starting and ending a run is deliberately **not** bound to space or click —
those are attack inputs, and spamming them shouldn't throw you into a fresh
run the moment you die. On phones the same job is done by the on-screen
**DESCEND** and **MAIN MENU** buttons, which only respond to taps inside them.

## Music

The soundtrack is an original 8-bit dirge written for this game — D minor,
four bars walking down Dm–Bb–F–A — synthesised live from oscillators rather
than played from a file. It shifts with the descent: slower and sparser on the
title screen, warmer in the Stank Tank, a whole step down in the River Coffin,
and faster and five semitones lower under a sawtooth drone in the Sepulcher.
It cuts out entirely when you die. No samples, nothing to license.

## Tech

Vanilla JavaScript on a single 480×300 canvas, upscaled with pixelated
rendering. Procedurally generated mazes (recursive backtracker), painter's
algorithm isometric renderer with cutaway walls, code-drawn pixel sprites,
per-depth palettes, a WebAudio chiptune engine and sound effects, localStorage
leaderboard. No assets, no libraries.

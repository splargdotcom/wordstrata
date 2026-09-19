# WordStrata

A browser word game about **excavation, gravity and increasingly valuable layers of language**.

Build and submit words to clear material, let the remaining tiles fall, and dig through progressively deeper strata. The surface is only the beginning: reach **Depth 50** to discover the Progenitor, then continue into the endless layers beyond.

**Play on itch.io:** https://splarg.itch.io/wordstrata

## Core ideas

- Form words from letter tiles to excavate the board
- Gravity collapses material into newly opened spaces
- Darker strata award **2× and 3×** score multipliers
- Bomb tiles clear a **3×3** crater
- Words of **8+ letters** trigger a Strata Collapse and refill cleared material
- Blind submissions can build streak multipliers
- Mining-themed words receive special bonuses
- Supply drops provide fresh tiles when stuck
- Discoveries, lifetime statistics and achievements are recorded locally

## Modes

### Normal

The main excavation run: descend through the strata, reach Depth 50 and continue digging beyond the Progenitor.

### Challenge

Enter a seed code to generate a fixed board. Players using the same code receive the same starting tile arrangement.

### Survival

Oxygen depletes continuously. Submitting words restores air, turning word finding into a time-pressure survival mode.

## Run locally

The release is a static browser package. Keep the supplied files together and open `index.html`, or serve the directory with a simple local web server:

```bash
python3 -m http.server 8000
```

There is no build step for normal play. The repository includes its bundled dictionary, local Phaser runtime, logo and icon assets.

## Source status

This repository preserves the current WordStrata itch.io release package supplied by the publisher. Release-package quirks in the initial import are intentionally retained so later fixes can be recorded as separate commits.

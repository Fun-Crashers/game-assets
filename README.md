# Funcrashers — Game Assets

Official marketing and integration assets for Funcrashers games.
This repository contains the official **icon** and **banner** of each game,
ready to be used by authorized partners in their platforms and promotional channels.

## Games

| Folder | Game | Genre |
|---|---|---|
| [`abducted`](./abducted)             | Abducted        | Crash |
| [`champion-goal`](./champion-goal)   | Champion Goal   | Football |
| [`chordmaster`](./chordmaster)       | Chordmaster     | Music / Rhythm |
| [`goal-spin`](./goal-spin)           | Goal Spin       | Slot — Football (Classic) |
| [`quantum-goal`](./quantum-goal)     | Quantum Goal    | Slot — Football (Futuristic) |
| [`vintage-kick`](./vintage-kick)     | Vintage Kick    | Slot — Football (Vintage) |
| [`world-cup-rush`](./world-cup-rush) | World Cup Rush  | Slot — Football (World Cup) |

## Folder layout

Each game folder contains exactly two files:

```
<game-slug>/
├── <game-slug>-icon.png     # square icon (lobby tile, app stores, thumbnails)
└── <game-slug>-banner.png   # promotional banner (hero, marketing)
```

Example:

```
champion-goal/
├── champion-goal-icon.png
└── champion-goal-banner.png
```

## Naming conventions

- All filenames in **lowercase**, `kebab-case`, no spaces or accents.
- Each file is prefixed with the **game slug** so it stays identifiable
  even when downloaded loose.
- Format: **PNG** with transparency where applicable.

## For partners

Authorized partners may use these assets in their platform integrations
and marketing materials following the partnership agreement.

- Do **not** modify logos, icons or brand elements beyond size/format
  adjustments required for technical integration.
- Do **not** redistribute these assets outside the scope of an authorized
  integration with Funcrashers.

For partnership inquiries or asset requests, contact the Funcrashers team.

## Adding a new game

1. Create a new folder named with the game slug (lowercase, kebab-case):
   `<new-game-slug>/`
2. Add the two files:
   - `<new-game-slug>-icon.png`
   - `<new-game-slug>-banner.png`
3. Add the new row to the **Games** table above.
4. Open a pull request.

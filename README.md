# FunCrashers — Game Assets

Official marketing and integration assets for FunCrashers games.
This repository contains the official **icon** and **banner** of each game,
ready to be used by authorized partners in their platforms and promotional channels.

## Games

| Folder | Game | Genre |
|---|---|---|
| [`abducted`](./abducted)             | Abducted        | Crash |
| [`champion-goal`](./champion-goal)   | Champion Goal   | Football |
| [`chordmaster`](./chordmaster)       | Chordmaster     | Music / Rhythm |
| [`dark-jester`](./dark-jester)       | Dark Jester     | Slot — Jester (Dark) |
| [`dice-jester`](./dice-jester)       | Dice Jester     | Slot — Jester (Dice) |
| [`fortune-alchemist`](./fortune-alchemist) | Fortune Alchemist | Slot — Fantasy (Alchemy) |
| [`goal-spin`](./goal-spin)           | Goal Spin       | Slot — Football (Classic) |
| [`jester-gems`](./jester-gems)       | Jester Gems     | Slot — Jester (Gems) |
| [`quantum-goal`](./quantum-goal)     | Quantum Goal    | Slot — Football (Futuristic) |
| [`race-rush`](./race-rush)           | Race Rush       | Slot — Racing |
| [`vintage-kick`](./vintage-kick)     | Vintage Kick    | Slot — Football (Vintage) |
| [`world-cup-rush`](./world-cup-rush) | World Cup Rush  | Slot — Football (World Cup) |

## Folder layout

Each game folder contains the **icon** and the **banner**, each in up to three formats:

```
<game-slug>/
├── <game-slug>-icon.png      # square icon (lobby tile, app stores, thumbnails) — master
├── <game-slug>-icon.webp     # same icon, lightweight version for the web
├── <game-slug>-icon.svg      # vector source (when available)
├── <game-slug>-banner.png    # promotional banner (hero, marketing) — master
├── <game-slug>-banner.webp   # same banner, lightweight version for the web
└── <game-slug>-banner.svg    # vector source (when available)
```

Example:

```
champion-goal/
├── champion-goal-icon.png
├── champion-goal-icon.webp
├── champion-goal-icon.svg
├── champion-goal-banner.png
└── champion-goal-banner.webp
```

The FunCrashers brand logos live in [`LogoFunCrashers`](./LogoFunCrashers)
(icon, horizontal, square and wordmark; black, white and transparent), also in PNG + WebP.

## Naming conventions

- All filenames in **lowercase**, `kebab-case`, no spaces or accents.
- Each file is prefixed with the **game slug** so it stays identifiable
  even when downloaded loose.
- Formats:
  - **PNG** — master file, full quality, with transparency where applicable.
  - **WebP** — same image and dimensions as the PNG, lighter. Preferred for websites and lobbies.
  - **SVG** — vector source, when available.

## For partners

Authorized partners may use these assets in their platform integrations
and marketing materials following the partnership agreement.

- Do **not** modify logos, icons or brand elements beyond size/format
  adjustments required for technical integration.
- Do **not** redistribute these assets outside the scope of an authorized
  integration with FunCrashers.

For partnership inquiries or asset requests, contact the FunCrashers team.

## Adding a new game

1. Create a new folder named with the game slug (lowercase, kebab-case):
   `<new-game-slug>/`
2. Add the files:
   - `<new-game-slug>-icon.png` and `<new-game-slug>-banner.png`
   - `<new-game-slug>-icon.webp` and `<new-game-slug>-banner.webp`
   - the `.svg` sources, if any
3. Add the new row to the **Games** table above.
4. Open a pull request.

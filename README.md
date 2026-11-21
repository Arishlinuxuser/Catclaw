# CATCLAW

**Nine Lives. One Last Stand.**

CATCLAW is a browser-based 2D action platformer. Play as a cat, fight through enemy-filled stages, dodge incoming projectiles, and try to complete all six levels as quickly as possible.

## Play online

**Play CATCLAW:** https://arishlinuxuser.github.io/Catclaw/

The game runs directly in a modern browser. No installation, account, build tools, or backend are required.

> The public game page becomes available after GitHub Pages is enabled for this repository under **Settings → Pages**.

## Controls

### Keyboard

| Key | Action |
| --- | --- |
| `A` / `D` or `←` / `→` | Move left / right |
| `W` / `↑` | Jump (double-jump is supported) |
| `Space` | Claw attack |
| `S` / `↓` | Dodge roll |
| `E` | Meow wave — briefly stuns nearby enemies |

Touch controls are included for supported mobile screens.

## Features

- Six handcrafted platforming levels.
- Normal and Punishing difficulty modes.
- Movement, jumping, double-jumping, claw attacks, dodge rolls, and a meow stun ability.
- Enemies that patrol, detect the player, and fire projectiles.
- Health, elapsed time, level, death-count, and best-time HUD.
- Quick die-and-retry flow.
- Synthesized sound effects with a mute control.
- Responsive canvas and on-screen touch controls.
- Best completion times saved locally in the player's browser using `localStorage`.

## Technology

- HTML5 for page structure.
- CSS3 for menus, HUD, and responsive layout.
- Vanilla JavaScript for game state, input, physics, collisions, enemy behaviour, and audio.
- HTML Canvas 2D API for rendering.
- Web Audio API for synthesized sound effects.
- `localStorage` for personal best-time records.

This is a client-side game. It does not currently include player accounts, online multiplayer, a server-side leaderboard, or cloud-synced scores. Personal best times stay in the browser and device where each player plays.

## Run locally

1. Clone or download this repository.
2. Open `index.html` in a modern browser.

No package installation or build step is required.

## Deploy with GitHub Pages

1. Open this repository's **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**.
4. Click **Save**.
5. Wait for GitHub Pages to finish publishing, then open the URL above.

The entry file must remain named `index.html` in the repository root.

## Project structure

```text
Catclaw/
├── index.html
└── README.md
```

## Project status

A playable prototype built for an AI-assisted game-development event. The project is intentionally lightweight and can be extended with more stages, enemy types, abilities, and online features later.

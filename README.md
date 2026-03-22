# Tank Arena

A browser-based tank battle game built with vanilla HTML5 Canvas. No frameworks, no dependencies — just a single HTML file.

**[▶ Play now](https://economist1895.github.io/tanks/)**

---

## Features

- **1 Player** — Face off against a CPU opponent with three difficulty levels: Easy, Normal, and Hard
- **2 Players** — Local multiplayer on the same device (keyboard or touch)
- **Power-ups** — Heal, Invincibility Shield, and Rapid Fire spawn periodically around the arena
- **Mobile support** — On-screen D-pad and fire button for touchscreen play
- **Particle effects & animated tanks** — Fully rendered with the Canvas 2D API

---

## How to Play

Destroy the enemy tank before they destroy yours. Each tank starts with 100 HP. Bullets deal 20 damage on hit. Collect power-ups by moving into them or shooting them.

### Controls

|  | Player 1 | Player 2 |
|---|---|---|
| **Move** | `W A S D` | `↑ ← ↓ →` |
| **Shoot** | `Space` | `Enter` |

On mobile, use the on-screen D-pad and **FIRE** button. In 2-player mode, each player gets their own set of controls on opposite sides of the screen.

### Power-ups

| Icon | Name | Effect |
|---|---|---|
| `+` | Heal | Restores 30 HP |
| `★` | Invincibility | No damage taken for 5 seconds |
| `»` | Rapid Fire | Greatly increased fire rate for 8 seconds |

---

## Tech Stack

- Vanilla HTML, CSS, and JavaScript — no build step, no dependencies
- HTML5 Canvas (2D API) for all rendering
- [Orbitron & Rajdhani](https://fonts.google.com/) fonts via Google Fonts
- Deployed via GitHub Pages

---

## Running Locally

Just open `index.html` in any modern browser — no server required.

```bash
git clone https://github.com/economist1895/tanks.git
cd tanks
open index.html
```

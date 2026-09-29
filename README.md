# 🐟 Feeding Frenzy

A juicy single-file HTML5 arcade game — swim through the ocean, eat fish smaller than you to grow, and avoid the ones that bite back!

## How to Play

- **Drag the joystick** (bottom right) or use **arrow keys** to swim
- Eat fish **smaller** than you to grow bigger and level up through stages: Minnow → Goldfish → Snapper → Barracuda → **Shark**
- Avoid fish **bigger** than you — they bite! You have 3 lives (❤️)
- Grab bonus bubbles for power-ups:
  - ⚡ **Speed Boost** — swim much faster
  - 🛡️ **Shield** — survive one bite
  - 🧲 **Magnet** — attract smaller fish toward you
  - 💥 **Frenzy** — eat everything, even predators!
  - ❤️ **Extra Life** — gain one more heart
- Golden fish are worth **5x** points — chase them!

## Features

- Underwater world with light rays, seaweed, plankton, and rising bubbles
- Predator fish home in on you — danger ring warns you off bigger fish
- Stage growth bar with fanfare when you grow up
- Juicy juice: screen shake, particles, floating score text, and synthesized underwater sounds via Web Audio API
- Persistent best score (localStorage)

## Controls

| Input | Action |
|---|---|
| Drag joystick / Arrow keys | Swim |
| — | No buttons — pure movement |

## Run It

Just open `index.html` in any modern browser — no build step, no dependencies, no server required. Works with mouse, touch, and keyboard.

## Tech

- Single HTML file, vanilla JavaScript + Canvas 2D
- Web Audio API for all sound effects

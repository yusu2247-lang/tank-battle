# Tank Battle

A single-file HTML5 canvas tank battle game. No dependencies, no build step — just open `index.html` in a browser.

![Genre](https://img.shields.io/badge/genre-arena%20shooter-orange) ![Engine](https://img.shields.io/badge/engine-vanilla%20JS%20%2B%20canvas-brightgreen) ![Dependencies](https://img.shields.io/badge/dependencies-none-blue)

## Play

Open `index.html` directly, or serve the folder (recommended so audio autoplay policies stay happy):

```bash
npx serve .        # or: python -m http.server
```

## Controls

| Input | Action |
|---|---|
| `W A S D` / arrows | Drive / steer |
| Mouse | Aim turret |
| Left click / `Space` | Fire |
| `P` | Pause |
| `M` | Mute |

## Gameplay

- Survive endless waves of AI enemy tanks that flank, keep their distance, lead their shots, and hunt you with line-of-sight checks.
- Bullets destroy wooden crates; crates sometimes drop repair kits (+30 hull).
- Enemy count, hull, speed, and accuracy scale with the wave number.
- Score: 100 + 25 × wave per kill.

## Features

- Camera-follow viewport over a 1920×1080 arena with minimap
- Destructible cover, particles, screen shake, fading tank tracks
- Procedural WebAudio sound effects (no audio files)
- Zero dependencies — everything is in `index.html`

## License

MIT

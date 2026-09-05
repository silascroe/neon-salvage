# Neon Salvage

A self-contained browser-based Three.js hovercraft game. Recover five energy cores from Blacksite 07, then return to the extraction beacon before the clock or your hull integrity runs out.

## Run locally

```bash
npm install
npm run dev
```

Open the local URL Vite prints. The game is client-side only and uses procedural geometry, lighting, particles, bloom, and Web Audio—no proprietary assets required.

## Controls

- `WASD` — thrust and strafe
- `SPACE` — vertical boost / air dash
- `SHIFT` — magnetic beam pull toward the nearest nearby core
- `ESC` — pause or resume

Collect cores for score, stay above the void, evade the patrol drones, and return to the amber extraction ring to win.


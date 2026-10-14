# Tower Building Game 🏗️

A complete, high-fidelity clone of the [Riseup Labs Tower Building Game](https://riseuplabs.com/play/tower-building/).

## Overview
- **Game Engine**: HTML5 Canvas with custom physics, swinging crane hook, and dynamic building stack mechanics.
- **Visuals**: Full original asset pack including cloud animations, flight layers, swing physics, and particle/landing effects.
- **Audio**: Original background music (`bgm.mp3`), drop sound effects (`drop.mp3`, `drop-perfect.mp3`), game over tune (`game-over.mp3`), and rotation effects.
- **Controls**:
  - **Click / Tap**: Drop tower block
  - **Spacebar**: Drop tower block (Desktop support)
  - **Sound Toggle**: In-game mute / unmute button in top HUD
  - **High Score**: Persists in `localStorage` across sessions
  - **Responsive**: Auto-scales on desktop and mobile portrait mode

## Running Locally

### Option 1: Python HTTP Server (Zero Dependencies)
```bash
python -m http.server 3000
```
Open [http://localhost:3000](http://localhost:3000) in your browser.

### Option 2: Node.js
```bash
npm start
```
or
```bash
npx serve . -l 3000
```

## Ditto MCP Clone Job
- Initiated job via Ditto MCP: `52c97be8-0ca8-440a-8581-6881e5a6945b`
- Remote URL: `https://riseuplabs.com/play/tower-building/`

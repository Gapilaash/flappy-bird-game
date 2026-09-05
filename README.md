# Flappy Champ 🐤

A polished, browser-based Flappy Bird clone built entirely with **HTML5 Canvas** and **vanilla JavaScript** — no external libraries or frameworks used. Tap, click, or press Space to flap and dodge the pipes for as long as you can!

## 🎮 Live Demo

🔗 [https://gapilaash.github.io/flappy-bird-game/](https://gapilaash.github.io/flappy-bird-game/)

## Features

- 🎨 Smooth canvas-based rendering with animated wing flaps and rotation physics
- 🔊 Procedurally generated sound effects (flap, score, hit, swoosh) using the Web Audio API — no audio files needed
- 🔇 Mute/unmute toggle button
- ☁️ Animated scrolling background with clouds and ground
- 🏆 Best score saved locally using `localStorage` — persists even after closing the browser
- 📱 Fully responsive — playable on both desktop (keyboard/mouse) and mobile (touch)
- 🚫 Zero dependencies — single self-contained HTML file

## How to Play

1. Open the [live demo link](https://gapilaash.github.io/flappy-bird-game/) in your browser.
2. Press **Space**, **click**, or **tap** the screen to make the bird flap upward.
3. Avoid hitting the pipes, the ground, or the top of the screen.
4. Each pipe you pass adds to your score — try to beat your best score!

## Tech Stack

- **HTML5 Canvas** — Game rendering
- **CSS3** — UI styling, gradients, and responsive layout
- **JavaScript (Vanilla)** — Game loop, physics, collision detection
- **Web Audio API** — Real-time sound effect generation
- **localStorage** — Persisting the player's best score

## Run Locally

1. Clone this repository:
```
git clone https://github.com/gapilaash/flappy-bird-game.git
```

2. Navigate into the project folder:
```
cd flappy-bird-game
```

3. Open `index.html` directly in your browser — no server or build step required.

## Deployment

This project is deployed for free using **GitHub Pages**. Since it's a single static HTML file, any changes pushed to the main branch will automatically reflect on the live site after a few minutes.

## License

This project is open source and free to use for learning purposes.

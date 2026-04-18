# 👾 Pixel Monster Meme

A single-file HTML meme featuring a bouncing purple pixel monster with chiptune music.

🔴 **Live demo:** [singhgurman8011.github.io/Meme](https://singhgurman8011.github.io/Meme)

---

## What is this?

A self-contained `index.html` file you can open in any browser. No dependencies, no build step, no server — just open and enjoy.

## Features

- **Purple Space Invaders-style pixel monster** with two animation frames (legs flap as it moves)
- **Bounces off all four walls** like a DVD screensaver
- **Pixel grid background** — the whole screen is made of tiny black squares
- **Chiptune background music** — looping 8-bit melody + bass line via the Web Audio API
- **"YOU HAVE BEEN MEMED"** — classic Impact font pinned at the bottom
- Zero dependencies — pure HTML, CSS, and vanilla JavaScript

## Run locally

```bash
# Just open the file — no server needed
start index.html
```

Music starts automatically. If the browser blocks autoplay, click anywhere on the page.

## Deploy (GitHub Pages)

This repo is ready for GitHub Pages out of the box:

1. Go to **Settings → Pages** in this repo
2. Under **Source**, select **Deploy from a branch**
3. Choose **main** branch, **/ (root)** folder
4. Click **Save**

Your live URL will be: `https://singhgurman8011.github.io/Meme`

## Built with

- HTML5 Canvas
- Web Audio API (chiptune synth)
- Vanilla JavaScript — no frameworks, no dependencies

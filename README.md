# Saga Runes

A mobile-first rune tracing mini-game inspired by Norse folklore.

## Current Prototype

This repo currently contains a single-file browser prototype:

- `index.html`

## What It Does

- Mobile-first layout
- 24 Elder Futhark-inspired runes
- Finger tracing on a touchscreen
- Basic accuracy scoring
- Linear Saga Mode progression
- Practice Mode with all runes available
- Saga Thread screen for unlocked story fragments
- Local save using browser `localStorage`
- No backend
- No login
- No ads
- No pay-to-play mechanics

## Core Loop

1. Learn the rune.
2. Trace the rune with your finger.
3. Cast it after reaching the pass score.
4. Reveal the next Norse folklore-inspired saga fragment.
5. Graduate to the next rune.

## GitHub Pages Setup

To publish this as a phone-accessible web app:

1. Open this repository on GitHub.
2. Go to **Settings**.
3. Go to **Pages**.
4. Under **Build and deployment**, set:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ root**
5. Save.

After GitHub finishes deploying, the site should be available at:

```text
https://belleprofreelance-droid.github.io/saga-runes/
```

## Design Note

This is a fantasy education game inspired by runic tradition, Norse mythology, and saga literature. It should not claim to represent exact historical ritual practice.

## Next Build Targets

- Improve stroke-order detection
- Add better cast animations
- Add sound effects
- Add screen transitions
- Add a reset-progress button
- Refine saga writing and mythology sourcing
- Make the app installable as a PWA

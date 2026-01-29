# Chord-Tree

Chord Tree is an interactive chord-progression and voicing exploration tool (with center-anchored voicings, playback, and MIDI out support).

## Features
- Center note “anchor” for voicings (click the keyboard)
- Chord suggestions with functional tags (diatonic / secondary / borrowed / tritone, etc.)
- Playback with BPM + interval controls
- Strum mode
- MIDI out routing (WebMIDI) + optional internal audio engine
- Voicing controls (Bass Drop, Inversions, Spread)

## Quick Start
This project is a static web app.

### Option A: Just open it
Open `index.html` in a modern browser.

### Option B: Run a local server (recommended)
Any static server works.

Example (Python):
```bash
python -m http.server 8080

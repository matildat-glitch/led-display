# LED Display Editor

A lightweight 4-digit 7-segment LED animation editor built with plain HTML/CSS/JS.

## Features

- Click each segment to toggle on/off.
- Save the current display as a frame with custom duration.
- Timeline preview with play, pause, stop, and loop playback.
- Overlay `full_display.svg` in editor mode for visual alignment.
- Adjustable digit size, spacing, anchor, and offsets via CSS variables.

## Run Locally

Open `index.html` directly in a browser.

## Main CSS Variables

Defined in `:root` inside `index.html`:

- `--panel-bg-width`: panel background width.
- `--digits-gap`: base spacing between digits.
- `--digits-overlap`: extra negative overlap between adjacent digits.
- `--digits-edge-offset`: distance from left/right anchor edge.
- `--digits-shift-x`, `--digits-shift-y`: whole 4-digit row offset.

## Git Workflow

```bash
git add .
git commit -m "Update LED layout"
git push
```

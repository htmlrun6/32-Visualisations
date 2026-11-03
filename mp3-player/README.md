# 64 Visualisations

A lightweight, original music visualiser player that runs entirely in the browser. No build step, no dependencies.

## Features
- Select or drag & drop **MP3 files only** (other formats, including MP4, are rejected)
- 64 real-time visualisations (16 styles x 4 colour palettes), powered by the Web Audio API
- Playlist, seek, volume, auto-cycle mode, fullscreen
- Beat flash, hue slider for custom colours, and optional microphone visualisation
- Works on desktop and mobile

## Run
Open `index.html` in a modern browser, or serve the folder:

```
python3 -m http.server 8000
```

## Shortcuts
| Key | Action |
| --- | --- |
| Space | Play / pause |
| Left / Right | Previous / next visualisation |
| 1-9 | Jump to visualisation |
| A | Toggle auto-cycle |
| L | Playlist |
| F | Fullscreen |

Your audio never leaves your device.

# Trimix Blender PWA

## Files
- `index.html` — the calculator
- `manifest.json` — PWA config
- `sw.js` — service worker (offline caching)
- `icon-192.png` / `icon-512.png` — app icons
- `img.jpg` — YOU ADD THIS (the "best I can do" meme image)

## Setup

1. Add your `img.jpg` (the meme image) to this folder
2. Push all files to a GitHub Pages repo
3. Visit the URL once on your phone
4. Add to Home Screen
5. Done — works offline forever

## Updating

1. Edit files, push to GitHub
2. Change `CACHE_NAME` in `sw.js` from `v1` to `v2` (forces cache refresh)
3. Next time the app opens with any connectivity, it updates automatically

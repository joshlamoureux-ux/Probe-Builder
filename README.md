# Inspection Plus Probe Program Builder

A single-page tool that writes EIA probing programs for Renishaw Inspection Plus
on a Mazak Smooth control (Mazatrol tool data), from the cycle formats in
Renishaw manual H-2000-6903.

## Use it
Open the GitHub Pages address for this repository. On a phone:
- **iPhone (Safari):** Share → Add to Home Screen
- **Android (Chrome):** menu → Install app

After the first visit it works offline. Jobs are saved in the browser on that device only.

## Important
Every generated program must be proved out on the machine in D1 test mode before
production use. Probe cycles will not run with G68 rotation or mirror image active.

## Files
- `index.html` – the whole app
- `manifest.webmanifest`, `sw.js`, icons – install and offline support

# Cola Gummy

An interactive 3D cola-bottle gummy you can grab, stretch, twist and slice with a knife. It runs in the browser on WebGPU, with a real-time soft-body simulation.

## Running it

It's a single self-contained `index.html` with no build step. Serve it over HTTPS (for example on Netlify), because WebGPU only runs on secure pages.

It needs a WebGPU-capable browser, such as a current Chrome, Edge or Safari.

## Controls

- **Hand**: drag a piece to pull it; scroll (or use a second finger) while holding to twist it. Drag empty space to orbit.
- **Knife**: draw a line across the gummy and let go to cut.
- Keys: `Space` pause, `N` nudge, `R` reset, `K` toggle knife, `H` hand.

# solar-system-journey

An interactive 3D solar system explorer that runs in the browser, built with [Three.js](https://threejs.org/).

## Features

- The Sun, all 8 planets and their rings, placed at their real positions for today's date and moving at their real relative speeds
- Dwarf planets (Ceres, Pluto, Haumea, Makemake, Eris, Gonggong) and the large asteroids Vesta, Pallas and Hygiea
- 465 moons: every named moon with real orbit and size data, plus Jupiter's and Saturn's unnamed small moons placed on orbits typical of their families
- The asteroid belt, Jupiter's trojan asteroids and the Kuiper belt
- Click any object to fly to it; planets show their moons orbiting with fading trails, and an info panel gives stats, a description and facts
- Free flight with WASD or the on-screen control panel (thrust pad, lift and boost buttons), orbit and zoom with the mouse
- Time controls from real time up to 10 years per second, search, labels and orbit toggles, and a "true distances" mode

## Run it

It's a single file. Open `index.html` in a modern browser, or serve the folder:

```sh
npx serve .
```

Three.js r128 loads from cdnjs, so an internet connection is needed.

## Controls

| Action | Input |
| --- | --- |
| Look / orbit | Drag |
| Zoom | Scroll |
| Fly | W A S D or thrust pad |
| Rise / sink | E / Q or Up / Down |
| Boost | Shift or Boost button |
| Select and fly to | Click |
| Back out | Esc |
| Pause / speed | Space, `,` and `.` |

Sizes are enlarged and distances compressed by default so everything is visible.

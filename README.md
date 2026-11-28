# solar-system-journey

An interactive 3D solar system explorer that runs in the browser, built with [Three.js](https://threejs.org/).

## Features

- The Sun, all 8 planets and their rings, placed at their real positions for today's date and moving at their real relative speeds
- Dwarf planets (Ceres, Pluto, Haumea, Makemake, Eris, Gonggong) and the large asteroids Vesta, Pallas and Hygiea
- 465 moons: every named moon with real orbit and size data, plus Jupiter's and Saturn's unnamed small moons placed on orbits typical of their families
- The asteroid belt, Jupiter's trojan asteroids and the Kuiper belt
- Click any object to fly to it; planets show their moons orbiting with fading trails, and an info panel gives stats, a description and facts
- Free flight with WASD or the on-screen control panel (thrust pad, rotate and lift buttons), orbit and zoom with the mouse
- Back and Forward buttons to retrace the objects you've visited
- Journeys: seven guided tours (Grand Tour, Ocean Worlds, Fire and Ice, Lords of the Rings, Record Breakers, Kuiper Frontier, Moons of Jupiter) that fly you between stops with narration
- Quiz: 10 questions per round from a hand-written and data-generated bank; the camera flies to each answer, and your best and last scores are saved in your browser
- Works on phones and tablets: drag to look, pinch to zoom, tap to select
- Bottom controls scale to fit the window, and can be stowed away and launched again with the docking-hatch button (or M)
- A start screen and a welcome screen that the narrator reads aloud
- A narrator (on by default; mute with the Sound on/off button) reads out each world you visit and narrates journeys, using the device's best available female English voice
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
| Zoom | Scroll, or pinch on touch screens |
| Fly | W A S D or thrust pad |
| Rise / sink | E / Q or Up / Down |
| Rotate left / right | Z / C or Rotate buttons |
| Boost | Shift |
| Select and fly to | Click |
| Return home (with confirmation) | Return home button or H |
| Stow / launch controls | Stow button or M |
| Back out | Esc |
| Previous / next object | Back and Forward buttons, Backspace, Alt+← / → |
| Pause / speed | Space, `,` and `.` |

Sizes are enlarged and distances compressed by default so everything is visible.

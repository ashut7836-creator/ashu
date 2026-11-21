# CURLING ARENA 3D

A mobile-friendly browser curling prototype built as a separate version alongside the original 2D game.

## Open the game

https://ashut7836-creator.github.io/ashu/curling-arena-3d/

## Stage 1 features

- Three.js 3D arena, ice sheet, house markings, boards, grandstands and lighting.
- Procedural curling stones with blue and red handles.
- Rapier 3D rigid-body collisions; fixed-step simulation and custom ice-friction tuning.
- Aim angle, shot power, left/right curl, and press-and-hold sweeping.
- One-end quick match with eight stones per team.
- Player vs CPU and local two-player modes.
- Closest-stone scoring for the end.
- Automatic local save and a resume prompt on the same browser/device.

## Skills and technical references applied

- [Three.js Game Skills](https://github.com/majidmanzarpour/threejs-game-skills): game-director workflow, gameplay systems, graphics, responsive UI, debugging and release checks.
- [Full Stack Three.js Skills](https://github.com/full-stack-skills/threejs-skills): Three.js setup, cameras, controls, loaders and animations.
- [Three.js](https://threejs.org/) for 3D rendering and OrbitControls.
- [Rapier](https://rapier.rs/) for rigid-body collisions.
- [Poly Haven — Studio Small 06](https://polyhaven.com/a/studio_small_06) for optional 1K environment lighting. Poly Haven assets are CC0; its HDRI is loaded directly by the page. Arena lights provide a fallback if it cannot load.

## Controls

- Change the aim angle and shot power.
- Choose left or right curl.
- Press **RELEASE STONE** to deliver.
- Hold **SWEEP** while the stone moves to reduce the simulated ice friction.
- Drag the 3D scene to orbit the camera and pinch to zoom.
- The game saves locally in browser storage; the save is not synced across devices.

## Development status

This is the first playable 3D slice, not the final tournament release. Tournament brackets and match-to-match progression, full multi-end championship settings, deeper CPU strategy, asset optimisation and broader mobile QA are later stages. The original 2D game remains in `/curling-arena/` and is not replaced.

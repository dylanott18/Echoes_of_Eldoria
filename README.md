# Echoes of Eldoria

A vertical puzzle-platformer about a powerless, outcast wizard climbing a tower of three biomes to reach the dragon **Eldaria**.

**Play:** open `index.html` in a modern browser. It is one self-contained file. All the art, music and sound effects are generated at runtime with Canvas 2D and the Web Audio API, so there are no image, sound or font files.

## The climb
| Screen | Biome | Echo regained | Challenges |
|---|---|---|---|
| 1 (bottom) | **Lurielle Village**: sunset, thatched roofs | **Dash** (Shift) | bramble patches, a thorn pit, wall-jumping up the bell tower, a patrolling thorn block, key → security blocks |
| 2 | **Faelyn Falls**: mist, cascading water, crystals | **Twining Tendril** (E / click) | crystal-thorn basin, grapple anchors, moving platforms, swinging spiked vines, key → security blocks |
| 3 (top) | **Sylvan Sanctuary**: elder trees, starlight | **Glacial Glare** (hold Q, release / right-click) | freezing a fast platform, freezing falling boulders as stepping stones, freezing a spiked vine, key → shrine, the **dragon emblem** |

The camera moves one screen at a time. It snaps up only when you climb past the top edge, and if you fall back through a screen boundary you drop to the screen below. Touching a hazard sends you back to that screen's entry checkpoint.

## Controls
- **A/D or ←/→** run · **W / Space / ↑** jump (hold to jump higher) · **S + Jump** drop through a ledge
- Slide down a wall and press **Jump** to ricochet off it
- **Shift**: magical dash (1.5 s cooldown)
- **E** or **left click**: Twining Tendril. You zip to a green anchor and cling to it briefly, so you can chain tendrils or jump off
- **Q** (hold to aim, release to fire) or **right click**: Glacial Glare. It freezes platforms, boulders, vines and thorn blocks for 4 seconds
- **P / Esc** pause · **M** mute

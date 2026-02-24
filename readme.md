# Unreal Engine Port — Wall Merge (A Link Between Worlds)

This blueprint project is an **Unreal Engine 5 port** of the wall-merge mechanic recreated by **Mix and Jam** in their tutorial based on **The Legend of Zelda: A Link Between Worlds**.

It adapts the original Unity implementation to Unreal Engine while preserving the core behavior: allowing the player to **merge into walls and traverse them as a flat, 2D-constrained form**.

Original tutorial:
**Recreating A Link Between Worlds' Wall Merge**
[https://www.youtube.com/watch?v=JvbsktWVHU8](https://www.youtube.com/watch?v=JvbsktWVHU8)

Original Unity repository:
[https://github.com/mixandjam/LBW-WallMerge](https://github.com/mixandjam/LBW-WallMerge)

---

## Overview

The Wall Merge mechanic allows the player to:

* Detect valid mergeable wall surfaces
* Transition from standard 3D character movement into a wall-merged state
* Constrain movement along the wall plane
* Exit the wall and return to normal gameplay

This Unreal implementation recreates the mechanic using Unreal’s character movement system, surface detection (line traces), and state switching logic.

---

## Features

* Wall detection via line traces
* Movement constrained to wall surface
* Camera adjustments during merge
* Example test level included

---

## Controls (Default Example)

| Action       | Input |
| ------------ | ----- |
| Move         | WASD  |
| Merge / Exit | E     |
| Jump         | Space |

---

## Getting Started

1. Clone or download this repository.
2. Open the `.uproject` file in Unreal Engine 5.x.
3. Open the main test level (if not set as default).
4. Press **Play** to test the mechanic.

---

## Implementation Notes

This port mirrors the logic structure from the original Unity project while adapting it to Unreal Engine concepts:

* Character state switching instead of Unity component toggling
* Line tracing instead of Unity raycasts
* Movement mode adjustments for wall traversal
* Rotation alignment to wall normals

The goal of this project is **learning and experimentation**, not a 1:1 engine-level recreation.

---

## Credits

* Original concept & Unity implementation: **Mix and Jam**
* Inspired by: **The Legend of Zelda: A Link Between Worlds**

---

## License

This project is intended for educational purposes.
Please refer to the original repository for licensing details regarding the base implementation.

---

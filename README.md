



https://github.com/user-attachments/assets/1f5e88c1-e968-426e-ba7b-d345ba0e1102




# Swing-bash

Developed a game which uses grappling gun concept to swing around 2D objects by implementing concepts of SDL
library in C++
- The game has text rendering, visual and sound effects.
- The game uses Vector Calculus to apply Newtons laws of motion, Conservation of momentum and Circular Motion.
- Architected the game using modular OOP design — separate RenderWindow, ObjectManager, EventManager, and Physics_2D classes decouple rendering, spawning, input handling, and physics calculations.
- Implemented a persistent high-score system with file I/O, tracking and sorting scores across sessions via a saved scoreboard.
- Built a real-time game loop with live HUD rendering — score and text overlays rendered every frame via a custom texture wrapper.
- Wrote a reusable 2D vector math library from scratch (no external math dependency), used across physics, collision, and rope calculations.
- Tech Stack Used: SDL library in C++

## How to Build & Run
Requires SDL2, SDL2_image, SDL2_ttf, and SDL2_mixer (install via `brew install sdl2 sdl2_image sdl2_ttf sdl2_mixer` on macOS).

```bash
cd Tarzan-Swing-main
make
./TarzanSwing
```

## How to Play
- Click **PLAY** on the main menu to start.
- **Left-click** anywhere on screen to fire a grappling rope at the nearest object — you'll swing around it in a physics-based arc (gravity + circular motion).
- **Release** to let go and free-fall until your next click.
- Chain swings across the level: hit **friend** objects for +100 points each, avoid **enemy** objects and the lava below — touching either ends the run.
- On game over, click **Retry** to play again or **Exit** to quit. High scores persist across sessions.




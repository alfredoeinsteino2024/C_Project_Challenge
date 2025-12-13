# SDL2 Learning Projects

This branch contains my SDL2 learning journey with various projects and exercises.

## Projects

### Latest: SDL2 Sprite Game (`sdl2-sprite-game.c`)
A complete 2D game featuring:
- PNG sprite rendering (Player, Car, Truck, Tree, Pig)
- Collision detection
- Camera system following the player
- Smooth movement with delta time

### Learning Progression:
1. `01_Open_Window.c` - Basic SDL2 window
2. `SDL2_Renderer_Event.c` - Event handling
3. `Rectangle_Key_Control.c` - Keyboard input
4. `Collision_Detection.c` - Collision system
5. `StepRect.c` - Movement
6. `cameraOnPlayer_Frame_Per_Seconds.c` - Camera and timing
7. `sdl2-sprite-game.c` - Complete game with textures!

## Tech Stack
- C Programming
- SDL2
- SDL2_image

## Compilation
```bash
gcc sdl2-sprite-game.c -lSDL2 -lSDL2_image -o game
```

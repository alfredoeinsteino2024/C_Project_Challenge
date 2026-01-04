# SDL2 Learning Projects
This branch contains my SDL2 learning journey with various projects and exercises.

## Projects

### Latest: SDL2 Sprite Game - Refactored Version (`sdl2-sprite-game-with-loops.c`)
✨ **NEW: Improved with for loops and arrays!**

A complete 2D game featuring:
- PNG sprite rendering (Player, Car, Truck, Tree, Car1)
- Collision detection
- Camera system following the player
- Smooth movement with delta time

**Key Improvements:**
- Eliminated repetitive code using arrays and for loops
- Cleaner texture loading and management
- Simplified rendering and cleanup
- Easier to add new game objects
- More maintainable code structure

### Previous Version: SDL2 Sprite Game (`sdl2-sprite-game.c`)
Original version with repetitive code - kept for comparison to show learning progress.

### Learning Progression:
1. `01_Open_Window.c` - Basic SDL2 window
2. `SDL2_Renderer_Event.c` - Event handling
3. `Rectangle_Key_Control.c` - Keyboard input
4. `Collision_Detection.c` - Collision system
5. `StepRect.c` - Movement
6. `cameraOnPlayer_Frame_Per_Seconds.c` - Camera and timing
7. `sdl2-sprite-game.c` - Complete game with textures
8. `sdl2-sprite-game-with-loops.c` - **Refactored with for loops** ⭐

## Key Learning: Code Refactoring
Compare `sdl2-sprite-game.c` with `sdl2-sprite-game-with-loops.c` to see:
- How arrays eliminate variable repetition
- How for loops reduce code duplication
- Better code maintainability and scalability

## Tech Stack
- C Programming
- SDL2
- SDL2_image

## Compilation
```bash

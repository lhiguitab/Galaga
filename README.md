# Galaga Clone in Jack

This project is a simple clone of the classic arcade game **Galaga**, implemented in the Jack programming language for the Nand2Tetris platform.

## Gameplay
- Control your spaceship at the bottom of the screen.
- Shoot at the enemy fleet at the top.
- Avoid enemy bullets and enemy kamikaze attacks.
- If an enemy or enemy bullet hits your ship, the game ends.
- If all enemies are destroyed, a new wave appears.

## Controls
- **Left Arrow (←):** Move ship left
- **Right Arrow (→):** Move ship right
- **Spacebar:** Shoot
- **Q:** Quit the game

## Features
- Multiple enemies moving in a zigzag pattern
- Enemies can shoot at the player
- Occasionally, enemies perform a special attack, diving towards the player
- Collision detection between bullets, enemies, and the player
- New enemy fleet spawns when all are destroyed

## File Structure
- `Main.jack` — Entry point, starts the game
- `SpaceGame.jack` — Main game logic and loop
- `Ship.jack` — Player ship logic and drawing
- `Enemy.jack` — Enemy ship logic and drawing
- `EnemyFleet.jack` — Manages the enemy fleet and their movement/attacks
- `Bullet.jack` — Bullet logic for both player and enemies

## How to Compile and Run
1. **Compile all `.jack` files:**
   - Use the JackCompiler from the Nand2Tetris tools:
     ```
     JackCompiler
     ```
2. **Run the game:**
   - Open the project folder in the VM Emulator (VMEmulator) from Nand2Tetris.
   - Load `Main.tst` or simply run the compiled `.vm` files.
   - Play using the keyboard controls above.

## Requirements
- Nand2Tetris software suite (JackCompiler, VMEmulator)
- All `.jack` files in the same directory

## Notes
- The game is designed for educational purposes and demonstrates OOP and game logic in Jack.
- You can tweak enemy count, speed, and attack frequency in `SpaceGame.jack` and `EnemyFleet.jack`.

Enjoy playing and hacking your own Galaga in Jack!

## Authors
- Author 1: [Lucas Higuita Bedoya]
- Author 2: [Santiago Gómez Ospina]
- Author 3: [Daniel Arcila Salazar]
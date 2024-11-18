# Shooting Game

A 2D fighter jet shooting game built with Pygame where players control a fighter jet, shoot enemies, and avoid collisions.

## Main Game Features

The `main.py` file implements the core game mechanics:

### Game Components
- Player-controlled fighter jet
- Enemy jets that spawn from the top of the screen
- Bullet shooting mechanism
- Collision detection system
- Score tracking

### Controls
- LEFT/RIGHT Arrow Keys: Move the fighter jet horizontally
- UP Arrow Key: Shoot bullets
- SPACE: Start the game
- R: Restart after game over
- ESC: Quit the game

### Technical Implementation Details

The game utilizes several key Pygame features and programming concepts:

1. **Game Initialization**
   - Screen setup (800x600 pixels)
   - Asset loading (fighter jet, enemy, and bullet images)
   - FPS control (60 frames per second)

2. **Game States**
   - Start screen
   - Active gameplay
   - Game over screen

3. **Game Mechanics**
   - Enemy spawning system with timing controls
   - Bullet firing mechanism
   - Player movement within screen boundaries
   - Collision detection between:
     - Bullets and enemies
     - Player and enemies

4. **Score System**
   - Tracks successful hits (bullet-enemy collisions)
   - Displays current score during gameplay

## Dependencies
- Python 3.x
- Pygame library

## Game Assets

The game uses the following image assets:

- fighter_jet02.png - Player's fighter jet
- enemy_jet02.png - Enemy aircraft
- bullet02.png - Projectile sprite
   

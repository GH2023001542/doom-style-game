# DOOM Style Game 🔫

A DOOM-style first person shooter built in Python using Pygame.

## Features
- Raycasting 3D engine (no game engine used!)
- 3 enemy types: Soldier, CacoDemon, CyberDemon
- Enemy AI with pathfinding (BFS algorithm)
- Animated sprites and weapons
- Sound effects and background music

## How to Run
1. Install Python and pygame:
   pip install pygame
2. Run the game:
   cd DOOM-style-Game-main
   python main.py

## Controls
| Key | Action |
|-----|--------|
| W A S D | Move |
| Mouse | Look around |
| Left Click | Shoot |
| Esc | Quit |

## Project Structure
- main.py — Game loop
- raycasting.py — 3D rendering engine
- npc.py — Enemy AI
- pathfinding.py — BFS navigation
- player.py — Movement and input
- weapon.py — Shotgun system

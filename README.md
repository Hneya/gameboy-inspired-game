# gameboy-inspired-game

## Project Overview
Rebuilding the GameBoy experience featuring:
- A functional GFameboy system with menus, input controls, and screen managemnt
- Snake
- Hangman: the classic word-guessing challenge
## Key Features Implemented
- Interactive menu system for game selection
- Smooth input handling (arrow keys/WASD)
- Game lifecycle management: load, play, switch, exit
### Snake
- Smooth snake movement and growth mechanics
- Food generation and collision detection
### Hangman
- Word category system and lives management
- Progressive hangman drawing
- Letter input handling
### Object-Oriented Design
-**Inheritance:**A base Game class definign core interfaces inherited by each game
-**Polymorphism:**Virtual functions for game update/render cycles
-**Composition:**Games composed of modular components (snake body segments, hangman figure)
-**Abstraction:**Abstract screen and input handling classes to unify UI across games
## Technologies used
- C++
- SFML
## Other Contributors
- Abeerah Sohail

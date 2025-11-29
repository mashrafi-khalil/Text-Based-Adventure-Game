# Text-Based Adventure Game

A fully immersive text-based adventure game, designed in **C programming language**, where players navigate a mysterious world, solve puzzles, and make critical decisions to shape the storyline.

---

## Table of Contents

- [Introduction](#introduction)  
- [Gameplay](#gameplay)  
- [Features](#features)  
- [Code Structure](#code-structure)  
- [Development Strategy](#development-strategy)  
- [Challenges](#challenges)  
- [Future Enhancements](#future-enhancements)  
- [How to Play](#how-to-play)  
- [License](#license)  

---

## Introduction

This project is a narrative-driven text-based adventure game built in C. Players are transported into an unknown dimension, navigating through terrains, interacting with characters, and solving riddles to progress in the story.  

The game demonstrates fundamental C programming concepts such as:

- Loops and conditional statements  
- Functions and recursion  
- Input validation  
- Global variable management  

It merges **technical programming skills** with **creative storytelling**, providing an engaging, interactive experience without graphics.

---

## Gameplay

- Players start in a familiar city and are transported to a mysterious world.  
- Key locations and encounters include:
  - Misty River or Paved Road: Player choices determine the path.  
  - NPC Encounters: A wise scholar, shopkeeper, and city mayor offer puzzles and quests.  
  - Temple Trials: Logical puzzles, parkour challenges, and guardians test the player.  
  - Final Test: Solve riddles posed by an Ancient Being of Knowledge to win.  
- Multiple endings based on player decisions, offering replayability.  

---

## Features

- **Interactive Choices**: Player decisions shape the storyline.  
- **Logical Puzzles**: Riddles and challenges test critical thinking.  
- **Modular Design**: Functions handle encounters, resets, and validations.  
- **Input Validation**: Ensures smooth gameplay and prevents crashes.  
- **Replayability**: Randomized elements and branching paths encourage multiple playthroughs.  
- **Error Handling**: Guides players through invalid input without breaking the game.  

---

## Code Structure

- **Modular Functions**:  
  - `startGame()`, `mistyRiver()`, `temple()`, `gameOver()`, etc.  
- **Global Variables** track player progress and game state:  
  - `mistyRiverVisited`, `returnedToFork`, `gameWon`  
- **Loops** manage repeated gameplay elements and input validation.  
- **Conditional Statements** determine narrative branching.  
- **Recursion** allows restarting the game seamlessly.  
- **Randomization** via `rand()` introduces variety in riddles and encounters.  

---

## Development Strategy

1. **Planning & Flowchart**: Structured the entire game flow and branching logic.  
2. **Function-Based Development**: Modular functions developed to manage encounters and decisions.  
3. **Integration & Testing**: Functions combined and rigorously tested for logical consistency.  
4. **Debugging**: Addressed edge cases and ensured stable gameplay.  

---

## Challenges

- **Game State Management**: Ensured logical consistency and prevented revisits to completed areas.  
- **Input Validation & Error Handling**: Handled numeric and string inputs to prevent crashes.  
- **Logical Flow**: Maintained a cohesive narrative despite branching paths.  
- **Designing Puzzles**: Balanced difficulty to provide challenge without frustration.  
- **Debugging Complex Scenarios**: Tested all paths to ensure seamless gameplay.  

---

## Future Enhancements

- **Save/Load Feature**: Allow players to save their progress.  
- **Expanded Storyline**: Add new locations, characters, and puzzles.  
- **Graphical Enhancements**: Integrate basic graphics or animations for a richer experience.  

---

## How to Play

1. Clone or download the repository.  
2. Open the project in a C compiler or IDE (e.g., Code::Blocks, Dev C++, or GCC).  
3. Compile the `.c` files.  
4. Run the executable and follow on-screen prompts.  
5. Make choices, solve riddles, and explore the adventure world.  

---

## License

This project is **free to use and modify** for educational purposes.  

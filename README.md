# SHOOTING-GAME-1st-Sem-Project-
🎯 2D SHOOTING GAME

👨‍💻 Developed By
Muhammad Hassan

Asif Ali Ansaree

Dawood Akbar

Iqrar Ur Rehman

🎮 Project Overview
This project is a fast-paced 2D shooting game designed to test your accuracy, reflexes, and strategic skills. With progressive difficulty, randomized challenges, and interactive audio-visual effects, it keeps players engaged through escalating levels and varied gameplay. Each level is more challenging than the last, rewarding player mastery while offering a satisfying and replayable experience.

🧩 Key Features

🔫 Player Controls
Move left and right using arrow keys.

Press spacebar to shoot bullets.

🎯 Target & Obstacle System
Green targets descend randomly — shoot them to score points.

Gray stones reduce your score if hit — avoid or dodge them.

⚙️ Difficulty Modes
Choose between Easy, Medium, or Hard.

Difficulty affects spawn rate, object speed, and score targets.

🆙 Level Progression
Every level has a score target and time limit.

Progress to the next level by achieving the target within the time.

⏱️ Timer System
Countdown timer controls the time available for each level.

At timeout, the game checks for win/loss conditions.

🔊 Visual & Audio Feedback
Includes sound effects for shooting, hits, and collisions.

Real-time visuals display score, timer, and target status.

🔁 Retry & Endgame System
Players can retry if they fail a level.

Displays custom win/loss messages with options to replay or quit.

🎲 Randomized Gameplay
Random spawn locations and timings keep gameplay fresh and unpredictable.

📈 Progressive Difficulty
As levels advance, gameplay gets faster and more complex.

🧭 User-Friendly Interface
Clear menus and instructions to guide players before gameplay.

🧱 Game Architecture
🔧 Core Modules Breakdown
1. Game Initialization
Sets up the game window, textures, and audio.

Loads resources and prepares game state variables.

2. Input Handling
Captures keyboard input for movement and shooting.

Updates player position and spawns bullets accordingly.

3. Game Object Management
Controls bullets, targets, and obstacles.

Manages spawning, updating, and deactivation.

4. Collision Detection
Detects interactions between bullets, targets, and obstacles.

Triggers score updates and object state changes.

5. Scoring System
Tracks player score dynamically.

Increments for targets hit, decrements for stone collisions.

6. Timer & Level Logic
Monitors time remaining.

Determines level outcome based on time and score.

7. UI Rendering
Renders player, bullets, and objects.

Displays score, timer, and messages clearly on screen.

8. Audio System
Plays context-sensitive sounds: shooting, hitting, collision, etc.

9. Main Game Loop
The heart of the program.

Continuously updates all modules and renders the game in real-time.

🔄 Module Interactions Diagram
Initialization Module → Prepares resources for the game loop.

Input Module → Triggers changes in player position and shooting.

Object Manager ↔ Collision & Scoring Modules → Handle interactions and scoring.

Timer Module → Signals the end of a level to the main loop.

Audio & UI Modules → React to in-game events for user feedback.

🚀 How to Run the Game
Requirements:
Visual Studio or Visual Studio Code

Raylib Library

Setup Instructions:
Download and configure Raylib in your IDE.
(You can find setup guides for your system by searching "Raylib setup for Visual Studio/VSCode").

In your project file:

Include the raylib header:
#include "raylib.h"

Build and run the project — enjoy the game!

✅ Final Notes
This 2D Shooting Game is an excellent demonstration of game development fundamentals such as:

Real-time user input handling

Sprite rendering

Object-oriented modular architecture

Collision and score logic

Sound integration

Difficulty scaling and level design

Whether you're a casual gamer or an aspiring developer, this project offers both fun and insights into game mechanics!

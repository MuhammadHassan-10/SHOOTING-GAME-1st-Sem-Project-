# SHOOTING-GAME-1st-Sem-Project-
# 🎯 2D Shooting Game

## 👨‍💻 Developed By

- **Muhammad Hassan**  
- **Asif Ali Ansaree**  
- **Dawood Akbar**  
- **Iqrar Ur Rehman**

---

## 🎮 Project Overview

This project is a fast-paced 2D shooting game designed to test your **accuracy**, **reflexes**, and **strategic skills**. With **progressive difficulty**, **randomized challenges**, and **interactive audio-visual effects**, it keeps players engaged through escalating levels and varied gameplay. Each level becomes more challenging, rewarding player mastery while offering a satisfying and replayable experience.

---

## 🧩 Key Features

### 🔫 Player Controls

- Move **left** and **right** using arrow keys.  
- Press **spacebar** to shoot bullets.

### 🎯 Target & Obstacle System

- **Green targets** descend randomly — shoot them to score points.  
- **Gray stones** reduce your score if hit — avoid or dodge them.

### ⚙️ Difficulty Modes

- Choose between **Easy**, **Medium**, or **Hard**.  
- Difficulty affects **spawn rate**, **object speed**, and **score targets**.

### 🆙 Level Progression

- Each level includes a **time limit** and **target score**.  
- Progress to the next level by achieving the score within the time.

### ⏱️ Timer System

- Countdown timer tracks remaining level time.  
- Game evaluates **win/loss condition** once the timer ends.

### 🔊 Visual & Audio Feedback

- **Sound effects** for shooting, hitting targets, and collisions.  
- Visuals include background image, score, timer, and target indicators.

### 🔁 Retry & Endgame System

- Retry a level if time runs out or the score target isn't met.  
- Displays **win/loss messages** with options to **replay or quit**.

### 🎲 Randomized Gameplay

- Random **spawn positions** and **timing** of targets and obstacles.

### 📈 Progressive Difficulty

- Speed and complexity of descending objects increase with levels.

### 🧭 User-Friendly Interface

- Clear **menus** and **instructions** guide players at each stage.

---

## 🧱 Game Architecture

### 🔧 Core Modules

#### 1. Game Initialization

- Initializes game window, textures, and audio.
- Loads all required resources.
- Sets up initial variables and game state.

#### 2. Input Handling

- Captures player keyboard input.
- Controls movement and shooting.
- Updates player position and spawns bullets.

#### 3. Game Object Management

- Manages **bullets**, **targets**, and **obstacles**.
- Handles spawning, updating, and deactivation of objects.

#### 4. Collision Detection

- Detects collisions between objects.
- Updates object states and scoring logic based on outcomes.

#### 5. Scoring System

- Tracks the player’s score dynamically.
- Adds points for hitting targets and subtracts for hitting stones.

#### 6. Timer & Level Logic

- Monitors time for each level.
- Determines **win/loss conditions** based on score and timer.

#### 7. UI Rendering

- Renders bullets, players, targets, and game text.
- Displays current score, timer, and end-game messages.
- Shows initial menu and difficulty selection screen.

#### 8. Audio System

- Plays sounds for shooting, hits, and obstacles.

#### 9. Game Loop

- Central loop connecting all modules.
- Updates game state continuously and handles rendering.

---

### 🔄 Module Interaction Flow

- **Initialization Module** → Sets up assets and passes them to Game Loop.  
- **Input Module** → Controls player actions and interacts with Object Manager.  
- **Object Manager** ↔ **Collision Detector** → Handles object updates and interactions.  
- **Scoring Module** → Communicates with UI to update score.  
- **Timer Module** → Notifies Game Loop of level completion state.  
- **Audio System** → Triggered by gameplay events like shooting and collisions.  
- **UI Module** → Displays all feedback and instructions to the player.

---

## 🚀 How to Run the Game

### 🧰 Requirements

- **Visual Studio** or **Visual Studio Code**
- **Raylib Library**

### 🛠 Setup Instructions

1. Download and install **Raylib** for your operating system.  
   Search: `Raylib setup for Visual Studio` or `Raylib VSCode setup`.

2. Create a C/C++ project and include the Raylib header:

   ```c
   #include "raylib.h"

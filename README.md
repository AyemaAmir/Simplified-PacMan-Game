# Simplified Pac-Man in C++ with SFML

As a data science student, I built this project to explore object-oriented programming (OOP) and agent-based simulation — concepts that are also valuable in AI, behavioral modeling, and reinforcement learning. This simplified Pac-Man game, developed using C++ and the SFML graphics library, demonstrates clean modular design, real-time interaction, and state-driven logic.

---

## 🚀 Key Features

### 🎮 Core Gameplay
Control Pac-Man using the keyboard to collect coins (100 pts) and cherries (starting at 300 pts) while avoiding ghosts.

### 📈 Progressive Difficulty (4 Levels)
- Each level adds one more ghost that actively chases Pac-Man.
- Fruit points increase as a reward in higher levels.

### 👻 Enemy AI
- One ghost initially chases Pac-Man.
- Others move randomly and change directions every few seconds.
- More ghosts begin chasing as levels progress.

### 🌀 Game Flow
- Starts with a “Start Game” screen.
- Ends with a “You Won!” or “Game Over” screen, both offering a “Play Again” option.

### 🔊 Audio Feedback
Includes sound effects for collecting items and ghost collisions.

---

## 🧠 Object-Oriented Design

- **Map**: Draws the play area and screen borders.
- **Coin / Fruit**: Places collectibles and handles scoring logic.
- **Ghost**: Implements ghost behavior — chasing logic and timed direction changes.
- **PacMan**: Controls movement, collision, and scoring.
- **main()**: Manages the game loop, input handling, and state updates.

---

## 🔒 License

This project is **not open source**. All rights reserved.  
**Do not reuse, redistribute, or modify the code without explicit permission.**

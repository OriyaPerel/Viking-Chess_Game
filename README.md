# 🛡️ Viking Chess Game  

An interactive strategy board game inspired by **Viking Chess (Hnefatafl)** — fully implemented in **Java** with an intuitive **Swing GUI** and a robust **Object-Oriented Architecture**.  
This project demonstrates a complete game engine, real-time graphical interaction, performance analytics, and automated testing.

---

## 🎮 Overview

**Viking Chess** is a two-player asymmetric strategy game between **Attackers** and **Defenders**.  
The defenders must protect their **King** and guide him safely to one of the board’s corners, while the attackers aim to capture him before he escapes.

This project brings the ancient strategy to life with:

- A **fully playable board** with an interactive graphical interface.  
- **Comprehensive game logic**, including movement rules, captures, and victory detection.  
- **Turn management** and real-time updates after each move.  
- **Post-game analytics** summarizing player performance and movement statistics.  

---


### 🧩 Object-Oriented Design
The system is built on a modular OOP structure with clear abstractions and separation of concerns:

- **`Piece`**, **`Player`**, **`PlayableLogic`** — Core interfaces defining shared behavior.  
- **`ConcretePiece`**, **`Pawn`**, **`King`** — Hierarchy of game pieces, each with specific properties and logic.  
- **`ConcretePlayer`** — Tracks player information, moves, and win history.  
- **`GameLogic`** — Implements core mechanics: setup, validation, moves, captures, undo, and victory conditions.  
- **`GUI_for_chess_like_games`** — Swing-based interface enabling full visual and interactive gameplay.  

---

## 🧪 Testing & Validation

Automated testing ensures the correctness and stability of game behavior using **JUnit 5**.

- **Parameterized tests** (`GameLogicTest.java`) validate moves against expected outputs from resource files.  
- **Console output capture** verifies rule consistency and result accuracy.  
- Each move, capture, and undo operation is validated against real game logic to ensure a fully playable experience.


---

## 🚀 How to Run


# 1. Clone the repository
git clone https://github.com/oriyaPerel/Viking-Chess_Game.git

# 2. Navigate to the project folder
cd Viking-Chess_Game

# 3. Compile the Java source files
javac Main.java

# 4. Run the game
java Main




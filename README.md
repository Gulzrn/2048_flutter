# 2048 Game in Flutter

This is a Flutter implementation of the classic **2048 puzzle game**, built entirely using Dart and Flutter widgets. It features smooth animations, touch controls, and dynamic tile movements.

## 🧠 Game Objective

The goal of 2048 is to **slide numbered tiles on a 4×4 grid** to combine them and create a tile with the number **2048**. When two tiles with the same number collide, they merge into one and their values add up.

---

## 🕹️ How It Works

### 🎮 Game Logic
- A 4x4 board is created.
- Each move (swipe left, right, up, down) **shifts tiles** in that direction.
- If two tiles of the same value collide, they **merge** and their value doubles.
- A new tile (2 or 4) appears randomly after every move.
- The game ends when:
  - You **create a 2048 tile** (win),
  - OR there are **no possible moves left** (loss).

### 🎨 UI & Animations
- Tiles move smoothly with **position and scale animations**.
- Merging tiles show a **pop animation**.
- A **score counter** tracks your progress.
- Buttons allow:
  - Restarting the game
  - Undoing a move (if implemented)
  - Exiting the app

---

💡 Features
Fully working 2048 game logic

Responsive touch controls

Animated tile movement and merging

Score tracking

Restart Game button

Clean and modern UI

🧱 Built With
Flutter – For UI and animations

Dart – For game logic and backend

No external packages (entire logic is written manually)


![image](https://github.com/user-attachments/assets/13a98422-22ec-407e-8abd-b55a54ab66b1)
![image](https://github.com/user-attachments/assets/26ffd7b4-4dff-43c3-8c2d-46ed78f3ce24)



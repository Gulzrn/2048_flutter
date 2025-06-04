# 🧩 2048 Game in Flutter

This is a full implementation of the **2048 puzzle game** built using the **Flutter framework**. The game features smooth animations, responsive touch gestures, and a dynamic user interface – all made possible using Flutter's powerful widget system.

---

## 🚀 Why Flutter?

The app is built with Flutter because:

- 🔁 **Hot Reload** makes it easy to iterate on UI and logic.
- 🎨 **Custom Widget Composition** allows us to build complex UIs (like animated tiles and boards) with reusable, testable components.
- 🧱 **Declarative UI** makes state-based UI updates seamless.
- 📱 **Cross-platform Output**: With Flutter, this game can run on Android, iOS, Web, and Desktop with little to no change in code.

---

## 🛠️ Flutter Features Used

### 1. **State Management (Stateful Widgets & setState)**
- The game board updates dynamically as you swipe.
- `setState` is used to trigger UI updates when tiles move, merge, or new tiles are added.

### 2. **Gesture Detection**
- `GestureDetector` handles swipe gestures (up, down, left, right) to move tiles.
- It provides a smooth and responsive control system for touch devices.

### 3. **Custom Widgets**
- Everything on the screen (tiles, board, score, buttons) is built using custom widgets for modular and clean code.
- Examples:
  - `AnimatedTile` for moving/merging tiles
  - `TileWidget` for visual design
  - `ScoreWidget` for showing score updates

### 4. **Animations**
- Flutter’s built-in **implicit animations** (`AnimatedPositioned`, `AnimatedScale`) create fluid tile movements.
- Helps replicate the classic 2048 feel with natural transitions.

### 5. **Layout Widgets**
- `Stack` is used to layer tiles over the board.
- `Grid`, `Row`, and `Column` widgets build the 4x4 layout.
- `Padding`, `SizedBox`, and `Align` give precise control over UI layout.

### 6. **Theme & Styling**
- Colors, shadows, and rounded tiles are all done using `BoxDecoration`, `TextStyle`, and `Container`.

---

## 🎮 Game Functionality

- Tiles move in the direction of swipe.
- Matching tiles merge and double in value.
- New tile (2 or 4) spawns after every move.
- Game ends when:
  - You create a tile with value 2048 (Win), or
  - No more valid moves exist (Lose).

---

## 📱 Cross-Platform Compatibility

Since it's made with Flutter:
- ✅ Android and iOS support
- ✅ Runs on desktop (Windows, macOS, Linux)
- ✅ Can be compiled to Web (via `flutter build web`)



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



# 🐍 Snake Game in C using Graphics.h

This is a simple **Snake Game** developed in C using the `graphics.h` library. The game runs in a graphical environment, where the player controls a snake that grows in length by consuming food and must avoid hitting the walls or itself.


---

## 🎮 Gameplay Overview

- The game is played within a bordered screen.
- Use **Arrow Keys** to control the direction of the snake:
  - ⬅️ Left Arrow: Move Left
  - ➡️ Right Arrow: Move Right
  - ⬆️ Up Arrow: Move Up
  - ⬇️ Down Arrow: Move Down
- The snake increases in length each time it eats food.
- The game ends if the snake hits the walls or itself.
- The final **score** is the number of food items eaten.

---

## 🧱 Features

- Snake movement in real-time.
- Random food generation using `rand()` and `time.h`.
- Collision detection using `getpixel()`.
- Color-coded snake and food blocks.
- Simple point system.

---

## 📦 Requirements

To run this project, make sure you have the following:

- Turbo C++ or any compiler that supports `graphics.h`
- DOSBox (for 64-bit systems)
- Libraries:
  - `graphics.h`
  - `dos.h` or `windows.h` (for `GetAsyncKeyState`)
---

## 🚀 How to Run

### 🔧 Step-by-Step (Turbo C++ / DOSBox):

1. **Install Turbo C++ / DOSBox** on your machine.
2. Copy the source code into a file, e.g., `snake.c`.
3. Open Turbo C++ or run DOSBox and open your project directory.
4. Compile the program:
   ```
   Ctrl + F9
   ```
5. Run the program:
   ```
   Ctrl + F10
   ```

> 💡 Ensure `graphics.h` and `BGI` folder are properly set in your compiler settings.

---

## 🧠 Code Structure

- `main()` - Initializes graphics, creates initial snake and boundary.
- `X[], Y[]` - Arrays to store the positions of the snake segments.
- `rx, ry` - Coordinates of the randomly generated food.
- Movement is handled via `GetAsyncKeyState()` and updated per frame.
- The snake’s body is drawn using `bar()` with different fill styles.

---

## 📸 Screenshots

> *(Add screenshots here if available)*

---

## 📚 Credits

Developed by: **Your Name**  
Language: **C (Turbo C++ with graphics.h)**

---

## 📜 License

This project is open-source and free to use for learning and educational purposes.

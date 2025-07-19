# 🏀 Simple Scratch Basketball Game

A basic basketball-catching game built using [Scratch](https://scratch.mit.edu). Move your player left or right to catch falling basketballs. Score points and avoid missing too many drops!

---

## 🎮 Gameplay Features

- 🧍‍♂️ **Player Controls**: Use **left** and **right arrow keys** to move.
- 🏀 **Catch Basketballs** to earn points.
- ❌ **Missed Drops**: Each missed basketball increases your drop count.
- 🏁 **Game Ends** when drop limit is reached.

---

## 📋 Requirements

- [Scratch 3.0](https://scratch.mit.edu) – use the online editor or offline app
- Two sprites:
  - A **player**
  - A **basketball**

---

## 🛠️ Game Logic

- **Variables Used**:
  - `score` – increases by 1 on catch.
  - `drops` – increases by 1 on miss.
  - `game running` – controls the game loop.

- **Main Blocks Used**:
  - Conditionals (`if drops > limit`)
  - Loops (`forever`, `repeat`)
  - One **custom block** with input (like `fallWithSpeed(speed)` or similar)

---

## 🚀 How to Run

1. Download the `.sb3` file.
2. Open it on [scratch.mit.edu](https://scratch.mit.edu).
3. Click the green flag to start the game.
4. Use the arrow keys to move and catch the ball.

---

## 🧾 Project Files

- `scratch-basketball-game.sb3`
- `README.md`

---

## 🪪 License

Open-source for learning and remixing. Give credit when sharing or building on this project.

---

## 🙌 Creator

Made with ❤️ by [@krix2112](https://github.com/krix2112)


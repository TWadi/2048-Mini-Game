# 2048‑mini (PyQt)

A tiny, clean implementation of the 2048 puzzle game built with **Python** and **PyQt**.

> Merge tiles with the same value to reach **2048**. Use arrow keys (or swipe/WSAD) to move.

---

## ✨ Features

* Smooth animations
* Keyboard support
* Undo (single‑step) & Restart
* Configurable board size (default 4×4)
* Auto‑spawn logic with 2/4 distribution
* Persistent best score (JSON file)
* Simple, themeable UI

---

## 📦 Tech Stack

* Python 3.10+
* PyQt (developed with Qt Creator)

---

## ▶️ Run

Open the project in **Qt Creator** and run `main.py`.

---

## 🎮 Controls

* **Arrow Keys / WASD** — move tiles
* **U** — undo last move
* **R** — restart game
* **Esc** — quit

---

## 🧠 Game Rules (Quick)

1. Each move slides all tiles in one direction.
2. Tiles with the **same number** merge into one (sum of both).
3. After each move, a new **2** (90%) or **4** (10%) appears in a random empty cell.
4. The game ends when **no moves** are possible.

---

## 📂 Project Structure (suggested)

```
2048-mini/
├─ src/
│  ├─ main.py              # app entry
│  ├─ ui.py                # board view, animations
│  ├─ game.py              # core game logic
│  ├─ storage.py           # score persistence
│  ├─ config.py            # constants
│  └─ theming.py           # stylesheets
├─ assets/
│  └─ icons/               # app icons (optional)
├─ tests/
│  └─ test_game.py         # unit tests
├─ README.md
└─ LICENSE
```

---

## 📄 License

MIT

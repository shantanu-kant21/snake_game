# 🐍 Python Snake Game 🎮

### A classic Snake game built with Python's `turtle` module

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Turtle](https://img.shields.io/badge/Library-Turtle-00C853?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Playable-success?style=for-the-badge)

*Eat the food, grow longer, beat your high score, and don't hit the walls!* 🍎


---

## 📸 Preview

<!-- Add a screenshot or GIF of your game here, for example:
![Gameplay](screenshot.png)
-->

> 💡 **Tip:** Run the game and take a screenshot to show visitors what it looks like.

---

## ✨ Features

- 🎯 **Classic Snake gameplay** - guide the snake to eat food and grow
- ⌨️ **Dual controls** - play with **Arrow Keys** or **WASD**
- 🏆 **Score and High Score** tracking shown live on screen
- ⚡ **Increasing difficulty** - the snake gets faster as you eat
- 💥 **Collision detection** - hitting a wall or your own body resets the game
- 🎨 **Neon look** - lime snake, red food, black background
- 🪶 **Lightweight** - no external libraries to install

---

## 🕹️ Controls

| Key | Action |
|-----|--------|
| ⬆️ / `W` | Move Up |
| ⬇️ / `S` | Move Down |
| ⬅️ / `A` | Move Left |
| ➡️ / `D` | Move Right |

> The snake can't reverse directly into itself, and it won't move until you press a key.

---

## 🎲 Game Rules

1. 🍎 Eat the **red food** to gain **+10 points** and grow one segment.
2. 🚀 Every time you eat, the snake gets **slightly faster**.
3. 🧱 Touching the **border** resets the game.
4. 🐍 Biting your **own body** resets the game.
5. 🏅 Your **High Score** stays on screen until you close the game.

---

## 🛠️ Requirements

- **Python 3.x** ([Download here](https://www.python.org/downloads/))
- `turtle`, `time` and `random` are all part of Python's standard library. **No `pip install` needed!** ✅

> 🐧 **Linux users:** if you get a Tkinter error, install it with
> `sudo apt install python3-tk`

---

## 🚀 How to Run

**1. Clone the repository**

```bash
git clone https://github.com/shantanu-kant21/snake_game.git
```

**2. Go into the project folder**

```bash
cd snake_game
```

**3. Run the game**

```bash
python snake_game.py
```

> On macOS/Linux, use `python3 snake_game.py` if `python` doesn't work.

**4. Play!** 🎉 Click on the game window and press any arrow key or WASD to start.

---

## 📁 Project Structure

```
snake_game/
├── snake_game.py   # Main game code
└── README.md       # You are here 📍
```

---

## 🧠 How It Works

- **`turtle.Screen()`** creates the 600x600 game window with a black background.
- **`screen.tracer(0)`** turns off automatic redraws, and `screen.update()` is called manually each frame for smooth animation.
- **The snake** is a list of turtle squares: the head moves 20px per frame and each body segment follows the one in front of it.
- **Food** spawns at a random grid position using `random.randrange()`.
- **Collisions** are detected with `distance()` checks and screen boundary limits.
- **Keyboard input** is handled with `screen.listen()` and `screen.onkeypress()`.

---

## 🔮 Future Improvements

- [ ] 🔊 Add sound effects
- [ ] 💾 Save high score to a file
- [ ] 🎚️ Add difficulty levels
- [ ] 🌐 Port to HTML/JavaScript for browser play
- [ ] ⏸️ Add pause and restart buttons

---

## 🤝 Contributing

Contributions are welcome! 🙌

1. 🍴 Fork this repository
2. 🌿 Create a new branch (`git checkout -b feature/amazing-feature`)
3. 💾 Commit your changes (`git commit -m "Add amazing feature"`)
4. 📤 Push to the branch (`git push origin feature/amazing-feature`)
5. 🔃 Open a Pull Request

---

## 🙏 Credits

- 📦 Uploaded and documented by **[Shantanu Kant](https://github.com/shantanu-kant21)**

---


### ⭐ If you enjoyed the game, give this repo a star! ⭐

Made with ❤️ and Python 🐍

</div>

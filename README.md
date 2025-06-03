# 🐤 Flappy Bird Clone (Python + Pygame)

A simple Flappy Bird game clone built with Python and Pygame. Control a bird by tapping the space or arrow keys to fly through pipes and try not to crash!

---

## 🎮 Gameplay

- Press **Space** or **Up Arrow** to flap and start the game.
- Avoid the upper and lower pipes.
- The score increases as you pass through pipes.
- Game over if you hit a pipe or fall off the screen.

---

## 📁 Features

- Realistic gravity and flap physics.
- Moving pipe obstacles with collision detection.
- Score display using number images.
- Smooth frame rate and responsive controls.
- Background, bird, pipe, and base graphics rendered with `pygame`.

---

## 📷 Screenshots

> *(Optional: Add gameplay screenshots or a short demo GIF here)*

---

## 🛠️ Requirements

Install the required library using:

```bash
pip install pygame
```

---

## 📂 Project Structure
```bash
FlappyBird/
├── images/
│   ├── 0.png to 9.png      # Score digit images
│   ├── background.jpg      # Game background
│   ├── base.jfif           # Sea-level image
│   ├── bird.png            # Flappy bird sprite
│   └── pipe.png            # Pipe image (used both rotated and normal)
├── flappy_bird_game.py     # Main game script (rename your .py file if needed)
└── README.md
```

---


## 🚀 How to Run the Game

1. Ensure you have Python 3 installed.

2. Clone this repo or download the code and assets.

3. Place all images inside FlappyBird/images/ as described above.

4. Run the script:

```bash
python flappy_bird_game.py
```

Replace flappy_bird_game.py with the actual filename if different.

---


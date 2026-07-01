# 🕯️ Shadow Maze

A stylized first-person survival game built with Python, Pygame, NumPy, and Numba. Explore a procedurally generated maze, survive hostile enemies, and reach the exit before the darkness closes in.

![Gameplay Preview](https://img.shields.io/badge/Status-Playable-brightgreen) ![Python](https://img.shields.io/badge/Python-3.10%2B-blue) ![License](https://img.shields.io/badge/License-Open%20Source-lightgrey)

## ✨ Features

- Procedurally generated maze levels
- First-person ray-casting style rendering
- Animated enemies with simple AI behavior
- Sword combat and player health system
- Background music and immersive textures
- Lightweight and easy to run locally

## 🎮 How to Play

- Move with W, A, S, D or the arrow keys
- Look around with your mouse
- Left-click to swing your sword
- Press Esc to exit the game

## 🛠️ Installation

Make sure you have Python 3.10 or newer installed.

```bash
python -m pip install --upgrade pip
pip install pygame numpy numba
```

Then start the game:

```bash
python main.py
```

On Windows, this also works:

```powershell
py main.py
```

## 📁 Project Structure

- main.py — main game loop, rendering logic, enemy AI, and gameplay systems
- background.mp3 — background music
- skybox2.jpg, floor.jpg, wall.jpg — environment textures
- sword1.png, zskeleton.png — sprite assets

## ⚙️ Requirements

- Python 3.10+
- pygame
- numpy
- numba

## 💡 Notes

This project relies on local asset files in the same folder as the script, so keep the media files alongside main.py when running it.

If you'd like, I can also turn this into a more premium README with a screenshot section, badges, and a dedicated “How It Works” section.

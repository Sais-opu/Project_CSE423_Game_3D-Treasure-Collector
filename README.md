# 3D Treasure Collector

Developed as a group project:

- Simran Zaman Mayabi  
- Md Saidul Islam Apu  
- Al-Amin Sagor  

This is a simple 3D exploration game built with Python and PyOpenGL.  
The player moves around a large world, collects treasures, avoids falling bricks, and survives as long as possible while managing time and health.

The project intentionally avoids using a game engine. All mechanics, rendering, and interactions are implemented manually.

---

## Images / Screenshots

![Game Screenshot](https://i.ibb.co.com/qMDfdzvQ/2.png)

---

## Features

### Core Gameplay
- Explore a fully open grid world
- Collect normal and special treasures
- Use a key to unlock special treasures
- Restart and replay the game

### Health and Damage
- Random falling bricks can hit the player
- Traps and collapsing debris reduce life
- Game over when health reaches zero or time runs out

### Time System
- Total play time is limited
- Special treasures can increase remaining time

### Special Key System
- A key spawns at a random location
- Special treasures are locked until the key is collected
- Some special treasures become visible for a short time after picking the key

### Cheat Mode
- Temporarily shows important elements
- Stops random brick falling for a short time

### Brick and Ceiling System
- Bricks spawn randomly and often target the player
- Ceiling collapse triggers when time runs out
- Debris falls dynamically across the map

---

## Controls

- W / A / S / D — Move  
- Space — Jump  
- C — Toggle Cheat Mode  
- R — Restart  

---

## Technologies Used

### Language
- Python

### Libraries
- OpenGL.GL  
- OpenGL.GLU  
- OpenGL.GLUT  
- math, time, random  

---

## How to Run

1. Install Python (3.8+ recommended)

```bash
pip install PyOpenGL PyOpenGL_accelerate
```

2. Run the game:

```bash
python main.py
```

(Replace `main.py` with your actual filename.)

---

## Game Rules

### Winning
- Collect treasures
- Stay alive
- Manage time carefully

### Losing
- Health reaches zero
- Time runs out
- Hit by too many falling obstacles

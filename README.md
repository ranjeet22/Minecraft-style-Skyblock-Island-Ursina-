# 🧱 Minecraft-style Skyblock Island (Ursina)

A fun, lightweight 3D **Skyblock island simulation** made using the **Ursina Engine** in Python!  
Inspired by the Minecraft Skyblock concept, this project includes basic block placement/destruction mechanics and a free-moving first-person controller.

---

## 🎮 Game Overview

This game lets you:
- Explore a floating island made of voxel blocks
- Interact with the world using block-building and destruction
- Walk around using simple first-person controls
- Switch between different block types (Grass, Stone, Brick, Dirt)

---

## 🕹 Controls

| Key                | Action                        |
|--------------------|-------------------------------|
| `W`, `A`, `S`, `D` | Move forward, left, backward, right |
| `Space`            | Jump                          |
| `Mouse Movement`   | Look around                   |
| `Left Click`       | Place selected block          |
| `Right Click`      | Destroy targeted block        |
| `1`                | Select **Grass Block**        |
| `2`                | Select **Stone Block**        |
| `3`                | Select **Brick Block**        |
| `4`                | Select **Dirt Block**         |
| `Esc`              | Quit Game                     |

---

## 🛠️ Technologies Used

- **Python 3**
- **Ursina Engine**
- **Custom Assets** (Textures and Sounds)

---

## 📂 Project Structure
```
/assets
├── grass_block.png
├── stone_block.png
├── brick_block.png
├── dirt_block.png
├── skybox.png
├── arm_texture.png
├── block.obj
└── punch_sound.wav
```
> Make sure all asset files are correctly placed in the `assets/` directory.

---

## 📦 How to Run

1. **Install Python (if not already):**  
   [Download Python](https://www.python.org/downloads/)

2. **Install Ursina Engine:**

   ```bash
   pip install ursina

3. **Run the game:**
   
   ```bash
   python main.py

---

## 🌤 Features

- First-person camera movement  
- Block-based world generation  
- Add or destroy blocks interactively  
- Punch sound effect when placing/removing blocks  
- Simple hand animation for immersive gameplay  

---

## 🚧 Future Improvements

- Add more block types (wood, water, lava, etc.)  
- Save/load island states  
- Add basic mobs or animations  
- Expand to survival gameplay  

---

## 🙋‍♂️ Author

Made with ❤️ by a beginner exploring 3D game development using Python.  

> “Every big game starts with a small block!”


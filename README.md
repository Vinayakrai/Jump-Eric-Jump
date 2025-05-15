# 🕺 Jump Eric Jump

An energetic **3D jumping game** built with **Three.js**, where a vibrant green stick-figure hero(Eric) leaps across a sunset-lit cityscape on zig-zag platforms. Includes stylish mid-air jumps, idle dancing, and satisfying confetti explosions upon victory!

---

## 🌟 Features

- 🟩 **Green Stick Hero**: Fully animated with legs, arms, and head
- 🌇 **Sunset Background**: Gradient sky and fog for mood lighting
- 🏙️ **Dynamic Cityscape**: Randomized buildings create urban depth
- 🧱 **Zig-Zag Planks**: Narrow paths that test your timing and direction
- 🪂 **Mid-Air Jumping**: One extra jump allowed while airborne
- 🎊 **Confetti Celebration**: Sprays when you reach the final platform
- 💃 **Victory Dance**: Player breaks into an animated celebration
- 🔁 **Play Again**: Instant restart with button click

---

## 🕹 Controls

| Key           | Action                     |
|---------------|----------------------------|
| ⬆️ Arrow Up    | Jump forward               |
| ⬅️ Arrow Left  | Jump diagonally left       |
| ➡️ Arrow Right | Jump diagonally right      |

- You are allowed **one mid-air jump**.
- Land precisely on narrow planks to progress.
- Falling off resets your position.

---

## 📸 Visuals

| Element        | Style                     |
|----------------|---------------------------|
| 🎨 Scene        | Orange-pink sunset theme  |
| 🧍‍♂️ Hero        | Bright green stickman     |
| 🧱 Platforms    | 3D planks & blocks        |
| 🎉 Confetti     | Metallic gold and silver  |
| 💡 Lighting     | Hemisphere + directional  |

---

## 🔧 Tech Stack

| Tool/Library | Purpose                        |
|--------------|---------------------------------|
| Three.js     | 3D rendering and scene control  |
| JavaScript   | Game logic and animation        |
| HTML + CSS   | Layout and interface styling    |

---

## 📂 Project Structure

| Component       | Role                                      |
|------------------|---------------------------------------------|
| `createStickFigure()` | Builds the animated green player figure |
| `onKeyDown()`    | Handles jump input                          |
| `animate()`      | Core game loop: physics, motion, win state  |
| `startDance()`   | Triggers win animation and confetti         |
| `spawnConfetto()`| Adds falling confetti                       |
| `resetGame()`    | Restarts the game                           |

---

## 🧠 Game Logic

- Each jump follows a parabolic arc based on gravity.
- Collision checks with platforms allow landing detection.
- Jump count ensures one mid-air action only.
- Goal platform triggers state change to "dancing."

---

## ✅ How to Play

1. Open the HTML file in a browser.
2. Press Arrow keys to jump between platforms.
3. Reach the final block to win!
4. Click **Play Again** to restart.

---

## 🧑‍💻 Author

Built with creativity and physics by **Vinayak Rai**  
🔥 Combining fun mechanics with visual polish using pure JS & Three.js.

---

## 🪪 License

Open-source and free to use for learning and personal fun!

---


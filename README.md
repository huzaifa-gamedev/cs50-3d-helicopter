# 🚁 CS50 — Helicopter Game 3D

[![Unity](https://img.shields.io/badge/Engine-Unity-black)](https://unity.com/)
[![Language](https://img.shields.io/badge/Language-C%23-blue)](https://learn.microsoft.com/en-us/dotnet/csharp/)
[![Course](https://img.shields.io/badge/Course-CS50G-red)](https://cs50.harvard.edu/games/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

**Course:** [CS50's Introduction to Game Development](https://cs50.harvard.edu/games/)  
**Assignment:** Helicopter Game 3D  
**Engine / Language:** Unity / C#

---

## 📋 Project Overview

This repository contains my implementation of the **Helicopter Game 3D** assignment from CS50's Introduction to Game Development.

The project is a 3D endless-runner-style game in which the player controls a helicopter while avoiding obstacles, collecting coins, and progressing through an increasingly fast-moving environment.

For this assignment, I extended the provided CS50 source code by implementing **Gems** as a new collectible and fixing the game-speed reset bug that occurs when restarting the game.

📺 You can also watch the gameplay on [YouTube](https://youtu.be/NLHnCM--vq0?si=ifd7cNz0nh4x9NT8).

---

## ✨ What I Implemented

### 💎 Gems

- ✔️ Added a new **Gem** collectible to the game.
- ✔️ Added a dedicated **GemSpawner** system.
- ✔️ Gems spawn similarly to Coins.
- ✔️ Gems have a lower spawn frequency than Coins.
- ✔️ Each collected Gem awards **5 coins**.
- ✔️ Gems automatically move from right to left with the game environment.
- ✔️ Gems despawn after moving past the left edge of the screen.
- ✔️ Added a Gem prefab using the available 3D model.

### 🔄 Game Speed Reset Fix

- ✔️ Fixed the bug where the scrolling speed was not reset after restarting the game.
- ✔️ Ensured that planes, Coins, and buildings return to their original scrolling speed when the game is restarted using the **Space Bar**.
- ✔️ Addressed the issue caused by the speed value being stored in a static variable that persists when the scene is reloaded.

---

## 🎬 Gameplay Preview

![Gameplay Preview](docs/gameplay.gif)

---

## 🚀 How to Run

### Prerequisites

You will need:

- [Unity](https://unity.com/)
- **Unity 2018.4.28f1** or another compatible version for the original CS50 project.
- [Blender 2.79](https://www.blender.org/) if you need to reimport or modify the provided 3D models.

> **Note:** The original CS50 assignment was designed around older versions of Unity and Blender. For the best compatibility with the original source code, use the versions recommended by the course.

### Clone the Repository

```bash
git clone https://github.com/huzaifa-gamedev/cs50-3d-helicopter.git
cd cs50-3d-helicopter
```

### Open the Project

1. Open **Unity Hub**.
2. Select **Open**.
3. Browse to the cloned project directory.
4. Open the project using a compatible Unity version.
5. Navigate to:

```text
Assets/Resources/Scenes
```

6. Open the **Main** scene.
7. Press the **Play** button in Unity.

---

## 🎮 Controls

- **Space Bar** — Start / Restart the game
- **Space Bar** — Control the helicopter
- **Escape** — Quit the game

---

## 🕹️ Gameplay Mechanics

The game contains several gameplay elements:

### 🚁 Helicopter

The player controls a helicopter that must navigate through the environment while avoiding obstacles.

### 💰 Coins

Coins spawn throughout the level and can be collected by the player to increase the score.

### 💎 Gems

Gems are a rarer collectible introduced as part of this assignment.

Each Gem:

- Is less common than a Coin.
- Awards **5 coins** when collected.
- Moves from right to left with the environment.
- Despawns after leaving the playable area.

### 🏢 Buildings

Buildings continuously move through the environment to create the scrolling effect of the game.

### ✈️ Airplanes

Airplanes act as moving obstacles and travel through the environment alongside the other scrolling objects.

---

## 🛠️ Technologies Used

- **Unity**
- **C#**
- **Blender**
- **Unity Prefabs**
- **Unity Scene Management**
- **Unity GameObjects & Components**
- **CS50 Game Development Framework**

---

## ✨ Credits

- Original skeleton code, assets, and assignment: **CS50's Introduction to Game Development (Harvard University)**
- Original course: [CS50's Introduction to Game Development](https://cs50.harvard.edu/games/)
- 3D models and starter assets provided through the original CS50 project.

---

## 📄 License

- This implementation: © 2025 Muhammad Huzaifa Karim. Licensed under the [MIT License](LICENSE).  

For more details, see [ATTRIBUTION.md](ATTRIBUTION.md).  

---

## ✍️ Author

**Muhammad Huzaifa Karim**

[GitHub Profile](https://github.com/huzaifakarim1)

---

## 📬 Contact

For ideas, feedback, or collaboration, feel free to reach out via [GitHub](https://github.com/huzaifakarim1).

---

© 2025 Muhammad Huzaifa Karim. All rights reserved.

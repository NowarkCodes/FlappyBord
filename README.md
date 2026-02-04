# 🐦 FlappyBord

![Unity](https://img.shields.io/badge/Unity-2021%2B-000000?style=for-the-badge&logo=unity)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp)
![Platform](https://img.shields.io/badge/Platform-Windows-0078D6?style=for-the-badge&logo=windows)

A classic arcade-style endless runner game inspired by the legendary Flappy Bird. Built with **Unity** and **C#**, this project recreates the challenging mechanics of navigating a bird through infinite pipe obstacles.

---

## 🎮 Game Overview

**FlappyBord** is a test of reflexes and patience. The goal is simple: keep the bird flying without hitting the pipes or the ground.

* **Genre**: Endless Runner / Arcade
* **Engine**: Unity
* **Platform**: Windows (x64)

---

## 🚀 How to Play

### Controls
* **Jump / Fly**: Press `Spacebar` or `Left Mouse Button`.
* **Objective**: Fly through the gaps between the pipes to score points.

### Running the Game
No installation is required. You can play the game directly from the build folder.

1.  **Download** the repository or the latest release.
2.  Navigate to the game folder:
    ```
    FlappyBord/Basic Flappy Bird-fd15798a964143b07892ae0e30936845b4bef472/
    ```
3.  Double-click **`Basic Flappy Bird.exe`** to launch the game.

---

## 📂 Project Structure

This repository contains the built binaries for the game.

```bash
FlappyBord/
├── Basic Flappy Bird.exe         # Main Game Executable
├── Basic Flappy Bird_Data/       # Game assets and resources
│   ├── app.info                  # Configuration file
│   └── Managed/                  # C# Assemblies (Game Logic)
├── UnityPlayer.dll               # Unity Engine Core
├── UnityCrashHandler64.exe       # Error handling tool
└── MonoBleedingEdge/             # Mono Runtime

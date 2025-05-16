# Apple Picker - Unity Game

## Author
Nathan Shorez

---

## Project Overview
Apple Picker is a Unity game where players control a basket to catch falling apples. The objective is to catch as many apples as possible while avoiding rotten apples. The game features dynamic spawning, scoring, and material effects.

---

## Key Components
- **Gameplay Logic:** C# scripts manage apple spawning, basket movement, and scoring.
- **Materials and Objects:** Custom materials for apples, baskets, and background.
- **Scenes:** Main game scene with interactive objects and UI elements.

---

## Dependencies
- Unity 2021 or later
- TextMesh Pro (included in Unity package)
- Visual Studio or another C# editor

---

## Project Structure
```
ApplePicker/
│── Assets/
│   ├── Mat/          # Materials
│   ├── Objects/      # Game objects
│   ├── Scenes/       # Game scenes
│   └── Scripts/      # C# scripts for game logic
│── ProjectSettings/
│── .gitignore
│── README.md
```

---

## Running the Game
1. **Open the Project in Unity:**
   - Open Unity Hub and select the project folder.

2. **Open the Main Scene:**
   - Navigate to `Assets/Scenes/` and open the main game scene.

3. **Play the Game:**
   - Click the Play button in the Unity Editor to start the game.

---

## Building the Game
1. **Go to `File > Build Settings`:**
   - Select the target platform (e.g., Windows, Mac, WebGL).

2. **Add Open Scenes:**
   - Ensure the main scene is added to the build list.

3. **Click `Build and Run`:**
   - Choose a build directory and wait for the game to compile.

---

## Future Enhancements
- Implement power-ups and bonus items.
- Add difficulty levels and timed challenges.
- Integrate a scoring leaderboard.

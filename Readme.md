# Zombie Shmup!

## 1. Game Overview
**Name**: Zombie Shmup!

### Mechanics
- **Round-Based Gameplay**: Players face waves of increasingly difficult zombie enemies in a large post-apocalyptic city.
- **Points System**: Players earn points for dealing damage to zombies and defeating them. Points can be spent to unlock new areas of the city.
- **Power-Ups**: Players can collect power-ups that double their health, increase their damage output, etc.
- **Weapon Variety**: Players can use semi-automatic or fully automatic rifles, handguns, or shotguns.

### Aesthetic
- **Setting**: A ravaged post-apocalyptic city filled with explorable shops and defense emplacements.
- **Visual Style**: A silly, cartoony art style with a focus on exaggeration to exclude explicit details. The zombies are grotesque, with appearances like citizens of the city.
- **Audio**: The game features simple royalty-free music and sound effects to ensure no copyright violations occur.

### Narrative
- **Story**: Players awaken in a post-apocalyptic city that was ground zero for a zombie outbreak. To survive, they must unlock different sections of the city and uncover the mystery behind the outbreak. The narrative unfolds through environmental storytelling, with scattered notes and ominous audio logs from the doomed citizens.

## 2. Technology
- **Language**: C# for core game mechanics, including enemy behavior, player actions, and wave management.
- **Game Engine**: Unity
- **Key Classes**:
  - `WaveManager`: Handles enemy waves, spawning, and round progression.
  - `ZoneManager`: Manages accessible zones and ensures enemies spawn in areas players can reach.
  - `ScoreManager`: Tracks player points, handles multipliers, and manages points awarded for hits and kills.
  - `Enemy` and `Player`: Implement damage interfaces and handle interactions like dealing and taking damage.

## 3. Project Timeline & Plan
Based on previous experience making a similar game in Unreal Engine, along with the FPS microgame project that comes with Unity, I believe I have the experience and solutions to bring this project to life in Unity. 
### Week 1
- Set up the project and establish a basic game loop.
- Implement core classes (`WaveManager`, `ZoneManager`, `ScoreManager`) with simple functionality.
- Create a basic player character with shooting and movement mechanics.

### Week 2
- Develop the enemy behavior and implement zombie spawning in waves.
- Add the points system and scoring logic, including multipliers for consecutive hits.
- Set up zones within the and integrate `ZoneManager` to handle accessible areas.

### Week 3
- Implement power-ups and ensure they interact correctly with enemies.
- Polish the user interface and add audio cues to enhance immersion.
- Playtest and debug the game, making adjustments to balance and performance as needed.

### Strategy for Success
- **Modular Design**: The game is designed with modular classes to simplify implementation and debugging.
- **Scope Management**: By focusing on a single environment (the city) and limiting the number of features, development can stay on schedule.
- **Early Playtesting**: Conducting playtests early will help identify and fix any major issues, ensuring a smoother final product.

# Duck Game - A 2D Multiplayer Platformer

<div align="center">
  <img src="https://i.postimg.cc/NfY181Z2/Screenshot-2025-07-11-132153.png" width="">
</div>

<div align="center">
    <a href="https://isocpp.org/">
        <img src="https://img.shields.io/badge/Made%20with-C%2B%2B-FE6E06">
    </a>
    <a href="https://www.sfml-dev.org/">
        <img src="https://img.shields.io/badge/Graphics%20Made%20with-SFML-8cc445">
    </a>
    <a href="https://github.com/">
        <img src="https://img.shields.io/badge/Platform-Windows-blue">
    </a>
</div>

## 🎮 About

Duck Game is a fast-paced 2D multiplayer platformer where two players control ducks and battle it out across multiple maps. The first player to reach 10 points wins! Pick up weapons, jump around platforms, and eliminate your opponent in this action-packed local multiplayer game.

This project was developed as a collaborative effort by a college team, combining game development skills and teamwork to create an engaging multiplayer experience.

## ✨ Features

### Gameplay
- **Local Multiplayer**: Two-player competitive gameplay on the same screen
- **Multiple Weapons**: Choose from various weapons including:
  - 🗡️ Sword (melee combat)
  - 🔫 Pistol (rapid fire)
  - 🎯 Sniper (long-range precision)
  - ⚡ Laser Gun (energy-based)
  - 💣 Grenade (explosive area damage)
- **Weapon System**: Pick up weapons from the ground, hold and fire with customizable controls
- **Physics-Based Movement**: Jump, run, and navigate through platformer mechanics
- **Multiple Maps**: Battle across 6 different maps with unique layouts and obstacles
- **Scoring System**: First to 10 points wins the match
- **Tile-Based Level Design**: Customizable maps with various tile types (Ground, Cement, Tree, Stone, Branch, etc.)

### Technical Features
- **SFML Graphics**: Smooth 2D sprite-based rendering
- **Audio System**: Sound effects for weapons, explosions, and character actions
- **Menu System**: Complete UI with main menu, settings, pause menu, and end screen
- **Custom Vector Implementation**: Optimized data structures for game objects
- **Collision Detection**: Precise collision handling for platforms, weapons, and bullets

## 🎯 Controls

### Player 1 (Duck 1)
- **W** - Jump
- **A** - Move Left
- **D** - Move Right
- **C** - Hold/Pick Up Weapon
- **V** - Fire Weapon

### Player 2 (Duck 2)
- **↑** - Jump
- **←** - Move Left
- **→** - Move Right
- **K** - Hold/Pick Up Weapon
- **L** - Fire Weapon

## 🛠️ Technologies Used

- **C++**: Core programming language
- **SFML 2.x**: Graphics, audio, window management, and networking libraries
- **Visual Studio**: Development environment (`.vcxproj` project files included)

## 📁 Project Structure

```
Duck_Game/
├── main.cpp          # Main game loop and initialization
├── Game.h            # Game state management
├── Logic.h            # Game logic, physics, and mechanics
├── MainMenu.h         # Menu system implementation
├── GameTile.h         # Tile system for level design
├── img/               # Game assets (sprites, textures, sounds)
├── External/          # External libraries (SFML)
├── Debug/             # Build output directory
└── Temp/              # Visual Studio project files
```

## 🎨 Assets

The game includes various assets in the `img/` directory:
- Character sprites (ducks, arms)
- Weapon sprites (pistol, sniper, laser, grenade, sword)
- Tile textures (ground, cement, stone, tree, branches)
- Background images
- Sound effects (gunshots, explosions, quacks)
- UI elements (menus, avatars)

## 🤝 Contributing

This project was developed with a college team.
---

**Enjoy the game and may the best duck win! 🦆**

# Collision Detection with Coin

## Overview

This project demonstrates a simple 3D scene using Three.js where a player-controlled cube can move around, jump, and collect a coin while avoiding enemy cubes. The coin rotates and disappears when collected, and the player can track the number of collected coins. Enemies spawn at regular intervals and move towards the player.

## Features

- **Player-Controlled Cube**: Move with `W`, `A`, `S`, `D` keys and jump with `Space`.
- **Rotating Coin**: Collect the coin to increase the score.
- **Enemy Spawning**: Enemies spawn and move towards the player.
- **Collision Detection**: Detect collisions between the player and the ground, coin, and enemies.

## Getting Started

### Prerequisites

- A modern web browser with JavaScript enabled.

### Installation

1. **Download or clone the repository.**
2. **Open `index.html` in your web browser.**

### Usage

- **Movement**: Use `W`, `A`, `S`, `D` keys to move the cube.
- **Jump**: Press `Space` to make the cube jump.
- **Collect Coin**: Move the cube into the rotating coin to collect it and increase the coin count.
- **Avoid Enemies**: Avoid colliding with the enemies, or the game will stop.

### Code Explanation

- **Scene Setup**: Creates a scene, camera, and renderer using Three.js.
- **Box Class**: Represents a cube with properties like velocity, position, and dimensions. It includes methods for updating its position and applying gravity.
- **Coin Class**: Inherits from `Box` but uses a cylinder geometry to represent a coin.
- **Collision Detection**: Checks for collisions between boxes (player, ground, enemies, and coin).
- **Event Listeners**: Listens for keydown and keyup events to control the player's movement.
- **Animation Loop**: Updates the scene, moves the player, spawns enemies, and checks for collisions.

### Notes

- The coin rotates and disappears when collected, increasing the coin count.
- Enemies continuously spawn at intervals, moving towards the player.
- The game stops if the player collides with an enemy.

### Future Improvements

- Add more levels and challenges.
- Introduce new enemy types and power-ups.
- Implement a scoring system and UI elements.

---

Feel free to modify the code to add more features or improve existing ones. Enjoy building and exploring with Three.js!

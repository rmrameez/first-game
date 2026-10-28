# 🗡️ First Game

My **very first game**: a small 2D pixel-art platformer made with **Godot 4**.

You play as a little knight. Run and jump across grassy hills, stone blocks and floating platforms, and try not to fall off the map.

> This project is how I'm learning game development: movement, physics, tilemaps, cameras and scenes. It's simple, but it's mine, and it's only the start. 🎮

---

## ✨ Features

- 🏃 Smooth left/right movement and jumping, with gravity
- 🧱 Level built from a tile-based world (TileMapLayer)
- 🎥 A camera that follows the player
- 🎨 Pixel-art characters, coins, fruit and slimes
- 🎵 Music and sound effects

## 🎮 Controls

| Action     | Key                 |
|------------|---------------------|
| Move left  | ← Left Arrow        |
| Move right | → Right Arrow       |
| Jump       | Space / Enter       |

## 🛠️ Built With

- [Godot Engine 4.7](https://godotengine.org/) (.NET edition)
- GDScript / C#

## 🚀 How to Run

1. Install [Godot 4.x](https://godotengine.org/download) (.NET version if you use the C# scripts).
2. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   ```
3. Open Godot, click **Import**, and select the `project.godot` file.
4. Press **F5** to play.

## 📁 Project Structure

```
assets/
  fonts/      # Game fonts
  music/      # Background music
  sounds/     # Sound effects
  sprites/    # Knight, slimes, coins, fruit, tileset
scenes/
  game.tscn   # Main level
  player.tscn # Player character
scripts/
  player.gd   # Player movement and jumping
```

## 🗺️ What's Next

- [ ] Collectible coins with a score counter
- [ ] Enemies (slimes!) that can defeat the player
- [ ] Death zone and respawn
- [ ] More levels
- [ ] Start menu and game-over screen

## 🙏 Credits

- Art and audio assets: *<asset pack name and author>*
- Made with ❤️ using Godot Engine

---

⭐ This is my first game, so if you like it, a star would mean a lot! Feedback and tips are always welcome.

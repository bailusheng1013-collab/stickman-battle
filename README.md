# Stickman Battle

A fast-paced browser fighting game where customizable stickmen battle across floating platforms while avoiding lava, asteroids, explosions, and other hazards.

## Features

* 🥊 Fast stickman combat
* 🔫 Multiple weapons:

  * Uzi
  * Sword
  * Bat
  * Spear
  * Bow
  * Gatling gun
  * Bomb
  * Nuke
* 🛡️ Armor pickups:

  * Light
  * Medium
  * Heavy
* ⚡ Super Ray attack
* 🌀 Aerial 3-hit combo
* ☄️ Falling asteroid events
* 🌋 Rising lava
* 🔥 Volcano fireballs
* ☢️ Nuclear radiation clouds
* 💥 Explosions and destructible platforms
* 🎨 Character creator
* 📊 Customizable character stats
* 🌈 Multiple character colors
* 📏 Small, Medium, and Large character sizes
* 🗺️ Five different worlds
* 🤖 CPU opponents
* 👥 Local 2-player multiplayer
* 🔊 Procedurally generated sound effects
* 📺 Full-screen browser support

## Worlds

The game currently includes five stages:

1. **Meadow**
2. **Desert**
3. **Night City**
4. **Volcano**
5. **Snow Peak**

Each world has its own visual theme, while the Volcano stage also features falling fireballs.

## Game Modes

* **1 vs 1 CPU**
* **1 vs 2 CPUs**
* **1 vs 3 CPUs**
* **Multiplayer (2P)**

## Character Creator

Before fighting, you can customize your character.

### Customization

* Character name
* Preset color
* Custom RGB color
* Character size
* Health
* Speed
* Damage
* Jump

You have **20 total stat points** to distribute between Health, Speed, Damage, and Jump.

### Character Sizes

| Size   | Description    |
| ------ | -------------- |
| Small  | Fast & Fragile |
| Medium | Balanced       |
| Large  | Slow & Tanky   |

## Controls

### Player 1

| Key     | Action                         |
| ------- | ------------------------------ |
| `A`     | Move left                      |
| `D`     | Move right                     |
| `W`     | Jump                           |
| `F`     | Punch / Use weapon             |
| `G`     | Kick                           |
| `Q`     | Aerial combo                   |
| `SPACE` | Super Ray                      |
| `R`     | Change character after a match |
| `ESC`   | Quit                           |

### Menus

| Key       | Action           |
| --------- | ---------------- |
| `W` / `S` | Navigate         |
| `↑` / `↓` | Navigate         |
| `A` / `D` | Change selection |
| `F`       | Confirm          |
| `K`       | Confirm          |
| `Enter`   | Confirm          |
| `Space`   | Confirm          |

During character creation:

* Type letters to change your name
* `Backspace` deletes characters
* `Q` / `E` switches RGB channels
* `A` / `D` adjusts selected values

## Combat

Every fighter starts with basic melee attacks.

### Punch

A quick close-range attack that deals damage and builds Super charge.

### Kick

A stronger close-range attack with greater range than a punch.

### Weapons

Weapons can appear on platforms throughout the battle.

Ranged weapons use ammunition and can require reloading. Weapons also have limited durability.

### Super Ray

When the Super meter reaches 100%, the fighter can unleash a powerful energy beam.

The Super meter charges through:

* Punches
* Kicks
* Projectile attacks
* Aerial combo hits

## Hazards

The arena isn't safe.

### Rising Lava

Lava periodically rises, forcing fighters to climb to higher platforms.

### Asteroids

Asteroids fall from above and can damage fighters.

Large asteroids can also destroy nearby platforms.

### Fireballs

The Volcano stage periodically launches falling fireballs.

### Explosions

Bombs and other explosive weapons can damage fighters and destroy platforms.

### Nuclear Radiation

The Nuke creates a large explosion followed by a toxic radiation cloud that continues damaging fighters inside it.

## Platforms

The game uses floating platforms instead of relying on a traditional solid floor.

Platforms are generated dynamically throughout the battle. As the lava rises, additional platforms can be generated to keep the fight moving upward.

## Winning

The last fighter with health remaining wins the round.

The winner's win counter increases after a victory.

If all fighters are eliminated, the match ends in a draw.

After the match:

* Press `R` to change your character.
* Press `R` twice to change the game mode.
* Press `ESC` to quit.

## Running the Game

This is a browser-based HTML/JavaScript game.

### Quick Start

1. Save the game as an `.html` file.
2. Open the HTML file in a modern web browser.
3. Click the game screen or press any key to start.
4. Choose a game mode.
5. Customize your character.
6. Choose a weapon.
7. Choose a world.
8. Fight!

For the best experience, use a modern browser such as Chrome, Edge, Firefox, or Safari.

## Technology

The game is built using:

* **HTML5**
* **JavaScript**
* **HTML Canvas**
* **Web Audio API**

No external game engine is required.

## Credits

**Stickman Battle**

A browser-based stickman fighting game featuring platform combat, weapons, character customization, hazards, explosions, and arcade-style action.

Have fun fighting! ⚔️

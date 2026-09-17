# Super Mario

A small Mario-inspired platformer I made using plain HTML, CSS and JavaScript.

This was made as part of a **Hack Club event** and was mainly a fun project to experiment with game development in the browser.

## 🎮 Play

**Project:** [link-pack.xyz](https://link-pack.xyz)

**Hack Club:** [hackclub.com](https://hackclub.com/)

## How to play

Use the **arrow keys** to move around:

* `←` Move left
* `→` Move right
* `↑` Jump

You start with **3 lives** and **100 seconds** to finish the game.

### Scoring

* 🪙 Collecting a coin: **+50 points**
* 👾 Jumping on an enemy: **+100 points**
* Getting hit by an enemy costs a life.
* Falling off the platforms also costs a life.

There is also background music and a coin sound effect. You can toggle the music using the button in the game.

## 🛠️ Built with

Nothing fancy here:

* HTML
* CSS
* JavaScript
* HTML Canvas
* A few image and audio assets

The actual game is rendered on a `<canvas>` and most of the gameplay logic lives in `script.js`.

## 📁 Files

```text
.
├── index.html       # Starting / instructions screen
├── mario.html       # Game page
├── script.js        # Game logic
├── style.css        # Game styling
├── images/          # Sprites and background
├── audio/           # Music and sound effects
└── .gitignore
```

The starting screen gives the controls and basic rules before loading the game.

## ✨ Features

* Platform-based movement
* Jumping and gravity
* Coins and scoring
* Enemies
* Lives system
* 100-second timer
* Background music
* Sound effect when collecting coins
* Game-over screen
* Long scrolling level with multiple platforms

## Why I made this

Honestly, I just wanted to make a playable browser game instead of another normal website.

It was also a good excuse to mess around with Canvas, collision detection, animation, keyboard controls and basic game physics.

There are definitely things I would change and improve in the code, but that's part of the fun of making these projects.

## Credits

Made for a **Hack Club event**.

Inspired by the classic Super Mario games.

Please don't treat this as an official Nintendo project — it's just a fan-made experiment.

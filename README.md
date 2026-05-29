# 🐍 Learn & Slither!

**A free, browser-based preschool learning game by [NeumanGames™](https://github.com/NeumanGames)**

> Guide your snake around the board to collect numbers, letters, or shapes **in the correct order** — and watch your snake grow into a colorful, learning-filled trail!

[![Play Now](https://img.shields.io/badge/🎮%20Play%20Now-Learn%20%26%20Slither-22c55e?style=for-the-badge)](https://snakegame.neumangames.com)
[![Ko-fi](https://img.shields.io/badge/☕%20Support-Ko--fi-ff5e5b?style=for-the-badge)](https://ko-fi.com/neumangames)
[![Patreon](https://img.shields.io/badge/🎨%20Support-Patreon-ff424d?style=for-the-badge)](https://patreon.com/NeumanGames)

-----

## 🌟 About

Learn & Slither is a **free, no-install, no-account** educational game designed for preschool and early elementary students. It combines the classic snake game with number, letter, and shape recognition to reinforce foundational learning skills in a fun, engaging way.

Built with love by **Tom & Shia Neuman** — a tech dad and an elementary school teacher — as part of the [NeumanGames™](https://github.com/NeumanGames) family of free educational games.

-----

## 🎮 How to Play

1. **Choose a game mode** — Numbers, Letters, or Shapes
1. **Configure your settings** — range, case, board size, speed, and control layout
1. **Press Play!**
1. **Steer your snake** toward the **correct next item** in the sequence (shown in the gold “Catch!” box at the top)
1. **Collect the right item** → your snake grows and earns **+10 points**
1. **Collect the wrong item** → your snake shrinks and loses **−5 points**
1. If your snake gets too small → **Game Over!**

The snake’s body fills up with the items you’ve collected, reading **in order from head to tail** — so you can see the sequence building right on the snake itself!

-----

## 📚 Game Modes

### 🔢 Numbers

Count your way through a number sequence. The snake collects numbers in order and repeats the series when complete.

|Range|Sequence               |
|-----|-----------------------|
|1–5  |1, 2, 3, 4, 5, 1, 2, 3…|
|1–10 |1 through 10, repeating|
|1–20 |1 through 20, repeating|

### 🔤 Letters

Work through the alphabet at your own pace.

|Range|Case Options                  |
|-----|------------------------------|
|A–E  |UPPERCASE, lowercase, or Mixed|
|A–J  |                              |
|A–M  |                              |
|A–Z  |                              |

### 🔷 Shapes

Identify and collect shapes in sequence. The snake body shows the **actual shapes**, not just labels.

|Range   |Shapes Included                  |
|--------|---------------------------------|
|4 Shapes|Circle, Triangle, Square, Diamond|
|6 Shapes|+ Star, Heart                    |
|8 Shapes|+ Pentagon, Hexagon              |

-----

## ⚙️ Settings

|Setting    |Options                                                              |Description                                               |
|-----------|---------------------------------------------------------------------|----------------------------------------------------------|
|**Board**  |🐣 Tiny (10×10) · 🐥 Small (15×15) · 🐤 Medium (20×20) · 🐦 Large (28×22)|Larger cells are easier for younger children              |
|**Speed**  |🐌 Tiny · 🐢 Slow · 🐇 Medium · 🦊 Fast · ⚡ Zoom                         |From ~720 ms/step down to ~90 ms/step                     |
|**D-Pad**  |◀ Left · ◀▶ Both · ▶ Right · 👆 Swipe                                 |Position of the directional pad, or enable swipe-only mode|
|**Buttons**|◀ Left · ◀▶ Both · ▶ Right · 🚫 Hide                                  |Position of Pause and Menu buttons                        |
|**Music**  |🎵 / 🔊                                                                |Toggle background music on/off (header button)            |

-----

## 🕹️ Controls

|Input                    |Action                                    |
|-------------------------|------------------------------------------|
|**Arrow Keys** / **WASD**|Steer the snake                           |
|**Spacebar**             |Pause / Resume                            |
|**On-screen D-Pad**      |Tap directional buttons                   |
|**Swipe** (touch)        |Swipe on the canvas or swipe zone to steer|


> **Tip for tablets & touch screens:** Set D-Pad to **👆 Swipe** for a clean, full-screen experience with no buttons in the way.

-----

## 🎵 Music

Five cheerful background tracks play in random order (never repeating back-to-back):

1. 🌟 **Twinkle** — gentle nursery melody
1. 🥁 **March** — bouncy staccato march
1. 💤 **Waltz** — slow dreamy 3/4 lullaby
1. 🎪 **Skip** — playful square-wave tune
1. ✨ **Dreamy** — flowing arpeggios

All music is generated in real-time using the **Web Audio API** — no audio files to download.

-----

## 🛠️ Tech Stack

|Technology                                 |Usage                            |
|-------------------------------------------|---------------------------------|
|**HTML5 Canvas**                           |Game rendering                   |
|**Vanilla JavaScript**                     |All game logic                   |
|**Web Audio API**                          |Procedural music & sound effects |
|**CSS3**                                   |Responsive layout, animations, UI|
|Google Fonts (**Fredoka One** + **Nunito**)|Typography                       |

No frameworks. No dependencies. No build step. Just open `index.html` in any modern browser.

-----

## 🚀 Getting Started

### Play online

👉 **[snakegame.neumangames.com](https://snakegame.neumangames.com)**

### Run locally

```bash
git clone https://github.com/NeumanGames/SnakeGame.git
cd SnakeGame
# Open index.html in your browser — no server required
open index.html
```

That’s it. No `npm install`. No build tools. Just a single HTML file.

-----

## 📁 Project Structure

```
learn-slither/
├── index.html      # The entire game — HTML, CSS, and JS in one file
└── README.md       # This file
```

-----

## 🤝 Contributing

Contributions, bug reports, and feature ideas are warmly welcome!

1. **Fork** the repository
1. **Create** a feature branch (`git checkout -b feature/my-idea`)
1. **Commit** your changes (`git commit -m 'Add my idea'`)
1. **Push** to the branch (`git push origin feature/my-idea`)
1. **Open a Pull Request**

### Ideas for future features

- [ ] High score persistence (localStorage)
- [ ] Additional languages / character sets
- [ ] Counting mode (show dots/objects to count)
- [ ] Parent/teacher settings lock
- [ ] Accessibility improvements (larger text mode, high-contrast theme)
- [ ] Sound effects toggle separate from music

-----

## 💛 Support the Project

Learn & Slither is completely **free** and will always stay that way. If it’s been useful in your classroom or at home, consider supporting continued development:

|Platform     |Link                                                      |
|-------------|----------------------------------------------------------|
|☕ **Ko-fi**  |[ko-fi.com/neumangames](https://ko-fi.com/neumangames)    |
|🎨 **Patreon**|[patreon.com/NeumanGames](https://patreon.com/NeumanGames)|
|🐙 **GitHub** |[github.com/NeumanGames](https://github.com/NeumanGames)  |

-----

## 🎓 Also by NeumanGames™

|Game                                                     |Description                                              |
|---------------------------------------------------------|---------------------------------------------------------|
|🗺️ **[USA Explorer](https://usaexplorer.neumangames.com)**|Free interactive US geography quiz — learn all 50 states!|

-----

## 📄 License

© 2024–2025 **NeumanGames™**. All rights reserved.

This project is free to use for personal and educational purposes.  
Please do not redistribute or resell without permission.

-----

<div align="center">
  Made with ❤️ by <strong>Tom &amp; Shia Neuman</strong><br>
  <em>A tech dad and an elementary school teacher, making learning fun — one game at a time.</em>
</div>
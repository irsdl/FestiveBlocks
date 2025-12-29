# 🎄 Festive Blocks 🎮

A festive Christmas-themed Tetris game with 3D blocks, power-ups, and holiday cheer! Built as a single HTML file that runs entirely in the browser.

🎮 **[Play Now!](https://irsdl.github.io/FestiveBlocks/)** 🎮

![Festive Blocks](https://img.shields.io/badge/Game-Festive%20Blocks-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-Canvas-orange)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow)
![License](https://img.shields.io/badge/License-AGPL--3.0-blue)

## ✨ Features

- 🎨 **Beautiful 3D Blocks** - Beveled, glossy blocks with Christmas-themed emojis
- 🎁 **6 Power-ups** - Special abilities that appear every few pieces
- 👻 **Ghost Piece** - See where your piece will land
- 📦 **Hold System** - Save a piece for later use
- 🏆 **High Score** - Persistent high score saved locally
- 📱 **Responsive Design** - Works on desktop, tablet, and mobile
- 🎅 **Festive Theme** - Santa & Mrs. Claus cheer you on!
- 📤 **Share Feature** - Share your score on social media with a screenshot
- 🔊 **Sound Effects** - Festive audio feedback (optional)

## 🎮 How to Play

Stack the falling blocks to create complete horizontal lines. When a line is complete, it clears and you earn points. The game speeds up as you level up!

### Scoring
- **Single line**: 100 × level
- **Double**: 300 × level
- **Triple**: 500 × level
- **Tetris (4 lines)**: 800 × level
- **Combo bonus**: Extra points for consecutive line clears

### Leveling Up
- Level 1: 10 lines
- Level 2: 12 lines
- Level 3+: Increases progressively

## 🕹️ Controls

### Keyboard
| Key | Action |
|-----|--------|
| ← → | Move left/right |
| ↓ | Soft drop |
| ↑ or X | Rotate clockwise |
| Z | Rotate counter-clockwise |
| Space | Hard drop |
| C | Hold piece |
| P | Pause/Resume |
| Esc | Pause |
| F1 | Help |

### Mouse/Touch
- **Click sides** of board to move
- **Click/tap piece** to rotate
- **Double-click/tap** for hard drop
- **Scroll wheel** to rotate
- **Swipe** left/right/down on mobile

### On-Screen Buttons
Full touch controls available for mobile and accessibility.

## 🎁 Power-ups

Power-ups appear every 4 pieces (after the first few). They cannot be held!

| Power-up | Emoji | Effect |
|----------|-------|--------|
| **Fire** | 🔥 | Burns through blocks below |
| **Bomb** | 💥 | 3×3 explosion at landing point |
| **Ice** | ❄️ | Freezes nearby blocks temporarily |
| **Santa's Sack** | 🎁 | Clears entire column |
| **Magic Wave** | ✨ | Clears entire row |
| **Hourglass** | ⏳ | Slows down time (rare!) |

## 🎄 Christmas Themes

Each Tetris piece has a festive emoji:
- **I** - 🎄 Christmas Tree
- **O** - 🎅 Santa
- **T** - 🧦 Stocking
- **S** - ⛄ Snowman
- **Z** - 🍪 Gingerbread
- **J** - 🔔 Bell
- **L** - 🎁 Present

## 📸 Screenshots

*Add your own screenshots here!*

```
![Gameplay](screenshots/gameplay.png)
![Power-ups](screenshots/powerups.png)
![Mobile View](screenshots/mobile.png)
```

## 🚀 Play Online

🎮 **[Play Festive Blocks Now!](https://irsdl.github.io/FestiveBlocks/)** 🎮

## 💾 Local Installation

No installation required! Simply:

1. Clone or download this repository
2. Open `index.html` in any modern web browser
3. Start playing!

```bash
git clone https://github.com/irsdl/FestiveBlocks.git
cd FestiveBlocks
# Open index.html in your browser
```

Or play directly by opening the HTML file - no server needed!

## 💻 Technical Details

- **Single File**: Entire game in one HTML file (~4000 lines)
- **No Dependencies**: Pure HTML5, CSS3, and vanilla JavaScript
- **Canvas Rendering**: Smooth 60fps gameplay
- **Local Storage**: High scores persist between sessions
- **Responsive**: Adapts to screen sizes from 320px to 4K

### Browser Support
- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

## 🎨 Customization

The game uses CSS variables for easy theming:

```css
:root {
  --primary-teal: #4ECDC4;
  --deep-teal: #00A896;
  --primary-coral: #FF6B6B;
  --warm-orange: #FFB347;
  --accent-purple: #6C5CE7;
}
```

## 📄 License

This project is licensed under the [GNU Affero General Public License v3.0 (AGPL-3.0)](https://github.com/irsdl/FestiveBlocks/blob/main/LICENSE).

Copyright © 2025 Soroush Dalili

This program is free software: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License as published by the Free Software Foundation, version 3 of the License.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU Affero General Public License for more details.

## 👤 Author

**Soroush Dalili (@irsdl)**

- GitHub: [@irsdl](https://github.com/irsdl)
- Repository: [FestiveBlocks](https://github.com/irsdl/FestiveBlocks)

## 🙏 Acknowledgments

- Inspired by the classic Tetris game by Alexey Pajitnov
- Christmas emojis provided by system fonts
- Built with ❤️ for the holiday season

---

⭐ **If you enjoy the game, please give it a star!** ⭐

🎄 **Happy Holidays and Happy Gaming!** 🎮

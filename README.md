# 🐍 Neon Snake - 10 Game Modes

A modern, neon-styled take on the classic Snake game featuring 10 unique game modes, stunning visual effects, and responsive design. Built with vanilla HTML5, CSS3, and JavaScript.

![Neon Snake Preview](https://img.shields.io/badge/Game-Neon%20Snake-00ffcc?style=for-the-badge&logo=gamemaker&logoColor=white)

## ✨ Features

- **10 Unique Game Modes** - Each with distinct gameplay mechanics
- **Neon Cyberpunk Aesthetic** - Glowing effects and retro styling
- **Responsive Design** - Works on desktop and mobile devices
- **High Score Tracking** - Individual high scores for each game mode
- **Smooth Animations** - Fade transitions and glow effects
- **Retro Font** - Press Start 2P font for authentic arcade feel

## 🎮 Game Modes

### 1. 🟢 Classic
The traditional Snake experience - eat food, grow longer, avoid walls and yourself.

### 2. 🧘 Zen Mode
Relaxed gameplay with no walls - wrap around the screen edges for endless play.

### 3. ⚡ Speed Demon
Adrenaline rush mode - the snake gets faster with every piece of food consumed.

### 4. 🚧 Obstacle Course
Navigate through static obstacles scattered across the playing field.

### 5. 🌀 Portal Jumper
Use magical portals to teleport across the map - enter one, exit the other.

### 6. 🏛️ The Labyrinth
Navigate through a complex maze structure that fills the entire board.

### 7. 🍎 Food Frenzy
Multiple food items appear simultaneously - collect them all!

### 8. 🔄 Inverse Controls
Mind-bending challenge where up is down and left is right.

### 9. 🔦 Flashlight
Limited visibility mode - only a small area around the snake head is visible.

### 10. ☠️ Sudden Death
After collecting 5 food items, a deadly obstacle wall appears in the center.

## 🕹️ Controls

- **Arrow Keys** - Control snake direction
- **Enter/Click** - Select menu options
- **ESC** - Return to main menu (during game over)

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/akshdeepsingh7/neon-snake.git
   cd neon-snake
   ```

2. **Or download directly**
   - Download the HTML file from the repository
   - Save it to your local machine

3. **Run the game**
   - Open the HTML file in your web browser
   - Or serve it using a local web server
   - **Live Demo**: [Play Neon Snake](https://akshdeepsingh7.github.io/neon-snake/)

### Local Server (Optional)
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js
npx serve .

# Then open http://localhost:8000
```

## 🎨 Customization

### Color Scheme
The game uses CSS custom properties for easy theming:

```css
:root {
    --primary-color: #00ffcc;    /* Snake head & UI */
    --secondary-color: #ff00ff;  /* Snake body & accents */
    --food-color: #ffff00;       /* Food items */
    --bg-color: #0d0d1a;         /* Background */
    --text-color: #f0f0f0;       /* Text */
}
```

### Game Parameters
Modify these constants in the JavaScript section:

```javascript
const GRID_SIZE = 20;           // Size of each grid cell
const CANVAS_RESOLUTION = 600;  // Canvas size in pixels
let gameSpeed = 120;            // Initial game speed (ms)
```
## 🏆 High Scores

High scores are automatically saved to your browser's local storage for each game mode individually. Scores persist between sessions.

## 🔧 Technical Details

### Built With
- **HTML5 Canvas** - Game rendering
- **CSS3** - Styling and animations
- **Vanilla JavaScript** - Game logic
- **Local Storage** - High score persistence
- **Google Fonts** - Press Start 2P font

### Performance
- Optimized rendering loop
- Efficient collision detection
- Responsive design with CSS clamp()
- Hardware-accelerated CSS effects

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/akshdeepsingh7/neon-snake/issues).

### How to Contribute
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Ideas for Contributions
- Additional game modes
- Sound effects and music
- Particle effects
- Touch/swipe controls for mobile
- Leaderboard system
- Game replay system
- Power-ups and special items

## 🌟 Show Your Support

Give a ⭐️ if you enjoyed playing Neon Snake!

[![GitHub stars](https://img.shields.io/github/stars/akshdeepsingh7/neon-snake?style=social)](https://github.com/akshdeepsingh7/neon-snake/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/akshdeepsingh7/neon-snake?style=social)](https://github.com/akshdeepsingh7/neon-snake/network/members)

**Enjoy the neon-powered snake adventure!** 🐍✨

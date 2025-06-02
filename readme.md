# 🏏 Cricket Batting Game

A realistic cricket batting simulator built with HTML5, CSS3, and JavaScript. Experience the thrill of batting from a first-person perspective with dynamic ball physics, multiple shot types, and immersive gameplay.

![Cricket Game Demo](https://img.shields.io/badge/Game-Cricket%20Batting-green?style=for-the-badge&logo=cricket)

## 🎮 Game Features

### Core Gameplay
- **Batsman's POV**: Authentic first-person batting experience
- **Dynamic Ball Physics**: Realistic ball delivery with varying speeds
- **5 Shot Types**: Each with unique timing and power characteristics
- **Live Scoring**: Real-time score tracking with boundaries and statistics
- **Visual Effects**: Boundary celebrations and shot animations

### Shot Types
| Shot | Key | Description | Power | Timing |
|------|-----|-------------|-------|--------|
| **Defense** | `D` | Safe defensive shot | Low | Easy |
| **Drive** | `S` | Classic straight drive | Medium | Medium |
| **Cut** | `A` | Square cut shot | Medium | Medium |
| **Pull** | `W` | Aggressive pull shot | High | Hard |
| **Sweep** | `E` | Sweep shot | Medium | Medium |

## 🚀 Quick Start

### Play Online
Simply open the `index.html` file in any modern web browser - no installation required!

### Local Setup
```bash
# Clone the repository
git clone https://github.com/r3dhulk/cricket-batting-game.git

# Navigate to project directory
cd cricket-batting-game

# Open in browser
open index.html
# or
python -m http.server 8000  # For local server
```

## 🎯 How to Play

1. **Start Game**: Click "Start Game" or press the start button
2. **Watch the Ball**: Ball is delivered from the bowler toward you
3. **Time Your Shot**: Use buttons or keyboard keys when ball approaches
4. **Score Runs**: Good timing results in runs, great timing gives boundaries!

### Controls
- **Mouse**: Click shot buttons at bottom of screen
- **Keyboard**: Use `D`, `S`, `A`, `W`, `E` keys for different shots
- **Spacebar**: Quick drive shot

### Scoring System
- **1-3 Runs**: Regular shots with good timing
- **4 Runs**: Boundary hit (FOUR!)
- **6 Runs**: Over the boundary (SIX!)
- **0 Runs**: Missed shots or poor timing

## 🛠️ Technical Details

### Technologies Used
- **HTML5**: Game structure and canvas
- **CSS3**: Advanced animations and responsive design
- **Vanilla JavaScript**: Game logic and physics
- **No Dependencies**: Pure web technologies only

### Browser Compatibility
- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- 📱 Mobile browsers supported

### Performance Features
- Smooth 60fps animations
- Efficient DOM manipulation
- Memory-optimized ball physics
- Responsive design for all screen sizes

## 🎨 Game Screenshots

```
🏏 Pitch View
┌─────────────────────────────┐
│     🌤️  Sky & Clouds        │
│                             │
│  🧍 Bowler                   │
│   │                         │
│   │ 🔴 Ball                 │
│   │                         │
│   │                         │
│   │                         │
│   🏏 Batsman (You)          │
│   ⚏ Stumps                  │
└─────────────────────────────┘
```

## 🎮 Game Mechanics

### Ball Physics
- **Speed Variation**: Random delivery speeds (3-5 units/frame)
- **Straight Trajectory**: Realistic pitch-to-batsman path
- **Timing Windows**: Each shot has optimal timing zones

### Shot Mechanics
- **Power System**: Different shots have varying power potential
- **Accuracy Factor**: Timing affects shot success rate
- **Visual Feedback**: Batsman animations for each shot type

### Scoring Algorithm
```javascript
// Simplified scoring logic
if (timing > 0.7 && power > 0.7) return 6; // Six
if (timing > 0.5 && power > 0.5) return 4; // Four  
if (timing > 0.3) return 1-3; // Regular runs
else return 0; // Miss
```

## 🔧 Customization

### Difficulty Settings
Modify these variables in the JavaScript section:
```javascript
// Ball speed range
const speed = Math.random() * 2 + 3; // 3-5 (Easy: 2-4, Hard: 4-7)

// Timing windows  
shot.timing + 0.3 // Easy: +0.4, Hard: +0.2
```

### Visual Customization
- Change colors in CSS variables
- Modify pitch dimensions
- Add new shot animations
- Customize UI elements

## 📊 Statistics Tracked

- **Total Score**: Cumulative runs scored
- **Balls Faced**: Number of deliveries
- **Boundaries**: 4s and 6s hit
- **Strike Rate**: Calculated automatically

## 🤝 Contributing

We welcome contributions! Here's how you can help:

### Bug Reports
- Use GitHub Issues for bug reports
- Include browser version and steps to reproduce
- Screenshots are helpful

### Feature Requests
- **Bowling Variations**: Different ball types (yorker, bouncer)
- **Multiplayer Mode**: Challenge friends
- **Career Mode**: Progressive difficulty
- **Sound Effects**: Audio feedback for shots

### Development Setup
```bash
# Fork the repository
# Clone your fork
git clone https://github.com/r3dhulk/cricket-batting-game.git

# Create feature branch
git checkout -b feature/your-feature-name

# Make changes and test
# Commit and push
git commit -m "Add your feature"
git push origin feature/your-feature-name

# Create Pull Request
```

## 📝 License

MIT License - feel free to use this project for learning, modification, or commercial purposes.

## 🎯 Roadmap

### Version 2.0 (Planned)
- [ ] Multiple difficulty levels
- [ ] Bowling machine with different deliveries
- [ ] Career mode with tournaments
- [ ] Leaderboard system
- [ ] Mobile app version

### Version 2.1 (Future)
- [ ] Multiplayer support
- [ ] Sound effects and music
- [ ] 3D graphics upgrade
- [ ] VR compatibility

## 🏆 Achievements

Try to unlock these milestones:
- **Century**: Score 100+ runs
- **Boundary King**: Hit 10+ boundaries in one game
- **Perfect Timing**: Score 6 consecutive boundaries
- **Endurance**: Face 50+ balls in one game

## 📞 Support

- **Issues**: [GitHub Issues](https://github.com/r3dhulk/cricket-batting-game/issues)
- **Discussions**: [GitHub Discussions](https://github.com/r3dhulk/cricket-batting-game/discussions)
- **Email**: your.email@example.com

## 🙏 Acknowledgments

- Cricket physics inspired by real cricket mechanics
- UI design influenced by modern cricket video games
- Thanks to the cricket community for feedback and suggestions

---

**Enjoy the game and may you score many boundaries! 🏏🎯**

*Star ⭐ this repository if you enjoyed the game!*
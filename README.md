# 🎮 Pong Game

A classic Pong game built with HTML, CSS, and JavaScript. Play against the computer AI in this nostalgic arcade experience with modern styling and smooth gameplay.

## 🌟 Features

- **Player vs Computer**: Challenge the AI opponent with adaptive difficulty
- **Mouse & Keyboard Control**: Control your paddle with mouse movement or arrow keys
- **Real-time Scoring**: Keep track of scores for both player and computer
- **Physics-Based Collision**: 
  - Ball bounces off walls realistically
  - Paddle collisions with spin mechanics
  - Smooth ball trajectory calculations
- **Neon Cyberpunk Design**: Modern visual effects with glowing elements
- **Responsive Gameplay**: Smooth 60 FPS animation using RequestAnimationFrame
- **Easy Reset**: Reset the game with a single button click

## 🎮 How to Play

1. **Open the Game**: Simply open `index.html` in your web browser
2. **Control Your Paddle**: 
   - Move your mouse up/down over the game canvas, OR
   - Use arrow keys (↑/↓) to move the left paddle
3. **Objective**: 
   - Prevent the ball from reaching the left edge (your side)
   - Get the ball past the computer's paddle to score
4. **Scoring**: Each time the ball goes out of bounds, the opposite player scores a point
5. **Reset**: Click the "Reset Game" button to start over with scores at 0-0

## 🕹️ Controls

| Action | Input |
|--------|-------|
| Move Paddle Up | Mouse Move Up or ⬆️ Arrow Key |
| Move Paddle Down | Mouse Move Down or ⬇️ Arrow Key |
| Reset Game | Click "Reset Game" Button |

## 🎨 Game Elements

- **Left Paddle (Green)**: Controlled by the player
- **Right Paddle (Green)**: Controlled by the computer AI
- **Ball (Magenta)**: Bounces around the court
- **Center Line**: Divides the court
- **Scoreboard**: Displays current scores

## 🤖 AI Difficulty

The computer opponent has an adaptive difficulty level set at 0.8x, making it challenging but beatable. The AI:
- Tracks the ball's position
- Predicts ball movement
- Moves smoothly to intercept
- Can be beaten with skilled gameplay

## 📋 Game Specifications

| Specification | Value |
|---|---|
| Canvas Size | 800x400 pixels |
| Paddle Dimensions | 10x80 pixels |
| Ball Size | 8px radius |
| Player Paddle Speed | 6 pixels/frame |
| Computer Paddle Speed | 4.5 pixels/frame |
| Ball Initial Speed | 5 pixels/frame |

## 🚀 Getting Started

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge, etc.)
- No installation or dependencies required!

### Installation
1. Clone or download this repository
2. Open `index.html` in your web browser
3. Start playing!

### File Structure
```
pong-game/
├── index.html      # Complete game file (HTML, CSS, and JavaScript)
└── README.md       # This file
```

## 💡 Tips for Winning

1. **Use Mouse Control**: Mouse movement provides smoother, more responsive control
2. **Predict Ball Trajectory**: Anticipate where the ball will go
3. **Use the Edges**: Position your paddle at the edges to cover more area
4. **Add Spin**: Hit the ball at different paddle heights to change its trajectory
5. **Stay Alert**: Keep your paddle moving to react quickly

## 🛠️ Technical Details

### Technologies Used
- **HTML5**: Canvas API for game rendering
- **CSS3**: Styling with gradients and shadows
- **JavaScript (ES6)**: Game logic, physics, and AI

### Key Functions
- `update()`: Updates game state each frame
- `draw()`: Renders all game elements
- `gameLoop()`: Main game loop using RequestAnimationFrame
- `resetBall()`: Resets ball to center with random direction
- `resetGame()`: Resets entire game state

### Physics Implementation
- Velocity-based movement
- Collision detection using AABB (Axis-Aligned Bounding Box)
- Spin mechanics based on paddle position
- Ball trajectory prediction for AI

## 🎯 Future Enhancements

Possible improvements for future versions:
- Sound effects and background music
- Power-ups (speed boost, paddle size increase)
- Difficulty levels (Easy, Medium, Hard)
- Two-player mode (local multiplayer)
- Score history/statistics
- Mobile touch controls
- Particle effects

## 📝 License

This project is open source and available for educational and personal use.

## 🤝 Contributing

Feel free to fork this project and submit pull requests with improvements or new features!

## 📧 Contact

For questions or suggestions, feel free to reach out.

---

**Enjoy the game! 🎮✨**

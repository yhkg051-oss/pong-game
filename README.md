# Pong Game

A classic Pong game implementation using HTML5 Canvas, CSS3, and vanilla JavaScript. Play against an AI opponent in this nostalgic arcade game!

## Features

- **Player vs Computer AI**: Challenge the computer in an engaging match
- **Mouse and Keyboard Controls**: Control your paddle using your mouse or arrow keys
- **Collision Detection**: Realistic ball physics with wall and paddle collision
- **Score Tracking**: Keep track of both player and computer scores
- **Dynamic Ball Physics**: Ball speed increases with each paddle hit
- **Responsive Design**: Beautiful UI with gradient background and smooth animations

## Game Rules

- Use your left paddle to hit the ball back towards the computer
- The computer controls the right paddle with AI logic
- If the ball passes your paddle, the computer scores a point
- If the ball passes the computer's paddle, you score a point
- First to reach the highest score wins!

## Controls

| Control | Action |
|---------|--------|
| **Mouse Movement** | Move left paddle up/down |
| **Arrow Up (↑)** | Move left paddle up |
| **Arrow Down (↓)** | Move left paddle down |
| **Reset Button** | Reset game score and restart |

## How to Play

1. Open `index.html` in your web browser
2. Move your mouse or use arrow keys to control the left paddle
3. Try to hit the ball back to the computer's side
4. Earn points when the ball passes the opponent's paddle
5. Click "Reset Game" to start over

## Game Features Explained

### Ball Physics
- Ball bounces off top and bottom walls
- Ball increases in speed with each paddle hit (up to max speed)
- Ball trajectory changes based on where it hits the paddle
- Ball angle is affected by paddle hit position for strategic play

### AI Opponent
- Computer uses predictive AI to track the ball
- Has a reaction zone to provide fair gameplay
- Moves at a balanced speed for competitive yet beatable difficulty

### Scoring System
- Points awarded when ball passes opponent's paddle
- Score resets when Reset button is clicked
- Scores displayed prominently at the top

## Installation

No installation needed! Simply:

1. Clone or download this repository
2. Open `index.html` in any modern web browser
3. Start playing!

## Browser Compatibility

Works on all modern browsers that support:
- HTML5 Canvas
- CSS3 Gradients
- ES6 JavaScript

## File Structure

```
pong-game/
├── index.html   # Main HTML file
├── styles.css   # Game styling
├── script.js    # Game logic
└── README.md    # This file
```

## Technical Details

- **Canvas Resolution**: 800x400 pixels
- **Ball Size**: 8 pixels diameter
- **Paddle Size**: 10x80 pixels
- **Max Ball Speed**: 8 pixels/frame

## Future Enhancements

- Difficulty levels (Easy, Medium, Hard)
- Sound effects
- High score tracking
- Power-ups (speed boost, larger paddle, etc.)
- Two-player local multiplayer mode
- Score animations and visual effects

## License

Feel free to use and modify this game for personal or educational purposes.

Enjoy playing! 🏓
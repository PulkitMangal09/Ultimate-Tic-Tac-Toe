# Ultimate Tic-Tac-Toe

[![Live Demo](https://img.shields.io/badge/demo-live-green.svg)](https://ultimate-tic-tac-toe-gilt-pi.vercel.app/)

An enhanced version of the classic Tic-Tac-Toe game with nested boards and strategic gameplay.


## Features

**Interactive Gameplay**  
- Play against an AI opponent
- Clear visual indicators for active boards
- Smooth animations and sound effects

**Modern UI**  
- Clean, responsive design
- Distinct color scheme for X (purple) and O (red)
- Pulsing animation on active boards

**Enhanced Win Detection**  
- Visual celebration with confetti when you win
- Clear display of winning board combinations
- Different animations for win/lose/draw outcomes

**Mobile-Friendly**  
- Fully responsive design
- Optimized for touch devices
- Adapts to different screen sizes

## How to Play

1. **Game Board**: The main board consists of 9 small tic-tac-toe boards
2. **First Move**: X starts by playing in any cell of any small board
3. **Subsequent Moves**: Your move determines where your opponent plays next
   - If you play in a small board's top-right corner, your opponent must play in the top-right small board
4. **Winning a Small Board**: Get 3 in a row (X or O) to claim that board
5. **Winning the Game**: Win 3 small boards in a row on the main grid

Special Rule: If sent to an already-won or full small board, you can choose any available board.

## Live Demo

Play the game now: [https://ultimate-tic-tac-toe-gilt-pi.vercel.app/](https://ultimate-tic-tac-toe-gilt-pi.vercel.app/)

## Technologies Used

- HTML5, CSS3, JavaScript (Vanilla JS)
- CSS Grid for board layout
- CSS Variables for theming
- Web Animations API
- Vercel for deployment

## Installation

To run locally:

```bash
git clone https://github.com/your-username/ultimate-tic-tac-toe.git
cd ultimate-tic-tac-toe
# Open index.html in your browser

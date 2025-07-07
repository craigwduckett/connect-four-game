# Connect Four Game

A classic Connect Four game built with HTML, CSS, and JavaScript. Drop your pieces strategically to connect four in a row and win!

## 🎮 Game Overview

Connect Four is a two-player strategy game where players take turns dropping colored pieces into a vertical grid. The objective is to be the first player to connect four of your pieces in a row - horizontally, vertically, or diagonally.

## 🎯 How to Play

### Game Rules

1. **Two Players**: Red and Yellow pieces alternate turns
2. **Drop Pieces**: Click on any column to drop your piece into the lowest available slot
3. **Win Condition**: Connect four of your pieces in a row:
   - **Horizontally** (←→)
   - **Vertically** (↑↓)
   - **Diagonally** (↗↙ or ↖↘)
4. **Turn Order**: Red player goes first, then players alternate

### Game Board

- **Grid Size**: 7 columns × 6 rows
- **Piece Colors**: Red and Yellow
- **Gravity**: Pieces fall to the lowest available position in each column

## 🚀 How to Start the Game

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software installation required

### Running the Game

1. **Clone or Download** the project files to your computer
2. **Open** the `index.html` file in your web browser by:
   - Double-clicking the file, or
   - Right-clicking and selecting "Open with" → your browser, or
   - Dragging the file into your browser window
3. **Start Playing** immediately - the game loads automatically!

### Game Controls

- **Click** on any column to drop your piece
- **Restart Button**: Click to start a new game at any time
- **Winner Display**: Shows which player won when the game ends

## 🎨 Features

- **Interactive Gameplay**: Click-to-drop interface
- **Visual Feedback**: Clear red and yellow piece colors
- **Win Detection**: Automatic detection of all winning combinations
- **Game Status**: Winner announcement when game ends
- **Restart Function**: Easy game reset with the restart button
- **Responsive Design**: Clean, centered layout that works on different screen sizes

## 🏗️ Technical Details

### File Structure

```
connectfour/
├── index.html      # Main game interface
├── app.js          # Game logic and functionality
├── style.css       # Visual styling and layout
└── README.md       # This file
```

### Technologies Used

- **HTML5**: Game structure and layout
- **CSS3**: Styling, colors, and responsive design
- **Vanilla JavaScript**: Game logic, event handling, and win detection

## 🎲 Game Strategy Tips

- **Center Control**: Playing in the center columns gives you more winning opportunities
- **Block Opponents**: Watch for opponent's potential four-in-a-row and block them
- **Set Up Multiple Threats**: Create situations where you can win in multiple ways
- **Think Ahead**: Consider how your move affects future possibilities

## 🔧 Customization

The game can be easily customized by modifying:

- **Colors**: Edit the CSS color values in `style.css`
- **Board Size**: Modify the `rows` and `columns` variables in `app.js`
- **Styling**: Adjust the visual appearance in `style.css`

## 🎉 Enjoy the Game!

Have fun playing Connect Four! Challenge your friends and family to see who can master the strategy of connecting four pieces in a row.

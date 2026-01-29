# Tic Tac Toe React Game 🎮

A fully functional Tic Tac Toe game built with React featuring a modern UI, move history, and game reset functionality.

## Features ✨

- **3x3 Interactive Game Board** - Click to place X or O
- **Two Player Turns** - Alternates between X and O players
- **Win Detection** - Automatically detects wins in rows, columns, and diagonals
- **Draw Detection** - Identifies when the game ends in a draw
- **Current Player Display** - Shows whose turn it is
- **Winner Announcement** - Displays the winner when game ends
- **Game Reset** - Reset button to start a new game
- **Move History** - Track and jump to any previous move
- **Beautiful Gradient UI** - Modern, responsive design with smooth animations

## Prerequisites 📋

Before you begin, ensure you have the following installed:
- **Node.js** (version 14 or higher) - [Download here](https://nodejs.org/)
- **npm** (comes with Node.js) or **yarn**

## Installation & Setup 🚀

Follow these step-by-step instructions to run the project locally:

### Step 1: Clone the Repository

```bash
git clone https://github.com/WavyWare/tictactoereact.git
cd tictactoereact
```

### Step 2: Install Dependencies

Install all required packages using npm:

```bash
npm install
```

Or if you prefer yarn:

```bash
yarn install
```

### Step 3: Start the Development Server

Run the app in development mode:

```bash
npm start
```

Or with yarn:

```bash
yarn start
```

### Step 4: View the Game

The game will automatically open in your default browser at:
```
http://localhost:3000
```

If it doesn't open automatically, manually navigate to the URL above.

## How to Play 🎯

1. **Starting the Game**: The game starts with Player X
2. **Making a Move**: Click on any empty square to place your mark (X or O)
3. **Taking Turns**: Players alternate turns automatically
4. **Winning**: Get three of your marks in a row (horizontally, vertically, or diagonally)
5. **Draw**: If all squares are filled and no player has won, the game is a draw
6. **Reset**: Click the "Reset Game" button to start a new game
7. **Move History**: Use the move history buttons on the right to jump to any previous game state

## Project Structure 📁

```
tictactoereact/
├── public/
│   └── index.html          # HTML template
├── src/
│   ├── App.js              # Main game component with logic
│   ├── App.css             # Game styling
│   ├── index.js            # React entry point
│   └── index.css           # Global styles
├── package.json            # Dependencies and scripts
├── .gitignore              # Git ignore file
└── README.md               # This file
```

## Available Scripts 📜

In the project directory, you can run:

### `npm start`
Runs the app in development mode at [http://localhost:3000](http://localhost:3000)

### `npm test`
Launches the test runner in interactive watch mode

### `npm run build`
Builds the app for production to the `build` folder

### `npm run eject`
⚠️ **Note: this is a one-way operation. Once you eject, you can't go back!**

## Building for Production 🏗️

To create an optimized production build:

```bash
npm run build
```

This creates a `build` folder with optimized files ready for deployment.

## Technologies Used 💻

- **React 18.2** - JavaScript library for building user interfaces
- **React Hooks** - useState for state management
- **CSS3** - Modern styling with gradients and animations
- **Create React App** - Toolchain for React development

## Game Logic 🧠

The game implements:
- **State Management**: Uses React hooks to manage game state, move history, and current player
- **Win Condition Checking**: Validates all 8 possible winning combinations (3 rows, 3 columns, 2 diagonals)
- **Immutable State**: Uses array slicing to maintain move history
- **Draw Detection**: Checks if all squares are filled without a winner

## Customization 🎨

You can customize the game by editing:
- `src/App.css` - Change colors, sizes, and animations
- `src/App.js` - Modify game logic or add new features

## Troubleshooting 🔧

**Port already in use?**
```bash
# Kill the process on port 3000 (Mac/Linux)
lsof -ti:3000 | xargs kill -9

# Or run on a different port
PORT=3001 npm start
```

**Dependencies not installing?**
```bash
# Clear npm cache and reinstall
npm cache clean --force
rm -rf node_modules package-lock.json
npm install
```

## License 📄

This project is open source and available under the MIT License.

## Contributing 🤝

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## Author ✍️

Created by JFTech

## Acknowledgments 🙏

- Inspired by the official React tutorial
- Built with Create React App

---

**Enjoy playing Tic Tac Toe! 🎉**

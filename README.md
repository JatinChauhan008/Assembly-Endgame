# Assembly Endgame

Assembly Endgame is a React-based application built with Vite, designed to provide an interactive and engaging word-guessing game experience. This project leverages modern web development tools and libraries to create a dynamic and responsive application.

## Features

- **React Framework**: Built with React 18.3.1 for creating dynamic and modern user interfaces.
- **Vite Integration**: Utilizes Vite for fast development, building, and previewing.
- **Interactive Gameplay**: Players guess letters to uncover a hidden word, with visual feedback for correct and incorrect guesses.
- **Game Over Conditions**:
  - **Win**: Successfully guess all the letters in the word.
  - **Lose**: Exceed the maximum number of incorrect guesses.
- **Visual Feedback**:
  - Correct guesses are highlighted.
  - Incorrect guesses are marked, and visual elements change to indicate mistakes.
- **Confetti Celebration**: A confetti effect is triggered when the player wins.
- **Accessibility**: Includes features like disabling the keyboard when the game is over and providing appropriate labels for buttons.

## Rules

1. **Objective**: Guess the hidden word by selecting letters from the virtual keyboard.
2. **Guesses**:
   - Each incorrect guess is counted and displayed visually.
   - The game ends when the player either guesses the word or runs out of allowed incorrect guesses.
3. **Game Reset**: A "New Game" button allows players to start a new game with a fresh word.
4. **Revealing the Word**: If the player loses, the full word is revealed.

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd Assembly-Endgame
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm start
   ```

## Learn More

- [Vite Documentation](https://vitejs.dev/)

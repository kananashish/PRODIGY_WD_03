# Tic-Tac-Toe Web Application

A modern, interactive Tic-Tac-Toe game built with HTML, CSS, and JavaScript, styled using Tailwind CSS. This web application offers a visually appealing experience with smooth animations, a responsive design, and both two-player and AI opponent modes. The game includes glowing win effects, a modal for game results, and a clean interface, making it engaging and easy to play.

## Features

- **Two-Player Mode**: Compete against a friend on the same device.
- **AI Opponent**: Challenge a simple AI that prioritizes winning, blocking, or taking the center.
- **Responsive Design**: Works seamlessly on desktop and mobile devices.
- **Stylish UI**: Tailwind CSS-powered design with a gradient background, hover animations, and glowing win effects.
- **Game State Management**: Tracks moves, checks for wins or ties, and displays results in a modal.
- **Restart Option**: Easily start a new game with a single click.
- **Footer**: Includes a custom footer with "Made by Ashish Kanan with ❤️".

## Demo

Play the game by opening `index.html` in a web browser. No server setup is required as it runs entirely client-side.

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/your-username/tic-tac-toe.git
   ```
2. **Navigate to the Project Directory**:

   ```bash
   cd tic-tac-toe
   ```
3. **Open the Game**:
   - Open `index.html` in a web browser (e.g., Chrome, Firefox).
   - No additional dependencies or server setup are needed, as Tailwind CSS is included via CDN.

## Usage

1. **Start the Game**:
   - Click "Two Players" to play with a friend or "Play vs AI" to challenge the computer.
   - Player X goes first, followed by Player O.
2. **Gameplay**:
   - Click an empty cell to place your marker (X or O).
   - The game checks for three markers in a row (horizontally, vertically, or diagonally).
   - If all cells are filled without a winner, the game ends in a tie.
3. **AI Mode**:
   - The AI opponent prioritizes winning, blocking the player's winning moves, or taking the center, with a slight delay for a natural feel.
4. **Restart**:
   - Click "Restart Game" or "Close" in the result modal to start a new game.

## Technologies Used

- **HTML**: Structure of the game board and UI elements.
- **CSS**: Styling with Tailwind CSS for a modern, responsive design and custom animations.
- **JavaScript**: Game logic, including move handling, win detection, and AI behavior.
- **Tailwind CSS**: Included via CDN for rapid styling and responsive design.

## Project Structure

```
tic-tac-toe/
├── index.html      # Main HTML file with game logic and styling
└── README.md       # Project documentation
```

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit (`git commit -m "Add your feature"`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.


## Acknowledgements

- Built with ❤️ by Ashish Kanan.
- Powered by Tailwind CSS for styling.

---

Made by Ashish Kanan with ❤️
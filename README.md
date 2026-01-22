# Rock-Paper-Scissors Game
This project is an interactive implementation of the classic Rock-Paper-Scissors game, developed to practice core JavaScript fundamentals like DOM manipulation, event handling, and local storage for state persistence.

## Structure of Repository
```
├── images
├── scripts
│   ├── rock-paper-scissors.js
├── styles
│   ├── rock-paper-scissors.css
├── rock-paper-scissors.html
└── README.md
```

## Technical Implementation
* **DOM Manipulation:** Extensively utilized document.querySelector and innerHTML to dynamically update the game results, player moves, and score display without refreshing the page.
* **State Management:** Implemented localStorage with JSON.parse and JSON.stringify to maintain the score (Wins, Losses, Ties) across browser sessions, ensuring data persistence.
* **Event Handling:** Added interactive event listeners for both mouse clicks and keyboard inputs (keydown), allowing users to play using specific keys (r, p, s).
* **Game Logic:** Engineered a randomized computer opponent using Math.random() and conditional logic to determine the winner based on standard game rules.
* **Asynchronous Operations:** Created an "Auto Play" feature using setInterval to simulate the game playing itself automatically every second.

## Key Features
* **Persistent Scoreboard:** The game remembers your score even if you close or refresh the tab.
* **Auto Play Mode:** A simulation mode where the computer plays against itself, useful for testing game logic rapidly.
* **Keyboard Shortcuts:** Full keyboard accessibility for faster gameplay:
  * r - Rock
  * p - Paper
  * s - Scissors
  * a - Toggle Auto Play
  * Backspace - Reset Score
* **Reset Confirmation:** A UI safety check that asks for confirmation before clearing the score history.
 
<br>
<img width="503" height="641" alt="Screenshot 2026-01-23 003657" src="https://github.com/user-attachments/assets/c7130ba9-efaf-48d7-b636-582954398dc9" />

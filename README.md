## Project Overview

The "Pig Game" is a simple two-player dice game where the objective is to be the first player to reach a predefined score. Players take turns rolling a dice, and the outcome of the roll is added to their current score. If a player rolls a 1, they lose their current score, and it's the next player's turn. The game continues until one of the players reaches the winning score(30).

## Acknowledgements

This project was built for learning purposes as a part of "The Complete JavaScript Course 2023: From Zero to Expert!" course.

The project was designed by Jonas Schmedtmann, the tutor. For more details, you can check out the course [here](https://www.udemy.com/course/the-complete-javascript-course/).

You can view my certificate of completion [here](https://www.udemy.com/certificate/UC-aab2cca8-5a8d-440d-9a2d-4d31847739b1/).

## Technologies Used

- **HTML**
- **CSS**
- **JavaScript:** The core game logic and functionality are implemented using JavaScript. This includes:

- Selecting and manipulating HTML elements in the Document Object Model (DOM).
- Managing game state, player scores, and current scores.
- Implementing dice roll functionality.
- Determining the game winner and handling game-over scenarios.
- Handling user interactions through event listeners.

## Functionality

The "Pig Game" project provides the following key functionalities:

**Initialization (init function):** The game initializes with two players, both starting with a score of 0. Player 1 is the initial active player. The "Roll Dice" and "Hold" buttons are active, and the dice image is hidden.

**Rolling the Dice:** Clicking the "Roll Dice" button triggers the roll of a six-sided die. The rolled number is displayed in the dice image, and if it's not a 1, the current score for the active player is updated. If a 1 is rolled, the current score is reset to 0, and it's the next player's turn.

**Holding the Score:** Clicking the "Hold" button adds the current score to the active player's total score. If the total score of any player reaches or exceeds the winning score (30 in the current implementation), that player is declared the winner, and the game ends. The dice is hidden, and the "Roll Dice" and "Hold" buttons are disabled.

**Switching Players:** After a turn is completed (either by rolling a 1 or clicking "Hold"), it's the next player's turn. The active player is visually highlighted, and their current score is updated accordingly.

**New Game:** Clicking the "New Game" button resets the game to its initial state. Both players' scores and the current score are set to 0, and Player 1 is designated as the active player.

## How to Play

Start a new game by clicking the "New Game" button.

Roll the dice by clicking the "Roll Dice" button.

Keep rolling to accumulate points, but be cautious not to roll a 1, as it will end your turn and reset your current score.

Click the "Hold" button to add your current score to your total score. If your total score reaches or exceeds the winning score (30), you win!

Switch turns with your opponent, and continue rolling and holding until one player wins.

To start a new game, click the "New Game" button.

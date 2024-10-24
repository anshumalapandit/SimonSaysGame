
# Simon Says Game

## Project Overview

This project is a simple **Simon Says Game** built using **HTML**, **CSS**, and **JavaScript**. The game challenges players to remember and repeat a sequence of colors that gets longer with each level. If the player makes a mistake, the game ends and shows their score. This project demonstrates my ability to create interactive web applications using basic web technologies.

## Features

- **Random Color Sequence**: The game generates a new color sequence each time you play. It adds one more color to the sequence with each level.
- **User Interaction**: Players interact by clicking on the colored buttons. The game checks if the player’s input matches the correct sequence.
- **Level System**: Every time the player repeats the sequence correctly, they move to the next level, which adds another step to the sequence.
- **Game Over and Restart**: If the player clicks the wrong button, the game shows a "Game Over" message along with their score, and they can press any key to restart the game.

## How to Play

1. Press any key to start the game.
2. Watch the sequence of colors that flashes on the screen.
3. Click the colored buttons in the same order.
4. The game gets harder with each level by adding another color to the sequence.
5. If you click the wrong color, the game ends and shows your score. You can start again by pressing any key.

## Technologies Used

- **HTML**: For the structure of the game.
- **CSS**: To style the buttons and the layout.
- **JavaScript**: To handle the game logic and user interactions.

## Key Code Details

- The game stores the sequence in `gameseq[]` and the user’s clicks in `userseq[]`.
- A random color is chosen from the list of available colors (`red`, `yellow`, `green`, `purple`) each time the game levels up.
- The game compares the player's input to the correct sequence. If the player is correct, they move to the next level. If not, the game ends.

## Installation and Setup

1. **Clone the Repository**  
   To get a copy of the game, clone this repository:
   ```bash
   git clone https://github.com/your-username/simon-says-game.git
   ```

2. **Open the Game**  
   Open the `index.html` file in your browser to start playing.

## Future Enhancements

- **Add Sound**: I plan to add sound effects to make the game more interactive.
- **High Scores**: I might add a high score system to keep track of the best scores.

## What I Learned

- How to manipulate the DOM using JavaScript to create interactive games.
- How to manage game states and create a smooth user experience.
- How to use event listeners to handle user inputs in real time.

Number Guessing Game
A simple number guessing game built with JavaScript where the player tries to guess a secret number between 1 and 20.

Game Features
Randomly generated secret number between 1-20

Score tracking that decreases with each wrong guess

Highscore system to track your best performance

Visual feedback (color changes) for correct/wrong guesses

"Too high/Too low" hints for incorrect guesses

Reset functionality to play again

How to Play
Clone or download this repository

Open index.html in your browser

Enter your guess in the input field

Click the "Check!" button to submit your guess

The game will tell you if your guess is too high, too low, or correct

Try to guess the number before your score reaches 0

Click "Again!" to restart the game

Game Logic
The secret number is randomly generated when the game starts or resets

Each wrong guess decreases your score by 1

If you guess correctly:

The background turns green

The secret number is revealed

Your highscore updates if you beat your previous best

If your score reaches 0, you lose the game

Code Structure
The game is implemented in a single JavaScript file with the following components:

Variables:

secretNumber: The number to guess (1-20)

score: Current player score (starts at 20)

highscore: Best score achieved

Functions:

displayMessage(): Updates the message display

Event listeners for "Check!" and "Again!" buttons

Technologies Used
HTML5

CSS3

JavaScript (ES6)

Future Improvements
Add difficulty levels (different number ranges)

Implement animations for better user experience

Add sound effects

Create a mobile-friendly version

Add multiplayer functionality

How to Contribute
Fork the project

Create your feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some AmazingFeature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request

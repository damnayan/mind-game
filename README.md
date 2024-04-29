# mind-game
This Python script is a simple, interactive command-line version of the classic game Mastermind. In this game, players attempt to guess a secret code consisting of a series of colors. The player has a limited number of tries to guess the code based on feedback provided after each guess.
Key Features:

Secret Code Generation: A random sequence of colors is generated as the secret code at the beginning of each game.
Interactive Guessing: Players input their guesses, and the script checks for the correctness of the colors and their positions.
Feedback System: After each guess, the script provides feedback indicating the number of correctly guessed colors in the correct positions and the number of correct colors in incorrect positions.
Limited Attempts: Players have a set number of tries to guess the code, enhancing the challenge.
Technologies Used:

Python 3.
Standard Libraries: random
Gameplay Instructions:

Run the script to start the game.
You will be prompted to guess a sequence of 4 colors chosen from Red (R), Green (G), Blue (B), Yellow (Y), White (W), and Orange (O).
Enter your guess in the format: "R G B Y". Make sure to separate the colors by spaces.
The game will provide feedback on your guess:
Correct positions: Number of colors that are both correct and in the correct position.
Incorrect positions: Number of correct colors but placed in the wrong position.
Continue guessing until you either guess the code correctly or exhaust your allowed attempts (10 tries).

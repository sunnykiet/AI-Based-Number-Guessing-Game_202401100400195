# AI-Based-Number-Guessing-Game_202401100400195
AI-Based Number Guessing Game

Introduction

The AI-Based Number Guessing Game is a fun and interactive game where players attempt to guess a randomly generated number within a specified range. The game provides hints at specific intervals to assist players and includes a leaderboard to track high scores.

Why We Created This Game

This game was developed to enhance logical thinking and problem-solving skills while making the number guessing experience more engaging. By integrating AI-like hint systems, players can make more informed guesses rather than relying on pure luck. It also serves as a great learning project for beginners in Python, introducing them to concepts such as loops, conditional statements, and random number generation.

Features

Multiple Difficulty Levels: Choose between Easy (1-50), Medium (1-100), and Hard (1-200).

Intelligent Hint System:

Parity Hint (Even/Odd) after 5 attempts.

Divisibility Hint after 10 attempts.

Range Hint after 15 attempts.

Leaderboard: Tracks and displays the highest scores.

User-Friendly Interface: Simple and interactive gameplay.

Replay Option: Players can choose to play again after each round.

AI-Like Guidance: The hint system acts like an AI assistant guiding the player.

Installation

Prerequisites

Ensure you have Python installed on your system. You can download it from Python's official website.

Steps

Clone this repository or download the guessing_game.py file.

Open a terminal or command prompt and navigate to the game directory.

Run the following command:

python guessing_game.py

How to Play

Start the game and enter your name.

Choose a difficulty level.

Try to guess the secret number within 20 attempts.

Use the provided hints to improve your chances.

Your score will be recorded in the leaderboard if it's among the best.

You can choose to play again or exit the game.


Example Output

Welcome to the AI-Based Number Guessing Game!
Enter your name: Sunny Kumar
Choose a difficulty level:
1. Easy (1-50)
2. Medium (1-100)
3. Hard (1-200)
Enter 1, 2, or 3: 1

I have selected a number between 1 and 50.
You have 20 attempts to guess it correctly!
Enter your guess: 25
Too low!
Attempts remaining: 19
Enter your guess: 35
Too high!
Attempts remaining: 18
Enter your guess: 30
Too high!
Attempts remaining: 17
Enter your guess: 27
Congratulations Sunny Kumar! You guessed it in 4 attempts.
Your score for this round is: 17

--- Leaderboard ---
1. Sunny Kumar: 17
-------------------

Do you want to play again? (yes/no): no
Thank you for playing! Goodbye.

ontributions

Contributions are welcome! Feel free to submit issues or pull requests.

Future Enhancements

Implement a graphical user interface (GUI) for a better user experience.

Add sound effects and animations to make the game more interactive.

Introduce additional hint types, such as sum of digits or nearest prime.

Multiplayer mode where players compete against each other in real time.

License

This project is open-source and free to use.

References

Developed with Python

Uses Python’s random module

Inspired by classic number guessing games



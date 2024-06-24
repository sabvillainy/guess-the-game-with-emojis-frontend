# Guess The Game With Emojis - Frontend
Welcome to the frontend repository for the "Guess The Game With Emojis" project. This repository contains the client-side code built using HTML, CSS, and JavaScript. The frontend provides the user interface for the game, allowing users to interact with the game and submit their guesses.

## Project Overview
"Guess The Game With Emojis" is an interactive game where users try to guess the name of a video game based on a series of emojis that represent the game. Each game in the database has a corresponding set of emojis that give users hints about the game title.

## Features
- **Display Emojis:** Shows a random set of emojis that represent a game.
- **Guess Submission:** Allows users to submit their guesses and receive feedback on their correctness.
- **Auto-Complete:** Provides game name suggestions as users type their guesses.

## Structure
The frontend code is structured into the following main parts:
- **HTML:** The main structure and layout of the application.
- **CSS:** Styling for the application, including external Bootstrap integration.
- **JavaScript:** Handles API interactions, form submissions, and dynamic content updates.

## Future Enhancements
### 1. Hint System:
- Users will have 5 attempts to guess the game.
- Initially, only one emoji will be shown.
- For each incorrect guess, an additional emoji and a hint (e.g., Metacritic score, release year, genre) will be revealed.

### 2. Game Over Mechanism:
- The game will end after 5 incorrect guesses, indicating the user did not guess the game.

### 3. User Authentication:
- Implement user authentication to track scores and progress.

### 4. Leaderboard:
- Create a leaderboard to display top players based on their scores.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your code adheres to the project's coding standards and includes appropriate tests.

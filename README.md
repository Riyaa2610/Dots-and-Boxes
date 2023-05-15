# Dots and Boxes Game

## Introduction
Dots and Boxes is a classic pen-and-paper game where two players take turns connecting adjacent dots on a grid. The goal is to create as many boxes as possible by completing the fourth side of a square. Each completed box awards the player with a point, and the player with the highest number of points at the end wins the game.

This GitHub project is an implementation of the Dots and Boxes game using the Qt Creator framework. It provides a graphical user interface (GUI) that allows users to play the game against an AI opponent or another human player.

## Features
- Interactive GUI for a visually appealing gaming experience.
- Two gameplay modes: against an AI opponent or against another human player.
- Player vs. AI mode offers different difficulty levels to challenge the user.
- The AI opponent uses intelligent strategies to make optimal moves.
- Automatic detection of completed boxes and awarding points to the respective player.
- Real-time score tracking during gameplay.
- Game restart option to play multiple rounds without closing the application.
- Easy-to-use interface with clear instructions for playing the game.

## Technologies Used
- Qt Creator: A cross-platform integrated development environment (IDE) for creating Qt-based applications.
- C++: The programming language used to develop the game logic and user interface.
- Qt Widgets: The GUI framework provided by Qt Creator for creating interactive user interfaces.
- Object-Oriented Programming (OOP) principles: The game's code is structured using OOP concepts for modularity and reusability.

## Getting Started
To run the game on your local machine, follow these steps:

1. Ensure that you have Qt Creator installed on your system.
2. Clone this GitHub repository to your local machine.
3. Open the project in Qt Creator.
4. Build and compile the project.
5. Run the application.
6. The game window will appear, and you can start playing by following the on-screen instructions.

## Project Structure
The project's directory structure is organized as follows:

- `src/` - Contains the source code files for the game.
  - `main.cpp` - The entry point of the application.
  - `mainwindow.h` - Header file for the main game window.
  - `mainwindow.cpp` - Source file for the main game window.
  - `gameboard.h` - Header file for the game board logic.
  - `gameboard.cpp` - Source file for the game board logic.
  - `aiplayer.h` - Header file for the AI player logic.
  - `aiplayer.cpp` - Source file for the AI player logic.
  - `player.h` - Header file for the human player logic.
  - `player.cpp` - Source file for the human player logic.
- `resources/` - Contains any additional resources used by the game, such as images or sounds.
- `docs/` - Contains additional documentation or notes related to the project.

## Contributing
Contributions to this project are welcome! If you have any ideas, suggestions, or bug fixes, please feel free to submit a pull request. Be sure to follow the project's code style and guidelines.

## License
This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the code for both commercial and non-commercial purposes.

## Acknowledgments
- The game was inspired by the traditional Dots and Boxes pen-and-paper game.
- Thanks to the Qt Creator development team for providing an excellent framework for building cross-platform applications.
- Appreciation to the open-source community for their contributions and support.

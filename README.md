# 🎮 Python Mini Games Hub

A Python-based **Mini Games Hub** that combines multiple interactive games into a single menu-driven application.

This project is developed using **Object-Oriented Programming (OOP)** concepts in Python. It demonstrates fundamental programming concepts such as classes, objects, methods, conditional statements, loops, lists, user input, and random number generation.

---

## 📌 Project Overview

The **Python Mini Games Hub** is a collection of small interactive games developed as a Python programming project.

Instead of creating each game as a separate program, all games are organized into a single application using a **`MiniGamesHub` class**.

The user can select a game from the main menu and interact with it through the console.

---

## 🎮 Games Included

The application includes the following games:

| No. | Game | Description |
|---|---|---|
| 1 | 🪨📄✂️ Rock Paper Scissors | Player competes against the computer |
| 2 | 🔢 Number Guessing | Player tries to guess a randomly generated number |
| 3 | 🎲 Dice Rolling | Simulates rolling a dice |
| 4 | 🪙 Coin Toss | Simulates a coin toss |
| 5 | 🏏 Mini Cricket | A simple cricket-based interactive game |
| 6 | ⚽ Penalty Shootout | A penalty shootout simulation |
| 7 | 🐍 Python Quiz | Tests basic Python programming knowledge |
| 8 | 🚪 Exit | Exits the application |

---

## 🛠️ Technologies Used

- **Python**
- **Jupyter Notebook**
- **Object-Oriented Programming (OOP)**
- **Python `random` module**

---

## 🧠 Python Concepts Demonstrated

This project demonstrates several fundamental Python concepts:

- Classes and Objects
- `__init__()` constructor
- `self` keyword
- Methods
- Variables and attributes
- Lists
- Conditional statements (`if`, `elif`, `else`)
- Loops
- User input
- String methods
- Random number generation
- `return` statement
- Menu-driven programming
- Basic input validation

---

## 🏗️ Object-Oriented Structure

The project uses a main class:

```python
class MiniGamesHub:

The class contains methods for each game:

MiniGamesHub
│
├── __init__()
├── rock_paper_scissors()
├── number_guessing()
├── dice_rolling()
├── coin_toss()
├── mini_cricket()
├── penalty_shootout()
├── python_quiz()
└── main_menu()

The application is started by creating an object:

game_hub = MiniGamesHub()

and calling:

game_hub.main_menu()
📂 Project Files
Python-Mini-Games-Hub/
│
├── Mini_Games_Hub.ipynb
├── Mini_Games_Hub.py
└── README.md
File Description
File	Description
Mini_Games_Hub.ipynb	Jupyter Notebook containing the project code and outputs
Mini_Games_Hub.py	Complete Python source code
README.md	Project documentation
▶️ How to Run the Project
Option 1: Using Jupyter Notebook
Download or clone this repository.
Open Jupyter Notebook or JupyterLab.
Open:
Mini_Games_Hub.ipynb
Run the cells in order.
The main menu will be displayed.
Select a game by entering the corresponding option.
Option 2: Using Python

Make sure Python is installed on your computer.

Open a terminal in the project folder and run:

python Mini_Games_Hub.py

The main menu will then appear in the console.

🖥️ Main Menu

The application provides a menu-driven interface similar to:

========================================
          MINI GAMES HUB
========================================

1. Rock Paper Scissors
2. Number Guessing
3. Dice Rolling
4. Coin Toss
5. Mini Cricket
6. Penalty Shootout
7. Python Quiz
8. Exit

Enter your choice:
🎯 Project Objectives

The main objectives of this project are:

To develop a menu-driven Python application.
To understand and implement Object-Oriented Programming.
To practice creating classes and objects.
To use Python methods for organizing program functionality.
To work with user input and conditional logic.
To use the random module for game-based operations.
To develop simple interactive console-based applications.
To improve Python programming and problem-solving skills.
💡 Key Learning Outcomes

Through this project, the following concepts were practiced:

1. Classes and Objects

A class is used to organize the complete game application.

class MiniGamesHub:

An object is created using:

game_hub = MiniGamesHub()
2. Constructor

The __init__() method initializes the starting values of the application.

def __init__(self):
    self.player_score = 0
    self.computer_score = 0
3. Methods

Each game is implemented as a separate method, making the program easier to understand and maintain.

4. Random Module

The random module is used to generate unpredictable game results such as computer choices, numbers, dice values, and coin tosses.

📸 Screenshots

Screenshots of the application can be added here to demonstrate the games and their outputs.

Main Menu

Add your main menu screenshot here.

Rock Paper Scissors

Add your Rock Paper Scissors screenshot here.

Number Guessing Game

Add your Number Guessing screenshot here.

Python Quiz

Add your Python Quiz screenshot here.

🔮 Future Enhancements

The project can be extended with additional features such as:

Adding more mini games
Adding difficulty levels
Maintaining detailed game statistics
Adding a graphical user interface (GUI)
Adding sound effects
Saving player scores to a file
Adding multiple-player functionality
Improving input validation
Adding a persistent leaderboard
🎓 Academic Project

This project was developed as part of a Python programming project to demonstrate practical implementation of Python and Object-Oriented Programming concepts.

Institute: Besant Technologies

Project: Python Mini Games Hub

👩‍💻 Author

Priyanka

Python Learner | Aspiring Software Developer

📄 License

This project is created for educational and learning purposes.


### One small change I recommend

Since your actual GitHub repository is:

**`Python-Mini-Games-Hub`**

your README's project title can stay:

> **Python Mini Games Hub**

That's cleaner than making the title exactly match the repository name.

Also, **don't add screenshots yet** unless you have uploaded them to GitHub. Once you upload them, I can

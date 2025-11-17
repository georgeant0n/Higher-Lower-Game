# 📈 Higher Lower Game

A simple "Higher Lower" game for the terminal, written in Python. Can you guess which social media account has more followers?

📖 About This Project

This project is a text-based game that challenges you to guess which of two given accounts has more social media followers. The game pulls data from a local data file (game_data.py), presents you with two options, and you must choose 'A' or 'B'. If you're correct, your score increases, and you continue your streak. If you're wrong, the game ends.

✨ Features

Real Data: Uses a pre-defined list of social media accounts (from game_data.py) with their follower counts.

Score Tracking: The game keeps track of your score, rewarding you for each correct answer.

Endless Gameplay: The game continues indefinitely until you make an incorrect guess.

Clear UI: Uses ASCII art (from the art library) to create a clean visual separation between rounds.

Reusable Functions: The code is structured with helper functions (format_data, check_answer) for clarity and maintainability.

🚀 How to Run This Project

To run the game on your local machine, follow these steps:

Prerequisites

Python 3

pip (usually installed with Python)

Installation & Execution

Clone the repository:

git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)


(Replace your-username/your-repository-name with your actual username and repo name)

Navigate to the project directory:

cd your-repository-name


Install the required dependencies:
This project uses the art library to display the logos.

pip install art


Ensure all game files are present:
This script (main.py or game.py) relies on two other files in the same directory:

game_data.py (which contains the data list)

art.py (which contains the logo and vs variables - Note: this is imported from the art library, so game_data.py is the main local dependency)

Make sure you have the game_data.py file with the list of data dictionaries in the same folder as your main game script.

Run the game:

python main.py


(Or python game.py, depending on what you named your main file)

🕹️ How to Play

Run the script.

You will be presented with "Compare A:" and "Against B:", each describing a social media account.

Type A or B to guess which account has more followers.

The screen will clear, and you'll be told if you were right or wrong.

If you are correct, your score increases, and the account from 'B' moves to the 'A' position for the next round.

If you are wrong, the game ends and displays your final score.

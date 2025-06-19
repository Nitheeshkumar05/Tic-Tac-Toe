🎮 Tic-Tac-Toe (Single Player & Two Player) — Python Tkinter
A beautifully designed Tic-Tac-Toe game with both Single Player (vs Computer) and Two Player modes, built using Python Tkinter GUI library.
The game offers a clean, modern interface with dynamic highlights, winning move effects, and a basic AI for the computer opponent.

📸 Project Overview
✅ Play Single Player vs Computer (with simple AI strategy)
✅ Play Two Players locally taking turns
✅ Modern, styled Tkinter interface with button animations
✅ Highlights the winning move positions in gold
✅ Displays game over dialogs for win, loss, or draw
✅ Easy-to-use Reset Game button

📽️ How It Works
The game window displays a 3x3 grid of buttons representing the Tic-Tac-Toe board.

Choose between Single Player (vs Computer) and Two Player modes before starting.

Players take turns placing their mark (X or O) by clicking on the grid.

In Single Player, the computer responds automatically based on:

Try to win if possible.

Block the player if they’re about to win.

Take the center if available.

Otherwise pick a random available move.

Winning positions are highlighted in gold.

Game result dialogs display when there's a win, draw, or reset.

📦 Requirements
Package	Recommended Version
Python	3.8+
tkinter	Comes built-in with Python

✅ No external libraries needed — only built-in tkinter and random.

📥 Installation
1️⃣ Clone the repository

bash
Copy
Edit
git clone https://github.com/yourusername/tkinter-tic-tac-toe.git
cd tkinter-tic-tac-toe
2️⃣ Run the application

bash
Copy
Edit
python main.py
✅ No extra installations or requirements. Works out of the box with Python 3.8+.

📂 Folder Structure
css
Copy
Edit
tkinter-tic-tac-toe/
│
├── main.py         # Main game code
├── README.md       # Project description
📌 Features
🎮 Single Player Mode with simple AI

🎮 Two Player Mode on the same device

✨ Modern themed Tkinter interface

✨ Dynamic color highlights (Red for X, Blue for O)

🏆 Winning positions highlighted in Gold

📊 Message boxes for Win / Draw / Reset

🔁 Reset Game button to start fresh

🤖 AI tries to win, block or pick center intelligently

📋 Notes
No external installations required — runs with native Python and tkinter.

Ensure Python 3.8+ is installed.

Works on Windows, macOS, and Linux.

💡 Future Enhancements
🎨 Add theme switching (light/dark mode)

📈 Add score tracking system

🌐 Build a network multiplayer version

🙌 Author
Nitheesh Kumar
GitHub

📌 Final Note
This project is intended for educational and entertainment purposes, designed to demonstrate Python’s GUI capabilities using tkinter and implementing game logic with a simple AI.

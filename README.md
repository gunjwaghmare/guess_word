# Guess Word Game

A simple interactive word guessing game built with **Python** and **Flask**. Users can register, log in, and play the game by guessing letters of a hidden word. The app tracks attempts and maintains a leaderboard of top players.

---

## Features

- User registration and login with password hashing
- Play the word guessing game by entering letters
- Track attempts for each word
- Leaderboard showing top players by score
- Responsive interface using Bootstrap

---

## Folder Structure
│
├── app.py                # Main Flask application
├── guess_game.db         # SQLite database (auto-created)
├── templates/            # HTML templates for UI
│   ├── base.html
│   ├── home.html
│   ├── login.html
│   ├── register.html
│   └── game.html
├── static/               # Optional: images, JS, or CSS
└── README.md             # Project description
---

## Requirements

- Python 3.9+
- Flask
- Flask-Bcrypt
- Flask-SQLAlchemy

Install dependencies:

```bash
pip install flask flask-bcrypt flask-sqlalchemy
How to Run
	1.	Clone the repository:
git clone https://github.com/your-username/guess_word.git
cd guess_word
	3.	Run the app:
python app.py
Open your browser at:
http://127.0.0.1:5000/
How to Play
	1.	Register a new user account or log in.
	2.	Click Start Game on the home page.
	3.	Guess letters to reveal the hidden word.
	4.	Attempts are tracked and points are awarded based on performance.
	5.	Leaderboard shows top players by score.

⸻

Notes
	•	Database is automatically created on first run (guess_game.db).
	•	Passwords are securely hashed using Flask-Bcrypt.
	•	The app uses Bootstrap for a clean and responsive interface.

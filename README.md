# 🪢 Hangman Game (Python)

## 📖 Overview
This is a **console-based Hangman game** written in Python. The program randomly selects a word from a custom list (`names_hangman.py`) and challenges the player to guess it letter by letter. Each incorrect guess reduces the number of lives and updates the ASCII-art hangman drawing.

## 🚀 Features
- Random word selection from `names_hangman.py`
- ASCII art visualization of the hangman’s progress
- Tracks guessed letters to prevent duplicates
- Win/lose conditions with clear messages
- Simple, beginner-friendly Python code


## 🛠️ Requirements
- Python 3.7 or higher  
- `names_hangman.py` file containing a list of words (variable: `names`)

Example `names_hangman.py`:
```python
names = ["python", "hangman", "developer", "analysis", "science"]
```

## ▶️ How to Run
1. Clone or download this repository.
   ```bash
   git clone https://github.com/your-username/hangman-game.git
   ```
2. Navigate into the project folder:
   ```bash
   cd hangman-game
   ```
3. Ensure you have a `names_hangman.py` file with a list of words.
4. Run the game:
   ```bash
   python hangman.py
   ```

## 🎮 Gameplay Instructions
- The program randomly selects a word from the `names` list.
- You guess one letter at a time.
- Each incorrect guess reduces your lives and updates the hangman drawing.
- Win by revealing all letters before lives run out.
- Lose if the hangman is fully drawn before you guess the word.


## 📂 Project Structure
```
hangman-game/
│── hangman.py         # Main game script
│── names_hangman.py   # Word list file (must define 'names')
│── README.md          # Project documentation
```

---

## ✨ Future Improvements
- Add difficulty levels (easy, medium, hard)
- Load words from external files or APIs
- Track scores across multiple rounds
- GUI version using Tkinter or PyQt

## 🤝 Contributing
Pull requests are welcome! If you’d like to add new features or improve the code, please fork the repo and submit a PR.


👉 Would you like me to also **write a sample `names_hangman.py` file** for you, so your README includes a ready-to-use word list? That way, anyone cloning your repo can run the game immediately without setup issues.

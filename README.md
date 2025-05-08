```markdown
# Wordle Recreation

Welcome! This is a Python remake of the classic Wordle game, built as my class 12 project. My goal was to capture the fun and challenge of Wordle while adding user accounts, stats, and a simple GUI-making it easy for anyone to play and track their progress.

---

## 🎮 What’s Inside?

- **Full Wordle Gameplay:** Guess a 5-letter word in 6 tries, with color-coded feedback (green, yellow, grey) just like the real thing.
- **User Accounts:** Sign up, log in, or play as a guest. Your stats and progress are saved.
- **Stats & Leaderboard:** Track your wins, streaks, and see how you stack up against others.
- **Easy-to-Use Interface:** Built with `tkinter` for a straightforward, click-and-play experience.
- **Data-Driven:** Uses official and extended word lists for realistic gameplay.

---

## 📁 Project Structure


wordle_recreation/
│
├── data/
│   ├── 5-letter(12972)CSVwords.txt
│   ├── OfficialWordles(2315)CSV.txt
│   └── UserDatabase.csv
│
├── src/
│   └── wordle_recreation.py
│
├── docs/
│   └── Final-Code.txt
│
├── README.md
└── LICENSE



## 🚀 Getting Started

1. Make sure you have Python 3 installed.
2. Put all required data files in the `data/` folder.
3. Run the game:
   
   python src/wordle_recreation.py
   
4. Follow the prompts to log in, sign up, or play as a guest.

---

## 🕹️ How to Play

- Enter a valid 5-letter word and click **Check**.
- **Green:** Letter is correct and in the right spot.
- **Yellow:** Letter is in the word but in the wrong spot.
- **Grey:** Letter isn’t in the word.
- You have 6 attempts to guess the word.
- Check your stats and the leaderboard from the main menu.

---

## 📝 Notes

- All user data is saved in `data/UserDatabase.csv`.
- Word lists are in `data/OfficialWordles(2315)CSV.txt` and `data/5-letter(12972)CSVwords.txt`.
- If you run into issues, double-check that all files are in the right place and you have permission to read/write them.

---

Thanks for checking out my project!  
If you have feedback or spot a bug, feel free to open an issue or suggest improvements.  
Enjoy playing Wordle in Python!

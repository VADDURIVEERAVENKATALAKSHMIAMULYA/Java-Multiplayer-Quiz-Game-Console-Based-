# Java-Multiplayer-Quiz-Game-Console-Based-
A **Java-based console application** that allows users to play quiz games in both **single-player** and **multiplayer** modes. Designed for fun and learning, this project supports scoring, explanations for incorrect answers, and multi-user gameplay with turn-based interaction.

---

## Features

* 🔐 User login system (by email)
* 🧠 Randomized multiple-choice questions from a file
* ✨ Instant feedback with detailed explanations for incorrect answers
* 🧑‍🤝‍🧑 Multiplayer mode with custom player count and turn-based play
* 📊 Score tracking and history logging
* 📁 Easy-to-edit questions (`questions.txt`)

---

## Project Structure

```
src/
└── main/
    └── QuizProject/
        ├── Main.java            # Entry point
        ├── QuizEngine.java      # Quiz logic (single + multiplayer)
        ├── Question.java        # Question model
        ├── Player.java          # Multiplayer player model
        ├── ScoreManager.java    # Score tracking
        └── questions.txt        # Question bank
```

---

## Sample Question Format (`questions.txt`)

Each line follows this format:

```
Question|OptionA|OptionB|OptionC|OptionD|CorrectAnswer|Explanation
```

### Example:

```
What is the size of int in Java?|4 bytes|8 bytes|2 bytes|Depends on system|A|In Java, int is always 4 bytes regardless of the platform.
```

---

## How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/java-multiplayer-quiz-game.git
   ```
2. Open the project in your Java IDE (e.g., IntelliJ, Eclipse, VS Code)
3. Make sure your question file is placed in:

   ```
   src/main/QuizProject/questions.txt
   ```
4. Run `Main.java`
5. Choose single-player or multiplayer mode and enjoy!
---
## Future Enhancements

* 💬 Chat system for multiplayer users
* 🎨 GUI version using JavaFX or Swing
* 🌍 Online multiplayer support via sockets
* 🏆 Leaderboard with persistent storage
---
## License
This project is open-source and free to use for educational and personal use.

Happy quizzing! 🎉

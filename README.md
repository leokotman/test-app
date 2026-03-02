# Quiz CLI

> 🎮 An interactive command-line quiz game built with Node.js - Test your JavaScript and programming knowledge!

A lightweight, dependency-free terminal quiz application featuring colorful output, progress tracking, and instant feedback. Perfect for developers looking to test their knowledge or learn while having fun!

---

## ✨ Features

- 📚 **15 Curated Questions** - Covering JavaScript Basics, Node.js Fundamentals, and General Programming
- 🎨 **Colorful Terminal Output** - Beautiful ANSI-colored interface for enhanced readability
- 📊 **Real-time Progress Tracking** - Visual progress bar showing your advancement
- 🔀 **Randomized Questions** - Fisher-Yates shuffle algorithm ensures unique quiz experiences
- 💡 **Educational Explanations** - Learn from detailed answer explanations
- 📝 **Review Incorrect Answers** - Review what you missed after completing the quiz
- 🔁 **Replay Functionality** - Take the quiz again to improve your score
- ⚡ **Zero Dependencies** - Built entirely with Node.js built-in modules
- 🎯 **Performance Feedback** - Get personalized feedback based on your score

---

## 📋 Prerequisites

Before running this application, ensure you have:

- **Node.js** >= 18.0.0 installed
- Terminal/Command Prompt with ANSI color support (most modern terminals)

Check your Node.js version:
```bash
node --version
```

---

## 🚀 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/quiz-cli.git
   cd quiz-cli
   ```

2. **No installation needed!** 🎉

   This project uses zero external dependencies - it's ready to run immediately!

---

## 🎮 Usage

Start the quiz with either command:

```bash
npm start
```

or

```bash
node index.js
```

---

## 📁 Project Structure

```
quiz-cli/
├── index.js                 # Application entry point - initializes and starts the quiz
├── package.json             # NPM configuration and project metadata
├── src/
│   ├── quiz.js             # Core Quiz class with game logic and flow control
│   ├── input.js            # Readline wrapper for handling user input
│   └── colors.js           # ANSI terminal color utilities for styled output
└── data/
    └── questions.json      # Question bank with categories and explanations
```

### File Descriptions

| File | Purpose |
|------|---------|
| `index.js` | Main entry point that initializes and launches the quiz application |
| `src/quiz.js` | Contains the `Quiz` class with methods for game flow, scoring, and question management |
| `src/input.js` | Wrapper around Node.js `readline` module for simplified async user input |
| `src/colors.js` | Utility functions for ANSI escape codes to add colors to terminal output |
| `data/questions.json` | JSON database containing quiz questions, answers, and explanations |

---

## 🎯 How to Play

1. **Start the Quiz** - Run the application using the commands above
2. **Read Each Question** - Questions are displayed one at a time with multiple choice options
3. **Enter Your Answer** - Type the letter (A, B, C, or D) corresponding to your choice
4. **Get Instant Feedback** - See if you're correct with color-coded responses:
   - ✅ **Green** = Correct answer
   - ❌ **Red** = Incorrect answer
5. **View Explanations** - Learn from detailed explanations after each question
6. **Track Progress** - Watch the progress bar fill as you advance
7. **Review Performance** - At the end, see your final score and performance rating
8. **Review Mistakes** - Option to review all incorrect answers
9. **Play Again** - Choose to retake the quiz and improve your score!

### Performance Ratings

- 🏆 **80-100%** - Excellent! You're a programming wizard!
- 👍 **60-79%** - Good job! You have solid knowledge!
- 📚 **40-59%** - Not bad! Keep learning and practicing!
- 💪 **0-39%** - Keep going! Every expert was once a beginner!
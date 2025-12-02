# 🧠 Quiz Game in C

A simple console-based **General Knowledge Quiz Game** built in **C programming language**.
The game tests the player's knowledge through 10 basic MCQ questions and stores the score in a scoreboard file.

---

## 📌 Features

✔ **10 General Knowledge Questions**
✔ **Scoreboard system** using text file (`Quiz score.txt`)
✔ Shows **Correct/Wrong** feedback instantly
✔ Prevents invalid input using re-attempt
✔ Allows users to **Replay**
✔ Clean and simple console UI

---

## 🎮 How to Play

When you run the program, you’ll see 3 options:

```
1. Start Quiz  
2. Show Scoreboard  
3. Quit
```

### 👉 1. Start Quiz

* Each question has 4 options
* Correct answer → “Correct!”
* Wrong answer → shows correct answer
* Invalid input → repeats the same question
* After 10 questions, final result will be shown
* User can enter name and save score

### 👉 2. Show Scoreboard

* Displays all previous scores stored in `Quiz score.txt`
  
  ![Scoreboard Preview](https://drive.google.com/uc?export=view&id=1wLQhiHWfrR9SmqreqjcJE3YNhOI2ehYo)

### 👉 3. Quit

* Exits the game

---

## 🧪 Project Structure

```
📁 Quiz-Game-C
 ├── quiz_game.c
 ├── Quiz score.txt
 └── README.md
```

---

## 🛠 Technologies Used

* **C Language**
* `stdio.h`, `stdlib.h`, `conio.h`
* File handling (`fopen`, `fscanf`, `fprintf`)

---

## 🚀 How to Run

### Windows / Linux / Mac

1. Compile the code

   ```bash
   gcc quiz_game.c -o quiz
   ```
2. Run

   ```bash
   ./quiz
   ```

---

## 📸 Output Preview

```
Welcome to the QUIZ GAME
-------------------------------
The quiz has 10 very basic questions...

1. Start Quiz
2. Show Scoreboard
3. Quit
```

---

## 📂 Scoreboard Example

```
Name: Rahim, Score: 7
Name: Karim, Score: 9
Name: Sifat, Score: 10
```

---

## 📖 Summary

This project is a perfect beginner-friendly C program demonstrating:

* Conditional statements
* Loops
* File handling
* User input validation
* Basic UI/UX in console

Feel free to modify the quiz questions or improve the UI!

---

## ⭐ Suggestions for Improvement

Want to extend it further? Try adding:

* Timer for each question
* Difficulty levels
* Randomized questions
* GUI version using C++/SDL


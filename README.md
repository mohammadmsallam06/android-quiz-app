# QuizApp – Android Application (Java)

A fully functional Quiz Android application built using *Java* and *Android Studio*.  
The app allows users to take quizzes, track their score, customize settings, and view final results with a clean and simple UI.

This project demonstrates your skills in:
- Android development (Activities, Intents, UI Components)
- Java OOP
- Managing timers, user input, event listeners
- Working with SQLite or static data (according to the file structure)
- Building multi-screen applications

---

## 📌 Features

### 🏠 1. Home Screen
- Start the quiz
- Open settings
- Clean and minimal interface

### 🧠 2. Quiz Play Screen
- Displays questions and 4 multiple-choice answers
- Countdown timer for each question
- Highlights the correct/wrong answer
- Moves automatically to the next question
- Tracks:
  - Score
  - Correct answers
  - Wrong answers
  - Total questions

### ⚙ 3. Settings Screen
Users can:
- Enable / Disable sound effects
- Allow/disallow skipping questions
- Reset saved preferences

### 🏁 4. Results Screen
Shows detailed results:
- Final score  
- Number of correct and incorrect answers  
- Option to restart quiz  

---

## 📁 Project Structure
/app
└── /src
└── /main
└── /java/com/example/quizapp
├── HomeActivity.java
├── playActivity.java
├── settingActivity.java
├── ResulteActivity.java
├── QuestionsHolder.java
├── QuestionAnswer.java
└── Stopwatch.java
---

## 🛠 Tech Stack

- *Java (Android)*  
- *XML layouts*  
- *Android Studio*  
- *OOP & Interfaces*  
- *Timers & Handlers*  
- *SharedPreferences* (for settings)

---

## ▶ How to Run

1. Open the project in *Android Studio*
2. Sync Gradle
3. Run the app on:
   - Physical Android device  
   - OR Android Emulator  
4. The app starts at *HomeActivity*

---

## 🎯 Purpose of the Project

This project was built to practice:
- Android app development
- Event-driven programming
- UI/UX basics
- Working with multiple activities
- Building a complete mobile application from scratch

---

## 👤 Author

Mohammad Musallam
---

## 📜 License

This project is for educational and learning purposes.  
Feel free to use or modify it.

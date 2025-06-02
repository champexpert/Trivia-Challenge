# 🧠 Trivia Challenge App

A fun, interactive quiz game built with **Python** and **Tkinter** GUI.

## 🎮 Features

- 20 multiple-choice trivia questions
- Real-time score tracking
- Instant feedback after each answer
- User-friendly interface with visually styled buttons and labels
- Pop-up final score summary

## 🖼️ Preview

*(Add a screenshot here if you want to show the interface)*

## 📁 File Structure

trivia_app/
├── trivia_quiz.py # Main Python script (GUI + logic)
├── README.md # Project documentation

bash
Copiar
Editar

## ▶️ How to Run

1. Make sure you have Python 3 installed.
2. Clone the repository:
   ```bash
   git clone https://github.com/your-username/trivia_app.git
   cd trivia_app
Run the app:

bash
Copiar
Editar
python trivia_quiz.py
🧱 Dependencies
Python Standard Library:

tkinter (built-in GUI library)

messagebox from tkinter

No external libraries required!

👨‍💻 Code Overview
The app is structured using a class called TriviaApp:

Question Bank: Stored in a list of dictionaries, each with a question, four options, and the index of the correct answer.

UI Elements: Includes Label, Radiobutton, Button, and message pop-ups using tkinter.messagebox.

Logic Flow:

Loads one question at a time.

Tracks the selected answer.

Provides instant feedback.

Ends with a final score alert.

📌 Future Improvements
Add categories and difficulty levels

Include a timer for each question

Store scores in a local file or database

Improve visual styling with custom themes

📝 License
This project is open-source and free to use under the MIT License.

Enjoy the quiz and challenge your brain!

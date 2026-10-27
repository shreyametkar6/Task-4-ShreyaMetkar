# Task 4: General Knowledge Quiz (Python)

## Description
A command-line multiple-choice quiz written in Python. The program asks 3 general knowledge questions, each with 4 options (A, B, C, D), and gives +1 point for each correct answer. At the end it prints the final score. Answers are cleaned with `.strip().lower()`, so extra spaces and capital letters don't cause wrong marks.

Built as **Task 4** of my Python Programming Internship at **DecodeLabs** (Batch 2026).

## Features
- 3 questions with 4 options each (A, B, C, D)
- Score counter (+1 per correct answer)
- Answers ignore extra spaces and capital letters
- Invalid choices (like `x`) are rejected and asked again
- Shows the correct option when you get one wrong
- Final score with a feedback message

## How to Run
1. Install Python and Jupyter Notebook.
2. Download this repository (green **Code** button, then **Download ZIP**) and extract it.
3. Open a terminal in the extracted folder and start Jupyter:

```
jupyter notebook
```

4. Open `gk_quiz.ipynb`.
5. Click the code cell and press **Shift + Enter** to run it.
6. Type A, B, C or D for each question and press Enter.

## Example
```
===== GENERAL KNOWLEDGE QUIZ =====

Answer 3 questions. You get +1 point for each correct answer.

Q1. What is the capital of France?
   A) London
   B) Paris
   C) Berlin
   D) Madrid
Your answer (A/B/C/D): b
Correct! +1 point

Q3. What is the largest ocean on Earth?
   A) Atlantic
   B) Indian
   C) Arctic
   D) Pacific
Your answer (A/B/C/D): a
Wrong. The correct answer is D) Pacific

=============================
Final score:  2 out of 3
=============================
Good job! Almost there.
```

## Concepts Used
- `if / elif / else` control flow
- Score counter variable (`score = 0`, `score += 1`)
- Input sanitization with `.strip()` and `.lower()`
- Lists and Dictionaries to store the questions
- f-strings for output
- Functions and a `for` loop with `enumerate()`

## Author
Shreya Metkar - [GitHub](https://github.com/shreyametkar6)

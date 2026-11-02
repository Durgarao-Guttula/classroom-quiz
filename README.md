<p align="center"><img src="logo.png" alt="RV University" height="80"></p>

# Classroom Quiz

A classroom quiz that runs on the teacher's Windows laptop. Questions come from an Excel sheet;
students join by scanning a QR code on the classroom WiFi and answer on their phones, with instant
right/wrong feedback and an explanation. No internet, accounts or phone app needed.

## Get started

1. Click the green **Code** button → **Download ZIP**, and unzip it (e.g. into Documents).
2. Double-click **ClassroomQuiz.exe**. Your browser opens the start page.
3. Read **[HOW-TO-USE.txt](HOW-TO-USE.txt)** for first-run warnings, classroom WiFi and writing questions.

Keep `questions.xlsx` and the `images` folder in the same folder as the exe.

## Files

| File | What it is |
|---|---|
| `ClassroomQuiz.exe` | The app |
| `questions.xlsx` | Sample quizzes showing every feature: *All question types*, *Picture questions*, *Quick 5-question quiz* |
| `template.xlsx` | A blank starting point for your own questions |
| `images/` | Pictures used by the sample questions (periodic table, circuit, triangle, solar system, graph) |
| `HOW-TO-USE.txt` | Guide for teachers |

## What it can do

| Feature | |
|---|---|
| **MCQ** | 2 to 6 options |
| **True/False** | |
| **Short answer** | Students type; several accepted answers; numbers match by value |
| **Word cloud** | Answers shown as a cloud on the projector; not scored |
| **Pictures** | Any question can show a diagram, graph or photo, on the projector and on every phone |
| **Explanations** | Shown to students after each reveal |
| **League** | Top 10 after every question, by anonymous 3-digit ID |

## First run

Windows may say *"Windows protected your PC"*: click **More info → Run anyway**. Allow the firewall
prompt for **Private networks**, or phones cannot connect. To check your copy is genuine, run
`certutil -hashfile ClassroomQuiz.exe SHA256` in Command Prompt; it should print
`98ba6f1d5306ba458a62635bbe23db2301da5c8342e96a7d732f6077c9f2c035`.

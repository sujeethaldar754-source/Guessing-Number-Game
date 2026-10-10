# 🎯 Number Guessing Game

A number guessing game that starts as a simple C console program and is rebuilt as an interactive web app with a clean UI.

🔗Live demo: file:///C:/Users/user/Downloads/Guess%20the%20Number.html

## How it works
The game picks a random number from 1 to 100. After each guess you get a hint to go higher or lower, and the game shows how close you are. Keep guessing until you find the number.

## Features
- Random number from 1 to 100
- "Go higher" and "go lower" hints, plus closeness feedback
- Number line that narrows to the range the number can still be in
- Guess history and a best score saved in the browser
- Input validation for numbers that are not whole or not in range
- Works on mobile, with light and dark themes

## Versions

### C version (console)
```bash
gcc guess.c -o guess
./guess
```

### Web version
Open `index.html` in any browser. No installation needed.

## What I practiced
- C: `rand()`, `srand(time(NULL))`, loops, conditions
- Rebuilding the same logic in JavaScript and DOM manipulation
- Responsive layout and theming with CSS

## Project structure
```
├── guess.c       # console version in C
├── index.html    # web version
└── README.md
```

## Author
sujit haldar· [LinkedIn](www.linkedin.com/in/sujit-haldar)

# 🎯 The Git Relay Challenge

Welcome to **The Git Relay** - a collaborative coding challenge where teamwork and problem-solving skills are put to the test!

## 📋 Rules of the Game

### Team Structure

- **Teams of 3-4 members**
- Each member tackles one problem sequentially
- Solutions provide clues for the next challenge
- **Each question contains exactly 4 errors: 2 logical + 2 syntax**

### How It Works

1. **Team creates a fork** of this repository
2. **Member 1** solves Problem 1, gets a clue, pastes it in the solution comment, and pushes to the fork
3. **Member 2** pulls the updated fork, uses the clue to solve Problem 2, gets another clue, and pushes
4. **Member 3** pulls, uses the clue to solve Problem 3, gets the final clue, and pushes
5. **Member 4** pulls, uses all clues to solve the final puzzle

### Challenge Flow

```
Problem 1 (C) → Clue A → Problem 2 (C++) → Clue B → Problem 3 (Python) → Clue C → Problem 4 (Java) → Final Solution
```

### Git Workflow

1. **Fork this repository** to your team account
2. **Share the fork link** with all team members
3. **Work sequentially** - one member at a time
4. **Pull before starting** your assigned problem
5. **Push after solving** to share your clue with the next member

## 🛠️ Prerequisites

Before starting, ensure you have the following installed:

### For C Programming (Problem 1)

- **GCC Compiler** (MinGW on Windows, gcc on Linux/Mac)
- Command to test: `gcc --version`

### For C++ Programming (Problem 2)

- **G++ Compiler** (included with GCC)
- Command to test: `g++ --version`

### For Python (Problem 3)

- **Python 3.x** interpreter
- Command to test: `python --version` or `python3 --version`

### For Java (Problem 4)

- **JDK 8 or higher** (includes JRE and JVM)
- Command to test: `javac --version` and `java --version`

### Git Requirements

- **Git** installed and configured
- **GitHub account** for forking
- Basic knowledge of `git pull` and `git push`

## 🚀 Getting Started

1. **Fork this repository**

   ```bash
   # Go to GitHub and click "Fork" button
   # Then clone your fork:
   git clone <your-fork-url>
   cd git-relay-challenge
   ```

2. **Team member assignment**

   - Member 1: Problem 1 (C)
   - Member 2: Problem 2 (C++)
   - Member 3: Problem 3 (Python)
   - Member 4: Problem 4 (Java)

3. **Sequential workflow**

   ```bash
   # Before starting your problem:
   git pull origin main

   # After solving and adding your clue:
   git add .
   git commit -m "Solved Problem X - Added clue for next member"
   git push origin main
   ```

## 🎮 Challenge Overview

### Problem 1: C Programming 

**Focus**: Array manipulation and basic algorithms
**Errors**: 2 logical + 2 syntax errors
**Output**: Clue for C++ problem

### Problem 2: C++ Programming 

**Focus**: Object-oriented programming and STL
**Errors**: 2 logical + 2 syntax errors  
**Output**: Clue for Python problem

### Problem 3: Python 

**Focus**: Data structures and string manipulation
**Errors**: 2 logical + 2 syntax errors
**Output**: Clue for final problem

### Problem 4: Final Challenge 

**Focus**: Integration of all clues
**Errors**: 2 logical + 2 syntax errors
**Output**: Final solution!

## 🔍 Error Types to Look For

Each problem contains exactly **4 errors**:

- **2 Logical Errors**: Wrong algorithms, incorrect conditions, wrong operations
- **2 Syntax Errors**: Missing semicolons, incorrect function calls, typos, wrong operators

## 🏆 Winning Condition

Successfully solve all 4 problems as a team and piece together the final solution from all clues!

## 💡 Tips for Success

1. **Read the goal comment carefully** - it explains what the code should do
2. **Test frequently** - compile/run after each fix
3. **Communicate with teammates** - share progress and clues immediately
4. **Don't overthink** - errors are designed to be fixable within 10 minutes
5. **Follow the Git workflow** - pull before starting, push after solving

## 🤝 Collaboration Guidelines

1. **Work sequentially** - only one person works on their assigned problem at a time
2. **Pull before starting** - always get the latest clues from previous members
3. **Clear commit messages** - help your teammates understand your progress
4. **Share clues immediately** - paste the clue in the solution comment and push
5. **Help each other** - but let each person solve their assigned problem

## 📝 Solution Format

When you solve your problem, paste **ONLY the clue** (not the entire corrected code) in the solution comment at the end of your file, then commit and push.

Example:

```c
/*
SOLUTION - PASTE YOUR CLUE HERE:
Member Name: John Doe
Clue for next problem: [7, 15, 23, 31]
*/
```

---

**Good luck, and may the best team win! 🚀**

_Remember: This is about teamwork, problem-solving, and Git collaboration. Have fun!_

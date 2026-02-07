# 🐍💧🔫 Snake Water Gun Game in C

![Language](https://img.shields.io/badge/language-C-blue.svg)
![Status](https://img.shields.io/badge/status-Complete-green.svg)
![License](https://img.shields.io/badge/license-MIT-lightgrey.svg)

## 📖 Overview

**Snake Water Gun** is a command-line interface (CLI) implementation of the classic childhood game (a variation of Rock-Paper-Scissors). Built in **C**, this project demonstrates user interaction, random number generation, and conditional logic.

The user plays against the computer, which makes random decisions, ensuring a unique outcome every round.

## 🎮 Game Rules

The logic follows a simple cyclic hierarchy:

* **Snake (s)** drinks **Water (w)** $\rightarrow$ **Snake Wins**
* **Water (w)** drowns **Gun (g)** $\rightarrow$ **Water Wins**
* **Gun (g)** shoots **Snake (s)** $\rightarrow$ **Gun Wins**
* **Same choice** $\rightarrow$ **Draw**

| You Choose | Computer Chooses | Result |
| :--- | :--- | :--- |
| Snake (s) | Water (w) | ✅ Win |
| Snake (s) | Gun (g) | ❌ Lose |
| Water (w) | Gun (g) | ✅ Win |
| Water (w) | Snake (s) | ❌ Lose |
| Gun (g) | Snake (s) | ✅ Win |
| Gun (g) | Water (w) | ❌ Lose |

## 🛠️ Tech Stack & Concepts

This project showcases the following C programming concepts:
* **Control Flow:** Uses `if-else` ladders to determine game outcomes.
* **Randomization:** Utilizes `rand()` and `srand(time(0))` to generate unpredictable computer moves.
* **Input/Output:** Handles character input (`scanf`) and formats output (`printf`).
* **Logic Building:** Implements the game algorithm efficiently.

## 🚀 Getting Started

Follow these steps to run the game on your local machine.

### Prerequisites
You need a C compiler (like GCC) installed.
* **Windows:** MinGW or Visual Studio Code with C extensions.
* **Linux/macOS:** GCC is usually pre-installed.

### Installation & Run

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/your-username/snake-water-gun.git](https://github.com/your-username/snake-water-gun.git)
    cd snake-water-gun
    ```

2.  **Compile the Code**
    Open your terminal/command prompt and run:
    ```bash
    gcc project_2_.c -o game
    ```

3.  **Run the Game**
    * **Windows:**
        ```bash
        .\game.exe
        ```
    * **Linux/Mac:**
        ```bash
        ./game
        ```

**Created by Saniya Mir**

## 📸 Usage Example

Here is an example of the game running in the terminal:

```text
Enter 's' for snake, 'w' for water and 'g' for gun
s
You win!
You chose s and computer chose w.

Enter 's' for snake, 'w' for water and 'g' for gun
g
You lose!
You chose g and computer chose w.
```

# Demo: 

<img width="744" height="329" alt="Screenshot 2026-02-07 192317" src="https://github.com/user-attachments/assets/7555adf3-4fef-4f58-963c-9b7ee6ec9c67" />


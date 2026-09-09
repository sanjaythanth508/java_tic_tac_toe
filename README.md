# 🎮 Java Tic-Tac-Toe Game (Console Application)

[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.oracle.com/java/)
[![OOP](https://img.shields.io/badge/OOP-Inheritance_&_Polymorphism-blue?style=for-the-badge)]()
[![Platform](https://img.shields.io/badge/Platform-Console_/_Terminal-lightgrey?style=for-the-badge)]()

An interactive, console-based **Tic-Tac-Toe** game developed in **Java**. This project demonstrates fundamental and intermediate software engineering principles, with a strong focus on **Object-Oriented Programming (OOP)**, modular class hierarchies, and robust terminal interaction.

---

## 🌟 Game Modes & Features

- 🤖 **Single Player Mode (vs Computer)**:
  - Play against an automated computer opponent that generates tactical moves using algorithmic randomization.
- 👥 **Two-Player Mode (Pass & Play)**:
  - Battle against a friend locally on the same terminal with custom player names.
- 🏆 **Session Score Tracking**:
  - Automatically records win counts and scores across multiple rounds until the players choose to exit.
- 🎯 **ASCII Board Rendering**:
  - Dynamically updates and visualizes the 3x3 game grid in the terminal after every valid move.
- 🛡️ **Defensive Input Validation**:
  - Employs exception handling and validation loops to prevent illegal cell overrides or non-numeric inputs.

---

## 🧠 Core Computer Science Concepts Demonstrated

| Concept | Implementation Details |
| :--- | :--- |
| **Object-Oriented Design** | Abstracted base game class (`Tictac`) extended by specialized subclasses (`playwithComputer` and `playWithFriend`). |
| **Inheritance & Polymorphism**| Reusable board verification, turn alternation, and overridden gameplay logic. |
| **Multi-Dimensional Arrays**  | Matrix representation of the game grid (`char[][] Met = new char[5][5]`) for cell positioning and visual separators. |
| **Control Flow & Game Loop**   | Nested `switch-case`, `do-while`, and conditional evaluation for win/draw checking. |
| **Exception Handling**         | Handles invalid user inputs gracefully via `Scanner` and boundary safeguards. |
| **Randomization**              | Utilizes `java.util.Random` for simulating unpredictable computer choices. |

---

## 📜 Rules of the Game

1. The game is played on a **3x3 grid**.
2. **Player 1** is assigned `'X'`, and **Player 2** (or Computer) is assigned `'O'`.
3. Players take turns selecting a vacant grid position (numbers `1` through `9`).
4. The first player to achieve **3 marks in a row** (horizontally, vertically, or diagonally) wins the round.
5. If all 9 squares are filled and neither player has 3 in a row, the match concludes in a **Draw**.

```text
       Grid Reference
       ┌───┬───┬───┐
       │ 1 │ 2 │ 3 │
       ├───┼───┼───┤
       │ 4 │ 5 │ 6 │
       ├───┼───┼───┤
       │ 7 │ 8 │ 9 │
       └───┴───┴───┘
```

---

## 📁 Repository Contents

```text
java_tic_tac_toe/
├── Tictac2.java     # Complete Java source code (Classes, OOP hierarchy, and Main runner)
├── shop.html        # Bonus responsive web storefront interface (VogueCart)
└── README.md        # Project documentation
```

---

## 🚀 How to Run

### Prerequisites
- [Java Development Kit (JDK 8 or higher)](https://www.oracle.com/java/technologies/downloads/) installed.
- Verify installation by running:
  ```bash
  javac -version
  java -version
  ```

### Compilation & Execution
1. Clone the repository:
   ```bash
   git clone https://github.com/sanjaythanth508/java_tic_tac_toe.git
   cd java_tic_tac_toe
   ```

2. Compile the Java source file:
   ```bash
   javac Tictac2.java
   ```

3. Run the application:
   ```bash
   java Tictac2
   ```

4. Follow the on-screen terminal prompts to select your mode and play!

---

## 👤 Author

- **Sanjay Thanth** ([@sanjaythanth508](https://github.com/sanjaythanth508))

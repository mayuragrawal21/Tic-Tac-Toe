
# 🤖❌⭕ AI-Based Tic Tac Toe – Minimax Algorithm in Python

A two-player **Tic Tac Toe** game with an AI opponent powered by the **Minimax algorithm**. The game includes a user-friendly interface built with `pygame` and demonstrates decision-making logic commonly used in game theory and reinforcement learning.

![Tic Tac Toe Screenshot](tic-tac-toe.png)

## 🧠 Powered by AI

This implementation uses the **Minimax algorithm** to make optimal moves for the computer player. The algorithm simulates all possible game states and selects the move that maximizes the AI's chance of winning while minimizing the human player's.

## 🎮 Features

- 🧠 **AI Opponent** using Minimax logic (hard to beat!)
- 🖱️ Mouse-based interaction
- 📊 Win, lose, or draw detection
- 🔁 Option to restart game
- 🧩 Modular design for clarity and reuse

## 🗂️ Project Structure

```
📦Tic-Tac-Toe/
 ┣ 📜constants.py         # Game config (grid size, colors, symbols)
 ┣ 📜tictactoe.py         # Main game with Minimax logic and rendering
 ┣ 📜tic-tac-toe.png      # Game screenshot
 ┗ 📜README.md            # This file
```

## ▶️ How to Play

1. **Install requirements**:
```bash
pip install pygame
```

2. **Run the game**:
```bash
python tictactoe.py
```

3. **Instructions**:
- Play as Player X (human)
- The computer plays as O (AI)
- Try to win or force a draw!

## 🧮 How Minimax Works

- Recursively evaluates all possible moves
- Assigns scores: +1 (AI win), -1 (Player win), 0 (draw)
- Chooses the move with the best outcome for the AI

## 🛠 Technologies

- Python
- pygame
- Minimax Algorithm

## 👤 Author

**Mayur Agrawal**  
🔗 [GitHub](https://github.com/mayuragrawal21) | [LinkedIn](https://www.linkedin.com/in/mayur-agrawal21/)  
📧 [agrawalmayur2001@gmail.com](mailto:agrawalmayur2001@gmail.com)

---

> 🤖 Challenge the AI and see if you can beat a perfect player!

# 🎯 **Tic-Tac-Toe AI with Minimax & Alpha-Beta Pruning** 🤖

## 📌 **Overview**
Welcome to the **Tic-Tac-Toe AI** project! This Python-based game lets you challenge an advanced AI in the timeless game of Tic-Tac-Toe. The AI utilizes the **Minimax Algorithm** with **Alpha-Beta Pruning** for optimal decision-making, ensuring a challenging and strategic gameplay experience. 🏆  

---

## 🚀 **Key Features**
✔ **AI vs Human Mode** – Play against an intelligent AI or compete with a friend.  
✔ **Optimized AI** – Uses Alpha-Beta Pruning to speed up decision-making.  
✔ **Intuitive Console Interface** – Play via a simple and user-friendly terminal.  
✔ **Real-time Game State Evaluation** – Detects win, loss, or draw conditions instantly.  

---

## 🎮 **How It Works**
1️⃣ **Game Setup** – The board starts as an empty 3x3 grid.  
2️⃣ **Alternating Turns** – Players take turns making moves.  
3️⃣ **AI Decision Making** – The AI analyzes the best move using Minimax and Alpha-Beta Pruning.  
4️⃣ **Game Completion** – The game ends when a player wins or no moves remain.  

---

## 🏁 **Player Modes**
🔵 **Human Player (X)** – The user manually selects a move by entering row and column numbers (e.g., `0 2` for top-right).  
❌ **AI Player (0))** – The AI calculates the best possible move using advanced algorithms.  

---

## 🛠 **Technology Used**
- 🐍 **Python 3** – Primary programming language.  
- 🧠 **Minimax Algorithm** – Ensures optimal decision-making.  
- ⚡ **Alpha-Beta Pruning** – Optimizes Minimax by eliminating unnecessary computations.  

---

## 📝 **Code Breakdown**

### 🔹 Key Functions:
- **`initialize_board()`** – Creates a 3x3 empty game grid.  
- **`current_player(board)`** – Determines whose turn it is.  
- **`valid_moves(board)`** – Returns available moves.  
- **`game_over(board)`** – Checks if the game has ended.  
- **`evaluate(board)`** – Assigns a score:
  - `-1` for AI victory.  
  - `+1` for Human victory.  
  - `0` for a draw.  
- **`minimax(board, player)`** – Implements the **Minimax Algorithm** for move selection.  
- **`alpha_beta(board)`** – Enhances Minimax with **Alpha-Beta Pruning** for faster execution.  

### ⚡ **How Minimax with Alpha-Beta Pruning Works**:
The AI efficiently evaluates moves by **pruning unnecessary branches**, drastically reducing the number of calculations needed while maintaining optimal gameplay. This ensures **faster and smarter AI decisions**.  

---

## 📌 **Sample Gameplay Output**
```plaintext
'Tic Tac Toe'


Current board:
[None, None, None]
[None, None, None]
[None, None, None]

Player:  X
Player 1 turn with sign X
Enter row: 0
Enter column: 2
Current board:
[None, None, 'X']
[None, None, None]
[None, None, None]
















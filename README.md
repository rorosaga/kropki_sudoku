# 🧩 Kropki Sudoku Solver 🧩

Welcome to the **Kropki Sudoku Solver**! This notebook demonstrates solving Kropki Sudoku puzzles using advanced algorithms and heuristics. Whether you're a Sudoku enthusiast or a fan of algorithmic problem-solving, you're in the right place!

## 🔍 What is Kropki Sudoku?

Kropki Sudoku is a variant of classic Sudoku with additional constraints:
- A white dot between two cells indicates their values differ by 1.
- A black dot between two cells means one value is twice the other.
- No dot? No such relationship exists between those cells.

The added complexity makes solving Kropki Sudoku a fascinating computational challenge!

## 🛠️ Features of the Solver

This solver incorporates:
- **Backtracking**: A systematic approach to explore all possible solutions.
- **Constraint Propagation**: Reduces the search space by applying logical constraints early.
- **Minimum Remaining Values (MRV) Heuristic**: Prioritizes cells with fewer possible values, optimizing the solving process.

## 🧑‍💻 Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook
- Basic knowledge of Sudoku (optional but helpful!)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/rorosaga/kropki_sudoku.git
   cd kropki-sudoku-solver
   ```
2. Run the notebook:
   ```bash
   jupyter notebook assignment2.ipynb
   ```
   
## 🎉 Try It Out!
Feel free to run the solver with your own Kropki Sudoku puzzles. Edit the puzzle input, and watch the solver do its magic!

## 📬 Feedback
Have suggestions or found a bug? Open an issue or contribute to the project with a pull request. Let's make this solver even better!


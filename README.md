# Boggle Solver

A high-performance **Boggle solver** implemented in Java, capable of finding all valid words on a given Boggle board using a dictionary. The solver uses a **Trie** (prefix tree) for efficient word lookup and **DFS with backtracking** to explore the board.

---

## Features

- Loads a dictionary of uppercase words (A-Z) into a Trie.
- Computes all valid words on any Boggle board.
- Calculates the Boggle score for each word based on standard scoring rules:
  - 3–4 letters: 1 point  
  - 5 letters: 2 points  
  - 6 letters: 3 points  
  - 7 letters: 5 points  
  - 8+ letters: 11 points  
- Optimized adjacency precomputation for faster DFS traversal.
- Handles the special `'Qu'` Boggle rule.

---

## Requirements

- Java 8 or higher
- [Princeton Algorithms library](https://algs4.cs.princeton.edu/code/)

---

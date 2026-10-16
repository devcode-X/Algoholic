# 🧩 Algoholic

> **Addicted to algorithms** — A competitive programming toolkit and problem-solving platform built for HackSprint 2025.

![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Hackathon](https://img.shields.io/badge/HackSprint-2025-FF6B6B?style=for-the-badge)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Hackathon_Build-orange?style=for-the-badge)

---

## 📖 Overview

**Algoholic** was built during **HackSprint 2025** as a competitive programming and algorithmic problem-solving platform. It brings together a curated set of algorithmic tools, visualizers, and practice utilities to help developers sharpen their problem-solving skills. Whether you're grinding LeetCode, prepping for interviews, or exploring data structures, Algoholic gives you the edge.

---

## ✨ Key Features

- 🧠 **Algorithm library** — Implementations of classic algorithms (sorting, searching, graph traversal, dynamic programming) ready to use and study
- 📊 **Step-by-step visualizer** — Watch algorithms execute in real-time to build intuition for time and space complexity
- 🏆 **Problem set tracker** — Curated problems organized by topic and difficulty (Easy / Medium / Hard)
- ⏱️ **Complexity analyzer** — Annotates solutions with Big-O time and space complexity breakdowns
- 🔁 **Custom test runner** — Run your solutions against edge cases and stress tests locally
- 📈 **Progress dashboard** — Track problems solved, streaks, and weak topic areas

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Language | Python 3.10+ |
| Visualization | matplotlib / rich |
| CLI Interface | argparse / Typer |
| Data Structures | Built from scratch (no black-box libs) |
| Testing | pytest |

---

## 🚀 Quick Start

### Prerequisites

- **Python** 3.10+
- **pip**

### Installation

```bash
# 1. Clone the repo
git clone https://github.com/devcode-X/Algoholic.git
cd Algoholic

# 2. Create and activate a virtual environment
python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt
```

### Run the CLI

```bash
# Launch the interactive problem-solving menu
python main.py

# Run a specific algorithm with visualization
python main.py --algo quicksort --visualize

# Test your solution against a problem
python main.py --problem two-sum --test
```

### Run Tests

```bash
pytest tests/ -v
```

---

## 📁 Folder Structure

```
Algoholic/
├── main.py                     # CLI entry point
├── algorithms/
│   ├── sorting/                # Bubble, Merge, Quick, Heap sort
│   ├── searching/              # Binary search, BFS, DFS
│   ├── dynamic_programming/    # Knapsack, LCS, Fibonacci, etc.
│   └── graph/                  # Dijkstra, Floyd-Warshall, Kruskal
├── problems/
│   ├── easy/
│   ├── medium/
│   └── hard/
├── visualizer/
│   └── renderer.py             # Step-by-step algorithm animation
├── tests/
│   └── test_algorithms.py
├── requirements.txt
└── README.md
```

---

## 🏅 HackSprint 2025

Built in 24 hours at **HackSprint 2025** with the mission to make algorithmic learning more visual, interactive, and addictive. 🚀

---

## 👤 Author

**Devansh Awasthi** · [@devcode-X](https://github.com/devcode-X)

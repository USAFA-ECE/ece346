# 🧭 Dijkstra's Algorithm

## 🎯 Objective: Your task is to implement Dijkstra’s algorithm to compute the shortest path in a weighted graph using an adjacency matrix.

## Overview

In this homework assignment, you will complete a Python implementation of **Dijkstra’s algorithm**. The algorithm finds the shortest path between two nodes in a graph with non-negative edge weights. You are provided with a scaffolded codebase and a set of test cases. Your task is to fill in the missing logic using the pseudocode from **Lecture 16**.

---

## Learning Outcomes

By the end of this lab, you will be able to:

- Apply Dijkstra’s algorithm to solve shortest path problems.
- Translate pseudocode into working Python code.
- Work with adjacency matrices and graph traversal logic.


> ⚠️ **Academic Integrity & AI Policy**  
> Do not use AI tools (like Copilot or ChatGPT) to complete the core logic of this lab. You are expected to write your own code and demonstrate understanding.  
> Uphold your honor and follow the [ECE 346 AI policy](https://usafa-ece.github.io/ece346/AI_policy.html).

---

## Git Workflow

Before pulling updates from the upstream repository, make sure your local changes are committed to avoid merge conflicts. Run the following commands:

```bash
git status
git add -A
git commit -m "Add your message"
git push
```

This ensures your work is saved and synced before integrating new changes from the course repository. To confirm that your upstream repository is configured correctly, run:

```bash
git remote -v
```

You should see something like:

```bash
$ git remote -v
origin  git@github.com:ECE-346/ece346_baek.git (fetch)
origin  git@github.com:ECE-346/ece346_baek.git (push)
upstream https://github.com/ECE-346/ece346_ws_2025.git (fetch)
upstream https://github.com/ECE-346/ece346_ws_2025.git (push)
```

Then you can safely pull updates:

```bash
git pull upstream main
```

Make sure the following files are present:
   - `shortest_path.py` (main scaffolded code)
   - `graph_utils.py` (helper functions for graph generation and visualization)


Open the terminal via View > Terminal. If your prompt starts with (.venv), your virtual environment is active. If not, activate it by running:
```bash
.\.venv\Scripts\Activate.ps1
```

Then install the required packages:
```bash
pip install -r .\requirements.txt
```

## Instructions

### Step 1: Review the Pseudocode

Refer to **Lecture 16** for the pseudocode of Dijkstra's algorithm. Understand the role of:

- Distance list `L`
- Predecessor list `pred`
- Visited set `S`
- Node selection and neighbor updates

---

### Step 2: Complete the `dijkstra()` Function

Open `shortest_path.py` and locate the following section:

```python
while target not in S:
    # Use the Pseudo code from L16 S14 as a guide
    # TODO: Write your code here
```

You must:

- Select the unvisited node with the smallest known distance.
- If no reachable node remains, return an empty path.
- Mark the selected node as visited.
- Update distances and predecessors for its neighbors.

---

### Python Tip: Using Sets

In this assignment, you will use a Python `set` to keep track of visited nodes. If you're new to sets, here is a quick reminder:

- To check if a node `u` has already been visited, use:
  ```python
  if u in S:
      # u is already in the visited set
  ```

Sets are fast and efficient for membership checks, making them ideal for tracking visited nodes in Dijkstra's algorithm.

---

### Step 3: Run the Test Cases

The `main()` function includes several test cases. **Do not modify them.** These include:

- Simple 3-node graph
- Lecture examples (Slides 5 and 20)
- Exercise 10.6.2
- A graph with no path to target
- Randomly generated graphs with varying sizes

Run the script using the triangle button at the top right corner. To debug, click the arrow next to the triangle and select "Python Debugger: Debug Python File".

Verify that your implementation correctly computes the shortest path and passes all tests.

```{warning}
You will receive a grade of zero if your code crashes with an error. The minimum requirement for this assignment is that your code runs without crashing.
```

---

## Submission

Once your implementation is complete and all tests pass:

1. Commit your changes:
   ```bash
   git add shortest_path.py
   git commit -m "Completed Dijkstra's algorithm implementation"
   ```

2. Push to your repository:
   ```bash
   git push origin main
   ```




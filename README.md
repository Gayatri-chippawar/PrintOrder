# 🌳 Binary Tree Traversals in Java

## 📌 Overview

This project implements a **Binary Tree** in Java and demonstrates different **tree traversal techniques**.

Binary Trees are a fundamental concept in **Data Structures and Algorithms (DSA)** and are frequently asked in **coding interviews and technical assessments**.

### ✨ Features Implemented

* 🌱 Build Binary Tree
* 🔁 Preorder Traversal
* 🔄 Inorder Traversal
* 🔙 Postorder Traversal
* 📊 Level Order Traversal (Breadth First Search)

---

# 🌿 Binary Tree Structure

A **Binary Tree** is a hierarchical data structure where each node has at most **two children**:

* ⬅️ Left Child
* ➡️ Right Child

Example Tree:

```
        1
       / \
      2   3
     / \   \
    4   5   6
```

---

# ⚙️ Features Implemented

## 🌱 1. Build Tree

The binary tree is constructed using **recursion**.

```
Node buildTree(int nodes[])
```

This function reads the **array representation of nodes** and recursively constructs the tree.

⏱ Time Complexity: **O(n)**

---

# 🔍 Tree Traversals

Traversal means **visiting every node of a tree exactly once**.

---

# 🔁 1. Preorder Traversal

Traversal Order:

```
Root → Left → Right
```

Example Output:

```
1 2 4 5 3 6
```

📌 Used in:

* Tree copying
* Expression trees

⏱ Time Complexity: **O(n)**

---

# 🔄 2. Inorder Traversal

Traversal Order:

```
Left → Root → Right
```

Example Output:

```
4 2 5 1 3 6
```

📌 Important Property:

If the tree is a **Binary Search Tree (BST)**, inorder traversal gives **sorted order**.

⏱ Time Complexity: **O(n)**

---

# 🔙 3. Postorder Traversal

Traversal Order:

```
Left → Right → Root
```

Example Output:

```
4 5 2 6 3 1
```

📌 Used in:

* Deleting trees
* Expression tree evaluation

⏱ Time Complexity: **O(n)**

---

# 📊 4. Level Order Traversal

Also called **Breadth First Search (BFS)**.

Traversal is performed **level by level using a Queue**.

Example Output:

```
1
2 3
4 5 6
```

📌 Data Structure Used:

```
Queue
```

⏱ Time Complexity: **O(n)**

---

# 📋 Traversal Summary

| Traversal      | Order               |
| -------------- | ------------------- |
| 🔁 Preorder    | Root → Left → Right |
| 🔄 Inorder     | Left → Root → Right |
| 🔙 Postorder   | Left → Right → Root |
| 📊 Level Order | Level by Level      |

---

# ⏱ Time Complexity

| Operation      | Complexity |
| -------------- | ---------- |
| 🌱 Build Tree  | O(n)       |
| 🔁 Preorder    | O(n)       |
| 🔄 Inorder     | O(n)       |
| 🔙 Postorder   | O(n)       |
| 📊 Level Order | O(n)       |

---

# 🧠 Concepts Used

* 🌳 Binary Trees
* 🔁 Recursion
* 📊 Queue (BFS)
* 🔎 Tree Traversal Algorithms
* 🌐 Depth First Search (DFS)

---

# 🎯 Learning Outcome

After completing this project you will understand:

✔ How binary trees are built
✔ Difference between **DFS and BFS**
✔ Tree traversal techniques
✔ Recursion in tree problems

These concepts are essential for **DSA interviews and competitive programming**.

---


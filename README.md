# capstone-assignment-dsa-in-python-
# 🌐 Social Network Explorer (SNE)

## 📌 Overview

Social Network Explorer (SNE) is a data-structure-based project that models a social network using graphs. It allows users to create profiles, connect with others, and explore relationships using traversal algorithms like BFS and DFS.

---

## 🎯 Features

* Add users to the network
* Create and manage friendships
* Display network (Adjacency List)
* BFS traversal (level-wise exploration)
* DFS traversal (deep exploration)
* Friend suggestions (friends-of-friends)
* Fast user search using hashing

---

## 🧠 Data Structures Used

* **Graph (Adjacency List)** – Core structure for connections
* **Hash Table** – Fast user lookup
* **Queue** – Used in BFS
* **Stack / Recursion** – Used in DFS

---

## ⚙️ Algorithms

* **BFS (Breadth First Search)** → O(V + E)
* **DFS (Depth First Search)** → O(V + E)
* **Hashing** → O(1) average lookup

---

## 🚀 How It Works

1. Users are added as nodes
2. Friendships are edges
3. Graph is stored using adjacency list
4. Traversal algorithms explore connections
5. Suggestions are generated from mutual friends

---

## 🖥️ Installation & Setup

```bash
# Clone the repository
git clone https://github.com/your-username/sne-project.git

# Go to project folder
cd sne-project

# Run the program
python main.py
```

---

## 📂 Project Structure

```text
sne-project/
│── main.py
│── graph.py
│── user.py
│── utils.py
│── README.md
```

---

## 📊 Example

Input:
A connects with B, C
B connects with D

Output:

* BFS from A → A, B, C, D
* DFS from A → A, B, D, C
* Friend Suggestion → D

---

## ⚡ Complexity

| Operation      | Complexity |
| -------------- | ---------- |
| Add User       | O(1)       |
| Add Connection | O(1)       |
| BFS / DFS      | O(V + E)   |
| Search User    | O(1) avg   |

---

## 🔮 Future Improvements

* GUI (React / Web Interface)
* Database integration
* Weighted graph (strong/weak connections)
* Recommendation system using ML

---

## 👩‍💻 Author

* Your Name

---

## 📚 License

This project is for educational purposes.

---

## ⭐ Note

This project demonstrates real-world application of data structures like graphs, hashing, and traversal algorithms.

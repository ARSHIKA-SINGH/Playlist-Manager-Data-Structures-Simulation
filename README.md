# 🎵 Playlist Manager – Data Structures Simulation

A **visual and interactive Python application** that simulates three fundamental **Linked List data structures** using a real-world **music playlist manager**.  
This project helps students understand data structures through **visualization and user interaction**.

---

## 📌 Project Overview

The **Playlist Manager** demonstrates how different linked list implementations behave when performing common playlist operations such as adding, removing, and navigating songs.

The project visually shows:
- Nodes (songs)
- Pointers (`next`, `prev`)
- Real-time changes during operations

---

## 🎯 Features

✅ Supports **three linked list types**  
✅ Real-time **visual representation of nodes & pointers**  
✅ Interactive playlist controls  
✅ Educational step-by-step simulation  
✅ Clean and beginner-friendly GUI  

### 🔗 Data Structures Implemented
- Singly Linked List  
- Doubly Linked List  
- Circular Linked List  

---

## 🧠 Data Structures Explained

### 1️⃣ Singly Linked List
- Each node points to the **next node**
- Forward navigation only
- Memory efficient

### 2️⃣ Doubly Linked List
- Each node points to **next and previous nodes**
- Allows forward & backward traversal
- Uses extra memory

### 3️⃣ Circular Linked List
- Last node links back to the first node
- Infinite looping
- Ideal for repeat playlists

---

## 🎮 How to Use

1. Run the application  
2. Select the **Linked List type** from the dropdown  
3. Add songs manually or using **Add Random**  
4. Use playback controls:
   - ▶ Play  
   - ⏭ Next  
   - ⏮ Previous  
5. Remove individual songs or clear the playlist  
6. Observe **real-time visualization updates**

## 📂 Project Structure

```text
playlist_manager/
│
├── main.py                  # Entry point – RUN THIS FILE
├── README.md                # Project documentation
│
├── data_structures/         # Core linked list implementations
│   ├── node.py              # SongNode class
│   ├── singly_list.py       # Singly Linked List
│   ├── doubly_list.py       # Doubly Linked List
│   └── circular_list.py     # Circular Linked List
│
├── gui/                     # User Interface components
│   ├── app.py               # Main application logic
│   ├── controls.py          # Buttons and user inputs
│   └── display.py           # Playlist visualization
│
└── utils/                   # Utility functions
    └── helpers.py           # Sample data and helper methods
````  

## 🛠 Technologies Used

### 🔹 Programming Language
- **Python 3.x**

### 🔹 GUI Framework
- **Tkinter** (Python built-in library)

### 🔹 Core Concepts
- Data Structures  
- Linked Lists (Singly, Doubly, Circular)  
- Object-Oriented Programming (OOP)  
- GUI Programming  
- Event Handling  

### 🔹 Development Tools
- Visual Studio Code / Any Python IDE
- Git & GitHub (Version Control)

### 🔹 Dependencies
- **None** – This project uses only Python built-in libraries

## ⚙️ Installation & Execution

1. Install Python (if not installed)
2. Clone or download this repository
3. Navigate to the project folder
4. Run the project using:

```bash
python main.py



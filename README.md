# 🎵 Playlist Manager - Data Structures Simulation

A visual simulation project demonstrating three types of Linked List data structures through an interactive music playlist manager.

## 📊 Project Overview
This application visually demonstrates how different linked list data structures work using a real-world example of a music playlist manager.

## 🎯 Features
- **Three Data Structures**: Singly, Doubly, and Circular Linked Lists
- **Visual Representation**: Real-time visualization of nodes and pointers
- **Interactive Controls**: Add, remove, play, and navigate songs
- **Statistics Panel**: Shows current state and operations
- **Educational Tool**: Step-by-step demonstration of linked list operations

## 📁 Project Structure

playlist_manager/
├── main.py # Entry point - RUN THIS FILE
├── data_structures/ # Core linked list implementations
│ ├── node.py # SongNode class
│ ├── singly_list.py # Singly Linked List
│ ├── doubly_list.py # Doubly Linked List
│ └── circular_list.py # Circular Linked List
├── gui/ # User interface components
│ ├── app.py # Main application logic
│ ├── controls.py # Buttons and inputs
│ └── display.py # Visualization canvas
├── utils/ # Helper functions
│ └── helpers.py # Sample data and utilities
└── README.md # This documentation file

🎮 **How to Use**
   **.**Select Data Structure Type from the dropdown menu
   **.**Add Songs using the input form or "Add Random" button
   **.**Use Playback Controls (Next, Previous, Play)
   **.**Remove Songs or clear the entire playlist
   **.**Watch Visualization update in real-time

📚 **Data Structures Demonstrated**

1. **Singly Linked List**
Each node points only to the next node
Forward navigation only
Memory efficient

2. **Doubly Linked List**
Each node points to both next AND previous nodes
Bidirectional navigation
More flexible but uses extra memory

3. **Circular Linked List**
Last node points back to the first node
Continuous loop navigation
Perfect for repeat playlists

🛠️**Technologies Used**
Language: Python 3.x
GUI Framework: Tkinter (built-in)
Concepts: Data Structures, OOP, GUI Programming
Dependencies: None (Pure Python)
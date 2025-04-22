# Data Structures and Algorithms: Network Equipment Library (Java)

This project implements **Abstract Data Types (ADTs)** in Java to simulate a real-world system: a **Network Equipment Library**. The system demonstrates the application of ADTs such as stacks, queues, and linked lists for managing, updating, and retrieving network equipment data. It forms part of the Unit 19 coursework.

## Project Overview

The goal of this project is to design and implement a small-scale equipment tracking system using ADTs in Java. The system allows users to:
- Add new network equipment
- Search for equipment by serial number
- Update equipment location
- Connect two pieces of equipment
- Retrieve the last updated equipment (FIFO logic)

The program follows a **menu-driven console interface** using Java's `Scanner` class for user input and file I/O for data persistence.

## Features

- **Encapsulated object structure** with constructor, getters, and setters
- **LinkedList ADT** to store and manage the equipment data
- **Data validation** for IP addresses and location input
- **File persistence** using `equipment.txt`
- **Search and update functionalities** with O(N) complexity
- **Connection simulation** between two equipment nodes
- **FIFO-style retrieval** for last updated equipment

## Data Structures Used

- **Stack & Queue (conceptual)** for LIFO and FIFO demonstrations
- **LinkedList (ADT)** for storing equipment objects dynamically
- **Encapsulation** to protect object data
- **Switch-case** menu control for navigation

## Complexity Analysis

Each core method follows:
- **Time Complexity**: O(N)
- **Space Complexity**: O(1)

The system has a **total time complexity of O(N)** and **constant space complexity O(1)**, ensuring efficiency for small-to-medium data sets.

## Key Algorithms

- **Bubble Sort vs Quick Sort**: Comparative analysis done on stability, space, and time complexity
- **Dijkstra vs Bellman-Ford**: Implemented shortest path logic conceptually, compared for routing and GPS systems
- **Asymptotic Analysis**: Big-O, Theta, and Omega explored for algorithm performance evaluation

## Object-Oriented Design

- Demonstrates principles of **OOP**: abstraction, encapsulation, modularity
- Uses **Software Stack Examples**: e.g., LAMP, XAMPP
- Connects **ADT usage to real-world software** (network libraries)

## Trade-Offs & Justifications

The project discusses:
- Time vs space trade-offs in algorithm design
- Read efficiency vs write flexibility in ADTs
- Use of encapsulation for security vs access complexity

## Implementation Independent Data Structures

- Emphasizes reusable and abstract logic
- Avoids exposing internal implementation
- Promotes adaptable and scalable coding style

## How to Run

1. Extract the `.zip` file and open the Java source files in any Java IDE (e.g., IntelliJ, Eclipse, BlueJ)
2. Compile and run the `Main` class
3. Follow the menu instructions in the console
4. All equipment data will be saved in `equipment.txt`

## Author

Talal AbuAbdo  
Unit 19: Data Structures and Algorithms
GitHub: [github.com/Talal-Abuabdu](https://github.com/Talal-Abuabdu/Data-Structres-and-algorithms)

## License

This project was developed for academic purposes as part of the Unit 19 coursework. No commercial license is applied.

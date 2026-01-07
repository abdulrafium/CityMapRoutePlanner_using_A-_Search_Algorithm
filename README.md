# City Map Shortest Route Finder using A* Algorithm

This project is a Python-based desktop application that demonstrates the working of the A* (A-Star) search algorithm using a graphical city map. The application allows users to select a start city and a destination city and visually displays the shortest path between them.

The system is developed using Tkinter for the graphical user interface. Cities are represented as nodes, and roads are represented as weighted edges.

---

## Objectives

- Implement the A* search algorithm
- Visualize shortest path finding on a city map
- Apply heuristic-based search techniques
- Understand graph traversal concepts

---

## Tools & Technologies

- Python 3
- Tkinter
- Priority Queue
- A* Pathfinding Algorithm

---

## Working Methodology

1. Cities are displayed on a graphical canvas.
2. Roads are drawn between connected cities.
3. User selects:
   - First click → Start city
   - Second click → Destination city
4. A* algorithm calculates the shortest path.
5. The final path is animated and total cost is displayed.

---

## Algorithm Used

A* Search Algorithm

f(n) = g(n) + h(n)

Where:
- g(n) is the actual path cost
- h(n) is the heuristic (Euclidean distance)

---

## Educational Outcome

This project demonstrates the practical implementation of AI search algorithms, heuristic functions, and graph-based pathfinding using a graphical interface.

---

## How to Run

1. Make sure Python 3 is installed on your system.
2. Save the program file as `project.py`.
3. Open a terminal or command prompt in the project folder.
4. Run the following command:

python project.py

---

## Author

Abdul Rafiu
Department of Computer Science

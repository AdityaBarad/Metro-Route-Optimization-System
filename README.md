# Metro Route Optimization System

## Overview
The Metro Route Optimization System is a Java-based application designed to optimize metro routes using Data Structures and Algorithms (DSA). It provides functionalities for finding the shortest path between two stations using Dijkstra's algorithm, implemented with a graph representation and a heap data structure for efficient priority queue operations.

## Files
- **Graph_M.java**: Contains the implementation of the graph data structure used for representing the metro network and the Dijkstra's algorithm for finding the shortest path.
- **Heap.java**: Implements a min-heap data structure, essential for efficiently managing the priority queue in Dijkstra's algorithm.

## Features
- **Shortest Path Calculation**: Calculates the shortest path between two metro stations using Dijkstra's algorithm.
- **Efficient Data Structures**: Utilizes graph representation and a heap for optimal performance in pathfinding operations.
- **Flexibility**: Can be extended to include additional features such as route planning, fare calculation, etc., leveraging the underlying DSA principles.

## Installation
1. **Clone the repository**:
git clone https://github.com/your-username/metro-route-optimization.git:

3. **Open in your Java IDE**:
Import the project into your preferred Java IDE (e.g., IntelliJ IDEA, Eclipse).

4. **Compile and Run**:
Compile and run the `Graph_M.java` file to execute the metro route optimization system.

## Usage
1. **Input Format**:
Modify the input graph (metro network) directly in `Graph_M.java`. You can define stations, connections, and weights (distances) between them.

2. **Running the Program**:
Run `Graph_M.java` to initiate the system. Follow the prompts to input the start and destination stations. The program will output the shortest path and relevant details.

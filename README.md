# Smart Route Planner | Data Structure & Algorithm

## Project Overview

This C++ project implements a Smart Route Planner to model a transportation system. It analyzes user-provided data to recommend the most economical or fastest route between stations.

### Features

- **Algorithm**: Developed a C++ algorithm to model the transportation system and recommend routes based on cost or time.
- **Optimization**: Utilized the Breadth-First Search (BFS) technique for efficient path optimization.
- **Data Structure**: Implemented a Priority Queue to efficiently prioritize routes based on time and cost considerations.

### How It Works

1. **Input**: The program prompts the user to enter the source station, destination station, and whether they want to optimize for time or money.
2. **Processing**: The algorithm processes the input using BFS and a Priority Queue to determine the optimal route.
3. **Output**: Displays the cost or time of the route and the path between the source and destination.

### Getting Started

#### Prerequisites

- C++ Compiler (e.g., `g++`)
- Visual Studio Code or any other C++ development environment

#### Compilation and Execution

1. **Clone the Repository**

   ```bash
   git clone <repository_url>
   cd <repository_directory>
2. Compile the Code

   Open the terminal in VS Code and run:

   g++ -o route_planner route_planner.cpp

3. Run the Program

   Execute the compiled program with:

   ./route_planner

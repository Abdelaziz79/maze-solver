# Maze Solver Project
![image](https://github.com/user-attachments/assets/27497872-ffce-4d81-8b9b-597efe1a6882)

This project is a web-based maze solver application developed using React and Bootstrap. The application allows users to create and interact with a maze, set start and end points, add obstacles, and solve the maze using either Breadth-First Search (BFS) or Depth-First Search (DFS) algorithms. Users can also control the speed of the solver and adjust the maze dimensions.

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)

## Features

- Create a maze with customizable rows and columns.
- Click on boxes to set them as the source, target, or obstacles:
  - Single click to set a box as the source.
  - Double click to set a box as the target.
  - Triple click to set a box as an obstacle.
  - Quadruple click to reset a box to normal.
- Randomly generate source, target, and obstacles.
- Solve the maze using BFS or DFS algorithms.
- Control the speed of the maze solver.
- Responsive design using Bootstrap for a smooth user experience.

## Demo

Check out the live demo of the application [here](https://azeez-app-maze-solver.surge.sh/).

## Requirements

- Node.js and npm (Node Package Manager)

## Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/Abdelaziz79/maze-solver.git
   ```

2. **Navigate to the project directory:**

   ```sh
   cd maze-solver
   ```

3. **Install the dependencies:**

   ```sh
   npm install
   ```

## Usage

1. **Run the application:**

   ```sh
   npm start
   ```

2. **Open the application in your browser:**

   Go to `http://localhost:3000`

3. **Interact with the maze:**

   - Click on boxes to set the source, target, and obstacles.
   - Use the control panel to start solving the maze using BFS or DFS.
   - Adjust the speed of the solver.
   - Modify the maze dimensions by setting the number of rows and columns.

## Project Structure

```
maze-solver/
├── public/
│   ├── index.html
│   └── ...
├── src/
│   ├── components/
│   │   ├── Main
│   │   ├── MiniCube
│   │   ├── NavBar
│   │   
│   ├── App.js
│   ├── index.js
│   └── ...
├── README.md
└── package.json
```

- `components/`: Contains the React components for the application.
  - `Main`: Folder Contain Component Main page.
  - `MiniCube`: Folder Contain Component representing MiniCube.
  - `NavBar`: Folder Contain Component for the NavBar.
- `App.js`: Main component that integrates all parts of the application.
- `index.js`: Entry point of the React application.

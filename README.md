**Edit: This project won Best Solo Hack at NorCalHacks 2020 **
https://event.hackhub.com/event/NorcalHacks/teams/submissions/5824cdf4-4815-4b2e-afa4-707d1f82135d

# Live Demo
https://shamsansari.github.io/Pathfinding-Visualization-NorcalHacks/
--> Refresh for new maze


# Pathfinding-Visualization-NorcalHacks
Submission for Norcal Hackathon. A Breadth first search pathfinding visualization for a maze generated with Recursive division. 

This is A Maze solving visualization. How algorithms solve mazes or find paths between two points. Graph Theory and complex tree data structures are confusing so I built this simple visualization to help students understand how pathfinding algorithms. The program generates a unique maze with the "Recursive division" algorithm. It then randomly sets a start cell (green) and an end cell (red). The program then tries to find a path between the start and end cells using the breadth-first search (BFS) algorithm. Cells that are searched are colored yellow so you can visualize which cells have been searched.

# Directory
- .mp4 : Video submission
- index.html
- css/
  - style.css : styling
- js/
  - lib/
    - buckets.js : Data structure library for javascript
  - calculate.js : Algorithms and helper function
  - color.js : colors pairing for rendering
  - render.js : Rendering both gui and console
  - main.js : Main js file, calls other files, d3.js selections
 


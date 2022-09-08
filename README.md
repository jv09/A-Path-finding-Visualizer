# A-Path-finding-Visualizer
A python visualization of the A* pathfinding algorithm using Pygame and TKinter. It allows users to pick a start and end point and view the process of finding the shortest path.

The A-star algorithm is employed here to determine the  shortest path between two nodes in a 2-D grid, with the option of placing the obstacles given to the user. Based on A-star's heuristic  function, different  paths  are traversed and the final path is determined using backtracking. 


The project thus helps in visually interpreting how the A-Star algorithm functions.

## Requirements
1. The only requirement is to install Pygame, which can be done by running either of the following two commands in cmdprompt

    pip install pygame

    python -m pip install pygame

After installing Pygame, simply run the command: python aStartVisual.py

## Steps to Run the Project

Initially, on a 2-D Grid you can choose two different position, starting and ending position, by right clicking on the 2-D grid. The starting position is marked by yellow and ending position is marked by a blue node.

Once it has been done, you can now start placing obstacles interactively by right clicking on the cells you want to. The obstacles are represented by black colour.

Once you're done with placing obstacles, press the Space Bar on your Keyboard to let the project function and determine paths heurestically from starting to ending node. The visualisation of the whole process can be seen using a red stream that flows from the starting node that tries to reach the ending node. The functioning A-Star algorithm is visualised through this manner.

Once the final node is reached, a stream of purple colour backtracks to find the optimal path free of obstacles from starting to ending node.

## Starting position, Ending Position And Obstacle Positioning Example

![Screenshot (203)](https://user-images.githubusercontent.com/70435148/189087451-76589911-296b-452f-ba04-7dbcb5bdac76.png)

## A* Algorithm Pathfinding Visualization using red stream

![Screenshot (206)](https://user-images.githubusercontent.com/70435148/189088025-8e9c3e97-c0e6-4a00-8f28-734a843d0a0a.png)

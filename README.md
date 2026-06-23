# Tree-Visualizer

## Project Overview

Tree Visualizer is an interactive web-based application developed to help students and learners understand the working of tree data structures through graphical visualization. The application provides real-time visualization of Binary Trees, Binary Search Trees (BST), and AVL Trees, enabling users to perform various operations and observe structural changes dynamically.

The project was designed to simplify the learning of hierarchical data structures by converting theoretical concepts into visual representations. Users can insert nodes, search elements, perform traversals, and observe AVL balancing operations directly on the screen.

## Objectives

* To provide an interactive platform for understanding tree data structures.
* To visualize node insertion and tree formation in real time.
* To demonstrate the differences between Binary Trees, BSTs, and AVL Trees.
* To implement traversal algorithms and display their outputs.
* To illustrate AVL tree balancing using rotations.
* To improve understanding of recursion and tree-based algorithms.

## Features

### Binary Tree Visualization

* Level-order insertion of nodes.
* Automatic placement of nodes.
* Dynamic tree generation.

### Binary Search Tree Visualization

* Node insertion based on BST properties.
* Efficient searching using ordered structure.
* Visualization of left and right subtree organization.

### AVL Tree Visualization

* Self-balancing binary search tree implementation.
* Automatic balancing after insertion.
* Support for:

  * Left-Left (LL) Rotation
  * Right-Right (RR) Rotation
  * Left-Right (LR) Rotation
  * Right-Left (RL) Rotation

### Search Operation

* Search for any node value entered by the user.
* Highlights whether the node exists in the tree.

### Tree Traversals

The application supports:

* Inorder Traversal
* Preorder Traversal
* Postorder Traversal
* Level Order Traversal

### Dynamic Visualization

* Real-time graphical representation using HTML5 Canvas.
* Nodes represented as circles.
* Parent-child relationships represented using connecting edges.
* Different themes and colors for each tree type.

## System Architecture

User Input → Tree Operation Processing → Tree Data Structure → Canvas Rendering Engine → Visual Output

The system accepts user input and performs the requested operation on the selected tree structure. After processing, the rendering engine updates the visualization dynamically on the canvas.

## Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript (ES6)

### Visualization

* HTML5 Canvas API

### Data Structures

* Binary Tree
* Binary Search Tree
* AVL Tree

### Algorithms

* Breadth First Search (BFS)
* Depth First Search (DFS)
* Tree Traversal Algorithms
* AVL Rotation Algorithms

## Working Methodology

1. User selects a tree type (BT, BST, or AVL).
2. User enters a node value.
3. System inserts the node according to the selected tree rules.
4. Tree structure is updated internally.
5. Canvas renderer redraws the tree.
6. Users can perform search and traversal operations.
7. Traversal results are displayed instantly.


## Outcomes

* Successfully visualized tree structures dynamically.
* Improved understanding of recursion and balancing algorithms.
* Demonstrated practical implementation of data structure concepts.
* Created an educational tool for students learning trees.


## Applications

* Data Structure Learning Platform
* Educational Demonstrations
* Coding Interview Preparation
* Classroom Teaching Aid
* Algorithm Visualization Tool

## Conclusion

The Tree Visualizer project successfully demonstrates the implementation and visualization of Binary Trees, Binary Search Trees, and AVL Trees. By integrating data structure algorithms with graphical representation, the project transforms complex concepts into an interactive learning experience. It enhances understanding of tree operations, traversal techniques, and balancing mechanisms while providing practical exposure to JavaScript, recursion, and algorithm design.

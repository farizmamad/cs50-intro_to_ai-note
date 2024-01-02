# AI for search problem

The computer that perceive its environment is able to act in order to reach the goal set from the initial state.

## Terms:
1. Agent
2. State and Initial state
3. Actions
4. Transition model
5. State space
6. Goal test
7. Path cost

## Solving search problems:
1. Find a sequence of actions that leads from initial state to the goal state
2. Optimal solution: finding solution with lowest path cost among all solutions

## Node
Data for this problem usually stored in a Node.
Node is a data structure that consists of:
1. State
2. Parent node
3. Path cost

## Frontier
The mechanism that manages Nodes to "actually search" is called Frontier.

Frontier is also a data structure that contains Node and rules the arrangement of in and out.
Two data structures for Frontier are:
1. Stack: last in first out
2. Queue: first in first out

## Approaches
### A. Approaches to solve search problems:
A. Single agent uninformed
1. Depth First Search (dfs) - Stack
2. Breadth First Search (bfs) - Queue

### B. Single agent informed
1. Greedy Best First Search (gbfs)
2. A* search

### C. Multiple Agents
1. Adversarial Search
2. Minimax.

Optimization of Minimax:
1. Alpha Beta Pruning
2. Depth-Limited Minimax

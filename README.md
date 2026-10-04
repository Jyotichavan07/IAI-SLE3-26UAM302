# IAI-SLE3-26UAM302
# BFS vs DFS Graph Search System

## Overview

This project implements and compares Breadth-First Search (BFS)
and Depth-First Search (DFS) on a graph.

## Algorithms

### BFS
Uses a queue to explore nodes level by level.

### DFS
Uses a stack to explore nodes depth-first.

## Input

Start Node: A
Goal Node: I

## Output

The system displays:
- Selected algorithm
- Start node
- Goal node
- Search repetitions
- Path found
- Nodes expanded

## Profiling

py-spy is used to profile the execution workload.

## C4 Architecture

### Level 1 – Context
[link/image]

### Level 2 – Container
[link/image]

### Level 3 – Component
[link/image]

### Level 4 – Code

Main functions:
- bfs()
- dfs()
- run_bfs_workload()
- run_dfs_workload()
- display_results()

## How to Run

python src/bfs_dfs.py bfs

python src/bfs_dfs.py dfs

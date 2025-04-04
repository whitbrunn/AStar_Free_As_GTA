# AStar_Free_As_GTA


## What we do


- Try 3 heuristic functions in A*: 
    - Manhattan
    - Euclidean
    - Chebyshev
    - Whatever you want to try
- Degenerate the A* to:
    - Dijkstra’s Algorithm
    - Greedy Best First Search (GBFS) Algorithm
- Visualtion


---

Make sure you have the following folder structure:

Project-Root/ 
├── README.md
├── astar.ipynd
├── map/ 
|   ├── vivocity_freespace.png 
|   └── ...
└── res/ 
    ├── 8-ngb_Manhattan_res.txt
    ├── 8-ngb_Dij_res.txt
    └── ...


## How to use

- Simply run the `astar.ipynb` block by block (without miising any folded one).
- In Section 1, 
    - modify the `h_MODE` and `g_MODE` to change the heuristic h(x) and cost-so-far g(x) that you want to use.
        - When h(x) -> 0, A* -> Dijkstra
        - When g(x) -> 0, A* -> Greedy Best First Search
    - modify `ngb_MODE` to choose 4 neighbour exploration region or 8 neighbour.



## One more thing

Please contact maijy1010@163.com for any questions.
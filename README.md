# Algorithm Visualiser

A simple tool built step by step visualisation for path finding, maze creating and sorting algorithms 

![Example](Fonts/Example.png "Example")

### Included algorithms:

Path Finding:
* [A* Path finding algorithm](Algorithms/astar.py)
* [Dijkstra algorithm](Algorithms/dijkstra.py)

Maze:
* [Prim's algorithm](Algorithms/prims.py)
* [Kruskal's algorithm](Algorithms/kruskal.py)
* [Sidewinder algorithm](Algorithms/sidewinder.py)
* [Eller's algorithm](Algorithms/ellers.py)
* [Recursive backtracking algorithm](Algorithms/recursive_backtracking.py)
* [Aldous Broder algorithm (Modified)](Algorithms/aldous_broder.py)
* [Wilson's algorithm](Algorithms/wilson.py)
* [Hunt and Kill algorithm](Algorithms/hunt_and_kill.py) (Modified)
* [Growing Tree algorithm](Algorithms/growing_tree.py) (newest and random choices combined)
* [Binary Tree algorithm](Algorithms/binary_tree.py)
* [Recursive division algorithm](Algorithms/recursive_division.py)

Sorting:
* [Bubble Sort](Sorts/bubble.py)
* [Merge Sort](Sorts/iterativemerge.py) (Iterative method)
* [Selection Sort](Sorts/selection.py)

---
#### To run the application:

Install modules
```bash
pip install pygame
pip install argparse
```

Run command for more information:
```bash
python app.py -h
or
python app.py --help
```

Run to get started right away!:
```bash
python app.py
```

---
#### To use the tool:
> Different coloured squares represents the following:

|  Color 	|   Representation	|  
|---	|---	|
|   White	|  Empty Square 	|
|   Black	| Barrier  	|
|   Red	|   Visited	|
|   Green	|  To be visited 	|
|   Orange	|   Start Node	|
|   Teal	|   End Node	|
|   Purple	|   Shortest Path	|

> Basic Keys:

|   Key	|   Function	|
|---	|---	|
| Backspace  	|  Clear Screen 	|
|   Tab	|  Switch off or on grid 	|
|   Mouse Right Click	|   Clear node or obstacle	|
|   Mouse Left Click	|   Add Node or obstacle	|

> Maze Generation:

|   Key	|   Function	|
|---	|---	|
| p  	|   Prim's algorithm	|
|  k 	|   Kruskal's algorithm	|
|   s	|   Sidewinder algorithm	|
|  r 	|   Recursive backtracking algorithm	|
|  u 	|   Aldous Broder algorithm	|
|  h 	|   Hunt and Kill algorithm	|
|   g	|   Growing Tree algorithm	|
|   b	|   Binary Tree algorithm	|
|   q	|   Recursive Division algorithm	|
|  w 	|  	 Wilson's algorithm|
|  e 	|  	 Eller's algorithm|

> Path Finding:

|   Key	|   Function	|
|---	|---	|
| a  	|   A* algorithm	|
| d  	|   Dijkstra algorithm	|
|   	|  	|

> Sorting:

|   Key	|   Function	|
|---	|---	|
|   Space	| Shuffle 	|
| 2  	|   Bubble Sort	|
| 3  	|  Merge Sort (iterative)	|
|  1 	|  Selection Sort	|
|   	|  	|

#### Note:
1) Maze algorithms don't work if start and end nodes are mentioned already.
2) Path finding algorithms work only if start and end nodes are mentioned.
3) Sort algorithms work only when lines are shuffled 
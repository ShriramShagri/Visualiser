# Algorithm Visualiser

A simple tool built step by step visualisation for path finding and maze creating algorithms 

### Included algorithms:

Path Finding:
* A* Path finding algorithm
* Dijkstra algorithm

Maze:
* Prim's algorithm
* Kruskal's algorithm
* Sidewinder algorithm

---
#### To run the application:

Install pygame
```bash
pip install pygame
```

Run command for more information:
```
python app.py -h
```
or
```
python app.py --help
```
---
#### To use the tool:
Different coloured squares represents the following:

|  Color 	|   Representation	|  
|---	|---	|
|   White	|  Empty Square 	|
|   Black	| Barrier  	|
|   Red	|   Visited	|
|   Green	|  To be visited 	|
|   Orange	|   Start Node	|
|   Teal	|   End Node	|
|   Purple	|   Shortest Path	|

Keys:

|   Key	|   Function	|
|---	|---	|
| Backspace  	|  Clear Screen 	|
|   Mouse Right Click	|   Clear node or obstacle	|
|   Mouse Left Click	|   Add Node or obstacle	|
| p  	|  Draw maze using Prim's 	|
|  k 	|  Draw maze using Kruskal's	|
|   s	|  Draw maze using Sidewinder algorithm	|
| a  	|  Run A* algorithm	|
| d  	|  Run Dijkstra algorithm	|
|   	|  	|

#### Note:
1) Maze algorithms don't work if start and end nodes are mentioned already.
2) Path finding algorithms work only if start and end nodes are mentioned.

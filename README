/*

"Dijkstra's algorithm, conceived by Dutch computer scientist Edsger Dijkstra, is a graph search algorithm that solves the single-source shortest path problem for a graph with nonnegative edge path costs, producing a shortest path tree. This algorithm is often used in routing and as a subroutine in other graph algorithms."

*/

```
var map = {a:{b:3,c:1},b:{a:2,c:1},c:{a:4,b:1}},
    graph = new Graph(map);

graph.findShortestPath('a', 'b');      // => ['a', 'c', 'b']
graph.findShortestPath('a', 'c');      // => ['a', 'c']
graph.findShortestPath('b', 'a');      // => ['b', 'a']
graph.findShortestPath('b', 'c', 'b'); // => ['b', 'c', 'b']
graph.findShortestPath('c', 'a', 'b'); // => ['c', 'b', 'a', 'c', 'b']
graph.findShortestPath('c', 'b', 'a'); // => ['c', 'b', 'a']
```

It is also possible to define your input map as an array of edges like this:

```
var map = [
            {head: 'a', tail: 'b', dist: 3},
            {head: 'a', tail: 'c', dist: 1},
            {head: 'b', tail: 'a', dist: 2},
            {head: 'b', tail: 'c', dist: 1},
            {head: 'c', tail: 'a', dist: 4},
            {head: 'c', tail: 'b', dist: 1}
        ];
```    

You can also make your graph bidirectial by calling:

```
var bidirectional = true;
graph = new Graph(map, bidirectional);
```

Note: bidirectional only is applied to array or edges.

<h1 align="center">
    <br>
    <a style ="color:black; text-decoration:none;" href="">Path Searcher</a>
</h1>

<h4 align="center">A web app to help visualizing typical graph searching algorithms</h4>

<p align="center">
    <a href="#live-demo">Live Demo</a> •
    <a href="#development-stack">Development Stack</a> •
    <a href="#brief-info-about-the-algorithms">Brief Info About The Algorithms</a> •
</p>

## Live Demo

You can [play-around]() with the live demo of the project.

## Development Stack
<h1 align="center">
    <img width="20%" height="100" src="https://www.ad-ventures.cc/static/aca21772a37e26761da9d791044f4e45/3cb25/p5js-pink.png" alt="P5.js logo">
    <img width="20%" height="100" src="https://www.w3.org/html/logo/downloads/HTML5_1Color_Black.svg" alt="HTML logo">
    <img width="20%" height="100" src="https://getbootstrap.com/docs/4.0/assets/brand/bootstrap-social-logo.png" alt="Bootstrap logo">
</h1>

## Brief Info About The Algorithms
- ### **A\* Search:**
  ![screenshot](https://upload.wikimedia.org/wikipedia/commons/9/98/AstarExampleEn.gif)

  A* (pronounced "A-star") is a graph traversal and path search algorithm, which is often used in many fields of computer science due to its completeness, optimality, and optimal efficiency. One major practical drawback is its ![ComplexAlo](https://wikimedia.org/api/rest_v1/media/math/render/svg/c99d691c81f015266d1626ef381d2a1a49466fbb) space complexity, as it stores all generated nodes in memory. Thus, in practical travel-routing systems, it is generally outperformed by algorithms which can pre-process the graph to attain better performance, as well as memory-bounded approaches; however, A* is still the best solution in many cases. [More on Wikipedia](https://en.wikipedia.org/wiki/A*_search_algorithm#cite_note-Zeng-3)

- ### **Breadth First Search (BFS):**
  ![screenshot](https://upload.wikimedia.org/wikipedia/commons/4/46/Animated_BFS.gif)
    
    Breadth-first search (BFS) is an algorithm for traversing or searching tree or graph data structures. It starts at the tree root (or some arbitrary node of a graph, sometimes referred to as a 'search key'), and explores all of the neighbor nodes at the present depth prior to moving on to the nodes at the next depth level. <_Wikipedia_>
- ### **Depth First Search (DFS):**
    ![screenshot](https://upload.wikimedia.org/wikipedia/commons/thumb/7/7f/Depth-First-Search.gif/220px-Depth-First-Search.gif)
    
    Depth-first search (DFS) is an algorithm for traversing or searching tree or graph data structures. The algorithm starts at the root node (selecting some arbitrary node as the root node in the case of a graph) and explores as far as possible along each branch before backtracking. <_Wikipedia_>

- ### **Best-First Search (Greedy):**
    ![screenshot](https://upload.wikimedia.org/wikipedia/commons/thumb/5/57/Dijkstra_Animation.gif/220px-Dijkstra_Animation.gif)
    
    Best-first search is a search algorithm which explores a graph by expanding the most promising node chosen according to a specified rule.
    Judea Pearl described best-first search as estimating the promise of node n by a "heuristic evaluation function f(n) which, in general, may depend on the description of n, the description of the goal, the information gathered by the search up to that point, and most important, on any extra knowledge about the problem domain."
    Some authors have used "best-first search" to refer specifically to a search with a heuristic that attempts to predict how close the end of a path is to a solution, so that paths which are judged to be closer to a solution are extended first. This specific type of search is called greedy best-first search or pure heuristic search.
    <_Wikipedia_>
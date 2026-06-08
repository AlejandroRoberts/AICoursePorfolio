# Project 3 - Search Algorithms

## Objective 
The objective of this assignment was to apply classical AI search techniques to two different domains: shortest path planning in an environment with obstacles and the Missionaries and Cannibals problem. The project focused on representing each problems as a search problems, selecting appropriate search algorithms, and analyzing how different search strategies affect solution quality and efficiency. 

## Implementation 

The assignment was divided into two main problems. The first problem involved finding the shortest collision free path between a start and goal location in a plane containing convex polygonal obstacles. To solve this problem, a visibility graph was constructed using obstacles vertices, and search algorithms were applied such as: 

- Bread first Search 
- Uniform Cost Search 
- Greedy Best first Search
- A* Search 

The second problem focused on the Missionaries and Cannibal puzzle. A state representation was developed to track the number of missionaries, and the boat location. Valid actions and state transitions were implemented while enforcing the safety constraints of the problem. Finally, a Breadth First Search was then used to find an optimal solution while avoiding repeated states. 

## Challanges 

One of the main challenges of this assignment was correctly formulating each problem as a search problem. I learned that the quality of the solution depends heavily on how the problem is represented. Because of this, we defined states, actions, successor functions, goal tests, and path costs. 

Additionally, understanding the differences between the search algorithms and determining which one should be used was a big challenge for me. While several algorithms were capable of finding solutions, I had to find the optimal search algorithm for each problem. 

## Lessons Learned

This assignment helped me better understand how search algorithms are applied to different types of AI problems. Although both problems where in a way different, the same general search framework could be applied. The project also allowed me to compare when different search algorithms are the most effective depending on the problem/situation. For example, in the first problem the breadth first search was able to find a solution, but did not necessarily produce the shortest geometric path. However, the Greedy best First search often explored fewer states but could not produce longer paths. Moreover, the A* search provided the best overall balance by using a heuristic to guide the search while still maintaining an optimal solution. 

## Final Thoughts 
I consider this assignment one of the most important projects of the course because it connected many of the search concepts discussed in class with practical implementations. It showed me that AI is not only about finding solutions, but also about finding efficient ways to represent problems. I am also motivated to explore how these algorithms can be applied in different real world problems.

I especially enjoyed the A* search, how it combines the actual path cost with a heuristic estimate to guide the search toward the goal more efficiently. A* seemed like the most balanced approach because it could still find optimal solutions while reducing the amount of unnecessary exploration. 
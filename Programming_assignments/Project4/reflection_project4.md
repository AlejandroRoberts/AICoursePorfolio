# Local Search Algorithms for the 8-Puzzle and 8-Queens Problems

## Objective

The objective of this assignment was to compare the performance of different local search algorithms on the 8-puzzle and 8-queens problems. The project focused on understanding how local search methods navigate a search space, handle local optima, and balance exploration and exploitation when searching for a solution.

## Implementation

The project was developed using the AIMA Python repository and evaluated four local search algorithms:

- Steepest-Ascent Hill Climbing
- First-Choice Hill Climbing
- Random-Restart Hill Climbing
- Simulated Annealing

Random instances of the 8-puzzle and 8-queens problems were generated and solved using each algorithm. For every instance, the exact reference cost was computed and used to compare algorithm performance across different levels of difficulty.

The experiments recorded whether each algorithm successfully solved the problem and the number of neighbor evaluations required during the search. The results were collected and organized into tables and graphs using pandas and matplotlib, allowing us to compare success rates and search costs across the different algorithms.

## Challenges

One of the challenges we faced was understanding why the same algorithm could perform differently depending on the problem being solved. Although the algorithms remained the same, the structure of the search space had a significant impact on performance. The 8-puzzle often contained plateaus and local optima that prevented algorithms from reaching the goal, while the 8-queens problem generally provided more opportunities for improvement through local moves.

Another challenge was evaluating performance beyond simply finding a solution. Since local search algorithms do not guarantee optimal results, it was important to analyze success rates, search costs, and the number of neighbor evaluations in order to make meaningful comparisons between algorithms.

## Lessons Learned

This assignment helped me better understand the strengths and limitations of local search algorithms. The results showed that random-restart hill climbing generally achieved the highest success rates because it could recover from poor starting positions by exploring multiple search paths. Simulated annealing demonstrated how temporarily accepting worse states can help escape local optima and improve the chances of finding a solution.

The project reinforced concepts such as local optima, heuristic evaluation, exploration versus exploitation, and performance analysis. It also showed that the effectiveness of an algorithm depends heavily on the structure of the problem being solved rather than the algorithm alone.

The experiments demonstrated the importance of collecting data and evaluating AI systems through testing. Rather than assuming that one algorithm would always outperform another, the results showed that each search strategy has advantages and disadvantages depending on the environment and problem characteristics.

## Final Thoughts

I enjoyed this project because it allowed me to compare several Artificial Intelligence techniques in a practical setting and observe how they behaved on different types of problems. It was interesting to see how the same algorithm could produce very different results depending on the structure of the search space.

Overall, I am very pleased with what we as a group accomplished and how this project strengthened my understanding of local search algorithms and optimization techniques. It provided a practical demonstration of concepts discussed in class and showed the importance of experimentation when evaluating Artificial Intelligence systems.
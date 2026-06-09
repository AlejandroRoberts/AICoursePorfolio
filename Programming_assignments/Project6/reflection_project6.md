# Project 6 - Constraint Satisfaction Problem

## Objective 

The objective of this assignment was to solve the Zebra puzzle by formulating it as a Constraint Satisfaction Problem. The project focused on representing the problem using variables, domains, and Constraints and then applying CPS techniques to find a solution that satisfied all the given clues. 

## Implementation 

The Zebra Puzzle was modeled using the AIMA Python CSP framework. The representation assigned a house position from 1 to 5 to each attribute in the puzzle, including colors, nationalities , candies, drinks, and pets. This resulted in a total of 25 variables, each with a domain consisting of the five house positions. 

The clues provided in the puzzle were translated into constraints, These include equality constraints, adjacency constraints, ordering constraints, and all different constraints to ensure that no two houses shared the same attribute within a category. The problem was solved using backtracking search with the minimum remaining values (MRV) heuristic and forward checking to improve efficiency. 

## Challenges

The main challenge we faced as a team was translating the natural language clues into mathematical constraints that could be understood by the CSP solver. While the clues appear straightforward when read by a person, converting them into precise relationships between variables required careful attention to detail.

Additionally, debugging constraints was challenging because a single incorrectly defined constraint could prevent the solver from finding a valid solution. This required verifying that every clue was properly represented and that all constraints worked together consistently. 

## Lessons Learned

This assignment helped me better understand the fundamentals of Constraint Satisfaction Problems and how many reasoning task can be represented using variables, domains, and constraints. The CSP solver successfully found a solution that satisfied all the puzzle's constraints. The final solution determined that the Japanese person owned the zebra and that the Norwegian drank water. Verifications Checks confirmed that every clue provided in the puzzle was satisfied by the final assignment. 

I learned how heuristics such as MRV and techniques like forward checking can improve search efficiency by reducing unnecessary exploration.

## Final Thoughts
What I found most valuable was learning how different representations can affect both readability and solver performance. Although the final solution was important, the process of modeling the problem taught me more about AI problem formulation and the importance of designing an effective representation before attempting to solve a problem 

Because this was the final Programming assignment, I want to highlight the progress we have made as a group since the start of the semester. The development processes has shown a dramatic improvement since the first time we worked as a team. I am satisfied with the work we have done during the semester and how we have learned to work with each other using our own individual strengths to our advantage.  


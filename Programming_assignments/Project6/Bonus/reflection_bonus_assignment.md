# Bonus Assignemt - Sudoku Solver Using CSP

## Objective 

The objective of this bonus assignment was to formulate and solve Sudoku as a Constraint Satisfaction Problem. The project focused on representing the puzzle using variables, domains, and constraints while applying CSP techniques to efficiently solve puzzles of varying difficulty levels.

## Implementation 
The Sudoku board was modeled as a CSP with 81 variables, one for each cell in the puzzle. Each variable had a domain consisting of the digits 1 through 9, while pre-filled cells were assigned singleton domains based on the puzzle clues. Constraints ensured that no digit was repeated within any row, column, or 3x3 sub-grid. 

The solver was implemented using the AIMA Python CSP framework and combined several CSP techniques, such as:

- AC-3 constraint propagation
- Backtracking search
- Minimum Remaining Values (MRV)
- Degree heuristic tiebreaking
- Least Constraining Value (LCV)
- Maintaining Arc Consistency (MAC)

Additionally, the solver was tested on easy, medium, and hard levels to evaluate its effectiveness and efficiency.
## Challenges 
A main challenge of this assignment was understanding how a Sudoku puzzle could be represented as a CSP rather than a traditional search problem. Instead of searching for a sequence of actions, the objective was to find a complete assignment that satisfied all constraints simultaneously.

In another way, interpreting the performance metrics was interesting because the harder puzzles required significantly more recursive calls and search effort than the easier puzzles. 
## Lessons Learned
The assignment helped me further understand how CSP techniques can be applied to real world reasoning problems. It reinforced the concepts of variable, domains, and constraints while demonstrating how propagation and heuristic can dramatically improve solving efficiency

The solver successfully solved all three puzzles (easy, medium, and hard). The experiments demonstrated that CSP techniques significantly reduced the amount of search required compared to plain backtracking

## Final Thoughts
I found this assignment very entertaining because Sudoku is a puzzle that most people solve manually, yet it can be represented mathematically as a CSP. While the Zebra puzzle helped me understand the fundamentals of CSP and problem formulation, this bonus assignment allowed me to explore more advanced CSP techniques. 

Overall, this bonus assignment was useful to further understand CSP and demonstrated how AI can solve complex logical problems through efficient reasoning and constraint propagation 
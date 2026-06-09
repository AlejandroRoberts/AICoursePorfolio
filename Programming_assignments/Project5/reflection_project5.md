# Project 5 - Adversarial AI in Games

## Objective

The objective of this assignment was to design and evaluate an agent capable of playing a game of Briscas (Two player version). The project focused on adversarial search concepts, decision making under uncertainty , and the use of Monte Carlo Simulation to evaluate possible future outcomes in a game with hidden information. 

## Implementation 

The project was developed using the AIMA Python Game framework and implemented the complete rules of a two player Briscas game. The environment included card representations, game state management, scoring rules, legal actions, and state transitions (next rounds) 

Three different agents were implemented and compared:

- Random agent: Selected legal moves uniformly at random
- Heuristic agent: used game specific knowledge and predefined strategies
- Monte Carlo agent: Evaluated legal moves by sampling possible hidden card distributions and simulating future game outcomes. 

Multiple tournaments where conducted between each agent and results where collected and organized in tables and graphs using matplotlib and pandas libraries. 

## Challanges
 One of the challenges we faced was translating the card game to code. The simulator needed to accurately manage card strengths, trick winners, score calculations, draw mechanics, and legal moves while maintaining a valid game state throughout the entire match. Additionally, Balancing performance and decision quality was an important consideration. Increasing the number of Monte Carlo simulations generally improved decision making but it also increased execution time. Finding a reasonable balance between accuracy and computational cost became an important part of the project. 

## Lessons Learned 

This assignment showed me how AI can be applied to adversarial environments that contain uncertainty and hidden information. The tournament results showed that the Monte Carlo agent consistently outperformed the random agent, demonstrating that simulation-based decision making provides a significant advantage over random play, However, performance is limited to the capacity of simulations that can be handled. In comparison with the heuristic agent, it was more competitive because the heuristic player made decisions based on game specific strategies and rules previously given. 

The project reinforced the importance of experimentation and evaluation, Rather than assuming an agent performs well, repeated tournaments and statistical analysis were necessary to measure its actual performance against different opponents. One can assume that the random agent will always lose against the Monte Carlo agent, but the data showed that the random agent was able to win in some instances. 


## Final Thoughts 

I really enjoyed this project because of the game environment we where able to build. It was entertaining to run the tournaments and see how each agent performed. Moreover, it was satisfying to see the games run correctly when introduced with the correct set of rules and game state management. 

Overall, I am very pleased with what we as a group built and how this project strengthened my understanding of adversarial AI, decision making under uncertainty, and the importance of evaluating AI systems through experimentation. It also gave me a greater appreciation for the complexity involved in designing game playing agents and the tradeoffs that must be considered when balancing performance and computational resources.
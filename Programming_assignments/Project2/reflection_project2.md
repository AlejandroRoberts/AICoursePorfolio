# Programming homework assignment Chapter 2 - Agents

## Objective 
The objective of this assignment was to design and analyze intelligent agents operating within different versions of the vacuum cleaner world. The project focused on applying the PEAS framework, implementing various agent architectures, and evaluating their performance in environments with different levels of complexity and observability

## Implementation 
The assignment was divided into two exercises. In the first exercise we implemented a modular vacuum world simulator following the PEAS framework. The simulator separated the agent program environment dynamics, sensors, actuators, and performance evaluator to create a flexible design. Multiple agents were tested, including a simple reflex agent and a random agent to compare their performance. 

In the second exercise, we explored a more challenging environment where the environment was unknown to the agent. To address this problem. We implemented three different agent architectures:

- simple reflex agent
- randomized reflex agent 
- stateful reflex agent

Each agent was evaluated in multiple environments to observe how exploration, memory, and decision making affected performance. Pandas and matplotlib was used for data visualization. 

## Challenges

One of the main challanges of this assignment was designing the environment and agent in a modular way while ensuring that each component remained independent. The PEAS framework that was built needed to interact correctly without becoming highly dependent on one another. 

Another challenge was understanding and implementing how the agents would behave when placed in different environments. While implementing the randomized and stateful agents, it became clear that there is no single strategy that performs best in every scenario. We just needed to find a way to make the agents take a direction when faced in a particular situation in the environment. Through experimentation, I observed how different factors such as agent type and environment significantly affected an agent's performance 

## Lessons Learned

The results showed that the simple reflex agent performed well in the classic two-location vacuum world because the environment was small and the available inputs provided sufficient information for effective decision making

In the unknown environment, the randomized reflex agent generally outperformed the reflex agent by exploring more of the environment. However, additional experiments demonstrated that randomness is not always effective. In structured environments, the randomized agent performed worse because it wasted time exploring unnecessary directions. 

# Final thoughts 

This assignment helped me better understand the relationship between an agent and its environment. This project was great for connecting theoretical concepts with practical demos, making the experience interactive and interesting for me and my group. Although it was hard to grasp the final implementation, it gave me the motivation to keep exploring different solutions with my team

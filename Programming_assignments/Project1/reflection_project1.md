# Project 1 - Python Performance with and without NumPy

## Objective 

The objective of this assignment was to compare the performance of pure python implementation against Numpy implementations for vector and matrix multiplication. The project focused on understanding how different implementations affect computational efficiency and scalability 

---

## Implementation 

We implemented both operations using standard Python loops and then compared them against NumPy's optimized implementation of element-wise multiplication and library uses such as BLAS. After verifying that both approaches produced the same result, we measured their execution times for different input sizes and analyzed how performance changed as the problem size increased. 

## Challanges 

One of the main challenges was implementing matrix multiplication efficiently in pure Python while ensuring correctness. Since matrix multiplication has cubic time complexity, large matrices required significantly more execution time, making it important to structure the code carefully. During development, we underestimated how computationally expensive large matrix operations could become, and at one point my computer became unresponsive while running the program 

## Lessons learned 

This assignment helped me better understand computational complexity and the impact of implementation choices on performance. It demonstrated how optimized numerical libraries such as NumPy can dramatically improve execution speed compared to interpreted Python loops. 

As a team, our brainstorming needs better organization, although I am confident that in the future this will be less of a problem. 

## Final thoughts

The project provided a practical introduction to performance analysis and numerical computing. Beyond comparing execution time, it helped me appreciate how decisions in design can influence efficiency and scalability. Additionally, this project has provided me with an introduction for what to take in mind for future projects and an introduction of new tools that will be used in the future. The results clearly illustrated why scientific and AI applications often rely on optimized libraries rather than implementing large numerical operations directly in pure Python. 
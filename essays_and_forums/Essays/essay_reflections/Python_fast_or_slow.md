# Python Fast or Slow Assignment

## Objective
This assignment consisted of comparing the computational performance of pure Python and NumPy implementations for elements wise vector multiplication and matrix multiplication. The essay focused on understanding how implementation choices algorithmic complexity, and optimized numerical libraries affect execution time and scalability. 

## Summary
This essay evaluated element wise vector multiplication and matrix multiplication. Both operations were implemented using pure Python and NumPy, and their execution times were measured and compared. The analysis focused on how performance changed as the size of the vectors and matrices increased. 

The results showed that NumPy consistently outperformed pure Python, with the difference becoming more significant as the problem size increased. For vector multiplication, NumPy achieved noticeable performance improvements, while for matrix multiplication the advantage became dramatic due to the computational complexity of the operation. The report explained how Python's interpreter overhead and nested loops contribute to slower execution times, while NumPy delegates computationally intensive operations to optimize compiled libraries such as Basic Linear Algebra Subprograms (BLAS). These libraries are designed to execute numerical operations efficiently by taking advantage of optimized memory access patterns, vectorized instructions, and low-level hardware optimizations. The findings demonstrated the importance of selecting appropriate tools and numerical libraries when working with computationally intensive tasks.

## Final Thoughts
This report showed me the relationship between algorithmic complexity and software performance. Before completing the assignment, I understood that some implementations could be faster than others, but I did not fully appreciate how significant those differences could become when processing large amounts of data. 

Additionally, during this semester I was taking Linear Algebra. It was useful to see this material because I actually implemented the NumPy library in assignments from that class. 

In conclusion, this topic strengthened both my understanding of computational efficiency and my ability to analyze and present experimental results.





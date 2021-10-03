# Dynamic Programming
![images](https://media.geeksforgeeks.org/wp-content/cdn-uploads/Dynamic-Programming-1-1024x512.png)

The topic that I chose to write about is **Dynamic Programming** which is a technique commonly used to solve programming questions. The technique *recursively* breaks down the problem into smaller simplier sub problems that make it easier to solve the main question. The idea is that the [optimal solution](https://www.geeksforgeeks.org/dynamic-programming/) for the main problem can be found by creating optimal solutions for sub problems. 


## About

Often times when using Dynamic programming we can reduce the amount of time an algorithm solves a problem. A common example of this is reducing the time complexity from expoential to a polynomial runtime*(ex:exponential to linear runtime)*. This technique breaks down the problem into simplier sub-prpblems, and programming this can often mean using helper methods to solve a part of a question if that part of the question shows up multiple times in a problem. For example, keeping a seperate method for sorting an array in a complex array programming question could be considered dynamic programming. 



## Uses in Dynamic Programming

Besides computer programming this technique can be used in:

- mathmatical problems
- economics
- bioinformatics

A common usecase in math are the Bellman equations which use a recursive relationship between value functions to calcutate the value of y from the value functions at i-1. The optimal values for all the decision variables can be found by tracking the calculations at each state. 


### Economics 
In economics we can also use value functions to **maximize/minimize** dynamic social welfare problems. Similarly to mathematics we use value functions from previous states in order to find the most optimal solution for solving *social economic problems*. A good example of this is [Ramsey's problem](https://en.wikipedia.org/wiki/Ramsey_problem), which in simple terms relates the different levels of utility of a product to the amount of consumption that product takes. An example of this would be for a manufacturer deciding how much to raise the products price so that the revenue equals the total cost of producing the good.
### Bioinformatics
In bioinformatics algorithms have been used in the case of RNA structure predicting, protein DNA binding, and sequence alignment. The first algorithm of this kind used in bioinformatics was for protein DNA binding developed by **Charles DeLisi** in the 1970s. As of lately common areas where dynamic programming is used is in transcription factor binding and nucleosome positioning.  
![Dyanmic Programming in Bioinformatics](https://slidetodoc.com/presentation_image_h/165110be40e0efb492f3aff979a67f0e/image-58.jpg)


## Examples of Dyanmic Prgramming Computer algorithms

One of the simpliest examples of dybamic programming in computer science in when you have to **calculate the nth number in a fibonacci sequence**. The way dynamic programming improves the straightforward naiive approach, is instead of calucating the [fibonacci sequence](https://en.wikipedia.org/wiki/Fibonacci_number) for the numbers leading up to the nth number, *we store the values in a map* thereby removing all the uncessary recomputations that add the the time of the naiive algorithm approach. By removing uncessary operations we get to the most optimized version of the solving the ficonacci problem(the difference in time is from O(n^2) -> O(n)). 

Another example dynamic programming is used is in path finding algorithms specifically [Dijkstra's algorithm](https://www.geeksforgeeks.org/dijkstras-shortest-path-algorithm-greedy-algo-7/). There is a dynamic programming functional equation that this algorithm successively approximates the shortest distance from one node to another node. The algorithm starts with a beginning vertex and find the shortest paths to all other nodes in the graph. 

![Dijkstra's](https://i.ytimg.com/vi/pVfj6mxhdMw/hqdefault.jpg)





## See also
- [Dynamic Programming Overview](https://en.wikipedia.org/wiki/Dynamic_programming)
- [Programming Questions using Dynamic Programming](https://www.geeksforgeeks.org/dynamic-programming/)
- [From Beginner to Advanced Dynamic Programming](https://www.topcoder.com/thrive/articles/Dynamic%20Programming:%20From%20Novice%20to%20Advanced)

## References
1. “What Is Dynamic Programming?” InterviewBit, InterviewBit, https://www.interviewbit.com/courses/programming/topics/dynamic-programming/. Accessed 3 Oct. 2021.  
2. What Is Dynamic Programming With Python Examples, Skerritt.blog, 31 Dec. 2019, https://skerritt.blog/dynamic-programming/. Accessed 3 Oct. 2021. 
3. Dynamic Programming, Wikipedia, 25 Sept. 2021, https://en.wikipedia.org/wiki/Dynamic_programming. Accessed 3 Oct. 2021. 
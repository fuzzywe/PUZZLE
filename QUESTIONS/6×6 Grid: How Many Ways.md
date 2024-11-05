Puzzle – 6×6 Grid: How Many Ways?
Last Updated : 18 Jan, 2023
Question: 
You begin in the top left corner of a 6×6 grid, and your objective is to move to the bottom right corner. There are just two directions you can move: right or down. Both diagonal and backward movements are prohibited. How many different ways are there to get from the start to the finish?

Solution:
The problem is to count all the possible paths from the top left to the bottom right of a 6×6 grid with the constraint that from each cell you can either move only to the right or down.
we can solve this problem using two approaches:-

Approach 1
Using Combinatorics:
Three conditions of reaching at the last end
Three conditions of reaching at the last end

Example of some ways to reach endpoint
Example of some ways to reach endpoint

We can see here that the number of paths from starting left point to the right ending is not depending on the way of the path, it depends on the number of rows and columns taken to reach the end. Whenever we face such kind of problem, where we have a choice to take or a fixed number of rows or columns to be taken in grid. We can think about mathematics in those cases. Here, we are going to use a mathematical concept, called combinatorics.
 

Why combinatorics?
In this case of a 6×6 grid, all the paths must consist of a total of 10 moves, 5 down and 5 right, our job is to select the 5 right moves from the collection of 10 moves. we must employ a certain number of rows and columns (5 of the total 10 blocks) to travel from the left beginning to the right end.
if we choose 5 rows box then the answer is 10c5=252 and the same if we choose 5 column answer is 10c5=252.

# :octocat: N-Queen-Solutions

### What is the N-Queen problem?
The N Queen is the problem of placing N chess queens on an N×N chessboard so that no two queens attack each other. For example, the eight queens puzzle is the problem of placing eight chess queens on an 8×8 chessboard so that no two queens threaten each other.  
Thus, a solution requires that no two queens share the same row, column, or diagonal.     

## What is the purpose of this repo:

Some highly comprehensive and well-documented solutions to the N-Queens Problem. 

### Added Solution-1 
For a very basic and detailed understanding of the solution of the N-Queens problem.  
Drawback: For values of the size of the board>15, the Kernel might take a very long time. </br>
This is not the most efficient solution out there (wrt time complexity), although it does get the preliminary job done.

### Added Solution-2 
For a better and different understanding of the solution of the N-Queens problem.  
This notebook contains two no_conflict() functions. The first one (commented out) is slightly more time-intensive than the second (active).  
Feel free to compile using each of them to notice the difference in time taken for finding the solutions.
Drawback: For values of the size of the board>15, the Kernel might take a very long time. </br>

### Added Solution-3 
For a slightly advanced understanding of the solution of the N-Queens problem using Permutations (itertools).  
This is done using the:
#### Raymond Hettingers permutations based solution.  
Drawback: One disadvantage with this solution is that we can't simply "skip" all the permutations that start with a certain prefix, after discovering that that prefix is incompatible. For example, it is easy to verify that no permutation of the form (1,2,...) could ever be a solution, but since we don't have control over the generation of the permutations, we can't just tell it to "skip" all the ones that start with (1,2) </br>

### Added Solution-4 
For a quick and simple understanding of the use of recursion in the backtracking solution of the N-Queens problem.  
Drawback: Please note that the main aim of this code is just to demonstrate the use of recursive algorithms for backtracking.  
So there is only one board output for a given size of board. </br>

</br>

### For visualisation of the solving of the N-Queens Problem, check out https://www.cs.usfca.edu/~galles/visualization/RecQueens.html
</br>

## Support me
If you have any other solution to this fantastic problem, feel free to share with me.  
I am open to collaborations!  
Feel free to contact me at rb1311997@gmail.com  

### Thank you!

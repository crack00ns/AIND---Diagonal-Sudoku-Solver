# Artificial Intelligence Nanodegree
## Introductory Project: Diagonal Sudoku Solver

# Question 1 (Naked Twins)
Q: How do we use constraint propagation to solve the naked twins problem?  
A: Contraint propagation is all about using local constraints in a space (in the case of Sudoku, the constraints of each unit) to reduce the search space iteratively until the space can't be reduced any further. Naked Twins case is another constraint that we apply after eliminate followed by only choice contraint. The order doesn't really matter. We might as well apply only choice followed by naked twins. All the contraints reduce the search space and we are doing exactly that in order to reach a solution if possible 

# Question 2 (Diagonal Sudoku)
Q: How do we use constraint propagation to solve the diagonal sudoku problem?  
A: In case of a diagonal Sudoku problem, everything remains the same except we add diagonal units to our list of units too. This will make sure diagonal constraints are satisfied too. 

### Install
This project requires **Python 3**.

We recommend to install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project. 

##### Optional: Pygame
Optionally, you can also install pygame if you want to see your visualization. If you've followed our instructions for setting up our conda environment, you should be all set.

### Code

* `solution.py` - Implemented naked_twins function and added diagonal contraints.
* `solution_test.py` - Do not modify this. You can test your solution by running `python solution_test.py`.
* `PySudoku.py` - Do not modify this. This is code for visualizing your solution.
* `visualize.py` - Do not modify this. This is code for visualizing your solution.

Models -->
1. 3D Array Representation
2. 1D Array Representation
3. Bit-board Reprsentation

Solvers -->
1. Bfs Solver 
2. Dfs Solver
3. ...


Abstract Class for Models --->
1. All the 18 different rotations of the cube: F, Fprime, F2, U, Uprime, etc.
2. Print function: A function that takes the Rubik’s Cube and prints it in the Planar Representation Format.
3. Random Shuffle: A function that returns a randomly shuffled Rubik’s Cube which is solvable.
4. isSolved(): a boolean function that tells whether the current configuration of the Rubik’s Cube is solved or not.


How to get a shuffled array --->
1. Take 3x3x6 colors and add it any where (May not be solvable)
2. Take a solved rubiks cube and do some random moves (Will definately be solvable)
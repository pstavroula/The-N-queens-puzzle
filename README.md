The N-queens puzzle


Project description
The N-queens puzzle is to place N queens on an N x N chessboard such that no two queens threaten each other. This project uses a genetic algorithm that creates an amount of situations (chessboard snapshot) represented by chromosomes. Using a fitness function creates generations and makes possible mutations to reach the best possible solution.


Usage
Compile java files and run main class.
Input a prime number that represents the number of queens and the size of the chessboard
The output of the program is the best solution of the given number anlong with the runtime


Components
Main class
Running the project main class prompts user to enter prime number that represents the number of queens that need to be placed in a N*N chessboard.
GeneticAlgorithm is initialised and runs.
Gives us the best solutuin found and the runtime

GeneticAlgorithm class
Uses the core logic of the genetic algorithm
Creates 2 ArrayList (that represent the population) of object Chromosome  and fitness number. 
Initializes the population, performs selection, crossover, and mutation to evolve solutions.

Chromosome 
Creates a table that represents each spot on the chessboard for each queen.
Encodes position of queens on the board
Includes methods for calculating fitness,mutating and reproducing

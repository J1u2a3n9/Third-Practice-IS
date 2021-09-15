# Third-Practice-IS

Names: Balderrama Mauricio
       Canedo Juan Luis
       La Fuente Mercedes

IMPORTANT!

--> How to use
* After cloning the repository enter the folder, open a git bash and put the following command: git checkout master, with this command you will be able to see all the files 
* For the correct functioning of the code you first need to install "numpy" from the console with the following command: pip install numpy  

### Problem-Solver Agent

### Objective Formulation:
    The first square of the puzzle must start with the number zero and the other squares with the following consecutive numbers 

### Problem Formulation:

### Initial State:
      Puzzle with random values in the squares 
      
![8-Puzzle](https://user-images.githubusercontent.com/74753713/132054522-fc84e30a-10ad-4ab8-b0db-c76c92a4af37.png)


### Objective State:
     Puzzle with values equal to that of the target state
 
![8-Puzzle - copia](https://user-images.githubusercontent.com/74753713/132054536-42d15fd9-cb60-4c35-842d-28dffc1354c5.png)



### Test of Objective:
     Is the initial puzzle the same as the target puzzle?
 
### Actions:
      Moven Up
      Move Down
      Move Right
      Move Left



### Cost:
     Cost dependent on the heuristic functions to be applied
  
  


1. h1(n) Number of parts out of place with respect to the target condition
2. h2(n) Sum of the Manhattan distance
3. h3(n) Sum of inverse permutations

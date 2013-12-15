SquareProblem
=============

CS 1336 – PROJECT 5 – Pattern Squares 
CS 1336 – PROJECT 5 – Pattern Squares 
Pseudocode Due: in eLearning - 11/21 by 11:59 PM – No late submissions accepted 
Code Due:   in eLearning - 12/15 by noon – No late submissions accepted 
THIS PROJECT WILL COUNT FOR DOUBLE POINTS 
Submission: The program and pseudocode are to be submitted in eLearning.  Please submit a Word document or PDF for the pseudocode and the program’s .cpp file for the project Pseudocode will not be accepted late. 
Problem:  Write a program that uses a two-dimensional character grid (15 rows and 15 columns) and generates various square patterns.  The user can choose 1 of 6 different patterns and will input the symbol used to fill in the pattern: 
1. Box xxxxx x   x x   x x   x xxxxx  
2. X x   x  x x    x    x x  x   x  
3. Plus   x     x   xxxxx   x     x    
4. Bordered X – box around the x 5. Bordered plus – box around the plus 6. Checkerboard x x x  x x  x x x  x x  x x x   
The program should contain (at a minimum) the following functions: 
 GetUserChoice – no parameters, returns an integer value representing the choice of the pattern the user wishes to generate.  The function should validate the input before returning the value  GetUserChar – character parameter passed by reference – The function should ask the user for the desired symbol to fill in the grid and store it in the variable passed by reference  ClearGrid – array parameter, no return type. The function should write a space into each element of the array  FillBorder – array parameter and character parameter (symbol to use in the grid), no return type.  The function should fill in the outer borders of the grid with the symbol given  FillPlus - array parameter and character parameter (symbol to use in the grid), no return type.  The function should fill in the middle row and column of the grid with the symbol given  FillX - array parameter and character parameter (symbol to use in the grid), no return type.  The function should fill in the outer borders of the grid with the symbol given  FillCheckerBoard – array parameter and character parameter (symbol to use in grid), no return type.  The function should mark every other box in a checkerboard fashion with the symbol given.  WriteGrid – array parameter, no return type.  This function should write the grid to the screen 
All patterns must be created using nested loops.   
The remainder of the code can be in the main function.  The menu presented to the user should have an option allowing the user to exit the program. 
Input:  The user must be provided a menu to select the pattern.  You must validate that the menu selection by the user is valid.  You may assume that the user will enter the proper data type for the information.  You must verify that what they entered is a valid option from the menu. 
Output: All output will be to the screen. 
Helpful Hint:  Those wanting to make the ClearGrid function work more effectively may want to take a look at the strcpy function in the cstring library (Chapter 10). 

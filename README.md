# WordPuzzleSolver

 (The full source code will be available in late decemeber to avoid academic pilgraism for CS 2150: Program and Data Representation class)

 In a grid of letters, the goal is to find words in the puzzle in any of the eight directions. The word circled in red is in the south-east direction. Words can go backward (although none do in this example), but they cannot "wrap around" from one side to the other (or from top to bottom, etc.).

A string of letters from the grid depends on four values:

    The x value of the starting letter
    The y value of the starting letter
    The direction, d, of the word
    The length, l, of the string

![Image](https://upload.wikimedia.org/wikipedia/commons/thumb/f/fa/Wordsearch.svg/948px-Wordsearch.svg.png)

So, given a dictionary and word search grid, your program should output all the words in the grid that are in the dictionary.
There are two main parts to this lab: creating a hash table and writing a word search solver.Word search solver, implemented in wordPuzzle.cpp, should:

1- Take in a dictionary file and grid file, in that order, using command line parameters
2- Read in a dictionary and store its words in a hash table which is implemented without using a vector of vectors or any STL hash table
3- Read in a word search grid no larger than 500x500 and store it in an appropriate data structure
4- Output every word of length three or greater and its location in the grid
5- Output the time it took to find all the words
6- Employs various optimization techniques to find the words in minimum possible time. 
    
  Here are results from come runs of the program. This program was written, built and ran on emacs on a linux machine.
  
  

  ![Image](https://i.imgur.com/0gcUeXZ.png)
![Image](https://i.imgur.com/5UhSGLo.png)
![Image](https://i.imgur.com/MN6wyDs.png)

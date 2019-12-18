#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a O(n). It's like a for loop.

b) O(n^2).  It has two nested loops.

c) O(n). Same as a factorial. It's just keeps getting smaller and adds them up, eventually getting to 0.

## Exercise II

 1. Start off on the middle floor (f // 2) and drop an egg. 

 2. Check to see if egg break == False: move halfway up to the top floor. 
 
 3. Check to see if egg break == True: move halfway up to the bottom floor.
 
 4. Recurse through until the the floor is reached with the lowest
    number of broken eggs.

  The average performance of the method results in a complexity of O(n log n).


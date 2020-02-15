# python-bubbleSort
Bubble Sort implementation, in Python3
Bubble sort is one of the easiest sorting algorithms out there. 
It works by taking 2 adjacent cells, and swapping them if they are not in order. 
THe above step is repeated until the whole array is sorted. 

Example : 

Input array = [ 8, 34, 2, 7, 8 ] 
After , 
      First pass : [8, 34, 2, 7, 8]
      Second pass : [8, 2, 34, 7, 8] 
      The last pass : [2, 7, 8, 8 , 34 ] 
      
 NB : After very iteraction, we are getting the last position fixed. So , in the consequent iteration, we dont have to check for the last position. In other words , the program evaluates all n positions in the first iteration, n-1 in the second, n-2 in hte thirs and so on . 
The last pass happens when the program traverses through the whole array without any swap. 

CONS: 
 1 : Multiple swaps in each iteration.

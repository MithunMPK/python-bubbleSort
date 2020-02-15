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
The last pass happens when the program traverses through the whole array without any swap. 
So, its important to keep a flag, to keep in track of any swaps that happened in the last pass. 

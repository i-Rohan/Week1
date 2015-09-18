# Week1
#Category HAL9000 (Beginner)
##Minimum Dot Product: 
We’re all familiar with vectors in physics. Represent a vector as a set of n integers, and calculate the minimum scalar product of the vectors. For example: - 
If Vector A is 5 4 3 1 4 6 6 
If Vector B is 1 1 2 2 1 1 8 
Then a potential final answer could be 42. (Not saying that’s the solution) 
Remember that the vectors need not be of equal length.  

#Category JARVIS
##Flood Fill
A given matrix of ‘n X k’ contains 0s and 1s. Where, 1s represent free space and 0s represents edges a shape. Flood fill the shape i.e. change the all the 1s inside it to 0s. 
Input is taken from a .txt file which contains the matrix with 0’s and 1’s.  Output should be .txt file.
n X k limit :  1024 * 1024.

Example Input:<br><br>
1 1 1 1 0 0 1 1 1 1 1 1 1 1<br>
1 1 1 0 1 1 0 1 1 1 1 1 1 1<br>
1 1 0 1 1 1 1 0 1 1 1 1 1 1<br>
1 1 1 1 0 1 0 1 1 1 1 1 1 1<br>
1 1 1 1 1 0 1 1 1 1 1 1 1 1<br><br>
Example Output: <br><br>

1 1 1 1 0 0 1 1 1 1 1 1 1 1<br>
1 1 1 0 0 0 0 1 1 1 1 1 1 1<br>
1 1 0 0 0 0 0 0 1 1 1 1 1 1<br>
1 1 1 1 0 0 0 1 1 1 1 1 1 1<br>
1 1 1 1 1 0 1 1 1 1 1 1 1 1<br>


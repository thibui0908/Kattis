You are given an 𝑛-by-𝑛 grid where each square is colored either black or white. A grid is correct if all of the following conditions are satisfied:

1. Every row has the same number of black squares as it has white squares.
2. Every column has the same number of black squares as it has white squares.
3. No row or column has 3 or more consecutive squares of the same color.
Given a grid, determine whether it is correct.

Input
The first line contains an integer 𝑛 (2≤𝑛≤24 ; n is even). Each of the next n lines contains a string of length n consisting solely of the characters ‘B’ and ‘W’, representing the colors of the grid squares.

Output
If the grid is correct, print the number 1 on a single line. Otherwise, print the number 0 on a single line.

Sample Input 1	Sample Output 1
4
WBBW
WBWB
BWWB
BWBW
1
Sample Input 2	Sample Output 2
4
BWWB
BWBB
WBBW
WBWW
0
Sample Input 3	Sample Output 3
6
BWBWWB
WBWBWB
WBBWBW
BBWBWW
BWWBBW
WWBWBB
0
Sample Input 4	Sample Output 4
6
WWBBWB
BBWWBW
WBWBWB
BWBWBW
BWBBWW
WBWWBB
1

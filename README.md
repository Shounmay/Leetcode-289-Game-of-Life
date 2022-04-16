<h1 align='center'><u><b> Game of Life</b> </u></h1>

<h2> <u>Problem Link:</u> https://leetcode.com/problems/game-of-life/</h2>

<h1 ><u> Idea Used: </u></h1>

## Here we have initialized coordinates {x,y} for neighbors of (0,0) as {(-1,0),(1,0)...so on} As we increment x cordinate the x-cordinate of initialized coordinate will also increase. After reaching a index of 2D grid and changing the initialized coordinates of neighbours, we check that a particular coordinate is valid or not, if valid then we check if thats 0 or not, then we increment the count of live neighbour of that index. If the coordinate will die(i.e value was 1), then we make that value to -1, if that coordinate will live ( it was 0), we change the value to 2, with these conditions we change final grid. hence solve this in in-place algorithm.

<h1 ><u> Time and Space Analysis </u></h1>

## Time-Complexity: O(N\*M)

## Space-Compexity: O(1)

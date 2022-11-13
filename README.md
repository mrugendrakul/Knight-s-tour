# Knight-s-tour
In this problem a knight of chess has to traverse along the chess board and find the best path so that it will cover whole chess board.

# Moves of knight in chess
Before going for real problem first let us understand how a knight moves in chess. The kinght moves in 2 steps in horizantal direction and 1 in vertical or vice versa. using this moves kinght has to travel over all keyboard.

# Need of Visualization for this problem
For better understanding of the problem we are going to visualize the tour of the knight problem in 3D using which we will have bettering understanding about the problem.

# Software used for visualization
For visualization purpose we are going to a free software "Blender". It provides us vast tools which will be needed for our visualization purpose

![image](https://github.com/mrugendrakul/Knight-s-tour/blob/main/1.png)

# Algorithm used for this problem
For our purpose we are going to use backtracking algorithm so find optimal solution.

If all squares are visited
    print solution
Else
   a) Add one of the next moves to solution vector and recursively 
   check if this move leads to a solution. (A Knight can make maximum 
   eight moves. We choose one of the 8 moves in this step).
   b) If the move chosen in the above step doesn't lead to a solution
   then remove this move from the solution vector and try other 
   alternative moves.
   c) If none of the alternatives work then return false (Returning false 
   will remove the previously added item in recursion and if false is 
   returned by the initial call of recursion then "no solution exists" )

# Using Blender for this app 
First you will need to get the Blender app from its official store for your os.
Then after starting the blender go to file and open and select the file which is availble in this repository.
Done just click on the play button on the timeline space, it near the bottom of the screen.

# Sample rendered video 

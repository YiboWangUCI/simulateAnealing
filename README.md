# simulateAnealing

Code is written in Matlab.



main1a.m
* Test simulated annealing on N by N chessboard with 0/1 coloring.
Temperature starts at 100 and cooling rate is 0.99.
Metropolis method is applied when determining if updated variable is accepted.
Stopping criteria is number of violations is 0.
Max size on the test run is 15 by 15 which cost about 20 seconds.
Data is saved in “chessboard01.txt”.

main1b.m
* Test simulated annealing on N by N chessboard with 4 colors (0,1,2,3).
Temperature starts at 100 and cooling rate is 0.99.
Metropolis method is applied when determining if updated variable is accepted.
Stopping criteria: the number of violations is 0.
Max size on the test run is 22 by 22 which cost about 60 seconds.
Data is saved in “chessboard0123.txt”.

main2.m
* Compare simulated annealing method with coordinate descend method for the same 2-dimension function below. Number of samples is 50. 

# superoptimizer-jlee671
I spent most of the time reading both "Superoptimizer: a look at the smallest program" and part of AHA documentation (I speak English as second language so it took fair amount of time for me to read and understand). 

Then I tested some of given xxx.frag.c files with different parameters and observed the instructions in the solution. I think it was pretty cool to see AHA working after I read about it in the previous paper. It was also impressive how many solutions AHA can find with more allowed number of instructions (I had to modify the code so that it only prints the number of solutions found not the actual solutions because there were simply too many). "?" in the table means it ran for too long that I had to terminate it around after 30 minutes of running.

| file (xxx.frag.c) | operations | solutions | time (sec) |
| :---:             | :---:      | :---:     | :---:      |
|abs                | 2          | 0         | 0          |
|                   | 3          | 2         | 0.01       |
|                   | 4          | 398       | 1.716      |
|                   | 5          | 112372    | 551        |
|avg                | 2          | 0         | 0          |
|                   | 3          | 0         | 0.028      |
|                   | 4          | 3         | 8.395      |
|                   | 5          | ?         | ?          | 
|bic3               | 2          | 6         | 0          | 
|                   | 3          | 244       | 0.009      |
|                   | 4          | 37068     | 1.627      |
|                   | 5          | 10178375  | 521.839    |
|bitblt             | 2          | 0         | 0          | 
|                   | 3          | 7         | 0.059      |
|                   | 4          | 2168      | 24.722     |
|                   | 5          | ?         | ?          | 
|bool               | 2          | 0         | 0          | 
|                   | 3          | 2         | 0.014      |
|                   | 4          | 449       | 2.589      |
|                   | 5          | 143807    | 844.809    | 
|invbool            | 2          | 0         | 0          | 
|                   | 3          | 4         | 0.018      |
|                   | 4          | 1128      | 3.741      |
|                   | 5          | ?         | ?          | 
|negbool            | 2          | 0         | 0          | 
|                   | 3          | 2         | 0.013      |
|                   | 4          | 493       | 2.380      |
|                   | 5          | ?         | ?          | 

Additionally, I also made some of my own xxx.frag.c files to test AHA. 

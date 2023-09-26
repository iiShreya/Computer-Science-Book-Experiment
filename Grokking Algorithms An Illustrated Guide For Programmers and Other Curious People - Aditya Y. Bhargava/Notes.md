## 1. Dynamic Programming ( *It's not always smart to be greedy* ):
1. Dynamic Programming starts by solving sub-problems and builds up to solving the big problem.
2. It is useful when trying to optimize something given a constraint.
3. Every DP solution involves a grid. And the values in the grid are what you're trying to optimize. The cells in the grid are the sub-problems.
4. Is there a common algorithm to solve all DP problems? No :( According to the author, Computer Scientists have said there does exist a simple algo to DP problems, that is, **The Feyman Algorithm**.
   You need to:
   a. write down the problem statement
   b. think real hard
   c. write down the solution
This is just a funny way of saying there's no hard defined formula for all DP questions.
   

### 1.1. The Knapsack Problem:
This one is the 0-1 Knapsack problem.
#### Some Intriguing Questions:
1. ques. What happens if you change the order of the rows?
   ans. The answer remains the same, order of rows doesn't matter.

2. ques. Can you fill the grid column-wise instaed of row-wies?
   ans. For knapsack, it doesn't make a difference. For other problems, it might.

3. ques. What happens if you add an item?
   ans. The answer changes in certain cases.

4. ques. Would the value of a column ever go down?
   ans. No, because at every iteration, you are storing the max estimate and the estimate can never get orse than it as before.


### 1.2. Longest Common Substring / Longest Common Subsequences

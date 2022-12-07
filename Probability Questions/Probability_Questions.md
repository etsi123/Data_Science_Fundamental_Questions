# Probability Fundamental Questions


## **1. Roll a dice 3 times. What is the probability of getting 2 6's in a row?**

Easiest way to solve this problem is to count the total number of ways to get 2 6's in a row, count the total number of 3 roll outcomes, and then 	  divide the two. How many ways to get 2 6's in a row? 

1. Roll 1 is a 6, Roll 2 is a 6, Roll 3 is anything (6)
2. Roll 2 is a 6, Roll 3 is a 6, Roll 1 is anything (6)
3. We counted rolling a 6 three consecutive times in both (1) and (2), so we must subtract 1. 

Therefore, answer is (6 + 6 - 1) / (6^3) = 11/216. 

## **2. Roll a dice 3 times. What is the probability of getting numbers in increasing order?**

Choose the 3 numbers. C(6,3) = 20.  Only one way to arrange in increasing order. so 20/216 = 5/54. 

## **3. Consider a three dimensional coordinate system. How many ways of getting from (0,0,0) to (3,3,3) using only ups, rights, and forwards?** 

We are going to have to take 9 steps, 3 in each direction. The order in which they are taken doesn't matter. So the solution is C(9,3)*C(6,3)*C(3,3) = 9!/(6!3!) * 6!/(3!3!) = 9!/(3!3!3!) = 1680






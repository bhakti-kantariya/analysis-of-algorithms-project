# Analysis of Algorithms Programming Project

Implemented the variations of buying and selling stock problem using Dynamic Programming and Greedy programming.  

Following are the problem variations and their solution approaches:  

**Problem1**: Given a matrix A of mxn integers (non-negative) representing the predicted prices of m
stocks for n days,  nd a single transaction (buy and sell) that gives maximum profit.  
**Task 1:** Designed a $O(m * n^2)$ time brute force algorithm for solving Problem1  
**Task 2:** Designed a $O(m * n)$ time greedy algorithm for solving Problem1  
**Task 3A & 3B:** Designed a $O(m * n)$ time dynamic programming algorithm for solving Problem1 (Recursive Memoization & iterative BottomUp implementation) 

**Problem2**: Given a matrix A of mxn integers (non-negative) representing the predicted prices of m
stocks for n days and an integer k (positive),  find a sequence of at most k transactions
that gives maximum profit.  
**Task 4:** Designed a $O(m * n^{2k})$ time brute force algorithm for solving Problem2  
**Task 5:** Designed a $O(m * n^2 * k)$ time dynamic programming algorithm for solving Problem2  
**Task 6A & 6B:** Designed a $O(m * n * k)$ time dynamic programming algorithm for solving Problem2 (Recursive Memoization & iterative BottomUp implementation)   

**Problem3** Given a matrix A of m n integers (non-negative) representing the predicted prices of m
stocks for n days and an integer c (positive), find the maximum profit with no restriction
on number of transactions. However, you cannot buy any stock for c days after selling any
stock. If you sell a stock at day i, you are not allowed to buy any stock until day i+c+1  
**Task 7:** Designed a $O(m * 2^n)$ time brute force algorithm for solving Problem3  
**Task 8:** Designed a $O(m * n^2)$ time dynamic programming algorithm for solving Problem3  
**Task 9A & 9B:** Designed a $O(m * n)$ time dynamic programming algorithm for solving Problem3 (Recursive Memoization & iterative BottomUp implementation)  

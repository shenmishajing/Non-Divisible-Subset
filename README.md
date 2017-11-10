# Non-Divisible-Subset
这是一个比较聪明的算法，利用取模运算，达到线性时间复杂度
以下是原题目：
Given a set, , of  distinct integers, print the size of a maximal subset, , of  where the sum of any  numbers in  is not evenly divisible by .

Input Format

The first line contains  space-separated integers,  and , respectively. 
The second line contains  space-separated integers (we'll refer to the  value as ) describing the unique values of the set.

Constraints

All of the given numbers are distinct.
Output Format

Print the size of the largest possible subset ().

Sample Input

4 3
1 7 2 4
Sample Output

3
Explanation

The largest possible subset of integers is , because no two integers will have a sum that is evenly divisible by :

, and  is not evenly divisible by .
, and  is not evenly divisible by .
, and  is not evenly divisible by .
The number  cannot be included in our subset because it will produce an integer that is evenly divisible by when summed with any of the other integers in our set:

, and .
, and .
, and .
Thus, we print the length of  on a new line, which is .
FROM https://www.hackerrank.com/challenges/non-divisible-subset/problem

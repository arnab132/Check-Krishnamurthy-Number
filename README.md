# Check Krishnamurthy Number Using Python

A Krishnamurthy number is a number whose sum of the factorial of digits is equal to the number itself. For example 145, sum of factorial of each digits: 
1! + 4! + 5! = 1 + 24 + 120 = 145

Examples: 

Input : 145
Output : YES
Explanation: 1! + 4! + 5! = 
1 + 24 + 120 = 145, which is equal to input,
hence YES.

Input : 235
Output : NO
Explanation: 2! + 3! + 5! = 
2 + 6 + 120 = 128, which is not equal to input, 
hence NO.


The idea is simple, we compute sum of factorials of all digits and then compare the sum with n. 

Interestingly, there are exactly four Krishnamurthy numbers i.e. 1, 2, 145, and 40585 known to us. 

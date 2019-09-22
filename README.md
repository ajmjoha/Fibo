# Fibo ## 
A Fibonacci sequence is the integer sequence of 0, 1, 1, 2, 3, 5, 8.... 
* In this program, we store the number of terms to be displayed in nterms . A recursive function recur_fibo() is used to calculate the nth term of the sequence. We use a for loop to iterate and calculate each term recursively.

* The first two terms are 0 and 1. All other terms are obtained by adding the preceding two terms.This means to say the nth term is the sum of (n-1)th and (n-2)th term.

**To Know more about Python Recursion** [Recursion](https://realpython.com/python-thinking-recursively/)
**Process Are ** 

    *1st Fibonacci number = 0 (by assumption)
    *2nd Fibonacci number = 1 (by assumption)
    *3rd Fibonacci number = 1st + 2nd
        = 0 + 1
        = 1
    4th Fibonacci number = 2nd + 3rd
    = 1 + 1
    = 2
    5th Fibonacci number = 3rd + 4th
    = 1 + 2
    = 3
    6th Fibonacci number = 4th + 5th
    = 2 + 3
    = 5
    So, nth Fibonacci number = (n-1)th Fibonacci + (n-2)th Fibonacci

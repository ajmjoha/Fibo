# Fibo ## 
A Fibonacci sequence is the integer sequence of 0, 1, 1, 2, 3, 5, 8.... 
* In this program, we store the number of terms to be displayed in nterms . A recursive function recur_fibo() is used to calculate the nth term of the sequence. We use a for loop to iterate and calculate each term recursively.

* The first two terms are 0 and 1. All other terms are obtained by adding the preceding two terms.This means to say the nth term is the sum of (n-1)th and (n-2)th term.

**To Know more about Fibo** [Recursion](https://realpython.com/python-thinking-recursively/)
# Process are 
* 1st Fibonacci number = 0 (by assumption)
* 2nd Fibonacci number = 1 (by assumption)
* 3rd Fibonacci number = 1st + 2nd
        = 0 + 1
        = 1
* 4th Fibonacci number = 2nd + 3rd
    = 1 + 1
    = 2
   
* 5th Fibonacci number = 3rd + 4th
    = 1 + 2
    = 3
* 6th Fibonacci number = 4th + 5th
    = 2 + 3
    = 5
    
## So, nth Fibonacci number = (n-1)th Fibonacci + (n-2)th Fibonacci


# Advantages of Python Recursion

1. Reduces unnecessary calling of function, thus reduces length of program.
2. Very flexible in data structure like stacks, queues, linked list and quick sort.
3. Big and complex iterative solutions are easy and simple with Python recursion.
4. Algorithms can be defined recursively making it much easier to visualize and prove.

# Disadvantages of Python Recursion

1. Slow.
2. Logical but difficult to trace and debug.
3. Requires extra storage space. For every recursive calls separate memory is allocated for the variables.
4. Recursive functions often throw a Stack Overflow Exception when processing or operations are too large.

# Image 
![Image] (https://www.google.com/search?client=firefox-b-d&biw=1280&bih=949&tbm=isch&sxsrf=ACYBGNTdX7s-elU_qFw4pXIr1W_L8UuxEA%3A1569190159764&sa=1&ei=D_GHXdulLsHe9QOvgq-wBw&q=python+fibo+&oq=python+fibo+&gs_l=img.3..35i39j0i24.4172.4172..4384...0.0..0.117.117.0j1......0....1..gws-wiz-img.b_wlxUUsDc8&ved=0ahUKEwib6brwuOXkAhVBb30KHS_BC3YQ4dUDCAY&uact=5#imgrc=JNq_TGRv3gog8M:)

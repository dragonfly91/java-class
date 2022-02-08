# Iterations

Calculate how many times will `foo()` be executed:

```Java
for (int i = 0; i < 10; i++) {
  foo();
}
```

```Java
int j;
for (j = 0; j < 7; j++) {
  foo();
}
```

```Java
for (int i = 0; i < 10; i = i + 2) {
  foo();
}
```

```Java
for (int i = 10; i > 1; i = i - 2) {
  foo();
}
```

```Java
for (int i = 0, j = 10; i < 10 && j > 5; i++, j--) {
  foo();
}
```

```Java
for (int i = 0; i < 10;) {
  foo();
}
```

```Java
for (int i = 4; i < 20; i = 2 * i + 3) {
  foo();
}
```

```Java
for (int i = 0; i < 10; i++) {
  for (int j = 0; j < 10; j++) {
    foo();
  }
}
```

# Count

For each of the loops in the [Iterations](#iterations) question, print the number of iterations via code.

Expected Output:

```bash
Count: 10
Count: 7
...
etc.
```

# Sum 1 to N

Given an input n, write a Java program to calculate the sum of integers 1, 2, 3, ... n.

Expected Input:

```bash
Input Number: 10
```

Expected Output:

```bash
Sum of numbers 1 to 10 = 55
```

_Themes: loop_

# Sum Odd

Given an input n, where n is an odd number, write a program to calculate the sum of odd integers up to n: 1, 3, 5, ... n.

Expected Input:

```bash
Input Number: 11
```

Expected Output:

```bash
Sum of odd numbers from 1 to 11 is 36
```

# Sum Even

Given an input n, where n is an even number, write a program to calculate the sum of odd integers up to n: 2, 4, 6, ... n.

Expected Input:

```bash
Input Number: 10
```

Expected Output:

```bash
Sum of even numbers from 2 to 10 is 30
```

# Sum Squares

Given an input n, write a program to calculate the sum of squares of integers up to n: 1<sup>2</sup> + 2<sup>2</sup> + 3<sup>2</sup> + ... + n<sup>2</sup>.

Expected Input:

```bash
Input Number: 10
```

Expected Output:

```bash
Sum of squares of numbers from 1 to 10 is 385
```

# Product 1 to N

Write a program called Product1ToN to compute the product of integers from 1 to 10 (i.e., 1x2x3x...x10), as an integer. Take note that it is the same as factorial of N.

Expected Input:

```bash
Input N: 10
```

Expected Output:

```bash
3628800
```

# Fibonacci

Write a Java program to accept a number n and print all the Fibonacci numbers in the increasing order less than n (inclusive).

Expected Input:

```bash
Enter a number n: 20
```

Expected Output:

```bash
1, 1, 2, 3, 5, 8, 13
```

# Sum and Average

Write a program in Java to input 5 numbers from keyboard and find their sum and average.

Expected Input:

```bash
Input the 5 numbers:                                                            
1                                                                                
2                                                                                
3                                                                                
4                                                                                
5                                                                                
```

Expected Output:

```bash
The sum of 5 no is : 15                                                          
The Average is : 3.0
```

# Maximum

Write a program in Java to input 2 numbers from keyboard and print the maximum.

Expected Input:

```bash
Input the two numbers:
3
6
```

Expected Output:

```bash
Maximum: 6
```

Now modify the program to make it work for 3 numbers

Expected Input:

```bash
Input the three numbers:
3
10
6
```

Expected Output:

```bash
Maximum: 10
```

Now modify the program to make it work for n numbers, where n is also an input

Expected Input:

```bash
Input n: 4
Input the 4 numbers:
4
5
2
6
```

Expected Output:

```bash
Maximum: 6
```

Now modify the program to make it print the minimum as well.

Expected Input:

```bash
Input n: 4
Input the 4 numbers:
4
5
2
6
```

Expected Output:

```bash
Maximum: 6
Minimum: 2
```

# Harmonic Sum

Write a program called HarmonicSum to compute the sum of a harmonic series to 3rd decimal precision, as shown below.

```
Harmonic(n) = 1 + 1/2 + 1/3 + ... + 1/n
```

where n = 50000

Expected Input:

```
Enter the value of n: 50000
```

Expected Output:

```
Harmonic(50000): 11.397
```

# Compute PI

Write a program to compute the value of pi to 3rd digit precision, using the following series expansion. Use the maximum denominator (maxDenominator) as the terminating condition. Try maxDenominator of 100001.

```
pi = 4 * (1 - 1/3 + 1/5 - 1/7 + 1/9 - 1/11 + 1/13 - 1/15 + ... + 1/maxDenominator)
```

Expected Input:

```
Enter the value of maxDenominator: 100001
```

Expected Output:

```
Value of pi: 3.141
```

# Patterns

Write a program that prompts user for size (a non-negative integer in int); and prints the following patterns using two nested for-loops.

Expected Input:

```
Enter the size: 5
```

Expected Output:

```
# # # # #
# # # # #
# # # # #
# # # # #
# # # # # 
Square Pattern

# # # # # 
 # # # # #
# # # # # 
 # # # # #
# # # # # 
Checker Pattern

#
# #
# # #
# # # #
# # # # #
---------
# # # # #
# # # #
# # #
# #
#
---------
# # # # #
  # # # #
    # # #
      # #
        #
---------
        #
      # #
    # # #
  # # # #
# # # # #
Triangular Patterns

# # # # #
#       #
#       #
#       #
# # # # #
---------
# # # # #
  #
    #
      #
# # # # #
---------
# # # # #
      #
    #
  #
# # # # #
---------
# # # # #
  #   #
    #
  #   #
# # # # #
---------
# # # # #
# #   # #
#   #   #
# #   # #
# # # # #
Box Patterns

        #
      # # #
    # # # # #
  # # # # # # #
# # # # # # # # #
-----------------
# # # # # # # # #
  # # # # # # #
    # # # # #
      # # #
        #
-----------------
        #
      # # #
    # # # # #
  # # # # # # #
# # # # # # # # #
  # # # # # # #
    # # # # #
      # # #
        #
-----------------
# # # # # # # # #
# # # #   # # # #
# # #       # # #
# #           # #
#               #
# #           # #
# # #       # # #
# # # #   # # # #
# # # # # # # # #
Hill Patterns

1
1 2
1 2 3
1 2 3 4
1 2 3 4 5
---------
1 2 3 4 5
  1 2 3 4
    1 2 3
      1 2
        1
---------
        1
      2 1
    3 2 1
  4 3 2 1
5 4 3 2 1
---------
5 4 3 2 1
4 3 2 1
3 2 1
2 1
1
Number Patterns
```

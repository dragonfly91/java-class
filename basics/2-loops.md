# Iterations（繰り返し文）

Calculate how many times will `foo()` be executed:

何回　foo()が実行されるかを数えましょう。

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

# Count（）

For each of the loops in the [Iterations](#iterations) question, print the number of iterations via code.

繰り返し文の問題の各ループについて、コードで反復回数をプリントしてください。

Expected Output:

できるもの：

```bash
Count: 10
Count: 7
...
etc.
```

# Sum 1 to N（１からN番目の数の合計は）

Given an input n, write a Java program to calculate the sum of integers 1, 2, 3, ... n.

nの数が与えられたとき、1, 2, 3, ... nの整数の合計を計算するJavaのプログラムを書きましょう。

Expected Input:

できるもの：

```bash
Input Number: 10
```

Expected Output:

できるもの：

```bash
Sum of numbers 1 to 10 = 55
```

_Themes: loop_

# Sum Odd（奇数の合計）

Given an input n, where n is an odd number, write a program to calculate the sum of odd integers up to n: 1, 3, 5, ... n.

奇数であるnの数字が与えられたとき、1, 3, 5, ... nまでの奇数の合計を計算するプログラムを書きましょう。

Expected Input:

できるもの：

```bash
Input Number: 11
```

Expected Output:

```bash
Sum of odd numbers from 1 to 11 is 36
```

# Sum Even（偶数の合計）

Given an input n, where n is an even number, write a program to calculate the sum of odd integers up to n: 2, 4, 6, ... n.

偶数であるnの数字が与えられたとき、2, 4, 6, ... nまでの偶数の合計を計算するプログラムを書きましょう。


Expected Input:

できるもの：

```bash
Input Number: 10
```

Expected Output:

```bash
Sum of even numbers from 2 to 10 is 30
```

# Sum Squares（2乗の合計）

Given an input n, write a program to calculate the sum of squares of integers up to n: 1<sup>2</sup> + 2<sup>2</sup> + 3<sup>2</sup> + ... + n<sup>2</sup>.

nの数が与えられたとき、1^1+2^2+3^3+... + n^nの合計を計算するプログラムを書きましょう。

Expected Input:

```bash
Input Number: 10
```

Expected Output:

```bash
Sum of squares of numbers from 1 to 10 is 385
```

# Product 1 to N（1からNまでのかけ算の合計）

Write a program called Product1ToN to compute the product of integers from 1 to 10 (i.e., 1x2x3x...x10), as an integer. Take note that it is the same as factorial of N.

Expected Input:

1から10までの整数の積（すなわち1x2x3x...x10）を整数で計算するProduct1ToNというプログラムを作成しましょう。Nの階乗と同じであることに注意しましょう。

```bash
Input N: 10
```

Expected Output:

できるもの：

```bash
3628800
```

# Fibonacci（フィボナッチ数列）

Write a Java program to accept a number n and print all the Fibonacci numbers in the increasing order less than n (inclusive).

数nを受け取り、nより小さい（含む）昇順のフィボナッチ数をすべて表示するJavaプログラムを作成しましょう。

Expected Input:

できるもの：

```bash
Enter a number n: 20
```

Expected Output:

できるもの：

```bash
1, 1, 2, 3, 5, 8, 13
```

# Sum and Average（合計と平均値）

Write a program in Java to input 5 numbers from keyboard and find their sum and average.

5つの数字を入れ、それらの合計と平均値を出すJavaのプログラムを作りましょう。

Expected Input:

できるもの：

```bash
Input the 5 numbers:                                                            
1                                                                                
2                                                                                
3                                                                                
4                                                                                
5                                                                                
```

Expected Output:

できるもの：

```bash
The sum of 5 no is : 15                                                          
The Average is : 3.0
```

# Maximum（最大値）

Write a program in Java to input 2 numbers from keyboard and print the maximum.

2つの数字を入れ、最大値をプリントするJavaのプログラムを書きましょう。

Expected Input:

```bash
Input the two numbers:
3
6
```

Expected Output:

できるもの：

```bash
Maximum: 6
```

Now modify the program to make it work for 3 numbers

Expected Input:

できるもの：

```bash
Input the three numbers:
3
10
6
```

Expected Output:

できるもの：

```bash
Maximum: 10
```

Now modify the program to make it work for n numbers, where n is also an input

Expected Input:

できるもの：

```bash
Input n: 4
Input the 4 numbers:
4
5
2
6
```

Expected Output:

できるもの：

```bash
Maximum: 6
```

Now modify the program to make it print the minimum as well.

Expected Input:

できるもの：

```bash
Input n: 4
Input the 4 numbers:
4
5
2
6
```

Expected Output:

できるもの：

```bash
Maximum: 6
Minimum: 2
```

# Harmonic Sum（ハーモニックサム？）

Write a program called HarmonicSum to compute the sum of a harmonic series to 3rd decimal precision, as shown below.

以下のように、調和級数の和を小数点以下3桁の精度で計算するプログラムをHarmonicSumと名付けよ。

```
Harmonic(n) = 1 + 1/2 + 1/3 + ... + 1/n
```

where n = 50000

Expected Input:

できるもの：

```
Enter the value of n: 50000
```

Expected Output:

できるもの：

```
Harmonic(50000): 11.397
```

# Compute PI（円周率の計算）

Write a program to compute the value of pi to 3rd digit precision, using the following series expansion. Use the maximum denominator (maxDenominator) as the terminating condition. Try maxDenominator of 100001.

以下の級数展開により、円周率の値を3桁の精度で計算するプログラムを作成しなさい。最大分母(maxDenominator)を終端条件として使用する。maxDenominator を 100001 にしてみてください。

```
pi = 4 * (1 - 1/3 + 1/5 - 1/7 + 1/9 - 1/11 + 1/13 - 1/15 + ... + 1/maxDenominator)
```

Expected Input:

できるもの：

```
Enter the value of maxDenominator: 100001
```

Expected Output:

できるもの：

```
Value of pi: 3.141
```

# Patterns（模様）

Write a program that prompts user for size (a non-negative integer in int); and prints the following patterns using two nested for-loops.

2つの繰り返し文（for loopを使って）以下の模様をかき、ユーザーにサイズ（int型の非負整数）の入力を促すプログラムを作成しましょう。

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

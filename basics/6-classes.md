# Array Class

Create a class Array which:
1. Consumes the size in the constructor and prefills it with random numbers from 0 to 100. The size needs to obtained from the user.
2. Implements `Array.print()` method, which prints the contents of the array in a single line, separated by `,`.

Expected Input:

```
Input a value for array size: 5
```

Expected Ouptut:

```
Array: 3, 66, 90, 4, 12
```

3. Implements `Array.getSum()`, which returns the sum of values in the array.
4. Implements `Array.getAverage()`, which returns the average of the values in the array.
5. Implements `Array.getProduct()`, which returns the product of the values in the array.
6. Implements `Array.getMinimum()` and `Array.getMaximum()`, which return the minimum and maximum values in the array respectively.

Expected Ouptut:

```
Sum: 175
Average: 35
Product: 855360
Maximum: 90
Minimum: 3
```

7. Implements `Array.find(int key)`, which checks if `key` is present in the array and returns its index and `-1` otherwise.

Expected Input:

```
Input a value for key: 3
```

Expected Ouptut:

```
3 is present in the array at index 0
```

Expected Input:

```
Input a value for key: 5
```

Expected Ouptut:

```
5 is not present in the array
```

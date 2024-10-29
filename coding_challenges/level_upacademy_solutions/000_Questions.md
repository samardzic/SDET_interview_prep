
### 01_swap_numbers
```
Write a program to swap 2 numbers without using the 3rd (temporary) variable?
```
<br/>


### 02_sum_of_two

```
Sum of two. Write a method that accepts an int[] array and an int number, and find 2 elements in the array that
sum is equal to the given int. Assume that an input array will have only one pair of numbers that sum equal
to our given number. It will always have this pair. See input and output examples. I use the Brute Force algorithm.

Method 1: Brute Force
The brute force method involves checking all possible pairs in the array to find the pair that sums up to the target number.
Time Complexity: O(n^2), where n is the number of elements in the array. This is because it involves a nested loop to compare each element with every other element.

Method 2: Sorting and Two-Pointers
First, sort the array, then use two pointers to find the two numbers. One pointer starts at the beginning of the array, and the other starts at the end. Move the pointers towards each other based on the sum of their corresponding elements compared to the target sum.
Time Complexity: O(n log n) due to the sorting step. The two-pointer approach itself is O(n), making this more efficient than the brute force approach for large arrays.
```

### 03_sort_array

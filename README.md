# DualpivotQuicksort

## Overview
This project implements the **Dual-Pivot QuickSort** algorithm in Java. Dual-Pivot QuickSort is a variant of the classic QuickSort algorithm that uses two pivots instead of one to enhance performance in some cases.

## Features
- Implements the **Dual-Pivot QuickSort** sorting technique.
- Uses **LinkedList** to store and sort integer values.
- Recursively sorts the list by partitioning it into three sections:
  - Elements less than the first pivot.
  - Elements between the two pivots.
  - Elements greater than the second pivot.
- Includes a function to check if a list is empty.

## Usage
### Compilation & Execution
1. Compile the Java program:
   ```sh
   javac DualPivotQuicksort.java
   ```
2. Run the program:
   ```sh
   java DualPivotQuicksort
   ```

### Sample Input/Output
#### Input:
The program sorts the following list:
```
[24, 3, 45, 29, 15, 10, 5, 1, 8, 7, 6, 2, 4, 9]
```
#### Output:
```
Original list: [24, 3, 45, 29, 15, 10, 5, 1, 8, 7, 6, 2, 4, 9]
Sorted list: [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 15, 24, 29, 45]
```

## Code Explanation
The program follows these steps:
1. Selects two pivots (first and last elements of the list).
2. Partitions the list into three sublists based on the pivots.
3. Recursively sorts the partitions.
4. Merges the sorted partitions back together.



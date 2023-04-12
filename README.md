# Prakarsh Mathur

# 202001012

# Section A

<h2>P1:</h2>

| Tester Action and Input Data      | Expected Outcome |
|-----------------------------------|------------------|
|                                   |                  |
| Equivalence Partitioning          |                  |
| When value is found:              |                  |
| [1, 2, 3, 4, 5], 3                | 2                |
| When value is not found:          |                  |
| [2, 4, 6, 8], 5                   | -1               |
| When a variable is non-integer:   |                  |
| [a, 3, 5, 7], 4                   | Invalid          |
| When an integer is not in range:  |                  |
| [1, 3, 5, INT_MAX+2], 7           | Invalid          |
| [1, 3, 5, 7], INT_MAX+12          | Invalid          |
| [INT_MIN-21, 1, 3, 5], 7          | Invalid          |
| [1, 3, 5, 7], INT_MIN-12          | Invalid          |
| When array is empty:              |                  |
| [], 5                             | -1               |
|                                   |                  |
| Boundary Value Analysis:          |                  |
| When value is found:              |                  |
| [5, 10, 15, 20, 25], 5            | 0                |
| [5, 10, 15, 20, 25], 25           | 4                |
| When array is empty:              |                  |
| [], 5                             | -1               |
| When value is not found:          |                  |
| [3, 7, 9, 11], 10                 | -1               |
| When an integer is not in range:  |                  |
| [1, 3, 5, INT_MAX+1], 7           | Invalid          |
| [1, 3, 5, 7], INT_MAX+1           | Invalid          |
| [INT_MIN-1, 1, 3, 5], 7           | Invalid          |
| [1, 3, 5, 7], INT_MIN-1           | Invalid          |

<h2>P2:</h2>

| Tester Action and Input Data        | Expected Outcome |
|-------------------------------------|------------------|
|                                     |                  |
| Equivalence Partitioning            |                  |
| When integer is found:              |                  |
| [5, 5, 6, 7, 8, 5], 5               | 3                |
| When integer is not found:          |                  |
| [2, 4, 6, 8], 5                     | 0                |
| When a variable is non-integer:     |                  |
| [a, 3, 5, 7], 4                     | Invalid          |
| When an integer is not in range:    |                  |
| [1, 3, 5, INT_MAX+1], 7             | Invalid          |
| [1, 3, 5, 7], INT_MAX+1             | Invalid          |
| [INT_MIN-1, 1, 3, 5], 7             | Invalid          |
| [1, 3, 5, 7], INT_MIN-1             | Invalid          |
| When array is empty:                |                  |
| [], 5                               | -1               |
|                                     |                  |
| Boundary Value Analysis:            |                  |
| When array is empty:                |                  |
| [], 5                               | -1               |
| When value is found once:           |                  |
| [5, 10, 15, 20, 25], 5              | 1                |
| When value is found multiple times: |                  |
| [5, 10, 15, 20, 25], 5              | 1                |
| [5], 5                              | 1                |
| When integer is not found:          |                  |
| [12, 24, 36, 48], 5                 | 0                |

<h2>P3:</h2>

| Tester Action and Input Data        | Expected Outcome |
|-------------------------------------|------------------|
|                                     |                  |
| Equivalence Partitioning            |                  |
| When value is found:                |                  |
| [1, 2, 3, 4, 5], 3                  | 2                |
| When value is not found:            |                  |
| [2, 4, 6, 8], 5                     | -1               |
| When a variable is non-integer:     |                  |
| [a, 3, 5, 7], 4                     | Invalid          |
| When an integer is not in range:    |                  |
| [1, 3, 5, INT_MAX+2], 7             | Invalid          |
| [1, 3, 5, 7], INT_MAX+12            | Invalid          |
| [INT_MIN-21, 1, 3, 5], 7            | Invalid          |
| [1, 3, 5, 7], INT_MIN-12            | Invalid          |
| When array is empty:                |                  |
| [], 5                               | -1               |
|                                     |                  |
| Boundary Value Analysis:            |                  |
| When value is found:                |                  |
| [5, 10, 15, 20, 25], 5              | 0                |
| [5, 10, 15, 20, 25], 25             | 4                |
| When array is empty:                |                  |
| [], 5                               | -1               |
| When value is not found:            |                  |
| [3, 7, 9, 11], 10                   | -1               |
| When an integer is not in range:    |                  |
| [1, 3, 5, INT_MAX+1], 7             | Invalid          |
| [1, 3, 5, 7], INT_MAX+1             | Invalid          |
| [INT_MIN-1, 1, 3, 5], 7             | Invalid          |
| [1, 3, 5, 7], INT_MIN-1             | Invalid          |
| When (length of array)>(INTMAX/2):  |                  |
| [1, 3, 5,...], 6                    | Invalid          |

<h2>P4:</h2>

| Tester Action and Input Data |     |    | Expected Outcome |
|------------------------------|-----|----|------------------|
| Equivalence Partitioning:    |     |    |                  |
| A                            | B   | C  |                  |
| 1                            | 2   | 3  | Invalid          |
| 3                            | 3   | 3  | Equilateral      |
| 6                            | 6   | 4  | Isosceles        |
| 2                            | 3   | 4  | Scalene          |
|                              |     |    |                  |
| Boundary Value Analysis:     |     |    |                  |
| A                            | B   | C  |                  |
| 1                            | 2   | 3  | Invalid          |
| 1                            | 3   | 2  | Invalid          |
| 3                            | 1   | 2  | Invalid          |
| 5                            | 5   | 5  | Equilateral      |
| 8.5                          | 8.5 | 7  | Isosceles        |
| 6                            | 4   | 6  | Isosceles        |
| 3                            | 5   | 5  | Isosceles        |
| 15                           | 32  | 34 | Scalene          |

<h2>P5:</h2>

| Tester Action and Input Data |          | Expected Outcome |
|------------------------------|----------|------------------|
| Equivalence Partitioning:    |          |                  |
| s1                           | s2       |                  |
| ""                           | ""       | True             |
| ""                           | "hello"  | True             |
| "Mo"                         | "Motion" | True             |
| "gs"                         | "Songs"  | False            |
| "abababa"                    | "ab"     | False            |

|                              |          |                  |
| Boundary Value Analysis:     |          |                  |
| s1                           | s2       |                  |
| ""                           | ""       | True             |
| ""                           | "music"  | True             |
| "ft"                         | "Lift"   | False            |
| "cdcdcdc"                    | "cd"     | False            |


# Section B

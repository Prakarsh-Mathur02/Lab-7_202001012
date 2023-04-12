# Prakarsh Mathur

# 202001012

# Section A

<h2>P1:</h2>

| Tester Action and Input Data      | Expected Outcome |
|-----------------------------------|------------------|
|                                   |                  |
| Equivalence Partitioning          |                  |
| When value is found(Valid):       |                  |
| [1, 2, 3, 4, 5], 3                | 2                |
| [5, 10, 15, 20, 25], 5            | 0                |
| When value is not found(Invalid): |                  |
| [2, 4, 6, 8], 5                   | -1               |
| [1, 3, 5, 7], 4                   | -1               |
| [a, 3, 5, 7], 4                   | Invalid          |
| [1, 3, 5, INT_MAX+1], 7           | Invalid          |
| [1, 3, 5, INT_MAX+1], 7           | Invalid          |
| [INT_MIN-1, 1, 3, 5], 7           | Invalid          |
| [INT_MIN-1, 1, 3, 5], 7           | Invalid          |
|                                   |                  |
| Boundary Value Analysis:          |                  |
| [5, 10, 15, 20, 25], 5            | 0                |
| [5, 10, 15, 20, 25], 25           | 4                |

<h2>P2:</h2>

| Tester Action and Input Data        | Expected Outcome |
|-------------------------------------|------------------|
|                                     |                  |
| Equivalence Partitioning            |                  |
| When integer is found(Valid):       |                  |
| [1, 2, 3, 2, 4, 5], 2               | 2                |
| [5, 5, 6, 7, 8, 5], 5               | 3                |
| When integer is not found(Invalid): |                  |
| [2, 4, 6, 8], 5                     | 0                |
| [1, 3, 5, 7], 4                     | 0                |
| [a, 3, 5, 7], 4                     | Invalid          |
| [1, 3, 5, INT_MAX+1], 7             | Invalid          |
| [1, 3, 5, INT_MAX+1], 7             | Invalid          |
| [INT_MIN-1, 1, 3, 5], 7             | Invalid          |
| [INT_MIN-1, 1, 3, 5], 7             | Invalid          |
|                                     |                  |
| Boundary Value Analysis:            |                  |
| [5, 10, 15, 20, 25], 5              | 1                |
| [5], 5                              | 1                |

<h2>P3:</h2>

| Tester Action and Input Data        | Expected Outcome |
|-------------------------------------|------------------|
|                                     |                  |
| Equivalence Partitioning            |                  |
| When integer is found(Valid):       |                  |
| [1, 2, 3, 4, 5], 3                  | 2                |
| [5, 10, 15, 20, 25], 5              | 0                |
| When integer is not found(Invalid): |                  |
| [2, 4, 6, 8], 5                     | -1               |
| [1, 3, 5, 7], 4                     | -1               |
| [a, 3, 5, 7], 4                     | Invalid          |
| [1, 3, 5, INT_MAX+1], 7             | Invalid          |
| [1, 3, 5, INT_MAX+1], 7             | Invalid          |
| [INT_MIN-1, 1, 3, 5], 7             | Invalid          |
| [INT_MIN-1, 1, 3, 5], 7             | Invalid          |
|                                     |                  |
| Boundary Value Analysis:            |                  |
| [5, 10, 15, 20, 25], 5              | 0                |
| [5], 5                              | 0                |



# Section B

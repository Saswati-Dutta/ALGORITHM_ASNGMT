
### Algorithm Steps

1.  **Start** program execution.
2.  **Declare** variables: $n$ (int) and $fact$ (unsigned long long, initialized to 1), and $i$ (loop counter, int).
3.  **Input**: Read and store the number $n$.
4.  **Conditional Check**: Is $n < 0$?
    a.  **If Yes**: Output an "Error: Factorial of negative number does not exist." Go to Step 8.
    b.  **If No**: Proceed to Step 5.
5.  **Initialize**: Set loop counter $i = 1$.
6.  **Loop Condition Check**: Is $i \le n$?
    a.  **If Yes**:
        i.  **Process**: Update the factorial: $fact = fact \times i$.
        ii. **Increment**: $i = i + 1$.
        iii. Return to Step 6 (Loop Condition Check).
    b.  **If No**: Proceed to Step 7.
7.  **Output**: Display the final calculated $fact$.
8.  **End** the program.

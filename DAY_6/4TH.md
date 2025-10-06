

### Algorithm Steps

1.  **Start** program execution.
2.  **Declare** variables: $n$ (input limit), $first$ (initialized to 0), $second$ (initialized to 1), and $next$ (all integers).
3.  **Input**: Read and store the number of terms $n$.
4.  **Initialize**: Set loop counter $i = 1$.
5.  **Loop Condition Check**: Is $i \le n$?
    a.  **If Yes**:
        i.  **Output**: Print the current value of $first$.
        ii. **Process (Update)**: Calculate $next = first + second$.
        iii. **Reassign**: Shift the sequence forward: $first = second$ and $second = next$.
        iv. **Increment**: $i = i + 1$.
        v. Return to Step 5 (Loop Condition Check).
    b.  **If No**: Proceed to Step 6.
6.  **End** the program.

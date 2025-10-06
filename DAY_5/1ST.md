

### Algorithm Steps

1.  **Start** program execution.
2.  **Declare** variables: $num1, num2, result$ (double) and $op$ (char).
3.  **Input 1**: Read and store the first number, $num1$.
4.  **Input 2**: Read and store the operator, $op$.
5.  **Input 3**: Read and store the second number, $num2$.
6.  **Switch Decision (op)**: Evaluate the operator $op$.
    a.  **Case '+'**: Calculate $result = num1 + num2$. Output $result$. Go to Step 7.
    b.  **Case '-'**: Calculate $result = num1 - num2$. Output $result$. Go to Step 7.
    c.  **Case '\*'**: Calculate $result = num1 \times num2$. Output $result$. Go to Step 7.
    d.  **Case '/'**: Check if $num2$ is NOT equal to 0.
        i.  **If Yes ($num2 \neq 0$):** Calculate $result = num1 / num2$. Output $result$. Go to Step 7.
        ii. **If No ($num2 = 0$):** Output "Error! Division by zero". Go to Step 7.
    e.  **Default**: Output "Invalid operator!". Go to Step 7.
7.  **End** the program.

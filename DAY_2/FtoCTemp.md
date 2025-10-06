### Algorithm Steps

1.  **Start** program execution.
2.  **Declare** floating-point variables: $celsius$, $fahrenheit$, and integer variable $choice$.
3.  **Display** the conversion menu and prompt for input.
4.  **Input** (Read) the integer $choice$ from the user.
5.  **Decision**: Check if $choice$ is $1$.
    a.  **IF (YES, choice = 1)**:
        i.   Input $celsius$ value.
        ii.  **Calculate**: $fahrenheit = (celsius \times 9/5) + 32$.
        iii. Display the result in Fahrenheit.
    b.  **ELSE IF (choice = 2)**:
        i.   Input $fahrenheit$ value.
        ii.  **Calculate**: $celsius = (fahrenheit - 32) \times 5/9$.
        iii. Display the result in Celsius.
    c.  **ELSE (Invalid Choice)**:
        i.   Display "Invalid choice!".
6.  **Return** the integer value $0$, and **End** the program.

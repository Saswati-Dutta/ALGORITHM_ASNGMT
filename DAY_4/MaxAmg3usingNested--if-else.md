
### Algorithm Steps

1.  **Start** program execution.
2.  **Declare** three integer variables: $a$, $b$, and $c$.
3.  **Input**: Read and store the values for $a$, $b$, and $c$ from the user.
4.  **Decision 1**: Check if $a > b$.
    a.  **IF Yes** ($a$ is potentially the maximum):
        i.  **Nested Decision**: Check if $a > c$.
            1.  **IF Yes**: Output "$a$ is the maximum".
            2.  **IF No**: Output "$c$ is the maximum".
    b.  **IF No** ($b \ge a$; $b$ is potentially the maximum):
        i.  **Nested Decision**: Check if $b > c$.
            1.  **IF Yes**: Output "$b$ is the maximum".
            2.  **IF No**: Output "$c$ is the maximum".
5.  **End** the program.

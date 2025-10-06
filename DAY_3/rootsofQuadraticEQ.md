### Algorithm Steps

1.  **Start** program execution.
2.  **Include** the necessary math library (`math.h`).
3.  **Declare** double variables: $a$, $b$, $c$ (coefficients), $D$ (discriminant), $root1$, $root2$, $real$, $imag$.
4.  **Input**: Read and store coefficients $a$, $b$, and $c$ from the user.
5.  **Process**: Calculate the Discriminant: $D = b^2 - 4ac$.
6.  **Decision 1**: Check if $D > 0$.
    a.  **IF (D > 0)** (Roots are Real and Distinct):
        * Process: $root1 = (-b + \sqrt{D}) / (2a)$ and $root2 = (-b - \sqrt{D}) / (2a)$.
        * Output: Display $root1$ and $root2$ as real and different.
    b.  **ELSE**: Proceed to Decision 2.
7.  **Decision 2**: Check if $D = 0$.
    a.  **IF (D = 0)** (Roots are Real and Equal):
        * Process: $root1 = root2 = -b / (2a)$.
        * Output: Display $root1$ and $root2$ as real and equal.
    b.  **ELSE (D < 0)** (Roots are Complex):
        * Process: Calculate the real part $real = -b / (2a)$ and the imaginary part $imag = \sqrt{-D} / (2a)$.
        * Output: Display the complex roots ($real \pm i \times imag$).
8.  **End** the program.

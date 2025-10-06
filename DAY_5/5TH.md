
### Algorithm Steps

1.  **Start** program execution.
2.  **Declare** variables: $marks, m$ (int) and $grade$ (char).
3.  **Input**: Read and store the student's $marks$ (integer).
4.  **Process**: Calculate the tens digit: $m = marks / 10$.
5.  **Switch Decision (m)**: Evaluate the value of $m$ (the tens digit).
    a.  **Case 10 or 9 (90-100)**:
        i. **If** $marks \ge 95$: Set a flag/value indicating 'A+'.
        ii. **Else**: Set $grade = 'A'$.
        iii. **Break** from the switch.
    b.  **Case 8 (80-89)**: Set $grade = 'B'$. **Break**.
    c.  **Case 7 (70-79)**: Set $grade = 'C'$. **Break**.
    d.  **Default (Below 70)**: Set $grade = 'F'$.
6.  **Output**: Display the calculated $grade$. Handle the special 'A+' case for printing.
7.  **End** the program.

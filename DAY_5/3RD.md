
### Algorithm Steps

1.  **Start** program execution.
2.  **Declare** variables: $basic, hra, ta, da, gross$ (float) and $choice$ (int).
3.  **Input 1**: Read and store the $basic$ salary.
4.  **Input 2**: Display menu options (1-4) and read the user's $choice$.
5.  **Switch Decision (choice)**: Evaluate the user's $choice$.
    a.  **Case 1 (HRA)**: Calculate $hra = 2.0 \times basic$. Output $hra$. Go to Step 6.
    b.  **Case 2 (TA)**: Calculate $ta = 0.10 \times basic$. Output $ta$. Go to Step 6.
    c.  **Case 3 (DA)**: Calculate $da = 0.05 \times basic$. Output $da$. Go to Step 6.
    d.  **Case 4 (Gross)**:
        i. Calculate $hra = 2.0 \times basic$.
        ii. Calculate $ta = 0.10 \times basic$.
        iii. Calculate $da = 0.05 \times basic$.
        iv. Calculate $gross = basic + hra + ta + da$.
        v. Output $gross$. Go to Step 6.
    e.  **Default**: Output "Invalid choice! Please enter 1–4".
6.  **End** the program.

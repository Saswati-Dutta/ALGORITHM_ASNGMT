
### Algorithm Steps

1.  **Start** program execution.
2.  **Declare** variables: $units$ (int), $bill$ (float, initialized to 0), and $choice$ (int).
3.  **Input 1**: Read and store the total $units$ consumed.
4.  **Input 2**: Display menu options (1-4) and read the user's $choice$.
5.  **Switch Decision (choice)**: Evaluate the user's $choice$.
    a.  **Case 1 (First 100)**: Calculate bill for the first 100 units at ₹5/unit. Output the result. Go to Step 6.
    b.  **Case 2 (Next 100)**: Calculate bill for units 101-200 at ₹7/unit. Output the result. Go to Step 6.
    c.  **Case 3 (Above 200)**: Calculate bill for units above 200 at ₹10/unit. Output the result. Go to Step 6.
    d.  **Case 4 (Total Bill)**:
        i. **If** $units \le 100$: $bill = units \times 5$.
        ii. **Else If** $units \le 200$: $bill = (100 \times 5) + ((units - 100) \times 7)$.
        iii. **Else** ($units > 200$): $bill = (100 \times 5) + (100 \times 7) + ((units - 200) \times 10)$.
        iv. Output the $Total Bill$. Go to Step 6.
    e.  **Default**: Output "Invalid choice! Please enter 1–4".
6.  **End** the program.

# Recurssion
### Recursion

**Objective:**  
To explore the concept of recursion.

**Overview:**  
**Definition:** Recursion in C++ is a programming technique in which a function calls itself to solve a problem. This method is particularly useful for problems that can be broken down into smaller, similar subproblems. A recursive function typically consists of two main components:
- **Base Case:** A condition that stops the function from calling itself, preventing infinite recursion.
- **Recursive Case:** The section of the function where it calls itself with modified arguments, gradually moving toward the base case.

**Algorithm: Addition of Integers**

1. **Start.**
2. **Function Definition:**
   - Define a function `sum(n)` that takes an integer `n`.
   - **Base Case:** If `n` equals 0, return 0.
   - **Recursive Case:** Otherwise, return `n + sum(n - 1)`.
3. **Main Function:**
   - Declare an integer variable `num`.
   - Display the prompt: "Enter a number: ".
   - Read the input value into `num`.
4. **Call the sum Function:**
   - Call `sum(num)` and store the result.
5. **Output the Result:**
   - Print "Sum of integers is: " followed by the result from step 4.
6. **End.**

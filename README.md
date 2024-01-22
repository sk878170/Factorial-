# Factorial-

**Factorial:**

**Definition:**
Factorial is a mathematical operation denoted by the symbol "!" that represents the product of all positive integers less than or equal to a given positive integer \(n\). It is often expressed as \(n!\), where \(n\) is a non-negative integer. Mathematically, \(n! = n \times (n-1) \times (n-2) \times \ldots \times 3 \times 2 \times 1\).




**Algorithm:**

1. The `factorial` function takes a non-negative integer `n` as input.
2. If `n` is 0 or 1, the function returns 1 because the factorial of 0 and 1 is 1.
3. If `n` is greater than 1, the function initializes a variable `result` to 1. It then uses a `for` loop to iterate from 2 to `n` (inclusive) and multiplies each number to the `result`.
4. The final result is the factorial of the input number.

**Uses of Factorial:**

1. **Combinatorics:**
   - Factorials are used in combinatorics to calculate permutations and combinations.
   - For example, the number of ways to arrange \(n\) distinct items is given by \(n!\).

2. **Probability:**
   - In probability theory, factorials are used to calculate the number of possible outcomes in a sample space.

3. **Series and Calculus:**
   - Factorials are used in the series expansion of functions such as the exponential function and binomial theorem.

4. **Recursive Definitions:**
   - Factorials often appear in recursive definitions of mathematical and computational concepts.

5. **Mathematical Identities:**
   - Factorials are involved in various mathematical identities and formulas.

In summary, the factorial of a number is a crucial mathematical operation with applications in combinatorics, probability, series expansion, and various mathematical concepts. In programming, calculating factorials is a common task and is often implemented using loops or recursion.

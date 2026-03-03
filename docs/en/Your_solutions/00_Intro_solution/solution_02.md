# Problem 2: Solving a System of Linear Equations

## Problem Statement

Solve the following system of linear equations:

$$
\begin{aligned}
2x + 3y &= 12 \\
x - y &= 1
\end{aligned}
$$

---

## Method 1: Substitution Method

### Step 1: Isolate a variable from one equation

From the second equation, we isolate $x$:

$$
x - y = 1
$$

$$
x = 1 + y
$$

**Explanation:** We rearrange the equation to express $x$ in terms of $y$.

### Step 2: Substitute into the first equation

Substitute $x = 1 + y$ into the first equation:

$$
2(1+y) + 3y = 12
$$

### Step 3: Expand and simplify

Distribute the 2:

$$
2 + 2y + 3y = 12
$$

Combine like terms:

$$
2 + 5y = 12
$$

### Step 4: Solve for $y$

Subtract 2 from both sides:

$$
5y = 10
$$

$$
y = 2
$$

### Step 5: Back-substitute to find $x$

Now substitute $y = 2$ back into $x = 1 + y$:

$$
x = 1 + 2 = 3
$$

### Step 6: Verification

Check the solution in both original equations:
- First equation: $2(3) + 3(2) = 6 + 6 = 12$ ✓
- Second equation: $3 - 2 = 1$ ✓

**Answer (Method 1):**

$$
\boxed{x = 3, \quad y = 2}
$$

---

## Method 2: Matrix Formalism (Gaussian Elimination)

We can represent the system in matrix form as $A\mathbf{x} = \mathbf{b}$, where:

$$
A = \begin{pmatrix} 2 & 3 \\ 1 & -1 \end{pmatrix}, \quad \mathbf{x} = \begin{pmatrix} x \\ y \end{pmatrix}, \quad \mathbf{b} = \begin{pmatrix} 12 \\ 1 \end{pmatrix}
$$

### Step 1: Form the augmented matrix

Create the augmented matrix $[A|\mathbf{b}]$:

$$
\left[\begin{array}{cc|c} 2 & 3 & 12 \\ 1 & -1 & 1 \end{array}\right]
$$

### Step 2: Gaussian Elimination - Forward elimination

**Operation 1:** Swap rows (Row 1 ↔ Row 2) to get a smaller leading coefficient:

$$
\left[\begin{array}{cc|c} 1 & -1 & 1 \\ 2 & 3 & 12 \end{array}\right]
$$

**Operation 2:** Eliminate below the pivot (Row 2 - 2·Row 1 → Row 2):

$$
\left[\begin{array}{cc|c} 1 & -1 & 1 \\ 0 & 5 & 10 \end{array}\right]
$$

**Explanation:** We subtracted 2 times the first row from the second row to eliminate the first element in the second row.

### Step 3: Back-substitution

From the second row: $5y = 10 \implies y = 2$

From the first row: $x - y = 1 \implies x = 1 + y = 1 + 2 = 3$

**Answer (Method 2):**

$$
\boxed{x = 3, \quad y = 2}
$$

---

## Summary

Both methods yield the same solution:

$$
\boxed{\begin{pmatrix} x \\ y \end{pmatrix} = \begin{pmatrix} 3 \\ 2 \end{pmatrix}}
$$

- **Substitution method:** Best for smaller or simple systems
- **Matrix method:** More systematic and scalable to larger systems

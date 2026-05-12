# 4. Step-by-Step Reduction of a Complex Mixed Circuit

**Problem Objective:** Determine the total equivalent resistance ($R_{eq}$) of the resistive network where every individual resistor has a fixed value of $R = 10 \, \Omega$.

### **I. Initial Circuit Decomposition**
To solve complex networks, we apply the **Method of Successive Reduction**, starting from the branch furthest from the source and moving inward.

### **II. Step 1: Solving the Parallel Sub-Branch**
At the center of the lower branch, we observe two resistors ($R_{3}$ and $R_{4}$) connected across the same two nodes. This represents a simple parallel configuration.
* **Formula:** $R_{p1} = \frac{R \cdot R}{R + R}$
* **Calculation:** $R_{p1} = \frac{10 \cdot 10}{10 + 10} = \frac{100}{20} = 5 \, \Omega$
* **Physical Logic:** In a parallel circuit, the total resistance is always less than the smallest individual resistor.

### **III. Step 2: Series Integration of the Lower Branch**
The equivalent resistance $R_{p1}$ is connected in series with the preceding resistor ($R_{2}$).
* **Formula:** $R_{lower\_total} = R_2 + R_{p1}$
* **Calculation:** $R_{lower\_total} = 10 + 5 = 15 \, \Omega$

### **IV. Step 3: Integrating the Parallel Upper Branch**
Now, the entire lower branch ($15 \, \Omega$) is in parallel with the top-most horizontal resistor ($R_{1} = 10 \, \Omega$).
* **Formula:** $R_{main\_parallel} = \frac{R_{lower\_total} \cdot R_1}{R_{lower\_total} + R_1}$
* **Calculation:** $R_{main\_parallel} = \frac{15 \cdot 10}{15 + 10} = \frac{150}{25} = 6 \, \Omega$

### **V. Final Step: Total Series Completion**
The entire network simplified so far is in series with the final output resistor ($R_{out} = 10 \, \Omega$).
* **Formula:** $R_{eq} = R_{main\_parallel} + R_{out}$
* **Final Calculation:** $R_{eq} = 6 + 10 = 16 \, \Omega$

**Final Result:** The total equivalent resistance is $16 \, \Omega$.

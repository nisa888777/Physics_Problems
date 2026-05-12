# 15. Theoretical Analysis of a Resistor Cube

**Problem:** Calculate the equivalent resistance ($R_{eq}$) between two body-opposite corners of a cube consisting of 12 identical resistors, each of value $R$.

### **I. Symmetry and Equipotential Nodes**
In a perfectly symmetrical cube, the current entering a corner must distribute itself equally among the three available paths.
- **Stage 1 (Entry):** The current $I$ enters and splits into **3 edges**. Due to symmetry, each carries $I/3$. The resistance of this parallel set is $R/3$.
- **Stage 2 (Middle):** At the next set of vertices, each of the 3 currents must split again into **2 edges**. This creates 6 equal paths, each carrying $I/6$. The resistance of this parallel set is $R/6$.
- **Stage 3 (Exit):** Finally, the 6 paths merge back into **3 edges** to reach the exit corner. Each carries $I/3$. The resistance is $R/3$.

### **II. Total Resistance Summation**
Since these stages are in series relative to the total current flow:
$$R_{eq} = R_{Stage1} + R_{Stage2} + R_{Stage3}$$
$$R_{eq} = \frac{R}{3} + \frac{R}{6} + \frac{R}{3}$$

### **III. Common Denominator Calculation**
Convert to a common denominator of 6:
$$R_{eq} = \frac{2R}{6} + \frac{R}{6} + \frac{2R}{6} = \frac{5R}{6}$$

**Final Result:** The equivalent resistance is **$\frac{5}{6}R$**.

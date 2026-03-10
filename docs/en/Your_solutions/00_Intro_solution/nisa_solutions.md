# 00_Intro_solution
# Section 0: Mathematical Foundations - Step-by-Step Solutions

## 1. Vector Algebra
**Given vectors:** $\vec{a} = [2, 1, -3]$ and $\vec{b} = [4, -2, 1]$

* **Step 1 (Magnitude of $\vec{a}$):** Using $|\vec{a}| = \sqrt{a_x^2 + a_y^2 + a_z^2}$, we calculate $\sqrt{2^2 + 1^2 + (-3)^2} = \sqrt{14}$.
* **Step 2 (Magnitude of $\vec{b}$):** Similarly, $\sqrt{4^2 + (-2)^2 + 1^2} = \sqrt{16 + 4 + 1} = \sqrt{21}$.
* **Step 3 (Dot Product):** $\vec{a} \cdot \vec{b} = (2 \times 4) + (1 \times -2) + (-3 \times 1) = 8 - 2 - 3 = 3$.
* **Step 4 (Cross Product):** Using the determinant method, the result is the vector $[-5, -14, -8]$.
* **Step 5 (Angle):** Since $\cos(\theta) = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}||\vec{b}|}$, we find $\theta = \arccos\left(\frac{3}{\sqrt{294}}\right) \approx 79.9^\circ$.

## 2. Systems of Equations
**Equations:** $2x + 3y = 12$ and $x - y = 1$
* **Step 1:** Isolate $x$ in the second equation: $x = y + 1$.
* **Step 2:** Substitute $x$ into the first equation: $2(y + 1) + 3y = 12 \Rightarrow 2y + 2 + 3y = 12 \Rightarrow 5y = 10$.
* **Step 3:** Solve for $y$: $y = 2$. Then find $x$: $x = 2 + 1 = 3$.
* **Final Answer:** $(x, y) = (3, 2)$.

## 3. Proportionality (Universal Law of Gravitation)
**Analysis of $F = G \frac{m_1 m_2}{r^2}$:**
* **Distance ($r$):** If $r$ is doubled ($2r$), the force decreases by a factor of $2^2 = 4$ due to the inverse square law.
* **Masses ($m$):** If both masses are halved, the product $m_1 \times m_2$ decreases by a factor of $1/2 \times 1/2 = 4$.
* **Conclusion:** The total force $F$ changes by a factor of $1/4 \times 1/4 = 1/16$.

## 4. Rearranging Formulas
**Goal:** Solve $T = 2\pi\sqrt{\frac{L}{g}}$ for $g$.
* **Step 1:** Square both sides: $T^2 = 4\pi^2 \frac{L}{g}$.
* **Step 2:** Multiply by $g$ and divide by $T^2$ to isolate $g$: $g = \frac{4\pi^2 L}{T^2}$.

## 5. Trigonometry
**Given:** Magnitude $= 15$, Angle $= 60^\circ$.
* **Horizontal Component ($A_x$):** $15 \cdot \cos(60^\circ) = 15 \cdot 0.5 = 7.5$.
* **Vertical Component ($A_y$):** $15 \cdot \sin(60^\circ) = 15 \cdot \frac{\sqrt{3}}{2} \approx 12.99$.

## 6. Function Analysis
**Function:** $f(x) = 3x^2 - 12x + 7$
* **Step 1 (Derivative):** $f'(x) = 6x - 12$.
* **Step 2 (Critical Point):** Set $f'(x) = 0 \Rightarrow 6x = 12 \Rightarrow x = 2$.
* **Step 3 (Verification):** $f''(x) = 6 > 0$, confirming $x = 2$ is a **local minimum**.

## 7. Logic & Series (The Fly Problem)
* **Collision Time:** The bicycles are 10m apart and move at 1m/s. They collide in $10 / 1 = 10$ seconds.
* **Fly's Path:** The fly moves at a constant speed of 2m/s for the entire 10 seconds.
* **Total Distance:** $2 \text{ m/s} \times 10 \text{ s} = 20 \text{ meters}$.

## 8. Definite Integrals
**Area calculation:** $\int_0^\pi \sin(x) dx$
* **Integration:** $[-\cos(x)]_0^\pi = -\cos(\pi) - (-\cos(0)) = -(-1) - (-1) = 2$.
* **Result:** The area under the curve is 2.

## 9. Optimization Problem
**Maximize Area $A = x \cdot y$ where $y = 3 - x^2$:**
* **Function:** $A(x) = x(3 - x^2) = 3x - x^3$.
* **Derivative:** $A'(x) = 3 - 3x^2$. Set $A'(x) = 0 \Rightarrow 3x^2 = 3 \Rightarrow x = 1$.
* **Dimensions:** Width $= 1$, Height $= 3 - 1^2 = 2$.

## 10. Infinite Series
**Position Calculation:**
* **X-axis (East/West):** $1 - 1/3 + 1/5 - \dots = \pi/4 \approx 0.785\text{ m}$.
* **Y-axis (North/South):** $1/2 - 1/4 + 1/6 - \dots = \frac{1}{2} \ln(2) \approx 0.347\text{ m}$.
* **Final Position:** $(0.785, 0.347)$.

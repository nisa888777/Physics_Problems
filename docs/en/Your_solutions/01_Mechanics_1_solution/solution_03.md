## 3. Path Intersection
**Problem:** Determine if Alice $A(t)$ and Bob $B(t)$ collide.

* **Step 1: Equating X-coordinates**
  $x_A(t) = 2 + t$
  $x_B(t) = 2t - 1$
  $2 + t = 2t - 1 \Rightarrow t = 3$ (They are at the same horizontal position at 3 seconds)
* **Step 2: Checking Y-coordinates at $t=3$**
  - Alice: $y_A(3) = 8 - 3(3) = 8 - 9 = -1$
  - Bob: $y_B(3) = 2(3) + 2 = 6 + 2 = 8$
* **Conclusion:** Since $y_A(3) \neq y_B(3)$, the paths do not intersect at the same time. They miss each other by 9 units of height.

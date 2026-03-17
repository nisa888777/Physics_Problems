## 10. Kinematics (3D Path Analysis)
**Problem:** Point M moves according to $\vec{r}(t) = (a\cos\omega t, b\sin\omega t, bt)$. Find the trajectory, compute the path length, and discuss special cases.

* **Step 1: Trajectory Analysis**
  The coordinates are $x = a\cos(\omega t)$, $y = b\sin(\omega t)$, and $z = bt$.
  In the $xy$-plane, the motion follows an ellipse: $\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1$.
  Since $z$ increases linearly with time, the overall path is an **elliptical helix** (spiral).

* **Step 2: Velocity and Path Length ($L$)**
  Velocity vector: $\vec{v}(t) = \frac{d\vec{r}}{dt} = (-a\omega\sin\omega t, b\omega\cos\omega t, b)$
  Path length formula: $L = \int_0^{t_0} |\vec{v}(t)| dt = \int_0^{t_0} \sqrt{a^2\omega^2\sin^2(\omega t) + b^2\omega^2\cos^2(\omega t) + b^2} dt$

* **Step 3: Special Case ($a=b$)**
  If $a=b$, the path becomes a **circular helix**.
  The speed simplifies to: $|\vec{v}| = \sqrt{a^2\omega^2(\sin^2 + \cos^2) + b^2} = \sqrt{a^2\omega^2 + b^2}$
  Path length: $L = \sqrt{a^2\omega^2 + b^2} \cdot t_0$

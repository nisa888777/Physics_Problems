# Mechanics I - Complete Solutions

## 1. Projectile Motion
**Given:** $v_0 = 100 \text{ m/s}$, $\theta = 37^\circ$, $g = 9.8 \text{ m/s}^2$

* **Velocity Components:**
  $v_{0x} = v_0 \cos(37^\circ) = 100 \cdot 0.8 = 80 \text{ m/s}$
  $v_{0y} = v_0 \sin(37^\circ) = 100 \cdot 0.6 = 60 \text{ m/s}$
* **Time of Flight ($T$):**
  $T = \frac{2 v_{0y}}{g} = \frac{2 \cdot 60}{9.8} \approx 12.24 \text{ s}$
* **Maximum Height ($H$):**
  $H = \frac{v_{0y}^2}{2g} = \frac{60^2}{19.6} \approx 183.67 \text{ m}$
* **Range ($R$):**
  $R = v_{0x} \cdot T = 80 \cdot 12.24 \approx 979.2 \text{ m}$

---

## 2. Range Optimization
**Proof:** The range formula is $R(\theta) = \frac{v_0^2 \sin(2\theta)}{g}$.

* To find the maximum range, we take the derivative of $R$ with respect to $\theta$ and set it to zero:
  $\frac{dR}{d\theta} = \frac{v_0^2}{g} \cdot 2\cos(2\theta) = 0$
* This implies $\cos(2\theta) = 0$, so $2\theta = 90^\circ \Rightarrow \theta = 45^\circ$.
* **Conclusion:** The maximum range is achieved at a launch angle of $45^\circ$.

---

## 3. Path Intersection
**Paths:** $A(t) = (2+t, 8-3t)$ and $B(t) = (2t-1, 2t+2)$

* **Step 1:** Set the x-coordinates equal to find the time $t$:
  $2 + t = 2t - 1 \Rightarrow t = 3$
* **Step 2:** Substitute $t=3$ into the y-coordinates:
  $y_A(3) = 8 - 3(3) = -1$
  $y_B(3) = 2(3) + 2 = 8$
* **Conclusion:** Since $y_A(3) \neq y_B(3)$, the paths do not intersect.

---

## 4. Vector Calculus
**Position:** $\vec{r}(t) = (3t^2)\hat{i} + (5t - 8t^2)\hat{j}$

* **Velocity Vector ($\vec{v}$):**
  $\vec{v}(t) = \frac{d\vec{r}}{dt} = (6t)\hat{i} + (5 - 16t)\hat{j}$
* **Acceleration Vector ($\vec{a}$):**
  $\vec{a}(t) = \frac{d\vec{v}}{dt} = (6)\hat{i} + (-16)\hat{j}$

---

## 5. Relative Velocity
**Given:** $v_{river} = 2 \text{ m/s}$ (East), $v_{boat} = 5 \text{ m/s}$, Width $= 200 \text{ m}$

* **Step 1 (Angle):** $5 \sin(\theta) = 2 \Rightarrow \theta = \arcsin(0.4) \approx 23.58^\circ$ (West of North).
* **Step 2 (Resultant Velocity):**
  $v_y = \sqrt{5^2 - 2^2} = \sqrt{21} \approx 4.58 \text{ m/s}$
* **Step 3 (Time):**
  $t = \frac{200}{4.58} \approx 43.67 \text{ s}$

---

## 6. Variable Velocity
**Given:** $v(t) = t^2 + 2t - 5$, $x(0) = 4$

* **Step 1 (Position Equation):**
  $x(t) = \int (t^2 + 2t - 5) dt = \frac{t^3}{3} + t^2 - 5t + 4$
* **Step 2 (Calculation at t=3):**
  $x(3) = \frac{27}{3} + 9 - 15 + 4 = 7$
* **Step 3 (Acceleration):**
  $a(t) = \frac{dv}{dt} = 2t + 2 \Rightarrow a(3) = 8 \text{ m/s}^2$

---

## 7. Elimination of Time
**Equations:** $x(t) = 2t^2$, $y(t) = 3t^3$

* **Step 1:** $t = (x/2)^{1/2} \Rightarrow y = 3(x/2)^{3/2}$
* **Step 2:** $\vec{v}(t) = (4t)\hat{i} + (9t^2)\hat{j}$
* **Step 3:** $\vec{a}(t) = (4)\hat{i} + (18t)\hat{j}$
* **Conclusion:** Acceleration is not constant because it depends on $t$.

---

## 8. Circular Motion
**Given:** $R = 6378000 \text{ m}$, $T = 86400 \text{ s}$

* **Velocity ($v$):**
  $v = \frac{2 \pi R}{T} \approx 463.83 \text{ m/s}$
* **Centripetal Acceleration ($a_c$):**
  $a_c = \frac{v^2}{R} \approx 0.0337 \text{ m/s}^2$

---

## 9. Momentum Comparison
**Formula:** $p = m \cdot v$

* **Fly:** $m = 0.002 \text{ kg}, v = 10 \text{ m/s} \Rightarrow p = 0.02 \text{ kg}\cdot\text{m/s}$
* **Tennis Ball:** $m = 0.06 \text{ kg}, v = 1 \text{ m/s} \Rightarrow p = 0.06 \text{ kg}\cdot\text{m/s}$
* **Result:** The tennis ball has a greater momentum.

---

## 10. Kinematics Trajectory
**Position:** $\vec{r}(t) = (a\cos\omega t)\hat{i} + (b\sin\omega t)\hat{j} + (bt)\hat{k}$

* **Trajectory:** The path is an **elliptical helix**.
* **Path Length ($L$):**
  $v(t) = \sqrt{(-a\omega\sin\omega t)^2 + (b\omega\cos\omega t)^2 + b^2}$
  $L = \int_0^{t_0} \sqrt{a^2\omega^2\sin^2\omega t + b^2\omega^2\cos^2\omega t + b^2} dt$

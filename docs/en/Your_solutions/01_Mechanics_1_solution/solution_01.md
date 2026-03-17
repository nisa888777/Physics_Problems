# 🚀 Projectile Motion: Physics & Kinematics

Projectile motion is a form of motion experienced by an object or particle that is thrown near the Earth's surface and moves along a curved path under the action of gravity only.

### 1. Fundamental Assumptions
* **Constant Acceleration:** $a_y = -g$ (where $g \approx 9.8 \text{ m/s}^2$).
* **Zero Horizontal Acceleration:** $a_x = 0$ (no air resistance).
* **Independence of Motion:** Horizontal and vertical motions are independent of each other.

---

### 2. Initial Velocity Components
When a projectile is fired with an initial velocity $v_0$ at an angle $\theta$:

* **Horizontal Component:** $v_{0x} = v_0 \cdot \cos(\theta)$
* **Vertical Component:** $v_{0y} = v_0 \cdot \sin(\theta)$



---

### 3. Key Kinematic Equations

| Parameter | Formula |
| :--- | :--- |
| **Horizontal Displacement** | $x = v_{0x} \cdot t$ |
| **Vertical Displacement** | $y = v_{0y} \cdot t - \frac{1}{2}gt^2$ |
| **Vertical Velocity** | $v_y = v_{0y} - gt$ |

---

### 4. Summary of Key Formulas

The following formulas apply when the projectile starts and ends at the **same horizontal level**:

#### A. Time of Flight ($T$)
The total time the object remains in the air:
$$T = \frac{2 \cdot v_{0y}}{g} = \frac{2v_0 \sin(\theta)}{g}$$

#### B. Maximum Height ($H$)
The highest vertical point reached:
$$H = \frac{v_{0y}^2}{2g} = \frac{(v_0 \sin(\theta))^2}{2g}$$

#### C. Horizontal Range ($R$)
The total horizontal distance traveled:
$$R = v_{0x} \cdot T = \frac{v_0^2 \sin(2\theta)}{g}$$



---

### 5. Worked Example
**Given:** $v_0 = 100 \text{ m/s}$, $\theta = 37^\circ$, $g = 9.8 \text{ m/s}^2$.

1.  **Velocity Components:**
    * $v_{0x} = 100 \cdot 0.8 = 80 \text{ m/s}$
    * $v_{0y} = 100 \cdot 0.6 = 60 \text{ m/s}$

2.  **Time of Flight:**
    $$T = \frac{2 \cdot 60}{9.8} \approx 12.24 \text{ s}$$

3.  **Maximum Height:**
    $$H = \frac{60^2}{19.6} \approx 183.67 \text{ m}$$

4.  **Range:**
    $$R = 80 \cdot 12.24 \approx 979.2 \text{ m}$$

---

> **Note:** For GitHub rendering, these formulas use standard LaTeX delimiters. GitHub automatically renders `$` for inline and `$$` for block equations.

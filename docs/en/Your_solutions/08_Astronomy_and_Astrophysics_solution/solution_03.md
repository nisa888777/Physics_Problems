# 3. Assessment of Microgravity and Orbital Weightlessness

**Problem Statement:** What is the acceleration due to gravity ($g$) at the altitude of the International Space Station (ISS), which orbits at $400 \, \text{km}$ above the Earth's surface? Why do astronauts experience a state of "weightlessness" despite this gravity?

---

### **I. Theoretical Framework**
According to Newton's Law of Universal Gravitation, the acceleration due to gravity ($g$) at any altitude depends on the mass of the planet and the total distance from the absolute center of that planet.

* **Governing Formula:**
$$g = \frac{G \cdot M_E}{r^2}$$

* **Where:**
  * $G$ = Universal Gravitational Constant $\approx 6.674 \times 10^{-11} \, \text{m}^3\text{kg}^{-1}\text{s}^{-2}$
  * $M_E$ = Earth's Mass $\approx 5.972 \times 10^{24} \, \text{kg}$
  * $r$ = Total distance from Earth's center to the satellite ($R_E + h$)

---

### **II. Step-by-Step Numerical Computation**
To find the precise gravitational acceleration at the ISS altitude, we follow three structured steps:

#### **Step 1: Calculate Total Radial Distance ($r$)**
The Earth's mean radius ($R_E$) is approximately $6378 \, \text{km}$ and the ISS altitude ($h$) is $400 \, \text{km}$.
$$r = R_E + h = 6378 \, \text{km} + 400 \, \text{km} = 6778 \, \text{km}$$
Converting this parameters into standard SI meters:
$$r = 6778 \times 10^3 \, \text{m} = 6.778 \times 10^6 \, \text{m}$$

#### **Step 2: Apply Values to the Gravitational Formula**
We substitute our values into the primary equation:
$$g = \frac{(6.674 \times 10^{-11}) \times (5.972 \times 10^{24})}{(6.778 \times 10^6)^2}$$
$$g = \frac{3.9857 \times 10^{14}}{4.5941 \times 10^{13}} \approx 8.68 \, \text{m/s}^2$$

---

### **III. Physical Interpretation of "Weightlessness"**
The numerical calculation shows that gravity at the ISS altitude ($8.68 \, \text{m/s}^2$) is still about **$88.5\%$** of the gravity on the Earth's surface ($9.81 \, \text{m/s}^2$). Therefore, gravity is fully present in space.

Astronouts experience a state of "weightlessness" not because there is no gravity, but because they are in a state of **continuous free-fall** around the Earth. The ISS and the astronauts fall towards the Earth together at the exact same acceleration rate. Because there is no normal reaction force pushing back against their feet, they experience a complete sensation of zero-gravity.

**Final Result:** The acceleration due to gravity at the ISS is **$8.68 \, \text{m/s}^2$**, and the weightlessness is purely caused by continuous orbital free-fall.

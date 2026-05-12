# 14. Mathematical Modeling of a Series RLC Circuit

**Objective:** Write the governing differential equation for a series RLC circuit and compare it to mechanical damped harmonic oscillation.

### **I. Derivation using Kirchhoff’s Voltage Law (KVL)**
For a series loop containing an Inductor ($L$), Resistor ($R$), and Capacitor ($C$), the sum of voltage drops equals the source voltage $V(t)$:
$$V_L + V_R + V_C = V(t)$$

Substituting the constitutive relations for each component:
* Inductor: $V_L = L \frac{dI}{dt} = L \frac{d^2Q}{dt^2}$
* Resistor: $V_R = I \cdot R = R \frac{dQ}{dt}$
* Capacitor: $V_C = \frac{Q}{C}$

The resulting **Second-Order Differential Equation** is:
$$L \frac{d^2Q}{dt^2} + R \frac{dQ}{dt} + \frac{1}{C} Q = V(t)$$

### **II. Mechanical Analogy**
This equation is mathematically identical to a **Damped Harmonic Oscillator**:
$$m \frac{d^2x}{dt^2} + b \frac{dx}{dt} + kx = F(t)$$

### **III. Comparison Table**

| Electrical Parameter | Mechanical Analogy | Role in System |
| :--- | :--- | :--- |
| **Inductance ($L$)** | **Mass ($m$)** | Inertia (Resistance to change in flow/velocity) |
| **Resistance ($R$)** | **Damping Constant ($b$)** | Energy Dissipation (Friction) |
| **Reciprocal Capacitance ($1/C$)** | **Spring Constant ($k$)** | Potential Energy Storage (Elasticity) |
| **Charge ($Q$)** | **Displacement ($x$)** | State of the system |
| **Voltage ($V$)** | **Driving Force ($F$)** | External Excitation |

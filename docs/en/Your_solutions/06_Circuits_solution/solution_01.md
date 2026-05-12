# 1. Series and Parallel Circuit Analysis

**Problem:** Calculate total resistance ($R_{eq}$) and battery current ($I$) for $R_1=15\Omega, R_2=30\Omega, R_3=50\Omega$ with $V=12\text{V}$.

### **A. Series Connection**
In a series circuit, the total resistance is the algebraic sum of all individual resistances because the current has only one path to follow.

* **Step 1: Formula** 
  $$R_{eq} = R_1 + R_2 + R_3$$
* **Step 2: Calculation** 
  $R_{eq} = 15\Omega + 30\Omega + 50\Omega = 95\Omega$
* **Step 3: Ohm's Law for Current** 
  Using $V = I \cdot R$:
  $I = \frac{V}{R_{eq}} = \frac{12\text{V}}{95\Omega} \approx 0.1263\text{ A}$ (or $126.3\text{ mA}$)

### **B. Parallel Connection**
In a parallel circuit, the voltage across each resistor is the same, and the total resistance decreases as more paths are added.

* **Step 1: Reciprocal Formula** 
  $$\frac{1}{R_{eq}} = \frac{1}{R_1} + \frac{1}{R_2} + \frac{1}{R_3}$$
* **Step 2: Common Denominator (150)**
  $\frac{1}{R_{eq}} = \frac{10}{150} + \frac{5}{150} + \frac{3}{150} = \frac{18}{150}$
* **Step 3: Solve for $R_{eq}$** 
  $R_{eq} = \frac{150}{18} \approx 8.333\Omega$
* **Step 4: Ohm's Law for Current** 
  $I = \frac{V}{R_{eq}} = \frac{12\text{V}}{8.333\Omega} \approx 1.44\text{ A}$

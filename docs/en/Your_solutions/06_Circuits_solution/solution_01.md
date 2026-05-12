# 1. Comparative Analysis of Series and Parallel Circuits

**Problem Statement:** Three resistors $R_1 = 15 \, \Omega$, $R_2 = 30 \, \Omega$, and $R_3 = 50 \, \Omega$ are connected to a $12 \, V$ battery. We calculate the equivalent resistance ($R_{eq}$) and the source current ($I$) for both configurations.

## **A. Series Configuration**
In a series circuit, the total resistance is the sum of all individual resistances as the current follows a single, continuous path.

### **1. Equivalent Resistance ($R_{eq}$)**
The formula for resistors in series is:
$$R_{eq} = R_1 + R_2 + R_3$$
Substituting the given values:
$$R_{eq} = 15 + 30 + 50 = 95 \, \Omega$$

### **2. Current Flowing from the Battery ($I$)**
Using Ohm’s Law ($V = I \cdot R$):
$$I = \frac{V}{R_{eq}} = \frac{12 \, V}{95 \, \Omega} \approx 0.126 \, A$$

---

## **B. Parallel Configuration**
In a parallel circuit, the voltage across each resistor is identical, and the total resistance decreases as more branches are added.

### **1. Equivalent Resistance ($R_{eq}$)**
The reciprocal of the equivalent resistance is the sum of the reciprocals of individual resistances:
$$\frac{1}{R_{eq}} = \frac{1}{R_1} + \frac{1}{R_2} + \frac{1}{R_3}$$
$$\frac{1}{R_{eq}} = \frac{1}{15} + \frac{1}{30} + \frac{1}{50}$$
To solve, we find a common denominator of $150$:
$$\frac{1}{R_{eq}} = \frac{10}{150} + \frac{5}{150} + \frac{3}{150} = \frac{18}{150}$$
$$R_{eq} = \frac{150}{18} \approx 8.33 \, \Omega$$

### **2. Current Flowing from the Battery ($I$)**
$$I = \frac{V}{R_{eq}} = \frac{12 \, V}{8.33 \, \Omega} \approx 1.44 \, A$$

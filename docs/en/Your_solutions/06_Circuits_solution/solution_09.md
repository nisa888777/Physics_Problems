# 9. Determination of Instantaneous Current via Differential Calculus

**Problem Statement:** The charge $Q$ (measured in Coulombs) flowing through a cross-section of a wire is given as a function of time $t$ (measured in seconds) by the following expression:
$$Q(t) = 5t^2 + 5$$
Our objective is to calculate the instantaneous current $I$ flowing through the wire at exactly $t = 3 \, s$.

### **I. Physical and Mathematical Definition**
In electrodynamics, current is defined as the net rate of flow of electric charge through a surface. While average current is the ratio of charge to a finite time interval, the **instantaneous current** is defined as the limit of this ratio as the time interval approaches zero. Mathematically, this is expressed as the first derivative of the charge function with respect to time:
$$I(t) = \frac{dQ}{dt}$$

### **II. The Differentiation Process**
To derive the current function $I(t)$, we apply the fundamental rules of differentiation to the provided function $Q(t) = 5t^2 + 5$:

1.  **Power Rule Application:** For the term $5t^2$, we bring the exponent to the front and decrease the power by one:
    $$\frac{d}{dt}(5t^2) = 2 \cdot 5 \cdot t^{2-1} = 10t$$
2.  **Constant Rule Application:** The derivative of any constant value (in this case, $+5$) is zero:
    $$\frac{d}{dt}(5) = 0$$

Combining these results, the general function for the current $I$ at any time $t$ is:
$$I(t) = 10t$$

### **III. Evaluation at $t = 3 \, s$**
To find the specific current at the requested moment, we substitute the value $t = 3$ into our derived linear function:
$$I(3) = 10 \cdot (3)$$
$$I(3) = 30 \, A$$

**Final Result:** The instantaneous current flowing through the wire at $t = 3 \, s$ is exactly **$30 \, A$ (Amperes)**.

### **IV. Summary of Analogies**
This calculation demonstrates that just as velocity is the derivative of position, current is the "velocity" of charge flow.

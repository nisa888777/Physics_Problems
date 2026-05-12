# 9. Comprehensive Determination of Instantaneous Current

**Problem Statement:** A time-varying electric charge ($Q$) flows through a conductor. The relationship between the total charge in Coulombs ($C$) and time ($t$) in seconds ($s$) is defined by the following quadratic function:
$$Q(t) = 5t^2 + 5$$
The objective is to derive the equation for the **instantaneous current** ($I$) and evaluate its specific value at exactly $t = 3 \, s$.

---

### **I. Theoretical Framework**
In the study of electrodynamics, we distinguish between average current and instantaneous current. 
* **Average Current** ($\Delta Q / \Delta t$) measures flow over a duration.
* **Instantaneous Current** ($I$) measures flow at a single point in time.

Mathematically, current is defined as the **first-order derivative** of the charge function with respect to time. This represents the slope of the $Q$-$t$ graph at any given moment:
$$I(t) = \lim_{\Delta t \to 0} \frac{\Delta Q}{\Delta t} = \frac{dQ}{dt}$$

---

### **II. Step-by-Step Differentiation Process**
To transition from the charge function $Q(t)$ to the current function $I(t)$, we apply differential calculus rules to each term of the expression $Q(t) = 5t^2 + 5$:

#### **1. Differentiating the Quadratic Term ($5t^2$):**
We utilize the **Power Rule**, which states that $\frac{d}{dt}(at^n) = n \cdot a \cdot t^{n-1}$.
* Here, coefficient $a = 5$ and exponent $n = 2$.
* Step-by-step: $\frac{d}{dt}(5t^2) = 2 \cdot 5 \cdot t^{(2-1)}$
* Result: $10t^1 = 10t$

#### **2. Differentiating the Constant Term ($+5$):**
We utilize the **Constant Rule**, which states that the derivative of any constant value $k$ is zero ($\frac{dk}{dt} = 0$).
* This is because a constant does not change as time passes, so its rate of change is zero.
* Result: $\frac{d}{dt}(5) = 0$

#### **3. Constructing the Current Function ($I(t)$):**
By combining the derivatives of the individual terms, we obtain:
$$I(t) = 10t + 0 \implies I(t) = 10t$$

---

### **III. Final Evaluation at $t = 3 \, s$**
To calculate the magnitude of the current at the specific timestamp requested ($t = 3 \, s$), we substitute the value into our derived linear equation:
* **Equation:** $I(t) = 10 \cdot t$
* **Substitution:** $I(3) = 10 \cdot (3)$
* **Result:** $I(3) = 30$

**Final Result:** The instantaneous current at $t = 3 \, s$ is **$30 \, A$** (Amperes). One Ampere is defined as one Coulomb per second ($1 \, A = 1 \, C/s$).

---

### **IV. Physical Interpretation**
The resulting function $I(t) = 10t$ indicates that the current is not constant but is **increasing linearly** with time. This implies that for every additional second, the current grows by $10 \, A$, showing that the acceleration of charge is constant.

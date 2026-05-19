# 11. Comprehensive Analysis of Power Dissipation and Energy Consumption

**Problem Statement:** A constant DC voltage of $V = 50 \, V$ is applied across a purely resistive component with a resistance of $R = 100 \, \Omega$. We need to calculate:
1. The electrical power ($P$) dissipated by the resistor, measured in Watts ($W$).
2. The total electrical energy ($E$) consumed by the system over a continuous duration of $5 \, \text{minutes}$.

---

### **I. Part 1: Electrical Power Dissipation ($P$)**
Electrical power represents the exact rate at which electrical potential energy is converted into another form of energy (in this case, thermal energy or heat) per unit time.

#### **1. Mathematical Formula**
By combining Joule's Law ($P = I \cdot V$) with Ohm's Law ($I = \frac{V}{R}$), we derive a direct formula that relies strictly on the known parameters of voltage and resistance:
$$P = \frac{V^2}{R}$$

Where:
* $P$ is the thermal power output in **Watts (W)**, where $1 \, W = 1 \, \text{Joule per second} \, (J/s)$.
* $V$ is the applied potential difference in **Volts (V)**.
* $R$ is the electrical resistance in **Ohms ($\Omega$)**.

#### **2. Step-by-Step Calculation**
Substituting the given parameters into our derived quadratic power equation:
* Squaring the voltage value: $V^2 = 50^2 = 2500$
* Dividing by the constant resistance:
$$P = \frac{2500}{100}$$
$$P = 25 \, W$$

---

### **II. Part 2: Total Energy Consumption ($E$)**
Electrical energy is the cumulative product of the power drawn by the system over a specified time window.

#### **1. Dimensional Standardization (Time Conversion)**
In compliance with the International System of Units (SI), the standard metric for time is the **second (s)**. The timeframe given in minutes must be converted to seconds to match the definition of a Watt ($J/s$).
* **Conversion Factor:** $1 \, \text{minute} = 60 \, s$
* **Mathematical Substitution:**
$$t = 5 \, \text{minutes} = 5 \times 60 = 300 \, s$$

#### **2. Mathematical Formula and Calculation**
The linear relationship between total energy, constant power, and time is defined as:
$$E = P \cdot t$$

Substituting our calculated power ($P = 25 \, W$) and standard time ($t = 300 \, s$):
$$E = 25 \, W \cdot 300 \, s$$
$$E = 7500 \, J$$

For proper academic presentation on GitHub, we can also express this value in kilojoules ($kJ$):
$$E = 7.5 \, kJ$$

---

### **III. Final Results Summary**
* **Dissipated Thermal Power:** $25 \, W$ (This indicates that the resistor actively converts $25 \, \text{Joules}$ of electrical energy into waste heat every single second).
* **Total Accumulated Energy:** $7500 \, J$ (or $7.5 \, kJ$).

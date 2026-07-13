## Kirchhoff's Current Law (KCL)
Statement: The algebraic sum of all currents entering and leaving a node (junction) is zero

A-in == A-out

Core Principle: [Conservation of Charge](Conservations#Charge)

Formula: $\sum_{k=1}^{n} I_k = 0$ (At any node) 

Practical Meaning:
Total current flowing into a node = Total current flowing out of the node

Why it matters:
* Current is charge per second
* If more charge entered than left, charge would build up - which doesn't happen in normal circuits

---
## Kirchhoff's Voltage Law (KVL)
Statement: The algebraic sum of all voltages around any closed loop is zero

Core principle: [Conservation of Energy](Conservations#Energy)

Formula: $\sum_{k=1}^{n} V_k = 0$

Practical meaning:
total voltage rises (sources) = Total voltage drops (loads) in the loop.

Why it matters:
Voltage = energy per unit charge (J/C). Going around a full loop, the net energy change for a charge must be zero

---
## Watt's Law (Power Forumla)
Statement: The electrical power (P) in a circuit is equal to the voltage = (V) multiplied by the current (I)

Core Equation: [[General Equations/Equations#Watt's Law|Watt's Law Equation]]

Units: 
* P = Power in Watts (W)
* V = Voltage in Volts (V)
* I = Current in Amps (A)

Physical meaning:
Power is the rate at which energy is used or transferred.
1 Watt = 1 Joule per second (1 W = 1 J/s)

---
## Ohm's Law
Statement: The voltage (V) across a conductor is directly proportional to the current (I) flowing through it, with Resistance (R) as the constant proportionality

Core Equation: [[General Equations/Equations#Ohm's Law|Ohm's Law]]

Units:
V = Voltage in Volts (V)
I = Current in Amps (A)
R = Resistance in Ohms ($\Omega$)

Physical Meaning:
Ohm's Law describes the linear relationship between voltage, current, and resistance in a conductor.

It tells us how much "pressure" (voltage) is needed to push a certain amount of charge (current) through a material that resists the flow (resistance)

---
## Thévenin theorem
**Statement:** Any linear two-terminal network made of voltage sources, current sources, and resistors can be replaced by a **single equivalent voltage source** ($V_{th}$) in series with a **single equivalent resistor** ($R_{th}$).

**Core Equation / Model:** The entire circuit (from the two terminals) behaves exactly like this simple circuit:

$V_{th}$ (Thévenin voltage) in series with $R_{th}$ (Thévenin resistance)

**Units:**

- $V_{th}$ = Voltage in **Volts (V)**
- $R_{th}$ = Resistance in **Ohms (Ω)**

**Physical Meaning:** Thévenin’s Theorem lets you simplify a complicated circuit into one easy-to-understand voltage source and one resistor.

- $V_{th}$ is the **open-circuit voltage** — the voltage you would measure across the two terminals if nothing is connected (no load). It’s the “pressure” the circuit wants to produce.
- $R_{th}$ is the **equivalent resistance** you see looking into the terminals when all independent voltage sources are shorted (turned off) and current sources are opened (removed). It tells you how “stiff” or “weak” the source is.

**Simple Intuition:** Imagine a big, messy battery-powered circuit with lots of resistors and batteries. From the outside, it looks and behaves exactly like one ideal battery ($V_{th}$) with one series resistor ($R_{th}$) inside it.

**Real-world example you can picture:** You have a complicated sensor circuit. Instead of analyzing the whole thing every time, you measure:

- $V_{th}$ = 3.2 V (what a voltmeter reads with nothing connected)
- $R_{th}$ = 220 Ω

Now you can treat the whole sensor as just a 3.2 V source with a 220 Ω resistor in series. Super useful when connecting it to an Arduino analog pin or another circuit!
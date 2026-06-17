# 1.2 Voltage, Current, and Resistance
## 1.2.1 Voltage and Current

#### Voltage
 (Symbol _V_ or sometimes _E_): The voltage between two points is the cost in energy (work done) required to move a unit of positive charge from the more negative point (lower potential) to the more positive point (higher potential)
* Voltage is also called _potential difference_ or _electromotive force (EMF)_
* The unit of measure is the _volt_
*  A _Joule (J)_ of work is done in moving a _coulomb (C)_ $6.242 * 10^{18} electrons$ of charge through a _potential difference_ of _1V_
	* _Electric Potential Energy Equation_:
	* $Joules (J) = Coulomb (C) * Volts (V)$
#### Current
(symbol I): Current is the rate of flow of electrical charge past a point.
* The unit of measurement is Amperes or Amps (A)
* A current of 1A = a flow of 1 Coulomb (C) of charge per second (time) 
* By convention, current in a circuit is considered to flow from a more positive point to a more negative c, ***even though the actual electron flow is in the opposite direction***

***Important:***
* Currents ***flow through things***
* Voltages are applied (or appear) ***across things***
* What you got to say:
	* The voltage _between_ two points or _across_ two points in a circuit
	* Refer to current _through_ a device or connection in a circuit

We _generate_ voltages by doing work on charges in devices such as batteries (conversion of electrochemical energy), generators (conversion of mechanical energy by magnetic forces), solar cells (photovoltaic conversion of energy of photons). 

<center>We get currents by placing voltage across things</center>

In real circuits we connect things together with wires (metallic conductors), each of which has the same voltage on it everywhere (with respect to ground).

#### Rules about voltage and current

* ***Kirchhoff's current law (KCL)***: The sum of the currents into a point in a circuit equals the sum of the current out (Conservation of charge)
	* In other words A-in == A-out:
		* 5 A comes in from a power source
		* 2 A leaves through on resistor
		* 3 A leaves through another branch
		* 5 A in = 2 A + 3 A out -> in == out
* ***Kirchhoff's voltage law (KVL)***: The sum of the voltage drops around any closed circuit is 0 (Conservation of Energy)
	* Battery = elevator that lifts you +5 m (potential rise)
	* Resistor = path downhill where you lose EXACTLY 5m of height by the time you get back to the starting point
	* You cannot end up higher or lower than where you started after a full loop
* Watts (Power/P) = Volts (V) * Current (I): The power (energy per unit of time) consumed by a circuit
	* V in volts
	* I in amps
	* P in Watts
		* A watt is a Joule (J) per second (1W = 1J/S)
	* Examples: [[Watts Law Practice Problems]]
## 1.2.2 Relationship between voltage and current: resistors

### A: Resistance and resistors

Current through a metallic conductor (or other partially conducting material) is proportional to the voltage across it
* In case of wire conductors in circuits, we usually choose a thick enough gauge of wire so that these "voltage drops" will be negligible

A resistor is made of a conductive material, as shown below, with a wire or contacts at each end. It is characterized by resistance: [[Equations#Ohm's Law|Ohm's Law]]
* Carbon
* Thin metal or carbon film
* Wire of poor conductivity

Typical resistors of the most frequently used type (metal-oxide film, metal film, or carbon film) come in values from ***1 ohm (1 $\Omega$) to about megaohms (10 M$\Omega$)

Resistors are also characterized by how much power they can:
* Safely dissipate
* Their physical size
* by other parameters such as:
	* Tolerance (accuracy)
	* Temperature coefficient
	* Noise
	* Voltage coefficient (the extent to which R depends on applied V)
	* Stability with time
	* Inductance
	* Many more

Roughly speaking, resistors are used to convert a voltage to a current, and vice versa\

Resistors are available with resistances 
* from 0.0002 $\Omega$ through $10^{12} \Omega$, 
* standard power ratings from 1/8 watt though 250 watts
* accuracies from .005% though 20%

#### B: Resistors in series and parallel

From the definition of _R_, some simple results follow:
* Series
	* $R = R_1 +R_2$
	* By putting resisters in series, you always get a ***larger*** resistor
* Parallel
	* $R = \frac{R_1 * R_2}{R_1 + R_2}$ or $R = \frac{1}{\frac{1}{R_1} + \frac{1}{R_2}}$
	* By putting resistors in parallel, you always get a ***smaller*** resistor

#### Resistor Trimming Shortcuts
When you cannot find the exact resistor value you need, you can combine two resistors to get very close

##### Series Combination (Trim up)
* Adding resistors in series always ***increases*** total resistance
*  ***Rule of thumb***: A large resistor in series with a small resistor ~ the value of the larger one
How to use it:
* Pick a resistor that is smaller than your target
* Add a much smaller resistor in series to make up the difference
Example:
* Target = 1.2kΩ
* You have a 1kΩ resistor
* Add a 220Ω resistor in series -> Total  = 1.22kΩ
How to:
* Since its series we use the equation in [[#B Resistors in series and parallel]]
	* $R_{total} = 1000Ω + 220Ω = 1220Ω / 1000Ω = 1.22 kΩ$
		* Reminder we can use this when converting [[Misc Useful Notes#Unit Conversion Rule (Metric Prefixes)|Unit Conversion]]

#### Parallel Combination (Trimming Down)
* Adding resistors in parallel always ***decreases*** total resistance
* ***Rule of thumb***: A large resistor in parallel with a small resistor ~ the value of the small one
How to use it:
* Pick a resistor that is larger than your target
* Add a much larger resistor in parallel to pull the value down slightly
Example:
* Target = 10kΩ
* You have a 12kΩ
* Put a 100kΩ resistor in parallel -> total ~ 10.7kΩ
How to:
* We  also use the equation from [[#B Resistors in series and parallel]]
	* $R = \frac{R_1 * R_2}{R_1 + R_2}$ or $R = \frac{1}{\frac{1}{R_1} + \frac{1}{R_2}}$
		* $12000Ω * 100000Ω / 12000Ω + 100000Ω = (120000000Ω / 112000Ω) / 1000 ~ 10.7kΩ$

#### C: Power in Resistors

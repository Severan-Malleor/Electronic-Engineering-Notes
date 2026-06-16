[[General Equations/Equations#Ohm's Law|Ohm's Law]]

1. A resistor has **12 V** across it and a resistance of **300 Ω**. What current flows through it?
Answer:
* 12V = I * 300 $\Omega$
* 12V / 300 $\Omega$ = I
* 0.04 A


2. A circuit draws **0.05 A** (50 mA) through a **220 Ω** resistor. What is the voltage across the resistor?
Answer:
* V = .05A * 220
* V = 11

3. An LED has **2 V** across it and **0.01 A** (10 mA) flowing through it. What is the resistance of the current-limiting resistor needed?
Answer:
* 2V = .01A * $\Omega$
* 2V / .01 = $\Omega$
* 200 = $\Omega$
* 200 $\Omega$ (Ohms)



4. A 5 V Arduino pin is connected to a resistor. If the current is **0.02 A**, what is the resistance?
Answer:
* 5V = .02A * $\Omega$
* 5V / .02A = $\Omega$
* 250 =$\Omega$
* 250 $\Omega$ (Ohms)

#### Intermediate / Practical Problems (Arduino & Real-World)

5. You measure **9 V** across a resistor and **0.03 A** flowing through it.
* a) What is its resistance? 
* b) How much power is it dissipating? (Use Watt’s Law too)

Answer a: 
* 9V = .03 * $\Omega$
* 9 / .03 = $\Omega$
* 300 = $\Omega$
* 300 $\Omega$ (Ohms)
Answer b:
* P = 9 * .03
* P = .27W

6. An Arduino 5 V pin drives an LED with a **1.8 V** forward voltage through a **330 Ω** resistor. 
a) What is the voltage across the resistor? 
b) What current flows through the LED?
Answer a:
* [[Misc Useful Notes#Forward Voltage|Forward Voltage]]
* 5 - 1.8 = 3.2V
Answer b:
* 5V - 1.8V = I * 330 $\Omega$
* 3.2 Volts = I * 330 $\Omega$
* 3.2 Volts/ 330 $\Omega$ = I
* .009 A (More like .0096 or .01 if we round, not sure if we do that or not)

6. A small DC motor is rated for **12 V** and has an internal resistance of **4 Ω** (stall condition). 
a) What current would it draw if stalled? 
b) Is this safe for most Arduino pins? (Hint: Arduino pins are usually limited to ~20–40 mA)

Answer a:
* 12V = I * 4 $\Omega$
* 12V / 4 $\Omega$ = I
* 3 = i
* 3 Amps
Answer b:
No, the pin is running at 3000 mA

8. You want to limit the current to **10 mA** for an LED on a **5 V** supply (LED forward voltage = 2.2 V). What value resistor should you use?
Answer:
* (5-2.2) = (10 / 1000 <- convert to Amps)* $\Omega$
* 2.8 = .01 * *$\Omega$
* 2.8 / .01 = $\Omega$
* 280 = $\Omega$
* 280 Ohms or a step higher at 330 Ohms

8. A 470 Ω resistor is connected across a **9 V** battery. 
a) What current flows?
b) How much power does the resistor dissipate?

Answer a: 
* 9 = I * 470
* 9 / 470 = I
* .019 = I
* .019 A
Answer:
* P = 9 * .019
* P = .171 W

10. You have a 1000 Ω resistor and measure **15 mA** through it. What voltage is across the resistor?
Answer:
* V = (15 / 1000) * 1000
* V = .015 * 1000
* V = 15
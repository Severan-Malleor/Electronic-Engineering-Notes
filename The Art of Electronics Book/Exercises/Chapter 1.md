# Exercise 1.1

You have a 5k resistor and a 10k resistor. What is their combined resistance
(a) in series 
(b) in parallel

Answer a:
* R = 5 + 10
* R = 15k ohms
Answer b:
* R = (5 * 10) / 5 + 10
* R = 50 / 15
* R = 3.33k ohms

# Exercise 1.2

If you place a 1 ohm resistor across a 12-volt car battery, how much power will it dissipate?

Answer:
Using Ohm's law, we find the current to use in Watt's law

V = IR
12 = I * 1
12 / 1 = I
12 = I
12 Amps

Now that we have the current (in amps), we can use Watt's law to find out how much energy is being used/transferred/dissipated
P = VI
P = 12 * 12
P = 144 Watts

# Exercise 1.5 

Show that it is not possible to exceed the power rating of a 1/4 watt resistor of resistance greater than 1k, no matter how you connect it, in a circuit operating from a 15-volt battery.

.25W = 15^2V / R
.25W = 225V / R
.25W * R = 225V * 1/ .25W
R = 225V / .25W
R = 900Ω

We are calculating the **minimum safe resistance** you can use with a given power rating and supply voltage.

- For a **1/4 (.25) W resistor** on **15 V**:
    - Minimum safe resistance = **900 Ω**
    - So any resistor **1 kΩ or higher** is safe (it will never exceed 0.25 W, no matter how you connect it).

# Exercise 1.6. 

New York City requires about $10^{10}$ watts of electrical power at 115 volts (this is plausible: 10 million people, each averaging 1 kilowatt). A heavy power cable might be an inch in diameter. 

Let’s calculate what will happen if we try to supply the power through a cable 1 foot in diameter made of pure copper. Its resistance is 0.05 $\muΩ$ ($5 × 10^{-8}$ ohms) per foot. 

Calculate (a) the power lost per foot from “$I^2R$ losses,” 

Answer a:
First lets find current:
* $I = 10^{10} / 1.15 * 10^2$
* $I = 10^8 / 1.15 = 86956521.74$
* $I = 8.696 * 10^7$
* $I = 86,956,522A$ 
Than we use $P = I^2* R$
* $P_{loss} = (8.696 * 10^7)^2 * (5 * 10^{-8})$
* $P_{loss} = (75.62 * 10^{14}) * (5* 10^{-8})$
* $P_{loss} = 378.1 * 10^6$

(b) the length of cable over which you will lose all 10  watts, and 

(c) how hot the cable will get, if you know the physics involved (CT = 6 x 10^-12   W/K4 cm2). If you have done your computations correctly, the result should seem preposterous. What is the solution to this puzzle?
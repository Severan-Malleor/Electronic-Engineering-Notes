
# Scientific Notation
To express a number in scientific notation, you rewrite it as a number $\ge 1$ and $\lt 10$, multiplied by a power of 10

Sample:
The speed of light is _299792458_ meters per second. 
* This is expressed in scientific notation as $2.99792458 \times 10^8 m/s$ and may be rounded to fewer digits like this: $3.00 \times 10^8m/s$ 

The charge of an electron is a tiny number: 0.00000000000000000016021766208 coulombs
* We can use scientific notation to write the number more simply: $1.6021766208 \times 10^{-19} coulombs$ 
* Note: The _coulomb_ is the Système International d'Unités (SI) unit of charge.
	* The coulomb is defined as:
		* The amount of charge flowing past a point in a wire in one second when the current in the wire is one amp
		* 1 coulomb = 1 amp flowing for 1 second
	* In terms of electrons, one coulomb is the combined charge of $6.24 \times 10^{18} electrons$

# Engineering Notation
The habit in engineering is to use a slightly modified scientific notation.
* Engineers like exponents in multiples of three. This means the digits to the left of the decimal point fall in the range of 1 to 999.

Sample:
It takes light 0.0000333564095 seconds to travel 10 km in a vacuum

1. Find the decimal point
2. Hop over _three (3)_ digits at a time, going right, until you hop over one, two, or three _nonzero digits_.
	1. In this case, take two hops to the right, until you hop over 33
3. Write down 33
4. Add a decimal 33. 
5. Write down the remaining digits: 33.3564095
6. Because we hopped _right_ finish by writing 10 raised to the _negative_ number of hops times three: $-2 hops \times 3 = -6$
7. $33.3564095 \times10^{-6}$ seconds is the time it takes for light to travel 10 km in a vacuum, in engineering notation

One flaw in engineering notation is that it can mislead about the number of significant figures
* Engineers generally deal with wide tolerances of manufactured components, so the number of significant figures in circuit designs is usually small: two to three.
* If the tolerance is important, it is common to write it next to the number, as shown in this example

A large resistance value: $33.3 \times 10^6 \Omega \pm 1\%$

# [[Prefixes|Prefixes]]



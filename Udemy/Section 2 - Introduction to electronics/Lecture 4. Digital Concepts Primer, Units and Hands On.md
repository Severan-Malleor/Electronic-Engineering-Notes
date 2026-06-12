## 1.1.2 Digital Electronics
* Digital electronics are ultimately based on analog building blocks, but these building blocks have been encapsulated in chips (in most cases) and operate with only two states:
	* _HIGH_ (ON)
	* _Low_ (OFF)
* In reality, digital circuits are composed of many analog building blocks, but these parts are internal to each digital building block; hence, each digital component is a black box as far as we are concerned
	* Only when designing interfaces or very high-speed systems do you really have to worry about the electrical characteristics of the chips. Some examples of digital systems are
		* Computers
		* Calculators
		* LCD watches
		* Video game consoles
* Everything in the real world is analog, and we convert the analog signals and data into digital approximations
## 1.2 Units of Measure and Their Origins
* The system most widely used in electronics is the ***International System of Units (SI)***.
* ***We will use the "Metric System."***

| Quantity | Name     | Symbol | Fundamental Units            |
| -------- | -------- | ------ | ---------------------------- |
| Time     | Second   | s      | N/A                          |
| Length   | Meter    | m      | N/A                          |
| Mass     | Kilogram | kG     | N/A                          |
| Force    | Newton   | N      | $1 kg * m/s^2$               |
| Charge   | Coulomb  | C      | $6.24 * 10 ^ {18} electrons$ |
| Energy   | Joule    | J      | $1 N * m$                    |
| Current  | Ampere   | A      | $1 C/s$                      |
| Voltage  | Volt     | V      | $1 J/C$                      |
| Power    | Watt     | W      | $1 J/s$                      |
* ***Force (N)*** is measured in Newtons (N). 1 Newton (N) is equal to the amount of force needed to accelerate a mass of 1 Kilogram (kg) to $1 meter (m) / second (s)^2$ 
* ***The Coulomb (C)*** is the standard measure of charge. 1C = $6.24 * 10^{18}$  or the inverse 1 _electron_ is $1/64 * 10 = 1.6021 * 10 ^{-19}$ (That is a tiny charge)
* ***The Joule (J)*** is a measure of work or energy. One Joule (J) is the amount of energy or work of a ***1 N*** of force applied for a ***1  meter (m) of distance*** 
* Electrical current is measured in ***amperes (A)*** and ***1A*** = ***1 Coulomb (C) /  Second (s)*** or the flow of $6.24 * 10^{18}$ electrons per second past a point of reference.
* The fundamental unit of ***electromotive force*** (the force that move electrons) is named the ***volt***.
	* Voltage is the potential difference between two points in space
	* A more fundamental way to describe a volt is: If you were to move 1 Coulomb (C) of charge while ***expending*** 1 Joule (J) of energy between any two points in space then the potential difference is ***1 volt***
* The ***Watt (W)*** is a measure of power. A watt is a measure of energy expended per second; amazingly enough the unites are just that, ***Joules (J) / Second (s)*** or 1 Watt (W) = ***1J/s*** 
## 1.2.1 SI System Prefixes
* The system also has a number of prefixes that can help you writ large or small quantities in _scientific notation_
	* Scientific notation is a standard way of writing numbers in mathematics. In scientific notation ***all numbers are written as powers of 10*** in the form (_mantissa_ $10^{exp}$), where mantissa is a number ***greater than or equal to 1.0 and exp is ANY positive or negative integer***
		* Examples:
		* 35.0 = 2.4 * $10^1$
		* -0.002323 = -2.323 * $10^{-3}$

| Symbol | Prefix | Scaling Factor |
| ------ | ------ | -------------- |
| a      | atto   | $10^{-18}$     |
| f      | femto  | $10^{-15}$     |
| p      | pico   | $10^{-12}$     |
| n      | nano   | $10^{-9}$      |
| $\mu$  | micro  | $10^{-6}$      |
| m      | mili   | $10^{-3}$      |
| k      | kilo   | $10^{3}$       |
| M      | mega   | $10^{6}$       |
| G      | giga   | $10^{9}$       |
| T      | tera   | $10^{12}$      |
| P      | peta   | $10^{15}$      |
| E      | exa    | $10^{18}$      |

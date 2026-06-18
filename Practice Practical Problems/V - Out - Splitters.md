# Voltage Divider Practice Problems

**Formula Reminder:**
$$
V_{out} = V_{in} \times \frac{R_2}{R_1 + R_2}
$$

---

### Problem 1 – Basic
- $V_{in} = 5\,\text{V}$
- $R_1 = 1\,\text{k}\Omega$
- $R_2 = 1\,\text{k}\Omega$

**Calculate $V_{out}$**

Answer:
$5 \times 1000 / 1000 + 1000$
$5 * .5 = 2.5 V_{out}$


---

### Problem 2
- $V_{in} = 9\,\text{V}$
- $R_1 = 2\,\text{k}\Omega$
- $R_2 = 1\,\text{k}\Omega$

**Calculate $V_{out}$**

Answer:
$9 \times 1000 / 2000 + 1000$
$9 \times 3.33 = 3 V_{out}$


---

### Problem 3 – Arduino Level Shifting
You have a 12 V sensor but your Arduino only accepts 5 V max.  
- $V_{in} = 12\,\text{V}$
- $R_1 = 10\,\text{k}\Omega$
- $R_2 = 4.7\,\text{k}\Omega$

**Calculate $V_{out}$. Is it safe for the Arduino?**

$12 \times 4700 / 4700 + 10000$
$12 \times .320 = 3.84 v_{out}$

Yes because the voltage out going to lower potential is less than the max (3.84 < 5)

---

### Problem 4 – Design Problem
You want $V_{out} = 3.3\,\text{V}$ when $V_{in} = 5\,\text{V}$.  

**Choose reasonable standard resistor values** for $R_1$ and $R_2$.

Answer:
$3.3 = 5 * R_2 / R_1 + R_2$
$3.3 \ 5 = R_2 / R_1 + R_2$
$.66 = R_2 / R_1 + R_2$
$.66(R_1 + R_2) = R_2$
$.66R_1 + .66R_2 = R_2$
$.66R_1 = R_2 - .66R_2$
$.66 R_1 = .34R_2$
$.66 / 0.34 = 1.941 R_2$

$R_2 ~= 1.941 * 10000kΩ= 19.41kΩ$

10kΩ and a 20kΩ

---

### Problem 5 – Loaded Divider (Real World)
Same as Problem 1, but now add a **10 kΩ load resistor** from $V_{out}$ to ground.

**Calculate the new $V_{out}$** and compare it to Problem 1.

First we find the parallel resistance for $R_2$

$R_L = 1000 * 10000 / 1000 + 10000$
$1000000 / 11000$

$R_L = 909.09$ <- New $R_2$

$5 \times 909.09 / 1000 + 909.09$
$5 \times 909.09 / 1909.09$
$5 \times0.476$
$2.38 V_{out}$



---

**Tips:**
- Standard resistor values: 1k, 2.2k, 4.7k, 10k, 22k, etc.
- When $R_1 = R_2$, $V_{out} = V_{in}/2$
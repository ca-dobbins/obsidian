# Rocket Thrust Calculation Practice Problems

---

### Problem 1: Direct Thrust, Effective Exhaust Velocity, and Specific Impulse at Altitude
A liquid-propellant rocket engine operates at an altitude where the ambient atmospheric pressure is $P_0 = 25\text{ kPa}$. During steady-state firing, the engine consumes propellant at a mass flow rate of $\dot{m} = 240\text{ kg/s}$ and expels exhaust gases at a velocity of $V_e = 3,150\text{ m/s}$ through a nozzle with an exit area of $A_e = 0.85\text{ m}^2$. If the static pressure of the exhaust gas right at the nozzle exit plane is $P_e = 40\text{ kPa}$:

1. Calculate the total thrust ($F_T$) produced by the rocket engine in Newtons ($\text{N}$) and kilonewtons ($\text{kN}$).
2. Calculate the effective exhaust velocity ($c$) in $\text{m/s}$.
3. Calculate the engine's specific impulse ($I_{sp}$) at this altitude in seconds ($\text{s}$), using $g_0 = 9.81\text{ m/s}^2$.

#### **Step-by-Step Solution**

1. **Total Thrust ($F_T$):**
   From the general rocket thrust equation:
   $$F_T = \dot{m}V_e + (P_e - P_0)A_e$$
   Convert pressures from $\text{kPa}$ to $\text{Pa}$ ($\text{N/m}^2$):
   $$P_e = 40\text{ kPa} = 40,000\text{ Pa}, \quad P_0 = 25\text{ kPa} = 25,000\text{ Pa}$$
   Substitute the given values:
   $$F_T = (240\text{ kg/s})(3,150\text{ m/s}) + (40,000\text{ Pa} - 25,000\text{ Pa})(0.85\text{ m}^2)$$
   $$F_T = 756,000\text{ N} + (15,000\text{ Pa})(0.85\text{ m}^2)$$
   $$F_T = 756,000\text{ N} + 12,750\text{ N} = \mathbf{768,750\text{ N}} \quad (\text{or } \mathbf{768.75\text{ kN}})$$

2. **Effective Exhaust Velocity ($c$):**
   Using $F_T = \dot{m}c$:
   $$c = \frac{F_T}{\dot{m}} = \frac{768,750\text{ N}}{240\text{ kg/s}} = \mathbf{3,203.13\text{ m/s}}$$

3. **Specific Impulse ($I_{sp}$):**
   Using $c = I_{sp} g_0$:
   $$I_{sp} = \frac{c}{g_0} = \frac{3,203.13\text{ m/s}}{9.81\text{ m/s}^2} = \mathbf{326.52\text{ s}}$$

---

### Problem 2: Isentropic Nozzle Flow and Sea-Level Thrust
A solid rocket motor has a combustion chamber total pressure of $p_t = 6.5\text{ MPa}$ and a total combustion temperature of $T_t = 3,200\text{ K}$. The exhaust gas has a specific heat ratio of $\gamma = 1.25$ and a specific gas constant of $R = 320\text{ J/(kg}\cdot\text{K)}$. The nozzle has a throat area of $A^* = 0.04\text{ m}^2$ and is designed so that the exhaust exits at a Mach number of $M_e = 2.8$ with an exit area of $A_e = 0.185\text{ m}^2$.

Assuming isentropic nozzle flow and standard sea-level ambient pressure ($P_0 = 101,325\text{ Pa}$), calculate:
1. The propellant mass flow rate ($\dot{m}$) through the choked throat.
2. The nozzle exit temperature ($T_e$) and exit velocity ($V_e$).
3. The nozzle exit static pressure ($p_e$) and resulting sea-level thrust ($F_T$).

#### **Step-by-Step Solution**

1. **Mass Flow Rate ($\dot{m}$):**
   $$\dot{m} = \frac{A^* p_t}{\sqrt{T_t}} \sqrt{\frac{\gamma}{R}} \left(\frac{\gamma + 1}{2}\right)^{-\frac{\gamma + 1}{2(\gamma - 1)}}$$
   First, evaluate the exponent and constant factor:
   $$\frac{\gamma + 1}{2} = \frac{1.25 + 1}{2} = 1.125$$
   $$-\frac{\gamma + 1}{2(\gamma - 1)} = -\frac{2.25}{2(0.25)} = -4.5$$
   $$(1.125)^{-4.5} \approx 0.5889$$
   Now substitute all values ($p_t = 6.5 \times 10^6\text{ Pa}$):
   $$\dot{m} = \frac{(0.04\text{ m}^2)(6.5 \times 10^6\text{ Pa})}{\sqrt{3,200\text{ K}}} \sqrt{\frac{1.25}{320\text{ J/(kg}\cdot\text{K)}}} (0.5889)$$
   $$\dot{m} = \frac{260,000}{56.5685} \times (0.0625) \times (0.5889) \approx \mathbf{169.17\text{ kg/s}}$$

2. **Exit Temperature ($T_e$) and Exit Velocity ($V_e$):**
   $$\frac{T_e}{T_t} = \left(1 + \frac{\gamma - 1}{2}M_e^2\right)^{-1} = \left(1 + \frac{0.25}{2}(2.8)^2\right)^{-1} = (1 + 0.125 \times 7.84)^{-1} = (1.98)^{-1} \approx 0.5051$$
   $$T_e = 3,200\text{ K} \times 0.5051 = \mathbf{1,616.16\text{ K}}$$
   Now calculate exit velocity:
   $$V_e = M_e \sqrt{\gamma R T_e} = 2.8 \sqrt{(1.25)(320)(1,616.16)} = 2.8 \sqrt{646,464} = 2.8 \times 804.03 = \mathbf{2,251.28\text{ m/s}}$$

3. **Exit Pressure ($p_e$) and Sea-Level Thrust ($F_T$):**
   $$\frac{p_e}{p_t} = \left(1 + \frac{\gamma - 1}{2}M_e^2\right)^{-\frac{\gamma}{\gamma - 1}} = (1.98)^{-\frac{1.25}{0.25}} = (1.98)^{-5} \approx 0.03284$$
   $$p_e = (6.5 \times 10^6\text{ Pa})(0.03284) = \mathbf{213,460\text{ Pa}} \quad (\approx 213.46\text{ kPa})$$
   Finally, compute sea-level thrust:
   $$F_T = \dot{m}V_e + (p_e - P_0)A_e$$
   $$F_T = (169.17\text{ kg/s})(2,251.28\text{ m/s}) + (213,460\text{ Pa} - 101,325\text{ Pa})(0.185\text{ m}^2)$$
   $$F_T = 380,849\text{ N} + (112,135\text{ Pa})(0.185\text{ m}^2)$$
   $$F_T = 380,849\text{ N} + 20,745\text{ N} = \mathbf{401,594\text{ N}} \quad (\text{or } \mathbf{401.59\text{ kN}})$$
<p align="center">
  <img src="./circuit.png" alt="Circuit Analysis">
</p>

# Advanced Level of Circuit Analysis

Circuit analysis is a vital skill that you employ as an electrical engineer or technician to understand and predict the behavior of an electric circuit. Circuit analysis includes applying mathematical formulas and rules, such as Kirchhoff's and Ohm's laws, to analyze the voltage and current in each circuit component.

Circuit analysis aims to understand how a circuit behaves under different conditions and predict its future behavior. It is crucial for designing and troubleshooting circuits in various systems, including power systems, electronic devices, and communication systems.

## Why Is Circuit Analysis Important?

Circuit analysis is essential for engineers and technicians as it allows them to comprehend how an electric circuit functions. Mathematical formulas and laws like Kirchhoff's and Ohm's are used to study and anticipate the circuit's behavior.

Key uses of circuit analysis include:
- Predicting a circuit's behavior before construction.
- Ensuring the circuit works as planned during the design phase.
- Identifying and resolving issues with a circuit after construction.
- Designing circuits and components to meet specific performance specifications.

In summary, circuit analysis is crucial for comprehending, constructing, and anticipating the behavior of electric circuits.

## Key Terms and Concepts in Circuit Analysis

When learning circuit analysis, you will encounter the following key terms and concepts:

1. **Ohm's Law:**
   - According to this law, the resistance is inversely proportional to the current flowing through a conductor and directly proportional to the voltage applied across it. The relationship between the quantities of electricity flowing through a conductor (such as a wire), the amount of voltage used, and the conductor's resistance is described by the scientific concept known as Ohm's Law.
  
$$
\begin{aligned}
V = I*R
\end{aligned}
$$

2. **Kirchhoff's Laws:**
   - These two rules govern the conservation of charge and energy in an electric circuit. The total current flowing into and out of a junction in a circuit must equal each other, according to the first law, Kirchhoff's current law. According to the second law, known as Kirchhoff's voltage law, all closed loops in a circuit must have a total voltage of zero.

$$
\begin{aligned}
\text{Kirchhoff's Current Law (KCL):} & \quad \sum_{n=1}^{N} I_n = 0 \\
\text{Kirchhoff's Voltage Law (KVL):} & \quad \sum_{n=1}^{N} V_n = 0 \\
\end{aligned}
$$


3. **Resistance:**
   - The amount that a substance or equipment opposes the flow of electric current is known as its resistance. In electrical equations, it is denoted by the letter "R" and is expressed in terms of ohms. Both the voltage across a circuit and the quantity of current flowing through it may be influenced by its resistance. The resistance values of various materials and devices vary, and resistors can also be used to modify a circuit's resistance.

$$
\begin{aligned}
R = \frac{\rho \cdot L}{A}
\end{aligned}
$$


4. **Capacitance:**
   - A circuit or object's capacitance is its capacity to hold an electrical charge. It is denoted by the letter "C" in electrical equations and is measured in farads (F) units. A capacitor is a typical two-terminal device that stores electrical energy in an electric field. They serve as energy stores, signal filters, and other purposes in various electronic circuits. The physical characteristics of the components used to build a capacitor, such as the dielectric constant of the insulator between the plates, affect the capacitance.

$$
\begin{aligned}
C = \frac{\varepsilon \cdot A}{d}
\end{aligned}
$$


5. **Inductance:**
   - A circuit or device's inductance is its capacity to store energy in a magnetic field. In electrical equations, it is denoted by the letter "L" and is expressed in henrys (H) of measurement. An inductor is a popular two-terminal device that stores energy in a magnetic field. They serve as energy stores, signal filters, and other purposes in various electronic circuits.

   - The physical characteristics of the materials used to build an inductor, such as the number of wire turns, the cross-sectional area of the wire, and the permeability of the core material, affect the inductance of the device.

$$
\begin{aligned}
L = \frac{\mu \cdot N^2 \cdot A}{l}
\end{aligned}
$$


6. **AC and DC Circuits:**
   - The two primary categories of electrical circuits are AC and DC circuits. The voltage and current in an AC circuit continually oscillate or fluctuate in a sinusoidal waveform, frequently at a set frequency like 50 or 60 Hz. The power grid usually provides this electricity to residences and commercial buildings.

   - Voltage and current in a DC circuit are constant and don't vary over time. Batteries and other electronic gadgets utilize this kind of electrical power.

   - However, some electronic gadgets, like laptops and cellphones, are made to absorb AC power from the wall outlet and convert it to DC power for internal usage.

$$
\begin{aligned}
\text{DC Power (P):} & \quad P = V \cdot I \\
\text{AC Power (P):} & \quad P = V_{\text{rms}} \cdot I_{\text{rms}} \cdot \cos(\theta)
\end{aligned}
$$

7. **Series and Parallel Circuits:**
   - Electrical circuits typically come in two flavors: series and parallel. The components of a series circuit are wired in a line and linked one after the other so that the current passes through each component in turn. As a result, each component in a series circuit receives the same amount of current. However, the voltage applied across each component may vary.

   - Each component in a parallel circuit has a different current route, thanks to how the components are connected in branches. This indicates that the elements of a parallel circuit share the current. However, the voltage applied across each component is the same.

$$
\begin{aligned}
\text{Series Resistance (Rs):} & \quad R_s = R_1 + R_2 + \ldots + R_n \\
\text{Parallel Resistance (Rp):} & \quad \frac{1}{R_p} = \frac{1}{R_1} + \frac{1}{R_2} + \ldots + \frac{1}{R_n} \\
\end{aligned}
$$


9. **Network Analysis:**
   - Network analysis assesses a circuit's voltage and current using mathematical formulas and rules like Kirchhoff's and Ohm's laws. Electrical engineers may use network analysis, a powerful technique, to forecast and comprehend the behavior of various electrical systems.

   - According to Ohm's Law, the resistance between two locations has an inverse relationship to their voltage and a direct relationship to the current flowing through that conductor. The formula I = V/R is frequently used to express this connection.

   - Kirchhoff's laws are a pair of rules that define how charge and energy are conserved in a circuit. According to Kirchhoff's current law, the total current entering and leaving a junction in a circuit must be equal. According to Kirchhoff's voltage law, all closed loops in a circuit must have zero overall voltage.

   - These rules are used in network analysis and other mathematical methods to calculate the voltage and current in a circuit and anticipate how the circuit would behave under certain circumstances.

$$
\begin{aligned}
\text{Node-Voltage Analysis:} & \quad I_k = \frac{V_i - V_k}{R_k} \quad \text{(Ohm's Law)} \\
\text{Mesh-Current Analysis:} & \quad V_k = I_k R_k \quad \text{(Ohm's Law)} \\
\text{Laplace Transform:} & \quad F(s) = \mathcal{L}\{f(t)\} = \int_0^\infty e^{-st}f(t)dt \\
\text{Two-Port Network Analysis:} & \quad Z_{\text{in}} = \frac{V_{\text{in}}}{I_{\text{in}}}, \quad Z_{\text{out}} = \frac{V_{\text{out}}}{I_{\text{out}}} \\
\end{aligned}
$$


10. **Superposition Theorem:**
   - According to the superposition theorem, the voltage or current at any point in a linear circuit with many sources equals the total of the voltages or currents generated by each source functioning independently. Only linear circuits—which adhere to Kirchhoff's and Ohm's laws and in which the voltage-current relationship is linear—can be used to prove this theorem.

   - Complex circuit problems can be resolved using the Superposition theorem. The voltage or current at each point in the circuit is calculated by assuming that each source operates independently. The final answer is then obtained by adding the results. The examination of a circuit with several sources is made easier with this technique.

   - It is important to note that this theorem does not cover non-linear circuits, such as those that contain diodes, transistors, or other non-linear components.

$$
\begin{aligned}
V_x & = \sum_{n=1}^{N} V_{x_n} \\
I_x & = \sum_{n=1}^{N} I_{x_n}
\end{aligned}
$$


11. **Thevenin's and Norton's Theorem:**
    - Methods for reducing a complicated circuit to a single equivalent circuit for analysis include Thevenin's and Norton's theorem. According to the theorem, any linear circuit can be replaced by an equivalent circuit of an ideal voltage source connected in series with an internal impedance. The voltage represents the open-circuit voltage, and the resistance is visible when looking back into the circuit across the load terminals.

    - According to Norton's Theorem, any linear circuit can be replaced by an equivalent circuit consisting of an ideal current source parallel to an internal impedance. The current, in this case, is the short-circuit current, and the internal impedance is the resistance seen when looking back into the circuit across the load terminals.

    - With the aid of these theorems, a complicated circuit may be reduced to a simpler, easier-to-understand equivalent circuit. These theorems are helpful when examining circuits with several sources or attempting to predict how a circuit will behave in various scenarios.

$$
\begin{aligned}
\text{Thevenin's Theorem:} & \quad V_{\text{th}} = \frac{\sum \text{(EMF)}}{\sum \text{(Resistance)}} \\
& \quad R_{\text{th}} = \sum \text{(Resistance)} \\
\text{Norton's Theorem:} & \quad I_{\text{N}} = \frac{\sum \text{(EMF)}}{\sum \text{(Resistance)}} \\
& \quad R_{\text{N}} = \sum \text{(Resistance)} \\
\end{aligned}
$$

  - After getting a brief introduction to some fundamental ideas, let's examine some of the methods employed in circuit analysis.

These terms and concepts form the foundation of circuit analysis.

## 10 Different Techniques Used To Analyze Circuits

There are several techniques used to analyze circuits, including:

1. **Ohm's Law:**
2. **Kirchhoff's Laws:**
3. **Network Analysis:**
4. **Superposition Theorem:**
5. **Thevenin's and Norton's Theorem:**
6. **Node-Voltage Analysis:**
7. **Mesh-Current Analysis:**
8. **Laplace Transform:**
9. **Two-Port Network Analysis:**
10. **Software-Aided Analysis:**
    
## Conclusion

Circuit analysis is foundational for electronics engineering, and essential for designing, building, and troubleshooting electrical and electronic circuits. It allows for predicting circuit behavior, making informed design decisions, and analyzing the performance of existing circuits.

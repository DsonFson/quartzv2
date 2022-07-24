# Ohm's Law & Derivations
- State Ohm's law
	- The current through a conductor is proportional to the potential difference across it, given a constant temperature
- IV characteristics 
	- metallic conductor
		- Draw IV graph
			- ![[Untitled-2.png|250]]
		- Account for the shape of the graph 
		- A metallic conductor is ohmic; the current is directly proportional to the potential difference. 
	- filament lamp 
		- draw IV graph
			- ![[filament iv.png|250]]
		- Account for the shape of the graph
			- non-ohmic at high voltages but ohmic at small potential differences. 
			- Increased voltage causes increased rate of flow of electrons through the lamp. At higher speeds there are more collisions with atoms in the conductor. These collisions result in energy loss in the form of heat. 
	- semiconductor diode/Light-Emitting-Diode (LED)
		- Definition
			- a solid substance or material whose electrical conductivity is intermediate between that of conductors and insulators 
		- Draw IV graph
			- ![[semiconductor 3.png|500]]
			- What is the region D? 
				- Reverse Bias - Current does not flow 
			- What is the region B?
				- Forward bias - current flows 
			- Which term refers to the voltage value, E?
				- Knee voltage - Around 0.7 V where current starts to flow 
			- Account for the steep rise in the graph beyond C?
				- The voltage barrier is overcome so current starts to flow 
			- What happens to the diode at A?
				- The depletion region (charge barrier) is removed and a high reverse avalanche current flows, permanently damaging the diode. 
			- Account for the occurrence of the red region
				- In  a semiconductor, a charge barrier is formed between the p-type and n-type material as electrons flow from the n-type to the p-type material 
# Kirchhoff's Laws 
- Kirchhoff's laws are helpful for doing calculations for series-parallel circuits. 
- First law
	-  states that
		- **sum** of the currents entering a junction = **sum** of currents leaving the junction
	- This law must be true since
		- The total amount of electric charge in a system does not change with time. (Law of conservation of charge) 
- Second law
	- states that 
		- the sum of all voltages around a closed loop in any circuit must be equal to zero.
	- Voltage drop is 
		-  the energy released PER electron caused by the resistor.
	- How do we determine whether there is a voltage drop or gain across a resistor
		- The polarity of the voltage drop across any resistive component is determined by the direction of current flow through it: _positive_ entering, and _negative_ exiting.
		- ![[Parallel circuit.jpg|500]]
		- NB. This is important for determining voltage drop/gain for resistors across a junction
- Use Kirchhoff's laws to derive an equation for 
	- Resistance in parallel
		- Factors to consider
			- Current: Sum in = Sum out: It = I1 + I2 
			- for any loop sum of V = 0, therefore V is constant 
			- Ohms law: V = IR 
		- Calculation
			-  $It = I_{1} + I_{2}$
			   $V_{t}/R_{t}$= $V_{1}/R_{1} + V_{2}/R_{2}$
			   V is constant, so 
			   
			   $V/R_{t}$ = $V/R_{1} + V/R_{2}$  
			   $1/R_{t}$ = $1/R_{1} + 1/R_{2}$  
			- - ![[paste-397236ac79a75288590112b1733b71b0cbd10e3c.jpg|500]]
	- Resistance in series 
		 - ![[Parallel circuit 1.png]]
		- Factors to consider
			1. $V_{t}  = V_{1}  + V_{2}$  
			2. Current is constant 
				3. Ohmic devices, V= IR
		- Working for derivation 
				$I_{t}R_{t}  = I_{1}R_{1} + I_{2}R_{2}$
					Since current is constant,
				
				$IR = IR_{1} + IR_{2}$
				
				$R_{t}= R_{1}+R_{2}$
		
- Standard example 
- 

# Potential Divider & Wheatstone Bridge 

## Potential divider
### Definition
A potential divider is  a circuit that splits its voltage between components to produce a specific  out put voltage 
### For a potential divider, the $V_{out}$ differs from the $V_{in}$ by the equation

$$V_{out} = Vin \times\frac{R_{2}}{R_{1} + R_{2}}$$



## Wheatstone Bridge
#### Diagram 
![[Potential Divider circuit 2.png]]
#### Derive Potential Divider Equation for an unbalanced bridge 

When Wheatsone bridge is unbalanced, wheatstone bridge, $V_{D}$ is not 0

$$V_{D} = (\frac{R_{2}}{R_{1} + R_{2}})V_{A} - (\frac{R_{3}}{R_{3} + R_{4}})V_{A}$$













#### Derive Potential Divider Equation for  unbalanced bridge

When Wheatsone bridge is unbalanced, wheatstone bridge, $V_{D}$ is  0

$$V_{D} = (\frac{R_{2}}{R_{1} + R_{2}})V_{A} - (\frac{R_{4}}{R_{3} + R_{4}})V_{B}$$

$V_{D}$ is  0 so 

$$ (\frac{R_{2}}{R_{1} + R_{2}})V_{in} = (\frac{R_{4}}{R_{3} + R_{4}})V_{in}$$
$$ \frac{R_{2}}{R_{1} + R_{2}}= \frac{R_{4}}{R_{3} + R_{4}}$$
$$R_{2}(R_{3} + R_{4}) = R_{4}(R_{1} + R_{2})$$
$$R_{2}R_{3} + R_{2}R_{4} = R_{1}R_{4} + R_{2}R_{4}$$
$$R_{2}R_{3} = R_{1}R_{4}$$
$$ \frac{R_{2}}{R_{4}} = \frac{R_{4}}{R_{3}}$$ (Works when $V_{D}$ = 0













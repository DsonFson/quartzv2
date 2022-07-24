
# Coulomb
- Worded formula for Coulomb  
	- The coulomb is equal to the amount of **charge** transported by a constant current of one **Ampere** in one **second**
- Fundamental equation for Coulomb
	- Q = IT
- One Coulomb is equal to how many elementary charges
	- $6.24\times 10^{18}$  elementary charges (see working below)
		- Since 1 electron is $1.6\times 10^{-19}$ C, 1 C = $\frac{1}{1.6\times 10^{-19}}$ = $6.24\times 10^{18}$
- Use an equation to express Coulombs (Q as subject) in terms of work done (W)
	-  Q = $\frac{W}{\bigtriangleup V}$ ( ${\bigtriangleup V}$ is the potential difference )
 # Voltage
- Coulomb is the SI derived unit of 
	- amp-second (recall Q = IT)
# Voltage
- Define voltage/potential difference
	- Electrical energy transferred per unit charge, when electrical energy is converted into another form
- 1 Volt is defined as (worded definition)
	- the potential difference between two points in a circuit when 1 Joule of **energy** is converted to cause 1 Coulomb of **charge**  to flow flow *between the two points*.
- Distinguish between emf  and potential difference in terms of 
	- charge
		- The emf is the amount of energy given to each Coulomb of charge while the  potential difference is the amount of energy utilized by each Coulomb
	- energy
		- emf is the non-electrostatic **influence** causing transfer of  energy across the circuit while the potential difference is an **indication**/measurement of energy difference between any two places in a circuit
	- resistance
		- emf is independent of the circuit's internal resistance but potential difference is proportional to the circuit's resistance.
	- See [[Electrical Circuits]] for empirical and algebraic relationship between emf and voltage 
- The potential difference between two points, A and B, is +/- 1 V  if 
	- the work done in taking 1 C of positive charge between the two points is 1 J (The + and - would become relevant in [[Electric Fields]])
- Express voltage in terms of charge (V as subject)
	- V = W/Q
- A component in a circuit receives energy-carrying charges. Account for an **increase** **in energy** received by the component when **voltage is increased**. 
	- The number of Joules that one Coulomb of charge gives to a component is expressed in Volts. More volts implies more electrical energy is being converted ( W has unit J, E = QV)
# Current
- 1 A is defined as (worded definition)
	- One Coulomb
	- 
	- 
	-  per second
- Electrical current flows from one place to another in a circuit because 
	- of a difference in potential (moves from lower to higher potential)
# Resistance
- Resistance is defined as 
	- Opposition to the flow of current through a conductor
- What does resistance tell us about how electrons are moving in a circuit?
	- It tells us how hard it is for electrons to move in an electrical circuit
- Resistance depends on three factors:
	a) Resistivity
	b) Length
	c) Cross-sectional area
	- Express a single equation relating  the above factors where Resistance (R) is the subject
		-  $R =  \frac{\rho L}{A}$
		- Under what condition does this equation hold true 
			-  Constant temperature
		- How does resistance change if the radius of a conducting wire is doubled
			- $R =  \frac{\rho L}{\pi r^{2}}$ (original)
			- $R_{1} =  \frac{\rho L}{\pi (2r)^{2}}$
			- $R_{1} =  \frac{\rho L}{\pi (4r^{2})}$
			- $R_{1} =  \frac{\rho L}{4 \pi (r^{2})}$ (doubled radius)
			- $\frac{R}{R_{1}}$ = $\frac {\frac{\rho L}{\pi r^{2}}}{\frac{\rho L}{4 \pi (r^{2})}}$ = $\frac{1}{4}$
			- Therefore, resistance decreases by a factor of 4 when the radius of a wire is doubled
		- Define resistivity in terms of resistance (worded definition)
			- The resistance per unit length and cross sectional area of a material at a certain temperature.
	- Distinguish between resistance and resistivity
		- Resistance relates to the  current moving within a circuit, and is dependent on the extrinsic features of the circuit components (Length, cross-sectional areas of wires; current, voltage). But, resistivity is an intrinsic property of a material that depends that describes the ability of a specific material to conduct electricity.
# Power
- A basic definition of power is 
	 work done per unit time. 
	- When applied to electrical circuits, it is
		the rate per unit time at which an electrical circuit transfers electrical energy
- Equations for power in terms of
	- current and voltage only
		- $P=IV$
	- current and resistance only
		- $P=I^{2}R$
	- voltage and resistance only 
		- $P = V^{2}R$
- You plug values into the equivalent equations for power but get different values when they supposed to be ? Explain this
	- Although all the equations are valid, you cannot apply every one of them directly. 
	- Apply this to $P=IV$, $P = V^{2}R$
		- The "V" given in the equation might be the emf. But V in the power equation (and in ohms law) is the potential difference across a given resistor. 
	- Apply this to $P = I^{2}R$
		You often get the right answer with this equation for series circuit. In series,  the current flowing through the circuit is equal to the current flowing through any resistor. And so, you get away with just using it directly
# Drift Velocity & Related Concepts 
![[Drift velocity]]
## Deriving fundamental equation
- The time for a single electron to travel along this section equal to
	$t = \frac{L}{v}$
- The number of electrons (N) within this section of conductor is equal to 
	N = volume x charge carrier density = nLA
- Number of electrons passing through per second is equal to
	- N/t = $\frac{nLA}{t}$ 
	- Reduce above equation
		- N/t = vAn, since L/t gives v
		- Hence write an expression for I
			- I = Q/t =Ne/t
			- I = vAne, or I = neVa (just for mnemonics sake)
## Meat & Potatoes
- Why is that arrow for current pointing in the opposite direction of the electron-flow
	- Conventional current - assumes that current flows out of the positive terminal, through the circuit and into the negative terminal of the source. So this direction does not tell us what direction the electrons are moving in. 
- Define drift velocity
	 The drift velocity is the average rate at which freely-moving electrons are displaced along the length of a conductor. 
- What causes this flow of electrons in the first place?
	- When a potential differenc
	- e is applied across a conductor, delocalised electrons drift towards the positive terminal of the conductor, colliding with metal atoms in the conductor along its path.![[main-qimg-fd36724761e709def93c7ec3fb6ae018.gif]]
- Describe the kinematics of an electrons in a conductor when an electrical field is applied
	- The electron initially accelerates but soon reach a steady state average velocity. 
- The equation for current through the section of a current factoring in its drift velocity is: 
	- I = nevA
	-  Where n is
		charge carrier density/ number of electrons per unit **volume**
	- e is 
		the charge of one electron
		- which is?
			- $1.6\times 10^{-19}$ C
	- v is 
		drift velocity
- The current through an area depends on
	- concentration of charge carriers
	- charge of charge carriers
	- magnitude of drift velocity 
- What is the direction of drift velocity relative to the electric field? 
	- It always opposes the electric field


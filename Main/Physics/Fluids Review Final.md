# Density

- Density is the ratio of mass per volume of a certain object
- Density is represented by the letter rho or $\rho$
- The formula for density is $\rho = \frac{m}{V}$
- Density is an intrinsic property of an object and does not change with size
- Specific gravity is the ratio of densities. 
	- Example: if the specific gravity is more than one relative to water than it will sink

# Pressure and Forces

## Pressure

- Pressure is the ratio of force perpendicular to the area of an object, traditionally measured in atmospheres(atm)
- This is represented by $P = \frac{F}{A}$

## Hydrostatic Pressure

- The pressure exerted on an object submerged in a liquid is known as hydrostatic pressure
- Hydrostatic pressure is represented by $\rho gh$ where $\rho$ is the density of the fluid, the $g$ is $9.81$, and $h$ is the height above the reference point/depth submerged in a fluid
- There are two ways to measure pressure, absolute and gauge pressure
	- Absolute pressure is the sum of the atmosphere and the gauge pressure
		- $P(absolute) = P(atmosphere) + \rho gh$
		- $P(gauge) = \rho gh$
- The general form of the pressure equation is:
	- $P = \rho gh + \frac{1}{2} \cdot \rho v^2$ where P is pressure, $\rho$ is the density of the fluid, $g$ is the acceleration of gravity($9.81$), h is the height above the reference point, and $v$ is the velocity of the fluid

## Pascals Principle

- The pressure at a point in a fluid is equal in all directions
	- This means that if you apply a force to one part of a confined fluid, the pressure will increase throughout the entire fluid, and the force will be transmitted to every point in the fluid and to the walls of the container.
	- Pascal's principle states that the pressure applied to a confined fluid is transmitted undiminished to every part of the fluid and to the walls of the container

## The Bernoulli Effect

- Pressure and velocity are inversely correlated, areas of low velocity have high pressure and vice versa
- Slow moving fluids exert greater pressure on the walls of the container than faster moving fluids, this is known as the Bernoulli Effect
- This is represented by Bernoulli's Equation $P_{1} + \frac{1}{2}\rho v_{1}^2 + \rho gh_{1} = P_{2} + \frac{1}{2}\rho v_{2}^2+ \rho gh$ 
	- Bernoulli's Equation is generally used to determine the velocity or pressure at one point given data from two points
	- Example:
		- Water flows through a horizontal pipe with a cross sectional area of $4m^2$ at a speed of $5 m/s$ with a pressure of $300,000Pa$ at point A. At point B, the cross sectional area is $2m^2$. (a) What is the speed of the water at point B? (b) Calculate the pressure at point B.
		- We can break the equation down into parts, first we use the mass flow rate equation to calculate the velocity at point B
			-  $$
\begin{align}
A_{1}V_{1} = A_{2}V_{2} \\
4 \cdot 5 = 2(V_{2}) \\
V_{2} = 10
\end{align}
$$
		- Then we can calculate the pressure at point B
			- $$
\begin{align}
300,00 + \frac{1}{2}(1000)(5)^2 = P_{2} + \frac{1}{2}(1000)(10)^2 \\
P_{2} = 262,500
\end{align}
$$

# Fluid and Free-Body Diagrams

Here are the steps for drawing a free-body diagram (FBD) for a fluid problem:

1.  Identify the object of interest. This is the object for which you are trying to draw the FBD.

2.  Identify the forces acting on the object. These may include the weight of the object, the buoyant force acting on the object, and any other forces that are applied to the object, such as friction or tension.
  
3.  Draw a reference line to represent the object. This should be a horizontal line, as the object is in a fluid.

4.  Draw a vector to represent each force acting on the object. The vectors should be drawn in the direction in which the force is applied, and their length should be proportional to the magnitude of the force.

5.  Label each force vector with the symbol and magnitude of the force. For example, you might label the weight of the object as "W" and the buoyant force as "Fb."

6.  Add any necessary notes or annotations to the FBD. For example, you might include the density of the fluid or the volume of the object.

7.  Check the FBD to ensure that it is complete and accurate. Make sure that all forces acting on the object are represented, and that the forces are balanced (the sum of the forces is zero).

# Buoyancy

## The Buoyant Force

- Buoyancy is the force cause by a difference in pressure at the top of an object and the bottom of the object
- Using Archimedes Principle we know that the magnitude of the buoyant force is equivalent to the weight of the displaced fluid
- The formula for buoyant force if $F_{b} = \rho Vg$ where g is gravity($9.81$), $V$ is the volume of the object, and $\rho$ is the density of the fluid

## Apparent Weight

- Apparent weight is the weight of an object in a particular fluid
- In a fluid the apparent weight of an object is the force that the object exerts on the scale or other measuring device used to determine it's weight
- The apparent weight of an object in a fluid can be determined via the formula $W_{a} = F_{g} - F_{b}$, the force of gravity on an object - the buoyant force on an object
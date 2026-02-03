#Physics #Math
# Unit1 - Kinematics

## Significant Figures or Sig Figs
 - AP Physics Exams basically ignore sig figs.
	- Use roughly 3 sig figs: 0.02
## Vectors and Scalars
Vectors have both magnitude and direction.
- Examples of Vectors: Displacement, velocity, acceleration.
- Written: $\vec{V}$, $V_{x}$, **V**
- Use arrows to illustrate vectors. Longer arrow = Larger magnitude

 Scalars have magnitude only. (no direction)
- Say, scalar $X$ is just a number that is a magnitude.
- Examples: Time, distance, mass, speed, volume, density, work, energy, rotational inertia.

## Displacement, Velocity, and Acceleration:

### Displacement => $\vec{V}$
- Straight-line distance between the object's initial and final locations.
- Change in position of an object: $\Delta \vec{X} = \vec{X}_{f} - \vec{X}_{i}$
	- If an object stops at the place it started, $\Delta \vec{X} = 0$
- Distance object travels >= magnitude of displacement of the object
### Average speed => $X$
- Distance traveled over time duration of travel
- $Speed_{avg} = \frac{distance}{time}$ 
### Average Velocity => $\vec{V}$
- $\vec{V}_{avg} = \frac{\Delta \vec{x}}{\Delta \vec{t}}$
- Ex units: $\frac{m}{s}| \frac{km}{hr}| \frac{miles}{hr}$
- For a small time interval, velocity ~= instantaneous velocity
	- Think: $\lim_{ \Delta t \to 0 } (\frac{\Delta \vec{x}}{\Delta \vec{t}})$
### Average Acceleration => $\vec{V}$
- $\vec{a}_{avg} = \frac{\Delta \vec{v}}{\Delta t}$
- Ex unit: $\frac{m}{s^2}$
- For a small time interval, acceleration ~= instantaneous acceleration
### Uniformly Accelerated Motion (UAM) Equations or Kinematics Equations.
- These equations can **only** be used when the acceleration is constant.
- Variables: $a| v_{f}| v_{i}| \Delta x| \Delta t$
	- $v_{f}$ & $v_{i}$ are instantaneous velocities.
>$v_{x} = v_{x0} + a_{x}t$  | $v_{fx} = v_{ix} + a_{x}\Delta t$
>$v_{x}^2 = v_{x0}^2+2a_{x}(x-x_{0})$ | $v_{fx}^2=v_{ix}^2+2a_{x}\Delta x$
>$x = x_{0}+v_{x0}t+\frac{1}{2}a_{x}t^2$ | $\Delta x = v_{ix}\Delta t+\frac{1}{2}a_{x}\Delta t^2$ 
>>(not on sheet)
>>$\Delta x=\frac{1}{2}(v_{x}+v_{x0})t$ | $\Delta x \frac{1}{2}(v_{fx}+v_{ix})\Delta t$
- These equations assume $t_{i} = 0 \implies \Delta t = t_{f} - t_{i} = t_{f}-0=t_{f}=t$
- $v_{x}=v_{fx}$ & $x_{f}-x_{i} = x - x_{0} = \Delta x$
- Variables are positive or negative depending on direction
- If you know 3 of the UAM variables you can determine the other 2


## Free Fall
When the only force acting on an object is gravity, then an object is in free fall.
- Think: an ball bouncing up and down
We can use the UAM equations because $a_{y}$ is constant => $g \approx\ \pm \frac{10m}{s^2}$

## Motion Graphs

Position vs time graph
- slope = velocity
- $slope = \frac{\Delta y}{\Delta x} \implies v = \frac{\Delta x}{\Delta t}$
Velocity vs time graph
- slope = acceleration
- $slope = \frac{\Delta y}{\Delta x} \implies a = \frac{\Delta v}{\Delta t}$
- The area between the curve vs time axis is $\Delta x$
Acceleration vs time graph
- The area between the curve vs time axis is $\Delta v$

## Two Dimensional Motion:

Often you'll have to break, or resolve, vectors into their component vectors, x and y.
This is different from interpreting them as a magnitude and direction.
To obtain these, recall geometry: basic trigonometry.


| $\triangle A,A_{x},A_{y}$ <br>$\sin \theta = \frac{opposite}{hypotenus} = \frac{A_{x}}{A}\implies A_{x}=A\sin \theta$<br>$\cos \theta = \frac{ajdacent}{hypotenuse}=\frac{A_{y}}{A}\implies A_{y}=A\cos \theta$ | ![[VectorTriangle.svg\|350]] |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------- |

- 

### Projectile Motion
An object moves in two-dimensions near the surface of a planet where the only force acting on it is the force of gravity.

| x-direction                       | y-direction                                               |
| --------------------------------- | :-------------------------------------------------------- |
| $a_{x}=0$                         | Free Fall                                                 |
| Constant Velocity                 | $a_{y} = -g = -\frac{9.81m}{s^2} \approx-\frac{10m}{s^2}$ |
| $v_{x}=\frac{\Delta x}{\Delta t}$ | Uniformly Accelerated Motion                              |
|                                   |                                                           |
|                                   |                                                           |
- $\Delta t$ is the same in both directions
- Velocity at top in y-direction is zero
- When $\Delta y=0, \Delta t_{up}=\Delta t_{down}$ and $v_{iy} = -v_{fy}$

### Relative motion:
- The description of the motion of an object changes depending on the frame of reference of the person observing the motion.
- Vector addition
- In AP Physics: Relative motion problems are only in one dimension.
- T






#Physics
#Classical_Mechanics
#Lagrangian
#Susskind


# Lagrangian, least action, Euler-Lagrange equations
Created:2022-07-25 14:51

## principle least action
it is a misnomer. Which is word wrong? Least. Because least action means stationary. action is minimum, it tells you that the action is stationary.

### What is law determining equilibrium?
The equilibrium does not require that the potential energy be minimum. stationary requires $$\frac {dV}{dx}=0$$The right word for potential energy is stationary. stationary means, if you move particle a little bit to left and right, particle back. Now we define $\delta v$ 
$$\delta V = \dfrac {dV}{dx} \delta x$$
and the equilibrium equivalent with$$\delta V=0$$
Remind this point the above equation is right for first order. it's not true generally. Equilibrium does not have time dependence. 

### What is the shortest line between two points?
Shortest means minimum. Minimum means stationary.
![[Pasted image 20220521131132.png|#right]]
$$ds = \sqrt {dx^2+dy^2} = \sqrt {1+\dfrac {dy^2}{dx^2}}dx$$
now for minimizing the length of curve, we should minimize $S_{12}$ 
$$S_{12}= \int \sqrt {1+\dfrac {dy^2}{dx^2}}dx$$

If we change a little bit the function, the length of curve will increase. by analogy we should have$$\delta S_{12}=0$$
The shortest path between two points on a curved surface is called a geodesic and a geodesic on a flat plane is a straight line. 

#### Like light but, shortest time

It is similar about light approximately. light travels with same speed. Now imagine light travels in a medium with different refraction. and the speed of light depends on index refraction. it's clear the speed of light depends on position. $C(x,y)$ is a function that shows speed of light in different position. the time is required from 1 to 2 is for incremental is $$dt = \dfrac {\sqrt {1+\dfrac {dy^2}{dx^2}}dx}{C(x,y)}$$
In fact this is the way that light moves in media. **But notice light finds the shortest time not shortest distance.**

#### initial conditions
We need to know two groups initial conditions. 
- position and velocity at $t=0$
- position at final configuration and $t=0$ (we can interpolate between two points)


### What is the connection between this form (Lagrangian) and newton's equation?
In this section we want to explain a law that govern to nature. instead of newton's equation, we seek to another description. For example when we pin the beginning and the end of chain, chain stands like a parabola. Why? In all problem of classical physics, we should minimizing something. In this instance guess what? The potential energy. Now we introduce $\mathcal{A}$ such as action $$ \mathcal{A}= \int dt \mathcal{L}(X,\dot{X}) $$
Action always should be minimum then must $$\delta\mathcal{A}=0$$
For simplicity $$\int dt \rightarrow \varepsilon \sum $$
![[Pasted image 20220523015531.png]]
Final results is:
$$\dfrac {\partial \mathcal{L}(X_{i},V_{i})}{\partial X_{i}} =\dfrac {d}{dt} \dfrac {\partial \mathcal{L}(X_{i},V_{i})}{\partial V_{i}}$$
#### Why Lagrangian is useful?
Because of packaging thing simply. Other reason, it's extremely good tool for changing variable and coordinate. You want to can rewrite in polar or spherical coordinate. This work is complicated to rewrite newton's equation.

## References:
- Classical mechanics, Theoretical minimum, Leonardo Susskind, Lecture 3


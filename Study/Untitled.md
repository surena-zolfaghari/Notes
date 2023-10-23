question 2

The time-averaged potential of a neutral hydrogen atom is given by $\phi = \dfrac {q}{4 \pi\epsilon_0} \dfrac{\exp^{-\alpha r}}{r}(1+ \dfrac{\alpha r}{2})$ where q is the magnitude of the electronic charge, and $α^{−1} = a_0 /2$, $a_{0}$ being the Bohr radius. Find the distribution of charge
(both continuous and discrete) that will give this potential and interpret your result physically.

question 3

A Variation on Coulomb’s Law Suppose the electrostatic potential of a point charge were $V(r) =(1/4πϵ 0 )r ^{−(1+ϵ)}$ rather than the usual Coulomb formula.
Find the potential $V (r)$ at a point at a distance $r$ from the center of a spherical shell of radius $R > r$ with uniform
surface charge per unit area σ. Check the Coulomb limit $\epsilon=0$

 
 3(b)
 To first order in ϵ, show that
 $$\dfrac {V(R)-V(r)}{V(R)} = \dfrac{\epsilon}{2}[\dfrac{R}{r}\ln \dfrac{R+r}{R-r} - \ln \dfrac{4R^2}{R^2-r^2}]$$
 Since the time of Cavendish, formulae like this one have been used in experimental tests of the correctness of Coulomb’s law.
 
 


4(a)
For a given point x 0 and an arbitrary function $\phi$, define $$f(r,x_0) = 1/(4\pi r^2) \int \limits_{S} \phi(x_0+r\hat n') da'$$ where S is the sphere with radius r centered at $x_0$ . (Clearly, f is the average of ϕ over S) Then prove that:$$\dfrac {\partial f}{\partial r} = \dfrac {1}{4\pi r^2} \int \nabla^2\phi(x')d^3x'$$ where the integral is over the volume of the same sphere.



question 7



Let f (z) = u(x, y) + iv(x, y) be an analytic complex function of z = x + iy.
Show that both u and v satisfy the two-dimensional Laplace equation, i.e.:
$$\dfrac {\partial^2 u}{\partial x^2} + \dfrac {\partial^2 u}{\partial y^2} = 0 \; \; \dfrac {\partial^2 v}{\partial x^2} + \dfrac {\partial^2 v}{\partial y^2} = 0$$
(Hint: Use the Cauchy-Riemann equations.)



7 c 


Find u and v for the function $f (z) = log z$ draw curves of u = const. and v = const. and describe the charge configuration
that gives rise to the potential Φ = u.
Hint: $log z$ is not analytic everywhere on the complex plane. But you can remove the branch cut Re z ≤ 0 so that it becomes analytic.


7 d

(d) Let $F = u(x,y) \hat i  − v(x,y) \hat j$ be a two-dimensional vector field. Show that ∇ · F = ∇ × F = 0.


8

Prove the Helmholtz decomposition theorem: Let F(x) be a vector field on $R^3$ and V be a volume bounded by S. Then
$$F(x) = - \nabla \phi(x) + \nabla \times A(x)$$
where:
$$\phi(x)= \dfrac{1}{4\pi}\int_V \dfrac{\nabla'.F(x')}{|x-x'|}d^3x' - \dfrac{1}{4\pi} \int_S \dfrac{F(x').n'da'}{|x-x'|}$$
$$A(x)=\dfrac{1}{4\pi}\int_V \dfrac{\nabla'\times F(x')}{|x-x'|}d^3x' + \dfrac{1}{4\pi} \int_S \dfrac{F(x')\times n'da'}{|x-x'|}$$
So if for any reason the surface terms vanish, a knowledge of the divergence and the curl of F at all points in a region is enough to specify F everywhere in that region.

8 b
Give a counterexample for the applicability of the theorem to $x \notin V$.


8 c
Apply this Helmholtz decomposition theorem to electrostatics and obtain $$\phi(x) = \dfrac{1}{4\pi\epsilon_0} \int_V \dfrac{\rho(x')}{R}d^3x' + \dfrac{1}{4\pi} [\oint_S \dfrac{1}{R} \dfrac{\partial \phi}{\partial n'} - \phi \dfrac{\partial}{\partial n'}(\dfrac{1}{R}]da'$$



$$\phi(x) = \dfrac{1}{4\pi\epsilon_0} \int_V \dfrac{\rho(x')}{R}d^3x' + \dfrac{1}{4\pi} [\oint_S \dfrac{1}{R} \dfrac{\partial \phi}{\partial n'} - \phi \dfrac{\partial}{\partial n'}(\dfrac{1}{R}]da'$$ 

I want to copy this answer and paste in tex file and the run latex.





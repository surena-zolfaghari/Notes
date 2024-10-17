# 2024-01-04 16:30 Su Untitled
Created:2024-01-04 16:30

Current probability for 3-D

$$
\vec{J}(x, t)=\frac{\hbar}{2 m} \operatorname{Im}\left(\psi^{*} \nabla \psi\right)
$$

Current conservation for 3-D

$$
\frac{\partial p}{\partial t}+\nabla \cdot \vec{j}=0
$$

Unit

$$
[\vec{J}]=\frac{1}{L^{2}} \frac{1}{T} \text { probability per unit area and unit time }
$$

Note: In 3-D $[Y]=L^{-3 / 2}$

$$
\begin{aligned}
\frac{d N}{d t}=\int_{-\infty}^{\infty} \frac{\partial P}{\partial t} d x=-\int_{-\infty}^{\infty} d x \frac{\partial J}{\partial x}=- & {[\bar{J}(x=\infty, t)-J(x=-\infty, 2)} \\
& J=\frac{h}{2 i m}\left(\psi^{*} \frac{\partial \psi}{\partial x}-\frac{\psi \partial \psi^{*}}{\partial x}\right)
\end{aligned}
$$

$\Rightarrow \frac{d N}{d t}=0 \quad \Rightarrow \quad 2$ ideas existence of a current for probability $A$ is a hermitian operator

So we saw $\int(\hat{H} \psi)^{*} \psi d x=\int \psi^{*}(\hat{H} \psi) d x$. This is true And therefore we suspect $\hat{h}$ is a hermitian operator. And the thing we should do in order to make sure it is, is put two different functions, not equal function, and it work for different function and it's a good exercise.

$$
\int\left(\hat{H} \psi_{1}\right)^{*} \psi_{2} d x=\int \psi_{1}^{*}\left(\hat{H} \psi_{2}\right) d x
$$

Explain the analogy with current conservation
The interpretation is the same as we have in electromagnetism.
And there is a complete analogy for every thing here not for the wave function, but for all these charge densities and current densities.

|  | $E M$ | $Q_{M}$ |
| :---: | :---: | :---: |
| $p$ | Charges density | Probability <br> densities |
| $Q$ | charges in <br> volume | probability find <br> the particle <br> in volume |
| $J$ | current <br> density | probability <br> current <br> density |

Ampere's law has that current. Ityenerates the curl of $B$. $\left(\nabla \times B=\mu_{0} J\right)$
What I want to make sure is that you understand why these equations like $\frac{\partial p}{\partial t}+\frac{\partial g}{\partial x}=0$ are more powerfull than just showing $\frac{d N}{d t}=0$. They imply a local conservation of probability. You see there has to be physics of this thing.

So the total probability must be one. But suppose you have the probability distributed over space. There must be some relation
between the way the probability are varying at one point and varying in other points. So that every thing is consistence And these are $\frac{\partial P}{\partial t}+\frac{\partial J}{\partial x}=0$. That says whenever you see a probability density change any where, it's because there's some current ia And that's make sense. If you see the charge density in same point in space changing, it's because there must be current.

Thanks to current, You can learn how to interpret the probability much more physically. Because if you ask what is the probability that the particle is from this distance to that distance? you can leak at what the currents are at the edges and see whether that probability is increasing or decreasing. So let's see that

Suppose we have a volume and you put the charge inside the volume. Does this charge change in time? sure it could.

$$
Q_{V}(t)=\int p(x, t) d^{3} x
$$

$$
\frac{\partial Q}{d t}(t)=\int_{V} \frac{\partial P}{\partial t} d^{3} x=-\int_{V} \nabla \cdot \vec{J} d^{3} x
$$

Gauss's law enable us to change this divergence to a Surface integral

$$
\frac{d Q}{d t}=-\int_{S} \vec{J} \cdot d \vec{a}
$$

And this is how you understand current conservation. Charge is never created or destroyed. So if you see the charge inside the volume changing it's because there's some current escaping through the surface. So that's the physical interpretation of that differential equation.

62
$\frac{\partial p}{\partial t}+\nabla \cdot J=0$. This is current conservation and many people lookat this equation and say what? But when you book at $\frac{d a}{d t}=-\int \vec{J} \cdot d \vec{a}$ you say oh yes. The charge changes only because it escapes the volume, not created not destroyed.

Same thing happens for the probability. Now let me closeup with this statement in one dimension.

$$
\begin{gathered}
P_{a b}(t)=\int_{a}^{b} d x p(x, t) \\
\left.\frac{d P_{a b}}{d t}=\int_{a}^{b} d x \frac{\partial \rho}{\partial t}=-\int_{a}^{b} d x \frac{\partial J}{\partial x}=-(J(x=b, t)-J(x=a, t))\right) \\
\frac{d P_{a b}}{d t}=-J(b, t)+J(a, t)
\end{gathered}
$$

You have been looking for the particle and decided to look at this range from a to b. That's the probability to find it there. We learned already that the total probability to find it any where is going to be one. and that's goingtobe conserved. But now let's just ask given what happens to this probability in time? well, it could change. Because the wave function could go up and down. $\rightarrow$ maybe the function was big at appoint and a little later is smah So there's a little probability to find it here. But now you have another physical variable to help you understand it, and that's current.

If the probability to find the particle in this region changes, it's because some current most be escaping from the edges. If the current at $b$ is positive, there's a current going out so that tends to reduce the probability. That's why the sign came out with amin w. on other hand if there is a current in a that tends to send in probability and that why increases in (*) equation. So the difference between these two currents determines whether the probability here increases or decreases
## References:

## Related:





# A-1

Certainly, here are the equations with inline LaTeX formatting using `$`:

1. Start with Gauss's law for electric fields: $\nabla \cdot \mathbf{E} = \frac{\rho}{\varepsilon_0}$

2. Consider the case of a point charge $q$ located at the origin (0, 0, 0). The charge distribution is given by $\rho = q \delta^3(\mathbf{r})$, where $\delta^3(\mathbf{r})$ is the Dirac delta function.

3. Since the charge is at the origin, the electric field $\mathbf{E}$ will only depend on the radial distance $r$, and it will point radially outward from the origin. Therefore, you can write $\mathbf{E}$ as $E(r) \mathbf{r}$.

4. Apply the condition $\nabla \times \mathbf{E} = 0$, which implies that the electric field is irrotational (curl-free) because there are no magnetic monopoles in electrostatics.

5. Given that $\mathbf{E}$ is irrotational, there exists a scalar potential $V$ such that $\mathbf{E} = -\nabla V$.

6. Substitute the charge distribution $\rho = q \delta^3(\mathbf{r})$ into Gauss's law: $\nabla \cdot (-\nabla V) = \frac{q}{\varepsilon_0} \delta^3(\mathbf{r})$

7. This yields Poisson's equation for the electric potential: $\nabla^2 V = -\frac{q}{\varepsilon_0} \delta^3(\mathbf{r})$

8. To solve this equation, use the fact that the Laplacian of $1/|\mathbf{r}|$ is proportional to the Dirac delta function: $\nabla^2 \left(\frac{1}{|\mathbf{r}|}\right) = -4\pi \delta^3(\mathbf{r})$

9. Integrate both sides with respect to $|\mathbf{r}|$ and multiply by $\frac{1}{4\pi\varepsilon_0}$ to obtain the electric potential: $V(\mathbf{r}) = \frac{q}{4\pi\varepsilon_0 |\mathbf{r}|}$

10. Finally, find the electric field from the potential $V$: $\mathbf{E} = -\nabla V = -\nabla \left(\frac{q}{4\pi\varepsilon_0 |\mathbf{r}|}\right) = \frac{1}{4\pi\varepsilon_0} \frac{q}{r^2} \mathbf{r}$

So, by incorporating the condition $\nabla \times \mathbf{E} = 0$ and solving for the electric potential, we have deduced Coulomb's law.



# A 4 a

For a given point x 0 and an arbitrary function $\phi$, define $$f(r,x_0) = 1/(4\pi r^2) \int \limits_{S} \phi(x_0+r\hat n') da'$$ where S is the sphere with radius r centered at x 0 . [Clearly, f is the average of ϕ over S.] Then prove that $$\dfrac {\partial f}{\partial r} = \dfrac {1}{4 \pi r^2} \int_S \nabla^2 \phi(x')d^3x'$$

![[Pasted image 20231017181817.png]]
![[Pasted image 20231017181951.png]]
![[Pasted image 20231017182109.png]]



# A 4 b
 For a given point x 0 and an arbitrary function $\phi$, define $$f(r,x_0) = 1/(4\pi r^2) \int \limits_{S} \phi(x_0+r\hat n') da'$$Let S be a sphere with radius r centered at $x_{0}$ . Show that $\int d\Omega' 1/|x−x′|$ is equal to $4\pi/r$ if S engulfs x, and equal to $4\pi/|x−x′|$
otherwise. (You can interpret this result in physical terms as the fact that the electric potential outside of a uniformly
charged shell is the same as that of a point at its center, and that the electric field inside vanishes. The (constant) value of
the potential inside follows from continuity.)


# Solve
![[Pasted image 20231017185608.png]]

![[Pasted image 20231017185649.png]]

![[Pasted image 20231017185718.png]]




# A 6



## Proof of the Maximum Principle for Harmonic Functions

The "maximum principle" for harmonic functions states that if a function $u$ is harmonic in a connected open set $\Omega$, then $u$ attains its maximum and minimum values on the boundary $\partial \Omega$ or at isolated points in $\Omega$ where $u$ is constant. This property is significant in various fields, including electrostatics, fluid dynamics, and heat conduction.

**Definition**: A function $v$ is said to be subharmonic in a domain $\Omega$ if it is twice continuously differentiable in $\Omega$ and $\Delta v \geq 0$ in $\Omega$, where $\Delta$ is the Laplacian operator.

**Theorem (Maximum Principle for Harmonic Functions)**:
If $u$ is a harmonic function in a connected open set $\Omega$, then $u$ attains its maximum and minimum values on the boundary $\partial \Omega$ or at isolated points in $\Omega$ where $u$ is constant.

**Proof**:

1. **Maximum and Minimum on Boundary**: Assume for contradiction that there exists a point $\mathbf{x}_0$ in the interior of $\Omega$ where $u$ attains its maximum or minimum value. Without loss of generality, assume it's a maximum. Then, there must be a neighborhood of $\mathbf{x}_0$ where $u$ attains a local maximum.

2. **Construct a Subharmonic Function**: Define a function $v(\mathbf{x}) = u(\mathbf{x}) - u(\mathbf{x}_0)$. This function $v$ is harmonic because $u$ is harmonic. Now, consider $v$ in a neighborhood of $\mathbf{x}_0$.

3. **Local Maximum for $v$**: At the point $\mathbf{x}_0$, we have $v(\mathbf{x}_0) = 0$. In the neighborhood, $v$ attains its local maximum at $\mathbf{x}_0$ because $u$ is maximal there.

4. **Using Subharmonic Function**: By the maximum principle for subharmonic functions, $v$ should be constant on the boundary of the neighborhood or have a local maximum at an isolated point in the neighborhood. Since $\mathbf{x}_0$ was assumed to be an interior point, $v$ must be constant in a neighborhood, and by extension, in the entire connected open set $\Omega$

5. **Consequence**: If $v$ is constant in $\Omega$, it means $u$ is constant in $\Omega$. However, if $u$ is constant in an open connected set, it must be a constant function in that set. So, the assumption that $u$ attains a maximum in the interior leads to $u$ being constant in $\Omega.

6. **Conclusion**: If $u$ is not constant, it can't have a maximum in the interior. Therefore, it either attains its maximum and minimum values on the boundary of $\Omega$ or at isolated points in $\Omega$.

This concludes the proof of the maximum principle for harmonic functions. In physical terms, this principle has significant applications, such as Earnshaw's theorem, which states that a point charge cannot be held in stable equilibrium by electrostatic forces because the electric potential must be harmonic, and a maximum within the region implies that the system is unstable.


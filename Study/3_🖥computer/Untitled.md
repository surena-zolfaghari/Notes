
# Electrodynamics

- [x] introduction; 1.1-1.5, 1.7.
- [x] Helmholtz's decomposition theorem; Green function as an operator inverse.
- [x] 1.8-1.10
- [x] 1.10-1.12, 2.5.
- [x] Assignment 1
- [x] 2.6, 2.10.
- [x] relation between harmonic and analytic functions, 2.11, 3.1
- [x] 3.2, 3.3.
- [x] 3.5, more on the peaks and angular shape of spherical harmonics, 3.6.
- [x] 3.12, 4.1.
- [x] Assignment 
- [x] 4.1, 4.2, macroscopic fields.
- [x] macroscopic equations of electrostatics (4.3)
- [x] 4.4, 4.5
- [x] 4.5, 4.6,
- [x] 5.1
- [x] 5.2, 5.4, 5.6.
- [x] 5.6-5.8.
- [x] 5.9, 5.10.
- [x] 5.11, 5.12, 6.1.
- [x] 6.2-6.4
- [x] 6.4, 6.5.
- [x] 6.7
- [x] 6.9, 6.10.
- [x] 6.11, 6.12.
- [x] 11.6.
- [x] 11.6, 11.9
- [x] 11.10
- [x] 12.7
- [x] 12.10
- [x] 12.1

$$\nabla . \dfrac {{\hat{x}}}{|x^2|}$$



Consider the surface $z = 2\sqrt r$ (in cylindrical coordinates) as a two-dimensional manifold embedded in $\mathbb{R^3}$. It has a cusp in the center. By considering radial geodesics going toward the center, can you say whether the manifold is geodesically complete or not?


Show that the metric on our manifold (induced from $\mathbb{R^3}$ ) is $ds^2=(1+\dfrac {1}{r})dr^2+r^2 d\theta^2$

and the obtain Ricci curvature of the manifold



show that radial geodesics satisfy
$$\dfrac {dr}{ds}=\sqrt{\dfrac {r}{r+1}}$$
where s is the affine parameter. From this equation show that r = 0 is reached in a finite amount of s and so radial geodesics are not complete.





(Superposition in spherically symmetric spacetimes) We explained in the text that Einstein’s equations are nonlinear
and solutions cannot be superposed. A surprising exception to this result is in the case of spherically symmetric spacetimes of a particular kind. This exercise explores this feature.
(a) Consider a metric of the form
$$ds^2=-f(r)dt^2 + f(r)^{-1} dr^2 + r^2(d\theta^2+sin^2\theta$d\phi^2 \tag{1}$$

with a general function $f(r)$ that needs to be determined via Einstein’s equations. Show that this metric will satisfy Einstein’s equations provided the the source energy-momentum tensor has the form

$$T^t_t=T^r_r=-\dfrac {\epsilon(r)}{8\pi G};\;\; T^\theta_\theta=T^\phi_\phi=- \dfrac {\mu(r)}{8\pi G} \tag{2}$$
Equation (2) also defines the functions $\epsilon(r)$ and $\mu(r)$.

Show that the Einstein equations now reduce to:
$$\dfrac {1}{r^2}(1-f)-\dfrac {f'}{f}=\epsilon \; ;\; \nabla^2=-2\mu$$

Given any $\epsilon(r)$, integrate the Eq. (3)
$$\dfrac {1}{r^2}(1-f)-\dfrac {f'}{f}=\epsilon \; ;\; \nabla^2=-2\mu \tag{3}$$
 to determine the solution to be
 $$f(r)1-\dfrac {a}{r}-\dfrac {1}{r} \int_a^r\epsilon(r)r^2dr$$
 with a being an integration constant chosen such that $f = 0$ at $r = a$ and $\mu(r)$ is fixed by $\epsilon(r)$ through
 $$\mu(r)=\epsilon+\dfrac {1}{2}r\epsilon'$$
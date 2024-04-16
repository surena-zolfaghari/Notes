

Review of Tensor calculus.
vectors are column vectors like$\left(\begin{array}{l}1 \\ 2 \\ 3 \\ 1\end{array}\right)$,and  covectors are row vectors like : $(\left.\ 2,3,3,4\right)$.

Tensors are combinations vectors and covectors.

# Transition matrix

## convention for basis vector
old basis : $\left\{e_1, e_2\right\} \quad$ New basis. $\left\{\tilde{e}_1, \tilde{e}_2\right\}$
$$
\left\{\begin{array}{l}
\tilde{e}_1=2 e_1+1 e_2 \\
\tilde{e}_2=-\frac{1}{2} e_1+1 / 4 e_2
\end{array}\right.
$$

Change of basis matrix (transition matrix) is $\left[\begin{array}{rr}2 & -1 / 2 \\ 1 & 1 / 4\end{array}\right]=F$

This matrix changes old to new. So if you multiple this matrix with a vector in old basis, It gives you a vector in new basis.

Now how will changes the components of a vector? inverse!
old basis




Visualize


Imagine

It's clear each component of new basis is twice of old basis and each component of $V$ new basis is half of the component of $V$ in old basis.

Now let's pay to convector. I said vectors are column vectors and convectors are row vectors. Notice Convector is not about transpose.
Paleo $\qquad$
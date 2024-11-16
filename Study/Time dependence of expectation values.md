# 2024-02-16 17:05 Su Time dependence of expectation values
Created:2024-02-16 17:05

It's a statement about the time dependence of the expectation valves. it's fundamental theorem.

$$
\begin{align*}
\frac{d}{d t}\langle\hat{Q}\rangle & =\frac{d}{d t} \int \psi^{*} Q \psi d x=\int[\underbrace{\frac{\partial \psi^{*}}{\partial t} Q}_{\text {Schrodinger equation }} \psi_{(x, t)} +\psi^{*} Q \frac{\partial \psi(x, t)}{\partial t}] d x  \tag{C}\\
& =\int d x\left(\frac{i}{\hbar}(\hat{H} \psi)^{*} Q \psi(x, t)-\frac{i}{\hbar} \psi^{*} Q \hat{H} \psi(x, t)\right)
\end{align*}
$$

Remember $\quad i \hbar \frac{\partial \psi}{\partial t}=\hat{H} \psi$

$$
\begin{aligned}
& \stackrel{\times i \hbar}{\Rightarrow} \quad i \hbar \frac{d}{d t}\langle Q\rangle=\int d x(\Psi^{*} Q \hat{H} \Psi-(\underbrace{(\hat{H}}_{\text {is Hermitian }} \Psi)^{*} Q \Psi \\&
\overset{\text{by Hermiticy}}{\underset{\text{on second terms}}{=}} \int d x\left(\Psi^{*} Q \hat{H} \Psi\left(\Psi^{*}\right)-\Psi^{*} H Q \Psi\right)
\end{aligned}
$$

What do we see? QH, HQ it represent commutator.
it $\frac{d}{d t}\langle Q\rangle=\int d x \psi^{*}(\underbrace{Q \hat{H}-\hat{H} Q}_{[Q, H]}) \psi(x, t)$
( $\int d x \psi^{*}(Q \hat{H}-H Q) \psi(x, t)$ is expectation value of $[Q, H]$ $i \hbar \frac{d}{d t}\langle Q\rangle=\langle[Q, H]\rangle$
## References:39

## Related:


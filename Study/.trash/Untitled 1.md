Let's approach this problem directly. We have the geodesic equation in the form:

\[\frac{\mathrm{D} t^\alpha}{\mathrm{d} \lambda} = \kappa t^\alpha\]

And we have the relationship between the parameters $\lambda^*$ and $\lambda$:

\[\frac{\mathrm{d} \lambda^*}{\mathrm{d} \lambda} = \exp\left(\int \kappa(\lambda) \mathrm{d} \lambda\right)\]

We want to show that if $u^\alpha = \frac{\mathrm{d} x^\alpha}{\mathrm{d} \lambda^*}$, then $\frac{\mathrm{D} u^\alpha}{\mathrm{d} \lambda^*} = 0$.

First, let's express $u^\alpha$ in terms of $\lambda$:

\[u^\alpha = \frac{\mathrm{d} x^\alpha}{\mathrm{d} \lambda^*} = \frac{\mathrm{d} x^\alpha}{\mathrm{d} \lambda} \frac{\mathrm{d} \lambda}{\mathrm{d} \lambda^*}\]

From the given relationship, we know that $\frac{\mathrm{d} \lambda}{\mathrm{d} \lambda^*} = \exp\left(\int \kappa(\lambda) \mathrm{d} \lambda\right)$.

Thus:

\[u^\alpha = t^\alpha \exp\left(-\int \kappa(\lambda) \mathrm{d} \lambda\right)\]

Now, let's differentiate $u^\alpha$ with respect to $\lambda^*$:

\[\frac{\mathrm{D} u^\alpha}{\mathrm{d} \lambda^*} = \frac{\mathrm{d}}{\mathrm{d} \lambda^*} \left(t^\alpha \exp\left(-\int \kappa(\lambda) \mathrm{d} \lambda\right)\right)\]

Using the product rule:

\[\frac{\mathrm{D} u^\alpha}{\mathrm{d} \lambda^*} = \frac{\mathrm{d} t^\alpha}{\mathrm{d} \lambda^*} \exp\left(-\int \kappa(\lambda) \mathrm{d} \lambda\right) + t^\alpha \frac{\mathrm{d}}{\mathrm{d} \lambda^*} \left(\exp\left(-\int \kappa(\lambda) \mathrm{d} \lambda\right)\right)\]

But $\frac{\mathrm{d} t^\alpha}{\mathrm{d} \lambda^*} = \frac{\mathrm{d} t^\alpha}{\mathrm{d} \lambda} \frac{\mathrm{d} \lambda}{\mathrm{d} \lambda^*} = \kappa t^\alpha$ and $\frac{\mathrm{d}}{\mathrm{d} \lambda^*} \left(\exp\left(-\int \kappa(\lambda) \mathrm{d} \lambda\right)\right) = 0$ because the exponential term is independent of $\lambda^*$.

Therefore, we have:

\[\frac{\mathrm{D} u^\alpha}{\mathrm{d} \lambda^*} = \kappa t^\alpha \exp\left(-\int \kappa(\lambda) \mathrm{d} \lambda\right) = \kappa u^\alpha\]

But from the geodesic equation, we know that $\frac{\mathrm{D} t^\alpha}{\mathrm{d} \lambda} = \kappa t^\alpha$. This means $\frac{\mathrm{D} u^\alpha}{\mathrm{d} \lambda^*} = \kappa u^\alpha = \frac{\mathrm{D} t^\alpha}{\mathrm{d} \lambda}$. 

Since $u^\alpha$ satisfies the same equation as $t^\alpha$ under the transformation $\lambda^*$, it means that $u^\alpha$ also satisfies the geodesic equation. Therefore, $\frac{\mathrm{D} u^\alpha}{\mathrm{d} \lambda^*} = 0$.
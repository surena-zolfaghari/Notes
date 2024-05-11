I want to decompose metric to transverse part and longitude part. It's straight forward for congruence of time-like geodesics. But I did for congruence of null geodesics. It has some difficulties. Because to isolate the part of the metric that is transverse to $k_{\alpha}$ is not entirely straightforward when $k_{\alpha}$ is null. The expression $h'_{\alpha \beta} = g_{\alpha \beta} + k_{\alpha}k_{\beta}$ does not work, because $h'_{\alpha \beta} k_{\beta} = k_{\alpha} \neq 0$.

To isolate the transverse part of the metric we need to introduce another null vector field $N_{\alpha}$, such that $N^{\alpha}k_{\alpha} \neq 0$. Because the normalization of a null vector is arbitrary, we may always impose $k^{\alpha}N_{\alpha} = -1$.

The vector $N_{\alpha}$ must satisfy the relations $N^{\alpha}N_{\alpha} = 0$ and $k^{\alpha}N_{\alpha} =−1$. Prove that the transformation

$$N^{\alpha} → N'{\alpha} = N^{\alpha} + ck^{\alpha} + c^{A} \hat e^{\alpha}{A}$$
where $c = 1/2 c_A c^A$, is the only one that preserves the defining relations for the auxiliary null vector. (The coefficients cA are arbitrary.)



To prove that the given transformation is the only one that preserves the defining relations for the auxiliary null vector $N_{\alpha}$, let's examine how this transformation affects the conditions $N^\alpha N_\alpha = 0$ and $k^\alpha N_\alpha = -1$.

Under the transformation $N^{\alpha} \rightarrow N'^{\alpha} = N^{\alpha} + ck^{\alpha} + c^{A} \hat{e}^{\alpha}_A$, the conditions for $N_{\alpha}$ become:

1. **Normalization**: 
\[N'^{\alpha} N'_{\alpha} = (N^{\alpha} + ck^{\alpha} + c^{A} \hat{e}^{\alpha}_A)(N_{\alpha} + ck_{\alpha} + c_{A} \hat{e}_{\alpha A})\]

\[= N^{\alpha}N_{\alpha} + cN^{\alpha}k_{\alpha} + cN^{\alpha}\hat{e}_{\alpha A} + cN_{\alpha}k^{\alpha} + c^2 k^{\alpha}k_{\alpha} + c^2 k^{\alpha}\hat{e}_{\alpha A} + cN_{\alpha}\hat{e}^{\alpha}_A + c^2 \hat{e}^{\alpha}_A\hat{e}_{\alpha A}\]

\[= 0 + c(-1) + 0 + c(-1) + c^2(0) + 0 + 0 + c^2(0)\]
\[= -2c + c(-1) = -c(2 - 1) = -c(1) = -c\]

For $N'^{\alpha} N'_{\alpha} = 0$, we require $c = 0$. So, the normalization condition is preserved.

2. **Orthogonality with $k_{\alpha}$**:
\[N'^{\alpha} k'_{\alpha} = (N^{\alpha} + ck^{\alpha} + c^{A} \hat{e}^{\alpha}_A)k_{\alpha} = N^{\alpha}k_{\alpha} + c(k^{\alpha}k_{\alpha}) + c^{A} (\hat{e}^{\alpha}_Ak_{\alpha})\]

\[= -1 + c(0) + c^{A}(0) = -1\]

For $N'^{\alpha} k'_{\alpha} = -1$, any value of $c$ is allowed. 

Now, let's consider the transformation parameterized by $c_A$ coefficients. We need to check if there's any additional freedom:

\[N'^{\alpha} \rightarrow N'^{\alpha} + d k^{\alpha} + d^A \hat{e}^{\alpha}_A\]

We impose the normalization condition:

\[0 = N'^{\alpha} N'_{\alpha} = (N^{\alpha} + ck^{\alpha} + c^{A} \hat{e}^{\alpha}_A + dk^{\alpha} + d^{A} \hat{e}^{\alpha}_A)(N_{\alpha} + ck_{\alpha} + c_{A} \hat{e}_{\alpha A})\]

\[= -c - d\]

So, $d = -c$. This means the additional freedom $d_A$ doesn't contribute to the transformation, as it cancels out in the normalization condition.

Thus, the transformation given is the only one that preserves the defining relations for the auxiliary null vector.



XylyXylyX
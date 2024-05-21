
First of all you need to load the package

```mathematica
<< xAct `xTensor`
```

# Define a manifold, two tensor fields and a metric

Define a manifold

```mathematica
DefManifold[M, 4, {a, b, c, d, e, f}]
```

Define a vector field on manifold
```mathematica
DefTensor[v[a],M]
```
Define a tensor field on manifold

```mathematica
DefTensor[F[-a,-b],M,Antisymmetric[{-a,-b}]]
```
- You can change $Anitsymmetic$, it's just an example.

**Define a metric**
```mathematica
DefMetric [-1,g[-a,-b],CD]
```
- $-1$ is about minus determinant and $CD$ is about torsion is zero.

```mathematica
v[a] delta[-a,b]
```

Covariant Derivative
```mathematica
CD[F[-b, -c] v[c]]
```

Zero terms
```mathematica
% //ToCanonical
```
- % gives past output.
- the following function gives zero terms.
- You can use this function without % at the end of line, If you want to do this in one step.

https://youtu.be/nvLGEbW90lc?t=872
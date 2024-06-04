

# 2024-06-06 21-43 Su Christoffel symbol
Created:2024-06-06 21-43

To calculation:
```mathematica
Christoffel[CD, PD][a, -b, -c]
```

There is a difference between

```Mathematica
ComponentArray@ToBasis[-sph]@Christoffel[cd, PDsph][a, -b, -c]
```
and
```mathematica
ComponentArray@ToBasis[-sph]@Christoffel[CD, PDsph][a, -b, -c]
```
and check this why are the components zero?
```Mathematica
ToValues@ComponentArray@ToBasis[-sph]@Christoffel[CD, PDsph][a, -b, -c]
```

Check these:
>
ChristoffelPDsph
ChristoffelCD
ChristoffelCDPDsph


- [ ] covariant derivative associated to that metric


The definition of the covariant derivative does not use the metric in space. However, for each metric there is a unique torsion-free covariant derivative called the Levi-Civita connection such that the covariant derivative of the metric is zero
## References:
- CTensorEntries.nb
- Christoffel.nb
## Related:






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

## References:
- CTensorEntries.nb
- Christoffel.nb
## Related:




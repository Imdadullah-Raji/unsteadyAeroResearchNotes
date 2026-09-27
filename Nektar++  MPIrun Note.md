
> Do not naively use as many cores as possible. Parallelization has overhead. There has to be communications between the ranks, and communication time scales as $\mathcal{O}(N^{2/3})$ and compute time scales as $\mathcal{O}(N)$, where $N$ is number of cells per rank. So compute beats communications if N is large. 

- **Rule of Thumb**: 20-50k cells per rank  

| Setup   | Linear Solver                                   | Time per 20 steps  |
| ------- | ----------------------------------------------- | ------------------ |
| Serial  | DirectMultilevelStaticCond (serial default)     | 2.07s              |
| 2 ranks | IterativeStaticCond+Diagonal (parallel default) | ~10.5 ( 5x slower) |
| 2 ranks | XxtMultilevelStaticCond                         | 1.45s              |


`limit_cycle.py` should test for a subharmonic at f/2 before reporting the period, and use the fundamental for both the cycle count and the convergence windowing. Otherwise every angle past the period-doubling onset will silently record half the requested cycles and report a spurious CONVERGED=no at the end — including on your friend's machine, across most of the odd angles.

Want me to make that fix and re-run AoA 30's phase 2 for another 10 fundamental cycles to bring it to 20? The restart point at t=120.5 is intact, so extending costs only the extra cycles, not a re-run.
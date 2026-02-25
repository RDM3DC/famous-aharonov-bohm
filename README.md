# Aharonov–Bohm Effect

*Phase-Lifted geometric phase with winding sectors*

**ID:** `famous-aharonov-bohm`  
**Tier:** famous  
**Units:** OK  
**Theory:** PASS-WITH-ASSUMPTIONS  

## Equation

$$
\theta_R[\gamma]=\mathrm{unwrap}\!\Big(\frac{q}{\hbar}\oint_\gamma \mathbf A\cdot d\mathbf\ell;\;\theta_{\rm ref},\pi_a\Big)=\frac{q}{\hbar}\int_S \mathbf B\cdot d\mathbf S + 2\pi_a w
$$

## Description

The Aharonov–Bohm phase expressed through Phase-Lift with explicit winding-number sectors. The unwrap operator removes branch-cut ambiguity and tracks accumulated windings w ∈ ℤ around the solenoid.

## Assumptions

- Gauge region excludes singular crossings during unwrapping.
- Reference phase θ_ref is consistent along γ.
- π_a → π in the classical limit.

## Repository Structure

```
images/       # Visualizations, plots, diagrams
derivations/  # Step-by-step derivations and proofs
simulations/  # Computational models and code
data/         # Numerical data, experimental results
notes/        # Research notes and references
```

## Links

- [TopEquations Leaderboard](https://rdm3dc.github.io/TopEquations/leaderboard.html)
- [TopEquations Main Repo](https://github.com/RDM3DC/TopEquations)
- [Certificates](https://rdm3dc.github.io/TopEquations/certificates.html)

---
*Part of the [TopEquations](https://github.com/RDM3DC/TopEquations) project.*

# Kalman Filter Notes (Python / Jupyter)

My personal study notes from the **Kalman Filtering specialization** by Dr. Gregory L. Plett
(University of Colorado, on Coursera). The course uses Octave; here I rewrote the ideas in
**Python** with small, runnable examples.

The notes use simple language and skip long derivations. The focus is on the intuition,
the key equations, and code you can run and modify.

| # | Notebook | Topics |
|---|----------|--------|
| 1 | [Kalman Filter Boot Camp](01_Kalman_Filter_Boot_Camp.ipynb) | State-space models, discretisation, observability, mean & covariance, noise, Van Loan method, first linear KF |
| 2 | [Linear Kalman Filters](02_Linear_Kalman_Filters.ipynb) | Sequential probabilistic inference, Joseph form, square-root KF, tuning, correlated/coloured noise, outlier gating, RTS smoother, steady-state KF, target tracking, IMM, α–β filter |
| 3 | [Nonlinear Kalman Filters](03_Nonlinear_Kalman_Filters.ipynb) | EKF, sigma-point KF (UKF/CDKF), iterated EKF, cubature KF, adaptive EKF, parameter & joint state/parameter estimation |
| 4 | [Particle Filters](04_Particle_Filters.ipynb) | Bayesian recursion, grid filter, Monte-Carlo & importance sampling, SIS/SIR particle filter, resampling, indoor navigation with RSSI beacons |

## Run locally

```bash
pip install -r requirements.txt
jupyter notebook
```

All examples use simulated data, so no datasets are needed. Random seeds are fixed, so results are reproducible.

## Note

These are my own notes and code, written while studying. They are not official course material.
For the full theory and derivations, please take the original course.
The recommended textbook is *Dan Simon, Optimal State Estimation (Wiley, 2006)*.

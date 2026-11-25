# Finite Elements, SVD/POD and PGD — Model Order Reduction Labs

Report of three computational mechanics labs on the unsteady heat equation, moving from a full finite element solver to reduced-order models that cut computation and storage costs.

M2 MSCHP, Université Paris-Saclay. Pair work by **Ahmed Taleb Bechir** and **Abdelghani Ameziane**, supervised by Victor Matray. Report: [`TPRDM_rendu.pdf`](TPRDM_rendu.pdf).

## Contents

| Lab | Topic | Key points |
|---|---|---|
| 1 | **Finite Element Method** for the unsteady heat equation | Weak formulation, assembly of mass and stiffness matrices and load vector from mesh connectivity, backward Euler time integration |
| 2 | **Data decomposition and compression** with SVD (POD) and PGD | Low-rank approximation of solution snapshots, truncation rank versus reconstruction error, storage gain |
| 3 | **Proper Generalized Decomposition** applied to the heat equation | Separated space-time representation solved mode by mode, compared with the full FEM reference |

Implemented in MATLAB.

## Why it matters

Reduced-order models (POD, PGD) replace a large discretised system with a handful of modes. They make parametric studies, real-time simulation and repeated solves affordable, with an error that can be controlled by the number of modes kept.

## Authors

**Ahmed Taleb Bechir** — [atbechir.com](https://atbechir.com) · [LinkedIn](https://www.linkedin.com/in/ahmed-taleb-bechir-97a7301a4)
**Abdelghani Ameziane**

# PINN-PDE-solver

This repo builds a physics-informed neural network (PINN) solver from scratch in PyTorch, starting from ODEs and working up to the heat, wave, and Burgers' equations. Each solver is validated against a known solution using relative L² error.

## Metric

Relative L² error, with target ε < 1%:

ε = ‖u_pred − u_exact‖₂ / ‖u_exact‖₂

## Progress

- [ ] Week 1: Autograd and fitting sin(x) with a small network
- [ ] Week 2: ODE u′ = −u, u(0) = 1
- [ ] Week 3: 1D heat equation
- [ ] Week 4: Hardening (collocation-point study, README, figures)
- [ ] Week 5: Wave equation
- [ ] Week 6: Burgers' equation
- [ ] Week 7: General solver (PDE passed in as a function)
- [ ] Week 8: PINN vs finite difference, final write-up

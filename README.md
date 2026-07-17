# pinn-cylinder-flow
Physics-Informed Neural Network (PINN) to simulate 2D incompressible Navier-Stokes flow around a circular cylinder, predicting velocity ($u, v$) and pressure ($p$) fields by minimizing the residual of the underlying partial differential equations.

Dataset: https://modelflows.github.io/modelflowsapp/databases/#cylinder-2d
gt

TODO 

- Correct residual equations for the physics loss.
- Use collocation points only for the physics loss.
- Incorporate boundary conditions.
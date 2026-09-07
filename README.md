# pinn-cylinder-flow
Physics-Informed Neural Network (PINN) to simulate 2D incompressible Navier-Stokes flow around a circular cylinder, predicting velocity ($u, v$) and pressure ($p$) fields by minimizing the residual of the underlying partial differential equations.

Dataset: https://zenodo.org/records/5039610

TODO 

- Correct residual equations for the physics loss.
- Use collocation points only for the physics loss.
- Incorporate boundary conditions.


# Reproducibility

To reproduce the results described in the report, follow the steps outlined in this section. Firstly, download the data from this link: https://zenodo.org/records/5039610. The simulation data is stored in the file "fixed_cylinder_atRe100". Download this file into the directory of this repository before running the code blocks in `convert.ipynb` to convert the data into the HDF5 `.h5` format.       